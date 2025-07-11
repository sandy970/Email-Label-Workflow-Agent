# Email-Label-Workflow-Agent
Smart n8n workflow that uses an open AI API to auto-classify Gmail emails into labels like “Application Received,” “Interview Invitation,” “Interview Scheduling,” and “Follow-Up.” Automatically organizes and archives your inbox. Perfect for job seekers—no coding or AI training needed. 
📬 n8n AI-Powered Gmail Email Classifier
This project is a no-code, AI-enhanced email sorting agent built using n8n, Gmail, and an open AI API like OpenAI, Cohere, or Hugging Face.

It automatically reads incoming emails, uses an AI model to classify them into four key job-related categories, and applies Gmail labels to keep your inbox organized. It’s ideal for job seekers or anyone dealing with large volumes of application-related emails.

🔧 Features
🤖 AI-based classification into:

Application Received

Interview Invitation

Interview Scheduling

Follow-Up & Next Steps

🏷️ Automatically creates and applies Gmail labels

📨 Archives messages to declutter the inbox

🛠️ No manual filtering, no keyword logic—just plug-and-play AI

🔄 Polls Gmail every 5 minutes for new unread emails

🧠 How It Works
Gmail Trigger detects new unread emails

Function Node extracts subject and body

HTTP Request sends content to an AI classification API

Switch Node reads the AI's response

Gmail Label Nodes apply the appropriate label

Gmail Modify Node archives the message from Inbox

⚙️ Requirements
An n8n instance (self-hosted or n8n.cloud)

Gmail OAuth2 credentials

API key for an AI model (e.g., OpenAI, Claude, Cohere)

Optional: Google Sheets/Slack for logging results

🚀 Quick Start
Import gmail_ai_classifier_workflow.json into n8n

Set up your Gmail and AI credentials

Customize the AI prompt (if needed)

Activate the workflow — you're done!

📌 Use Case
Stay focused on what matters by offloading email triage to a smart agent. This workflow is perfect for streamlining job applications, interview coordination, and recruiter communication—no coding required.

Let your inbox organize itself.
