# WebRTC Charts

Helm charts for webrtc servers.

## Supported servers

- janus

- ion-sfu

## Installation

- clone the repository

- install helm tool

- login to your kubernetes cluster

- choose chart

  ```zsh
  export chart_name=<from_supported_charts>
  ```

- install chart

  ```zsh
  helm upgrade --install $chart_name charts/$chart_name
  ```

- uninstall chart

  ```zsh
  helm uninstall $chart_name
  ```
