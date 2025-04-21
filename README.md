# -AI-Powered-Resume-Matcher
 AI-Powered Resume Matcher!
🎯 Goal:
Match job descriptions to resumes using NLP techniques and rank them based on relevance.

✅ Step 1: Define Requirements
Input: A job description (text)

Input: Multiple resumes (as text or PDF, we’ll extract text)

Output: Ranked list of resumes based on similarity





🧱 Tech Stack
Python (main language)

NLP with TF-IDF and cosine similarity

Flask (to make it a web app)

Optionally: PDF parsing with PyMuPDF or pdfminer

resume-matcher/
├── app/
│   ├── templates/
│   │   └── index.html
│   ├── static/
│   ├── __init__.py
│   ├── matcher.py         # Core logic
│   └── routes.py          # Flask routes
├── resumes/               # Uploaded resumes
├── job_descriptions/      # Uploaded job descriptions
├── app.py                 # App launcher
├── requirements.txt
└── README.md
