# Real-Time Data Streaming and Automation Using AWS, Apache NiFi, and Snowflake

This repository contains all the resources and scripts needed to implement a real-time data streaming and automation pipeline. The project demonstrates how to extract, process, and load real-time data into Snowflake using AWS services, Apache NiFi, and Snowflake's native capabilities.

## Project Overview

This project showcases:
- **Real-Time Data Streaming**: Data extraction from a synthetic real-time data generator (using the Faker library) and storage in an Amazon S3 bucket via Apache NiFi.
- **Containerized Deployment**: Utilized Docker containers on an AWS EC2 instance for efficient management and deployment of Apache NiFi.
- **Data Loading Automation**: Configured Snowflake Snowpipe to continuously and automatically load data into Snowflake tables.
- **Data Workflow Automation**: Automated SQL scripts and workflows using Snowflake Tasks.
- **Slowly Changing Dimensions (SCD)**: Handled SCD to maintain historical accuracy and ensure data consistency in Snowflake tables.
