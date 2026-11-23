# Business Problem & Stakeholder Analysis

## Context
This portfolio case study considers a web-based e-commerce business where customers browse products, place orders, track fulfilment and sometimes request returns or refunds. The project assumes that unclear checkout steps, limited order visibility and inconsistent return handling can create avoidable friction.

These are scenario assumptions, not findings from interviews, company records or production analytics.

## Problem statement
Customers need a straightforward way to complete purchases and understand what happens after payment. Operations administrators need a consistent view of order information and status changes.

**Analysis question:** How can the proposed order-management experience reduce uncertainty for customers and make routine order handling clearer for administrators?

## Stakeholder groups

| Stakeholder | Main need | System support |
|---|---|---|
| Customer | Complete an order with confidence | Cart review, checkout, confirmation and order history |
| Customer | Understand order progress | Clear order statuses and tracking information |
| Customer | Request a return or refund | Visible request process and status |
| Operations administrator | Review and manage orders | Searchable order details and controlled status actions |
| Customer support | Respond to order enquiries | Consistent order and return information |
| Product / delivery team | Build the right functionality | Prioritised, testable requirements |

These are stakeholder roles for the scenario, not named or interviewed individuals.

## Business objectives
1. Make the purchase journey easier to understand.
2. Make order information accessible after purchase.
3. Define a predictable return and refund workflow.
4. Clarify administrator responsibilities and permitted actions.
5. Give the delivery team requirements that can be reviewed and tested.

## Expected value
If implemented and validated, the proposed capabilities could help reduce customer uncertainty, support more consistent order handling and make service performance easier to monitor. These are expected benefits, not measured outcomes.

## Questions I would validate
- Which checkout step causes the most customer difficulty?
- What payment failure and retry scenarios must be supported?
- Which order statuses are currently used and who updates them?
- What return eligibility rules apply to different products?
- What information does support need to resolve an enquiry?
- Which administrative actions require approval or an audit trail?

## Scope boundaries
The case study covers customer registration, product browsing, cart and checkout, order history and tracking, return/refund requests, and administrative order management. Native mobile apps, international shipping and vendor onboarding are outside the stated scope.
