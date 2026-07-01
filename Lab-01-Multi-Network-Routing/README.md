# Lab 01 – Multi-Network Routing & Router Interface Expansion

## Overview

This lab demonstrates the configuration of multiple networks using a Cisco router in Cisco Packet Tracer. It also covers router interface expansion using the HWIC-4ESW module and troubleshooting interface configuration issues.

---

## Objectives

- Configure multiple LANs.
- Assign IPv4 addresses to router interfaces.
- Configure PCs with the correct IP addressing.
- Expand router interfaces using the HWIC-4ESW module.
- Verify connectivity between networks.
- Troubleshoot interface configuration errors.

---

## Network Topology

(Add your topology screenshot here.)

---

## Devices Used

- 1 Cisco Router
- 3 Cisco Switches
- Multiple PCs
- HWIC-4ESW Module
- Copper Straight-through Cables

---

## IP Addressing

| Device | IP Address |
|---------|------------|
| Router G0/0 | 192.168.1.1 |
| Router G0/1 | 192.168.2.1 |
| Router Fa0/1/0 | 192.168.3.1 |
| PC0 | 192.168.1.10 |
| PC1 | 192.168.2.10 |
| PC2 | 192.168.3.10 |

---

## Router Configuration

Configured:

- Hostname
- Interface IP addresses
- no shutdown
- Interface verification
- Saved configuration

---

## Verification

Successful ping tests were completed between all configured networks.

All devices communicated successfully.

---

## Challenges Encountered

Initially, assigning an IP address to FastEthernet0/1/0 returned an **Invalid Input Detected** error.

After investigation, I discovered that the newly installed HWIC-4ESW module provides Layer 2 switch ports by default. The interface required additional configuration before it could be used correctly.

This troubleshooting process improved my understanding of Cisco router interface behavior.

---

## Skills Demonstrated

- Cisco Packet Tracer
- Router Configuration
- Network Troubleshooting
- IPv4 Addressing
- Multi-Network Routing
- Interface Expansion
- Cisco IOS CLI

---

## Lessons Learned

- Configure router interfaces correctly.
- Verify interface status using `show ip interface brief`.
- Understand the difference between Layer 2 switch ports and routed interfaces.
- Always verify connectivity using ping.
- Troubleshooting is an essential networking skill.
