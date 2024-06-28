# Windows Key Extractor

## Description

This script extracts the Windows product key from a Windows machine and sends it to a Discord server channel using a BadUSB device.

## Script Details

- **Title**: Windows Key Extractor
- **Author**: Chris Garey
- **Description**: Extracts Windows product key and sends it to a Discord server channel.
- **Original Source**: [GitHub Repository](https://github.com/cgarey2014/BadUSB-Scripts/blob/main/windows_key_steal.txt)
- **Target**: Windows

## Features

- **Product Key Extraction**: Retrieves the Windows product key using PowerShell's `Get-WmiObject` cmdlet.
- **Discord Integration**: Sends the extracted product key to a specified Discord webhook.
- **Automated Execution**: Automates the process upon insertion of the BadUSB device.

## Usage

### Prerequisites

- Insert the BadUSB device into a target Windows machine.
- Replace `'WebHookURL_here'` with your actual Discord webhook URL before using.

### Instructions

1. Clone or download the script from the [GitHub Repository](https://github.com/cgarey2014/BadUSB-Scripts/blob/main/windows_key_steal.txt).
2. Insert the BadUSB device into the Windows machine you want to extract the product key from.
3. The script will automatically:
   - Open PowerShell.
   - Retrieve the Windows product key.
   - Send the product key to a specified Discord webhook.

### Notes

- This script is for educational purposes only. Ensure you have appropriate authorization before running it.
- Use responsibly and comply with all legal and ethical guidelines.
- Replace `'WebHookURL_here'` with your actual Discord webhook URL before use.

## License

This project is licensed under the MIT License.
