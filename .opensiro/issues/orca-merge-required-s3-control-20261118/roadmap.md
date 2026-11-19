# Orca — independent S3 current Run-commitment re-run synchronized (2026-11-19)

**Plan-only second source-first independent review transcribed after authority activation.** New bounded verdict: GO / NEEDS_EVIDENCE; original was read-only at decision time because of then PAUSE. The 2026-11-18 case remains in Git history and is compared without conflating it with this new original-pinned review.

## Identity and pins

- Original repository: stablyai/orca
- Original HEAD: 2eb3748d5aec4ff0b44718741721b12e9b40a079
- Observed at: 2026-11-19
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/9fe281441f1820014dda5da8fff70e5fb1c9b246/assessments/or/orca-stablyai.md
- Accepted assessment blob SHA: 982a55242d439c8f685e6a02c78d7cc3988119d1
- Accepted review ref: c33a446190bdfa21286a373e097c50a2b3e0a4d4
- Accepted reviewed at: 2026-09-17
- System in focus: Supported first-party local Orca orchestration Run/Task/Dispatch/worker lifecycle with provider-generic current-head PR/review commitments and developer-composed current-work manager, excluding external CI, provider maintainer rights and unverified remote/paired mode
- Receipt contract: proposal-gate
- Repository-wide source map: Independent source-first six-function review at pinned main plus CLI/Run/task/control/agent-worker docs and existing open original issues/PR heads; continuation refined exact P1-A/P1-B and native-coordinator comparator. Historical case documents supply only prior comparison, not the new source verdict. Native code/tests NOT_RUN; no claim of exhaustive current-main per-file audit
- Priority rationale: S3 current Run obligations have an operator-visible split between worker_done and explicitly merge-required final outcome; first-party Run/Task/gate/owner primitives are available but a separate bounded autonomously developer-composable whole-Run discretionary actor with enforced action/return is not established
- Accepted VSM vector: S1=A · S2=C · S3=— · S3*=— · S4=— · S5=—
- S1 disposition: ALREADY_A — coding agents autonomously produce and revise work inside supported Orca sessions
- S2 disposition: ALREADY_C — isolated worktrees attenuate multi-worker edit collisions; OPEN #37030 FIFO locks are S2-adjacent, not a shipped S3 actor
- S3 disposition: P0 — current Run-level commitments, priority and next-eligible-owner choices across workers are not an accepted first-party C, proposed source-native actor/authority/effect/feedback path below
- S3* disposition: DEFER — human review/worker identity and PR CI status are not independent first-party corrective audit with later S3 return
- S4 disposition: DEFER — model/CI/provider revisions are inputs to current work, not a source-demonstrated outside-looking prospective adaptation controller
- S5 disposition: PARENT_RESERVED — human requires merge objective and protected authorization; no autonomous ultimate policy manager or merge authority transferred
- Target transition: S3=— -> S3=C
- P1 dependencies: P1-A provider-generic durable review/merge obligation at exact PR head, named next owner/recheck and worker_done-not-merged; P1-B Run-scoped bounded manager authority, versioned/replay-safe decisions, restart-persistent current commitments, native coordinator/Task/Run/gate integration; source overlap with original #21984 and open PRs before implementation
- P2 optional: NONE — no other function or parent policy upgrade bundled
- Proposed C construction: First-party opt-in S3 Run-commitment snapshot, feasible hold/reassign/settle options, developer-installed autonomous S3 manager decision, Run/Task/Dispatch and protected-gate enforced intervention, and actual later provider/current-head + next-worker feedback to the same manager
- C sufficiency falsifier: If the actual native Orca coordinator/Task/Run already provides equivalent lawful independent actor choice with durable versioned obligations and true next-operation return, or the new actor cannot control a later effect and receive feedback, separate S3=C constructor is not qualified
- Scenario basis: HYPOTHETICAL
- Proposal-stage decision: GO
- Research disposition: NEEDS_EVIDENCE
- Proposed validation: Compare original #21984 lifecycle-only native coordinator with proposed S3 actor on merge-required workflow; test worker_done vs merged, stale head, requested changes, two distinct lawful manager choices, Run owner/capacity/gate/replay failures, restart persistence and exact next Task/Run and provider result readback
- Validation state: NOT_RUN
- Proposal falsifier: Minimal existing Orca native coordinator plus #21984 board/Run lifecycle achieves the same durable owner→authorized action→verified merge/current-head outcome and later feedback with equal/lower costs, or relevant first-party S3 actor rights/return cannot lawfully be composed
- Evaluation object: Optional developer-composed autonomous S3 whole-Run manager for ongoing merge-required resource and action commitments, not deterministic provider notification, mere PR opened, worker_done terminal or a duplicate workflow builder
- Existing-work overlap: Orca shipped CLI/Run/worker status and worktree isolation; original #21984 OPEN provider-generic review-to-adoption obligation, #11229 OPEN deterministic pipelines; OPEN #16852 Run capacity (no auto-backfill), #10211 decision gates, #37030 FIFO resource locks, #42284 worker identity, #40378 first-winner gate resolution
- Our on-top contribution: Source-native opt-in S3 decision registration and safe current Run authority/effect/return bridge, only after baseline lifecycle P1-A and coordinator P1-B comparison; not a second provider contract or automatic human merge
- Incremental benefit: HYPOTHETICAL discretionary current-Run hold vs reassignment without losing existing review commitments and exact-head closure under owner/capacity limits; no measured benefit over Orca's native coordinator
- Decision scope: GO for complete falsifiable S3=C *proposal* only; technical and native-coordinator evidence remains NEEDS_EVIDENCE, no implementation, current-HEAD Index grade or original-publication authorization

