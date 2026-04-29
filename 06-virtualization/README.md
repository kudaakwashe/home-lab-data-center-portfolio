# 06 - Virtualization Lab (Proxmox)

## 📌 Overview
This section documents the setup and configuration of a virtualization environment using Proxmox VE. The goal of this lab is to simulate a real-world data center environment by deploying and managing virtual machines.


---

## 🧱 Lab Architecture

Laptop → Managed Switch → Proxmox Host → Virtual Machines

- Proxmox host IP: 192.168.10.50
- Ubuntu VM IP: 192.168.10.60
- Network: 192.168.10.0/24


---

## ⚙️ Technologies Used

- Proxmox VE (Hypervisor)
- Ubuntu Server 24.04 LTS
- SSH (Remote access)
- VLAN-ready switching environment


---

## 🎯 Objectives

- Install and configure Proxmox VE
- Create and manage virtual machines
- Configure VM networking
- Enable SSH access to VMs
- Simulate a production-like environment


---

## 📡 Network Design Notes

- Flat Layer 2 network used for initial lab setup
- Static IP addressing configured on VM
- SSH used for remote administration
- Designed for future VLAN segmentation (VLAN 10 / VLAN 20)
- Trunking to be considered for future upgrades

![Network Virtualisation](../assets/network-diagram-virtualisation.png)


---

## ✅ Key Achievements

- Successfully deployed Proxmox VE
- Created Ubuntu Server VM
- Configured static IP addressing
- Enabled SSH remote access
- Verified network connectivity (Layer 2)


---

## 🔍 Validation

Validation done by ping command and ssh remote access to the Ubuntu VM (IP: 192.168.10.60) on the Proxmox host from laptop (IP: 192.168.10.30)

![Ubuntu VM](../assets/ubuntu-vm-ping-ssh.png)
