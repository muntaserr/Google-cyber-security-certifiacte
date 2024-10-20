# **Network Concepts and Security Summary**

## **Types of Network**
- **LAN**: Local Area Network (e.g., within a building)
- **WAN**: Wide Area Network (e.g., across cities or countries, including the internet)

---

## **Network Devices**
- **Hub**: Broadcasts info to all devices on the network.
- **Switch**: Sends data only to the intended recipient device.
- **Router**: Connects multiple networks.
- **Modem**: Connects a router to the internet.

**Example Flow**: Device → Router → Modem → Internet → Modem → Router → Device

---

## **Virtualization Tools**
- **Software** that performs network operations instead of physical hardware.

---

## **Network Models**

### **TCP/IP Model**
1. **Network Access Layer**: Transfers data packets within a network (Ethernet, WLAN).
2. **Internet Layer**: Connects networks using IP addresses (IPv4/6).
3. **Transport Layer**: Controls traffic flow and ensures error handling (TCP, UDP).
4. **Application Layer**: Handles communication between apps (HTTP, DNS).

### **OSI Model**
1. **Physical Layer**: Physical hardware.
2. **Data Link Layer**: Transmits data packets within a network.
3. **Network Layer**: Handles routing between networks.
4. **Transport Layer**: Manages data flow and error handling.
5. **Session Layer**: Manages communication sessions.
6. **Presentation Layer**: Handles encryption and formatting.
7. **Application Layer**: Interfaces with user applications.

---

## **IPv4 vs IPv6**

- **IPv4 Header Example**:
  ![IPv4 Header](files/ipv4-packet.png)
- **IPv4 vs IPv6 Comparison**:
  ![Comparison](files/ipv4-vs-ipv6.png)

---

## **Network Protocols**
- **TCP**: Establishes reliable connections.
- **ARP**: Resolves MAC addresses.
- **DNS**: Translates domain names to IPs.
- **HTTPS**: Secure web communication.

### **Categories of Protocols**
- **Communication**: HTTP(S), DNS, SSH, SMTP
- **Management**: SNMP, ICMP, DHCP
- **Security**: HTTPS, SFTP

---

## **Common Ports**
- **DHCP**: UDP 67/68
- **SSH**: TCP 22
- **HTTP**: TCP 80
- **HTTPS**: TCP 443

---

## **Wi-Fi Security**
- **WPA3**: Latest standard with enhanced encryption.
- **WPA2**: Uses AES encryption, widely adopted.
- **WEP**: Outdated, vulnerable.

---

## **Firewalls**
- **Hardware Firewall**: Filters packets before entering the network.
- **Software Firewall**: Installed on devices to filter traffic.
- **NGFW**: Advanced firewall with deep packet inspection.

---

## **VPNs (Virtual Private Networks)**
- **WireGuard**: Open-source, easy to set up.
- **IPSec**: More complex, widely used.

---

## **Network Segmentation**
- **DMZ**: Public-facing servers like web and DNS.
- **Internal Network**: Private services accessible only to employees.
- **Restricted Zone**: Confidential resources.

---

## **Proxy Servers**
- **Forward Proxy**: Handles requests from users to the internet.
- **Reverse Proxy**: Handles requests from the internet to a server.
- **Email Proxy**: Filters spam emails.

---

## **Network Attacks**
- **SYN Flood**: Overwhelms server with synchronization requests.
- **Ping of Death**: Sends malformed ICMP packets to crash systems.
- **Man-in-the-Middle (MITM)**: Intercepts communication between devices.
- **Brute Force Attack**: Attempts to guess passwords through repeated login attempts.

---

## **Prevention Techniques**
- **Firewall Rules**: Block unnecessary ports.
- **Strong Passwords**: Enforce password policies.
- **Multi-Factor Authentication (MFA)**: Adds an extra layer of security.
- **Intrusion Detection Systems (IDS)**: Monitor for suspicious activity.

---

## **Cloud Hardening**
- **IAM (Identity Access Management)**: Manages access to cloud resources.
- **Hypervisors**:
  - **Type 1**: Runs directly on hardware.
  - **Type 2**: Runs on host operating systems.

---

## **Conclusion**
This summary provides an overview of **network concepts, protocols, security practices, and common attack types**. With a clear understanding of the **TCP/IP model, Wi-Fi security, and network segmentation**, organizations can implement **proactive measures** to secure their infrastructure, including **firewalls, VPNs, and network monitoring tools**.


