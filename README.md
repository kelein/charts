# Helm Charts

Helm Charts Library for Kubernetes

## Usage

```bash
❯ helm repo add <REPO> https://kelein.github.io/charts
"<REPO>" has been added to your repositories

❯ helm repo list
NAME    URL
<REPO>  https://kelein.github.io/charts

❯ helm search repo <CHART>
❯ helm -n <NS> install <REPO>/<CHART> --version <VERSION>
```
