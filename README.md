# Network Configuration Simulation

## Overview

This project implements a network simulation using Cisco Packet Tracer. It covers the setup and configuration of routing protocols and various network services. The network consists of two main segments: RIP and OSPF, which are divided into multiple OSPF areas. Several network services such as DHCP, DNS, Telnet, and Access Control Lists (ACL) are configured to provide dynamic address allocation, domain name resolution, and secure access control.

## Features

- **Network Segmentation**:
  - RIP and OSPF configuration, with OSPF divided into Backbone, Totally Stubby, and Stub areas.
- **Routing Protocols**:
  - Configuration of RIPv2 and OSPF to ensure network connectivity between all devices.
- **DHCP**:
  - Dynamic IP allocation for devices in OSPF and RIP segments.
- **Telnet**:
  - Remote access to router R1 using Telnet.
- **DNS**:
  - Local DNS setup for domain name resolution.
- **Access Control Lists (ACL)**:
  - Configuring ACLs to secure the network by controlling access to services like DNS and web servers.

## Project Files

- **`network.pkt`**: Packet Tracer file containing the network topology and configurations.
- **`network_topology.png`**: The picture of network topology
  
## Usage

1. **Open in Packet Tracer**: Load the provided `.pkt` file in Cisco Packet Tracer.
2. **Run the Simulation**: View or modify the configuration using the provided command scripts.
3. **Test Connectivity**: Use tools within Packet Tracer to verify the routing protocols, DHCP, DNS, and ACL functionalities.

## Dependencies

- **Cisco Packet Tracer**: Version 8.0 or newer is required to open and simulate the provided `.pkt` file.
