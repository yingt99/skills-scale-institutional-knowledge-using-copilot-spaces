# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Project Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Key Interactions
- Collaborates with **UX Researcher/Designer** on design handoff and user flows
- Works with **Security/Privacy Engineer** on threat models and secure design patterns
- Partners with **Platform Engineer/SRE** on deployment and operational concerns
- Engages with **Data Analyst/Data Engineer** on event instrumentation and success metrics

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Key Interactions
- Partners with **UX Researcher/Designer** to understand user needs and shape requirements
- Collaborates with **Data Analyst/Data Engineer** to define success metrics and measure impact
- Works with **Customer Success/Support Liaison** to incorporate customer feedback and support implications
- Aligns with **Technical Program Manager** on cross-team roadmap priorities

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Key Interactions
- Escalates cross-team dependencies and risks to **Technical Program Manager**
- Coordinates with **Platform Engineer/SRE** on deployment windows and operational readiness
- Works with **Security/Privacy Engineer** on compliance sign-off and security readiness gates

---

## Extended Roles (for Complex & Cross-Functional Projects)

### Technical Program Manager (TPM)

#### Role Summary
Technical Program Managers coordinate complex cross-team delivery, manage program-level milestones and dependencies, facilitate risk mitigation, and ensure alignment across multiple delivery teams.

#### Responsibilities
- Manage cross-team dependencies and integration points
- Maintain program-level timeline and release roadmap
- Facilitate technical design reviews and architecture decisions
- Identify and escalate program-level risks and blockers
- Coordinate with stakeholders, product, and engineering leadership
- Track program health metrics (velocity, burndown, quality signals)

#### Goals
- Deliver integrated solutions across multiple teams on time
- Minimize cross-team handoff friction and rework
- Maintain clear visibility into program status and risks
- Unblock teams and remove organizational friction

#### Typical Communication
- Weekly program syncs across team leads
- Cross-team dependency tracking and escalation
- Program-level risk registers and decision logs
- Stakeholder updates on program health

#### Key Interactions
- Works closely with **Project Managers** to align team timelines and dependencies
- Partners with **Platform Engineer/SRE** on infrastructure and deployment coordination
- Escalates risks with **Security/Privacy Engineer** on compliance and security gates
- Aligns with **Product Manager** on program-level prioritization trade-offs

---

### Platform Engineer / SRE (Site Reliability Engineer)

#### Role Summary
Platform Engineers and SREs provide operational guidance, design infrastructure, ensure reliability and scalability, and own production runbooks and incident response. They work to make systems observable, resilient, and easy to operate.

#### Responsibilities
- Design infrastructure and deployment architecture
- Implement monitoring, logging, and alerting
- Create runbooks and disaster recovery plans
- Participate in design reviews for operational concerns
- Conduct reliability assessments and performance tuning
- Support on-call rotations and incident response

#### Goals
- Ensure systems are reliable, scalable, and observable
- Minimize mean-time-to-detection (MTTD) and mean-time-to-recovery (MTTR)
- Reduce operational toil through automation
- Enable self-service deployments and operations

#### Typical Communication
- Design and architecture reviews
- Operational readiness checklists
- Incident reports and postmortems
- Infrastructure documentation and runbooks

#### Key Interactions
- Collaborates with **Developers** on deployment patterns, observability instrumentation, and operational testing
- Partners with **Project Manager** on deployment windows and go-live readiness
- Works with **Security/Privacy Engineer** on secure infrastructure design and compliance controls
- Supports **Technical Program Manager** with infrastructure dependencies and cross-team rollout coordination

---

### UX Researcher / Designer

#### Role Summary
UX Researchers and Designers conduct user research, define user journeys, produce design artifacts (wireframes, prototypes, high-fidelity mocks), and validate usability. They advocate for user needs and usability throughout the product lifecycle.

#### Responsibilities
- Conduct user research, interviews, and usability testing
- Define user personas, journeys, and workflows
- Create design artifacts (wireframes, prototypes, design systems)
- Participate in design reviews and iterate based on feedback
- Validate designs with users before handoff to engineering
- Document design decisions and rationale

#### Goals
- Deliver intuitive, user-friendly solutions
- Reduce user errors and support burden through good design
- Ensure designs meet accessibility standards (WCAG, ARIA)
- Advocate for user needs in prioritization decisions

#### Typical Communication
- Design specs and component libraries
- Usability testing findings and recommendations
- Design review sessions
- User research reports and personas

#### Key Interactions
- Partners closely with **Product Manager** to shape requirements and validate problem understanding
- Hands off designs to **Developers** with design specs, assets, and interaction flows
- Collaborates with **QA/Testing** on acceptance criteria and usability test plans
- Works with **Customer Success/Support Liaison** to understand support friction and design for supportability

---

### Data Analyst / Data Engineer

