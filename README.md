# Banking Customer Churn Prediction

## Overview
This project analyzes customer churn behavior at a financial institution using a dataset containing customer demographics, account details, and churn status. The objective is to identify key factors influencing churn, uncover patterns in customer behavior, and provide actionable insights to help the bank improve its customer retention strategies.

## Problem Statement
Customer churn is a critical issue for financial institutions, directly impacting profitability and long-term growth. This project explores the behavioral and demographic characteristics of customers who churn (leave the bank) compared to those who remain loyal, providing insights into the drivers of churn and offering targeted recommendations for retention.

## Project Objectives
1. **Analyze customer demographics and behavior** to identify trends and patterns associated with churn.
2. **Segment customers based on key attributes** such as age, account balance, and product holdings to understand which segments are more likely to churn.
3. **Identify significant factors influencing churn** through correlation analysis and statistical testing.
4. **Generate actionable recommendations** to help the bank reduce churn and improve customer retention.

## Project Approach
This project follows a structured exploratory data analysis (EDA) approach, organized into six main steps:

1. **Define the Two Groups - Churned vs. Loyal Customers**:
   - Establish the basis for comparison between churned and loyal customers.
2. **Summary Statistics and Distribution Analysis**:
   - Calculate and visualize summary statistics for numerical variables to understand central tendencies and variations.
3. **Visualizing Behavioral Differences**:
   - Use visualizations such as histograms, box plots, and count plots to display distribution and behavioral differences.
4. **Correlation Analysis**:
   - Explore the relationships between numerical attributes and customer churn to identify key factors associated with churn.
5. **Chi-Square Tests for Categorical Variables**:
   - Perform Chi-square tests to determine if categorical variables (e.g., `Gender`, `Geography`) are significantly associated with churn.
6. **Generate Insights and Recommendations**:
   - Summarize key findings and provide actionable recommendations for reducing churn and improving customer retention.

## Key Insights
- **Older Customers**: Older customers are more likely to churn compared to younger customers, indicating that the bank’s offerings may not align with their needs or expectations.
- **High-Balance Customers**: Churned customers have higher average account balances, suggesting that even high-value customers may leave if their expectations are not met.
- **Product Engagement**: Customers holding only one product are significantly more likely to churn, highlighting the importance of cross-selling and product engagement strategies.
- **Geographic Differences**: Churn rates vary significantly by geography, with Germany showing the highest churn rate, potentially due to service dissatisfaction or competitive offerings in that region.
- **Inactive Members**: Inactive members are much more likely to churn compared to active members, underscoring the importance of keeping customers engaged with the bank’s products and services.

## Recommendations
- **Enhance Product Engagement**: Offer personalized product recommendations and incentives for using multiple products to increase engagement and reduce churn.
- **Focus on High-Balance Customers**: Provide exclusive benefits and personalized services to retain high-balance customers, as they have a higher likelihood of churning.
- **Targeted Retention Programs for Older Customers**: Develop tailored offerings and communication strategies to better meet the needs of older customers.
- **Address Churn in Germany**: Investigate reasons for high churn rates in Germany and implement localized strategies to improve satisfaction and reduce churn.
- **Increase Activity Among Inactive Members**: Implement initiatives such as personalized outreach and special promotions to encourage higher activity levels and reduce churn.

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
1. **Clone the repository**:
    ```bash
    git clone https://github.com/DaananDasilva/Banking-Customer-Churn-Prediction.git
    ```
2. **Install the required libraries**:
    ```bash
    pip install pandas matplotlib seaborn scipy
    ```
3. **Open the Jupyter notebook and run the cells**:
    ```bash
    jupyter notebook banking_customer_churn_prediction.ipynb
    ```

## Future Work
- **Develop a Predictive Model**: Build a machine learning model to predict customer churn based on the identified key features. This can help proactively identify customers at risk of churning.
- **Incorporate Qualitative Research**: Use qualitative research methods such as in-depth interviews or customer surveys to gain deeper insights into customer dissatisfaction and reasons for churn.
- **Analyze Customer Feedback Data**: Integrate customer feedback data, such as survey responses or complaints, to better understand customer sentiment and areas of improvement.

## Contact
If you have any questions or would like to connect, feel free to reach out via:

- **Email**: daanandasilva@gmail.com
- **LinkedIn**: [LinkedIn Daanan Dasilva](https://www.linkedin.com/in/daanan-dasilva-784b10211/)
