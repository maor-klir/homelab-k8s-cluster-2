<div align="center">

# 🏡☸️ homelab-k8s-cluster-2

</div>

My second homelab Kubernetes cluster implemented through [GitOps principles](https://opengitops.dev/) and powered by Talos Linux and Argo CD.

## 📖 Introduction

This Kubernetes cluster was concieved first and foremost for learning purposes.

My main goal is to learn how to deploy and implement each tooling i.e. technology mentioned following industry's best-practices regarding networking, identity, security, and scalability.

Secondly, I plan to self-host some applications for personal usage.


## ⚙️ Core Components

- [Talos Linux](https://www.talos.dev/): a secure, immutable, and minimal Linux distribution designed specifically for Kubernetes
- [Cilium](https://cilium.io): an eBPF-based networking, observability, and security solution for Kubernetes. Cilium serves as the cluster's [CNI](https://www.cni.dev) and [Ingress controller]((https://kubernetes.io/docs/concepts/services-networking/ingress-controllers/))
- [Local Path Provisioner](https://github.com/rancher/local-path-provisioner): dynamically provisioning persistent local storage with Kubernetes
- [Argo CD](https://argo-cd.readthedocs.io/en/stable/): a declarative, GitOps continuous delivery tool for Kubernetes
- [cert-manager](https://cert-manager.io/): cloud-native certificate management for Kubernetes
- [External Secrets Operator](https://external-secrets.io/latest/): a Kubernetes operator that integrates external secret management systems (in my case, with [AWS Secrets Manager](https://aws.amazon.com/secrets-manager/))

---

**Note**: This documentation is a working document and will be updated to reflect the ongoing development of the cluster.
