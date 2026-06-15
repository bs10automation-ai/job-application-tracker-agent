# job-application-tracker-agent
job-application-tracker-agent/
README.md  screenshots/  
├─ workflow.png  
├─ airtable.png  workflow/  
└─ job-tracker-agent.json
# Job Application Tracker Agent

AI-powered job application tracking system built with n8n, Airtable, and Google Gemini.

## Overview

This workflow automatically analyzes new job applications submitted through Airtable Forms.

When a new application is created:

1. Airtable Trigger detects the new record
2. Google Gemini analyzes the company and position
3. AI generates:
   - Company Summary
   - Hiring Potential
   - Interview Difficulty
   - Recommendation
4. Results are written back into Airtable

## Stack

- n8n
- Airtable
- Google Gemini API
- Airtable Forms

## Workflow

Airtable Form
↓
Airtable Trigger
↓
AI Agent
↓
Google Gemini
↓
Airtable Update Record

## Example Output

Company: Microsoft

Analysis:
- Strong AI hiring momentum
- Competitive interview process
- High compensation potential
- Recommended to continue application

## Skills Demonstrated

- Workflow Automation
- AI Integration
- Prompt Engineering
- CRM Design
- Airtable Operations
- API Integration

## Author

Bogdan Sukhina
