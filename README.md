Using this template, storage account can be deployed.

->To deploy a template, sign in to either the Azure CLI or Azure PowerShell

     az login
     
->Create a resource group

     az group create --name resourceGroupName --location "West Europe"
     
->Deploy template

     az deployment group create --name DeployLocalTemplate --resource-group $resourceGroupName --template-file <PATH-TO-storage.JSON> --parameters <PATH-TO-storage.PARAMETERS.JSON> 
