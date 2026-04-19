# Hotel Revenue Statistical Analysis 2024

## Overview
This project applies statistical tools and techniques to analyse Hotel 
Revenue data for 2024. Using Microsoft Excel, the dataset was explored 
through descriptive statistics, multiple visualisations and regression 
analysis across six visitor countries and three seasons. The findings 
are presented in a format suitable for senior business decision-makers.

---

## What Was Done

### 1. Descriptive Statistics
Revenue was analysed across six visitor countries — France, Germany, 
Italy, Spain, the UK and the USA — using key statistical measures 
including mean, median, mode, standard deviation, variance, skewness, 
kurtosis and range.

Key findings:
- The USA had the highest total revenue of 2,342,000 with the highest 
  count of 29 records
- Germany had the highest average revenue at 89,142.85
- Spain showed the highest variability with a standard deviation of 
  4,960 and a range of 15,000, indicating diverse revenue performance
- The UK was the most stable market with the lowest standard deviation 
  of 2,203.89
- Germany showed strong left skewness (-2.77) while the USA showed 
  right skewness (3.53), indicating different distribution shapes 
  across markets

---

### 2. Histogram — Customer Review Score Distribution
A histogram was produced to show the distribution of average review 
scores across score intervals:
- Most reviews fell in the (4.4, 4.5] range with a frequency of 45, 
  indicating strong positive customer perception
- Significant frequencies were also recorded in (4.5, 4.6] with 27 
  and (4.6, 4.7] with 31
- Only 6 reviews fell in the lowest range [4.3, 4.4]
- No reviews were recorded above 4.7

This confirms overall high customer satisfaction with a clear central 
tendency around the 4.4 to 4.6 range.

---

### 3. Box and Whisker Plot — Seasonal Occupancy Rates
A box and whisker plot was used to compare occupancy rates across 
winter, spring and summer:
- Winter and spring both had a median occupancy of 0.78 with a 
  whisker range of 0.75 to 0.81 and a small IQR between 0.75 and 
  0.80, indicating stable and consistent occupancy
- Summer had a slightly lower median of 0.775 and mean of 0.767 
  with a broader IQR from 0.7475 to 0.7925
- Summer showed the lowest minimum of 0.73 and the greatest overall 
  range, indicating more variability in occupancy during this season

---

### 4. Pareto Chart — Reservations by Season
A Pareto chart was created combining a bar chart and cumulative 
percentage line to identify the most significant seasons for bookings:
- Winter had the highest number of reservations at 518
- Summer followed with 278 reservations
- Spring had the lowest at 152 reservations
- Winter and summer together account for over 80% of all reservations, 
  making them the key seasons for resource allocation and marketing focus

---

### 5. Scatter Plot — Revenue vs Total Revenue
A scatter plot was produced to visualise the relationship between 
revenue and total revenue:
- The trend line equation was y = 0.6296x
- The R-squared value was 0.9995, indicating a very strong positive 
  correlation between the two variables
- As revenue increases, total revenue increases proportionally

---

### 6. Regression Analysis — Marketing Spend vs Revenue
A linear regression model was built to investigate the impact of 
marketing spend on revenue:

| Metric | Value |
|---|---|
| Multiple R | 0.988 |
| R-Squared | 0.974 (97.47%) |
| Adjusted R-Squared | 0.974 |
| Standard Error | 719.05 |
| F-Statistic | 4,125.29 |
| Significance F | 2.77e-87 |
| Intercept | 51,998.05 |
| Marketing Spend Coefficient | 0.549 |

Key findings:
- 97.47% of the variation in revenue is explained by marketing spend, 
  confirming it as a strong predictor of revenue
- The intercept of 51,998.05 represents the base revenue level when 
  no marketing spend is applied
- For every additional unit spent on marketing, revenue increases by 
  approximately 0.549 units
- The F-statistic of 4,125.29 and extremely low significance F value 
  confirm the model is statistically significant
- The line fit plot confirmed an upward trend with predicted values 
  closely matching actual data points

---

## Key Takeaway
Marketing spend has a strong, direct and measurable impact on hotel 
revenue. Winter and summer are the dominant seasons for bookings and 
should be the focus of resource planning. Germany and Spain are the 
highest-performing markets by average revenue, while the UK offers 
the most stable and predictable performance. Future analysis should 
consider residual evaluation, multicollinearity checks and additional 
revenue-influencing variables to further strengthen the model.

---

## Tools Used
- **Microsoft Excel** — descriptive statistics, histogram, box and 
  whisker plot, Pareto chart, scatter plot and regression analysis
