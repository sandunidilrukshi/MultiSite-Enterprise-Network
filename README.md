# Secure MultiSite Enterprise Network Infrastructure & Wireless Architecture

## Project Overview

This project demonstrates the design and implementation of a secure, scalable, and redundant multi-site enterprise network infrastructure using Cisco Packet Tracer.

The network architecture includes a Head Office (HQ), two branch offices, and an ISP connection.

## Technologies & Concepts

- Cisco Packet Tracer
- VLAN Segmentation
- Inter-VLAN Routing
- IEEE 802.1Q Trunking
- EtherChannel (LACP)
- HSRP (Gateway Redundancy)
- STP / PVST
- DHCP
- Wireless LAN Architecture
- Wireless Access Points
- WPA2-PSK Security
- Network Management VLAN
- DNS Services
- Network Redundancy

## VLAN Architecture

| VLAN ID | VLAN Name |
|---|---|
| 10 | Management |
| 20 | HR |
| 30 | Finance |
| 40 | IT |
| 50 | Servers |
| 60 | Guest |
| 70 | Voice |
| 100 | Network Management |

## Network Topology

The network consists of:

- Two Core Layer 3 Switches
- HQ Router
- Two Branch Routers
- ISP Router
- Multiple Access Switches
- Servers
- Wireless LAN Controller
- Wireless Access Points
- Wired and Wireless Clients

## Wireless Network

- SSID: Enterprise-WiFi
- Security: WPA2-PSK
- Encryption: AES
- Guest Network: VLAN 60
- Multiple Access Points with different 2.4 GHz channels

## Network Services

- DHCP
- DNS
- NTP
- RADIUS
- Syslog

## Testing & Verification

The following network functionalities were tested:

- DHCP address allocation
- Inter-VLAN connectivity
- HSRP gateway connectivity
- Server reachability
- DNS name resolution
- Wireless client connectivity
- Guest VLAN connectivity
- Switch trunking
- STP operation
- Network redundancy

## Project Files

- `Multisite-enterprise-Network.pkt` – Main Cisco Packet Tracer project.
- `Screenshots/` – Project configuration and verification screenshots.

## Software

Cisco Packet Tracer

## Author

ICT Undergraduate  
University of Sri Jayewardenepura  
Faculty of Technology
