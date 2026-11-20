# Orca — source-native S3 C-construction technical contract

**Canonical storage:** opensiro-contributions/orca@opensiro/meta:.opensiro/issues/orca-merge-required-s3-control-20261118/constructor-sufficiency.md.
**Level 1 / Human decision Issue:** [issue.md](issue.md).
**Canonical decision receipt:** [roadmap.md](roadmap.md), authoritative for Index vector, case pins, priority and verdict.
**Stage:** PLAN_ONLY / HYPOTHESIS, current v0.18.2 template synchronization; **DRAFT — NOT PUBLISHED**. Native validation NOT_RUN.

## 1. Function-specific construction boundary and methodology checks

**Source and mode boundary:** Original stablyai/orca at current original HEAD fd74d16b4793fb19f985aa0486f386609826e7cf, first-party entrypoints [docs/site/content/docs/cli/orchestration.mdx](https://github.com/stablyai/orca/blob/fd74d16b4793fb19f985aa0486f386609826e7cf/docs/site/content/docs/cli/orchestration.mdx) and [src/cli/orchestration/tasks/task-handlers.ts](https://github.com/stablyai/orca/blob/fd74d16b4793fb19f985aa0486f386609826e7cf/src/cli/orchestration/tasks/task-handlers.ts). The canonical historical research HEAD remains 2eb3748d5aec4ff0b44718741721b12e9b40a079; accepted historical Index https://github.com/opensiro/vsm-harness-index/blob/9fe281441f1820014dda5da8fff70e5fb1c9b246/assessments/or/orca-stablyai.md reviewed at c33a446190bdfa21286a373e097c50a2b3e0a4d4. The supported local first-party runtime and its explicit optional modes are the unit of analysis. Original project's own CI, third-party provider, external management and parent owner are not silently counted as agent functions.

**Target transition:** S3=— -> S3=C

**Six-function dependencies (S1/S2/S3/S3*/S4/S5):** S1 and S2 already have supported roles. S3 specifically concerns outstanding whole-Run post-worker obligations, not raw worker scheduling; S3* must not be inferred from human PR diff review. S5 merge policy stays human. Reuse historical S1=A · S2=C · S3=— · S3*=— · S4=— · S5=— without changing the Index. Supporting runtime permissions and transport are not themselves autonomous decisions.

**Function witness:** A worker sends worker_done but the original Run still owes review, requested changes or merge of the exact PR head; the no-longer-active task may lose a rightful current owner. The legitimate independent choice and owner: an optional developer-installed whole-Run manager decides whether outstanding merge-required work should be held, reassigned, or settled based on the authoritative exact PR head. Hold review work, reassign an eligible worker, or settle only on verified exact-head merge/adoption, subject to human merge authorization. The effect and feedback must be Run/Task status and next-worker dispatch follow the lawful manager choice; later PR check/review/merge state returns to that manager..

**Counterfactual owner test:** Remove the optional developer-composed S3 decision actor but keep current source machinery: Shipped Orca Run/Task/Dispatch, coordinator wakeups, worker_done and decision gates already provide current task regulation. Worker completion alone does not prove a merge-required PR was reviewed, merged and adopted. Original issue #21984 remains OPEN. The specific extra choice would then be missing: The first-pass source evidence rules OUT a generic duplicate coordinator; it does not establish that shipped current coordinator code closes the narrower merge-required exact-head objective. Prior GO is retained only for that narrower proposal, with native equivalence untested.. A mere generic hook or another model call does not count.

**Possible methodological negative control:** If baseline first-party code already closes the exact owner/choice/effect/return at the supported boundary, or only a human parent may choose, report native equivalence and withdraw the new C design rather than regrade.

**Contributor / maintainer priorities:** NOT_STATED as approval of this exact VSM construction; third-party product direction remains the maintainer's.

## 2. Source-pinned baseline and parallel native Track A / on-top Track B

**Original native workflow:** Shipped Orca Run/Task/Dispatch, coordinator wakeups, worker_done and decision gates already provide current task regulation. Worker completion alone does not prove a merge-required PR was reviewed, merged and adopted. Original issue #21984 remains OPEN. First-party pinned source: [docs/site/content/docs/cli/orchestration.mdx](https://github.com/stablyai/orca/blob/fd74d16b4793fb19f985aa0486f386609826e7cf/docs/site/content/docs/cli/orchestration.mdx) and [src/cli/orchestration/tasks/task-handlers.ts](https://github.com/stablyai/orca/blob/fd74d16b4793fb19f985aa0486f386609826e7cf/src/cli/orchestration/tasks/task-handlers.ts).

**Closest existing solution:** Test ordinary native Orca coordinator and #21984-style review tracking on the same Run before building any new S3 manager; no duplicate framework or unauthorized merge.

**Relevant original Issues/PRs:** https://github.com/stablyai/orca/issues/21984 (OPEN, review-to-merge objective); native Run and worker CLI are SHIPPED. Broad search found contemporary orchestration PRs but not proof the scoped obligation has shipped.. Labels such as OPEN or CLOSED are current at this follow-up only where checked; unverified heads are not treated as merged.

| Required C link or operator outcome | Track A: shipped/current source | Track B: minimum integration | Falsifier |
| --- | --- | --- | --- |
| Bounded whole-function decision | Shipped Orca Run/Task/Dispatch, coordinator wakeups, worker_done and decision gates already provide current task regulation. Worker completion alone does not prove a merge-required PR was reviewed, merged and adopted. Original issue #21984 remains OPEN. | Hold review work, reassign an eligible worker, or settle only on verified exact-head merge/adoption, subject to human merge authorization. | The first-pass source evidence rules OUT a generic duplicate coordinator; it does not establish that shipped current coordinator code closes the narrower merge-required exact-head objective. Prior GO is retained only for that narrower proposal, with native equivalence untested. |
| Lawful downstream effect | Source entrypoints at docs/site/content/docs/cli/orchestration.mdx and src/cli/orchestration/tasks/task-handlers.ts | Run/Task status and next-worker dispatch follow the lawful manager choice; later PR check/review/merge state returns to that manager. | Stale PR head, requested changes, lack of merge authority, coordinator loss or replay cannot yield false settlement; ordinary non-merge-required Run behavior stays unchanged. |

**On-top distinctness:** The first-pass source evidence rules OUT a generic duplicate coordinator; it does not establish that shipped current coordinator code closes the narrower merge-required exact-head objective. Prior GO is retained only for that narrower proposal, with native equivalence untested. First prefer the exact native solution; a copied supervisor abstraction is insufficient.

**Source ambiguity / rights blockers:** Future source HEAD/PR changes, reviewer identity, permission of the original owner, and tests are unverified. A matched fork research write does not authorize external original actions or code changes. No evidence-free demand assumption.

## 3. Minimal complete S3 first-party C construction

**Required property:** A first-party S3-specific path to install a legitimate autonomous decision owner, enforce its selected lawful alternative, and return later operational evidence.

| Necessary native component or port | Existing first-party source | Smallest proposed change / integration | Legitimate owner, effect, return |
| --- | --- | --- | --- |
| Decision evidence and invocation | [docs/site/content/docs/cli/orchestration.mdx](https://github.com/stablyai/orca/blob/fd74d16b4793fb19f985aa0486f386609826e7cf/docs/site/content/docs/cli/orchestration.mdx) | Reuse native Run and Task transitions. Bind an exact current PR head and outstanding review obligation with a bounded decision authority; let a composed Run manager choose hold/reassign/settle, then require native gated effect and later provider/current-head feedback. | an optional developer-installed whole-Run manager decides whether outstanding merge-required work should be held, reassigned, or settled based on the authoritative exact PR head |
| Bound decision and later feedback | [src/cli/orchestration/tasks/task-handlers.ts](https://github.com/stablyai/orca/blob/fd74d16b4793fb19f985aa0486f386609826e7cf/src/cli/orchestration/tasks/task-handlers.ts) | Run/Task status and next-worker dispatch follow the lawful manager choice; later PR check/review/merge state returns to that manager. | Hold review work, reassign an eligible worker, or settle only on verified exact-head merge/adoption, subject to human merge authorization. |

**Architectural C-sufficiency argument:** Native baseline: Shipped Orca Run/Task/Dispatch, coordinator wakeups, worker_done and decision gates already provide current task regulation. Worker completion alone does not prove a merge-required PR was reviewed, merged and adopted. Original issue #21984 remains OPEN. The key residual is The first-pass source evidence rules OUT a generic duplicate coordinator; it does not establish that shipped current coordinator code closes the narrower merge-required exact-head objective. Prior GO is retained only for that narrower proposal, with native equivalence untested. The strongest scoped optional solution is Reuse native Run and Task transitions. Bind an exact current PR head and outstanding review obligation with a bounded decision authority; let a composed Run manager choose hold/reassign/settle, then require native gated effect and later provider/current-head feedback. Alternative one: use native/manual Test ordinary native Orca coordinator and #21984-style review tracking on the same Run before building any new S3 manager; no duplicate framework or unauthorized merge. Alternative two: avoid building if protected authority or actual feedback cannot be established. This proposal claims constructibility, not new implemented grade.

**Explicit non-goals:** No unrelated function upgrades, blanket task guardian, unrequested S5 authority, generic provider dependency, automatic external PR, or forced adoption.

**Implementation dependency graph:** Verify pinned current source and accepted assessment -> resolve P1 native rights/overlap/feedback proof -> implement minimal P0 only with separately authorized product work -> run native positive/negative closure tests -> reconsider adoption based on measured benefit.

## 4. Priorities, optional alternative and stopping rules

**P0 and P1:** P0 is First-party opt-in S3 Run-commitment snapshot, feasible hold/reassign/settle options, developer-installed autonomous S3 manager decision, Run/Task/Dispatch and protected-gate enforced intervention, and actual later provider/current-head + next-worker feedback to the same manager P1 is P1-A provider-generic durable review/merge obligation at exact PR head, named next owner/recheck and worker_done-not-merged; P1-B Run-scoped bounded manager authority, versioned/replay-safe decisions, restart-persistent current commitments, native coordinator/Task/Run/gate integration; source overlap with original #21984 and open PRs before implementation. Priorities are inherited, not newly changed.

**P2:** NONE — no other function or parent policy upgrade bundled. No forced second VSM function.

**Alternative path:** Test ordinary native Orca coordinator and #21984-style review tracking on the same Run before building any new S3 manager; no duplicate framework or unauthorized merge.. Prefer this if it closes the same operator outcome with no independent C need.

**Stop:** Complete native equivalence, impossible independent actor right, no enforced return, policy veto or missing indispensable evidence triggers NO_GO/BLOCKED under the parent protocol. A missing measured saving is not by itself NO_GO.

## 5. Future source-native acceptance — derive tests, do not copy a matrix

**Native test commands and entry points:** First-party src/cli/orchestration/orchestration.test.ts and src/cli/orchestration/tasks/task-handlers.ts are actual original entrypoints; native tests NOT_RUN.

**Positive functional closure:** A worker_done for a still-unmerged PR cannot settle a merge-required Run; a later verified merged exact head permits final settlement, with bounded independent hold/reassign choices.

**Independent alternative (where applicable):** Hold review work, reassign an eligible worker, or settle only on verified exact-head merge/adoption, subject to human merge authorization. A genuine owner should be able to make two lawful different choices under different bounded contexts, not simply follow an always-grant rule.

**Negative authority and compatibility (where applicable):** Stale PR head, requested changes, lack of merge authority, coordinator loss or replay cannot yield false settlement; ordinary non-merge-required Run behavior stays unchanged.

**Matched native alternative:** Test ordinary native Orca coordinator and #21984-style review tracking on the same Run before building any new S3 manager; no duplicate framework or unauthorized merge. Execute the same task once with current native behavior and once with conditional construction. No results or economics have yet been collected.

## 6. Proposal verdict, falsification, evidence ownership and handoff

**Proposal-stage decision:** GO

**Research disposition:** NEEDS_EVIDENCE

**Primary falsifier:** If the actual native Orca coordinator/Task/Run already provides equivalent lawful independent actor choice with durable versioned obligations and true next-operation return, or the new actor cannot control a later effect and receive feedback, separate S3=C constructor is not qualified

**Validation state:** NOT_RUN; proposal only, no native tests.

**Ownership of truth:** Profile owns semantics; Skills owns assessment method; Index owns historical accepted classification; original stablyai/orca owns product change and maintainer choice; the [roadmap.md](roadmap.md) case receipt owns these decisions.

**Cost status:** NOT_MEASURED.

**Next permitted action:** Source-verify the narrow A/B comparison at current original HEAD and test scope under new explicit permission, or keep this as an unpublished research case.

**Human backlink:** [issue.md](issue.md); **case receipt:** [roadmap.md](roadmap.md).

**AI disclosure:** Drafted with AI; no native execution, maintainer consent, economic proof or independently verified value claimed.
