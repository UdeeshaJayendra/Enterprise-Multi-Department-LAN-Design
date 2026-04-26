# 🏢 Enterprise Multi-Department LAN Design (Cisco Packet Tracer)

A scalable and fault-tolerant enterprise network designed to support multiple departments.

## Technologies Used

* **VLANs (Virtual LANs)** – Department-based segmentation
* **VTP (VLAN Trunking Protocol)** – Centralized VLAN management
* **EtherChannel (LACP/PAgP)** – Link aggregation for redundancy and bandwidth improvement
* **STP (Spanning Tree Protocol)** – Loop prevention and optimized path selection
* **Port Security** – Prevents unauthorized network access
---

## Key Features

### VLAN Segmentation

* VLAN 10 – HR
* VLAN 20 – ICT
* VLAN 30 – Finance

### Redundancy with EtherChannel

* Combines multiple physical links into logical channels
* Ensures high availability and failover

### Loop Prevention with STP

* Root bridge manually configured
* Optimizes network traffic flow

### Port Security

* Limits MAC addresses per port
* Protects against unauthorized devices

## How to Run

1. Download the `Campus_Network.pkt` file
2. Open using **Cisco Packet Tracer (v8.2 or higher)**
3. Verify configuration using:

show vlan brief
show etherchannel summary
show spanning-tree

## Learning Outcomes

* Designed an enterprise-level LAN
* Implemented VLAN-based segmentation
* Configured EtherChannel for redundancy
* Optimized Layer 2 topology using STP
* Applied port-level security controls

## Author
**Udeesha Jayendra**

