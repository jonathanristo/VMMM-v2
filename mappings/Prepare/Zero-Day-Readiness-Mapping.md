# Capability Mapping — Zero-Day Readiness

**Model:** VMMM v2.0.0  
**Domain:** Prepare • **Tier:** Foundational • **Updated:** 2026-01-30

> **Who This Mapping Is For:**
> * Incident response teams coordinating rapid assessment, containment, and remediation when zero-day vulnerabilities or critical threats emerge
> * CISOs and security leadership managing crisis communication with executives, boards, customers, and regulators under intense time pressure
> * IT operations teams executing emergency patches, workarounds, and mitigations on production systems with minimal testing time
> * Business and executive leadership making risk decisions about service continuity, customer notifications, and public disclosure during active exploitation

---

## Executive Summary

Zero-Day Readiness determines how effectively organizations respond when vulnerabilities emerge with active exploitation, no patches available, and compressed decision timelines measured in hours not days. Unlike routine vulnerability management, zero-day response requires crisis coordination across security, IT, business, legal, and communications teams under extreme pressure. Mature organizations maintain crisis playbooks, conduct regular simulations, establish clear decision authority, and practice coordinated response before crises occur. Without mature zero-day readiness, organizations discover response gaps during actual incidents—unclear ownership, missing contact lists, untested mitigations, decision paralysis. This capability strengthens evidence for incident response (IR-4, IR-8), contingency planning (CP-2), and preparedness across NIST 800-53, CSF 2.0, and ISO 27001, transforming zero-day events from organizational chaos into coordinated, measured crisis response.

**Key Frameworks:** NIST 800-53 (IR-4, IR-8, CP-2) • CSF 2.0 (RS.MA, RS.AN, RS.CO) • ISO 27001 (A.5.26, A.5.24)  
**Primary Evidence:** Crisis response playbooks, simulation exercise records, communication templates, decision authority documentation, post-incident reviews with improvements  
**Cross-Domain Dependencies:** Crisis Communication Readiness (stakeholder notification), Compensating Controls (emergency mitigations), Threat Intelligence (zero-day detection and assessment)

---

## Capability Overview

Zero-day vulnerabilities expose the difference between documented processes and organizational muscle memory. Log4Shell, MOVEit, Sunburst, EternalBlue—these weren't managed through routine VM processes. They hit Friday afternoons, required emergency executive meetings, forced patch-or-shutdown decisions with incomplete information, and demanded coordination across teams who rarely worked together under normal conditions. Organizations without zero-day readiness discovered critical gaps in real-time: nobody knew who makes the "take production offline" decision, communication templates didn't exist, compensating controls were untested, and teams burned 12 hours arguing about response while attackers exploited systems.

Mature Zero-Day Readiness means practicing crisis before crisis arrives. Playbooks document: Who gets called? Who has decision authority? What communication templates exist? What compensating controls can be deployed quickly? Where's the emergency change process? Teams practice through tabletop exercises and simulations, discovering gaps in safe environments. Decision trees pre-define: At what exploitation threshold do we notify customers? When do we escalate to CEO/board? What constitutes "take offline" criteria? Crisis communication templates exist for executives, customers, regulators, and media. Post-incident reviews capture lessons, and improvements get integrated into next drill. When a real zero-day hits, mature organizations activate practiced playbooks rather than improvising under pressure. Response times measure in hours instead of days. Decisions get made by designated authorities instead of consensus paralysis. Stakeholders receive consistent messages instead of conflicting communications. The zero-day still causes disruption, but coordinated response minimizes damage and demonstrates organizational resilience.

---

## Maturity-Based Evidence Progression

| Maturity Level | Evidence Characteristics |
|----------------|-------------------------|
| **Level 1** | No formal zero-day response process exists. Teams react inconsistently when critical vulnerabilities emerge. Limited coordination between security, IT, business. No documentation of who should do what. Response depends entirely on individual initiative and tribal knowledge. Evidence: None—no playbooks, templates, or documented procedures exist. |
| **Level 2** | Ad hoc procedures exist but response depends on individual heroics. Some teams have informal "call these people" lists and basic runbooks. Response not repeatable—different people, different approaches each time. Ownership unclear during crises. Post-incident reviews happen sometimes but improvements rarely implemented. Evidence: Personal notes, informal contact lists, scattered email threads showing uncoordinated response, inconsistent documentation across incidents. |
| **Level 3** | Defined crisis response process documented: communication channels established, designated incident leads assigned, response steps documented. Roles and responsibilities clear (who assesses, who decides, who implements, who communicates). Emergency change process defined. Basic playbook exists covering detection, assessment, containment, remediation, communication. Evidence: Documented crisis response plan with assigned roles, contact lists, communication templates, emergency change procedures, evidence of plan communication to relevant teams. |
| **Level 4** | Crisis readiness supported by detailed playbooks covering various scenarios (internet-facing vs. internal, exploitation observed vs. theoretical, patch available vs. mitigation-only). Pre-established workflows integrate with ticketing, change management, communication systems. Regular crisis simulations (tabletop exercises, drills) involving cross-functional teams. Response timelines measured (time-to-assessment, time-to-containment, time-to-remediation). Improvements tracked from exercises and actual incidents. Evidence: Scenario-specific playbooks, simulation exercise records with participant lists and findings, response timeline metrics, documented improvements from lessons learned, integration configurations showing automated workflows. |
| **Level 5** | Cross-functional crisis response framework operates with real-time threat intelligence feeding automated detection and assessment. Workflow automation accelerates response (automated asset identification, pre-approved emergency changes, auto-deployment of tested compensating controls). Defined escalation paths with decision authority at each level. Continuous improvement: every exercise and incident feeds lessons learned database, playbooks automatically updated, response metrics tracked showing improvement over time. Strategic integration: zero-day response performance informs risk posture discussions, investment decisions, architecture choices. Evidence: Automated threat intelligence integration, response automation configurations, metrics dashboards showing response time improvements, lessons learned database with implemented changes, executive briefings showing zero-day readiness as strategic capability. |