## Rights and authority

- [Original MIT LICENSE](https://github.com/stablyai/orca/blob/2eb3748d5aec4ff0b44718741721b12e9b40a079/LICENSE) and other contributor requirements are reviewed only to documented scope; CLA/DCO/AI disclosure or signature cannot be presumed absent or satisfied.
- Verified matching fork opensiro-contributions/orca. Historical PAUSE/DORMANT prevented write during independent 2026-11-19 rerun and continuation; owner subsequently activated queue on 2026-11-19 and fork now reads ACTIVE/ALLOW with append-only owner event. This permits **internal metadata synchronization** only, not a public fork Issue/PR or original publication.
- Parent human/host defines merge-required objective and admission budget, owns final PR merge, protected gates, Run identity, and authorizations; S3 actor receives only delegated bounded Run-scoped rights, not provider IAM or S5 policy.

## Existing work / overlap

[Original Issue #21984](https://github.com/stablyai/orca/issues/21984) OPEN: a worker can say worker_done or open a PR while the actual required merge/release/adoption is pending; exact head revision, next named owner, trigger/time and successor route are needed. [Issue #11229](https://github.com/stablyai/orca/issues/11229) OPEN: deterministic multi-agent workflow alternatives to brittle scripts/LLM routing. Original [README](https://github.com/stablyai/orca/blob/2eb3748d5aec4ff0b44718741721b12e9b40a079/README.md) documents parallel agents/worktrees and human review/steering. [PR #16852](https://github.com/stablyai/orca/pull/16852) OPEN for Run capacity, explicitly not automatic backfill; [#10211](https://github.com/stablyai/orca/pull/10211) OPEN for pending decision gates; [#37030](https://github.com/stablyai/orca/pull/37030) OPEN for FIFO resource locks/board; [#42284](https://github.com/stablyai/orca/pull/42284) OPEN for worker creator/assignee IDs; [#40378](https://github.com/stablyai/orca/pull/40378) OPEN for first-gate answer. None of those unmerged heads is credited to shipped original HEAD.

**Freshness margin:** the exact independent source commit was 2eb3748d5aec4ff0b44718741721b12e9b40a079 on 2026-11-19 ~18:01 UTC. At sync original main advanced to [ab1a03311399d05708156a89214272a469199173](https://github.com/stablyai/orca/commit/ab1a03311399d05708156a89214272a469199173), **14 commits ahead**, zero behind per native GitHub comparison. These commits include agent-hook state preservation, bot item questions and UI/Windows changes; this change set was not independently reclassified or natively tested for the whole Run constructor. This case pins original research at 2eb3748d5aec4ff0b44718741721b12e9b40a079, with a required current-HEAD overlap preflight before implementation. It does not quietly assert this new main is assessed.

## Function ownership

Historical Index is S1=A / S2=C / S3=— / S3*=— / S4=— / S5=—. Operations are external coding-agent loops hosted in standard Orca; coordination is supplied per-worker worktree isolation. Proposed S3 owns different choices for *current whole Run obligations* (hold, reassign, settle) under operator limits rather than raw task control; code/data structures alone do not provide an autonomous actor. S3* requires independent corrective audit beyond ordinary human PR review; S4 requires prospective options development and later S3 return; S5 is reserved parent identity/merge consent. Missing historical grades do not automatically imply useful new product work.

## Capability priority

**P0:** S3=— -> S3=C as optional decision/authority/actual action/feedback composition in first-party Run/Task/worker code. S3 must remain explicit developer-composed and legitimate.

**P1-A (native prerequisite):** provider-generic persistent review obligation with required outcome, exact PR head, observed check/review status, next owner, trigger and expiry. A worker_done event must NOT settle merge-required work. This is likely original #21984's smallest legitimate product-native path, even without any VSM C.

**P1-B (S3-specific closure):** opt-in Run-scoped owner-controlled actor registration, legal hold/reassign/settle alternatives, authority/gate/capacity enforcement, idempotency/epoch fencing, restart persistence, real Task/Dispatch/merged-current-head feedback. Verify whether shipped coordinator and its extension/CLI/Run transitions already provide an equivalent complete constructor. No duplicate architecture without proof of incremental effect.

**P2:** NONE.

## Parallel contribution-on-top review

| S3 C link | Track A shipped / original-native work | Track B minimal source-native constructor | Falsifier |
| --- | --- | --- | --- |
| Whole-current commitment and disturbance | Existing worker lifecycle can report worker_done; Issue #21984 defines unclosed merge-required objective | Extend first-party durable Run commitment snapshot with exact current PR head, owner and pending review state | Native existing commitment record already provides this accurately |
| Bounded lawful options | CLI/coordinator/Task/Run and human gates; #16852/#10211 open | Only hold, reassign eligible successor, settle after proven exact-head merged, under bounded parent rights | Hardcoded retry/FIFO or privileged external merge |
| Decisive autonomous S3 owner | Host/operator chooses manual steering; #11229 seeks deterministic workflows | Opt-in developer-composed independent Run-scoped model agent chooses one legal present-work option | Existing coordinator alone already makes equivalent actual autonomous choices |
| Enforced next operation | Run Task/Dispatch transitions, capacity and human gates | Versioned per-Run decision receipt, atomic next Task dispatch or held Run, deny stale/cross-Run actions | Only advisory text or stale lease alters worker |
| Return and next commitment | Worker result/provider check feedback, current CLI status | Correlate decision ID to true follow-up worker status and PR merge/current head; re-present state to S3 actor | Mere worker_done/PR URL counted as merged |

## Implementation options

1. Independently verify the cheapest provider-generic original #21984 P1-A solution; do not duplicate a new provider integration or independent merge authority.
2. Review native coordinator/Run lifecycle and all relevant unmerged PR heads. If a first-party, developer-composable S3 manager is still missing, prototype opt-in P1-B in first-party Run/Task/CLI with bounded rights.
3. Test the same merge-required task both ways, with lawfully different manager hold/reassign/settle effects, restart/replay negatives and current-head proof. If native coordinator plus #21984 meets the outcome with less cost, stop P0 and retain only native implementation.
4. Local Run first; remote/paired variants and third-party PRs only after fresh formalities/rights verification. No product source edits in this synchronization.

## Specification and domain alternatives

Only new source-demonstrated VSM ownership ambiguity merits an Index/Profile/Skills routing; old accepted assessment is not revised by roadmap. A separately authorized domain experiment may test the S3 hypothesis but cannot stand in for supported original-native first-party composition or original maintainer acceptance.

## Cost experiment

Match A/B tasks with merge-required goal, wrong/stale head, pending review, provider outage, human gate and next eligible worker. Compare native coordinator+minimal #21984 against proposed developer-composed S3. Measure wrong terminal closures, correct next ownership, confirmed merge, runtime/cost, implementation/integration/review/test and maintenance effort. No real experiment.
- Cost status: NOT_MEASURED

## Delivery and publication

- Result: NEEDS_EVIDENCE
- External issue: DRAFT — NOT PUBLISHED
- Native tests: NOT_RUN, no Orca product code modified or released; this metadata sync is not proof of original-HEAD current C.
- Independent 2026-11-19 chat outcome at exact 2eb3748d5aec4ff0b44718741721b12e9b40a079: GO for proposal / NEEDS_EVIDENCE research; a continuation refined **P1-A** exact head/required merge and **P1-B** bounded actor rights, replay and persistence. Both remained read-only under old PAUSE, with no public original contact.
- Historical previous case: [2026-11-18 roadmap at 7313d9072a67d4071694338bef6765909ec40531](https://github.com/opensiro-contributions/orca/blob/7313d9072a67d4071694338bef6765909ec40531/.opensiro/issues/orca-merge-required-s3-control-20261118/roadmap.md), original HEAD 270fc64dcf478e3510f88aa9f0dc58a0c78c5d52, already GO plan-only but no independent fresh case. Git history preserves its former DATE/DECISION_READY and PAUSE labels. Newer original source 14 commits ahead is a freshness constraint, not an unreasoned invalidation.
- No public GitHub fork Issue/PR, original Issue/comment/PR, human CLA signature, implementation, current Index upgrade or measured savings. Public publication requires separate exact approval.
