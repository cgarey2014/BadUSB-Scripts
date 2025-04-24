# 🔐 Passwords Extractor

**Author:** Chris Garey  
**Original Script:** [`password_steal.txt`](https://github.com/cgarey2014/BadUSB-Scripts/blob/main/Passwords/Credential_Steal/password_steal.txt)  
**Target:** Windows  
**Category:** BadUSB / Credential Harvesting

---

## 📜 Description

This BadUSB payload is designed to extract saved browser passwords from a Windows target machine and exfiltrate the data via SSH. It utilizes [WebBrowserPassView](https://www.nirsoft.net/utils/web_browser_password.html) by NirSoft to recover stored credentials and displays the results in a local HTML file before securely uploading them to a remote server. Finally, the script clears evidence from the event logs to minimize traceability.

---

## ⚙️ Features

- Downloads and extracts NirSoft’s WebBrowserPassView
- Automates password export to HTML
- Uploads stolen credentials to a remote SSH server
- Displays results briefly in an incognito browser session
- Clears PowerShell, System, Application, and Security logs

---

## 🛠️ Requirements

- A BadUSB-compatible device (e.g., Flipper Zero, Rubber Ducky)
- Target machine must have:
  - PowerShell enabled
  - Internet access to download tools
  - OpenSSH client installed and available in PATH
- Remote SSH server credentials (edit script to reflect your IP and credentials)

---

## 🚨 Disclaimer

This script is intended for **educational and authorized penetration testing** purposes only. Unauthorized use of this script against systems you do not own or have explicit permission to test is strictly prohibited and illegal. The author assumes **no responsibility** for misuse or damages resulting from this tool.

---

## 🧠 Usage

1. Modify the following values in the script:
   - `ssh user@192.168.0.1` → your SSH server address and username
   - `yourpassword` → replace with your SSH password
   - Update
