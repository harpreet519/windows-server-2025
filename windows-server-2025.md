# Standard Operating Procedure (SOP)
**Company Name:** MITT
**Version:** 1.0  
**Written by:** Harpreet Brar
**Approved by:** Felix
**Date:** 03-27-2025
## Purpose  
This document provides easy-to-follow steps for setting up and configuring Windows Server 2025. It explains the process clearly so that anyone can install and set up the server correctly.
## Application
This SOP applies to IT administrators responsible for Windows Server deployment.
## Definitions
- **DNS (Domain Name System):** Resolves domain names to ip addresses.
- **GPO (Group Policy):** A tool for configuring and managing Windows settings across the network.
- **ISO:** Disk image file format.
## Procedure Steps
### Step 1: Download Windows Server 2025
- Download the latest ISO file for Windows Server 2025 by visiting the official website of **Microsoft**.
### Step 2: Install Windows Server 2025
- Insert the USB and boot from it.
- Follow the installation wizard to complete setup.
### Step 3: Configure System Settings
- Provide hostname.
- Provide administrator password.
- Assign time-zone.
### Step 4: Network Configuration
- Provide static IP address or Set DHCP.
- Configure DNS Settings.
### Step 5: Install and Configure Roles
- Go to "Add Roles and Features" in Server Manager and install important roles (Active Directory Domain Services , File and Storage Services ).
- Promote server to Domain Controller.
  ## Resources
- [Microsoft Official Documentation](https://docs.microsoft.com/)
- [Rufus Bootable USB](https://rufus.ie/)

 
