# Network Topology

## Subnet Allocation

- Public Subnets: `10.100.1.0/24`, `10.100.2.0/24` (Load Balancers, Bastion)
- Private Subnets: `10.100.10.0/24`, `10.100.20.0/24` (App Nodes)
- Database Subnets: `10.100.30.0/24`, `10.100.40.0/24` (Isolated Data Tier)

## Access Controls

All internal node access requires SSH key-based authentication routed through bastions or VPN gateway.
