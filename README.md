#AI Restaurant Automation System

##Overview

This project is an AI-powered restaurant assistant built using n8n and Google Gemini.

It can:
* Answer customer queries (FAQ)
* Check food availability from Google Sheets
* Process orders and store them automatically

##Tech Stack
* n8n (Workflow Automation)
* Google Gemini AI
* Google Sheets API

##Workflow

User Input → AI Agent → Decision →
→ FAQ Response
→ Inventory Check
→ Order Storage in Google Sheets

##Files

workflow.json → n8n workflow export

##How to Run
1. Import `workflow.json` into n8n
2. Connect Google Sheets + Gemini credentials
3. Run the workflow
