# kali-linux-hacking-lab
Ethical hacking lab using Kali Linux, Metasploitable2, and common penetration testing tools

# Kali Linux Hacking Lab (Ethical Penetration Testing Environment)

This project documents how I created a secure, self-contained hacking lab using **Kali Linux**, **VirtualBox**, and intentionally vulnerable systems like **Metasploitable2** and **DVWA**. The lab was designed for ethical hacking practice, penetration testing, and real-world cybersecurity training in a legal environment.

---

## 🔧 Tools & Technologies Used

- **Kali Linux** – Penetration testing distribution
- **VirtualBox** – Virtual machine management
- **Metasploitable2** – Intentionally vulnerable Linux machine
- **DVWA** – Damn Vulnerable Web App (optional)
- **Nmap**, **Metasploit**, **Burp Suite**, **Wireshark**

---

## ⚙️ Lab Setup

### 1. Virtual Environment
- Installed VirtualBox on host machine (Windows 11, 8GB RAM)
- Created a Kali Linux VM (2GB RAM, 20GB disk)
- Imported Metasploitable2 VM as the target system

### 2. Network Configuration
- Both VMs set to **Host-Only Adapter**
- Verified both machines are on the same subnet using `ip a` or `ifconfig`

---

## 💻 Penetration Testing Scenarios

### Port Scanning (Nmap)
```bash
nmap -sV 192.168.56.101
