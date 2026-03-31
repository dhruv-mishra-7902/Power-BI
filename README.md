# 📊 Power BI Campaign Performance Dashboard

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow?style=for-the-badge&logo=powerbi)
![Data Analysis](https://img.shields.io/badge/Domain-Marketing%20Analytics-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge)

---

## 🚀 Project Overview
This project focuses on analyzing **global social media advertising campaigns** using Power BI.  
The goal is to transform raw data into **actionable insights** by building an **interactive dashboard**.

📁 **Datasets Used:**
- Users
- Ads
- Ad Events (Sample)
- Campaigns

---

## 🎯 Objectives

✔ Analyze campaign performance  
✔ Understand user behavior patterns  
✔ Identify high-performing audience segments  
✔ Compare ad performance across platforms  
✔ Build an interactive Power BI dashboard  

---

## 📊 Dashboard Features

### 🔹 KPI Metrics
- 📌 Total Impressions  
- 📌 Total Clicks  
- 📌 CTR (Click Through Rate)  
- 📌 Total Conversions  

---

### 📈 Data Visualizations

#### 1️⃣ User Activity Analysis
- 📊 Bar Chart → Users by Day of Week  
- 🥧 Pie Chart → Users by Time of Day  

#### 2️⃣ Time-Based Analysis
- 📅 Impressions & Clicks by Day  
- ⏰ CTR by Time of Day  

#### 3️⃣ Audience Segmentation
- Matrix: Gender × Age Group  
- Metrics:
  - Impressions  
  - Clicks  
  - CTR  
  - Conversions  

#### 4️⃣ Ad Performance Analysis
- Platform Comparison: Facebook vs Instagram  
- Ad Types:
  - Video  
  - Image  
  - Carousel  
  - Stories  

---

## 🧠 Data Modeling

Relationships created between datasets:

- 🔗 `ad_events → users`
- 🔗 `ad_events → ads`
- 🔗 `ads → campaigns`

Ensured proper **primary & foreign key mapping** for accurate insights.

---

## ⚙️ DAX Calculations

### 📌 Event Classification
Created a calculated column:
- Impression  
- Click  
- Engagement  
- Conversion  

---

### 📌 Key Measures

```DAX
Total Impressions = COUNTROWS(FILTER(ad_events, ad_events[event] = "Impression"))

Total Clicks = COUNTROWS(FILTER(ad_events, ad_events[event] = "Click"))

CTR = DIVIDE([Total Clicks], [Total Impressions])

Total Engagements = COUNTROWS(FILTER(ad_events, ad_events[event] = "Engagement"))

Total Conversions = COUNTROWS(FILTER(ad_events, ad_events[event] = "Conversion"))
```

## 🎛️ Dashboard Design

✔ 4 KPI Cards  
✔ 2 Interactive Charts  
✔ 1 Dynamic Filter (Slicer)  

---

## 💡 Learning Outcomes

📊 Built interactive dashboards using Power BI  
🔄 Learned data modeling & relationships  
🧮 Developed DAX calculation skills  
📈 Performed marketing campaign analysis  
🎯 Gained insights into user behavior  

---

## 🛠️ Tools Used

- Power BI  
- Power Query  
- DAX  
- Excel / CSV  

---

## 📌 How to Use

1. Download the `.pbix` file  
2. Open in **Power BI Desktop**  
3. Explore visuals & filters  
4. Analyze insights interactively  

---

## 🔗 Connect With Me

💼 LinkedIn: [Dhruv Mishra](https://www.linkedin.com/in/dhruv-mishra-131b35337/) 

📧 Email: [Mail Us](mishradhruv9098@gmail.com)
