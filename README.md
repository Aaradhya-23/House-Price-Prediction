# House Price Prediction using Machine Learning

A data-driven project to predict house prices in Boston using regression models. This project demonstrates a complete machine learning workflow, from data cleaning and exploratory data analysis to model training and performance optimization. The final model achieves a **Coefficient of Determination (R²) of 0.87**.

![Feature Importance Plot](images/feature_importance.png)
*(This is a placeholder. After you run your notebook, save your feature importance plot to the `images` folder and it will show up here.)*

---

### Tech Stack

*   **Python**
*   **pandas** for data manipulation and analysis
*   **scikit-learn** for machine learning models and metrics
*   **seaborn** & **Matplotlib** for data visualization
*   **Jupyter Notebook** as the development environment

---

### Project Workflow

1.  **Data Loading and Cleaning:** The Boston Housing dataset was loaded using pandas. Initial data cleaning was performed to handle any inconsistencies.
2.  **Exploratory Data Analysis (EDA):** A thorough EDA was conducted using seaborn and Matplotlib to understand feature distributions, correlations, and outliers. Key relationships between features (like number of rooms, crime rate) and house prices were identified.
3.  **Feature Engineering & Selection:** Features were selected based on their correlation with the target variable and their importance as determined by initial model training.
4.  **Model Training & Comparison:** Three different regression models were implemented and compared:
    *   Linear Regression (as a baseline)
    *   Decision Tree Regressor
    *   Random Forest Regressor
5.  **Hyperparameter Tuning & Evaluation:** The Random Forest model, being the most promising, was optimized using K-Fold Cross-Validation and GridSearch to find the best hyperparameters. The model's performance was evaluated using the **R² score**.

---

### Results

The final, optimized Random Forest model achieved a robust **R² score of 0.87** on the test set, indicating that it can explain 87% of the variance in house prices, making it a reliable predictive tool.

---

### How to Run this Project

To run this project on your local machine, follow these steps:

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/[your-username]/house-price-prediction.git
    cd house-price-prediction
    ```

2.  **Create a virtual environment:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3.  **Install the required libraries:**
    ```sh
    pip install -r requirements.txt
    ```

4.  **Launch the Jupyter Notebook:**
    ```sh
    jupyter notebook House_Price_Prediction.ipynb
    ```

---

### File Structure
