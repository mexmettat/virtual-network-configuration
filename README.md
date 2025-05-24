# Virtual Network Environment Configuration and Service Implementation on Windows Server

This repository contains the practical implementation of a virtualized network environment using Windows Server and two client machines. The goal is to simulate an enterprise network by configuring key infrastructure services and verifying them via client devices.

## ✅ Tasks Completed

1. Installed Windows Server and 2 Client OS (Windows 10 and Windows 7) in VirtualBox  
2. Set up Active Directory with domain name `mehmet.tat`  
3. Installed DNS server and created A, MX, NS, CNAME records for `mehmet.net.tr` and `tat.net.tr`  
4. Connected 2 Ethernet cards with addresses `10.16.16.1/16` and `10.17.17.1/16` and configured NAT  
5. Created Group Policy rules:  
   - Blocked Control Panel access for "Student" group  
   - Prevented software installation for "Personal" group  
6. Created and tested domain users: OgrUser1, OgrUser2 (Student group), PersUser1, PersUser2 (Personal group)  
7. Installed DHCP server with IP pools for both networks and tested automatic IP assignment  
8. Installed FTP server and configured different user access rights  
9. Installed and configured a Web Server to host two separate websites  
10. Installed a Mail Server and configured Outlook on the client to send/receive emails  

## 🖥️ Client Usage

Two virtual client machines were used to verify and demonstrate the services:

- Logging in with domain users (OgrUser1, PersUser1, etc.)  
- Group Policy enforcement (Control Panel lockout, software restriction)  
- DHCP IP assignment from defined pools  
- FTP and website access from browser or File Explorer  
- Outlook mail send/receive test with the configured mail server  

## 📁 Folder Structure

All screenshots have been organized and named according to the assignment requirements:

A/ → Virtual machine and Windows Server installation  
B/ → Active Directory setup  
C/ → DNS configuration  
D/ → NAT and network settings  
E/ → Group Policy creation and enforcement  
F/ → User and group management  
G/ → DHCP server and IP lease demonstration  
H/ → FTP server setup and file permissions  
J/ → Web server and domain publishing  
K/ → Mail server setup and Outlook test  

Each folder contains numbered `.png` screenshots (e.g., `1.png`, `2.png`, `3.png`...) as requested in the assignment.

## 📦 Submission Format

The screenshots and this README are submitted via GitHub as a digital archive of the assignment. A compressed ZIP version is also available for direct submission (`241002312-1.zip`).

---

Submitted by: Mehmet TAT  
University: Düzce University – Computer Engineering  
Course: Computer Networks II
