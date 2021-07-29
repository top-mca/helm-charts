# Helm charts for ThinQ On-Premise
***
This package installs the ThinQ On-Premise.
##Usage
***
###Add helm repository & update
```
helm repo add top-chart https://top-mca.github.io/helm-charts/
helm repo update
```
###Install package
```
helm install <your release name> top-chart/top
```
###Uninstall package
```
helm uninstall <your release name>
```