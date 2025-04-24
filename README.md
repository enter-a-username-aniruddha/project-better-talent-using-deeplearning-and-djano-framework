# Project Better Talent - AI Response Detection System

> **An AI-driven framework to detect and differentiate between human-written and AI-generated responses in case-study based hiring processes.**

## 🚀 Project Overview

**Better Talent** is a deep learning and Django-based web application that enables organizations to assess the authenticity of candidate responses during recruitment. It detects whether responses are genuinely human-written or generated with the help of AI tools like ChatGPT/GPT-4.

This system integrates advanced **Natural Language Processing (NLP)** and **unsupervised learning** techniques such as BERT, GPT-2 embeddings, K-Means clustering, and Autoencoders to evaluate text authenticity and ensure fair hiring decisions.

## 📌 Key Features

- ✅ Detects AI-generated responses using linguistic patterns and embeddings.
- 🔍 Embedding-based feature extraction with BERT and GPT-2.
- 🧠 Unsupervised clustering via K-Means for pattern discovery.
- 📉 Anomaly detection using Autoencoders.
- 🌐 Django-based web portal for candidate registration and response submission.
- 🧮 AI probability score for each response with classification.
- 🗂️ MySQL database integration for secure response storage.

## 🧪 Technologies Used

| Category | Tech Stack |
|---------|------------|
| **Frontend** | HTML, CSS, JavaScript (via Django Templates) |
| **Backend** | Python, Django Framework |
| **AI/ML** | BERT, GPT-2, K-Means, Autoencoders, Scikit-learn, PyTorch |
| **Database** | MySQL |
| **Deployment** | Localhost (development) [http://amiportal.in:8002](http://amiportal.in:8002) |

## 📊 Results

The system classifies each candidate response with an **AI Probability Score**, ensuring:
- Transparent and fair evaluation.
- Identification of AI-generated or paraphrased content.
- Prevention of undeserved candidate shortlisting based on AI-written answers.

## 📈 Future Work

- ✅ Real-time detection enhancements.
- 🧩 Incorporation of more transformer models (e.g., GPT-4, LLaMA).
- 🌍 Cloud deployment and API support.
- 🛡️ Improved resistance to paraphrased AI content.

## 🤝 Acknowledgements

Developed as part of MSc in Statistics & Data Science capstone project at **NMIMS, Mumbai** in collaboration with **Axis My India**.

Mentors:
- **Mrs. Shraddha Sarode** (NMIMS)
- **Mr. Sundar Balasubramaniam** (Axis My India)
