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

### [Power BI](./power-bi.ipynb)

The notebook shows DAX querie can be executed from Azure SQL DB using the `executeQueries` REST endpoint provided by Power BI datasets

- [Execute DAX queries in Power BI]

### [Azure Cognitive Services]

Work in progress

### [Azure SignalR]

Work in progress

### [Azure Logic Apps]

Work in progress

### [Azure API Management](./azure-api-management.ipynb)

The notebook contains samples on how to invoke an HTTPS REST endpoint no matter if it is residing in Azure or in any other cloud or hosting platform, by securely publishing and API using [Azure API Management](https://learn.microsoft.com/en-us/azure/api-management/)

- Call an external REST endpoint using API Management

## Contribute

Do you want to contribute adding a sample? Do you see something missing or incorrect? Please help this repository to grow, and submit an issue or fork it a submit a Pull Request. Details on how to contribute can be found here: [Contributing](./CONTRIBUTING.md) 