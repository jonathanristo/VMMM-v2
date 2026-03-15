# Capability Mapping — Manual Discovery & Analyst Testing

**Model:** VMMM v2.0.0  
**Domain:** Prepare • **Tier:** Foundational • **Updated:** 2026-01-31

> **Who This Mapping Is For:**
> * Security teams relying exclusively on automated vulnerability scanners discovering scanning misses business logic flaws, complex authentication vulnerabilities, authorization bypasses requiring human intelligence and creativity that automated tools cannot detect
> * Penetration testing teams attempting to demonstrate security assessment value struggling to articulate why manual testing matters beyond automated scanning when management questions cost-effectiveness of expensive analyst time versus cheap automated tools
> * Vulnerability management teams achieving excellent automated scanning coverage metrics yet experiencing breaches through vulnerabilities automated scanners fundamentally cannot detect requiring complementary manual discovery and analyst testing capabilities
> * Compliance teams demonstrating comprehensive vulnerability assessment for audit requirements needing evidence that assessment includes manual testing methodologies addressing limitations of automated scanning tools per industry frameworks requiring defense-in-depth assessment approaches

---

## Executive Summary

Manual Discovery & Analyst Testing determines organizational capability to systematically employ human intelligence and creativity for vulnerability discovery through manual testing methodologies including penetration testing, red team exercises, code review, architecture analysis, and threat modeling—complementing automated scanning by addressing complex vulnerabilities requiring contextual understanding, business logic comprehension, and adversarial thinking that automated tools fundamentally cannot detect. Without manual testing capability, organizations operate under false confidence from 100% automated scanning coverage believing comprehensive vulnerability assessment achieved while entire vulnerability classes remain undetected: business logic flaws enabling unauthorized transactions, complex authentication bypasses through session manipulation, authorization vulnerabilities from privilege escalation chains, application-specific weaknesses requiring domain knowledge, configuration vulnerabilities needing architecture understanding. Security program achieves 98% automated vulnerability scanning coverage reporting excellent security metrics while external penetration testers identify critical business logic flaw enabling unauthorized fund transfers—vulnerability invisible to automated scanners requiring manual testing understanding application workflow and business rules. This capability strengthens evidence for security testing (CA-8, SA-11) in NIST 800-53 by demonstrating manual testing complements automated assessment, vulnerability identification (ID.RA-01) in CSF 2.0 through comprehensive multi-method assessment, penetration testing (Control 18.4) in CIS explicitly requiring manual testing, and security testing (A.8.29) in ISO 27001 with documented manual assessment methodologies. Higher maturity demonstrates systematic manual testing integrated with vulnerability management workflow, skilled analyst teams with specialized testing capabilities, testing methodologies tailored to application types and risk profiles, and continuous improvement incorporating lessons learned from manual discovery into automated detection enabling scaling analyst expertise through tooling.

**Key Frameworks:** NIST 800-53 (CA-8, SA-11, SA-15) • CSF 2.0 (ID.RA-01, DE.AE-02) • CIS Control 18.4 • ISO 27001 (A.8.8, A.8.29)  
**Primary Evidence:** Manual testing methodologies and procedures, penetration test reports, red team exercise documentation, code review findings, threat modeling outputs, analyst training and certification records  
**Cross-Domain Dependencies:** Automated Vulnerability Scanning, Application Security, Threat Intelligence

---

## Capability Overview

Security team implements comprehensive automated vulnerability scanning across infrastructure and applications achieving 100% coverage. Monthly reports show thousands of vulnerabilities identified and remediated. Security metrics dashboard displays excellent scanning coverage, low mean-time-to-remediation, declining vulnerability counts. Management sees strong security program maturity based on automated scanning metrics. External penetration testing firm conducts annual assessment as audit requirement. Week one, penetration testers identify critical business logic flaw in financial application: multi-step transaction process contains race condition enabling users to complete transactions after account balance verification but before balance deduction, allowing negative balances and unauthorized withdrawals. Automated vulnerability scanners completely missed vulnerability—requires understanding application business logic, transaction workflow, timing analysis, manual testing simulating concurrent transactions. Security team surprised: "Automated scanner showed no critical findings in this application." Penetration tester explains: "Business logic flaws invisible to automated tools. Requires human understanding of application purpose and creative attack scenarios automated scanners cannot generate." Further manual testing identifies additional vulnerabilities automated scanning missed: complex authentication bypass through session manipulation, privilege escalation chain requiring multiple steps, API rate limiting bypass, configuration weaknesses requiring architecture knowledge. Annual penetration test discovers more critical vulnerabilities in one week than automated scanning found in entire year—revealing fundamental gap in vulnerability assessment relying exclusively on automated tools without complementary manual testing capability.