---

## Framework Alignment Overview

| Framework | Primary References | Alignment Summary |
|-----------|-------------------|-------------------|
| **NIST Cybersecurity Framework 2.0** | RS.MA, RS.AN, RS.CO | Supports incident management, analysis, and communication activities during high-pressure response scenarios |
| **NIST SP 800-53 Rev. 5** | IR-4, IR-8, CP-2 | Strengthens incident handling, incident response plan, and contingency planning for crisis-level events |
| **CIS Critical Security Controls v8** | Control 17 | Supports incident response management including planning, testing, and coordination |
| **ISO/IEC 27001:2022** | A.5.26, A.5.24 | Demonstrates incident management planning and management review of information security |

---

## NIST SP 800-53 Rev. 5 Alignment

**Relevant Control Families:** IR – Incident Response, CP – Contingency Planning

Zero-day events represent highest-pressure incident response scenarios requiring pre-planned procedures and practiced coordination. Maturity demonstrates organizational preparedness for crisis-level security events.

**Key Exemplar Controls:**

| Control | How This Capability Strengthens Evidence |
|---------|------------------------------------------|
| **IR-4 – Incident Handling** | Demonstrates incident handling capability under most demanding conditions—zero-days require rapid coordination, decision-making under uncertainty, and cross-functional response that tests incident handling maturity |
| **IR-8 – Incident Response Plan** | Provides documented incident response plan specifically addressing high-criticality, time-sensitive scenarios with pre-defined roles, procedures, communication protocols, and decision criteria |
| **CP-2 – Contingency Plan** | Shows contingency planning addresses scenarios requiring rapid response including potential service disruption, emergency changes, and business continuity decisions during active exploitation |

> Additional controls strengthened include IR-3 (Incident Response Testing through simulations), IR-6 (Incident Reporting for stakeholder notification), and IR-10 (Integrated Information Security Analysis Team for cross-functional coordination).

---

## NIST CSF 2.0 Alignment

**Relevant Function:** Respond (RS)

Zero-day readiness directly supports response function's most demanding scenarios—events requiring analysis, mitigation, and communication under extreme time pressure with incomplete information.

**Key Exemplar Subcategories:**

| Subcategory | How This Capability Strengthens Evidence |
|-------------|------------------------------------------|
| **RS.MA – Incident Management** | Demonstrates incident management processes function effectively under crisis conditions with clear roles, established procedures, and practiced coordination |
| **RS.AN – Analysis** | Shows analytical capability to rapidly assess zero-day impact, determine affected assets, evaluate exploitation risk, and recommend response actions under time pressure |
| **RS.CO – Communications** | Provides communication processes for crisis scenarios including stakeholder notification, status updates, and coordinated messaging to executives, customers, and regulators |

---

## CIS Critical Security Controls v8 Alignment

**Relevant Control:** Control 17 – Incident Response Management

CIS Control 17 requires incident response planning and testing. Zero-day readiness represents highest-maturity implementation addressing most demanding incident scenarios.

**Key Exemplar Safeguards:**

| Safeguard | IG Level | How This Capability Strengthens Evidence |
|-----------|----------|------------------------------------------|
| **17.1 – Designate Personnel to Manage Incident Handling** | IG1 | Directly implements personnel designation for incident management with specific focus on crisis-level events requiring clear authority and rapid decision-making |
| **17.9 – Conduct Periodic Incident Response Exercises** | IG2 | Demonstrates regular testing of incident response capabilities through simulations specifically addressing zero-day and critical vulnerability scenarios |

> This capability also supports 17.3 (Incident Response Communication), 17.4 (Incident Response Procedures), and demonstrates maturity across entire Control 17.

---

## ISO/IEC 27001:2022 Alignment

**Relevant Control Category:** Organizational Controls (5.x)

ISO 27001 requires incident management planning and management oversight. Zero-day readiness demonstrates preparedness for highest-impact incident scenarios requiring coordinated organizational response.

**Key Exemplar Controls:**

