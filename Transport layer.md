Transport Layer (Layer 4) of the OSI Model
The Transport Layer is the fourth layer of the OSI model and is responsible for ensuring reliable and efficient data transfer between devices.
It provides end-to-end communication, error handling, and flow control to guarantee that data is delivered completely, correctly, and in the right order.

Functions 

Segmentation and Reassembly
Divides large data into smaller segments for transmission.
Reassembles segments in the correct order at the receiver’s end.

Flow Control
Regulates data flow to prevent overwhelming a slow receiver.
Example: If a sender transmits data too fast, flow control slows it down.

Error Detection and Correction
Ensures data integrity by checking for transmission errors.
Example: Checksums and Acknowledgments (ACK) in TCP.

Connection Control
Supports Connection-Oriented (TCP) and Connectionless (UDP) communication.
TCP ensures reliable, ordered delivery, while UDP is faster but less reliable.

Multiplexing
Enables multiple applications to communicate simultaneously using port numbers.
Example: A web browser (HTTP - Port 80) and an email client (SMTP - Port 25) can work together on the same device.

Ports and the Transport Layer
The Transport Layer uses port numbers to distinguish between different applications. Some well-known ports include
Port 80 – HTTP (Web browsing)
Port 443 – HTTPS (Secure web browsing)
Port 25 – SMTP (Sending emails)
Port 53 – DNS (Domain Name System)

Transport Layer in Cybersecurity
Port Scanning Attacks – Attackers use tools like Nmap to find open ports and exploit vulnerabilities.
DDoS Attacks – Overloading a system with massive UDP or TCP traffic to disrupt services.
TCP SYN Flood – A type of DoS attack that exploits TCP’s handshake process.
Mitigation Measures – Firewalls, intrusion detection systems (IDS), and rate-limiting prevent transport-layer attacks.
