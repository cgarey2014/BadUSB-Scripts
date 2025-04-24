# 🛡️ Cyber Security Setup for Ubuntu

**Author:** Chris Garey  
**Date:** 6/26/2024  
**Repository:** [BadUSB-Scripts](https://github.com/cgarey2014/BadUSB-Scripts)  
**Category:** Setup / Cyber Security / Ubuntu

---

## 📜 Description

This script automates the process of **setting up a cybersecurity environment** on an Ubuntu system. It configures **UFW** (Uncomplicated Firewall), allows **OpenSSH** access, and installs essential cybersecurity tools for penetration testing, network analysis, and ethical hacking. These tools are commonly used for tasks like vulnerability scanning, password cracking, network sniffing, and exploitation.

---

## ⚙️ Script Overview

### **cyber_sec.txt**
   - **Description:** This script prepares an Ubuntu machine for cybersecurity-related tasks by setting up the firewall, allowing SSH access, and installing critical tools for ethical hacking and security research.
   - **Target:** Ubuntu (Linux)
   - **Key Features:**
     - Enables **UFW** and allows OpenSSH for remote access.
     - Installs a variety of **penetration testing tools** like **Nmap**, **Wireshark**, **Metasploit**, and more.
     - Updates and upgrades the system to ensure all packages are up-to-date.

---

## 🚨 Disclaimer

**This script is intended for educational and authorized penetration testing purposes only.**  
**Unauthorized use on systems you do not own or have explicit permission to test is illegal and unethical.**  
The author assumes no responsibility for the misuse of these tools. Always ensure that you have proper authorization before executing these scripts.

---

## 🛠️ Requirements

- **Target Machine:**
  - Running **Ubuntu** (or a compatible Debian-based distribution)
  - Sudo privileges to run system-level commands
  - Active internet connection to install necessary packages

---

## 🧠 Usage

1. **Deploy the script**:
   - Save the script to your **BadUSB** device or run it directly on your Ubuntu machine.

2. **Run the script**:
   - Execute the script to:
     - Enable **UFW** (Uncomplicated Firewall) and allow **OpenSSH** through the firewall.
     - Install essential **cybersecurity tools** used for penetration testing and ethical hacking.

3. **Check the status**:
   - The script will display the status of **UFW** to confirm the firewall is active and SSH is allowed.

4. **Post-setup**:
   - The script installs a variety of essential tools. Once completed, your machine will be ready for penetration testing and other cybersecurity tasks.

---

## 📌 License

This project is distributed for educational purposes under the [MIT License](https://opensource.org/licenses/MIT).

