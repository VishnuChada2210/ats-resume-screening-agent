# ats-resume-screening-agent

🚀 ATS Resume Screening AI Agent (n8n + Gemini + Google Sheets)

This project automates the entire ATS resume screening process using n8n, Google Gemini, Google Sheets, and Gmail automation.

🔥 What this Workflow Does

Accepts resume submissions through a form

Extracts PDF text automatically

Uses Google Gemini to evaluate candidate

Generates:

Compatibility Rating

ATS Score

Summary & Recommendation

Automatically updates Google Sheet with structured output

Sends email to:

HR with candidate summary

Candidate for acknowledgement

Rejection email if ATS score is low

🧠 Tech Stack

n8n Workflow Automation

Google Gemini LLM

Google Sheets API

Gmail Automation

Form Trigger

File Text Extraction

📁 Workflow File

workflow.json (import into n8n)

📸 Architecture

Form → Extract PDF → LLM → Output Parser → IF condition → Google Sheet → Gmail Notifications
