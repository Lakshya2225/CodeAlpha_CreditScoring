# 💳 Credit Scoring Model

A Machine Learning project developed as part of the **CodeAlpha Machine Learning Internship** to predict whether a customer is a **Good Credit Risk** or **Bad Credit Risk** using classification algorithms.

---

## 📌 Project Overview

Financial institutions use credit scoring models to determine whether a customer is likely to repay a loan. This project applies Machine Learning techniques to classify customer credit risk using the German Credit dataset.

The project includes:
- Data preprocessing
- Missing value handling
- Label Encoding
- Model training
- Model comparison
- Performance evaluation
- Model serialization using Joblib

---

## 📂 Dataset

- **Dataset:** German Credit Dataset
- **Total Records:** 1000
- **Target Variable:** Risk
  - Good Credit
  - Bad Credit

Features include:

- Age
- Sex
- Job
- Housing
- Saving Accounts
- Checking Account
- Credit Amount
- Duration
- Purpose

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Jupyter Notebook

---

## 📁 Project Structure

```
CodeAlpha_CreditScoring/
│
├── dataset/
│   └── german_credit_data.csv
│
├── images/
│   └── image.png
│
├── model/
│   └── credit_scoring_model.pkl
│
├── notebook/
│   └── Credit_Scoring.ipynb
│
├── README.md
├── requirements.txt
├── app.py
├── test.py
└── .gitignore
```

---

## ⚙️ Workflow

1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis (EDA)
4. Handle Missing Values
5. Encode Categorical Features
6. Train-Test Split
7. Train Machine Learning Models
8. Evaluate Performance
9. Save Best Model

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📊 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|---------:|----------:|--------:|----------:|
| Logistic Regression | 66.5% | 69.73% | 92.14% | 79.38% |
| Decision Tree | 60.5% | 72.26% | 70.71% | 71.48% |
| **Random Forest** | **72.0%** | **74.71%** | **90.71%** | **81.94%** |

**Best Performing Model:** Random Forest Classifier

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## 📸 Confusion Matrix

The Random Forest model achieved the best performance.

You can find the confusion matrix inside:

```
images/image.png
```

---

## 💾 Model Saving

The trained Random Forest model is saved using Joblib.

```python
joblib.dump(rf, "credit_scoring_model.pkl")
```

Saved model location:

```
model/credit_scoring_model.pkl
```

---

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/Lakshya2225/CodeAlpha_CreditScoring.git
```

Go to the project directory:

```bash
cd CodeAlpha_CreditScoring
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```
notebook/Credit_Scoring.ipynb
```

---

## 🚀 Future Improvements

- Hyperparameter Tuning
- Feature Engineering
- Cross Validation
- ROC-AUC Curve
- One-Hot Encoding
- Streamlit/Flask Web Application
- Model Deployment

---

## 👨‍💻 Author

**Lakshya Neema**

- GitHub: https://github.com/Lakshya2225

---

## ⭐ Acknowledgement

This project was developed as part of the **CodeAlpha Machine Learning Internship** using the German Credit Dataset for educational purposes.
