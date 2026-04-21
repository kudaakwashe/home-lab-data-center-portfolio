# Lab Overview

## 🎯 Objective

The goal of this lab is to build a realistic, small-scale data center environment using enterprise-grade hardware.

This lab is designed to develop practical skills in:

* Network configuration
* Hardware validation
* Structured cabling
* Virtualization
* Troubleshooting

---

## 🧱 Lab Design

This lab follows a simplified enterprise network structure:

* Access layer (Cisco switch)
* Structured cabling (patch panel)
* Compute layer (mini PC running virtual machines)

---

## 🏗️ Architecture

The lab is built around three core components:

### 1. Network Layer

* Cisco Catalyst 2960X switch
* VLAN-based segmentation (planned)

### 2. Compute Layer

* Lenovo ThinkCentre M710q Tiny
* Will host virtual machines using Proxmox

### 3. Physical Infrastructure

* 2-post rack with shelves
* Patch panel for structured cabling
* Short patch cables for clean layout

---

## 🔄 Data Flow (Simplified)

Devices connect through the patch panel into the switch, where traffic is segmented using VLANs and routed to services hosted on virtual machines.

---

## 📈 Design Principles

This lab is built with the following principles:

* **Simplicity** → Keep design easy to understand
* **Realism** → Mirror real-world setups
* **Scalability** → Allow future expansion
* **Clean cabling** → Improve troubleshooting and visibility

---

## 🚀 Planned Enhancements

* VLAN segmentation and isolation
* Inter-VLAN routing
* DHCP and DNS services
* Monitoring and logging

---

## 🧠 Key Learning Goals

* Understand how physical and logical networking interact
* Gain hands-on experience with Cisco CLI
* Practice troubleshooting real network issues
* Learn how to document technical work effectively
