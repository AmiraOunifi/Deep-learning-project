# French to English Translation Project

## Overview
This project implements a translation system capable of translating text between French and English. It utilizes a pre-trained model (`Helsinki-NLP/opus-mt`) from Hugging Face, which was trained on multilingual translation tasks. The project features an interactive system for inputting English sentences and receiving French translations.

## Features
- Translation from English to French in real-time.
- High accuracy for general-purpose and conversational text.
- Minimal setup with pre-trained transformer models.

## Tools and Libraries
- **Python**: Core programming language for implementation.
- **Hugging Face Transformers**: For loading and utilizing the pre-trained `Helsinki-NLP` translation models.
- **Pandas**: For dataset handling and manipulation.
- **Kaggle Dataset**: Parallel text pairs for benchmarking.

## Prerequisites
Ensure the following libraries are installed:
```bash
pip install -r requirements.txt
