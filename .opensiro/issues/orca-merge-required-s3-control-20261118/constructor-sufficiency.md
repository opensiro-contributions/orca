# Orca — independent S3 source-native constructor and acceptance (AI)

**PLAN_ONLY · proposal-stage GO · research NEEDS_EVIDENCE · NOT IMPLEMENTED / NOT PUBLISHED**

**Target transition:** S3=— -> S3=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

[issue.md](issue.md) · [roadmap.md](roadmap.md)

## 1. Boundary, ownership and counterfactual

At source HEAD 2eb3748d5aec4ff0b44718741721b12e9b40a079, system in focus is one standard local Orca orchestration Run with Task/Dispatch/worker records, permissible CLI controls and provider-generic PR status/revision observations. Accepted historic S1 A, S2 C, S3/S3*/S4/S5 unestablished are explained in Human's six-row table. This plan proposes **not a shipped S3**, but an opt-in first-party C interface where a developer supplies a truly autonomous current-Run decision actor.

**Owner and closure:** operator declares merge-required objective, rights and capacity; external provider reports head/check/review/merge states, but cannot exercise Orca Run authority; S3 manager sees actual current commitments and chooses hold/reassign/settle among lawful options; native Run/Task/Dispatch/gates enforce next work, and observed later Task/provider receipt changes the actor's next decision. Without composed manager, existing manual/direct native lifecycle remains valid and cannot be credited as an autonomous S3 decision.

## 2. Track A exact original-native work

