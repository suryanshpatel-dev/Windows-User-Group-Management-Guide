# 🛠️ Windows User & Group Management Guide (`lusrmgr.msc` & PowerShell)

A comprehensive reference guide and documentation covering local user administration, security group management, enterprise deployment scenarios, and PowerShell automation on Windows operating systems.

---

## 📌 Overview

This repository/guide provides a complete walkthrough for managing system accounts and permissions in Windows environments:
* **GUI Administration:** Using `lusrmgr.msc` (Local Users and Groups) for standalone machine management.
* **Command-Line & Automation:** Utilizing PowerShell cmdlets for local and Active Directory account management.
* **Enterprise Use Cases:** Understanding non-domain servers, Sysprep golden imaging, and break-glass administrative accounts.

---

## 🚀 Quick Start: Accessing `lusrmgr.msc`

1. Press `Win + R` on your keyboard to open the **Run** dialog.
2. Type `lusrmgr.msc` and press **Enter**.

> **Note:** `lusrmgr.msc` is natively available on **Windows Pro, Enterprise, and Education** editions. It is not included in Windows Home edition.

---

## 📁 Key Features & Operations Covered

### 1. Core GUI Operations (`lusrmgr.msc`)
* **Create User Accounts:** Add new user profiles with custom account flags (e.g., *Password Never Expires*).
* **Reset Passwords:** Administrative override for changing account passwords without knowing the original credentials.
* **Manage Permissions (Groups):** Assign users to standard local security groups (`Administrators`, `Remote Desktop Users`, `Users`).
* **Disable/Delete Accounts:** Safely lock down profiles or remove user privileges.



# Disable a user account
Disable-LocalUser -Name "TechAdmin"
