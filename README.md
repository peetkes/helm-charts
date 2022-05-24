# My [Helm](https://helm.sh) Charts

This repository contains [Helm](https://helm.sh) chart(s) for various projects

* [Marklogic](charts/marklogic/)
* [Test](charts/test/)

## Installing Charts from this Repository

Add the Repository to Helm:

    helm repo add helm-charts https://peetkes.github.io/helm-charts

Install MarkLogic:

    helm install helm-charts/marklogic

Install Test:

    helm install helm-charts/test