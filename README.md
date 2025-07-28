

# Transformer-Based Question Answering System

A simple yet powerful question answering system using Hugging Face Transformers and SQuAD v1.1, built during my NLP internship at **Elevvoo Tech**.

## 🔍 Overview

This project builds a system that can extract answers from a context paragraph using transformer models like DistilBERT.

## 📌 Features

- Pre-trained models fine-tuned on SQuAD v1.1
- Evaluated on 50 validation samples:
  - **Exact Match:** 84.00%
  - **F1 Score:** 85.60%
- Streamlit app with ngrok support for deployment
- Interactive interface for custom questions

## 🛠️ Tools & Libraries

- Python
- Hugging Face Transformers
- Datasets (SQuAD v1.1)
- Pandas
- Streamlit
- Pyngrok

## 🚀 Usage

### 1. Install dependencies

```bash
pip install -r requirements.txt
