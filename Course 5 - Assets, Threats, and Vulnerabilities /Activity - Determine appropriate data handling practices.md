# Data Risk Assessment and Handling Practices

## **Overview**

This activity involves reviewing a data leak incident to determine whether effective data handling processes were implemented to protect information privacy. You will analyze the scenario, evaluate the current data privacy controls, and recommend improvements to prevent future incidents. The company’s data handling policy is based on the **NIST Cybersecurity Framework (CSF)** and **NIST SP 800-53: AC-6**.

---

## **Scenario**

You work for an educational technology company that developed an application to automate grading assignments. Recently, **internal business plans** were accidentally shared on social media by a customer. An investigation found that during a sales meeting, **confidential documents** were mistakenly shared with the customer by a company employee. 

### **Summary of Incident**

- A manager shared a folder containing internal documents (including customer analytics and marketing materials) with a customer success representative.
- The manager **forgot to unshare the folder** after the meeting.
- During a sales call, the representative mistakenly shared the **entire folder** with the customer instead of only the marketing materials.
- The customer posted the internal documents on **social media**.

---

## **Step-by-Step Instructions**

1. **Analyze the Situation:**  
   Describe the factors that led to the data leak and why the principle of least privilege was not followed.

2. **Review Current Data Privacy Controls:**  
   Summarize **NIST SP 800-53: AC-6**, focusing on how it addresses access control and least privilege.

3. **Identify Control Enhancements:**  
   Use the NIST SP 800-53 resource to list **two control improvements** that could have prevented the leak.

4. **Justify Your Recommendations:**  
   Provide a brief justification for why your recommended controls would reduce the risk of future leaks.

---

## **Data Leak Worksheet Solution**

| **Section**          | **Response**                                                                                                                                                      |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Issue(s)**         | The data leak occurred because a folder with internal documents was shared with a customer by mistake. The principle of least privilege was not followed, as the employee had unnecessary access to sensitive information. |
| **Review**           | NIST SP 800-53: AC-6 outlines how to implement **least privilege** to limit user access to only the information necessary for their role. It also recommends auditing user permissions regularly to prevent unauthorized access. |
| **Recommendation(s)**| 1. **Automatically revoke access** after a set period of time. <br> 2. **Regularly audit user privileges** to ensure only necessary access is granted. |
| **Justification**    | Automating the revocation of access reduces the chance of **human error**, such as forgetting to remove access after meetings. Regular audits help ensure that users do not retain access to information they no longer need, limiting the risk of accidental data leaks. |

---

## **Conclusion**

The data leak in this scenario highlights the importance of following the **principle of least privilege**. Employees should have access only to the information necessary for their role, and **temporary access** should be automatically revoked when it is no longer needed. Regular **audits** of user permissions ensure that users do not retain access to sensitive information beyond their needs. Implementing these controls can significantly reduce the risk of future data leaks.

---

## **Key Takeaways**

- **Least privilege** ensures that users only access information they need.
- **Automatic access revocation** can prevent forgotten access permissions from becoming a security risk.
- **Auditing user privileges** ensures that access controls remain effective over time.
- Demonstrating these security practices can be valuable when applying for roles in **cybersecurity** or **data privacy management**.

---

## **Pro Tip**

Save a blank copy of the data leak worksheet template for future practice. Use this template to **build your portfolio** and demonstrate your **security skills** to potential employers.

