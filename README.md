# AI-Powered Text Summarizer Website

A simple web application that uses Python (Flask) and Natural Language Processing (NLTK TextRank) to generate summaries from user-provided text.

## Features
- Paste any text and get an automatic summary  
- Extractive summarization using word frequency scoring  
- Easy-to-use web UI (HTML + CSS + Flask)  
- Lightweight NLP model (no GPU needed)

## Tech Stack
- Python (Flask)
- HTML / CSS
- NLTK (TextRank-like algorithm)

## How to Run

```bash
# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate         # Mac / Linux
venv\Scripts\activate            # Windows

# Install required dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py
