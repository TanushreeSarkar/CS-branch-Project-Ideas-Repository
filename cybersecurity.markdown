# 🔒 Unique Cybersecurity Project Ideas 

Beyond the usual password checker / traffic analyzer / file encryptor set — these map to what security teams are actually hiring for: **SOC automation, zero trust, supply chain security, threat hunting, and DevSecOps**. 🔐

---

## 📋 Quick Reference Table

| # | Project | Tech Stack | Why It's Hireable |
|---|---------|-----------|-------------------|
| 1 | SOC Alert Triage Automation Bot | Python, SIEM API, LLM | SOC automation is the #1 security-hiring trend |
| 2 | Zero Trust Access Gateway | Open Policy Agent, Envoy | Zero trust is now the default enterprise security model |
| 3 | Phishing Simulation & Awareness Platform | Python, GoPhish API, Flask | Practical security-awareness tooling companies buy |
| 4 | Cloud Security Posture Scanner | Python, AWS Config, boto3 | CSPM is a fast-growing, well-paid niche |
| 5 | Container Image Vulnerability Pipeline | Trivy, Docker, GitHub Actions | Supply-chain security is now a hard requirement |
| 6 | Threat Intelligence Aggregator | Python, MISP, STIX/TAXII | Real threat-intel tooling used by SOC analysts |
| 7 | Malware Sandbox Analyzer | Cuckoo Sandbox, Python | Hands-on malware analysis, rare student-level skill |
| 8 | API Security Fuzzer | Python, OpenAPI parsing | API security is an underserved, high-demand niche |
| 9 | Honeypot Network for Attack Logging | Cowrie, ELK Stack | Real attacker-behavior data, great writeup material |
| 10 | Supply Chain SBOM Generator & Scanner | Syft, Grype | SBOMs are now a regulatory/compliance requirement |
| 11 | Zero-Day Exploit Pattern Classifier | Python, scikit-learn | ML-driven threat detection, cutting-edge signal |
| 12 | DevSecOps Pipeline (SAST/DAST) | GitHub Actions, Semgrep, OWASP ZAP | Shift-left security is standard in modern engineering orgs |
| 13 | Identity & Access Anomaly Detector | Python, CloudTrail, ML | IAM security is a top cloud-breach root cause |
| 14 | Zero-Knowledge Password Manager | Rust, AES-GCM, Argon2 | Applied cryptography done right, strong systems signal |
| 15 | Threat Hunting Query Library | Sigma rules, Elasticsearch | Real threat-hunting workflow used in SOCs |
| 16 | Ransomware Behavior Simulator (Sandboxed) | Python, isolated VM, YARA | Deep understanding of a top real-world threat |
| 17 | DNS Tunneling Detector | Python, Scapy, ML | Detects a classic, hard-to-spot exfiltration technique |
| 18 | Container Runtime Security Monitor | Falco, Kubernetes | Runtime security is the newest layer of cloud-native defense |
| 19 | Secure Multi-Factor Auth Service | Python, TOTP, WebAuthn | Modern passwordless auth implementation |
| 20 | Insider Threat Detection (UEBA) | Python, pandas, anomaly detection | Behavioral analytics is a growing enterprise-security niche |
| 21 | Automated Incident Response Playbook Engine | Python, SOAR-style workflows | SOAR skills reduce SOC response time — a big deal |
| 22 | API Key Leak Scanner for GitHub Repos | Python, regex, GitHub API | Solves a real, common, embarrassing security failure |
| 23 | End-to-End Encrypted File Transfer | Python, RSA/AES hybrid | Applied crypto with a genuinely useful output |
| 24 | Custom Web Application Firewall | Nginx/Lua, ModSecurity | Hands-on WAF rule-writing, real defensive skill |
| 25 | Blockchain-Based Audit Log System | Python, Merkle trees | Tamper-evident logging, a novel compliance angle |
| 26 | Social Engineering Awareness Chatbot Trainer | LLM, Flask | Creative use of AI for a real training gap |
| 27 | Network Segmentation Policy Validator | Python, NetworkX | Validates zero-trust segmentation, an enterprise need |
| 28 | AI-Assisted Secure Code Review Tool | LLM, Semgrep rules | AI + AppSec is an emerging, differentiated combo |
| 29 | Credential Stuffing Detection System | Python, Redis, rate analysis | Directly addresses one of the top account-takeover vectors |
| 30 | IoT Device Security Scanner | Python, Nmap, CVE database | IoT security is a fast-growing, understaffed field |
| 31 | Encrypted Messaging App (Forward Secrecy) | Signal Protocol, Python | Implements real production-grade crypto protocols |
| 32 | Automated Firewall Rule Auditor | Python, iptables parsing | Practical, immediately useful sysadmin/security tool |
| 33 | Dark Web Monitoring Tool | Python, Tor, keyword scraping | Threat-intel gathering with real OSINT technique |
| 34 | Security Awareness Gamification Platform | React, Flask | Makes a boring compliance requirement engaging |
| 35 | Kubernetes RBAC Auditor | Python, kube-api, Rego | Cloud-native access control auditing, in-demand skill |
| 36 | Digital Forensics Timeline Builder | Python, Volatility, Autopsy | DFIR skills are highly specialized and well-paid |
| 37 | Certificate & TLS Config Scanner | Python, SSL/TLS libraries | Prevents a very common, very costly outage/breach cause |
| 38 | Automated Pen-Test Report Generator | Python, LLM summarization | Saves pentesters hours of repetitive report writing |
| 39 | Secure Multi-Party Computation Demo | Python, PySyft | Cutting-edge privacy-preserving crypto technique |
| 40 | Bot Traffic Detection for Web Apps | Python, ML, behavioral fingerprinting | Directly ties to fraud prevention and ad-fraud teams |
| 41 | Risk-Based Vulnerability Prioritization Engine | Python, CVSS + EPSS scoring | Solves real "which CVE do I patch first" problem |
| 42 | CIS Benchmark Compliance Checker | Python, Ansible | Automates a real, tedious compliance audit process |
| 43 | GDPR/PII Data Discovery Scanner | Python, regex + NER | Privacy compliance tooling, regulator-relevant |
| 44 | Encrypted Backup & DR Tool | Python, AES, cloud storage | Combines crypto with practical business continuity |
| 45 | Behavioral Biometric Authentication | Python, keystroke dynamics, ML | Novel, differentiated continuous-auth approach |
| 46 | Automated Red Team Recon Tool | Python, Shodan API, OSINT | Real offensive-security reconnaissance automation |
| 47 | Secure DNS Resolver with Filtering | Python, DNS-over-HTTPS | Privacy + security combined at the network layer |
| 48 | Log Tampering Detection (Hash Chains) | Python, cryptographic hashing | Tamper-evidence is a real forensic/compliance need |
| 49 | Smart Contract Security Auditor | Slither, Python | Web3 security is a niche but well-paid specialty |
| 50 | Adaptive MFA Risk Engine | Python, ML, contextual signals | Modern risk-based auth used by major identity providers |

