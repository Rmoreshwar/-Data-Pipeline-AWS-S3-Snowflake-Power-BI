# -Data-Pipeline-AWS-S3-Snowflake-Power-BI
![s3 aws glue snowflake](https://github.com/user-attachments/assets/0cb487f3-fc6a-4ad2-925d-f6f9312caca6)

# 🚀 End-to-End Data Pipeline: AWS S3 ➡️ Snowflake ➡️ Power BI  

This project demonstrates the creation of a comprehensive **data pipeline** that moves data from AWS S3 (staging area) to Snowflake (data warehouse) and finally to Power BI for business intelligence reporting.  

## 📋 Overview  
The pipeline is divided into two main parts:  
1. **AWS S3 to Snowflake Integration:** Setting up a staging area, configuring secure connections, and loading data into Snowflake.  
2. **Snowflake to Power BI:** Fetching data from Snowflake into Power BI for analysis and visualization.  

## 🛠️ Steps Involved  

### **1. AWS S3 to Snowflake Integration**  
**Screenshots: 1–10**  
- Created an **AWS S3 bucket** for staging CSV files.  
- Configured **IAM roles and policies** in AWS IAM for secure access.  
- Retrieved the **ARN** and S3 bucket location.  
- Integrated Snowflake with AWS by generating a **Snowflake ARN and External Stage ID**.  
- Updated S3 bucket roles and trust policies with the ARN and External Stage ID.  
- Defined a **file format** in Snowflake for CSV files.  
- Created an **external stage** in Snowflake.  
- Loaded data from S3 to Snowflake tables.  

### **2. Snowflake to Power BI Integration**  
**Screenshots: 11–19**  
- Connected Snowflake to Power BI for querying data.  
- Designed and developed **interactive dashboards** in Power BI to visualize data insights.  

## 💡 Key Features  
- **Staging Area:** Raw data uploaded and stored securely in AWS S3.  
- **Data Integration:** Secure and scalable connection between AWS and Snowflake.  
- **Data Warehouse:** Transformed and structured data stored in Snowflake.  
- **Business Intelligence:** Visualized data using Power BI for actionable insights.  

## 🚀 Tech Stack  
- **AWS S3**: Cloud storage for staging raw data.  
- **Snowflake**: Cloud data warehouse for data integration and transformation.  
- **Power BI**: Business intelligence tool for data visualization and reporting.  
- **AWS IAM**: Identity and access management for secure role and policy configurations.  

## 📂 Project Structure  
```plaintext  
/  
├── screenshots/                # Screenshots demonstrating key steps (1–19)  
├── scripts/                    # Any SQL or configuration scripts (if applicable)  
├── README.md                   # This README file  


📸 Screenshots
Screenshots are organized as follows:

1–10: AWS S3 to Snowflake integration.
11–19: Snowflake to Power BI reporting.
✨ How to Reproduce
Set up an AWS S3 bucket and upload your CSV files.
Configure IAM roles and policies for Snowflake integration.
Use Snowflake's external stage and SQL queries to load data.
Connect Power BI to Snowflake and create dashboards.
🤝 Acknowledgments
Special thanks to the open-source community and documentation that made this project possible.

📝 License
This project is licensed under the MIT License.
