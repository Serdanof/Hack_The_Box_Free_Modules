## Module: Introduction To Academy (Tier 0)
**Questions:** What is the name of the first section of this module? If you are using a translation solution while studying, please disable it temporarily to enter the first section's name in English.

**Ans:** Introduction

**Questions:** Based on the commands you executed, what is likely to be the operating system flavor of this instance? (case-sensitive)

**Ans:** parrot

**Questions:** What is the proof text displayed in the Target website you browsed?

**How to find:**

click on target to see the ipaddress with port number
then copy that and put that on a web browser search bar as http://83.136.255.150:57021
you will see "Welcome to HTB Academy! Proof: t4rg3ts"
**Ans:** t4rgts

## Module: INTRODUCTION TO NETWORKING

**Notes:**
- Fully Qualified Domain Name (FQDN)
- Uniform Resource Locator (URL)
**Common Terminology:**

| Network Type                    | Definition                                  |
|--------------------------------|---------------------------------------------|
| Wide Area Network (WAN)        | Internet                                    |
| Local Area Network (LAN)       | Internal Networks (Ex: Home or Office)      |
| Wireless Local Area Network (WLAN) | Internal Networks accessible over Wi-Fi  |
| Virtual Private Network (VPN)  | Connects multiple network sites to one LAN |

**Book Terms:**

| Network Type                           | Definition                                  |
|---------------------------------------|---------------------------------------------|
| Global Area Network (GAN)             | Global network (the Internet)               |
| Metropolitan Area Network (MAN)       | Regional network (multiple LANs)            |
| Wireless Personal Area Network (WPAN) | Personal network (Bluetooth)                |



| Network Topology  | Description                                           |
|-------------------|-------------------------------------------------------|
| Point-to-Point    | Direct connection between two devices                |
| Bus               | All devices are connected to a single backbone       |
| Star              | All devices are connected to a central hub or switch |
| Ring              | Each device is connected to exactly two other devices, forming a ring |
| Mesh              | Every device is connected to every other device      |
| Tree              | Hierarchical structure with a root node and branches |
| Hybrid            | Combination of two or more different topologies      |
| Daisy Chain       | Devices are connected in series, like links in a chain |

## OSI model:

| Layer                  | Description                                             |
|------------------------|---------------------------------------------------------|
| **Layer 7: Application** | Provides interfaces for applications to access network services. Examples include HTTP, FTP, SMTP. |
| **Layer 6: Presentation** | Translates data between the application layer and the network format. Handles encryption, compression, and data formatting. |
| **Layer 5: Session** | Establishes, manages, and terminates connections between applications. Manages sessions and dialogues. |
| **Layer 4: Transport** | Provides end-to-end communication between hosts. Ensures data reliability, flow control, and error correction. Examples include TCP and UDP. |
| **Layer 3: Network** | Routes data packets between networks. Handles logical addressing and routing. Examples include IP and ICMP. |
| **Layer 2: Data Link** | Transmits data frames over the physical network. Handles framing, error detection, and MAC addressing. Examples include Ethernet and Wi-Fi. |
| **Layer 1: Physical** | Transmits raw data bits over the physical medium. Specifies electrical, mechanical, and procedural standards for transmission. Examples include cables, hubs, and repeaters. |

## TCP/IP model:

| Layer            | Description                                       |
|------------------|---------------------------------------------------|
| **Application**  | Provides network services directly to user applications. Examples include HTTP, FTP, SMTP. |
| **Transport**    | Provides end-to-end communication between hosts. Ensures data reliability, flow control, and error correction. Examples include TCP and UDP. |
| **Internet**     | Routes data packets between networks. Handles logical addressing and routing. Examples include IP and ICMP. |
| **Link**         | Transmits data frames over the physical network. Handles framing, error detection, and MAC addressing. Examples include Ethernet and Wi-Fi. |

## IPv4 Structure


| Class | Network Address | First Address | Last Address | Subnetmask     | CIDR | Subnets     | IPs               |
|-------|-----------------|---------------|--------------|----------------|------|-------------|-------------------|
| A     | 1.0.0.0         | 1.0.0.1       | 127.255.255.255 | 255.0.0.0   | /8   | 127         | 16,777,214 + 2    |
| B     | 128.0.0.0       | 128.0.0.1     | 191.255.255.255 | 255.255.0.0 | /16  | 16,384      | 65,534 + 2        |
| C     | 192.0.0.0       | 192.0.0.1     | 223.255.255.255 | 255.255.255.0 | /24 | 2,097,152   | 254 + 2           |
| D     | 224.0.0.0       | 224.0.0.1     | 239.255.255.255 | Multicast    | Multicast | Multicast | Multicast         |
| E     | 240.0.0.0       | 240.0.0.1     | 255.255.255.255 | Reserved     | Reserved  | Reserved  | Reserved          |

