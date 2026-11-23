# Process Analysis & Proposed Workflows

## My analysis approach
I treated the customer journey as a sequence of connected processes rather than a collection of screens. For each workflow, I considered the user's goal, required information, system decisions and the outcome that should be communicated.

The process-flow PDF in the repository is the visual artefact. These notes explain the intended analysis behind the main journeys.

## 1. Checkout journey
**Customer goal:** place an order and receive clear confirmation.

| Step | Activity | Requirement consideration |
|---|---|---|
| 1 | Customer reviews the cart | Show product, quantity, price and order summary |
| 2 | Customer proceeds to checkout | Check that the cart contains valid items |
| 3 | Customer provides or selects delivery details | Validate required address information |
| 4 | Customer selects a payment method | Display available methods and relevant instructions |
| 5 | System processes payment response | Handle success, failure, pending and retry outcomes |
| 6 | System creates or confirms the order | Do not present an unconfirmed payment as a successful order |
| 7 | Customer receives confirmation | Display an order reference and next steps |

**Exception paths to consider:** item becomes unavailable, invalid address, payment declined, delayed payment response, duplicate submission, session expiry and customer retry.

## 2. Order fulfilment and tracking
**Customer goal:** understand whether an order has been received, prepared and dispatched.

A proposed status lifecycle could include: Placed → Confirmed → Processing → Shipped → Delivered. Additional outcomes may include Cancelled or Delivery Exception. The final status vocabulary and transition rules should be confirmed with the business.

The system should make the current status and relevant update visible to the customer. Administrative status changes should follow defined permissions and should not allow invalid transitions.

## 3. Return and refund journey
**Customer goal:** request a return and understand what happens next.

| Step | Activity | Requirement consideration |
|---|---|---|
| 1 | Customer opens an eligible order | Show return availability and order details |
| 2 | Customer selects an item and reason | Capture required return information |
| 3 | System checks eligibility | Apply agreed return-window and policy rules |
| 4 | Request is submitted | Generate a reference and confirmation |
| 5 | Administrator reviews the request | Provide a queue and decision options |
| 6 | Return progresses through its stages | Make status and next steps visible |
| 7 | Refund is processed where approved | Record outcome and communicate completion |

The exact eligibility policy, inspection process, refund method and service-level targets are business decisions to confirm.

## Current-state vs proposed-state thinking
Because this is a simulated case study, there is no verified company-specific AS-IS process. I therefore avoid claiming that I measured an existing workflow. The analysis uses potential friction points as hypotheses and describes a proposed TO-BE workflow.

| Analysis area | Potential issue to validate | Proposed design response |
|---|---|---|
| Checkout | Customers may not understand the steps or final amount | Clear order summary and explicit confirmation |
| Payment | Failure or delayed response may create uncertainty | Defined success, failure, pending and retry behaviour |
| Tracking | Customers may not know what each status means | Consistent status definitions and visible updates |
| Returns | Eligibility and next steps may be unclear | Policy checks, request reference and status tracking |
| Administration | Status actions may be inconsistent | Defined roles, permitted transitions and history |

## What I would do in a real engagement
I would observe the existing workflow, review support tickets and funnel data, interview customers and operations staff, validate pain points, and compare the proposed process against the measured baseline. That evidence would determine which improvements should be prioritised.
