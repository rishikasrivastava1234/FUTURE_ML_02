# Support Ticket Classification System using NLP & Machine Learning

## Overview

This project focuses on automatically classifying customer complaint tickets into predefined categories using Natural Language Processing (NLP) and Machine Learning techniques.

Customer support teams often receive thousands of complaints every day. Manually reviewing and routing these tickets is time-consuming and prone to delays. This project demonstrates how text classification can be used to automatically identify the category of a complaint and streamline the support process.

The model was trained on real-world consumer complaint data and achieved an accuracy of **81.72%** using TF-IDF feature extraction and Logistic Regression.

---

## Problem Statement

Organizations receive customer complaints related to different financial products and services. Efficiently categorizing these complaints is essential for:

* Faster ticket routing
* Reduced manual effort
* Improved customer support efficiency
* Better issue tracking and analysis

The objective of this project is to build a machine learning model capable of predicting the complaint category from the complaint text.

---

## Dataset

The project uses consumer complaint records containing:

* Consumer Complaint Narrative (text description)
* Product Category (target label)

### Categories Used

* Credit Card or Prepaid Card
* Credit Reporting & Credit Repair Services
* Debt Collection
* Mortgage
* Student Loan

---

## Project Workflow

### 1. Data Preparation

* Loaded and filtered complaint records
* Removed missing values
* Selected relevant categories

### 2. Text Preprocessing

* Converted text to lowercase
* Removed special characters and unwanted symbols
* Cleaned complaint narratives for analysis

### 3. Feature Engineering

* Applied TF-IDF Vectorization
* Generated 5,000 text features

### 4. Model Training

* Split data into training and testing sets
* Trained a Logistic Regression classifier

### 5. Model Evaluation

* Accuracy Score
* Classification Report
* Confusion Matrix

### 6. Prediction System

* Accepts new complaint text
* Predicts the most likely complaint category

---

## Model Performance

| Metric   | Score  |
| -------- | ------ |
| Accuracy | 81.72% |

The model demonstrated strong classification performance across multiple complaint categories while maintaining good precision and recall scores.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* TF-IDF Vectorizer
* Logistic Regression
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

---

## Project Structure

```text
FUTURE_ML_02
│
├── notebook/
│   └── support_ticket_classification.ipynb
│
├── screenshots/
│   ├── dataset_preview.png
│   ├── cleaned_text.png
│   ├── tf_idf.png
│   ├── train_split.png
│   ├── classification_report.png
│   ├── confusion_matrix.png
│   └── sample_prediction.png
│
├── requirements.txt
└── README.md
```

---

## Sample Prediction

**Input Complaint**

> "I was denied a mortgage loan even though my credit score is good."

**Predicted Category**

> Mortgage

---

## Future Improvements

* Experiment with advanced NLP models
* Compare multiple classification algorithms
* Deploy the model as a web application
* Integrate real-time ticket prediction APIs

---

## Author

**Rishika Srivastava**

Machine Learning & Data Science Enthusiast