**Questions:** Submit the decimal representation of the subnet mask from the following CIDR: 10.200.20.0/27

**Ans:** 255.255.255.224

**Questions:** Submit the broadcast address of the following CIDR: 10.200.20.0/27

**Ans:** 10.200.20.31

**Questions:** Split the network 10.200.20.0/27 into 4 subnets and submit the network address of the 3rd subnet as the answer.

**Ans:** 10.200.20.16

**Questions:** Split the network 10.200.20.0/27 into 4 subnets and submit the broadcast address of the 2nd subnet as the answer.

**Ans:** 10.200.20.15

## Network Key Terminology


| Protocol                                           | Acronym | Description                                                                                                                       |
|----------------------------------------------------|---------|-----------------------------------------------------------------------------------------------------------------------------------|
| Wired Equivalent Privacy                           | WEP     | WEP is a type of security protocol that was commonly used to secure wireless networks.                                             |
| Secure Shell                                      | SSH     | A secure network protocol used to log into and execute commands on a remote system.                                                |
| File Transfer Protocol                            | FTP     | A network protocol used to transfer files from one system to another.                                                              |
| Simple Mail Transfer Protocol                     | SMTP    | A protocol used to send and receive emails.                                                                                       |
| Hypertext Transfer Protocol                       | HTTP    | A client-server protocol used to send and receive data over the internet.                                                          |
| Server Message Block                              | SMB     | A protocol used to share files, printers, and other resources in a network.                                                        |
| Network File System                               | NFS     | A protocol used to access files over a network.                                                                                   |
| Simple Network Management Protocol                | SNMP    | A protocol used to manage network devices.                                                                                        |
| Wi-Fi Protected Access                            | WPA     | WPA is a wireless security protocol that uses a password to protect wireless networks from unauthorized access.                  |
| Temporal Key Integrity Protocol                   | TKIP    | TKIP is also a security protocol used in wireless networks but less secure.                                                        |
| Network Time Protocol                             | NTP     | It is used to synchronize the timing of computers on a network.                                                                    |
| Virtual Local Area Network                        | VLAN    | It is a way to segment a network into multiple logical networks.                                                                   |
| VLAN Trunking Protocol                            | VTP     | VTP is a Layer 2 protocol that is used to establish and maintain a virtual LAN (VLAN) spanning multiple switches.                  |
| Routing Information Protocol                      | RIP     | RIP is a distance-vector routing protocol used in local area networks (LANs) and wide area networks (WANs).                      |
| Open Shortest Path First                          | OSPF    | It is an interior gateway protocol (IGP) for routing traffic within a single Autonomous System (AS) in an Internet Protocol (IP) network. |
| Interior Gateway Routing Protocol                 | IGRP    | IGRP is a Cisco proprietary interior gateway protocol designed for routing within autonomous systems.                              |
| Enhanced Interior Gateway Routing Protocol         | EIGRP   | It is an advanced distance-vector routing protocol that is used to route IP traffic within a network.                              |
| Pretty Good Privacy                               | PGP     | PGP is an encryption program that is used to secure emails, files, and other types of data.                                       |
| Network News Transfer Protocol                    | NNTP    | NNTP is a protocol used for distributing and retrieving messages in newsgroups across the internet.                               |
| Cisco Discovery Protocol                          | CDP     | It is a proprietary protocol developed by Cisco Systems that allows network administrators to discover and manage Cisco devices connected to the network. |
| Hot Standby Router Protocol                       | HSRP    | HSRP is a protocol used in Cisco routers to provide redundancy in the event of a router or other network device failure.           |
| Virtual Router Redundancy Protocol                | VRRP    | It is a protocol used to provide automatic assignment of available Internet Protocol (IP) routers to participating hosts.          |
| Spanning Tree Protocol                            | STP     | STP is a network protocol used to ensure a loop-free topology in Layer 2 Ethernet networks.                                        |
| Terminal Access Controller Access-Control System  | TACACS  | TACACS is a protocol that provides centralized authentication, authorization, and accounting for network access.                 |
| Session Initiation Protocol                       | SIP     | It is a signaling protocol used for establishing and terminating real-time voice, video and multimedia sessions over an IP network.  |
| Voice Over IP                                     | VOIP    | VOIP is a technology that allows for telephone calls to be made over the internet.                                                  |
| Extensible Authentication Protocol                 | EAP     | EAP is a framework for authentication that supports multiple authentication methods, such as passwords, digital certificates, one-time passwords, and public-key authentication. |
| Lightweight Extensible Authentication Protocol    | LEAP    | LEAP is a proprietary wireless authentication protocol developed by Cisco Systems. It is based on the Extensible Authentication Protocol (EAP) used in the Point-to-Point Protocol (PPP). |
| Protected Extensible Authentication Protocol      | PEAP    | PEAP is a security protocol that provides an encrypted tunnel for wireless networks and other types of networks.                  |
| Systems Management Server                         | SMS     | SMS is a systems management solution that helps organizations manage their networks, systems, and mobile devices.                  |
| Microsoft Baseline Security Analyzer              | MBSA    | It is a free security tool from Microsoft that is used to detect potential security vulnerabilities in Windows computers, networks, and systems. |
| Supervisory Control and Data Acquisition          | SCADA   | It is a type of industrial control system that is used to monitor and control industrial processes, such as those in manufacturing, power generation, and water and waste treatment. |
| Virtual Private Network                           | VPN     | VPN is a technology that allows users to create a secure, encrypted connection to another network over the internet.                |
| Internet Protocol Security                        | IPsec   | IPsec is a protocol used to provide secure, encrypted communication over a network. It is commonly used in VPNs, or Virtual Private Networks, to create a secure tunnel between two devices. |
| Point-to-Point Tunneling Protocol                 | PPTP    | It is a protocol used to create a secure, encrypted tunnel for remote access.                                                        |
| Network Address Translation                       | NAT     | NAT is a technology that allows multiple devices on a private network to connect to the internet using a single public IP address. NAT works by translating the private IP addresses of devices on the network into a single public IP address, which is then used to connect to the internet. |
| Carriage Return Line Feed                         | CRLF    | Combines two control characters to indicate the end of a line and a start of a new one for certain text file formats.             |
| Asynchronous JavaScript and XML                   | AJAX    | Web development technique that allows creating dynamic

