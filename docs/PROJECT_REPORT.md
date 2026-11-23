# Project Report: E-Commerce Order Management & Checkout System

## 1. Introduction
For this project, I worked through a Business Analyst case study based on a web-based e-commerce order-management system. I wanted to understand how the customer experience before and after placing an order could be translated into clear business and system requirements.

I treated the work as a simulated business scenario. The purpose was to practise the analysis and documentation expected in a Business Analyst role, not to represent a real client implementation.

## 2. Understanding the problem
I focused on three connected parts of the customer journey: completing checkout, understanding order progress and requesting a return or refund. I also considered the operations administrator, who needs a structured way to review orders and manage status changes.

The central question guiding my work was: how can the system make order-related tasks easier to understand for customers and more consistent for administrators?

I used potential issues such as unclear checkout steps, limited order visibility and uncertain return status as hypotheses to guide the requirements. In a real project, I would validate these through stakeholder discussions, workflow observation, support-ticket analysis and product data.

## 3. Defining the scope
I included customer registration, product browsing, cart and checkout, order history and tracking, return/refund requests and administrative order management. I excluded native mobile applications, international shipping and vendor onboarding to keep the proposed solution focused.

Defining these boundaries helped me avoid expanding the project into every possible e-commerce feature.

## 4. Turning the business need into requirements
I organised the documentation into business, system and functional requirements. The BRD captures the business context and scope; the SRS describes system-level expectations; and the FRD focuses on functional behaviour, rules and validations.

I also used user stories and acceptance criteria to express requirements from the perspective of the people using the system. This makes a requirement easier to discuss with stakeholders and gives the delivery team a starting point for validation.

## 5. Mapping the workflows
I considered checkout, order fulfilment and return journeys as end-to-end processes. For checkout, I included cart and delivery validation, payment outcomes and order confirmation. For tracking, I considered the status information a customer needs after purchase. For returns, I considered eligibility, request submission, administrator review and refund completion.

I paid particular attention to exception cases such as failed payments, missing information, duplicate submissions and ineligible return requests. These cases matter because a process is not complete if it only describes the ideal path.

## 6. Communicating the proposed solution
The process-flow PDF communicates the workflow visually, while the wireframes show how key screens could be organised. The Jira screenshots provide supporting evidence of Agile planning activity. The user-stories spreadsheet connects proposed functionality to delivery-oriented work items.

Together, these artefacts show how I moved from a broad business problem towards requirements and design communication.

## 7. Measuring whether the solution works
I identified candidate KPIs such as checkout completion, checkout abandonment, order-status enquiry rate, on-time fulfilment, return resolution time and refund turnaround time.

I have not reported numerical results because the project does not include production event data or a live implementation. In an actual engagement, I would agree on KPI definitions and reporting rules, establish a baseline, and compare results after release.

I also outlined UAT scenarios for successful and failed checkout, order access, return eligibility and administrator permissions. These scenarios describe how the proposed behaviour could be checked; they are not claimed as completed test results.

## 8. What I learned
This project helped me practise breaking a broad business problem into smaller, connected workflows. I also learned to distinguish a business objective from a functional requirement, and a requirement from the test that proves it has been met.

One important lesson was to consider exception paths early. Payment failure, access restrictions and return eligibility can change the customer's experience just as much as the happy path.

## 9. Limitations and next steps
The case study is based on assumptions rather than primary research. It has no deployed application, production dataset, measured baseline, stakeholder interview record or executed UAT evidence. The next step would be to validate the problem with representative stakeholders, reconcile requirement IDs across all artefacts, refine policy rules and test workflows using a clickable prototype.

## 10. Conclusion
I approached this project as an exercise in structured problem-solving: understand the business need, define a manageable scope, translate needs into requirements, model workflows and consider how the proposed solution would be validated. The resulting documents form a portfolio example of my Business Analysis approach and the way I communicate requirements to business and delivery stakeholders.
