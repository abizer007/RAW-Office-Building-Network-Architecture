# RAW Office Building Network Architecture

# 🛰️ RAW Office Network Infrastructure

Welcome to the GitHub repository for the **RAW Office Network Infrastructure Project**. This repository contains a comprehensive design and implementation of a secure, scalable, and efficient network tailored for the Research and Analysis Wing (RAW) office environment.

---

## 🚀 Project Overview
This project addresses the need for a robust network capable of supporting critical intelligence operations by integrating advanced security, scalability, and efficient communication solutions.

**Key Objectives:**
- Secure communication across departments and remote users
- Advanced network security with firewalls, VPNs, and IDS/IPS
- High availability and redundancy
- Efficient resource sharing



![image](https://github.com/user-attachments/assets/d3511a2f-2e09-429e-9c4f-0b55dc07d6af)



---

## 🧩 Architecture Highlights

| Feature                             | Description                                  |
|-------------------------------------|----------------------------------------------|
| **Client-Server Model**             | Centralized management for essential services|
| **Hybrid Network**                  | Combination of client-server & peer-to-peer |
| **VLAN Segmentation**               | Enhanced security and efficient management  |
| **Redundant Network Paths**         | High availability and fault tolerance       |



---

## 🌐 Network Topologies

- **⭐ Star Topology**: General office use, easy management, and scalability.
- **🔗 Mesh Topology**: Critical departments for redundancy.
- **🔄 Hybrid Topology**: Flexibility for various departmental needs.



---

## 🔌 Transmission Medium & Hardware

- **Ethernet (Cat6)**: Cost-effective, internal connectivity
- **Fiber Optics**: High-speed inter-floor connections
- **Wi-Fi (Access Points)**: Flexible mobile connectivity



---

## 🔐 Security Features

Ensuring top-tier security with:
- Next-Generation Firewalls (Cisco ASA)
- Intrusion Detection and Prevention (IDS/IPS)
- Secure VPN Access
- Zero Trust Architecture (ZTA)
- AES-256 Data Encryption
- DNS Security (DNSSEC)



---

## 📌 VLAN & IP Addressing

| VLAN ID | Department                   | IP Range             |
|---------|------------------------------|----------------------|
| 10      | Counterintelligence          | `192.168.10.0/24`    |
| 20      | Cyber Surveillance Unit      | `192.168.20.0/24`    |
| 30      | Strategic Operations         | `192.168.30.0/24`    |
| 40      | Cryptanalysis Division       | `192.168.40.0/24`    |
| 50      | IT and Communications        | `192.168.50.0/25`    |
| 60      | Server Room                  | `192.168.60.0/27`    |
| 70      | Wireless Network             | `192.168.70.0/22`    |


---

## ⚙️ Routing Protocols

- **TCP/IP**: Reliable data transfer and routing
- **OSPF**: Optimized inter-VLAN routing



---

## 🛡️ Firewall & DMZ Configuration

| Interface         | Security Level | Description                             |
|-------------------|----------------|-----------------------------------------|
| Internal Network  | 100            | Secure and trusted internal network     |
| DMZ               | 50             | Semi-trusted, hosting public services   |
| External Network  | 0              | Untrusted, controlled external access   |


---

## 📈 Industry Relevance
This design mirrors enterprise-level setups employed by:
- ✅ **Cisco Systems**
- ✅ **IBM**
- ✅ **AWS**

Incorporating multi-layered firewalls, zero-trust principles, and advanced threat protection.

---

## 🎯 Conclusion
The implemented network infrastructure is robust, secure, and highly scalable, serving as a foundational blueprint adaptable for larger, complex environments.

---

## 📚 References
- Cisco ASA 5500-X Series Documentation
- Data and Computer Communications by William Stallings
- Computer Networks by Tanenbaum and Wetherall
- AWS & Google Cloud network security best practices

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
