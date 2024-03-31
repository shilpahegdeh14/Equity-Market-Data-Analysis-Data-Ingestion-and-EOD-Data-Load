# Project: Data Ingestion of Stock Exchange Data into Parquet using Azure Blob Storage and Azure Databricks

## Description
The project aims to ingest stock exchange data from various file formats into Parquet files, leveraging Azure Blob Storage and Azure Databricks. The data sources consist of daily submissions from stock exchanges in a semi-structured text format.

### Data Sources
The data sources are stock exchange daily submissions files in semi-structured text format.

### Azure Blob Storage
The Azure Blob storage contains folders named `output` and `output_csv`, indicating successful writes of NYSE and NASDAQ stock exchange event data ingested as CSV and JSON files.

### Notebook Code
The notebook code demonstrates how to parse CSV and JSON files based on the event type and then save them as separate Parquet files partitioned by the record type or event type.

[Azure Blob Storage Screenshot after successful data ingestion]

<img width="1440" alt="image" src="https://github.com/shilpahegdeh14/stock_exchange_data_ingestion_guidedcapstone2/assets/24759597/785179b9-4d86-44f9-9349-b4ab05d8a9f4">
