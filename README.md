# Row Health Marketing Campaign Analysis

## Project Overview
Row Health is a medical insurance company serving thousands of customers across the United States. In 2019, the company launched a marketing campaign focused on better understanding customer needs, with themes such as wellness tips, affordability, and preventative care. Four insurance plans were introduced: Bronze, Silver, Gold, and Platinum — each offering different premium and coverage levels.

Recently, Row Health hired a data team to analyze how these campaigns impacted customer signups and claims. The goal was to guide the marketing team's budget decisions for the upcoming year.

## Dataset
The dataset consisted of three main tables:
- **Customer Information:** Details about individuals who signed up.
- **Campaign Category:** The marketing theme that attracted the customer.
- **Claims Data:** Information about filed insurance claims.

## Project Structure
The analysis was broken down into three sections:

### 1. Marketing Metrics
- **Impressions:** Number of times a campaign was seen.
- **Click Through Rate (CTR):** Percentage of people who clicked the campaign.
- **Cost Per Click (CPC):** Cost for each campaign click.

### 2. Signup Metrics
- **Signup Count:** Total customer signups per campaign.
- **Signup Rate:** Percentage of viewers who signed up.
- **Cost Per Signup (CPS):** Money spent per acquired signup.

### 3. Claim Metrics
- **Claim Amount:** Total payouts for filed claims.
- **Average Claim Amount:** Average payout per claim.

## Insights

### Marketing Insights
- The **'Health for All'** and **'Benefit Updates'** categories had the highest CTRs (25% and 22%), despite having fewer impressions.
- **Golden Years Security** had the highest CPC ($0.68) but the lowest CTR (1.41%), making it an inefficient campaign.
- **Family Coverage** showed over 1.1 million impressions but had missing click and cost data — highlighting a need for better data management.

### Signup Insights
- **Health for All** achieved a 2.08% signup rate — a 316% increase compared to other campaigns.
- Cost per signup for **Health for All** was extremely low at $1.23 compared to **Benefit Updates** at $47.81.
- Signups spiked during the early COVID-19 pandemic period, especially in 2020.

### Claim Insights
- **Compare Health Coverage** saw a 592% surge in claim amounts during the pandemic, underlining the impact of external factors on insurance costs.
- It also had the highest total payout ($3.9M) and highest cost per claim ($410).

## Recommendations
- Scale up the **Health for All** campaign, given its high CTR and cost efficiency.
- Investigate missing data in **Family Coverage** with the engineering team.
- Discontinue or restructure **Golden Years Security** to improve ROI.
- Revisit plan options in **Compare Health Coverage** to minimize costly claims and improve forecasting models.

## Dashboard
Interactive Tableau dashboard visualizes key campaign trends by plan, state, and category:
https://public.tableau.com/views/RowHealth_17214427985250/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Tools & Technologies
- **SQL** for querying and cleaning data
- **Tableau** for dashboard creation
- **Excel** for data wrangling and exploration
