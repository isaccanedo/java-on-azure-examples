# Exemplos de Java no Azure

Este repositório do GitHub contém um conjunto de exemplos do Azure especificamente para desenvolvedores Java começarem a usar o Azure rapidamente.
Use o rastreador de problemas para deixar comentários, arquivar problemas ou propor outros exemplos.

## Começando

Para trabalhar com esses exemplos, supõe-se que você tenha a CLI do Azure instalada, que tenha feito logon e definido sua assinatura padrão.
Se ainda não o fez, siga os passos abaixo.

_Observação: Fazer login e definir sua assinatura padrão precisa ser feito uma vez por sessão de terminal._

### Instale a CLI do Azure

To setup the Azure CLI, please visit [Install the Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli).
And once you are done come back to this README.

### Login into Azure

<!-- workflow.skip() -->
````shell
  az login
````

### Set your default subscription

Get a list of your subscriptions (notice the `refresh` parameter that retrieves up-to-date subscriptions from the server) :

<!-- workflow.skip() -->
````shell
  az account list --output table --refresh
````

Set your default subscription for this session using the subscription id from the previous output:

<!-- workflow.skip() -->
````shell
  az account set --subscription "subscription-id"
````

<!-- workflow.run() 

  exit 0

  -->

## Our alphabetical list of examples

1. [Azure App Configuration examples](appconfig/)      <!-- workflows run Tuesday   / 2 examples -->
1. [Azure App Service examples](appservice/)           <!-- workflows run Friday    / 18 examples -->
1. [Azure Cache for Redis examples](redis/)            <!-- workflows run Sunday    / 2 examples  -->
1. [Azure Container Apps examples](containerapp/)      <!-- workflows run Tuesday   / 9 examples  -->
1. [Azure Container Instances examples](container/)    <!-- workflows run Monday    / 3 examples  -->
1. [Azure Container Registry examples](acr/)           <!-- workflows run Sunday    / 15 examples -->
1. [Azure Cosmos DB examples](cosmosdb/)               <!-- workflows run Thursday  / 8 examples  -->
1. [Azure Data Explorer examples](kusto/)              <!-- workflows run Sunday    / 4 examples  -->
1. [Azure Database for MySQL examples](mysql/)         <!-- workflows run Tuesday   / 4 examples  -->
1. [Azure Database for PostgreSQL examples](postgres/) <!-- workflows run Monday    / 4 examples  -->
1. [Azure Event Hubs examples](eventhubs/)             <!-- workflows run Saturday  / 4 examples  -->
1. [Azure Functions examples](functionapp/)            <!-- workflows run Thursday  / 3 examples  -->
1. [Azure Key Vault examples](keyvault/)               <!-- workflows run Tuesday   / 6 examples  -->
1. [Azure Kubernetes Service examples](aks/)           <!-- workflows run Saturday  / 7 examples  -->
1. [Azure Monitor examples](monitor/)                  <!-- workflows run Thursday  / 1 example   -->
1. [Azure Networking examples](network/)               <!-- workflows run Wednesday / 1 example   -->
1. [Azure Red Hat OpenShift examples](aro/)            <!-- workflows run Friday    / 1 example   -->
1. [Azure Resource Group examples](group/)             <!-- workflows run Saturday  / 2 examples  -->
1. [Azure Service Bus examples](servicebus/)           <!-- workflows run Friday    / 9 examples  -->
1. [Azure Spring Apps examples](spring/)               <!-- workflows run Wednesday / 3 examples  -->
1. [Azure SQL Database examples](sql/)                 <!-- workflows run Wednesday / 4 examples  -->
1. [Azure Storage examples](storage/)                  <!-- workflows run Monday    / 3 examples  -->

<!-- next day for workflows is Monday -->

## Contributing

How do I contribute? See [Contributing](CONTRIBUTING.md)
