 Customer Churn Analysis in Telecommunications
 Overview

Customer churn is a major challenge in the telecommunications industry, as losing customers directly impacts long-term revenue and growth. Traditional approaches often react to churn after it occurs, rather than preventing it.

This project aims to:

Predict which customers are likely to churn
Identify key drivers behind churn behavior
Quantify the financial impact of churn
Recommend actionable strategies to improve retention

Risk Segmentation and Business Impact

<img width="1024" height="374" alt="Screenshot 2026-04-13 at 12 50 40 PM" src="https://github.com/user-attachments/assets/6f261e5f-2907-4dbe-a1ac-eecbe93c4aa2" />

Churn risk is not evenly distributed across the customer base. By segmenting customers into risk tiers, we observe that a relatively small portion of customers accounts for a disproportionately large amount of revenue at risk.

This segmentation allows businesses to:

prioritize high-risk, high-value customers
allocate retention resources more effectively
understand where the greatest financial exposure exists

This step is critical because it transforms churn from a general problem into a targeted business opportunity.

Model Performance

<img width="521" height="314" alt="Screenshot 2026-04-13 at 12 53 10 PM" src="https://github.com/user-attachments/assets/c790d8a4-d939-4400-b34c-2b3eeede9359" />
<img width="364" height="110" alt="Screenshot 2026-04-13 at 12 53 51 PM" src="https://github.com/user-attachments/assets/a024b6ad-d401-4325-bfeb-86411f8a83e0" />


To predict churn, we trained machine learning models and evaluated their performance using multiple metrics.

While standard metrics such as AUC and accuracy show that the model performs well, the most important result is the lift analysis.

Lift demonstrates that:

the model successfully ranks customers by churn risk
the highest-risk groups contain significantly more churners than average
targeted intervention is far more effective than random outreach

This confirms that the model is not only accurate, but also actionable in a business context.

Key Drivers of Churn

<img width="1024" height="374" alt="Screenshot 2026-04-13 at 12 50 40 PM" src="https://github.com/user-attachments/assets/7e9366ab-7750-4c6d-9bd0-6cb20a1eb0d4" />

Understanding why customers churn is just as important as predicting who will churn.

The cohort analysis reveals two major drivers:

Tenure: New customers are significantly more likely to churn
Contract Type: Month-to-month customers have the highest churn rates

The interaction between these factors is especially important.
New customers on flexible contracts are the most vulnerable segment.

This insight suggests that:

early customer experience is critical
contract structure plays a major role in retention
Financial Impact of Churn

<img width="809" height="459" alt="Screenshot 2026-04-13 at 12 56 34 PM" src="https://github.com/user-attachments/assets/c99ac8fb-7886-47fc-8ba9-5d0ccf772e00" />

To evaluate the business impact, we calculated expected value under two scenarios:

No Action: Customers churn based on predicted probabilities
Intervention: Targeted retention strategies are applied

Results show:

Doing nothing leads to significant expected losses
Targeted intervention produces positive expected value

This demonstrates that churn prediction is not just informative — it directly supports profit-improving decisions.

Targeting High-Value Customers

<img width="661" height="269" alt="Screenshot 2026-04-13 at 11 47 37 AM" src="https://github.com/user-attachments/assets/9ee24190-83ac-4f9c-bc7c-352db9003c52" />

Not all customers should be treated equally.
By combining churn probability with customer value (CLV), we can identify the most important customers to retain.

These high-priority customers:

have high churn risk
represent significant revenue
provide the greatest return on intervention efforts

This allows businesses to move from broad retention campaigns to precision targeting.

📈 Strategy Recommendations

👉 INSERT GRAPH HERE:
Integrated Strategy Playbook (impact vs effort + ranking)

Based on the analysis, we developed a set of strategic recommendations prioritized by:

expected impact
implementation effort
estimated return on investment

Key strategies include:

contract conversion incentives
improving onboarding for new customers
targeted retention offers for high-risk segments

While these strategies are informed by model insights, they represent business decisions built on data, rather than purely automated outputs.
