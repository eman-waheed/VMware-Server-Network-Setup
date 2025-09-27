VMware and Server Connection Project

Overview
This project demonstrates setting up a virtual machine using VMware Workstation, installing a server operating system, and configuring connectivity between the virtual machine and a physical machine. It highlights virtualization, server configuration, and network integration in practical scenarios.

Objectives
- Install and configure VMware Workstation
- Set up and configure a server OS (Windows Server 2016/2019 or Linux)
- Establish network connectivity between a VM and a physical machine
- Test and troubleshoot network communication

System Requirements
Hardware:
- 64-bit processor with virtualization support (Intel VT-x / AMD-V)
- Minimum 8 GB RAM (16 GB recommended)
- 100 GB free storage
- Functional network interface card (NIC)

Software:
- VMware Workstation Pro/Player (v15 or later) or VMware ESXi
- Server OS: Windows Server 2016/2019 or Ubuntu Server 20.04 LTS
- Network tools: ping, traceroute, file sharing (SMB/NFS)

Implementation Steps
1. Install VMware Workstation
   - Download from VMware official site and install
   - Configure drivers and network adapters
2. Create and Configure Virtual Machine
   - Allocate CPU cores, RAM, and disk space
   - Install server OS from ISO
3. Post-Installation Setup
   - Configure static IP addresses
   - Enable firewall and required server roles (DNS, DHCP, File Server)
4. Connect VM to Physical Machine
   - Configure network adapters (Bridged/NAT)
   - Assign IPs in same subnet
   - Test connectivity with ping, file sharing, and remote desktop
5. Troubleshooting
   - Check firewall rules
   - Verify network adapter configuration
   - Ensure correct IP addressing

Files in this Repository
- Report.pdf : Detailed documentation of VMware installation, server setup, and network connection
- Presentation.pdf : Slides used for project presentation (if available)
- Diagrams/ : Network configuration and VM setup diagrams

Future Enhancements
- Implement advanced server roles (DNS, DHCP, Active Directory)
- Expand setup to multiple VMs in a virtual network
- Cloud integration with VMware vSphere or ESXi
