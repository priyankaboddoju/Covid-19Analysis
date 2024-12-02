# Covid-19Analysis

[Presentation](https://youtu.be/CPEK-1heh3A)
# COVID-19 Data Analysis Pipeline

## Overview
This project involves the creation of a scalable data analysis pipeline for processing and visualizing COVID-19 trends using AWS cloud services. The pipeline is designed to handle large datasets efficiently and provide valuable insights into the pandemic's global progression.

## Objective
The goal of this project is to provide an automated and scalable solution for analyzing COVID-19 data, supporting decision-making processes for public health agencies and researchers.

## Technologies Used
- **AWS Services:** S3, Glue, Lambda, SageMaker
- **Programming Languages:** Python
- **Libraries & Frameworks:** Pandas, Matplotlib, Seaborn, Boto3
- **Data Sources:** Public COVID-19 datasets (e.g., John Hopkins University, World Health Organization)

## Features
1. **Data Collection & Storage**  
   - Data is collected from publicly available COVID-19 datasets and stored in AWS S3 buckets for easy access and future processing.

2. **ETL Pipeline**  
   - Utilized **AWS Glue** to perform the ETL (Extract, Transform, Load) processes. This automated pipeline cleans, structures, and aggregates the data, making it ready for analysis.

3. **Real-Time Analytics**  
   - Implemented **AWS Lambda** for real-time processing, allowing the pipeline to scale dynamically based on incoming data.

4. **Data Visualization**  
   - Used **Matplotlib** and **Seaborn** to create insightful visualizations, highlighting trends such as infection rates, recovery rates, and deaths across various regions.

5. **Scalability & Performance**  
   - Optimized the pipeline to handle large volumes of data, making it capable of processing future updates without performance degradation.

