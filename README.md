# SKALA class-9 / sk301 Helm charts

```sh
helm repo add sk301-mycharts https://skala-dg.github.io/mycharts
helm repo update sk301-mycharts
helm upgrade --install sk301-myfirst-helm sk301-mycharts/sk301-myfirst-helmchart --version 0.0.1 --namespace class-9 --wait
```

Images: skala-registry.skala-ai.com/class-9/sk301-webserver

This chart is configured for class-9 and sk301. Version 0.0.2 demonstrates chart package versioning; application settings remain explicit in values.yaml.
