# Active-Directory-Linux-Integration-Final-Project
This project simulates a real-world enterprise environment by integrating a Linux database server with a Windows Active Directory domain. It covers the deployment and configuration of AD DS, DNS, and DHCP services, as well as Linux domain joining using SSSD, Kerberos, and Samba Winbind. The setup enables centralized authentication, secure access control, and reliable cross-platform communication. Automation scripts (PowerShell, Bash, Python) are included to validate domain health, test integration, and ensure database connectivity.

Project Deliverables

Network Diagram - Visual representation of the Xpandcs infrastructure

Windows Server Configuration - Fully configured AD DS, DNS, DHCP services for Xpandcs.local

Linux Server - Database server integrated with Xpandcs Active Directory

Script Case - Automation and monitoring scripts including:

PowerShell domain health monitoring for Xpandcs

Bash AD integration checking for Xpandcs.local

Python integration testing

Documentation - Complete implementation guide for Xpandcs domain

Verification Procedures - Steps to validate the integration with Xpandcs domain


Success Criteria

Linux server successfully joined to Xpandcs Active Directory domain

Database services running on Linux server

Xpandcs AD users can authenticate to Linux server

DNS resolution working between servers

DHCP serving IP addresses to clients

All scripts executing without errors
