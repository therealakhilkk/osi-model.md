Data Link Layer (Layer 2) of the OSI Model
The Data Link Layer is the second layer of the OSI model, responsible for enabling reliable communication between directly connected devices. 
It ensures error-free data transfer between network nodes and controls access to the physical transmission medium.

Functions 

Framing
Converts raw bits into frames for efficient transmission.
Example: Ethernet frames contain source MAC, destination MAC, and payload.

MAC Addressing
Uses MAC (Media Access Control) addresses to uniquely identify devices on a network.
Example: A device’s MAC address looks like 00:1A:2B:3C:4D:5E.

Error Detection and Correction
Detects and corrects errors in transmitted frames.
Example: Cyclic Redundancy Check (CRC) is used in Ethernet to verify data integrity.

Flow Control
Prevents a fast sender from overwhelming a slow receiver.
Example: Stop-and-Wait Protocol ensures data is received before sending more.

Media Access Control (MAC)
Determines how devices share and access the physical network medium.
Example: CSMA/CD (Carrier Sense Multiple Access with Collision Detection) in Ethernet networks.

Sub-Layers of the Data Link Layer
Logical Link Control (LLC) Sub-Layer
Handles error checking and flow control.
Allows multiple network protocols (e.g., IPv4, IPv6) to operate over the same physical network.
Media Access Control (MAC) Sub-Layer
Manages access to the physical transmission medium.
Uses MAC addresses for device identification and communication.

Devices Operating at the Data Link Layer
Switches – Forward frames based on MAC addresses.
Bridges – Connect two LANs and filter traffic.
Network Interface Cards (NICs) – Provide hardware-based MAC addressing.

Data Link Layer in Cybersecurity
MAC Spoofing – Attackers change their MAC address to bypass network controls.
Man-in-the-Middle (MITM) Attacks – Intercepting frames in a switched network.
VLAN Hopping – Exploiting VLAN misconfigurations to access restricted networks.
Mitigation Measures – MAC filtering, port security, and enabling 802.1X authentication.
