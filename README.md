# 🏫 K.K. Wagh Department Asset Management System

A robust desktop application developed for the **Computer Engineering Department at K.K. Wagh** to streamline inventory tracking, hardware/software asset management, and department resource allocation.

---

## 🚀 Features
* **Automated Asset Tracking**: Easily log, update, and monitor departmental hardware and software.
* **Secure Database Integration**: Powered by a robust local MySQL backend.
* **Professional Windows Installer**: Packaged into a seamless standalone setup wizard (`KKWagh_Inventory_Setup.exe`) with automatic desktop shortcuts.
* **User-Friendly Dashboard**: Clean interface tailored for department staff and administrators.

---

## 🛠️ Tech Stack
* **Language**: Python
* **Database**: MySQL
* **Installer Packaging**: Inno Setup

---

## 📥 Installation & Setup Guide

### For Evaluators & Users:
1. Head over to the **[Releases](../../releases)** tab of this repository.
2. Download the latest **`KKWagh_Inventory_Setup.exe`** installer file[cite: 10].
3. Double-click the installer to launch the setup wizard. *(Note: If Windows SmartScreen prompts you, click "More info" -> "Run anyway").*
4. Follow the on-screen instructions to complete the installation and place the shortcut on your desktop.

### Database Configuration (MySQL):
Because this application relies on a local database backend, ensure the following steps are completed on your machine:
1. Install **MySQL Server** locally.
2. Import the provided department database schema using the included `.sql` file:
   ```sql
   CREATE DATABASE kkwagh_inventory;
   -- Import tables using your MySQL workbench or command line
