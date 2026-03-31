# API Documentation

## POST /analyze
Analyze single text

Request:
{
  "text": "I love this"
}

Response:
{
  "sentiment": "positive",
  "score": 0.95
}

---

## POST /upload
Upload CSV file

Response:
{
  "results": [...]
}