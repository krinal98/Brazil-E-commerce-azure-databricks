# Brazil-E-commerce-azure-databricks
In this project, I built a complete end-to-end data pipeline and analytics solution using Microsoft Azure, with the support of Databricks for data processing and Power BI for data visualization. The project utilizes the Brazilian E-Commerce Public Dataset by Olist, and focuses on building a scalable, relational data model for advanced analysis and insights.
![image](https://github.com/user-attachments/assets/1d8ac1f2-8046-49d7-8fb7-47a183e7a365)

 Tools & Components Used
Azure Data Factory
Used to ingest raw files (available in this repository) and move them into a staging area within Azure Data Lake Gen2.

Azure Data Lake Gen2
Acts as the cloud storage layer, with separate zones for:

Raw data (initial landing zone)

Transformed data (ready for loading into Synapse)

Azure Databricks
Responsible for data cleaning and exploratory data analysis (EDA). Databricks was used to enforce schema consistency and prepare the data for loading into a structured database model.

Azure Synapse Analytics
A powerful analytics service used to store the relational data warehouse model, run SQL queries, and support data modeling for reporting.

Power BI
Final dashboards were built using Power BI, providing stakeholders with easy-to-understand visual insights from the cleaned and modeled data.
![image](https://github.com/user-attachments/assets/5547ac43-819c-4cf1-b8b5-a1870157c078)

🔄 ETL Process Overview
Following a classic ETL (Extract, Transform, Load) approach:

Extract:
Raw data files were extracted using Azure Data Factory and stored in the staging layer of Data Lake Gen2.

Transform:
Azure Databricks was used to clean the data, explore relationships, and apply the required transformations. This step ensured that the data met the structure and schema expectations of Synapse.

Load:
The transformed data was then loaded into Azure Synapse, where it was organized into a relational model for querying and reporting.

Visualize:
The final step involved using Power BI to connect to Synapse and build interactive dashboards for business insights.
![image](https://github.com/user-attachments/assets/da91f397-451b-4fd8-8cf7-33e9ad0db314)
![image](https://github.com/user-attachments/assets/2b2ac383-bce1-4d89-aa22-f4bec8bde1f6)
![image](https://github.com/user-attachments/assets/1cb75ddd-c9c9-4f7c-b1dd-ac832e41e674)
![image](https://github.com/user-attachments/assets/5d073b1a-c7b0-4cd5-bd7e-15e857cd3288)

Load Tables & Start Building Dashboards
Once connected, you can select the tables or views you want to work with. Power BI will load the data into its model, and you can start creating interactive reports and dashboards.
![image](https://github.com/user-attachments/assets/ce3322b8-cd75-4f25-a12a-6b0d945e0c87)

