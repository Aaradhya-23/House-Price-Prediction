# House Price Prediction | Machine Learning Project


## Overview

This project focuses on predicting house prices using various regression models. The goal was to build a model that can accurately estimate the market value of a house based on its features. This was a self-directed project developed from May to June 2024 to apply and showcase skills in data science and machine learning.

---

## Key Features & Results

*   **Models Developed:** Implemented and compared Linear Regression, Decision Tree, and Random Forest models.
*   **Data Processing:** Executed comprehensive data cleaning, feature engineering, and Exploratory Data Analysis (EDA) using `pandas` and `seaborn` to uncover key market drivers.
*   **Top Performance:** The final optimized **Random Forest model achieved a predictive R² score of 0.87** on the test set.
*   **Model Optimization:** Leveraged cross-validation and hyperparameter tuning (e.g., GridSearch CV) to enhance model accuracy and prevent overfitting.

---

## Tech Stack

*   **Language:** Python
*   **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

---

## Project Walkthrough

The project is detailed in the `house_price_prediction.ipynb` Jupyter Notebook, which covers:
1.  **Data Loading & Initial Exploration:** Understanding the dataset's structure and features.
2.  **Data Cleaning:** Handling missing values and correcting data types.
3.  **Exploratory Data Analysis (EDA):** Visualizing relationships between features and the target variable (price).
4.  **Feature Engineering:** Creating new features to improve model performance.
5.  **Model Building & Training:** Training Linear Regression, Decision Tree, and Random Forest models.
6.  **Model Evaluation & Tuning:** Comparing models using the R² score and optimizing the best performer.
7.  **Conclusion:** Summarizing the final results and findings.

---

## How to Run

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/House-Price-Prediction.git
    ```
2.  Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
3.  Open and run the Jupyter Notebook:
    ```bash
    jupyter notebook house_price_prediction.ipynb
    ```
---

## Key Result Visualization

Here is a chart showing the most important features identified by the Random Forest model that influence house prices.

![Feature Importance Chart](images/feature_importance.png) <!-- Link to your best chart -->
