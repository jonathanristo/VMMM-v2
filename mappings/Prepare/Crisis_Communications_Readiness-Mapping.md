# Capability Mapping — Crisis Communications Readiness

**Model:** VMMM v2.0.0  
**Domain:** Respond • **Tier:** Foundational • **Updated:** 2026-01-31

> **Who This Mapping Is For:**
> * Incident response teams preparing stakeholder communication plans for vulnerability-related security incidents requiring coordinated external messaging
> * Communications teams establishing crisis communication procedures ensuring consistent, accurate messaging when vulnerabilities exploited or disclosed
> * Security leadership defining escalation criteria and approval authorities for public vulnerability disclosures, customer notifications, and regulatory reporting
> * GRC teams demonstrating incident communication readiness to auditors showing documented procedures for notifying affected parties and regulatory bodies

---

## Executive Summary

Crisis Communications Readiness capability ensures organization prepared to communicate effectively about vulnerability-related security incidents. Mature organizations have documented communication plans defining: what types of incidents require external communication, who has authority to approve messaging, which stakeholders receive notifications (customers, partners, regulators, media), message templates for common scenarios, communication channels and timing. This capability strengthens evidence for incident response (IR-4, IR-6) in NIST 800-53, response communications (RS.CO) in CSF 2.0, and incident management (A.5.26) in ISO 27001. Higher maturity enables organizations to demonstrate communication procedures tested through tabletop exercises, message templates customized for different stakeholder groups, and post-incident communication reviews improving future response clarity and stakeholder confidence.

**Key Frameworks:** NIST 800-53 (IR-4, IR-6, AU-6) • CSF 2.0 (RS.CO) • CIS Control 17.9 • ISO 27001 (A.5.26, A.5.27)  
**Primary Evidence:** Crisis communication plan documentation, stakeholder notification procedures, message templates, escalation criteria, tabletop exercise results, post-incident communication reviews  
**Cross-Domain Dependencies:** Program Governance, Roles & Responsibilities, Incident Response Integration

---

## Capability Overview

Many organizations operate vulnerability management without considering how to communicate about security incidents resulting from unpatched vulnerabilities. Critical vulnerability exploited in production system affecting customer data. IT discovers breach Friday evening. Security team contains incident over weekend. Monday morning: executive leadership asks "What do we tell customers?" No documented plan exists. Marketing says wait until investigation complete. Legal says notify immediately to comply with regulations. Customer success says customers already asking questions on social media. Executive team debates messaging in crisis mode creating inconsistent information shared with different groups.

Without crisis communications readiness, systematic failures emerge. Customer notification delayed because unclear who has authority to approve disclosure—each stakeholder believes another should decide. Message crafted hastily without considering regulatory requirements leading to inadequate disclosure triggering compliance violations. Different teams communicate contradicting information: security says vulnerability patched, support team tells customers investigation ongoing, executives tell board incident minor. Media publishes story based on social media speculation because organization provided no official statement. Regulatory body learns about breach from news article not company notification.

Mature Crisis Communications Readiness establishes procedures before crisis occurs. Communication plan documents: incident severity thresholds triggering external communication (Critical vulnerability exploited affecting customer data requires notification, routine patching does not), stakeholder groups requiring notification (customers, partners, regulators, employees, media) with contact methods and timing, approval authorities for each stakeholder group (CISO approves customer notifications, legal approves regulatory filings, CEO approves media statements), message templates for common scenarios providing starting point for incident-specific customization.

Escalation criteria explicitly defined preventing ambiguity about when external communication required. Communication roles documented: incident commander coordinates response, communications lead drafts messages, legal reviews for compliance, executive sponsor approves disclosure. Message templates address different stakeholder needs: customers receive actionable guidance (what happened, what data affected, what actions required), regulators receive compliance-focused details (discovery date, affected records, remediation timeline), media receives public-facing summary (incident overview, customer impact, company response). At highest maturity, communication procedures tested through tabletop exercises identifying gaps before real crisis, post-incident reviews analyze communication effectiveness improving templates and procedures, stakeholder feedback incorporated into plan updates.

---

## Maturity-Based Evidence Progression

| Maturity Level | Evidence Characteristics |
|----------------|-------------------------|
| **Level 1** | No documented crisis communication plan. When vulnerability-related incident occurs requiring stakeholder notification, organization debates what to communicate and who decides in crisis mode. Evidence: None—communication procedures nonexistent. |
| **Level 2** | Informal understanding that "someone handles communications" but no documented plan. When incident occurs, security team emails IT leadership who forwards to communications team creating ad hoc response. Evidence: Email threads showing improvised communication coordination, inconsistent messaging to different stakeholders. |
| **Level 3** | Documented crisis communication plan defining: incident severity thresholds requiring external communication, stakeholder groups (customers, partners, regulators), approval authorities, basic message templates. Communication roles assigned (incident commander, communications lead, legal reviewer, executive sponsor). Evidence: Crisis communication plan document, stakeholder notification procedures, message templates, role assignments, escalation criteria. |
| **Level 4** | Communication procedures tested through tabletop exercises identifying gaps and improving readiness. Message templates customized for different stakeholder groups with specific regulatory compliance language. Communication plan reviewed and updated annually or after major incidents. Post-incident reviews include communication effectiveness assessment. Evidence: Tabletop exercise reports, customized message templates, annual review documentation, post-incident communication analysis. |
| **Level 5** | Continuous communication readiness optimization through stakeholder feedback surveys, automated notification systems reducing manual effort, measured communication metrics (time to first notification, stakeholder satisfaction, regulatory compliance), plan updates triggered by regulatory changes or organizational transformation. Evidence: Stakeholder feedback analysis, automated notification system configurations, communication effectiveness metrics, continuous improvement documentation. |

