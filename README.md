# Benchmarking-Classification-Models-Across-Diverse-Datasets
A comparative study of seven popular machine learning classifiers across 20 diverse datasets  evaluated through accuracy, precision, F1-score, ROC-AUC, and runtime metrics.
📘 Detailed Description :

This project benchmarks the performance of seven classification algorithms on 20 randomly selected datasets, aiming to evaluate their generalisation capabilities across varied data distributions. It provides a clear, metric-based comparison of model efficiency and reliability in real-world classification scenarios.

🔍 Key Objectives

Assess model performance consistency across multiple datasets

Identify trade-offs between accuracy, computational cost, and stability

Determine which algorithms perform best under specific data conditions

⚙️ Models Evaluated

Generalized Linear Model (GLM)

Linear Discriminant Analysis (LDA)

Quadratic Discriminant Analysis (QDA)

Naïve Bayes

Support Vector Machine (SVM)

Random Forest (RF)

K-Nearest Neighbors (KNN)

🧩 Data Preparation & EDA

Handled missing values via imputation (mean/median replacement)

Performed one-hot encoding for categorical features

Normalized numerical attributes for consistent comparison

Conducted dataset-level EDA to ensure balanced representation of classes

📊 Evaluation Metrics

Each model was assessed using:

Accuracy

Precision & Recall

F1 Score

ROC Curve & AUC Score

Confusion Matrix

Runtime performance

🧠 Key Insights

Benchmarks highlight Random Forest and SVM as top performers on most datasets

GLM and LDA exhibited faster runtimes but lower adaptability for nonlinear relationships

Provides reproducible insights into the bias-variance trade-offs of each model

🛠️ Tech Stack

Languages: Python

Libraries: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn

Visualization: Confusion matrix plots, ROC curves

Tools: Jupyter Notebook / Google Colab

🎯 Outcome

Delivers a transparent, multi-metric comparison framework for evaluating classification models — useful for practitioners selecting the optimal algorithm for a given dataset type or business problem.
