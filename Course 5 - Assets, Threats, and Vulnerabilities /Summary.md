# Cybersecurity Concepts Overview

## **Risk and Security Plan**

- **Risk:** Anything that can impact the **CIA triad** (Confidentiality, Integrity, Availability) of an asset.
  
### **3 Elements of a Security Plan:**
1. **Assets:** Valuable items to the organization (e.g., data, people, buildings).
2. **Threats:** Circumstances or events that negatively affect assets (intentional or unintentional).
3. **Vulnerabilities:** Weaknesses that can be exploited by threats (technical or human flaws).

---

## **Asset Management and Classification**
- **Asset Management:** Tracking assets and the risks affecting them.
- **Asset Inventory:** Catalog of assets requiring protection.
- **Asset Classification:** Labelling assets by sensitivity and importance:
  - **Public:** Accessible to anyone.
  - **Internal-only:** Accessible to anyone in the organization.
  - **Confidential:** Specific people within the organization.
  - **Restricted:** Highly sensitive (e.g., health, payment data).

---

## **States of Data**
- **In Use:** Data actively being processed.
- **In Transit:** Data being transferred.
- **At Rest:** Data stored on disk.

---

## **Policies, Standards, and Compliance**
- **Policy:** Rules to reduce risk and protect information.
- **Standards:** Inform how to set policies.
- **Procedures:** Step-by-step instructions for specific tasks.
- **Compliance:** Adhering to internal and external standards.
- **Regulations:** Government/authority rules controlling processes.

---

## **NIST Cybersecurity Framework (CSF)**
- **Core Functions:**
  - **Identify** risks.
  - **Protect** assets.
  - **Detect** incidents.
  - **Respond** to incidents.
  - **Recover** operations.

- **Tiers (Performance):**
  - **Passive:** Minimum standard.
  - **Adaptive:** Exemplary performance.

- **Profiles:** Describe the current state of security systems.

---

## **Types of Security Controls**
- **Technical:** Encryption, firewalls.
- **Operational:** Awareness training, scanning.
- **Managerial:** Policies, standards, and procedures.

---

## **Data Roles**
- **Data Owner:** Person responsible for data access and use.
- **Data Custodian:** Responsible for data handling and storage.
- **Data Steward:** Manages data governance policies.

---

## **Types of Accounts**
- **Guest Accounts:** Limited external access.
- **User Accounts:** Employee access.
- **Service Accounts:** Software interaction.
- **Privileged Accounts:** Administrator-level access.

---

## **Data Lifecycle**
1. Collect
2. Store
3. Use
4. Archive
5. Destroy

---

## **Public Key Infrastructure (PKI)**
- **Asymmetric Encryption:** Uses public and private keys (e.g., RSA, DSA).
- **Symmetric Encryption:** Uses one key (e.g., AES, 3DES).
- **Digital Certificates:** Establish trust between systems.

---

## **Hashing and Non-repudiation**
- **Hashing:** Ensures data integrity.
- **Non-repudiation:** Ensures authenticity cannot be denied.

---

## **Access Control and Authentication (AAA Framework)**
- **Authentication:** Verifies identity.
  - **Knowledge:** Passwords.
  - **Ownership:** Tokens, smart cards.
  - **Characteristic:** Biometrics.
  
- **Authorization:** Grants permissions.
  - **Separation of Duties:** Prevents conflicts of interest.
  - **Principle of Least Privilege:** Minimize access to what’s necessary.

- **Accounting:** Tracks activities.

---

## **Access Control Models**
- **MAC:** Mandatory Access Control (e.g., military).
- **DAC:** Discretionary Access Control (e.g., document owner permissions).
- **RBAC:** Role-Based Access Control (assign permissions based on roles).

---

## **Vulnerability Management Process**
1. Identify vulnerabilities.
2. Consider potential exploits.
3. Prepare defenses.
4. Evaluate defenses.
5. **Zero-day vulnerability:** No time to fix before exploitation.

---

## **Defense-in-Depth (Castle Approach)**
- **Perimeter Layer:** Authentication.
- **Network Layer:** Firewalls.
- **Endpoint Layer:** Device protection.
- **Application Layer:** Secure software.
- **Data Layer:** Asset classification.

---

