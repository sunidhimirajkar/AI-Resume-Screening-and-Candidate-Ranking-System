# AI-Resume-Screening-and-Candidate-Ranking-System

An intelligent web application designed to automate and streamline the initial phase of the hiring process by scoring and ranking candidates based on their resume's relevance to a specific job description.

## ✨ Features

* **PDF Text Extraction:** Reads and extracts text content directly from uploaded PDF resumes using `PyPDF2`.
* **Relevance Scoring:** Utilizes **TF-IDF (Term Frequency-Inverse Document Frequency)** and **Cosine Similarity** to calculate a numerical score indicating how well a resume matches the provided job description.
* **Candidate Ranking:** Automatically sorts and displays resumes in descending order of their similarity score, highlighting the best-fit candidates first.
* **Intuitive Web Interface:** Built with **Streamlit** for a simple, interactive user experience.

## 🛠️ Technologies & Libraries

The project is built entirely in Python and leverages powerful machine learning and data handling libraries:

* **Python 3.x**
* **Streamlit:** For creating the interactive web application.
* **Scikit-Learn:**
    * `TfidfVectorizer`: To convert text into numerical vectors.
    * `cosine_similarity`: To calculate the similarity score.
* **PyPDF2:** For extracting text from PDF files.
* **Pandas:** For managing and displaying the ranked results in a clear table format.
