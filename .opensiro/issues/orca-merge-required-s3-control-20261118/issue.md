# Orca — S3=— -> S3=C (OpenSiro fork-local Human roadmap)

**PLAN_ONLY · proposal-stage GO · research NEEDS_EVIDENCE · DRAFT — NOT PUBLISHED**

**One-sentence proposal:** Reuse native Run and Task transitions. Bind an exact current PR head and outstanding review obligation with a bounded decision authority; let a composed Run manager choose hold/reassign/settle, then require native gated effect and later provider/current-head feedback.

**Canonical decision receipt:** [roadmap.md](roadmap.md) — source of truth for historical assessment, canonical target, P0/P1/P2, decision and research state.
**Technical companion:** [constructor-sufficiency.md](constructor-sufficiency.md) — source-native controls and future test contract.
**Working fork:** opensiro-contributions/orca on opensiro/meta.
**Case:** .opensiro/issues/orca-merge-required-s3-control-20261118/.

## 1. Why Opensiro and central accepted VSM assessment

OpenSiro explores whether VSM-informed organizational construction helps agent harness engineering. It is a **research hypothesis**, not product certification, cost savings or a maintainer adoption request.

### Central starting point — accepted Index, not the target

> **ACCEPTED HISTORICAL INDEX — not current-HEAD grades or proposed after-states**
>
> **S1=A · S2=C · S3=— · S3*=— · S4=— · S5=—**
>
> [Pinned accepted Index assessment](https://github.com/opensiro/vsm-harness-index/blob/9fe281441f1820014dda5da8fff70e5fb1c9b246/assessments/or/orca-stablyai.md); blob SHA 982a55242d439c8f685e6a02c78d7cc3988119d1; historical review ref c33a446190bdfa21286a373e097c50a2b3e0a4d4; reviewed 2026-09-17; historical Profile/Skills versions retained in the canonical [roadmap.md](roadmap.md).

**Repository-wide audit:** The present same-case v0.18.2 follow-up used stablyai/orca original HEAD fd74d16b4793fb19f985aa0486f386609826e7cf, checked first-party source at [docs/site/content/docs/cli/orchestration.mdx](https://github.com/stablyai/orca/blob/fd74d16b4793fb19f985aa0486f386609826e7cf/docs/site/content/docs/cli/orchestration.mdx) and [src/cli/orchestration/tasks/task-handlers.ts](https://github.com/stablyai/orca/blob/fd74d16b4793fb19f985aa0486f386609826e7cf/src/cli/orchestration/tasks/task-handlers.ts), original repository https://github.com/stablyai/orca/issues/21984 (OPEN, review-to-merge objective); native Run and worker CLI are SHIPPED. Broad search found contemporary orchestration PRs but not proof the scoped obligation has shipped., prior accepted assessment and published protocol. The system in focus is the installed first-party agent harness and its supported components; separate host provider, original maintainer policy, repo CI and external services are not automatically in-boundary autonomous owners. Prior fork-case evidence was opened only after the source-first #58 [checkpoint](https://github.com/opensiro/upstream/issues/58#issuecomment-7047329680). This was a bounded source review, not exhaustive source classification or a fresh accepted Index grade.

| Function / plain-language role | Historical Index state | Current source-backed owner/closure | Candidate / justified no-target / uncertainty and rank |
| --- | --- | --- | --- |
| **S1 · Operations** | A | Shipped Orca Run/Task/Dispatch, coordinator wakeups, worker_done and decision gates already provide current task regulation. Worker completion alone does not prove a merge-required PR was reviewed, merged and adopted. Original issue #21984 remains OPEN. | ALREADY_A — coding agents autonomously produce and revise work inside supported Orca sessions |
| **S2 · Coordination** | C | Shipped Orca Run/Task/Dispatch, coordinator wakeups, worker_done and decision gates already provide current task regulation. Worker completion alone does not prove a merge-required PR was reviewed, merged and adopted. Original issue #21984 remains OPEN. | ALREADY_C — isolated worktrees attenuate multi-worker edit collisions; OPEN #37030 FIFO locks are S2-adjacent, not a shipped S3 actor |
| **S3 · Current management** | — | Shipped Orca Run/Task/Dispatch, coordinator wakeups, worker_done and decision gates already provide current task regulation. Worker completion alone does not prove a merge-required PR was reviewed, merged and adopted. Original issue #21984 remains OPEN. | P0 conditional: The first-pass source evidence rules OUT a generic duplicate coordinator; it does not establish that shipped current coordinator code closes the narrower merge-required exact-head objective. Prior GO is retained only for that narrower proposal, with native equivalence untested. |
| **S3* · Independent review** | — | S1 and S2 already have supported roles. S3 specifically concerns outstanding whole-Run post-worker obligations, not raw worker scheduling; S3* must not be inferred from human PR diff review. S5 merge policy stays human. | DEFER — human review/worker identity and PR CI status are not independent first-party corrective audit with later S3 return |
| **S4 · Future adaptation** | — | S1 and S2 already have supported roles. S3 specifically concerns outstanding whole-Run post-worker obligations, not raw worker scheduling; S3* must not be inferred from human PR diff review. S5 merge policy stays human. | DEFER — model/CI/provider revisions are inputs to current work, not a source-demonstrated outside-looking prospective adaptation controller |
| **S5 · Identity/policy** | — | Legitimate parent/user controls ultimate policy, approval and publication, not the proposed auditor or controller. | PARENT_RESERVED — human requires merge objective and protected authorization; no autonomous ultimate policy manager or merge authority transferred |

**Interpretation:** A, C, P and — denote ownership categories, **not quality ranks**; a historical dash is not proof work is necessary and A is not inferior to C. Unsupported current-HEAD functions stay UNKNOWN rather than silently regraded.

**Priority rationale:** S1 and S2 already have supported roles. S3 specifically concerns outstanding whole-Run post-worker obligations, not raw worker scheduling; S3* must not be inferred from human PR diff review. S5 merge policy stays human. The selected S3 target is the only conditional P0 in this existing case. Utility and actual independent operation remain unmeasured.

**Deliberate exclusions / methodology challenge:** No first-party independent actor has been shown to ship the complete optional link. Do not promote the historical grade or treat a proposed design as installed. No new S5 delegation or additional automatically generated Sx. Separate Profile/Skills review is required for any real classification counterexample.

**Contributor / maintainer interests:** NOT_STATED as approval for this construction. An original Issue is not maintainer acceptance.

## 2. Selected construction hypothesis and operator outcome

**Target transition:** S3=— -> S3=C

**Function-specific disturbance:** A worker sends worker_done but the original Run still owes review, requested changes or merge of the exact PR head; the no-longer-active task may lose a rightful current owner.

**Proposed C capability (P0):** Reuse native Run and Task transitions. Bind an exact current PR head and outstanding review obligation with a bounded decision authority; let a composed Run manager choose hold/reassign/settle, then require native gated effect and later provider/current-head feedback.

**Best native operator alternative:** Test ordinary native Orca coordinator and #21984-style review tracking on the same Run before building any new S3 manager; no duplicate framework or unauthorized merge. Native source: [docs/site/content/docs/cli/orchestration.mdx](https://github.com/stablyai/orca/blob/fd74d16b4793fb19f985aa0486f386609826e7cf/docs/site/content/docs/cli/orchestration.mdx) and [src/cli/orchestration/tasks/task-handlers.ts](https://github.com/stablyai/orca/blob/fd74d16b4793fb19f985aa0486f386609826e7cf/src/cli/orchestration/tasks/task-handlers.ts).

**Expected user benefit:** HYPOTHETICAL. HYPOTHETICAL discretionary current-Run hold vs reassignment without losing existing review commitments and exact-head closure under owner/capacity limits; no measured benefit over Orca's native coordinator No native implementation or matched benefit test has occurred.

**Architectural sufficiency argument:** The first-party baseline already provides part of the path: Shipped Orca Run/Task/Dispatch, coordinator wakeups, worker_done and decision gates already provide current task regulation. Worker completion alone does not prove a merge-required PR was reviewed, merged and adopted. Original issue #21984 remains OPEN. The proposed developer-installed decision owner adds the strictly scoped capability: Hold review work, reassign an eligible worker, or settle only on verified exact-head merge/adoption, subject to human merge authorization. A lawful effect and later feedback are required: Run/Task status and next-worker dispatch follow the lawful manager choice; later PR check/review/merge state returns to that manager. This is a conditional complete design, not a shipped C witness.

## 3. Existing native work versus missing construction

**Track A — native coverage:** SHIPPED first-party source: [docs/site/content/docs/cli/orchestration.mdx](https://github.com/stablyai/orca/blob/fd74d16b4793fb19f985aa0486f386609826e7cf/docs/site/content/docs/cli/orchestration.mdx) and [src/cli/orchestration/tasks/task-handlers.ts](https://github.com/stablyai/orca/blob/fd74d16b4793fb19f985aa0486f386609826e7cf/src/cli/orchestration/tasks/task-handlers.ts). Existing original evidence: https://github.com/stablyai/orca/issues/21984 (OPEN, review-to-merge objective); native Run and worker CLI are SHIPPED. Broad search found contemporary orchestration PRs but not proof the scoped obligation has shipped.. Issue or PR is never treated as deployed simply by title.

**Track B — independent on-top C construction:** Reuse native Run and Task transitions. Bind an exact current PR head and outstanding review obligation with a bounded decision authority; let a composed Run manager choose hold/reassign/settle, then require native gated effect and later provider/current-head feedback. Keep the original's native terminology, identities, state and permission checks.

| C-sufficiency requirement | Already present / original status (A) | Smallest conditional first-party delta (B) |
| --- | --- | --- |
| Scoped independent owner choice | Shipped Orca Run/Task/Dispatch, coordinator wakeups, worker_done and decision gates already provide current task regulation. Worker completion alone does not prove a merge-required PR was reviewed, merged and adopted. Original issue #21984 remains OPEN. | Hold review work, reassign an eligible worker, or settle only on verified exact-head merge/adoption, subject to human merge authorization. |
| Enforced effect and later observation | docs/site/content/docs/cli/orchestration.mdx, src/cli/orchestration/tasks/task-handlers.ts provide candidate entrypoints, not a proven new C | Run/Task status and next-worker dispatch follow the lawful manager choice; later PR check/review/merge state returns to that manager. |

**Distinctness and falsifier:** The first-pass source evidence rules OUT a generic duplicate coordinator; it does not establish that shipped current coordinator code closes the narrower merge-required exact-head objective. Prior GO is retained only for that narrower proposal, with native equivalence untested. If the actual native Orca coordinator/Task/Run already provides equivalent lawful independent actor choice with durable versioned obligations and true next-operation return, or the new actor cannot control a later effect and receive feedback, separate S3=C constructor is not qualified Historic prior decision remains the canonical baseline; no new unrelated function is implied.

## 4. Priorities and minimum sufficient result

- **P0:** First-party opt-in S3 Run-commitment snapshot, feasible hold/reassign/settle options, developer-installed autonomous S3 manager decision, Run/Task/Dispatch and protected-gate enforced intervention, and actual later provider/current-head + next-worker feedback to the same manager
- **P1:** P1-A provider-generic durable review/merge obligation at exact PR head, named next owner/recheck and worker_done-not-merged; P1-B Run-scoped bounded manager authority, versioned/replay-safe decisions, restart-persistent current commitments, native coordinator/Task/Run/gate integration; source overlap with original #21984 and open PRs before implementation
- **P2:** NONE — no other function or parent policy upgrade bundled

**Proposed C-sufficiency verdict:** PROPOSED_C_SUFFICIENT at a conditional architectural proposal stage only. No native build, cost proof, Index regrade or external consent.

## 5. Proposed acceptance and stop gates

**Future positive test:** A worker_done for a still-unmerged PR cannot settle a merge-required Run; a later verified merged exact head permits final settlement, with bounded independent hold/reassign choices.

**Future negative test:** Stale PR head, requested changes, lack of merge authority, coordinator loss or replay cannot yield false settlement; ordinary non-merge-required Run behavior stays unchanged.

**Proposed falsifier:** Minimal existing Orca native coordinator plus #21984 board/Run lifecycle achieves the same durable owner→authorized action→verified merge/current-head outcome and later feedback with equal/lower costs, or relevant first-party S3 actor rights/return cannot lawfully be composed

**Validation state:** NOT_RUN; only document structural validation will be performed on fork-local artifacts, not native tests.

## 6. Independent paths

**Original-native contribution:** Test ordinary native Orca coordinator and #21984-style review tracking on the same Run before building any new S3 manager; no duplicate framework or unauthorized merge. Third-party code PR, Issue or comment requires separate owner approval and normal project rules.

**Profile / Skills:** No forced methodology change; raise an independent correction only for a reproducible semantics/ownership conflict.

**Domain fork:** Optional licensed and permission-checked test only, not performed or authorized here.

## 7. Cost hypothesis

Matched native A versus optional new B would measure actual engineering, review, integration, runtime and maintenance effort alongside the named operator outcome. **Cost status: NOT_MEASURED.** Cost reduction is not asserted.

## 8. Decision / handoff

**Proposal-stage decision:** GO

**Research disposition:** NEEDS_EVIDENCE

**Decision reason / next permitted step:** Canonical proposal remains GO / NEEDS_EVIDENCE based on the earlier source-pinned receipt. This v0.18.2 source-first follow-up found The first-pass source evidence rules OUT a generic duplicate coordinator; it does not establish that shipped current coordinator code closes the narrower merge-required exact-head objective. Prior GO is retained only for that narrower proposal, with native equivalence untested. and does not claim newly shipped capabilities or five independent isolated chat contexts. Compare the cheapest native alternative, source drift and lawful C feedback before product implementation.

**Agent/developer handoff:** [constructor-sufficiency.md](constructor-sufficiency.md) and [roadmap.md](roadmap.md), with reservations and prior-independent checkpoint at [Upstream #58](https://github.com/opensiro/upstream/issues/58#issuecomment-7047108048).

**Rights and publication:** MIT original LICENSE; matched fork opensiro/meta owner state was ACTIVE / ALLOW at preflight; recheck before effect. **No public fork Issue**, original Issue/comment/PR, implementation, changed Index grade or new S5 authority is authorized. PAUSE/STOP must block. This draft is not externally published.

**AI disclosure:** Prepared with AI assistance. No native tests, independent human validation or measured benefit claimed.
