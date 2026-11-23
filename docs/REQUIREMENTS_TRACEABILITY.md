# Requirements Traceability

## Purpose
Traceability connects the business need to the system capability and the test that should confirm it. It helps prevent requirements from becoming isolated statements with no clear business reason.

The table below is a high-level traceability view for this portfolio scenario. It should be reconciled against the detailed IDs and wording in the BRD, SRS, FRD and User_Stories.xlsx before a delivery team treats it as a controlled requirements baseline.

| Business need | Proposed capability | Example acceptance condition | Validation |
|---|---|---|---|
| Customer needs to review a purchase | Cart summary | Cart displays selected items, quantities and calculated total before checkout | UAT: verify cart contents and total |
| Customer needs to complete checkout | Checkout workflow | Required delivery and payment information is validated before submission | UAT: valid and invalid checkout cases |
| Customer needs confirmation | Order confirmation | Successful order displays a unique reference and summary | UAT: successful payment/order scenario |
| Customer needs order visibility | Order history and tracking | Customer can view their own orders and current status | UAT: ownership and status visibility |
| Customer needs a return route | Return request | Eligible items can be submitted with required details | UAT: eligible and ineligible item cases |
| Administrator needs order control | Admin order management | Only authorised users can perform permitted status actions | UAT: role and permission scenarios |
| Business needs reliable records | Order event history | Important status changes are recorded with timestamp and actor | UAT: audit-history verification |

## Requirement quality checks
- **Necessary:** linked to a stakeholder need or business objective.
- **Unambiguous:** written so business and technical readers interpret it consistently.
- **Testable:** supported by observable acceptance criteria.
- **Feasible:** realistic within agreed scope and constraints.
- **Traceable:** connected to a business need and validation method.
- **Consistent:** not in conflict with another requirement or policy.

## Suggested requirement ID convention
If the existing documents do not already use a consistent convention, IDs could follow:
- BR-## — business requirement
- FR-## — functional requirement
- NFR-## — non-functional requirement
- US-## — user story
- UAT-## — user acceptance test

Do not renumber existing requirements until the BRD, SRS, FRD and spreadsheet have been checked together.
