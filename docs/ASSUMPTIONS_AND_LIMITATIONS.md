# Assumptions, Risks & Limitations

## Project status
This is an independent, documentation-led portfolio case study based on a simulated e-commerce scenario. It is not a live client project or a deployed product.

## Assumptions used
- The business operates a web-based storefront.
- Customers can create accounts and place orders.
- The system needs customer-facing order history and tracking.
- Customers may request returns or refunds under a business-defined policy.
- Administrators have controlled access to order-management functions.
- The business wants clearer and more consistent order-related workflows.

These assumptions provide a starting point. They should be validated before implementation.

## Decisions that require stakeholder confirmation
- Supported payment methods and payment-provider behaviour
- Inventory reservation and out-of-stock handling
- Delivery options, promised dates and carrier integration
- Order cancellation rules and status transitions
- Return eligibility windows, exclusions and approval rules
- Refund methods and service-level expectations
- Administrator roles, permissions and audit requirements
- Data retention, privacy, security and accessibility requirements

## Risks to consider

| Risk | Potential impact | Analysis / mitigation |
|---|---|---|
| Ambiguous order status definitions | Customer confusion and inconsistent operations | Agree status definitions, owners and allowed transitions |
| Payment response delays | Duplicate submissions or uncertain order state | Define idempotency, pending states and retry behaviour with the technical team |
| Unclear return policy | Disputes and inconsistent decisions | Confirm policy rules and represent them explicitly in requirements |
| Excessive administrator permissions | Unauthorised order changes | Define role-based access and audit important actions |
| Incomplete exception handling | Failed or confusing customer journeys | Include negative and edge-case scenarios in requirements and UAT |
| Unvalidated assumptions | Solution may not address the real problem | Validate with stakeholders and operational evidence |

## Evidence limitations
The repository contains the listed requirements and design artefacts, but this documentation pass did not inspect the internal contents of every DOCX, XLSX and PDF file. The README and supporting notes therefore describe the deliverables at a high level and do not claim that every detailed requirement, ID or diagram has been independently reconciled.

There is no production dataset, measured baseline, deployed application, integration test report or verified business-impact result in the reviewed repository listing.

## Recommended next steps
1. Review and reconcile the BRD, SRS, FRD and user-story spreadsheet line by line.
2. Add or confirm unique requirement IDs and a complete traceability matrix.
3. Validate process flows and policy assumptions with representative stakeholders.
4. Add detailed non-functional requirements for security, privacy, accessibility, performance and availability.
5. Expand UAT coverage for payment, inventory, cancellation, delivery exceptions and refunds.
6. Prototype the main customer and administrator journeys and conduct usability feedback sessions.
7. Establish KPI definitions and a baseline before claiming business improvement.
