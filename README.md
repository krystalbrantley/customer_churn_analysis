# **Analyzing Customer Churn in Power BI**

## Description
This project involved analyzing customer churn to understand why customers were leaving and creating a comprehensive report using Power BI. The analysis aimed to identify key factors contributing to customer churn and provide actionable insights to reduce future attrition.

## Objectives
- Identify patterns and trends associated with customer churn.
- Determine key factors influencing customer attrition.
- Develop visualizations to effectively communicate findings.
- Provide recommendations to reduce churn based on the analysis. 

## Data Source
The analysis was conducted using a dataset for a fictitious telecommunications company called Databel. The dataset contains customer information and churn status. The dataset included various attributes such as customer demographics, service usage, and account details.

## Tools and Technologies
- Power BI: For data visualization and report creation.
- Power Query editor: For data preprocessing and transformation.
- Data Source File: `Databel - Data.csv`

## Overarching Insights

![Customer Churn Analysis Overview](https://github.com/krystalbrantley/customer_churn_analysis/blob/main/Customer%20Churn%20Overview.png?raw=true)
- **Churn rate:** The churn rate for Databel is ~27%.
- **Top reasons why customers churn:**
  - Competitors made a better offer
  - Competitors had better devices
  - Attitude of support person
- ~45% of the reasons why customers churn are related to competitors, raising the question: Is Databel competitive enough?
- **Churn rate by state:** The churn rate in California is abnormally high with more than 60% of customers leaving.

## Data Exploration and Analysis

![Customer Churn Analysis Groups and Categories](https://github.com/krystalbrantley/customer_churn_analysis/blob/main/Customer%20Churn%20Groups.png?raw=true)

### Analyze and Visualize Data
#### Analyzing Demographics
- **Churn rate by age:** The churn rate increases with age. Senior citizens (age 65 and over) have a churn rate of 38.46%, significantly above the average.
- **Individual vs. Group Plans:** The churn rate for individual plans is significantly higher at 32.85% compared to people in a group of 2 or more. The average monthly charge for group plans is lower (about $23) compared to individual plans ($33.50).
- **Monthly vs. Yearly Contracts:** Monthly contracts have a higher churn rate compared to yearly contracts.


![Customer Churn Analysis Extra Charges](https://github.com/krystalbrantley/customer_churn_analysis/blob/main/Customer%20Churn%20Charges.png?raw=true)
#### Impact of Unlimited Data Plan
- **Hypothesis:** People who are not on an unlimited data plan are more likely to churn.
- The churn rate is 32.11% for those with unlimited data plans compared to 16.10% for those without unlimited data.
- Customers who consume 10 or more gigabytes and are not on an unlimited data plan pay $31.19 on average, incurring extra costs for additional data usage.

#### International Calls
- 91% of people without an international plan could be potential clients for a new promotion.
- The churn rate for customers who pay for an international plan but don’t call internationally is extremely high.

![Customer Churn Analysis Insights](https://github.com/krystalbrantley/customer_churn_analysis/blob/main/Customer%20Churn%20Insights.png?raw=true)
### Investigate Churn Rate by State
- California has an abnormally high churn rate with more than 60% of customers leaving.

### Investigate Reasons for Churn
- The top 3 reasons customers churn are:
  - Competitors made a better offer
  - Competitors had better devices
  - Attitude of support person
  
### Customer Service Calls
- Even though the use of customer service is higher for churners, California stands out with the highest churn rate and the lowest number of customer service calls.

## Recommended Next Actions
Based on the findings, the following actions are recommended to reduce customer churn:

1. **Enhance Competitiveness:**
   - Review and improve pricing and service offerings to match or exceed competitors.
   - Invest in better devices and technology to attract and retain customers.

2. **Improve Customer Service:**
   - Address issues related to the attitude and effectiveness of support personnel.
   - Increase customer service outreach, especially in high-churn states like California.

3. **Promote Group Plans:**
   - Encourage customers to switch to group plans which have a lower churn rate and offer better value.

4. **Adjust Contract Types:**
   - Offer incentives for senior customers to switch from monthly to yearly contracts to reduce churn.

5. **Unlimited Data Plan Promotion:**
   - Promote unlimited data plans, especially to customers who consume high amounts of data to prevent extra charges that lead to churn.

6. **International Plan Promotion:**
   - Target customers without international plans with promotions or propose they downgrade their plan to increase satisfaction and reduce churn.

## How to Run the Project

1. **Clone the repository:**
    ```bash
    git clone https://github.com/krystalbrantley/data-analyst-portfolio.git
    cd data-analyst-portfolio/customer-churn-analysis
    ```

2. **Open the Power BI Report:**
    - Open the `Customer Churn Report.pbix` file in Power BI Desktop.
    - Review and interact with the report to explore the analysis.

3. **Review the Analysis and Findings:**
    - Examine the visualizations and insights provided in the Power BI report.
    - Consider the recommendations and how they can be applied to reduce customer churn.

## Conclusion

The Customer Churn Analysis project provided valuable insights into the reasons behind customer attrition. By leveraging the power of Power BI for data visualization, the analysis identified key factors influencing churn and offered actionable recommendations to enhance customer retention efforts.

## Contact Information

For any questions or further information, please feel free to contact me:

- **LinkedIn:** [My LinkedIn Profile](https://www.linkedin.com/in/krystalbrantley)

Thank you for reviewing this project!
