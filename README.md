# Cyber-Security-Audit-Botium-Toys
A comprehensive internal security audit for Botium Toys, focusing on risk assessment, NIST CSF alignment, and control recommendations.
# Internal Security Audit: Botium Toys

## 📌 Project Overview
The scope of this audit covers the entire security program at **Botium Toys**. This includes an evaluation of all physical assets (employee equipment, devices, storefront products), the internal network, and integrated systems. The audit reviewed existing assets, controls, and compliance practices to identify critical gaps and improve the organization's security posture.

---

## 🎯 Objectives
*   **Asset Assessment:** Identify and document all hardware, software, and data assets managed by the IT department.
*   **Compliance Review:** Determine alignment with U.S. and international regulations (GDPR, PCI-DSS).
*   **Gap Analysis:** Use the Controls and Compliance Checklist to identify missing security best practices.
*   **NIST Alignment:** Map findings to the **NIST Cybersecurity Framework (CSF)** to establish a remediation roadmap.

---

## 🛡️ Risk Assessment
| Metric | Details |
| :--- | :--- |
| **Risk Score** | **8 / 10** (High) |
| **Impact** | **Medium** (IT department lacks visibility into specific asset risks) |
| **Compliance Risk** | **High** (Lack of necessary controls for critical data privacy/security) |

> **Risk Summary:** Inadequate asset management and a lack of proper security controls place Botium Toys at significant risk of data breaches and regulatory fines.

---

## 🔍 Audit Findings & Gap Analysis

### **1. Access Control & Identity Management**
*   **Vulnerability:** Lack of **Least Privilege** and **Separation of Duties**. All employees currently have access to sensitive internal data, including customer PII and cardholder data.
*   **Vulnerability:** Password policies are nominal and do not meet modern complexity standards (e.g., lack of special characters).
*   **Vulnerability:** No centralized password management system, leading to productivity loss and security risks.

### **2. Data Security & Cryptography**
*   **Vulnerability:** Encryption is **not used** for credit card information at rest or in transit within the internal database.
*   **Vulnerability:** No disaster recovery plans or data backups are currently in place for critical systems.

### **3. Network & System Security**
*   **Vulnerability:** No **Intrusion Detection System (IDS)** is installed.
*   **Vulnerability:** Legacy systems are monitored but lack a regular maintenance schedule or clear intervention methods.
*   **Strength:** A firewall is active with defined security rules.
*   **Strength:** Antivirus software is installed and monitored regularly.

### **4. Physical Security & Compliance**
*   **Strength:** Physical locations are secured with sufficient locks, CCTV surveillance, and fire prevention systems.
*   **Strength:** An EU breach notification plan (72-hour window) is established.

---

## 🛠️ Assets Under Management
The audit evaluated the following IT-managed assets:
*   **On-premises equipment:** End-user devices, remote workstations, surveillance cameras, and peripherals.
*   **Storefront & Inventory:** Products available for retail and online sale; warehouse inventory.
*   **Systems & Services:** Accounting, ecommerce, inventory management, and database services.
*   **Legacy Systems:** End-of-life systems requiring specialized monitoring.

---

## 💡 Recommended Remediation
1.  **Enforce Least Privilege:** Restrict access to PII and cardholder data to only essential personnel.
2.  **Implement Encryption:** Deploy AES-256 encryption for all customer financial data.
3.  **Deploy IDS:** Install an Intrusion Detection System to monitor for unauthorized network traffic.
4.  **Resilience Planning:** Create a formal **Disaster Recovery Plan** and implement automated offsite backups.
5.  **Modernize Passwords:** Implement a centralized password manager and update complexity requirements.

---

## 🚀 Skills Demonstrated
*   **NIST CSF Framework Alignment**
*   **Compliance Auditing (GDPR/PCI-DSS)**
*   **Risk Identification & Scoring**
*   **Technical Policy Documentation**
