# 🌐 Packet Tracer - Basic Connectivity Lab


This project demonstrates a fundamental networking lab focused on configuring switches, assigning IP addresses, and verifying connectivity between devices using Cisco Packet Tracer.



## 🎯 Objectives


- Configure basic settings on switches (S1 & S2)
- Assign IP addresses to PCs and switches
- Configure Switch Virtual Interface (SVI)
- Verify connectivity using ping and show commands



## 🧪 Lab Overview



### 🔹 Network Topology


- 2 Switches (S1, S2)
- 2 PCs (PC1, PC2)
- Single network: 192.168.1.0/24



### 🔹 IP Addressing


| Device | Interface | IP Address     | Subnet Mask     |
|--------|----------|----------------|-----------------|
| S1     | VLAN 1   | 192.168.1.253  | 255.255.255.0   |
| S2     | VLAN 1   | 192.168.1.254  | 255.255.255.0   |
| PC1    | NIC      | 192.168.1.1    | 255.255.255.0   |
| PC2    | NIC      | 192.168.1.2    | 255.255.255.0   |



## ⚙️ Configuration Steps



### 1️⃣ Switch Configuration


- Set hostname (S1, S2)
- Configure VLAN 1 interface
- Assign IP address to SVI
- Enable interface using `no shutdown`
- Save configuration



### 2️⃣ PC Configuration


- Assign static IP addresses
- Configure subnet mask



### 3️⃣ Connectivity Testing


- Used `ping` to verify communication between:
  - PC ↔ Switch
  - PC ↔ PC
  - Switch ↔ Switch
 
  - 

### 4️⃣ Verification Commands


- `show ip interface brief`
- `ping`
- `copy running-config startup-config`



## 💡 Key Concepts Learned



- Role of SVI (Switch Virtual Interface)
- Importance of IP addressing in network management
- Basic troubleshooting using ping
- Understanding initial connectivity issues (ARP resolution)



## 🚀 Outcome


- Successfully established full network connectivity
- All devices were able to communicate with each other
- Strengthened understanding of networking fundamentals


## 📌 Tools Used



- Cisco Packet Tracer


---


💻 This lab is part of my hands-on networking practice and foundational learning in cybersecurity and cloud networking.
