# Data Enthusiast

#### Technical Skills: Python, SQL, AWS, MySQL, Power BI, Machine Learning, Deep Learning, Big Data, Data Visualization, Linux, Django

## Education
- PG-Diploma in Big Data Analytics | Centre for Development of Advanced Computing, Mumbai, India (_August 2024_)
- Bachelor of Technology | Dr. Babasaheb Ambedkar Technological University, India (_September 2023_)

## Projects

### [Amazon Customer Sales Pipeline](https://github.com/Shubham9975/BigDataProject.git)

Analyzed **Amazon customer reviews** using **big data analytics** to extract **customer sentiments, product trends, and insights**. Built an **ETL pipeline** leveraging **AWS services**:
- **Data Storage**: Raw and processed data stored in **Amazon S3**.
- **Data Processing**: Used **AWS Glue & Apache Spark on EMR** to clean and transform data.
- **Querying & Metadata Management**: Enabled querying via **Amazon Athena & AWS Glue Data Catalog**.
- **Visualization**: Developed **Power BI dashboards** for sentiment analysis, trend identification, and product comparison.
- **Automation**: Implemented **GitHub Actions** for automatic ETL execution.

#### **Architecture Overview**
The **ETL pipeline** follows a structured approach using **AWS services** for **scalability, automation, and efficiency**.

1. **Data Ingestion (Amazon S3 - Data Lake)**
   - Stores raw customer review data for scalable and cost-effective storage.
2. **Data Cleaning (AWS Glue - ETL Processing)**
   - Removes duplicates, missing values, and inconsistencies.
3. **Data Transformation (Amazon EMR + Apache Spark)**
   - Processes and restructures the data into separate datasets for **Customers, Products, and Reviews**.
4. **Metadata Management (AWS Glue Crawler + Data Catalog)**
   - Automatically scans datasets and updates the **AWS Glue Data Catalog** for easy querying.
5. **Data Querying (Amazon Athena)**
   - Runs **serverless SQL queries** directly on structured S3 data.
6. **Data Visualization (Power BI)**
   - Connects to **Amazon Athena** for interactive dashboards that provide business insights.

This project enhances **data-driven decision-making** for product improvement and market strategy by extracting insights from large-scale customer reviews.

![Big Data Project Architecture](https://github.com/user-attachments/assets/e9df7e9b-ae3c-40d9-84dc-f97b0cd612de)

### [Boston House Price Prediction & Deployment](https://github.com/Shubham9975/End_To_End_ML_Project_deployment.git)

Developed a **Machine Learning model** to predict house prices in **Boston** using **Linear Regression** and deployed it using **Google Cloud Run**. Key highlights:
- **Preprocessing**: Cleaned and standardized the Boston House Pricing dataset.
- **Model Training**: Used Linear Regression and evaluated performance with **MAE, MSE, RMSE, and R² score**.
- **Deployment**: Containerized the model with **Docker** and deployed it using **Google Cloud Run** with **GitHub Actions**.

This project demonstrates expertise in **ML model development, cloud deployment, and automation** using modern tools.

### [Basic Recommendation Engine](https://github.com/Shubham9975/Basic-Recommendation-Engine-ML.git)

Developed a **Job Role Recommender** that suggests the **top three most similar job roles** based on skills. The system uses **Jaccard Similarity** to compare skill sets and rank job roles based on the highest similarity score. Key features include:
- **MultiLabelBinarizer** for binary skill encoding.
- **Jaccard Similarity Calculation** to measure skill overlap.
- **Fast Dictionary Lookup** for quick role retrieval.
- **Sorted Rankings** to ensure the top three job roles are recommended.

This approach ensures an **efficient and scalable recommendation engine** for job seekers based on skill sets.

### [Facility Booking Management Dashboard](https://github.com/Shubham9975/Facility_Bookings_Data_Analysis.git)

Developed an **interactive dashboard** to analyze facility booking trends, peak time slots, revenue analysis, and instructor demand. The goal was to **clean inconsistencies** in the dataset and extract meaningful insights for **optimized operations**.

- **Data Cleaning**: Managed missing values and inconsistencies in **Facility, Booking Type, Instructor Allocation, Price, and Duration**.
- **Key Insights**:
  - **Peak Booking Hours**: Most bookings occur between **14:00 - 15:00**.
  - **Day-wise Trends**: **Saturdays and Mondays** have the highest number of bookings.
  - **Revenue Contribution**: Bookings for **Facilities, Classes, and Birthday Parties** contribute equally to total revenue.
  - **Pending vs Confirmed**: **49%** of bookings are still pending confirmation.
  - **Data Discrepancies**: **Service Name, Facility, and Booking Type** contain overlapping but critical data.
- **Technologies Used**:
  - **Power BI** for visualization.
  - **Python (Pandas, NumPy)** for data cleaning.
  - **SQL** for data transformation and querying.

This project enhances **data-driven decision-making** by providing valuable insights into facility utilization, revenue trends, and operational efficiency.

![Dashboard Insights](https://github.com/Shubham9975/Facility_Bookings_Data_Analysis/blob/main/Booking%20Management%20Dashboard.gif?raw=true)