## Transmission Control Protocol


| Protocol                                              | Acronym       | Port        | Description                                                                                         |
|-------------------------------------------------------|---------------|-------------|-----------------------------------------------------------------------------------------------------|
| Telnet                                                | Telnet        | 23          | Remote login service                                                                                |
| Secure Shell                                          | SSH           | 22          | Secure remote login service                                                                         |
| Simple Network Management Protocol                    | SNMP          | 161-162     | Manage network devices                                                                             |
| Hyper Text Transfer Protocol                          | HTTP          | 80          | Used to transfer webpages                                                                          |
| Hyper Text Transfer Protocol Secure                  | HTTPS         | 443         | Used to transfer secure webpages                                                                   |
| Domain Name System                                    | DNS           | 53          | Lookup domain names                                                                                |
| File Transfer Protocol                                | FTP           | 20-21       | Used to transfer files                                                                             |
| Trivial File Transfer Protocol                       | TFTP          | 69          | Used to transfer files                                                                             |
| Network Time Protocol                                 | NTP           | 123         | Synchronize computer clocks                                                                        |
| Simple Mail Transfer Protocol                        | SMTP          | 25          | Used for email transfer                                                                            |
| Post Office Protocol                                  | POP3          | 110         | Used to retrieve emails                                                                            |
| Internet Message Access Protocol                     | IMAP          | 143         | Used to access emails                                                                              |
| Server Message Block                                  | SMB           | 445         | Used to transfer files                                                                             |
| Network File System                                   | NFS           | 111, 2049   | Used to mount remote systems                                                                       |
| Bootstrap Protocol                                    | BOOTP         | 67, 68      | Used to bootstrap computers                                                                        |
| Kerberos                                              | Kerberos      | 88          | Used for authentication and authorization                                                          |
| Lightweight Directory Access Protocol                | LDAP          | 389         | Used for directory services                                                                        |
| Remote Authentication Dial-In User Service           | RADIUS        | 1812, 1813  | Used for authentication and authorization                                                          |
| Dynamic Host Configuration Protocol                  | DHCP          | 67, 68      | Used to configure IP addresses                                                                     |
| Remote Desktop Protocol                              | RDP           | 3389        | Used for remote desktop access                                                                     |
| Network News Transfer Protocol                       | NNTP          | 119         | Used to access newsgroups                                                                          |
| Remote Procedure Call                                | RPC           | 135, 137-139| Used to call remote procedures                                                                     |
| Identification Protocol                              | Ident         | 113         | Used to identify user processes                                                                    |
| Internet Control Message Protocol                    | ICMP          | 0-255       | Used to troubleshoot network issues                                                                |
| Internet Group Management Protocol                   | IGMP          | 0-255       | Used for multicasting                                                                              |
| Oracle DB (Default/Alternative) Listener             | oracle-tns    | 1521/1526   | The Oracle database default/alternative listener is a service that runs on the database host and receives requests from Oracle clients.                           |
| Ingres Lock                                          | ingreslock    | 1524        | Ingres database is commonly used for large commercial applications and as a backdoor that can execute commands remotely via RPC.                                      |
| Squid Web Proxy                                      | http-proxy    | 3128        | Squid web proxy is a caching and forwarding HTTP web proxy used to speed up a web server by caching repeated requests.                                              |
| Secure Copy Protocol                                 | SCP           | 22          | Securely copy files between systems                                                                |
| Session Initiation Protocol                          | SIP           | 5060        | Used for VoIP sessions                                                                             |
| Simple Object Access Protocol                        | SOAP          | 80, 443     | Used for web services                                                                              |
| Secure Socket Layer                                  | SSL           | 443         | Securely transfer files                                                                            |
| TCP Wrappers                                         | TCPW          | 113         | Used for access control                                                                            |
| Internet Security Association and Key Management Protocol | ISAKMP    | 500         | Used for VPN connections                                                                           |
| Microsoft SQL Server                                 | ms-sql-s      | 1433        | Used for client connections to the Microsoft SQL Server.                                            |
| Kerberized Internet Negotiation of Keys              | KINK          | 892         | Used for authentication and authorization                                                          |
| Open Shortest Path First                             | OSPF          | 89          | Used for routing                                                                                   |
| Point-to-Point Tunneling Protocol                    | PPTP          | 1723        | Is used to create VPNs                                                                             |
| Remote Execution                                     | REXEC         | 512         | This protocol is used to execute commands on remote computers and send the output of commands back to the local computer.                                          |
| Remote Login                                         | RLOGIN        | 513         | This protocol starts an interactive shell session on a remote computer.                                |
| X Window System                                      | X11           | 6000        | It is a computer software system and network protocol that provides a graphical user interface (GUI) for networked computers.                                       |
| Relational Database Management System                | DB2           | 50000       | RDBMS is designed to store, retrieve and manage data in a structured format for enterprise applications such as financial systems, customer relationship management (CRM) systems.  |

