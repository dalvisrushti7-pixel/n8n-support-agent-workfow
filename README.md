# n8n-support-agent-workfow
# Build a Lean AI Agent Workflow in n8n Using APIs, Webhooks, and JSON

## Workflow
Webhook (POST) → AI Agent → Google Gemini Chat Model

## Description
This workflow receives user requests through a Webhook, processes input in JSON format, and uses Google Gemini via the AI Agent node to generate responses in real time.

## Technologies Used
- n8n
- Webhooks
- JSON
- Google Gemini API
- AI Agent Node

## Example Input
{
  "message": "My order hasn't arrived yet."
}

## Example Output
I apologize for the delay with your order. To help me investigate, please provide your order number.
