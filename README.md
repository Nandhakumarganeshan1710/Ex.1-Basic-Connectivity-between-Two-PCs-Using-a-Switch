## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 15/10/2026


# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="958" height="536" alt="image" src="https://github.com/user-attachments/assets/f9498920-aa42-4667-9cb8-9c954cd38934" />


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

________________________________________
# Output (Screenshots / Ping Results)
CONFIGURATION

<img width="959" height="539" alt="Screenshot 2026-10-15 172128" src="https://github.com/user-attachments/assets/32fced2e-c6ef-4bdc-8d87-3785f5ef8cee" />
<img width="736" height="489" alt="Screenshot 2026-10-15 173735" src="https://github.com/user-attachments/assets/2a452a74-c8c9-4a79-8f1c-df962ac8b9ef" />

PING
<img width="946" height="531" alt="Screenshot 2026-10-15 172428" src="https://github.com/user-attachments/assets/93e22478-b9cb-45e0-870a-7ffb5f9455c0" />

Insert screenshots showing ping success, configuration, or simulation results.
________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
