# PlausibleBA

**Institutional-grade BA skills for Claude.**

PlausibleBA packages practitioner methodology into Claude skills — so every command produces a professional artefact, not a chat response.

---

## What makes PlausibleBA different

Most Claude skill libraries are prompt wrappers. PlausibleBA is a methodology layer.

Every skill shares a common taxonomy standard — one numbering system, one MECE rule, one XLSX artefact format, one colour palette. Outputs from different skills reference the same business objects, so a capability map, a concept model and a value stream all speak the same language and cross-validate each other.

The quality bar is simple: **if you couldn't hand the output to a board, the skill isn't ready.**

---

## Skills library

| Skill | Status | Description |
|-------|--------|-------------|
| [ba-capability-mapping](https://github.com/plausibleba/ba-skills/tree/main/ba-capability-mapping) | ✅ Live — v1.0.0 | BABOK-grounded Business Capability Map. MECE 4-level hierarchy, Execution/Governance split, validated XLSX artefact. |
| ba-concept-model | 🔜 In progress | Business Object Taxonomy — grounds capability definitions, cross-validates capability map coverage. |
| ba-value-streams | 📋 Planned | Value Stream Analysis — orchestrates capabilities into stages, surfaces gaps and unused capabilities. |
| ba-requirements | 📋 Planned | Requirements elicitation and classification aligned to BABOK knowledge areas. |
| ba-stakeholder-analysis | 📋 Planned | Stakeholder identification and engagement mapping. |

---

## Install

**Claude Cowork / Claude Code desktop:**
```
Plugins → Browse → Personal → + → Add marketplace from GitHub → plausibleba/ba-skills
```

**Claude Code CLI:**
```bash
claude plugin marketplace add plausibleba/ba-skills
claude plugin install ba-capability-mapping@ba-skills
```

---

## Grounded in practice

PlausibleBA is built on real delivery experience — not synthesised from training data.

The taxonomy standard and methodology layer draw from the **Value Cognition Canvas (VCC)** framework, **BABOK v3 Section 10.6** (Business Capability Analysis), and years of enterprise architecture and BA practice. Each skill is tested end-to-end on real business domains before publication, with validated XLSX outputs as the proof of quality.

---

## Community

- 🌐 **Website:** [www.plausibleba.com](https://www.plausibleba.com)
- 📖 **Blog / Substack:** [plausibleba.substack.com](https://plausibleba.substack.com)
- 💼 **LinkedIn:** [PlausibleBA](https://www.linkedin.com/company/plausibleba)
- 💬 **Discussions:** [github.com/plausibleba/ba-skills/discussions](https://github.com/plausibleba/ba-skills/discussions)

Questions, feedback, and skill suggestions welcome in Discussions.

---

*PlausibleBA is maintained by [Terry Roach](https://www.linkedin.com/in/terryroach) — researcher, enterprise architect, and BA practitioner.*
