# TASK$ 


# **Firewall Configuration & Traffic Filtering (UFW/Windows Firewall)**

## 📌 **Overview**

This project demonstrates the basic configuration of host-level firewall rules on Linux using **UFW (Uncomplicated Firewall)**. The goal is to understand how firewall policies control network traffic, secure services, and restrict unauthorized access.

---

## 🚀 **Steps Performed**

### **1. Enable UFW**

```bash
sudo ufw enable
```

### **2. Check Active Rules**

```bash
sudo ufw status numbered
```

### **3. Block Telnet (Port 23)**

```bash
sudo ufw deny 23
```

### **4. Allow SSH Access**

```bash
sudo ufw allow 22
```

### **5. Remove Rule**

```bash
sudo ufw delete <rule-number>
```

---

## 📷 **Screenshots**

(Add the screenshots you captured while running the commands.)

---

## 🔒 **Understanding Firewall Filtering**

A firewall evaluates every packet entering or leaving the system and makes a decision based on:

* **Port number** (e.g., 22 for SSH, 80 for web traffic)
* **Protocol** (TCP/UDP)
* **Source or destination IP address**

By applying these rules, the firewall protects the system from:

* Unauthorized access attempts
* Exposure to unsafe services
* Port scanning and reconnaissance
* Malicious or unwanted traffic

---

## 📁 **Project Deliverables**

* Firewall rule configurations
* Screenshots of applied rules
* Documentation explaining each step

---

## ✅ **Conclusion**

This project shows how simple rule-based configuration can significantly improve system security. UFW provides an easy and effective method to manage access control on Linux systems.

---



Just tell me!

