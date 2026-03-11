# active-directory-home-lab
Cybersecurity home lab using VirtualBox, Windows Server 2022, Windows 10, and Ubuntu to simulate an enterprise Active Directory environment.
## Lab Environment
Host Machine: 
MacOS
Virtualization: 
VirtualBox
Operating Systems:
- Windows Server 2022 (Domain Controller)
- Windows 10 (Client Machine)
- Ubuntu Linux
## Network Architecture
Virtual Network Name: vboxnet0
- Cyberlab
Machines:
- DC01- Windows Server Domain Controller
CLIENT01 - Windows 10 Client
LINUX01 - Ubuntu Linux Systems
## Network Diagram
DC01 (Windows Server 2022)
IP: 192.168.56.10
Role Domain Controller
Client01 (Windows 10)
IP: 192.168.56.20
Role: Domain Client
LINUX01 (Ubuntu)
IP: 192.168.56.39
Role: Linux system connected to the lab network
## Purpose
This lab was built to simulate a small enterprise Active Directory environment and practice:
- Active Directory administration
- Network configuration
- Domain authentication
- Security monitoring
- Virtualized infrastructure deployment
## Objectives 
- Deploy a Windows Server Domain Controller
- Install Active Directory Domain Services
- Create a domain environment
- Join a Windows client to the domain
- Create Domain Users
- Demonstrate network communication between systems
## Lab Implementation
1. Installed Windows Server 2022 in VirtualBox
2. Configured Static IP addressing
3. Installed Active Directory Domain Services
4. Promoted server to Domain Controller
5. Created a domain environment
6. Installed Windows 10 client machine
7. Joined the client to the domain
8. Created domain user accounts
9. Verified domain authentication 
## Verification
Successful domain authentication was verified on the Windows 10 client using the following command:
whoami
Output confirmed the system authenticated against the Active Directory Domain 
