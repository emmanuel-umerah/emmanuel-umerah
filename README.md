# Emmanuel Nnaemeka Umerah | Hybrid Risk & Tech-Audit Portfolio
**Head of Customer Service @ UBA | Certified ISO 42001 Lead Auditor | Google Cybersecurity Professional | Aviatrix Cloud Engineer**

Welcome to my professional risk infrastructure and technology audit portfolio. This space showcases my practical applications at the strategic intersection of **Tier-1 Core Banking Operations**, **Advanced Data Analytics/Modeling**, and **Enterprise Cyber/Cloud Security Governance**. 

---

## 🚀 Featured Architecture Project: Project Aegis
### *Automated Cloud Governance & Risk Intelligence Pipeline for Enterprise Banking Systems*

### 📋 Project Overview
Traditional manual auditing frameworks introduce extreme latency into systemic risk identification. **Project Aegis** addresses this structural vulnerability by automating the ingestion, parsing, and compliance-mapping of heterogeneous infrastructure log files across hybrid cloud environments. The framework extracts raw operational logs, detects adversarial patterns, validates perimeters, and updates live risk matrices for senior stakeholders.

### 🛠️ Strategic Framework & Tool Stack
* **Infrastructure & Security:** Aviatrix Certified Multicloud Network Security, Google Cybersecurity Suite, Python Core.
* **Log Ingestion & Data Querying:** SQL Server, Linux/Bash Network Monitoring, Wireshark Network Analysis.
* **Governance Frameworks:** ISO/IEC 42001 (AI Management Systems), Central Bank Controls, AML/KYC.
* **Business Intelligence & Reporting:** PowerBI Data Analytics, Excel Core Financial Modeling.

### 🗂️ Project Repository Architecture & Code
Below is the core automated security parser script designed to dynamically detect potential structural authentication failures or adversarial brute-force exploits across critical application databases.

```python
import re
import csv
from datetime import datetime

# Input simulation: Enterprise financial database log architecture
LOG_FILE_PATH = "security_access_logs.txt"
AUDIT_REPORT_PATH = "credit_system_breach_report.csv"

# Strict regex matching pattern for failed Multi-Factor Authentication (MFA)
FAILED_AUTH_PATTERN = r"(?P<timestamp>\d{4}-\d{2}-\d{2} \d{2}:\d{2}:\d{2}) - ID: (?P<user_id>\w+) - IP: (?P<ip>\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}) - Status: (?P<status>FAILED_MFA|UNAUTHORIZED_ACCESS)"

def execute_automated_risk_audit(log_path, report_path):
    flagged_incidents_count = 0
    print(f"[*] Initializing Automated Security Audit on Core Ledgers...")
    
    with open(report_path, mode='w', newline='') as csv_file:
        fieldnames = ['Timestamp', 'User_ID', 'IP_Address', 'Risk_Classification', 'Action_Required']
        writer = csv.DictWriter(csv_file, fieldnames=fieldnames)
        writer.writeheader()
        
        try:
            with open(log_path, mode='r') as logs:
                for line in logs:
                    match = re.search(FAILED_AUTH_PATTERN, line)
                    if match:
                        flagged_incidents_count += 1
                        # Map log data cleanly against internal risk governance parameters
                        writer.writerow({
                            'Timestamp': match.group('timestamp'),
                            'User_ID': match.group('user_id'),
                            'IP_Address': match.group('ip'),
                            'Risk_Classification': 'CRITICAL_VULNERABILITY',
                            'Action_Required': 'IMMEDIATE_ACCOUNT_SUSPENSION_AND_IAM_AUDIT'
                        })
            print(f"[+] Audit execution complete. Flagged System Threats: {flagged_incidents_count}")
            print(f"[+] Production-ready compliance report exported to: {report_path}")
        except FileNotFoundError:
            print(f"[-] Execution Error: Specified server log file '{log_path}' not detected.")

if __name__ == "__main__":
    execute_automated_risk_audit(LOG_FILE_PATH, AUDIT_REPORT_PATH)
```

### 📊 Business Impact & Deliverables
1. **Data Silo Elimination:** Converted raw, unformatted network log structures into structural, auditable transaction tables.
2. **Proactive Fraud Mitigation:** Reduced risk exposure intervals by shifting control protocols from periodic physical checking to streaming data analysis.
3. **Verified Audit Readiness:** Output maps directly onto **ISO/IEC 42001** and internal credit policy requirements, creating clear evidence files for regulatory reviews.

---

## 🏆 Verified Credentials Matrix

### 🔐 AI Governance, IT Audit & Cyber Security
* **ISO/IEC 42001:2023 Certified Lead Auditor** | *Mastermind Assurance (ID: wh16sxqf4r)*
* **Google Cybersecurity Professional Certificate** | *Google / Coursera ([Verify Badge via Credly](https://credly.com))*
* **Aviatrix Certified Engineer (ACE) – Multicloud Network Associate** | *Aviatrix, Inc. (ID: 2025-26325)*
* **Internal Auditing – Fundamental Principles & Concepts** | *Alison (CPD Certified | Score: 100%)*
* **Offensive Security Pathway (46.5 Hours)** | *Udemy / Jarno Baselier (ID: UC-2136d9ae-f4e6-4312-b09a-373fb6c58371)*
* **Introduction to Cybersecurity** | *Cisco Networking Academy*

### 📊 Data Analytics, Financial Modeling & Business Intelligence
* **Data Analytics Professional Certification** | *Techpye (Cert No: TP/000004/24/01)*
* **Financial Modeling – Core Modeling Skills** | *Delmich Academy (ID: 1507-7185468645)*
* **PowerBI from Beginner to PRO** | *Delmich Academy (ID: 1752-3540443038)*
* **Business Analysis Basics** | *Simplilearn SkillUp (Cert Code: 8944170)*
* **Basics of Business Analytics** | *UniAthena / Cambridge International Qualifications, UK*
* **Lean Six Sigma White Belt Certified** | *Management and Strategy Institute (Cert #344936181)*

### 💼 Banking Operational Risk, Compliance & Credit
* **Associate Chartered Certified Accountant (ACCA)** | *In Progress / Candidate*
* **Associate, Chartered Institute of Bankers of Nigeria (ACIB)** | *In Progress / Candidate*
* **Banking Operations, Compliance/Internal Control, and International Trade** | *UBA Academy*
* **Annual Compliance & Policy Knowledge Certification** | *UBA Academy*
* **Credit Policy and Asset Risk Certificate** | *UBA Academy*

### ⚡ Leadership, Strategy & Customer Experience Architecture
* **Certified Customer Service Professional (CCSP) & BCCS** | *West Africa Association of Customer Service Professionals (WAACSP)*
* **Customer Relationship Management (CRM) Software Mastery** | *WAACSP (Cert No: CRMF2025-89-796-2638)*
* **Business Management Essentials** | *Management and Strategy Institute (Cert #344945408)*
* **Customer Experience (CX) Course for Managers / Pillars of CX** | *UBA Academy*
* **Product Management Frameworks Certificate** | *Betechified (Cert No: BT/DEC/080)*
* **Advanced Soft-Skills & Corporate Communication** | *Jobberman Nigeria / Mastercard Foundation*

---
📫 **Connect with Me:** [Professional Email](mailto:nnaemekaemmanuel503@gmail.com)