## User Datagram Protocol

| Protocol                                       | Acronym   | Port | Description                                                                                                    |
|-----------------------------------------------|-----------|------|----------------------------------------------------------------------------------------------------------------|
| Domain Name System                            | DNS       | 53   | It is a protocol to resolve domain names to IP addresses.                                                      |
| Trivial File Transfer Protocol                | TFTP      | 69   | It is used to transfer files between systems.                                                                 |
| Network Time Protocol                         | NTP       | 123  | It synchronizes computer clocks in a network.                                                                 |
| Simple Network Management Protocol            | SNMP      | 161  | It monitors and manages network devices remotely.                                                              |
| Routing Information Protocol                  | RIP       | 520  | It is used to exchange routing information between routers.                                                    |
| Internet Key Exchange                        | IKE       | 500  | Internet Key Exchange                                                                                          |
| Bootstrap Protocol                            | BOOTP     | 68   | It is used to bootstrap hosts in a network.                                                                    |
| Dynamic Host Configuration Protocol           | DHCP      | 67   | It is used to assign IP addresses to devices in a network dynamically.                                         |
| Telnet                                        | TELNET    | 23   | It is a text-based remote access communication protocol.                                                       |
| MySQL                                         | MySQL     | 3306 | It is an open-source database management system.                                                               |
| Terminal Server                               | TS        | 3389 | It is a remote access protocol used for Microsoft Windows Terminal Services by default.                         |
| NetBIOS Name                                  | netbios-ns| 137  | It is used in Windows operating systems to resolve NetBIOS names to IP addresses on a LAN.                      |
| Microsoft SQL Server                         | ms-sql-m  | 1434 | Used for the Microsoft SQL Server Browser service.                                                             |
| Universal Plug and Play                      | UPnP      | 1900 | It is a protocol for devices to discover each other on the network and communicate.                             |
| PostgreSQL                                   | PGSQL     | 5432 | It is an object-relational database management system.                                                          |
| Virtual Network Computing                    | VNC       | 5900 | It is a graphical desktop sharing system.                                                                      |
| X Window System                              | X11       | 6000-6063 | It is a computer software system and network protocol that provides GUI on Unix-like systems.               |
| Syslog                                       | SYSLOG    | 514  | It is a standard protocol to collect and store log messages on a computer system.                                |
| Internet Relay Chat                          | IRC       | 194  | It is a real-time Internet text messaging (chat) or synchronous communication protocol.                        |
| OpenPGP                                     | OpenPGP   | 11371 | It is a protocol for encrypting and signing data and communications.                                            |
| Internet Protocol Security                   | IPsec     | 500  | IPsec is also a protocol that provides secure, encrypted communication. It is commonly used in VPNs to create a secure tunnel between two devices. |
| X Display Manager Control Protocol           | XDMCP     | 177  | XDMCP is a network protocol that allows a user to remotely log in to a computer running the X11.               |