---

## 📖 Detailed Breakdown

### 1. SOC Alert Triage Automation Bot 🤖
- **Description**: Ingest raw SIEM alerts, use an LLM to summarize and classify severity, and auto-close known false positives.
- **Tech Stack**: Python, SIEM API (Splunk/Elastic), LLM API
- **Why It's Cool**: Tackles the #1 SOC analyst pain point — alert fatigue — head-on.
- **Hiring Appeal**: SOC automation is the single most requested skill in current security job listings.

### 2. Zero Trust Access Gateway 🚪
- **Description**: Build a policy-enforcement layer that checks identity, device posture, and context before granting access to any resource.
- **Tech Stack**: Open Policy Agent (OPA), Envoy proxy
- **Why It's Cool**: Implements "never trust, always verify" as actual working code, not a slide.
- **Hiring Appeal**: Zero trust is now the default architecture enterprises are migrating toward.

### 3. Phishing Simulation & Awareness Platform 🎣
- **Description**: Run controlled phishing campaigns against a test user group and track click/report rates with a dashboard.
- **Tech Stack**: Python, GoPhish API, Flask
- **Why It's Cool**: A real tool security teams pay licenses for — you're building the alternative.
- **Hiring Appeal**: Security-awareness tooling is a concrete, demoable enterprise product category.

