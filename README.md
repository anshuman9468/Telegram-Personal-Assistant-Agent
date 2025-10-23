# 🤖 Telegram Assistant (n8n Workflow)

This is a **no-code Telegram AI Assistant** built entirely using **n8n**.  
It connects your **Telegram account**, **OpenAI model**, and **Google Calendar**, allowing you to chat with your personal AI assistant directly in Telegram.

---

## 🧩 Features

- 🧠 AI-powered chat using GPT-4.1-mini  
- 🗓️ Google Calendar integration for checking events  
- 💬 Real-time Telegram conversation  
- 🧏 Memory of last 7 messages for contextual replies  
- ⚙️ Fully no-code and customizable  

---

## ⚡ How It Works

1. **Telegram Trigger** → Starts when a message is received on Telegram.  
2. **Edit Fields** → Extracts `chat.id` and `message.text`.  
3. **AI Agent** → Processes message using GPT-4.1-mini and LangChain.  
4. **Google Calendar Tool** → Fetches schedule/events when requested.  
5. **Memory Buffer Window** → Stores last 7 messages for context.  
6. **Send a Text Message** → Sends AI’s reply back to Telegram.

---

## 🧠 Tech Stack

| Component | Purpose |
|------------|----------|
| n8n | Automation platform |
| Telegram API | Triggers and replies |
| OpenAI GPT-4.1-mini | AI model |
| LangChain Agent | AI logic orchestration |
| Google Calendar API | Schedule data |
| Memory Buffer | Conversational memory |

---

## 🧰 Setup Instructions

### Prerequisites
- n8n (Cloud or self-hosted)
- Telegram Bot Token (via [@BotFather](https://t.me/BotFather))
- OpenAI API Key
- Google Calendar OAuth credentials

### Installation
1. Import the JSON file into n8n:
2. Configure credentials:
- **Telegram API**
- **OpenAI API**
- **Google Calendar OAuth2**

3. Activate the workflow in n8n.
---

## 📈 Example Commands

| Command | Description |
|----------|--------------|
| `Hello` | Greets you politely |
| `What's my schedule today?` | Fetches today’s events |
| `Who are you?` | Describes its purpose |

---

## 🚀 Future Improvements

- Add voice message support  
- Add Notion or Todoist integration  
- Enable persistent long-term memory  

---

## 🧑‍💻 Author

**Anshuman Dutta**  
Made with ❤️ 

