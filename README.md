# building a data ingestion and processing pipeline on GCP with real-time streaming and batch loads
### Data-Ingestion-pipeline-using-GCP-with-SQL-and-Google-Cloud-Dataflow
Data Ingestion project using GCP with SQL and Google Cloud Dataflow 


![image](https://github.com/DhruvAjmeri/Data-Ingestion-project-using-GCP-with-SQL-and-Google-Cloud-Dataflow/assets/65453606/981d5a99-d234-473d-9c26-b0c7d8fcd8cc)

### Overview
This project demonstrates the construction of a robust data processing pipeline on Google Cloud Platform (GCP) utilizing Apache Beam, Dataflow, and BigQuery, with a focus on the Yelp dataset. The pipeline encompasses data ingestion, transformation, and visualization, offering insights into real-time streaming and batch processing.

### Learning Objectives
**Google Cloud Storage:** Understand the project and its integration with Google Cloud Storage.
**Architecture Visualization:** Visualize the complete system architecture.
**Google Cloud SDK:** Introduction to Google Cloud SDK and connecting it to the service account.
**Yelp Dataset:** Explore Yelp dataset, utilizing both JSON stream and JSON file.
**PubSub:** Create and use PubSub topics for data ingestion.
**Apache Beam:** Understand and use Apache Beam for executing data processing pipelines.
**Dataflow:** Create and comprehend Dataflow stream and batch jobs.
**Cloud Composer/Airflow:** Understand and use Cloud Composer for orchestrating batch workloads.
**BigQuery:** Integrate Google Cloud Dataflow and Google BigQuery as a data warehouse.
**Data Studio:** Visualize live stream results using Google Data Studio.

### Project Description
The project focuses on building a data ingestion and processing pipeline on GCP with real-time streaming and batch loads. The Yelp dataset is utilized for academic and research purposes. The agenda includes creating a service account, using Google Cloud SDK, connecting to GCP, downloading and connecting to the Yelp dataset, creating Google Cloud Bucket, understanding PubSub for data ingestion, utilizing Apache Beam for data processing, and integrating various components like Cloud Composer, Dataflow, BigQuery, and Data Studio.

### Dataset Usage
The Yelp dataset in JSON format is used in two ways:

#### Yelp Dataset File:
JSON file is connected to Cloud Storage using Cloud SDK.
Connected to Google Cloud Composer/Airflow for scheduling and orchestration.

#### Yelp Dataset Stream:
JSON streams are published to Google PubSub for real-time data ingestion.
Connected to Apache Beam for further processing.
