# DHCP and DNS Configuration Using Cisco Packet Tracer

## 📌 Project Overview
This project demonstrates the design and implementation of a multi-LAN network using Cisco Packet Tracer with:

- Centralized DHCP Server
- Centralized DNS Server
- Multiple routed LANs
- Automatic IP assignment
- Name resolution using DNS

## 🗺️ Network Topology
The network consists of:
- 1 Router
- 3 LANs with PCs
- 1 DHCP Server
- 1 DNS Server

## 🧱 IP Addressing Scheme

| Network | Purpose | Gateway |
|--------|----------|----------|
| 192.168.0.0/24 | Server Network | 192.168.0.1 |
| 192.168.1.0/24 | LAN 1 | 192.168.1.1 |
| 192.168.2.0/24 | LAN 2 | 192.168.2.1 |
| 192.168.3.0/24 | LAN 3 | 192.168.3.1 |

## ⚙️ Configuration Summary

- Router interfaces were configured and enabled.
- DHCP server was configured with 3 pools.
- DHCP relay (ip helper-address) was configured on the router.
- DNS server was configured with domain records.
- PCs were set to obtain IP addresses automatically.

## 🧪 Testing & Verification

- Clients successfully received IP addresses via DHCP.
- Successful ping between networks.
- Successful name resolution using:
