# AI Email Assistant

![n8n](https://img.shields.io/badge/n8n-Workflow-orange)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4o-412991)
![Gmail](https://img.shields.io/badge/Gmail-API-EA4335)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-API-34A853)
![Docker](https://img.shields.io/badge/Docker-2496ED)
![License](https://img.shields.io/badge/License-MIT-yellow)

An intelligent email automation workflow built with **n8n**, **OpenAI**, **Gmail API**, and **Google Sheets**.

The workflow automatically:

- Classifies incoming emails using AI
- Assigns Gmail labels
- Detects priority
- Identifies whether user action is required
- Generates AI summaries
- Stores structured data in Google Sheets

---

## 📌 Overview
---

## 🚀 Business Problem

Managing email manually is time-consuming and inefficient.

Important customer requests can be overlooked, invoices mixed with newsletters, and urgent support emails delayed.

Businesses need an automated way to organize incoming emails without spending time sorting them manually.

---

## 💡 Solution
---

## ✨ Features

- AI-powered email classification
- Automatic Gmail label assignment
- Priority detection (High / Medium / Low)
- Action required detection
- AI-generated email summaries
- Multi-language support
- Automatic Google Sheets logging
- Fully automated n8n workflow

---

## 🏗️ Architecture

```
                Incoming Email
                       │
                       ▼
               Gmail Trigger
                       │
                       ▼
              OpenAI Analysis
                       │
                       ▼
             JavaScript Processing
                  │            │
                  ▼            ▼
         Gmail Labels    Google Sheets
```

---

## ⚙️ Technology Stack

- **Workflow Automation:** n8n
- **AI:** OpenAI GPT-4o
- **Email:** Gmail API
- **Database:** Google Sheets
- **Infrastructure:** Docker
- **Reverse Proxy:** Traefik
- **Database Engine:** PostgreSQL
- **Hosting:** Ubuntu VPS

AI Email Assistant automatically processes every incoming email using OpenAI.

The workflow analyzes the email content, determines its category, assigns the appropriate Gmail label, detects priority, identifies whether action is required, generates a short summary and stores the results in Google Sheets.

The entire process runs automatically without manual intervention.

AI Email Assistant helps businesses organize incoming email automatically.

Instead of manually sorting invoices, customer requests, notifications, newsletters and personal messages, the workflow uses OpenAI to analyze every email and perform intelligent classification.

The result is a clean Gmail inbox, automatic labeling and a structured database that can be used for reporting, dashboards or CRM integrations.

