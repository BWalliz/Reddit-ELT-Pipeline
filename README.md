# Reddit ELT Pipeline
## Architecture

![Reddit Architecture](https://github.com/BWalliz/Reddit-ELT-Pipeline/blob/main/images/reddit-architecture.png)

## Overview

The pipeline extracts data from the [/r/DataEngineering](https://www.reddit.com/r/dataengineering/) API and exports a csv file to S3.  The most recent file is ingested into Redshift and subsequently transformed with DBT.  Airflow was used for orchestration and hosted locally with docker-compose; The output is a PowerBI dashboard that is connected to Redshift.

## ELT

![ELT](https://github.com/BWalliz/Reddit-ELT-Pipeline/blob/main/images/workflow.png)

## Dashboard

![Dashboard](https://github.com/BWalliz/Reddit-ELT-Pipeline/blob/main/images/dashboard-1.png)

## Acknowledgement
[Data Engineering Zoom Camp](https://github.com/DataTalksClub/data-engineering-zoomcamp)
