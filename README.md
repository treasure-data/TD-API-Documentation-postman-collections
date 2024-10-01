# Treasure Data Postman Collections for APIs

Treasure Data has created Postman collections for developers who are interested in quickly exercising Treasure Data APIs. Current collections include:

-   [Bulk Import Tutorial](https://github.com/treasure-data/TD-API-Documentation-postman-collections/blob/main/td-api/bulk-import-tutorial/README.md#postman-collection-for-bulk-import-tutorial)
-   [Live Connect API](https://github.com/treasure-data/TD-API-Documentation-postman-collections/blob/main/live-connect/README.md)


To use these collections you will need to do the following:
-   Download and install Postman on your local computer
-   Obtain a valid TD API Key for your API endpoints
-   Download an API-specific Postman collection file (`•••••••.postman_collection.json`)
-   Download the additional supporting files (if any) 
-   Configure the variables in the Postman collection

## Downloading and Installing Postman
You can down load Postman here:
    https://www.postman.com/downloads/
     
The TD Postman collections will work on any operating system that Postman supports, and the TD Postman collections do not require you to be logged into Postman for the APIs to work.

## Obtaining a Valid TD API Key
You can find instructions on obtaining a TD API key here:
    https://docs.treasuredata.com/display/PD/Getting+Your+API+Keys

After you have your API key, and the corresponding console URL, configure the Postman variables `{{ApiKeyAuth}}` and `{{baseUrl}}`. 


 ## Downloading a TD API Postman Collection
 Publicly available TD API Postman collections can be accessed in the Treasure Data [postman-collections](https://github.com/treasure-data/TD-API-Documentation-postman-collections) github repository.


 Generally, the collections are grouped by API. Browse to the API collection you want to work with and download the `•••••••.postman_collection.json` file and any other supporting files to your local machine.

## Configuring TD Collections in Postman
Configuring TD API Collections requires the following steps:
-   Importing the collection file
-   Configuring the `{{baseUrl}}` and `{{ApiKeyAuth}}` variables with the appropriate values.

To configure Postman with a TD API collection:

1. On your local machine, open the Postman application.
1. In the upper-left corner, in the My Workspace area, select **Import**.
1. Select the TD Postman collection you want to import.<br>
    The collection will display as a new collection.
1. Select the "View more actions" option ( ... ) for the new collection and select **Edit**.
1. Select the **Variables** tab.
1. In the Current Value column for the {{baseUrl}} variable enter the API endpoint you want to use.
1. In the Current Value column for the {{ApiKeyAuth}} variable enter the TD API key that corresponds to your endpoint.
1. Select **Save**.<br>
    Some of the variables defined for the collection may be empty or set to 0. In these cases, you may first need to run a "Create" or a "Get" API in order to get the ID or value to enter into the Current Value column.

From the navigation pane, you can now select the individual API you want to exercise. Refer to the [TD API portal](https://api-docs.treasuredata.com/) for instructions on how to exercise specific collections.
