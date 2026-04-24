# 🖧 Home Lab Data Center Portfolio

## 📌 Overview

This project documents my hands-on home lab where I am building and operating a small-scale data center environment using enterprise-grade hardware.

## 🎯 Objectives

* Learn Cisco switching (VLANs, ports, configuration)
* Build structured cabling setup
* Set up a rack for the equipment
* Validate and test network hardware
* Run virtualization workloads
* Practice troubleshooting

---

## 🧰 Lab Equipment

### Network

**Cisco Catalyst 2960X-24TS-L**


![Switch Front](assets/cisco-2960x-front.jpg)

* [Documentation](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst2960x/hardware/installation/guide/b_c2960x_hig.pdf)



### Compute

**Lenovo ThinkCentre M710q Tiny**

![PC Front](assets/lenovo-m710q-front.jpg)

Specs:
* 16GB RAM
* 256GB SSD
* i5 7th Generation
* [Documentation](https://download.lenovo.com/pccbbs/thinkcentre_pdf/m710q_10yc_ug_en.pdf)
    


### Infrastructure

* 4U 2-post rack with shelves
* Patch panel
* 25cm Cat6 cables

---

## 🧪 Hardware Validation

### Cisco Catalyst 2960X-24TS-L Initial Hardware Tests.


| Test | Result | Observations |
|------|--------|--------------|
| Physical Inspection | Very good | Ports: excellent, no bent pins |
| Physical Inspection | Very good | Case: good, minor cosmetic wear only |
| Physical Inspection | Very good | Power socket: Firm and straight |
| Physical Inspection | Very good | Fans: not blocked, minimal dust |
| Power-on test | Excellent | LEDs flash briefly, system LED turn green |
| Power-on test | Excellent | Fan runs smooth, no grinding or clicking |
| Boot Process | Excellent | LEDs stable, switch is quiet, no reboot loop |
| Console access | TBA | Console cable working using PuTTY |
| Port LED test | Excellent | All port LEDs light |
| Loopback test | TBA | Pending loopback cable test |

➡️ **Result:** Switch testing is still in progress

---

### Lenovo ThinkCentre M710q Tiny Initial Hardware Tests


| Test | Result | Observations |
|------|--------|--------------|
| Physical Inspection | Very good | Ports: USB and Ethernet ports show no physical damage |
| Physical Inspection | Very good | Case: → minor cosmetic scratches only |
| Physical Inspection | Very good | Power: socket is firm |
| Physical Inspection | Very good | Wifi antenna: missing, not required for this wired lab |
| Power-on test | Excellent | Power indicator green, Storage indicator green |
| Power-on test | Excellent | Fan runs smoothly, no grinding or clicking |
| Boot Process | Pass | Boots into Windows |
| BIOS Check | TBA | Virtualization setting still to be confirmed |

➡️ **Result:** mini PC testing is still in progress

---

## 🚀 Status

🟢 Hardware setup in progress
🟡 Network configuration pending
🔵 Virtualization setup pending
