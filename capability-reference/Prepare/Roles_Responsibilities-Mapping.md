# Capability Mapping — Roles & Responsibilities

**Model:** VMMM v2.0.0  
**Domain:** Prepare • **Tier:** Foundational • **Updated:** 2026-01-31

> **Who This Mapping Is For:**
> * Security leadership defining accountability frameworks for vulnerability management activities preventing organizational gaps
> * Program managers clarifying who performs scanning, remediation, validation, and escalation activities across distributed teams
> * Operational teams understanding their specific VM responsibilities and handoff points to other functions
> * GRC teams demonstrating organizational accountability to auditors showing clear ownership for security activities

---

## Executive Summary

Roles & Responsibilities capability establishes clear accountability and ownership for vulnerability management activities across the organization. Mature organizations document who performs vulnerability scanning, who remediates findings, who validates fixes, who escalates issues, and who accepts risk. This capability strengthens evidence for personnel security (PS family) and contingency planning coordination (CP-2) in NIST 800-53, organizational context (GV.OC) in CSF 2.0, and segregation of duties (A.5.3) in ISO 27001. Higher maturity enables organizations to demonstrate that VM operates with clear accountability rather than ambiguous "everyone's responsible" approaches, with documented decision rights preventing finger-pointing when vulnerabilities remain unaddressed, and systematic onboarding ensuring new team members understand their VM responsibilities immediately.

**Key Frameworks:** NIST 800-53 (PS-2, CP-2) • CSF 2.0 (GV.OC, GV.RR) • CIS Control 7.1 • ISO 27001 (A.5.3, A.6.8)  
**Primary Evidence:** RACI or responsibility assignment matrix, role descriptions with VM responsibilities, documented decision authority boundaries, segregation of duties documentation, onboarding materials with role-specific VM training  
**Cross-Domain Dependencies:** Program Governance, Policy & Standards, Asset Inventory & Classification

---

## Capability Overview

Many organizations operate vulnerability management without clear accountability. Everyone assumes someone else handles VM activities. Development teams believe infrastructure handles patching. Infrastructure teams assume applications patch themselves. Security team scans and reports but lacks authority to enforce remediation. When critical vulnerabilities remain unpatched for months, finger-pointing begins—each team claims another team responsible. Nobody owns the outcome.

Without documented roles, organizational gaps emerge. Scanning performed inconsistently because unclear who manages scanners. Remediation delayed because system owners don't recognize patching as their responsibility. Validation skipped because nobody designated to confirm fixes effective. Escalation paths broken because unclear who has authority to elevate unresolved vulnerabilities. New employees join and nobody explains their VM responsibilities. Contractors work on systems without understanding their vulnerability management obligations.

Mature Roles & Responsibilities capability documents who does what across VM lifecycle. RACI matrix or equivalent defines: who scans systems (Responsible), who approves scan schedules (Accountable), who receives scan results (Consulted), who is notified of critical findings (Informed). Role descriptions include VM-specific responsibilities: "System owners remediate vulnerabilities within SLA timeframes," "Security team validates remediation effectiveness," "CISO approves risk acceptance decisions exceeding tolerance thresholds." Decision authority boundaries documented: security team cannot approve exceptions without system owner input, system owners cannot delay Critical patches beyond 30 days without CISO approval, third parties must coordinate patching with internal teams.

At highest maturity, role definitions evolve systematically. Post-incident reviews identify responsibility gaps and drive role updates. Organizational changes (mergers, cloud migrations, DevOps adoption) trigger responsibility reassessment. Role effectiveness measured through accountability metrics: percentage of vulnerabilities remediated by designated owners within SLA, escalation timeliness, validation completion rates. Onboarding includes role-specific VM training ensuring new hires understand their responsibilities immediately.

---

## Maturity-Based Evidence Progression

| Maturity Level | Evidence Characteristics |
|----------------|-------------------------|
| **Level 1** | No documented roles or responsibilities. VM activities performed ad hoc by whoever notices issues. When vulnerabilities unaddressed, unclear who accountable. Evidence: None—organizational accountability undefined. |
| **Level 2** | Informal understanding exists (e.g., "security team handles VM") but not documented. Responsibilities communicated verbally or through tribal knowledge. Different teams have conflicting understanding of who does what. When gaps emerge, no documentation to resolve disputes. Evidence: Email threads discussing responsibilities, conflicting verbal accounts. |
| **Level 3** | Documented responsibility matrix (RACI or equivalent) defining roles across VM activities. Role descriptions include VM-specific responsibilities. Decision authority boundaries documented (who can approve exceptions, escalate issues, accept risk). Communicated to relevant teams. Segregation of duties implemented for conflicting responsibilities. Evidence: Approved RACI matrix, role descriptions with VM sections, authority documentation, communication records, segregation documentation. |
| **Level 4** | Roles embedded in operational workflows: automated systems route tasks to designated owners, escalation procedures reference specific roles, access controls align with documented responsibilities. Role assignments reviewed periodically (annual minimum) and updated based on organizational changes. Onboarding includes role-specific VM training. Responsibility overlaps identified and resolved systematically. Evidence: Workflow configurations enforcing role assignments, periodic review records, onboarding materials with VM training, overlap resolution documentation. |
| **Level 5** | Continuous role optimization through feedback mechanisms: post-incident reviews identify responsibility gaps driving role updates, organizational transformation (M&A, cloud adoption) triggers systematic reassessment, role effectiveness measured (accountability metrics, escalation patterns, gap frequency). Lessons learned from failures incorporated into role definitions. Evidence: Role evolution history tied to specific triggers, effectiveness metrics, incident-driven improvements, systematic learning examples. |

