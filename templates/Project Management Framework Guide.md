# Project Management Framework Guide

A phased, PMI-based and Agile-executed delivery model for software projects.

Prepared by Mahmoud Ghanem, Project Manager | moghanem345@gmail.com | +20 01093924681

Version 3.0

## 1. Executive Summary

Every project runs through eight phases, and each phase ends with a written approval that the next phase cannot start without. The model separates what is uncertain (scope, design, cost) from what is predictable (build, test, release), so the client prices real work rather than assumptions.

Cost is fixed only after scope and design are approved. Until then, the client sees an indicative range and pays small, fixed fees for the phases that remove uncertainty.

| The client receives | The client commits to |
| --- | --- |
| A signed scope document before any design starts | One decision-maker who can approve in writing |
| Approved designs before development cost is fixed | Feedback within 24 hours |
| A fixed price built from real estimates | Milestone payments on schedule |
| Working features demonstrated every sprint | Access, content and third-party accounts on time |
| A weekly written status with risks and decisions needed | Changes raised through change control, not chat |
| A tested, documented product and a warranty period | Acceptance testing inside the agreed window |

Three rules hold the model together:

- No design starts before the Scope Definition Document is approved.
- No development starts before the plan, cost and contract are approved and the first payment is received.
- No change is built before its impact on time and cost is analyzed and approved in writing.

Section 2 defines roles and gates, Section 3 shows the whole lifecycle, Sections 4 to 11 detail each phase, Sections 12 to 14 cover the controls that run across phases, and Sections 15 and 16 cover commercial terms and sign-off. Templates are indexed in Appendix A and detailed in Appendix B.

## 2. Operating Model: Principles, Roles and Gates

The model runs on seven principles, clear decision rights and six approval gates, and adapting it to a project changes the weight of the process, never the gates.

### Principles

1. **Scope before design.** Nobody designs what has not been defined and signed.
2. **Cost follows design.** Development is priced only when designs make the work visible.
3. **Written approvals.** An approval counts when the authorized client contact gives it in writing.
4. **Small increments.** Work is delivered and demonstrated in short cycles, so errors surface early.
5. **Early risk visibility.** Risks are logged in Phase 1, reviewed weekly and reported before they become issues.
6. **One source of truth.** One tracker, one versioned document set, one channel for decisions.
7. **Proportionate process.** Ceremonies and documents scale with project size; gates do not.

### Roles and decision rights

On small projects one person can hold several roles, but the accountability column does not change.

| Activity | Client contact | Project Manager | Designer | Tech lead | QA |
| --- | --- | --- | --- | --- | --- |
| Scope approval | A | R | I | C | I |
| Design approval | A | R | R | C | I |
| Estimate and plan | A | R | C | R | C |
| Sprint delivery | C | A | C | R | R |
| Change requests | A | R | C | C | I |
| UAT sign-off | A | R | I | C | R |
| Go-live decision | A | R | I | R | C |

R = does the work. A = accountable and approves. C = consulted. I = informed.

### Approval gates

| Gate | Closes | Evidence required | Approver |
| --- | --- | --- | --- |
| G1 Proposal accepted | Phase 0 | Initial proposal accepted, first 50% of the scope fee paid | Client sponsor |
| G2 Scope signed | Phase 1 | Signed Scope Definition Document, prioritized feature list, WBS | Client sponsor |
| G3 Design approved | Phase 2 | Approved wireframes and approved high-fidelity UI | Client sponsor |
| G4 Plan and cost approved | Phase 3 | Signed contract, development plan, final cost, first milestone paid | Client sponsor |
| G5 Release approved | Phase 5 | UAT sign-off, exit criteria met, go-live checklist complete | Client sponsor |
| G6 Project closed | Phase 7 | Handover pack delivered, final report, closure sign-off | Client sponsor |

Inside Phase 4, each sprint demo is a smaller acceptance point that releases the matching milestone.

## 3. Lifecycle at a Glance

The project moves through eight phases and six approval gates, and the price becomes fixed only at Phase 3.

&#91;embedded content: project lifecycle · 8 phases, 6 approval gates\]

Gates G1 to G6 and the evidence each needs are listed in Section 2. Inside Phase 4, each sprint demo releases the matching milestone payment.

## 4. Phase 0: Pre-Sales, Discovery and Initial Proposal

Phase 0 is free and ends when the client accepts an initial proposal, or when both sides decide not to proceed. The goal is to protect both parties from investing in a project that does not fit.

### Qualify the opportunity

Before the meeting, the PM checks six points. Two or more weak answers are a reason to decline or to reshape the offer.

- A clear business problem, not only a feature wish list
- A named decision-maker
- A budget range that is plausible for the described scope
- A realistic timeline
- Technology and domain the team can deliver
- Willingness to pay for Phase 1

### Discovery meeting

One meeting, prepared with a written agenda. The PM sends discovery notes within 24 hours and the client confirms them.

| Topic | Questions to answer |
| --- | --- |
| Business goals | What outcome defines success, and how will it be measured? |
| Users | Who uses it, how often and on which devices? |
| Scope | Which features are essential? Is there an existing system, design or code? |
| Constraints | What drives the deadline? What is the budget range? Any compliance or language needs? |
| Integrations | Payments, ERP, maps, messaging, other third-party services |
| Stakeholders | Who decides, who approves, who is affected? |
| Risks | What has failed before, and what worries the client most? |

