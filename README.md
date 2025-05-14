# 💳 Aurex Bank - Dynamic Credit Card Performance Monitoring Dashboard (Week 53)

## Overview

Aurex Bank, a tech-driven credit issuer, requires a dynamic and scalable analytics solution to track weekly credit card performance across multiple financial, demographic, and behavioral dimensions. With rising customer acquisition costs, fluctuating activation rates, and evolving delinquency risks, stakeholders need real-time KPIs to monitor revenue, transaction trends, and credit health.

This project integrates data from credit card operations and customer profiles to provide comprehensive insights into card usage patterns, customer behavior, and financial performance.

## 🧩 Problem Statement

Aurex Bank faces the challenge of tracking key performance indicators (KPIs) such as revenue, transaction trends, credit health, and customer satisfaction. The need for real-time data visualization is crucial to allow stakeholders to react quickly to any changes in card usage patterns, delinquency risks, or other financial metrics.

## 📁 Data Structure

### Credit Card Data

- **Client_Num**: Unique identifier for each client
- **Card_Category**: Type of card (e.g., Blue, Silver, Gold, Platinum)
- **Annual_Fees**: Fees charged annually for the card
- **Activation_30_Days**: Number of activations within the last 30 days
- **Customer_Acq_Cost**: Cost of acquiring the customer
- **Week_Start_Date**: The start date of the week
- **Week_Num**: Week number in the year
- **Qtr**: Quarter of the year
- **current_year**: The current year
- **Credit_Limit**: Total credit limit for the customer
- **Total_Revolving_Bal**: Total revolving balance on the card
- **Total_Trans_Amt**: Total transaction amount processed in the week
- **Total_Trans_Vol**: Total transaction volume processed in the week
- **Avg_Utilization_Ratio**: Average credit utilization ratio
- **Use Chip**: Whether the card uses a chip
- **Exp Type**: Type of transaction (e.g., online, in-person)
- **Interest_Earned**: Interest earned from the card
- **Delinquent_Acc**: Whether the customer has delinquent accounts

### Customer Detail Data

- **Client_Num**: Unique identifier for each client
- **Customer_Age**: Age of the customer
- **Gender**: Gender of the customer
- **Dependent_Count**: Number of dependents
- **Education_Level**: Education level of the customer
- **Marital_Status**: Marital status of the customer
- **state_cd**: State code
- **Zipcode**: Zip code of the customer
- **Car_Owner**: Whether the customer owns a car
- **House_Owner**: Whether the customer owns a house
- **Personal_loan**: Whether the customer has a personal loan
- **contact**: Method of contact (e.g., phone, email)
- **Customer_Job**: Job or occupation of the customer
- **Income**: Annual income of the customer
- **Cust_Satisfaction_Score**: Customer satisfaction score

## 📊 Key Insights — Week 53 (📅 31st Dec)

- **Revenue**: Increased by 28.8%, from $933K (24 Dec) to $1M (31 Dec), signaling strong year-end performance driven by holiday spending.
- **Total Transaction Volume**: Rose from 749K to 1M, a 33.5% jump, indicating heightened consumer activity during festive seasons.
- **Customer Satisfaction**: Dropped from 4.21 (24 Dec) to 3.49 (31 Dec), possibly due to service disruptions, credit card declines, or loan rejections during peak season.

## 📅 Year-To-Date (YTD) Overview

- **Total Revenue**: $57M
- **Total Interest Earned**: $8M (14% of overall revenue)
- **Total Transaction Amount Processed**: $46M
- **Revenue by Gender**: Male customers contributed $31M; Female customers contributed $26M.
- **Card Types**: Blue and Silver cards account for 93% of transactions, while premium cards (Gold, Platinum) underperform.
- **Regional Insights**: Texas (TX), New York (NY), and California (CA) account for 68% of total transactions.

### 📌 Key Metrics

- **Activation Rate**: 57.5% of issued cards are active, presenting an opportunity for improvement.
- **Delinquency Rate**: 6.06%, within acceptable limits but needs monitoring.
- **Revenue per Card**: Blue and Silver cards dominate in transaction volume but may not be the most profitable.
- **Satisfaction Drop**: The dip in satisfaction score during the peak holiday week warrants further investigation.

## 🔍 Observations & Strategic Insights

- **Blue & Silver cards** contribute to **93% of total transactions**, showing dominance of base and mid-tier cards.
- **Gold & Platinum cards** underperform — opportunity to reposition or adjust eligibility criteria.
- **Top 3 states — TX, NY, CA — contribute 68% of transactions** — potential for deeper segmentation or pilot campaigns.
- **Activation rate is only 57.5%** — nearly **42.5% of cards remain unused**.
- **Delinquency rate**: **6.06%** — manageable, but continuous risk segmentation by geography and demographics is critical.
- Blue & Silver cards drive high volume but may not be most profitable — **revenue-per-card analysis needed**.
- Targeted **offers, rewards, or financial education campaigns** can increase female customer engagement.
- Drop in satisfaction during Week 53 may affect NPS — **root cause analysis needed immediately**.

---
## 🎯 Recommendations & Next Steps

1. **Activation Rate Improvement**: 
   - Identify drop-off points in the customer activation journey.
   - Implement incentives, onboarding improvements, or behavioral nudges to increase activation.

2. **Delinquency Management**: 
   - Monitor delinquency trends in specific regions and card types.
   - Introduce targeted communication or credit limit restrictions to manage credit risk.

3. **Regional Focus**: 
   - Leverage high-concentration regions (TX, NY, CA) for targeted campaigns and deeper segmentation.

4. **Premium Card Strategy**: 
   - Investigate opportunities for upselling premium cards through better positioning or revised eligibility criteria.

5. **Customer Satisfaction**: 
   - Conduct root-cause analysis of satisfaction drops and improve service quality during peak periods.

6. **Revenue from Interest**: 
   - Promote revolving credit options with responsible usage education to increase interest earnings.

7. **Customer Segmentation**: 
   - Segment customers by satisfaction score, income, credit behavior, and education to optimize engagement and product placement.

## 🛠️ Technologies Used

- **Programming Languages**: Python, SQL
- **Data Visualization**: Power BI
- **Database**: MySQL, PostgreSQL
- **Tools**: GitHub

## 📌 Conclusion

The Aurex Bank Dynamic Credit Card Performance Monitoring Dashboard provides key insights into the credit card performance across multiple dimensions. The dashboard is designed to allow stakeholders to monitor trends, identify risks, and make data-driven decisions in real-time.

## 📌 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📌 Contact

For inquiries or further information, feel free to reach out to **Shubham Pandit** at [shubham.pandit@gmail.com].
