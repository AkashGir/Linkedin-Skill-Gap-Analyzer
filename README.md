# Linkedin-Skill-Gap-Analyzer
This project analyzes real LinkedIn job postings (2023–2024) and compares them with a user’s skill set to identify missing, high-demand skills. Built using NLP and semantic similarity, it acts as a career guide to help professionals upskill for their dream roles.


🚀 Features
Extract Skills from LinkedIn job postings using NLP (spaCy + skill dictionary).

Match & Compare against user-provided skills.

Suggest Missing Skills ranked by demand.

Interactive Dashboard via Streamlit for easy use.

Pre-trained NLP Models (BERT/Sentence-BERT) for semantic matching.

🛠 Tech Stack
Python

Pandas / NumPy → Data processing

spaCy → Named Entity Recognition

HuggingFace Transformers → Sentence-BERT embeddings

Streamlit → Interactive UI

Matplotlib / Seaborn → Visualizations

📂 Dataset
Source: LinkedIn Job Postings (2023–2024) - Kaggle

Downloaded using kagglehub inside Google Colab.

⚡ How It Works
Load Dataset → LinkedIn job postings CSV (2023–2024).

Extract Skills → Use NLP & regex from job descriptions.

User Skills Input → Example: "Python, SQL, Machine Learning".

Match & Rank → Compare user skills vs. job posting skills using semantic similarity.

Suggest Missing Skills → Output ranked list with demand score.

