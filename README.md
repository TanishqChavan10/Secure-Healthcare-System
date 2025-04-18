🏥 Secure Health Care Network – Cisco Packet Tracer Project
This project simulates a secure healthcare network for a multi-floor hospital, emphasizing network segmentation, security, and efficient communication across departments.

📄 Project Overview

![image](https://github.com/user-attachments/assets/7075e42c-cb59-422a-b27d-019ff42264a6)


The hospital comprises six departments spread over three floors. The network design ensures:

Segmentation of LAN, WLAN, and VoIP traffic using VLANs

Secure remote access via SSH

Efficient routing with EtherChannel and trunking

Redundancy with backup servers

Integration with simulated AWS cloud services

🛠️ Technologies & Tools
Cisco Packet Tracer

Devices: Cisco ASA 5500-X Firewall, WAN Router, Catalyst 3850 & 2950 Switches

Servers: DNS, DHCP, Email, HIS, File Server

Protocols: VLANs, STP, BPDU Guard, SSH

Simulated AWS Cloud Instances

🧩 Network Design Highlights
VLAN Configuration:

VLAN 10: LAN

VLAN 50: WLAN

VLAN 99: VoIP

Port Assignments:

Ports 3-20: LAN Users

Ports 21-24: Wireless Access Points

Security Measures:

SSH enabled on all switches and routers

BPDU Guard and STP PortFast on access ports

Access Control Lists (ACLs) for traffic filtering

Redundancy & Failover:

Two servers for DNS and DHCP services

Backup configurations for critical services

Cloud Integration:

Simulated AWS cloud network with dummy instances

Connectivity for remote patient access

🖥️ Setup & Configuration
Switch Configuration

Router Configuration

Firewall Setup

Server Deployment

Wireless Configuration

Cloud Simulation

(Detailed steps mentioned in the full guide)

🖼️ Network Topology Screenshot

📚 Learning Outcomes
Designing segmented and secure networks

Implementing VLANs and inter-VLAN routing

Configuring network devices with security best practices

Simulating cloud integrations within local networks