---

## Framework Alignment Overview

| Framework | Primary References | Alignment Summary |
|-----------|-------------------|-------------------|
| **NIST Cybersecurity Framework 2.0** | GV.OC, GV.RR | Demonstrates organizational context with defined roles and responsibilities plus supply chain security roles |
| **NIST SP 800-53 Rev. 5** | PS-2, CP-2, AT-2 | Strengthens position descriptions, contingency planning coordination, and role-based training requirements |
| **CIS Critical Security Controls v8** | Control 7.1 | Supports documented VM process by defining who performs vulnerability management activities |
| **ISO/IEC 27001:2022** | A.5.3, A.6.8 | Demonstrates segregation of duties and clear asset management responsibilities |

---

## NIST SP 800-53 Rev. 5 Alignment

**Relevant Control Families:** PS – Personnel Security, CP – Contingency Planning, AT – Awareness and Training

This capability provides the accountability framework required to implement VM activities with clear ownership preventing organizational gaps and enabling coordinated response.

**Key Exemplar Controls:**

| Control | How This Capability Strengthens Evidence |
|---------|------------------------------------------|
| **PS-2 – Position Risk Designation** | Core capability—documents VM responsibilities in position descriptions ensuring personnel understand their vulnerability management obligations as part of role requirements |
| **CP-2 – Contingency Plan** | Demonstrates contingency planning roles and responsibilities including who performs vulnerability management during contingency operations and how VM responsibilities shift during incidents |
| **AT-2 – Literacy Training and Awareness** | Provides foundation for role-based VM training by documenting which roles require which VM competencies enabling targeted training programs aligned to responsibilities |

> Additional controls strengthened include AT-3 (Role-Based Training), AC-5 (Separation of Duties), and RA-3 (Risk Assessment) through documented accountability frameworks.

---

## NIST CSF 2.0 Alignment

**Relevant Functions:** Govern (GV)

Mature roles and responsibilities capability directly supports organizational governance by defining accountability structures for cybersecurity risk management including VM activities.

**Key Exemplar Subcategories:**

| Subcategory | How This Capability Strengthens Evidence |
|-------------|------------------------------------------|
| **GV.OC – Organizational Context** | Demonstrates organizational cybersecurity risk management responsibilities are established and communicated including clear VM role definitions aligned to business functions |
| **GV.RR – Roles, Responsibilities, and Authorities** | Core capability—shows cybersecurity supply chain risk management roles and responsibilities established and communicated including third-party and vendor VM obligations |

---

## CIS Critical Security Controls v8 Alignment

**Relevant Control:** Control 7 – Continuous Vulnerability Management

CIS Control 7.1 requires establishing and maintaining VM process. Roles & Responsibilities provides the organizational accountability enabling systematic process execution.

**Key Exemplar Safeguard:**

| Safeguard | IG Level | How This Capability Strengthens Evidence |
|-----------|----------|------------------------------------------|
| **7.1 – Establish and Maintain a Vulnerability Management Process** | IG1 | Demonstrates VM process includes documented roles and responsibilities defining who performs scanning, remediation, validation, and escalation activities |

> This capability enables all Control 7 safeguards by providing accountability framework within which vulnerability management activities operate with clear ownership.

---

## ISO/IEC 27001:2022 Alignment

**Relevant Control Categories:** Organizational Controls (5.x), People Controls (6.x)

ISO 27001 requires organizational accountability and segregation of duties. Roles & Responsibilities capability demonstrates systematic approach to defining and communicating security responsibilities.

**Key Exemplar Controls:**

| Control | How This Capability Strengthens Evidence |
|---------|------------------------------------------|
| **A.5.3 – Segregation of Duties** | Core capability—demonstrates conflicting duties separated with documented responsibilities preventing single individual from compromising security through VM activities |
| **A.6.8 – Information Security Event Management** | Shows information security event management roles and responsibilities established including who handles vulnerability-related security events and escalates issues |

