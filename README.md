# Azure Data Engineering: Streamlined Integration with Data Factory, Databricks, Synapse Analytics, and Tableau

## Project Overview
This project demonstrates a comprehensive data engineering solution built on Microsoft Azure. The solution is designed to transform raw data into actionable insights by utilizing Azure services like Data Factory, Databricks, Synapse Analytics, and Tableau for visualization. The architecture is structured into layers to streamline the data management process.

![Architecture Diagram](https://github.com/Juanita-BA/tokyo-olympics/blob/main/azure_image.jpg)

## Architecture
The architecture is based on two key layers:
1. **Raw Data Layer**: Ingests unprocessed data.
2. **Transformed Data Layer**: Cleans, processes, and refines data for analysis.

### Azure Services Used:
- **Azure Data Factory**: Orchestrates and automates data pipelines.
- **Azure Databricks**: Processes and transforms data using Apache Spark.
- **Azure Synapse Analytics**: Provides advanced analytics and data warehousing capabilities.
- **Azure Data Lake Storage Gen 2**: Acts as the storage backbone for both data layers.
- **Tableau**: Visualizes the data insights for reporting.

## Setup Instructions
### Prerequisites:
- Active Azure subscription.
- Azure resources including Data Factory, Databricks, Synapse Analytics, ADLS, and Tableau.

### Configuration:
1. Set up an Azure Data Lake with containers for Raw and Transformed Data layers.
2. Use Azure Data Factory to automate data movement and transformations in Databricks.
3. Leverage Azure Synapse SQL pools to analyze transformed data.
4. Connect Tableau to Synapse for interactive reporting.

## Execution Steps
1. **Ingest Data**: Use Azure Data Factory to load data into the Raw Data Layer.
2. **Transform Data**: Run Databricks notebooks to process and move data into the Transformed Data Layer.
3. **Analyze Data**: Query transformed data using Synapse SQL.
4. **Visualize Data**: Create and share reports using Tableau.

## Dataset attached

For more details, refer to the document uploaded in this repository.
