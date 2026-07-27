# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Engineering Manager

### Role Summary
Engineering Managers ensure teams have the capacity, clarity, and support to deliver reliably. They bridge leadership expectations and day-to-day engineering execution, focusing on people, process health, and cross-team coordination.

### Responsibilities
- Own staffing, capacity planning, and headcount allocation for their teams
- Remove blockers and resolve cross-team dependencies
- Coach and grow individual engineers and tech leads
- Provide technical delivery governance and escalation paths
- Partner with Project Managers on execution risk and timeline feasibility

### Goals
- Sustainable team velocity with predictable delivery
- High developer satisfaction and retention
- Clear escalation paths for technical and organizational blockers

### Typical Communication
- 1:1s with direct reports and skip-level check-ins
- Capacity and dependency reviews in planning ceremonies
- Escalation updates to leadership and cross-team leads

### Interactions with Existing Roles
- **Developers:** provides coaching, unblocks prioritization conflicts, and advocates for sustainable pace and tooling investments
- **Product Managers:** aligns on scope trade-offs when capacity constraints affect roadmap commitments
- **Project Managers:** collaborates on execution risk, resource gaps, and timeline feasibility reviews

---

## Tech Lead / Solution Architect

### Role Summary
Tech Leads and Solution Architects set the technical direction for a product or initiative. They make architectural decisions, define non-functional requirements, and ensure implementation quality through design reviews and standards.

### Responsibilities
- Define and document architectural decisions (ADRs)
- Establish non-functional requirements (performance, scalability, security baselines)
- Lead technical design and code review standards
- Evaluate and recommend tools, frameworks, and patterns
- Identify and communicate technical risks early in the lifecycle

### Goals
- A coherent, maintainable, and secure technical architecture
- Reduced rework through proactive design review
- Shared understanding of technical constraints across the team

### Typical Communication
- Architecture review sessions and design docs
- ADR records tracked in the project repository
- Technical risk items surfaced in planning and status meetings

### Interactions with Existing Roles
- **Developers:** collaborates on implementation design, conducts design reviews, and provides technical mentorship
- **Product Managers:** aligns technical choices to product outcomes and helps translate technical constraints into product trade-offs
- **Project Managers:** informs on technical sequencing dependencies, risks, and complexity that affect timelines

---

## UX/UI Designer

### Role Summary
UX/UI Designers translate user needs into clear, accessible, and implementable interfaces. They own the user experience from problem framing through design handoff and QA validation.

### Responsibilities
- Conduct user research and synthesize insights into design requirements
- Create wireframes, prototypes, and high-fidelity mockups
- Define user flows, interaction patterns, and accessibility standards
- Provide implementation-ready design specs and assets
- Participate in design QA to verify fidelity against implementation

### Goals
- Intuitive, accessible products that reduce user friction
- Design decisions grounded in validated user needs
- Smooth handoffs that minimize back-and-forth with engineering

### Typical Communication
- Design reviews and critique sessions with cross-functional teams
- Figma (or equivalent) file handoffs with annotated specs
- Sync with Product Manager for user feedback loops and validation

### Interactions with Existing Roles
- **Developers:** provides implementable specs, assets, and acceptance criteria for visual and interaction quality; participates in design QA
- **Product Managers:** partners on problem framing, user research planning, and solution validation
- **Project Managers:** syncs on design delivery milestones, handoff readiness, and schedule impacts from design iteration

---

## DevOps / Platform Engineer

### Role Summary
DevOps and Platform Engineers build and maintain the foundations that enable reliable, repeatable delivery. They own CI/CD pipelines, environment management, observability tooling, and deployment safeguards.

### Responsibilities
- Design and maintain CI/CD pipelines and build infrastructure
- Manage environment configuration and provisioning standards
- Define and implement observability standards (logging, metrics, alerting)
- Enforce deployment safeguards and rollback mechanisms
- Evaluate and reduce infrastructure toil through automation

### Goals
- High deployment frequency with low failure rate
- Fast incident detection and recovery
- Consistent, reproducible environments across dev, staging, and production

### Typical Communication
- Pipeline and infra status updates in team channels
- Runbooks and playbooks maintained in the project repository
- Release readiness sign-off with Project Manager and Tech Lead

### Interactions with Existing Roles
- **Developers:** supports pipelines, runtime reliability, and local environment parity; reviews infrastructure-impacting code changes
- **Product Managers:** works with Product Manager on rollout strategies, feature flags, and risk mitigation plans for releases
- **Project Managers:** coordinates on release windows, deployment readiness gates, and incident response timelines

---

## Security Champion / Security Engineer

### Role Summary
Security Champions and Security Engineers embed security thinking throughout the delivery lifecycle. They perform threat modeling, run security review checkpoints, triage vulnerabilities, and ensure policy alignment.

### Responsibilities
- Conduct threat modeling at design and architecture stages
- Define and enforce security review checkpoints in the delivery process
- Triage and prioritize security vulnerabilities from scans and reports
- Advise on secure coding practices and dependency management
- Ensure compliance with internal security policies and relevant regulations

### Goals
- Security integrated early ("shift left"), not bolted on at release
- Clear vulnerability triage and remediation SLAs
- Shared security awareness across the engineering team