### 4. Cloud Security Posture Scanner ☁️
- **Description**: Scan an AWS account for common misconfigurations (public buckets, over-permissive IAM roles) and score the posture.
- **Tech Stack**: Python, AWS Config, boto3
- **Why It's Cool**: You'll likely find real misconfigurations, even in a test account.
- **Hiring Appeal**: Cloud Security Posture Management (CSPM) is one of the fastest-growing security niches.

### 5. Container Image Vulnerability Pipeline 🐳
- **Description**: Automatically scan every Docker image built in CI and block the pipeline if critical CVEs are found.
- **Tech Stack**: Trivy, Docker, GitHub Actions
- **Why It's Cool**: Shifts vulnerability discovery left, before deployment instead of after.
- **Hiring Appeal**: Supply-chain security is now a hard compliance requirement in most orgs.

### 6. Threat Intelligence Aggregator 🕵️
- **Description**: Pull indicators of compromise from multiple open threat-intel feeds and normalize them into one queryable database.
- **Tech Stack**: Python, MISP, STIX/TAXII
- **Why It's Cool**: This is the exact tooling real SOC analysts use daily.
- **Hiring Appeal**: Threat-intel platform familiarity is a strong SOC/analyst interview signal.

### 7. Malware Sandbox Analyzer 🧫
- **Description**: Detonate suspicious binaries in an isolated sandbox and generate a behavioral report (file/network/registry activity).
- **Tech Stack**: Cuckoo Sandbox, Python
- **Why It's Cool**: Hands-on malware analysis is rarely attempted at the student level.
- **Hiring Appeal**: Malware analysis skills are specialized, respected, and hard to fake in an interview.

### 8. API Security Fuzzer 🧨
- **Description**: Automatically generate malformed and edge-case requests from an OpenAPI spec to find broken auth or injection flaws.
- **Tech Stack**: Python, OpenAPI/Swagger parsing
- **Why It's Cool**: Finds real bugs, not just theoretical vulnerability classes.
- **Hiring Appeal**: API security is one of the most under-tooled, high-demand niches right now.

### 9. Honeypot Network for Attack Logging 🍯
- **Description**: Deploy fake vulnerable services on the public internet and log every attack attempt for pattern analysis.
- **Tech Stack**: Cowrie (SSH honeypot), ELK Stack
- **Why It's Cool**: You'll collect real attacker data within hours of deployment.
- **Hiring Appeal**: Gives you genuine threat data to discuss in interviews, not synthetic examples.

### 10. Supply Chain SBOM Generator & Scanner 📦
- **Description**: Generate a Software Bill of Materials for a codebase and cross-reference it against known vulnerability databases.
- **Tech Stack**: Syft (SBOM generation), Grype (vulnerability scanning)
- **Why It's Cool**: SBOMs went from niche to regulatory requirement (US Executive Order 14028) almost overnight.
- **Hiring Appeal**: Supply-chain transparency tooling is now expected in regulated industries.

### 11. Zero-Day Exploit Pattern Classifier 🎯
- **Description**: Train a model to flag anomalous system-call sequences that resemble unknown exploit behavior.
- **Tech Stack**: Python, scikit-learn, syscall tracing
- **Why It's Cool**: Goes beyond signature-based detection into behavioral anomaly territory.
- **Hiring Appeal**: ML-driven detection is where enterprise security vendors are investing heavily.

### 12. DevSecOps Pipeline with SAST/DAST 🔧
- **Description**: Wire static and dynamic security scanning directly into a CI/CD pipeline with pass/fail gates.
- **Tech Stack**: GitHub Actions, Semgrep, OWASP ZAP
- **Why It's Cool**: Security becomes a pipeline step, not a pre-launch afterthought.
- **Hiring Appeal**: "Shift-left security" is now table stakes at any modern engineering org.

