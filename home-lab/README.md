Home Lab Infrastructure

Overview

My home lab provides a low-power environment for learning networking, Linux administration, virtualisation, and ISP engineering concepts.

The infrastructure combines Proxmox VE, Debian Linux, MikroTik RouterOS, DNS filtering, and secure remote access.

Infrastructure:
Lenovo ThinkPad T470	|   Server           
Proxmox VE	          | Type-1 Hypervisor  
Debian 13 (Trixie)    |	Pi-hole DNS filterin
MikroTik RouterOS	    | Networking gear Manufacturer
Services              | Security, Wifi connectivity, DNS Filtering

Pi-hole provides DNS filtering for home network clients. The router distributes Pi-hole as the primary DNS resolver, with a secondary public resolver configured for fallback.

##Remote Access

WireGuard provides encrypted remote access to the home network for administration and lab access.

##Virtualisation

Proxmox VE hosts the Debian VM and provides the foundation for future Linux routing and network automation labs.

##Planned Improvements

1. Document the logical network topology

2. Create isolated virtual networks for networking experiments

3. Deploy Debian VMs for Linux networking

4. Install FRRouting and establish OSPF adjacency

5. Build an eBGP lab with multiple autonomous systems

6. Add practical troubleshooting notes and verification commands

##Security Considerations

This repository intentionally excludes credentials, private keys, public IP addresses, and sensitive configuration details. Network diagrams and configuration examples will be sanitised before publication.
