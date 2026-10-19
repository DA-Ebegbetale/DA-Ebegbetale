## Hi there 👋 I'm Dave, a Systems Engineer and Security Architect

I am passionate about security-first architectures, backend API development, and a decoupled, domain-driven development approach. My focus centers on engineering trust boundaries, unifying sub-systems, and driving system observability alongside governance analysis.

### 🧠 Engineering Principles

> *"True architectural advancement is marked by working logic, not convoluted patterns, nor does complexity equate to sophistication. Resilient systems are those engineered with absolute clarity."*

## 🛠️ Technical Stack

### Systems Architecture & Security
* **Design Paradigms:** Object-Oriented Analysis and Design (OOAD) | Domain-Driven Design (DDD) | Decoupled Microservices Architectures
* **Systems Security:** Zero-Trust patterns | Identity & Access Management (IAM) | Principle of Least Privilege (PLP) | Segregation of Duties (SoD) | Role-Based Access Control (RBAC) | Secure Coding Practices

### Software Engineering & Backend API Development
* **Backend Development:** Java | Python | Dart | PHP (Strict Typing)
* **Frameworks & Libraries:** Micronaut | FastAPI | Flutter
* **Databases & Cloud Storage:** PostgreSQL | Oracle Relational Database | MySQL | MongoDB | Firebase Firestore
* **Frontend Web Technologies:** HTML5/CSS3/Vanilla JavaScript (ES6+)

### Infrastructure, DevOps & Network Analysis
* **Network Analysis & Security:** Network design | Wireshark packet analysis | Splunk ES
* **DevOps & Administration:** Bash scripting | Git Version Control | Linux System Administration (Ubuntu)
* **Virtualization & Containerization:** Docker/Docker Compose | VMware | VirtualBox
* **Systems Observability:** Telemetry pipelines | Log Analysis & Metrics | Distributed Tracing

---

## ⭐ Featured Repositories

### 📁 [Clinic Management System](https://github.com/DA-Ebegbetale/clinic-mgmt-sys)
This platform delivers a secure, frameworkless, multi-layered domain-driven environment utilizing a four-tier architecture (Application, Domain, Infrastructure, and Presentation) engineered to address structural vulnerabilities typical in legacy EHR/EMR setups. 
* **Key Implementations:** Integrates an immutable data retention and preservation sub-system by strategizing a soft-deletion logic with comprehensive metadata and timestamp tracking to aid medical record auditing and compliance standards.
* **Security Posture:** Enforces a Zero-Trust architecture by incorporating core IAM principles, including the Principle of Least Privilege (PoLP) and Segregation of Duties (SoD), to clearly demarcate system boundaries. The backend intercepts exceptions to prevent stack trace leaks, returning predefined, generic messages specifically designed to eliminate client-side information disclosure.
* **Technologies:** PHP, MySQL, Vanilla JS, Custom Routing Framework

### 📁 [Secure Enterprise Campus Network Redesign](https://github.com/DA-Ebegbetale/campus-network-redesign)
This project delivers a transparent, high-throughput wireless solution to overcome complex physical deployment constraints at a multi-building corporate facility. It securely links campuses where traditional physical cabling was impossible due to an intersecting navigable canal.
* **Key Implementations:** Features a hybrid topology that utilizes a central Multi-Layer Switch in the primary facility and a high-density switch stack in the secondary facility, bridged seamlessly via a high-throughput Layer 3 wireless link. Local access tiers within both buildings are aggregated into their respective core anchors using high-bandwidth EtherChannel trunks. Localized loop mitigation and segment isolation are maintained using Cisco Rapid-PVST+ across 12 distinct functional VLANs, ensuring traffic stability across the wireless transit path.
* **Security Hardening:** Enforces network boundary security through extended Access Control Lists (ACLs) at the Layer 3 Core to isolate confidential segments. At Layer 2, infrastructural security is fortified against spoofing attacks by integrating DHCP Snooping and Dynamic ARP Inspection (DAI), while unused or blocked ports are securely isolated into an unrouted "blackhole" VLAN. Wireless edge security utilizes enterprise-grade WPA3-Enterprise with 802.1X RADIUS authentication for robust user identity verification.
* **Technologies:** Cisco Core L3 Switching, L2 Switch Stacking, EtherChannel, PTP Wireless Bridging, Rapid-PVST+, VLSM, 802.1X RADIUS

---

## 🔬 In-Progress Research & Development

### 🔒 Secure Email Gateway with Integrated Phishing & Impersonation Detection Sub-systems

This initiative presents a modular, enterprise-grade secure email gateway engineered to bridge operational gaps between automated ingestion layers and security team triage protocols.
* **Architectural Rationale:** The architecture validates incoming SPF, DKIM, and DMARC evidence, enforces configurable message-disposition state-machines (covering delivery, warning, quarantine, and rejection states), and runs a parallel supervised machine-learning classifier benchmarked against explainable logic arrays to evaluate relative detection performance including precision, recall, F1-score and false-positive and false-negative rates.
* **Technologies:** Python (FastAPI), PostgreSQL (SQLAlchemy, Alembic), Docker, JWT & Bcrypt Authentication, Supervised Machine Learning (Scikit-Learn)
***Note: The prototype is under active evaluation in a controlled environment***

---

## 🏅 Credentials

<a href="https://www.credly.com/badges/0361a6c1-00ef-4441-84fe-3ab6ae2457e2/public_url" target="_blank" title="Click to verify: Governance for AI Agents with MongoDB"><img src="https://images.credly.com/size/160x160/images/9a1ebf46-b34f-4b88-83c2-3af4863cf3df/blob" width="128" alt="Governance for AI Agents with MongoDB" /></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://www.credly.com/badges/f8fe8f91-b53f-4940-b92e-6563bfbd97e6/public_url" target="_blank" title="Click to verify: Observability for AI Agents"><img src="https://images.credly.com/size/160x160/images/bee03c5c-df2b-443e-9a1f-1ec32e14cf56/blob" width="128" alt="Observability for AI Agents" /></a>

---

## 🌐 Connect With Me

Whether you want to discuss a potential collaboration, work opportunities, my featured projects, or just talk tech, feel free to reach out through any of the channels below:
* **Professional Network:** [LinkedIn](www.linkedin.com/in/da-ebegbetale)
* **Direct Inquiries:** [da.ebegbetale@gmail.com](mailto:da.ebegbetale@gmail.com)
