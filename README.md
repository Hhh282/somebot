# somebot # GibberishBot AI Backend

A simple FastAPI backend for a chatbot API.  
Send POST requests to `/chat` with JSON `{ "message": "your text" }`  
and get AI-style replies.

## Deploy on Render.com

- Push this repo to GitHub  
- Connect to Render and create a new Web Service  
- Use the start command: `uvicorn main:app --host 0.0.0.0 --port $PORT`

## Run locally

```bash
pip install -r requirements.txt
uvicorn main:app --reload
