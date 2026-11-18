# Orca — merge-required Run commitment control (S3=C) roadmap (OpenSiro plan-only)

**OpenSiro PLAN_ONLY / DECISION_READY / DRAFT — NOT PUBLISHED** · Case: `.opensiro/issues/orca-merge-required-s3-control-20261118` on `opensiro/meta` · [AI/developer constructor contract](https://github.com/opensiro-contributions/orca/blob/opensiro/meta/.opensiro/issues/orca-merge-required-s3-control-20261118/constructor-sufficiency.md) · [receipt](https://github.com/opensiro-contributions/orca/blob/opensiro/meta/.opensiro/issues/orca-merge-required-s3-control-20261118/roadmap.md)

## 1. Why OpenSiro and accepted central assessment

OpenSiro tests whether reusable VSM-informed, source-native specifications can standardize AI harness development and reduce total implementation, integration, review and maintenance cost. This is a hypothesis: no savings or maintainer obligation has been demonstrated.

**Historical ACCEPTED Index starting point, NOT a target or current-HEAD regrade:** **S1=A · S2=C · S3=— · S3*=— · S4=— · S5=—**. [Accepted assessment](https://github.com/opensiro/vsm-harness-index/blob/5f6ea0c777733813ca42e3f210390a719488dcfb/assessments/or/orca-stablyai.md), blob `982a55242d439c8f685e6a02c78d7cc3988119d1`, reviewed **2026-09-17** at `c33a446190bdfa21286a373e097c50a2b3e0a4d4`, Profile **0.2.2**, Skills procedure **0.3.1**.

| Function | Accepted | Meaning and consequence |
| --- | --- | --- |
| S1 Operations | **A** | Supported coding agents autonomously execute work: no mandatory C conversion |
| S2 Coordination | **C** | Worktree isolation attenuates concurrent file interference: no duplicate C target |
| S3 Inside-and-now | **—** | No accepted whole-Run decision owner for current priorities/commitments; investigate actual need, not grade gap |
| S3* Independent audit | **—** | Human diff review is not first-party independent metasystem audit |
| S4 Outside-and-then | **—** | No accepted prospective organizational adaptation loop |
| S5 Identity/policy | **—** | Human task/merge choices are not automatically ultimate organizational policy; reserve operator authority |

**Pins:** original [`stablyai/orca@270fc64dcf478e3510f88aa9f0dc58a0c78c5d52`](https://github.com/stablyai/orca/blob/270fc64dcf478e3510f88aa9f0dc58a0c78c5d52/README.md), observed 2026-11-18; reviewed original `c33a446190bdfa21286a373e097c50a2b3e0a4d4` is historical. The accepted review is 62 days old: recommend an Index-owned source-pinned reassessment, advisory only; these provisional source observations never change Index grades. **Boundary:** supported first-party Orca local Run/Task/worker/CLI orchestration, one operator's Run; external providers and the original maintainer's governance remain outside the proposed controller. MIT repository; original formalities/CLA remain unverified, so no original publication or code transfer. Verified fork parent `stablyai/orca`; missing `opensiro/meta` was provisioned conservatively with `PAUSE/DORMANT`, **not** owner ALLOW.

## 2. Operator need and exact P0 decision

**P0 — S3 current commitment control, GO for a bounded source-native implementation proposal (not code approval).** An operator supervises concurrent coding workers and declares that a task is complete **only when its PR has merged at the required revision**, not when the worker reports `worker_done` or produces a PR URL. A developer should be able to install a Run-scoped decision actor that reads authoritative review/check/capacity state and chooses **hold**, **reassign a fixer**, or **settle after proven merge**. A rights-checked first-party bridge must apply that choice to a later Task/Run action and return a durable result. Different permitted actor choices must cause different observable operations. This addresses [original #21984](https://github.com/stablyai/orca/issues/21984) and the [deterministic multi-agent workflow need #11229](https://github.com/stablyai/orca/issues/11229), without replacing those issues or claiming their proposals are shipped.

**Cheapest native option:** Orca already launches agents and exposes orchestration via [README at observed HEAD](https://github.com/stablyai/orca/blob/270fc64dcf478e3510f88aa9f0dc58a0c78c5d52/README.md); a human/agent can combine manual checks, prompts or custom CLI scripts. [#11229](https://github.com/stablyai/orca/issues/11229) specifically documents why those alternatives are brittle for structured review/fix loops; [#21984](https://github.com/stablyai/orca/issues/21984) documents premature completion and stale-head review. If a small native lifecycle feature solves the complete user task with less total cost, prefer it and **NO_GO** the autonomous constructor.

## 3. Real overlap: shipped vs proposed

| Source | Verified status at observation | Reuse rather than duplicate |
| --- | --- | --- |
| [Orca README@HEAD](https://github.com/stablyai/orca/blob/270fc64dcf478e3510f88aa9f0dc58a0c78c5d52/README.md) | **SHIPPED documented** parallel agents, worktrees, orchestration, review UI, CLI | Reuse Task/Run/worker shells and human review; no claim of S3 |
| [Original issue #21984](https://github.com/stablyai/orca/issues/21984) | **OPEN ISSUE**: PR opened != merged; exact head, successor owner and event checks | Primary unmet user objective, not implemented proof |
| [Issue #11229](https://github.com/stablyai/orca/issues/11229) | **OPEN ISSUE**: deterministic declarative review/fix workflow | Native alternative and role/workflow overlap; not another ticket |
| [PR #16852](https://github.com/stablyai/orca/pull/16852) | **OPEN, UNMERGED**: target concurrency, eligible capacity slots; explicitly does *not* auto-backfill | Reuse if merged and still applicable; not shipped capacity control |
| [PR #10211](https://github.com/stablyai/orca/pull/10211) | **OPEN, UNMERGED**: pending human decision-gate notifications | Preserve human approval; no implied delegated authority |
| [PR #37030](https://github.com/stablyai/orca/pull/37030) | **OPEN, UNMERGED**: FIFO locks/collaboration board | S2 shared-resource safety; not a substitute S3 current-priority decision |
| [PR #42284](https://github.com/stablyai/orca/pull/42284) | **OPEN, UNMERGED**: caller/assignee session IDs in full worker output | Useful attribution, not first-party independent audit |

No complete first-party developer-composable S3 Run decision/return path was established from the verified README, issue and PR evidence; this is a **provisional residual**, not proof that no code implementation exists anywhere. Recheck current main and competing PR heads before engineering.

## 4. P0/P1/P2 and C sufficiency

| Priority | Proposed user outcome | Minimum complete native construction |
| --- | --- | --- |
| **P0 · S3=C design target** | Developer installs a legitimate Run commitment actor; authorized choices actually change ongoing work | Current-head review signal → durable objective/options (`hold/reassign/settle`) → independent developer-supplied decision actor → authorized Task/Run change → observed subsequent worker/merge/denial receipt |
| **P1 · prerequisite** | Correct current review-head and task ownership; no phantom completion | Provider-generic lifecycle/head evidence (reuse #21984), bounded Run capacity integration if #16852 lands, rights-checked task intervention and rollback; reuse native gates/locks instead of rebuilding |
| **P2 · NONE** | No separately evidenced second C or parent-mode feature | Do not turn historical S3*/S4/S5 gaps into backlog or force S3 `C(P)`/`A(P)` |

The [AI contract](https://github.com/opensiro-contributions/orca/blob/opensiro/meta/.opensiro/issues/orca-merge-required-s3-control-20261118/constructor-sufficiency.md) binds the five logical ports to Orca's Task/Run boundary, developer actor, authority and falsifiable native acceptance. A proposal, open PR and passing mock are **not shipped C**. Any later Index C claim requires an implemented native first-party witness and independent Index review.

## 5. Acceptance and stop

- **Positive:** merge-required task reaches `worker_done`, but stays Run-active; a selected authorized actor decision `reassign` starts an eligible follow-up Task; merge at the *current exact head* plus chosen `settle` closes the commitment and records feedback.
- **Alternative:** with the same genuine current inputs an authorized actor chooses `hold`, and no worker is wrongly started; show different subsequent native Run state.
- **Negative:** stale review head, missing actor, failed provider observation, exceeded capacity, revoked/cross-Run rights or human-reserved approval **cannot** close, dispatch or claim merge success; preserve manual-native operation.
- **Materiality:** compare both alternatives to a small provider-generic native review lifecycle; if actor composability adds no measured value relative to cost, stop the constructor before implementation.

Tests **NOT RUN**. Proposed scenarios must be adapted to real current Orca test harness before any Upgrade.

## 6. Three independent, optional routes

1. **Native integration:** deduplicate #21984/#11229 and ongoing PRs, then separately authorize a small fork-local engineering PR; no automatic original PR.
2. **Profile/Skills feedback:** report only a demonstrated assessment-semantics ambiguity; none is independently confirmed now.
3. **Permitted domain fork:** optional MIT-license experiment with one local Run and no claim of maintainer adoption.

## 7. Cost hypothesis

**NOT_MEASURED.** Compare identical multi-worker merge-required tasks under the smallest native manual/script+review-lifecycle solution and proposed S3 constructor. Count developer/integration/test/review/security/maintenance effort, repeated rebriefs, false completion and time-to-verified-merge. No claim that VSM is cheaper.

## 8. Final decision / public boundary

**Final operator decision: GO** — propose precisely the **P0 S3 Run commitment controller** scoped above because #21984 and #11229 show material missing operator outcomes; preserve and re-evaluate already OPEN PRs first. **Do now:** maintain the plan-only case and source-pinned handoff. **Do not:** implement code, invent C, overwrite Index, auto-run PR polling, publish external/original Issues, merge other PRs or transfer S5 authority. An Index reassessment is recommended, not a waiting gate. **Metadata attention is PAUSE/DORMANT** pending an attributable owner decision; no subsequent effectful work under PAUSE.

**Public fork Issue:** exact destination `opensiro-contributions/orca`, action `create issue`, title **Orca — merge-required Run commitment control (S3=C) roadmap (OpenSiro plan-only)**, body **this entire `issue.md`**. **DRAFT — NOT PUBLISHED; exact current-conversation approval required.** AI-assisted research; no native tests or independent human verification claimed.
