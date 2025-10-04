# n8n AI Agent

This repository contains an n8n workflow for an AI agent.

## How to Import into n8n
1. Open your n8n instance (Cloud or Self-hosted).
2. Go to "Workflows".
3. Click on the three-dot menu → **Import from file**.
4. Select `workflows/ai-agent.json`.

## Features
- Chat trigger (listens for messages).
- Rule-based categorization (EMAIL, BUDGET, SCHEDULE, etc.).
- Extensible for AI integrations.

## Notes
- This workflow requires the `LangChain Chat Trigger` node.
- You may need to set up API keys (e.g. OpenAI) depending on your usage.
