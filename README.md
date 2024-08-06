# macOS-Software-Updates

A collection of scripts and tips to better manage macOS updates and upgrades. This repository aims to provide helpful resources for automating and streamlining the process of keeping macOS systems up-to-date.

This page will be expanded as new scripts and tips are developed. Check back regularly for updates and additional content.

Current Scripts:

**1. Automated macOS Update Installation with Warning:**
This script checks for available macOS updates, downloads them, and notifies the user that the system will shut down in 5 minutes to complete the installation. It then proceeds to install the updates and reboots the system.

# Usage:

Download Updates: The script begins by checking for and downloading the latest macOS updates.
User Notification: It uses osascript to display a dialog warning the user that the system will shut down in 5 minutes for installation.
Install Updates: The script installs the updates and initiates a system restart.


**2. macOS Update with User Choice:**
This script also checks for and downloads macOS updates but gives the user the option to defer the installation. It provides a dialog box allowing the user to choose between installing the update immediately or deferring it.

Usage:

**Download Updates:** The script starts by checking for available updates and downloading them.
**User Prompt:** A dialog is displayed using osascript, giving the user the choice to "Install" or "Defer" the update.
**Conditional Installation:** If the user chooses "Install," the updates are installed, and the system is restarted. If "Defer" is chosen, the update is postponed.
Future Updates

I plan to add more scripts and tips to this repository to cover a wider range of macOS update management scenarios. Whether you're looking to automate the update process or give users more control over when updates are installed, stay tuned for more resources.

License:

This project is licensed under the MIT License. See the LICENSE file for details.
