A small source-level observation that may help narrow the implementation of this issue: Orca already distinguishes a worker's task from a bot-owned commitment.

In [Task settlement](https://github.com/stablyai/orca/blob/4e43dffdaca90950629735e77ccacb21f2513a1e/src/main/runtime/orchestration/db/dispatch-context/attempt-task-settlement.ts#L16-L49), a successful attempt completes the Task and promotes its dependents. Meanwhile, [Bot Items](https://github.com/stablyai/orca/blob/4e43dffdaca90950629735e77ccacb21f2513a1e/src/main/bots/bot-preamble.ts#L50-L57) have a separate "done means" contract and linked workers. The [Item close operation](https://github.com/stablyai/orca/blob/4e43dffdaca90950629735e77ccacb21f2513a1e/src/main/bots/bot-items-writes.ts#L59-L83) records an owner-authorized status transition, but does not itself verify a merge condition.

Could these two levels be used instead of making every worker task wait for a PR to merge?

- Keep an implementation Task complete when its scoped work is done.
- Keep a merge-required Item open, with its existing owner and PR watch. If a downstream Task actually requires the merge, have it depend on a separate verification Task rather than on implementation completion alone.
- Test this with two branches of the same Run: an independent task can proceed, while a deployment task stays blocked until its required merge is verified. A closed-but-unmerged PR must not satisfy that predicate.

This would complement #47050 and #47518, which address agent instructions and delivery routing, while keeping the existing coordinator responsible for the next action.

Our VSM-based source review found that Orca already has agent-owned current-work management; the question here is how to preserve the required outcome across its existing Task and Item boundaries, not how to add another coordinator. This is a design question based on static source inspection, not an implemented or tested fix.

*Context: OpenSiro architecture review; AI-assisted comment.*
