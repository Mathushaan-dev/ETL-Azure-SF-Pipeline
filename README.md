# 🚀 Azure Data Factory &amp; Snowflake ETL Pipeline

# 📊 Project Overview

This project is an ETL (Extract, Transform, Load) pipeline built using Azure Data Factory and Snowflake. The goal is to extract data from an external API, transform it into a usable format, and load it into Snowflake for further analysis.

# 🌟 Key Features

Data Extraction: Collect real-time data from APIs (e.g., OpenWeather).

Data Transformation: Clean and optimize data using Python.

Data Loading: Store transformed data in Snowflake via Azure Blob Storage.

Automation: Schedule and monitor data pipelines using Azure Data Factory.

# 🏗️ Project Architecture

Extract: Python scripts fetch data from APIs (e.g., weather data).

Transform: Data is cleaned and structured using Pandas.

Load: Data is stored in Azure Blob Storage and loaded into Snowflake.

Automate: Azure Data Factory triggers pipelines for regular ETL jobs.

# 📚 Tech Stack

Azure Data Factory: ETL orchestration and scheduling

Snowflake: Cloud-based data warehouse

Azure Blob Storage: Temporary data staging

Python: Data extraction and transformation

requests, pandas, snowflake-connector-python

SQL: Data querying and analysis

Azure CLI: Manage Azure resources

SnowSQL: Interface to query Snowflake

GitHub: Version control

