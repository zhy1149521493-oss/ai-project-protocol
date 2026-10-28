# D-0002: A complete step is the first round's delivery target

Authority: [engineering protocol](../../PROJECT-EXECUTION-PROTOCOL-ENGINEERING.md), sections 3.1 and 4.2. Related: [user guide](../../PROJECT-EXECUTION-PROTOCOL-USER.md), [template](../../DECISION-LOG-TEMPLATE.md), [skill](../../SKILL.md), [audit](../AUDIT-AND-EVIDENCE.md), and [D-0001](D-0001-budget-conversation-counting.md).

## Identity, scope and authorization

| Field | Recorded value |
| --- | --- |
| ID / type | D-0002 / controlled clarification of step and round semantics |
| Date / timezone / author | 2026-10-25 / Asia/Shanghai / Codex |
| Protocol / template state | 1.1→1.2 / T1→T2; still unbound to an application |
| User source | This conversation's task, “通用项目执行制度修订：明确「一步」与「一轮对话」的关系”, especially sections 1–3 |
| Decision status | Accepted for this package: the user explicitly instructed this exact correction |
| Evidence status | Existing document wording inspected; the reported application-project misunderstanding was not independently investigated |
| Lifecycle / related decision | Current clarification; D-0001's primary-round counting remains valid and unchanged |
| Application route / engineering budget / request sequence | Not applicable; no application-specific file, route, work order or budget was changed |
| Review / approval boundary | Codex edits and a separate agent's scoped document review; no invented three-round debate, user teach-back or second approval is claimed |

The original user instruction authorizes this local rule clarification. It does not authorize application work or relax future major-decision procedures. AI-added analysis below has not been represented as the user's own words or as having received a subsequent user review.

## User's original reasons

The user reported that project use exposed an interpretation problem. The following are direct statements from the current instruction:

> 项目中的一步，是一轮主工程对话需要完成的完整任务，而不是一个可以在五轮对话中逐步开发的阶段。

> 五轮是预算上限，不是开发进度表

The user's specified correction is to target the entire step in the first execution round, use later rounds for actual testing/defects/common-root repair/regression/acceptance or bounded handling of a real first-round blocker, and stop without consuming unnecessary rounds. Existing counting, budget, authorization and decision procedures must remain.

No project logs, application assets, code or application-specific files were inspected to verify the reported incident. That report is attributed to the user, not recast as an AI-observed engineering fact.

## Inspected ambiguity and evidence

The current engineering authority was read in full. The nine existing package documents were captured and inspected for affected definitions/references, including the installed skill entry. The relevant 1.1 wording did not explicitly prescribe five development phases, but was too weak to exclude that interpretation:

| Prior wording/location | Interpretation risk | Local repair |
| --- | --- | --- |
| Engineering 3.1: “目标是一轮主要工作完成” | An aspiration is treated as permission to plan primary implementation across later rounds | Define a step as a complete first-round task and prohibit planned primary-development deferral |
| Engineering 3.3: estimated rounds; 13.2: “预计工程轮次与分配” | The five-round allowance becomes a stage allocation table | Record complete first-round target/feasibility and follow-up verification/repair allowance instead |
| Engineering 4.2: primary implementation included in five rounds and implementation mentioned for the fifth round | Later major development appears to be a normal planned use of remaining budget | State follow-up purposes and genuine-blocker exception; retain the cap and resource bounds |
| User guide, skill and audit's brief definition | Readers/agents repeat the weaker interpretation | Synchronize the same meaning while pointing to the single authority |

These historical excerpts are evidence of ambiguity, not current instructions. D-0001's frozen reasons and events are retained without edits.

## Decision and alternatives

| Option | Benefit | Cost/risk | User-directed result |
| --- | --- | --- | --- |
| Treat five rounds as a primary-development schedule | Easy to divide investigation, framework and partial features across conversations | Conflicts with the user's complete-step intent; creates preventable handoffs | Rejected |
| Target complete first-round delivery, followed only by real verification/defect work or bounded first-round-blocker repair/retest | Aligns a route step with a usable result while keeping budget for real problems | Requires honest feasibility/blocker reporting and complete acceptance evidence | Selected |
| Require a success claim regardless of blockers or permissions | Appears to satisfy a single-round promise | Encourages false completion or unauthorized action | Rejected; not the meaning of the correction |

Within existing authority, the first round must autonomously organize necessary investigation, implementation, integration, repair and initial validation toward the complete approved step. Internal staging, subagents and parallel tools remain available and add no rounds. They must not be converted into planned later primary-development conversations.

Later independent main instructions remain chargeable as under 1.1. They address actual delivery testing, defect localization, similar issues/common causes, regression of original/related/affected functions, acceptance evidence, or bounded repair/retest of an actual first-round blocker. They are not mandatory second/third-round milestones. Once all required acceptance is met and no actual work remains, finish early.

Objective scale, dependency or authorization barriers require evidence, reasons, actual completed/remaining work and options. A true blocker does not make incomplete work successful and does not grant a new route or permission. Required route approvals, asset-deletion authorization, system-operation permissions and existing controlled-action boundaries still apply.

## AI-added analysis, risk and retained controls

