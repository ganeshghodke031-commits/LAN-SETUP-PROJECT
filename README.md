🖥️ Local Area Network (LAN) Setup and Configuration
📌 Project Overview

This project demonstrates the setup and configuration of a small Local Area Network (LAN) using Cisco Packet Tracer.

The project involves connecting multiple systems, configuring network settings, and testing communication between devices. File sharing and printer sharing concepts are explained theoretically as they require a real operating system environment.

🎯 Objectives
To create a small LAN network

To connect multiple computers using a switch

To configure IP addresses and subnet masks

To test connectivity using the ping command

To understand file and printer sharing concepts

🛠️ Tools and Technologies Used

Cisco Packet Tracer

2960 Switch

PCs (End Devices)

Copper Straight-Through Ethernet Cable

TCP/IP Protocol

🖧 Network Topology
        PC0        PC1
         |           |
         |           |
       --------Switch--------
⚙️ Implementation Steps
1️⃣ Adding Devices

Added 2 PCs

Added 1 Switch (2960)

2️⃣ Connecting Devices

Connected each PC to the switch using Copper Straight-Through cables

3️⃣ IP Address Configuration
Device	IP Address	Subnet Mask
PC0	192.168.1.1	255.255.255.0
PC1	192.168.1.2	255.255.255.0
All devices were configured in the same network range.

4️⃣ Connectivity Testing

Ping command was used to verify communication:

ping 192.168.1.2

Successful replies confirmed proper network setup.

📂 File Sharing (Theory)

File sharing allows computers in a LAN to share files and folders.

In a real Windows environment:

Network discovery is enabled

File sharing is turned on

A folder is shared with permissions

Other devices access it using the IP address

Example:

\\192.168.1.1

⚠ Note: File sharing is not supported in Cisco Packet Tracer because it is a network simulation tool.

🖨️ Printer Sharing (Theory)

Printer sharing allows multiple computers to use a single printer over a network.

In a real environment:

Printer is connected to one PC

Printer sharing is enabled

Other systems connect through the network

⚠ Note: Printer sharing cannot be implemented in Cisco Packet Tracer.

📚 Concepts Learned

LAN Architecture

IP Addressing

Subnet Mask

Switch Functionality

Packet Transmission

Network Troubleshooting using ping

✅ Result

The LAN was successfully created and configured in Cisco Packet Tracer. All devices were able to communicate with each other using the ping command.

📌 Conclusion

This project provided practical knowledge of LAN setup and configuration. It helped in understanding basic networking concepts and communication within a local network environment.

PC3	192.168.1.4	255.255.255.0

All devices were configured in the same network range.
