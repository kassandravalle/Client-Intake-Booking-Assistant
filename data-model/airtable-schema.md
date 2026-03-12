# Airtable Data Model

The Airtable database stores structured client intake records generated from customer inquiries.

## Leads Table

| Field | Type | Description |
|------|------|-------------|
| lead_id | Text | Unique identifier for each inquiry |
| client_name | Text | Name of the client |
| inquiry_source | Text | Origin of inquiry (Yelp, website, etc.) |
| service_requested | Text | Service the client is requesting |
| urgency | Enum | Low / Medium / High |
| timeline | Text | Client's requested timeline |
| lead_priority | Enum | Low / Medium / High |
| inquiry_text | Long text | Original client inquiry |
| response_draft | Long text | AI-generated response suggestion |
| status | Enum | New / Contacted / Booked / Closed |
| created_at | Date | Timestamp of inquiry |

---

## Purpose of the Data Model

The schema enables service businesses to:

- Track all client inquiries in one system
- Prioritize leads based on urgency
- Maintain inquiry history
- Improve response workflows
