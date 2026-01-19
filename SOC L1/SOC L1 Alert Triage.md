# Hello all !
# TryHackMe – SOC L1 Alert Triage

## 📌 Room Overview
The SOC L1 Alert Triage room introduces the fundamentals of Security Operations
Center (SOC) alert handling. It focuses on understanding how alerts are generated,
prioritized, investigated, and resolved by Level 1 SOC analysts using a SIEM dashboard.

**Room Status:** ✅ Completed (100%)  
**Duration:** 40 minutes

---

## 🎯 Objectives
- Understand the lifecycle of SOC alerts
- Learn alert properties such as severity, status, and verdict
- Perform alert prioritization based on severity and time
- Practice real-world alert triage workflows as an L1 analyst

---

## 🧠 SOC Concepts Learned
- Difference between events and alerts
- Alert severity vs alert verdict
- Importance of avoiding false positives while not missing real threats
- SOC L1 analyst responsibilities in a real SOC environment

---

<img width="1882" height="663" alt="Screenshot 2026-01-19 134136" src="https://github.com/user-attachments/assets/5b83e42a-eb4f-4f66-b219-1c2f5547d78b" />

## 🚨 Alerts Investigated

### 1️⃣ Potential Data Exfiltration
**Severity:** Critical  
**Verdict:** False Positive  

**Investigation Summary:**  
The alert was triggered due to a large amount of outbound data transfer.
Upon investigation, the activity was linked to frequent Zoom meetings,
which naturally generate high network traffic.

**Lesson Learned:**  
Legitimate business applications (like Zoom) can generate behavior similar
to data exfiltration. Context and user activity are critical before escalation.

---

### 2️⃣ Double Extension File Creation
**Severity:** High  
**Verdict:** True Positive  

**Investigation Summary:**  
A downloaded file had a suspicious double extension indicating potential malware.
The alert provided a file hash, which was checked using VirusTotal. The hash showed
a known malicious history.

**Actions Taken:**
- Identified malicious file behavior
- Recommended system isolation
- User awareness advised

**Lesson Learned:**  
Double file extensions are a common malware tactic. Hash-based threat intelligence
validation is an essential SOC skill.

---

### 3️⃣ GitHub Repository Download
**Severity:** Low  
**Verdict:** False Positive  

**Investigation Summary:**  
The alert flagged a repository download from GitHub. Further analysis confirmed
the user was a developer downloading React from a legitimate GitHub source.

**Lesson Learned:**  
Developer activity often triggers alerts. Understanding user roles prevents
unnecessary escalation.

---

## 🏁 Key Takeaways
- Not all high-severity alerts are malicious
- Context, user behavior, and business use cases matter
- Proper prioritization prevents alert fatigue
- L1 analysts play a crucial role in early threat detection

---

## 🛠️ Skills Gained
- SOC alert triage
- SIEM dashboard analysis
- Threat intelligence usage (VirusTotal)
- Alert prioritization and classification
- Real-world SOC workflows

<img width="1435" height="804" alt="Screenshot 2026-01-19 133738" src="https://github.com/user-attachments/assets/00a83578-120f-4d3e-96a8-2a5834d90c4b" />

