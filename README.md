### OSI Model
**What It Is**
The OSI (Open Systems Interconnection) Model is a conceptual framework used to understand and design how different network technologies interact and communicate with each other. It was developed by the ISO (International Organization for Standardization) to facilitate interoperability among various network systems and protocols.

**How Many Layers It Has**
The OSI model consists of 7 layers, each with specific functions:
1. **Physical Layer**: Transmission and reception of raw data over physical mediums like cables, fiber optics, or wireless.
2. **Data Link Layer**: Manages communication between physically close devices, such as in a LAN, error handling, and flow control.
3. **Network Layer**: Network addressing and data routing between devices on different networks.
4. **Transport Layer**: Ensures reliable and efficient data transfer between endpoints.
5. **Session Layer**: Manages communication sessions between applications on different devices.
6. **Presentation Layer**: Translates between data formats and encrypts/decrypts data.
7. **Application Layer**: Interface for network applications and end-user services.

**How It Is Organized**
Each layer in the OSI model serves the layer directly above it and implements services for the layer directly below. The lower layers are more oriented towards the transport of data, while the upper layers are more focused on the application and presentation of the information.

### What is a LAN?
**Typical Usage**
A LAN (Local Area Network) is used to connect computers and devices within a limited geographical area, such as a home, school, or office, to share resources (like printers) and for data communication.

**Typical Geographical Size**
The geographical size of a LAN varies but is generally limited to a single building or a group of nearby buildings.

### What is a WAN?
**Typical Usage**
A WAN (Wide Area Network) is used to connect devices or local networks across extensive geographical areas, facilitating communication and information exchange over long distances.

**Typical Geographical Size**
WANs can span cities, regions, countries, and even continents.

### What is the Internet?
**What Is an IP Address?**
An IP address is a unique identifier assigned to each device connected to a computer network using the Internet Protocol for communication. Its primary function is to enable the identification and location of devices on the network.

**The 2 Types of IP Addresses**
- **IPv4**: Uses a 32-bit structure, typically shown in decimal notation (e.g., 192.168.1.1).
- **IPv6**: Designed to overcome the shortage of IPv4 addresses, it uses 128 bits, allowing a significantly larger number of unique addresses.

**What Is Localhost?**
"localhost" refers to the local IP address of the user's own computer, typically mapped to the address 127.0.0.1 in IPv4, or ::1 in IPv6. It is used for testing or accessing services on the same machine.

**What Is a Subnet?**
A subnet (subnetwork) is a logical division of an IP network. The process of dividing a network into two or more networks is called subnetting. It is used to optimize the use of IP addresses and to improve network security and performance.

**Why Was IPv6 Created?**
IPv6 was primarily created to address the shortage of available addresses in IPv4. It offers a significantly larger address space and improvements in areas like network routing and security.

### TCP/UDP
**Mainly Used Data Transfer Protocols for IP**
- **TCP (Transmission Control Protocol)**
- **UDP (User Datagram Protocol)**

**Main Difference Between TCP and UDP**
TCP provides reliable, connection-oriented data delivery, ensuring that all packets arrive in order and error-free. It uses acknowledgments and retransmissions.
UDP is simpler and does not establish a connection. It does not guarantee the arrival of packets, making it faster but less reliable than TCP.

**What Is a Port?**
A port in computer networking is a number that identifies a specific application or process on a device within a network. Ports enable differentiating multiple data streams arriving at the same IP address.

**SSH, HTTP, and HTTPS Port Numbers**
- **SSH (Secure Shell)**: Port 22
- **HTTP (Hypertext Transfer Protocol)**: Port 80
- **HTTPS (HTTP Secure)**: Port 443

**Tool/Protocol to Check if a Device Is Connected to a Network**
The `ping` command is frequently used to check network connectivity to another device. It uses the ICMP (Internet Control Message Protocol) to send echo messages and wait for responses, helping determine the network's availability and latency to the target device.