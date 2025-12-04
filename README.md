Heart Disease Prediction using Supervised Learning

This project predicts the likelihood of heart disease using supervised machine learning techniques. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and performance evaluation.

The goal of this project is to analyze medical attributes and classify whether a person is likely to have heart disease.

Project Objectives

• Clean and preprocess the dataset
• Perform exploratory data analysis
• Build a binary classification model
• Compare different supervised learning algorithms
• Evaluate model performance using accuracy, precision, recall, and F1-score

Dataset Description

The dataset contains several clinical features commonly used for heart disease analysis:

Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol
Fasting Blood Sugar
Resting ECG
Maximum Heart Rate Achieved
Exercise-Induced Angina
ST Depression
ST Slope
Target (0 = No Heart Disease, 1 = Heart Disease)

Data Preprocessing

• Handling missing values
• Encoding categorical variables
• Outlier detection
• Feature scaling and normalization
• Splitting the dataset into training and testing sets

Exploratory Data Analysis (EDA)

• Distribution analysis of major features
• Correlation heatmap to identify key relationships
• Comparative plots for patients with and without heart disease

Machine Learning Models Used

• Logistic Regression
• K-Nearest Neighbors (KNN)
• Random Forest Classifier
• Support Vector Machine (SVM)

Model Evaluation

Models were evaluated using:

• Accuracy
• Precision
• Recall
• F1 Score
• Confusion Matrix

The best-performing model was selected based on balanced performance across metrics.

Project Structure

data/ – dataset files
notebooks/ – model training and EDA notebook
models/ – saved models (optional)
README.md – project documentation

Technologies Used

Python
NumPy
Pandas
Matplotlib
Scikit-learn

Key Learnings

• Handling real-world structured data
• Applying supervised learning techniques
• Improving model performance through preprocessing
• Understanding relationships between medical factors and predictions


Install the required Python libraries
Open the notebook file
Run all cells to view the analysis and predictions
