# Apex Solutions Network Design
A VLAN network design and configuration project for a fictional Sydney-based company built using Cisco Packet Tracer.

## Project Overview
This project involves designing and configuring a segmented network infrastructure for Apex Solutions — separating network access for Staff, Management, and Guest users using VLANs and inter-VLAN routing.

## Network Details
- **Router:** Cisco 2911 (Apex-Router)
- **Switches:** 2x Cisco 2960 (Switch-Staff, Switch-Guest)
- **End Devices:** 7 PCs across 3 VLANs

## VLANs
| VLAN ID | Name | Subnet |
|---|---|---|
| 10 | Staff | 192.168.10.0/24 |
| 20 | Guest | 192.168.20.0/24 |
| 99 | Management | 192.168.99.0/24 |

## What I Practised
- VLAN creation and assignment on Cisco switches via CLI
- Trunk port configuration (802.1Q)
- Inter-VLAN routing using router-on-a-stick
- IP addressing and default gateway assignment
- Connectivity testing using ICMP ping

## Files
- `Apex-Solutions-Network.pkt` — Cisco Packet Tracer simulation file
- `Apex_Network_Design_Report_Sanjeel.pdf` — Full written report

## View Pr
