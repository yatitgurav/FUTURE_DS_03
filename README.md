# FUTURE_DS_03 – Bank Marketing Campaign: Funnel & Conversion Analysis

## Objective
Analyze bank marketing campaign data to understand customer subscription behavior, identify conversion patterns, and generate actionable business insights.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power BI

## Dataset
The project uses the **Bank Marketing Campaign Dataset** containing customer and campaign-related information.

The analysis focuses on:
- Customer subscription
- Previous campaign contact
- Contact method
- Job/occupation
- Campaign contact frequency
- Campaign month
- Call duration
- Housing loan
- Personal loan

## Project Workflow
1. Load the bank marketing dataset.
2. Inspect the dataset structure and statistics.
3. Check missing values and duplicate records.
4. Create additional features for analysis.
5. Calculate overall subscription and conversion rates.
6. Analyze conversion by previous campaign contact.
7. Analyze conversion by contact method.
8. Analyze conversion by occupation.
9. Analyze conversion by campaign contact frequency.
10. Analyze monthly conversion rates.
11. Analyze conversion by call duration.
12. Analyze conversion based on housing and personal loans.
13. Export the cleaned dataset.
14. Create a Power BI dashboard for visualization.

## Key Business Insights
- Overall subscription conversion was **11.70%**, with **5,289 subscriptions from 45,211 customers**.
- Customers with previous campaign contact had an observed conversion rate of **23.07%**, compared with **9.16%** for customers without previous contact history.
- Observed conversion declined as campaign contact frequency increased, from **14.60% for one contact** to **3.93% for 10+ contacts**.
- Conversion varied across occupational segments, with students and retired customers showing the highest observed conversion rates.
- Monthly campaign conversion varied considerably.
- Call duration showed a strong association with conversion, increasing from **0.19% for calls under one minute** to **48.36% for calls exceeding ten minutes**.
- Customers without housing or personal loans showed higher observed conversion rates than customers with these loans.

## Business Recommendations
1. Use previous campaign engagement as a segmentation variable for follow-up campaigns.
2. Monitor conversion by campaign contact frequency and test different follow-up strategies.
3. Develop customer-segment-specific messaging using attributes such as occupation, age group, loan status, and previous engagement.
4. Investigate monthly campaign performance together with campaign volume and customer composition.
5. Analyze successful customer conversations to identify communication patterns.
6. Validate proposed campaign changes through controlled experiments before treating observed relationships as fixed business rules.

## Power BI Dashboard
A Power BI dashboard was created to visualize campaign performance and conversion patterns.

The dashboard can be used to understand:
- Overall conversion
- Customer subscriptions
- Campaign performance
- Customer segments
- Contact frequency
- Conversion trends

## Project Files
- `Task3.ipynb` – Python analysis notebook
- `Task 3 dashboard.pbix` – Power BI dashboard
- `bank_marketing_cleaned.csv` – Cleaned dataset

## Conclusion
This project analyzed **45,211 customer records** from a bank marketing campaign and identified important relationships between customer characteristics, campaign activity, and subscription conversion.

The findings highlight opportunities for customer segmentation, improved use of campaign history, evaluation of contact-frequency strategies, campaign timing analysis, and improved customer interactions.

The observed relationships should be validated through controlled experiments before being converted into fixed campaign rules.

## Internship Track
**Track:** Data Science & Analytics  
**Task:** 03
