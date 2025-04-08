# Dry-Bean-Classification

# Dry Bean Classification Model
## Overview
    This project builds a Dry Bean Classification Model to predict the category of dry beans based on their morphological features. The goal is to help in automating the classification process of dry beans using machine learning, which is useful in agriculture and food quality control.

The following classification algorithms are used in this model:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

XGBoost Classifier

K-Nearest Neighbors (KNN) Classifier

Support Vector Machine (SVM) Classifier

📂 Dataset
The dataset consists of various numerical features that describe physical characteristics of dry beans, such as:

Area, Perimeter, MajorAxisLength, MinorAxisLength, AspectRatio

Eccentricity, ConvexArea, Extent, Solidity, Roundness

Compactness, ShapeFactor1 to ShapeFactor4

The target column represents the type of bean (e.g., SEKER, BARBUNYA, BOMBAY, etc.).

🚀 Project Workflow
1. Data Preprocessing
Checked for missing values and ensured data quality

Normalized numerical data for model compatibility

Converted target labels into numerical format using encoding

2. Exploratory Data Analysis (EDA)
Visualized class distributions

Analyzed key feature correlations

Gained insights into the relationship between features and bean types

3. Feature Engineering
No additional features were created; all existing features were numeric and ready for modeling

4. Model Implementation
Trained multiple classification models

Used accuracy as the primary evaluation metric

Compared models using performance metrics

5. Model Evaluation
Accuracy Score used to determine how well each model predicted bean types

Confusion Matrix used to evaluate misclassifications

🔍 Results & Key Insights
Logistic Regression performed well and served as a baseline

XGBoost Classifier provided the highest accuracy among all tested models

KNN and SVM models were highly sensitive to scaling but still effective

Random Forest and Decision Tree models handled the data complexity well

🛠 Technologies Used
Python

Pandas – Data manipulation and preprocessing

NumPy – Numerical operations

Matplotlib & Seaborn – Visualization

Scikit-learn – Machine Learning algorithms

XGBoost – Advanced gradient boosting algorithm

🤝 Contribution
Feel free to contribute by:

Tuning hyperparameters

Implementing cross-validation

Trying additional classifiers

Improving visualizations or feature engineering

📄 License
This project is open-source under the MIT License.