### Indicative estimate

The PM builds a rough order of magnitude with the tech lead and the designer. It lists modules, gives a low and high figure for each, and adds a contingency (suggested 20 to 40% at this stage, because detail is thin). It is shared as a range for budget and timeline, clearly marked non-binding.

### Initial proposal

The proposal is short and contains:

- Client needs, restated in the client's own terms
- Assumptions
- Initial scope and a first out-of-scope list
- Proposed phases and approval gates
- Indicative budget and timeline range
- The Phase 1 fixed fee and what it produces
- Validity period (suggested: 14 days) and the next step

### Gate G1: proceed or stop

The client accepts the proposal and pays the first 50% of the Phase 1 fee. The PM records the decision and opens the project in the tracker. If sales and delivery are different people, a handover checklist records what was promised, what was shared, who the contacts are and which risks were heard.

## 5. Phase 1: Scope Definition and Planning (Paid)

Phase 1 turns an idea into a signed blueprint in about five working days, at a fixed fee, before any design starts. It aligns the parties, reduces risk and gives design and estimation a reliable base.

### Five-day plan

| Day | Focus | Output |
| --- | --- | --- |
| 1 | Kickoff, stakeholders, goals and success criteria | Stakeholder register, draft RACI, goals and KPIs |
| 2 | Requirements sessions on users, business flows and user flows | Flow diagrams, draft requirement list |
| 3 | Requirements sessions on features, integrations and non-functional needs | Feature list v1, integration list, non-functional requirements |
| 4 | Prioritization (MVP versus later), WBS, risks and assumptions | Prioritized feature list, WBS, risk register, assumptions log |
| 5 | Client review of the draft and corrections | Scope Definition Document issued for signature |

These are days of working effort. The calendar stretches when the client is slow to respond, which is why Section 14 sets response times.

### What the Scope Definition Document contains

1. Business context and goals
2. Success criteria and KPIs
3. Users and roles
4. In-scope features by module, each with acceptance criteria
5. Explicit out-of-scope list
6. MVP and later phases
7. Integrations and third-party services
8. Non-functional requirements: performance, security, languages, devices
9. Assumptions, constraints and dependencies
10. Initial risks
11. Glossary
12. Approval record

### Prioritization

Features are ranked Must, Should, Could or Won't (this release). A common rule of thumb keeps Must items to about 60% of total effort, which leaves room for Should items and contingency. The MVP is the set of Must items, agreed with the client in the workshop.

### Deliverables and acceptance

- Scope Definition Document (signed)
- Detailed Feature List (prioritized)
- Work Breakdown Structure (WBS)
- Assumptions and Constraints Log
- Initial Risk Register
- Stakeholder Register and Communication Plan

The phase is complete when every in-scope feature has acceptance criteria, every assumption has an owner and the out-of-scope list has been reviewed with the client.

### Price and payment

The fee is fixed and covers meetings, documentation, stakeholder alignment and review. It is built from the estimated hours per day, the number of days, the scope complexity and the level of collaboration required.

Illustrative example: 2 hours per day × 5 days = 10 hours, multiplied by the applicable hourly rate, gives the fixed fee. The fee is confirmed in writing before the phase starts and changes only if the agreed assumptions change, such as more sessions, more stakeholders or a wider scope. Any change is agreed before the extra work begins.

- 50% before the phase starts
- 50% on delivery of the Scope Definition Document

### Gate G2 and scope control

No design work begins until the Scope Definition Document is reviewed and approved in writing. Any requirement not documented and approved here is out of scope and goes through change control (Section 12).

> This phase ensures that all future work is built on a clear, validated foundation, saving time, cost and rework during design and development.

## 6. Phase 2: UI/UX Design

Phase 2 produces approved designs in two stages, wireframes first and high-fidelity UI second, so structural feedback arrives before visual polish. Each stage has its own written approval.

### Workflow

1. Design kickoff: review the scope document, user flows, references and brand assets.
2. Low-fidelity wireframes for every in-scope screen.
3. Client review and written low-fidelity approval.
4. High-fidelity UI with a style guide: colors, typography, components and states.
5. Clickable prototype of the key flows.
6. Client review, iteration and written high-fidelity approval.
7. Developer handoff: specifications, assets and component library.

### Feedback protocol

- The client sends one consolidated list per round, through the single point of contact.
- The PM sorts each item within one working day into a revision, a clarification or a change request.
- Two minor revisions per phase are included.
- Conflicting feedback goes to the sponsor to decide.

### Deliverables

- Approved wireframes
- Final UI designs
- Clickable prototype
- Style guide and component library
- Developer handoff package
- Screen inventory mapped to scope features

### Developer handoff checklist

- [ ] Every screen maps to a feature in the WBS
- [ ] All states are designed: empty, loading, error and success
- [ ] Responsive behavior is defined for each supported device size
- [ ] Assets are exported and named consistently
- [ ] The tech lead has walked through the designs with the designer

### Price and payment

Project management is a fixed fee for design coordination, reviews and alignment, typically about 25% of the designer's total effort. The design fee comes from the designer's detailed estimate and depends on the number of screens, their complexity and the iterations expected.

- 50% before starting
- 25% after low-fidelity approval
- 25% after high-fidelity approval

### Gate G3

No estimate is finalized and no development starts before high-fidelity approval. Changes after approval follow change control (Section 12).

