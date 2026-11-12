---
id: <system>
title: <System>
type: manifest
owner: <system>
standard: formulary/0.2
profile: system
status: draft
summary: <one sentence: what the system is>
code: .
depends: []
documents: [<system>/requirements, <system>/architecture, <system>/increments, <system>/decisions, <system>/open-items]
date: YYYY-MM-DD
---

<!-- System manifest and workspace index. `standard` names the version of Formulary (https://github.com/0x1d/formulary) the documents conform to.
     Copy to docs/README.md. Level L0 of the standard: it names the system's documents, the projects and the packages and points to them; nothing else. One screen. -->

# <System>

<!-- One or two sentences: what the system is and which projects it unifies. -->

| Document | Content |
| --- | --- |
| [requirements.md](requirements.md) | Purpose, goals, constraints |
| [architecture.md](architecture.md) | How the projects fit together |
| [increments.md](increments.md) | Product increments: how the system evolves, and the planned work |
| [decisions.md](decisions.md) | Decisions `<system>/AD-NN` |
| [open-items.md](open-items.md) | Open items `<system>/OI-NN` |

| Project | Summary | Documentation |
| --- | --- | --- |
| <system>/<project> | <one line> | [projects/<project>/docs/](../projects/<project>/docs/README.md) |

| Package | Summary | Documentation |
| --- | --- | --- |
| <system>/packages/<package> | <one line> | [packages/<package>/docs/](../packages/<package>/docs/README.md) |
