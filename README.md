# 🏢 Enterprise Multi-Department LAN Design (Cisco Packet Tracer)

A scalable and fault-tolerant enterprise network designed to support multiple departments

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

1. Download the `VLANs.pkt` file
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

## Screenshots

## Enterprise Multi-Department LAN Topology
<img width="1533" height="703" alt="1" src="https://github.com/user-attachments/assets/f78562f9-7836-4685-ae58-344a655cd048" />

## VTP Domain & Client Mode Status Verification
<img width="1909" height="365" alt="2" src="https://github.com/user-attachments/assets/47ecc7cb-91f5-4154-a9af-6fd4f3ee0e39" />

## EtherChannel Protocol & Port-Channel Verification
<img width="1891" height="791" alt="3" src="https://github.com/user-attachments/assets/7c26a0e9-0013-42ce-bb38-f679e6199e1d" />

## Access Layer Port Security Configuration
<img width="1903" height="590" alt="4" src="https://github.com/user-attachments/assets/2fad177b-6397-4f0a-bcd0-7d83a30b752c" />

## VLAN Database & Access Port Allocation
<img width="1905" height="664" alt="5" src="https://github.com/user-attachments/assets/766a7c2d-4e1f-4863-8d5d-85ded8869152" />

## Intra-VLAN Host Connectivity Testing
<img width="1919" height="698" alt="6" src="https://github.com/user-attachments/assets/a9e65388-72fe-4574-884e-4b8a9c36149b" />

## Interface Trunking & Port-Channel Status
<img width="1904" height="600" alt="7" src="https://github.com/user-attachments/assets/8e4ad427-fab0-475d-9a75-b5bc6a2deee3" />

## MAC Address Table & Port-Channel Forwarding
<img width="1919" height="407" alt="8" src="https://github.com/user-attachments/assets/af73ebaa-f256-41b2-8176-e207fdd20604" />

## Per-VLAN Spanning Tree (PVST+) Root Bridge Verification
<img width="1912" height="902" alt="9" src="https://github.com/user-attachments/assets/ec873eb2-cd88-434e-85b8-03c831364842" />


## Author
**Udeesha Jayendra**

