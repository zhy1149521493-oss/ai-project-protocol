# D-0001: Separate engineering conversations from internal workload

Normative authority: [engineering protocol](../../PROJECT-EXECUTION-PROTOCOL-ENGINEERING.md), section 4.1. Related documents: [user guide](../../PROJECT-EXECUTION-PROTOCOL-USER.md), [record template](../../DECISION-LOG-TEMPLATE.md), [audit](../AUDIT-AND-EVIDENCE.md), [index](../README.md).

## Identity, authorization and status

| Field | Value |
| --- | --- |
| ID / type | D-0001 / controlled protocol change |
| Date / timezone / author | 2026-10-25 / Asia/Shanghai / Codex |
| Protocol / state revision | 1.0→1.1 / T0→T1 |
| Application route / step / budget request | Not applicable: the reusable package remains unbound; no application route or extension is authorized |
| User source | The current conversation's explicit task, “任务：修订项目管理制度的工程对话预算计数规则”, especially sections 2, 3, 4 and 6 |
| Decision status | Accepted: the user explicitly instructed implementation of the enumerated counting rules |
| Evidence status | Existing wording and user instruction inspected; project-efficiency effects remain unverified |
| Lifecycle | Current for this package; adopted external project copies are not automatically migrated |
| Prior formal record | None found; only the empty template existed before this change |
| Review participants | Codex performed the edit; a separate subagent reviewed only counting consistency and preservation of scope. This is not a three-round debate. |
| Record boundary | The user's instruction is the authorization for this exact change. No additional user teach-back, debate participation, or second review of AI-added analysis is claimed. Those future governance requirements remain unchanged. |

The supplied package location was checked against the existing delivery before editing. No directory was moved, renamed or duplicated; host-specific location details are omitted from this reusable package.

## User's original rationale and decision

The following is the user's own stated causal reason, quoted from section 6 without adding AI reasoning:

> 因为我们希望限制的是反复对话却没有实际进展的情况，而不是限制 Codex 在单轮工作中使用子 Agent 提高效率，所以决定将工程对话轮次与内部工作量分开计数。这样既保留预算约束，又允许执行者自由使用并行协作，避免制度反过来压低工程效率。

The user explicitly designated the six counting rules as authoritative, authorized the local revision and required an actual causal record. The user also explicitly retained five rounds per step, extensions of at most three, persistent request sequences and their debate requirements, major-route control, real user participation, full rereading and handoffs. This is a bounded instruction to change counting, not an approval to change any application route.

The AI analysis below is authored for this record. It is not represented as something the user had already said or subsequently confirmed. User inspection of the completed revision remains a future event.

## Inspected previous rule and concrete problem

Before editing, Codex read all seven existing Markdown files, including the full main document through its end, user guide, template, skill, audit and indexes. No other local file defined a conversation budget.

The following quotations are **superseded 1.0 history only**, not current instructions:

- Engineering section 4.1 charged separately delegated implementation/testing/review as “每个独立工单 +1，派发前预留”.
- The user guide said “另行委派的独立测试、实现、工程复核也要记账，不能靠多开 Agent 免费增加预算”.
- The audit's old test case with U=4, A=0, Q=0 allowed only one of two delegated tests because each had been treated as a separately charged job. That expected result has been replaced in the current audit.

This interpretation mixed a user's additional engineering conversation with the executor's internal decomposition. It could spend the dialogue budget merely by parallelizing one instruction and could encourage serial or artificially merged internal work. This is an incentive risk identified from the wording and the user's stated intent; no measured productivity loss is claimed.

## Decision and alternatives

The user chose one primary engineering instruction, its continuous internal work and integrated result as the unit of one conversation round. Internal subagents, tools, parallel tasks, code iterations, tests, review, retries and coordination do not add rounds. Codex may choose reasonable internal organization autonomously within the authorized target and bounds.

| Option | Benefit | Cost/risk | Outcome |
| --- | --- | --- | --- |
| Retain separately charged internal tasks | Internal task count remains visible | Task count is not user dialogue count; penalizes parallel execution and confuses costs | Rejected by the user's explicit revision |
| Count primary user-to-main-agent engineering rounds; record internal work/resources separately | Budget constrains repeated instructions while retaining execution flexibility | A long primary round can hide scope growth or resource waste unless bounded | Selected and authorized |
| Ignore internal workload and actual resources entirely | Less reporting | Hides costly retries and incomplete work | Not selected; separate proportional recording remains required |

Subagent count cannot be converted directly into conversation rounds: delegation does not itself create a new user instruction or close the main round, and different tasks/models can have different costs. Internal workload may be documented for diagnosis; elapsed time, model quota and compute must use actual available measurements or be marked unknown. Neither workload nor resource totals prove acceptance.

New user engineering instructions after a reported result count normally. Work that must pause for a new user instruction or approval is handed off; after approval, a subsequent new engineering instruction starts the next round. The approval message alone is administrative. Progress updates and internal reports do not automatically end a primary round. Multiple actual subsequent primary instructions cannot be merged retrospectively, and internal task splits cannot manufacture extra rounds.

## AI-added risk analysis and controls

| Risk identified by AI | Control retained or clarified |
| --- | --- |
| One primary instruction grows into an indefinite engineering project | State the target, acceptance, finite task boundary and applicable resource limits before work; respect existing route and approval gates |
| Excessive internal retries consume quota or time without new information | Record retries/anomalies and actual available resource use; stop the affected attempt at a hard limit, stop condition, abnormal use, or repeated failure without new distinguishing evidence |
| A completed round is relabeled as an internal stage to hide a follow-up | Preserve the user instruction, work continuity, integrated result or required-approval pause, and subsequent instruction in the main W-ID ledger |
| Stage count or internal reports inflate budget use | Reserve and charge only the primary W-ID; internal task identifiers do not change U/Q/R |
| Busy multi-agent work is mistaken for successful delivery | Evaluate actual artifacts, required evidence, untested gaps and acceptance independently of agent count |
| Shared-file edits collide during parallel work | Keep ownership/write scope and coordinated integration; serialize shared-ledger writes without requiring serial internal execution |

