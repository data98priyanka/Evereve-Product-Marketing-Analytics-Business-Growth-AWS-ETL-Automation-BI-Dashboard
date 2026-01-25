
<h1 style="font-size:1.6em;"> Evereve — ⭐End to End Full Stack Analyst Project | Data ingestion (CRM + ERP + WEB) |AWS-ETL-Pipeline-Automation | Driving Sustainable Sales Growth and Marketing Efficiency in Women’s Health through - Product & Marketing Analysis</h1>
<p style="font-size:12px; color:#555;">
  <b><i><u> 🔴 Product & Marketing Research Analyst initiative | ⭕ FMCG ⭕ Women’s Health & Personal Care ⭕ Feminine Hygiene ⭕ B2C</u></i></b>
</p>
<p>
<img src="IMAGES/logo.png" width="300" align="LEFT" style="margin-right:15px;"/>
  
</p>
🌍 <b>Evereve Company Vision (Public & Strategic Context)</b>

> <small>Evereve is a women’s hygiene & personal care brand focused on safe, high-quality feminine products that promote dignity, awareness, and well-being across all socio-economic segments.</small>






---
<h3>🚀 Project Overview : </h3> 

<small>
<span style="color:gray;">

• This project delivers a <b>comprehensive, data-driven analysis</b> for a <b>Sanitary Napkin FMCG brand</b> , focused on <b>Product Strategy</b> and <b>Marketing Performance</b> 📊 to accelerate growth in a highly competitive market 📈. <br>

• The core objective is to identify what truly drives <b>sales</b> and <b>repeat purchases</b> — including <b>pack-size performance</b>, <b>pricing</b>, <b>customer retention</b> 🔁, <b>promotions</b> 💸, and <b>campaign impact</b> 🚀. <br>

• The project delivers <b>clear insights</b> and <b>actionable recommendations</b> to improve <b>product performance</b>, <b>customer loyalty</b>, <b>marketing efficiency</b>, and <b>regional expansion</b> 🗺️ — enabling smarter decisions and <b>sustainable growth</b> 🏆.

</span>
</small>

----
<h2>🎯 Problem Statement : </h2> 

<small>
<span style="color:gray;">

The <b>sanitary napkin market in India</b> is highly competitive and fast-changing, driven by:

1. <b>Strong competition</b> from established and emerging brands 🏷️  
2. <b>Price-sensitive customers</b> and heavy <b>discounting wars</b> 💸  
3. The need to improve <b>awareness</b>, <b>trust</b>, and <b>repeat purchases</b> 🩷  
4. Changing consumer expectations for <b>comfort</b>, <b>safety</b>, and <b>quality</b> 🌿  

This project addresses the need for <b>data-driven growth</b> and smarter <b>decision-making</b>. By analyzing <b>product</b>, <b>sales</b>, and <b>marketing performance</b>, we aim to:

1. Identify what drives <b>sales</b> and <b>repeat buying</b> 🔁  
2. Optimize <b>pricing</b>, <b>pack sizes</b>, and <b>promotions</b> 📦  
3. Improve <b>marketing efficiency</b> and <b>ROI</b> 🎯  
4. Discover <b>high-potential regions</b> and <b>channels</b> for expansion 🗺️  

</span>
</small>

----
## ⚡ Product and Market Analyst Counter Questions to the Stakeholders :

To align analytics with real business impact, I framed the following counter-questions for stakeholders across **Marketing, Product, Sales, Production, and Growth Section**:

1. **Growth Objective:**<br>
     • Are we prioritizing **new customer acquisition** or **repeat purchases**, and what is the target uplift for the next **3–6 months**?<br>
     • Are we **optimizing primarily** for **short-term sales growth** or for **long-term customer retention and brand trus**t — and should our **strategy differ based** on that objective?
2. **Marketing ROI:** Which success metric matters most right now — **ROAS, CAC, cost per repeat customer, or contribution margin after marketing spend**?
4. **Product Strategy:** Which SKUs are strategic priorities (**value packs vs premium variants**), and are we optimizing for **volume growth** or **margin growth**?
5. **Sales & Channel Focus:** Which channel do we want to win (**Retail / D2C / Marketplace**), and which one delivers the best mix of **sales + repeat + margin**?





----

## 📌 ETL Pipeline - Data Ingestion flowchart
<img src="IMAGES/ETL%20flowchart.png" width="900"/>

