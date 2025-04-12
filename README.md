# BIG-DATA-ANALYSIS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: ANUBHAV SINGH

*INTERN ID*: CT06DA708

*DOMAIN*: DATA ANALYTICS

*DURATION*: 6 WEEEKS

*MENTOR*: NEELA SANTOSH



## Task 1: Housing Data Analysis with PySpark

### Overview

This project focuses on performing exploratory data analysis on a housing dataset using PySpark to demonstrate big data processing and scalability. The goal is to understand housing market trends and identify factors influencing house values through various PySpark functionalities.

### Tasks Performed

*   Installed PySpark library.
*   Created a Spark Session to work with distributed data processing.
*   Loaded the `housing.csv` dataset into a Spark DataFrame.
*   Explored the dataset schema, displayed sample data, and generated descriptive statistics.
*   Checked for missing values in the dataset.
*   Performed basic GroupBy analysis to explore the relationship between `ocean_proximity` and `median_house_value`, and `median_income`.
*   Filtered the dataset to identify high-value, low-income homes.
*   Built a Linear Regression model using PySpark MLlib to predict `median_house_value` based on selected features.
*   Evaluated the regression model using RMSE and R² metrics.
*   Created a scatter plot visualization to show the correlation between `median_income` and `median_house_value`.
*   Summarized key insights from the data exploration and model evaluation.

### Code and Resources Used

*   **Programming Language:** Python
*   **Libraries:** PySpark, matplotlib, pandas
*   **Dataset:** `housing.csv` (California Housing dataset)
*   **Notebooks:**
    *   [Link to Task 1 Notebook (task1.ipynb)](task1.ipynb)

### Results and Insights

*   **"NEAR BAY" areas exhibit higher average house values compared to other proximities.** This suggests location significantly impacts property prices.
*   **Median income shows a positive correlation with median house value.** As income increases, house values tend to increase as well.
*   **High-value homes can exist even in low-income regions**, potentially due to desirable locations or other factors not captured in income data alone.
*   **The Linear Regression model achieved an RMSE of approximately 76768 and an R² of 0.547.** This indicates the model has a moderate predictive capability for house values based on the selected features.

### How to Run (Optional)

The code is designed to be run in Google Colab. Simply open the `task1.ipynb` notebook in Colab and run the cells sequentially.