- [Orca README@independent HEAD](https://github.com/stablyai/orca/blob/2eb3748d5aec4ff0b44718741721b12e9b40a079/README.md) describes agent worktrees, parallel coding and human review.
- [Original #21984](https://github.com/stablyai/orca/issues/21984) OPEN says PR opened or worker_done is not a merge-required task completion. Provider-agnostic state needs exact head checks, next owner and recheck trigger. It is the cheapest native P1-A candidate.
- [Original #11229](https://github.com/stablyai/orca/issues/11229) OPEN proposes deterministic workflow builders over manual shell/LLM flow.
- Original open PRs, **not shipped** at reviewed HEAD: [#16852](https://github.com/stablyai/orca/pull/16852) Run target capacity but no auto backfill; [#10211](https://github.com/stablyai/orca/pull/10211) gate notifications; [#37030](https://github.com/stablyai/orca/pull/37030) FIFO locks/board (S2), [#42284](https://github.com/stablyai/orca/pull/42284) creator/assignee identity, [#40378](https://github.com/stablyai/orca/pull/40378) first-winner gate update.
- Current original main was subsequently observed 14 commits ahead at ab1a03311399d05708156a89214272a469199173. The related agent hook and bot item changes are **NOT evaluated as a new complete S3 assessment**; do a current source/PR overlap pass before any implementation.
- Prior original-native comparator, explicitly required by the continuation: shipped coordinator, CLI/Run ownership, Task transitions and protected human decision gates. Compare those under the same merge-required task before adding any new autonomous actor.

## 3. Track B minimum complete logical C chain

| Mandatory logical port | Current source-native substrate / on-top delta | Legitimate actor and returned effect |
| --- | --- | --- |
| S3CommitmentSnapshot | Read Run, Task, Dispatch, required outcome, provider PR head, stale check status and next action; P1-A augments durable provider-generic commitment record | Current state does NOT become decision owner merely by existing |
| S3CurrentOptions | Compute eligible hold, reassign eligible worker, settle only after exact current-head merge, versioned under Run cap/gates | Parent defines limits; no provider or controller may mint merge rights |
| S3DecisionConstructor | Supported opt-in first-party registration/invocation for developer-composed autonomous S3 Run manager | Actor must choose among at least two lawful alternatives; no actor implies safe default/manual path, never an invented S3=A |
| S3AuthorizedIntervention | Atomic Run/principal/epoch, capacity and human gate check on Task/Dispatch transitions, commit/release; replay-safe and restart-persistent | Approved choice changes the **later real work** under same Run, not an explanatory log |
| S3ReturnReceipt | Correlate decision and actual Task result, verified current PR head and merge/review outcome, denied and unknown cases, then feed updated Run obligations back to same S3 actor | A stale URL or worker_done cannot falsify completion; receipt must show actual later effect |

A generic hook/scheduler, YAML workflow, single FIFO or bot worker is NOT sufficient by itself. The proposed first-party interface is function-specific and relies on an independently composed decision owner rather than a new embedded control plane. If chosen options do not affect Run work or do not reach later feedback, the construction fails C sufficiency.

## 4. Priorities from two Orca chats

**P0 S3=— -> S3=C, GO as a design hypothesis.** **P1-A**, durable review obligation: exact PR head at observation, owner, trigger, expiry/next check, recheck on head change, no early settlement on worker_done. **P1-B**, lawfully registered Run-scoped actor: owner authority, capacity, protected approvals, fencing/replay, restart persistence and next Task/action feedback. **P2 NONE.**

**Important conditionality:** P1-A is independently useful original-native bug/feature work from Issue #21984 and can be implemented without S3. P1-B should proceed ONLY if source-native coordinator benchmark proves a distinct new decision/effect/return gap. These are dependencies, not two arbitrary new VSM functions or an implementation mandate.

## 5. Native proposed acceptance (NOT EXECUTED)

| Case | Setup / legal S3 choice | Required observed next effect, or stop |
| --- | --- | --- |
| ORCA-S3-01 | Two workers, PR opened, worker_done but review pending at head A; choose hold | Run merge-required obligation still active; no mistaken settled state; same-head receipt |
| ORCA-S3-02 | Changes requested at exact head A; choose reassign to eligible fixer | Exactly one next Task/Dispatch within capacity; actor receives downstream result |
| ORCA-S3-03 | Verified provider merged exact head B; choose settle | Run released only after observed outcome B and allowed gate; changed head invalidates earlier check |
| ORCA-S3-04 | Same state, independently installed actor chooses another legal hold versus reassign | Different real admitted/held subsequent worker action under same hard rights; proves discretionary actor |
| ORCA-S3-05 | Stale epoch, wrong Run/principal, human approval required, unknown provider, exhausted slots | Fail closed before mutation/duplicate dispatch, produce denial/unknown receipt |
| ORCA-S3-06 | Run restart and repeated decision ID | Durable current commitment, idempotent decision and no fake merged status; no unverified remote mode claim |

**Implementation compatibility:** test native first-party Run/Task/CLI mode and current PR head, compare with minimal coordinator+Issue #21984 path, verify licencing, contribution requirements and actual suite commands at implementation HEAD. Tests, CI, benchmarks and future cost observations are **NOT_RUN / NOT_MEASURED**. Human merge approval is reserved even if a model recommends settle.

## 6. Falsifiers, historic comparison and gates

**Primary falsifier:** shipped native coordinator already provides equivalent autonomous whole-Run discretion plus lawful next-operation effect/feedback, or the full user's merge-required outcome is handled by minimal original-native #21984 at lower/equal cost. **Secondary:** first-party model actor cannot receive allowed authority, replay-safe later effect, or truthful current-head feedback. Then NO_GO to extra C, though original issue remains valid.

[Earlier Orca case](https://github.com/opensiro-contributions/orca/blob/7313d9072a67d4071694338bef6765909ec40531/.opensiro/issues/orca-merge-required-s3-control-20261118/roadmap.md) dated 2026-11-18 had conditional GO at original 270fc64d. The *independent fresh* 2026-11-19 rerun pinned 2eb3748d5aec4ff0b44718741721b12e9b40a079 and continued by separating P1-A and P1-B. It was READ_ONLY because previous fork PAUSE; the owner later changed it to ACTIVE/ALLOW. This metadata update faithfully transcribes those chat conclusions; **does not create a new independent 14-commit-later judgement**.

No product code, real provider mutation, public Issue, original maintainer contact, Index grade, native test PASS or CLA consent is asserted. Fork meta persistence requires validator and exact GitHub readback.
