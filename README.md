# Diabetes-Prediction-Using-Machine-Learning-Python-Pandas-Scikit-learn
# Diabetes Prediction Using Machine Learning

## 📌 Overview

This project is a Machine Learning-based system that predicts whether a person is likely to have diabetes based on medical and health-related attributes.

The project uses a **Support Vector Machine (SVM)** with a linear kernel for binary classification. The input features are standardized using **StandardScaler** before training the model.

## 📊 Dataset

The dataset contains **768 records** with **8 input features** and one target variable, `Outcome`.

### Features

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

### Target

* `0` → Non-Diabetic
* `1` → Diabetic

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Jupyter Notebook

## ⚙️ Project Workflow

1. Load and explore the diabetes dataset using Pandas.
2. Separate the input features and target variable.
3. Standardize the input features using `StandardScaler`.
4. Split the dataset into **80% training data and 20% testing data** using stratified sampling.
5. Train a **Support Vector Machine (SVM)** classifier with a linear kernel.
6. Evaluate the model using training and testing accuracy.
7. Use the trained model to predict whether a new person is diabetic or non-diabetic.

## 🤖 Machine Learning Model

The project uses:

**Support Vector Machine (SVM) — Linear Kernel**

SVM finds a decision boundary that separates diabetic and non-diabetic cases based on the available features.

## 🚀 Running the Project

Install the required Python libraries:

```bash
pip install numpy pandas scikit-learn jupyter
```

Run the Jupyter Notebook:

```bash
jupyter notebook diabetes.ipynb
```

Make sure `diabetes.csv` is available in the same directory as the notebook.

## 📁 Project Structure

```text
Diabetes-Prediction/
│
├── diabetes.ipynb
├── diabetes.csv
└── README.md
```

## 🎯 Conclusion

This project demonstrates an end-to-end basic Machine Learning classification workflow, including data exploration, feature standardization, train-test splitting, model training, accuracy evaluation, and prediction on new patient data.

> **Note:** This project is intended for educational purposes and should not be used as a substitute for professional medical diagnosis.
