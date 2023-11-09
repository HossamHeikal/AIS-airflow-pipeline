End-to-End Automated Data Pipeline: From Data Acquisition to Visualization with Dockerized Spark, HDFS, and Airflow
![image](https://github.com/HossamHeikal/AIS-airflow-pipeline/assets/58578405/b4b000b5-0b52-4613-b044-03aefa7a2560)
Project Objective
This project aims to develop a system that automates the entire data workflow, from downloading and processing to preparing it for visualization.

About the Project
The system focuses on extracting and leveraging Automatic Identification System (AIS) data to analyze and visualize maritime traffic patterns.

AIS Data
AIS is a navigation safety communication system that allows ships to exchange a variety of vessel information, including identification, location, and vessel specifics.

Key Components
Docker: Ensures consistent setup across different environments.
Apache Spark: Manages large-scale data processing.
HDFS (Hadoop Distributed File System): Stores the datasets.
PostgreSQL: Database for storing processed data.
Metabase: Tool for data visualization.
Airflow: Automates and schedules tasks.
Workflow Overview
Setup: Initialize the environment using Docker to integrate Spark, Hadoop, PostgreSQL, and Metabase.
Data Collection and Storage: Automate the downloading of AIS data and store it in HDFS.
Task Automation: Utilize Airflow to manage the daily workflow of data download and processing.
Data Transformation: Clean the collected data and analyze for insights, such as popular shipping destinations.
Project Outcome
The system is designed to autonomously manage the data pipeline, ensuring the data is ready for analytical review and visualization on a daily basis.

Recommendations for Users
Implement error handling mechanisms to enhance operational stability.
Integrate processed results with PostgreSQL for advanced visualization capabilities.
Perform regular checks to maintain system health and performance.
Feel free to contribute to this project by submitting pull requests or opening issues for any bugs or enhancements.
