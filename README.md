# Linkedin-Skill-Gap-Analyzer
This project analyzes real LinkedIn job postings (2023–2024) and compares them with a user’s skill set to identify missing, high-demand skills. Built using NLP and semantic similarity, it acts as a career guide to help professionals upskill for their dream roles.

## 🚀 Features
- **Skill Extraction** from LinkedIn job postings using NLP (**spaCy + custom skill dictionary**)
- **Demand Ranking** for missing skills
- **Interactive Dashboard** via **Streamlit** (Under Development)
- Visual insights with **Matplotlib / Seaborn**

---

## 🛠 Tech Stack
- **Python**
- **Pandas / NumPy** → Data processing
- **spaCy** → Named Entity Recognition
- **Streamlit** → Interactive UI (Under Development)
- **Matplotlib / Seaborn** → Visualizations

---

## ⚡ How It Works
1. **Load Dataset** → LinkedIn job postings CSV (2023–2024)  
2. **Extract Skills** → Use NLP & regex from job descriptions  
3. **User Skills Input** → Example: `"Python, SQL, Machine Learning"`  
4. **Match & Rank** → Compare user skills vs. job posting skills using semantic similarity  
5. **Suggest Missing Skills** → Output ranked list with demand score

## 📂 Dataset
**Source:** [LinkedIn Job Postings (2023–2024) - Kaggle](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings)

**Download in Colab:**
```python
import kagglehub
path = kagglehub.dataset_download("arshkon/linkedin-job-postings")
print("Dataset Path:", path)
