# DEZ-capstone-project

## Dataset
NYC 311 Customer Service Requests Analysis
https://www.kaggle.com/datasets/shubhammore12/nyc-311-customer-service-requests-analysis

## Project summary

This project builds an end-to-end batch data pipeline for NYC 311 service requests. The pipeline ingests raw complaint data, stores it in a cloud data lake, loads it into BigQuery, transforms it into analytics-ready tables, and visualizes complaint patterns in a dashboard.

## Key questions
I want to focus on answering these questions: 
- What complaint types are reported most frequently?
- How do complaint volumes change over time?
- Which boroughs generate the most service requests?

Focus on columns:
Unique Key
Created Date
Closed Date
Agency
Complaint Type
Borough
Status



### Raw table

raw_311_requests

### Cleaned table

stg_311_requests

### Aggregate tables

complaints_by_type
complaints_over_time
complaints_by_borough