> Additional controls (A.5.1 Information Security Policies, A.5.2 Information Security Roles and Responsibilities) directly benefit from documented VM accountability framework.

---

## Maturity Investment Guidance

**Foundational Investment (Levels 1–2):**  
Document basic responsibility matrix (RACI or equivalent) defining who scans, remediates, validates, and escalates across VM lifecycle. Update role descriptions to include VM-specific responsibilities aligned to documented matrix. Communicate to relevant teams. **ROI:** Eliminates finger-pointing when vulnerabilities unaddressed by establishing clear accountability, reduces organizational gaps through explicit ownership, enables escalation by documenting decision authority, improves onboarding by incorporating VM responsibilities into role definitions.

**Enhanced Investment (Levels 3–4):**  
Embed role assignments into operational workflows: configure systems to route tasks to designated owners automatically, align access controls with documented responsibilities, implement segregation of duties preventing conflicts. Establish periodic role review process (annual minimum) updating assignments based on organizational changes. Develop role-specific VM training materials for onboarding. **ROI:** Automated enforcement prevents responsibility confusion, systematic reviews keep roles current during organizational evolution, standardized training ensures consistent understanding, segregation prevents conflicts enabling audit compliance.

**Strategic Investment (Level 5):**  
Implement continuous role optimization: conduct post-incident reviews identifying responsibility gaps driving role updates, trigger systematic reassessment during organizational transformation (M&A, cloud migration, DevOps adoption), measure role effectiveness (accountability metrics, escalation timeliness, gap frequency). Incorporate lessons learned from VM failures into role definitions. **ROI:** Data-driven role evolution ensures accountability framework remains effective as organization and threats change, measurable effectiveness demonstrates framework value, systematic learning prevents responsibility gaps from recurring, continuous improvement reduces incidents caused by unclear ownership.

---

## Practical Applications

This capability mapping may be used to:

- **Accountability Framework Design:** Guide creation of VM responsibility matrix defining who performs each activity across vulnerability lifecycle preventing organizational gaps
- **Gap Identification:** Analyze current responsibilities identifying activities with unclear ownership or conflicting assignments requiring resolution
- **Onboarding Acceleration:** Develop role-specific VM training materials ensuring new employees understand their responsibilities immediately
- **Segregation of Duties:** Establish separation between scanning, remediation validation, and risk acceptance preventing conflicts of interest
- **Third-Party Management:** Define vendor and contractor VM responsibilities ensuring external parties understand their vulnerability management obligations
- **Organizational Change:** Reassess role assignments during mergers, cloud migrations, or DevOps adoption maintaining clear accountability through transformation

---

## Boundaries & Limitations

**What This Mapping Is NOT:**
- ❌ An organizational chart showing reporting relationships (roles focus on activities not hierarchy)
- ❌ A determination of specific role assignments appropriate for any organization (assignments must reflect organizational structure)
- ❌ A guarantee that documented roles eliminate all VM gaps (execution still required)
- ❌ A replacement for Program Governance capability (roles define "who does what" while governance provides authority)

**Critical Dependencies:**
- Roles & Responsibilities depends on Program Governance (provides oversight authority enforcing accountability), Policy & Standards (defines requirements roles must fulfill), and Asset Inventory & Classification (determines which assets each role manages). Without these, roles lack authority to enforce responsibilities, unclear what activities roles should perform, and ambiguous which systems fall under each role's accountability.

**Common Misinterpretation:**
- Organizations often confuse "having job titles" with "defining responsibilities." A team called "Vulnerability Management Team" does not automatically clarify who scans which systems, who validates remediation, or who approves exceptions. Mature capability requires explicit documentation of activities each role performs, decision authority boundaries, and handoff points between roles.

**Important Notes:**
- Role definitions must reflect actual organizational structure—documenting responsibilities for "Security Operations Center" when organization lacks SOC creates confusion not clarity
- Segregation of duties requires sufficient organizational capacity—very small organizations may need documented compensating controls when single individual must perform conflicting activities
- Third-party and vendor responsibilities must be explicitly documented—assuming contractors understand VM obligations without documentation creates gaps when external personnel rotate
- Role assignments should be reviewed when organizational changes occur (new leadership, restructuring, cloud adoption)—static role documentation becomes outdated as organization evolves

---

**Document Control:**  
**Version:** 2.0.0 | **Framework Versions:** NIST CSF 2.0 (2024), NIST 800-53 Rev 5 (2020), CIS v8 (2021), ISO 27001:2022  
**Last Reviewed:** 2026-01-31 | **Next Review:** 2027-01-31  
**Feedback:** Contact ZenzizenSec for framework mapping corrections or clarifications

© 2026 ZenzizenSec Inc. All rights reserved.
