# **Activity: Incident Report Analysis Using the NIST Cybersecurity Framework**

---

## **Activity Overview**

In this activity, you will take on the role of a cybersecurity analyst for a multimedia company that experienced a **DDoS (Distributed Denial of Service) attack**. You will apply the **NIST Cybersecurity Framework (CSF)** to analyze the incident and create a report with recommended solutions to improve the company’s security practices. The framework will guide your response, helping you identify the attack, protect assets, detect potential incidents, respond efficiently, and recover from disruptions.

The **NIST CSF** consists of five key functions:
1. **Identify:** Assess risks and vulnerabilities.
2. **Protect:** Safeguard assets through preventive measures.
3. **Detect:** Monitor network traffic for potential threats.
4. **Respond:** Contain and neutralize incidents.
5. **Recover:** Restore operations and recover from the attack.

Use the provided **incident report analysis template** to complete this activity.

---

## **Scenario Overview**

You are working as a **cybersecurity analyst** for a multimedia company that provides web design and marketing services. Recently, the company experienced a **DDoS attack**. The attack overwhelmed the internal network with **ICMP ping packets**, rendering services unavailable for two hours. 

After identifying that the attack exploited a **misconfigured firewall**, the incident management team blocked incoming ICMP packets, restored critical services, and initiated a full investigation.

The cybersecurity team implemented several measures in response:
- **Firewall rules** to limit incoming ICMP traffic.
- **IP verification** on the firewall to block spoofed addresses.
- **Network monitoring tools** to detect abnormal traffic.
- **IDS/IPS systems** to filter suspicious ICMP packets.

Your task is to create a report that follows the **NIST CSF framework** and outlines the company’s response to the attack.

---

## **Instructions**

1. **Identify the attack and systems affected** – Determine the type of attack and which systems were impacted.
2. **Develop a protection plan** – Suggest measures to protect the company from future attacks.
3. **Outline detection strategies** – Identify tools or processes to monitor for suspicious activity.
4. **Create a response plan** – Develop a strategy for responding to future incidents.
5. **Recommend recovery steps** – List actions needed to restore operations after an attack.

---

# **Solution: Incident Report Analysis**

## **Identify: Type of Attack and Systems Affected**
- **Attack Type:** Distributed Denial of Service (DDoS) using ICMP pings.
- **Impact:** 
  - Network services were **unavailable for two hours**.
  - **Critical resources** were affected, disrupting internal operations.
  - **Firewall misconfiguration** allowed the attack to bypass protections.

---

## **Protect: Plan to Safeguard Assets**
- **Firewall Rules:** 
  - Implement **rate limiting** for incoming ICMP packets.
  - **Block non-essential traffic** during periods of high network activity.

- **Access Control:** 
  - Enforce **multi-factor authentication (MFA)** to secure administrative accounts.
  - Regularly **audit access privileges** to limit unauthorized access.

- **Training and Awareness:** 
  - Conduct **employee training** on detecting phishing attempts and suspicious activity.
  - Implement **incident response drills** to improve response times.

---

## **Detect: Strategies for Monitoring Threats**
- **Network Monitoring Tools:** 
  - Use **real-time network monitoring** to detect abnormal traffic patterns.
  - Deploy **alert systems** for high ICMP traffic or failed login attempts.

- **Intrusion Detection Systems (IDS):** 
  - Utilize IDS to **filter and detect suspicious ICMP packets**.
  - Ensure **IP verification** to block spoofed addresses attempting to bypass the firewall.

- **Log Management:** 
  - Maintain **detailed logs** of network activity for analysis.
  - Regularly **review logs** to identify patterns that indicate potential attacks.

---

## **Respond: Plan for Future Incidents**
- **Containment:**
  - **Isolate** affected systems to prevent the spread of malicious traffic.
  - Block **malicious IP addresses** and monitor for additional attacks.

- **Incident Reporting:**
  - Establish a **communication protocol** for incident reporting to stakeholders.
  - Share information with **external partners and authorities**, if needed.

- **Analysis:** 
  - Review **logs and attack patterns** to identify the root cause.
  - Conduct a **post-incident review** to improve future response strategies.

---

## **Recover: Steps to Restore Operations**
- **System Restoration:**
  - **Restart essential services** and gradually reintroduce non-critical systems.
  - Verify **system integrity** to ensure no backdoors were introduced.

- **Backup Restoration:** 
  - Use **backups** to restore data affected during the incident.

- **Improvement Plan:** 
  - Update **firewall configurations** to close identified gaps.
  - Conduct **regular security audits** to ensure continued protection.

---

## **Conclusion**
This DDoS attack highlighted the importance of **firewall configuration** and the need for **real-time monitoring** to detect suspicious activity. The incident response team implemented several key measures to mitigate the impact and prevent future attacks. 

By following the **NIST Cybersecurity Framework**, the organization can enhance its **network security posture**, improve **incident response processes**, and ensure the **continuity of operations**.

---

## **Self-Assessment**
1. Did you identify the type of attack and the systems affected? **Yes**
2. Does your report offer a plan to protect the network from future incidents? **Yes**
3. Did you describe methods to detect security events? **Yes**
4. Does your report include a response plan? **Yes**
5. Did you outline recovery steps to restore operations? **Yes**


