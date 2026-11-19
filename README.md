# The Governance Gap

Agent identity and the questions the industry still can't answer — a reading of McKinsey's *Technology Trends Outlook 2026*, documented as a short research paper.

This is not an original field study. It's a secondary reading: what a major industry report says about the collapsing vulnerability window, the inversion of human-to-machine identity ratios, and the open governance questions around autonomous agents — connected to the concrete problem facing anyone who builds or audits agentic systems against real surface.

## The paper

- 📄 [English (PDF)](paper/en/The_Governance_Gap.pdf) · [LaTeX source](paper/en/paper_en.tex)
- 📄 [Español (PDF)](paper/es/La_Brecha_de_Gobernanza.pdf) · [fuente LaTeX](paper/es/paper_es.tex)

**Abstract.** This text is a reading of the *Cybersecurity and trustworthy systems* and *Agentic AI* sections of McKinsey's *Technology Trends Outlook 2026*, not original field research. It documents three observations from the report — the collapse of the vulnerability window, the inversion of the human-identity-to-machine-identity ratio, and the absence of consensus on agent governance — and connects them to the concrete question facing anyone building or operating agentic systems against real surface: who audits an agent's action before, during, and after it happens. It closes with a list of open questions, not resolved principles, because the report itself is explicit that the industry has not answered them yet.

## The three observations

1. **The window that closed.** More than 75% of cybersecurity vulnerabilities are now classified as zero-day — by disclosure time, an exploit already exists. The defense problem shifts from "did we detect it?" to "can we tell real signal from agent-generated volume?"
2. **Identity inverts.** Non-human identities (agents, API keys, service accounts) already outnumber human identities roughly 100 to 1 inside organizations running agents in production — a new class of identity-and-access risk, not an extension of the old one.
3. **The question nobody answers yet.** Who authorized an agent's action, whether it stayed in scope, and how delegation flowed — McKinsey is explicit this is an open industry question, not a solved problem waiting on adoption.

## Open questions

The paper closes with five open questions rather than design principles — see the [PDF](paper/en/The_Governance_Gap.pdf) for the full list, covering scope-evidence beyond text logs, responsibility across agent-to-agent delegation chains, auditing non-human identity lifecycles, which governance standard emerges first, and how to measure a governance control before an incident does it for you.

## Methodological note

This is a secondary reading of a published source — McKinsey & Company, *Technology Trends Outlook 2026*, sixth edition, September 2026, authors Michael Chui, Roger Roberts, and Tanguy Catlin — not original field research or production data from NullGhost or KIRUX. Figures and findings are cited indirectly, without reproducing tables, charts, or extended passages from the original.

## License

MIT — see [LICENSE](LICENSE).

---

# La Brecha de Gobernanza *(ES)*

Identidad de agentes y las preguntas que la industria todavía no responde — una lectura del *Technology Trends Outlook 2026* de McKinsey, documentada como research paper corto.

Esto no es un estudio de campo propio. Es una lectura secundaria: qué dice un reporte de industria mayor sobre la ventana de vulnerabilidad colapsada, la inversión de la proporción identidad-humana/identidad-de-máquina, y las preguntas de gobernanza abiertas alrededor de agentes autónomos — conectado con el problema concreto de quien construye o audita sistemas agénticos contra superficie real.

El paper completo está en `paper/es/` (PDF + fuente LaTeX).

## Licencia

MIT — ver [LICENSE](LICENSE).
