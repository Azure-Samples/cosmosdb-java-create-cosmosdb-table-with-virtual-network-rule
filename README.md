---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Cosmos
  platforms: java
---

# Getting Started with Cosmos - Create Cosmos DB Table With Virtual Network Rule - in Java #


  Azure CosmosDB sample for using Virtual Network ACL rules.
   - Create a Virtual Network with two subnets.
   - Create an Azure Table CosmosDB account configured with a Virtual Network Rule
   - Add another virtual network rule in the CosmosDB account
   - List all virtual network rules.
   - Delete a virtual network.
   - Delete the CosmosDB.
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/master/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/master/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/cosmosdb-java-create-cosmosdb-table-with-virtual-network-rule.git

    cd cosmosdb-java-create-cosmosdb-table-with-virtual-network-rule

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.