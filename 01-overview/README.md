# Lab Overview

## 🎯 Purpose

This home lab is designed to simulate a small-scale data center environment using real networking hardware, structured cabling, and a virtualized compute platform.

The goal is to build practical skills relevant to data center technician, field technician, and junior network support roles.

---

## Lab Objectives

- Validate and document enterprise hardware
- Build a structured cabling setup using a patch panel
- Configure Cisco switching features
- Deploy virtual machines on a mini PC
- Practice troubleshooting real network issues
- Document the full process as a technical portfolio

---

## 🧱 Lab Design

### Design Principles

This lab is built with the following principles:

- **Simplicity** → Keep the lab simple and realistic
- **Realism** → Use enterprise-style components where possible & treat the lab like a real operational environment
- **Traceability** → Document every step clearly to improve troubleshooting and visibility
- **Scalability** → Build small, testable sections before adding complexity

### Core Components
This lab follows a simplified enterprise network architecture, structured into key layers:

#### Access Layer
- Cisco Catalyst 2960X switch
- Responsible for connecting end devices
- Handles VLAN segmentation and port configuration

#### Cabling Layer
- Patch panel with structured Cat6 cabling
- Implements T568B termination standard
- Separates permanent cabling from switch connections

#### Compute Layer
- Lenovo ThinkCentre M710q Tiny
- Hosts virtual machines for testing and simulation
- Will be used for services such as Linux servers and network tools

#### Routing Layer
- Home router (with potential future upgrade to a dedicated router)
- Provides default gateway, DHCP, and internet connectivity

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

* 4U 2-post rack with shelves
* Patch panel for structured cabling
* Short patch cables for clean layout

---

## 🔄 Data Flow (Simplified)

Devices connect through the patch panel into the switch, where traffic is segmented using VLANs and routed to services hosted on virtual machines.

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
* Incoporate safety and environmental awareness in all tasks

---

## 🛠️ Skills Demonstrated

| Skill Area          | Practical Work                                        |
| ------------------- | ----------------------------------------------------- |
| Hardware validation | Power-on tests, fan checks, port inspection           |
| Networking          | Switch access, VLAN planning, port testing            |
| Cabling             | Patch panel wiring, T568B termination, cable labeling |
| Virtualization      | Proxmox and Linux VM setup                            |
| Troubleshooting     | Link issues, cable faults, VLAN misconfiguration      |

---

## 🚧 Current Status

| Area                  | Status      |
| --------------------- | ----------- |
| Hardware acquired     | Complete    |
| Switch validation     | In progress |
| Mini PC validation    | In progress |
| Rack setup            | Complete |
| Cabling               | Planned     |
| Network configuration | Planned     |
| Virtualization        | Planned     |




