# 🛡️ Analyze Network Attacks – SYN Flood Case Study

This project presents a practical analysis of a simulated network-layer attack. The investigation reveals a **SYN flood DoS attack** that disrupted normal employee access to the company's web service.

## 📂 Files Included

| File Name | Description |
|-----------|-------------|
| **Cybersecurity_Incident_Report_Rehan.docx** | Final report documenting the entire investigation. It explains the attack, its impact, and suggests mitigation steps. |
| **Wireshark_TCP_HTTP_log.xlsx** | Raw log of TCP/HTTP traffic captured during the attack. Includes packet timestamps, source/destination, and protocol info. Highlights attacker and normal traffic. |
| **How to read a Wireshark TCP_HTTP log.odt** | A guide to understanding the structure and meaning of Wireshark logs. Used as reference to decode patterns in this project. |

---

## 📝 Summary

### 🔍 Scenario
As a Security Analyst at a travel agency, I was alerted to a service interruption. Upon inspection, I discovered that a **malicious IP was sending repeated TCP SYN requests**, overwhelming the server’s capacity and preventing employees from accessing critical web content.

### 🛠 Tools Used
- **Wireshark**
- **TCP/HTTP Protocol Analysis**
- **Firewall Rule Configuration**
- **Incident Response Documentation**

---

## ✅ What I Did
- Captured and analyzed network logs using Wireshark
- Identified attacker behavior through SYN packet patterns
- Differentiated between legitimate and malicious traffic
- Drafted a professional **incident report** for internal escalation

---

## 📸 Screenshot

![Wireshark Log Screenshot](https://github.com/i-am-rehan/Analyze-network-attacks/blob/main/Screenshot%202025-07-08%20210838.png)


---

## 📌 Key Skills Demonstrated
- Network packet analysis  
- Identifying and interpreting SYN flood attacks  
- Incident response documentation  
- Network security troubleshooting

---

## 🔗 How to Use
1. Open the `Wireshark_TCP_HTTP_log.xlsx` to view color-coded traffic logs.
2. Refer to the `.odt` file to understand the log structure.
3. Read the `.docx` report to follow the investigation and conclusions.

---

## 📚 Learning Outcome
This case study helped me reinforce key concepts in:
- TCP 3-way handshake
- SYN flood detection via traffic behavior
- Defensive response strategies (like IP blocking and firewall tuning)

---

## 🤝 Let's Connect!
If you're hiring for an analyst role or want to collaborate, feel free to [connect on LinkedIn](https://www.linkedin.com/in/rehan-ahmad-9551b21ab/) or drop me a message!

