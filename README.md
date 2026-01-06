# Resume Screening and Job Recommendation System

A Flask-based web application that screens resumes, extracts key information, and recommends suitable job roles using machine learning models.

## 🚀 Features

* Upload resumes in **PDF** or **TXT** format
* Extracts **name, phone number, email, education, and skills**
* Predicts **resume category** using trained ML models
* Recommends a **job role** suitable for the candidate
* User-friendly web interface with clean design

## 🛠️ Tech Stack

* **Backend**: Python, Flask
* **Frontend**: HTML, CSS
* **ML Models**: Random Forest, TF-IDF Vectorizer (scikit-learn)
* **Libraries**: PyPDF2, pandas, numpy

## 📂 Project Structure

```
project-root/
│── app.py                     # Flask server
│── requirements.txt            # Dependencies
│── README.md                   # Project documentation
│
├── templates/
│   └── resume.html             # Frontend HTML template
|
├──static
│   └── style.css               # CSS styles
│
├── models/                     # Trained ML models (pkl files)
│   ├── rf_classifier_categorization.pkl
│   ├── tfidf_vectorizer_categorization.pkl
│   ├── rf_classifier_job_recommendation.pkl
│   └── tfidf_vectorizer_job_recommendation.pkl
│
├── data/                       # Datasets (optional, if small)
│   ├── UpdatedResumeDataSet.csv
│   ├── Resume.csv
│   └── clean_resume_data.csv
```

## ⚙️ Installation & Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/resume-screening.git
   cd resume-screening
   ```

2. Create a virtual environment (recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate   # For Linux/Mac
   venv\Scripts\activate      # For Windows
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:

   ```bash
   python app.py
   ```

5. Open your browser and go to:

   ```
   http://127.0.0.1:5000/
   ```

## 📊 Example Output

After uploading a resume, the app displays:

* Predicted Resume Category
* Recommended Job Role
* Extracted Candidate Details (Name, Phone, Email, Skills, Education)

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.


