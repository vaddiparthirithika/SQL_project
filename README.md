# New Wheels – SQL-Based Business Analysis Project

## Problem Statement

**New-Wheels**, a vehicle resale company, has seen declining sales and customer satisfaction over the past year. As a result, the leadership team seeks a **quarterly business report** with actionable insights to identify key problem areas and inform decision-making.

The company offers an end-to-end service—from vehicle listing to post-sale feedback—through its mobile app. The dataset includes order details, feedback, shipping times, and customer ratings.

---

## Business Context

In today’s resale vehicle market, customers are sensitive not only to pricing but also to post-purchase service quality. **New-Wheels’ app** is central to their operations, but declining metrics indicate systemic inefficiencies.

The CEO wants a **data-driven report** covering quarterly trends in revenue, orders, customer ratings, shipping times, and customer feedback.

---

## Objective

As a Data Analyst, your role is to:
- Analyze historical data using SQL.
- Create a quarterly business performance report.
- Identify operational bottlenecks and customer pain points.
- Provide **actionable business recommendations** to reverse the negative trend.

---

## Data Source

- Database dump imported into a relational database.
- Multiple tables covering:
  - Orders
  - Customer feedback
  - Shipping metrics
  - Ratings and cancellations
  - Product and regional information

---

## Tools Used

- **SQL**: For querying and analysis
- **DBMS**: MySQL / PostgreSQL (or any SQL-compatible environment)
- **Spreadsheet / BI Tool**: For visualization (optional)
- **Python (Optional)**: For extending insights and dashboarding

---

## Key Findings

| Metric | Insight |
|--------|---------|
| Revenue & Orders | Sharp drop from Q1 to Q4; Q4 = only ~18.7% of total revenue |
| Repeat Customers | Very low repeat purchase rate = weak brand loyalty |
| Ratings | Dropped to an average of **3.065**, declining every quarter |
| 'Good' Feedback | Only 20.5% of feedback is positive |
| Shipping Delays | Avg. shipping time in Q4 = **105 days** (extremely high) |
| Cancellations & Delays | Spiked in Q3 & Q4, pointing to broken fulfillment |
| Regional Trends | Different vehicle brand preferences by region |
| App Role | App handles everything from listing to shipping |

---

## Business Recommendations

1. **Run Seasonal Promotions**: Revive order volume and customer interest with offers and discounts.
2. **Launch Loyalty & Referral Programs**: Improve retention and build trust among repeat customers.
3. **Improve After-Sales Service**: Build a dedicated support team to reduce negative feedback.
4. **Logistics Optimization**: Audit and streamline the shipping pipeline to reduce delivery times.
5. **Add App Features**: Include “Track My Order”, “Live Chat”, and “Escalate Issue” options.
6. **Switch to Monthly Dashboards**: Reduce decision lag by monitoring KPIs like shipping time, ratings, and revenue monthly.
7. **Use Predictive Analytics**: Forecast churn and personalize product recommendations.
8. **Run Targeted Marketing Campaigns**: Use regional and past behavior data for location-based offers.
9. **Upsell & Premium Offers**: Introduce premium services like extended warranties to boost order value.
10. **Form a Quarterly Business Health Task Force**: Regular review of KPIs and proactive decision-making.

---

## Files Included

- new_wheels_ER_diagram.pdf
- new_wheels_project_dumpfile.sql - Input Data
- SQL_NewWheels_output.docx - Queries and answers 
- `README.md` – Project overview and recommendations

---

## Future Scope

- Automate KPI tracking with a live SQL dashboard
- Use NLP to analyze open-ended customer feedback
- Integrate predictive models for churn and order value forecasting
- Build a real-time performance dashboard for executive stakeholders

