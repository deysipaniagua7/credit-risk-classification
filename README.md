# credit-risk-classification
# **Credit Risk Classification Repository**  

## **Module Overview**  
This repository contains my **Module 20 Credit Risk Classification Challenge**.  

In this challenge, we used various techniques to **train and evaluate a model based on loan risk**. The dataset used consists of **historical lending activity** from a **peer-to-peer lending services company**. The objective was to build a model that **identifies the creditworthiness of borrowers**.  

The challenge was divided into three parts:  
- **Splitting the data** into training and testing sets.  
- **Creating a logistic regression model** using the original dataset.  
- **Writing a Credit Risk Analysis Report**, including a **summary and performance analysis** of the machine learning models used.  

## **Credit Risk Analysis Report**  

### **Overview of the Analysis**  
The purpose of this analysis was to **create a supervised machine learning model** that predicts whether a loan is **healthy** or **high-risk**.  

A **logistic regression model** was used to analyze financial data, including:  
- **Loan size**  
- **Interest rate**  
- **Borrower income**  
- **Debt-to-income ratio**  
- **Number of accounts**  
- **Derogatory marks**  
- **Total debt**  

The goal was to predict loan status as either:  
- **Healthy loan ("0")**  
- **High-risk loan ("1")**  

### **Steps Taken**  
- **Split the data** into labels and features, setting **"loan_status"** as the label and the remaining columns as features.  
- **Divided the dataset** into training and testing sets using **train_test_split**.  
- **Created a logistic regression model** using the training data.  
- **Made predictions** on the test dataset using the fitted model.  
- **Evaluated the model's performance** by generating a **confusion matrix** and a **classification report**.  

### **Results**  
The following metrics describe the **logistic regression model’s performance**:  

- **Accuracy**: The model had an **overall accuracy of 99%**, correctly classifying loans **99% of the time**.  
- **Precision**:  
  - **Healthy loans (class 0):** **100% precision**  
  - **High-risk loans (class 1):** **84% precision**  
- **Recall**:  
  - **Healthy loans (class 0):** **99% recall**  
  - **High-risk loans (class 1):** **94% recall**  

### **Summary**  
- The **logistic regression model is highly effective** at predicting **healthy loans (class 0)**, achieving **100% precision** and **99% recall**.  
- However, it is **less accurate at predicting high-risk loans (class 1)**, with **84% precision** and **94% recall**.  
- The **imbalance in the dataset** may contribute to this difference, as class 0 contains **18,765 instances**, whereas class 1 contains only **619 instances**.  
- **High-risk loan predictions are more important** than healthy loan predictions because financial institutions **face greater losses from misclassifying risky loans**.  
- A **more balanced dataset** would likely **improve model performance**.  

## **Repo Breakdown**  
The main **"credit_risk-classification"** repository contains:  
- **Credit_Risk** folder, which houses:  
  - **"credit_risk_classification.ipynb"** (Jupyter Notebook with code implementation).  
  - **"lending_data.csv"** (dataset used for training and evaluation).  

> **Note:** I used **in-class activities and notes** to complete this challenge.  
