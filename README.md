---
page_type: sample
languages:
- sql
products:
- azure-functions
- azure-event-hubs
- azure-openai
- azure-sql-database
- power-bi
- azure-api-management
urlFragment: azure-sql-db-invoke-external-rest-endpoints
name: Call REST endpoints from Azure SQL database
description: |
  sp_invoke_external_rest_endpoint is a system stored procedure that allows native invocation of an HTTPS REST endpoint from Azure SQL DB.
---

# Azure SQL DB sp_invoke_external_rest_endpoint samples

`sp_invoke_external_rest_endpoint` is a system stored procedure that allows native invocation of an HTTPS REST endpoint from Azure SQL DB.

For full details on this stored procedure, please take a look at the official documentation here: [sp_invoke_external_rest_endpoint (Transact-SQL)](https://learn.microsoft.com/sql/relational-databases/system-stored-procedures/sp-invoke-external-rest-endpoint-transact-sql)

## Samples

Samples are made available via Jupyter Notebook, natively supported by GitHub and also by [Azure Data Studio](https://learn.microsoft.com/en-us/sql/azure-data-studio/notebooks/notebooks-guidance)

### [Azure Functions](./azure-functions.ipynb)

In the provided notebook you can find samples on how to invoke an [Azure Function](https://learn.microsoft.com/azure/azure-functions/functions-overview) using a [HTTP Trigger](https://learn.microsoft.com/azure/azure-functions/functions-bindings-http-webhook-trigger):

- Invoke a public (or anonymous) Azure Function
- Invoke an Azure Function protected by a secret key
- Invoke an Azure Function protected by Azure AD

### [Azure Event Hubs](./azure-event-hubs.ipynb)

The notebook contains samples on how to send messages to [Azure Event Hubs](https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-about):

- Send events using a SAS Token
- Send events using a Managed Identity

### [Azure Event Grid]

Work in progress

### [Azure OpenAI](https://github.com/azure-samples/azure-sql-db-openai)

This sample shows how you can call Azure OpenAI to get text embeddings and then find similar text using cosine similarity.

### [Power BI](./power-bi.ipynb)

The notebook shows how DAX queries can be executed from Azure SQL DB using the `executeQueries` REST endpoint provided by Power BI datasets

- Execute DAX queries in Power BI

### [Azure Cognitive Services](./azure-cognitive-services.ipynb)

The notebook shows how to send data back and forth between an Azure Cognitive services, configured to perform Anomaly Detection.

### [Azure SignalR]

Work in progress

### [Azure Logic Apps]

Work in progress

### [Azure API Management](./azure-api-management.ipynb)

The notebook contains samples on how to invoke an HTTPS REST endpoint no matter if it is residing in Azure or in any other cloud or hosting platform, by securely publishing and API using [Azure API Management](https://learn.microsoft.com/en-us/azure/api-management/)

- Call an external REST endpoint using API Management

### [Azure Blob Storage](./azure-storage.ipynb)

This notebook has examples on working with Azure Blob Storage with SAS tokens and Managed Identities. Use the REST APIs for creating files, containers and then reading them back.

## Contribute

Do you want to contribute adding a sample? Do you see something missing or incorrect? Please help this repository to grow, and submit an issue or fork it a submit a Pull Request. Details on how to contribute can be found here: [Contributing](./CONTRIBUTING.md) 
