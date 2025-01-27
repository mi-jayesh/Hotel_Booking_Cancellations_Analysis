# Hotel_Booking_Cancellations_Analysis

This analysis investigates booking cancellations in City Hotels and Resort Hotels from 2015 to 2017, aiming to uncover factors contributing to high cancellation rates and offering actionable insights for minimizing cancellations in the future. The goal is to support hotel management with data-driven strategies to optimize booking retention and improve revenue stability.

**Problem Statement:-**
---
Between 2015 and 2017, both City Hotels and Resort Hotels experienced significant booking cancellations, leading to revenue loss and operational inefficiencies. The analysis focuses on understanding the key drivers of cancellations, comparing cancellation rates across hotel types, and providing insights for reducing cancellations.


**Objectives :-**
---
* **Cancellation Rates:-** Quantify and compare cancellation rates for City Hotels and Resort Hotels.
* **Statistical Significance:-** Use hypothesis testing to determine whether the difference in cancellation rates between the two hotel types is statistically significant.
* **Key Drivers:-** Identify and analyze factors contributing to cancellations, such as customer type, lead time, and seasonal trends.
* **Customer Segmentation:-** Segment customers to determine which groups (e.g., transient, contract, or group customers) are more prone to cancellations.

**Hypotheses :-**
---
* **Lead Time:-** Customers with longer lead times (time between booking and check-in) are more likely to cancel their bookings.
* **Waiting List:-** Bookings placed on a waiting list have higher cancellation rates.
* **Pricing (ADR):-** Higher average daily rates (ADR) contribute to an increased likelihood of cancellations.

**Analysis Workflow :-**
---
* **Cleaning:-** Data preparation and preprocessing to ensure high-quality data for analysis.
* **Analysis:-** Use Python to extract insights, focusing on cancellation rates, customer types, lead times, and seasonal trends.
* **Statistical Analysis:-** Perform a two-proportion Z-test and hypothesis testing to assess key factors influencing cancellations.
* **Reporting:-** Summarize key findings and insights, present actionable recommendations for reducing cancellations, and create visualizations to support decision-making.

 
**Key Highlights:-**

* **Overall Cancellation Rate:-** 37% across both hotel types, with City Hotels (42%) having a significantly higher cancellation rate than Resort Hotels (22%).
* **Customer Type Impact:-**Transient customers are the leading cause of cancellations, contributing to 82.57% of cancellations in City Hotels and 84.67% in Resort Hotels.
* **Lead Time Influence:-** Longer lead times (over 100 days) significantly increase cancellations, particularly for contract and transient customers.
* **Pricing Impact:-** Resort Hotels show a correlation between higher ADR during peak months and increased cancellations, potentially due to affordability concerns.
* **Seasonality:-** High cancellation rates observed in City Hotels from April to October, with August being the peak month; Resort Hotels see high cancellations in July and August.
* **Geographic Insights:-** Portugal, the UK, and Spain are the top countries contributing to cancellations.


**Tools and Technologies Used :-**
---
* **Python:-** Utilized Python libraries such as Pandas for data cleaning, preprocessing, and exploratory data analysis to uncover meaningful insights.
* **Matplotlib & Seaborn (Python Libraries For Visualization):-** Used for data visualization to create insightful charts and plots for cancellation trends and factors.
  
