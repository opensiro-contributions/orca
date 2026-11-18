# Orca — S3 current-commitment C construction and native acceptance contract

**PLAN_ONLY / DECISION_READY · DRAFT — NOT PUBLISHED.** [Human decision Issue](https://github.com/opensiro-contributions/orca/blob/opensiro/meta/.opensiro/issues/orca-merge-required-s3-control-20261118/issue.md) ↔ this AI/developer contract. **Final decision GO; P0 S3 Run commitment controller, P1 native lifecycle/authority, P2 NONE.** Historical accepted Index: **S1=A · S2=C · S3=— · S3*=— · S4=— · S5=—**, [reviewed 2026-09-17](https://github.com/opensiro/vsm-harness-index/blob/5f6ea0c777733813ca42e3f210390a719488dcfb/assessments/or/orca-stablyai.md), original ref `c33a446190bdfa21286a373e097c50a2b3e0a4d4`, blob `982a55242d439c8f685e6a02c78d7cc3988119d1`, Profile 0.2.2 / procedure 0.3.1. Current original observed [`270fc64dcf478e3510f88aa9f0dc58a0c78c5d52`](https://github.com/stablyai/orca/blob/270fc64dcf478e3510f88aa9f0dc58a0c78c5d52/README.md) on 2026-11-18, not reassessed. Fork metadata begins `PAUSE/DORMANT`.

## Functional scope and boundary

| Function | First-party behavior vs candidate | Target status |
| --- | --- | --- |
| S1 A | Coding agents produce operational changes | Exclude mandatory C |
| S2 C | Worktree isolation controls collisions; FIFO lock [PR #37030](https://github.com/stablyai/orca/pull/37030) is unmerged | Exclude mandatory C, preserve conflict boundaries |
| **S3 —** | Run-wide present commitments and resource/priority choice not established in accepted assessment | **P0 proposed, not installed** |
| S3* — | Human review and proposed worker identity ≠ independent metasystem S3* audit | Exclude from this P0 |
| S4 — | No sourced future/external organizational adaptation proposal in scope | No target |
| S5 — | Human owner retains required approvals, policy and ultimate authority | No actor/parent-right transfer |

**System in focus:** one supported local Orca orchestration Run, with multiple Task/Dispatch/worker lifecycles and provider-generic PR acceptance evidence. External CI/review providers own their statuses; the VSM proposal does not become a provider or a GitHub maintainer. Remote/paired variants are explicitly out of first pilot until equivalent authority and readback are validated.

**Counterfactual:** remove the developer-composed S3 decision actor but retain the Task/Run transports and hard gates. If core rules alone select the same hold/reassign/settle decision, the actor is cosmetic and **does not witness a composable C**. If no actor is installed, the current manual/native path remains legitimate without invented autonomous selection.

## Existing first-party source and independent proposed work

| Grounded source at observation | Status | Claim and explicit limit |
| --- | --- | --- |
| [README pinned](https://github.com/stablyai/orca/blob/270fc64dcf478e3510f88aa9f0dc58a0c78c5d52/README.md) | SHIPPED documented | Runs supervised agents in parallel worktrees; CLI and human diff review exist. No S3 governance grade follows |
| [Issue #21984](https://github.com/stablyai/orca/issues/21984) | OPEN ISSUE | Merge-required goal may outlive worker_done; exact revision and downstream owner/action are required |
| [Issue #11229](https://github.com/stablyai/orca/issues/11229) | OPEN ISSUE | Manual shell / natural language routing falls short of deterministic review–fix flow |
| [PR #16852](https://github.com/stablyai/orca/pull/16852) | OPEN PR, not current main | `target_concurrency`, `capacity_eligible`/slot claim; author explicitly excludes automatic replacement |
| [PR #10211](https://github.com/stablyai/orca/pull/10211) | OPEN PR, not current main | Durable pending gate attention; human resolution remains first-party owner |
| [PR #37030](https://github.com/stablyai/orca/pull/37030) | OPEN PR, not current main | SQLite FIFO lease + board for shared resources, S2 overlap; no Run-wide policy actor |
| [PR #42284](https://github.com/stablyai/orca/pull/42284) | OPEN PR, not current main | Worker creator/assignee identity projection, not an independent audit or permission |
| [PR #40378](https://github.com/stablyai/orca/pull/40378) | OPEN PR, not current main | Pending-only first decision gate update avoids conflicting resolutions |

**Current-HEAD uncertainty:** the README and source-linked issue/PR diffs were read; complete installed runtime capabilities, current local release modes, native test suite and current-source code/PR merge conflict matrix are **not independently executed**. Before implementation compare latest default HEAD plus each relevant open PR head and find equivalent existing S3-specific implementation. CLA/DCO and AI attribution policy remain **UNVERIFIED**; original MIT license is public. A recommendation to source-pinned Index re-review is advisory (>30 days).

## Proposed S3=C logical first-party ports (none claimed shipped)

| Port | Native input/output | Decisive owner and hard boundary | Required source-native delta |
| --- | --- | --- | --- |
| **S3CommitmentSnapshot** | Run/Task/Dispatch, required terminal outcome, provider URL and observed exact head, check/review evidence, capacity/owner, last observation timestamp | Sensor/normalizer is not the S3 chooser; unknown provider state stays unknown | Extend current Task/Run persistence using provider-generic issue #21984 schema, not a new global control plane |
| **S3CurrentOptions** | Versioned Run commitment; only `hold`, `reassign eligible fixer`, `settle after valid current-head merge`, with preconditions/expiration | Human declares required outcome and bounded delegated Run rights; provider adapter cannot forge merge | Add durable supported S3 option store with explicit head-revision invalidation and decision replay key |
| **S3DecisionConstructor** | Developer registers one Run-scoped autonomous actor mapping eligible snapshot/options to signed choice/reason; no actor gives no auto choice | Actor, not Core, selects among lawful S3 alternatives; principal/Run/scope/revocation checked | New function-specific first-party registration/invocation port, not an arbitrary callback that never governs work |
| **S3AuthorizedIntervention** | Conditional transition of Task status/owner, successor Work item/dispatch admission or final settlement; atomic capacity check | Existing hard S2 resource locks and human-required decision gates remain enforced, no privileged external merge | Adapter into native Run/Task/Dispatch mutation, first-winner lease/revision check; reuse relevant #16852/#10211 if merged |
| **S3ReturnReceipt** | Observed later Task status, worker launch/denial/merge at current head; durable actor decision → outcome link | Controller sees actual closure, not intended action or `worker_done` summary | Introduce truthful receipt and subsequent Run snapshot/update, unknown and replay denials observable |

**Sufficiency claim, conditional on later implementation:** these five logical elements jointly allow a developer to compose an actual independently deciding S3 actor in the supported distribution, choose between real current-management alternatives, enforce the selected authorized path and observe returned operational feedback. Removing the actor or any of the decision/authority/effect/feedback links must break the **C** witness. No library hook, generic scheduler, issue title, PR code alone, prompt or future hypothetical fulfils it.

## Priority, native integration and independent options

- **P1 prerequisite, possible first:** implement only provider-generic current-head review commitment evidence needed by #21984. Use existing Run/Task DB and authorization; reconcile #16852 capacity-slot PR and #10211 gates rather than introducing duplicate stores. Explicit "unknown" readback and owner/trigger mandatory on external waits.
- **P0 target:** one `Run` commitment type with externally supplied policy actor, three bounded choices and applied/denied feedback; no universal workflow YAML engine or extra S5/agent controller. First fork pilot local Run only.
- **P2 NONE:** no second function construction or optional parent mode justified; S3* independence needs its own separate observed need and tests.
- **Native alternative:** ship #21984's minimal lifecycle/owner/merge resolution without AI decision construction, and/or use manual CLI scripts documented in #11229. If it meets matched task at lower risk/cost, stop proposed P0 and return NO_GO during implementation preflight.

## Proposed native acceptance cases (NOT EXECUTED)

| Case | Supported original-native setup + actor decision | Verifiable subsequent Run/Task state | Fail/stop meaning |
| --- | --- | --- | --- |
| **ORCA-S3-01 hold despite worker_done** | Two worker Tasks, one PR requires merge. Confirm `worker_done`; registered Run controller chooses `hold` while current-head checks are pending | Durable commitment stays active, no incorrect completion/worker admission, receipt references same head | `worker_done` alone closes Run |
| **ORCA-S3-02 reassign when review blocks** | Existing PR receives changes requested at head A; authorized actor chooses `reassign` to eligible Task | Exactly one successor admitted within capacity; original Task retains clear ownership/lineage; later receipt returns observed worker outcome | Duplicate dispatch or unauthorized resource claims |
| **ORCA-S3-03 close only on exact merge** | Provider reports merged at verified head B with required outcome; actor chooses `settle` | Run-level obligation changes to settled with pinned B/current-source receipt, worker release can follow | PR merely opened, green checks, or stale head A is accepted as merge |
| **ORCA-S3-04 lawful alternative** | Same eligible Task inputs but a different installed actor chooses `hold` rather than `reassign` | Different observable admission/Run state without changing underlying hard rights | Core hardcodes all choices; constructor cosmetic |
| **ORCA-S3-05 fail-closed rights/revisions** | Cross-Run/expired actor, missing actor, gate requiring human decision, provider unreachable, stale head or exhausted capacity | No unauthorized transition; concrete denial/unknown receipt; native manual workflow intact | Escalation or close without owner/capacity/current-head proof |
| **ORCA-S3-06 compatibility/cleanup** | Restart Run or optionally test paired host after local acceptance; compare with smallest native lifecycle-only alternative | No duplicate decisions, receipts survive restart; if remote unverified mode fails closed | Invisible release, false success, speculative remote support |

**Test implementation routing:** create focused Vitest cases in current `src/main/runtime/orchestration` store / RPC / CLI suites (see evidence and test pattern linked in [PR #16852](https://github.com/stablyai/orca/pull/16852)); then execute `pnpm typecheck` and native focused `pnpm test` commands under the repository's current contribution instructions. Commands, fixtures, test counts and passing statuses must be verified again at actual implementation revision. **No commands have been run for Orca in this plan-only study.**

## Falsification, cost and decision owner

- If source/current merged PR already provides a first-party S3 Run controller, run the same tests before adding one: **NO_GO duplicate**.
- If #21984's small lifecycle closes user need without autonomous composition, or if per-Task decision never regulates Run-wide commitments, **NO_GO P0**.
- If controller cannot be installed with bounded Run rights, cannot change downstream work, or cannot return truthful feedback, **no C sufficiency**.
- If third-party original contributor terms/CLA prevent an external PR, use permitted separate fork research only; never imply consent.
- Measure matched native and S3-informed task completion, review, maintenance and security costs; **NOT_MEASURED**.

**Final operator decision: GO (plan only)** for the narrow S3 commitment controller; earliest **implementation gate** is fresh source overlap + legal preflight + separate Upgrade intent and owner `RESUME/ALLOW`. **No product code, current VSM grade, public GitHub Issue, external PR, owner mandate or external review action is authorized here.** Metadata `PAUSE/DORMANT` remains binding.
