# 🚀 AI-Powered WhatsApp Assistant (n8n + OpenAI)

An advanced, fully automated WhatsApp Business Assistant that handles customer queries 24/7. Built using the power of **n8n**, **OpenAI**, and **Whapi.cloud**.

## 📊 Workflow Overview
![Full Workflow](./images/workflow.png)
*Visual representation of the n8n automation flow.*

## ✨ Key Features
- **💬 Intelligent Text Chat:** Powered by GPT-4o.
- **🎙️ Voice Note Transcription:** Whisper API integration.
- **🖼️ Image Vision:** Analyzes media files instantly.
- **🧠 Knowledge Base:** Supabase Vector Store for RAG.

## 🛠️ Tech Stack
- **n8n.io** | **OpenAI** | **Whapi.cloud** | **Supabase**

## 📱 Live Demo
<p align="center">
  <img src="./images/demo.png" width="300" title="WhatsApp Chat Demo">
</p>
*Example of the bot responding to a customer query.*

## 📝 How It Works
1. **Trigger:** Message received via Webhook from Whapi.cloud.
2. **Logic:** Switch node identifies message type (Text/Voice/Image).
3. **Processing:** AI Agent retrieves data from Supabase and generates a response.
4. **Action:** Final reply is sent back via HTTP Request.

## 🚀 Getting Started
1. Download `AI-Powered WhatsApp Assistant.json`.
2. Import into n8n.
3. Add your API Keys (OpenAI, Supabase, Whapi).
4. Execute and test!

---
Built with ❤️ by [Your Name]
