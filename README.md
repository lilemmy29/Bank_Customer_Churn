**Bank Customers Churn Project**

---

**Problem Statement:**
Customer churn is a significant concern for banks, as it impacts revenue and customer satisfaction. Understanding the factors that contribute to customer churn and developing strategies to retain customers are crucial for the long-term success of the bank. In this project, we aim to analyze customer churn in a bank dataset and provide actionable recommendations to improve user retention.

---

**Project Description:**
This project focuses on analyzing customer churn in a bank dataset. The dataset contains information about customers' demographics, financial status, activity, and geographical location. The goal is to explore factors influencing churn and provide recommendations to improve user retention.

---

**1. Data Inspection and Cleaning Process:**

- **Data Loading:** Loaded the dataset using the pandas `read_csv()` function.
  
- **Column Names Standardization:** Standardized column names to lowercase using the `columns.str.lower()` method for consistency and ease of access.
  
- **Dataset Overview:** Checked the length and shape of the dataset using `len()` and `shape` attributes respectively.
  
- **Data Information:** Obtained an overview of data types and non-null counts for each column using the `info()` method.
  
- **Numeric and Categorical Columns Separation:** Separated numeric and categorical columns using the `select_dtypes()` method.
  
- **Statistical Summary:** Generated a statistical summary of numeric columns using the `describe()` method to understand distribution and central tendency.
  
- **Data Type Conversion:** Converted 'age' column from float to integer data type and 'id' column from integer to object data type for consistency.
  
- **Target Variable Transformation:** Replaced numerical values in the 'exited' column with categorical labels ('churned' and 'Not Churned') for interpretability.
  
- **Data Quality Check:** Conducted a value count of 'exited' column to inspect churned and not churned customers distribution.
  
- **Visualization:** Visualized churned and not churned customers using a horizontal bar chart.

---

**2. Exploratory Analysis of Churned Customers:**

- **Demographics:**
  - Analyzed age and gender distribution among churned users.
  - Explored tenure distribution of churned customers.

- **Financial Information:**
  - Investigated balance and credit score distribution among churned customers.

- **Product Usage:**
  - Examined the number of products used by churned customers.

- **Activity Status:**
  - Explored the activity status of churned users.

- **Geographical Analysis:**
  - Analyzed churn rates across different geographical regions.

---

**3. Recommendations to Retain Users:**

- **Localized Marketing Campaigns:** Develop region-specific marketing strategies tailored to high-churn regions.
  
- **Personalized Engagement:** Implement personalized incentives and financial tools based on user characteristics.
  
- **Product Optimization:** Customize offerings based on user preferences and feedback.
  
- **Community Engagement Initiatives:** Foster community participation to understand regional challenges.
  
- **Continuous Monitoring and Adaptation:** Regularly monitor churn metrics and adapt strategies accordingly.
  
- **Localized Customer Support:** Provide personalized assistance to users in high-churn regions.

---

**Conclusion:**
This project provides valuable insights into customer churn behavior and offers actionable recommendations to improve user retention in the banking sector.

---

**Dependencies:**
- pandas
- matplotlib
- seaborn

---

**Author:**
Tolulope Emuleomo

**Date:**
21st April 2024


---

This README provides an overview of the project, including the problem statement, data inspection and cleaning process, exploratory analysis findings, recommendations, and dependencies.
