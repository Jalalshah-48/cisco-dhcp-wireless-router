# 🌐 Project 1: Configure DHCP on a Wireless Router

![Cisco Packet Tracer](https://img.shields.io/badge/Tool-Cisco%20Packet%20Tracer-blue)
![Level](https://img.shields.io/badge/Level-Beginner-green)
![Topic](https://img.shields.io/badge/Topic-DHCP%20%7C%20Networking-orange)

## 📋 Project Overview

This project demonstrates how to configure a **DHCP (Dynamic Host Configuration Protocol) server** on a wireless router using Cisco Packet Tracer. DHCP is a fundamental networking protocol that automatically assigns IP addresses to devices on a network — eliminating the need for manual configuration.

---

## 🎯 Objectives

- Configure DHCP server settings on a wireless router
- Define IP address pool for automatic assignment
- Connect wireless clients to the router
- Verify that devices receive IP addresses automatically
- Understand subnet masks, default gateways, and DNS settings

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Cisco Packet Tracer | Network simulation and configuration |
| Wireless Router | DHCP server and network gateway |
| End Devices (PCs/Laptops) | DHCP clients for testing |

---

## 📚 Concepts Covered

- **DHCP Protocol** — How automatic IP assignment works
- **IP Addressing** — Subnetting, address pools, and ranges
- **Default Gateway** — Routing traffic outside the local network
- **DNS Server Configuration** — Domain name resolution
- **Network Verification** — Using `ipconfig` and `ping` to confirm connectivity

---

## 🔧 Configuration Steps

### Step 1: Router Setup
- Opened Cisco Packet Tracer and loaded the network topology
- Accessed the wireless router's GUI interface

### Step 2: DHCP Pool Configuration
- Navigated to DHCP settings on the router
- Set start IP address for the pool
- Defined maximum number of users
- Configured subnet mask
- Set default gateway (router's IP)
- Added DNS server address

### Step 3: Client Configuration
- Set end devices to obtain IP automatically (DHCP mode)
- Verified IP assignment via `ipconfig` command

### Step 4: Connectivity Testing
- Used `ping` command to test communication between devices
- Verified internet simulation connectivity

---

## ✅ Results

- All connected devices successfully received unique IP addresses from the DHCP pool
- Network communication verified between all clients
- Default gateway and DNS resolved correctly

---

## 💡 Key Learnings

- DHCP eliminates manual IP configuration, reducing human error
- Properly sized IP pools prevent address exhaustion
- Default gateway must match the router's LAN IP for routing to work
- Understanding DHCP is essential for network administration and cybersecurity (DHCP spoofing attacks)

---

## 🔗 Related Concepts to Explore Next

- DHCP Snooping (security feature)
- Static IP vs Dynamic IP
- DHCP Starvation Attack
- ARP Protocol

---

## 📁 Files in This Repository

```
project1-dhcp/
├── README.md                                   ← This file
└── Configure_DHCP_on_a_Wireless_Router.pka    ← Packet Tracer activity file
```

> **Note:** To open the `.pka` file, you need Cisco Packet Tracer installed.  
> Download free at: [Cisco NetAcad](https://www.netacad.com)

---

## 👤 About Me

Self-learning cybersecurity through Cisco's curriculum.  
Currently building hands-on lab projects to strengthen my practical skills.

📌 Connect with me on [LinkedIn](#)https://www.linkedin.com/in/jalal-shah-98a03a265/
