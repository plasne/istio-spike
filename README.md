# Istio-Spike

This repository is intended to compliment the "istio-spike.docx" document which is private. If you need access to that document, please let me know.

These supporting files provide an easy way to follow along in the documentation.

To provision the AKS environment, the following az-cli command was used:

```bash
az aks create -g pelasne-internal -n pelasne-internal --location eastus --enable-vmss --load-balancer-sku Standard
```
