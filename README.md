# active-directory-home-lab
Beginner Active Directory and IT support home lab using Windows
## Overview
This project documents my beginner Active Directory home lab using VMware and Windows Server 2022

The goal of this lab is to simulate a real-world enterprise IT environment while learning:
- Active Directory
- Windows Server Administration 
- Domain management
- User administration
- Troubleshooting
- Help desk tasks

---

## Tools Used
- VMWare(you can also use oracle's virtualbox that is also a great alternative)
- Windows Server 2022
- Windows 10
- Github

---

## Lab Objectives
- Install Windows Server 2022 in a virtual machine
- Install Ubuntu which will serve as one of the users in the home lab
- Install Kali to serve as another user and in further projects and attack machine
- Configure Active Directory Domain Services
- Create a domain controller
- Create users and organizational units
- Join Windows clients to domain
- Simulate real-world IT issues

---

## Problems Encountered
### Issue 1: Installed Server Core Instead of Desktop Experience
- Learned the difference between Server Core and Desktop Experience
- Reinstalled using desktop experience

### Issue 2: Hit a snag trying to run kali in VMWare
- Learned to install the VMWare version of kali instead of trying to run the ISO image in VMWare(If VirtualBox is being used instead of VMware, the ISO image works fine without any issues, so it might be a VMWare thing for me).

### Issue 3: VMWare Virtualization Errors
Errors encountered:
- hv.capable was 0
- VPMC errors

Fixes:
- Disabled Hyper-V
- Disabled Memory Intergrity
- Adjusted VMWare processor settings
---

### Some beginner tips 
- When an error message pops up where it says "No bootable medium found" or something like "Failed to boot", it almost always is one of three things:
- no ISO attached
- bad ISO
- or wrong boot order

## Skills Demonstrated
- Virtual machine management
- Windows Server Installation
- Troubleshooting virtualization issues
- Documentation
- Active Directory fundamentals

---

## Screenshots


