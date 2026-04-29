# 🌐 Networking Troubleshooting

## 🧩 Issue 3: Cannot Reach Gateway

### 🔍 Symptoms

ping 192.168.10.1 → success
ping 8.8.8.8 → fail


### 🧠 Root Cause

* Missing or incorrect routing


### ✅ Resolution

ip route

* Verified default gateway configuration


---

## 🧩 Issue 4: DNS Not Working

### 🔍 Symptoms

ping 8.8.8.8 → works
ping google.com → fails


### 🧠 Root Cause

* DNS not configured


### ✅ Resolution

sudo nano /etc/resolv.conf

Added:

nameserver 8.8.8.8


---

## 🧩 Issue 5: Wrong IP Configuration

### 🔍 Symptoms

* Device unreachable
* IP mismatch


### 🧠 Root Cause

* Incorrect subnet/gateway settings


### ✅ Resolution

* Corrected IP configuration


---

## 📚 Key Learning

* Always test:

  * IP → Gateway → Internet → DNS
