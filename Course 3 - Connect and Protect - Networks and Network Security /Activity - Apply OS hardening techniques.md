# Cybersecurity Incident Report: HTTP and DNS Protocol Analysis  

## **Activity Overview**  

In this activity, you are assigned the role of a cybersecurity analyst for **yummyrecipesforme.com**. Visitors to the website experience a security issue when loading the webpage. Your task is to investigate, identify, document, and recommend a solution to this security incident.  

When investigating the incident, you will review a **tcpdump log**. You must identify the protocols used in the attack and document your findings. In addition, you will recommend a security measure to prevent similar attacks in the future.  

Knowing how to identify common protocols and malicious activity is essential to protecting networks from security incidents. Your documentation will serve as a reference point for future incident management and compliance audits.  

---

## **Scenario**  

You are a cybersecurity analyst working for **yummyrecipesforme.com**, a website that sells recipes and cookbooks. A **disgruntled baker** has compromised the website by executing a **brute force attack** to gain admin access. They guessed the default password and changed the website's source code. The altered website prompts visitors to **download malware disguised as a browser update**. When the file runs, users are redirected to a **fake website** (greatrecipesforme.com), where recipes are posted for free.  

Multiple customers have reported the issue, stating that their computers started running slowly after downloading the file. The **website owner is locked out of the admin panel** and contacts the hosting provider. Your task is to investigate the issue, document the protocols used, and recommend preventive measures for the future.  

---

## **Cybersecurity Incident Report**  

### **Section 1: Identify the Network Protocol Involved in the Incident**  

| **Protocol**         | **Explanation**                                                                 |
|----------------------|---------------------------------------------------------------------------------|
| **HTTP**             | The attack involved the **Hypertext Transfer Protocol (HTTP)** at the application layer. |
| **DNS**              | The **Domain Name System (DNS)** was also involved to resolve URLs to IP addresses. |

#### **Log Analysis**  
- The **DNS & HTTP traffic log** shows that the initial DNS request resolved the **yummyrecipesforme.com** URL correctly.
- An HTTP request was sent to the webpage, prompting users to download the **malicious file** disguised as a browser update.
- After executing the downloaded file, a **new DNS request** resolved the **greatrecipesforme.com** URL.
- The **HTTP protocol** was used to redirect users to the fake website.

---

### **Section 2: Document the Incident**  

Several customers reported that when they accessed **yummyrecipesforme.com**, they were prompted to **download and run a suspicious file** claiming to update their browser. After running the file, they were redirected to a fake website (**greatrecipesforme.com**) and noticed their computers running more slowly.  

The **website owner** attempted to log in to the admin panel but was locked out. The security team created a **sandbox environment** to test the website without affecting the network. During testing, the team ran **tcpdump** to capture network traffic.  

- **Observation:**  
  - A **DNS request** resolved the IP address for **yummyrecipesforme.com**.  
  - An **HTTP request** initiated the download of the **malicious file**.  
  - After executing the file, another **DNS request** resolved the IP for **greatrecipesforme.com**.  

The **source code** on the website was modified to prompt the malicious download. The senior cybersecurity analyst confirmed that the attacker gained **admin access through a brute force attack** by guessing the default password. **No brute force mitigation controls** were in place to prevent the attack.  

---

### **Section 3: Recommend One Remediation for Brute Force Attacks**  

| **Recommended Measure** | **Explanation** |
|--------------------------|----------------|
| **Two-Factor Authentication (2FA)** | Implementing **2FA** ensures users must verify their identity through an **additional step** beyond entering a password. This reduces the risk of brute force attacks by requiring both the password and a **one-time password (OTP)** sent to the user's phone or email. |

#### **Why 2FA is Effective**  
- Even if a malicious actor guesses a password, they would also need access to the **OTP** to log in.
- **2FA** adds a **layer of security** to the login process, making it more difficult for unauthorized users to gain access.

---

## **Conclusion**  

This incident involved **DNS and HTTP protocols**, where an attacker used a **brute force attack** to access the admin panel and modify the website. The attacker embedded malicious **JavaScript** to prompt users to download a fake browser update. After executing the file, users were redirected to a **fake website** where the company’s recipes were posted for free.

To prevent future incidents, the company should implement **Two-Factor Authentication (2FA)** to protect admin accounts. Additionally, **monitoring login attempts** and **enforcing strong passwords** can further enhance the website’s security posture.

