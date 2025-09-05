# **Mushroom Classification using Logistic Regression with and without PCA**

## **Project Overview**

This project explores the classification of mushrooms as edible or poisonous using the Mushroom dataset (mushroom.csv).
The workflow involves applying Logistic Regression on the original dataset and then repeating the classification after applying Principal Component Analysis (PCA).
The results from both approaches are compared to study the effect of dimensionality reduction on model performance.

## **Files**

asgn2.ipynb → Jupyter Notebook containing code for preprocessing, model training, PCA, and performance evaluation.

mushroom.csv → Dataset used for classification.

## **Methods Used**

- Data Preprocessing

  - Categorical feature encoding

  - Handling of missing values (if any)

  - Train-test splitting

- Logistic Regression

  - Applied to the full dataset without dimensionality reduction

  - Accuracy, precision, recall, and F1-score used for evaluation

- Principal Component Analysis (PCA)

  - Reduced dataset dimensionality

  - Retained principal components explaining most variance

  - Logistic Regression applied on PCA-transformed features

- Comparison

  - Performance of Logistic Regression with and without PCA compared

  - Trade-offs between accuracy and dimensionality discussed

## **Results**

Logistic Regression on original data: Higher accuracy due to full feature space.

Logistic Regression on PCA-transformed data: Slight reduction in accuracy but significant feature reduction, improving efficiency.

## **How to Run**

- Open the notebook:

`jupyter notebook asgn2.ipynb`

- Ensure mushroom.csv is in the same directory.

- Run all cells to reproduce results.

## **Dependencies**

- Python 3.x

- Jupyter Notebook

- NumPy

- Pandas

- Scikit-learn

- Matplotlib / Seaborn (for visualization)

## **Conclusion**

This project demonstrates how Logistic Regression performs with full features compared to PCA-transformed features, highlighting the balance between model interpretability, computational efficiency, and accuracy in classification tasks.
