---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Cosmosdb
  platforms: java
---

# Getting Started with Cosmosdb - Create Cosmos DB Table With Virtual Network Rule - in Java #


  Azure CosmosDB sample for using Virtual Network ACL rules.
   - Create a Virtual Network with two subnets.
   - Create an Azure Table CosmosDB account configured with a Virtual Network Rule
   - Add another virtual network rule in the CosmosDB account
   - List all virtual network rules.
   - Delete a virtual network.
   - Delete the CosmosDB.
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/cosmosdb-java-create-cosmosdb-table-with-virtual-network-rule.git

    cd cosmosdb-java-create-cosmosdb-table-with-virtual-network-rule

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.