| AI analysis | Control/limit |
| --- | --- |
| A stronger first-round target can be mistaken for guaranteed success | Report actual evidence and partial/blocked/untested states; distinguish target from achieved acceptance |
| A first-round target can encourage unlimited retries or oversized scope | Keep finite scope, resources and stop conditions; report genuine scale/dependency blockers instead of silently spreading development across rounds |
| A blocker label could disguise planned unfinished implementation | Identify the actual blocker and evidence, remaining work, bounded repair/retest purpose and next acceptance conditions |
| Eliminating unnecessary follow-ups could omit required validation | Early finish only after all required acceptance/validation is satisfied; do not invent tests merely to spend budget |
| Installed and canonical rules could diverge | Modify the existing canonical package and verify installed entry/dependencies resolve to the same files; do not create a second rule copy |

Expected result: remove the ambiguity that five rounds authorize a five-stage implementation schedule. This is the user's operational contract, not a research-proven optimum or a measured productivity claim. No new management system or fixed repair/test round schedule is introduced.

Unchanged: 10→7→target-5 route checks; per-step default cap of five main rounds; extension maximum three and explicit approval; persistent issue/request sequence and odd/even debate; main-instruction counting and internal-work/resource separation; real major-route debate, user own-word understanding and second review; change control, causal-history rules, full main-document reading, evidence and stop conditions. Existing project copies retain their adopted version until an authorized migration; this task changes no application instance.

## Validation and history boundary

Planned document acceptance: matching engineering/user/skill meaning; actual D-0002 record; no active five-stage-development interpretation; preserved protected sections and D-0001; valid installed references/version; saved files and valid links. Paper cases: complete first-round delivery, real first-round blocker, a later bug, no further required testing, and anticipated budget overrun. An intentionally pre-staged development plan and an authorization boundary are also checked without performing engineering.

At creation of this decision body, post-edit checks are pending. Append their actual observations below rather than rewriting the user's reasons. The user's subsequent inspection and real-project effects remain unverified.

## Append-only events

The authorization and rationale above form the decision snapshot. Later verification or corrections are appended with date, author and evidence; a changed decision requires a linked record.

### EV-0001: Controlled revision verification

- Date / timezone / author: 2026-10-25 / Asia/Shanghai / Codex.
- Evidence: actual saved package files, the before/after text comparisons and validation outputs in this revision's conversation, and the separate agent's read-only installed-path exercise. No application or external-source research was performed.
- Protected-content comparison: the pre-edit 1.1 text and saved revision match exactly for scope/roles/modes, route compression and route-approval/budget-inheritance rules, all of section 4.1 counting/resource separation, sections 4.3–4.4 request and debate rules, major-decision/user participation/teach-back/second-review/change-control/history procedures, and exception/stop/effectiveness/deployment rules. The mandatory full-read start gate, root README, frozen D-0001, external evidence and inactive alternatives also remain unchanged.
- Saved-file validation: 10 Markdown files exist and decode as UTF-8; no replacement characters or unbalanced fenced code blocks were found. All 58 local Markdown links and explicit anchor targets resolve, with 0 errors.
- Installed-reference validation: the entry and three dependencies are the same physical files through the installed junction and canonical package; the engineering/user/template headers all read 1.2. The installed entry's `quick_validate.py` check exited 0 with `Skill is valid!`. No separate rule copy or new installation was created.
- Independent exercise: the reviewer followed the installed entry and read the complete revised main document through its final section, then checked the related user/template/audit/index/install/decision documents. No unresolved substantive conflict or unintended expansion was found. The exercise wrote no project state or other files.

| Scenario | Observed document-level result |
| --- | --- |
| Normal full first-round delivery with required acceptance passed | Complete the handoff and finish; do not spend remaining rounds |
| Real first-round dependency/technical blocker and unfinished implementation | Record partial/blocked state, evidence, completed/remaining work and options; allow bounded blocker repair/retest, not planned staged development |
| Later tests reveal similar defects | Diagnose the common cause, repair within scope/authority/budget and regress original, related and affected functions |
| No actual issue and all required validation/evidence complete | End the step without manufacturing tests or repairs |
| Four rounds used and required remaining work is expected to exceed the approved balance | Report and apply under the existing procedure now; no over-cap new round without explicit approval |
| Planned first-round investigation, second-round framework, third-round primary features | Rejected as planned deferral of the step's main implementation |
| Complete-delivery target conflicts with missing controlled-action authorization | Stop the unauthorized part and report it as a blocker; do not infer new permission |

- File disposition: seven existing files received local edits (engineering, user guide, template, skill, documentation index, affected audit text, current installation-version references); this D-0002 is new. Root README and D-0001 were inspected and left unchanged. Historical 1.1 installation observations were retained as history, not rerun or relabeled as 1.2 tests.
- Actual result and limits: the document revision, identity/version checks and paper scenarios pass. This does not establish real-project efficiency, guaranteed first-round success, automatic model compliance or a new CLI loading result. The user's later inspection remains a future event.
- Next entry / stop: protocol 1.2 is current for this shared unbound package. Stop after handoff; apply to an application instance only under later authorization and its migration/change rules.
