🎓 Student Performance Prediction using Machine Learning
📌 Problem Motivation

Student academic performance is a critical indicator of educational success. However, identifying students who are at risk of failing is often done too late, usually after examinations. This project aims to use machine learning techniques to analyze historical student data and predict whether a student is likely to pass or fail the final examination. Early prediction can help educators, parents, and institutions take timely corrective actions such as academic counseling, extra classes, or personalized support.

📂 Dataset Description

Source: UCI Machine Learning Repository

Dataset Type: Tabular

Number of Records: ~400–500 student instances

Features:

Academic attributes (study time, previous grades, failures)

Social and demographic attributes (parental education, guardian, absences)

Behavioral attributes (going out with friends, health status)

Target Variable: Student final status (Pass / Fail)

🧹 Pre-processing Steps

The dataset was prepared using the following steps:

Handling missing and inconsistent values

Encoding categorical variables into numerical values

Feature scaling to normalize numerical attributes

Removing irrelevant or redundant features

Splitting the dataset into:

Training set

Validation set

Test set

These steps improved model convergence and generalization.

🤖 Algorithm Explanations

The problem was formulated as a binary classification task. The following machine learning algorithms were implemented and compared:

Logistic Regression:
Used as a baseline classifier due to its simplicity and interpretability.

K-Nearest Neighbors (KNN):
A distance-based classifier that assigns class labels based on nearest neighbors.

Support Vector Machine (SVM):
Implemented using Linear, Polynomial, and Gaussian (RBF) kernels.
Hyperparameter tuning was performed to obtain optimal performance.

📊 Evaluation Tables + Plots

Model performance was evaluated using standard classification metrics:

Accuracy

F1-Score

Confusion Matrix

ROC Curve

ROC-AUC Score

🔹 Sample Comparison Table
Model	Accuracy (%)	F1-Score	ROC-AUC
Logistic Regression	~78	0.75	0.81
KNN	~80	0.77	0.79
SVM (Linear Kernel)	~84	0.82	0.80

Visualization plots such as confusion matrices and ROC curves were used to analyze model behavior and performance.

✅ Conclusion & 🔮 Future Scope
Conclusion

The experimental results demonstrate that machine learning models can effectively predict student academic performance. Among all tested models, Support Vector Machine with a linear kernel achieved the best overall performance. Feature analysis revealed key academic and behavioral factors influencing student success.

Future Scope

Use larger and more diverse datasets

Apply deep learning models

Deploy the model as a web-based application

Integrate real-time academic monitoring systems