## 7. Phase 3: Estimation, Cost Finalization and Contract

Phase 3 fixes the development price only after designs are approved, because that is the first point where the work is visible enough to estimate fairly. The result is a single fixed project cost built from real data.

### Method

1. Technical breakdown: convert screens and features into tasks by layer, such as backend, web or mobile front end, integrations, DevOps and QA.
2. Bottom-up estimates from the developers who will build it. Uncertain items get a three-point estimate.
3. Non-coding effort added by the PM: project management (typically 10 to 15%), QA, DevOps, documentation, UAT support and rework.
4. Risk review and a contingency allowance (suggested 10 to 30%, depending on uncertainty).
5. Timeline: effort divided by team capacity, adjusted for dependencies and client review time.
6. Review by the tech lead and the PM for gaps, and a comparison with similar past projects.

The three-point estimate for an item, where O is optimistic, M most likely and P pessimistic:

```latex
E = \frac{O + 4M + P}{6}
```

### Fixed price build-up

| Cost line | Basis | Status at approval |
| --- | --- | --- |
| PM planning | Effort in this phase | Fixed |
| Development | Developer estimates by module | Fixed |
| QA and UAT support | Test plan effort | Fixed, included |
| Deployment | Release effort and environment setup | Estimated, then fixed in the price |
| Closing | Handover, documentation, retrospective | Estimated, then fixed in the price |
| Contingency | Risk-based allowance | Shown openly |
| Third-party costs | Hosting, licenses, app store fees, SMS and email, gateway fees | Listed separately, paid by the client |

Estimated lines such as deployment and closing are consolidated into the fixed price, and the allowance is stated openly, so the client sees what the fixed price contains.

### Deliverables

- Development Plan: milestones, sprint structure and team
- Final Timeline
- Final Cost Breakdown
- Contract or Statement of Work
- Kickoff readiness checklist

### Development kickoff readiness

- [ ] Contract signed and first milestone paid
- [ ] Plan, timeline and cost approved in writing
- [ ] Team assigned and available
- [ ] Tracker, repositories and environments set up
- [ ] Third-party accounts and credentials requested from the client
- [ ] Communication plan confirmed
- [ ] Definition of Done agreed

### Gate G4

No development starts before full written approval of the plan, timeline and cost, the signed contract and receipt of the first payment.

## 8. Phase 4: Development and Execution

Phase 4 delivers the product in short sprints (suggested: two weeks), with a client demo at the end of each so that misunderstandings are caught while they are cheap to fix.

### Sprint cadence

| Ceremony | When | Participants | Output |
| --- | --- | --- | --- |
| Sprint planning | Start of sprint | PM, team, client contact for priorities | Sprint goal and committed items |
| Daily follow-up | Daily, 15 minutes | Team and PM | Blockers surfaced |
| Backlog refinement | Mid-sprint | PM, tech lead, client contact | Next sprint items ready, with acceptance criteria |
| Sprint review and demo | End of sprint | Team and client | Features accepted or returned, with feedback |
| Retrospective | After the review | Team | Improvement actions |
| Weekly status report | Weekly | PM to client | Written status (Section 13) |

### Definition of Done

A feature is done when all of the following are true:

- It matches the approved design and acceptance criteria
- Peer code review has passed
- Unit and functional tests have passed
- QA has verified it in a staging environment
- No critical or high-severity defect is open against it
- It has been demonstrated to the client
- Documentation is updated

### Quality practices

- Version control with branch and pull request rules
- Automated build and tests on each merge where feasible
- Separate development, staging and production environments
- Security basics reviewed: access control and data handling
- Performance checked on the key user flows

### The PM's operating rhythm

- Track burndown and velocity, and compare them with the plan every week
- Keep every task traceable to the WBS and the approved scope
- Review the risk register weekly (Section 12)
- Clear blockers within one working day or escalate them
- Shield the team from ad-hoc requests by routing them through change control
- Record decisions in the tracker and update the plan after every approved change

### Milestones and payment

Milestones are defined in the Development Plan. Each one groups a set of features with an amount, and becomes payable when the client accepts those features. Suggested acceptance window: five working days after the demo, with a reminder before silence is treated as acceptance.

## 9. Phase 5: Testing and UAT

Testing runs inside every sprint, and Phase 5 is the final hardening window that ends with the client's signed acceptance. Nothing is released without it.

### Test levels

| Level | Owner | Purpose |
| --- | --- | --- |
| Unit and integration | Developers | Logic works and components work together |
| Functional and regression | QA | Features meet acceptance criteria and earlier features still work |
| Cross-device and browser | QA | Supported devices and browsers behave correctly |
| Security and performance checks | Tech lead and QA | Basic protection and speed on key flows |
| User acceptance testing (UAT) | Client | The product meets the business need in real use |

### Defect severity

| Severity | Definition | Release rule |
| --- | --- | --- |
| Critical | System down, data loss or security flaw, no workaround | Fixed before release, worked on immediately |
| High | Core feature broken, no practical workaround | Fixed before release |
| Medium | Feature impaired, reasonable workaround exists | Fixed, or accepted in writing by the client |
| Low | Cosmetic or minor | Backlog, or fixed if time allows |

Response times per severity are set in the Development Plan.

### UAT process

