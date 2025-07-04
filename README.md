# House Price Prediction



## Overview

This project is an end-to-end machine learning solution for predicting house prices in California. The primary objective was to develop and evaluate various regression models to find the one that most accurately predicts house values based on housing census data. This project demonstrates a complete data science workflow, from data cleaning and exploratory data analysis (EDA) to model training, hyperparameter tuning, and final evaluation.

---

## Key Achievements

*   **Developed and Compared Models:** Implemented **Linear Regression**, **Decision Tree**, and **Random Forest** regressors in Python to predict house prices with high accuracy.
*   **Data Analysis & Feature Engineering:** Executed comprehensive data cleaning, feature exploration, and EDA using `pandas` and `seaborn` to identify key market drivers like median income and average house occupancy.
*   **Optimized Performance:** Achieved a predictive **R² score of 0.87** on the test set with the final tuned Random Forest model.
*   **Advanced Techniques:** Utilized **cross-validation** and **GridSearchCV** for robust hyperparameter tuning, preventing overfitting and maximizing model performance.

---

## Tech Stack

*   **Language:** `Python`
*   **Libraries:** `Scikit-learn`, `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`

---

## Project Workflow

The analysis is documented in the `house_price_prediction.ipynb` Jupyter Notebook and follows these steps:

1.  **Data Loading:** Loaded the California Housing dataset from Scikit-learn.
2.  **Exploratory Data Analysis (EDA):** Investigated the data to understand feature distributions and correlations, using visualizations like heatmaps and histograms.
3.  **Data Preprocessing:** Prepared the data for modeling by splitting it into training and testing sets.
4.  **Model Building:** Trained three different regression models to establish a performance baseline.
5.  **Model Evaluation:** Compared the models using metrics like R-squared (R²) and Mean Absolute Error (MAE).
6.  **Hyperparameter Tuning:** Optimized the best-performing model (Random Forest) using GridSearchCV to find the best parameters.
7.  **Final Evaluation:** Assessed the tuned model on the test set and analyzed the feature importances to understand what drives the predictions.

---

## How to Run This Project

To replicate this project on your own machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Aaradhya-23/House-Price-Prediction.git
    cd House-Price-Prediction
    ```

2.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Launch the Jupyter Notebook:**
    ```bash
    jupyter notebook house_price_prediction.ipynb
    ```

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


---

## Key Results

The Random Forest model, after tuning, emerged as the most effective. 
