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

## 📂 Detailed Folder Description

📁 A/ - Virtual Machine and Windows Server Installation  
│   ├── 1.png → Screenshot showing VirtualBox or other virtualization software installed  
│   ├── 2.png → Start of Windows Server installation  
│   └── 3.png → Screen where administrator password is set after installation  

📁 B/ - Active Directory Setup  
│   ├── 1.png → Active Directory installation wizard  
│   ├── 2.png → Domain name entry screen (`mehmet.tat`)  
│   └── 3.png → Installation completed screen  

📁 C/ - DNS Configuration  
│   ├── 1.png → DNS server setup screen  
│   ├── 2.png → Domain names added (mehmet.net.tr / tat.net.tr)  
│   └── 3.png → Screenshot of records like A, MX, NS, CNAME  

📁 D/ - NAT and IP Configuration  
│   ├── 1.png → First Ethernet card with IP `10.16.16.1/16`  
│   ├── 2.png → Second Ethernet card with IP `10.17.17.1/16`  
│   ├── 3.png → Routing and Remote Access initial NAT setup screen  
│   ├── 4.png → NAT internal/external interface selection  
│   └── 5.png → NAT configuration completed screen  

📁 E/ - Group Policy and User Restrictions  
│   ├── 1-2.png → Group Policy creation screens  
│   ├── 3.png → Applying GPO to user groups (Student / Personal)  
│   ├── 4.png → User creation screen  
│   ├── 5.png → Adding a user to a group  
│   ├── 6.png → List of created users  
│   ├── 7.png → Logging into client with domain user  
│   └── 8.png → Example: Control Panel blocked for OgrUser1  

📁 F/ - Users and Groups  
│   ├── 1.png → Creating users: OgrUser1, OgrUser2, PersUser1, PersUser2  
│   ├── 2.png → List showing all 4 users  
│   ├── 3.png → Groups: Student and Personal  
│   └── 4.png → Group membership list  

📁 G/ - DHCP Server Setup  
│   ├── 1.png → DHCP server installation screen  
│   ├── 2.png → Pool for 10.16.0.0 network  
│   ├── 3.png → Pool for 10.17.0.0 network  
│   └── 4.png → Client showing IP received from DHCP  

📁 H/ - FTP Server  
│   ├── 1.png → FTP server setup screen  
│   └── 2.png → User-specific file access permissions  

📁 J/ - Web Server and Websites  
│   ├── 1.png → Web server setup (IIS or equivalent)  
│   ├── 2.png → Two domains published (`www.mehmet.net.tr`, `www.tat.net.tr`)  
│   ├── 3.png → First domain accessed in browser  
│   └── 4.png → Second domain accessed in browser  

📁 K/ - Mail Server Setup and SMTP-Based Email Testing  
│   ├── 1.png → SMTP-compatible mail server setup screen (e.g., hMailServer)  
│   ├── 2.png → Creating two mail accounts (e.g., mehmet@mehmet.net.tr)  
│   └── 3.png → Sending and receiving emails tested using Outlook or another client (SMTP/IMAP setup)  
 
## 📦 Submission Format

The screenshots and this README are submitted via GitHub as a digital archive of the assignment. A compressed ZIP version is also available for direct submission (`241002312-1.zip`).

---

Submitted by: Mehmet TAT  
University: Düzce University – Computer Engineering  
Course: Computer Networks II
