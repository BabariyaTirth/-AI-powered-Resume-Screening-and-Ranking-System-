# AI Resume Scanning & Candidate Ranking System

## Overview
This is an AI-driven Resume Screening and Ranking System based on Streamlit. It assists recruiters and hiring managers in analyzing and ranking resumes according to a provided job description through Natural Language Processing (NLP) methods, namely TF-IDF vectorization and cosine similarity.

## Features
- **PDF Resume Parsing**: Text extraction from PDF resumes uploaded.
- **Job Description Matching**: Matches resumes to a given job description
- **Automated Candidate Ranking**: Ranks resumes using TF-IDF and cosine similarity.
- **Streamlit Web Interface**: Interactive UI for resume upload and result viewing.

## Technologies Used.
- **Python**: Underlying programming language.
- **Streamlit**: Web framework used for UI.
- **PyPDF2**: Text extraction from PDF resumes.
- **scikit-learn**: Applies TF-IDF vectorization and ranking results.
- **pandas**: Filters and shows ranked results.

## Installation
### Prerequisites
- Python 
- pip package manager

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/ai-resume-ranking.git](https://github.com/BabariyaTirth/-AI-powered-Resume-Screening-and-Ranking-System-
   cd ai-resume-ranking
   ```
2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the Streamlit application:
   ```sh
   streamlit run app.py
   ```.

## Usage
1. Enter the job description in the provided text area.
2. Upload one or multiple resumes in PDF format.
3. Click the **Submit** button to rank resumes based on relevance.
4. View the ranked list of candidates with similarity scores .


