# Azure-Resource-Manager-Template-Sample

## Basic Commands
### Azure-cli

- List Subscriptions
  ```
  az group list --output table
  ```
- Set Subscription
  ```
  az account set --subscription <subscription id>
  ```
- List Resource Groups
  ```
  az group list --output table
  ```
- Deploy ARM
  ```
  az deployment group create --name <name> --resource-group <resource group name> --template-file <arm json file>
  ```