----
## ✔ **Scope & Responsibilities:**
- Structured the business problem and defined key success metrics
- Identified and quantified drivers of underperformance and growth
- Designed and executed the pre–post impact evaluation framework
- Synthesized insights into clear, actionable business recommendations

  ----

## ❓ Leadership Questions Raised by Stakeholders |(Sales Head & CMO)

| Leadership Question |
|----------------------|
| 🔴 Where exactly are we underperforming across regions, and what are the primary drivers of that underperformance? |
| 🔴 Did the targeted discounts and festival campaigns deliver sustainable improvement, or only short-term uplift? |

# 🔁 My Counter-Question (As Marketing Analyst Perspective)
  🔶 Are we optimizing primarily for short-term sales growth or for long-term customer retention and brand trust — and should our strategy differ based on that objective?
----

<div style="font-size: 0.50em;">

## 📌 Business Summary

| WHAT | WHY |
|------|------|
| 🧠 **Business Problem** | Sales in Karnataka and Delhi were lagging behind other major states, indicating uneven regional performance. |
| 🔍 **Insight** | Lower conversion and seasonal engagement were observed compared to western and southern markets. |
| 🎯 **Action** | Targeted discounts and festival-led campaigns (Diwali & holiday offers) were rolled out in Karnataka and Delhi. |
| ⏱ **Timeline** | Campaigns were active for 8 months. |
| 📈 **Impact** | Delhi sales increased by 21% and Karnataka by 28% compared to the pre-campaign baseline. |
| 💡 **Outcome** | Sales distribution became more balanced, improving overall performance across regions. |

</div>

-----

<h2>📊 Before vs After Campaign Impact</h2>
<table>
  <tr>
    <td align="center"><b>Before Campaign</b></td>
    <td align="center"><b>After Campaign</b></td>
  </tr>
  <tr>
    <td><img src="IMAGES/11.JPG" width="800"/></td>
    <td><img src="IMAGES/22.JPG" width="800"/></td>
  </tr>
</table>

----




---
## **⚙️ End-to-End Analytics Workflow — (As per the Company Need and Stakeholder Ask)**

| *Step* | *Layer / Phase* | *Description* | *Tools & Techniques* |
|--------|------------------|---------------|----------------------|
| 1 | Data Ingestion | Ingested data from CRM, ERP, web events, APIs, and partners | APIs, Batch Jobs, Cloud Connectors |
| 2 | Bronze Layer | Stored raw data in the data lake | AWS S3 / Azure Data Lake |
| 3 | Data Quality & Validation | Applied schema validation, null checks, and deduplication | SQL (JOINs, GROUP BY, CTEs, Window Functions), Python |
| 4 | Silver Layer | Created cleaned and standardized analytical tables | SQL, Python |
| 5 | EDA & Statistical Analysis | Performed pattern discovery and hypothesis testing | SQL, Python (NumPy, Pandas), Statistics |
| 6 | Gold Layer | Built business-ready aggregates and KPIs | SQL, Power BI |
| 7 | Modeling / Segmentation | Built models and segments when needed | Python (scikit-learn), SQL |
| 8 | Visualization & Storytelling | Designed dashboards and narratives | Python (Matplotlib, Seaborn, Plotly), Power BI (DAX, Power Query) |
| 9 | Governance & Compliance | Ensured privacy, security, and access control | IAM, Data Policies |
|10 | Business Delivery | Reviewed insights with stakeholders and iterated | Presentations, Reviews |
|11 | Stakeholder Communication | Communicated insights clearly, aligned teams, and supported decision-making | Storytelling, Executive Summaries |
|12 | Decision & Impact Review | Measured outcomes, validated assumptions, and refined strategy | KPI Tracking, Post-Analysis |
|13 | Continuous Improvement | Incorporated feedback and continuously improved models and processes | Retrospectives, Iteration |


**Team Size:** 2  
**Author:** Priyanka De  
**Proflie** - [Priyanka De](https://www.linkedin.com/in/priyanka-de-711555289/)





## 📌 Slides Preview (Last 3)

<p float="left">
  <img src="IMAGES/22.JPG" width="32%" />
  <img src="IMAGES/33.png" width="32%" />
  <img src="IMAGES/ETL%20flowchart.png" width="32%" />
</p>


