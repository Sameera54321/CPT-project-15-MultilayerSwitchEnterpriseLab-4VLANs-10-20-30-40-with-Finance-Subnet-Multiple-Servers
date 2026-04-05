# CPT-project-15-MultilayerSwitchEnterpriseLab-4VLANs-10-20-30-40-with-Finance-Subnet-Multiple-Servers
I’m excited to share my latest Cisco Packet Tracer project – a multilayer switched enterprise network featuring two multilayer switches, a Layer 2 access switch, four servers, multiple PCs, and a laptop. The network is segmented into four VLANs (10, 20, 30, 40) with a dedicated Finance subnet (192.168.20.0/24).


![image alt](https://github.com/Sameera54321/CPT-project-15-MultilayerSwitchEnterpriseLab-4VLANs-10-20-30-40-with-Finance-Subnet-Multiple-Servers/blob/main/15.png?raw=true)

## 📌 Summary

### Multilayer Switch Enterprise Lab is a Cisco Packet Tracer simulation that models a campus network using multilayer switching for inter‑VLAN routing. The topology includes:

    2 multilayer switches (e.g., 3560 or 3650) – providing routing between VLANs

    1 Layer 3 switch (2950‑24TT) – connecting end devices

    3 servers (Server0…Server3) – can host DHCP, DNS, web, or file services

    5 PCs (PC0…PC3) and 1 HR laptop (Laptop0)

    4 VLANs (10, 20, 30, 40) – representing different departments (HR, Finance, Engineering, IT)

    Finance subnet – 192.168.20.0/24 (likely VLAN 20)

### The project focuses on:

    Enabling IP routing on multilayer switches (ip routing)

    Creating SVIs (Switch Virtual Interfaces) for each VLAN with IP addresses

    Configuring trunk ports between switches to carry multiple VLANs

    Assigning access ports to appropriate VLANs for end devices and servers

    Verifying inter‑VLAN connectivity (ping from HR to Finance)

    Optional – DHCP server configuration on one of the servers or the multilayer switch

## ✨ Features

    ✅ 4 VLANs (10, 20, 30, 40) – logical segmentation of the network

    ✅ Multilayer switching – inter‑VLAN routing without an external router

    ✅ 2 multilayer switches – potential for redundancy or distribution layer

    ✅ 3 servers – can provide network services (DHCP, DNS, HTTP, FTP)

    ✅ Finance subnet – 192.168.20.0/24 (example IP scheme)

    ✅ End devices – PCs and laptop for testing connectivity

    ✅ Full Packet Tracer file (.pkt) – ready to open and practice

    ✅ Documentation – VLAN mapping, SVI IPs, switch configs, trunk details

## Suggested VLAN & IP Assignment:

| VLAN | Name | Subnet | SVI IP (Gateway) | Devices |
| :--- | :--- | :--- | :--- | :--- |
| 10 | HR | 192.168.10.0/24 | 192.168.10.1 | Laptop0, possibly PCs |
| 20 | Finance | 192.168.20.0/24 | 192.168.20.1 | Finance subnet (PCs?) |
| 30 | IT | 192.168.30.0/24 | 192.168.30.1 | PC0, PC1, etc. |
| 40 | Servers | 192.168.40.0/24 | 192.168.40.1 | Server0 – Server3 |

## 🛠️ Built With

    Cisco Packet Tracer – version 8.x

    CLI – multilayer switch and Layer 2 switch configurations

## 🤝 Contributing

Contributions are welcome! To extend this lab:

    Fork the repository.

    Add more VLANs or departments.

    Implement HSRP (Hot Standby Router Protocol) between the two multilayer switches for gateway redundancy.

    Configure DHCP relay to allow servers in VLAN 40 to serve addresses to other VLANs.

    Add access control lists (ACLs) to restrict inter‑VLAN traffic.

    Introduce wireless access points for a guest VLAN.

    Open a pull request with a clear description.

## 📜 License

Distributed under the MIT License. See the LICENSE file for more information.
Free to use, modify, and share for educational purposes.
