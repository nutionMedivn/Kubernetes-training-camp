# Kubernetes The Hard Way

## Cluster Details

高可用、端到端加密和RBAC认证的集群

- kubernetes v1.18.6
- containerd v1.3.6
- coredns v1.7.0
- cni v0.8.6
- etcd v3.4.10

## 安装工具

### CFSSL

`packages/`目录下有cfssl和cfssljson的二进制程序，请在其中之一节点安装CFSSL。

### kubectl

请在三个master节点上分别安装`kubectl`