# Grafana Gemini LLM Stack

This project integrates **Google Gemini LLM** with **Grafana V12.4** using **LiteLLM Proxy** on Ubuntu.

## Prerequisites
- Docker & Docker Compose
- Gemini API Key

## Setup
1. Clone this repo.
2. Create a `.env` file with your `GEMINI_API_KEY`.
3. Run the stack:
   ```bash
   docker-compose up -d

## Components

- **Grafana V12.4**: Built-in LLM Plugin enabled.
- **LiteLLM**: Acts as an OpenAI-compatible gateway for Gemini.
- **Gemini Pro**: The underlying LLM providing the intelligence.
