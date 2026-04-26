# PDF Summarizer

A Streamlit web app that summarizes PDF documents (or raw text) using the **Cohere** summarization API.

## Features

- 📄 Upload a PDF or paste text directly
- 🧠 Summarization via Cohere's `summarize` endpoint
- 🧹 Built-in text cleaning (deduplication, special-character removal)
- 🎨 Custom-styled Streamlit UI

## Setup

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt

cp .env.example .env
# then edit .env and add your COHERE_API_KEY
```

Get a free Cohere API key at https://dashboard.cohere.com/api-keys

## Usage

```bash
streamlit run app.py
```

Then open http://localhost:8501

## Stack

- Python 3.9+
- Streamlit
- Cohere
- pdfplumber
- python-dotenv

## License

MIT
