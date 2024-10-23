# Incident Response Lifecycle and Related Concepts

---

## **NIST CSF (Recap)**

1. **Identify**  
2. **Protect**  
3. **Detect**  
4. **Respond**  
5. **Recover**

---

## **Incident Response Lifecycle**

1. **Preparation**  
2. **Detection and Analysis**  
3. **Containment, Eradication, and Recovery**  
4. **Post-Incident Activity**

---

## **The 5 W’s of an Incident**

1. **Who** triggered the incident  
2. **What** happened  
3. **When** the incident occurred  
4. **Where** the incident took place  
5. **Why** the incident occurred

---

## **Incident Response Teams**

- **CSIRT**: Computer Security Incident Response Team  
  Team typically includes:
  - Security analysts
  - Technical lead
  - Incident coordinator
  - Legal, communications staff (if needed)

**Goals:** Command, Control, Communication

---

## **Security Operations Center (SOC)**

- **Tier 1**: Analyst (handles initial triage)  
- **Tier 2**: Analyst (handles escalated issues)  
- **Tier 3**: Lead analyst (advanced detection)  
- **SOC Manager**: Oversees operations

---

## **Incident Response Plans**

Components:
- Incident response procedures  
- System information  
- Contact forms, templates

---

## **Tools for Incident Response**

### **Intrusion Detection Systems (IDS):**
- Examples: **Zeek, Suricata, Snort, Sagan**

### **Intrusion Prevention Systems (IPS):**
- Examples: **Suricata, Snort, Sagan**

### **Endpoint Detection and Response (EDR):**
- Examples: **Open EDR, Bitdefender EDR, Forti EDR**

---

## **SIEM Process**

1. **Collect and aggregate data**  
2. **Normalize data**  
3. **Analyze data**

---

## **SOAR (Security Orchestration, Automation, and Response)**

- Automates incident analysis and response.  
- **SIEM**: Collects & reports events.  
- **SOAR**: Tracks & manages incidents.

---

## **Network Monitoring Concepts**

- **IoC (Indicators of Compromise):** Observable evidence of an attack.
- **Data Exfiltration:** Unauthorized transmission of data.  
- **Network Traffic:** Amount of data moving through the network.  
- **Network Data:** The content being transmitted.

---

## **Monitoring Techniques**

- **Flow Analysis:** Look for unusual ports, packets, or protocols.  
- **Packet Payload Info:** Analyze packet data content.  
- **Temporal Patterns:** Check if data transfers align with typical working hours.

---

## **Defensive Measures**

1. **Prevent attacker access.**  
2. **Monitor network activity.**  
3. **Protect assets.**  
4. **Detect and stop data exfiltration.**

---

## **Packet Captures (P-Caps)**

- **Libpcap:** Unix-based, used by tools like tcpdump.  
- **WinPcap:** Older format for Windows.  
- **Npcap:** Modern format by Nmap for Windows.  
- **PCAPng:** Next-gen format, captures packets and metadata.

---

## **IP Packet Structure**

### **IPv4:**
- **Version:** v4/v6  
- **Header Length:** Total length of header + options  
- **Type of Service:** Priority level  
- **Time to Live (TTL):** Lifespan of packet  
- **Source & Destination IP:** Origin and target addresses

### **IPv6:**
- **Traffic Class:** Like Type of Service  
- **Flow Label:** Identifies specific streams  
- **Hop Limit:** Similar to TTL  
- **Source & Destination IP:** Origin and target addresses

---

## **Using tcpdump**

```bash
sudo tcpdump -i any -v -c 1

