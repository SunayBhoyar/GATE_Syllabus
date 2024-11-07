# GATE Computer Networks Preparation Checklist

## 1. **Concept of Layering: OSI and TCP/IP Protocol Stacks**
- [ ] **OSI Model (Open Systems Interconnection)**
  - [ ] Overview of the OSI model: 7 layers
    - [ ] Layer 1: Physical Layer
    - [ ] Layer 2: Data Link Layer
    - [ ] Layer 3: Network Layer
    - [ ] Layer 4: Transport Layer
    - [ ] Layer 5: Session Layer
    - [ ] Layer 6: Presentation Layer
    - [ ] Layer 7: Application Layer
  - [ ] Functions of each OSI layer
  - [ ] Protocols associated with each OSI layer
  - [ ] Encapsulation and de-encapsulation process
- [ ] **TCP/IP Protocol Stack**
  - [ ] Overview of the TCP/IP model: 4 layers
    - [ ] Layer 1: Link Layer
    - [ ] Layer 2: Internet Layer
    - [ ] Layer 3: Transport Layer
    - [ ] Layer 4: Application Layer
  - [ ] Comparison of OSI and TCP/IP models
  - [ ] Protocols associated with each TCP/IP layer

## 2. **Basics of Packet, Circuit, and Virtual Circuit-Switching**
- [ ] **Circuit Switching**
  - [ ] Concept of dedicated communication path
  - [ ] Example: Telephone networks
  - [ ] Advantages and disadvantages of circuit switching
- [ ] **Packet Switching**
  - [ ] Concept of data divided into packets
  - [ ] Example: The Internet
  - [ ] Advantages and disadvantages of packet switching
  - [ ] Types of packet-switching techniques: Datagram and Virtual Circuit
- [ ] **Virtual Circuit Switching**
  - [ ] Virtual circuit establishment and teardown
  - [ ] Example: ATM (Asynchronous Transfer Mode)
  - [ ] Comparison with circuit and packet switching

## 3. **Data Link Layer**
- [ ] **Framing**
  - [ ] Purpose of framing in the data link layer
  - [ ] Types of framing methods: Character Count, Flag Bytes with Byte Stuffing, and Bit Stuffing
- [ ] **Error Detection and Correction**
  - [ ] Parity Check: Even and odd parity
  - [ ] Cyclic Redundancy Check (CRC)
  - [ ] Hamming code and its applications
  - [ ] Error correction vs. error detection
- [ ] **Medium Access Control (MAC)**
  - [ ] Purpose of MAC protocols
  - [ ] Techniques: ALOHA, CSMA/CD (Carrier Sense Multiple Access with Collision Detection), Token passing, Polling
  - [ ] Examples: Ethernet, Wi-Fi, Bluetooth
- [ ] **Ethernet Bridging**
  - [ ] Concept of Ethernet frame and MAC address
  - [ ] Switches and their role in Ethernet bridging
  - [ ] Learning and forwarding in Ethernet switches
  - [ ] Spanning Tree Protocol (STP) and loop prevention

## 4. **Routing Protocols**
- [ ] **Shortest Path Routing**
  - [ ] Dijkstra’s Algorithm for finding the shortest path
  - [ ] Bellman-Ford Algorithm and its application in distance vector routing
- [ ] **Flooding**
  - [ ] Concept and operation of flooding in network routing
  - [ ] Pros and cons of flooding
- [ ] **Distance Vector Routing**
  - [ ] Bellman-Ford routing algorithm
  - [ ] Distance vector protocols: RIP (Routing Information Protocol)
  - [ ] Limitations of distance vector routing (count-to-infinity problem)
- [ ] **Link State Routing**
  - [ ] Dijkstra’s algorithm in link state routing
  - [ ] Link state protocols: OSPF (Open Shortest Path First), IS-IS (Intermediate System to Intermediate System)
  - [ ] Comparison with distance vector routing

## 5. **Fragmentation and IP Addressing**
- [ ] **Fragmentation**
  - [ ] Need for fragmentation in networks
  - [ ] How fragmentation works in the network layer
  - [ ] Maximum Transmission Unit (MTU) and packet size limits
