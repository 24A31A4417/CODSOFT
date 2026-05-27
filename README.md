CODSOFT Internship Tasks 🚀
This repository contains all the data science and software engineering tasks assigned during my internship at CODSOFT.

🛳️ Task 1: Titanic Survival Prediction
📋 Project Overview
Built a predictive model that determines whether a passenger on the Titanic survived or not based on individual characteristics like Age, Gender, Ticket Class, Fare, and Family Size.

🛠️ Technical Implementation
Data Cleaning: Implemented conditional median imputation for missing Age values relative to Pclass, handled missing values for Embarked, and removed high-cardinality/incomplete columns (Cabin, Name, Ticket).
Feature Engineering: Developed a novel feature FamilySize combining siblings, spouses, parents, and children indicators to capture social grouping patterns.
Categorical Encoding: Leveraged One-Hot Encoding (pd.get_dummies) for structural conversion of text fields to numeric identifiers.
Model Pipeline: Trained a Robust Random Forest Classifier with an 80/20 train-test split pattern.
📊 Model Performance Metrics
Validation Accuracy: 81.01%
Precision (Survived Class 1): 82%
Recall (Survived Class 1): 69%
📁 Directory Reference
Task_1_Titanic_Survival/Titanic_Prediction.ipynb: Complete implementation notebook containing code execution, Feature Importance Plots, and Confusion Matrix analytics.


🎬Task 2: Movie Rating Prediction using Machine Learning
🚀 This project was developed as part of my CodSoft Data Science Internship (Task-02), focusing on building a predictive model to estimate movie ratings based on multiple influencing factors.

📌 Project Objective
The primary goal of this project is to analyze movie data and predict ratings using Machine Learning techniques. By leveraging features such as genre, duration, votes, and cast, the model uncovers patterns that influence audience ratings.

📊 Dataset Description
The dataset contains key attributes of movies, including:
🎭 Genre
⏱️ Duration
👍 Votes
🎬 Director
⭐ Actors
📅 Year
🌟 Rating (Target Variable)
⚙️ Workflow
🔹 1. Data Preprocessing
Handled missing/null values
Removed inconsistencies
Encoded categorical variables (Label Encoding / One-Hot Encoding)
🔹 2. Exploratory Data Analysis (EDA)
Visualized data distributions and correlations
Identified trends affecting movie ratings
Used graphs to uncover hidden insights
🔹 3. Feature Engineering
Selected important features
Transformed variables for better model performance
🔹 4. Model Building
Implemented regression algorithms such as:
Linear Regression
(Optional) Random Forest Regressor
🔹 5. Model Evaluation
Evaluated performance using:
Mean Squared Error (MSE)
R² Score

🛠️ Technologies & Tools
Programming Language: Python 🐍
Libraries:
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Environment: Jupyter Notebook

📈 Results & Insights
The model successfully predicts movie ratings with reasonable accuracy
Features like votes and genre showed strong influence on ratings
Data preprocessing and feature selection significantly improved performance
🎯 Key Learnings
✔ Importance of data cleaning and preprocessing
✔ Understanding real-world datasets through EDA
✔ Application of regression models in prediction tasks
✔ Model evaluation and performance tuning

🚀 Future Enhancements
Implement advanced models like XGBoost / Gradient Boosting
Perform hyperparameter tuning for better accuracy
Deploy the project using Streamlit or Flask
Integrate real-time movie datasets
