# Azure SQL DB sp_invoke_external_rest_endpoint samples

`sp_invoke_external_rest_endpoint` is a system stored procedure that allows native invocation of an HTTPS REST endpoint from Azure SQL DB.

For full details on this stored procedure, please take a look at the official documentation here: [sp_invoke_external_rest_endpoint (Transact-SQL)](https://learn.microsoft.com/sql/relational-databases/system-stored-procedures/sp-invoke-external-rest-endpoint-transact-sql)

## Samples

### [Azure Functions](./azure-functions.ipynb)

- Call a public (or anonymous) Azure Function
- Call an Azure Function protected by a secret key
- Call an Azure Function protected by Azure AD
