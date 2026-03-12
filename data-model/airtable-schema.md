# Airtable Data Model

The Airtable database acts as the central intake system for all incoming client inquiries.

---

## Leads Table

| Field | Type | Description |
|------|------|-------------|
| lead_id | Text | Unique ID for inquiry |
| created_at | Date | Timestamp of inquiry |
| source | Text | Source channel (website, Yelp, Google) |
| client_name | Text | Name of the client |
| email | Email | Client email address |
| inquiry_message | Long text | Original inquiry text |
| service_requested | Text | Extracted service request |
| urgency | Enum | Low / Medium / High |
| summary | Long text | AI-generated inquiry summary |
| response_draft | Long text | Suggested reply message |
| status | Enum | New / Contacted / Booked |

---

## Purpose

This schema allows service businesses to:

- track all client inquiries
- organize intake workflows
- maintain inquiry history
- improve response processes
