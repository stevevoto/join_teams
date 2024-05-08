# Join Teams Script

## Overview

The **Join Teams Script** automates the process of joining Microsoft Teams meetings on Linux-based systems. It opens the meeting link in a web browser, maximizes the browser window, clicks the "Join now" button, and closes the browser after a specified duration. Additionally, it includes features for logging script activities.

## Requirements

### Operating System

The script is designed to run on Linux-based distributions such as:

- Ubuntu with GUI
- CentOS with GUI

### Tools

The following tools are required to run the script:

1. **Bash Shell**: A Bash-compatible shell is required to execute the script.
2. **xdg-open**: Used to open the provided Teams meeting URL in the default web browser.
3. **xdotool**: Used for simulating keyboard input, mouse activity, and window manipulation. It is utilized to maximize the browser window, simulate mouse clicks, and move the mouse cursor.

## Preliminary Steps

Before running the script, ensure the following:

1. **Operating System**: Confirm that the system is running either Ubuntu or CentOS.
2. **Screen Lock and Screensaver**: Disable screen lock and screensaver functionalities to prevent interruptions during script execution. This can typically be done through system settings or configuration options in the desktop environment.
3. **Install Required Tools**: Make sure that `xdg-open` and `xdotool` are installed on the system. You can install them using package managers like `apt` for Ubuntu or `yum` for CentOS.

```bash
git clone https://github.com/stevevoto/join_teams
cd join_teams/
chmod +x pre-install 
chmod +x join_teams 
./pre-install

