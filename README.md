# Digits-Classification-with-ML-Models
Digits classification using Logistic Regression, Decision Tree, KNN, and ANN with train/validation/test split, hyperparameter tuning, and test evaluation.

---

This project performs classification on the **Digits dataset** from `sklearn.datasets`, using four machine learning models:

- **Logistic Regression**
- **Decision Tree**
- **K-Nearest Neighbors (KNN)**
- **Artificial Neural Network (ANN / MLPClassifier)**

## 1. Dataset

We use the built-in **Digits** dataset containing handwritten digit images  

## 2. Data Splitting

The dataset is randomly split into:

- **60%** training set  
- **20%** validation set  
- **20%** test set  

A fixed random seed is used to ensure reproducibility.

## 3. Model Training

Each model is trained on the **training set**:

- Logistic Regression  
- Decision Tree  
- KNN (various values of \(k\))  
- ANN (MLP with different hidden-layer sizes)

## 4. Hyperparameter Tuning

We use the **validation set** to select the best hyperparameter configuration for each model.

## 5. Final Evaluation

Using the **test set**, we compute:

- Overall accuracy  

- Recall per class  

A results table (11 columns) is generated, including:

- Test accuracy  
- Recall for each digit class (0–9)  
- Best hyperparameters
