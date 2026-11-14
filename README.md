# Small Business Network Design & Implementation

## Project Overview

This project focuses on designing and implementing a small business network infrastructure using **Cisco Packet Tracer**. The network is designed for a growing company that requires reliable communication between three different departments while maintaining network segmentation and providing both wired and wireless connectivity.

The network uses a Cisco router and a central switch to connect the departments and enable communication across different VLANs.

## Network Requirements

The network was designed to meet the following requirements:

- One Cisco router and one Cisco switch.
- Three separate departments with individual VLANs.
- Wireless network connectivity for each department.
- Automatic IPv4 address allocation using DHCP.
- Communication between devices across all departments.
- Network segmentation to improve organization and security.

## Departmental VLAN Configuration

| Department | VLAN ID | Network Address | Subnet Mask |
|---|---:|---|---|
| Admin/IT | 10 | 192.168.1.0/28 | 255.255.255.240 |
| Finance/HR | 20 | 192.168.1.64/28 | 255.255.255.240 |
| Customer Service/Reception | 30 | 192.168.1.128/26 | 255.255.255.192 |

## Network Components

The network topology includes:

- Cisco 2911 Router
- Cisco Network Switch
- Wireless Access Points
- Desktop Computers
- Laptops
- Printers
- Smartphones
- Tablet Devices

## Technologies & Concepts

- Cisco Packet Tracer
- Virtual LANs (VLANs)
- Inter-VLAN Routing
- Router-on-a-Stick Configuration
- DHCP (Dynamic Host Configuration Protocol)
- Wireless Networking
- IPv4 Addressing and Subnetting
- Network Connectivity Testing

## Network Implementation

The network is divided into three departmental VLANs to logically separate network traffic.

Each department has its own wireless access point, allowing wireless devices to connect to the network.

The router provides inter-VLAN routing, enabling communication between devices belonging to different departments.

DHCP is used to automatically assign IPv4 addresses to network devices, reducing the need for manual IP configuration.

## Project Files

| File | Description |
|---|---|
| [Cisco Packet Tracer Project](Network-Design.pkt) | Download the network simulation file |
| [Network Screenshots](screenshots/) | View network topology and implementation screenshots |

## Learning Outcomes

Through this project, I gained practical experience in:

- Designing a departmental network infrastructure.
- Configuring VLANs for network segmentation.
- Understanding inter-VLAN routing.
- Implementing automatic IP address allocation.
- Integrating wired and wireless network devices.
- Configuring Cisco networking devices.
- Troubleshooting network connectivity.

## Tools Used

**Cisco Packet Tracer**

---

**Project Category:** Computer Networking  
**Project Type:** Network Design & Implementation
