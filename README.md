# Smart Hotel Network Design with Cisco Packet Tracer
This project simulates an end-to-end complex network infrastructure required by a modern hotel enterprise using Cisco Packet Tracer. The project practically demonstrates core networking principles, including network hierarchy, IoT integration, and wide area network (WAN) connectivity.

## Technical Architecture and Features
1. Network Segmentation (VLAN Configuration)
To optimize network performance and security, the system is divided into logical layers:

VLAN 10 (Guest Network): An isolated layer dedicated to providing internet access for hotel guests.

VLAN 30 (Staff Network): Internal communication segment for reception, kitchen, and housekeeping departments.

VLAN 40 (Parking/IoT Network): A specialized segment that isolates sensor and smart display traffic from the main network.

2. Server and Management Services
Centralized servers host key services to maximize system efficiency:

DHCP: Automated IP address assignment for all laptops and IoT devices.

DNS: Domain name resolution for the hotel's custom web address (e.g., grandmarmaraotel.com).

HTTP: A custom-designed web interface hosting internal hotel information and services.

3. IoT and Hardware Automation
Physical processes within the hotel are fully digitized:

Smart Parking System: Real-time vehicle tracking using Microcontroller Units (MCU) and motion sensors, paired with an LCD screen providing instant occupancy updates.

Digital Service Notification: Instant request delivery from smart buttons in rooms directly to staff monitoring screens (IoT Monitor).

4. Security (ACL & WAN)
WAN Simulation: Simulation of the hotel network’s connection to the outside world (External/Home network).

Access Control Lists (ACL): Firewall rules configured on the Core Switch to block unauthorized traffic and prevent external breaches into the Staff and Parking networks.

Conclusion: This simulation serves as an integrated capstone project, demonstrating how VLAN management, IP routing protocols, service configurations, and hardware programming (Python/MCU) seamlessly converge within a unified network architecture.
