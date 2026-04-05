# 👋 Hi, I'm Christelle Janine Lureñana

**Security Detection · Network Engineering · Automation**  
Polytechnic University of the Philippines · GPA: 1.23 / 1.00

---

## 🧠 About Me

I build **detection systems and network infrastructure that hold under real conditions**, not just controlled labs.

My work focuses on:

* Translating ambiguous security problems into **repeatable detection logic**
* Designing networks with **enforced boundaries and validated failover**
* Automating infrastructure with **state verification, not just deployment**

Most student projects stop at *“it works.”*
Mine are built to answer:

> *Does it still work under failure, scale, and misconfiguration?*

---

## ⚙️ What I Actually Do

* Build **SIEM-style detection logic** from raw logs (not dashboards on clean data)
* Design **segmented enterprise networks** with measurable resilience
* Implement **network-as-code pipelines** with drift detection
* Develop **risk-based anomaly detection systems** using SQL correlation logic

---

## 🚀 Selected Work

### 🔐 Cloud Security Detection Engine

**Repo:** [https://github.com/janinelurenana/cloud-security-analyzer](https://github.com/janinelurenana/cloud-security-analyzer)

Built a modular detection pipeline that processes CloudTrail-style logs and produces **severity-ranked, MITRE ATT&CK–mapped findings**.

* 8 detection rules across 26 simulated cloud resources
* 43 validated findings surfaced via Streamlit
* Config-driven thresholds (no hardcoded detection logic)

**What matters:**

* Detection logic is **decoupled from thresholds** → mirrors real SIEM rule design
* Outputs are **explicitly mapped to attacker behavior**, not generic alerts

**Mapped Techniques:**

* T1078 — Valid Accounts / Privilege Abuse
* T1098 — Account Manipulation
* T1110 — Brute Force

---

### 🌐 Enterprise Network Architecture (HA + Segmentation)

**Repo:** [https://github.com/janinelurenana/Enterprise-Campus-Network-Architecture](https://github.com/janinelurenana/Enterprise-Campus-Network-Architecture)

Designed and validated a segmented campus network with **enforced least privilege and high availability**.

* VLAN segmentation: IT, HR, Guest, DMZ
* ACL-enforced zone isolation (not theoretical)
* FortiGate Active–Passive HA

**Validation, not assumption:**

* ~1 second failover convergence
* Session persistence during link failure

**Additional work:**

* Documented HSRP convergence behavior (5–10s)
* Extending to multi-site OSPF + IPsec VPN

---

### ⚙️ Declarative Network Automation + Drift Detection

**Repo:** [https://github.com/janinelurenana/declarative-network-provisioning](https://github.com/janinelurenana/declarative-network-provisioning)

Built a **multi-vendor network-as-code pipeline**:

YAML → Jinja2 → Netmiko → Device Configuration → State Verification

**Key capability:**

* Drift detection is **bidirectional**

  * Detects missing intended config
  * Detects unauthorized changes

**Why this matters:**
Most automation scripts push configs.
This enforces **state integrity**, which is what production environments actually need.

---

### 💳 Fraud Detection via SQL Correlation Logic

**Repo:** [https://github.com/janinelurenana/banking-fraud-detection-analytics](https://github.com/janinelurenana/banking-fraud-detection-analytics)

Built a transaction analysis system using **weighted anomaly scoring**, not simple thresholds.

* 5,500 transactions across 200 accounts
* Multi-table joins with CASE-based scoring

**Detection includes:**

* Velocity anomalies
* Geographic inconsistencies
* High-value outliers

**Key insight:**
Single signals don’t trigger alerts—**combined risk does**
→ aligns with real SIEM correlation logic

**Output:**

* Star schema → Power BI dashboards
* Geographic threat clustering for interpretability

---

## 🧰 Stack

**Security**

* Log Analysis · MITRE ATT&CK
* IAM Auditing · CSPM
* Burp Suite (SQLi) · Nmap

**Networking**

* GNS3 · FortiGate HA
* OSPF · VLANs · ACLs
* IPsec VPN · HSRP / VRRP
* NAT · STP

**Programming / Automation**

* Python · SQL
* Jinja2 · YAML
* Pandas · Streamlit · Netmiko

**Tooling**

* Power BI · MySQL
* AWS CloudTrail
* Kali Linux
* Git / GitHub

---

## 📈 Current Direction

* Multi-site network simulation (OSPF + IPsec WAN)
* Detection engineering aligned with SOC workflows via TryHackMe
* CompTIA Security+ (target: Q3 2026)

---

## 🤝 Opportunities

Open to **junior-level roles**, not just internships:

* Security Analyst
* Network Engineer
* Detection Engineer (entry/junior)

---

## 📬 Contact

* Email: [lchristellejanine@gmail.com](mailto:lchristellejanine@gmail.com)
* LinkedIn: [https://linkedin.com/in/lurenanachristellejanine](https://linkedin.com/in/lurenanachristellejanine)

---
