# Client Intake & Booking Assistant

## Tagline
AI-powered workflow that converts online inquiries into structured booking leads and organized intake workflows.

---

## Overview

Service businesses receive inquiries across many channels — contact forms, Yelp messages, email, and social platforms. Most of these arrive as unstructured messages that are difficult to track and prioritize.

This system captures client inquiries, analyzes them with AI, and converts them into structured booking leads that can be organized and managed through a centralized intake workflow.

---

## Purpose

The goal of this system is to automate the client intake process so service businesses can:

- Capture inquiries automatically
- Extract structured booking details from messages
- Organize leads into a centralized database
- Respond faster to potential clients

---

## Primary Users

- Service business owners
- Operations teams managing inbound leads
- Booking coordinators or customer support teams

---

## Business Outcomes

- Faster response times to client inquiries
- Structured lead records instead of scattered messages
- Automated lead classification and prioritization
- Organized intake pipeline for booking workflows

---

## System Architecture

The workflow converts unstructured customer inquiries into structured lead records through a series of automated steps.

### Inquiry Sources

Client inquiries can originate from:

- Yelp messages
- Website contact forms
- Email inquiries
- Online messaging platforms

### Automation Workflow

1. **Webhook Capture**

   Incoming inquiries are received through a webhook trigger.

2. **AI Intake Analysis**

   An LLM analyzes the inquiry to extract:

   - service requested
   - urgency or timeline
   - booking intent
   - lead priority

3. **Structured Lead Creation**

   Extracted information is written into a structured lead database.

4. **Team Notification**

   The system sends a Slack notification alerting the team of a new inquiry.

---

## Technical Stack

- Make (automation orchestration)
- OpenAI (LLM intake analysis)
- Airtable (lead database)
- Slack (team notifications)
- Webhooks (event triggers)

---

## Repository Structure

client-intake-booking-assistant
│
├── README.md
│
├── architecture
│ └── system-overview.md
│
├── workflows
│ └── make-scenario.json
│
├── prompts
│ └── intake-analysis-prompt.md
│
├── data-model
│ └── airtable-schema.md
│
└── docs
├── workflow-overview.md
└── testing-scenarios.md

---

## Future Improvements

Potential extensions of this system include:

- Automated booking scheduling
- Calendar integrations
- Lead scoring models
- CRM integrations
