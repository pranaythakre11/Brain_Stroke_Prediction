<h1>Brain Stroke Prediction</h1>

This project leverages Machine Learning techniques to predict the likelihood of a brain stroke based on user-provided health parameters. It aims to assist healthcare professionals and individuals in early diagnosis and preventive measures.

## Features
- **User Input:** Collects data like age, gender, BMI, blood pressure, and more.
- **Machine Learning Model:** Utilizes algorithms such as Logistic Regression, Random Forest, Decision Tree, KNN or XGBoost for prediction.
- **Accurate Predictions:** Trained and tested on a healthcare dataset with high accuracy.
- **User-Friendly Interface:** Simple and intuitive UI for ease of use.

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript.
- **Backend:** Python with Flask.
- **Machine Learning:** Scikit-learn, Pandas, NumPy, Seaborn, matplotlib for data processing and model building.

## Dataset
The model was trained on a publicly available healthcare dataset containing features like:
- Age
- Gender
- Hypertension
- Heart disease
- Smoking status
- BMI
- Glucose levels
- Work Type
- Residence Type
- Ever Married

## Model Accuracy Comparison
The Brain Stroke Prediction model was evaluated using multiple machine learning algorithms. Below is the accuracy achieved by each algorithm on the test dataset:

- **Decision Tree (DT):** 98.35%  
- **K-Nearest Neighbors (KNN):** 97.22%  
- **XGBoost:** 97.84%  
- **Random Forest (RF):** 99.38%  
- **Logistic Regression:** 77.48%  

### Key Insights
- Random Forest achieved the highest accuracy, making it the most reliable algorithm for this task.  
- Logistic Regression showed relatively lower accuracy, likely due to its linear nature and the complexity of the dataset.  
- XGBoost and Decision Tree performed competitively, providing robust alternatives.  
