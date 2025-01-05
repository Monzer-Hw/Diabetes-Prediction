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
   git clone https://github.com/Monzer-Hw/Diabetes-Prediction
   ```
2. Install `uv` on your machine
   
   For macOS and linux:
   ````bash
   curl -LsSf https://astral.sh/uv/install.sh | sh
   ````
   For windows:
   ````bash
   powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
   ````
3. Run the following commands:
   
   To create a virtual environment with the required libraries:
   ````bash
   uv sync
   ````

   To create a kernel for the jupyter notebook:
   ````bash
   uv run ipython kernel install --user --name=diabetes-prediction
   ````
4. Run the jupyter notebook with this command:
   ````bash
   uv run --with jupyter jupyter lab
   ````
   Or just select the virtual environment and run the notebook if you have VS Code with jupyter extention.