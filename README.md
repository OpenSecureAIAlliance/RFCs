# Shared AI Findings Exchange (SAFE)

> **Status: Approved** — Approved by the Steering Committee.

SAFE is a working group focused on AI incident learning: confidentially collecting and analyzing AI incidents and near misses, and turning recurring failures into shared, evidence-based controls that reduce systemic risk. 

---
## How SAFE Works

**Report.** As a condition of membership, members agree to report incidents when they become aware, or reasonably suspect, that an AI system they operate has caused unauthorized access or harm, escaped a containment boundary, or continued acting outside approved scope. Intent does not determine whether an event is reportable. Near misses count too.

**Notify.** Affected organizations are notified as soon as possible. Customers with credible exposure are notified within 72 hours. A confidential initial report is submitted to SAFE within 4 business days. Public safety reports follow at 30 and 90 days, subject to security and investigative constraints.

**Review.** Each incident is examined across the full operating stack, model behavior, instructions, safeguards, tools, environment, monitoring, human operations, and supply chain, to surface technical and systemic causes without assigning blame. The affected organization may correct factual errors but does not control the findings.

**Share.** Findings become shared defensive controls. Every review produces a recommendation that specifies the failure, the required defensive outcome, a minimum control and acceptable alternatives, a reproducible verification method, and adoption metrics. SAFE maintains these in a shared, versioned catalog.

**Disclose.** Disclosure follows a tiered model:
1. Confidential rapid alert: Immediate indicators, containment steps and affected patterns for trusted members.
2. Member operating advisory: De-identified analysis, implicated controls, tests and recommended actions.
3. Public safety report: Root causes, systemic lessons, recommendations and adoption metrics after sensitive details are removed.

📄 For full detail on reporting obligations, notification timelines, evidence preservation, and the review framework, see the [SAFE RFC](./rfc-safe-proposal.md).

---

## Guiding Principles

- **Openness with accountability.** Transparent disclosure processes strengthen collective defense, subject to Coordinated Vulnerability Disclosure (CVD) best practices.
- **Open learning.** Reviews focus on technical and systemic causes and not intended to address blame.
- **Risk-based response.** Reporting, disclosure and escalation should reflect actual risk.
- **Member sovereignty.** SAFE establishes minimum interoperability and assurance practices without superseding members’ internal security policies or legal obligations.
- **Learning is separate from enforcement.** Confidential review should encourage candid reporting, while regulators and affected parties retain their legal rights.

---

## Membership

SAFE is open to representatives from across the AI ecosystem:

- Model developers and open-model organizations
- AI deployers and enterprise customers
- Evaluation, hosting, cloud, and tool providers
- Independent security and safety researchers
- Critical-infrastructure operators
- Civil-society and affected-user representatives
- Government and standards bodies as non-controlling observers

SAFE operates independently — no vendor or industry segment controls its findings. Its processes apply equally to open and closed AI systems. Trust is not a control; shared evidence and verifiable improvement are how trust is earned.

---

## Governance

Charter: *(coming soon)*

| Role | Name | Organization |
|---|---|---|
| Interim Chair | Paul DiOrio | NVIDIA |
| Interim Co-chair | Josh Boyer | Red Hat |

---

## Get Involved

- 💬 **Join `#wg-safe`** on [Alliance Slack](https://join.slack.com/t/opensecureaialliance/shared_invite/zt-48aexc4mu-toSufFfbSxcdwcb_vVHupQ) — introduce yourself and start a conversation
- 📋 **Read [CONTRIBUTING.md](./CONTRIBUTING.md)**
- 🙋 **Open an issue** to propose ideas or signal interest
- 📅 **Meetings** — watch `#wg-safe` for scheduling updates

# License

[Creative Commons Attribution 4.0 (CC-BY-4.0)](./LICENSE)
