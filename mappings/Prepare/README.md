# VMMM v2 — Prepare Phase Capability Mappings

The **Prepare** phase of the Vulnerability Management Maturity Model (VMMM v2) establishes the foundational conditions required for consistent, defensible vulnerability management decisions.

Capabilities in this phase do not focus on finding or fixing vulnerabilities. Instead, they define **context, authority, expectations, and readiness** — the structures that determine whether vulnerability management decisions can be made deliberately rather than reactively.

Without maturity in the Prepare phase, later phases (Identify, Analyze, Communicate, Treat) tend to exhibit activity without alignment, speed without direction, and metrics without meaning.

---

## How to Use This Folder

Each capability in the Prepare phase is documented using **three complementary artifacts**:

- **Card** — A one-page executive orientation  
  Designed for leadership and stakeholders who need to understand *why the capability matters*, *what breaks without it*, and *how to recognize maturity at a glance*.

- **Guide** — Interpretive and explanatory guidance  
  Explains *why the capability exists*, *what maturity looks like over time*, *common failure modes*, and *how the capability supports decision-making and governance*.

- **Mapping** — Framework alignment and traceability  
  Maps the capability to external standards and frameworks (e.g., NIST, ISO, CIS), clarifies evidence expectations, and supports audit, assessment, and regulatory interpretation.

These artifacts are intended to be used together, but **not always by the same audience**. Executives may only read the Card. Practitioners and assessors will typically rely on the Guide and Mapping.

This repository is intentionally **not** an implementation manual. It defines *what mature behavior looks like*, not *how to configure tools or processes* to achieve it.

---

## Prepare Phase Capabilities

### Context
Establishes how technical vulnerability data is interpreted in relation to business systems, environments, and operational realities.

- Context-Card
- Context-Guide
- Context-Mapping

### Zero-Day Readiness
Defines how organizations prepare for high-uncertainty vulnerability events that require rapid prioritization and decision-making under pressure.

- Zero-Day-Readiness-Card
- Zero-Day-Readiness-Guide
- Zero-Day-Readiness-Mapping

### Policy & Standards
Documents how expectations for vulnerability handling are formalized, communicated, and enforced across the organization.

- Policy-Standards-Card
- Policy-Standards-Guide
- Policy-Standards-Mapping

### Program Governance
Defines decision authority, escalation paths, and accountability structures for vulnerability-related tradeoffs.

- Program-Governance-Card
- Program-Governance-Guide
- Program-Governance-Mapping

### VM Roles & Responsibilities
Clarifies ownership boundaries, handoffs, and responsibility for vulnerability decisions across technical and business functions.

- Roles-Responsibilities-Card
- Roles-Responsibilities-Guide
- Roles-Responsibilities-Mapping

### Risk Appetite & Tolerance Definitions
Establishes how much vulnerability-related risk the organization is willing to accept, defer, or mitigate — and under what conditions.

- Risk-Appetite-Tolerance-Card
- Risk-Appetite-Tolerance-Guide
- Risk-Appetite-Tolerance-Mapping

### Security Ecosystem Integration
Describes how vulnerability management interfaces with adjacent security and risk disciplines without collapsing decision authority.

- Security-Ecosystem-Integration-Card
- Security-Ecosystem-Integration-Guide
- Security-Ecosystem-Integration-Mapping

### Crisis Communication Readiness
Defines readiness to communicate vulnerability-related risk during incidents, disclosures, or public-facing events.

- Crisis-Communication-Readiness-Card
- Crisis-Communication-Readiness-Guide
- Crisis-Communication-Readiness-Mapping

### Data Quality & Source of Truth
Establishes expectations for data reliability, ownership, and consistency that underpin all vulnerability decisions.

- Data-Quality-Source-of-Truth-Card
- Data-Quality-Source-of-Truth-Guide
- Data-Quality-Source-of-Truth-Mapping

### Third-Party VM Readiness
Defines how vulnerability risk in vendors, partners, and externally managed systems is understood and governed.

- Third-Party-VM-Readiness-Card
- Third-Party-VM-Readiness-Guide
- Third-Party-VM-Readiness-Mapping

---

## Interpretation Guidance

Prepare phase maturity is often **invisible** when it is working well and painfully obvious when it is not.

Strong performance in later phases cannot compensate for weak Prepare phase foundations. Organizations frequently exhibit high remediation activity while lacking clear authority, context, or risk boundaries — resulting in inconsistent decisions and unmanaged exposure.

Maturity assessments should evaluate these capabilities **before** drawing conclusions about prioritization quality, SLA effectiveness, or remediation efficiency.

---

## Relationship to the VMMM Canon

These materials support and extend the **VMMM v2 Canon**, but they do not replace it.

- The Canon defines *how maturity is interpreted*
- These artifacts illustrate *how maturity manifests within specific capabilities*
- External frameworks are mapped *to* the model, not the other way around

None of the documents in this folder should be used as:
- An audit checklist
- A compliance certification
- A tool selection guide
- An implementation playbook

Their purpose is to support **consistent interpretation, assessment, and governance of vulnerability management maturity**.

---

## Versioning and Authority

These documents align with **VMMM v2** and will evolve alongside the canonical model.

Changes to capability definitions, maturity interpretation, or framework mappings will be reflected here as the canon evolves. Historical versions may be retained for reference but should not be used for current assessments.
