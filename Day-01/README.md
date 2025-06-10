# 🛡️ Day 1 Cyber Security Notes

---

## 1. Basics of Cyber Security

- Cyber security involves protecting computer systems and networks from cyber threats.
- It ensures data confidentiality, integrity, and availability (CIA triad).
- Key areas:
  - Network security
  - Application security
  - Endpoint security
  - Cloud security
  - Physical security

---

## 2. Types of Cyber Attacks

| Type of Attack        | Description |
|-----------------------|-------------|
| **Phishing**          | Tricking users into revealing sensitive information via fake emails or websites. |
| **Ransomware**        | Encrypts files and demands ransom for decryption. |
| **Malware**           | Malicious software such as viruses and worms. |
| **Social Engineering**| Psychological manipulation to gain confidential info. |
| **DDoS**              | Overloads servers/networks to disrupt services. |
| **SQL Injection**     | Inserting malicious SQL queries to manipulate databases. |
| **Zero-Day Attack**   | Exploiting unknown vulnerabilities. |

---

## 3. L1, L2, and L3 Security Levels

- **L1 (Tier 1):**
  - Initial monitoring and alerting.
  - Follows predefined playbooks.
  - Escalates when necessary.

- **L2 (Tier 2):**
  - Handles incident investigation.
  - Correlates logs and alerts.
  - Uses SIEM tools and threat intelligence.

- **L3 (Tier 3):**
  - Advanced forensic and threat hunting.
  - Deep malware analysis.
  - Develops detection strategies.

---

## 4. SIEM (Security Information and Event Management)

- Centralized platform to collect, store, and analyze log data.
- Helps detect and respond to threats in real-time.
- Examples:
  - Splunk
  - IBM QRadar
  - ELK Stack

---

## 5. Bitdefender

- Advanced antivirus and endpoint protection tool.
- Features:
  - Real-time protection
  - Ransomware defense
  - Web protection
  - Email scanning

---

## 6. Wireshark

- Network protocol analyzer used for packet inspection.
- Helps in:
  - Troubleshooting network issues
  - Detecting malicious activity
  - Analyzing network performance

**Example Filter:**
```bash
ip.addr == 192.168.0.1 && tcp.port == 443




