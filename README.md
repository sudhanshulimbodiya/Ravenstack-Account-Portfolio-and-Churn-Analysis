# Ravenstack-Account-Portfolio-and-Churn-Analysis
## Project Overview
This project was developed to help Ravenstack leadership understand and mitigate a sudden retention crisis that emerged in late 2024. While the company maintains a robust $136M Annual Recurring Revenue (ARR) with a strong Average Revenue Per User (ARPU) of $22.68K, the dashboard reveals a critical escalation in volatility, with churn rising from 2.00% in February to a peak of 26.60% in December 2024.

## The Business Problem
The executive team observed inconsistent retention results across segments and could not pinpoint the drivers behind the massive late-year churn spike.
Some of them are:
1. Which high-value segments were leaking the most revenue.
2. Whether the product expansion strategy—specifically beta feature adoption—was effectively acting as a "retention anchor".
3. The primary reasons customers were leaving, categorized by their plan tiers.
          
## Key Data Sources
The analysis is driven by five core datasets:
1. **ravenstack_accounts**: Customer demographics, industry, and churn status.
2. **ravenstack_subscriptions**: Financial data including ARR, MRR, billing frequency, and plan tiers.
3. **ravenstack_churn_events**: Detailed churn dates, reason codes (e.g., Pricing, Competitor), and feedback.
4. **ravenstack_feature_usage**: Engagement metrics for standard and beta features.
5. **ravenstack_support_tickets**: Customer satisfaction and resolution data.

## Insights Derived
### 1. The Beta Anomaly
The analysis revealed a implausible finding, Beta Adopters have a 22.15% churn rate, nearly double the 12.50% churn rate of Standard Users. While early feature access drives engagement, it is currently correlated with higher-risk segments, suggesting that the features themselves are not yet overcoming external pricing pressures.

### 2. Industry Risk Segmentation
Through risk-segmentation mapping, two distinct categories were identified:
* The Danger Zone (DevTools): A significant outlier with a churn rate exceeding 30%, driven largely by customers switching to competitors.
* The Revenue Anchor (Cybersecurity): The most stable segment, contributing healthy revenue with the portfolio's lowest churn rate of 16%.

### 3. Financial Friction vs Product Value 
Despite active engagement with new features like **feature_35**, churned Enterprise accounts consistently cited "Budget" and "Pricing" as their primary reasons for leaving. This indicates that the 2024 spike was primarily a financial friction issue rather than a lack of product utility.

## Business Impact & Recommendations
Leadership can protect the $136M ARR baseline by implementing the following strategies:
* Stabilize Enterprise Billing: Transition high-risk monthly Enterprise accounts to annual billing to secure revenue and reduce monthly volatility.
* Targeted DevTools Retention: Deploy a specialized success squad to the DevTools segment to address high "switched to competitor" rates.
* Beta Experience Audit: Investigate the feedback of the 22.15% of adopters who churned to ensure beta features are not introducing technical friction for power users.