### 13. Identity & Access Anomaly Detector 👤
- **Description**: Analyze cloud IAM logs to flag unusual login locations, privilege escalations, or off-hours access.
- **Tech Stack**: Python, AWS CloudTrail, anomaly detection
- **Why It's Cool**: IAM compromise is consistently the root cause of major cloud breaches.
- **Hiring Appeal**: Identity security is one of the highest-priority hiring areas in cloud security.

### 14. Zero-Knowledge Password Manager 🔐
- **Description**: Build a password manager where the server never sees plaintext passwords or the master key.
- **Tech Stack**: Rust, AES-GCM, Argon2 key derivation
- **Why It's Cool**: Applied cryptography done properly is a genuinely hard systems problem.
- **Hiring Appeal**: Demonstrates real crypto implementation skill, not just "I used a library."

### 15. Threat Hunting Query Library 🏹
- **Description**: Build a searchable library of detection queries (Sigma rules) mapped to MITRE ATT&CK techniques, queryable against live logs.
- **Tech Stack**: Sigma rules, Elasticsearch, MITRE ATT&CK mapping
- **Why It's Cool**: Mirrors exactly how professional threat hunters organize their work.
- **Hiring Appeal**: MITRE ATT&CK fluency is a near-universal SOC/threat-hunter interview expectation.

### 16. Ransomware Behavior Simulator (Sandboxed) 🦠
- **Description**: In a fully isolated VM, simulate ransomware-like file encryption behavior to test detection tooling.
- **Tech Stack**: Python, isolated VM, YARA rules
- **Why It's Cool**: Deep, hands-on understanding of the top real-world enterprise threat.
- **Hiring Appeal**: Shows you understand attacker TTPs well enough to simulate them safely.

### 17. DNS Tunneling Detector 🌐
- **Description**: Detect covert data exfiltration hidden inside DNS query patterns using statistical and ML features.
- **Tech Stack**: Python, Scapy, ML classifier
- **Why It's Cool**: DNS tunneling is a classic, hard-to-spot technique — detecting it is genuinely impressive.
- **Hiring Appeal**: Network security teams specifically look for candidates who understand this attack vector.

### 18. Container Runtime Security Monitor 🐋
- **Description**: Detect anomalous behavior inside running containers (unexpected process spawns, file writes) in real time.
- **Tech Stack**: Falco, Kubernetes
- **Why It's Cool**: Runtime security is the newest, least-saturated layer of cloud-native defense.
- **Hiring Appeal**: Container/K8s security is a rapidly growing specialization within cloud security.

### 19. Secure Multi-Factor Auth Service 🔢
- **Description**: Implement a standalone MFA service supporting TOTP and WebAuthn/passkeys for any app to plug into.
- **Tech Stack**: Python, TOTP (pyotp), WebAuthn
- **Why It's Cool**: Passkeys/WebAuthn are the modern passwordless standard — implementing it yourself is rare.
- **Hiring Appeal**: Demonstrates hands-on understanding of the auth methods replacing passwords industry-wide.

### 20. Insider Threat Detection (UEBA) 👁️
- **Description**: Build a User and Entity Behavior Analytics system that flags employees deviating from their normal access patterns.
- **Tech Stack**: Python, pandas, anomaly detection (Isolation Forest)
- **Why It's Cool**: Insider threats are notoriously harder to detect than external attacks.
- **Hiring Appeal**: UEBA is a growing enterprise-security investment area with real budget behind it.

### 21. Automated Incident Response Playbook Engine 📋
- **Description**: Build a SOAR-style engine that automatically executes response steps (isolate host, revoke token) when a specific alert fires.
- **Tech Stack**: Python, SOAR-style workflow engine, webhook integrations
- **Why It's Cool**: Cuts incident response time from hours to seconds for known alert types.
- **Hiring Appeal**: SOAR platform experience directly reduces SOC operational costs — a strong business pitch.

