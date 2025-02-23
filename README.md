# Coupon-Acceptance-Rates

#Project Overview:
This project investigates factors influencing whether drivers accept coupons for restaurants, bars, coffee houses, and carryout orders. The goal is to compare behavioral and demographic differences between customers who accept coupons and those who do not, providing insights for more targeted marketing strategies.

#Data and Methodology
Data Source: Amazon Mechanical Turk (UCI Machine Learning Repository)

Key Attributes: Destination, passenger type, weather, time, coupon type, age, income, marital status, education, and frequency of visits (bars, restaurants, coffee houses, etc.)

Data Preparation: Handled missing values by replacing them with the model for categorical or median for numerical values and also removed duplicated records.

Analysis Tools: Python (pandas, matplotlib, seaborn) created visualizations and computed acceptance rates for various customer segments.

#Key Findings
#Bar Coupons:
Frequent Bar Goers: Drivers who visit bars more than three times per month accept coupons at a high rate (78%) compared to those with fewer visits (34%).

Age Factor: Drivers over 25 who frequently go to bars have an acceptance rate of about 69%, while other groups are closer to 34%

Passenger and Occupation Influence: Drivers without kids as passengers and with occupations outside farming, fishing, and forestry accept coupons at about 71%, significantly higher than the 31% seen in other groups.

Conclusion: These findings suggest that frequent bar visits, older age, and certain social/occupational contexts correlate with higher coupon acceptance.

#Restaurant (<$20) Coupons:
Budget-Friendly Diners: Customers who dine frequently at inexpensive restaurants and earn less than $75K have an acceptance rate of approximately 72.5%.

Young Buyers: Under 30 drivers who frequently purchase takeaway food show similar high acceptance (~73.3%).

Social Dining: Those who dine with partners or friends and also visit coffee houses are the most responsive (84.9% acceptance).

Additional Factors: Fast food diners with low-to-mid incomes accept coupons at 69.8%, while drivers on strict schedules and in bad weather conditions are less receptive (57.1% and 32.3%, respectively).


#Restaurant ($20-$50) Coupons:
Middle-Aged Moderate Diners: Customers aged 30–50 with moderate

Young Budget-Conscious: Younger diners with lower incomes show a slightly higher acceptance rate (53.97%).

Social Diners: Those dining with partners or friends are the most receptive, with a rate of 73.33%.

Lower Engagement: Commuters and customers impacted by adverse weather conditions show lower acceptance rates (45.24% and 25.37%, respectively).

#Conclusion:
Targeted Marketing: Younger, budget-conscious, and socially active customers (e.g., those dining with partners or friends) are most likely to accept coupons.

Behavioral Insights: Frequent visits to a specific type of establishment, whether it’s a bar or an inexpensive restaurant, strongly predict coupon acceptance.

Strategic Implications: Tailoring coupon offers based on demographics (age, income), situational context (weather, time of day, destination), and behavioral patterns (frequency of visits, passenger type) can significantly improve coupon acceptance.


