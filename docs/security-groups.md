# Security Group Specifications

## Bastion Security Group

- Ingress: SSH (22) restricted to corporate VPN IP ranges.
- Egress: Internal subnets only (`10.100.0.0/16`).

## Web Tier Security Group

- Ingress: HTTP (80) & HTTPS (443) from ALB.
- Egress: App tier instances (`10.100.10.0/24`).
