# 🛡️ Cyber Security Home Lab Setup

**Project Duration:** February 2025 – March 2025  
**Purpose:** To build a hands-on environment for experimenting with cybersecurity tools, simulating real-world attack scenarios, and strengthening blue team capabilities.

---

## 🔍 Overview

This project provided a controlled, virtualized lab for testing and learning various cybersecurity techniques. It deepened my understanding of network vulnerabilities, attack vectors, and defense mechanisms. The lab enabled practical skill development in threat hunting, incident response, and security tool configuration.

---

## 🧩 Key Components

### ⚔️ Attack Platform
- **Kali Linux VM** (`192.168.233.133`)
- Used for ethical hacking, penetration testing, and simulating adversarial behavior.

### 🔐 Security Gateway
- **OPNsense Firewall** (`192.168.29.130`)
- Configured to manage traffic, enforce security policies, and monitor ingress/egress activity.

### 🎯 Target Network
- **Simulated Internal Network** (`192.168.200.133`)
- Includes a Domain Controller and client machines to mimic a vulnerable enterprise environment.

### 📊 SIEM Integration
- **Splunk Enterprise** (`192.168.246.133`) with Universal Forwarder
- Centralized log collection, correlation, and alerting for threat detection and incident response.

### 🧱 Network Segmentation
- **VMware Virtual Networks**: Vmnet2–Vmnet6
- Logical separation of lab zones to simulate DMZ, internal, and attacker networks.

### 📡 Traffic Monitoring
- **SPAN Port** on interface `em4` within Splunk
- Captures mirrored traffic for forensic analysis and anomaly detection.

---

## 🧠 Skills Demonstrated

- Network Traffic Analysis  
- Log Analysis & Threat Detection  
- SIEM Deployment & Administration (Splunk)  
- Firewall Configuration & Management (OPNsense)  
- Virtualization Technologies (VMware)  
- Network Security Principles & Implementation  

---

## 📁 Repository Contents

- `README.md` – Project overview and documentation  
- `configs/` – Sample firewall rules, Splunk inputs, and network diagrams *(optional)*  
- `scripts/` – Log generators, threat simulation scripts *(optional)*  
- `screenshots/` – Visuals of lab setup and dashboards *(optional)*  

---

## 🚀 Future Enhancements

- Integration with ELK Stack  
- Automation with Ansible  
- Threat emulation using Atomic Red Team  

---

> This lab was built for educational and professional development purposes. All IPs and configurations are internal and non-routable.