Without manual testing, organizations discover complex vulnerabilities through breaches not proactive assessment. Application team implements custom authentication system for partner portal believing secure design. Automated security testing during development identifies standard vulnerabilities: missing input validation, SQL injection opportunities, cross-site scripting. All remediated. Application passes automated security scanning. Deployed to production. Six months operation. Security breach: unauthorized access to partner portal. Investigation reveals sophisticated authentication bypass through session token manipulation exploiting subtle timing vulnerability in token generation algorithm. Attacker reverse-engineered token generation pattern, predicted valid tokens, accessed arbitrary accounts. Vulnerability required deep authentication flow analysis, cryptographic weakness identification, timing attack execution—none detectable by automated scanning. Post-incident analysis: automated tools tested for known vulnerability patterns but cannot understand authentication architecture, analyze cryptographic implementations, or simulate adversarial reverse-engineering. Manual security code review or penetration testing would have identified flaw during development preventing production deployment of vulnerable authentication system.

Different organization attempts manual testing through ad hoc penetration tests. Purchases annual penetration test from external firm. Testing conducted once yearly for compliance checkbox. Test methodology generic using standard tools and attack patterns without deep application context. Pentest report lists medium and low findings mostly duplicate of automated scanner results. High-impact vulnerabilities missed because testing time-boxed to few days, testers lack application domain expertise, no threat modeling identifying critical attack scenarios, testing methodology shallow surface scanning not deep analysis. Management questions penetration testing value: "Why pay $50,000 for findings automated scanner already identified?" Security team cannot articulate manual testing value beyond compliance requirement. Penetration testing becomes compliance theater—expensive annual exercise producing little additional value over automated scanning because manual testing performed without methodology, expertise, or integration with vulnerability management.

Compliance audit reveals manual testing evidence gaps. Auditor requests penetration testing documentation for PCI DSS requirement 11.3 requiring annual penetration testing. Organization provides single pentest report from external vendor. Auditor asks about remediation of identified findings. Security team shows subset of findings remediated. Auditor questions: "Report dated 11 months ago. How do you know these vulnerabilities still fixed? Any retesting after remediation?" No retest evidence. Auditor asks about testing scope: "Report covers subset of in-scope systems. How selected? What about other payment processing systems?" Testing scope arbitrary based on budget not risk. Auditor asks about testing methodology: "Report describes automated scanning with some manual verification. Where's evidence of manual testing per requirement?" Automated scanning mislabeled as manual testing. Audit finding: penetration testing inadequate, lacks systematic methodology, insufficient evidence of manual testing, no validation of remediation, scope incomplete. Similar manual testing gaps discovered for other frameworks requiring assessment beyond automated scanning.

Security metrics fail to reflect manual testing value. Dashboard shows automated scanning metrics: "12,000 vulnerabilities identified, 11,500 remediated, 98% scanning coverage." Metrics imply comprehensive vulnerability management. Missing from metrics: critical business logic flaws requiring manual discovery, complex authentication vulnerabilities needing analyst expertise, architecture weaknesses demanding security design review. Annual penetration test identifies 8 critical findings automated scanning missed completely. Executive asks "How do we have excellent scanning metrics but penetration test finds critical vulnerabilities?" Security team explains automated scanning limitations but lacks systematic manual testing program demonstrating proactive manual discovery not just annual audit checkbox.

Mature Manual Discovery & Analyst Testing capability prevents these failures through systematic integration of manual testing with automated vulnerability management. Penetration testing program established: regular penetration tests scheduled based on risk not just annual compliance requirement, testing scope risk-driven targeting critical applications and recent changes, methodology tailored to application types (web apps, APIs, mobile, infrastructure), retesting validates remediation of identified vulnerabilities. Analyst expertise developed: security analysts trained in manual testing techniques, certifications pursued (OSCP, GPEN, CEH), specialized skills developed for application types (mobile app testing, API security, cloud infrastructure), continuous learning incorporating new attack techniques. Testing methodologies documented: penetration testing procedures standardized, code review checklists for common vulnerability patterns, threat modeling framework for architecture analysis, methodology adapts to technology stack and business context.

