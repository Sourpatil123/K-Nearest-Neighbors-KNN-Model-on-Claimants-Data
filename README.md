# K-Nearest-Neighbors-KNN-Model-on-Claimants-Data
🧠 K-Nearest Neighbors (KNN) Model on Claimants Data
📘 Project Overview

This project applies the K-Nearest Neighbors (KNN) algorithm to analyze Claimants Data and predict class labels based on feature similarity. The model helps identify patterns in claim-related information using distance-based learning, which is widely used for classification problems in finance, insurance, and customer risk assessment.

🎯 Objective

To build and evaluate a KNN Classification Model that predicts outcomes for claimants based on input features. The model aims to achieve a balanced performance between precision, recall, and F1-score for both training and testing datasets.

🧩 Dataset Description

The Claimants Dataset contains information related to individuals filing claims, with several categorical and numerical features influencing the prediction outcome.
Typical features may include:

Age, Gender, and Marital Status

Number of Claims Filed

Income or Policy Details

Previous Claim History

The target variable indicates whether a claimant is likely to be in a particular category (e.g., accepted/rejected claim).

⚙️ Technologies Used

Language: Python 🐍

Libraries:

pandas – Data manipulation

numpy – Numerical computation

matplotlib / seaborn – Data visualization

scikit-learn – Model building and evaluation

🧮 Model Development Steps

Data Preprocessing

Handling missing values

Encoding categorical features using OneHotEncoder or LabelEncoder

Feature scaling using StandardScaler

Model Building

Importing and initializing KNeighborsClassifier

Selecting optimal k value using cross-validation

Model Evaluation

Evaluated on precision, recall, and F1-score metrics

Compared performance on training and testing datasets

📊 Model Performance
Dataset	Precision	Recall	F1-Score
Train	0.76	0.68	0.72
Test	0.72	0.68	0.72

✅ The model demonstrates consistent generalization with similar performance on both train and test data, indicating that it is not overfitting.

🔍 Insights

The model effectively identifies patterns in claimants’ data using nearest neighbor relationships.

Balanced precision and recall values indicate a good trade-off between correctly identifying positive cases and minimizing false positives.

Further improvement could be achieved by experimenting with different distance metrics or applying feature selection.

📈 Visualization

Confusion Matrix to understand class-wise predictions.

Elbow Plot to determine the optimal number of neighbors (k).

Feature Distribution Charts to understand data spread and influence.
