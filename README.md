# bunana-ai-backend

This is the backend for Bunana.AI, a chatbot powered by OpenAI's API.

## Features
- Accepts user queries.
- Processes queries with OpenAI GPT.
- Returns AI-generated responses.

## How to Use
- Deploy the backend on Railway.
- Send POST requests to the `/bunana` endpoint with a JSON body containing the user's query.

## Example
- Request:
  ```json
  {
    "query": "What is the meaning of life?"
  }
