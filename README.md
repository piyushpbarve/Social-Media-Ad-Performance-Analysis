# Social-Media-Ad-Performance-Analysis
A Power BI dashboard analyzing Meta ad performance across Facebook &amp; Instagram. Tracks impressions, clicks, engagements, conversions, demographics, geography, time trends, and budget insights. Built using event-level Meta datasets to optimize targeting, ROI, and campaign efficiency.

# 📊 Meta Ad Performance Analysis Dashboard

This project analyzes advertising performance across Facebook and Instagram using a complete event-level dataset. It tracks campaign reach, engagement, conversions, demographics, time trends, and budget utilization to provide deep insights into campaign effectiveness.  
(References: BRD, Domain Knowledge, Dashboard Insights)  


## 🚀 Project Overview
The Power BI dashboard provides a full-funnel analysis covering:

- **Impressions, Clicks, Shares, Comments, Purchases**  
- **CTR, Engagement Rate, Conversion Rate, Purchase Rate**  
- **Budget utilization & average spend per campaign**  
- **Demographic & geographic targeting insights**  
- **Hourly, weekly & monthly engagement trends**

The dashboard helps identify:
- The most effective ad formats  
- High-engagement audience segments  
- High-value countries  
- Funnel drop-offs and optimization areas  
:contentReference[oaicite:2]{index=2}


## 📂 Dataset Structure
Based on a star-schema model:

### **Fact Table**
- **ad_events** – impressions, clicks, shares, purchases, timestamps  
  (Foundation for all KPIs)  
  :contentReference[oaicite:3]{index=3}

### **Dimension Tables**
- **ads** – ad metadata (platform, type, targeting)  
- **campaigns** – budget, duration, strategy  
- **users** – gender, age group, location, interests  
:contentReference[oaicite:4]{index=4}


## 📈 Key Insights
From the dashboard analysis:

- **216K impressions** and **25.4K clicks**, leading to a strong **CTR of 11.76%**  
- **Engagement Rate: 13.56%**, showing strong resonance  
- **Purchases: 1.3K**, but **Purchase Rate only 0.61%** → funnel drop-off  
- **Top audience**: Females aged **18–30**, mainly from **India & Brazil**  
- **Best-performing formats**: **Video > Stories > Carousel/Image**  
- **Peak activity:** Afternoons & evenings  
:contentReference[oaicite:5]{index=5}


## 📊 Visuals Included
- Target Gender Donut Chart  
- Age Group Bar Chart  
- Country Map  
- Calendar Heat Map  
- Weekly Stacked Trend  
- Hourly Activity Area Chart  
- Ad Type Matrix  
:contentReference[oaicite:6]{index=6}


## 🛠 Tools & Technologies
- **Power BI**
- **DAX**
- **CSV/XLSX datasets (Meta Ads format)**
- **Star Schema Data Modeling**


## 🔍 Recommendations Based on Analysis
- Optimize the landing page to reduce funnel leakage  
- Increase budget allocation for **Video & Story ads**  
- Target young female audiences in **India & Brazil**  
- Run campaigns primarily in **afternoon & evening** slots  
:contentReference[oaicite:7]{index=7}


## 📁 Files Included
- BRD (Business Requirement Document)  
- Domain Knowledge Guide  
- Dashboard Insights  
- Power BI PBIX file  
- Raw datasets (ads, ad_events, campaigns, users)


## 📬 Author
**Piyush Barve**
Data Analyst skilled in SQL, Power BI, Python, ETL, and predictive analytics. Passionate about building dashboards, analyzing data, and solving real-world problems through analytics.
📧 Email: piyushbarve@outlook.com
🔗 GitHub: github.com/piyushpbarve
🔗 LinkedIn: linkedin.com/in/piyushbarve
