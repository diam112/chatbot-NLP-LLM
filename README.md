# Multi-Subject AI Chatbot 

A modular AI chatbot that automatically detects the subject of a user’s question and retrieves verified information from online sources, with optional transformer-based answer generation. Designed as a professional portfolio project and developed using Google Colab.

---

## Overview

This project demonstrates an end-to-end AI chatbot capable of answering questions across multiple academic domains such as biology, chemistry, physics, mathematics, computer science, and history.

The system combines:
- Automatic subject detection
- Verified knowledge retrieval from Wikipedia
- Optional large language model (LLM)–based explanation generation

The focus is on **modularity, transparency, and reproducibility**, rather than black-box answers.

---

## Features

- Automatic subject classification using NLP
- Factual answer retrieval from Wikipedia
- Optional transformer-based text generation
- Modular and extensible architecture
- Runs in Google Colab or Jupyter Notebook
- Portfolio-ready, well-documented implementation

---

## System Architecture

User Question  
→ Subject Detection (TF-IDF + Naive Bayes)  
→ Knowledge Retrieval (Wikipedia API)  
→ Optional AI-Based Explanation (Hugging Face Transformers)  
→ Final Answer

---

## Technologies Used

- Python
- Scikit-learn (TF-IDF, Naive Bayes)
- Wikipedia API
- Hugging Face Transformers
- PyTorch
- Google Colab

---

## How to Run

### Option 1: Google Colab (Recommended)
1. Open Google Colab
2. Upload the notebook or open it from GitHub
3. Enable GPU (optional): Runtime → Change runtime type → GPU
4. Run all cells from top to bottom
5. Ask questions using the example cells or interactive loop

### Option 2: Jupyter Notebook
```bash
pip install wikipedia transformers torch scikit-learn sentencepiece
jupyter notebook
