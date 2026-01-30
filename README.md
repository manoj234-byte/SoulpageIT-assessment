# Conversational Knowledge Bot – LangChain + Gemini

## Overview
This project implements a conversational knowledge bot using LangChain and Google Gemini. The bot maintains conversation memory, performs live web search, and answers contextual factual questions.

## Features
- Conversational memory using ConversationBufferMemory
- Web search via DuckDuckGo
- Context-aware follow-up answers
- Command-line chat loop
- Optional Streamlit UI

## Architecture
- LLM: Gemini 1.5 Flash
- Agent: Conversational ReAct Agent
- Memory: ConversationBufferMemory
- Tool: DuckDuckGo Web Search

## Setup
1. Create a Google API key
2. Set environment variable:
   export GOOGLE_API_KEY=your_key
3. Install dependencies:
   pip install -r requirements.txt
4. Run CLI:
   python main.py
5. Run UI:
   streamlit run streamlit_app.py

## Example Conversation
User: Who is the CEO of OpenAI?  
Bot: Sam Altman is the CEO of OpenAI.  

User: Where did he study?  
Bot: Sam Altman studied at Stanford University.

## Repository Structure
- main.py
- requirements.txt
- README.md
- 
