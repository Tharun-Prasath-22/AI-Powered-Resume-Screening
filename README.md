# AI-Powered Resume Screening & Ranking System

## 📌 Overview
The **AI-Powered Resume Screening & Ranking System** is a web-based application that automates resume screening and ranking. Built using **Python, Streamlit, and scikit-learn**, this system compares uploaded resumes to a given job description and ranks them based on **TF-IDF & Cosine Similarity**.

This project is ideal for **recruiters, HR professionals, and hiring managers** who want to streamline the resume shortlisting process and improve efficiency.

---

## 🚀 Features
✅ Upload multiple **PDF** resumes.  
✅ Enter a **job description** to compare.  
✅ Uses **TF-IDF & Cosine Similarity** for ranking resumes.  
✅ Displays **ranked resumes** with similarity scores.  
✅ **Future Updates:** Advanced ML models (BERT/GPT), API integration, and multi-format support (DOCX, TXT, etc.).

---

## 📂 Folder Structure
```bash
resume_screening_app/
│── app.py                     # Main application file
│── requirements.txt            # Dependencies
├── Resume_Screening_Model.ipynb  # Jupyter Notebook for resume ranking
│── data/                       # Data directory
│   ├── UpdatedResumeDataSet.csv # Sample dataset
│   ├── sample_resume.pdf       # Sample resume file
│── README.md                   # Project documentation
🛠️ Installation & Setup
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/AI-Powered-Resume-Screening.git
cd AI-Powered-Resume-Screening
2️⃣ (Optional) Create a Virtual Environment
bash
Copy
Edit
python -m venv .venv
source .venv/bin/activate  # Mac/Linux
.venv\Scripts\activate     # Windows
3️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4️⃣ Run the Application
bash
Copy
Edit
streamlit run app.py
The app will open in your default web browser.

📌 How It Works
1️⃣ Upload PDF resumes using the file uploader.
2️⃣ Enter a job description in the provided text area.
3️⃣ The system extracts text from resumes and converts them into TF-IDF vectors.
4️⃣ The job description is compared against resumes using cosine similarity.
5️⃣ Ranked results are displayed with similarity scores.

📡 Deployment
🚀 Deploy on Streamlit Cloud (Free)
Push your project to GitHub.
Go to Streamlit Cloud and log in.
Click New App, select your repo, and set the file path to app.py.
Click Deploy 🚀.
🔧 Requirements
bash
Copy
Edit
streamlit
PyPDF2
pandas
scikit-learn
numpy
Install using:

bash
Copy
Edit
pip install -r requirements.txt
🎯 End Users
✅ HR & Recruiters – Automates resume screening for faster hiring.
✅ Hiring Managers – Ranks resumes efficiently for job roles.
✅ Job Portals – Enhances resume-job matching accuracy.
✅ AI Enthusiasts & Students – Learn NLP-based resume analysis.

🔮 Future Scope
✅ AI-Based Scoring – Use ML/Deep Learning for better ranking.
✅ Advanced NLP – Integrate BERT/GPT for deeper analysis.
✅ Multi-Format Support – Add support for DOCX, TXT, and OCR.
✅ Skill Matching – Extract and rank skills from resumes.
✅ API Integration – Connect with job portals & HR systems.

🔚 Conclusion
The AI-powered Resume Screening & Ranking System automates the time-consuming and inefficient process of manual resume screening. Using TF-IDF and Cosine Similarity, the system provides an objective and efficient ranking mechanism, ensuring faster and more accurate candidate shortlisting.

With PDF text extraction, real-time ranking, and easy deployment via Streamlit, this project is an excellent solution for recruiters, hiring managers, and job portals. 🚀

