# Cisco Enterprise Network Simulation – Albion Project

This project is a complete simulation of an enterprise network designed using **Cisco Packet Tracer**. It includes both a main campus network and a remote branch office. The goal is to demonstrate practical knowledge of network design, VLAN configuration, subnetting, and inter-VLAN routing using Cisco devices.

## Project Overview

The network is divided into two major sections: the **Albion Main Network** and the **Albion Branch Network**. These two locations are connected through a routed WAN link (`10.10.10.0/30`), simulating real-world enterprise connectivity between sites.

### Albion Main Network

The main network is organized across three buildings: **Building A**, **Building B**, and **Building C**. Each building contains various departments assigned to specific VLANs. Every department has its own switch, PC workstations, and printers. Servers such as FTP and Web servers are hosted in the IT department.

Departments are segmented into VLANs to separate traffic logically and improve security. Inter-VLAN communication is handled by a Layer 3 switch. Each VLAN is assigned a unique subnet for IP addressing.

### Albion Branch Network

The branch site mirrors the organizational structure of the main network but at a smaller scale. It includes VLANs for departments like `LAB_STUDIO` and `STAFF`, with corresponding PCs and printers. These VLANs are also subnetted and managed through switches connected to a central routing device. The branch office connects to the main site over the `10.10.10.0/30` link.

## Technologies Used

- Cisco Packet Tracer
- Layer 2 and Layer 3 Cisco Switches
- VLAN configuration and management
- Static routing and inter-VLAN routing
- Subnetting and IP address planning
- Server setup (Web and FTP)
- Network printing and host configuration

## Objective

This simulation was built as part of my hands-on learning in computer networking, and to strengthen my skills in enterprise network setup, as required for certifications like **CompTIA Network+** and **Cisco CCNA**. The goal was to replicate a realistic network layout that demonstrates an understanding of how to design and configure an efficient, secure, and scalable network infrastructure.
