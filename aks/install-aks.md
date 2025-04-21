# Create resource group

```
az group create --name go-web-app-rg --location centralindia
```

# Create AKS cluster

```
az aks create --resource-group go-web-app-rg --name go-web-app-cluster --node-count 1 --generate-ssh-keys
```