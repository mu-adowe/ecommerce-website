# Rustys

## Overview
Rustys is a full-stack PHP project designed as an e-commerce platform for selling goods. This is a prototype and should not be used in production.

### Prerequisites
- PHP 7.4 or higher
- MySQL 5.7 or higher
- **Windows:** Windows 10/11 (64-bit)
- **Linux:** Any 64-bit distribution (Ubuntu, Fedora, etc.)
- **macOS:** macOS 10.6 or later

### Windows

1. Download the latest installer from [apachefriends.org/download.html](https://www.apachefriends.org/download.html)
2. Double-click `xampp-windows-x64-8.2.12-0-VS16-installer.exe`
3. Click **Next** → accept the default components (Apache, MariaDB, PHP, phpMyAdmin)
4. Keep the default install path `C:\xampp`
5. Click **Next** → **Next** to finish
6. Launch the **XAMPP Control Panel** from the Start menu
7. Click **Start** next to Apache and MariaDB

> **Tip:** You can also install via Command Prompt (admin):
> ```
> winget install --id ApacheFriends.Xampp.8.2
> ```

### Linux

1. Download the `.run` installer from [apachefriends.org/download.html](https://www.apachefriends.org/download.html)
2. Open a terminal and navigate to your Downloads folder:
   ```bash
   cd ~/Downloads
3. Make the installer executable :
   ```
   chmod +x xampp-linux-x64-8.2.12-0-installer.run
   ```
4. Run the Installer :
   ```
   sudo ./xampp-linux-x64-8.2.12-0-installer.run
   ```
5. Follow the wizard and make sure you remember default path
6. start XAMPP :
   ```
   cd /path/to/file
   sudo ./manager-linux-x64.run
   ```

### Mac OS

1. Download the .dmg installer from apachefriends.org/download.html
2. Double-click xampp-osx-8.2.4-0-installer.dmg
3. Double-click XAMPP.app and enter your admin password
4. Follow the setup wizard (default path: /Applications/XAMPP)
5. Open XAMPP Control Panel from Launchpad
6. Click Start next to Apache and MariaDB
7. Verify Installation
8. Open your browser and navigate to:
```
http://localhost
```
You should see the XAMPP dashboard. To access phpMyAdmin:
```
http://localhost/phpmyadmin
```