1. The PM and the client agree the UAT scope, scripts and window (suggested: five working days).
2. QA prepares test data and a UAT environment.
3. The client runs the scripts and logs issues in the tracker.
4. The team triages daily, fixes and retests.
5. The client signs the UAT acceptance.

### Exit criteria for Gate G5 (part 1)

- All in-scope features tested against their acceptance criteria
- Zero open critical or high defects
- Medium and low defects fixed or accepted in writing
- Regression suite passed
- UAT sign-off signed

Deliverables are the test report, the defect log and the UAT sign-off.

## 10. Phase 6: Deployment and Go-Live

Phase 6 releases the product through a checked go-live process, with a rollback plan ready and the team on hand afterward. Most go-live problems come from missing accounts and credentials, so these are prepared early.

### Production prerequisites

- Hosting and infrastructure
- Domain, DNS and SSL certificates
- Email, SMS and notification providers
- Live payment gateway credentials
- Analytics, monitoring and backup services
- App store developer accounts and store listings, where mobile apps are in scope

Suggested practice: accounts are created in the client's name so ownership is clear from day one.

### Go-live readiness checklist

- [ ] UAT signed and no critical or high defects open
- [ ] Production environment configured and verified
- [ ] Data migration tested, if applicable
- [ ] Backups taken and a restore tested
- [ ] Rollback plan written and rehearsed
- [ ] Release notes and client communication prepared
- [ ] Monitoring and alerts active
- [ ] Support contacts and roles confirmed for release day
- [ ] Client go-live approval received (Gate G5, part 2)

### Release steps

1. Confirm go or no-go with the client.
2. Freeze changes.
3. Deploy to production using the release checklist.
4. Smoke-test the critical flows.
5. Announce go-live.
6. Monitor. If the smoke tests fail, roll back as planned.

### Hypercare

For the first working days after go-live (suggested: five), the team monitors the system daily, triages issues quickly and sends the client a short daily update.

### Deliverables and payment

The deliverables are the live product and the deployment documentation. The final milestone payment is due on go-live acceptance.

## 11. Phase 7: Closing, Handover and Warranty

Phase 7 transfers everything the client needs to own and run the product, and closes the project formally so that nothing is left open.

### Handover pack

- Source code repository access and branch structure
- Inventory of environments and credentials, transferred securely
- Architecture overview and deployment guide
- User and admin guides, and API documentation where relevant
- Test report and known-issues list
- List of third-party accounts and who owns each
- Design files and style guide

### Closing activities

1. Handover session with the client team, with training where agreed.
2. Final report: scope delivered against plan, timeline and cost against plan, approved changes, issues and how they were resolved, quality results and recommendations.
3. Retrospective with the team and, ideally, the client.
4. Lessons learned recorded and shared.
5. Cost reconciliation and final invoice.
6. Team released and project artifacts archived.
7. Closure sign-off by the client (Gate G6).

### Warranty and support

Defects in delivered, approved scope are fixed at no charge during a warranty period (suggested: 30 days after go-live). The warranty does not cover new features, changes to approved scope, failures of third-party services or misuse.

After the warranty, support continues under a separate agreement, either a monthly retainer or time and materials, or through change control.

### Relationship follow-up

- A check-in call about 30 days after go-live
- A short client satisfaction survey
- Permission to use the project as a case study
- A discussion of the next phase or roadmap items

## 12. Project Controls: Risk, Issues, Change and Scope

Four controls keep a fixed price and Agile delivery compatible: risk management, issue escalation, change control and scope protection.

### Risk management

The register is created in Phase 1 and reviewed every week. Each risk is scored as likelihood times impact, each rated 1 to 3, and scores of 6 and 9 are reviewed with the sponsor.

1. Identify risks in Phase 1 and at every sprint planning.
2. Assess likelihood and impact.
3. Choose a response: avoid, mitigate, transfer or accept.
4. Assign an owner and a due date for the response.
5. Review weekly and report the top risks to the client.

The register records the risk ID, description, likelihood, impact, score, response, owner and status. Typical software risks to watch:

- Unclear or changing requirements
- Slow client feedback or approvals
- Third-party API or app store delays
- Key person unavailable
- Scope creep through informal requests
- Under-estimated integrations

### Issue escalation

An issue is a risk that has happened. Suggested response times:

| Level | Who handles it | Trigger | Target |
| --- | --- | --- | --- |
| 1 | Tech lead and PM | Blocks a task or sprint item | Resolved within 1 working day |
| 2 | PM and client contact | Affects the plan or needs a client decision | Decision within 2 working days |
| 3 | Sponsors | Threatens scope, timeline or cost | Decision within 3 working days |

### Change control

Included: up to two minor revisions per phase. A minor revision adjusts an already approved item without changing its function, flow or structure, such as copy, colors, spacing or small layout tweaks.

Not included: new features, major changes, and changes to approved scope, flows or integrations.

1. The client submits the change request form.
2. The PM logs it with an ID.
3. Impact analysis on scope, time, cost and risk (suggested: within two working days).
4. The client approves or rejects in writing.
5. The team implements, and the PM updates the scope document, plan and budget.

The form records the ID, date, requester, description, reason, affected items, effort, timeline and cost impact, risks, decision, approver and date. In Agile execution, an item of equal effort can be swapped for an unstarted one at no extra cost. A critical defect on a live system is fixed first and documented afterward.

Rule: no change is implemented without full written approval.

### Scope protection

