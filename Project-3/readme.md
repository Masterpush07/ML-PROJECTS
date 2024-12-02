# Diabetes Prediction Project

This project focuses on predicting the likelihood of diabetes in patients using the **PIMA Diabetes Dataset**. The solution leverages machine learning techniques to analyze and classify data.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Model Details](#model-details)
4. [How to Use](#how-to-use)
5. [Technologies](#technologies)
6. [License](#license)
7. [Results](#results)
8. [Contributors](#contributors)

## Project Overview
The objective of this project is to build a predictive model that determines whether a person has diabetes based on input features such as glucose levels, blood pressure, BMI, etc. The project includes data preprocessing, exploratory data analysis, and training/testing the model.

## Dataset Description
The dataset used is the **PIMA Diabetes Dataset**, which contains patient data collected by the National Institute of Diabetes and Digestive and Kidney Diseases.

**Features:**
- Number of Pregnancies
- Glucose Levels
- Blood Pressure
- Skin Thickness
- Insulin
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age

**Target:**
- 0: Non-Diabetic
- 1: Diabetic

## Model Details
The predictive model employs **Support Vector Machines (SVM)**, a robust machine learning algorithm for classification tasks.

**Steps:**
1. Data preprocessing (e.g., scaling with `StandardScaler`)
2. Splitting the data into training and testing sets.
3. Training an SVM classifier on the training set.
4. Evaluating the model using accuracy metrics.

## How to Use
### Google Colab Users:
- Directly upload the `3_Diabetes_Prediction.ipynb` file to Google Colab.
- Most libraries like NumPy, Pandas, and Scikit-learn are pre-installed, so no additional installation is required.

### Other Environments:
1. Install the required libraries:
    ```bash
    pip install numpy pandas scikit-learn
    ```
2. Run the Jupyter Notebook:
    ```bash
    jupyter notebook 3_Diabetes_Prediction.ipynb
    ```

## Technologies
- **Python**
- **NumPy, Pandas**
- **Scikit-learn**

## License
This project is licensed under the [MIT License](../LICENSE) - see the LICENSE file for details.## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Results
The model achieved a satisfactory accuracy of **77%** on the testing dataset. Further optimization can be conducted to enhance performance.

## Contributors
- **Pushpanathan**: Development and implementation.


---
This project is part of a series focusing on machine learning applications in healthcare.

