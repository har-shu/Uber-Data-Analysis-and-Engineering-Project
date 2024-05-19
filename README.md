# Uber-Data-Analysis-and-Engineering-Project


## Project Overview
This project involves analyzing Uber data and building a data engineering pipeline. The main tasks included creating fact and dimension tables using Lucidchart, processing data from CSV files with Jupyter Notebook and Pandas, setting up a data pipeline on Google Cloud Platform (GCP) using the ETL tool Maze, and performing data analysis in BigQuery. The final output was visualized using Looker Studio.


![architecture](https://github.com/har-shu/Uber-Data-Analysis-and-Engineering-Project/assets/71369996/abf04c9f-b808-437c-bb44-b0b2e9e2bee8)



## Project Components

### 1. Data Modeling
- **Lucidchart**: Designed the schema for the data warehouse including fact and dimension tables. The fact table includes trip-related information, while dimension tables include data such as drivers, vehicles, and locations.

- ![image](https://github.com/har-shu/Uber-Data-Analysis-and-Engineering-Project/assets/71369996/a33ee9f5-47a0-46a5-840e-622e61241fc5)


### 2. Data Processing
- **Jupyter Notebook and Pandas**: 
  - Loaded the Uber CSV data.
  - Cleaned and transformed the data.
  - Created the fact and dimension tables as per the schema designed in Lucidchart.

### 3. Google Cloud Platform (GCP) Setup
- **Google Cloud Storage**:
  - Created a bucket to store the Uber CSV files.
- **Google Compute Engine**:
  - Set up VM instances to perform ETL operations.
  - Configured the necessary APIs and services to facilitate the data pipeline.
  
### 4. ETL Pipeline
- **Maze ETL Tool**:
  - Utilized Maze to perform Extract, Transform, and Load (ETL) operations.
  - Extracted data from the CSV files stored in the Google Cloud Storage bucket.
  - Transformed the data according to the designed schema.
  - Loaded the data into BigQuery for analysis.

### 5. Data Analysis and Visualization
- **BigQuery**:
  - Performed SQL operations to analyze the data.
  - Created new tables with the required data for analysis.
- **Looker Studio**:
  - Built interactive dashboards to visualize the insights derived from the data.
  - The dashboards provide a comprehensive view of various metrics such as trip durations, distances, and driver performance.

### Project Link
- [Looker Studio Dashboard](https://lookerstudio.google.com/reporting/118d61d4-7aa0-4f65-9eec-6710dde361b7)

## Technologies Used
- **Lucidchart**: For data modeling.
- **Jupyter Notebook**: For data processing and transformation.
- **Pandas**: Python library for data manipulation.
- **Google Cloud Platform (GCP)**: For cloud storage, compute resources, and data warehousing.
  - **Google Cloud Storage**: For storing raw data files.
  - **Google Compute Engine**: For setting up virtual machines.
  - **BigQuery**: For data analysis and querying.
- **Maze ETL Tool**: For building and managing the ETL pipeline.
- **Looker Studio**: For creating data visualizations and dashboards.

## Steps to Reproduce the Project

1. **Data Modeling**:
   - Design the schema in Lucidchart, identifying the necessary fact and dimension tables.

2. **Data Processing**:
   - Load the Uber CSV data into Jupyter Notebook.
   - Clean and transform the data using Pandas.
   - Create the fact and dimension tables and save them as new CSV files if needed.

3. **GCP Setup**:
   - Create a Google Cloud Storage bucket and upload the CSV files.
   - Set up a Google Compute Engine VM instance to handle ETL tasks.

4. **ETL Pipeline**:
   - Use the Maze ETL tool to extract data from Google Cloud Storage.
   - Transform the data as per the designed schema.
   - Load the transformed data into BigQuery.

5. **Data Analysis and Visualization**:
   - Perform SQL operations in BigQuery to analyze the data.
   - Create additional tables and views as needed for detailed analysis.
   - Build interactive dashboards in Looker Studio to visualize the insights.

## Conclusion
This project showcases a comprehensive workflow from data modeling and processing to building a cloud-based ETL pipeline and visualizing the results. By leveraging the power of GCP and tools like Pandas, Maze, and Looker Studio, the project demonstrates how to effectively handle and analyze large datasets to derive actionable insights.

For more detailed visual insights, please visit the [Looker Studio Dashboard](https://lookerstudio.google.com/reporting/118d61d4-7aa0-4f65-9eec-6710dde361b7).
