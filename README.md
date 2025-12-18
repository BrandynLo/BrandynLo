# Hi, I’m **Brandyn** 👋
I am currently a student at the University of Minnesota Twin Cities, and am interested in Cloud Infrastructure and IaC.

---
## Current Stack

| Tool                       | What I Do With It                                                      |
|----------------------------|------------------------------------------------------------------------|
| **Terraform**               | Provision OCI VMs and IBM Kubernetes Clusters available through Tailscale |
| **Oracle Cloud Containers** | Deploy private cloud networks, VMs, NAT gateways, bastion hosts         |
| **IBM Kubernetes**          | Orchestrate containerized apps with Terraform & TailScale               |

---
## What I’m Building Right Now

```mermaid
graph LR
    A[Terraform] --> B[Provision Kubernetes Clusters on IBM Cloud]
    B --> C[IBM Kubernetes Cluster IKS]
    C --> D[Flask/Docker Web Application]
    D --> E[Cloudflare WAF, DNS, SSL/TLS Termination]
    C --> F[Tailscale Remote Management]

    G[Terraform] --> H[Provision VMs on Oracle Cloud]
    H --> I[Ansible Automated Apache Web Hosting]
    I --> J[Apache Web Server Configuration]
    H --> K[Configure VCN Routing and Security]
    K --> L[Private Key Authentication for Secure Access]
