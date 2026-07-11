# Sapoholic Labs Consultation Automation

An AI-powered enquiry automation workflow built with n8n for Sapoholic Labs.

## Overview

This workflow automates the consultation process from enquiry to notification.
When a client submits the consultation form:

- A new record is added to Google Sheets.
- The client receives an acknowledgement email.
- OpenAI analyzes the enquiry.
- A Telegram notification is sent to the business owner.
- The Google Sheet is updated with the AI analysis and enquiry status.

## Workflow

Google Forms
→ Google Sheets
→ OpenAI
→ Gmail
→ Telegram
→ Google Sheets Update

## Tech Stack

- n8n
- OpenAI API
- Google Forms
- Google Sheets
- Gmail
- Telegram Bot API

## Features

- AI-powered enquiry summaries
- Lead prioritization
- Instant business notifications
- CRM updates
- Automated email acknowledgements

## Future Improvements

- WhatsApp notifications
- Auto-generated quotations
- Follow-up reminders
- Analytics dashboard

## Author

**Stephanie Onyiwa**
