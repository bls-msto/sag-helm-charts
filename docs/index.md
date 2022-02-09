## Helm Charts by SoftwareAG Government Solutions

This is a Helm Charts repository for the containers provided and maintained by Software AG Government Solutions

### Current charts

- saggov-helm-charts/webmethods-apigateway
- saggov-helm-charts/webmethods-devportal
- saggov-helm-charts/webmethods-terracotta

### Install the repo

```bash
helm repo add saggov-helm-charts https://softwareag-government-solutions.github.io/saggov-helm-charts
```

### Verify

```bash
helm search repo webmethods-devportal
helm search repo webmethods-apigateway
helm search repo webmethods-terracotta
```

### Deploy the charts

```
helm install webmethods-devportal saggov-helm-charts/webmethods-devportal
helm install webmethods-apigateway saggov-helm-charts/webmethods-apigateway
helm install webmethods-terracotta saggov-helm-charts/webmethods-terracotta
```

### Support or Contact

Having trouble with these charts? Please submit an issue, right here, on github!

Also, please refer to our blue-print sample deployments project at [webmethods-container-deployments](https://github.com/softwareag-government-solutions/webmethods-container-deployments)

For more information on the SoftwareAG products, you can Ask a Question in the [TECHcommunity Forums](http://tech.forums.softwareag.com).
You can also find additional information in the [Software AG TECHcommunity](http://techcommunity.softwareag.com).

Finally, for access and other general question, contact Software AG Government Solutions at info@softwareaggov.com 