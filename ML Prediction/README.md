
# SpaceX First Stage Landing Prediction

This machine learning project predicting whether the first stage of a Falcon 9 rocket will land successfully after launch.

This project walks through the full supervised learning workflow:
- data preprocessing
- feature scaling
- train-test split
- model training
- hyperparameter tuning
- model evaluation
- performance comparison across multiple classification algorithms

---


## Models Implemented

The following classification algorithms were trained and evaluated:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors (KNN)

Hyperparameters were optimized using GridSearchCV with cross-validation.

---

## Workflow

### 1. Data Preprocessing
- Imported launch datasets
- Converted outcome labels into numerical format
- Standardized feature variables using `StandardScaler`
- Split data into training and testing sets

### 2. Model Training
Each model was trained using:
- scikit-learn pipelines
- hyperparameter tuning
- 10-fold cross validation

### 3. Model Evaluation
Models were evaluated using:
- accuracy score
- confusion matrices
- comparative performance visualization

---


