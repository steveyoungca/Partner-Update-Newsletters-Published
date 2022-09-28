

# March Newsletter V2


- [March Newsletter V2](#march-newsletter-v2)
  - [Ignite sessions](#ignite-sessions)
  - [Announcements This Month.](#announcements-this-month)
  - [Microsoft Azure Purview | Azure Purview support for Synapse as a data source](#microsoft-azure-purview--azure-purview-support-for-synapse-as-a-data-source)
  - [Microsoft Azure Purview | Azure Purview powered search in Synapse](#microsoft-azure-purview--azure-purview-powered-search-in-synapse)
  - [Microsoft Azure Purview | Purview connectors for on-prem sources](#microsoft-azure-purview--purview-connectors-for-on-prem-sources)


## Ignite sessions

I did a summary in a blog post of the Data & AI announcements from Microsoft Ignite a week or so ago.  [Top Data & AI Announcements and Session Roundup from Microsoft’s Ignite 2021](https://5minutebi.com/2021/03/08/top-data-ai-announcements-and-session-roundup-from-microsofts-ignite-2021/)

## Announcements This Month.

* Azure SQL Database | Azure Monitor SQL insights - Preview - [Intelligent Insights using AI to monitor and troubleshoot database performance (preview)](https://docs.microsoft.com/en-us/azure/azure-sql/database/intelligent-insights-overview)
  Intelligent Insights uses built-in intelligence to continuously monitor database usage through artificial intelligence and detect disruptive events that cause poor performance. Once detected, a detailed analysis is performed that generates an Intelligent Insights resource log (called SQLInsights) with an intelligent assessment of the issue. This assessment consists of a root cause analysis of the database performance issue and, where possible, recommendations for performance improvements.

* Azure SQL Database | Azure SQL DDM granular permissions - GA - [Dynamic Data Masking](https://docs.microsoft.com/en-us/sql/relational-databases/security/dynamic-data-masking?view=sql-server-ver15)



* Azure SQL Database | Cross-instance Service Broker - Preview


* Azure SQL Database | Long-term backup retention (LTR) for MI - Preview - [Link](https://techcommunity.microsoft.com/t5/azure-sql/long-term-backup-retention-on-azure-sql-managed-instance/ba-p/2183962)

* Azure SQL Database | Machine Learning for SQL Managed Instance - GA - [Link](https://docs.microsoft.com/en-us/azure/azure-sql/managed-instance/machine-learning-services-overview)
* 
* Data Explorer | Azure Data Explorer Performance Updates
* 
* Microsoft Azure Purview | Azure Purview support for Synapse as a data source




## Microsoft Azure Purview | Azure Purview support for Synapse as a data source

[Register and scan Azure Synapse Analytics](https://docs.microsoft.com/en-us/azure/purview/register-scan-azure-synapse-analytics)

## Microsoft Azure Purview | Azure Purview powered search in Synapse

Azure Synapse Analytics workspaces can now turn on an Azure Purview powered search. This integration allows customers to discover Azure Purview managed data assets and interact with them within the native Synapse Analytics workspace. With this feature, customers can:

Enable effortless data discovery - Data scientists and data engineers can now find data at their fingertips with an Azure Purview powered search within Synapse Studio.
Democratize access to all data - Azure Purview maps data across the organizational data landscape and with this feature, Synapse analytics users can now find data no matter its residency.
Understand and trust data enriched with metadata, classifications, lineage, annotations, taxonomy, and business glossary.
Stay up to date by connecting the newly discovered data to your Synapse workspace with linked services or integration datasets.
With this integration, customers can unlock exciting actions - New SQL Script, New Notebook, and New Data Flow.

* New SQL Script - View the top 100 rows to understand the shape of the data, create an external table from Synapse SQL database, and load data into a Synapse SQL database.
* New Notebook - Load data into a Spark DataFrame and create a Spark Table (when in Parquet format, it also creates a serverless SQL Pool table).
* New data flow - Create an integration dataset that can be used a source in a data flow pipeline. For more information about using data flow in Synapse.
Urge your Azure Synapse Analytics customers to get started today with documentation on connecting an Azure Purview Account to Synapse and enabling effortless data discovery within the Synapse workspace!


[Connect an Azure Purview Account - Azure Synapse Analytics | Microsoft Docs](https://docs.microsoft.com/en-us/azure/synapse-analytics/catalog-and-governance/quickstart-connect-azure-purview)

[Discover, connect, and explore data in Synapse using Azure Purview - Azure Synapse Analytics | Microsoft Docs](https://docs.microsoft.com/en-us/azure/synapse-analytics/catalog-and-governance/how-to-discover-connect-analyze-azure-purview)


## Microsoft Azure Purview | Purview connectors for on-prem sources
Azure Purview extends the Purview Data Map's ability to automatically scan data to more on-premises sources. With this feature, customers can now automatically scan and view lineage between assets for the following sources:

[Azure Purview now supports ERP sources like SAP S/4 HANA and SAP ECC.](https://docs.microsoft.com/en-us/azure/purview/register-scan-sapecc-source)
[Azure Purview also supports Oracle DB as a data source.](https://docs.microsoft.com/en-us/azure/purview/register-scan-oracle-source) - This article outlines how to register an Oracle data base in Purview and set up a scan. Supported capabilities;
* The Oracle source supports Full scan to extract metadata from an Oracle database and fetches Lineage between data assets.
