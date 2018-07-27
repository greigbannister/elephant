# Deploying elephant to Azure

### Prerequisites

* An Azure subscription.
* An SSH key pair that will be used to login to instances
* An existing VNET in which to deploy the elephant

You will also need an Azure Service Principal to manage the related Azure resources.  This comes in the form of a servicePrincipalAppId and a servicePrincipalAppKey.  If you do not have one, or wish for one to be created for you, click below and paste in:

<a href="https://shell.azure.com/bash" target="_blank"><img src="https://shell.azure.com/images/launchcloudshell.png"/></a>

az ad sp create-for-rbac

The servicePrincipalAppId is the value of UserId and the servicePrincipalAppKey is the value of "Password".

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fgreigbannister%2Felephant%2Fmaster%2Fazure%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>


### Steps

1. Click the **Deploy to Azure** button from above, this will lead you to the ARM provision page.
1. Fill in the parameters, agree to the terms & conditions and click Purchase. It takes about 20 minutes
   for the provision process to complete. Once the deployment is complete, the resource group contains
   all resources

