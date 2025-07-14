# LAN-Scenario-01
# LAN Scenario 01 - Basic Network with Switch and PCs

This scenario demonstrates a simple LAN with 3 PCs connected via a Cisco 2960 switch.
All PCs are configured with static IPs in the 192.168.1.0/24 subnet, and connectivity is tested using `ping`.

## Topology

![Topology Screenshot](./topology.jpg)

## Devices Used
- Cisco 2960 Switch
- 3 PCs
- Straight-Through Ethernet Cables

## IP Configuration

| Device | IP Address | Subnet Mask |
|--------|------------|-------------|
| PC0    | 192.168.1.10 | 255.255.255.0 |
| PC1    | 192.168.1.11 | 255.255.255.0 |
| PC2    | 192.168.1.12 | 255.255.255.0 |

## Results

All PCs successfully ping each other.  
No connectivity issues observed.

---
📎 Packet Tracer File: `LAN_Scenario_3PCs_Switch.pkt`  
📄 PDF Report included.
