Smart Life Copilot 🤖
An AI-powered personal productivity assistant built with n8n, Google Gemini, and connected productivity tools.

🚀 Overview
Smart Life Copilot helps users organize daily tasks, plan schedules, manage calendar events, retrieve productivity data, and automate routine activities through an AI agent.

✨ Features
AI-powered assistance: Understands natural-language requests using Google Gemini.
Persistent conversation memory: Uses the configured Simple Memory node.
Calendar automation: Creates Google Calendar events using the connected tool.
Productivity data: Reads task-related information from Google Sheets.
Email automation: Sends authorized emails through Gmail.
Weather-aware planning: Retrieves weather information through OpenWeatherMap.
Scheduled workflows: Supports automated execution through an n8n Schedule Trigger.
Chat interface: Accepts requests through the n8n chat trigger.


🏗️ Architecture
User Chat / Schedule Trigger
            |
            v
         AI Agent
            |
     +------+-------+---------+----------+
     |      |       |         |          |
   Gemini Memory Calendar   Sheets      Gmail
                              |
                        Weather Tool

                        
🛠️ Technology Stack
n8n — Workflow automation
Google Gemini — Language model
Google Calendar — Event creation
Google Sheets — Productivity data
Gmail — Email automation
OpenWeatherMap — Weather information

⚙️ Setup
Set up an n8n instance.
Configure Google Gemini credentials.
Connect the required Google services.
Configure the memory and weather nodes.
Connect each tool to the AI Agent's appropriate input.
Test the chat workflow and scheduled workflow separately.
Activate the workflow after successful testing.


🔐 Security
Never commit API keys, passwords, OAuth tokens, or private credentials.
Use n8n credentials to store authentication details securely.
Review email and calendar actions before enabling unattended automation.

📌 Current Project Status
The initial AI agent workflow has been assembled in n8n. Tool configuration, end-to-end testing, and documentation are ongoing.

🔮 Future Improvements
Daily personalized productivity briefings
Task prioritization and deadline tracking
Calendar conflict detection
Smart reminders and follow-ups
Better error handling and execution logging

👨‍💻 Author
Developed as a personal productivity automation project.
