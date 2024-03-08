# FlyingWhale Airline Customer & Loyalty Program Analysis

## Purpose
Gain data-driven insights into customer behavior and loyalty program performance, allowing FlyingWhale Airline to make informed decisions for optimization and enhanced customer experiences.

## Methodology
### Data Sources

1. **Customer Flight Activity:**
   - **Loyalty Number:** A unique identifier for each customer's loyalty account.
   - **Year and Month:** Period details for analysis.
   - **Flights Booked:** Number of flights booked by the member during the period.
   - **Flights with Companions:** Number of flights booked with additional passengers.
   - **Total Flights:** Combined total of Flights Booked and Flights with Companions.
   - **Distance:** Flight distance traveled in kilometers during the period.
   - **Points Accumulated:** Loyalty points earned in the period.
   - **Points Redeemed:** Loyalty points redeemed during the period.
   - **Dollar Cost Points Redeemed:** Dollar equivalent for points redeemed in Canadian Dollars (CDN).
   
2. **Customer Loyalty History:**
   - **Loyalty Number:** A unique identifier for each customer's loyalty account.
   - **Demographics:** Country, Province, City, Postal Code, Gender, Education, Salary, Marital Status.
   - **Loyalty Card:** Current loyalty card status.
   - **Customer Lifetime Value (CLV):** Total invoice value for all flights ever booked by the member.
   - **Enrollment Details:** Enrollment Type (Standard / 2018 Promotion), Enrollment Year, Enrollment Month.
   - **Cancellation Details:** Cancellation Year and Month if applicable.

### Preprocessing
- Data cleaning and validation (addressing inconsistencies, missing values)
- Date/time normalization
- Customer segmentation by loyalty tier and demographics
### Analysis Techniques
- Descriptive statistics (means, distributions, frequencies)
- Trend analysis (seasonality, year-over-year growth)
- Customer Segmentation Analysis
### Tools
- Power BI, Power Query, DAX, Microsoft Excel

## Key Findings
### Seasonal Booking Patterns
- Significant peaks around spring break, summer (July), and the holiday season (December).
- Potential lulls after the summer (possible correlation with the start of the school year).
### Growth Trend
- Year-over-year comparison shows an increase in bookings, with July 2018 outperforming July 2017.
### Demographic Insights
- Bachelor's degree holders have the highest cancellation rate (62.2%).
- Married customers represent the majority of cancellations (58.7%).
### Loyalty Program Metrics
- Average CLV of $8K, indicating healthy customer retention.
- Average enrollment duration of 15.88 months.
- 16.74K active members, with a total distance traveled exceeding 490 million km.
- 'Star' tier boasts the largest membership (45.6%).

## Recommendations
### Address Seasonality
- Increase capacity and targeted promotions during high-demand periods.
- Develop incentives to encourage off-season travel.
### Refine Loyalty Program
- Tailor benefits to resonate with bachelor's degree holders and small travel groups (2-3 companions).
- Consider incentives for married customers to boost retention.
### Regional Expansion
- Target provinces with lower membership (e.g., Prince Edward Island) for growth.
### Investigate Aurora Tier
- Understand reasons for short enrollment duration and implement strategies to improve engagement and loyalty.

## Next Steps
- **Deeper Dive**: Conduct surveys and qualitative research to understand cancellation reasons.
- **Correlation Analysis**: Explore relationships between demographics, flight preferences (routes, frequency), and loyalty program engagement.
- **Benchmarking**: Compare CLV, cancellation rates, and other KPIs against industry standards to assess program health.

## Contact
- **Project Maintainer**: Hussain Murtaza Ali
- **Email**: hussainmurtaza899@gmail.com
