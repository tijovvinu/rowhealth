# Row Health Marketing Campaign Analysis

## Project Overview
Row Health is a medical insurance company serving thousands of customers across the United States. In 2019, the company launched a marketing campaign focused on better understanding customer needs, with themes such as wellness tips, affordability, and preventative care. Four insurance plans were introduced: Bronze, Silver, Gold, and Platinum — each offering different premium and coverage levels.

Recently, Row Health hired a data team to analyze how these campaigns impacted customer signups and claims. The goal was to guide the marketing team's budget decisions for the upcoming year.

## Dataset
The dataset consisted of three main tables:
- **Customer Information:** Details about individuals who signed up.
- **Campaign Category:** The marketing theme that attracted the customer.
- **Claims Data:** Information about filed insurance claims.
![image](https://github.com/user-attachments/assets/f5a24f76-bd61-4736-95df-0d04e11e075f)



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

![image](https://github.com/user-attachments/assets/6cf285de-3dfd-457c-9b55-35ead02eb3ad)
![image](https://github.com/user-attachments/assets/dea5600d-38f1-4eb9-8282-aa4f3d281379)


### Signup Insights
- **Health for All** achieved a 2.08% signup rate — a 316% increase compared to other campaigns.
- Cost per signup for **Health for All** was extremely low at $1.23 compared to **Benefit Updates** at $47.81.
- Signups spiked during the early COVID-19 pandemic period, especially in 2020.

![image](https://github.com/user-attachments/assets/e3598b1f-457b-4f70-9ea3-892231f401ea)
![image](https://github.com/user-attachments/assets/c8b250be-b684-41fb-b067-810c7c224212)


### Claim Insights
- **Compare Health Coverage** saw a 592% surge in claim amounts during the pandemic, underlining the impact of external factors on insurance costs.
- It also had the highest total payout ($3.9M) and highest cost per claim ($410).
<img width="630" ![image](https://github.com/user-attachments/assets/4e68e511-1357-4032-b9c7-e791bff11261)>
<img width="630" ![image](https://github.com/user-attachments/assets/0af0b96e-66ad-495d-9988-7836276039ab)>
![image](https://github.com/user-attachments/assets/91c58895-cd0b-4955-8b9c-479a100cbcbd)


## Recommendations
- Scale up the **Health for All** campaign, given its high CTR and cost efficiency.
- Investigate missing data in **Family Coverage** with the engineering team.
- Discontinue or restructure **Golden Years Security** to improve ROI.
- Revisit plan options in **Compare Health Coverage** to minimize costly claims and improve forecasting models.

## Dashboard
Interactive Tableau dashboard visualizes key campaign trends by plan, state, and category:
https://public.tableau.com/views/RowHealth_17214427985250/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

<img width="630" alt="Dashboard 1" src="https://github.com/user-attachments/assets/7b256664-bd74-4f3f-b9c4-f00a504dec1b" />


## Tools & Technologies
- **SQL** for querying and cleaning data
- **Tableau** for dashboard creation
- **Excel** for data wrangling and exploration