Any work not explicitly defined in the approved Scope Definition Document is out of scope. Third-party costs such as hosting, licenses, app store fees, messaging services and gateway fees are excluded unless they appear in the Final Cost Breakdown.

A changed assumption in the assumptions log triggers re-estimation. When someone asks for "one small addition" in a call or chat, the PM logs it and routes it through change control.

## 13. Communication and Reporting

The client sees progress, risks and the decisions needed every week, in writing, so nobody learns about a problem for the first time at a demo.

### Cadence

| Forum | Frequency | Audience | Purpose |
| --- | --- | --- | --- |
| Kickoff | Start of the engagement and of Phases 1 and 4 | All stakeholders | Align goals, roles and working rules |
| Weekly sync | Weekly, 30 minutes | Client contact, PM, tech lead | Progress, decisions, risks |
| Sprint review | Every sprint | Client stakeholders and team | Demo and acceptance |
| Phase gate review | End of each phase | Sponsor and PM | Approve or correct before the next phase |
| Sponsor update | Monthly or at milestones, for larger projects | Sponsor | Budget, timeline and risk overview |

### Weekly report content

1. Overall health for scope, timeline and cost
2. Work completed this week
3. Work planned for next week
4. Milestone progress
5. Top risks and issues, each with an owner
6. Decisions or inputs needed from the client, with due dates
7. Pending change requests
8. Effort and budget used against plan

### Health status

| Status | Meaning | Action |
| --- | --- | --- |
| Green | On track, no help needed | Continue |
| Amber | At risk, but recoverable within the PM's control | PM presents a recovery plan in the report |
| Red | Off track, a sponsor decision is needed | Escalate within one working day |

### Working rules

- One agreed channel for decisions, so nothing is lost in informal chats
- Meeting notes and decisions sent within 24 hours
- One shared document set with version numbers
- A shared tracking board the client can open at any time

## 14. Client Responsibilities and Timeline Dependencies

Delivery dates hold only when the client answers quickly and decides clearly, so these duties are part of the agreement.

### Client responsibilities

- Give feedback within 24 hours
- Assign a single point of contact with authority to approve
- Give formal approvals on time (suggested: within three working days)
- Provide clear requirements and answer questions promptly
- Supply content, brand assets and test data
- Provide access to systems and APIs the project depends on
- Create or authorize the required third-party accounts
- Attend demos and take part in UAT
- Pay milestones on schedule

### What delays cause

All timelines depend on client responsiveness and approval speed. Suggested consequences:

| Situation | Effect |
| --- | --- |
| Feedback up to 5 working days late | Timeline shifts by the same period, and the team may be rescheduled |
| Feedback more than 5 working days late | The project pauses, and restart depends on team availability |
| Missing content or credentials | Dependent tasks wait and the timeline shifts |
| Late payment | Work pauses until payment is received |
| Scope change | Impact analysis and a revised timeline through change control |

The PM reports each client dependency in the weekly report, so the client sees the cost of a delay before it happens.

## 15. Commercial Terms

Fees are fixed per phase and paid in stages tied to approvals, so the client pays for verified progress.

### Payment schedule

| Phase | Fee type | Payment schedule |
| --- | --- | --- |
| 0. Discovery and proposal | Free | None |
| 1. Scope Definition | Fixed, PM effort | 50% before the phase, 50% on delivery of the Scope Definition Document |
| 2. UI/UX Design | PM fixed fee (about 25% of design effort) plus design estimate | 50% before the phase, 25% after low-fidelity approval, 25% after high-fidelity approval |
| 3. Estimation and contract | PM planning fee | Agreed before the phase starts |
| 4. Development | Fixed total from the approved estimate | Milestone-based, on accepted feature delivery |
| 5 to 7. Testing, deployment, closing | Included in the fixed price | Final milestone on go-live acceptance |

### Pricing mechanics

- Hourly rates by role are listed in the contract
- PM effort is shown as its own line
- Contingency is visible, not hidden in rates
- Third-party costs are passed through at cost and paid by the client
- Currency and taxes are stated on every estimate
- Estimates stay valid for a stated period (suggested: 30 days)

### Terms to confirm in the contract

- Invoice payment period (suggested: seven days)
- Work pauses when payment is late
- Source code and designs transfer to the client on full payment
- Third-party and open-source licenses stay with their owners
- Both parties keep project information confidential
- If the project is cancelled, completed work is billed and completed deliverables are handed over once payment is received
- Warranty terms as in Section 11
- Dispute path: sponsors first, then the process in the contract

This guide is not a contract. A lawyer should review the final contract wording, including liability and governing law.

## 16. Agreement and Sign-Off

Proceeding with a project means both parties accept the defined scope, the payment structure, the delivery model and the change control process. A signed contract or Statement of Work remains the binding document for each project.

|  | Client | Service provider |
| --- | --- | --- |
| Name |  |  |
| Title |  |  |
| Signature |  |  |
| Date |  |  |

## Appendix A: Templates and Artifacts by Phase

Every phase has a named artifact set, so nothing depends on memory or goodwill.

