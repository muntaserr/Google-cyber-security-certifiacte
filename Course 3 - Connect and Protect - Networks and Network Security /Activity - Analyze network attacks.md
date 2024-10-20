# Cybersecurity Incident Report Activity

## **Activity Overview**

In this activity, you will consider a scenario involving a customer of the company that you work for who experiences a security issue when accessing the company’s website. You will identify the likely cause of the service interruption, explain how the attack occurred, and describe the negative impact it had on the website. This activity will help you troubleshoot similar issues and apply the correct mitigation strategies to protect your organization’s network from future attacks.

## **Scenario**

You work as a security analyst for a travel agency that advertises sales and promotions on the company’s website. Employees access the sales webpage regularly to find vacation packages for their customers. One afternoon, you receive an automated alert from the monitoring system, indicating a problem with the web server. When you try to visit the site, your browser shows a connection timeout error.

Using a packet sniffer, you capture data packets going to and from the web server. The analysis reveals a large volume of TCP SYN requests coming from an unfamiliar IP address, causing the server to become overwhelmed and unable to respond to legitimate requests. 

You take the server offline temporarily to allow it to recover. You also configure the firewall to block the IP address sending abnormal traffic, but you recognize that this is only a temporary solution as attackers can spoof other IP addresses. You need to report the attack to your manager and suggest the next steps to secure the network and prevent future incidents. 

---

# Cybersecurity Incident Report

| **Section** | **Details** |
|-------------|-------------|
| **Date of Report:** | *[Enter Date]* |
| **Prepared By:** | *[Your Name]* |

---

## **1. Incident Overview**

| **Incident Description:** |
|---------------------------|
| On [Date], an alert was triggered by the monitoring system, indicating an issue with the web server of the company. Upon investigation, the security analyst identified a large number of TCP SYN requests originating from an unfamiliar IP address, overwhelming the server. This caused the web server to experience connection timeout errors. The attack disrupted the availability of the company’s website and affected employees’ ability to access essential resources. |

| **Incident Type:** | SYN Flood Attack (Denial of Service - DoS) |

---

## **2. Analysis of Attack**

| **Attack Analysis:** |
|----------------------|
| A SYN flood attack is a type of **Denial of Service (DoS)** attack. It occurs when an attacker sends a flood of TCP SYN requests to the target server but does not complete the handshake by sending ACK responses. This overwhelms the server, causing it to exhaust its resources as it waits for the handshake to complete. In this scenario, the abnormal SYN requests caused the server to become unresponsive, resulting in connection timeouts for both employees and customers. |

| **How the Attack Affected the Website:** |
|-----------------------------------------|
| The flood of SYN requests overwhelmed the web server, preventing it from processing legitimate traffic. This resulted in: |
| - **Connection timeout errors** for employees and customers attempting to access the website. |
| - **Loss of availability** of the company’s website, disrupting business operations. |
| - **Potential revenue loss** due to downtime during promotional activities and sales. |

---

## **3. Mitigation Actions**

| **Immediate Actions Taken:** |
|------------------------------|
| - Temporarily took the server offline to allow it to recover and restore normal operations. |
| - Configured the firewall to block the IP address sending the SYN flood traffic. |
| - Identified that IP blocking is a short-term solution as attackers can spoof other IP addresses to bypass restrictions. |

| **Next Steps:** |
|-----------------|
| - **Implement Rate Limiting:** Apply rate limiting to prevent an excessive number of SYN requests from overwhelming the server. |
| - **Enable SYN Cookies:** Configure the server to use SYN cookies to mitigate the impact of SYN flood attacks. |
| - **Install Intrusion Detection System (IDS):** Monitor and detect future network anomalies more effectively. |
| - **Review and Update Firewall Rules:** Regularly update firewall rules to block known malicious traffic sources. |
| - **Educate Employees:** Raise awareness about cyber threats to prevent social engineering and phishing attacks. |

---

## **4. Recommendations**

| **Recommendations for Future Prevention:** |
|--------------------------------------------|
| - Implement **Multi-Factor Authentication (MFA)** to prevent unauthorized access. |
| - Conduct **regular penetration testing** to identify and address vulnerabilities. |
| - Set up **network monitoring tools** to detect and mitigate attacks in real time. |
| - Develop and document **incident response plans** to ensure a quick response to future attacks. |
| - Use **DDoS mitigation tools** if the organization grows and faces distributed attacks. |

---

## **5. Conclusion**

| **Summary:** |
|--------------|
| The incident involving a SYN flood attack demonstrates the importance of proactive network security measures. Immediate actions helped restore operations, but long-term solutions such as SYN cookies and rate limiting are essential to prevent similar attacks. By implementing the recommended security measures, the organization can better protect its network and ensure website availability, minimizing the risk of future breaches. |