---

## Framework Alignment Overview

| Framework | Primary References | Alignment Summary |
|-----------|-------------------|-------------------|
| **NIST Cybersecurity Framework 2.0** | RS.CO | Demonstrates response communications coordinating with stakeholders during incident response activities |
| **NIST SP 800-53 Rev. 5** | IR-4, IR-6, AU-6 | Strengthens incident handling, incident reporting, and audit review requiring stakeholder communication procedures |
| **CIS Critical Security Controls v8** | Control 17.9 | Supports incident response plan establishment including communication procedures |
| **ISO/IEC 27001:2022** | A.5.26, A.5.27 | Demonstrates incident management response and learning from incidents including stakeholder communication |

---

## NIST SP 800-53 Rev. 5 Alignment

**Relevant Control Families:** IR – Incident Response, AU – Audit and Accountability

This capability provides documented communication procedures enabling organization to notify stakeholders systematically when vulnerability-related incidents occur rather than improvising crisis response.

**Key Exemplar Controls:**

| Control | How This Capability Strengthens Evidence |
|---------|------------------------------------------|
| **IR-4 – Incident Handling** | Core capability—demonstrates incident handling procedures include stakeholder notification protocols ensuring affected parties informed systematically according to documented plan rather than ad hoc crisis communication |
| **IR-6 – Incident Reporting** | Shows incident reporting mechanisms extend beyond internal escalation to external stakeholder notification when incidents meet defined severity thresholds requiring customer, partner, or regulatory communication |
| **AU-6 – Audit Review, Analysis, and Reporting** | Provides audit reporting framework including procedures for communicating security findings to appropriate stakeholders when audit identifies exploited vulnerabilities requiring disclosure |

> Additional controls strengthened include SI-5 (Security Alerts) for disseminating vulnerability alerts to stakeholders and PM-15 (Security and Privacy Groups) showing communication coordination with external entities.

---

## NIST CSF 2.0 Alignment

**Relevant Function:** Respond (RS)

Mature crisis communications capability supports response function by ensuring stakeholders receive timely, accurate information when vulnerability-related incidents occur.

**Key Exemplar Subcategory:**

| Subcategory | How This Capability Strengthens Evidence |
|-------------|------------------------------------------|
| **RS.CO – Response Communications** | Core capability—demonstrates organization coordinates response activities with stakeholders including customers, suppliers, and regulatory bodies through documented communication procedures ensuring consistent messaging when vulnerability incidents occur |

---

## CIS Critical Security Controls v8 Alignment

**Relevant Control:** Control 17 – Incident Response Management

CIS Control 17.9 requires establishing and maintaining incident response plan. Crisis Communications Readiness provides stakeholder communication component of comprehensive incident response.

**Key Exemplar Safeguard:**

| Safeguard | IG Level | How This Capability Strengthens Evidence |
|-----------|----------|------------------------------------------|
| **17.9 – Establish and Maintain Security Incident Response Plan** | IG1 | Demonstrates incident response plan includes documented stakeholder communication procedures ensuring affected parties notified systematically when vulnerability-related security incidents occur requiring external disclosure |

> This capability enables communication procedures to be integral component of incident response plan rather than afterthought improvised during crisis.

---

## ISO/IEC 27001:2022 Alignment

**Relevant Control Categories:** Organizational Controls (5.x)

ISO 27001 requires incident management and learning from incidents. Crisis Communications Readiness capability demonstrates organization prepared to communicate about vulnerability-related incidents to affected stakeholders.

**Key Exemplar Controls:**

| Control | How This Capability Strengthens Evidence |
|---------|------------------------------------------|
| **A.5.26 – Response to Information Security Incidents** | Core capability—shows incident response procedures include documented stakeholder communication protocols ensuring customers, partners, and regulators notified systematically when vulnerability incidents meet defined disclosure thresholds |
| **A.5.27 – Learning from Information Security Incidents** | Demonstrates post-incident reviews analyze communication effectiveness incorporating stakeholder feedback to improve future crisis communication procedures and message clarity |

> Additional controls (A.5.24 Information Security Event Management, A.5.7 Threat Intelligence) benefit from communication procedures enabling threat intelligence sharing and event escalation to external parties.

---

