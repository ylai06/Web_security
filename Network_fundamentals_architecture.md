# Network Fundamentals and Architecture 
Network security is critical for several reasons:
1. **Protection of sensitive data**: Preventing unauthorized access to sensitive information, such as personal data, intellectual property, and financial records.
2. **Compliance with regulations**: Many industries have strict data protection and privacy regulations.
3. **Maintaining productivity**: Ensure the network is available and performs optimally, allowing employees to work efficiently and without disruption.
4. **Building trust**: A secure network fosters trust between an organization and its clients, partners, and employees, as they can be confident that their data is protected.


## OSI model and Security concerns
The Open System Interconnection(OSI) model is a reference model that helps understand how computer networks operate and communicate. It contains 7 layers:
1. **Application Layer**
- The application layer is used by end-user software such as web browsers and email clients. It provides protocols that allow software to send and receive information and present meaningful data to users.
- A few examples of application layer protocols are the Hypertext Transfer Protocol (HTTP), File Transfer Protocol (FTP), Post Office Protocol (POP), Simple Mail Transfer Protocol (SMTP), and Domain Name System (DNS).
- *Security concern:* backdoors, program logic flaws, bugs, and Trojan horses.
2. **Presentation Layer**
- The presentation layer prepares data for the application layer. It defines *how two devices should encode, encrypt, and compress data* so it is received correctly on the other end.
- The presentation layer takes any data transmitted by the application layer and prepares it for transmission over the session layer.
- *Security concern:* Phishing attacks(釣魚). 
3. **Session Layer**
- The session layer creates communication channels, called sessions, between devices. It is responsible for opening sessions, ensuring they remain open and functional while data is being transferred, and closing them when communication ends.
- The session layer can also set checkpoints during a data transfer—if the session is interrupted, devices can resume data transfer from the last checkpoint.
- *Security concern:* Hijacking attacks.
4. **Transport Layer**
- The transport layer takes data transferred in the session layer and breaks it into “segments” on the transmitting end. It is responsible for reassembling the segments on the receiving end, and turning them back into data that the session layer can use.
- The transport layer carries out flow control, sending data at a rate that matches the connection speed of the receiving device, and error control, checking if data was received incorrectly and if not, requesting it again.
- The transport layer is responsible for end-to-end data transmission and flow control and reliable process-to-process delivery of a message.
- *Security concern:* session hijacking, SYN flood attacks, and man-in-the-middle attacks.
5. **Network Layer**
- The network layer has two main functions:
  1. Breaking up segments into network packets, and reassembling the packets on the receiving end.
  2. Routing packets by discovering the best path across a physical network.
- The network layer uses network addresses (typically Internet Protocol addresses) to route packets to a destination node(Source-to-destination delivery).
- *Security concern:* IP spoofing, denial of service (DoS) attacks(拒絕服務), and routing attacks.
6. **Data Link Layer**
- The data link layer establishes and terminates a connection between two physically connected nodes on a network. It breaks up packets into frames and sends them from source to destination. 
- The data link layer is composed of two parts—Logical Link Control (LLC), which identifies network protocols, performs error checking and synchronizes frames, and Media Access Control (MAC) which uses MAC addresses to connect devices and define permissions to transmit and receive data.
- The data link layer is responsible for error-free transmission of data frames between nodes on the same network. And moving frames from one hop (node) to the next(Hop-to-hop delivery).
- *Security concern:* sniffing(偵測), spoofing(欺騙), broadcast storms, and insecure or absent virtual LANs (VLANs).
(偵測（Sniffers）是一種網絡流量數據分析的手段，常見於網絡安全領域使用，取得網路上傳輸的資料包。)
7. **Physical Layer**
- The physical layer is responsible for the physical cable or wireless connection between network nodes.
- The physical layer defines the connector, the electrical cable or wireless technology connecting the devices, and is responsible for the transmission of the raw data, which is simply a series of 0s and 1s, while taking care of bit rate control.
- *Security concern:* Physical Tampering(物理篡改), eavesdropping(竊聽), and signal interference(信號干擾). 
## TCP/IP protocol suite 
The TCP/IP protocol suite, also known as the Internet Protocol Suite, is the foundation of the modern Internet. It consists of four layers:
1. **Application Layer**
   - responsible for the application, presentation, and session layer functions of the OSI model and for providing user interfaces and application services.
   - Common protocols: HTTP, FTP, SMTP, and DNS.
3. **Transport Layer**
   - responsible for the Transport layer functions of the OSI model and end-to-end data transmission and flow control.
   - 2 Primary Protocols: the Transmission Control Protocol (TCP) and the User Datagram Protocol (UDP).
4. **Internet Layer**
   - responsible for the Network(Internet) layer functions of the OSI model for routing data packets between networks.
   - Primary Protocol: Internet Protocol(IP)
5. **Network Interface Layer**
   - responsible for the physical and data link layer functions of the OSI model.
   - Deals with hardware addressing, error detection, and media access control.
### Addresses in TCP/IP
...
## Network architectures: LAN, WAN, VPN
### Local Area Network(LAN)



