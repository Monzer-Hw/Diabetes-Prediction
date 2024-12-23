# Diabetes Prediction Model

This repository contains a Jupyter Notebook for building and evaluating a machine learning model to predict diabetes outcomes using a dataset. The model utilizes various techniques including data preprocessing, model training, and evaluation metrics.

## Dataset

The dataset used in this project is the Pima Indians Diabetes Database, which can be found [here](https://www.kaggle.com/uciml/pima-indians-diabetes-database). The dataset contains the following features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (Target variable)

## Modeling

The model is built using the following steps:

1. Data loading and exploration
2. Data preprocessing (handling missing values, scaling)
3. Resampling using SMOTE to address class imbalance
4. Model training using a Random Forest Classifier
5. Hyperparameter tuning using Grid Search

## Evaluation

The model's performance is evaluated using metrics such as:

- ROC AUC Score
- Confusion Matrix
- Classification Report
- Feature Importance

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Monzer-Hw/Diabetes-Prediction.git
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebook.ipynb
   ```

4. Run the cells in the notebook to preprocess the data, train the model, and evaluate its performance.