## Maturity Investment Guidance

**Foundational Investment (Levels 1–2):**  
Document basic crisis communication plan defining: incident severity thresholds requiring stakeholder notification (Critical vulnerability exploited affecting customer data triggers communication), stakeholder groups (customers, partners, regulators), approval authorities (CISO approves customer notifications, legal approves regulatory filings), basic message templates providing starting point for incident-specific customization. Assign communication roles (incident commander, communications lead, legal reviewer). **ROI:** Eliminates crisis mode debates about what to communicate and who decides, provides starting templates reducing time to first notification, ensures regulatory compliance through documented legal review, prevents inconsistent messaging to different stakeholder groups by establishing approval authorities.

**Enhanced Investment (Levels 3–4):**  
Test communication procedures through tabletop exercises identifying gaps before real crisis, customize message templates for specific stakeholder groups with regulatory compliance language, establish annual review process updating plan based on regulatory changes or organizational transformation, conduct post-incident communication reviews analyzing effectiveness and incorporating improvements. Implement communication training for incident response team. **ROI:** Tabletop exercises identify procedural gaps reducing confusion during actual incidents, customized templates improve stakeholder-specific messaging clarity, annual reviews maintain plan relevance as organization evolves, post-incident analysis drives continuous improvement in communication effectiveness.

**Strategic Investment (Level 5):**  
Implement automated notification systems reducing manual effort during crisis, measure communication effectiveness through stakeholder feedback surveys and metrics (time to first notification, stakeholder satisfaction scores, regulatory compliance achievement), establish continuous improvement process updating plan based on stakeholder feedback and regulatory changes, integrate communication procedures with incident response workflows enabling seamless notification. **ROI:** Automated systems reduce time to first notification improving stakeholder confidence, measured metrics demonstrate communication program effectiveness to leadership, stakeholder feedback drives targeted improvements, integrated workflows eliminate coordination friction during crisis response.

---

## Practical Applications

This capability mapping may be used to:

- **Crisis Communication Planning:** Develop comprehensive stakeholder notification procedures for vulnerability-related incidents defining severity thresholds, stakeholder groups, approval authorities, and message templates
- **Tabletop Exercise Design:** Create realistic vulnerability disclosure scenarios testing communication procedures and identifying gaps before actual crisis
- **Regulatory Compliance:** Ensure notification procedures address regulatory requirements for breach disclosure, data protection violations, and mandatory reporting timelines
- **Message Template Development:** Create stakeholder-specific templates providing starting point for incident communication while allowing customization for specific circumstances
- **Stakeholder Management:** Define communication channels, timing, and content appropriate for different audiences (customers, partners, regulators, media, employees)
- **Post-Incident Analysis:** Review communication effectiveness after vulnerability incidents identifying improvement opportunities in messaging clarity, timing, and stakeholder satisfaction

---

## Boundaries & Limitations

**What This Mapping Is NOT:**
- ❌ A replacement for technical incident response procedures (communication complements not replaces containment and remediation)
- ❌ A legal opinion on specific disclosure requirements (organizations must consult legal counsel for compliance advice)
- ❌ A determination that specific communication timing appropriate for all incidents (must reflect incident severity and regulatory requirements)
- ❌ A guarantee that communication eliminates all stakeholder concerns (transparency is goal, not universal satisfaction)

**Critical Dependencies:**
- Crisis Communications Readiness depends on Program Governance (provides approval authorities for stakeholder notifications), Roles & Responsibilities (defines who performs communication activities), and Incident Response Integration (triggers communication procedures when incidents occur). Without these, unclear who has authority to approve disclosure, who executes communication activities, and when communication procedures should activate during incident response.

**Common Misinterpretation:**
- Organizations often confuse "having PR team" with "crisis communication readiness." Existence of communications department does not automatically mean documented procedures exist for vulnerability-related incident disclosure. Mature capability requires: documented severity thresholds, stakeholder notification procedures, approval authorities, message templates, and tested communication workflows. General PR capabilities provide foundation but vulnerability-specific procedures require explicit definition.

**Important Notes:**
- Regulatory requirements vary by jurisdiction and industry—communication plan must address applicable disclosure obligations for organization's specific regulatory environment
- Legal review essential before implementing crisis communication procedures to ensure regulatory compliance and minimize legal exposure
- Communication timing critical—delayed notification can increase regulatory penalties and stakeholder distrust, while premature disclosure may provide incomplete or inaccurate information requiring correction
- Cultural and linguistic considerations important for organizations with international stakeholder populations—message templates may require localization beyond simple translation

---

**Document Control:**  
**Version:** 2.0.0 | **Framework Versions:** NIST CSF 2.0 (2024), NIST 800-53 Rev 5 (2020), CIS v8 (2021), ISO 27001:2022  
**Last Reviewed:** 2026-01-31 | **Next Review:** 2027-01-31  
**Feedback:** Contact ZenzizenSec for framework mapping corrections or clarifications

© 2026 ZenzizenSec Inc. All rights reserved.
