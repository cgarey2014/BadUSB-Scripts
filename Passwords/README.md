# 🔑 BadUSB Password Extraction Scripts

**Author:** Chris Garey  
**Repository:** [BadUSB-Scripts](https://github.com/cgarey2014/BadUSB-Scripts)  
**Category:** BadUSB / Credential Harvesting / Windows Exploitation

---

## 📜 Description

This directory contains various **BadUSB scripts** designed to extract sensitive information, specifically saved **passwords** from browsers and systems running Windows. These scripts can be executed on a target machine via USB devices like Flipper Zero or Rubber Ducky. The extracted passwords are typically exfiltrated to a remote location for further analysis, such as uploading to an SSH server or sending them via Discord Webhook.

Each script in this directory serves a specific purpose in credential harvesting, and they can be used individually or as part of a red team engagement or penetration test.

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
  - An active internet connection for tool download (if required)
  - OpenSSH client installed and available in the system's PATH (for SSH exfiltration)

---

## 🧠 Usage

1. **Modify the scripts**:
   - Update URLs and credentials (e.g., SSH server, Discord Webhook URL)
   - Ensure that target directories and paths are properly configured

2. **Deploy to BadUSB device**:
   - Flash the modified script onto your BadUSB device.

3. **Execute on Target System**:
   - Plug the USB device into the target system, and the script will execute automatically.

4. **Monitor the exfiltrated data**:
   - Check your remote server (SSH, Discord Webhook, etc.) for the exfiltrated passwords or keys.

---

## 📌 License

This project is distributed for educational purposes under the [MIT License](https://opensource.org/licenses/MIT).

