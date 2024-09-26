# Data Transfer from Localhost to Azure Synapse Data Warehouse Using Self-Hosted Integration Runtime
### Overview
This project demonstrates the transfer of data from a local machine to an Azure Synapse Data Warehouse. The integration is powered by a Self-Hosted Integration Runtime (SHIR), which enables seamless communication between on-premise data sources and Azure services like Azure Data Factory and Azure Synapse Analytics.

### Project Flow

1. Local Data Source: Data from a local server is the source for the pipeline.
2. Self-Hosted Integration Runtime (SHIR): Acts as a bridge between the on-premise/local environment and Azure, enabling secure data movement.
3. Azure Data Factory (ADF): Orchestrates the data movement pipeline, utilizing SHIR to connect the local source with Azure Synapse.
4. Azure Synapse Analytics: The destination where data is loaded into a Synapse SQL pool for further processing and analytics.

### Key Features
- Self-Hosted Integration Runtime: Securely connects the local environment to Azure services.
- Data Pipelines: Automates the extraction, transformation, and loading (ETL) of data using ADF.
- Azure Synapse Analytics: Used as the data warehouse for optimized querying and analytics.

### Prerequisites
- Azure account with access to Azure Synapse Analytics and Azure Data Factory.
- A machine to host the Self-Hosted Integration Runtime.
- Local data source (e.g., SQL Server, CSV files, or any compatible data source).
- Administrative access to the machine hosting SHIR.

### Conclusion
By leveraging Self-Hosted Integration Runtime and Azure Data Factory, this project simplifies the process of transferring local data to Azure Synapse, creating a scalable solution for on-premise-to-cloud data movement.