Integration with vulnerability management workflow operationalizes manual testing. Manual testing findings integrated with automated scan results: penetration test discoveries added to vulnerability management platform alongside scanner findings, severity and priority assessed consistently across automated and manual discoveries, remediation tracked through same workflow regardless of discovery method. Risk-based testing targeting: manual testing resources focused on highest-risk applications identified through risk assessment, critical infrastructure receives deeper manual assessment, application changes trigger targeted manual testing, automated scanning provides continuous coverage while manual testing provides periodic deep assessment. Continuous improvement closes detection gaps: manual discoveries analyzed identifying new vulnerability patterns, patterns codified into automated detection rules where possible, automated scanning enhanced with signatures for manually discovered vulnerability types, analyst expertise scaled through tooling improvements.

Business logic testing addresses automated scanning blind spots. Security analysts develop application-specific test cases: financial applications tested for transaction logic flaws, access control systems assessed for privilege escalation paths, workflow applications evaluated for state machine vulnerabilities, API rate limiting and quota enforcement validated. Manual testing scenarios simulate real-world attacks: credential stuffing attempts, account takeover scenarios, business logic abuse, privilege escalation chains. Documentation captures business logic vulnerabilities: findings describe exploitation scenarios, business impact quantified, remediation guidance includes business logic fixes not just technical patches.

Code review complements runtime testing. Security analysts review critical code: authentication and authorization implementations examined, cryptographic code analyzed, input validation and sanitization reviewed, error handling assessed for information disclosure. Static analysis augmented with manual review: automated SAST findings prioritized by analysts, false positives eliminated through code review, complex vulnerabilities requiring code understanding identified manually. Secure development integration: code review findings inform development training, design review identifies security issues before implementation, architecture analysis validates security controls.

At highest maturity, manual testing operates as continuous security intelligence program. Purple team exercises combine red and blue: attackers simulate realistic threats, defenders practice detection and response, exercises identify detection gaps and defensive blind spots, collaboration improves security program effectiveness. Threat modeling drives targeted testing: threat models identify high-risk attack scenarios, manual testing validates threat model assumptions, modeling updated based on penetration testing discoveries. Automation scales analyst expertise: manual discoveries automated where possible, custom scanning modules developed for organization-specific patterns, AI/ML assists analysts with pattern recognition and anomaly detection. Strategic intelligence: vulnerability trends inform architecture decisions, common manual findings drive systematic improvements, manual testing insights shape security program evolution, executive reporting demonstrates value through critical findings preventing potential breaches.

---

## Maturity-Based Evidence Progression

| Maturity Level | Evidence Characteristics |
|----------------|-------------------------|
| **Level 1** | No systematic manual testing. Organization relies exclusively on automated vulnerability scanning. Complex vulnerabilities requiring human analysis remain undetected. Occasional ad hoc manual investigation when breach occurs but no proactive manual discovery program. Evidence: None—automated scanning reports only, no penetration testing documentation, no manual testing procedures, manual discovery reactive post-incident not proactive. |
| **Level 2** | Ad hoc manual testing for compliance only. Annual penetration test purchased from external vendor meeting minimum compliance requirement. Testing generic without application context. Findings often duplicate automated scanner results. No remediation validation or retesting. Manual testing viewed as compliance checkbox not security value. Evidence: Single annual penetration test report, compliance documentation citing pentest as requirement, minimal remediation tracking, no systematic manual testing methodology. |
| **Level 3** | Basic systematic manual testing program established. Penetration testing conducted semi-annually or quarterly. Testing scope includes critical applications. Some methodology standardization. Findings integrated with vulnerability management. Remediation tracking and validation testing implemented. Analyst training in manual testing techniques. Evidence: Multiple penetration test reports annually, testing methodology documentation, vulnerability management platform showing manual findings alongside automated, remediation validation evidence, analyst training records. |
| **Level 4** | Comprehensive manual testing integrated with vulnerability management. Regular penetration testing risk-driven not compliance-driven. Specialized testing capabilities for different application types. Code review for critical components. Threat modeling driving targeted testing. Manual findings inform automated detection improvements. Continuous analyst skill development. Evidence: Risk-based testing schedule, specialized testing reports (web app, API, mobile, infrastructure), code review findings, threat models, automated detection rules derived from manual discoveries, analyst certifications (OSCP, GPEN), continuous improvement documentation. |
| **Level 5** | Strategic continuous security intelligence through manual testing. Purple team exercises combining attack and defense. Threat modeling integrated with architecture decisions. Automation scaling analyst expertise through custom tools. Manual testing insights shaping security program evolution. Executive visibility into manual discovery value through prevented breach scenarios. Evidence: Purple team exercise reports, integrated threat modeling in design process, custom security testing tools developed, vulnerability trend analysis driving architecture decisions, executive briefings showing critical manual findings and prevented incidents, documented security program improvements from manual testing insights. |