| Phase | Artifacts and templates | Owner |
| --- | --- | --- |
| 0. Discovery | Qualification checklist, discovery agenda and notes, rough estimate sheet, initial proposal, handover checklist | PM |
| 1. Scope Definition | Scope Definition Document, feature list with priorities, WBS, assumptions log, risk register, stakeholder register, RACI, communication plan | PM |
| 2. Design | Wireframes, UI designs, prototype, style guide, handoff package, feedback log | Designer, PM |
| 3. Estimation | Estimation workbook, development plan, timeline, cost breakdown, contract or SOW, kickoff readiness checklist | PM, tech lead |
| 4. Development | Sprint backlog, sprint goals, demo notes, weekly report, decision log, Definition of Done | PM, team |
| 5. Testing and UAT | Test plan, test cases, defect log, UAT scripts, test report, UAT sign-off | QA, PM |
| 6. Deployment | Release checklist, deployment and rollback plan, release notes, go-live approval, deployment documentation | Tech lead, PM |
| 7. Closing | Handover pack, final report, lessons learned, closure sign-off, warranty terms | PM |
| All phases | Risk register, change request form and log, weekly status report, approval log | PM |

## Appendix B: Document Library

This library lists every document the project needs, who owns it, when it is due and what it must contain. Appendix A is the index, and this appendix is the detail.

### Document control rules

- **Naming:** project code, document name, version and status, for example PRJ01-Scope-Definition-v1.2-Approved.
- **Versions:** v0.x is a draft, v1.0 is the first approved version, and every approved change raises the number.
- **Status:** Draft, In review, Approved or Superseded. Only Approved documents are used for work.
- **Approval record:** the approver's name, date and the version approved, kept in the approval log (Section B.5).
- **Storage:** one shared folder per project with a subfolder per phase. Old versions stay, marked Superseded.
- **Ownership:** each document has one owner who keeps it current. The PM owns anything without a named owner.
- **Access:** the client sees client-facing documents. Internal estimates, rates and team notes stay internal.

### B.1 Phase 0 and Phase 1: Discovery and Scope

These documents take a project from first contact to a signed scope, and most disputes later trace back to something missing here.

#### Phase 0 documents

| Document | Purpose and timing | Must contain | Owner |
| --- | --- | --- | --- |
| Qualification checklist | Decides fit before time is invested; before the discovery meeting | Business problem, decision-maker, budget range, timeline, capability fit, willingness to pay for Phase 1, go or no-go note | PM |
| Discovery agenda | Keeps the meeting focused; sent one day before | Goals, topics and questions from Section 4, attendees, time limit | PM |
| Discovery notes | Records what was said; sent within 24 hours and confirmed by the client | Goals, users, features, constraints, integrations, stakeholders, risks, open questions, next steps | PM |
| Rough estimate sheet (internal) | Basis for the indicative range; before the proposal | Modules, low and high effort per module, contingency, assumptions, timeline range | PM, tech lead |
| Initial proposal | The offer for Phase 1; after the estimate | Needs, assumptions, initial scope and out-of-scope list, phases and gates, indicative range marked non-binding, Phase 1 fee, validity period, next step | PM |
| Handover checklist | Moves information from sales to delivery; at Gate G1 | Promises made, documents shared, contacts, risks heard, commercial terms discussed | Sales, PM |

#### Phase 1 documents

| Document | Purpose and timing | Must contain | Owner |
| --- | --- | --- | --- |
| Kickoff brief | Aligns goals and working rules; Day 1 | Goals, success criteria, scope summary, team, timeline, governance, communication rules | PM |
| Stakeholder register | Shows who matters and how to engage them; Day 1 | Name, role, organization, interest, influence, expectations, contact, preferred channel | PM |
| RACI matrix | Fixes decision rights; Day 1, finalized by Day 5 | Activities, roles and R, A, C or I for each | PM |
| Requirements log | Captures needs before they are formalized; Days 2 and 3 | ID, requirement, source, priority, status, acceptance criteria | PM |
| User and business flow diagrams | Show how the product is used; Day 2 | Actors, steps, decisions, exceptions, system touchpoints | PM, designer |
| Prioritized feature list | Separates MVP from later releases; Day 4 | Feature ID, module, description, Must, Should, Could or Won't rank, effort size, dependencies, release | PM |
| Work Breakdown Structure | Breaks scope into work packages; Day 4 | Levels from project to work package, IDs, deliverable per package | PM |
| Assumptions and constraints log | Makes hidden premises visible; Day 4, kept current | ID, assumption or constraint, owner, date, impact if wrong, status | PM |
| Initial risk register | Early view of what could go wrong; Day 4 | Fields listed in B.5 | PM |
| Communication plan | Defines who gets what and when; Day 5 | Audience, information, format, frequency, channel, owner | PM |
| Scope Definition Document | The signed blueprint; issued Day 5 for Gate G2 | The twelve sections listed in Section 5, plus the approval record | PM |

### B.2 Phase 2 and Phase 3: Design, Estimate and Contract

These documents turn an approved scope into approved designs, and approved designs into a fixed price the client has signed.

#### Phase 2 documents

