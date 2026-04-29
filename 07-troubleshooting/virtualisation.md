# 🖥️ Virtualisation Troubleshooting

## 🧩 Issue 6: VM Not Getting IP

### 🔍 Symptoms

ip a → no IP


### 🧠 Root Cause

* DHCP unavailable or misconfigured


### ✅ Resolution

Configured static IP:

sudo nano /etc/netplan/*.yaml
sudo netplan apply


---

## 🧩 Issue 7: VM Cannot Reach Network

### 🔍 Symptoms

* IP assigned but no connectivity


### 🧠 Root Cause

* Incorrect Proxmox bridge configuration


### ✅ Resolution

* Verified `vmbr0` mapping to physical NIC


---

## 🧩 Issue 8: SSH Connection Refused

### 🔍 Symptoms

Connection refused


### 🧠 Root Cause

* SSH not installed or running


### ✅ Resolution

sudo apt install openssh-server
sudo systemctl start ssh


---

## 🧩 Issue 9: Host Key Verification Failed

### 🔍 Symptoms

Host key verification failed


### 🧠 Root Cause

* Changed or new SSH key


### ✅ Resolution

ssh-keygen -R 192.168.10.60


---

## 📚 Key Learning

* Virtual networking depends on correct bridge configuration
* Services must be running, not just installed
