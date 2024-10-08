# WinBox for Linux

WinBox is a GUI tool used to administer MikroTik RouterOS routers. This project packages WinBox as a .deb package for easy installation on Debian-based Linux systems.


# About
WinBox for Linux brings the simplicity and power of MikroTik's WinBox utility to Linux users. It allows for easy access and management of MikroTik routers with a familiar interface.  
Winbox version 4 beta

# This project provides:

A .deb package for installing WinBox on Debian-based systems.
An easy-to-access launcher with a custom icon for integration with your desktop environment.
Features
Easy Installation: Pre-built .deb package for simple installation on Debian and Ubuntu systems.
Desktop Integration: Adds WinBox to your system’s application launcher with a custom icon.
Router Management: Use WinBox to manage MikroTik routers with a user-friendly GUI.

# Installation
Pre-built .deb Package
Download the .deb Package: Visit the releases page and download the latest version of the WinBox .deb package.

Install the Package: Run the following command in your terminal:

```
sudo dpkg -i winbox.deb
```
Install Missing Dependencies: If any dependencies are missing, 

run:

```
sudo apt --fix-broken install
```

# Building from Source
If you prefer to build the package from source:

Clone this repository:

```
git clone https://github.com/landaal-ict/Winbox
cd winbox
```
Build the .deb package:

```
dpkg-deb --build winbox
````
Install the package:


```
sudo dpkg -i winbox.deb
````
# Usage
After installation, you can launch WinBox from your system's application launcher. Search for "WinBox" in your desktop environment.


You can now use the GUI to manage your MikroTik routers as you would on a Windows machine.

# Updates
- Winbox4 Beta8 (latest)
- Winbox4 Beta6
- Winbox4 Beta4

# Contributing
Contributions are welcome! If you'd like to contribute, please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes.
Submit a pull request with a description of your changes.
Feel free to submit bug reports, feature requests, or enhancements.

# License
This project is licensed under the MIT License. See the LICENSE file for details.

# Credits
Maintainer: Wesley  
Original WinBox: MikroTik