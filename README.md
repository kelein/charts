# Helm Charts

![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)   ![Build](https://img.shields.io/github/actions/workflow/status/kelein/charts/codeql.yml?style=for-the-badge&logo=github)

Helm Charts Library for Kubernetes, ready to launching with [Helm](https://github.com/helm/helm).

## Usage

```bash
❯ helm repo add <REPO> https://kelein.github.io/charts
"<REPO>" has been added to your repositories

❯ helm repo list
NAME        URL
"<REPO>"    https://kelein.github.io/charts

❯ helm search repo <CHART>
❯ helm -n <NS> install <REPO>/<CHART> --version <VERSION>
```
