# EdTech Funnel & Growth Analysis (Excel & Power BI)

## Project Overview 
This project analyzes student acquisition and conversion behavior for an EdTech platform using Excel and Power BI. The focus is on understanding how users move through the funnel from website visits to applications and approvals.

The analysis identifies key drop-off points, evaluates traffic source effectiveness, and highlights top-performing countries and demographics.

The goal of this project is to help organizations:
- Improve conversion rates across the funnel 
- Identify high-performing acquisition channels 
- Understand user behavior and demographics 
- Optimize growth and marketing strategies 

---

## Problem Statement 
Many EdTech platforms attract large numbers of website visitors, but only a small percentage convert into applicants or enrolled users.

This project answers the following questions:
- What is the conversion rate from visitors to applications? 
- What percentage of applications get approved? 
- Which countries generate the most applications? 
- Which traffic sources drive the most users? 
- Where do users drop off in the funnel? 

---

## Tools Used 
- Excel – Data cleaning, preparation, and exploratory analysis 
- Power BI – Data modeling, DAX measures, and dashboard development 

---

## Dataset 
The dataset is a simulated but realistic EdTech dataset representing student behavior.

Main tables:
- Students – demographic details (country, age group, device type) 
- Website_Visits – user traffic and acquisition channels 
- Applications – application status and approval tracking 

Key fields:
- student_id 
- visit_id 
- traffic_source 
- application_status 
- application_date 

---

## Key Analysis Steps 

### 1. Data Cleaning (Excel) 
- Removed duplicate records from website visits 
- Handled missing values by assigning "Unknown" or logical defaults 
- Ensured proper date formatting 

---

### 2. Exploratory Data Analysis 
- Calculated total visits, applications, and approvals 
- Analyzed traffic distribution by source 
- Evaluated application trends over time 

---

### 3. Data Modeling (Power BI) 
- Built relationships between Students, Website_Visits, and Applications 
- Created a star schema with Students as the central dimension table 

---

### 4. DAX Measures 
Key metrics were created using DAX:
- Total Visits 
- Total Applications 
- Approved Applications 
- Conversion Rate (Visitors → Applications) 
- Approval Rate 

---

### 5. Funnel Analysis 
A funnel model was built to track user progression:

Website Visitors → Applications → Approved Members 

This helps identify drop-off points in the acquisition process.

---

## Dashboard Metrics 
- Total Website Visitors 
- Total Applications 
- Conversion Rate 
- Approval Rate 

---

## Dashboard Insights 

Key insights from the analysis:

- Only ~30% of website visitors convert into applications, indicating a significant drop-off at the top of the funnel. 
- Approximately 58% of applications are approved, suggesting a moderate selection process. 
- Traffic is evenly distributed across channels such as Email, WhatsApp, Instagram, and Referral. 
- Brazil and India are the top-performing countries in terms of applications. 

---

## Business Recommendations 

Based on the analysis:

- Optimize landing pages and CTAs to improve visitor-to-application conversion 
- Focus marketing efforts on high-performing countries (Brazil, India) 
- Invest more in top-performing traffic channels 
- Improve user engagement strategies to reduce funnel drop-offs 

---

## Project Outcome 

This project demonstrates how funnel analytics can be used to understand user behavior and improve growth performance.

The dashboard provides a clear view of:
- User acquisition 
- Conversion performance 
- Demographic trends 

It enables data-driven decision-making for marketing and product teams.

----