### 22. API Key Leak Scanner for GitHub Repos 🔑
- **Description**: Scan public (or your own) repos for accidentally committed API keys, tokens, and credentials.
- **Tech Stack**: Python, regex pattern matching, GitHub API
- **Why It's Cool**: You'll almost certainly find real leaked secrets when you run this at scale.
- **Hiring Appeal**: Secret-leak detection is a genuinely common, embarrassing, and costly failure mode companies fear.

### 23. End-to-End Encrypted File Transfer 📤
- **Description**: Build a file-sharing tool where files are encrypted client-side before upload, so the server never sees plaintext.
- **Tech Stack**: Python, RSA/AES hybrid encryption
- **Why It's Cool**: Applied crypto with a genuinely useful, shippable output.
- **Hiring Appeal**: Shows you can implement encryption correctly — a common area where junior devs make mistakes.

### 24. Custom Web Application Firewall 🧱
- **Description**: Write custom WAF rules to detect and block SQL injection, XSS, and path traversal attempts in real time.
- **Tech Stack**: Nginx + Lua, ModSecurity
- **Why It's Cool**: You write the actual defensive rules instead of just configuring a vendor product.
- **Hiring Appeal**: Hands-on WAF rule authorship is a real, demonstrable AppSec skill.

### 25. Blockchain-Based Audit Log System ⛓️
- **Description**: Build a tamper-evident logging system using hash chaining, so any log modification is instantly detectable.
- **Tech Stack**: Python, Merkle trees, cryptographic hashing
- **Why It's Cool**: A novel, technically interesting application of blockchain concepts outside of crypto-coins.
- **Hiring Appeal**: Tamper-evident logging is directly relevant to compliance and forensic-readiness needs.

### 26. Social Engineering Awareness Chatbot Trainer 🎭
- **Description**: An LLM-powered chatbot that role-plays common social engineering scenarios so employees can practice spotting them.
- **Tech Stack**: LLM API, Flask
- **Why It's Cool**: A creative, interactive answer to a training problem usually solved with boring slide decks.
- **Hiring Appeal**: Combines AI skills with a real security-awareness gap companies want solved.

### 27. Network Segmentation Policy Validator 🗺️
- **Description**: Model a network's segmentation rules as a graph and validate that no path violates zero-trust policy.
- **Tech Stack**: Python, NetworkX
- **Why It's Cool**: Turns firewall-rule spaghetti into a queryable, provable model.
- **Hiring Appeal**: Validates real zero-trust segmentation — a top enterprise architecture requirement.

### 28. AI-Assisted Secure Code Review Tool 🤖
- **Description**: Combine static analysis findings with an LLM that explains the vulnerability and suggests a concrete fix.
- **Tech Stack**: LLM API, Semgrep custom rules
- **Why It's Cool**: Pairs deterministic scanning with generative explanation — best of both worlds.
- **Hiring Appeal**: AI + AppSec is an emerging combo few candidates can currently speak to.

### 29. Credential Stuffing Detection System 🔓
- **Description**: Detect credential-stuffing attacks by analyzing login attempt patterns (velocity, IP reputation, device fingerprint).
- **Tech Stack**: Python, Redis (rate tracking), IP reputation APIs
- **Why It's Cool**: Directly addresses one of the top real-world account-takeover vectors.
- **Hiring Appeal**: Fraud/abuse prevention teams at any consumer platform need exactly this.

### 30. IoT Device Security Scanner 📡
- **Description**: Scan a local network for IoT devices and flag ones with default credentials, open ports, or known CVEs.
- **Tech Stack**: Python, Nmap, CVE database lookups
- **Why It's Cool**: IoT devices are notoriously under-secured — you'll find real issues on real networks.
- **Hiring Appeal**: IoT security is a fast-growing, understaffed field as smart devices proliferate.

### 31. Encrypted Messaging App with Forward Secrecy 💬
- **Description**: Implement a chat app using the Signal Protocol so that even a compromised key can't decrypt past messages.
- **Tech Stack**: Signal Protocol library, Python/JavaScript
- **Why It's Cool**: Implements the same cryptographic protocol behind Signal and WhatsApp.
- **Hiring Appeal**: Hands-on forward-secrecy implementation is a serious, respected applied-crypto project.

