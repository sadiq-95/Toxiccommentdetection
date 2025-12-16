# Telugu Comment Toxicity Detection System

A machine learning based web application for detecting toxic, abusive, and offensive comments in **Telugu**, with support for multilingual and code-mixed Indian language text. The system is built using **IndicBERT** and deployed as an interactive web app on **Hugging Face Spaces**.

🔗 **Live Demo**  
https://huggingface.co/spaces/Thilak118/teluguCommentToxicityDetection

---

## Problem Statement

With the rapid growth of regional language content on social media and online platforms, effective moderation for **low-resource languages like Telugu** remains a challenge. Existing toxicity detection systems are mostly English-centric and fail to perform well on Telugu and code-mixed text.

This project aims to bridge that gap by providing an **automated toxicity detection system focused on Telugu comments**, enabling scalable and reliable content moderation.

---

## Features

- Detects toxic, abusive, and offensive comments  
- Strong focus on Telugu language text  
- Handles Telugu-English code-mixed inputs  
- Trained on 200,000+ real-world comments  
- Interactive web-based interface  
- Fast and efficient inference  

---

## Model & Approach

- **Base Model**: IndicBERT  
- **Task**: Text classification (toxic vs non-toxic)  
- **Languages**: Telugu (primary), multilingual Indian text  
- **Dataset**:  
  - 200,000+ real-world comments collected from online platforms  
  - Includes abusive, offensive, and neutral samples  
- **Preprocessing**:  
  - Text normalization  
  - Handling of informal and code-mixed language  
  - Tokenization using IndicBERT tokenizer  

The model was fine-tuned to improve accuracy and robustness on low-resource and informal Telugu text commonly found on social media.

---

## Tech Stack

- **Programming Language**: Python  
- **NLP / Machine Learning**:  
  - Transformers  
  - IndicBERT  
  - PyTorch  
- **Web Interface**: Gradio  
- **Deployment**: Hugging Face Spaces  
- **Development Environment**: Jupyter Notebook  

---

## How It Works

1. User enters a Telugu or code-mixed comment  
2. Input text is preprocessed and tokenized  
3. IndicBERT model performs toxicity classification  
4. Output displays whether the comment is toxic or non-toxic  

---

## Installation (Local Setup)

```bash
git clone https://github.com/your-username/telugu-comment-toxicity-detection.git
cd telugu-comment-toxicity-detection
pip install -r requirements.txt
python app.py
