## Kubenetes 及其组件镜像

|  分类  |  组件名称   | 版本  |
|  ---- |  ----  | ----  |
| 核心 | kubernetes  | 1.15.4 |
| 核心 | etcd  | 3.3.10 |
| 核心 | docker  | docker-ce-18.09.9 |
| 核心 | gcr.io/google-containers/pause-amd64| 3.1 |
| 存储 | quay.io/external_storage/nfs-client-provisioner  | v3.1.0-k8s1.11 |
| 网络 | docker.io/coredns/coredns| 1.6.0 |
| 网络 | quay.io/coreos/flannel| v0.11.0-amd64 |
| 网络 | calico/node:v3.4.4 |
| 网络 | calico/cni:v3.4.4 |
| 网络 | calico/kube-controllers:v3.4.4 |
| 网络 | docker.io/traefik  | v1.7.11 |
| 监控 | docker.io/grafana/grafana  | v1.7.11 |
| 监控 | quay.io/prometheus/alertmanager  | v0.15.2 |
| 监控 | quay.io/prometheus/node-exporter  | v1.7.11 |
| 监控 | quay.io/prometheus/prometheus| v2.4.3 |
| 监控 | quay.io/prometheus/pushgateway| v0.5.2 |
| 监控 | quay.io/coreos/kube-state-metrics| v1.4.0 |
| Dashboard | gcr.io/google_containers/heapster-grafana-amd64| v4.4.3 |
| Dashboard | gcr.io/google_containers/heapster-amd64| v1.5.4 |
| Dashboard | gcr.io/google_containers/heapster-influxdb-amd64| v1.5.2 |
| Dashboard | k8s.gcr.io/metrics-server-amd64| v0.3.2 |
| Dashboard | k8s.gcr.io/kubernetes-dashboard-amd64| v1.10.0 |
| 工具 | docker.io/registry| 2 |
| 工具 | docker.io/konradkleine/docker-registry-frontend| v2 |
| 工具 | gcr.io/kubernetes-helm/tiller| v2.12.3 |
| 工具 | quay.io/coreos/configmap-reload| v0.0.1 |
| 工具 | docker.io/appropriate/curl| edge |

## 操作系统及其组件

|  分类  |  组件名称  |
|  ---- |  ----   |
| OS | CentOS 7.6 Minimal  |
| RPM | dnsmasq  | 
| RPM | chrony  | 
| RPM | ntpdate  | 
