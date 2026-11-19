# Orca — independent S3 Run commitment roadmap (Human)

**PLAN_ONLY · GO proposal-stage · research NEEDS_EVIDENCE · internal metadata only; NOT PUBLISHED**

**Target transition:** S3=— -> S3=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

[roadmap.md](roadmap.md) · [constructor-sufficiency.md](constructor-sufficiency.md)

## 1. Why OpenSiro and baseline

OpenSiro studies the unmeasured hypothesis that VSM-informed first-party constructor ports can make multi-agent harness work safer, cheaper to implement and easier to maintain. A GO means only that a specific design is testable; it is not an accepted Index grade or a mandate to the Orca maintainers.

[Accepted included Index](https://github.com/opensiro/vsm-harness-index/blob/9fe281441f1820014dda5da8fff70e5fb1c9b246/assessments/or/orca-stablyai.md), blob 982a55242d439c8f685e6a02c78d7cc3988119d1, original review ref c33a446190bdfa21286a373e097c50a2b3e0a4d4 on 2026-09-17, Profile 0.2.2 / Methodology 0.3.1. New original independent analysis HEAD [2eb3748d5aec4ff0b44718741721b12e9b40a079](https://github.com/stablyai/orca/commit/2eb3748d5aec4ff0b44718741721b12e9b40a079), 2026-11-19. **This is the historical accepted six-function vector, not a new assessment of that HEAD.**

| Function and plain-language role | Historic accepted | Source-native choice and exclusion |
| --- | --- | --- |
| **S1 · Operations** | A | Autonomous coding agents execute user tasks; leave standard first-party hosting intact |
| **S2 · Coordination** | C | Worktree isolation limits simultaneous file conflicts; open FIFO resource-lock PR is not shipped |
| **S3 · Current management** | — | Whole-Run live commitments need lawful choice, enforcement and feedback; **P0** for developer-composed manager |
| **S3* · Independent audit** | — | Human diff/CI evidence alone is not independent corrective metasystem |
| **S4 · Prospective adaptation** | — | Future provider changes are not a complete outside-looking adaptation owner/return |
| **S5 · Identity and policy** | — | Human authorizes objective and PR merge; manager may never acquire ultimate purpose/policy |

## 2. Operator problem and why it matters

Original [Issue #21984](https://github.com/stablyai/orca/issues/21984) describes a coding worker returning worker_done or opening a PR even when the real user requirement is **merged**. Review checks may fail, the PR head may change, another author must act, or the provider status may be unknown; none of those implies completed commitment. The source-native first step is to preserve required outcome and exact-head review/merge obligation with a named next owner. The additional optional S3 hypothesis is discretionary **Run-wide** choice among authorized hold, reassign and settle decisions with real later feedback.

## 3. Original-native Track A and on-top Track B

| Existing original capabilities / PR overlap (Track A) | Remaining S3 C construction (Track B) | How to falsify |
| --- | --- | --- |
| CLI/Run, Task and worker lifecycle; [#21984](https://github.com/stablyai/orca/issues/21984) OPEN exact-head merge obligation; [#11229](https://github.com/stablyai/orca/issues/11229) OPEN deterministic workflows | P1-A durable current Run obligation, exact PR head and next owner (original-native prerequisite) | Existing coordinator and P1-A alone may entirely solve this operator problem |
| OPEN PR [#16852](https://github.com/stablyai/orca/pull/16852) capacity, [#10211](https://github.com/stablyai/orca/pull/10211) pending gates, [#37030](https://github.com/stablyai/orca/pull/37030) FIFO locks, [#42284](https://github.com/stablyai/orca/pull/42284) worker identity and [#40378](https://github.com/stablyai/orca/pull/40378) first gate answer | P1-B developer-composed autonomous Run S3 manager with safe hold/reassign/settle options, versioned authority, applied later Task/Dispatch effect and feedback | Core scheduling/transport alone makes same choices or a stale decision can act |
| Existing human review and provider CI statuses are external facts | True later merge at exact current head, decision-correlated receipt to S3 | worker_done, PR opened, green check or old-head merge counted as final |

## 4. P0 / P1 / P2

**P0:** S3=— -> S3=C, first-party opt-in Run current-commitment snapshot → eligible options → developer-supplied autonomous chooser → Run/Task/Dispatch hard enforcement → later result and next decision feedback.

**P1-A:** first implement/verify Issue #21984's smaller native, provider-generic durable review/merge objective, exact checked PR head, next owner and recheck route; worker_done cannot settle merge-required goal.

**P1-B:** determine whether native coordinator is already sufficient. Only after proving a missing discretionary current management path should a bounded S3 actor get Run-scoped rights, replay-safe epoch control, restart persistence, gate/capacity validation and true later feedback.

**P2:** NONE. Not a global workflow builder, independent S3* or parent S5 mode.

## 5. Acceptance and falsifier (NOT_RUN)

Positive: the same two-worker Run with merge-required task has two different **lawful** S3 manager choices (hold while review is pending; reassign to eligible fixer after changes requested), producing different subsequent Task state/actions. Settle is authorized only on verified exact-head merge and returned feedback. Negative: stale checked head, missing manager, wrong Run, revoked permission, double replay, human gate denial, capacity exhausted or provider outage must fail safely with truthful unknown/denial.

**Stop P0:** if an existing Orca coordinator with minimal Issue #21984 lifecycle yields the same durable correct owner→next authorized action→feedback at lower/equal cost, an extra controller fails. Benchmarks and native tests NOT_RUN; provider charges/review latency savings NOT_MEASURED.

## 6. Current source and publication boundary

The independent re-run source was [2eb3748d5aec4ff0b44718741721b12e9b40a079](https://github.com/stablyai/orca/commit/2eb3748d5aec4ff0b44718741721b12e9b40a079) on 2026-11-19. At sync original main advanced 14 commits to [ab1a03311399d05708156a89214272a469199173](https://github.com/stablyai/orca/commit/ab1a03311399d05708156a89214272a469199173); the present metadata does not assert a full new-HEAD review. Previous [2026-11-18 case](https://github.com/opensiro-contributions/orca/blob/7313d9072a67d4071694338bef6765909ec40531/.opensiro/issues/orca-merge-required-s3-control-20261118/roadmap.md) used a different source and also described S3, but without the independent run's P1-A/B constraint. Old PAUSE/DORMANT stopped fork writes; current owner ACTIVATED/ALLOW enables this internal metadata-only sync.

No product changes, no public fork GitHub Issue, no original maintainer Issue/PR/comment, no Index assessment update. [AI contract](constructor-sufficiency.md) and [receipt](roadmap.md) own source links, rights and future acceptance.
