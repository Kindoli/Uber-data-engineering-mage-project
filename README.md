# Uber Data Analytics | Modern Data Engineering GCP Project
## Introduction
In this Uber Data Analytics project, I am leveraging modern data engineering tools like mage.ai, BigQuery, Looker Studio, and Cloud Storage on Google Cloud Platform (GCP). The project involves designing a comprehensive data pipeline and analytics dashboard to extract, transform, and visualize key insights from Uber's extensive datasets.

## Architecture Diagram
![Project Architecture](architecture.jpg)

## Technology used
- Programming Language - Python
- Scripting Language - SQL
- Google Cloug Platform
  - BigQuery
  - Cloud Storage
  - Looker Studio
  - Compute Instance
- Mage.AI ( A modern data pipeline tool)

**Modern data pipeline tool: https://www.mage.ai/**

## Data set used
The Uber dataset provides a comprehensive view of ride-sharing activity, including details such as trip durations, distances, pickup and drop-off locations, and timestamps. This data is crucial for analyzing trends in user behavior, optimizing routes, and improving overall service efficiency.

**Here is the data set used:https://github.com/Kindoli/Uber-data-engineering-mage-project/blob/main/data/uber_data.csv**

### More infomation about the dataset used:

1. Original dataset: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

2. Data Dictionary – Yellow Taxi Trip Records:https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data model
![Project Data Model](data_model.jpeg)

## Scripts used

1. [Extraction Python File](mage-files/extract.py)
2. [Load Python File](mage-files/load.py)
3. [Transform Python File](mage-files/transform.py)
   

