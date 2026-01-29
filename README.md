# Earnings Call Analyzer (Mistral + Ollama)

AI-powered tool for summarizing earnings call transcripts, classifying sentiment,
and extracting key financial insights.

## Features
- 3-sentence earnings call summary
- Sentiment classification
- Key financial insights (growth, risks, guidance)
- FastAPI backend + Streamlit frontend

## How to Run
1. Pull model:
   ollama pull mistral
2. Start backend:
   uvicorn backend.main:app --reload
3. Start frontend:
   streamlit run frontend/app.py
