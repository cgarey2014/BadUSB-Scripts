<div align=center>
# Windows WiFi Password Exfiltration
</div>

## Description

This script extracts stored WiFi passwords from a Windows machine and sends them to a Discord server channel using a BadUSB device.

## Script Details

- **Title**: Windows WiFi Password Exfiltration
- **Author**: Chris Garey
- **Description**: Extracts stored WiFi passwords and sends them to a Discord server channel.
- **Original Source**: [GitHub Repository](https://github.com/cgarey2014/BadUSB-Scripts/blob/main/windows_wifi_password_exfil.txt)
- **Target**: Windows

## Features

- **Password Extraction**: Uses `netsh wlan show profiles` and `netsh wlan show profile name=<profile> key=clear` commands to extract stored WiFi passwords.
- **Discord Integration**: Sends extracted passwords to a specified Discord webhook.
- **Automated Execution**: Automates the entire process upon insertion of the BadUSB device.

## Usage

### Prerequisites

- Insert the BadUSB device into a target Windows machine.
- Replace `'YOUR_WEBHOOK_HERE'` with your actual Discord webhook URL before using.

### Instructions

1. Clone or download the script from the [GitHub Repository](https://github.com/cgarey2014/BadUSB-Scripts/blob/main/windows_wifi_password_exfil.txt).
2. Insert the BadUSB device into the Windows machine you want to extract WiFi passwords from.
3. The script will automatically:
   - Open a Command Prompt.
   - Extract stored WiFi passwords and append them to a text file (`wifi_passwords.txt`).
   - Send the contents of `wifi_passwords.txt` to a specified Discord webhook.

### Notes

- This script is for educational purposes only. Ensure you have appropriate authorization before running it.
- Use responsibly and comply with all legal and ethical guidelines.
- Replace `'YOUR_WEBHOOK_HERE'` with your actual Discord webhook URL before use.

## License

This project is licensed under the MIT License.
