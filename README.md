Analysing At-Risk-Prediction Dataset

BMS College of Engineering – Department of Information Science and Engineering
Bachelor of Engineering (B.E.) Project, 2022-23

Authors:
	•	Aditi Sankaranarayanan (1BM20IS011)
	•	Diya Shetty (1BM20IS033)
	•	Hrishikesh Prahalad (1BM20IS051)
	•	Ibrahim Javeed Khan (1BM20IS052)

Guide: Mrs. Rashmi R, Assistant Professor

⸻

Table of Contents
	•	Abstract￼
	•	Introduction￼
	•	Problem Statement￼
	•	Literature Survey￼
	•	System Requirements￼
	•	System Design￼
	•	Implementation￼
	•	Test Results￼
	•	Conclusion￼
	•	References￼

⸻

Abstract

Machine learning (ML) algorithms are widely used for data analysis and prediction. This project focused on an At-Risk-Prediction Dataset for diabetes.

Key steps included:
	1.	Data analysis and visualization to understand the dataset
	2.	Feature selection and handling missing values
	3.	Selection of appropriate ML models for classification
	4.	Hyperparameter tuning to improve performance
	5.	Comparison of multiple models to select the best performing one

⸻

Introduction

Diabetes is a chronic medical condition affecting millions worldwide. Early diagnosis can prevent complications like heart disease, kidney disease, blindness, and amputations.

Traditional diagnosis relies on fasting blood glucose, oral glucose tolerance, and hemoglobin A1C tests, which have limitations such as cost, patient discomfort, and potential false results.

This project explores ML-based diabetes diagnosis, aiming to develop a reliable and efficient tool to assist healthcare professionals in making accurate and timely diagnoses. Patient data (demographics, medical history, lab results) is used to train and test ML models to predict the likelihood of diabetes.

⸻

Problem Statement

Traditional diabetes diagnostic methods face limitations in cost, comfort, and accuracy. Machine learning techniques can improve diagnostic efficiency and reliability.

Objective:
	•	Develop a ML-based tool to predict diabetes diagnosis from patient data
	•	Contribute to more effective, accessible, and timely diabetes diagnostics

⸻

Literature Survey
	•	Dataset: Pima Indians Diabetes Database by the National Institute of Diabetes and Digestive and Kidney Diseases
	•	Dataset characteristics:
	•	Female patients of Pima Indian heritage
	•	Ages 21 and above
	•	Several features related to health metrics and lab results

⸻

System Requirements

Operating System: Windows 10 or above
RAM: 8 GB or above
Applications: Google Colab

⸻

System Design

(Include flow diagram here if available; for GitHub, you can add as flowchart.png or directly embed a Mermaid diagram)

⸻

Implementation

Data Preprocessing:
	•	Handled null values using domain knowledge and correlation analysis
	•	Removed irrelevant or missing data and selected the most important features

Models Used:
	1.	Decision Tree
	•	Built and fine-tuned using Grid Search
	2.	Logistic Regression
	•	Compared performance with Decision Tree

Model Tuning:
	•	Hyperparameter tuning improved model accuracy
	•	Final comparison helped select the best-performing model

⸻

Test Results
	•	Decision Tree Model: Initial accuracy
	•	Fine-Tuned Decision Tree Model: Improved accuracy after Grid Search
	•	Logistic Regression Model: Compared to Decision Tree
(Include tables, graphs, or metrics here if available – e.g., Accuracy, Precision, Recall, F1-Score)

⸻

Conclusion
	•	ML models can accurately predict diabetes diagnosis based on patient data
	•	ML-based diagnostic tools assist healthcare professionals with timely and accurate decisions
	•	Potential for better insights into disease management
	•	Limitations: data availability, quality, and need for further validation
	•	Future work: refine model, include more clinical outcomes, and improve dataset diversity

