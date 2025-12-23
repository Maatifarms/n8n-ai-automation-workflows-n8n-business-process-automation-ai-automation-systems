# n8n-ai-automation-workflows-n8n-business-process-automation-ai-automation-systems
Reusable n8n workflows for AI-powered automation, API integrations, and RAG-based systems.
# AI Sales Research & Email Generation Assistant (n8n)

This automation is an AI-powered sales assistant built using n8n that automatically researches prospects, identifies opportunities, and generates highly personalized email and SMS outreach after a sales call is booked.

## What This Automation Does
- Reads booked sales calls from Google Sheets
- Researches company background, tech stack, and recent updates using AI
- Identifies relevant solutions based on business type and project
- Generates a personalized email subject, email body, and SMS
- Uses real testimonials to increase credibility
- Writes all outputs back into Google Sheets automatically

## Key Use Cases
- Sales teams booking discovery or demo calls
- Agencies running outbound or inbound lead qualification
- Founders wanting personalized follow-ups at scale

## Tech Stack
- n8n
- OpenAI (GPT-4.x)
- Tavily (web research)
- Google Sheets
- Retrieval-Augmented Generation (RAG)
- API & webhook-based orchestration

## How to Use
1. Import the JSON workflow into n8n
2. Configure API keys (OpenAI, Tavily)
3. Connect Google Sheets credentials
4. Update sheet structure if needed
5. Activate workflow

## Notes
- All credentials and sensitive data have been removed
- Designed for scalability and production use
- Can be customized for CRM systems, email tools, or databases
