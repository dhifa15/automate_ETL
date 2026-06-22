# Automate ETL Pipeline For Food Delivery Data

📌 Project Overview

This project is an Automated ETL Pipeline built using a food delivery transaction dataset inspired by Foodpanda operations.
The goal is to transform raw, inconsistent CSV data into clean, structured, and validated data ready for analytics and storage in MongoDB.

The pipeline focuses on improving data quality, consistency, and automation for better business decision-making.

📁 Dataset

- Data Source: https://www.kaggle.com/datasets/ayeshaimran1619/foodpanda-data-analysis

🎯 Objectives
- Extract raw transactional data from CSV files
- Clean and transform inconsistent data formats
- Apply automated data validation rules
- Load processed data into MongoDB
- Automate the ETL workflow with scheduling

🧹 Data Validation Rules

To ensure data quality, several validation checks were implemented:

- Ensure order_id is unique
- Validate correct data types (e.g., price as float)
- Ensure rating values are between 1 and 5
- Validate customer_id format (must start with "C")
- Restrict categorical values (e.g., Active / Inactive, Delivered / Delayed / Cancelled)
- Ensure schema consistency

🛠️ Tech Stack
- Python 🐍
- Pandas
- Great Expectations (Data Validation)
- MongoDB
- ETL Automation (Scheduling)

🔄 ETL Workflow
- Extract → Load raw CSV data
- Transform → Clean data, fix types, rename columns
- Validate → Apply data quality rules
- Load → Store cleaned data into MongoDB
- Schedule → Automated pipeline execution

⏱️ Automation

The pipeline is scheduled to run automatically on a defined interval to ensure updated and consistent data processing.

Presentation: https://canva.link/kuejww2ravqseva

---
**Hazna Dhifa Putri Ardeva**  
Data Analyst Enthusiast | Hactiv8 Bootcamp Student  
🔗 [LinkedIn](https://linkedin.com/in/haznadhifa) | 📧 [Email](mailto:haznadifa123@gmail.com)
