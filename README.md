# 📧 n8n Gmail Automation

## 📌 Project Overview

This project is an email automation workflow created using **n8n** and **Gmail OAuth2**.

The workflow automatically sends an email through Gmail based on a scheduled trigger.

## 🚀 Features

- ⏰ Schedule-based email automation
- 📧 Send emails using Gmail
- 🔐 Gmail OAuth2 authentication
- ⚙️ Built using n8n
- 🤖 Reduces manual email sending

## 🛠️ Technologies Used

- n8n
- Gmail API
- Google Cloud Platform
- OAuth 2.0
- Docker

## 🔄 Workflow

The workflow contains:

1. **Schedule Trigger**
   - Starts the workflow at the configured time.

2. **Gmail – Send a Message**
   - Sends the email automatically using the connected Gmail account.

### Workflow

```text
Schedule Trigger
       ↓
Gmail - Send a Message
       ↓
     Email Sent
