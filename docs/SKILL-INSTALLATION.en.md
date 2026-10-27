# Skill installation and invocation

[中文（默认）](SKILL-INSTALLATION.md) | **English**

Use this guide to install and read `ai-project-protocol`. The current protocol is [1.3](../PROJECT-EXECUTION-PROTOCOL-ENGINEERING.md); that engineering document is the sole normative rule source within an adopted instance. Installing or reading a Skill does not authorize application project work.

## Complete package and single source

Keep the repository structure intact. The [Skill entry](../SKILL.md), [engineering protocol](../PROJECT-EXECUTION-PROTOCOL-ENGINEERING.md), [user guide](../PROJECT-EXECUTION-PROTOCOL-USER.md), [decision template](../DECISION-LOG-TEMPLATE.md), and their relative references must remain readable. Do not install only the entry file.

Choose one maintained directory as the shared package source. If the host supports linked installation, point its discovery entry to that complete directory to avoid maintaining independent rule copies. A link requires the source to remain accessible; moving or deleting it breaks the link. For a copied installation, record its update source and adopted version rather than editing both copies independently.

Application project state belongs in the project instance explicitly selected by the user, not in the shared Skill template. Updating the shared package does not automatically migrate existing instances.

## Before installation

1. Use the current host's settings, capabilities or [official Skill documentation](https://learn.chatgpt.com/docs/build-skills) to confirm its actual search roots and link support. Do not assume one host's path works everywhere.
2. Check the target location for an existing `ai-project-protocol`, its source and version. Do not overwrite uninspected files.
3. Place the complete package in a confirmed supported location, or link the complete source using a host-supported method. This guide does not require changes to global system settings.
4. Check relative references and complete access to the engineering protocol, user guide and template. Their versions must match the selected source.

## Invocation and direct reading

If the host has discovered the Skill, select `ai-project-protocol` in its supported invocation interface. Automatic discovery, refresh behavior and short-name invocation require confirmation in the current environment; this guide or a structural check cannot establish them.

If automatic loading is unavailable, ask the executing agent to read the entry's absolute path directly. Replace the placeholder with the actual complete package location:

```text
Read <absolute-package-path>/SKILL.md, then follow its relative references
and read the complete engineering protocol through the end.
Identify the current protocol version and project binding state.
This is a read-only check: explain the rules without starting an application
project or changing project state, routes or budgets.
```

For example, read the entry in Windows PowerShell (the path is illustrative):

```powershell
Get-Content -LiteralPath 'C:\skills\ai-project-protocol\SKILL.md' -Raw -Encoding utf8
```

The expected result is readable entry text; the complete referenced engineering document must still be read. If tool output is truncated, read consecutive blocks through the end. Successful file reading does not establish automatic Skill loading.

## Read-only verification

Confirm these outcomes without creating an application route or consuming its project budget:

- The entry and dependencies exist, can be read completely, and correspond to the selected source.
- The executing agent identifies the engineering document's authority and unbound state.
- Internal subagents, tools, tests and repairs do not add rounds within one main engineering instruction; later independent main instructions count normally.
- At the engineering budget cap, the agent follows the application procedure. Task authorization does not add budget automatically.
- Complete-task authorization permits normal repairs within its scope, without covering unapproved risks, assets or operations.

Record actual observations for file access, discovery and invocation separately, including unverified parts. Paper answers and structural checks do not demonstrate long-term effectiveness or grant project permission. Begin application work only after separate user authorization and the protocol's applicable prerequisite approvals.
