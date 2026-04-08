## Lab Overview


This lab demonstrates the deployment, configuration and validation of a Windows Active Directory environment, including file sharing & permissions, and account management operations commonly performed.

## Environment
- Hypervisor: VirtualBox
- Network: Host-only network (isolated lab)
- Domain Controller: Windows Server 2022
    - Roles: Active Directory Domain Services, DNS
- Client: Windows 11 Enterprise (domain-joined)

## Scope of Work 
- Installed and configured Active Directory Domain Services
- Promoted Windows Server to Domain Controller for LAB.local
- Joined Windows 11 client to the domain
- Created and managed domain user accounts 
- Configured a shared folder on the Domain Controller 
- Mapped a network drive on the domain client via File Explorer
- Simulated account lockout and performed administrative password reset
- Troubleshot DNS resolution and domain discovery issues


## Validation and Outcome
- Successful domain join and authentication from Windows 11 client 
- Network drive mapped 
- Account lockout triggered through failed authentication attempts 
- Lockout account identified and reset via Active Directory Users and Computers
- Domain Controller discovery confirmed using nltest /dsgetdc
- Internal DNS resolution validated without external dependency

## Skills Demonstrated
- Active Directory Administration
- DNS configuration and troubleshooting 
- Windows file sharing and permissions
- User account lifecycle management 
- Account lockout investigation and remediation 
- Windows Server and client administration 
- Command-line diagnostics

## Security notes
- IP addresses are partially masked in public documentation
- Lab environment is isolated using host-only network configuration