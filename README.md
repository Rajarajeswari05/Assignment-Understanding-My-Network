# Assignment-Understanding-My-Network
Day 02 Assignment – Understanding My Network | Jayvik Labs


---

# THEORY

## 1. What is a computer network?

A computer network is a group of connected devices that communicate with each other and share resources such as files, applications, internet access, and other services.

## 2. What is the difference between a client and a server?

A client is a device or application that requests a service or resource. A server provides that service or resource to the client. For example, when I open a website, my computer acts as the client and the web server provides the requested webpage.

## 3. What is a LAN?

LAN stands for **Local Area Network**. It connects devices within a limited geographical area such as a home, office, school, or laboratory.

## 4. What is a WAN?

WAN stands for **Wide Area Network**. It connects networks over large geographical areas. The Internet is a common example of a WAN.

## 5. What is the purpose of a switch?

A switch connects multiple devices within a LAN and forwards network traffic to the appropriate device. It mainly uses MAC addresses to identify devices on the local network.

## 6. What is the purpose of a router?

A router connects different networks and forwards data between them. For example, a home router connects devices on a local network to the Internet.

## 7. What is a firewall?

A firewall is a security system that monitors and controls incoming and outgoing network traffic based on predefined security rules. It helps prevent unauthorized network access.

## 8. What is an IP address?

An IP address is a logical address assigned to a device on a network. It allows devices to identify each other and communicate over the network.

## 9. What is a MAC address?

A MAC address is a unique hardware-level address associated with a network interface. It is mainly used to identify devices when communicating within a local network.

## 10. What is a default gateway?

A default gateway is normally the IP address of a router that a device uses to communicate with destinations outside its local network.

## 11. What is DNS?

DNS stands for **Domain Name System**. It translates domain names such as `google.com` into IP addresses so computers can locate and communicate with the destination server.

## 12. Why is networking knowledge important for cybersecurity?

Networking knowledge is important for cybersecurity because many attacks and security incidents occur through networks. Understanding IP addresses, ports, protocols, DNS, routing, and network traffic helps security professionals identify suspicious activity, troubleshoot problems, investigate incidents, and protect systems from attacks.

---

# YOUR NETWORK INFORMATION

> **Privacy Note:** Sensitive network identifiers have been masked in this public GitHub repository. The complete network information is included in the PDF submitted to Jayvik Labs.

## 13. Private IPv4 Address

**Private IPv4 Address:** `10.10.xxx.xxx`

## 14. Default Gateway

**Default Gateway:** `10.10.xxx.x`

## 15. DNS Server

**DNS Server:** `8.8.8.8 / xxx.x.x.x`

## IPv6 Address

**IPv6 Address:** Not publicly disclosed for privacy reasons.

---

# SCREENSHOTS AND PRACTICAL WORK

## 1. IP Configuration – ipconfig

I used the following Windows command to view my system's network configuration:

```cmd
ipconfig /all

<img width="1036" height="883" alt="image" src="https://github.com/user-attachments/assets/5ec3e821-dedc-41af-8cdf-65de2ed58396" />
<img width="1067" height="740" alt="image" src="https://github.com/user-attachments/assets/2ae90dff-a77d-4c9a-ab47-2513e0d23977" />
<img width="1136" height="993" alt="image" src="https://github.com/user-attachments/assets/9d20038c-a35e-4478-8fb5-8d49b6ed9c2b" />




2. Connectivity Test – ping

I used the following Windows command to test connectivity between my computer and Google:

```cmd
ping google.com

The ping command sends ICMP Echo Request packets to the destination and waits for responses.

The test was successful, with 4 packets sent, 4 packets received, and 0% packet loss. The average response time was approximately 22 ms, which indicates that the destination was reachable from my computer at the time of testing.

<img width="790" height="317" alt="image" src="https://github.com/user-attachments/assets/34b7f9a8-698b-44ef-b2a2-09e3477516f0" />


3. Route/Path Test – tracert

I used the following Windows command to identify the network path between my computer and Google:

tracert google.com

The tracert command displays the intermediate network hops taken by packets while travelling from my computer to the destination.

The test displayed multiple network hops between my computer and Google's server. Some hops showed "Request timed out." This can happen when a router or network device does not respond to traceroute requests, and it does not necessarily mean that there is a connectivity problem.

For the public GitHub version, the first-hop private gateway has been masked for privacy.

<img width="1030" height="692" alt="image" src="https://github.com/user-attachments/assets/7c3f2265-f87c-4884-82f7-e4b4830cd6bb" />


Key Learning

Through this practical exercise, I gained a better understanding of how computer networks work and how Windows commands can be used to check network configuration and connectivity.

The main concepts I practiced were:

IP Address – Identifies a device logically on a network.
MAC Address – Identifies a network interface at the hardware/data-link level.
Default Gateway – Provides a path to other networks.
DNS – Translates domain names into IP addresses.
Switch – Connects multiple devices within a LAN.
Router – Connects different networks and forwards packets between them.
Firewall – Controls network traffic according to security rules.
Ping – Tests network reachability and connectivity.
Tracert – Shows the network path and intermediate hops.

These concepts are important in cybersecurity because understanding normal network communication helps security professionals identify unusual traffic, troubleshoot network problems, and investigate potential security incidents.

Conclusion

This assignment gave me practical exposure to basic computer networking. I learned about LAN, WAN, switches, routers, firewalls, IP addresses, MAC addresses, default gateways, and DNS.

I also practiced ipconfig, ping, and tracert commands on my own computer to understand network configuration, connectivity, and routing.

This practical knowledge provides a strong foundation for cybersecurity because security professionals need to understand how devices communicate, how network traffic travels, and how abnormal network activity can be identified during security monitoring and incident investigation.







