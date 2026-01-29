# <center> Vehicle-Insurance-EDA
# Overview
This project analyzes customer data from a vehicle insurance company to identify factors influencing customer response to insurance offers. The goal is to extract business insights through EDA and prepare the dataset for predictive modeling.
## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Objective:
Top perform data cleaning, exploratory data analysis (EDA), and visualization to find:
- To explore and understand customer demographics, vehicle attributes, and policy-related features.
- To identify patterns and drivers influencing customer response (Response).
- To uncover business insights that can help insurance companies optimize targeted marketing strategies.
- To prepare the dataset for future machine learning modeling.

## Process Followed:
Data Understanding:
- Loaded and inspected the dataset.
- Reviewed feature definitions and data types.
- Checked dataset size, structure, and basic statistics.
Data Cleaning & Preparation:
- Verified absence of missing values.
- Identified skewness and outliers in numerical features.
- Reviewed categorical feature distributions.
- Assessed class imbalance in the target variable.
Exploratory Data Analysis (EDA):
- Analyzed target variable distribution.
- Studied relationships between:
    - Age and Response.
    - Annual Premium and Response.
    - Vehicle Damage and Response.
    - Customer Vintage and Response.
- Used boxplots, histograms, countplots, and correlation heatmaps.
Insight Generation:
- Translated statistical patterns into business insights.
- Evaluated which features are strong or weak predictors.
- Identified opportunities for customer segmentation and targeting.


## Key Insights:
- The target variable (Response) is highly imbalanced, indicating low overall customer interest.
- Customers without prior insurance are significantly more likely to respond.
- Vehicle damage history strongly increases the probability of response.
- Older customers and long-tenure customers show higher engagement.
- Annual premium alone has limited predictive power.
- Numerical features show weak linear correlation with the target, suggesting non-linear modeling approaches.

## Business Takeaways:
- Mass marketing is inefficient due to low response rates.
- Targeting uninsured customers with vehicle damage history can improve conversions.
- Customer tenure (vintage) is a strong indicator of trust and engagement.
- Behavioral and historical features are more valuable than pricing alone.

## Conclusion:
This project demonstrates a complete exploratory analysis workflow on a real-world insurance dataset. By combining statistical analysis with business reasoning, it highlights how data-driven insights can support better decision-making in insurance marketing and customer targeting.

## Dashboard / Output:
![Vehicle-Insurance-EDA](https://github.com/mynk0220/Vehicle-Insurance-EDA/blob/main/AnnualPremium.png)
![Vehicle-Insurance-EDA](https://github.com/mynk0220/Vehicle-Insurance-EDA/blob/main/AnnualPremiumDisHist.png)
![Vehicle-Insurance-EDA](https://github.com/mynk0220/Vehicle-Insurance-EDA/blob/main/ClaimRate.png)
![Vehicle-Insurance-EDA](https://github.com/mynk0220/Vehicle-Insurance-EDA/blob/main/Claims.png)
![Vehicle-Insurance-EDA](https://github.com/mynk0220/Vehicle-Insurance-EDA/blob/main/CorrelationHEatmap.png)
![Vehicle-Insurance-EDA](https://github.com/mynk0220/Vehicle-Insurance-EDA/blob/main/CountplotVehicleAge.png)
![Vehicle-Insurance-EDA](https://github.com/mynk0220/Vehicle-Insurance-EDA/blob/main/DistributionvsPreviouslyinsured.png)
![Vehicle-Insurance-EDA](https://github.com/mynk0220/Vehicle-Insurance-EDA/blob/main/Duration.png)
![Vehicle-Insurance-EDA](https://github.com/mynk0220/Vehicle-Insurance-EDA/blob/main/Frequency.png)
![Vehicle-Insurance-EDA](https://github.com/mynk0220/Vehicle-Insurance-EDA/blob/main/Frequency.png)




