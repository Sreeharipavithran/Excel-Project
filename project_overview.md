# 📊 Project Overview: Airline Customer Satisfaction Analysis

---

## 🧠 Business Context

In the highly competitive aviation industry, customer satisfaction is a key driver of customer retention, brand loyalty, and revenue growth. Airlines must continuously monitor passenger experience across multiple touchpoints such as booking, onboard services, and post-travel interactions.

This project focuses on analyzing customer satisfaction data from an airline (Invistico) to identify:
- Key drivers of passenger satisfaction
- Service areas impacting customer experience
- Behavioral patterns across different customer segments

The goal is to enable **data-driven decision-making** for improving service quality and optimizing operational strategies.

---

## 🎯 Business Objectives

- Measure overall customer satisfaction levels
- Identify factors influencing satisfaction (service quality, travel class, demographics)
- Segment customers based on behavior and preferences
- Analyze service performance across multiple dimensions
- Provide actionable insights for improving customer experience

---

## 📂 Dataset Overview

The dataset consists of ~120,000+ airline passenger records with the following attributes:

### 👤 Customer Information
- Gender (Male / Female)
- Age (segmented into groups: Teen, Adult, Middle-aged, Old-aged)

### ✈️ Travel Details
- Travel Class (Business, Eco, Eco Plus)
- Type of Travel (Business / Personal)
- Flight Distance (categorized ranges)

### 😊 Satisfaction Metrics
- Satisfaction Level (Satisfied / Dissatisfied)

### ⭐ Service Ratings (1–5 scale)
- Seat Comfort
- Food & Drinks
- WiFi Service
- On-board Service
- Baggage Handling

---

## 🛠️ Data Processing & Preparation

- Cleaned missing and inconsistent values
- Standardized categorical fields (e.g., satisfaction labels)
- Created derived fields such as:
  - Age groups
  - Flight distance categories
- Built pivot tables to aggregate:
  - Passenger counts
  - Satisfaction distribution
  - Service rating trends

---

## 📊 Analytical Approach

The analysis follows a structured approach:

### 1. Descriptive Analysis
- Total passengers and demographic distribution
- Gender split and travel class distribution

### 2. Segmentation Analysis
- Satisfaction by:
  - Gender
  - Age groups
  - Travel class

### 3. Behavioral Analysis
- Satisfaction trends across flight distance
- Travel purpose vs satisfaction patterns

### 4. Service Quality Analysis
- Impact of service ratings on satisfaction:
  - Seat comfort
  - Food & Drinks
  - WiFi service
  - Baggage handling

### 5. Comparative Analysis
- Satisfied vs Dissatisfied customers across all dimensions

---

## 📈 Key Insights

### 🎯 Overall Satisfaction
- Approximately **55% of passengers are satisfied**, while **45% are dissatisfied**, indicating significant room for improvement.

### 💼 Travel Class Impact
- **Business class passengers show significantly higher satisfaction**
- Economy passengers contribute more to dissatisfaction → key improvement area

### 👥 Demographic Trends
- Certain age groups (middle-aged passengers) dominate the dataset
- Satisfaction patterns vary slightly across age groups but are strongly influenced by service quality

### ✈️ Flight Distance Insights
- Satisfaction varies across flight distance categories
- Medium to long-distance flights show stronger sensitivity to service quality

### ⭐ Service Quality Drivers (CRITICAL INSIGHT)
- Higher ratings in:
  - **Seat Comfort**
  - **WiFi Service**
  - **Food & Drinks**
  → Directly correlate with higher satisfaction levels

- Poor service ratings strongly align with dissatisfied customers

### 📦 Baggage Handling & Onboarding
- These operational services significantly influence customer perception
- Improvements here can directly reduce dissatisfaction

---

## 🧩 Business Recommendations

Based on the analysis:

- Improve **economy class experience** (highest dissatisfaction segment)
- Invest in **WiFi and seat comfort enhancements**
- Focus on **service consistency across flight distances**
- Monitor and improve **baggage handling efficiency**
- Personalize services based on **customer segments**

---

## 🖥️ Dashboard Capabilities

The interactive Excel dashboard enables:
- Real-time filtering using slicers:
  - Gender
  - Travel class
  - Customer type
  - Satisfaction level
- Dynamic visualization of:
  - Satisfaction distribution
  - Service rating trends
  - Passenger segmentation
- Easy identification of performance gaps

---

## 🧱 Analytics Engineering Perspective

Although built in Excel, this project can be extended into a modern data stack:

- **Data Ingestion** → Snowflake
- **Transformation** → DBT models (Raw → Staging → Mart layers)
- **Data Quality** → DBT tests (validations, constraints)
- **Serving Layer** → BI tools (Tableau / Power BI)

This transformation would enable:
- Scalable data pipelines
- Automated data validation
- Production-ready analytics workflows

---

## 🚀 Future Enhancements

- Build a **predictive model** to forecast customer satisfaction
- Automate data pipeline using **Python + SQL**
- Convert dashboard into **Power BI / Tableau**
- Implement **real-time analytics pipeline**
- Integrate **AI-based anomaly detection for service metrics**

---

## 📌 Conclusion

This project demonstrates how structured data analysis and visualization can uncover actionable insights into customer behavior and service performance.

By leveraging these insights, airlines can:
- Enhance customer experience
- Optimize service delivery
- Drive higher customer satisfaction and retention
