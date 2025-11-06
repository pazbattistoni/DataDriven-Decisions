The purpose of this project is to perform a customer value segmentation (RFM) and identify the most profitable products of the e-commerce company in order to propose two marketing actions focused on retention.

## Analysis & Segmentation (RFM)
We transformed the raw transaction log into a customer-centric DataFrame (`rfm_df`) using Recency, Frequency, and Monetary (RFM) metrics. Customers were then scored (1-5) and grouped into actionable business segments.

### Key Finding: Customer Segment Distribution
* grafico de barras *  
![Customer Segment Distribution](Customer_Segment_Distribution.png)

As shown, a significant portion of the customer base falls into the 'Lost' and 'Potential Loyalist' categories, while a core group of 'Champions' and 'Loyal Customers' drives significant value.

## Strategic Business Recommendations
As a Business Engagement Lead, the data analysis is only valuable if it drives action. Based on the RFM segmentation, I recommend the following targeted strategies:

| Segment | Strategy | Recommended Action (Example) |
| :--- | :--- | :--- |
| **Champions** | **Reward & Empower** | - Grant early access to new products.<br>- Offer exclusive 'loyalty' discounts (e.g., free shipping).<br>- Create a referral program; they are your best advocates. |
| **Loyal Customers** | **Upsell & Engage** | - Offer incentives for higher AOV (Average Order Value), such as "buy 2, get 1 free."<br>- Proactively ask for product reviews to build social proof. |
| **At Risk** | **Reactivate & Win-Back** | - **HIGH PRIORITY:** Target them with personalized win-back email campaigns ("We miss you!").<br>- Offer significant, time-sensitive discounts to incentivize a new purchase. |
| **Potential Loyalists** | **Nurture & Convert** | - Focus on converting their second purchase.<br>- Send follow-up content (e.g., how-to guides for their first purchase).<br>- Offer a small discount for their next order. |
| **Need Attention** | **Personalize & Onboard** | - These are high-spenders but low-frequency. Understand *why*.<br>- Send personalized recommendations based on their high-value purchase.<br>- Ensure their onboarding experience was positive. |
| **Lost** | **Minimal Investment** | - Do not spend significant marketing budget here.<br>- Include them in generic, low-cost marketing (e.g., general newsletter) but focus resources on 'At Risk' and 'Potential'. |