Expected benefit: remove a direct accounting penalty for efficient delegation while preserving bounded engineering conversations. This is a rationale, not a measured savings claim. Accepted cost: keeping a short primary-instruction ledger plus proportional internal/resource observations. There is no new metrics system or mandatory numerical quota for agents or tools.

## Preserved constraints and exact change boundary

- Route: initial at most 10 steps, compression to at most 7, further challenge toward 5; existing exceptions and approval conditions remain.
- Per-step conversation budget: default 5; each formal extension at most 3; no next round over the cap without explicit user approval.
- Persistent core-issue/request counters, rejected/withdrawn request counting, odd/even debate requirements and inherited higher scrutiny remain.
- Initial choice, replacement, abandonment or reopening of a major route still requires the existing full review and approval.
- Real user involvement from the first major-debate round, own-word understanding before approval, causal history, full main-document reading each primary engineering round, and state/acceptance/budget/next-entry updates remain.
- Formula C=5+A and R=C−U−Q is retained; U and Q refer only to primary rounds, never internal tasks. Existing records are not silently rewritten or recounted by this change.
- This modifies the reusable package only. No application project was bound, planned, tested or assigned a budget.

## Verification plan, result boundary and later events

Required document acceptance: matching user/engineering/skill rules; actual causal record with separated authorship; no active per-subagent charging; preserved protected rules; saved files and valid local references; a concise final diff summary. The empty decision template is not used as a substitute for this record.

At creation of this decision body, final post-edit verification is not yet complete. Results are appended below with authorship and evidence, not rewritten into the original decision rationale. Future project efficiency, automatic skill loading and the user's subsequent inspection remain unverified until actual evidence exists. Later findings or changes must append an event or create a linked successor decision rather than rewrite these reasons.

## Append-only events

The authorization and rationale above are retained as the decision snapshot. Verification events below record later observations; they do not assert user approval of AI-added reasoning or grant new engineering work.

### EV-0001: Saved-file and scoped consistency verification

- Date / timezone / author: 2026-10-25 / Asia/Shanghai / Codex.
- Evidence: the actual saved files linked above; local validation command outputs and the independent review in this revision's conversation. No external-source review was repeated.
- File integrity: all 8 Markdown files exist, decode as UTF-8, and contain no replacement characters or unbalanced fenced code blocks. All 37 local Markdown links and explicit anchors resolve; the scan reported 0 errors.
- Skill structure: ran the installed skill-creator's `scripts/quick_validate.py` against this package with `python -X utf8`; exit code 0, output `Skill is valid!`.
- Obsolete-rule scan: the old delegation-charging statements do not remain in active instructions or audit expectations. Their only retained quotations are explicitly superseded history in this record.
- Protected-content comparison: compared the actual pre-edit files captured in this turn with saved results. Route compression parameters, application counting and odd/even review, major-decision definitions, approval sequence, route/history control, effectiveness rules, external evidence and inactive alternatives remain unchanged. The debate procedure changed only its experimental-work counting sentence. Default 5, maximum extension 3 and C=5+A / R=C−U−Q remain present.
- Independent scoped review: a separate subagent read all 8 files and found no unresolved counting conflict or unintended change to protected requirements. This was a document/paper review, not a model-behavior experiment.

| Paper case | Verified interpretation |
| --- | --- |
| One remaining round, five internal subagents | Reserve/consume one primary round only; all five may work within its authorization and resource bounds |
| Implementation, repair, test and review under one primary instruction | One round and integrated result, without stage-based charges |
| First result followed by two independent user engineering instructions | Three rounds in total; no retrospective merging |
| Engineering waits for required user approval | Approval alone adds no round; the subsequent new engineering instruction starts the next round |
| Fifth round still has internal tasks | Complete its authorized scope and report; do not begin a sixth round without extension approval |
| Uninformative retries or abnormal resource use | Stop the affected attempt, report and preserve separate workload/resource/acceptance records |

| File disposition | Actual scope |
| --- | --- |
| Engineering protocol | Primary-round definition, examples, reservations, associated gate/ledger terms and version/index synchronization |
| User guide | Matching plain-language rules, resource distinction and revision reference |
| Decision template | Primary W-ID and separate workload/resource fields; no fictional decision entry |
| Skill entry | Main-instruction accounting boundary while retaining the single-authority reference |
| Audit and documentation index | Corrected counting interpretation, replaced obsolete paper expectation and linked this actual record |
| Root README.md | Inspected and unchanged; no budget-counting definition |
| This record | Newly created actual D-0001; original reasons retained, this verification appended |

- Actual outcome: the bounded document revision is saved and its document acceptance checks pass. No application project, route, code or application test was started.
- Resource visibility: one internal review subagent was used for this primary revision instruction; model quota, compute totals and exact elapsed cost were not exposed as reliable totals and remain unknown. This workload description does not add conversation rounds or prove delivery quality.
- Remaining uncertainty: future project efficiency, automatic skill discovery/adherence and user inspection of the completed files are unverified. There is no claim that the user approved this AI-authored analysis after reading it.
- Lifecycle/next entry: 1.1 is current for this unbound package. Stop after handing the revision back for user inspection; future corrections append an event or linked decision, without rewriting the authorized rationale.
