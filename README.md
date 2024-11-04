# E-Commerce User Activity Analysis

## Project Overview
This project analyzes user activity logs for an e-commerce website to derive business insights. The primary tasks include building a conversion funnel, preparing data for cohort analysis, calculating retention rates, and presenting findings in a polished format.

## Dataset
The dataset used for this analysis includes logs of user activities on the e-commerce platform. Each row represents an event, such as a product page view, shopping cart opening, or purchase, with the following columns:

- `user_id`: Unique customer ID
- `event_type`: Type of activity (e.g., page view, add to cart, purchase)
- `category_code`: Category of the product
- `brand`: Manufacturer of the product
- `price`: Price of the product in USD
- `event_date`: Date of user activity in YYYY-MM-DD format

## Project Link
[E-Commerce User Activity Analysis](https://docs.google.com/spreadsheets/d/1BkzDAsLUU4UvfIV7IG0OLs2IsUEwv5jcWGsncj1SloU/edit?usp=sharing)

## Introduction
As a new junior analyst at an e-commerce company, I was tasked with analyzing raw transaction logs to help the executive team better understand user behavior. The project includes building a conversion funnel, preparing data for cohort analysis, and calculating retention rates to gain insights into user engagement and retention on the website.

## Project Objectives
1. Build a conversion funnel to understand how well product page views convert into purchases.
2. Create acquisition cohorts based on the month of a user's first purchase and track retention month-by-month.
3. Calculate retention rates and summarize insights for each cohort.
4. Organize, document, and format the analysis for executive presentation.

## Methodology
1. **Conversion Funnel Analysis**: Built a conversion funnel in a pivot table to track user movement through three stages (views, adds to cart, and purchases). Calculated overall and next-step conversion rates.
2. **Cohort Preparation and Analysis**: Filtered the dataset to isolate purchase events and created acquisition cohorts based on the first purchase month. Monthly data columns were generated to track the age of each cohort, enabling detailed retention tracking.
3. **Retention Rate Calculation**: Aggregated the purchase data into cohorts and calculated retention rates for each cohort over a four-month period.
4. **Documentation and Formatting**: Summarized the results in an executive summary sheet, organized sheets for easy navigation, and formatted tables for readability.

## Visual Representations

### Conversion Funnel
This funnel shows how users interact with the website, from product views to purchases, and calculates conversion rates.

<img src="https://github.com/rubythedev/e-commerce-user-activity-aalysis/blob/main/conversionfunnel.png" width="400">

### Retention Rates by Cohort
This visualization shows the retention rates across cohorts, helping to understand customer retention trends over time.

<img src="https://github.com/rubythedev/e-commerce-user-activity-aalysis/blob/main/retentionrates.png" width="400">

### Unique Users by Cohort
This chart represents the number of unique users for each cohort, calculated by month. It highlights the initial user engagement and retention patterns over time for each cohort, providing insights into cohort-based user retention and engagement.

<img src="https://github.com/rubythedev/e-commerce-user-activity-aalysis/blob/main/cohortage.png" width="400">

## Key Findings

- **Conversion Funnel**:
  - Out of 10,459 users, 10,453 viewed items, 3,036 added items to their cart, and 1,081 made a purchase.
  - Conversion rate from viewing to adding to cart: 29.04%.
  - Conversion rate from viewing to making a purchase: 10.34%.
  - Conversion rate from adding to cart to purchasing: 35.61%.

- **Retention Rates**:
  - **September 2020 cohort**: 12.50% purchased in the first month, 6.25% in the second, none in the third, and 3.13% in the fourth.
  - **October 2020 cohort**: 7.49% purchased in the first month, 3.74% in the second, 0.53% in both the third and fourth months.
  - **November 2020 cohort**: 5.46% purchased in the first month, 2.94% in the second, and 0.42% in the third.
  - **December 2020 cohort**: 4.43% purchased in the first month and 2.96% in the second.
  - **January 2021 cohort**: 6.87% purchased in the first month.

## Conclusion
The analysis highlights key areas for improvement in user experience and retention. Optimizing the checkout process could increase conversion rates, and targeted marketing could enhance customer retention.

## Recommendations for Improvement
- **Reduce Drop-Off at Checkout**: Implement strategies such as simplifying the checkout process, offering discounts for completing purchases, or providing reminders for abandoned carts.
- **Engagement Strategies for New Users**: Create targeted engagement campaigns to encourage repeated visits within the first month after purchase, potentially increasing retention rates.

## Future Directions
1. **Advanced Funnel Analysis**: Further break down conversion rates by product categories or brands to understand specific product performance.
2. **User Segmentation Analysis**: Segment users based on spending patterns, frequency of visits, or other demographic factors to tailor marketing efforts.
3. **A/B Testing for Checkout Process**: Conduct A/B tests on different checkout experiences to identify the most user-friendly design.

---

This project provides valuable insights into user engagement and retention patterns, and the recommendations presented are aimed at helping the company drive better customer retention and improve the overall shopping experience.
