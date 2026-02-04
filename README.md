# Top Lawyers RAG Chatbot

An AI-powered chatbot built with n8n for the Top Avvocati legal services platform. Uses a RAG (Retrieval Augmented Generation) system to guide users toward the most relevant legal service based on their needs.

## How It Works

The system is divided into multiple n8n workflows:

- **Main Chat Workflow** — handles the conversation with the user in real time
- **RAG Indexing Workflow** — crawls the website pages and converts them into embedded vectors used to contextualize chatbot responses
- **Support Workflows** — error detection, chat history logging, and usage statistics

## Key Features

- The chatbot is not a simple FAQ bot. It runs a real AI agent that analyzes each user message and decides the best action.
- Source pages retrieved via RAG are rendered as clickable links directly in the chat interface.
- The CTA to book a consultation is visually distinct from other messages.
- Suggested follow-up questions are generated dynamically based on the conversation context, helping users explore content more effectively.

## Contents

| File | Description |
|---|---|
| `Workflow-chatbot.json` | The main n8n workflow (importable) |
| `Workflow-chatbot.png` | Visual diagram of the workflow |
| `Chat-1.png` | Screenshot of the chatbot in action |
| `Video-Chat-in-azione.mp4` | Demo video of the chatbot |