- [ ] **IPv4 Addressing**
  - [ ] IPv4 address structure (32-bit address)
  - [ ] Subnetting: Subnet mask, Network, Host, and Broadcast addresses
  - [ ] Classful addressing: Classes A, B, C, D, E
  - [ ] Private vs Public IP Addresses
  - [ ] CIDR (Classless Inter-Domain Routing) notation and its benefits
  - [ ] IP address allocation and subnetting example
- [ ] **Address Resolution Protocol (ARP)**
  - [ ] Role of ARP in IP to MAC address mapping
  - [ ] ARP request and response process
  - [ ] ARP table management and ARP cache
- [ ] **Dynamic Host Configuration Protocol (DHCP)**
  - [ ] DHCP client-server model
  - [ ] DHCP address leasing, renewal, and allocation
  - [ ] DHCP message types: Discover, Offer, Request, Acknowledge
  - [ ] DHCP relay and its operation
- [ ] **Internet Control Message Protocol (ICMP)**
  - [ ] ICMP message types: Echo request, Echo reply, Destination unreachable, Time exceeded
  - [ ] ICMP and its role in error reporting and diagnostics (Ping utility)
- [ ] **Network Address Translation (NAT)**
  - [ ] Concept of NAT and its use in IP address conservation
  - [ ] Types of NAT: Static NAT, Dynamic NAT, PAT (Port Address Translation)
  - [ ] How NAT affects end-to-end connectivity

## 6. **Transport Layer**
- [ ] **Flow Control and Congestion Control**
  - [ ] Flow control in transport layer: Preventing buffer overflow
  - [ ] Window-based flow control (Sliding window protocol)
  - [ ] Congestion control: Preventing network congestion
  - [ ] Techniques: TCP congestion control (Slow start, Congestion avoidance, Fast retransmit, Fast recovery)
- [ ] **UDP (User Datagram Protocol)**
  - [ ] Connectionless, unreliable protocol
  - [ ] UDP packet structure
  - [ ] Use cases of UDP (DNS, VoIP, Streaming)
- [ ] **TCP (Transmission Control Protocol)**
  - [ ] Connection-oriented protocol
  - [ ] Three-way handshake (SYN, SYN-ACK, ACK)
  - [ ] TCP segment structure (Header fields)
  - [ ] Flow control, reliability, and congestion control in TCP
  - [ ] TCP flags and state transitions (SYN, ACK, FIN, etc.)
  - [ ] TCP connection termination (FIN, ACK)
- [ ] **Sockets**
  - [ ] Socket programming basics
  - [ ] Types of sockets: Stream sockets (TCP), Datagram sockets (UDP)
  - [ ] Client-server architecture in socket programming

## 7. **Application Layer Protocols**
- [ ] **Domain Name System (DNS)**
  - [ ] DNS hierarchy and structure (Root, TLD, Authoritative servers)
  - [ ] DNS query and response process (Recursive, Iterative queries)
  - [ ] Types of DNS records: A, AAAA, CNAME, MX, PTR, etc.
  - [ ] Caching and TTL (Time to Live) in DNS
- [ ] **Simple Mail Transfer Protocol (SMTP)**
  - [ ] SMTP for email sending: Commands, responses, and server-client interaction
  - [ ] SMTP and email relay process
  - [ ] Differences between SMTP and POP/IMAP
- [ ] **Hypertext Transfer Protocol (HTTP)**
  - [ ] HTTP request and response model
  - [ ] HTTP methods: GET, POST, PUT, DELETE, HEAD, OPTIONS
  - [ ] HTTP status codes: 1xx, 2xx, 3xx, 4xx, 5xx
  - [ ] Stateless nature of HTTP and cookies
  - [ ] HTTPS (Secure HTTP) and SSL/TLS encryption
- [ ] **File Transfer Protocol (FTP)**
  - [ ] FTP client-server model
  - [ ] Active vs Passive FTP
  - [ ] FTP commands: LIST, RETR, STOR, etc.
  - [ ] FTP over SSL (FTPS) and SFTP (SSH File Transfer Protocol)
- [ ] **Email Protocols**
  - [ ] SMTP, POP3, IMAP
  - [ ] Email message format (Headers, body)
  - [ ] Email client-server architecture
