##Cross-Variety-Sarcasm-and-Sentiment-Detector



## Overview
This project explores sarcasm detection and sentiment classification across multiple English dialects using both traditional machine learning and modern transformer-based approaches.

The coursework investigates:
- Sentiment classification
- Sarcasm detection
- Cross-variety generalisation
- Dialect-aware NLP systems
- Explainability using LIME and SHAP
- LLM fine-tuning with LoRA
- Few-shot prompting
- Streamlit deployment

---

## English Varieties
The project focuses on three English dialects:

- British English (en-UK)
- Australian English (en-AU)
- Indian English (en-IN)

---

## Models Used

### 1. TF-IDF + Logistic Regression
Traditional NLP baseline using:
- TF-IDF vectorization
- Unigrams and bigrams
- Logistic Regression classifier

### 2. RoBERTa
Fine-tuned transformer-based model for:
- Sentiment classification
- Sarcasm detection

### 3. Llama 3.2 + LoRA
Parameter-efficient fine-tuning using:
- Llama 3.2 1B
- LoRA adapters
- Few-shot prompting

---

## Repository Structure

```text
BESSTIE-NLP-Coursework/
│
├── notebooks/
│   ├── 01_tfidf_roberta.ipynb
│   ├── 02_cross_variety_evaluation.ipynb
│   └── 03_llama_lora_fewshot.ipynb
│
├── app/
│   └── app.py
│
├── report/
│   └── Report_PG26.pdf
│
├── requirements.txt
├── README.md
└── .gitignore