### 32. Automated Firewall Rule Auditor 🧯
- **Description**: Parse a firewall's ruleset and flag overly permissive, redundant, or shadowed rules.
- **Tech Stack**: Python, iptables/firewall config parsing
- **Why It's Cool**: A genuinely practical tool that sysadmins would actually use.
- **Hiring Appeal**: Shows understanding of network security fundamentals beyond app-layer concerns.

### 33. Dark Web Monitoring Tool 🕸️
- **Description**: Monitor dark web forums/marketplaces for mentions of a company's domain, leaked credentials, or brand.
- **Tech Stack**: Python, Tor, keyword scraping
- **Why It's Cool**: Real OSINT technique applied to a genuinely valuable business use case.
- **Hiring Appeal**: Brand/credential monitoring is a service companies pay third parties for — you're building it yourself.

### 34. Security Awareness Gamification Platform 🎮
- **Description**: Turn security training into a points-and-leaderboard game with phishing-spotting challenges.
- **Tech Stack**: React, Flask
- **Why It's Cool**: Makes a compliance checkbox item genuinely engaging.
- **Hiring Appeal**: Human-factor security is finally getting real budget and attention.

### 35. Kubernetes RBAC Auditor 🔍
- **Description**: Scan a cluster's role bindings and flag overly broad permissions that violate least-privilege.
- **Tech Stack**: Python, Kubernetes API, Rego (OPA policy language)
- **Why It's Cool**: RBAC misconfigurations are one of the most common Kubernetes security gaps.
- **Hiring Appeal**: Cloud-native access-control auditing is a specifically requested skill in K8s security roles.

### 36. Digital Forensics Timeline Builder 🕰️
- **Description**: Parse memory dumps and disk artifacts to reconstruct a chronological timeline of an incident.
- **Tech Stack**: Python, Volatility framework, Autopsy
- **Why It's Cool**: Real DFIR work — the kind used in actual incident post-mortems.
- **Hiring Appeal**: Digital forensics is a highly specialized, well-compensated security discipline.

### 37. Certificate & TLS Config Scanner 🔏
- **Description**: Scan a list of domains for expiring certificates, weak cipher suites, and misconfigured TLS settings.
- **Tech Stack**: Python, ssl/TLS libraries, SSL Labs-style scoring
- **Why It's Cool**: Prevents a surprisingly common, very costly cause of outages and breaches.
- **Hiring Appeal**: A concrete, easily explainable tool with clear business value.

### 38. Automated Pen-Test Report Generator 📝
- **Description**: Feed raw scan/exploit results into an LLM that drafts a structured, client-ready pentest report.
- **Tech Stack**: Python, LLM API for summarization
- **Why It's Cool**: Saves pentesters hours of the most tedious part of their job.
- **Hiring Appeal**: A practical AI application that offensive security consultancies would genuinely pay for.

### 39. Secure Multi-Party Computation Demo 🧮
- **Description**: Let two parties jointly compute a result (e.g., average salary) without either revealing their private input.
- **Tech Stack**: Python, PySyft or a custom MPC protocol
- **Why It's Cool**: A cutting-edge privacy-preserving cryptography technique, rarely implemented outside research.
- **Hiring Appeal**: Signals genuinely advanced cryptography understanding beyond typical AppSec work.

### 40. Bot Traffic Detection for Web Apps 🤖
- **Description**: Distinguish human from bot traffic using behavioral signals (mouse movement, timing, request patterns).
- **Tech Stack**: Python, ML classifier, behavioral fingerprinting
- **Why It's Cool**: A cat-and-mouse problem where attackers actively adapt against your detector.
- **Hiring Appeal**: Directly ties to fraud-prevention and ad-fraud teams, a well-funded security niche.

### 41. Risk-Based Vulnerability Prioritization Engine ⚠️
- **Description**: Combine CVSS severity with real-world exploit-likelihood (EPSS) scores to rank which vulnerabilities to patch first.
- **Tech Stack**: Python, CVSS + EPSS data feeds
- **Why It's Cool**: Solves the real problem of "we have 10,000 open CVEs, which 20 actually matter."
- **Hiring Appeal**: Risk-based patching is exactly how mature vulnerability-management programs operate.

