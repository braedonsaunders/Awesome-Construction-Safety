# Awesome-Construction-Safety

## Top Construction Safety Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Site Safety Management, Incident Reporting, Hazard Tracking & Compliance Monitoring*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Construction Safety**. These tools help general contractors, safety directors, and site supervisors digitize safety workflows, capture incidents and hazards in real time, track corrective actions, and maintain audit-ready compliance documentation.



**Examples** include HammerTech, Safesite, SiteDocs, EcoOnline, EHS Insight, Procore Safety, Salus, SafetyCulture (iAuditor), Assignar, and FieldSafe (the category leaders).



**Open-source emphasis**: Construction safety has a **small but emerging open-source ecosystem**. The most significant open-source project is **Autonomous-EHS-Management**, a self-hosted EHS console with incidents, CAPA, audits, and TRIR-style metrics in PostgreSQL . A notable construction-specific project is **SafeSite Digital Twin**, a real-time worker safety intelligence platform with fatigue monitoring and dynamic hazard zones . However, commercial platforms dominate the category with deep integration into project management ecosystems and mobile-first field tools.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[HammerTech](https://www.hammertech.com/)**  

  Safety intelligence platform built specifically for construction, with deep integration into Procore for seamless safety and project management . Provides comprehensive HSEQ management including inductions, sign-in/out, qualifications tracking, RAMS/safety plans, daily briefings, inspections, permits, incident reporting, and equipment management . Features unlimited access for subcontractors and AI-driven capabilities via HammerTech Intelligence. Clients report 47% enhanced operational workflow efficiency, 57% quicker approval of key project documents, and 80% injury reduction in one case study .



- **[Safesite](https://safesitehq.com/)**  

  Mobile-first safety management system with inspections, safety meetings, incident reporting, hazard management, and leading indicator analytics . Users report 50% inspection time reduction, 4 hours saved weekly on paperwork, and up to 57% incident reduction. Hazard management allows real-time recording with photos, risk assessment conforming to WCIO injury descriptions, and root cause analysis .



- **[SiteDocs](https://www.sitedocs.com/)**  

  Safety management software with digital form builder, PDF timestamping, and worker certification portal . Supports global safety program unification while maintaining regional flexibility, as demonstrated by NPSG Global collecting over 188,000 unique signatures across regions . Features contractor management, incident management, corrective actions, hazard management, equipment management, worker orientation, and analytics.



- **[EcoOnline](https://www.ecoonline.com/)**  

  EHS software for multi-site, high-risk operations spanning construction, manufacturing, chemical, and energy . Provides incident reporting, audit management, risk assessment, corrective action tracking (CAPA), training management, permit-to-work, and real-time dashboards . Recognized as a Verdantix Green Quadrant leader. Features automated SDS management, ESG framework reporting (CSRD, TCFD, CDP), and mobile offline capability.



- **[EHS Insight](https://www.ehsinsight.com/)**  

  Mobile-first EHS platform with construction-specific capabilities including incident management, inspections/audits, training tracking, and document control . Features AI Copilot for instant OSHA guidance, smart reporting, checklist generation, and training support. Chemical manufacturing edition handles OSHA PSM, EPA RMP, REACH, and GHS compliance with SIF precursor detection .



- **[Procore Safety](https://www.procore.com/)**  

  Safety hub within Procore's construction management platform. Launched April 2026 in open beta, providing centralized company-level view of observations, inspections, and incidents across all projects . Integrates with HammerTech for dedicated safety workflows .



- **[Salus](https://www.salus.com/)**  

  Digital safety platform for construction and project sites, managing documents, forms, certificates, assets, compliance checks, and incident reporting . Features QR code-driven orientations, subcontractor management, digital forms, certificate tracking, and AI assistant "Rosie" for drafting documents and spotting trends .



- **[SafetyCulture (iAuditor)](https://safetyculture.com/)**  

  Mobile-first operations platform trusted by 70,000+ organizations, powering 600M+ checks annually . Features inspections, issue reporting, asset management, training, task management, and "Heads Up" team communication. Free for teams up to 10. Supports offline inspections, AI-generated templates, and professional report generation.



- **[Assignar](https://www.assignar.com/)**  

  Construction workforce and compliance management platform. Manages worker roles/tasks with attached skills, assets, and forms . Features asset requirement enforcement (no assets needed, needed, or required), supervisor permissions, docket templates, charge rates, and audit trails.



- **[FieldSafe](https://www.fieldsafesolutions.com/)**  

  Lone worker safety and compliance platform. Provides smarter workflows, lone worker monitoring, journey management, compliance calendar, and hazard assessments . Emphasizes connecting workers and improving safety while optimizing operations.



## Open-Source GitHub Projects



- **[Autonomous-EHS-Management (SafetyMP)](https://github.com/SafetyMP/Autonomous-EHS-Management)**  

  **The most complete open-source EHS console for construction safety.** Self-hosted platform with incidents, CAPA (Corrective and Preventive Actions), audits, and TRIR-style metrics in PostgreSQL . Features records and metrics with TRIR analytics, action queue on command center, environmental regulatory permits, incident RCA (5 Whys + Ishikawa), risk register with overdue review tracking, program automation samples, integrations backlog, and evidence attachment registry. AI suggests wording only — humans close records. Docker Compose deployment with PostgreSQL. **Open source**.



- **[SafeSite Construction Digital Twin](https://github.com/anshumanvatsa/construction-digital-twin)**  

  **Real-time construction site safety intelligence platform with predictive analytics and smart hazard detection.** Features live 2D/3D digital twin map showing worker positions and machinery operations, worker fatigue monitoring with biometrics and predictive warnings, dynamic hazard zones (geofences for crane operations, excavations, overhead lifts) with instant alerts, advanced simulation engine for hypothetical scenarios, and real-time analytics dashboard . Tech stack: React, TypeScript, Tailwind CSS, FastAPI, PostgreSQL, Redis. Docker deployment. **MIT License**.



- **[Spunta](https://interoperable-europe.ec.europa.eu/eu-oss-catalogue/solutions/spunta)**  

  **Open-source checklist manager for periodic equipment and site checks.** Born for daily review of Italian Red Cross equipment, adopted by multiple committees . Features inventory of objects (numeric, text, date, boolean), checklists organized into categories and slot hierarchy, time limit definitions, digital completion with personal PIN for authenticity, smartphone-designed interface, and internal alert system. **AGPL-3.0-or-later**. Available at spunta.app for hosting/support.



- **[site-safety-audit-agent](https://github.com/)**  

  Open-source agent for automated site safety audits. Research-stage project. **Open source**.



### Additional Strong Open-Source Options



- **EHS Management**: **Autonomous-EHS-Management** (most complete, PostgreSQL, TRIR metrics, CAPA) .

- **Construction-Specific**: **SafeSite Digital Twin** (real-time worker tracking, fatigue monitoring, hazard zones) .

- **Checklist Management**: **Spunta** (Red Cross deployed, PIN authentication, mobile-first) .

- **Compliance Foundations**: **OpenCAPA** (open-source CAPA management), **OpenEHS** (community EHS modules).



**Frameworks for building custom systems**: Combine **Autonomous-EHS-Management** for core incident, CAPA, and audit workflows with PostgreSQL, **SafeSite Digital Twin** for real-time worker safety monitoring and hazard detection, and **Spunta** for equipment and site checklist management. Add **PostgreSQL** for persistence and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Construction safety platforms handle sensitive incident and worker data; ensure compliance with OSHA, ISO 45001, and relevant regional safety regulations.

- **Open-source reality**: The open-source ecosystem for construction safety is **emerging but not yet equivalent to commercial platforms**. **Autonomous-EHS-Management** provides a self-hosted EHS console with core incident, CAPA, and audit capabilities . **SafeSite Digital Twin** offers real-time worker safety intelligence with fatigue monitoring and hazard zones . **Spunta** delivers production-proven checklist management deployed by the Italian Red Cross . However, commercial platforms (HammerTech, Safesite, SiteDocs, EcoOnline) provide **deep construction-specific workflows, subcontractor management at scale, mobile-first field tools, and integration with project management ecosystems** that open-source alternatives cannot match without significant institutional investment. The open-source path is most viable for organizations with strong engineering capacity building custom solutions or for specific focused use cases.



---



**Made for construction safety directors, site supervisors, EHS managers, and field operations teams.**  

Let's make construction safety more open, transparent, and proactive.
