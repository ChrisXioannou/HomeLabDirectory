# Virtualized Active Directory Home Lab

## Description
This home lab project represents a virtualized network environment featuring a Domain Controller (DC) running Server 2019 with complete Active Directory services and a Windows 10 virtual machine, to mimic a real-world internal network.

- **Network Services**: Incorporates DNS, essential for name resolution for networked devices.
- **User and Admin Interaction**: Demonstrates the management of multiple user accounts and access levels.
- **VPN Implementation**: Extends secure remote access capabilities.
- **RAS and NAT**: Enables private network communication with external networks.

## Languages and Utilities Used
- PowerShell
- Oracle VirtualBox

## Environments Used
- Windows Server 2019 virtual machine
- Windows 10 virtual machine

## Network Diagram
Below is the network architecture designed in this virtualized environment:
![Network Diagram](https://github.com/ChrisXioannou/HomeLabDirectory/blob/main/assets/diagam.png)



## Technical Details and Explanations
- **DC Server 19**: Manages network security and user data, provides authentication and authorization within a domain.
- **RAS**: Remote users can connect securely to the network.
- **NAT**: Multiple devices use one public IP to access the internet, conserving IPs and increasing security.
- **DNS**: Translates domain names to IP addresses.
- **DHCP**: Dynamically assigns IP addresses, simplifying network management.

## PowerShell Script for Creating Users
The PowerShell script for creating 1000 users was adapted from Josh Madakor's tutorial. For the original script, see [Josh Madakor's GitHub repository](https://github.com/joshmadakor1/AD_PS).

## Acknowledgments
Thanks to Josh Madakor (@joshmadakor1) for his guidance through his tutorials on setting up and configuring network services. His content provided foundational understanding and hands-on experience. For detailed instructions and script access, visit [Josh Madakor's GitHub repository](https://github.com/joshmadakor1/AD_PS).

## Project Outcomes
This project provided hands-on experience with Windows Server administration, networking principles, and security best practices, including configuring core services like Active Directory, DNS, DHCP, and VPN.
