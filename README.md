# WebRTC Charts

Helm charts for webrtc servers.

## Supported servers

- [janus](https://github.com/meetecho/janus-gateway)

- [ion-sfu](https://github.com/pion/ion-sfu)

## Installation

- clone the repository

- install helm tool

- login to your kubernetes cluster

- choose chart

  ```zsh
  chart=<from_supported_charts>
  ```

- install chart

  ```zsh
  helm upgrade --install $chart charts/$chart
  ```

- uninstall chart

  ```zsh
  helm uninstall $chart
  ```
