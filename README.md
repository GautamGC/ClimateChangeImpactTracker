# Climate Change Impact Tracker on GCP

A comprehensive, end-to-end **data engineering and analytics** solution on **Google Cloud Platform (GCP)** to track, analyze, and forecast long-term **climate change trends** using historical temperature data and machine learning.

## Project Overview

This project analyzes global climate data, identifies extreme weather patterns, and generates predictive forecasts using **BigQuery ML** with ARIMA_PLUS models. It leverages public datasets from NOAA and NASA GISS, showcasing cloud-native architecture, advanced SQL processing, and rich visualizations in **Looker Studio**.

## Architecture Diagram

![Architecture](./Gemini_Generated_Image_2n5eeu2n5eeu2n5e.png)

---

##  Key Features

- **Cloud-Native Infrastructure**: GCP project with proper billing/resource isolation.
- **Massive-Scale Climate Data**: Ingests NOAA and NASA datasets (petabyte-scale).
- **Advanced SQL Processing**: Cleansing, unit conversions, feature engineering.
- **Forecasting with BigQuery ML**: Time-series modeling using ARIMA_PLUS.
- **Interactive Dashboards**: Real-time data visualization in Looker Studio.

---

##  Data Pipeline Architecture

1. **Data Ingestion**:  
   - NOAA climate data from BigQuery Public Datasets  
   - NASA GISS temperature data from Cloud Storage

2. **Data Transformation**:  
   - SQL queries for cleaning, joining, and aggregating

3. **Machine Learning**:  
   - Forecasting with BigQuery ML’s `ARIMA_PLUS` model

4. **Visualization**:  
   - Looker Studio dashboards powered by BigQuery views

---

## 📊 Sample Visualizations

![Dashboard](./Screenshot%202025-08-01%20221444.png)

---

##  Technologies Used

- **Google Cloud Platform**
  - BigQuery
  - BigQuery ML
  - Cloud Storage
  - Looker Studio

- **Languages & Tools**
  - Standard SQL
  - BigQuery ML Syntax

---

## Datasets Used

- [NOAA GHCN/GSOD Climate Data](https://www.ncdc.noaa.gov/data-access)
- [NASA GISS Temperature Anomaly Data](https://data.giss.nasa.gov/gistemp/)

---

## Outcomes

- Built a scalable climate data pipeline in GCP.
- Transformed raw data into clean, analytical formats.
- Created a robust forecasting model using ARIMA_PLUS.
- Delivered an intuitive dashboard for public interpretation.

---

##  Setup & Usage

To replicate this project:

1. **Create a GCP Project**  
   - Enable BigQuery, BigQuery ML, and Cloud Storage APIs.

2. **Ingest Data**  
   - Use BigQuery Public Datasets for NOAA.  
   - Upload NASA data to a Cloud Storage bucket.

3. **Data Processing**  
   - Run SQL transformations in BigQuery.

4. **Model Training**  
   - Train ARIMA_PLUS models using BigQuery ML.

5. **Visualize**  
   - Connect Looker Studio to your BigQuery views.

---

