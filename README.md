# Active Directory Lab

## Objective

This repository documents the setup, exploitation, and detection mapping of a simulated Active Directory environment.

The goal is to:
- Simulate real-world AD misconfigurations
- Perform offensive techniques
- Map findings to MITRE ATT&CK
- Document detection opportunities

---

## Lab Architecture

- Windows Server 2019 (Domain Controller)
- Windows 10 Client
- Kali Linux Attacker Machine
- Vmware Environment

---

## Attack Scenarios Covered

- Enumeration
- Kerberoasting
- AS-REP Roasting
- Pass-the-Hash
- Lateral Movement
- Privilege Escalation

---

## Detection Mapping

Each attack is mapped against:
- MITRE ATT&CK technique ID
- Windows Event Logs
- Defensive monitoring notes
