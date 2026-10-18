# 🌐 IronOne Enterprise Network Design & Implementation

<p align="center">
  <strong>A Departmental Network Design Project Implemented Using Cisco Packet Tracer</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Cisco-Packet%20Tracer-00AEEF" alt="Cisco Packet Tracer">
  <img src="https://img.shields.io/badge/VLAN-Network%20Segmentation-8B5CF6" alt="VLAN">
  <img src="https://img.shields.io/badge/IPv4-Addressing-10B981" alt="IPv4">
  <img src="https://img.shields.io/badge/VLSM-Subnetting-F59E0B" alt="VLSM">
  <img src="https://img.shields.io/badge/Router-Network%20Routing-EF4444" alt="Router">
  <img src="https://img.shields.io/badge/Switch-Layer%202%20Networking-2563EB" alt="Switching">
  <img src="https://img.shields.io/badge/Inter--VLAN-Routing-DB2777" alt="Inter-VLAN Routing">
  <img src="https://img.shields.io/badge/IP%20Subnetting-Network%20Planning-0891B2" alt="IP Subnetting">
  <img src="https://img.shields.io/badge/Server-Network%20Services-7C3AED" alt="Server">
  <img src="https://img.shields.io/badge/PC-End%20Devices-65A30D" alt="End Devices">
  <img src="https://img.shields.io/badge/Topology-Network%20Design-E11D48" alt="Network Topology">
  <img src="https://img.shields.io/badge/CLI-Device%20Configuration-475569" alt="CLI Configuration">
  <img src="https://img.shields.io/badge/ICMP-Ping%20Testing-D97706" alt="Ping Testing">
</p>

---

## 📌 Project Overview

This project focuses on the design and implementation of a departmental enterprise network for **IronOne**, using Cisco Packet Tracer.

The network is organized into separate departmental LANs, with dedicated VLANs and IP address ranges based on departmental host requirements. The design includes network devices, end-user workstations, server connectivity, and router-based communication between network segments.

The project demonstrates practical networking concepts, including network topology design, IPv4 addressing, VLSM subnetting, VLAN segmentation, device configuration, and connectivity testing.

## 🌐 Network Design

### Network Topology

The network topology illustrates the departmental network layout, device interconnections, access switches, router connectivity, and server room.

![IronOne Network Topology](Network%20Design/IronOne-Network-Blueprint.png)

*Figure: IronOne departmental network topology designed in Cisco Packet Tracer.*

> Replace the image path above with the actual location and filename of your network screenshot in this repository.

---

## 🏢 Departmental Network Segmentation

The network design separates departments into individual IP subnets and VLANs.

| Department | VLAN ID | IP Address Range | Subnet |
|---|---:|---|---|
| Developers | 10 | `192.168.10.2 – 192.168.10.62` | `/26` |
| Finance | 20 | `192.168.10.66 – 192.168.10.94` | `/27` |
| Sales & Marketing | 30 | `192.168.10.98 – 192.168.10.126` | `/27` |
| Customer Care | 40 | `192.168.10.130 – 192.168.10.142` | `/28` |
| HR | 50 | `192.168.10.146 – 192.168.10.158` | `/28` |
| Network Team | 60 | `192.168.10.162 – 192.168.10.166` | `/29` |
| Legal | 70 | `192.168.10.170 – 192.168.10.174` | `/29` |
| Server Room | — | `10.254.1.0/24` | `/24` |

The departmental subnets use VLSM to allocate address ranges according to the estimated host requirements.

---

## 🔧 Technologies & Networking Concepts

This project covers the following networking concepts:

| Networking & Infrastructure | Implementation & Testing |
|---|---|
| 🏢 Enterprise Network Topology | 🖥️ Cisco Packet Tracer |
| 🔀 VLAN Configuration | ⚙️ Router & Switch Configuration |
| 🌐 IPv4 Addressing | 📐 VLSM Subnetting |
| 🔢 Subnet Mask Calculation | 🔗 Device Connectivity |
| 🖧 Departmental LAN Design | 🗄️ Server Network |
| 🔄 Inter-VLAN Routing Concepts | 🔍 Network Troubleshooting |
| 📋 Network Documentation | 🧪 Connectivity Verification |

> The table describes the project's networking scope; individual features should be claimed as implemented only where supported by the actual Packet Tracer file and configuration.

---

## 🎯 Project Objectives

The primary objectives of this project are to:

- Design a structured departmental enterprise network.
- Separate departmental networks using VLANs.
- Develop an IP addressing plan using VLSM.
- Allocate subnet ranges based on host requirements.
- Connect end-user devices through network switches.
- Configure router and switch interfaces.
- Provide communication between network segments where required.
- Include server connectivity within the network design.
- Test connectivity and troubleshoot network issues.
- Document the network topology and addressing structure.

---

## 🛡️ Network Design & Management

The network design focuses on:

### 🔀 Network Segmentation

Departmental networks are separated using VLAN IDs and dedicated IP subnets to create a structured network environment.

### 🌐 IP Address Management

VLSM is used to allocate different subnet sizes according to the estimated number of hosts in each department.

### 🖧 Network Connectivity

Routers and switches provide the infrastructure for connecting departmental devices and the server room.

### 🔍 Verification & Troubleshooting

Connectivity testing can be performed using tools such as `ping` and `tracert` where supported by the implemented topology.

---

## 📁 Repository Structure

```text
IronOne-Network-Project/
│
├── Network Design/
│   └── IronOne-Network-Blueprint.png
│
├── Documentation/
│   └── IronOne-Network-Documentation.pdf
│
├── LICENSE
└── README.md
```

> Note: Complete Packet Tracer source files and full device configuration files are intentionally excluded from the public repository to protect the originality and intellectual ownership of the project.

---

## 💻 Cisco Packet Tracer Project

The network was designed using Cisco Packet Tracer to represent the departmental network layout and device connectivity.

The original simulation file may contain the topology and device configurations associated with the implementation.

The public repository is intended to showcase the project design and demonstrate networking knowledge. The complete simulation file and detailed configurations may be kept private to protect the originality of the work.

---

## 🔒 Copyright & Usage Policy

### © 2023 Yesmin Jalaldeen. All Rights Reserved.

This repository showcases project materials prepared for educational, portfolio, and demonstration purposes.

The original network diagrams, project documentation, configurations, and implementation materials are protected by the author's stated usage policy, subject to any applicable third-party or institutional rights.

**No permission is granted to reproduce, modify, redistribute, republish, or submit the author's original project materials as another person's work without prior written permission.**

This policy applies to original materials associated with the project, including:

- Network diagrams and topology designs.
- Original configuration files.
- Project documentation and reports.
- Original project-specific implementation materials.

Access to a public repository does not, by itself, grant permission to reuse the author's original materials. Any reuse must respect applicable third-party rights and academic requirements.

### 📩 Permission Requests

Anyone wishing to reuse or redistribute protected original materials must obtain prior written permission from the author.

---

<div align="center">

### ✍️ Yesmin Jalaldeen

*Network Design & Implementation Project*

**BIT (Hons) Specialized in Computer Networks**  
**BCS HEQ PGD in Computer Networks**

*“Designing Structured Networks Through Practical Implementation.”*

**© 2023 Yesmin Jalaldeen — All Rights Reserved.**

</div>
