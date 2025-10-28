# Cardio-Risk-Predictor 

A Machine Learning project focused on predicting the presence of heart disease in patients based on various clinical and demographic features.

## Project Goal

The primary goal of this project is to build and evaluate a Machine Learning model (specifically, an Artificial Neural Network, as suggested by the notebook code) that can accurately predict whether a patient has heart disease (diagnosis) using the provided dataset.

## Technologies and Libraries

This project is implemented in a Jupyter Notebook using Python and popular data science libraries:

* **Python**
* **Jupyter Notebook**
* **Pandas** for data manipulation.
* **NumPy** for numerical operations.
* **Matplotlib** and **Seaborn** for data visualization (Exploratory Data Analysis - EDA).
* **Scikit-learn** for data preprocessing (scaling, splitting) and model evaluation.

## Dataset

The project uses the well-known **Heart Disease Dataset** from the UCI Machine Learning Repository.

The key features used for prediction include:
* `age`: Age of the patient.
* `sex`: (1 = male; 0 = female).
* `cp`: Chest pain type.
* `trestbps`: Resting blood pressure.
* `chol`: Serum cholestoral in mg/dl.
* ... and other relevant medical indicators.

## 📈 Results

The final trained model is used to make predictions on new, unseen data (`new_data`) after performing necessary preprocessing (reindexing and scaling). The output of the model is stored in `y_predictions (2)`. 

