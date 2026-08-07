# Sec Fundamentals

Practical, hands-on security write-ups and white papers by CP Drid.

Security fundamentals are timeless, but the environments we apply them to keep changing. Least privilege, segmentation, strong identity, and good visibility mattered on a flat VLAN twenty years ago, and they matter just as much between pods in a cluster today. What changes is how you implement them. This repository collects the longer-form pieces where I write that down: standalone papers meant to be read, applied, and kept.

Companion to the Sec Fundamentals blog at https://secfun8.wordpress.com.

## Papers

| Title | Topic | Link |
| --- | --- | --- |
| Kubernetes RBAC and Pod Security: Least Privilege Inside the Cluster | RBAC, service accounts, Pod Security Standards, policy as code, cluster audit | [PDF](papers/RBAC_PodSecurity_LeastPrivilege_whitepaper.pdf) |
| Kubernetes Ingress Security: Hardening the Edge with Traefik and Ambassador | Ingress, TLS, edge auth, WAF, least-privilege routing | [PDF](Ingress_Security_Traefik_Ambassador_whitepaper.pdf) |

## Topics covered

- Kubernetes and cloud-native security: network policy, ingress, runtime
- Zero trust and least privilege in practice
- Identity, encryption, and secure configuration
- Security operations: visibility, logging, and SIEM integration

## Structure

- `papers/` holds each standalone paper as a PDF
- Other folders will be added as the collection grows beyond papers

## About the author

CP Drid is a network and infrastructure engineer with more than two decades securing enterprise and mission-critical networks, from traditional route and switch and data center design through modern cloud-native and Kubernetes environments. These pieces are published under a handle to keep the focus on the ideas.
