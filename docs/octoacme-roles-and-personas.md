# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Delivery Roles

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
- **With Product Managers:** Clarify acceptance criteria, discuss technical trade-offs
- **With Project Managers:** Provide estimates, flag blockers and risks
- **With QA/Testing:** Collaborate on test strategy and bug resolution
- **With DevOps Engineers:** Coordinate deployment and infrastructure needs
- **With UX Designers:** Implement designs, provide feasibility feedback

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
- **With Project Managers:** Align on scope, priorities, and timelines
- **With Developers:** Define requirements, discuss feasibility, review solutions
- **With UX Designers:** Collaborate on user experience and feature design
- **With Stakeholders:** Communicate priorities and progress
- **With Support Lead:** Gather customer feedback and prioritize based on impact

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
- **With Product Managers:** Align on scope, timeline, and resource needs
- **With Developers:** Track progress, manage blockers, facilitate planning
- **With QA/Testing:** Schedule testing phases, manage quality checkpoints
- **With Business Analysts:** Document requirements and scope changes
- **With DevOps Engineers:** Coordinate deployment schedules and infrastructure readiness

---

### QA/Testing

#### Role Summary
QA and Testing professionals ensure quality throughout the project lifecycle by validating functionality, identifying defects, and confirming acceptance criteria are met.

#### Responsibilities
- Design and execute test plans and test cases
- Validate features against acceptance criteria
- Identify and document defects with clear reproduction steps
- Perform manual and automated testing as needed
- Conduct end-to-end and smoke tests before release
- Collaborate on quality standards and testing strategies

#### Goals
- Ensure high quality before release to production
- Reduce post-release defects and customer impact
- Provide clear visibility into quality status

#### Typical Communication
- Test plan reviews and strategy discussions
- Defect reports and quality status updates
- Test coverage metrics and risk assessments

#### Key Interactions
- **With Developers:** Report defects, collaborate on root cause analysis, validate fixes
- **With Product Managers:** Clarify acceptance criteria, discuss quality trade-offs
- **With Project Managers:** Report quality status, flag release-blocking issues
- **With DevOps Engineers:** Coordinate staging environment access and test data
- **With Technical Writers:** Validate that documentation matches actual functionality

---

## Cross-Functional Support Roles

### UX Designer

#### Role Summary
UX Designers translate product requirements into intuitive, user-centered designs. They ensure that features are usable, accessible, and consistent with design systems while collaborating closely with product and development teams.

#### Responsibilities
- Conduct user research and usability testing to inform design decisions
- Create wireframes, prototypes, and high-fidelity designs
- Establish and maintain design systems and component libraries
- Collaborate with developers to ensure design feasibility and consistency
- Provide design feedback and review code implementations for compliance
- Advocate for user needs and accessibility standards (WCAG, etc.)

#### Goals
- Deliver intuitive, user-centered product experiences
- Reduce design-to-development friction through clear specifications
- Ensure accessibility and inclusive design across all features
- Build and maintain design consistency across products

#### Typical Communication
- Design reviews and critiques
- Figma links and design specifications in PRs
- User research findings and design rationale documentation
- Accessibility checklists and design system updates

#### Key Interactions
- **With Product Managers:** Understand user needs, align on design direction, validate with research
- **With Developers:** Review implementations, provide detailed specs, iterate on technical feasibility
- **With Project Managers:** Provide design estimates, flag timeline risks for design work
- **With QA/Testing:** Validate design implementation against specs, test accessibility
- **With Stakeholders:** Present design concepts, gather feedback, demonstrate user value

---

### Technical Writer

#### Role Summary
Technical Writers ensure all technical documentation and user-facing materials are complete, accurate, clear, and accessible. They work across teams to capture and communicate product functionality, APIs, processes, and best practices.

#### Responsibilities
- Create and maintain user documentation, guides, and FAQs
- Document APIs, SDKs, and technical specifications
- Write release notes, changelog entries, and migration guides
- Review and edit documentation created by other teams
- Maintain documentation accuracy as features evolve
- Ensure documentation meets accessibility and localization standards
- Collaborate on knowledge base and support resources

#### Goals
- Enable users to understand and effectively use features
- Reduce support burden through clear, self-service documentation
- Ensure consistency and quality across all written materials
- Support product adoption and user satisfaction

#### Typical Communication
- Documentation reviews and editorial feedback
- Comments on PRs regarding documentation completeness
- Updates to knowledge bases and doc sites
- Documentation status reports and coverage metrics

#### Key Interactions
- **With Developers:** Understand implementation details, collect technical specifications, validate accuracy
- **With Product Managers:** Understand feature context, user audience, and key use cases
- **With QA/Testing:** Validate documentation against actual product behavior
- **With Project Managers:** Plan documentation timelines, coordinate release documentation
- **With Support Lead:** Ensure FAQ and troubleshooting docs address customer pain points

---

### DevOps Engineer

#### Role Summary
DevOps Engineers manage infrastructure, automate deployments, and ensure systems are reliable, secure, and scalable. They enable fast, safe releases and maintain production observability.