### Typical Communication
- Security review findings in PRs and design docs
- Vulnerability and risk reports surfaced to Project Manager and leadership
- Office hours or async Q&A for developer guidance

### Interactions with Existing Roles
- **Developers:** advises during implementation on secure patterns, dependency risks, and code review findings
- **Tech Lead / Solution Architect:** partners on secure architecture patterns and non-functional security requirements
- **Project Managers:** surfaces security-risk escalations and aligns on remediation timelines that affect release readiness

---

## Customer Success / Support Liaison

### Role Summary
Customer Success and Support Liaisons represent the voice of the customer inside the delivery team. They track post-release signals, coordinate support readiness, and ensure known issues are communicated transparently.

### Responsibilities
- Aggregate and relay customer feedback, pain points, and adoption signals to the team
- Coordinate support readiness activities ahead of releases (training, runbooks, FAQs)
- Communicate known issues and workarounds to support channels and customers
- Track post-release user sentiment and escalate critical issues
- Represent customer impact in prioritization and trade-off discussions

### Goals
- Customers are informed, supported, and heard throughout delivery
- Support teams are prepared before each release
- Customer-impacting bugs and regressions surface quickly for triage

### Typical Communication
- Post-release feedback summaries shared with Product Manager
- Support readiness reviews with Project Manager before releases
- Customer escalation reports to engineering and leadership

### Interactions with Existing Roles
- **Developers:** provides actionable defect context from support channels, including reproduction steps and customer impact scope
- **Product Managers:** feeds user pain points and adoption insights that inform backlog prioritization and success metric tracking
- **Project Managers:** collaborates on stakeholder communications, known-issue messaging, and support readiness milestones

---

## Data Analyst / BI Partner

### Role Summary
Data Analysts and BI Partners ensure that product and engineering decisions are grounded in measurement. They define metrics, guide instrumentation, and produce outcome reports for experiments and releases.

### Responsibilities
- Define and document success metrics and KPI frameworks for features and releases
- Guide Developers on event tracking and instrumentation requirements
- Build and maintain dashboards and reporting for project outcomes
- Analyze experiment results and surface actionable insights
- Monitor KPI progress and flag risk indicators to the team

### Goals
- Data-informed decisions throughout the delivery lifecycle
- Reliable, well-documented instrumentation with minimal gaps
- Timely, clear outcome reports that drive iteration and learning

### Typical Communication
- Metric definition docs shared before development starts
- Dashboard links and experiment readout summaries
- KPI status updates in weekly syncs and retrospectives

### Interactions with Existing Roles
- **Developers:** aligns on event tracking requirements and implementation of instrumentation; reviews tracking plans before merge
- **Product Managers:** partners on defining success metrics, interpreting experiment results, and refining KPI frameworks
- **Project Managers:** informs on KPI progress and risk indicators that may affect scope, timelines, or release decisions

---

## Collaboration Matrix

The table below maps the primary collaboration touchpoints among OctoAcme roles across the five delivery lifecycle phases. Use it to identify who to involve—and when—for key decisions, handoffs, and reviews.

| Role | Initiation | Planning | Execution | Release | Retrospective |
|---|---|---|---|---|---|
| **Project Manager** | Kickoff facilitation, stakeholder alignment | Timeline, risk register, resource plan | Status reporting, dependency unblocking | Release coordination, go/no-go | Retrospective facilitation, action items |
| **Product Manager** | Problem statement, success metrics, scope | Backlog prioritization, acceptance criteria | Spec clarification, trade-off decisions | Release notes, stakeholder announcement | Outcome review, backlog updates |
| **Developers** | Technical feasibility input | Estimation, dependency identification | Feature implementation, code review | Deployment support, post-deploy verification | Code quality reflection, improvement proposals |
| **Engineering Manager** | Resource and capacity confirmation | Capacity planning, risk escalation | Blocker removal, coaching | Staffing for on-call/support | Capacity and process health retrospective |
| **Tech Lead / Solution Architect** | Architecture spike, ADR initiation | Technical design, non-functional requirements | Design reviews, technical risk mitigation | Architecture sign-off, deployment review | ADR review, technical debt backlog |
| **UX/UI Designer** | UX research, problem framing | User flows, design milestones | Spec handoff, design QA | Visual acceptance validation | Design quality retrospective |
| **DevOps / Platform Engineer** | Environment needs assessment | Pipeline and infra planning | CI/CD maintenance, environment support | Deployment execution, rollback readiness | Incident review, pipeline improvement |
| **Security Champion** | Threat model initiation | Security requirements in backlog | Code review, vulnerability triage | Security sign-off, scan results | Security posture retrospective |
| **Customer Success Liaison** | Customer context and pain points | Support readiness planning | Feedback relay, escalation triage | Support enablement, known-issue comms | Customer sentiment review |
| **Data Analyst / BI Partner** | Metric definition, tracking plan | Instrumentation requirements | Tracking implementation review | Dashboard readiness, experiment launch | Outcome analysis, KPI retrospective |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the [Collaboration Matrix](#collaboration-matrix) to identify which roles to involve at each lifecycle phase.

