## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 09-08-2025		

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

Insert the network topology from Packet Tracer (Screenshot or drawing)

________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>
arduino<br>
CopyEdit<br>
Router> enable<br>
Router# configure terminal<br>
Router(config)# interface FastEthernet0/0<br>
Router(config-if)# ip address 192.168.1.1 255.255.255.0<br>
Router(config-if)# no shutdown<br>
________________________________________
# Output (Screenshots / Ping Results)

<img width="1913" height="1019" alt="Screenshot 2025-08-09 134757" src="https://github.com/user-attachments/assets/47eef176-afff-4c02-99c1-14737b22658b" />

<img width="843" height="656" alt="Screenshot 2025-08-09 134819" src="https://github.com/user-attachments/assets/2dc36991-5d18-4081-89b7-ccc819d8de01" />


________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
