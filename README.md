# Network Configuration, Security & Troubleshooting

A hands-on LAN networking project: connecting a router and multiple laptops in a Star topology, configuring static IP addressing, securing the network at the application and MAC-filtering level, enabling remote access, and diagnosing a real connectivity fault.

## Overview

This project simulates a small local area network in a controlled environment (no internet access), built to understand device communication, network security fundamentals, and structured troubleshooting.

## What We Built

**1. Network Setup**
- Connected multiple laptops to a router via Ethernet in a Star topology
- Assigned static IP addresses (subnet mask, default gateway) to each device
- Verified connectivity between all devices using `ping`

**2. Application-Level Security**
- Configured Windows Firewall to block a specific chat application (BeeBEEP) from accessing the network
- Tested and confirmed the blocked application could no longer connect while other network traffic remained unaffected

**3. LAN Communication Tools**
- Used LAN Messenger for text chat and voice/video calls between devices without internet access

**4. Remote Access**
- Used TeamViewer to establish full remote control of another device within the LAN

**5. MAC Address Filtering**
- Accessed the router's MAC Filter settings and reviewed the blacklist of restricted devices
- Identified all connected devices and their MAC addresses via the router's device list

**6. Troubleshooting Case Study**
While testing connectivity, we encountered a **"Destination Unreachable"** error using `ping`. We diagnosed the issue methodically:
1. Suspected a hardware/cabling issue → replaced USB-based connections with more stable Type-C cables (issue persisted)
2. Suspected the network equipment → replaced the router itself
3. Result: connectivity fully restored, `ping` succeeded with 0% packet loss

## My Contribution

This was a 6-member group project. Along with three teammates, I worked on the network setup, connectivity configuration, application security (firewall), and troubleshooting tasks described above.

## Tools Used

Windows Firewall · TeamViewer · LAN Messenger · BeeBEEP · Router MAC Filter settings · Command Prompt (`ping`, `ipconfig`)
