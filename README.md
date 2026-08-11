# ⚡ Abdul Faisal
**Security-Focused Software Engineer • AppSec & DevSecOps • Telemetry Architect**

I engineer resilient backend systems and the defensive infrastructure required to monitor them. Operating at the intersection of software architecture and threat detection, I build systems governed by a strict "Security by Design" philosophy and hardened by an offensive mindset.

> *"Mechanics over memory. Architecture over assumptions."*

---

## 🧠 Operating Philosophy

I reject the perimeter-only defense model. True security is structurally integrated at the code and database layer. I do not just configure firewalls or chase SIEM alerts—I engineer the backend mechanics that prevent anomalies from occurring, and build the telemetry pipelines that detect the rest. 

*   **Architectural Precision:** Leveraging Core Java, Spring Boot, and complex SQL data modeling to build systems that fail securely.
*   **Concurrency Defense:** Solving complex race conditions and double-booking anomalies at the database layer using strict transaction isolation.
*   **Adversary-Informed Design:** Utilizing offensive mechanics to dictate defensive engineering priorities. You cannot defend a system if you do not know exactly how it breaks.

---

## 🚧 Core Engineering & Security Mechanics

### 💼 Enterprise EV Aggregator Platform (Java/Spring Boot)
Engineering a high-concurrency Full Stack EV charging application bridging independent owners with EV drivers. This is not a standard CRUD app; it is an exercise in secure financial and state management.
*   **Stack:** `Java 21`, `Spring Boot`, `PostgreSQL`, `Stateless JWT`, `WebSockets (OCPP)`, `ReactJS`
*   **State & Concurrency:** Mitigating double-booking anomalies via **Optimistic Locking** to maintain data integrity across concurrent sessions.
*   **Financial Mechanics:** Executing atomic, double-entry financial ledgers (30/70 revenue splits). Utilizing strict `BigDecimal` primitives to eliminate floating-point precision vulnerabilities in financial calculations.
*   **AppSec:** Enforcing stateless JWT authentication, boundary sanitization, and Role-Based Access Control (RBAC) at the API gateway level.

### 🔹 APT Detection Platform & Telemetry Pipeline
Designed a behavioral analysis engine merging threat intelligence with network traffic analysis to detect Advanced Persistent Threats (APTs) before lateral movement occurs.
*   **Stack:** `Zeek`, `Python`, `Elastic Stack (ELK)`, `Sysmon`
*   **Detection Logic:** Engineered custom detection logic moving beyond static signatures to identify anomalous host behaviors and baseline deviations.
*   **Data Pipeline:** Integrated host and network telemetry into a centralized SIEM, parsing and normalizing logs for rapid querying and automated alerting.

### 🔹 Defensive Home SOC Lab
A self-hosted Blue Team sandbox built to validate detection rules against live adversary simulations.
*   **Stack:** `Wazuh`, `Splunk`, `Sysmon`, `Elastic Stack`
*   **Mechanics:** Generating custom attack telemetry using offensive tools, then writing Sigma/KQL rules to detect the resulting artifacts.

---

## ⚡ Technical Arsenal

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Backend & Architecture** | Java (Core & JVM Mechanics), Spring Boot, Hibernate (JPA), RESTful APIs |
| **Database & Modeling** | PostgreSQL, MySQL, ACID Compliance, Relational Normalization |
| **AppSec & DevSecOps** | Stateless JWT, OWASP Mitigation, Secure CI/CD, Docker, Git |
| **SecOps & Telemetry** | Splunk, Wazuh, Elastic Stack (ELK), Zeek, Sigma, KQL |
| **Offensive Frameworks** | MITRE ATT&CK, Nmap, Burp Suite, Metasploit, TryHackMe (Top 1%) |

---

## 📈 Professional & Academic Trajectory

*   **Specialization in Java FullStack Engineering** | *JSpiders* (March 2026 – Present)
    *   Deep-diving into JVM memory management, thread-safe execution, and enterprise Spring Boot architecture.
*   **Cybersecurity Intern** | *Pinnacle Labs* (April 2024 – May 2024)
    *   Executed threat hunting, log analysis, and vulnerability assessments in a live operational environment.
*   **B.Tech in Cyber Security (Minor in Data Science)** | *CMR College of Engineering & Technology* (June 2022 – May 2025)

---

## 📌 Current Operational Focus

I am currently deconstructing and mastering the following mechanics:
1.  **JVM Memory Optimization:** Tuning garbage collection and memory allocation for high-availability Spring Boot microservices.
2.  **Transaction Isolation:** Enforcing strict JPA/Hibernate isolation levels to prevent Phantom Reads and concurrency exploits.
3.  **Telemetry Synthesis:** Logging application state directly to Wazuh/Splunk to bridge the gap between software execution and SOC visibility.

---

## 🌍 Community & Leadership

*   **Secretary** | *Rotaract Club of Hyderabad HimayathNagar*
    *   Executing administrative operations, coordinating club initiatives, and managing cross-team workflows.
*   **Global Top 1%** | *TryHackMe*
    *   Continuous validation of offensive security mechanics and exploit methodologies.

---

## 🤝 Comms Protocol

I actively engage with engineers and analysts focused on secure Java architecture, threat telemetry, and application security. 

📧 abdulfaisal001@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/abdulfaisal1)  
🌐 [Portfolio / Live Projects](https://f57.vercel.app/)
