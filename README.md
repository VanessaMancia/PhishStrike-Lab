# 🛡️ Phishing Investigation (CyberDefenders)

**Platform:** [CyberDefenders.org](https://cyberdefenders.org)  
**Category:** Threat Intelligence | Email Security  
**Status:** Work in Progress 🚧  

---

## 📖 Scenario
As a **Cybersecurity Analyst** at an educational institution, you receive an alert about a **phishing email** targeting faculty members.  

- The email appears to be from a **trusted contact**.  
- It references a **$625,000 purchase** and provides a **link to download an invoice**.  

Your task is to **investigate the email** using Threat Intelligence tools, analyze the email headers, inspect the link for malicious content, and identify any **Indicators of Compromise (IOCs).**

---

## 🎯 Objectives
- Analyze **email headers** (SPF, DKIM, Return-Path).  
- Inspect the **URL** for malicious content.  
- Identify **IOCs**: IPs, domains, file hashes, registry keys, C2 servers.  
- Document findings to support **fraud prevention** and **phishing awareness**.  

---

## ❓ Challenge Questions & Answers

### Q1  
**Question:** Identifying the sender's IP address with specific SPF and DKIM values helps trace the source of the phishing email. What is the sender's IP address that has an SPF value of softfail and a DKIM value of fail?  
**Answer:** `**.***.**.***`  

---

### Q2  
**Question:** Understanding the return path of an email is essential for tracing its origin. What is the return path specified in this email?  
**Answer:** `***********.*****@****.***.**`  

---

### Q3  
**Question:** Identifying the source of malware is critical for effective threat mitigation and response. What is the IP address of the server hosting the malicious file related to malware distribution?  
**Answer:** `***.***.***.***`  

---

### Q4  
**Question:** The malicious URL can deliver several malware types. Which malware family is responsible for cryptocurrency mining?  
**Answer:** `*********`  

---

### Q5  
**Question:** Based on the previous analysis of the cryptocurrency malware sample, what does this malware request the URL?  
**Answer:**  


---

### Q6  
**Question:** Based on the BitRAT malware sample analysis, what is the executable's name in the first value added to the registry auto-run key?  
**Answer:** `******.***`  

---

### Q7  
**Question:** What is the SHA-256 hash of the file previously downloaded and added to the autorun keys?  
**Answer:**  

---

### Q8  
**Question:** What is the URL in the HTTP request used by the loader to retrieve the BitRAT malware?  
**Answer:**  

---

### Q9  
**Question:** What is the delay (in seconds) caused by the PowerShell command according to the BitRAT analysis?  
**Answer:** `**`  

---

### Q10  
**Question:** What is the C2 domain used by the BitRAT malware?  
**Answer:** `*****.******.***`  

---

### Q11  
**Question:** According to the AsyncRAT analysis, what is the Telegram Bot ID used by this malware?  
**Answer:** `*************`  

---

## 🧑‍💻 Skills Practiced
- Threat Intelligence Enrichment  
- Email Header Analysis  
- URL and Malware Investigation  
- IOC Extraction & Documentation  
- Malware Persistence & C2 Analysis  

---

## ✅ Learning Outcomes
- Understand **phishing email tactics** and evasion methods.  
- Detect **malware distribution infrastructure**.  
- Analyze **BitRAT and AsyncRAT malware behavior**.  
- Improve **incident documentation and faculty awareness training**.  


