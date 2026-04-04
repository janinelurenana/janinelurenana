# 👋 Hi, I’m Christelle Janine

**Christelle Janine M. Lureñana**  
IT Student · Security Detection & Network Automation  
Polytechnic University of the Philippines (GPA: 1.23 / 1.00)  

---

## 🧠 About Me

I’m a sophomore IT student focused on the intersection of **security detection** and **network infrastructure**.

My work follows a consistent pattern:
take a real operational problem—misconfigured cloud resources, anomalous transactions, inconsistent device configs—and build systems that **detect or prevent issues systematically**, not manually.

Current work includes:

* Cloud security posture analysis (Python, MITRE ATT&CK–mapped detection rules)
* SQL-based anomaly detection modeled after SIEM correlation logic
* Enterprise network architecture (GNS3, FortiGate HA with measured failover)
* YAML-driven multi-vendor network provisioning with drift detection

I focus on closing the gap between:

> *“it works in a lab”* vs *“it holds under failure conditions.”*

---

## 🚀 Featured Projects

### 🔐 Cloud Security Analyzer

**Repo:** [https://github.com/janinelurenana/cloud-security-analyzer](https://github.com/janinelurenana/cloud-security-analyzer)

* Built a modular Python pipeline to analyze CloudTrail-style logs
* Runs **8 configurable detection rules** across simulated cloud resources
* Outputs **43 severity-ranked findings** via Streamlit dashboard

**Key Design Decision:**
Detection thresholds are fully decoupled from logic via config files—mirroring how real SIEM rule engines operate.

**Credibility Signals:**

* MITRE ATT&CK–mapped detections:

  * T1078 (Valid Accounts / Privilege Abuse)
  * T1098 (Account Manipulation)
  * T1110 (Brute Force)
* Not generic alerts—explicit threat classification

---

### 🌐 Enterprise Campus Network Architecture

**Repo:** [https://github.com/janinelurenana/Enterprise-Campus-Network-Architecture](https://github.com/janinelurenana/Enterprise-Campus-Network-Architecture)

* Designed full Layer 3 enterprise topology in GNS3
* VLAN segmentation across IT, HR, Guest, and DMZ zones
* Enforced least privilege using ACLs
* Implemented FortiGate Active–Passive HA

**Key Validation:**

* ~1 second failover convergence (measured, not assumed)
* Session preservation under link failure

**Credibility Signals:**

* Documented HSRP convergence (5–10s)
* DMZ east–west restrictions enforced via ACLs
* Currently extending to multi-site OSPF + IPsec VPN

---

### ⚙️ Declarative Network Provisioning

**Repo:** [https://github.com/janinelurenana/declarative-network-provisioning](https://github.com/janinelurenana/declarative-network-provisioning)

* Built a **YAML → Jinja2 → Netmiko** pipeline for network automation
* Declarative configuration deployment across multi-vendor devices

**Key Feature:**

* **Bidirectional drift detection**

  * Detects missing configs *and* unauthorized changes

**Credibility Signals:**

* Multi-vendor support (not single-platform scripting)
* Architecture mirrors real-world tools (Ansible / Nornir)

---

### 💳 Banking Fraud Detection Analytics

**Repo:** [https://github.com/janinelurenana/banking-fraud-detection-analytics](https://github.com/janinelurenana/banking-fraud-detection-analytics)

* Built a SQL-based anomaly detection engine across 5,500 transactions
* Uses **weighted risk scoring** over multi-table joins

**Detection Logic Includes:**

* Velocity abuse
* Geographic anomalies
* High-value transaction outliers

**Key Design Insight:**

* Composite scoring prevents false positives—mirrors SIEM correlation logic

**Credibility Signals:**

* Star schema ETL → Power BI dashboards
* SOC-style visualizations with geographic threat clustering

---

## 🧰 Tech Stack

**Security**

* Log Analysis · MITRE ATT&CK
* IAM Auditing · CSPM
* Burp Suite (SQLi) · Nmap

**Networking**

* GNS3 · FortiGate HA
* OSPF · VLANs · ACLs
* IPsec VPN · HSRP / VRRP
* NAT · STP

**Programming**

* Python · SQL
* Jinja2 · YAML
* Pandas · Streamlit · Netmiko

**Tools**

* Power BI · MySQL
* AWS CloudTrail
* Kali Linux
* Git / GitHub

---

## 🎯 Current Focus

**In Progress**

* Multi-site OSPF + IPsec VPN (WAN simulation)
* TryHackMe SOC Level 1 path (structured SOC analyst training)
* CompTIA Security+ (Target: Q3 2026)

**Recently Shipped**

* Declarative network provisioning with drift detection (March 2026)
* Cloud security analyzer with MITRE ATT&CK detections (March 2026)

---

## 📬 Contact

* 📧 Email: [lchristellejanine@gmail.com](mailto:lchristellejanine@gmail.com)
* 🔗 LinkedIn: [https://linkedin.com/in/lurenanachristellejanine](https://linkedin.com/in/lurenanachristellejanine)

---

## 🤝 Open To

* Security Analyst Intern
* Network Engineer Intern (Philippines)

⏱️ Response time: ~24 hours
