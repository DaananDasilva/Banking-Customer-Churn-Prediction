# Banking Customer Churn Prediction

## Overview
This project aims to analyze customer churn behavior at a financial institution using a dataset containing customer demographics, account details, and churn status. The objective is to identify key factors influencing churn and provide actionable insights to help the bank improve its customer retention strategies.

## Problem Statement
Customer churn is a critical issue for financial institutions, impacting profitability and long-term growth. This project explores and analyzes the behavioral and demographic characteristics of customers who churn compared to those who remain loyal, providing insights into the drivers of churn and offering recommendations for retention.

## Project Objectives
1. **Analyze and visualize customer demographics and behavior** to identify trends and patterns related to churn.
2. **Segment customers based on key features** such as tenure, balance, and number of products to understand which segments have higher churn rates.
3. **Generate insights and recommendations** to help the bank reduce churn and improve customer retention.

## Project Approach
The project follows a structured exploratory data analysis (EDA) approach:

1. **Step 1: Define the Two Groups - Churned vs. Loyal Customers**
2. **Step 2: Summary Statistics and Distribution Analysis**
3. **Step 3: Visualizing Behavioral Differences**
4. **Step 4: Correlation Analysis**
5. **Step 5: Chi-Square Tests for Categorical Variables**
6. **Step 6: Generate Insights and Recommendations**

Each step involves analyzing and visualizing different features of the dataset to understand their relationship with churn and their impact on customer behavior.

## Key Insights
- **Older customers** have a higher likelihood of churning compared to younger customers.
- **Customers with only one product** are significantly more likely to churn compared to those holding multiple products.
- **Churn rates vary by region**, with Germany having the highest churn rate, suggesting potential service issues or increased competition.
- **Inactive members** have a much higher churn rate compared to active members, indicating the importance of customer engagement.

## Recommendations
- **Enhance product engagement** by offering personalized product recommendations and incentives for holding multiple products.
- **Focus on high-balance customers** by providing exclusive services or benefits to retain these valuable customers.
- **Address churn in Germany** by improving service quality or offering region-specific products.
- **Increase activity among inactive members** through personalized outreach or targeted promotions.

## Tools & Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, Seaborn, Matplotlib, Scipy
- **Data Analysis**: Exploratory Data Analysis (EDA), Correlation Analysis, Chi-square tests
- **Visualization**: Bar charts, Box plots, Histograms, Heatmaps

## Repository Structure
- **`Churn_Modelling.csv`**: The dataset used for analysis, containing customer information and churn status.
- **`LICENSE`**: Licensing information for the repository.
- **`README.md`**: Project overview and documentation.
- **`banking_customer_churn_prediction.ipynb`**: Jupyter notebook containing the analysis and visualizations.

## How to Run the Project
1. Clone the repository:
    ```bash
    git clone https://github.com/DaananDasilva/Banking-Customer-Churn-Prediction.git
    ```
2. Install the required libraries:
    ```bash
    pip install pandas matplotlib seaborn scipy
    ```
3. Open the Jupyter notebook and run the cells to see the analysis:
    ```bash
    jupyter notebook banking_customer_churn_prediction.ipynb
    ```

## Future Work
- Develop a machine learning model to predict customer churn based on the identified key features.
- Perform a deeper analysis of customer feedback data to gain further insights into the reasons for churn.

## Contact
If you have any questions or would like to connect, feel free to reach out via:

- **Email**: daanandasilva@gmail.com
- **LinkedIn**: [LinkedIn Daanan Dasilva](https://www.linkedin.com/in/daanan-dasilva-784b10211/)
