# Deploying elephant to Azure

### Prerequisites

* An Azure subscription.
* An Azure Service Principal to manage the related Azure resources.
* An SSH key pair that will be used to login remotely to the Jenkins master VM.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fgreigbannister%2Felephant%2Fmaster%2Fazure%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>


### Steps

1. Click the **Deploy to Azure** button from above, this will lead you to the ARM provision page.
1. Fill in the parameters, agree to the terms & conditions and click Purchase. It takes about 20 minutes
   for the provision process to complete. Once the deployment is complete, the resource group contains
   all resources

