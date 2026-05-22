# Network Automation Journey

A hands-on network automation learning repository focused on practical automation skills using Python, GNS3, and Cisco networking technologies.

This repository documents my journey from traditional network engineering to network automation engineering through real-world labs, scripts, and mini-projects.

---

# Goals

- Learn network automation from scratch
- Build practical Python automation skills
- Automate repetitive network operations
- Work with structured data formats (JSON, YAML, CSV)
- Automate Cisco devices using SSH and APIs
- Practice real-world troubleshooting workflows
- Prepare for Network Automation Engineer roles

---

# Lab Environment

## Tools Used

- GNS3
- Cisco IOSv / C7200 Routers
- IOSvL2 Switches
- Python 3
- VS Code
- Git & GitHub

---

# Technologies & Topics

## Python
- Variables & Data Types
- Functions
- File Handling
- Exception Handling
- Modules & Packages
- Multithreading

## Network Automation
- Netmiko
- Paramiko
- NAPALM
- REST APIs
- RESTCONF / NETCONF
- JSON / YAML / CSV Parsing

## Networking
- VLANs
- Routing & Switching
- OSPF
- SSH
- Network Troubleshooting

## DevOps & Automation
- Git
- GitHub
- Docker Basics
- CI/CD Concepts
- Infrastructure as Code

---

# Repository Structure

```text
network-automation-journey/
│
├── week1/
│   ├── inventory.json
│   ├── inventory.yaml
│   ├── scripts/
│   └── outputs/
│
├── week2/
├── week3/
├── projects/
│   ├── device-health-check/
│   ├── config-backup-tool/
│   ├── vlan-provisioning/
│   └── troubleshooting-engine/
│
├── topologies/
│
├── notes/
│
└── README.md
```

---

# Weekly Learning Plan

| Week | Focus Area |
|---|---|
| 1 | JSON, YAML, Python Basics |
| 2 | SSH Automation & Netmiko |
| 3 | Parsing CLI Output |
| 4 | Inventory & Health Check Scripts |
| 5 | Multi-device Automation |
| 6 | VLAN Automation |
| 7 | APIs & RESTCONF |
| 8 | Git & DevOps Basics |

---

# Milestone Projects

## 1. Device Inventory & Health Check
- SSH into routers
- Collect device information
- Verify interface status
- Generate reports

## 2. Configuration Backup Tool
- Pull running configs
- Store timestamped backups
- Detect config changes

## 3. VLAN Provisioning System
- Read VLANs from CSV/JSON
- Deploy VLANs to switches
- Validate deployment

## 4. Automated Troubleshooting Engine
- Detect failures
- Run diagnostics
- Generate incident reports

---

# Sample Scripts

## Read JSON Inventory

```python
import json

with open("inventory.json") as file:
    devices = json.load(file)

for device in devices:
    print(device["hostname"])
```

---

# Current Progress

- [x] GNS3 setup completed
- [x] Basic Python completed
- [ ] Netmiko automation
- [ ] RESTCONF automation
- [ ] Multi-device automation
- [ ] CI/CD pipeline labs

---

# Learning Resources

## Cisco DevNet
https://developer.cisco.com/

## Netmiko
https://github.com/ktbyers/netmiko

## NAPALM
https://napalm.readthedocs.io/

## GNS3
https://www.gns3.com/

---

# Future Improvements

- Add Flask-based web dashboard
- Add Ansible playbooks
- Add Dockerized automation tools
- Add pyATS testing framework
- Add network monitoring integrations

---

# Author

Athul

Network Engineer | Learning Network Automation & NetDevOps

---

# Disclaimer

This repository is built for educational and lab purposes only.
Do not use automation scripts directly in production without proper testing and validation.
