# Capability Mapping — Policy & Standards

**Model:** VMMM v2.0.0  
**Domain:** Prepare • **Tier:** Foundational • **Updated:** 2026-01-30

> **Who This Mapping Is For:**
> * Policy and governance teams writing enforceable VM policies that drive actual behavior rather than becoming shelf-ware
> * GRC and compliance teams demonstrating policy completeness and alignment to auditors against NIST, ISO, and regulatory requirements
> * Security engineering teams embedding standards into CI/CD pipelines, infrastructure-as-code templates, and automated compliance checks
> * Security leadership updating policies to keep pace with evolving threats, regulatory changes, and organizational risk appetite

---

## Executive Summary

Policy & Standards capability establishes the governance foundation for vulnerability management by defining requirements, responsibilities, timelines, and acceptable risk thresholds. Mature organizations move beyond static policy documents to embed standards directly into technical controls, automation workflows, and continuous feedback mechanisms. This capability strengthens evidence for policy and planning controls (PL-1, PM-1) across NIST 800-53, governance outcomes (GV.PO) in CSF 2.0, and policy requirements (A.5.1) in ISO 27001. Higher maturity enables organizations to demonstrate that VM activities operate within documented, approved frameworks that align to business priorities and regulatory obligations, with measurable enforcement rather than aspirational statements.

**Key Frameworks:** NIST 800-53 (PL, PM families) • CSF 2.0 (GV.PO, GV.RR) • CIS Control 7.1 • ISO 27001 (A.5.1)  
**Primary Evidence:** Approved policy documents, standards defining requirements and SLAs, exception tracking, enforcement metrics, policy update logs  
**Cross-Domain Dependencies:** Program Governance, VM Roles & Responsibilities, Risk Appetite & Tolerance Definitions

---

## Capability Overview

Many organizations treat VM policies as compliance artifacts—documents written to satisfy auditors, approved once, then filed away and ignored. Teams operate based on tribal knowledge, individual judgment, or whoever pressures them most loudly. When auditors ask "what's your policy on critical vulnerability remediation?", organizations scramble to find a document that may not reflect actual practice. This disconnect between documented policy and operational reality creates audit findings, inconsistent decision-making, and inability to demonstrate governance.

Mature Policy & Standards capability transforms policies from shelf-ware into living governance instruments. Policies clearly define what must be done, by whom, and by when. Standards translate policy into specific technical requirements: patching cadences, acceptable configuration baselines, vulnerability scoring criteria, risk acceptance thresholds. At higher maturity, these aren't just documents—they're embedded into CI/CD gates that block non-compliant deployments, automated scanners configured to organizational standards, and dashboards showing policy compliance in real-time. When threats evolve or regulations change, policies update proactively through documented processes, not reactive scrambles when auditors arrive.

---

## Maturity-Based Evidence Progression

