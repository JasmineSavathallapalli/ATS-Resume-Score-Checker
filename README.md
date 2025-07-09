# 📄 ATS Resume Score Checker

A smart and interactive tool to analyze how well your resume performs in an Applicant Tracking System (ATS). Built using **Python, spaCy, NLTK, scikit-learn**, and **matplotlib**, this tool simulates ATS behavior to provide both a **base resume quality score** and an optional **job description match score**.


## 🚀 Features

- 📂 Supports `.pdf`, `.docx`, and `.txt` resumes and job descriptions
- 🎯 Calculates ATS score based on:
  - Resume structure
  - Action verbs
  - Section presence (Experience, Education, Skills)
  - Length and formatting
- 🔍 Optionally compares resume to a Job Description using **TF-IDF + cosine similarity**
- 📊 Visual score display with matplotlib bar chart
- 🧠 Keyword suggestions & action verb recommendations
- 📉 Flags missing sections and over/underlength resumes
- ⚡ Built for interactive use in **Google Colab** using widgets


## 📦 Dependencies

- Python ≥ 3.7  
- Libraries:
  - `python-docx`
  - `PyPDF2`
  - `nltk`
  - `spacy`
  - `matplotlib`
  - `scikit-learn`
  - `ipywidgets`

🧠 How It Works
Base Score: Based on section presence, formatting bullets, use of action verbs, resume length

JD Match Score: If a job description is uploaded, matches using TF-IDF + cosine similarity

Improvement Tips: Recommends missing keywords, sections, and better phrasing

Output: ATS score (0–100), bar graph, keyword gaps, and writing suggestions