#### Responsibilities
- Design and maintain CI/CD pipelines and automated testing infrastructure
- Manage cloud infrastructure, containerization, and orchestration (Kubernetes, etc.)
- Implement monitoring, logging, and alerting for production systems
- Coordinate and execute production deployments
- Develop incident response and rollback procedures
- Ensure security best practices and compliance in infrastructure
- Optimize infrastructure costs and performance

#### Goals
- Enable fast, safe deployments with minimal manual effort
- Maintain high availability and performance of production systems
- Reduce time-to-detection and time-to-resolution for incidents
- Ensure infrastructure security and compliance

#### Typical Communication
- Deployment status and release coordination
- Incident post-mortems and incident response
- Infrastructure and pipeline improvements
- Monitoring dashboards and alerting configuration

#### Key Interactions
- **With Developers:** Support local development environments, troubleshoot deployment issues, communicate infrastructure requirements
- **With Project Managers:** Coordinate deployment windows, communicate infrastructure readiness
- **With QA/Testing:** Provision staging environments, manage test data, coordinate smoke test execution
- **With Security teams:** Ensure infrastructure meets security standards, manage secrets and access control

---

### Support Lead

#### Role Summary
Support Leads coordinate post-release customer support, collect and prioritize customer feedback, and ensure resolution workflows are efficient. They serve as a bridge between customers and the product/development teams.

#### Responsibilities
- Manage customer support workflows and triage processes
- Collect customer feedback, bug reports, and feature requests
- Identify patterns in support issues and escalate systemic problems
- Coordinate with development teams on issue resolution and prioritization
- Maintain support documentation and troubleshooting guides
- Track support metrics and customer satisfaction indicators
- Communicate known issues and workarounds to customers

#### Goals
- Resolve customer issues quickly and effectively
- Identify product gaps and improvement opportunities through customer feedback
- Reduce support volume through better documentation and self-service
- Maintain high customer satisfaction and retention

#### Typical Communication
- Customer feedback summaries and feature request reports
- Support metrics and issue prioritization
- Escalation notes and customer impact assessments
- Updates to FAQ and troubleshooting documentation

#### Key Interactions
- **With Product Managers:** Communicate customer needs, prioritize feature requests based on impact, validate solutions
- **With Developers:** Report bugs, track issue resolution, communicate timelines to customers
- **With Project Managers:** Escalate high-impact issues, coordinate rapid fixes or workarounds
- **With Technical Writers:** Ensure documentation addresses common customer issues
- **With DevOps Engineers:** Report production incidents, coordinate incident response

---

### Business Analyst

#### Role Summary
Business Analysts gather requirements, analyze business processes, and ensure alignment between stakeholder needs and technical solutions. They act as a bridge between business stakeholders and delivery teams.

#### Responsibilities
- Conduct stakeholder interviews and requirements gathering
- Document business rules, workflows, and acceptance criteria
- Analyze process improvements and identify inefficiencies
- Create requirements specifications and traceability matrices
- Validate that solutions meet business objectives
- Identify and document scope changes and impacts
- Support project planning with effort estimates and risk identification

#### Goals
- Ensure requirements are clear, complete, and traceable
- Reduce scope creep and rework through thorough analysis
- Enable team alignment on business objectives
- Support data-driven decision-making with analysis and metrics

#### Typical Communication
- Requirements documents and specification updates
- Stakeholder meeting summaries and action items
- Scope change requests and impact assessments
- Process flow diagrams and traceability matrices

#### Key Interactions
- **With Project Managers:** Define scope, create requirement specifications, manage change requests
- **With Product Managers:** Clarify business objectives, validate user stories align with business needs
- **With Developers:** Answer clarification questions, validate implementations against requirements
- **With Stakeholders:** Gather requirements, communicate timelines and trade-offs
- **With QA/Testing:** Define acceptance criteria, collaborate on test case creation

---

## Role Interaction Matrix

| Phase | Key Interactions | Coordination Points |
|-------|------------------|-------------------|
| **Initiation** | PM, PdM, BA, Stakeholders | Business case, scope, objectives |
| **Planning** | PM, PdM, BA, Dev, Designer, Tech Writer | Requirements, design, documentation, estimates |
| **Design** | Designer, Dev, PdM, Tech Writer | Design specifications, usability, feasibility |
| **Development** | Dev, DevOps, BA, PM, QA | Code quality, infrastructure, progress tracking |
| **Testing** | QA, Dev, Designer, Tech Writer, PM | Test coverage, defect resolution, release readiness |
| **Release** | DevOps, PM, Dev, Support, Tech Writer | Deployment, release notes, rollback plans |
| **Post-Release** | Support, PdM, Dev, Tech Writer, BA | Customer feedback, bug fixes, lessons learned |

---

## How These Personas Are Used in the Exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Key Interactions section to understand collaboration patterns and dependencies.
- Use the Role Interaction Matrix to visualize which roles collaborate during each project phase.