---

## Framework Alignment Overview

| Framework | Primary References | Alignment Summary |
|-----------|-------------------|-------------------|
| **NIST Cybersecurity Framework 2.0** | ID.RA-01, DE.AE-02 | Demonstrates comprehensive vulnerability identification and security event analysis through manual testing |
| **NIST SP 800-53 Rev. 5** | CA-8, SA-11, SA-15 | Strengthens penetration testing, developer security testing, and development life-cycle security through manual assessment |
| **CIS Critical Security Controls v8** | Control 18.4 | Explicit demonstration of penetration testing safeguard requiring manual security assessment |
| **ISO/IEC 27001:2022** | A.8.8, A.8.29 | Provides vulnerability management and security testing through documented manual methodologies |

---

## NIST SP 800-53 Rev. 5 Alignment

**Relevant Control Families:** CA – Assessment, Authorization, and Monitoring, SA – System and Services Acquisition

This capability demonstrates security assessment and testing through systematic manual methodologies complementing automated approaches.

**Key Exemplar Controls:**

| Control | How This Capability Strengthens Evidence |
|---------|------------------------------------------|
| **CA-8 – Penetration Testing** | Core capability—demonstrates systematic penetration testing through documented methodology, regular testing schedule, scope including critical systems, findings documentation and remediation validation, proving manual security assessment beyond automated scanning per control requirement for adversary perspective testing |
| **SA-11 – Developer Testing and Evaluation** | Shows developer security testing includes manual code review, threat modeling, architecture analysis beyond automated SAST/DAST, security analysts reviewing critical code and designs, manual testing identifying complex vulnerabilities automated tools miss, proving comprehensive development security testing |
| **SA-15 – Development Process, Standards, and Tools** | Demonstrates development security through manual security design review, threat modeling integrated with architecture decisions, code review for security-critical components, manual assessment validating security controls implementation proving security throughout development lifecycle |

> Additional controls strengthened include CA-2 (Security Assessments) through manual security assessment methodologies, RA-5 (Vulnerability Monitoring) complemented by manual discovery, and SA-3 (System Development Life Cycle) via security design review.

---

## NIST CSF 2.0 Alignment

**Relevant Functions:** Identify (ID), Detect (DE)

Manual testing supports vulnerability identification and anomaly detection through human intelligence and creativity automated tools lack.

**Key Exemplar Subcategories:**

| Subcategory | How This Capability Strengthens Evidence |
|-------------|------------------------------------------|
| **ID.RA-01 – Vulnerabilities in assets are identified, validated, and recorded** | Demonstrates comprehensive vulnerability identification using multiple methods including manual penetration testing, code review, threat modeling beyond automated scanning, human analysts identifying complex vulnerabilities automated tools miss, validation through manual testing proving vulnerability exploitability |
| **DE.AE-02 – Potentially adverse events are analyzed to better understand associated activities** | Shows security event analysis through penetration testing revealing attack paths and techniques, red team exercises demonstrating adversary tradecraft, manual analysis understanding complex attack scenarios automated detection misses |

---

## CIS Critical Security Controls v8 Alignment

**Relevant Control:** Control 18 – Penetration Testing

CIS Control 18.4 explicitly requires penetration testing. Manual discovery directly demonstrates this safeguard.

**Key Exemplar Safeguards:**

| Safeguard | IG Level | How This Capability Strengthens Evidence |
|-----------|----------|------------------------------------------|
| **18.4 – Perform Penetration Testing** | IG2 | Core capability—demonstrates systematic penetration testing through regular testing schedule, documented methodology, scope including external and internal perspectives, findings remediation and validation, proving manual security assessment complements automated vulnerability scanning |

