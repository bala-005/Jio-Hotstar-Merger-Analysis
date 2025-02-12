# Strategic Data Analysis for Jio-Hotstar Merger

## Project Overview
This project analyzes the strategic merger between **JioCinema** and **Hotstar**, focusing on key business and operational insights. The objective is to provide data-driven recommendations on **subscriber behavior, content consumption trends, and revenue optimization** to ensure a successful integration of the two OTT platforms.

## Business Problem
Jio, a leading telecom provider, is merging with Hotstar, a dominant streaming service, to establish a stronger OTT presence. The management requires insights on:
- Platform performance and user engagement trends.
- Content library comparison in terms of genres, languages, and watch time.
- Subscriber acquisition, churn, upgrades, and downgrades.
- Factors influencing inactivity and strategies to improve retention.
- Revenue analysis based on subscription plan transitions.

## Data Sources
The analysis is based on structured data from two primary databases:
### 1. JioCinema Database
- **Contents Table**: Details on available movies and series.
- **Subscribers Table**: User demographics, subscription details, and activity status.
- **Content Consumption Table**: Watch time and device usage.

### 2. Hotstar Database
- **Contents Table**: Language, genre, and content type details.
- **Subscribers Table**: Subscription plans, plan changes, and last active dates.
- **Content Consumption Table**: Watch time analysis across devices.

## Analytical Approach
### Step 1: Data Cleaning & Preparation
- Handled missing values in `last_active_date`, `plan_change_date`, and `new_subscription_plan`.
- Standardized date formats and removed duplicate records.

### Step 2: Exploratory Data Analysis (EDA) in Excel
- **Subscriber Growth Trends**: Active vs. inactive users segmented by city tier and age group.
- **Content Performance**: Most-watched genres, language preferences, and content type comparison.
- **User Engagement**: Device-wise watch time analysis and trends.
- **Upgrade & Downgrade Behavior**: Subscription transition patterns and impact on revenue.

### Step 3: Business Insights & Recommendations
- **Content Strategy Optimization**: Identified high-engagement genres and recommended mobile-friendly content.
- **User Retention Measures**: Targeted re-engagement strategies for inactive users.
- **Revenue Maximization**: Optimized pricing models for Tier 1, Tier 2, and Tier 3 cities.

## Key Findings
- **35% of users were inactive**, requiring engagement strategies to reduce churn.
- **80% of total watch time was mobile-driven**, indicating the need for mobile-first content.
- **Premium plan retention was highest in Tier 1 cities**, suggesting a location-based pricing advantage.

## Tools & Techniques Used
- **Excel**: Data Cleaning, Pivot Tables, VLOOKUP, COUNTIF, SUMIF, Conditional Formatting.
- **Dashboard**: Interactive Excel charts and slicers for visualization.
- **Business Strategy**: Insights for post-merger optimization.

## Project Deliverables
- **Excel-based Dashboard**: Interactive visualization of key metrics.
- **Data Analysis Report**: Business recommendations and strategic insights.
- **Presentation for Stakeholders**: Final summary of findings and action items.

## Future Enhancements
- Implement machine learning techniques for churn prediction.
- Develop AI-based personalized content recommendation models.
- Expand the study to analyze advertising revenue impact post-merger.


## Conclusion
This project provides a structured approach to analyzing a large-scale OTT merger using Excel. The insights generated serve as a foundation for **business decisions related to content strategy, user engagement, and revenue models**, ensuring the newly merged Jio-Hotstar platform remains competitive in India's streaming market.
