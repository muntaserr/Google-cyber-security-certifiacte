# Access Control Analysis Activity

## **Overview**
In this activity, you will assess the **access controls** used by a business and investigate a potential **security incident**. By analyzing event logs and identifying weaknesses in access management, you will provide recommendations to improve **authentication** and **authorization controls** to prevent future breaches.

---

## **Scenario**
You are the first **cybersecurity professional** hired by a growing business. Recently, a deposit was almost transferred to an **unknown bank account**. Fortunately, the transfer was stopped. The finance manager insists they did not make a mistake. Your task is to **investigate the incident** and find ways to **prevent similar issues** in the future.

You will:
1. **Review event logs** to identify suspicious activity.
2. **Identify access control issues** that led to the incident.
3. **Recommend mitigations** to improve access controls and reduce future risks.

---

## **Step-by-Step Instructions**

1. **Access the Template:**
   Use the following [Access Control Worksheet Template](https://docs.google.com/document/d/1jdI0FecPuabVB5ZI7na8C0Jm8J6bFlU76AEKD0T8dSw/template/preview?usp=sharing).

2. **Review the Event Log:**  
   - Open the **Accounting exercise spreadsheet** and find the **Event Log tab**.
   - Note any **important details** (e.g., event date, time, IP address).

3. **Identify Access Control Issues:**  
   - Compare the **Employee Directory tab** with the **Event Log tab**.
   - Identify **issues** with access control practices.

4. **Make Recommendations:**  
   - List **2 recommendations** to improve the company’s access controls.

---

## **Access Control Worksheet - Completed Example**

| **Section**            | **Response**                                                                                                                                     |
|------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| **Notes about the User** | The event occurred on **10/03/23**. The user has **administrator access** but is not listed as an admin. The IP address used was **152.207.255.255**. |
| **Access Control Issues** | **Robert Taylor, Jr.** is a former employee whose contract ended in 2019, but his account accessed payroll systems in 2023. The business uses **shared cloud storage**, leading to improper access. |
| **Recommendations**     | 1. **User accounts should automatically expire** 30 days after the end of employment. <br> 2. **Enable multi-factor authentication (MFA)** to protect accounts. |

---

## **Analysis**

1. **Event Log Observations:**  
   The incident log shows that a **former employee's account** accessed the payroll system years after his contract ended. The IP address associated with the event does not match the usual business network, suggesting the possibility of a **compromised account**.

2. **Access Control Issues:**  
   - The company does not enforce **account expiration** for former employees.  
   - Employees share access to cloud resources without proper **role-based access control (RBAC)**, creating **security risks**.

3. **Recommendations:**  
   - **Account expiration policies:** Ensure user accounts are **disabled** after employment ends to prevent unauthorized access.  
   - **Multi-Factor Authentication (MFA):** Enforce MFA to add an extra layer of security to prevent unauthorized logins.  
   - **Role-based access control:** Implement **RBAC** to ensure employees only have access to the information required for their roles.

---

## **Key Takeaways**

- **Shared accounts and cloud access** without proper controls increase the risk of unauthorized access.
- **Account expiration policies** are essential to prevent former employees from accessing systems.
- **Multi-Factor Authentication (MFA)** reduces the risk of account compromise through stolen or reused credentials.
- Implementing **role-based access control (RBAC)** ensures users only access information necessary for their roles.

---

## **Pro Tip**
Always **audit user accounts** regularly to ensure only active employees have access to business systems. **Automate account management processes** to enforce account expiration and maintain secure access practices.

---
