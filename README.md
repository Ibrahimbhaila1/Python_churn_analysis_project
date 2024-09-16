# Churn Analysis for an Online Retail Store

## Overview
This project analyzes customer churn for an online retail store, aiming to predict which customers are likely to stop making purchases. By leveraging customer purchase behavior, engagement metrics, and transaction history, the model identifies potential churners and provides actionable insights.

## Requirements
- pandas
- numpy
- matplotlib
- seaborn


## Steps
### 1. Data Preprocessing

- Firstly I imported the csv file of the data.The dataset contains transaction history and customer behavior data.

- Removed Unnecessary Columns: Extraneous columns that did not contribute to the analysis were removed from the dataset to streamline the data.

- Calculated Distribution: The percentage of male and female customers was computed, revealing a near-equal distribution with females at 50.6% and males at 49.4%.

![Screenshot 2024-09-16 162039](https://github.com/user-attachments/assets/09e096b3-cc15-47ed-97d6-2616642baff6)

### 2. Demographic Analysis

#### A) Categorized Age Groups: 
Customers were grouped into age brackets to simplify analysis.

#### B) Calculated Percentages:
 The distribution of customers across age groups was analyzed, showing the largest segment in the 40-60 age range at 39.8% and the smallest in the 18-24 range at 13.8%.

### 3. Spending Behavior Analysis

#### A) Identified Spending Range:
 Analyzed the range of total spending to determine the extent of high-value transactions, with the highest spend reaching $9,025.47.

![image](https://github.com/user-attachments/assets/fa8c83b8-ce4a-49f1-a1e5-5b1b71d1f7a5)

#### B) Analyzed Spending Variability:
 Observed a right-skewed distribution, indicating most customers spend less, with significant variability in spending habits.

#### C) Correlation Analysis:
 Examined the relationship between annual income and total spend, finding a weak correlation of -0.025.

![image](https://github.com/user-attachments/assets/bb0bfefb-78a1-4b70-a7a5-a79158ce5b4b)

### 4. Customer Engagement Metrics
#### A) Calculated Tenure Distribution: 
Analyzed the distribution of years as a customer, identifying that 6.7% have been customers for 17 years or more, with the most common tenure being 4 years.

![image](https://github.com/user-attachments/assets/68afe45f-53ab-45b9-b6b3-19de0d9ed698)


#### B) Reviewed Contact Frequency:
 Analyzed support contact data, noting that 21.6% of customers made only one support contact, indicating varied levels of support engagement.

#### C) Calculated Opt-In Rate:
 Determined that 51.8% of customers have opted in for marketing emails.

### 5.Promotional Response Analysis
#### A) Categorized Responses:
 Segmented promotional responses into three categories: responded, unsubscribed, and ignored.

#### B) Calculated Percentages:
 Found that 34.9% of customers responded to promotions, another 34.9% unsubscribed, and 30.6% ignored them.

![image](https://github.com/user-attachments/assets/6d1d0a76-54c1-4d60-82a0-7b940f329b46)

### 6. Satisfaction and Churn Analysis

#### A) Analyzed Score Distribution: 
Examined the distribution of satisfaction scores, noting that 22.2% of customers rated 3 out of 5 and 18.9% rated 5 out of 5.

![image](https://github.com/user-attachments/assets/72af811a-74fe-4602-acf3-6f4a6c1240b3)

#### B) Calculated Churn Rate: 
Determined that the churn rate is 51.5%, meaning that a higher proportion of customers have stopped engaging compared to those who continue.

### 7. Visualization and Interpretation

#### A) Created Visualizations:
 Generated charts and graphs to visually represent the data, including age distribution, gender distribution, annual income, total spend vs. annual income, and churn analysis by satisfaction score. 


 ##### Visualizations
 
![Screenshot 2024-09-16 173337](https://github.com/user-attachments/assets/d89bc5f9-5996-4bcb-8540-77756b0facc9)
![Screenshot 2024-09-16 173423](https://github.com/user-attachments/assets/2cb281d0-ddd8-4bfc-b263-6a67d0b073c2)


#### B) Interpreted Results:
 Used visualizations to interpret and highlight key insights, such as the weak correlation between spending and income and the impact of satisfaction scores on churn.

## Conclusion

This analysis provides a comprehensive view of customer profiles, behaviors, and engagement strategies, crucial for refining marketing approaches and improving customer retention.
The analysis reveals that the majority of customers, 39.8%, are aged between 40 and 60, with this group showing the highest email opt-in rates. Females outnumber males among the customers. Customers with up to 5 returns report an average satisfaction score of 3 out of 5, indicating moderate dissatisfaction. Furthermore, churned customers outnumber non-churned ones, pointing to potential retention challenges. The low satisfaction ratings are strongly associated with higher churn rates, underscoring the need for enhancements in product quality and customer experience to mitigate attrition and improve overall customer satisfaction.
