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

# How to Run the Project
The project will run in Docker container. Therefore, **Docker** and **Docker Compose** must be installed on your workstation.

  1. Install [Docker](https://docs.docker.com/engine/install/) on your workstation.
  2. Install [Docker Compose](https://docs.docker.com/compose/install/) on your workstation.

If **Docker** and **Docker Compose** are installed follow the steps below:

  1. Download the project from [GitHub](https://github.com/kanweitech/etl_airflow): `git clone https://github.com/kanweitech/etl_airflow.git`
  2. Once downloaded, go to the project directory
  3. Open terminal or command prompt and enter `docker-compose up` or `docker-compose up -d`
  4. It may take few minutes for the containers to download and install the required dependencies. Once the container is up, open browser and go to `localhost:8080`
  5. User: `admin` and Password: `admin1234`
  6. To run it once, trigger the `pgcb_etl` by clicking the play button under the Actions column
  7. To run it continuously, Unpause the workflow left of **pgcb_etl**
  8. You can watch the log files
![image](https://github.com/kanweitech/etl_airflow/blob/main/static/Image.png)
`git status`

