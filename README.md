# AI Assistant — Starter

> A lightweight AI customer-service assistant for WhatsApp.

Built by **Promptine**.

---

## Overview

AI Assistant is a lightweight conversational automation designed for businesses that want to handle customer communication through WhatsApp using AI.

It understands customer messages, maintains conversation context, and responds naturally in the customer's language.

The Starter version focuses on one thing:

**Reliable AI-powered customer communication without unnecessary complexity.**

---

## Workflow

![AI Assistant Workflow](workflow.png)

### Flow

**WhatsApp → Message Processing → AI Agent → WhatsApp Response**

The AI Agent is connected to:

- OpenRouter LLM
- Conversation Memory

---

## Features

- WhatsApp integration
- AI-powered customer conversations
- Conversation memory
- Multilingual communication
- Natural responses
- Basic customer information collection
- Automated WhatsApp replies
- Lightweight architecture

---

## Tech Stack

| Technology | Purpose |
|---|---|
| n8n | Automation & workflow orchestration |
| WhatsApp Business API | Customer communication |
| OpenRouter | AI model access |
| AI Agent | Conversation logic |
| Conversation Memory | Context retention |

---

## Starter Package

### $300

Designed for businesses that need a simple AI assistant for customer communication.

### Included

- Text-based AI assistant
- WhatsApp integration
- Conversation memory
- Multilingual responses
- Customer support conversations
- Basic information collection

### Not Included

- Voice messages
- Google Sheets
- Google Calendar
- Gmail
- Appointment booking
- Customer database
- Advanced business automation

---

## Pro Package

### $350

The Pro version extends the assistant with additional automation capabilities.

Possible integrations include:

- Voice message support
- Customer database
- Google Sheets
- Google Calendar
- Appointment booking
- Rescheduling & cancellation
- Email confirmations
- Advanced business workflows

---

## Architecture

The system uses **n8n** as the automation layer.

WhatsApp receives the customer message and passes it through the workflow.

The AI Agent processes the message using an LLM accessed through OpenRouter and maintains conversational context using memory.

The generated response is then sent back to the customer through WhatsApp.

---

## Privacy & Security

This repository contains documentation and architecture information only.

Production workflow files are intentionally not included.

No:

- API keys
- Access tokens
- Customer data
- Production credentials
- Private workflow JSON

are stored in this repository.

---

## About Promptine

**Promptine** builds practical AI automation systems for businesses.

> Not every job needs a hire. Some of it just needs a system.

---

## License

Private commercial system.

The workflow and implementation are proprietary to Promptine.
