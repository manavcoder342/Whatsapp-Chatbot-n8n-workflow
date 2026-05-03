WhatsApp Business Chatbot - n8n Workflow

A powerful **WhatsApp Chatbot** built with **n8n** for business automation. Handle customer inquiries, automate responses, manage conversations, and provide 24/7 support using WhatsApp Business API.

![n8n](https://img.shields.io/badge/n8n-Workflow-blue?style=for-the-badge&logo=n8n)
![WhatsApp](https://img.shields.io/badge/WhatsApp-Business_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)

## ✨ Features

- **Intelligent Chatbot** with conversation flow
- **Multi-intent Support** (Greetings, Support, Orders, Bookings, etc.)
- **Interactive Buttons & Quick Replies**
- **Media Support** (Images, Documents, Videos)
- **Fallback & Human Handoff** logic
- **Logging & Conversation History**
- **Easy to extend with AI** (OpenAI, Groq, Claude, etc.)
- **Business-friendly** responses and templates

## 🎯 Use Cases

- Customer Support Chatbot
- Sales & Lead Qualification
- Order Tracking & Status Updates
- Appointment Booking System
- Restaurant / Clinic / Service Booking
- E-commerce Support
- Marketing & Promotions

## 📋 Prerequisites

- n8n (Self-hosted recommended)
- WhatsApp Business Account
- Meta Business Verification
- WhatsApp Business API Access (Cloud API)

## 🚀 Quick Setup

1. Import the workflow JSON into n8n
2. Set up **WhatsApp Business Cloud API** credentials
3. Configure the **Webhook** URL in Meta/WhatsApp settings
4. Activate the workflow
5. Start chatting with your bot!

## 📥 Workflow JSON

json
{{PASTE_YOUR_WORKFLOW_JSON_HERE}}
Copy the entire JSON above and import it directly into n8n.
🔧 Configuration Guide
1. Credentials

Create credential: WhatsApp Business Cloud API
Add your Phone Number ID, Access Token, and Webhook Verify Token

2. Webhook Setup

Copy the production webhook URL from the Webhook node
Paste it in your WhatsApp Business API configuration in Meta

3. Customize Responses

Edit the Switch or IF nodes for different intents
Update greeting, menu, and fallback messages
Add your business information

🛠 Tech Stack

n8n – Workflow Automation Tool
WhatsApp Business Cloud API
JavaScript (Code Nodes)
Ready for AI Integration

Roadmap

 AI-powered natural conversations (LLM integration)
 Multi-language support
 Integration with CRM / Google Sheets / Airtable
 Analytics dashboard
 Voice message support

Contributing
Contributions, improvements, and new features are welcome! Feel free to open issues or pull requests.
License
MIT License – Feel free to use this workflow for personal or commercial projects.

Made with ❤️ for Business Automation
⭐ If this helps you, consider starring the repository!
