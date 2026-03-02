# 📩 Support Ticket Classification System

This project builds a Machine Learning model to automatically classify customer support tickets into categories and assign priority levels.

It helps support teams respond faster and route tickets efficiently.

---

## 🎯 Problem Statement

Businesses receive hundreds of customer support tickets daily.  
Manually categorizing and prioritizing them is time-consuming and inefficient.

This project uses Natural Language Processing (NLP) and Machine Learning to:

- Classify tickets into categories (Technical, Billing, Account)
- Automatically assign priority levels (High / Medium / Low)

---

## 🛠 Tools & Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Matplotlib / Seaborn

---

## 🧠 Machine Learning Approach

### 1️⃣ Text Preprocessing
- Converted text to lowercase
- Cleaned basic formatting

### 2️⃣ Feature Extraction
- Used **TF-IDF (Term Frequency–Inverse Document Frequency)**
- Converted text data into numerical vectors

### 3️⃣ Model Training
- Logistic Regression classifier trained on ticket data
- Train-Test split used for evaluation

### 4️⃣ Model Evaluation
- Used Classification Report
- Measured Precision, Recall, and F1-Score

---

## 🚦 Priority Assignment Logic

A simple rule-based system assigns priority:

- High → Critical issues (not working, crashing, incorrect charges)
- Medium → Performance-related issues
- Low → General account updates or minor requests

---

## 📊 Output

- Automatic ticket category prediction
- Priority tagging
- Confusion Matrix visualization
- Classification performance metrics

---

## 💼 Business Impact

This system can:

- Reduce manual ticket sorting time
- Improve response speed
- Automatically route tickets to correct departments
- Enhance customer satisfaction

---

## 🚀 Future Improvements

- Use advanced NLP models (e.g., Naive Bayes / SVM)
- Deploy as a web application
- Add real-time ticket prediction API
- Integrate with CRM systems

---

## 📂 Project Structure

FUTURE_ML_02/
│
├── ticket_classification.ipynb
├── support_tickets.csv
└── README.md

---

## 📌 Internship Track

Machine Learning Internship – Future Interns  
Track Code: ML  
Task 2 – Support Ticket Classification
