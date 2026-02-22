# Meta Ad Performance Analysis 

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-blue?style=for-the-badge&logo=microsoftpowerbi) 
![Excel](https://img.shields.io/badge/Tool-Excel-green?style=for-the-badge&logo=microsoftexcel) 
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge) 
![Domain](https://img.shields.io/badge/Domain-Digital%20Marketing-lightblue?style=for-the-badge) 
![Data Size](https://img.shields.io/badge/Data-Campaign%20Analytics-orange?style=for-the-badge) 
![Portfolio Project](https://img.shields.io/badge/Portfolio-Project-purple?style=for-the-badge) 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/yourprofile) 
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github)](https://github.com/yourusername)

---

## 📑 Table of Contents

1. [Project Background](#1-project-background)  
2. [Data Set Overview & Model](#2-data-set-overview--model)  
3. [Executive Summary](#3-executive-summary)  
4. [Key Insights](#4-key-insights)  
5. [Recommendations & Impact](#5-recommendations--impact)  
6. [Tools Used](#6-tools-used)  
7. [Author](#7-author)  
8. [Contact Information](#8-contact-information)  

---

## 1. Project Background
This project analyzes a **Meta advertising campaign** with a total investment of **$2.5M**. The goal is to understand why a high engagement rate (**11.76% CTR**) is not fully converting into completed purchases.  

By analyzing **user behavior** and **ad formats**, the project identifies friction points in the conversion funnel and provides actionable strategies to optimize future marketing spend.

---

## 2. Data Set Overview & Model
The campaign data is structured in a **relational database**, tracking user interactions from **first impression** to **final sale**.

<details>
<summary>Click to expand: Data Model & Column Details</summary>

### Tables & Columns

| Table       | Description | Key Columns |
|------------|------------|------------|
| **Campaigns** | Tracks high-level campaign data | `campaign_id`, `name`, `duration_days`, `total_budget` |
| **Ads** | Contains creative attributes | `ad_platform` (Facebook/Instagram), `ad_type` (Video/Stories), `target_interests` |
| **Users** | Contains demographic profiles | `user_gender`, `age_group`, `country`, `user_interests` |
| **Ad Events** | Central fact table recording interactions | `event_type` (Impression, Click, Purchase), `timestamp`, `time_of_day` |



</details>

---

## 3. Executive Summary
The Meta advertising campaign successfully captured the attention of a large audience. The ads reached a total of **216k people** and achieved an impressive **click-through rate (CTR) of 11.76%**, far above the industry average of 1–2%. This means that the campaign was very effective at attracting interest and getting people to click on the ads.

However, despite this high engagement, the number of **actual purchases was much lower**, with only **1,300 purchases** coming from **25,400 clicks**. This indicates that while the ads were successful in getting users’ attention, many potential customers were **dropping off before completing their purchase**. The main friction appears to be in the final steps—like the website experience, checkout process, or product details.

By looking closely at the campaign data, we can identify **who engaged with the ads, which ad formats worked best, and when users were most active**. This provides valuable insights for **optimizing future campaigns** to make sure clicks actually turn into purchases.

### Key Data Points (for easy reference)

- **Total Impressions:** `216K`  
- **Click-Through Rate (CTR):** `11.76%`  
- **Total Clicks:** `25.4K`  
- **Total Purchases:** `1.3K`  

### Dashboard Overview


<img width="661" height="377" alt="img2" src="https://github.com/user-attachments/assets/4ab774dd-e92f-4f9c-ae9b-32870681a3e8" />

---

## 4. Key Insights
<details>
<summary>Click to expand: Key Insights</summary>

- **Demographic Reach:** Women are the most active participants (`13K engagements`) vs men (`6K engagements`).  
- **Core Audience:** Young adults aged **18–30** form the primary user base.  
- **Format Performance:** Video ads lead with `11.9% CTR` and `5.2% purchase rate`.  
- **Brand Exposure:** Stories are highly effective, contributing `72K impressions`.  
- **Geography & Timing:** Highest engagement from **US, India, Brazil**, especially `15:00–20:00`.

</details>

---

## 5. Recommendations & Impact
<details>
<summary>Click to expand: Recommendations</summary>

- **Target Optimization:** Focus on women aged **18–30** in **US and India**.  
- **Creative Spend Shift:** Invest more in **Video and Stories**, reduce static image spend.  
- **Temporal Strategy:** Schedule ads during **afternoon and evening**.  
- **UX Improvements:** Optimize **landing pages** to reduce friction and boost conversions.  

**Expected Impact:**  
Reduces wasted ad spend on low-performing segments and improves **click-to-purchase conversion rate**.

</details>

---

## 6. Tools Used
<details>
<summary>Click to expand: Tools Used</summary>

| Tool       | Purpose |
|------------|--------|
| **Power BI** | Data modeling, DAX calculations, interactive dashboards |
| **Excel** | Initial data inspection, summaries |

</details>

---

## 7. Author 
 **Ghulam Mustafa**

---

 ## 📞 Contact Information

If you have any questions, suggestions, or would like to connect regarding this project, feel free to reach out:

- **Name:** Ghulam Mustafa  
- **Email:** ghulammustafa.ds.ai@gmail.com  
- **LinkedIn:** www.linkedin.com/in/ghulam-mustafa-data-analyst  
- **GitHub:** https://github.com/ghulammustafadsai-web 

I am always open to collaboration, feedback, or discussing data analytics and lending projects.  
