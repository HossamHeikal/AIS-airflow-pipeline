End-to-End Automated Data Pipeline: From Data Acquisition to Visualization with Dockerized Spark, HDFS, and Airflow
![image](https://github.com/HossamHeikal/AIS-airflow-pipeline/assets/58578405/b4b000b5-0b52-4613-b044-03aefa7a2560)
Objective: Develop an automated system for downloading, processing, and visualizing data.

Background: The project uses AIS data to analyze and visualize maritime traffic.

AIS Data: A safety system that shares ship details electronically, including identification, location, and other vessel specifics.

Key Components:

Docker for consistent environment setup.
Apache Spark for processing large data sets.
HDFS for data storage.
PostgreSQL for processed data storage.
Metabase for data visualization.
Airflow for task scheduling and automation.
Process:

Set up the environment using Docker with necessary tools.
Automate data download and storage in HDFS.
Schedule data handling tasks with Airflow.
Transform data for analysis like identifying popular ship destinations.
Outcome: Facilitates daily data management and preparation for visual analysis.

Suggestions:

Implement error-handling for reliability.
Integrate results with PostgreSQL for enhanced visualization.
Conduct regular system health checks.
