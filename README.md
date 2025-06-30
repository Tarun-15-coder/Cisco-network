# Cisco-network
This project demonstrates a simulated multi-building campus network using Cisco Packet Tracer, designed with VLAN segmentation, inter-VLAN routing, and inter-campus communication.
Network Overview
Main Campus (Block A):
Router: 2911 Main Campus R
Core Layer: Multilayer Switch (3560-24PS)

VLANs:
VLAN 20 (192.168.2.0/24) – Eco Dept. (Building A)
VLAN 30 (192.168.3.0/24) – Business Dept. (Building A)
VLAN 40 (192.168.4.0/24) – Lab (Building B)
VLAN 50 (192.168.5.0/24) – IT Dept. (Building B)

Servers: FTP and Web

Branch Campus (Block B):

Router: 2911 Branch Campus R

Core Layer: Multilayer Switch1 (3560-24RS)

VLANs:
VLAN 70 (192.168.9.0/24) – Staff (Building C)
VLAN 80 (192.168.8.0/24) – Student Lab (Building C)

Cloud Network:
Email Server connected via router 2911 Cloud
WAN connections using /30 subnets:

10.10.10.0/30 – Block A ↔ Block B

10.10.10.4/30 – Block A ↔ Cloud

20.0.0.0/30 – Cloud ↔ Email Server
