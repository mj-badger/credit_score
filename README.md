# **Credit Analysis and Hypothetical Credit Score Calculation**

This repository contains a comprehensive solution to analyze customer credit data and calculate a **hypothetical credit score**. The project focuses on performing **Exploratory Data Analysis (EDA)**, engineering new features, and developing a methodology to rate customers' creditworthiness based on domain knowledge and data-driven insights.

---

## **Problem Statement**
The project addresses the following key objectives:
1. Conduct a thorough **Exploratory Data Analysis (EDA)** to understand the dataset's structure, characteristics, and relationships.
2. Create **new, informative features** that enhance data usability for credit score calculations.
3. Develop a methodology to calculate a **hypothetical credit score** inspired by FICO scores.
4. Analyze the results to provide actionable insights and recommendations.

---

## **Approach**
### **1. Exploratory Data Analysis (EDA)**
- Examined the dataset's structure, distributions, and relationships.
- Identified and handled missing values, mismatched data types, inconsistencies, and outliers.
- Used visualizations such as:
  - **Histograms** to examine distributions.
  - **Scatter plots** and **box plots** to identify trends and outliers.
  - **Correlation matrices** to uncover relationships between variables.

---

### **2. Feature Engineering**
- Created new features to represent customer credit behavior, such as:
  - Aggregated transaction data at the customer level.
  - Recency-based metrics for the last 3 months and 6 months.
- Leveraged insights from EDA to inform feature creation.

---

### **3. Hypothetical Credit Score Calculation**
- Developed a methodology for calculating a **hypothetical credit score**:
  - Selected **5-10 relevant features** for scoring based on domain knowledge.
  - Assigned **weights** to features inspired by FICO scoring systems.
  - Provided scores for individual customers with clear explanations in the methodology.
- Explored variations in scores over different time frames (e.g., last 3 or 6 months).

---

### **4. Analysis and Insights**
- Highlighted meaningful patterns and anomalies from EDA.
- Provided aggregated features and credit scores for customers.
- Explored how credit scores and behavior metrics evolve over time, offering recency-based insights.

---

## **Files in This Repository**
- **Python Script**: The complete analysis, feature engineering, and credit score calculations are implemented in the [Python file](https://github.com/mj-badger/credit_score/blob/main/Credit_analysis_oct_10.ipynb).

---

## **Key Insights and Recommendations**
1. **EDA Findings**:
   - Identified trends and anomalies in customer credit behavior.
   - Highlighted correlations between features influencing credit scores.

2. **Credit Score Applications**:
   - Scores can be used by financial institutions to assess customer creditworthiness.
   - Risky customers are flagged based on low credit scores and negative behaviors.

3. **Recency Metrics**:
   - Scores and insights can be tailored for specific time frames (e.g., last 3 or 6 months) for better decision-making.

4. **Future Enhancements**:
   - Incorporate additional external datasets (e.g., income, employment history) for more accurate scoring.
   - Develop predictive models to assess future credit risk.
