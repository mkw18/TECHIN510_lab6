# Lab 6 - Chat with PDF

## Getting Started

1. `python -m venv venv`
1. `source venv/bin/activate`
1. `pip install -r requirements.txt`
1. `cp .env.sample .env`
1. Change the `.env` file to match your environment
1. `streamlit run app.py`

## Files included

- app.py: When running the file, type 'please provide feedback to the resume / cover letter' in  the chatbox, then it can provide feedback to the resume or cover letter.

## Lesson Learnt

- How to use RAG to extract knowledge from pdf.
- How to use openai api by llama index.
- How to show chat message in streamlit.

## Question to ask
- I found the example on official github of llama index that when creating the openai chat engine, the chat mode is "openai". But when I apply "openai" to chat mode, it usually can't recognize the system prompts, which make me confused.