> Manual testing proves Control 18 comprehensive penetration testing performed not just automated scanning mislabeled as penetration testing.

---

## ISO/IEC 27001:2022 Alignment

**Relevant Control Categories:** Technological Controls (8.x)

ISO 27001 requires vulnerability management and security testing. Manual discovery provides documented comprehensive assessment methodologies.

**Key Exemplar Controls:**

| Control | How This Capability Strengthens Evidence |
|---------|------------------------------------------|
| **A.8.8 – Management of Technical Vulnerabilities** | Shows technical vulnerability management includes manual discovery through penetration testing, code review, threat modeling identifying vulnerabilities automated scanning misses, comprehensive assessment methodology combining automated and manual approaches proving systematic vulnerability identification |
| **A.8.29 – Security Testing in Development and Acceptance** | Demonstrates security testing throughout development through manual code review, threat modeling, security design review, acceptance testing including manual penetration testing validating security controls before production deployment |

> Manual testing addresses auditor questions about assessment comprehensiveness proving testing beyond automated scanning includes human intelligence and creativity.

---

## Maturity Investment Guidance

**Foundational Investment (Levels 1–3):**  
Establish basic manual testing program. Purchase annual penetration testing from qualified external vendor covering critical applications and infrastructure. Define testing scope based on risk including internet-facing applications, systems processing sensitive data, recent major changes. Request detailed testing methodology description not just automated scanning. Establish remediation workflow: penetration test findings added to vulnerability management platform, prioritized alongside automated findings, remediation tracked, retesting validates fixes. Document testing for compliance: penetration test reports maintained for audit, findings remediation evidence collected, testing schedule defined. Provide basic analyst training: security team members attend penetration testing fundamentals training, industry certifications pursued (Security+, CEH), internal knowledge sharing about manual testing techniques. **ROI:** Establishes manual testing capability previously absent, identifies 5-20 critical vulnerabilities automated scanning missed preventing potential breaches, satisfies compliance requirements (PCI DSS 11.3, SOC 2 penetration testing), analyst training builds internal capability reducing reliance on external vendors, documented methodology provides audit evidence for comprehensive security assessment, typical penetration test ROI 10:1 through prevented breach cost versus testing investment.

**Enhanced Investment (Levels 3–4):**  
Implement comprehensive systematic manual testing program. Increase testing frequency: critical applications tested quarterly, standard applications semi-annually, risk-driven scheduling not just annual compliance. Develop specialized testing capabilities: train analysts in specific methodologies (web application testing, API security, mobile app assessment, cloud infrastructure pentesting), acquire specialized tools (Burp Suite Professional, mobile testing frameworks, cloud security tools), build expertise in technology stack used organizationally. Implement code review program: security analysts review critical code (authentication, authorization, cryptography), automated SAST findings triaged and validated manually, secure coding training for developers based on code review findings. Establish threat modeling practice: critical applications receive threat modeling during design phase, threat models identify high-risk scenarios guiding manual testing, models updated based on penetration testing discoveries. Integrate manual and automated testing: manual findings analyzed for automatable patterns, custom detection rules developed from manual discoveries, automated scanning enhanced with organization-specific vulnerability signatures. Document and improve: testing methodologies standardized in runbooks, lessons learned captured after each test, continuous improvement based on findings and techniques. **ROI:** Comprehensive manual testing identifies 50-100+ critical findings annually automated scanning cannot detect, code review prevents vulnerabilities before production deployment reducing remediation cost 10x, threat modeling identifies architecture security issues before implementation preventing costly redesign, specialized testing capabilities address organization-specific technologies automated tools lack coverage for, integration scales analyst expertise through automation improving efficiency, typical mature program prevents 2-5 security incidents annually with prevented breach costs 100x testing investment.

