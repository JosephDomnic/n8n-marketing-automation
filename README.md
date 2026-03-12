# n8n Marketing Automation Workflows

A collection of AI-powered marketing automation workflows built with n8n.

## Workflows

### 1. Campaign Performance Reporter
Automatically pulls campaign data from Google Sheets every Monday, 
analyses performance using Groq AI (Llama 3.3) and emails a structured 
report to your team.

**Nodes:** Schedule Trigger → Google Sheets → Code → HTTP Request (Groq) → Gmail

**Setup:**
1. Import the JSON file into n8n
2. Add your Google Sheet ID
3. Add Groq API key as Header Auth credential
4. Add Gmail credential
5. Activate workflow

## Tech Stack
n8n • Groq API (Llama 3.3) • Google Sheets • Gmail
