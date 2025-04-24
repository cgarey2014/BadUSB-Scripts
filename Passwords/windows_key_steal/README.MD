# 🔑 Windows Key Extractor

**Author:** Chris Garey  
**Original Script:** [`windows_key_steal.txt`](https://github.com/cgarey2014/BadUSB-Scripts/blob/main/windows_key_steal.txt)  
**Target:** Windows  
**Category:** BadUSB / Information Gathering

---

## 📜 Description

The **Windows Key Extractor** is a BadUSB payload designed to extract the Windows product key from a target machine and send it to a specified Discord server channel. This script utilizes PowerShell to query the system's licensing service and retrieve the product key. The key is then exfiltrated by making a POST request to a Discord Webhook URL, allowing for quick and covert extraction of valuable system information.

---

## ⚙️ Features

- Extracts the Windows product key using PowerShell
- Sends the extracted product key to a Discord channel via Webhook
- Completely automated and stealthy execution
- Ideal for red team engagements or ethical hacking demonstrations
- Works on Windows-based systems with PowerShell enabled

---

## 🛠️ Requirements

- A BadUSB-compatible device (e.g., Flipper Zero, Rubber Ducky)
- Target machine must have:
  - PowerShell enabled
  - Active internet connection to send data to Discord Webhook
- **Discord Webhook URL** (edit the script to input your own Webhook URL)

---

## 🚨 Disclaimer

This script is intended for **authorized penetration testing** and **educational purposes** only. Unauthorized use of this script on systems that you do not own or have explicit permission to test is **illegal** and unethical. The author assumes **no responsibility** for the misuse or consequences resulting from this tool.

---

## 🧠 Usage

1. Modify the following value in the script:
   - `$hookUrl = "WebHookURL_here"` → Replace with your own Discord Webhook URL

2. Flash the script to your BadUSB device.

3. Plug it into the target Windows system.

4. The script will execute automatically, extract the product key, and send it to your Discord server channel.

---

## 📌 License

This project is distributed for educational purposes under the [MIT License](https://opensource.org/licenses/MIT).
