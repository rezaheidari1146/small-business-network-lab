# Small Business Network Lab

## Overview

This project demonstrates the design and configuration of a small business network using Cisco Packet Tracer.

The lab was built as a practical networking project to apply fundamental concepts such as VLAN segmentation, trunking, inter-VLAN routing, DHCP, DNS, HTTP services, and basic traffic control using ACLs.

The project also includes network documentation and verification screenshots.

---

## Objectives

The main objectives of this project were:

- Design a small business network topology
- Configure VLAN segmentation
- Configure 802.1Q trunking
- Implement inter-VLAN routing
- Configure DHCP services
- Configure DNS services
- Configure HTTP services
- Implement basic traffic control using ACLs
- Verify network connectivity and configurations
- Practice Cisco IOS verification commands
- Document the network configuration

---

## Technologies & Concepts

- Cisco Packet Tracer
- Cisco IOS
- VLANs
- 802.1Q Trunking
- Inter-VLAN Routing
- DHCP
- DNS
- HTTP
- ACLs
- IPv4
- TCP/IP
- Network Troubleshooting

---

## Network Topology

The network was designed to represent a small business environment with multiple network segments and end devices.

The topology includes:

- Cisco Router
- Cisco Switches
- PCs
- Laptop
- Server
- Multiple VLANs
- Trunk links
- Inter-VLAN routing

---

## VLAN Structure

The network uses VLANs to logically separate devices and network traffic.

VLAN configuration and addressing information are documented in the project files.

See:

- [VLAN Table](documentation/vlan-table.txt)
- [IP Address Table](documentation/ip-address-table.txt)

---

## Inter-VLAN Routing

Inter-VLAN communication is implemented using router-based inter-VLAN routing.

The router provides Layer 3 connectivity between the different VLANs.

This allows devices in separate VLANs to communicate while maintaining logical network segmentation.

---

## Network Services

The project includes several basic network services:

### DHCP

DHCP is used to automatically provide IP configuration information to network clients.

The DHCP configuration was verified using Cisco IOS commands.

### DNS

DNS was configured to provide name resolution within the lab environment.

### HTTP

An HTTP service was configured on the network server to demonstrate basic application-layer network services.

---

## Network Security

Basic network traffic control was implemented using Access Control Lists (ACLs).

The ACL configuration was tested to verify that traffic was handled according to the defined rules.

This project focuses on fundamental ACL concepts rather than advanced enterprise security.

---

## Verification & Troubleshooting

Several Cisco IOS verification commands were used during the project, including:

```text
show vlan brief
show interfaces trunk
show ip interface brief
show ip route
show access-lists
show ip dhcp binding
