# Service Business Intake Automation

### AI system that captures inbound inquiries and converts them into structured client intake workflows.

---

## Overview

Service businesses receive inquiries from many places — website forms, Yelp messages, Google reviews, and email. These inquiries often arrive as unstructured messages that are difficult to track and respond to quickly.

This system automates the intake process by capturing incoming inquiries, analyzing them with AI, organizing them into a structured database, and notifying the team with actionable summaries.

The result is a simple operational workflow that ensures no inquiry is missed and responses happen faster.

---

## Problem

Client inquiries often arrive across multiple channels and formats:

- Website contact forms
- Yelp or Google messages
- Email inquiries
- Social messages

Without a centralized intake system, teams end up:

- missing inquiries
- responding slowly
- manually copying messages into CRM systems
- losing potential bookings

Service businesses need a simple way to **capture, organize, and respond to inquiries in one place.**

---

## Solution

This project demonstrates an automated intake workflow that:

1. Captures inbound inquiries via webhook triggers
2. Uses AI to analyze the message and extract key details
3. Stores the inquiry in a structured Airtable database
4. Sends a Slack alert summarizing the inquiry
5. Enables quick response and booking follow-up

---

## Operational Impact

- Centralized intake pipeline for client inquiries
- Faster response times for potential customers
- Structured records instead of scattered messages
- Automated notifications for new leads
- Reduced manual intake work

---

## Tech Stack Used

Make • OpenAI • Airtable • Slack • Webhooks

---

## How the System Works

**Step 1 — Inquiry Capture**

Client inquiries arrive through channels like website forms or external platforms. These messages trigger a webhook that starts the automation workflow.

**Step 2 — AI Intake Analysis**

An LLM analyzes the inquiry and extracts useful context such as the requested service, urgency, and a short summary.

**Step 3 — Structured Lead Record**

The processed data is written into an Airtable database that serves as the intake CRM.

**Step 4 — Team Notification**

The system sends a Slack alert summarizing the inquiry so the team can respond quickly or send a booking link.

---

## Repository Structure

Service-Business-Intake-Automation
│
├── architecture
│ └── system-overview.md
│
├── data-model
│ └── airtable-schema.md
│
├── docs
│ └── workflow-overview.md
│
├── prompts
│ └── intake-analysis-prompt.md
│
└── README.md

---

## Future Improvements

Potential extensions of this system include:

- Google Business Profile inquiry ingestion
- Yelp message integration
- Automated response generation
- Calendar booking integrations
- Lead qualification scoring
