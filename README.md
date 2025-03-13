# Data Ethics Assignment

## Overview
This project focuses on **data ethics in machine learning** by ensuring responsible collection, storage, and use of customer data. The goal is to analyze customer purchase patterns, build a **customer churn prediction model**, and implement data privacy and anonymization techniques.

## Problem Statement

### Part I: Customer Behavior Analysis & Churn Prediction
#### Introduction
As an online grocery delivery company, **Everyday Deals**, you are part of the data science team working to scale up the business with the power of data. Your team is tasked with generating better product recommendations for existing customers to enhance engagement and reduce churn.

#### Assignment Tasks
1. **Understand customer buying patterns and trends** based on the provided dataset.
2. **Identify customers likely to churn** and analyze possible reasons.
3. **Build a machine learning model** to predict customer churn based on assumptions.
4. **Define model evaluation metrics** to assess performance.
5. **Document the assumptions taken** for identifying churn and model building.

This part of the project focuses on analyzing transaction data and making business decisions based on customer behavior insights.

---

### Part II: Ethical Data Handling & Privacy Measures
#### Data Ethics Considerations
Ensuring ethical data handling is critical in this assignment. The goal is to identify and anonymize sensitive information while preserving dataset integrity for analysis.

#### Assignment Tasks
1. **Data Classification:** Identify and classify personally identifiable information (PII) such as names, addresses, phone numbers, and credit card details.
2. **Data Minimization:** Determine which sensitive attributes can be removed or securely stored with restricted access.
3. **Attribute Masking:** Apply masking techniques to protect customer identities while maintaining dataset usability.
4. **Non-Sensitive Attribute Identification:** Identify useful but non-sensitive attributes that provide business insights.
5. **Non-Personal Attribute Identification:** Determine attributes that do not contain PII but are useful for market research or modeling.
6. **Data Anonymization:** Apply generalization, suppression, or randomization to ensure privacy compliance.
7. **Updated Dataset Submission:** Implement privacy measures and submit the anonymized dataset along with a report outlining the steps taken.

## Dataset
The dataset contains customer transaction details with some level of anonymization. However, further processing is required to ensure compliance with ethical standards.

### Dataset and Data Dictionary Links
- **Data Dictionary:** [View Here](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fcdn.upgrad.com%2Fuploads%2Fproduction%2F7ef685a7-12c5-459b-a204-781c84934457%2FData%2Bethics%2Bassignment%2B-%2Bdata%2Bdictionary.xlsx&wdOrigin=BROWSELINK)
- **Dataset:** [Download Here](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fcdn.upgrad.com%2Fuploads%2Fproduction%2Fb30e3fc7-60d0-4dec-86e8-9f9a2aacba29%2FData%2Bethics%2Bassignment%2B-%2Bdataset.xlsx&wdOrigin=BROWSELINK)

## Project Pipeline

### 1. Data Understanding & Preprocessing
- Load and explore the dataset.
- Identify missing, duplicate, and inconsistent data.
- Define assumptions for identifying churn-prone customers.

### 2. Customer Behavior Analysis
- Identify buying patterns and trends among customers.
- Determine key factors contributing to customer churn.
- Use exploratory data analysis (EDA) to visualize trends.

### 3. Customer Churn Prediction Model
- Select a machine learning model (e.g., logistic regression, decision trees, random forests).
- Train the model using selected features.
- Evaluate model performance using accuracy, precision, recall, and F1-score.

### 4. Ethical Data Processing & Anonymization
- **Data Classification:** Identify and classify sensitive information (e.g., names, phone numbers, email addresses).
- **Data Minimization:** Remove or securely store sensitive attributes.
- **Attribute Masking:** Mask identifiable attributes to ensure privacy.
- **Non-Sensitive Attribute Identification:** Retain useful attributes for analysis while ensuring compliance with data ethics.
- **Data Anonymization Techniques:** Apply generalization, suppression, or randomization to protect customer identity.

### 5. Updated Data Submission
- Apply privacy measures and anonymization techniques.
- Submit an updated dataset with sensitive information anonymized.
- Provide a brief report outlining the privacy steps taken.

## Technologies Used
- **Python (Pandas, NumPy, Scikit-learn)**: Data processing and model building
- **Matplotlib/Seaborn**: Data visualization
- **Data Privacy Techniques**: Attribute masking, generalization, and anonymization

## Setup Instructions
1. Install dependencies:
   ```sh
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
2. Load and preprocess the dataset.
3. Perform EDA and define churn assumptions.
4. Train and evaluate the churn prediction model.
5. Apply anonymization techniques and submit updated files.

## Findings & Observations
- Identified key factors influencing customer churn.
- Ethical handling of customer data through anonymization and masking.
- Maintained dataset integrity while ensuring privacy compliance.

