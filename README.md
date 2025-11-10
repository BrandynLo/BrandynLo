# Hi, I’m **Brandyn** 👋

I’m interesting in becoming a Cloud Infrastructure Engineer and am currently a student at the University of Minnesota Twin Cities. 

---

## Current Stack 

| Tool | What I Do With It |
|------|-------------------|
| **Terraform** | Provision OCI VCNs, private subnets, security lists, compute instances – **fully IaC** |
| **Puppet** | Automate Apache web servers: `mod_security`, TLS, reverse proxy, CIS-hardening |
| **OCI** | Deploy private cloud networks, VMs, NAT gateways, bastion hosts |
| **IBM Kubernetes (IKS)** | Orchestrate containerized apps with secure networking to OCI |
| **Apache** | Build hardened web tiers with automated config management |
| **Linux / Bash** | Glue everything together with scripts that never break in prod |

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
