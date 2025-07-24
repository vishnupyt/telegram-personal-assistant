# 🤖 Telegram Personal Assistant (Beginner Project)

Welcome to my beginner-friendly **AI-powered Telegram Personal Assistant** built using **n8n** and **OpenAI**!

Unlike traditional Telegram bots that use commands like `/bookevent` or `/sendemail`, this assistant can **understand natural language directly** from the user and trigger workflows without needing slash commands.

---

## 🧠 What It Does

- ✅ Understands messages like:  
  - _"Remind me to call John tomorrow at 5 PM"_  
  - _"Send an email to Priya about the project delay"_  
  - _"Add a calendar event for my meeting next Monday at 10 AM"_

- ✅ Automatically detects **intent** (booking events, sending emails, fetching calendar) using **OpenAI’s GPT model**.

- ✅ Passes the data to appropriate workflows (like Email, Calendar, or Notes) in **n8n**, a no-code/low-code automation platform.

---

## 🔧 Tools & Tech Used

- **n8n**: For creating custom no-code workflows
- **Telegram Bot API**: To receive and send user messages
- **OpenAI (GPT)**: To analyze user messages and understand their intent
- **Code Nodes in n8n**: To process logic and dynamically parse messages

---

## 🛠 Project Features

| Feature            | Description |
|--------------------|-------------|
| 🌍 Natural Language | No slash commands! Just type like you talk. |
| 🧠 AI Intent Parsing | GPT understands what the user is trying to do. |
| 🗓️ Smart Workflows  | Events, reminders, and emails handled automatically. |
| 🧑‍💻 Beginner Project | Built as part of my journey to learn automation and AI. |

---

## 🚀 How It Works (Simplified)

1. **Telegram Trigger** receives the user's message.
2. Message is passed to **OpenAI GPT** to detect intent (email/calendar/reminder).
3. Based on intent, **Switch Node** in n8n routes the message to the correct workflow.
4. Additional **Code Node** logic parses the required fields (e.g., date, recipient, subject).
5. n8n executes the action using integrations (email/calendar APIs, etc.)

---

## 📷 Screenshots

![Screenshot 1](./screenshots/screenshot1.png)  
![Screenshot 2](./screenshots/screenshot2.png)

---

## 📘 Why I Built This

As a **complete beginner**, I wanted to explore:

- How AI can understand plain English messages
- Building practical automations using **n8n**
- Using **Telegram as a UI** for personal productivity
- Combining no-code tools with powerful AI

This is part of my learning journey in AI Automation and workflow systems.

---

## 📍 Next Goals

- Add Google Calendar API integration
- Add error handling and fallback messages
- Expand to handle WhatsApp messages using Twilio
- Deploy on cloud and make it production-ready

---

## 🤝 Want to Contribute?

This is a beginner-friendly project. If you're learning **n8n**, **OpenAI**, or **Telegram bots**, feel free to fork it and try building your own version.

---

## 📬 Contact

If you're interested in collaboration, guidance, or just want to connect:

- Twitter: [@yourhandle](https://twitter.com/yourhandle)
- LinkedIn: [Your Name](https://linkedin.com/in/yourprofile)

---

## ⭐️ Support

If you like this project, feel free to **star** the repo and share it with others on Reddit, Twitter, or LinkedIn!

---

> 🚧 Built with love and curiosity by a beginner trying to learn AI automation from scratch.
