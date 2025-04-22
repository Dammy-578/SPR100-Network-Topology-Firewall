# SPR100-Network-Topology-Firewall
Multi-VM network setup with firewall traffic control using nftables. Includes SSH, web access, and ICMP restrictions. Completed for SPR100 at Seneca Polytechnic.
# Multi-VM Network Topology & Firewall Rules – SPR100 Assignment 3

**Course:** SPR100 – Introduction to Security  
**Date:** November 2024  
**Institution:** Seneca Polytechnic

---

## 🧠 Overview
This project involved setting up and managing a secure local area network (LAN) using multiple virtual machines. Each VM was assigned a static IP address and role (Web, SSH, Win), and firewalls were configured using `nftables` to restrict or allow traffic based on specific rules. Traffic control demonstrations were captured and documented via screenshots.

---

## 🛠️ Topology Features
- Static IP configuration across Ubuntu, Kali, and Windows VMs
- Traffic control using `nftables` on Linux systems
- Blocking of HTTP, ICMP (ping), and SSH as per topology levels (D, C, B, A)
- Web queries tested using IP and FQDN (if DNS was implemented)
- Optional TLS encryption and secure web access for "A" level implementation

---

## 🔐 Firewall Demonstrations
- Created an `inet` filter table with input/output chains
- Allowed specific traffic and denied all other by default
- Verified rule behavior through live ping/web/SSH tests

---

## 📎 Files Included
- `Assignment 2.docx`: Contains screenshots of firewall setup, blocking ping/web traffic, and connectivity tests

---

## 🧠 Skills Demonstrated
- nftables  
- Network Security  
- Linux System Administration

---

## ✅ Project Status
- ✔️ Completed and submitted  
- ✔️ Screenshots included in final report  
- ✔️ All firewall rules tested and verified
