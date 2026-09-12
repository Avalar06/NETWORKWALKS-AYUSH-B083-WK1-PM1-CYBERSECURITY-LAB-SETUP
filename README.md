# NETWORKWALKS-AYUSH-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP
# Networkwalks Week 1 – Project Module 1

## Cybersecurity Lab Setup with VirtualBox and Kali Linux

This repository contains my work for **Week 1 – Project Module 1** of the Networkwalks Cybersecurity Internship.

The purpose of this module was to set up a basic cybersecurity lab environment using **Oracle VirtualBox** and **Kali Linux**. The environment has been configured and tested so that it can be used for the practical cybersecurity activities in the upcoming modules.

---

## Lab Environment

| Component | Configuration |
|---|---|
| Host Operating System | Windows 11 |
| Virtualization Platform | Oracle VirtualBox 7.2.16 |
| Virtual Machine | Kali Linux 2026.2 |
| Network Type | NAT Network |
| Network Range | `10.0.0.0/24` |
| Kali Linux IP | `10.0.0.2/24` |
| Gateway | `10.0.0.1` |
| DNS Server | `8.8.8.8` |

---

## Work Completed

The following tasks were completed as part of the lab setup:

- Installed Oracle VirtualBox.
- Configured a NAT Network using the required `10.0.0.0/24` subnet.
- Imported and configured the Kali Linux virtual machine.
- Connected Kali Linux to the configured NAT Network.
- Assigned the static IP address `10.0.0.2/24` to Kali Linux.
- Configured the gateway and DNS settings.
- Enabled bidirectional clipboard functionality.
- Enabled bidirectional drag-and-drop functionality.
- Configured the shared `/downloads` folder between the host and Kali Linux.
- Verified that the shared folder was accessible from Kali Linux.
- Tested Internet connectivity and DNS resolution from Kali Linux.
- Created a VirtualBox snapshot after completing the lab setup.



---

## Evidence

The repository includes screenshots showing the major setup and verification steps:

| Screenshot | Description |
|---|---|
| `01-virtualbox-installation.png` | Oracle VirtualBox installation |
| `02-nat-network.png` | NAT Network configuration |
| `03-kali-vm-network.png` | Kali Linux VM network configuration |
| `04-kali-ipv4-settings.png` | Kali Linux IPv4 configuration |
| `05-shared-folder-verification.png` | Shared folder verification |

---

## Network Verification

The Kali Linux virtual machine was configured with:

```text
IP Address : 10.0.0.2/24
Gateway    : 10.0.0.1
DNS Server : 8.8.8.8
