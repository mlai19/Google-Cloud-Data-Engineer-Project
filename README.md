# Google-Cloud-Data-Engineer-Project

## Project Overview  
**Project Title**: Automated Sales Data Pipeline on Google Cloud  
**Database**: sales_db [Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data)


<img width="601" height="337" alt="Screenshot 2025-09-21 at 11 31 22 PM" src="https://github.com/user-attachments/assets/2de58376-c9be-49ac-9546-359707325e3d" />



The goal of this project was to build a fully automated data pipeline that ingests sales data from multiple regions (USA, UK, India), processes it in the cloud, and enables real-time reporting.
<br>

****Architecture****
---

<img width="1107" height="402" alt="Screenshot 2025-09-22 at 11 16 44 AM" src="https://github.com/user-attachments/assets/2aed9153-67db-48e3-b20b-6100c471b1e0" />



****Process****
---

**1. Data Upload Portal**
- Designed a Python Flask web portal for shop managers to upload sales files (CSV/Excel)
- Built feedback mechanisms to confirm successful or failed uploads

**2. Cloud Storage And Processing**
- Configured a Google Cloud Storage (GCS) bucket as the staging layer for raw sales files
- Implemented Google Cloud Functions to trigger automatically on new file uploads
- Developed ETL logic to clean, transform, and load the processed data into BigQuery

**3. Data Warehouse And Reporting**
- Modeled sales data in BigQuery to support aggregation by region, product, and category
- Integrated BigQuery with Looker Studio to create dashboards showing KPIs like total sales, regional comparisons, and sales trends
- Added filtering and drill-down capabilities for flexible reporting (ex: by date, product category, geography)


****Conclusion****
---
This project not only demonstrates my ability to design and implement an end-to-end data pipeline on Google Cloud but also reflects how I think about scalability, automation, and real-world business needs. By combining ETL, cloud storage, and visualization, I was able to turn raw sales files into actionable insights that could directly support decision-making at a global scale.
