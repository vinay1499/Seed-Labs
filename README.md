# CPSC-8570 Network Technology Security (Seed-Labs)

This repository contains my work on SEED Labs completed during the Network Technologies Security course taught by Dr. Long Cheng.
The labs provided hands-on experience with various network security concepts, attacks, and defense mechanisms.


| S.No | Lab |
| --- | --- |
| 1. Lab-1 | TCP Attacks Lab |
| 2. Lab-2 | ICMP Redirect Attack Lab |
| 3. Lab-3| Local DNS Attack Lab |
| 4. Lab-4| ARP Cache Attack Lab  |
| 5. Lab-5| Firewall Exploration Lab  |


## Lab 1: TCP Attacks Lab
### Description:
In this lab, I explored various TCP attack techniques to understand vulnerabilities within the TCP protocol. 
The exercises included:

- **TCP SYN Flooding Attack:** Overwhelming a server with SYN requests to exhaust its resources.
- **TCP RST Attack:** Sending forged TCP reset packets to terminate existing connections.
- **TCP Session Hijacking:** Capturing and injecting packets into an active TCP session.

## Lab 2: ICMP Redirect Attack Lab
### Description:
This lab focused on ICMP Redirect attacks, demonstrating how attackers can manipulate a victim's routing table to redirect network traffic through a malicious node.

- **ICMP Redirect Messages:** Crafting and sending ICMP redirect packets.
- **Man-in-the-Middle (MitM):** Intercepting and monitoring redirected traffic.
- **Defense Mechanisms:** Implementing strategies to detect and prevent ICMP redirect attacks.


## Lab 3: Local DNS Attack Lab
### Description:
In the Local DNS Attack lab, I performed attacks to understand how DNS vulnerabilities can be exploited:

- **DNS Spoofing:** Redirecting a victim to a fraudulent website by poisoning the DNS cache.
- **DNS ID Hacking:** Predicting DNS transaction IDs to inject false DNS responses.
- **Mitigation Techniques:** Configuring DNS servers and clients to resist spoofing attempts.


## Lab 4: ARP Cache Attack Lab
### Description:
This lab delved into ARP cache poisoning attacks to intercept and manipulate network traffic:

- **ARP Spoofing:** Sending fake ARP messages to associate the attacker's MAC address with the IP address of another host.
- **MitM Attacks:** Eavesdropping or altering data packets between two parties.
- **Security Measures:** Implementing static ARP entries and using detection tools.


## Lab 5: Firewall Exploration Lab
### Description:
The Firewall Exploration lab provided insights into firewall configurations and their impact on network security:

- **Firewall Rules:** Understanding and setting up inbound and outbound rules.
- **Traffic Filtering:** Testing how different protocols and ports are managed.
- **Bypassing Techniques:** Exploring methods attackers might use to circumvent firewall protections.