| Document | Purpose and timing | Must contain | Owner |
| --- | --- | --- | --- |
| Design brief | Aligns the designer with scope and brand; at design kickoff | Goals, users, key flows, brand assets, references, constraints, screen list | PM, designer |
| Screen inventory | Maps screens to features; before wireframes | Screen ID, name, linked feature ID, user role, priority | Designer, PM |
| Low-fidelity wireframes | Show structure and flow; first approval | Every in-scope screen, navigation, key content blocks, annotations | Designer |
| Wireframe approval record | Evidence for the first design approval | Version approved, approver, date, feedback rounds used | PM |
| High-fidelity UI designs | Show the final look; second approval | Every screen in all states, responsive variants, final content | Designer |
| Style guide and component library | Keeps design consistent and speeds development | Colors, typography, spacing, icons, components with states | Designer |
| Clickable prototype | Lets the client test key flows before build | Linked screens for the main user journeys | Designer |
| Feedback log | Tracks every design comment and its outcome | ID, date, comment, type (revision, clarification or change request), decision, status | PM |
| Design handoff package | Gives developers everything needed to build | Final designs, assets, specifications, state coverage, tech lead walkthrough note | Designer, tech lead |
| High-fidelity approval record | Evidence for Gate G3 | Version approved, approver, date | PM |

#### Phase 3 documents

| Document | Purpose and timing | Must contain | Owner |
| --- | --- | --- | --- |
| Technical breakdown | Converts designs into buildable work | Tasks by layer (backend, front end, mobile, integrations, DevOps, QA), dependencies, technical decisions | Tech lead |
| Estimation workbook (internal) | Basis for the fixed price | Task estimates (optimistic, most likely, pessimistic), non-coding effort, contingency, rates, assumptions | Tech lead, PM |
| Technical architecture note | Records key technology choices | Stack, hosting, integrations, security approach, environments | Tech lead |
| Development plan | Shows how the build will run | Milestones, sprint structure, team and roles, feature-to-milestone map, dependencies, risks | PM |
| Final timeline | Gives committed dates | Phase and milestone dates, client input deadlines, assumptions behind the dates | PM |
| Final cost breakdown | Explains the fixed price | Lines from the price build-up in Section 7, contingency, third-party costs, payment milestones | PM |
| Contract or Statement of Work | The binding agreement | Scope reference, price, payment schedule, change control, warranty, IP, confidentiality, termination, signatures | PM, legal |
| Third-party account list | Prevents go-live surprises | Service, purpose, account owner, who creates it, needed by date, cost | PM, tech lead |
| Kickoff readiness checklist | Confirms the build can start | Items listed in Section 7, each ticked with a date | PM |
| Plan and cost approval record | Evidence for Gate G4 | Versions approved, approver, date, first payment received | PM |

### B.3 Phase 4: Development and Execution

The build phase produces a steady stream of small records, and keeping them current is what makes progress visible and disputes rare.

| Document | Purpose and timing | Must contain | Owner |
| --- | --- | --- | --- |
| Product backlog | The single list of all work; kept current all phase | Item ID, feature link, description, acceptance criteria, priority, estimate, status | PM |
| Sprint plan | Commits the team to a goal; start of each sprint | Sprint goal, selected items, capacity, risks, dependencies | PM, tech lead |
| Sprint board | Shows live status; updated daily | Items by status (to do, in progress, in review, in test, done), owner, blockers | Team |
| Daily blocker list | Tracks obstacles raised in stand-ups | Blocker, owner, date raised, action, target date | PM |
| Sprint review and demo notes | Records what was shown and decided; after each demo | Items demonstrated, accepted or returned, feedback, decisions, follow-ups | PM |
| Milestone acceptance record | Releases the matching payment | Milestone, features included, acceptance date, approver, payment trigger | PM |
| Retrospective notes | Captures improvements; after each sprint | What worked, what did not, actions, owners, due dates | PM |
| Velocity and burndown report | Shows pace against plan | Planned versus completed points or items, trend, forecast to milestone | PM |
| Weekly status report | Keeps the client informed; every week | Content listed in Section 13 | PM |
| Technical decision log | Preserves the reasons for design choices | Decision, options, choice, reason, date, owner | Tech lead |
| Environment and release log | Tracks what is deployed where | Environment, version, date, deployed by, changes included | Tech lead |
| Updated plan and scope baseline | Reflects every approved change | Revised dates, costs and scope after each approved change request | PM |

### B.4 Phase 5, 6 and 7: Testing, Release and Closure

The final three phases produce the evidence that the product works, that it was released safely and that the project is complete.

#### Phase 5 documents

| Document | Purpose and timing | Must contain | Owner |
| --- | --- | --- | --- |
| Test plan | Defines how quality is verified; start of the project, updated before UAT | Scope, test levels, environments, tools, entry and exit criteria, roles, schedule | QA |
| Test cases | Verify each acceptance criterion | ID, linked feature, steps, expected result, priority, result | QA |
| Defect log | Tracks every defect to closure | ID, description, severity, steps to reproduce, owner, status, found and fixed dates | QA |
| UAT plan and scripts | Lets the client verify real use | Scope, test window, scenarios, step-by-step scripts, who tests what, how issues are logged | QA, PM |
| Test report | Summarizes the results | Tests run and passed, defects by severity, open items and acceptance, regression result, recommendation | QA |
| UAT sign-off | Client acceptance of the product | Version tested, scripts completed, open items accepted in writing, approver, date | PM |

#### Phase 6 documents

