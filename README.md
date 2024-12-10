# VoIP Network Simulation Project

This repository contains a **VoIP (Voice over IP)** network simulation designed and implemented using **Cisco Packet Tracer**.

## Project Overview

This project demonstrates the design, configuration, and testing of a VoIP communication system within a simulated network environment. The purpose of the project is to explore the functionalities of VoIP and understand how to configure essential network components to enable voice communication.

## Features

- **VoIP Communication**: Configured devices to support voice calls.
- **Network Topology**: Includes routers, switches, IP phones, and PCs.
- **DHCP Configuration**: Dynamic IP address allocation for connected devices.
- **VoIP Protocols**: Utilized SIP (Session Initiation Protocol) and RTP (Real-Time Transport Protocol).
- **Call Manager Setup**: Configured Call Manager for call routing.
- **Testing**: Verified voice communication between devices in the network.

## Tools Used

- **Cisco Packet Tracer**: Version 8.0
- **Network Devices**: Routers, switches, IP phones, PCs, and servers.

## Network Topology

The project involves the following key components:

1. **Core Devices**:
   - Router (configured as the backbone of the network).
   - Switches (to connect end devices).

2. **End Devices**:
   - IP Phones.
   - PCs (configured to test VoIP applications).

3. **Servers**:
   - Call Manager Server.
   - DHCP Server (to allocate IP addresses automatically).

## Configuration Steps

1. **DHCP Setup**:
   - Configured DHCP for automatic IP address assignment to end devices.

2. **VoIP Configuration**:
   - Set up Call Manager to handle SIP signaling.
   - Assigned unique extension numbers to IP phones.

3. **Routing & Switching**:
   - Configured routers for inter-VLAN routing.
   - Set up switches to ensure proper connectivity between devices.

4. **Testing**:
   - Tested VoIP communication between IP phones using SIP protocol.

## Results

- Successful voice communication established between IP phones.
- Call routing and signaling handled effectively by Call Manager.

## How to Use the Project

1. Install Cisco Packet Tracer (version 8.0 or higher).
2. Download the `.pkt` file from this repository.
3. Open the file in Cisco Packet Tracer.
4. Explore the configuration from the documenttion and test the VoIP calls.

## Limitations

- This project is limited to a simulated environment and does not cover real-world hardware.
- Additional considerations for security and advanced QoS techniques are not included.

## Future Enhancements

- Implement advanced security protocols for VoIP traffic.
- Expand the network to include multiple branches.
- Integrate video conferencing features.
