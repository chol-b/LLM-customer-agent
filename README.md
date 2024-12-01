# LLM customer call answering agent

This project implements an AI-powered inbound call agent for Mobile Network Operator(MTN Rwanda as a case study). It uses OpenAI's new realtime API and integrates with Twilio to handle incoming phone calls.

## Functionalities

- RAG using OpenAI Assistants API
- Function Calling
- Caller History

This version uses Make.com as the backend for processing all RAG and Function Calls. 



## Features

- Handles incoming calls using Twilio's voice services
- Utilizes OpenAI's realtime API for natural language processing
- Transcribes user speech and generates AI responses in real-time
- Extracts customer details (name, availability, and special notes) from the conversation
- Sends extracted information to a webhook for further processing

## Technologies Used

- Node.js
- Fastify (web framework)
- WebSocket (for real-time communication)
- OpenAI GPT-4 Realtime API
- Twilio (for telephony services)
- dotenv (for environment variable management)

## Setup

   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add the following:
   ```
   OPENAI_API_KEY=your_openai_api_key
   ```

4. Start the server:
   ```
   npm start
   ```

## Usage

Once the server is running, it will handle incoming Twilio calls. The AI agent will engage with callers, transcribe their speech, generate appropriate responses, and extract relevant information from the conversation.


