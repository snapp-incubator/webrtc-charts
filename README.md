# CHARTS

helm charts for third-party tools

## Supported charts

- janus

- ion-sfu

## Installation

- clone the repository

- install helm tool

- login to your kubernetes cluster

- install chart

    ``` zsh
    helm upgrade --install $chart_name charts/$chart_name --generate-name
    ```

- uninstall chart

    ``` zsh
    helm uninstall $chart_name
    ```

