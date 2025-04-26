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
<div class='tableauPlaceholder' id='viz1745709533354' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ro&#47;RowHealth_17214427985250&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='RowHealth_17214427985250&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ro&#47;RowHealth_17214427985250&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1745709533354');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.minWidth='720px';vizElement.style.maxWidth='1260px';vizElement.style.width='100%';vizElement.style.minHeight='987px';vizElement.style.maxHeight='1287px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.minWidth='720px';vizElement.style.maxWidth='1260px';vizElement.style.width='100%';vizElement.style.minHeight='987px';vizElement.style.maxHeight='1287px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='1627px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

## Tools & Technologies
- **SQL** for querying and cleaning data
- **Tableau** for dashboard creation
- **Excel** for data wrangling and exploration