| Control | How This Capability Strengthens Evidence |
|---------|------------------------------------------|
| **A.5.26 – Response to Information Security Incidents** | Core capability—demonstrates incident response planning addresses crisis-level scenarios with documented procedures, assigned responsibilities, and regular testing through simulations |
| **A.5.24 – Information Security Incident Management Planning and Preparation** | Shows planning and preparation specifically addresses time-critical, high-impact scenarios requiring cross-functional coordination and rapid decision-making |

> Zero-day readiness also demonstrates management commitment (A.5.4) through resource allocation for crisis preparedness and supports business continuity (A.5.30) through crisis decision processes.

---

## Maturity Investment Guidance

**Foundational Investment (Levels 1–2):**  
Document basic zero-day response process: who gets notified, who assesses criticality, who makes containment decisions, who implements changes, who communicates. Create simple contact list and basic playbook. Establish emergency change process bypassing normal approval timelines. **ROI:** Reduces chaos during next zero-day event, ensures critical people get engaged quickly, provides foundation for coordinated response vs. everyone improvising, demonstrates basic crisis preparedness to auditors and executives.

**Enhanced Investment (Levels 3–4):**  
Develop detailed scenario-specific playbooks (internet-facing critical, internal high, exploitation confirmed vs. theoretical). Conduct tabletop exercises quarterly involving security, IT, business, legal, communications. Create communication templates for various scenarios and audiences. Implement response timeline tracking. Establish lessons learned process ensuring improvements get implemented. **ROI:** Confident, practiced response when zero-days occur, reduced response times through familiarity with procedures, improved coordination across teams, early gap identification through exercises vs. live incidents, demonstrable preparedness for customers and regulators.

**Strategic Investment (Level 5):**  
Integrate threat intelligence for automated zero-day detection and initial assessment. Automate response workflows (asset identification, initial containment actions, notification triggers). Implement decision support showing affected systems, business impact, compensating control options. Build response metrics showing improvement over time. Integrate zero-day performance into strategic risk discussions and architecture decisions. **ROI:** Fastest possible response leveraging automation, data-driven decision support during crisis, measurable response improvement demonstrating organizational resilience, strategic insights informing architecture and investment to reduce zero-day exposure and response times.

---

## Practical Applications

This capability mapping may be used to:

- **Crisis Preparedness Assessment:** Evaluate organizational readiness for zero-day events and identify gaps in processes, tools, or coordination before crisis occurs
- **Exercise Planning:** Design tabletop exercises and simulations testing zero-day response capabilities across security, IT, business, and communications teams
- **Incident Response Plan Development:** Enhance incident response plans with zero-day specific procedures, decision trees, and communication protocols
- **Executive Briefings:** Demonstrate crisis preparedness to boards and executives, showing practiced response capability and continuous improvement
- **Audit Evidence:** Provide documented processes, simulation records, and improvement tracking demonstrating incident management maturity
- **Vendor Assessment:** Evaluate third-party security providers' zero-day response capabilities when considering managed services or security tools

---

## Boundaries & Limitations

**What This Mapping Is NOT:**
- ❌ A guarantee that zero-day response will be successful (preparation reduces chaos but doesn't eliminate risk)
- ❌ A complete incident response playbook ready for use (organizations must create playbooks reflecting their specific environment)
- ❌ A replacement for threat intelligence and vulnerability management (detection and assessment require other capabilities)
- ❌ A claim that any specific response process satisfies framework requirements (effectiveness must be demonstrated through testing)

**Critical Dependencies:**
- Zero-Day Readiness depends on Threat Intelligence (detection and assessment), Compensating Controls (emergency mitigations), Crisis Communication Readiness (stakeholder notification), and Program Governance (executive decision authority). Without these, playbooks lack inputs, mitigations, communication channels, and decision-makers.

**Common Misinterpretation:**
- Organizations often confuse "having a playbook" with readiness. Mature capability requires regular practice through simulations—playbooks untested under pressure often fail when needed. Additionally, zero-day readiness isn't a one-time achievement—as systems change, threats evolve, and personnel turnover occurs, readiness degrades without continuous exercise and improvement.

**Important Notes:**
- Zero-day response often requires decisions with incomplete information—playbooks should include decision criteria and risk acceptance thresholds, not just technical procedures
- Cross-functional coordination is critical success factor—security alone cannot respond effectively to zero-days affecting production systems
- Legal and communications considerations often overlooked in technical playbooks—customer notification, regulatory reporting, and public disclosure require advance planning
- Response performance metrics valuable but can create perverse incentives if measuring speed without considering decision quality

---

**Document Control:**  
**Version:** 2.0.0 | **Framework Versions:** NIST CSF 2.0 (2024), NIST 800-53 Rev 5 (2020), CIS v8 (2021), ISO 27001:2022  
**Last Reviewed:** 2026-01-30 | **Next Review:** 2027-01-30  
**Feedback:** Contact ZenzizenSec for framework mapping corrections or clarifications

© 2026 ZenzizenSec Inc. All rights reserved.
