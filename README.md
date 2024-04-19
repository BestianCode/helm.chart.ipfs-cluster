# IPFS Cluster Helm Chart

## Installation

- Set HelmChart values in `values.yaml` file
- Install the chart:

```bash
helm upgrade --install ipfs-cluster charts/ipfs-cluster/ --namespace ipfs-cluster --create-namespace --values <./values.yaml>
```

## Usefull links

- IPFS Cluster / Running Cluster on Kubernetes (outdated): https://ipfscluster.io/documentation/guides/k8s/
- IPFS Docs: https://docs.ipfs.tech/install/
- IPFS Cluster repo: https://github.com/ipfs-cluster/ipfs-cluster
- IPFS Kubo repo: https://github.com/ipfs/kubo

---

- Forked from: https://github.com/w3f/ipfs-cluster-chart
