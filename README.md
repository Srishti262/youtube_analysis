### Project Overview

The project aims to securely manage, streamline, and analyze structured and semi-structured YouTube video data based on categories and trending metrics.

### Project Goals

1. **Data Ingestion**: Develop a mechanism to ingest data from various sources.
2. **ETL System**: Transform raw data into the proper format.
3. **Data Lake**: Establish a centralized repository to store data from multiple sources.
4. **Scalability**: Ensure the system scales efficiently with increasing data size.
5. **Cloud Integration**: Utilize AWS for processing vast amounts of data.
6. **Reporting**: Create a dashboard for querying and obtaining insights from the data.

### Services Utilized

1. **Amazon S3**: Object storage service offering scalability, data availability, security, and performance.
2. **AWS IAM**: Identity and access management for secure management of AWS services and resources.
3. **AWS Glue**: Serverless data integration service for discovering, preparing, and combining data for analytics and ML.
4. **AWS Lambda**: Computing service for running code without managing servers.
5. **AWS Athena**: Interactive query service for S3, eliminating the need to load data as it stays in S3.

### Dataset

The Kaggle dataset comprises CSV files containing statistics on daily popular YouTube videos across several months. Each region has its own file containing data on up to 200 trending videos published daily. Data includes video title, channel title, publication time, tags, views, likes, dislikes, description, comment count, and a category_id field specific to each region.
