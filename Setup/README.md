# Lab Setup

## Virtual Environment

- Hypervisor: Vmware
- RAM Allocation: 4GB DC, 4GB Client
- Network Type: Internal Network

## Machines

1. Windows Server 2019
   - Installed Active Directory Domain Services
   - Configured Domain Controller
   - Created domain: cicada.local

2. Windows 10 Client
   - Joined domain
   - Created low privilege test user

3. Kali Linux
   - Tools installed:
     - BloodHound
     - Impacket
     - CrackMapExec
     - Nmap
