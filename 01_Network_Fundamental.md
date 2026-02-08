# Basic Network Concepts
## What is Networking?
Network is the process of connecting two or more devices(like computer, mobile, server, printers) so they can communicate and share data and resources with each other.

## What is LAN, MAN, WAN, PAN
### LAN (Local Area Network)
LAN is stands for Local Area Network. LAN is a type of computer network that connect devices within in a small geographical area as a home, office, school, or laboratory.

**Key Points of LAN**
- Covers a limited area
- Provides high speed communication
- Low cost and easy to manage
- Usually privately owned
- Uses Ethernet cables or WiFi
### MAN (Metropolitan Area Network)
Man is a type of computer network that connects multiple LANs within a city or a large metropolitan area.

**Key Points of MAN**
- Covers a large area than LAN but smaller than WAN
- Usually spans a city or large campus
- Provide high speed data communication
- Often managed by ISPs, goverment, or large organization
### WAN (Wide Area Network)
WAN is a type of computer network that connects multiple LANs or MANs over a very large geographical area such as countries or continents.

**Kay Points of WAN**
- Covers a very large area -> Connects network over long distances
- Uses fiber optics, satellites, leased lines
- Generally slower than NAN (but improving with modern tech)
- Costly infractructure
### PAN (Personal Area Network)
PAN is a type of computer network used to connect personal devices within a very small range, usually around one person. Used device (like Bluetooth, USB, NFC).

## Intranet vs Internet
### Internet
The Internet is a global public network that connects million of computers, servers, and network worldwide. It is open to anyone.

**Key Features**
- Public accessible
- Connects users worldwide
- Uses TCP/IP protocol

**Common Internet Services**
- Websites(Google, Wikipedia)
- Email(Gmail, Outlook)
- Cloud services
- Streaming
- Social Media

**Security Lavel**
- Lower Security
- Needs Protection: firewall, antivirus, VPN, HTTPS
### Intranet
An Inranet is a private network used inside an organization(Company, College, Hospital) Only authorized user can access it.

**Key Features**
- Private and restricted
- Used within an organization
- Uses same technologies an internet (HTTP, TCP/IP)
- Owned by single organization

**Common Intranet Usses**
- Internal documents
- Employee portals
- Internal database
- Attandance system
- Internel announcements

**Security Lavel**
- Access controll by:
- Username/Password
- IP restriction
- Firewall
- VPN

## Client-Server Model
Client server model is a network architecture where a client request services or data. A server provides services or data. 
- Your browser(client) send a request to the web server.
- The server process the request.
- The server sends back the webpage to your browser.
this request-response process is called the client-server model.
### Feature of client-Server Model
- Centralized control of data and services.
- Easy to manage security and updates.
- Many clients can connect to one server.
- Used in websites, online games, email, banking apps, etc.

## Peer-To-Peer
The peer-to-peer model is a network where all computers are equal. Each computer can act as both a client and a server. There is no central server controlling everything.
### Features of Peer-To-Peer
- No central server needed
- Easy to setup and low cost
- Each computer share its own resources
- If one computer stops, the whole network usually still works

## Bandwidth, Latency, Throughput
<b>Bandwidth</b> : Bandwidth is the maximum amount of data that can be transmitted over a network per second.
- bits per second(bps)
- kbps
- mbps
- gbps

<b>Latency</b> : Latency is the time delay taken for data to travel from source to destination.
- Low latency = faster response

<b>Throughput</b> : Throughput is the actual amount of data successfully transmited per second in real conditions.
- Throughput = Real data transfer speed

## MAC Address vs IP Address
<b>MAC Address</b> : MAC address stands for Media Access Control address.A MAC address is a unique physical(hardware) address assigned to a network device's network interface card(NIC) by the manufacturer.
- Works at data link layer(Layer 2) of the OSI Model
- Permanent and usually cannot changed
- Used for communication inside a local network(LAN)
- Written in hexadecimal format
- MAC address = Physical identity of device

<b>IP Address</b> : IP address stands for Internet Protocol. An IP address is a logical address assigned to a device so it can communicate over a network or the Internet.
- Works at Network Layer (Layer 3)
- Can change(dynamic IP) or stay fixed(static IP)
- Used for communication between different networks
- Two main versions: IPv4 and IPv6 
