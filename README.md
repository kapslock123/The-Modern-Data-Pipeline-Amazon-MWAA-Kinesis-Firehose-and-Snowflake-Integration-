
# Modern Data Pipeline: Streaming with Amazon Kinesis Firehose, Orchestration with Amazon MWAA, and Analytics with Snowflake

## Description

This project demonstrates how to create a robust and scalable ELT (Extract, Load, Transform) data pipeline using Amazon Managed Workflow for Apache Airflow (MWAA), Amazon Kinesis Firehose, and Snowflake. The pipeline automates the flow of data from an Amazon EC2 instance to a Snowflake database, orchestrated by Apache Airflow.

## Architecture Diagram

Please refer to the 'architecture diagram.pdf' file in the project repository for a visual representation of the data pipeline architecture.

## Prerequisites

- AWS Account
- Snowflake Account
- Python 3.6 or higher

## Installation Steps

1. Set up an Amazon EC2 instance with a Kinesis agent for emitting data.
2. Configure Amazon Kinesis Firehose to send data to an Amazon S3 bucket.
3. Set up an Amazon MWAA environment and upload the necessary DAG files.
4. Configure Snowflake for processing and transforming the data.
5. Update the necessary configurations and credentials in the Airflow DAG script.

## Usage Example

1. Trigger the Airflow DAG from the Amazon MWAA console.
2. Monitor the DAG execution progress in the Airflow UI.
3. Verify the processed data in the Snowflake database and S3 processed bucket.
<img width="1046" alt="image" src="https://github.com/kapslock123/The-Modern-Data-Pipeline-Amazon-MWAA-Kinesis-Firehose-and-Snowflake-Integration-/assets/56737638/51e26808-2b2b-4476-ad82-288f6496f3c3">
