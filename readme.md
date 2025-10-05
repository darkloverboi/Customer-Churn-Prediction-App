# Predictive Analytics for E-Commerce Customer Churn

## Overview

This project builds a predictive analytics model to predict customer churn for an e-commerce business. It uses Python, Streamlit, and various machine learning libraries to analyze customer behavior data and identify customers who are likely to churn.

## Features

*   **Data Loading:** Supports uploading data from a CSV file or using a synthetic dataset.
*   **Exploratory Data Analysis (EDA):** Provides visualizations to understand the data, including churn distribution, feature distributions, and correlation heatmap.
*   **Data Preprocessing:** Handles missing values, encodes categorical variables, and scales numerical features.
*   **Model Training:** Trains a classification model (Logistic Regression or Random Forest) to predict churn.
*   **Model Evaluation:** Evaluates the model using accuracy, precision, recall, and ROC-AUC.
*   **Streamlit UI:** Provides a user-friendly interface for manual data input and prediction.
*   **Batch Prediction:** Predicts churn for the entire uploaded dataset.

## Requirements

*   Python 3.8 or higher
*   Streamlit
*   Pandas
*   NumPy
*   Matplotlib
*   Seaborn
*   Scikit-learn

## Setup

1.  **Create a virtual environment:**

   ```bash
   python -m venv venv
   ```

2.  **Activate the virtual environment:**

   *   On macOS/Linux:

       ```bash
       source venv/bin/activate
       ```

   *   On Windows:

       ```bash
       venv\Scripts\activate
       ```

3.  **Install dependencies:**

   ```bash
   pip install streamlit pandas numpy matplotlib seaborn scikit-learn
   ```

## Usage

1.  Run the Streamlit app:

   (Make sure your virtual environment is activated first: `venv\Scripts\activate`)

   ```bash
   streamlit run main.py
   ```

2.  Open the app in your web browser (usually at `http://localhost:8501`).

3.  Upload a CSV file or use the example data.

4.  Explore the data using the visualizations.

5.  Select a model (Logistic Regression or Random Forest).

6.  Enter new customer data manually to predict churn probability.

7.  Predict churn for the entire dataset.

## Example Dataset

The project includes a synthetic dataset with the following features:

*   `CustomerID`: Unique identifier for each customer.
*   `Recency`: Days since the last purchase.
*   `Frequency`: Number of purchases.
*   `MonetaryValue`: Total amount spent.
*   `SupportCalls`: Number of support calls.
*   `BrowsingTime`: Average browsing time per session.
*   `Churn`: Whether the customer churned (1) or not (0).



## License

[Specify the license for your project]
