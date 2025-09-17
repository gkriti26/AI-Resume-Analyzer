# AI-Resume-Analyzer
-Developed an AI-powered Resume Analyzer using Python and Streamlit that automated parsing of PDF resumes, reducing manual screening effort and improving recruiter efficiency.\\      -Integrated NLP techniques (tokenization, entity recognition, keyword matching) to extract candidate details such as skills, education

An AI-powered tool built with **Python, Streamlit, and NLP** to analyze resumes against job descriptions.

## 🚀 Features
- Parse resumes from PDF/DOCX
- Extract candidate skills using rule-based + semantic NLP
- Match resumes with job description (JD) skills
- Show missing skills & match percentage
- AI-generated insights using OpenAI API
- Interactive dashboard with Plotly charts

## 🛠 Tech Stack
- Python, Streamlit
- spaCy, SentenceTransformers
- pdfplumber, python-docx
- Plotly Express
- OpenAI API

## ⚙️ Installation
```bash
git clone https://github.com/gkriti26/AI-Resume-Analyzer.git
cd AI-Resume-Analyzer
pip install -r requirements.txt
streamlit run app.py
