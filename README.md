# 🔍 Nmap Network Scan Report

This repository contains the results and documentation for a local network scan performed using **Nmap**. The scan helps identify active devices, open ports, and potential security risks on a local subnet.

---

## 📌 Objectives

- Discover active hosts on the local network
- Identify open ports and running services
- Analyze network traffic (optional with Wireshark)
- Assess potential vulnerabilities
- Store scan results for documentation and future reference

---

## 🧪 Scan Procedure

1. **Install Nmap**
   - Download and install from the [official Nmap website](https://nmap.org/).

2. **Identify Your IP Range**
   - Example: `192.168.1.0/24`

3. **Run TCP SYN Scan**
   ```bash
   nmap -sS 192.168.1.0/24
