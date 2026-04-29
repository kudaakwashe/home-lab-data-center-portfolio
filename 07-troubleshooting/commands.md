# 🧰 Troubleshooting Command Toolkit

## 🌐 Networking

ip a
ip route
ping <ip>
traceroute <ip>
ss -tulnp


---

## 🔌 Interface Checks

ip link show
sudo ip link set ens18 down
sudo ip link set ens18 up


---

## 🔐 SSH

ssh user@ip
ssh -v user@ip
ssh-keygen -R <ip>


---

## 🖥️ System

top
df -h
journalctl -xe


---

## 🧪 Proxmox

qm list
qm start <vmid>
qm terminal <vmid>


---

## 📚 Key Learning

* Start simple (ping, ip a)
* Move layer by layer
* Use logs when needed
