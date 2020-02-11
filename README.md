# auto-deploy

Azure Resource Manager Templates - Best Practices Guide
https://github.com/Azure/azure-quickstart-templates/blob/master/1-CONTRIBUTION-GUIDE/best-practices.md

Azure CLI deploy command
```
templateFile="azuredeploy.json"
az group deployment create \
  --name docker-01 \
  --resource-group simon-auto-deploy \
  --template-file $templateFile
```