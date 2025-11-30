# Hi, I’m **Brandyn** 👋
I am currently a student at the University of Minnesota Twin Cities, and am interested in Cloud Infrastructure and IaC.

---
## Current Stack

| Tool                       | What I Do With It                                                      |
|----------------------------|------------------------------------------------------------------------|
| **Terraform**              | Provision OCI VMs and IBM Kubernete Clusers avaliable through Tailscale |
| **Oracle Cloud Containers**| Deploy private cloud networks, VMs, NAT gateways, bastion hosts         |
| **IBM Kubernetes**         | Orchestrate containerized apps with Terraform & TailScale               |
---
## What I’m Building Right Now

```mermaid
graph LR
    A[Terraform] --> B[OCI Private VCN]
    B --> C[Compute VM]
    C --> D[Puppet Agent]
    F[IBM IKS Cluster] --> G[VPN Tunnel to OCI]
