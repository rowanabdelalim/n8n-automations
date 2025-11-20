# n8n Automations

A collection of automation workflows built using **n8n**, focused on AI-assisted tasks, productivity, and communication.  
This repository includes modular, reusable workflows that can help automate everyday tasks with minimal setup.

---

## 🚀 Workflows

Below is a list of available workflows in this repository.

---

### ### **1. Email Assistant (`Email Assistant.json`)**

A conversational **AI-powered email assistant** that allows you to send emails simply by describing your request in natural language.

#### **What it does**
- Accepts user text like:  
  _“Ask Salma if she is available tomorrow at 10 AM.”_
- Uses an LLM (Google Gemini or OpenAI) to:
  - Understand the intent  
  - Extract recipient details  
  - Generate the email subject & body  
- Sends the email automatically via **Gmail**

##  Importing a Workflow in n8n

1. Download the `.json` file you want  
2. Open your n8n instance  
3. Click **Import from File**  
4. Select the file  
5. Update credentials (Gmail, Gemini, etc.)  
6. Activate the workflow

You're ready to run it!

