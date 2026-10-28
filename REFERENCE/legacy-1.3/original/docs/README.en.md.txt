[简体中文](README.md) | **English**

# Documentation

## Purpose and implemented scope

This package provides a reusable operating protocol for complex AI-assisted projects. It includes outcome acceptance, route compression and approval, primary engineering conversation accounting, bounded budget extensions, human participation, evidence reuse, causal decision records, and handoffs. Conversation rounds, internal workload, and actual resource costs/results are recorded separately; internal subagents and parallel tasks do not consume additional rounds. It contains documents and a skill entry, not an application, an enforcement service, or an application project plan.

Under protocol 1.2, each route step targets complete delivery in its first engineering round. Later rounds address actual testing, defect/common-cause repair, regression, acceptance or bounded recovery from a real first-round blocker. Five rounds is a cap, not a schedule for spreading primary development across conversations.

Protocol 1.3 adds complete-task authorization: covered operations, assets and risks can include the whole necessary execution/testing/repair/cleanup/recovery chain without repeated action-level permission. Normal failures remain repairable within that scope; stop only a boundary-crossing action and its real dependencies, while other independently safe, authorized work with budget continues. Existing round counting and approval gates remain.

## Reading order

| File | Purpose |
| --- | --- |
| [User guide](../PROJECT-EXECUTION-PROTOCOL-USER.md) | Plain Chinese explanation, participation duties, and synchronized project status |
| [Engineering protocol](../PROJECT-EXECUTION-PROTOCOL-ENGINEERING.md) | Sole normative source per adopted instance; complete current route and state remain together |
| [Decision template](../DECISION-LOG-TEMPLATE.md) | Copyable record with optional debate, budget, change, reopening, and outcome modules |
| [Skill entry](../SKILL.md) | Short execution entry that points to the authority without duplicating its rules |
| [Audit and evidence](AUDIT-AND-EVIDENCE.md) | Consensus coverage, concrete repairs, scientific support and limits, costs, open questions, and delivery verification |
| [D-0001: budget conversation counting](decisions/D-0001-budget-conversation-counting.md) | Actual decision record for the user-authorized 1.0→1.1 counting change, original rationale, AI risk analysis, and validation events |
| [D-0002: first-round step delivery](decisions/D-0002-step-first-round-delivery.md) | User-authorized 1.1→1.2 clarification of a complete step, follow-up purposes, blockers and verification |
| [D-0003: complete-task authorization](decisions/D-0003-complete-task-authorization.md) | User-authorized 1.2→1.3 authorization scope, normal failures, partial blocking, limits and checks |
| [Skill installation and invocation](SKILL-INSTALLATION.md) | Reusable installation, single-source maintenance, read-only loading checks and manual invocation |

The repository home page and this index default to Chinese and provide English counterparts. The normative engineering protocol, user guide and decision template remain Chinese; existing audit and historical decision records retain their recorded language.

## Installation and use

Prerequisite: a Markdown reader and an agent that can access the files. There is no application build or runtime dependency. Python and PyYAML are only needed for the optional bundled skill-creator validator; they are not needed to follow the protocol.

1. Read the user guide and engineering protocol. The delivered package is explicitly unbound: it grants no application engineering authorization.
2. When the user authorizes adoption for a project, choose one dedicated instance directory and copy the package without overwriting existing project files. Keep the three protocol/template files and their relative links together. Set the authoritative instance path and adoption version in engineering section 13.
3. Fill the project's actual goal, observable acceptance conditions, resources, roles, complete route, and current state. Carry out route approval before implementation. Retain any existing evidence and decision history after checking applicability.
4. For each independent primary engineering instruction, follow engineering section 9, then synchronize the same engineering file and user guide. Internal delegation shares its primary W-ID and does not reserve or consume additional rounds. A new independent user engineering instruction after the prior result, or after a required instruction/approval pause, starts the next round; administrative approval alone does not. Create actual decision records only when triggered; the template itself is not an active log.

For manual execution from the instance directory on Windows PowerShell:

```powershell
Get-Content -LiteralPath '.\PROJECT-EXECUTION-PROTOCOL-ENGINEERING.md' -Raw -Encoding utf8
```

Expected result: the complete main document is readable. If a tool truncates output, read consecutive blocks through the end before working. Then instruct the agent to follow that exact instance, verify its route and budget, and update it on closure. The engineering document includes a copyable manual prompt.

Before installing the complete package, verify the target host's actual search roots, name conflicts and permissions. Keep one maintained source and all dependencies; results on one host do not establish loading on another. See the [installation and invocation guide](SKILL-INSTALLATION.en.md) for setup and read-only checks. Shared installations remain unbound; project state belongs only in the selected project instance.

## Configuration and maintenance

Configure the project ID, instance path, mode, protocol/route/state versions, acceptance, significance thresholds, roles, and budget ledger in engineering section 13. Full mode starts with the parameters defined in the engineering protocol; do not change them in the skill or user guide. Lightweight mode requires the stated eligibility conditions.

Edit the engineering authority first. Synchronize affected user explanations and template fields, then check the skill's links. Existing project instances keep their adopted version until an explicit migration decision; a shared package update is not an approval to change project rules. Confirmed decision bodies are immutable; append result events or create linked successor decisions.

## Development and verification

For document changes, check local Markdown links and anchors, balanced code fences, required fields, matching numeric rules, budget inheritance, and approval order. Re-run only the affected checks after corrections. There is no project-specific documentation linter, link checker, or application test suite in this package.

If the bundled `skill-creator` is available, its `scripts/quick_validate.py` can validate the package directory. On Windows, use Python UTF-8 mode so Chinese paths and content are read consistently:

```powershell
# Replace the validator path with the actual installed skill-creator path.
python -X utf8 'C:\path\to\skill-creator\scripts\quick_validate.py' '.'
```

Expected result: `Skill is valid!`. This checks manifest structure, not actual compliance or project effectiveness. Historical structural checks remain in the audit; target-host loading checks are described in the installation guide. No real application project was run.