#### Role Summary
Data Analysts and Data Engineers identify measurement needs, instrument events and systems, create analytics queries and dashboards, and validate that success metrics are being met. They provide data-driven insights to inform decisions.

#### Responsibilities
- Define success metrics in collaboration with Product and stakeholders
- Design event instrumentation and data schema
- Build analytics queries, dashboards, and reports
- Validate data quality and integrity
- Provide post-release analysis and impact reports
- Identify data-driven opportunities for improvement

#### Goals
- Measure impact of features against success metrics
- Enable data-driven decision-making
- Ensure reliable, trustworthy data and analytics
- Support continuous learning and iteration

#### Typical Communication
- Success metrics definitions and instrumentation specs
- Analytics dashboards and reports
- Data validation and quality checks
- Post-release impact analysis

#### Key Interactions
- Partners with **Product Manager** to define success metrics and analyze post-release impact
- Works with **Developers** to embed instrumentation in code before feature launch
- Collaborates with **UX Researcher** on quantifying user behavior and validating design impact
- Provides **Technical Program Manager** with program-level health metrics and trend analysis

---

### Security / Privacy Engineer

#### Role Summary
Security and Privacy Engineers assess security and privacy implications, perform threat modeling, ensure compliance controls are addressed, and review designs and code for vulnerabilities. They champion secure and private-by-design practices.

#### Responsibilities
- Perform threat modeling and risk assessment
- Review designs and code for security vulnerabilities
- Ensure compliance with regulatory requirements (GDPR, HIPAA, SOC 2, etc.)
- Establish security policies and standards
- Participate in security incident response
- Conduct security testing and penetration testing

#### Goals
- Build security and privacy into the product by design
- Reduce security vulnerabilities and compliance risks
- Enable secure and compliant releases
- Maintain customer trust through strong data protection

#### Typical Communication
- Threat models and security assessments
- Security sign-off on releases
- Compliance checklists and audit documentation
- Security incident response and postmortems

#### Key Interactions
- Reviews designs with **Developers** and **UX Researcher** during planning phase
- Signs off with **Project Manager** and **Technical Program Manager** on release readiness for security-sensitive changes
- Partners with **Platform Engineer/SRE** on secure infrastructure design and compliance controls
- Coordinates with **Customer Success/Support Liaison** on security communication to customers

---

### Customer Success / Support Liaison

#### Role Summary
Customer Success and Support Liaisons provide customer context, capture support implications, prepare support runbooks and FAQs, and coordinate communication to customers. They bridge the gap between engineering and customer support.

#### Responsibilities
- Gather customer feedback and support trends
- Identify support implications of new features
- Prepare support documentation, runbooks, and FAQs
- Participate in release planning and communication
- Train support team on new features
- Capture post-release support metrics and feedback

#### Goals
- Reduce support burden and customer friction
- Ensure customers are prepared for new features
- Improve customer satisfaction and retention
- Surface customer needs to inform product roadmap

#### Typical Communication
- Support impact assessments
- Support documentation and training materials
- Customer communication drafts (release notes, in-app messaging)
- Support metrics and customer feedback summaries

#### Key Interactions
- Works with **Product Manager** and **Project Manager** on rollout communication and launch planning
- Collaborates with **Developers** and **QA/Testing** on acceptance criteria for supportability
- Partners with **UX Researcher** to understand design decisions that impact support
- Coordinates with **Technical Program Manager** on multi-team feature communication

---

## How These Personas Are Used

### In Project Planning
- Use persona definitions to identify required skills and team composition for your project
- Include extended personas (TPM, Platform Engineer, Designer, etc.) early in planning if your project involves:
  - Cross-team dependencies
  - Complex infrastructure or reliability concerns
  - User-facing design
  - Security or compliance implications
  - Measurable business impact

### In Communication
- Reference personas in meeting invites and decision documents to clarify who should be involved
- Use persona descriptions in onboarding and training to help new hires understand roles
- Use as "personas prompts" for Copilot Spaces to provide role-specific guidance

### In Retrospectives
- Review which personas were involved in the project
- Identify missing perspectives that caused issues (e.g., "We should have involved Security earlier")
- Use insights to improve future project staffing and planning

---

## Mapping Personas to OctoAcme Process Phases

| Phase | Core Roles | Extended Roles | Key Interactions |
|-------|-----------|-----------------|------------------|
| **Initiation** | PM, PdM, Stakeholders | TPM (if cross-team) | Identify required expertise early |
| **Planning** | PM, PdM, Developers | TPM, Designer, Data Analyst, Security, SRE | Assemble full team; define design & measurement approach |
| **Execution** | Developers, QA, PM | All extended roles as needed | Daily coordination; remove blockers |
| **Release** | Developers, PM, QA | SRE, Security, Support Liaison | Operational readiness; communication prep |
| **Retrospective** | PM, PdM, Team Leads | TPM (if cross-team) | Reflect on team composition and collaboration |
