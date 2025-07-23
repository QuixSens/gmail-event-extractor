# 📩 Gmail Event Extractor → 📅 Google Calendar

A Python tool to automatically extract events from Gmail emails and add them to Google Calendar using regex or an LLM (DeepSeek, OpenAI).

---

## 🧠 Features

- 🔍 Reads emails and detects event info (Date, Time, Venue)
- 🧠 Uses either regex or AI (e.g., DeepSeek/OpenAI)
- 📅 Automatically creates Google Calendar events

---

## 🔧 Requirements

- Python 3.8+
- Gmail account (IMAP enabled)
- Google Calendar API credentials
- Python packages: `google-auth`, `google-api-python-client`, etc.

---

## 🚀 Setup

1. **Clone or Download the Repo**
2. **Install Dependencies**

```bash
pip install -r requirements.txt

Enable Gmail IMAP and Setup Google Calendar API

Get credentials file (credentials.json)

Enable Google Calendar API from Google Cloud Console

Run the Script
python main.py

📥 Example Email Format
Subject: TEDx DAU Event  
Date: 2nd August 2025  
Time: 2:00 PM  
Venue: Lecture Theater-1, DAU

📁 Project Structure
gmail-event-extractor/
├── main.py
├── requirements.txt
├── sample_email.txt
└── README.md

🎥 Demo & Explanation
Watch the full breakdown on YouTube:
👉 YouTube Video Link

💡 Created by QuixSens


---
