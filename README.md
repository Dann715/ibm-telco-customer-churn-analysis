# IBM Telco Customer Churn Analysis (Python & Pandas)

🔎 Overview

Customer churn poses a significant revenue risk for subscription-based businesses. This project analyzes real-world telecommunications customer data to identify the key drivers of churn and provide actionable, data-driven recommendations to improve customer retention.
Using Python, pandas, and data visualization techniques, this analysis explores how contract structure, pricing, tenure, and service features influence churn behavior.

💼 Business Problem

The company is experiencing high customer churn and needs to understand:
- Which customers are most likely to churn
- What factors contribute most to churn
- When customers are most vulnerable to leaving
- How churn can be reduced through targeted interventions

🗂️ Dataset

- Source: IBM Telco Customer Churn Dataset
- Size: 7,043 customer records
- Features: 21 variables including demographics, contract details, services, pricing, tenure, and churn status

💻 Tools & Technologies

- Python
- pandas
- NumPy
- Matplotlib & Seaborn
- Jupyter Notebook
- VS Code

✍🏻 Data Preparation

- Converted financial fields (TotalCharges) from text to numeric format-
- Removed invalid or missing records to ensure data integrity
- Encoded churn as a binary variable (1 = churned, 0 = retained)
- Engineered tenure groups to analyze churn across customer lifecycle stages

🕵 Key Findings

Overall Churn

- The overall customer churn rate is 26.6%, meaning more than 1 in 4 customers leave the service.

📝Contract Type

Contract length is the strongest predictor of churn:

  - Month-to-month: 42.7%
  - One-year: 11.3%
  - Two-year: 2.9%
  - Month-to-month customers are nearly 15× more likely to churn than two-year contract customers.

💸 Pricing

- Churned customers have higher monthly charges on average.
- Higher prices increase churn risk, particularly when not paired with long-term contracts or high-value services.
- <img width="616" height="469" alt="image" src="https://github.com/user-attachments/assets/e8fe0b86-ae82-4754-81be-e3479e22c580" />


📅 Tenure

Churn is heavily concentrated in the first year:

  - 0–1 year: 47.7%
  - 1–2 years: 28.7%
  - 2–4 years: 20.4%
  - 4–6 years: 9.5%

Customers who remain beyond their first year are significantly more likely to stay long-term.

⚙️ Service Features (Online Security)

- Customers without Online Security churn at 41.8%
- Customers with Online Security churn at 14.6%
- Customers without internet service churn at only 7.4%
- Value-added services play a major role in retention.

👍 Business Recommendations

- Target early-tenure customers
- Focus retention efforts within the first 12 months
- Proactive outreach during onboarding
- Incentivize long-term contracts
- Offer discounts or perks for converting month-to-month customers
- Bundle high-value services
- Promote Online Security and similar features as retention tools
- Monitor high-cost customers
- Flag customers with rising monthly charges for retention campaigns

🔜 Next Steps

- Build a churn prediction model to flag high-risk customers
- Create an interactive dashboard (Tableau or Power BI)
- Segment customers further by demographics or service usage

🏁 Conclusion

- This analysis demonstrates that churn is driven by a combination of pricing pressure, contract instability, low perceived value, and early customer lifecycle risk. Addressing these factors can significantly improve customer retention and long-term revenue stability.
