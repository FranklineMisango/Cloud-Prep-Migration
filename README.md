1[](image.png)

This project is the second part of the IoT Data Migration series using AWS CDK. The first
project uses an AWS IoT device Simulator to replicate an On-Premise Data Center
infrastructure by ingesting real-time IoT-based data. The services used in the first project were
AWS CDK (CloudFormation), AWS IoT core, Kinesis Firehose, Lambda, AWS S3, EC2,
MariaDB, and AWS Secrets Manager. In this project, we will migrate and analyze the data,
schemas, tables, and functions from the MySQL server to “AWS Cloud Premise” using
DMS, RDS, AWS Glue, AWS Timestream, AWS S3, and QuickSight. Finally, the third project
will act as a mini-course to dive deep into the concepts and workings of
Infrastructure-as-a-Code (IaC) using AWS CDK (Cloud Development Kit).

## Data Description
Using the Device Simulator, we will simulate and deal with the geoLocation data of multiple
devices parallelly within the vicinity of a popular entertainment complex in London called The O2
Arena.

## Tech Stack:
* Language: Python, SQL
* Services: AWS Glue, AWS SCT, AWS DMS, AWS Timestream, AWS S3, AWS Secrets
Manager, AWS RDS, AWS Athena, Aurora Postgres, QuickSight, AWS SSM, Apache Spark