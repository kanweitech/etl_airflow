# Airflow Tutorial
This tutorial demonstrates how to use Apache Airflow for workflow orchestration.

# Objective
The objective of the project is to demonstrate how to use Apache Airflow to orchestrate data pipeline. In this project, ETL workflow will be orchestrated by Apache Airflow.

# Problem Statement
Extract data from [Power Grid Company of Bangladesh](https://pgcb.gov.bd/site/page/0dd38e19-7c70-4582-95ba-078fccb609a8/-). Daily reports from the power generation companies are uploaded daily on the webpage. We will extract and read the report from the webpage, transform the data and load it into local database.

# Requirements and Constriants
In first run, read only the first page
Extract and read reports, transform the data and load it into a database
In subsequent run, perform ETL only for the newly added reports from the first page.