### 42. CIS Benchmark Compliance Checker ✅
- **Description**: Automatically audit a server or cloud account against CIS hardening benchmarks and generate a compliance report.
- **Tech Stack**: Python, Ansible
- **Why It's Cool**: Automates a real, tedious, recurring audit task.
- **Hiring Appeal**: Compliance automation directly reduces audit prep time — an easy ROI story.

### 43. GDPR/PII Data Discovery Scanner 🕵️‍♂️
- **Description**: Scan databases and file stores to automatically locate personally identifiable information for compliance mapping.
- **Tech Stack**: Python, regex + Named Entity Recognition
- **Why It's Cool**: A genuinely hard problem — PII hides in unstructured text in unpredictable ways.
- **Hiring Appeal**: Privacy compliance tooling is regulator-relevant and increasingly mandated.

### 44. Encrypted Backup & Disaster Recovery Tool 💽
- **Description**: Build an automated backup tool that encrypts data client-side before pushing it to cloud storage.
- **Tech Stack**: Python, AES encryption, cloud storage SDKs
- **Why It's Cool**: Combines applied cryptography with a genuinely practical business-continuity use case.
- **Hiring Appeal**: Shows both crypto competence and operational/reliability thinking.

### 45. Behavioral Biometric Authentication ⌨️
- **Description**: Authenticate users continuously based on their unique typing rhythm, not just a one-time password check.
- **Tech Stack**: Python, keystroke dynamics analysis, ML
- **Why It's Cool**: A novel, differentiated approach to continuous authentication.
- **Hiring Appeal**: Behavioral biometrics is an emerging area some fintech/enterprise identity teams are exploring.

### 46. Automated Red Team Recon Tool 🎯
- **Description**: Automate OSINT reconnaissance (subdomains, exposed services, employee info) as the first phase of a red-team engagement.
- **Tech Stack**: Python, Shodan API, OSINT frameworks
- **Why It's Cool**: Real offensive-security tradecraft, automated and repeatable.
- **Hiring Appeal**: Strong signal for red-team/pentest roles where reconnaissance is a core, time-consuming skill.

### 47. Secure DNS Resolver with Filtering 🌐
- **Description**: Build a DNS-over-HTTPS resolver that blocks known malicious domains and logs query patterns privately.
- **Tech Stack**: Python, DNS-over-HTTPS (DoH)
- **Why It's Cool**: Combines network-layer security with privacy engineering in one tool.
- **Hiring Appeal**: Network security fundamentals paired with a modern privacy-conscious protocol.

### 48. Log Tampering Detection (Hash Chains) 🔗
- **Description**: Build a logging wrapper where each entry is cryptographically chained to the previous one, so tampering breaks the chain visibly.
- **Tech Stack**: Python, cryptographic hashing (SHA-256 chains)
- **Why It's Cool**: A simple idea that solves a genuinely important forensic-integrity problem.
- **Hiring Appeal**: Tamper-evidence is directly relevant to audit and compliance requirements.

### 49. Smart Contract Security Auditor ⛓️
- **Description**: Automatically scan Solidity smart contracts for reentrancy bugs, overflow issues, and common exploit patterns.
- **Tech Stack**: Slither (static analyzer), Python
- **Why It's Cool**: Smart contract bugs have led to hundreds of millions in real, irreversible losses.
- **Hiring Appeal**: Web3 security auditing is a niche but very well-paid specialty.

### 50. Adaptive MFA Risk Engine 🎚️
- **Description**: Build a risk-scoring engine that decides whether to prompt for MFA based on context (new device, unusual location, odd hour).
- **Tech Stack**: Python, ML risk scoring, contextual signals
- **Why It's Cool**: Balances security and user friction — the exact tradeoff major identity providers optimize for.
- **Hiring Appeal**: Risk-based/adaptive authentication is the modern standard replacing static MFA prompts.

---
