# Passwords Extractor and Secure Upload Script

This script automates the extraction of saved passwords from web browsers on a Windows system using NirSoft's WebBrowserPassView tool. It then securely uploads the extracted passwords to an SSH server and clears relevant event logs to cover tracks.

## Script Details

- **Title**: Passwords Extractor
- **Author**: Chris Garey
- **Description**: Extracts saved passwords and uploads them to an SSH server.
- **Original Source**: [GitHub Repository](https://github.com/cgarey2014/BadUSB-Scripts/blob/main/Passwords/password_steal.txt)
- **Target**: Windows

## Features

- **Password Extraction**: Uses WebBrowserPassView to extract saved passwords from installed web browsers.
- **Secure Upload**: Utilizes SSH for secure file transfer to a remote server.
- **Event Log Clearance**: Clears PowerShell, Security, Application, and System event logs to cover tracks post-extraction.

## Usage

### Prerequisites

- Ensure the script runs on a Windows system with administrative privileges.
- Install OpenSSH or have SSH access configured on both the local and remote machines.
- Adjust the script parameters (`user`, `IP address`, and `password`) as per your environment.

## Notes
This script is intended for educational and testing purposes. Use responsibly and with proper authorization.
Ensure that you have appropriate permissions and access rights to execute scripts and clear event logs.
Customize parameters (user, IP address, password) to match your SSH server credentials and environment setup.

## License
This project is licensed under the MIT License. 