| Document | Purpose and timing | Must contain | Owner |
| --- | --- | --- | --- |
| Release checklist | Makes go-live repeatable | Items from the go-live checklist in Section 10, owner and tick date for each | Tech lead, PM |
| Deployment plan | Describes how the release is executed | Steps, order, responsible people, timings, communication points | Tech lead |
| Rollback plan | Defines how to undo a failed release | Trigger conditions, steps, data handling, who decides, time limit | Tech lead |
| Release notes | Tells users and the client what changed | Version, date, new features, fixes, known issues | PM |
| Go-live approval | Client authorization to release; part of Gate G5 | Version, date, scope released, approver | PM |
| Deployment documentation | Lets others operate and redeploy the product | Environments, configuration, build and deploy steps, monitoring, backups, access list | Tech lead |
| Hypercare log | Records post-release issues and fixes | Date, issue, severity, action, resolution time | PM, tech lead |

#### Phase 7 documents

| Document | Purpose and timing | Must contain | Owner |
| --- | --- | --- | --- |
| Handover pack | Lets the client own and run the product | Items listed in Section 11 | PM, tech lead |
| User and admin guides | Help people use and manage the product | Tasks, screenshots, roles, troubleshooting, contacts | PM, QA |
| Final report | Measures the project against its plan | Scope delivered against plan, timeline and cost against plan, approved changes, issues and resolutions, quality results, recommendations | PM |
| Lessons learned | Improves the next project | What worked, what did not, causes, recommended actions, owners | PM |
| Cost reconciliation and final invoice | Closes the commercial side | Budget against actual, approved changes, payments received, balance due | PM |
| Warranty terms | Sets post-launch expectations | Period, start date, covered and excluded items, how to report a defect, response times | PM |
| Closure sign-off | Evidence for Gate G6 | Deliverables accepted, open items and owners, warranty start date, approver, date | PM |

### B.5 Cross-Phase Documents

These documents start early and stay open until closure, and they are the PM's main control tools.

| Document | Purpose | Fields to record | Review rhythm |
| --- | --- | --- | --- |
| Risk register | Tracks what could go wrong | Risk ID, description, cause, likelihood (1 to 3), impact (1 to 3), score, response (avoid, mitigate, transfer or accept), owner, due date, status | Weekly |
| Issue log | Tracks problems that have happened | Issue ID, description, date raised, severity, owner, escalation level, action, target date, status | Daily in stand-up, weekly in report |
| Change request form | Starts every change | Change ID, date, requester, description, reason, affected items, effort, timeline and cost impact, risks, decision, approver, decision date | When raised |
| Change log | Lists every change and its outcome | Change ID, title, date, decision, cost and time impact, status | Weekly |
| Decision log | Records decisions so they are not reopened | Decision ID, date, decision, options considered, decided by, impact | When made |
| Approval log | Proves who approved what and when | Document, version, approver, role, date, method (email or signature), link to the evidence | At every gate |
| Assumptions and dependency log | Tracks premises and client or third-party inputs | ID, assumption or dependency, owner, due date, impact if it fails, status | Weekly |
| Weekly status report | Keeps the client informed | Health for scope, timeline and cost, completed work, planned work, milestone progress, top risks and issues, decisions needed, pending changes, effort used against plan | Weekly |
| Meeting minutes | Records discussions and actions | Meeting, date, attendees, decisions, actions with owner and due date, open questions | Sent within 24 hours |
| Communication log | Keeps a trail of important exchanges | Date, from, to, topic, decision or request, follow-up | As needed |
| Stakeholder and RACI updates | Keeps roles accurate as the team changes | Changes to people, roles, contact details and decision rights | When changes occur |

### B.6 Gate Checklist: Documents Needed to Pass Each Gate

A gate opens only when every document below exists, is in Approved status and is recorded in the approval log.

| Gate | Documents that must be approved | Approved by |
| --- | --- | --- |
| G1 Proposal accepted | Discovery notes, initial proposal, handover checklist, first Phase 1 payment received | Client sponsor |
| G2 Scope signed | Scope Definition Document, prioritized feature list, WBS, assumptions and constraints log, initial risk register, RACI, communication plan | Client sponsor |
| G3 Design approved | Wireframe approval record, high-fidelity approval record, style guide, prototype, design handoff package | Client sponsor |
| G4 Plan and cost approved | Development plan, final timeline, final cost breakdown, contract or SOW, third-party account list, kickoff readiness checklist, first milestone payment received | Client sponsor |
| G5 Release approved | Test report, UAT sign-off, release checklist, deployment and rollback plans, go-live approval | Client sponsor |
| G6 Project closed | Handover pack, user and admin guides, final report, lessons learned, cost reconciliation, warranty terms, closure sign-off | Client sponsor |

Milestone acceptance records inside Phase 4 are approved by the client contact and release the matching payment.

## Appendix C: Review Notes (remove before sharing with clients)

Version 3.0 reorganizes the guide from a phase-by-phase narrative into an operating model, eight phases, shared controls and commercial terms.

### Structural changes from version 2.0

| Version 2.0 | Version 3.0 | Reason |
| --- | --- | --- |
| Principles inside "My Approach" | Section 2 holds principles, roles and gates | Decision rights and approval evidence are visible up front |
| Policies after the last phase | Sections 12 to 14 hold controls shared by all phases | Risk, change and client duties apply from Phase 1, not only at the end |
| Cost and payment repeated in each phase | Each phase keeps its own terms, and Section 15 holds the full schedule | One place to check what is paid when |
| Flow listed as a single line | Section 3 draws the lifecycle with its gates | Order and gates are read at a glance |
| No template list | Appendix A lists artifacts by phase | Delivery teams know what to produce |
