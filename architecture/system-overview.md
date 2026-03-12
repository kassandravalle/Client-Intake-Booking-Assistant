# System Architecture Overview

The Client Intake & Booking Assistant converts unstructured customer inquiries into structured booking leads through an automated workflow.

## High-Level Flow

Inquiry Source  
↓  
Webhook Trigger  
↓  
AI Intake Analysis  
↓  
Structured Lead Database  
↓  
Team Notification

---

## Step 1 — Inquiry Capture

Client inquiries are captured through webhook triggers when a message is submitted through:

- Yelp
- Website contact forms
- Email
- Messaging platforms

The webhook sends the inquiry content and metadata into the automation workflow.

---

## Step 2 — AI Intake Analysis

An LLM processes the inquiry and extracts structured booking information including:

- service requested
- timeline
- urgency
- lead priority
- suggested response

This allows unstructured messages to be converted into structured operational data.

---

## Step 3 — Lead Database

The extracted information is written into a structured Airtable database containing lead records.

This provides a centralized intake system where all client inquiries can be tracked.

---

## Step 4 — Team Notification

A Slack notification is sent to alert the team when a new inquiry is received.

This enables quick responses and ensures new leads are not missed.
