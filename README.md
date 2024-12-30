# Job Description and Resume Matching System

This project is designed to streamline the recruitment process by automatically matching job descriptions with uploaded resumes using machine learning techniques. The system leverages text similarity algorithms to identify the most suitable candidates efficiently, presenting recruiters with the top matches based on similarity scores.

---

## 📂 Features

- **Job Description Input**: Recruiters can input detailed job descriptions into the system.
- **Resume Upload**: Candidates can upload their resumes in various formats (PDF, DOCX, TXT).
- **Matching Algorithm**: The system uses the Tf-Idf Vectorizer algorithm to compute similarity scores between job descriptions and resumes.
- **Result Display**: Displays the top 3 resumes with their respective similarity scores to assist recruiters in decision-making.

---

## 🛠️ Technologies Used

- **Python**: Backend development and text processing.
- **Flask**: Web framework for building the server and handling HTTP requests.
- **Bootstrap**: Responsive and user-friendly UI design.
- **Machine Learning Libraries**: Scikit-learn for implementing the Tf-Idf vectorization and cosine similarity.
- **HTML/CSS**: Markup and styling for the frontend.
- **PyPDF2, docx2txt**: Libraries for extracting text from uploaded resumes in various formats.

---

## ⚙️ Project Workflow

1. **Job Description Input**: Recruiters enter a job description in a text area.
2. **Resume Upload**: Candidates upload resumes in supported formats (PDF, DOCX, TXT).
3. **Text Extraction**: The system extracts text from the uploaded resumes using PyPDF2, docx2txt, or text file parsing.
4. **Vectorization**: Job descriptions and resumes are vectorized using Tf-Idf.
5. **Similarity Calculation**: Cosine similarity scores are computed between the job description and resumes.
6. **Top Matches**: The system identifies the top 3 resumes with the highest similarity scores and displays them to the recruiter.

---

## 📊 Insights and Results

- **Efficiency**: Saves recruiters significant time by automating the resume screening process.
- **Accuracy**: Identifies resumes most relevant to the provided job description.
- **Flexibility**: Supports multiple resume formats for wider usability.

---

## 🖥️ How to Run the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Job_Description_and_Resume_Matching_System.git

2. Install the required libraries:
```bash
pip install -r requirements.txt

3. Run the Flask application:
```bash
python app.py
