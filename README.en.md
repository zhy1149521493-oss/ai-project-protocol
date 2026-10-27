# AI Project Execution Protocol

[中文（默认）](README.md) | **English**

A reusable execution protocol and Codex Skill for complex AI-assisted projects. It helps users and agents define delivery goals, control technical routes and engineering conversation budgets, reuse evidence, record important decisions, and maintain reliable handoffs.

The protocol is reusable across projects; the Skill entry targets Codex. Other execution environments can read the complete engineering document manually, but automatic loading must be verified separately.

Current protocol version: **1.3**. Each step targets complete task delivery in its first round; follow-up rounds address real testing, repairs and acceptance. Internal subagents, parallel tasks and tools do not consume extra rounds. One authorization for a clearly bounded task covers its necessary execution without repeated action-level permission. The engineering protocol defines the exact boundaries and approval requirements.

## Start here

| Document | Purpose |
| --- | --- |
| [User guide](PROJECT-EXECUTION-PROTOCOL-USER.md) | Understand the protocol, user participation and approval requirements |
| [Engineering protocol](PROJECT-EXECUTION-PROTOCOL-ENGINEERING.md) | Sole normative rule source within each adopted project instance |
| [Skill entry](SKILL.md) | Agent entry pointing to the complete rules and their dependencies |
| [Documentation index](docs/README.en.md) | Installation, use, maintenance, decision records and validation |
| [Causal decision template](DECISION-LOG-TEMPLATE.md) | Record reasons, risks, approvals and outcomes for important choices |

## Try the skill

Clone or download the **complete repository**, keeping its directory structure. Ask your agent to read `SKILL.md` and the complete referenced engineering protocol. For example:

> Read this repository's SKILL.md and its complete referenced engineering protocol, then explain the main rules. This is a read-only exercise: do not start an application project or modify project state.

For automatic discovery, first check the search roots actually supported by your environment, then install the complete folder. Do not copy only `SKILL.md` without its dependencies. This repository provides instructions and documents, not an automatic enforcement service.

## Languages

The homepage and documentation index default to Chinese with corresponding English pages. The engineering protocol, user guide and template remain Chinese; historical audits and decisions retain their original language. The English overview is not a complete translation of the protocol or a separate normative source.

This package is unbound to any application project. Reading or installing it does not authorize or start any application engineering.
