# SmartSphere AI: Agentic Google Workspace Assistant (Prototype)

> **Conversational agentic assistant for Google Calendar, Gmail, Tasks, and Drive — powered by LLMs, Python, and Google APIs.**

## Overview

SmartSphere AI is a prototype agentic assistant that unifies your Google digital life. It combines powerful LLM reasoning, real-time API integrations, and a memory layer to handle end-to-end workflows—all triggered from natural language conversation.

- **Automate** your scheduling, task management, follow-ups, document workflows, and emails.
- **Connect** multiple Google services (Calendar, Drive, Gmail, Tasks) in a single, context-aware loop.
- **Control** it entirely through human language—no technical prompts or scripting required.

## Key Features

- **Agentic orchestration**: Handles multi-step requests, decomposes them into actionable steps, and executes across Google services.
- **LLM-powered function-calling**: Uses OpenAI’s function-calling API for intelligent, dynamic tool invocation.
- **Persistent memory**: Maintains chat history and thread context for ongoing projects and multi-stage workflows.
- **Safety & transparency**: All risky operations (sending, deleting, sharing) require explicit confirmation, with live previews.
- **Extensible**: Designed for plug-and-play with new APIs and tools.

## Example Use Cases

- **“Plan my week and schedule deadlines around meetings.”**  
  SmartSphere scans your calendar, finds free time, and creates tasks—fully automated.
- **“Summarize a doc and email it to my team.”**  
  It fetches the file from Drive, summarizes it with an LLM, drafts the email, and sends after your confirmation.
- **“Remind me after client calls and log action items.”**  
  It adds reminders, creates follow-up tasks, and generates Google Docs for notes.

## Architecture

- **Python**: Core agentic logic, API clients, and orchestration.
- **OpenAI LLMs (function-calling)**: Converts user language to actionable plans, routes to the right tools.
- **Google APIs**: Calendar, Gmail, Drive, Tasks—all connected.
- **Memory/State Layer**: Tracks context across multiple steps and sessions.
- **Safety Layer**: Confirmation logic for risky/irreversible operations.


## Setup & Installation

> **Note:** This is an early-stage prototype. Some features require Google Cloud credentials and OpenAI API keys.

1. **Clone the repo**
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/smartsphere-agentic-assistant.git
   cd smartsphere-agentic-assistant
