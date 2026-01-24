## 🛡️ Junior Security Analyst Intro– TryHackMe

### Overview

This lab simulates the day-to-day responsibilities of a **Security Operations Center (SOC) Analyst**, including alert monitoring, threat investigation, escalation, and response. The objective was to analyze security alerts, identify malicious activity, and take appropriate remediation actions while collaborating with the SOC team.

---

### 🔍 Daily SOC Activities Simulated

* Reviewing security alerts and logs
* Investigating suspicious IP addresses and login activity
* Participating in SOC discussions and escalation workflows
* Collaborating with teammates to contain threats
* Learning about real-world attack techniques and defenses
* Understanding how security decisions impact business operations

---

### 🚨 Incident Summary: Unauthorized SSH Access Attempt

**Scenario:**
During the SOC simulation, two security alerts were generated related to an external IP address.

#### Alerts Observed

1. **Unauthorized access attempt** – flagged as low severity
2. **Successful SSH login from an external IP** – flagged as **critical**

---

### 🧠 Investigation Process

* Identified the source IP address associated with the SSH login alert
* Used an IP reputation checking tool to analyze the external IP
* Confirmed that the IP address was **malicious** and associated with suspicious activity
* Determined the event posed a potential security risk due to successful authentication

---

### 🚦 Response & Escalation

* Escalated the incident to the **SOC Team Lead** for deeper analysis
* Implemented containment by **blocking the malicious IP address at the firewall level**
* Ensured no further unauthorized access attempts occurred from the same source

---

### 🧰 Skills Demonstrated

* Security alert triage and prioritization
* Log and authentication event analysis
* IP reputation analysis
* Incident escalation and communication
* Firewall-based threat containment
* SOC workflow and incident-handling methodology

---

### 📸 Evidence

Screenshot from the SOC simulation showing alert investigation and response workflow:

<img width="1305" height="547" alt="SOC Alert Investigation" src="https://github.com/user-attachments/assets/c78a7ac7-e088-4e82-b856-4f9d072ee4d5" />

---

### 📌 Key Takeaway

This simulation reinforced practical SOC analyst skills such as **distinguishing low-risk events from critical threats**, validating alerts, escalating incidents appropriately, and applying containment measures to protect organizational assets.

---

### 💡 Optional:


> *Future improvements include automating IP reputation checks and creating detection rules for anomalous SSH login behavior.*


---


