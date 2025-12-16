📌 Problem Statement

Online platforms with regional language content often lack effective moderation tools, especially for low-resource languages like Telugu.
Manual moderation does not scale, and most existing models perform poorly on code-mixed or regional abusive text.

This project aims to solve that gap by building an automated toxicity detection system focused on Telugu comments.

🚀 Features

Detects toxic, abusive, and offensive language

Strong focus on Telugu

Handles code-mixed text (Telugu + English)

Trained on 200,000+ real-world comments

Web-based interactive interface

Fast inference suitable for real-time use

🧠 Model & Approach

Base Model: IndicBERT

Task: Text classification (toxic vs non-toxic)

Languages: Telugu (primary), multilingual Indian text

Data:

Real-world comments collected from online platforms

Includes abusive, offensive, and neutral samples

Preprocessing:

Text normalization

Handling code-mixed inputs

Tokenization using IndicBERT tokenizer

The model was fine-tuned to improve robustness on low-resource and informal text, which is common in social media comments.

🛠️ Tech Stack

Programming Language: Python

ML / NLP:

Transformers

IndicBERT

PyTorch

Web Interface: Gradio

Deployment: Hugging Face Spaces

Notebook: Jupyter

🖥️ How the Application Works

User enters a Telugu or code-mixed comment

Text is preprocessed and tokenized

IndicBERT model performs classification

Output displays whether the comment is toxic or non-toxic

📦 Installation (Local Setup)
git clone https://github.com/your-username/telugu-comment-toxicity-detection.git
cd telugu-comment-toxicity-detection
pip install -r requirements.txt
python app.py

🌐 Deployment

The project is deployed using Hugging Face Spaces, allowing anyone to test the model without local setup.

Live link:
https://huggingface.co/spaces/Thilak118/teluguCommentToxicityDetection

📊 Results

Improved accuracy on Telugu abusive text

Better handling of informal and code-mixed language

More robust compared to generic English-only toxicity models

👨‍💻 Author

M Sadiq

LinkedIn: https://linkedin.com/in/m-sadiq


Project details and background are aligned with the author’s academic and practical experience in cybersecurity and applied machine learning 

📈 Future Enhancements

Multi-class toxicity labels (hate, threat, harassment, etc.)

Support for more Indian languages

API-based integration for social media platforms

Improved explainability using attention visualization
