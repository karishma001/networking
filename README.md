 NetPath Illuminator: The Network Odyssey

 Overview
The NetPath Illuminator project integrates practical networking lab experiences with an innovative tool for visualizing packet flow through network devices and topologies. It aims to provide real-time graphical representations of data packet journeys, allowing users to query network events and understand interactions with switches, routers, and subnet boundaries.

 Project Description

### 1. Networking Fundamentals Integration
Students will simulate network environments using knowledge from Levels 1 to 8, covering ARP, MAC tables, switching, IP routing, routing tables, static and dynamic routing protocols.

### 2. Packet Sniffer
Use tools like Packet Capture or Wireshark to capture packets in various Levels in pcap format.

### 3. Visualization Component
Input packet captures into a database and design a system to graphically display packet flow, highlighting the path, intermediate devices, routing decisions, and final delivery.

### Expansion
Develop an AI-powered packet analyzer, inspired by open-source projects like Packet Buddy or Packet RAPTOR.

## Levels

### Level-1
Connect two PCs, assign IP addresses, and explore ARP, MAC addresses, and ARP tables using commands like `arp -d` and `arp -a`.

### Level-2
Connect multiple computers using a switch, perform "ping" tests, and explore the MAC table and VLANs.

### Level-3
Connect two computers directly with different IP addresses and subnets, investigate failed ping operations, and understand the need for routers.

### Level-4
Connect two computers using a router, perform ping tests, and examine routing tables and the default gateway using `show ip route` and `show ip int brief`.

### Level-5
Connect multiple computers using a router and a switch, perform ping tests, and explore routing, ARP, and MAC tables.

### Level-6
Configure static routes between networks, examine the Routing Information Base (RIB), and use `show ip route`.

### Level-7
Configure OSPF on routers, examine OSPF behavior, and observe routing tables using OSPF-specific commands.

### Level-8
Establish connectivity using OSPF, configure primary and backup paths, capture packets, and investigate OSPF's dynamic rerouting.

## Deliverables

- Simulate all network Levels and capture commands.
- Use packet sniffers or Wireshark to intercept packets, analyze headers, and create flow diagrams.
- Use flowchart tools to illustrate packet paths.

## Assessment Criteria

Upon completion, students should be able to:

- Explain MAC learning and IP networking distinctions.
- Differentiate between Layer 2 and Layer 3 networks.
- Explain subnetting, ARP, and the role of a default gateway.
- Troubleshoot connectivity issues.
- Differentiate between a router and a switch.
- Articulate static routing and network connectivity.
- Define RIB and routing protocols.
- Explain the ping function and develop a ping program using C/C++.
- Describe packet flow from a PC to an external web server.


