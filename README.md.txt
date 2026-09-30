# Simple Hybrid Network

## Project Overview

This project is a simple hybrid network built in Cisco Packet Tracer to practice fundamental networking concepts. The network represents how end-user devices, switches, routers, VLANs, subnets, and network services work together to provide communication between multiple networks.

## Skills Practiced

- Cisco Packet Tracer
- Network topology design
- Ethernet cabling
- VLAN configuration
- IPv4 addressing
- Subnetting
- Default gateways
- Static routing
- DNS
- HTTP
- Connectivity testing
- Network troubleshooting

## Network Topology

Each location uses a star topology where end devices such as computers and printers connect to a central switch. Switches forward Ethernet frames between devices on the local network.

Routers connect the different networks and route IP traffic between them. The routers are interconnected to create the wider hybrid network.

## VLANs

VLANs were used to logically separate devices into different networks. This helps organize network traffic and creates separate broadcast domains even when devices are connected to the same physical switch.

## Subnetting and Device Addressing

Each network was assigned its own subnet based on the number of devices it needed to support. The goal was to provide enough usable IP addresses for each network without unnecessarily wasting address space.

Devices were then assigned IP addresses, subnet masks, default gateways, and other required network settings.

## Routing

Router interfaces were configured with IP addresses to serve as gateways for the connected networks.

Static routes were configured so routers could determine how to reach networks that were not directly connected to them.

## DNS and HTTP

DNS and HTTP services were configured to demonstrate basic network services.

DNS allows users to access resources using names instead of having to remember IP addresses.

HTTP provides access to web resources hosted on the network.

## Testing and Troubleshooting

The completed network was tested using tools such as `ping` and other Cisco Packet Tracer troubleshooting methods.

Testing was used to verify:

- Communication between devices
- Communication between VLANs and networks
- Router connectivity
- Static routing
- DNS resolution
- HTTP access

## Project Files

The Cisco Packet Tracer `.pkt` file is included in the `packet-tracer` folder.

Additional screenshots and documentation will be added to demonstrate the network configuration and testing process.