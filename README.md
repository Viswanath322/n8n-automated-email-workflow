🚀 n8n Automated HR Outreach Workflow

This repository contains an n8n workflow that automates sending personalized outreach emails to HR teams using Google Sheets, AI-generated email content, and Gmail draft creation. It is designed to streamline job applications while maintaining a professional tone.

✨ Features

Reads company data from Google Sheets

Filters rows with status = pending

Uses Gemini AI to generate a clean subject + email body

Automatically attaches your resume (binary file in n8n)

Creates a Gmail draft for review instead of auto-sending

Updates Google Sheets with status after drafting

Clean text & HTML formatting (no spacing issues)

📁 Included

HR_Email_Automation_Workflow.json — the workflow export

Short documentation on setup

🔧 Requirements

n8n (self-hosted or cloud)

Google Sheets + Gmail credentials

Gemini API key

Resume uploaded into n8n (binary)

▶️ How to Use

Import the JSON file into n8n

Add your API credentials

Update Google Sheet ID + column mappings

Add your resume file path

Run the workflow or schedule it with Cron
