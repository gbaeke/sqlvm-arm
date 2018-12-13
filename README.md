Deploy VM with:

az group create -n resourcegroupname -l location

e.g. location = West Europe

az group deployment create -g resourcegroupname --template-file azuredeploy.json --parameters azuredeploy.parameters.json

*Note*: in variables section, set storageAccountName and storageAccountResourceGroupName to the storage account and resource group for VM diagnostics