# nmap_scan_task-1
# 🔍 Local Network Port Scan using Nmap (WSL)

This project demonstrates how to scan your local network for open ports using **Nmap** inside a **WSL (Windows Subsystem for Linux)** environment. It includes scan results, basic analysis, and a breakdown of potential security risks.

---

## 📌 Task Objective

Perform a TCP SYN scan across the local network to:
- Identify active devices (IP addresses)
- List open TCP ports on each device
- Analyze potential services running and assess security risks

---

## 🛠 Tools & Technologies

- **WSL (Ubuntu)**
- **Nmap** – Network Mapper
- **Wireshark** (optional, for packet analysis)

---

## 🚀 How to Run the Scan

### 1. Update System & Install Nmap
```bash
sudo apt update && sudo apt install nmap -y
