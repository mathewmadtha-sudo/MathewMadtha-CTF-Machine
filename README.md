# Cyber Security CTF Machine Development

## Author
**Mathew Madtha**

---

## Objective
Design and deploy a Capture The Flag (CTF) machine using Kali Linux and Ubuntu to simulate a real-world penetration testing environment.

---

## Machine Details

**Target Machine:** Ubuntu 14.04.6 LTS  
**Development Environment:** Kali Linux  
**Hostname:** madtha

### Open Ports
- 22 (SSH)
- 80 (HTTP)

---

## User Accounts

The following user accounts were created:

- mathew
- mokshith
- neha

---

## Services Configured

- OpenSSH Server
- Apache Web Server
- UFW Firewall

---

## Website Features

A professional portfolio website was developed and hosted using Apache Web Server.

### Hidden clues were implemented using:

- HTML Comments
- robots.txt
- JavaScript files
- CSS files
- Base64 Encoding

---

## Steganography Challenge

A hidden challenge was implemented using steganography.

- Carrier File: `profile.jpg`
- Hidden File: `resume.pdf`
- Tool Used: `steghide`

---

## Flag Locations

### User Flag
```
/home/wavex/wave/FLAG1.txt
```

### Root Flag
```
/root/FLAG2.txt
```

---

## Tools Used

- Kali Linux
- Ubuntu 14.04.6 LTS
- Apache2
- OpenSSH
- UFW Firewall
- Steghide
- VMware Workstation

---

## Execution Flow

1. Enumerate the target machine.
2. Discover hidden files through robots.txt.
3. Access secret web pages.
4. Analyze source code and hidden clues.
5. Extract hidden files using steganography.
6. Obtain credentials.
7. Gain SSH access.
8. Escalate privileges.
9. Capture the user flag.
10. Capture the root flag.

---

## Repository Structure

```
MathewMadtha-CTF-Machine/
│
├── README.md
├── website/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│   ├── robots.txt
│   └── secret.html
│
├── screenshots/
│   ├── 01_hostname.png
│   ├── 02_user_accounts.png
│   ├── 03_ssh_status.png
│   ├── 04_apache_status.png
│   ├── 05_firewall_status.png
│   ├── 06_website_files.png
│   ├── 07_robots_txt.png
│   ├── 08_secret_page.png
│   ├── 09_steganography_info.png
│   ├── 10_user_flag.png
│   └── 11_root_flag.png
│
└── CTF_Report.pdf
```

---

## Screenshots Included

- Hostname Configuration
- User Account Creation
- SSH Service Status
- Apache Service Status
- Firewall Configuration
- Website Files
- robots.txt Enumeration
- Hidden Web Page
- Steganography Challenge
- User Flag
- Root Flag

---

## Conclusion

This project demonstrates the complete design and implementation of a Capture The Flag (CTF) machine. It includes web enumeration, hidden file discovery, steganography, SSH access, privilege escalation concepts, and flag retrieval techniques used in penetration testing and cybersecurity assessments.
