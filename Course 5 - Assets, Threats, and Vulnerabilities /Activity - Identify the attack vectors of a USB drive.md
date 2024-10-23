# USB Attack Vectors Activity

## **Overview**
In this activity, you will assess the security risks associated with a USB drive found in a parking lot. You will analyze the drive’s contents from both the perspective of an **attacker** and a **target**. USB drives can introduce severe security risks, including malware infections and breaches of sensitive information.

---

## **Scenario**
You are a member of the **security team at Rhetorical Hospital**. While arriving at work, you find a **USB stick** in the parking lot with the hospital’s logo on it. Out of curiosity, you bring the USB back to your office and insert it into a **virtual environment** to inspect it safely.

Upon examination, the drive contains both **personal and work-related files** belonging to **Jorge Bailey**, the HR manager at the hospital. Your task is to analyze the contents and assess the risks associated with USB baiting attacks.

---

## **Step-by-Step Analysis**

### **Step 1: Inspect the Contents of the USB Drive**

The USB contains files belonging to **Jorge Bailey**, which include:
- Family and pet photos (personal files).
- A new hire letter and an employee shift schedule (work-related files).

**Contents Response:**
The USB contains both **personal** and **work-related information**, such as employee schedules and a new hire letter. Having personal and professional data on the same device is a security risk because **personally identifiable information (PII)** can be exploited by attackers for targeted attacks.

---

### **Step 2: Apply an Attacker Mindset**

Consider how an attacker could use the information on the USB drive:
- The personal files could help **social engineers** build a profile on Jorge.
- The work-related files, such as employee schedules, could be used to **time attacks** or **gain unauthorized access** to the hospital.
- The USB could also be **planted intentionally** to gain access to internal systems through malware or as a distraction.

**Attacker Mindset Response:**
An attacker could use the **employee schedule** to plan **targeted attacks** during low-staff periods. The **new hire letter** could provide information about internal processes, which could be exploited. Personal files like **family photos** might help an attacker **impersonate Jorge** in a phishing attempt, gaining access to hospital systems.

---

### **Step 3: Risk Analysis**

**USB baiting attacks** rely on the curiosity of employees to plug in unknown devices. Even without malware, the contents of a USB can expose sensitive information that could be exploited. If malicious code were present, it could:
- Install **spyware** or **ransomware**.
- Create a **backdoor** to internal systems.
- Leak sensitive **PII** or medical records.

Technical and operational controls can help mitigate these risks:
- **Disable USB ports** on non-essential systems.
- **Implement employee training** to raise awareness about USB baiting.
- **Enforce antivirus scanning** for all external devices.
- **Disable Autoplay** to prevent malware from executing automatically.

**Risk Analysis Response:**
Plugging an unknown USB into a computer presents risks of **malware infection** or **data breach**. **Disabling USB ports** on critical systems and **raising employee awareness** about USB baiting can reduce these risks. **Antivirus scanning** and **disabling Autoplay** are essential technical controls that protect against malware infections.

---

## **Completed USB Attack Vectors Activity**

| **Section**          | **Response**                                                                                                                                                      |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Contents**         | The USB contains both personal and work-related files, including family photos, a new hire letter, and employee schedules. Mixing personal and professional data on the same device introduces security risks. |
| **Attacker Mindset** | An attacker could use the employee schedule to plan attacks during low-staff periods. The personal files might be used to impersonate the employee or target them with social engineering. The USB could also have been intentionally planted to gain unauthorized access. |
| **Risk Analysis**    | USB drives present risks of malware infections and data breaches. Disabling USB ports, providing employee training, and enforcing antivirus scans are essential operational controls. Disabling Autoplay ensures that malicious code does not execute automatically. |

---

## **Key Takeaways**

- **USB baiting attacks** are a common method for delivering malware and stealing sensitive data.
- **Personal and work-related data** should be stored separately to avoid unintended risks.
- Implementing **technical controls** like disabling USB ports and **operational measures** like employee training can mitigate risks associated with unknown devices.

---

## **Pro Tip**

Always inspect unknown USB drives in a **virtual environment** to prevent malware from infecting critical systems. Educating employees about the risks of USB baiting helps protect your organization from targeted attacks.

---
