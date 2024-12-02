

---

# Spam Mail Prediction Project

This project focuses on classifying emails as **spam** or **ham** using machine learning techniques. The solution employs text preprocessing and feature extraction to build an efficient predictive system.

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
The goal of this project is to identify whether a given email is spam (irrelevant) or ham (legitimate). The system processes raw email text, extracts meaningful features, and classifies the emails using a Logistic Regression model.

## Dataset Description
The dataset consists of labeled email messages.

**Features:**
- `Message`: The email text.

**Target:**
- `Spam` (0): Irrelevant emails.
- `Ham` (1): Legitimate emails.

**Preprocessing Steps:**
- Handling missing values by replacing them with empty strings.
- Label encoding: Spam (0), Ham (1).

## Model Details
The predictive model uses **Logistic Regression**, a simple and effective algorithm for binary classification tasks.

**Steps:**
1. Text preprocessing and vectorization using **TF-IDF Vectorizer**.
2. Splitting the data into training and testing sets.
3. Training the Logistic Regression model on the training data.
4. Evaluating the model using accuracy metrics.

## How to Use
### Google Colab Users:
- Upload the `4_Spam_Mail_Prediction.ipynb` file to Google Colab.
- Libraries such as NumPy, Pandas, and Scikit-learn are pre-installed.

### Other Environments:
1. Install required libraries:
    ```bash
    pip install numpy pandas scikit-learn
    ```
2. Run the Jupyter Notebook:
    ```bash
    jupyter notebook 4_Spam_Mail_Prediction.ipynb
    ```

## Technologies
- **Python**
- **NumPy, Pandas**
- **Scikit-learn**

## License
This project is licensed under the [MIT License](../LICENSE) - see the LICENSE file for details.

## Results
The model achieved:
- **Training Accuracy**: 96.70% 
- **Testing Accuracy**: 96.65%

Further optimization can be performed to improve results.

## Contributors
- **Pushpanathan**: Development and implementation.

---

This project is part of a series focused on natural language processing applications.
