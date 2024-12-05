# Oficina Kubernetes


### Comando para criar o cluster Kubernetes local com K3D:

```bash
k3d cluster create meucluster --servers 3 --agents 3 -p "30000:30000@nodeport"
```