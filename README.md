# Walmart Black Friday Spending Analysis

## Project Overview
This project analyzes customer spending behavior on Black Friday at Walmart. The goal is to understand if there are significant differences in spending between different groups, such as male vs. female, married vs. unmarried, and different age groups. 

Using transactional data from Walmart's Black Friday sales, we applied statistical analysis techniques, such as **Confidence Intervals** and **Central Limit Theorem (CLT)**, to estimate population-level spending averages. The findings will help Walmart make better business decisions by leveraging customer insights.

## Key Business Questions
- Do women spend more on Black Friday than men?
- How does marital status influence spending habits?
- What are the spending differences across various age groups?

## Techniques Used
- **Exploratory Data Analysis (EDA)**: Analyzing the distribution and relationships of the dataset.
- **Confidence Interval (CI)**: Estimating the population mean spending using sample data.
- **Central Limit Theorem (CLT)**: Understanding the distribution of sample means and their impact on confidence intervals.
- **Statistical Hypothesis Testing**: Analyzing the differences in spending based on gender, marital status, and age groups.

## Dataset
The dataset used in this analysis contains transactional data from Walmart during Black Friday. It includes the following features:
- `User_ID`: Unique identifier for each user
- `Product_ID`: Unique identifier for each product
- `Gender`: Gender of the customer
- `Age`: Customer's age (binned into categories)
- `Occupation`: Occupation of the customer (masked)
- `City_Category`: City category where the customer resides (A, B, C)
- `StayInCurrentCityYears`: Number of years the customer has stayed in the current city
- `Marital_Status`: Marital status of the customer
- `ProductCategory`: Product category (masked)
- `Purchase`: Purchase amount on Black Friday

## Analysis Flow
1. **Data Preprocessing**: Cleaned and structured the dataset for analysis by converting categorical columns and handling missing values.
2. **Exploratory Data Analysis (EDA)**: Visualized distributions and relationships between key features (e.g., gender, marital status, age).
3. **Confidence Interval Calculation**: Calculated confidence intervals for male and female spending and performed similar calculations for marital status and age groups.
4. **Business Insights**: Based on the analysis, provided actionable recommendations to Walmart on improving Black Friday sales and targeting specific customer groups.

## Insights & Recommendations
- Women tend to spend more per transaction on Black Friday than men, based on confidence interval analysis.
- Married customers tend to spend more than unmarried ones, and specific age groups exhibit distinct spending behaviors.
- Walmart can leverage these insights to tailor marketing campaigns, promotions, and product offers based on gender, marital status, and age.
