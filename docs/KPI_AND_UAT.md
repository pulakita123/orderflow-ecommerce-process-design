# KPI Framework & User Acceptance Testing

## Why define measures?
A proposed system should have a way to determine whether it solves the business problem. I have identified candidate measures for the e-commerce journey. Since this is a simulated project with no production dataset, I have not assigned baseline values, targets or claimed improvements.

## Candidate business KPIs

| KPI | Definition | Why it matters | Data needed |
|---|---|---|---|
| Checkout completion rate | Completed checkouts ÷ checkout starts × 100 | Indicates how often checkout journeys finish | Checkout-start and order-completion events |
| Checkout abandonment rate | Checkout starts without completion ÷ checkout starts × 100 | Helps identify potential checkout friction | Session or funnel events |
| Order-status enquiry rate | Order-status support enquiries ÷ total orders × 100 | Indicates whether customers can find order information | Support ticket categories and order count |
| On-time fulfilment rate | Orders delivered by promised date ÷ orders due for delivery × 100 | Measures fulfilment reliability | Promised and actual delivery timestamps |
| Return resolution time | Time from return request to final decision | Measures speed of return handling | Return request and decision timestamps |
| Refund turnaround time | Time from refund approval to refund completion | Measures refund processing experience | Approval and completion timestamps |

**Measurement notes:** define reporting period, exclusions, cancellation treatment, event ownership and data-quality checks before comparing performance. Agree targets with stakeholders after a baseline is available.

## Example UAT scenarios

| Test ID | Scenario | Expected result |
|---|---|---|
| UAT-01 | Customer checks out with valid details and successful payment | Order is confirmed and a reference is displayed |
| UAT-02 | Customer submits checkout with a required field missing | System identifies missing information and prevents invalid submission |
| UAT-03 | Payment is declined | Customer sees a clear failure message and order is not shown as paid |
| UAT-04 | Customer retries after payment failure | System handles retry without unintended duplicate order |
| UAT-05 | Customer views an order belonging to their account | Customer can see the order and current status |
| UAT-06 | Customer attempts to access another customer's order | Access is denied |
| UAT-07 | Customer requests a return for an eligible item | Request is submitted and a reference/status is shown |
| UAT-08 | Customer requests a return for an ineligible item | System explains that the item is not eligible under configured policy |
| UAT-09 | Unauthorised user attempts an admin status change | Action is blocked |
| UAT-10 | Administrator updates an order status | Valid status change is saved and recorded |

## UAT completion considerations
A scenario should be considered passed only when the actual result matches the agreed expected result. Defects should be recorded with reproduction steps, expected behaviour, actual behaviour, severity and retest status.

These are proposed test scenarios, not evidence that testing has already been executed.
