# Cybersecurity Incident Report: DNS and ICMP Traffic Analysis

## **Activity Overview**

In this activity, you will analyze DNS and ICMP traffic using data from a network protocol analyzer tool. Your task is to identify which network protocol caused the service interruption. You will also explain how the attack or issue affected the system and propose solutions to resolve it. 

Network protocol analysis can help identify suspicious activity and potential threats within the network. You will leverage tools like `tcpdump` and logs to inspect IP packets and determine the root cause of the reported issue.

---

## **Scenario**

You are a cybersecurity analyst working at a company that provides IT consulting services. Several customers have reported that they cannot access the company’s website, **www.yummyrecipesforme.com**. The error message reads **“destination port unreachable.”**

You attempt to load the website yourself and confirm the same issue. Next, you load a network analyzer tool, **tcpdump**, and send a request to the website. Upon inspection, the following occurs:
- When you send **UDP packets** to the DNS server, you receive **ICMP responses** stating: **"udp port 53 unreachable."**
- The issue occurs repeatedly, preventing access to the website.

Based on your packet sniffing results, you must analyze the situation, write a report summarizing your findings, and propose steps to address the problem.

---

## **Cybersecurity Incident Report: Network Traffic Analysis**

### **Part 1: Summary of the Problem Found in the DNS and ICMP Traffic Log**

| **Details**                                      | **Explanation** |
|--------------------------------------------------|-----------------|
| **Protocol Impacted:**                          | UDP Protocol |
| **Error Message:**                              | "udp port 53 unreachable" |
| **Issue Description:**                          | The DNS server could not be reached using the UDP protocol on port 53, which is reserved for DNS services. Users trying to access the website received a **“destination port unreachable”** error. |
| **Reason for the Error:**                       | This error suggests that the **DNS server** may be down, blocked, or under attack, resulting in a failure to resolve the domain name. |

#### **Analysis of the Log**
- The **DNS request** was sent using **UDP packets** to port **53**.
- **ICMP responses** returned an **“unreachable”** message, indicating that the server did not respond on the DNS port.
- The repeated error confirms the DNS service is not functioning correctly, possibly due to a **Denial of Service (DoS) attack** or **firewall misconfiguration**.

---

### **Part 2: Analysis and Suggested Solution**

| **Details**                                      | **Explanation** |
|--------------------------------------------------|-----------------|
| **Date and Time of Incident:**                   | 13:24:32.192571 (1:24 PM) |
| **Reported Symptoms:**                          | Users reported receiving a **"destination port unreachable"** error when trying to access the website. |
| **Events Identified During Investigation:**     | The security team used **tcpdump** to analyze the network traffic and discovered that **port 53 (DNS)** was unreachable. |
| **Current Status of the Issue:**                | The issue is currently being handled by the security engineers, and further investigation is ongoing to restore the DNS service. |
| **Suspected Root Cause:**                       | The DNS server may have been affected by: |
|                                                  | 1. A **Denial of Service (DoS) attack** that overwhelmed the server. |
|                                                  | 2. **Firewall misconfiguration**, preventing traffic to port 53. |

---

### **Recommended Next Steps**

| **Task**                                         | **Explanation** |
|--------------------------------------------------|-----------------|
| **Verify DNS Server Functionality:**            | Check if the DNS server is operational and available. |
| **Check Firewall Rules:**                       | Ensure that port **53** is not being blocked by the firewall. Review and modify firewall settings if necessary. |
| **Investigate DoS Attack Possibility:**         | Monitor traffic logs for signs of **DoS attack patterns** targeting the DNS server. If confirmed, implement **rate limiting** and other security measures. |
| **Implement Continuous Monitoring:**            | Install monitoring tools to detect unusual traffic patterns and prevent future service disruptions. |

---

## **Conclusion**

The analysis of the DNS and ICMP traffic logs indicates that the **DNS server** was not responding on **port 53**, preventing domain name resolution and blocking access to the website. This issue could be due to a **Denial of Service (DoS) attack** or a **firewall misconfiguration**. Immediate actions include verifying the DNS server’s status, checking firewall rules, and monitoring for suspicious traffic. Long-term solutions involve implementing **network monitoring tools** and **firewall management** to prevent similar incidents in the future.


