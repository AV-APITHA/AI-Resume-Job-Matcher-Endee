# AI Resume–Job Matching & Ranking System using RAG and Endee Vector Database

## 📌 Overview
This project is an AI-powered Resume–Job Matching and Ranking system that uses
**semantic search and vector similarity** to evaluate how well resumes match a
given job description.

The system helps recruiters:
- Identify the most relevant candidates
- Rank resumes based on semantic similarity
- Understand skill gaps for each candidate

The project is built using the **Endee Vector Database** as the core vector
storage and retrieval layer and follows **RAG (Retrieval-Augmented) principles**,
where retrieved resume context is used to augment job–candidate analysis.

---

## 🚀 Features
- Upload and process multiple resumes (PDF format)
- Convert resumes and job descriptions into vector embeddings
- Store and retrieve embeddings using Endee Vector Database
- Semantic resume–job matching using vector similarity
- Ranking of resumes based on match percentage
- Skill gap analysis (strong skills vs missing skills)

---

## 🧠 Tech Stack
- Python
- Google Colab
- Sentence Transformers
- Endee Vector Database
- Scikit-learn
- NumPy
- PyPDF

---

## 🗄️ Endee Integration
The **Endee Vector Database** is used as the core vector storage and retrieval
mechanism in this project.

Integration steps:
- Forked the official Endee repository
- Used Endee as the vector database layer for storing resume embeddings
- Stored vectors along with resume metadata
- Performed semantic similarity search for resume–job matching and ranking

🔗 **Forked Endee Repository:**  
https://github.com/AV-APITHA/endee

---

## 🔍 How It Works
1. Resume PDFs are uploaded and text is extracted
2. Resume text is converted into vector embeddings
3. Embeddings are stored using Endee
4. Job description is converted into an embedding
5. Semantic similarity is calculated between job and resumes
6. Resumes are ranked based on similarity score
7. Skill gap analysis is generated for each resume

---

## ▶️ How to Run
1. Open `resume_job_matcher.ipynb` in Google Colab
2. Install dependencies listed in `requirements.txt`
3. Upload resume PDF files
4. Run all notebook cells
5. View ranked resumes and skill gap analysis output

---

## 📊 Sample Output
- Ranked list of resumes with match percentage
- Strong skills identified for each resume
- Missing skills highlighted for improvement

(Screenshots are available in the `screenshots/` folder)

---

## 🔮 Future Enhancements
- Streamlit-based web interface
- LLM-based answer generation using full RAG pipeline
- Job recommendation system
- Multi-job and multi-resume comparison dashboard

---

## 👩‍💻 Author
AV-APITHA

