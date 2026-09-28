# Small Business Network Lab

## Overview

This project demonstrates the design and configuration of a small business network using Cisco Packet Tracer.

The lab was built as a practical networking project to apply fundamental concepts such as VLAN segmentation, trunking, inter-VLAN routing, DHCP, DNS, HTTP services, and basic traffic filtering with ACLs.

## Objectives

* Design a small business network topology
* Configure VLANs for network segmentation
* Configure trunk links
* Implement inter-VLAN routing
* Configure DHCP for end devices
* Configure DNS services
* Configure an HTTP server
* Implement basic traffic control using ACLs
* Verify network connectivity and configuration using Cisco IOS commands

## Technologies & Concepts

* Cisco Packet Tracer
* IPv4
* VLAN
* 802.1Q Trunking
* Inter-VLAN Routing
* DHCP
* DNS
* HTTP
* Extended ACL
* Cisco IOS CLI

## Network Topology

![Network Topology](screenshots/topology.png)

## VLAN Structure

| VLAN | Name       | Purpose          |
| ---- | ---------- | ---------------- |
| 10   | ACCOUNTING | Accounting users |
| 20   | IT         | IT users         |
| 30   | USERS      | General users    |

## Network Services

### DHCP

DHCP is used to automatically provide IP configuration to client devices.

### DNS

A DNS service is configured to resolve hostnames to IP addresses within the lab environment.

### HTTP

An HTTP server is configured to demonstrate application-layer connectivity between network clients and the server.

## Security

Basic traffic filtering is implemented using Access Control Lists (ACLs).

The purpose of the ACL configuration is to control selected traffic between network segments while allowing required application traffic.

## Verification & Testing

The network configuration was verified using Cisco IOS commands and end-device testing, including:

* `show vlan brief`
* `show interfaces trunk`
* `show ip interface brief`
* `show ip route`
* `show ip dhcp binding`
* `show access-lists`
* `ipconfig`
* `ping`
* DNS testing
* HTTP testing

## Project Structure

```text
small-business-network-lab/
│
├── small-business-network-lab.pkt
│
├── documentation/
│   ├── ip-address-table.txt
│   ├── vlan-table.txt
│   └── network-design.txt
│
└── screenshots/
    ├── topology.png
    ├── vlan-configuration.png
    ├── ip-addressing.png
    ├── connectivity-test.png
    ├── services.png
    └── acl.png
```
## Screenshots

### Network Topology

![Network Topology](screenshots/TOPOLOGY.PNG)

### VLAN Configuration

![VLAN Configuration](screenshots/VLAN%20configuration.PNG)

### IP Addressing

![IP Addressing](screenshots/ip-addressing.PNG)

### Network Services

![Network Services](screenshots/show%20ip%20dhcp%20binding.PNG)

### Trunk Configuration

![Trunk Configuration](screenshots/show%20interfaces%20trunk.PNG)

### Routing Verification

![Routing Verification](screenshots/show%20ip%20route.PNG)

### ACL Configuration

![ACL Configuration](screenshots/ACL.PNG)


## What I Learned

Through this project, I practiced the configuration and troubleshooting of a small Cisco-based network.

The project helped me understand how VLANs provide network segmentation, how trunk links transport multiple VLANs, and how inter-VLAN routing enables communication between different network segments.

I also practiced using Cisco IOS verification commands and implementing basic traffic-control policies with ACLs.

## Future Improvements

Possible future improvements include:

* Implementing additional security policies
* Adding a firewall
* Expanding the network topology
* Adding a dedicated management VLAN
* Introducing Linux-based services
* Exploring network automation
* Migrating similar network concepts to a cloud environment

## Author

**Alireza Heidari**

IT & Networking Learner
