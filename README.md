# E-commerce Customer Retention Analysis

**Business Analytics | Machine Learning | Natural Language Processing**

Predicting customer repurchase behavior using the Brazilian Olist E-commerce Dataset.

---

## Project Overview

Customer retention is one of the main challenges faced by e-commerce companies. Acquiring a new customer is considerably more expensive than retaining an existing one, making customer loyalty a key business objective.

This project analyzes customer purchasing behavior using the Brazilian **Olist E-commerce Dataset** to identify the factors associated with customer recurrence and develop predictive models capable of identifying customers with a high probability of not returning.

The project was developed as the **Capstone Project** of the **University Diploma in Data Science, Artificial Intelligence and its Applications in Economics and Business**.

---

## Business Objective

The main objective of this project is to answer the following business question:

> **How can an e-commerce company identify customers who are unlikely to return and implement effective customer retention strategies?**

---

## Project Structure

### Part 1 — Data Preparation, Exploratory Analysis and Statistical Modeling

📓 **Notebook**

`notebooks/01_data_preparation_and_eda.ipynb`

Main tasks:

- Data integration
- Data cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Regression analysis
- Principal Component Analysis (PCA)
- Hierarchical Clustering

---

### Part 2 — Machine Learning Models

📓 **Notebook**

`notebooks/02_machine_learning_models.ipynb`

Models evaluated:

- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Perceptron
- Support Vector Machine (SVM)

Model comparison was performed using:

- Accuracy
- Precision
- Recall
- ROC Curve
- Precision–Recall Curve

---

### Part 3 — Natural Language Processing

📓 **Notebook**

`notebooks/03_nlp_sentiment_analysis.ipynb`

This stage analyzes customer reviews using Natural Language Processing and Deep Learning techniques.

Main tasks:

- Text preprocessing
- Word embeddings
- Neural Network
- Sentiment Classification
- Analysis of misclassified reviews

---

## Database Integration

The analytical database was created by integrating multiple datasets from the Olist marketplace.

![Database Integration](images/Union%20de%20bases.png)

---

## Final Report

A complete report describing the methodology, results and business recommendations is available here:

📄 `reports/Customer_Retention_Analysis_Report.pdf`

---

## Main Findings

The analysis revealed that **shipping cost** is one of the strongest factors associated with customer non-recurrence.

Among the evaluated Machine Learning models, **Random Forest** achieved the best predictive performance.

The NLP model complemented the structured analysis by extracting valuable insights from customer reviews, highlighting the complexity of customer satisfaction and sentiment.

---

## Business Recommendations

Based on the analytical results, the following actions were proposed:

- Personalized shipping discounts
- Customer loyalty programs
- Product recommendation systems
- Targeted marketing campaigns
- Customer segmentation
- Data-driven retention strategies

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Statsmodels
- TensorFlow / Keras
- Natural Language Processing (NLP)
- Machine Learning
- Deep Learning
- Statistical Analysis

---

## Repository Structure

```
ecommerce-customer-retention-analysis/
│
├── data/
├── images/
├── notebooks/
│   ├── 01_data_preparation_and_eda.ipynb
│   ├── 02_machine_learning_models.ipynb
│   └── 03_nlp_sentiment_analysis.ipynb
├── reports/
│   └── Customer_Retention_Analysis_Report.pdf
└── README.md
```

---

## Author
**Jorgelina Etchevest**
Economist | Business & Data Analyst

**Skills**
Python • SQL • Tableau • Power BI • Machine Learning • NLP • Business Analytics
