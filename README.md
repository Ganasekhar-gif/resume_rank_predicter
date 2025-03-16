# resume_rank_predicter

Project Overview

The Resume Rank Predictor is a machine learning-based application designed to evaluate and rank resumes based on key features such as skills, experience, education, and project details. This tool aims to assist hiring managers and recruiters in identifying top candidates efficiently.

Features

Automated Resume Ranking: Predicts a rank for each resume based on its content.

Skill Analysis: Identifies technical and soft skills.

Experience Evaluation: Considers past roles, durations, and achievements.

Education Assessment: Ranks education background with respect to role requirements.

Project Analysis: Considers the relevance of completed projects to the desired job role.

User-Friendly Interface: Provides clear visual feedback for each ranked resume.

Technologies Used

Python (Primary Language)

Scikit-learn (Model Development)

Pandas and NumPy (Data Processing)

NLTK (Natural Language Processing for text analysis)

Streamlit (Web Framework for deployment)

HTML/CSS/JavaScript (Frontend Interface)

Data Collection and Preprocessing

Collected resume datasets containing various job roles and candidate details.

Performed data cleaning to remove irrelevant information and standardize text data.

Extracted key features such as skills, education, and experience using NLP techniques.

Model Development

Applied various machine learning algorithms such as:

Logistic Regression

Evaluated model performance using metrics like accuracy, precision, and recall.

Installation Instructions

Clone the repository:

git clone https://github.com/your-username/resume-rank-predictor.git
cd resume-rank-predictor

Install dependencies:

pip install -r requirements.txt

Run the application:

python app.py

Open the web interface in your browser at http://localhost:5000.

How to Use

Upload a resume in .pdf or .docx format.

The system will analyze the content and assign a rank based on extracted features.

The ranked resumes will be displayed in a structured format with key highlights.

Results and Insights

Achieved 85% accuracy with the Random Forest Classifier model.

Optimized feature extraction improved prediction consistency and precision.

Enhanced user interface ensures clear visualization of ranked resumes.

Future Enhancements

Implement multi-language support for international resumes.

Incorporate additional job role datasets to improve model diversity.

Add resume keyword suggestions to improve candidate profiles.

Contributors

Ganasekhar kalla - Data Scientist and Developer



