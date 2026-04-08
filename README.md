<<<<<<< HEAD
# Help-Desk-Portfolio
=======
# Active Directory Home Lab (Windows Server + Windows 11)

## Overview
Built a fully functional Active Directory environment using Windows Server and Windows 11 Enterprise to simulate a small enterprise domain. The lab focuses on domain services, DNS, Group Policy, user management, and real-world troubleshooting.

## Environment
- Hypervisor: VirtualBox
- Domain Controller: Windows Server 2025
- Client: Windows 11 Enterprise
- Network: Host-Only Adapter
- Domain: LAB.local

## Key Features
- Installed and configured Active Directory Domain Services (AD DS)
- Configured DNS with forward lookup zones and SRV records
- Joined Windows 11 client to domain
- Implemented Organizational Units, users, and security groups
- Created and secured shared folders using NTFS and share permissions
- Applied Group Policy Objects (GPOs)

## Troubleshoots 
- DNS, NetLogon, and VirtualBox networking issues
- Password reset 


## Validation
- Successful domain discovery using `nltest /dsgetdc`
- DNS resolution verified using `nslookup`
- Client authentication and GPO application confirmed
>>>>>>> 1ee205d (Initial commit: Active Directory Lab)
