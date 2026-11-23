# OrderFlow: E-Commerce Operations & Process Design

A Business Analysis portfolio case study focused on improving the customer journey from product selection to checkout, order tracking and returns.

I approached this project as a business-process and requirements problem: identify where customers and operations teams may experience friction, translate those needs into clear system behaviour, and organise the proposed solution into documentation a product and delivery team could use.

> **Project type:** Independent portfolio case study / simulated business scenario. This is not a live client implementation. The business problems described are assumptions, not measured findings from a real company's operations.

## Project at a glance

| Area | Summary |
|---|---|
| Business domain | E-commerce order management |
| Primary users | Customers and operations administrators |
| Business focus | Checkout, order visibility, fulfilment and returns |
| BA activities | Problem framing, scope definition, requirements documentation, process modelling, user stories and Agile backlog organisation |
| Tools represented | Jira, Excel, Draw.io, PowerPoint / Figma |
| Deliverables | BRD, SRS, FRD, user stories, process flow, wireframes and Jira evidence |

## 1. The business problem

An online store can lose customer confidence when checkout is difficult to complete, order status is unclear, or returns require customers to contact support repeatedly. Operations teams can also struggle when order information and status changes are not organised consistently.

I framed the central question as:

**How might an e-commerce platform make placing, tracking and returning an order more predictable for customers, while giving administrators a clearer way to manage order activity?**

## 2. What I set out to improve

- **Checkout experience:** make cart review, address selection, payment and order confirmation understandable.
- **Order visibility:** let customers review order history and see meaningful status updates.
- **Returns and refunds:** define a consistent request, review and status-tracking process.
- **Administrative control:** give administrators a structured view of orders and permitted actions.

These are proposed solution goals. The repository does not claim measured improvements in conversion, fulfilment time or refund turnaround.

## 3. Scope

**In scope:** customer registration and authentication; product browsing and details; cart and checkout; order history and tracking; return/refund requests; administrative order management.

**Out of scope:** native mobile application; international shipping; vendor onboarding.

## 4. How I approached the analysis

1. **Frame the problem:** identify customer and operational pain points the proposed system should address.
2. **Define stakeholders and scope:** separate customer-facing needs from administrator workflows and establish boundaries.
3. **Translate needs into requirements:** document business objectives, system requirements, functional behaviour, validations and constraints.
4. **Model workflows:** map checkout, fulfilment and return journeys so steps and decision points are visible.
5. **Make requirements actionable:** express features as user stories with acceptance criteria.
6. **Support delivery planning:** organise work into a Jira-style Agile backlog and use wireframes to communicate intended screens.
7. **Plan validation:** define candidate success measures and UAT scenarios rather than assuming the design has already delivered results.

## 5. Repository deliverables

| Deliverable | Purpose |
|---|---|
| [Business Requirements Document (BRD)](BRD.docx) | Business context, objectives and scope |
| [Software Requirements Specification (SRS)](SRS.docx) | System-level requirements |
| [Functional Requirements Document (FRD)](FRD.docx) | Functional behaviour, rules and validations |
| [User Stories](User_Stories.xlsx) | Agile-ready requirements and acceptance criteria |
| [Process Flow](Process_Flow.drawio.pdf) | Visual representation of key workflows |
| [Wireframes](Wireframes.pdf) | Low-fidelity screen concepts |
| [Jira Screenshots](Jira_Screenshots.docx) | Evidence of backlog / Agile planning work |

Additional analysis notes:
- [Business problem and stakeholder view](docs/BUSINESS_PROBLEM.md)
- [Process analysis and proposed workflows](docs/PROCESS_ANALYSIS.md)
- [Requirements traceability](docs/REQUIREMENTS_TRACEABILITY.md)
- [KPI and UAT approach](docs/KPI_AND_UAT.md)
- [Project report](docs/PROJECT_REPORT.md)
- [Assumptions, risks and limitations](docs/ASSUMPTIONS_AND_LIMITATIONS.md)

## 6. Example business questions

- At which points in the customer journey could an order be abandoned or left incomplete?
- What information should a customer see before confirming an order?
- Which order statuses are meaningful to customers, and what should trigger an update?
- What checks should happen before a return request is accepted?
- Which administrator actions should be permitted, restricted or recorded?
- How can requirements be validated before a feature is released?

## 7. How success could be measured

Candidate measures include checkout completion rate, checkout abandonment rate, order-status enquiry rate, on-time fulfilment rate, return-request resolution time and refund turnaround time.

No baseline or post-implementation values are reported because this is a documentation-led simulation without production transaction data. See [KPI and UAT approach](docs/KPI_AND_UAT.md).

## 8. My role and skills demonstrated

I structured the case study from a Business Analyst perspective: framing the business need, defining scope, documenting requirements, modelling processes, preparing user stories and acceptance criteria, and organising work for Agile delivery.

**Skills demonstrated:** business problem analysis, requirements elicitation and documentation, BRD, SRS, FRD, functional and non-functional requirements, user stories, acceptance criteria, process mapping, wireframing, stakeholder thinking, scope management, KPI definition, UAT planning and Agile / Jira concepts.

## 9. How to review this project

1. Read this README for the business context.
2. Open the BRD to understand objectives and scope.
3. Review the process-flow PDF to follow the workflows.
4. Review the FRD and SRS for system behaviour and constraints.
5. Open the user-stories spreadsheet to see delivery-oriented requirements.
6. Review the wireframes and Jira evidence to understand how the proposed experience and work items are communicated.

## 10. Limitations and next steps

This repository documents a proposed solution; it does not include a deployed application, production dataset, integration test results or evidence of real operational impact. The next step would be to validate assumptions with representative users, refine the requirements, define edge-case scenarios and test the workflows with a clickable prototype.

---
*This project demonstrates structured Business Analysis thinking and clear documentation. It does not claim that a real e-commerce platform was built or that business performance improved.*
