# Cardiovascular Disease Prediction
This project uses machine learning techniques to predict cardiovascular disease. To achieve accurate health risk prediction, including data preprocessing, exploratory data analysis, feature scaling, handling class imbalance with SMOTE, and training multiple models, including SVM, KNN, Decision Tree, Random Forest, and Logistic Regression.

### Dataset Description:

The dataset contains medical attributes such as age, gender, height, weight, blood pressure, cholesterol, glucose level, smoking habits, physical activity, and a target variable indicating the presence of heart disease.

### Technologies Used:
Python

Pandas

NumPy

Matplotlib 

Seaborn

Scikit-learn

Imbalanced-learn (SMOTE)

### Data Preprocessing:
Removed unrealistic and missing values

Converted age from days to years

Handled outliers using visualization

Balanced data using SMOTE

Scaled features for better performance

### Exploratory Data Analysis:
Distribution plots for major features

Boxplots to detect outliers

Correlation heatmap to analyze relationships

### Machine Learning Models:
Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree

Random Forest

Support Vector Machine (SVM)

### Model Evaluation:
Accuracy score

Confusion matrix

Classification report

### Hyperparameter Tuning:

GridSearchCV is applied to Random Forest to optimize model performance.

### Results:

Random Forest and SVM achieved the highest accuracy, making them suitable for cardiovascular disease prediction.

### License:

This project is open-source and available under the MIT License.
