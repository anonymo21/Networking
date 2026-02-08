# Networking fundamentals 
## Basics Network Concepts
    * What is Networking?
    * LAN, MAN, WAN, PAN
    * Intranet VS Internet
    * Client-Server Model
    * Peer To Peer
    * Bandwidth, Latency, Throughput
    * MAC address vs IP address

## OSI Model
    Layer   Name            Hacker Focus
    7       Application     HTTP, FTP, SMTP, HTTPS, SSH attacks
    6       Presentation    Encoding, Encryption
    5       Session         Session Hijcking
    4       Transport       TCP/UDP, Port Scannong
    3       Network         IP, Routing, ICMP
    2       Data_Link       ARP Spoofing
    1       Physical        Cabble sniffing

    * Focus On which attack happens at which layer
    * Real world example of attack per layer

## TCP/IP Model
    *TCP/IP Layers
    * Difference between OSI vs TCP/IP 
    * How data flow in real life

# IP addressing and Routing
## IP addressing
    * IPv4 Structure
    * Public vs Private IP
    * Static vs Dynamic IP
    * Loopback(127.0.0.1)
    * APIPA(169.254.x.x)

## Subneting(Critical Skill)
    * CIDR notation (/24, /16, etc)
    * Subnet Calculation
    * Default gateway
    * Static Routing vd Dynamic Routing
    * Routing Table

# Core Protocol(Hacker's Toolkit)
## Transport Layer Protocol
    * TCP
        > Three Way Handshake
        > Flags (SYN, ACK, FIN, RST)
    * UDP
        > Connectionless behavior
    * Attack
        > SYN Flood
        > UDP Flood
        > Port Scanning
## Network Layer Protocol
    * IP
    * ICMP
        > Ping
        > Traceroute
    * ARP
        > ARP Request/Reply
    * Attack
        > ICMP Tunneling
        > ARP Poisoning
## Application Layer Protocol
    * HTTP/HTTPS
    * FTP
    * SMTP/ POP3/ IMAP
    * DNS
    * SSH
    * Telnet
    * SNMP
    ### For Each Protocol
    * Port Number
    * Working
    * Common Misconfiguration
    * Common Attacks

# Switching, Firewall & NAT
## Switching Concepts
    * Switch vs Hub
    * MAC Table
    * VLAN
    * Trunking
    * ATtack
        > VLAN Hopping
        > MAC Flooding
## Firewall
    * Packet Filtering Firewall
    * Stateful Firewall
    * Application Firewall
    * WAF
    * How Firewall blocks traffic
    * How attack bypass firewall
## NAT (Network Address Translation)
    * SNAT
    * DNAT
    * PAT
# Wireless Networking(WiFi Hacking Base)
## Wireless Basics
    * 802.11 standards
    * 2.4 GHz vs 5GHz
    * Channel & Interfaces
## Wireless Security
    * WEP (Broken)
    * WPA/WPA2/WPA3
    * PSK vs Enterprise
    * Attack
        > Handshake Capture
        > Deauthentication attack
        > Evil Twin

# Practile Networking
## Linux Networking Command
    * ifconfig / IP a
    * ip route
    * arp -a
    * netstate
    * ss
    * traceroute
    * tcpdump
## Packet Analysis
    * Tools
        > Wireshark
        > tcpdump
    * Learn
        > Capture Packets
        > Analyze TCP handshake
        > Find credentials in traffic
        > Detect suspicious packets

# Networking Attack & Defense
## Network Attacks
    * MITM attack
    * ARP Spoofing
    * DNS Spoofing
    * DHCP Starvation
    * Packet Sniffing
## Defense Concepts
    * IDS / IPS
    * SIEM basics
    * Network Monitoring
    * Logs Analysis

# Real-World Ethical Hacking View
## How Hackers see a network
    * Network Mapping
    * Attack surface indenification
    * Internal vs External Network
    * Lateral Movement
## Practice Plateform
    * TryHackMe
    * Hack The Box
    * OverTheWire
    * VulnHub

# Final Advice
### Don't Just Read- Also Do Practical

### Thanks for reading
