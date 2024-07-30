# ARP-Spoofing

This lab demonstrates how to perform an ARP Spoofing attack, also referred to as ARP Poisoning, Man-in-the-Middle, or On-path attack, on a Local Area Network using the arpspoof tool in Kali Linux. This lab was conducted in a segmented LAN environment to demonstrate the process of performing active reconnaissance with Nmap to enumerate operating system details from the host and to carry out an ARP spoofing attack on the target system. Once the ARP spoofing attack is initiated, further enumeration is performed using Wireshark.


## Active Reconnaissance on the Target using Nmap

![NmapOSDiscovery1.PNG](Images/NmapOSDiscovery1.PNG)

![NmapOSDiscovery2.PNG](Images/NmapOSDiscovery2.PNG)

![NmapOSDiscovery3.PNG](Images/NmapOSDiscovery3.PNG)


## Initiating the ARP Spoofing Attack with arpspoof

![arpspoof2.PNG](Images/arpspoof2.PNG)

![arpspoof3 arpspoof attack in action.PNG](Images/arpspoof3%20arpspoof%20attack%20in%20action.PNG)

![arpspoof4 arpspoof attack in action 2.PNG](Images/arpspoof4%20attack%20in%20action%202.PNG)

## Analyzing the Traffic with Wireshark

### Identifying DNS Server IP Address

![Wireshark DNS Server Extraction.PNG](Images/Wireshark%20DNS%20Server%20Extraction.PNG)

![Wireshark DNS Server Enumeration 5.PNG](Images/Wireshark%20DNS%20Server%20Enumeration%205.PNG)

![Wireshark DNS Server Enumeration 6.PNG](Images/Wireshark%20DNS%20Server%20Enumeration%206.PNG)

### NetBIOS and Other Information

![Wireshark Enumeration 0.PNG](Images/Wireshark%20Enumeration%200.PNG)

![Wireshark Enumeration 1.PNG](Images/Wireshark%20Enumeration%201.PNG)

![WSEnum1.PNG](Images/WSEnum1.PNG)

![WSEnum2.PNG](Images/WSEnum2.PNG)

![WSEnum3.PNG](Images/WSEnum3.PNG)

![WSEnum4.PNG](Images/WSEnum4.PNG)

### SSDP Enumeration

![WSEnum5.PNG](Images/WSEnum5.PNG)

![WSEnum6.PNG](Images/WSEnum6.PNG)

#### Other Host Information

![WSEnum7.PNG](Images/WSEnum7.PNG)
























