Network Infrastructure Project
Overview

This project is a simulation of an enterprise network infrastructure built using Cisco Packet Tracer.
It demonstrates the design, implementation, and configuration of a secure and scalable network across multiple locations (Location A, Location B, and a remote branch).

The topology includes routers, multilayer switches, VLAN segmentation, firewalls, wireless controllers, access points, and servers to provide end-to-end connectivity and security.

Features

Multi-location Network:

Location A and Location B connected via multiple routers.

Remote branch office integrated into the core topology.

Routing & Switching:

Static and dynamic routing between networks.

VLAN segmentation for different departments.

Inter-VLAN routing with multilayer switches.

Security:

Host-based firewall installed on end-user PCs.

Network-based firewall implemented between core routers and servers.

Wireless Network:

Wireless LAN Controller (WLC) managing Lightweight Access Points.

Wireless VLANs for mobile devices and laptops.

Servers:

Main server for internal services (e.g., DHCP, DNS).

Additional servers connected to Location B for redundancy.

IP Addressing Scheme

VLAN 10: 172.16.10.0/24

VLAN 20: 172.16.20.0/24

Interconnection Networks:

10.20.10.0/24, 10.5.1.0/24, 10.16.1.0/24, etc.

Location A LAN: 192.168.10.0/24, 192.168.15.0/24

Location B LAN: 172.15.0.0/24, 172.15.10.0/24

Remote Branch: 192.168.200.0/24

Devices Used

Routers: Multiple Cisco Routers for WAN connectivity.

Switches: Layer 2 and Layer 3 switches for VLANs and inter-VLAN routing.

Firewall: Dedicated firewall appliance securing the network perimeter.

Servers: DNS, DHCP, and application servers.

Wireless: WLC and Lightweight APs for wireless coverage.

End Devices: PCs, Laptops, Smartphones, and VoIP Phones.

Objectives

Design a network supporting both wired and wireless connectivity.

Implement VLANs for traffic segmentation and security.

Ensure secure routing between multiple sites.

Demonstrate firewall usage at both host and network level.

Provide redundancy and scalability for enterprise deployment.

How to Use

Open the file PROJECT.pkt in Cisco Packet Tracer.

Start the simulation mode to test connectivity between devices.

Verify:

Inter-VLAN communication.

Firewall filtering.

Wireless device connectivity.

End-to-end ping between Location A, Location B, and remote branch PCs.

Future Improvements

Add VPN connectivity for remote users.

Configure advanced security features (ACLs, IDS/IPS).

Implement load balancing between multiple servers.

Introduce QoS for VoIP traffic.

✦ Author: Vũ Quang Khải
✦ Tool Used: Cisco Packet Tracer
✦ Project Goal: Network Engineer Internship Preparation
