# OPNsense Firewall VM

## 📌 Overview

OPNsense was added to the homelab environment to provide:

- Firewalling
- Routing
- NAT
- DHCP services
- Network segmentation
- Future VLAN support
- Security policy management

The firewall VM acts as the central gateway between the internal virtualization environment and the internet.


---

## 🛠️ Architecture Role

OPNsense sits between:

- Internet router/modem
- Managed switch
- Proxmox virtual machines

This creates a more realistic enterprise-style network architecture.


---

## 🔌 Interfaces

| Interface | Purpose |
|---|---|
| WAN | Upstream internet connection |
| LAN | Internal homelab network |


---

## 🧾 Current Services

- NAT
- DHCP
- Firewall
- Routing
- Gateway services


---

## 🌐 Internal Network

| Device | IP Address |
|---|---|
| OPNsense LAN | 192.168.10.254 |
| Proxmox Host | 192.168.10.50 |
| Ubuntu Web Server | 192.168.10.60 |
| Netdata Monitoring | 192.168.10.70 |


---

## 🧰 Skills Demonstrated

This project demonstrates practical skills in:

- Virtual firewall deployment
- Interface configuration
- NAT and routing
- Linux virtualization
- Network troubleshooting
- Infrastructure design
- Layer 2 networking
- Gateway management


---

## 🎯 Planned Enhancements

Future work includes:

- VLAN segmentation
- IDS/IPS
- VPN access
- DNS filtering
- Advanced firewall rules
- Traffic monitoring
- Multi-network architecture