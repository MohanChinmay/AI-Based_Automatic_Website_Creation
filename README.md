AI-Based Multi-Agent System for Automatic Website Creation
Project Overview
This project is an AI-powered multi-agent system that automates website creation from user input (voice/text) to deployment.
Features
Voice & Text Input
Multi-Agent Architecture
Automated UI & Code Generation
PRD Generation
Workflow Automation (n8n)
Real-time Editing
Architecture
Parent Agent (Orchestrator)
Website Planner Agent (Scraping + PRD)
Lovable Browser Agent (Automation)
Tools: Firecrawl, Airtop, ElevenLabs, OpenAI/Gemini
Prerequisites
Node.js
n8n
API Keys
Execution
n8n start

Workflow
User → Planner → PRD → Browser Agent → Website
Editing
Provide modification instructions to update website.
Error Handling
Retries, session recreation, API recovery.
Security
Use HTTPS and secure API keys.
Performance
Website generation takes 2–5 minutes.
Future Scope
SEO, E-commerce, Mobile app.
Contributors
P. Laxmidhar, Team
Conclusion
AI automates web development efficiently.
