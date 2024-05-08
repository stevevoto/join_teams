Join Teams Script
Overview
The Join Teams Script automates the process of joining Microsoft Teams meetings on Linux-based systems. It opens the meeting link in a web browser, maximizes the browser window, clicks the "Join now" button, and closes the browser after a specified duration. Additionally, it includes features for logging script activities.

Requirements
Operating System
The script is designed to run on Linux-based distributions such as:

Ubuntu
CentOS
Tools
The following tools are required to run the script:

Bash Shell: A Bash-compatible shell is required to execute the script.
xdg-open: Used to open the provided Teams meeting URL in the default web browser.
xdotool: Used for simulating keyboard input, mouse activity, and window manipulation. It is utilized to maximize the browser window, simulate mouse clicks, and move the mouse cursor.
Preliminary Steps
Before running the script, ensure the following:

Operating System: Confirm that the system is running either Ubuntu or CentOS.
Screen Lock and Screensaver: Disable screen lock and screensaver functionalities to prevent interruptions during script execution. This can typically be done through system settings or configuration options in the desktop environment.
Install Required Tools: Make sure that xdg-open and xdotool are installed on the system. You can install them using package managers like apt for Ubuntu or yum for CentOS.
Usage
Finding the "Join now" Button
To find the "Join now" button using the mouse tool (xdotool), follow these steps:

Open the Teams meeting URL in the default web browser.
Inspect the web page to identify the location of the "Join now" button visually. Note the approximate coordinates (x, y) of the button on the screen.
Use the xdotool command to move the mouse cursor to the desired coordinates and simulate a mouse click on the button. Adjust the coordinates as needed to ensure accurate clicking.
By following these steps and running the provided script, users can automate the process of joining Microsoft Teams meetings, thereby saving time and effort. However, it's important to ensure that the system environment and prerequisites are properly configured before running the script for optimal performance.