## Authentication Protocols


| Protocol      | Description                                                                                                                                                                                                                                                                                                                                                         |
|---------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Kerberos      | Key Distribution Center (KDC) based authentication protocol that uses tickets in domain environments.                                                                                                                                                                                                                                                             |
| SRP           | This is a password-based authentication protocol that uses cryptography to protect against eavesdropping and man-in-the-middle attacks.                                                                                                                                                                                                                            |
| SSL           | A cryptographic protocol used for secure communication over a computer network.                                                                                                                                                                                                                                                                                    |
| TLS           | TLS is a cryptographic protocol that provides communication security over the internet. It is the successor to SSL.                                                                                                                                                                                                                                                |
| OAuth         | An open standard for authorization that allows users to grant third-party access to their web resources without sharing their passwords.                                                                                                                                                                                                                            |
| OpenID        | OpenID is a decentralized authentication protocol that allows users to use a single identity to sign in to multiple websites.                                                                                                                                                                                                                                        |
| SAML          | Security Assertion Markup Language is an XML-based standard for securely exchanging authentication and authorization data between parties.                                                                                                                                                                                                                           |
| 2FA           | An authentication method that uses a combination of two different factors to verify a user's identity.                                                                                                                                                                                                                                                             |
| FIDO          | The Fast IDentity Online Alliance is a consortium of companies working to develop open standards for strong authentication.                                                                                                                                                                                                                                         |
| PKI           | PKI is a system for securely exchanging information based on the use of public and private keys for encryption and digital signatures.                                                                                                                                                                                                                              |
| SSO           | An authentication method that allows a user to use a single set of credentials to access multiple applications.                                                                                                                                                                                                                                                    |
| MFA           | MFA is an authentication method that uses multiple factors, such as something the user knows (a password), something the user has (a phone), or something the user is (biometric data), to verify their identity.                                                                                                                                               |
| PAP           | A simple authentication protocol that sends a user's password in clear text over the network.                                                                                                                                                                                                                                                                      |
| CHAP          | An authentication protocol that uses a three-way handshake to verify a user's identity.                                                                                                                                                                                                                                                                            |
| EAP           | A framework for supporting multiple authentication methods, allowing for the use of various technologies to verify a user's identity.                                                                                                                                                                                                                               |
| SSH           | This is a network protocol for secure communication between a client and a server. We can use it for remote command-line access and remote command execution, as well as for secure file transfer. SSH uses encryption to protect against eavesdropping and other attacks and can also be used for authentication.                                                                                                     |
| HTTPS         | This is a secure version of the HTTP protocol used for communication on the internet. HTTPS uses SSL/TLS to encrypt communication and provide authentication, ensuring that third parties cannot intercept and read the transmitted data. It is widely used for secure communication over the internet, particularly for web browsing.                                                                                        |
| LEAP          | LEAP is a wireless authentication protocol developed by Cisco. It uses EAP to provide mutual authentication between a wireless client and a server and uses the RC4 encryption algorithm to encrypt communication between the two. Unfortunately, LEAP is vulnerable to dictionary attacks and other security vulnerabilities and has been largely replaced by more secure protocols such as EAP-TLS and PEAP. |
| PEAP          | PEAP on the other hand is a secure tunneling protocol used for wireless and wired networks. It is based on EAP and uses TLS to encrypt communication between a client and a server. PEAP uses a server-side certificate to authenticate the server and can also be used to authenticate the client using various methods, such as passwords, certificates, or biometric data. PEAP is widely used in enterprise networks for secure authentication. |
