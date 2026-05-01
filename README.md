# LA 311 Service Request Analysis

## 📊 Overview

This project analyzes public service request data from Los Angeles to evaluate service demand and response efficiency.

## 🎯 Objectives

* Analyze trends in service request volume over time
* Identify the most common types of service requests
* Evaluate response times to measure service efficiency

## 🧼 Data Cleaning

* Standardized column names and formats
* Removed duplicate records
* Converted date fields to datetime format
* Created a response time metric (closed_date - created_date)
* Handled missing and invalid values

## 📈 Analysis & Insights

* Service requests show increasing demand over time
* A small number of request types account for most volume
* Response times vary significantly across request types, indicating potential inefficiencies

## 🗺️ Dashboard

The Tableau dashboard includes:

* Requests over time (trend analysis)
* Top request types (demand analysis)
* Average response time by request type (performance analysis)
* Geographic distribution of service requests
#### Dashboard preview
<img width="2559" height="1440" alt="Screenshot 2026-05-01 153116" src="https://github.com/user-attachments/assets/7fab5171-8205-44bc-8fef-204b568866d4" />

## 🛠️ Tools Used

* Python (Pandas)
* SQL
* Tableau

## 🔍 Key Insights

* **Bulky item pickup requests dominate overall volume**, indicating high demand for waste-related services across the city.

* **Response times vary significantly by request type**, with some categories taking substantially longer to resolve than others.

* **Single streetlight issues, while relatively low in volume (~4,000 requests), have very high average response times (~85 days)**, suggesting potential inefficiencies or resource constraints in that service area.

* **Service request volume shows consistent activity over time**, highlighting ongoing demand for city services

## Data
Due to the file size limitations, I have provided a sample of the data I used. For the full dataset please go to:
https://data.lacity.org/City-Infrastructure-Service-Requests/MyLA311-Service-Request-Data-2025/h73f-gn57/about_data

## For full interactive dashboard please go here: 
https://public.tableau.com/app/profile/sydney.jue/viz/311_service_dash/LA311ServiceRequestAnalysis
