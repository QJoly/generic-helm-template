<p align="center">
    <img src="https://helm.sh/img/helm.svg" width="140px" alt="Helm LOGO"/>
    <br>
    <a href="https://qjoly.github.io/helm-charts"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=0F1689&background=FFFFFF00&center=true&vCenter=true&width=435&lines=QJOLY’s+Chart+Repository;qjoly.github.io%2Fhelm-charts;+Feel+free+to+contribute" alt="Typing SVG" /></a>
</p>

# How to use ? 

```bash
helm repo add qjoly https://qjoly.github.io/helm-charts/ # Add the repo to your helm
```
```bash
helm install myjoplin qjoly/joplin # Install your app
```

# Charts

| Name  | Description | Chart Version | App Version |
|-------|-------------|---------------|-------------|
| generic-app | Helm chart for deployment generic app on Kubernetes | v0.1.0 | 0 |


# Disclaimer

:warning: Only traefik is compatible with my charts. I do not plan to support any other ingress. (Ingress != IngressRoute) 

**:warning: I do not use any Ingress object ! Only __IngressRoute__ !!**

# Contributing 

I gladly accept Pull-Requests, feel free to open one if you want to correct/add a chart. 
