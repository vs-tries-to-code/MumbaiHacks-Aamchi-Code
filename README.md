# Medical Myth Buster – AI Agent

A lightweight AI agent that verifies health-related claims using trusted medical sources and provides safe, evidence-based responses.

## Features
- Detects and analyzes medical claims  
- Verifies information with credible sources  
- Generates safe, concise, research-backed outputs  

## Tech Stack
- n8n (agent workflows)  
- LLMs 
- Tavily API 

## How It Works
1. User submits a health claim  
2. Agent checks if it is medical  
3. Extracts keywords and validates information  
4. Returns True / False / Unverifiable with explanation

## Running the Project
1. Clone the repository  
2. Add API keys to `.env`  
3. Import the n8n workflow  
4. Start n8n locally

## Business Model
API-as-a-service for healthcare platforms and partners.

## Disclaimer
This system does **not** replace professional medical advice.