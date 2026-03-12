# Testing Scenarios

The workflow should be tested against several inquiry types.

## Scenario 1 — Standard Inquiry

Customer asks for information about a service.

Expected result:

- Service extracted correctly
- Lead record created
- Slack notification sent

---

## Scenario 2 — Urgent Request

Customer needs service immediately.

Expected result:

- Urgency detected
- Lead marked high priority

---

## Scenario 3 — Missing Information

Customer sends vague inquiry.

Expected result:

- Unknown fields populated
- Lead record still created

---

## Scenario 4 — Multiple Services

Customer requests multiple services.

Expected result:

- Primary service identified
- Additional notes captured
