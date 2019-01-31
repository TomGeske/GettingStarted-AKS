# GettingStarted with Azure Kubernetes Service
This guide provides some help how to setup your Azure Kubernetes Cluster (AKS)

## Prepare your local machine
* [Azure CLI](https://docs.microsoft.com/cli/azure/install-azure-cli)
* [Visual Studio Code](https://code.visualstudio.com/download)
* [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
* [helm](https://github.com/helm/helm/releases)

## Prepare your Azure Subscription
* Setup Azure Active Directory
* Register required Resource Provider in your Subscription
* Check Resource Quotas of your Azure Subscription

## Create your AKS cluster
* Decide for basic or advanced networking [Link](https://docs.microsoft.com/en-us/azure/aks/configure-advanced-networking)
* Role based access [Link](https://docs.microsoft.com/en-us/azure/aks/operator-best-practices-identity)
* Setup Reboot Deamon [Link](https://docs.microsoft.com/en-us/azure/aks/node-updates-kured)
* Setup logging [Link](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/container-insights-overview?toc=%2Fen-us%2Fazure%2Faks%2FTOC.json&bc=%2Fen-us%2Fazure%2Fbread%2Ftoc.json)
* Volume Configuration [Link](https://docs.microsoft.com/en-us/azure/aks/azure-files-dynamic-pv)
* Custom DNS: add custom dns server for stubdomain [Link](https://www.danielstechblog.io/using-custom-dns-server-for-domain-specific-name-resolution-with-azure-kubernetes-service/) and [k8s doc](https://kubernetes.io/docs/tasks/administer-cluster/dns-custom-nameservers/) 

## Web Application Firewall

## SSL Configuration

## Prep CI & CD
* Setup a container registry
