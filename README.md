# Inbox Autopilot 📩

An AI-powered Gmail inbox assistant that automates email classification, summarization, and organization using Google Apps Script and Groq LLM.

## 🚀 Features

- Automatically processes Gmail messages.
- Uses AI to classify and summarize emails.
- Sends Telegram notifications for important, non-spam emails.
- Creates reply drafts for emails that require a response.
- Labels and archives newsletters and spam.
- Maintains activity logs using Google Sheets.

## 🛠️ Tech Stack

- Google Apps Script
- Gmail API / Gmail Services
- Groq API (LLM)
- Telegram Bot API
- Google Sheets

## ⚙️ Architecture

Gmail Inbox → Google Apps Script → Groq LLM → Email Classification and Summarization → Telegram Notifications / Gmail Drafts / Google Sheets Logs

## 🔐 Configuration

Configure the following credentials in Google Apps Script Project Settings → Script Properties:

- `GROQ_API_KEY`
- `TELEGRAM_BOT_TOKEN`
- `TELEGRAM_CHAT_ID`

**Important:** Never expose API keys or bot tokens publicly.

## 📌 Project Purpose

The goal of Inbox Autopilot is to reduce manual email management by using AI-powered automation to organize messages and highlight important communications.

## 👨‍💻 Author

Abhishek Kokkula
