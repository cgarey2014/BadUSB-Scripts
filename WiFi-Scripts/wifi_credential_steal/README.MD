# 🛸 Windows Wifi Password Exfiltration Script

**Author:** Chris Garey  
**Repository:** [BadUSB-Scripts](https://github.com/cgarey2014/BadUSB-Scripts)  
**Category:** BadUSB / Wifi Password Extraction / Windows Exploitation

---

## 📜 Description

This script is designed to **extract saved WiFi passwords** from a Windows machine and send them to a remote Discord server via a **Webhook**. The script works by using PowerShell commands to gather all saved WiFi profiles and their respective passwords, then sends the information to a Discord channel for exfiltration.

The script is intended for educational and authorized penetration testing purposes. Ensure you have the proper permissions before using this script on any system.

---

## ⚙️ Script Overview

### **wifi_steal.txt**
   - **Description:** Automatically extracts all stored WiFi passwords from a Windows machine and sends them to a Discord Webhook for remote retrieval.
   - **Target:** Windows
   - **Key Features:**
     - Extracts saved WiFi profiles and their associated passwords using built-in `netsh` commands.
     - Sends the retrieved passwords to a Discord server via Webhook.
     - Fully automated, designed for BadUSB execution.

---

## 🚨 Disclaimer

**This repository and its scripts are intended for educational and authorized penetration testing purposes only.**  
**Unauthorized use of these scripts on systems you do not own or have explicit permission to test is illegal and unethical.**  
The author assumes no responsibility for the misuse of these tools. Always ensure that you have proper authorization before executing these scripts on any target system.

---

## 🛠️ Requirements

- **BadUSB-compatible device** (e.g., Flipper Zero, Rubber Ducky)
- **Target machine must have:**
  - PowerShell enabled
  - An active internet connection for exfiltration (Discord Webhook)
  - Administrative privileges (if required) to access stored WiFi passwords

---

## 🧠 Usage

1. **Modify the script**:
   - Replace `YOUR_WEBHOOK_HERE` with your Discord Webhook URL.

2. **Deploy to BadUSB device**:
   - Flash the modified script onto your BadUSB device.

3. **Execute on Target System**:
   - Plug the USB device into the target system, and the script will execute automatically.

4. **Monitor the exfiltrated data**:
   - Check your Discord channel for the exfiltrated WiFi passwords.

---

## 📌 License

This project is distributed for educational purposes under the [MIT License](https://opensource.org/licenses/MIT).
