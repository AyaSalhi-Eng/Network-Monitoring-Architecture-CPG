# Network Infrastructure Supervision | CPG Industrial Case Study

## 📌 Project Overview
Design and implementation of a centralized network monitoring solution for the **Compagnie des Phosphates de Gafsa (CPG)**. This project focused on ensuring high availability and real-time visibility for a complex industrial multi-site infrastructure.

<p align="center">
  <img src="https://github.com/user-attachments/assets/5f67096d-8672-40ae-a80e-31a741906a40" alt="Topologie Réseau CPG OpManager" width="900">
  <br>
  <i>Figure 1 : Visualisation de la topologie du Datacenter (Core Switches, Firewalls, MPLS) sous OpManager.</i>
</p>

## 🏗️ Infrastructure Architecture
The supervised network follows a hierarchical design (Core, Distribution, and Access layers) supporting industrial operations across multiple sites:
* **Core Layer:** High-speed backbone routing and redundancy.
* **Distribution Layer:** Inter-VLAN routing and policy-based connectivity.
* **Access Layer:** End-device connectivity and VLAN segmentation (VLAN 10, 20, 30).

## 🛠️ Technical Stack & Implementation
* **Monitoring Solution:** ManageEngine OpManager Plus.
* **Network Hardware:** Cisco Layer 3 Switches & Routers.
* **Protocols:** SNMP v3 (Secure Authentication & Encryption), ICMP, WMI, Syslog.
* **Security:** Implementation of secure polling and role-based access for network administration.

## 🚀 Key Engineering Achievements
* **Automated Node Discovery:** Configured secure SNMPv3 scanning for 100+ network devices.
* **KPI Monitoring:** Real-time tracking of Packet Loss, Latency, Bandwidth Usage, and CPU/RAM health.
* **Proactive Alerting:** Established multi-level threshold alerts (Critical/Warning) to minimize industrial downtime.
* **L3 Troubleshooting:** Analyzed bottlenecks and interface errors within the multi-site backbone.
* **Executive Reporting:** Designed automated performance dashboards for IT governance.

--- 
**Aya Salhi** | *Communications & Networks Engineer (EUR-ACE Label)*