## **Exposure and Vulnerabilities**
- **Exposure:** Mistakes that create opportunities for attacks.
- **Vulnerabilities:** Weaknesses that could be exploited.
- **CVE List:** Created by MITRE in 1999 and sponsored by the US.

### **Vulnerability Scoring (CVSS)**
- **0-4.0:** Low priority.
- **9.0-10.0:** Requires immediate attention.

---

## **OSINT (Open Source Intelligence)**
- **Information:** Raw data or facts.
- **Intelligence:** Analyzed information to generate insights.

---

## **Penetration Testing Teams**
- **Red Team:** Simulate attacks.
- **Blue Team:** Defense and incident response.
- **Purple Team:** Combination of both.

### **Types of Penetration Testing**
- **Open-Box:** Access similar to developers.
- **Closed-Box (Black-Box):** Access similar to outsiders.
- **Grey-Box:** Limited access or partial knowledge.

---

## **Threat Actors**
- **Competitor:** Seeks competitive advantage.
- **State Actor:** Sponsored by governments.
- **Criminal Syndicate:** Seeks financial gain.
- **Insider Threat:** Internal users with malicious intent.
- **APT (Advanced Persistent Threat):** Long-term access to a target’s systems.

---

## **Types of Hackers**
- **Unauthorized Hacker:** Malicious hacker.
- **Authorized Hacker:** Ethical hacker.
- **Semi-Authorized Hacker:** Hacktivist.

---

## **Attack Vectors**
- **Direct Access:** Physical interaction with systems.
- **Removable Media:** USB drives.
- **Social Media Platforms:** Phishing and scams.
- **Email:** Phishing attempts.
- **Wireless Networks:** Open Wi-Fi attacks.
- **Cloud Services:** Cloud misconfigurations.
- **Supply Chains:** Attacks on vendors.

---

## **Defending Against Threats**
- **User Education:** Training on security awareness.
- **Least Privilege:** Reducing access to only what’s needed.
- **Right Controls and Tools:** Using firewalls, encryption, MFA.

---

## **Social Engineering**
### **Stages of Social Engineering**
1. **Prepare:** Gather information.
2. **Establish Trust:** Pretexting.
3. **Use Persuasion Tactics.**
4. **Disconnect from the Target.**

### **Signs of Social Engineering Attacks**
- **Baiting:** Dropped USB devices.
- **Phishing:** Deceptive emails.
- **Quid Pro Quo:** Offering something in exchange.
- **Tailgating:** Physical entry without authorization.
- **Watering Hole:** Targeted malware on niche websites.

---

## **Types of Malware**
- **Virus:** Requires user activation.
- **Worm:** Spreads without user action.
- **Trojan:** Disguised as legitimate software.
- **Ransomware:** Encrypts data for ransom.
- **Spyware:** Collects and sells data.

### **Cryptojacking Malware Signs**
- Slow performance.
- Increased CPU usage.
- Sudden crashes.
- High electricity bills.

---

## **Web Exploits**
- **XSS (Cross-Site Scripting):** Code injection.
  - **Reflected:** Activated in response.
  - **Stored:** Injected on the server.
  - **DOM-based:** Exists in webpage elements.

- **SQL Injection:** Manipulating queries.
  - **In-Band:** Same channel for attack and results.
  - **Out-of-Band:** Uses alternate channels.
  - **Inferential:** Observing behavior changes.

### **SQL Injection Prevention**
- Use **prepared statements**.
- Perform **input sanitization** and **validation**.

---

## **Threat Modelling**
1. **Define Scope.**
2. **Identify Threats.**
3. **Characterize Environment.**
4. **Analyze Threats.**
5. **Mitigate Risks.**
6. **Evaluate Findings.**

### **Threat Modelling Frameworks**
- **PASTA:** Process for Attack Simulation and Threat Analysis.
- **STRIDE:** Spoofing, Tampering, Repudiation, Information Disclosure, DoS, Elevation of Privilege.
- **VAST:** Visual, Agile, Simple Threat.

---

## **Feedback and Observations**
- High-quality animations and interactive labs enhance the learning experience.
- Copyable commands during labs avoid unnecessary busywork.
- Some topics could focus more on advanced concepts, as the end-user advice feels basic for later stages of the course.
