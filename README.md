# Kali NetHunter Installation Script for Termux

This script automates the installation of Kali NetHunter on Termux, a Linux environment for Android devices. It includes fixes for compatibility issues, syntax errors, and file path errors that may occur during the installation process.

## Features

* Downloads and verifies the latest Kali NetHunter rootfs image
* Extracts the rootfs and configures it for Termux
* Creates launchers for easy access to the NetHunter CLI and GUI (KeX)
* Handles potential compatibility issues, including:
    * Updated rootfs file naming and directory structure
    * Corrected syntax errors in the script
    * Resolved "No such file or directory" errors during configuration

## Prerequisites

* Termux app installed on your Android device
* Basic familiarity with Termux and Linux commands

## Installation

1. Clone this repository: `git clone https://gitlab.com/un1xr00t/nethunter-rootless-fix.git`
2. Navigate to the cloned directory: `cd nethunter-rootless-fix`
3. Make the script executable: `chmod +x install-nethunter`
4. Run the script: `./install-nethunter`
5. Follow the on-screen prompts to choose the desired NetHunter image and complete the installation

## Usage

* Start NetHunter CLI: `nethunter` or `nh`
* Set KeX password: `nethunter kex passwd`
* Start NetHunter GUI: `nethunter kex &`
* Stop NetHunter GUI: `nethunter kex stop`
* Run NetHunter as root: `nethunter -r`

## Credits

* **Original Script:** The base of this script was adapted from the official NetHunter installation guide and other publicly available scripts.
* **Contributor:** un1xr00t (Your GitLab username) 

## Disclaimer

* Use this script at your own risk. The author is not responsible for any damage or data loss that may occur.
* Make sure you understand the implications of running Kali NetHunter on your device.
* Always follow ethical hacking practices and respect the privacy and security of others.

## License

This script is released under the [MIT License](LICENSE).
