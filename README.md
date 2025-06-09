
# 📊 Row Health Marketing Campaign Analysis

## 🧠 Project Overview
Row Health is a US-based medical insurance company that launched a marketing campaign in 2019 to understand and attract customers through themes like **wellness**, **affordability**, and **preventative care**. They introduced four plans: **Bronze**, **Silver**, **Gold**, and **Platinum**, each offering varying levels of premiums and coverage.

The company hired a data team to evaluate the campaign’s impact on **customer signups** and **insurance claims**, to inform future marketing spend.

---

## 📁 Dataset Overview
The dataset includes three main tables:

- `Customer Information` – User demographics and signup details
- `Campaign Category` – Campaign themes customers engaged with
- `Claims Data` – Details of insurance claims filed

<p align="center">
  <img width="600" src="https://github.com/user-attachments/assets/f5a24f76-bd61-4736-95df-0d04e11e075f" alt="Data Schema">
</p>

---

## 🔍 Project Structure

### 1️⃣ Marketing Metrics
- **Impressions** – Total campaign views
- **Click-Through Rate (CTR)** – Clicks / Impressions
- **Cost Per Click (CPC)** – Spend / Clicks

### 2️⃣ Signup Metrics
- **Signup Count** – Total new signups
- **Signup Rate** – Signups / Impressions
- **Cost Per Signup (CPS)** – Spend / Signups

### 3️⃣ Claims Metrics
- **Total Claim Amount**
- **Average Claim Amount per Campaign**

---

## 📈 Key Insights

### 📌 Marketing Performance
- 🟢 *Health for All* and *Benefit Updates* campaigns had **CTR > 20%**, indicating strong engagement.
- 🔴 *Golden Years Security* had the **lowest CTR (1.4%)** and **highest CPC ($0.68)** — inefficient spend.
- ⚠️ *Family Coverage* had **missing click/cost data**, signaling poor data capture.

<p align="center">
  <img width="600" src="https://github.com/user-attachments/assets/6cf285de-3dfd-457c-9b55-35ead02eb3ad" />
  <img width="600" src="https://github.com/user-attachments/assets/dea5600d-38f1-4eb9-8282-aa4f3d281379" />
</p>

---

### 🧾 Signup Trends
- 🏆 *Health for All* saw a **2.08% signup rate** and the **lowest CPS ($1.23)** — highly cost-effective.
- 🚀 Major signup spike occurred during the **COVID-19 pandemic in 2020**.

<p align="center">
  <img width="600" src="https://github.com/user-attachments/assets/e3598b1f-457b-4f70-9ea3-892231f401ea" />
  <img width="600" src="https://github.com/user-attachments/assets/c8b250be-b684-41fb-b067-810c7c224212" />
</p>

---

### 💸 Claims Analysis
- *Compare Health Coverage* had the **highest payout ($3.9M)** and saw a **592% claim surge** during the pandemic.
- This plan also recorded the **highest average claim amount ($410)**.

<p align="center">
  <img width="600" src="https://github.com/user-attachments/assets/4e68e511-1357-4032-b9c7-e791bff11261" />
  <img width="600" src="https://github.com/user-attachments/assets/0af0b96e-66ad-495d-9988-7836276039ab" />
  <img width="600" src="https://github.com/user-attachments/assets/91c58895-cd0b-4955-8b9c-479a100cbcbd" />
</p>

---

## ✅ Recommendations

- 📢 **Scale** *Health for All* – strong CTR and lowest acquisition cost.
- 🛠️ **Fix** missing data issues in *Family Coverage* campaign.
- 🔁 **Rework** or discontinue *Golden Years Security*.
- 📉 **Refine** plans like *Compare Health Coverage* to reduce costly claim payouts.

---

## 📊 Interactive Dashboard

Explore trends by campaign, plan, and state:
🔗 [View Tableau Dashboard](https://public.tableau.com/views/RowHealth_17214427985250/Dashboard1)

<p align="center">
  <img width="600" src="https://github.com/user-attachments/assets/7b256664-bd74-4f3f-b9c4-f00a504dec1b" alt="Tableau Screenshot">
</p>

---

## 🛠 Tools & Technologies

| Tool        | Purpose                       |
|-------------|-------------------------------|
| `SQL`       | Data cleaning and joins       |
| `Tableau`   | Dashboard & Visualizations    |
| `Excel`     | Data preprocessing & QA       |

---

## 🙋‍♂️ About Me

Hi, I’m Tijo Vargheese Vinu – a Data Science graduate passionate about using analytics to tell stories and improve business decisions. Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/tijovvinu/) or explore more of my work here on GitHub.

---
