# Multilingual-Sentiment-Analyzer
Built by **Pearl Shah** · CS & Linguistics @ SJSU

## 🚀 Live Demo
👉 [**Try it here — no installation needed!**](https://huggingface.co/spaces/Pearlvs/multilingual-sentiment-analyzer)


## What it does
Analyzes the emotional tone of text across 100+ languages in real time. 
Input any text — English, Spanish, Hindi, French, Mandarin, and more — 
and get instant sentiment detection (positive, neutral, negative) with 
a confidence score.

## Why I built this
As a CS and  Linguistics major, I wanted to bridge both fields into 
one project. Language is not one-size-fits-all — sentiment in Spanish 
doesn't work the same way as in English, and most tools only handle 
English well. This project explores how multilingual NLP models handle 
that complexity.

## Demo
<img width="1350" height="708" alt="Screenshot 2026-06-15 at 3 12 22 PM" src="https://github.com/user-attachments/assets/84354040-fd25-4e4e-bdb9-517ed3d54b0c" />


## Tech stack
- Python
- Hugging Face Transformers (bert-base-multilingual-uncased-sentiment)
- Gradio (web UI)
- langdetect (language identification)
- Google Colab

## How to run it

### Option 1 — Google Colab (easiest)
Click here → [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Rxt7yBMCWJUbQpY7Lsyg_2mUshCJjClk#scrollTo=jY8i8fr0RxXc)

### Option 2 — Local
```bash
pip install transformers torch gradio langdetect
jupyter notebook sentiment_analyzer.ipynb
```

## Sample outputs
| Input | Language | Sentiment | Confidence |
|---|---|---|---|
| "I love this!" | English 🇺🇸 | POSITIVE 😊 | 98.2% |
| "Me encanta!" | Spanish 🇪🇸 | POSITIVE 😊 | 96.1% |
| "यह अच्छा है" | Hindi 🇮🇳 | POSITIVE 😊 | 91.4% |
| "C'est difficile" | French 🇫🇷 | NEGATIVE 😔 | 87.3% |

## What I learned
- How transformer models handle multilingual tokenization differently
- Why low-resource languages have lower confidence scores
- How linguistic structure (SOV vs SVO word order) affects sentiment 
  detection accuracy

  ⚠️ Note: Sentiment accuracy varies by language. 
Low-resource languages may produce less reliable results 
due to unequal training data distribution — a known 
limitation of multilingual NLP models.

## Connect
[linkedin.com/in/pearlshah24](https://linkedin.com/in/pearlshah24)
