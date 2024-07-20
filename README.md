# Awesome Data Activation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Data Activation resources, libraries, tools and applications.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing. Feel free to improve this list by [contributing](CONTRIBUTING.md)!

## Table of Contents

- [Introduction](#introduction)
- [ETL (Extract, Transform, Load)](#etl-extract-transform-load)
  - [Open Source ETL Tools](#open-source-etl-tools)
  - [Commercial ETL Platforms](#commercial-etl-platforms)
  - [ETL Best Practices](#etl-best-practices)
- [Reverse ETL (rETL)](#reverse-etl-retl)
  - [Open Source rETL Tools](#open-source-retl-tools)
  - [Commercial rETL Platforms](#commercial-retl-platforms)
  - [rETL Best Practices](#retl-best-practices)
- [Data Warehouses and Lakes](#data-warehouses-and-lakes)
  - [Cloud Data Warehouses](#cloud-data-warehouses)
  - [Data Lakes](#data-lakes)
  - [Data Lakehouses](#data-lakehouses)
- [Data Integration Patterns](#data-integration-patterns)
- [Data Governance and Quality](#data-governance-and-quality)
- [Real-time Data Activation](#real-time-data-activation)
- [Machine Learning for Data Activation](#machine-learning-for-data-activation)
- [Resources](#resources)
  - [Tutorials and Guides](#tutorials-and-guides)
  - [Books and Publications](#books-and-publications)
  - [Articles and Case Studies](#articles-and-case-studies)
  - [Conferences and Events](#conferences-and-events)
  - [Community Resources](#community-resources)
  - [Related Topics](#related-topics)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Data Activation involves the process of transforming data into insights by transferring it from storage systems to operational tools used for business processes and decision making. It includes ETL (Extract, Transform, Load) to transfer data into repositories and Reverse ETL to synchronize data back to operational systems.

## ETL (Extract, Transform, Load)

### Open Source ETL Tools

- [Airbyte](https://airbyte.io/) - An open-source data integration platform that helps you replicate your data in your warehouses, lakes, and databases.
- [Apache NiFi](https://nifi.apache.org/) - A powerful and scalable system to process and distribute data between disparate systems.
- [Singer](https://www.singer.io/) - An open-source standard for writing scripts that move data between databases, web APIs, files, and more.
- [Meltano](https://meltano.com/) - An open source ELT platform built by GitLab that enables you to integrate various data sources and destinations.
- [Apache Kafka](https://kafka.apache.org/) - A distributed streaming platform that can be used for building real-time data pipelines and streaming apps.

### Commercial ETL Platforms

- [Fivetran](https://www.fivetran.com/) - A cloud-based data integration platform that enables data engineers to build data pipelines to sync data from various sources to data warehouses.
- [Stitch](https://www.stitchdata.com/) - A cloud-first, developer-focused platform for rapidly moving data from source to destination.
- [Talend](https://www.talend.com/) - A unified platform for data integration and data integrity to solve complex data challenges at scale.
- [Informatica PowerCenter](https://www.informatica.com/products/data-integration/powercenter.html) - An enterprise-grade data integration platform for complex, high-performance data management.
- [AWS Glue](https://aws.amazon.com/glue/) - A fully managed extract, transform, and load (ETL) service that makes it easy to prepare and load data for analytics.
- [Google Cloud Dataflow](https://cloud.google.com/dataflow) - A fully managed streaming analytics service that minimizes latency, processing time, and cost through autoscaling and batch processing.
- [Microsoft Azure Data Factory](https://azure.microsoft.com/en-us/services/data-factory/) - A fully managed, serverless data integration solution for ingesting, preparing, and transforming data at scale.

### ETL Best Practices

- [Link Name](link) - Description

## Reverse ETL (rETL)

### Open Source rETL Tools

- [Grouparoo](https://www.grouparoo.com/) - An open-source framework for syncing customer data from your data warehouse to cloud-based tools.
- [Multiwoven](https://github.com/Multiwoven/multiwoven) - An open-source Reverse ETL platform that enables real-time data synchronization between data warehouses and business tools.
- [Airbyte](https://airbyte.io/) - While primarily known for ETL, Airbyte also supports reverse ETL workflows for certain destinations.
- [Jitsu](https://jitsu.com/) - An open-source data integration platform that can handle both ETL and reverse ETL processes.
- [Meltano](https://meltano.com/) - An open-source ELT platform that supports reverse ETL through its extensive plugin ecosystem.

### Commercial rETL Platforms

- [Census](https://www.getcensus.com/) - A reverse ETL platform that syncs data from your warehouse to your business tools, enabling operational analytics.
- [Hightouch](https://hightouch.io/) - A Reverse ETL platform that syncs data from your data warehouse to business tools without code.
- [Polytomic](https://www.polytomic.com/) - A data activation platform that moves data from your data warehouse into your business tools.
- [Omnata](https://omnata.com/) - A reverse ETL platform that specializes in syncing data from cloud data warehouses to Salesforce.
- [Seekwell](https://www.seekwell.io/) - A reverse ETL tool that allows you to build data products and sync warehouse data to your tools.
- [Rudderstack](https://rudderstack.com/) - A customer data platform that offers reverse ETL capabilities along with traditional ETL features.
- [Segment Reverse ETL](https://segment.com/product/reverse-etl/) - Part of Segment's CDP, this feature allows you to send computed traits and audiences to downstream tools.

### rETL Best Practices

- [Link Name](link) - Description

## Data Warehouses and Lakes

### Cloud Data Warehouses

- [Databricks SQL](https://databricks.com/product/databricks-sql) - A cloud data warehouse built on an open lakehouse architecture, offering high performance and seamless integration with data lakes.
- [Snowflake](https://www.snowflake.com/) - A cloud-native data warehouse offering instant scalability, secure data sharing, and per-second pricing.
- [Amazon Redshift](https://aws.amazon.com/redshift/) - A fully managed, petabyte-scale data warehouse service in the cloud, part of the AWS ecosystem.
- [Google BigQuery](https://cloud.google.com/bigquery) - A serverless, highly scalable, and cost-effective multi-cloud data warehouse designed for business agility.
- [Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/) - An integrated analytics service that brings together data integration, enterprise data warehousing, and big data analytics.
- [Firebolt](https://www.firebolt.io/) - A cloud data warehouse architected for high performance and efficiency on large-scale data.

### Data Lakes

- [Amazon S3](https://aws.amazon.com/s3/) - Object storage built to store and retrieve any amount of data from anywhere, commonly used as a data lake solution.
- [Azure Data Lake Storage](https://azure.microsoft.com/en-us/services/storage/data-lake-storage/) - A highly scalable data lake solution for big data analytics, built on Azure Blob Storage.
- [Google Cloud Storage](https://cloud.google.com/storage) - A unified object storage for developers and enterprises, from live applications data to cloud archival.
- [Databricks Delta Lake](https://delta.io/) - An open-source storage layer that brings reliability to data lakes, implemented by Databricks.
- [Cloudera Data Platform](https://www.cloudera.com/products/open-source/apache-hadoop/key-cdh-components.html) - A hybrid data platform for data engineering, streaming analytics, and data science workloads.

### Data Lakehouses

- [Databricks Lakehouse Platform](https://databricks.com/product/data-lakehouse) - Combines the best elements of data lakes and data warehouses, providing a unified solution for all data workloads.
- [AWS Lake Formation](https://aws.amazon.com/lake-formation/) - A service that makes it easy to set up, secure, and manage your data lake.
- [Dremio](https://www.dremio.com/) - A data lakehouse platform that delivers high-performance SQL querying directly on cloud data lake storage.
- [Starburst](https://www.starburst.io/) - A data lakehouse platform built on open source Trino, providing fast analytics across varied data sources.
- [Oracle Autonomous Data Warehouse](https://www.oracle.com/autonomous-database/autonomous-data-warehouse/) - A cloud-native data lakehouse solution that combines elements of both data warehouses and data lakes.

## Data Integration Patterns

- [Link Name](link) - Description

## Data Governance and Quality

- [Link Name](link) - Description

## Real-time Data Activation

- [Link Name](link) - Description

## Machine Learning for Data Activation

- [Link Name](link) - Description

## Resources

### Tutorials and Guides
- [Link Name](link) - Description

### Books and Publications
- [Link Name](link) - Description

### Articles and Case Studies
- [Link Name](link) - Description

### Conferences and Events
- [Link Name](link) - Description

### Community Resources

#### Forums and Discussion Boards
- [Link Name](link) - Description

#### Slack Channels
- [Link Name](link) - Description

#### Notable Blogs
- [Link Name](link) - Description

### Related Topics

#### Data Mesh
- [Link Name](link) - Description

#### DataOps
- [Link Name](link) - Description

#### Data Fabric
- [Link Name](link) - Description

## Contributing

We welcome contributions to this awesome list! Please read our [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.

## License

This awesome list is under the [Creative Commons Zero v1.0 Universal License](LICENSE).
