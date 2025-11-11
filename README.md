# Hi, I’m **Brandyn** 👋

I’m interesting in becoming a Cloud Infrastructure Engineer and am currently a student at the University of Minnesota Twin Cities. 

---

## Current Stack 

| Tool | What I Do With It |
|------|-------------------|
| **Terraform** | Provision OCI VCNs, private subnets, security lists, compute instances  |
| **Puppet** | Automate Apache web servers|
| **Oracle Cloud Containers** | Deploy private cloud networks, VMs, NAT gateways, bastion hosts |
| **IBM Kubernetes** | Orchestrate containerized apps with Terraform & Ansible |
| **Apache** | Build hardened web tiers with automated config management |


---

## What I’m Building Right Now

```mermaid
graph LR
    A[Terraform] --> B[OCI Private VCN]
    B --> C[Compute VM]
    C --> D[Puppet Agent]
    D --> E[Apache + TLS + ModSecurity]
    F[IBM IKS Cluster] --> G[VPN Tunnel to OCI]
    E --> H[Internal Microservices]
    H --> I[Zero-Trust Ingress]
