---
services: search
platforms: rest
author: brjohnstmsft
---

# Getting Started with Azure Search using the REST API

This sample includes scripted REST API requests that are meant to help when getting started with the Azure Search REST API. The sample REST API requests show how to:

* Create and Delete an Azure Search index
* Upload Documents to an Azure Search index
* Search & Filter documents within an index

## Running the REST API sample

The REST API sample is currently a PowerShell script that runs on Windows. First you will need to edit the script, which is called `RestHowTo.ps1` and is in the `RestHowTo` directory. Set the `$apiKey` and `$searchServiceName` variables at the top of the file to the admin key and name of your Azure Search service. Then, from the PowerShell command prompt, change to the `RestHowTo` directory and run `./RestHowTo.ps1`.

## More information

For more details on these samples, please refer to these articles on Azure.com:

  - [Create an Azure Search index using the REST API](https://azure.microsoft.com/documentation/articles/search-create-index-rest-api/).
  - [Import data to Azure Search using the REST API](https://azure.microsoft.com/documentation/articles/search-import-data-rest-api/).
  - [Query your Azure Search index using the REST API](https://azure.microsoft.com/documentation/articles/search-query-rest-api/).