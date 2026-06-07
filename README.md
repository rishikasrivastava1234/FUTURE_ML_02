# Support Ticket Classification System using NLP & Machine Learning

## Overview

This project focuses on automatically classifying customer complaint tickets into predefined categories using Natural Language Processing (NLP) and Machine Learning techniques.

Customer support teams receive thousands of complaints every day. Manually reviewing and routing these tickets is time-consuming and prone to delays. This project demonstrates how text classification can be used to automatically identify the category of a complaint and streamline the support process.

The model was trained on real-world consumer complaint data and achieved an accuracy of **81.72%** using TF-IDF feature extraction and Logistic Regression.

---

## Problem Statement

Organizations receive large volumes of customer complaints related to different financial products and services. Manually categorizing these complaints can be inefficient and lead to delays in issue resolution.

The objective of this project is to build a machine learning model capable of automatically classifying complaint narratives into their appropriate categories.

---

## Dataset

The project uses consumer complaint records containing:

* Consumer Complaint Narrative (text description)
* Product Category (target label)

Due to the large dataset size, the raw dataset is not included in this repository.

Users can download the dataset separately and place it inside the `data/` directory before running the notebook.

### Categories Used

* Credit Card or Prepaid Card
* Credit Reporting & Credit Repair Services
* Debt Collection
* Mortgage
* Student Loan

---

## Project Workflow

1. Data Loading and Exploration
2. Text Cleaning and Preprocessing
3. TF-IDF Feature Extraction
4. Train-Test Split
5. Logistic Regression Model Training
6. Model Evaluation
7. Sample Prediction
8. Model Saving using Pickle

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Natural Language Processing (NLP)
* TF-IDF Vectorization
* Logistic Regression
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Model Performance

### Accuracy

**81.72%**

### Evaluation Metrics

The model was evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Project Structure

```text
FUTURE_ML_02/
│
├── data/
│
├── notebook/
│   └── support_ticket_classification.ipynb
│
├── screenshots/
│   ├── dataset preview.png
│   ├── cleaned text.png
│   ├── tf idf.png
│   ├── train split.png
│   ├── classification report.png
│   ├── confusion matrix.png
│   └── sample prediction.png
│
├── requirements.txt
└── README.md
```

---

## Results

* Model Accuracy: **81.72%**
* Successfully classified customer complaint narratives into predefined categories.
* Automated ticket categorization using NLP techniques.
* Generated predictions for unseen complaint text.

---

## Sample Prediction

Input Complaint:

> I was denied a mortgage loan even though my credit score is good.

Predicted Category:

> Debt Collection

---

## Future Improvements

* Experiment with advanced NLP models such as BERT.
* Build a web interface using Streamlit.
* Support real-time complaint classification.
* Improve performance through hyperparameter tuning.

---

## Conclusion

This project demonstrates the practical application of Natural Language Processing and Machine Learning in automating support ticket classification. By using TF-IDF feature extraction and Logistic Regression, the system can efficiently categorize customer complaints and help streamline support operations.
