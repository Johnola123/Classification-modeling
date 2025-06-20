# Car Sales Classification-modeling

# Objective:
To classify car buyers based on historical car sales data using Random Forest and evaluate model performance.

# Workflow Summary:
## 1. Data Loading and Encoding
Read car sales dataset using pandas.

Applied LabelEncoder and one-hot encoding for categorical variables.

## 2. Data Splitting
Used train_test_split to create training and test sets (default 80/20 split).

## 3. Model Implementation
Chose RandomForestClassifier for its robustness and interpretability.

Fit the model using default parameters.

## 4. Evaluation
Computed:

Accuracy score

Classification report

Confusion matrix

Feature importance was optionally visualized.

# Results:
Test Accuracy: ~96.6%

Model showed high precision and recall across most classes.

Excellent generalization with minimal overfitting.

