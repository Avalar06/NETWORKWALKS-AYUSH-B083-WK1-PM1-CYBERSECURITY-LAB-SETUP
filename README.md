# NETWORKWALKS-AYUSH-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP

## Networkwalks Week 1 – Project Module 1

### Cybersecurity Lab Setup with VirtualBox and Kali Linux

This repository contains my work for **Week 1 – Project Module 1** of the Networkwalks Cybersecurity Internship.

The objective of this module was to build a practical cybersecurity lab environment using **Oracle VirtualBox and Kali Linux**. The environment was configured and verified for use in upcoming hands-on cybersecurity activities.

---

## Lab Environment

| Component | Configuration |
|---|---|
| Host Operating System | Windows 11 |
| Virtualization Platform | Oracle VirtualBox 7.2.16 |
| Virtual Machine | Kali Linux 2026.2 |
| Network Type | NAT Network |
| Kali Linux | Configured with a static network configuration |
| Network Connectivity | Internet connectivity verified |
| DNS Resolution | Verified successfully |

---

## Work Completed

The following tasks were completed as part of the Week 1 lab setup:

- Installed and configured Oracle VirtualBox.
- Configured the required NAT Network environment.
- Imported and configured the Kali Linux virtual machine.
- Connected Kali Linux to the configured virtual network.
- Configured the Kali Linux network interface.
- Enabled bidirectional clipboard functionality.
- Enabled bidirectional drag-and-drop functionality.
- Configured a shared folder between the host system and Kali Linux.
- Verified that the shared folder was accessible from Kali Linux.
- Tested Internet connectivity from Kali Linux.
- Verified DNS resolution from Kali Linux.
- Created a VirtualBox snapshot after completing the lab setup.

---

## Challenge and Troubleshooting

During the initial network configuration, Kali Linux did not obtain the required network connectivity correctly.

I reviewed the NetworkManager configuration and followed the troubleshooting procedure provided in the project instructions. The network connection was then reactivated successfully.

After troubleshooting, I verified:

- Network interface status
- Internet connectivity
- DNS resolution
- Shared folder accessibility

The lab environment was successfully brought to a working state.

---

## Key Learning

This project provided practical experience with:

- Virtual machine deployment and configuration
- Kali Linux environment setup
- Linux network configuration
- Virtual networking
- Network troubleshooting
- Shared folder configuration
- Connectivity and DNS verification
- Creating VM snapshots for recovery

The setup provides a controlled environment for performing the practical cybersecurity activities planned for the upcoming modules.

---

## Evidence

The repository contains screenshots documenting the major setup and verification stages:

| Screenshot | Description |
|---|---|
| `01-virtualbox-installation.png` | Oracle VirtualBox installation |
| `02-nat-network.png` | NAT Network configuration |
| `03-kali-vm-network.png` | Kali Linux virtual machine network configuration |
| `04-kali-ipv4-settings.png` | Kali Linux network configuration |
| `05-shared-folder-verification.png` | Shared folder verification |

---

## Completion Status

**Week 1 – Project Module 1: Completed**

The VirtualBox and Kali Linux cybersecurity lab was successfully configured, tested, and prepared for the upcoming practical cybersecurity modules.
