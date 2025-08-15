# CCNA Cisco Packet Tracer Labs

Welcome to my comprehensive CCNA preparation repository! This repository contains a curated collection of hands-on network design, configuration, implementation, and troubleshooting labs developed using **Cisco Packet Tracer**. These labs are aligned with the official Cisco Certified Network Associate (CCNA 200-301) exam blueprints.

---

## 🛠️ Complete Labs Blueprint & Technical Skills

### 1. Network Fundamentals & IP Addressing
*   **Subnetting & VLSM:** Implementing Variable Length Subnet Masking (VLSM) to optimize IPv4 allocation and reduce IP wastage.
*   **IPv6 Implementation:** Configuring IPv6 global unicast, link-local addressing, and stateless autoconfiguration (SLAAC).
*   **Cisco IOS Navigation:** Mastering CLI modes (User EXEC, Privileged EXEC, Global Configuration) and basic device hardening (banners, hostnames, and passwords).

### 2. Advanced Routing Technologies (Layer 3)
*   **Inter-VLAN Routing:** Configuring Router-on-a-Stick (Subinterfaces) and Layer 3 Switch Multi-Layer Routing (SVIs).
*   **Static & Default Routing:** Designing redundant paths using Floating Static Routes by modifying Administrative Distance (AD).
*   **OSPFv2 (Single-Area):** Configuring Open Shortest Path First (OSPF), tuning OSPF timers, adjusting interface cost, and verifying neighbor adjacencies and the LSDB.

### 3. Switching & Infrastructure Services (Layer 2)
*   **VLANs & Trunking:** Creating VLANs and configuring 802.1Q encapsulation trunk links, native VLANs, and allowed VLAN lists.
*   **EtherChannel (Link Aggregation):** Bundling links using PAgP (Cisco proprietary) and LACP (IEEE 802.3ad) for high bandwidth and link redundancy.
*   **Spanning Tree Protocol (STP):** Understanding PVST+ and Rapid PVST+, modifying root bridge priorities, and configuring PortFast and BPDU Guard to protect access ports.

### 4. Network Security & Access Control
*   **Access Control Lists (ACLs):** Deploying Standard ACLs for source filtering and Extended ACLs for precise protocol, port, and destination traffic control.
*   **Switchport Security:** Mitigating MAC flooding attacks by limiting allowed MAC addresses per port and defining violation actions (Shutdown, Restrict, Protect).
*   **Device Hardening:** Configuring secure remote management via SSH (blocking vulnerable Telnet) and enabling AAA/Local database authentication.

### 5. IP Services & Network Automation
*   **NAT/PAT:** Implementing Static NAT, Dynamic NAT, and Port Address Translation (NAT Overload) to preserve public IPv4 space.
*   **DHCP & DHCP Relay:** Configuring Cisco routers as DHCP servers (with excluded pools) and setting up IP Helper Addresses for multi-subnet environments.
*   **Network Discovery & Management:** Utilizing CDP (Cisco Discovery Protocol) and LLDP for topology mapping, along with Syslog, NTP, and device backup management.

---

## 💻 Laboratory Files Guide

The repository includes specific `.pkt` network topologies targeting dedicated core concepts:
*   `access list extended.pkt`: Comprehensive packet filtering and firewall-like rules using Extended ACLs.
*   `cdp-lldp.pkt`: Network discovery and multi-vendor neighbor analysis topologies.
*   `dynamic-ro1.pkt`: Dynamic routing protocols deployment and path optimization labs.
*   `back up.pkt` / `back up1.pkt`: Disaster recovery, running-config backups, and TFTP file management.

---

## 🚀 How to Run These Labs

To execute and study these laboratory files, follow these steps:

1. Download and install the latest version of [Cisco Packet Tracer](https://www.netacad.com/).
2. Clone this repository locally:
   ```bash
   git clone [https://github.com/essam-elsharkawy/CCNA-Packet-Tracer-Labs.git](https://github.com/essam-elsharkawy/CCNA-Packet-Tracer-Labs.git)