**Strategic Investment (Level 5):**  
Implement strategic continuous security intelligence program. Deploy purple team exercises: monthly exercises simulating realistic attack scenarios, blue team practices detection and response, collaboration identifies defensive gaps, exercises inform security program improvements. Integrate threat modeling with architecture: all new systems receive threat modeling in design phase, threat models drive security requirements, manual testing validates threat model assumptions, architecture decisions informed by threat intelligence and penetration testing insights. Automate analyst expertise: develop custom security testing tools specific to organizational applications, implement AI/ML assisting vulnerability analysis and pattern recognition, create automated test suites from manual testing scenarios enabling continuous validation. Build internal red team: dedicated internal red team conducting ongoing adversary simulation, persistent presence identifying vulnerabilities automation misses, collaboration with development and operations improving security culture. Establish strategic analytics: vulnerability trends analyzed showing common weaknesses, manual testing insights inform technology selection, executive reporting demonstrates prevented breaches through proactive discovery, security program evolution data-driven from manual testing intelligence. **ROI:** Purple team exercises dramatically improve detection capabilities and incident response reducing breach dwell time from months to days, proactive red teaming identifies critical vulnerabilities before external attackers with estimated prevented breach savings millions annually, automation scaling expertise enables testing more applications with same analyst headcount improving coverage, strategic analytics demonstrate security program business value supporting continued investment, mature manual testing programs typical ROI 20:1+ through comprehensive vulnerability discovery preventing major incidents.

---

## Practical Applications

This capability mapping may be used to:

- **Compliance Penetration Testing:** Satisfy regulatory penetration testing requirements (PCI DSS 11.3, SOC 2, ISO 27001 A.8.8) through documented systematic manual testing, comprehensive scope definition, remediation validation, retesting evidence proving compliance beyond automated scanning
- **Business Logic Vulnerability Discovery:** Identify business logic flaws automated scanners cannot detect through manual testing understanding application workflow, transaction logic, state machines, privilege models requiring human comprehension of business context
- **Application Security Code Review:** Complement automated SAST through manual security code review of critical components (authentication, authorization, cryptography), false positive elimination, complex vulnerability identification requiring code understanding
- **Threat Modeling & Architecture Analysis:** Validate security architecture through threat modeling identifying attack scenarios, manual testing validating threat model assumptions, architecture review ensuring security controls properly designed before implementation
- **Purple Team Security Improvement:** Improve detection and response capabilities through purple team exercises simulating realistic attacks, identifying defensive gaps, fostering collaboration between offensive and defensive security teams
- **Custom Vulnerability Pattern Detection:** Scale analyst expertise by analyzing manual discoveries for automatable patterns, developing custom detection rules, enhancing automated scanning with organization-specific vulnerability signatures

---

## Boundaries & Limitations

**What This Mapping Is NOT:**
- ❌ A replacement for automated vulnerability scanning (manual testing complements not replaces automated continuous assessment)
- ❌ A guarantee identifying all vulnerabilities (even skilled analysts miss some vulnerabilities in time-boxed assessments)
- ❌ A specific penetration testing methodology prescription (organizations must define methodology appropriate to risk and technology)
- ❌ A checklist for performing penetration tests (requires skilled security professionals with training and experience)

**Critical Dependencies:**
- Manual Discovery & Analyst Testing depends on Automated Vulnerability Scanning (provides baseline continuous assessment), Application Security (provides application context for testing), and Threat Intelligence (informs realistic attack scenarios). Without these, manual testing lacks baseline comparison, application understanding, or threat context guiding testing focus.

**Common Misinterpretation:**
- Organizations often view manual testing as expensive luxury versus automated scanning necessity. Mature understanding recognizes complementary roles: automated scanning provides continuous broad coverage while manual testing addresses complex vulnerabilities requiring human intelligence. Additionally, annual compliance-driven penetration testing alone insufficient—systematic risk-based manual testing required for effective security.

**Important Notes:**
- Manual testing requires skilled analysts—investment in training and certification essential for effective testing, inexperienced analysts produce findings similar to automated scanners providing limited additional value
- Scope and methodology critical—generic checklist penetration testing provides minimal value over automated scanning, effective manual testing requires understanding application context and threat scenarios
- Integration with vulnerability management essential—manual findings must integrate with automated discoveries for unified remediation workflow and metrics
- Continuous improvement necessary—manual testing should inform automated detection improvements, lessons learned captured, methodologies evolved based on discoveries

---

**Document Control:**  
**Version:** 2.0.0 | **Framework Versions:** NIST CSF 2.0 (2024), NIST 800-53 Rev 5 (2020), CIS v8 (2021), ISO 27001:2022  
**Last Reviewed:** 2026-01-31 | **Next Review:** 2027-01-31  
**Feedback:** Contact ZenzizenSec for framework mapping corrections or clarifications

© 2026 ZenzizenSec Inc. All rights reserved.
