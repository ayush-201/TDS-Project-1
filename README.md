# TDS Virtual TA 

This project implements a RAG-based virtual TA for the IITM TDS course, combining course content and Discourse posts.

## Deployment

- Built with Flask and OpenAI API (via AIProxy)

## Environment Variables

- `AIPROXY_TOKEN` — required (set via Railway's Environment Variables UI)

## Endpoints

- POST `/api/` with:
  ```json
  {
    "question": "...",
    "image": "base64string (optional)"
  }


##Credits
- IIT Madras Data Science
- Developed by Ayush Kumar, June 2025.