| Maturity Level | Evidence Characteristics |
|----------------|-------------------------|
| **Level 1** | No formal policies or standards exist. Teams operate independently based on individual judgment or vendor recommendations. Requirements undefined. Remediation happens (or doesn't) based on team capacity and priorities. No documented expectations. Evidence: None—teams rely on institutional knowledge and email threads. |
| **Level 2** | Basic expectations documented informally (e.g., "patch critical vulnerabilities quickly", "follow vendor security guidance"). Documentation fragmented across wikis, SharePoint sites, team-specific runbooks. Application inconsistent—enforcement depends on individual team culture or external audit pressure. Evidence: Scattered documents with vague requirements, no version control, unclear ownership. |
| **Level 3** | Organization-wide policies formally documented, approved by leadership, and communicated. Standards specify ownership, remediation timelines by severity, acceptable risk thresholds, exception handling process, compliance alignment. Published centrally with defined review cadence. Evidence: Approved policy documents with signatures, published standards accessible to all teams, documented compliance mapping, annual review records. |
| **Level 4** | Policies embedded into technical workflows: CI/CD pipelines enforce configuration standards, IaC templates include security baselines, vulnerability scanners configured to organizational requirements. Exceptions centrally tracked with approvals. Policy updates triggered by regulatory changes, threat intelligence, or risk appetite shifts. Evidence: Policy-as-code implementations, automated compliance checking logs, exception database with workflow history, documented policy update triggers and approvals. |
| **Level 5** | Continuous policy evolution through feedback loops: exposure metrics identify policy gaps, incident post-mortems drive standard updates, audit findings trigger systematic reviews. Enforcement automated across hybrid/multi-cloud with policy violations blocked or auto-remediated. Policy effectiveness measured (e.g., reduction in policy-violating deployments, time-to-compliance improvement). Evidence: Policy effectiveness dashboards, automated enforcement logs, feedback-driven policy change history, measurable improvement in compliance outcomes. |

---

## Framework Alignment Overview

| Framework | Primary References | Alignment Summary |
|-----------|-------------------|-------------------|
| **NIST Cybersecurity Framework 2.0** | GV.PO, GV.RR | Supports documented policies and procedures, defined roles and responsibilities, and governance oversight |
| **NIST SP 800-53 Rev. 5** | PL-1, PM-1, PM-9 | Strengthens policy and procedures documentation, program management, and risk management strategy |
| **CIS Critical Security Controls v8** | Control 7.1 | Directly implements documented vulnerability management process with defined policies and standards |
| **ISO/IEC 27001:2022** | A.5.1, A.5.2, A.5.10 | Demonstrates policies for information security, defined roles/responsibilities, and acceptable use definitions |

---

## NIST SP 800-53 Rev. 5 Alignment

**Relevant Control Families:** PL – Planning, PM – Program Management

This capability provides the documented policy and standards foundation required throughout NIST 800-53. Policies establish organizational requirements that system-level controls implement. Standards define specific security and privacy requirements that flow down to technical implementations. Mature policy capability demonstrates organizational commitment to security and privacy through approved, communicated, and enforced requirements.

**Key Exemplar Controls:**

| Control | How This Capability Strengthens Evidence |
|---------|------------------------------------------|
| **PL-1 – Planning Policy and Procedures** | Directly satisfies requirement for documented policies and procedures addressing purpose, scope, roles, responsibilities, and compliance for planning activities including vulnerability management |
| **PM-1 – Information Security Program Plan** | Contributes documented VM program strategy, objectives, and requirements as component of enterprise information security program with defined governance and accountability |
| **PM-9 – Risk Management Strategy** | Provides documented risk tolerance thresholds, risk acceptance criteria, and risk-based decision frameworks embedded in VM policies and standards |

> Additional controls strengthened include PL-2 (System Security Plans), PL-4 (Rules of Behavior), and CA-5 (Plan of Action and Milestones) through established policy frameworks.

---

## NIST CSF 2.0 Alignment

**Relevant Function:** Govern (GV)

Mature policy capability directly supports governance function by establishing documented expectations and requirements. Organizations demonstrate that VM activities operate within formal frameworks rather than ad hoc practices.

**Key Exemplar Subcategories:**

| Subcategory | How This Capability Strengthens Evidence |
|-------------|------------------------------------------|
| **GV.PO – Policy** | Demonstrates documented policies establishing organizational expectations for vulnerability management aligned to mission, stakeholders, and applicable regulations |
| **GV.RR – Roles, Responsibilities, and Authorities** | Documents roles and responsibilities for VM policy development, approval, communication, enforcement, and updates with clear accountability |

---

## CIS Critical Security Controls v8 Alignment

**Relevant Control:** Control 7 – Continuous Vulnerability Management

CIS Control 7.1 explicitly requires documented vulnerability management process. This capability provides that foundational documentation including policies, standards, and procedures.

**Key Exemplar Safeguard:**

| Safeguard | IG Level | How This Capability Strengthens Evidence |
|-----------|----------|------------------------------------------|
| **7.1 – Establish and Maintain Vulnerability Management Process** | IG1 | Directly implements requirement for documented VM process reviewed and updated annually or when significant changes occur, establishing foundational governance |

> This capability supports all Control 7 safeguards by providing policy framework within which scanning, remediation, and tracking activities operate.

---

## ISO/IEC 27001:2022 Alignment

**Relevant Control Category:** Organizational Controls (5.x)

ISO 27001 requires documented policies as foundation for ISMS. Policy & Standards capability demonstrates systematic approach to establishing, communicating, and enforcing VM requirements.

**Key Exemplar Controls:**

| Control | How This Capability Strengthens Evidence |
|---------|------------------------------------------|
| **A.5.1 – Policies for Information Security** | Core capability—provides documented, approved, communicated policies addressing VM requirements aligned to business, legal, and regulatory obligations |
| **A.5.2 – Information Security Roles and Responsibilities** | Documents VM roles and responsibilities within policy framework including ownership, accountability, and escalation paths |
| **A.5.10 – Acceptable Use of Information and Other Associated Assets** | Defines acceptable risk thresholds, vulnerability tolerances, and acceptable security configurations within VM standards |

> Additional organizational controls (A.5.4, A.5.6) benefit from established policy governance processes including reviews, approvals, and stakeholder engagement.

---

## Maturity Investment Guidance

**Foundational Investment (Levels 1–2):**  
Document basic VM policies and standards addressing ownership, timelines, and expectations. Gain leadership approval and communicate to relevant teams. Establish annual review cycle. **ROI:** Reduces audit findings related to missing policies, provides baseline requirements for teams, enables consistent expectations across organization. Creates foundation for demonstrating governance to regulators and customers.

**Enhanced Investment (Levels 3–4):**  
Develop detailed standards translating policies into specific requirements: remediation SLAs by severity/asset tier, configuration baselines, risk scoring criteria, exception approval workflows. Embed standards into technical controls: scanner configurations, CI/CD gates, IaC templates. Implement policy-as-code where feasible. Establish proactive update process triggered by regulatory changes or threat landscape evolution. **ROI:** Automated enforcement reduces policy violations, embedded standards prevent non-compliant deployments before production, centralized exception tracking improves risk visibility, proactive updates prevent compliance gaps.

**Strategic Investment (Level 5):**  
Implement continuous policy improvement through feedback mechanisms: exposure metrics identify policy gaps, incident post-mortems drive updates, audit findings trigger systematic reviews. Measure policy effectiveness (compliance rates, time-to-compliance, reduction in violations). Automate enforcement across hybrid/multi-cloud environments with policy violations blocked or auto-remediated. **ROI:** Data-driven policy evolution ensures relevance, measurable effectiveness demonstrates program value, automated enforcement at scale reduces manual effort and human error, continuous improvement prevents policy obsolescence.

---

## Practical Applications

This capability mapping may be used to:

- **Policy Development:** Guide creation of comprehensive VM policies and standards aligned to framework requirements and organizational needs
- **Gap Analysis:** Identify missing policy elements (e.g., exception handling, risk acceptance criteria, update procedures) required for framework compliance
- **Audit Preparation:** Demonstrate documented policies with evidence of approval, communication, enforcement, and periodic review
- **Governance Discussions:** Show how policy maturity progression strengthens organizational governance and reduces compliance risk
- **Automation Planning:** Identify opportunities to embed policies into technical controls (CI/CD gates, scanner configs, IaC templates)
- **Policy Review Cycles:** Benchmark policy update processes against maturity expectations to ensure policies remain current with threats and regulations

---

## Boundaries & Limitations

**What This Mapping Is NOT:**
- ❌ A compliance determination or attestation that existing policies meet specific framework requirements
- ❌ A policy template or standard document ready for adoption (policies must reflect organizational context)
- ❌ A guarantee that documented policies alone satisfy control requirements (implementation and enforcement required)
- ❌ A replacement for legal review of regulatory compliance obligations

**Critical Dependencies:**
- Policy & Standards capability depends on Program Governance (provides approval and oversight structure), VM Roles & Responsibilities (defines who implements policies), and Risk Appetite & Tolerance Definitions (establishes risk thresholds embedded in policies). Without these, policies lack enforcement mechanisms and organizational alignment.

**Common Misinterpretation:**
- Organizations often confuse "having a policy document" with policy maturity. A beautifully written policy that nobody follows or enforces represents Level 1-2 maturity regardless of documentation quality. Maturity is measured by enforcement, embedding into workflows, and continuous improvement—not document completeness.

**Important Notes:**
- Policies must reflect actual organizational practice—documenting aspirational requirements you cannot enforce creates audit risk when reality doesn't match policy
- Policy effectiveness depends on communication, training, and enforcement mechanisms beyond the document itself
- Different regulatory environments may require specific policy elements or review frequencies not universally applicable

---

**Document Control:**  
**Version:** 2.0.0 | **Framework Versions:** NIST CSF 2.0 (2024), NIST 800-53 Rev 5 (2020), CIS v8 (2021), ISO 27001:2022  
**Last Reviewed:** 2026-01-30 | **Next Review:** 2027-01-30  
**Feedback:** Contact ZenzizenSec for framework mapping corrections or clarifications

© 2026 ZenzizenSec Inc. All rights reserved.
