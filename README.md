# 🤖 Telegram AI Chatbot

A simple **n8n AI chatbot** that connects Telegram with OpenAI to provide helpful and intelligent responses to user messages.

## 🚀 Features

* 💬 Telegram chat integration
* 🤖 AI-powered responses
* 🧠 OpenAI GPT-5 Mini
* ⚡ Automatic message processing
* 📚 Beginner-friendly AI assistant
* 🔄 Real-time Telegram responses

## 🛠️ Tech Stack

* n8n
* Telegram
* OpenAI
* GPT-5 Mini

## 🔄 Workflow

Telegram Message
       ↓
Telegram Trigger
       ↓
AI Agent
       ↓
OpenAI Chat Model
       ↓
Send Response to Telegram

## ⚙️ How It Works

1. A user sends a message through Telegram.
2. The Telegram Trigger receives the message.
3. The AI Agent processes the user's question.
4. OpenAI GPT-5 Mini generates a response.
5. The response is automatically sent back to Telegram.

## 📁 Project Structure

telegram-ai-chatbot/
└── Telegram-AI-Chatbot.json

## 🔐 Setup

Before running the workflow, connect your own:

* Telegram Bot credentials
* OpenAI API credentials

Import the JSON workflow into n8n and configure your credentials.
