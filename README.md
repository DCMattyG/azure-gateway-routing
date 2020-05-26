# azure-gateway-routing
Transit routing between vNet in Hub &amp; Spoke using a Virtual Network Gateway + UDR's

This template will deploy everything required (networking) to demonstrate dynamic networking w/ Hub & Spoke via Virtual Network Gateway in a "hub" vNet with several "spoke" vNets.

### Example Deployment
```sh
az login  
az deployment sub create --location westus --template-file azuredeploy.json --parameters azuredeploy.parameters.json
```
