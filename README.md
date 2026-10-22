# Aditya Security Labs

<div align="center">

[![Website](https://img.shields.io/badge/Website-adityasecuritylabs.tech-059669?style=for-the-badge&logo=google-chrome&logoColor=white)](https://adityasecuritylabs.tech/)
[![Research CVEs](https://img.shields.io/badge/Research-CVE%20Records-ef4444?style=for-the-badge&logo=cve&logoColor=white)](https://nvd.nist.gov/)
[![GitHub](https://img.shields.io/badge/GitHub-sivaadityacoder-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sivaadityacoder)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Siva%20Aditya-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sivaaditya-panuganti-b67484316/)
[![Discord](https://img.shields.io/badge/Discord-Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/ctZBaVQG)

**Independent Cybersecurity Research · Application Security · AI Security · Open-Source Security**

*Web & API Security · AI/LLM Infrastructure · Android Security · Software Supply Chain Security*

</div>

---

## About Aditya Security Labs

[**Aditya Security Labs (ASL)**](https://adityasecuritylabs.tech/) is an independent cybersecurity research and product-security initiative founded by **Siva Aditya Panuganti**, with **Ainavilli Swamy Ganesh** as co-founder. ASL focuses on vulnerability research, application security, open-source software security, AI and LLM security, mobile application security, and security tooling.

Our approach combines source-code review, analysis of application behaviour, controlled validation, proof-of-concept development, impact assessment, and responsible disclosure. The objective is to provide technically reproducible findings and practical remediation guidance—not just automated scan output.

### At a glance

- Independent security research and product-security initiative.
- Research associated with six public CVE records listed below.
- Experience with paid open-source security bounty programs, including NIIS/X-Road and Qdrant.
- Creator of **ASL V6**, an AI-security assessment and red-teaming project.
- Development of security research and vulnerability-testing workflows, including VulnHunt.
- Practical experience through vulnerability research, source-code analysis, and more than 90 hands-on cybersecurity labs.

> **Verification note:** CVE records, severity scores, acknowledgments, bounty details, project capabilities, and licensing should be checked against their linked official records or repositories. Descriptions in this README summarize the supplied project and research information; they are not a substitute for the vendor advisory or NVD record.

---

## Leadership

### Siva Aditya Panuganti — Founder & Security Researcher

Siva leads vulnerability research, source-code security analysis, application security, AI/LLM security research, and security-tool development at Aditya Security Labs.

**Focus areas**
- Vulnerability discovery and root-cause analysis
- Web application and API security
- Authentication, authorization, and access-control testing
- Source-code analysis and safe proof-of-concept development
- Python sandbox and AI-agent security research
- Open-source software security and coordinated vulnerability disclosure
- Security automation and technical vulnerability reporting

**Profiles:** [GitHub](https://github.com/sivaadityacoder) · [LinkedIn](https://www.linkedin.com/in/sivaaditya-panuganti-b67484316/) · [Aditya Security Labs](https://adityasecuritylabs.tech/)

### Ainavilli Swamy Ganesh — Co-Founder & Head of Security Engineering

Ainavilli focuses on mobile application security, defensive security engineering, threat analysis, and web application testing.

**Focus areas**
- Android application security and APK reverse engineering
- Java/Kotlin, Smali, and application-behaviour analysis
- Dynamic instrumentation using Frida and Objection
- IPC, exported components, intent handling, and local data-storage review
- Web application penetration testing and VAPT
- Blue-team security, SOC-related defensive practices, and fraud-exposure analysis
- Adversarial AI threat analysis

**Profile:** [LinkedIn](https://www.linkedin.com/in/ainavilli-swamy-ganesh-7870112a8/)

---

## Security Services & Research Pillars

### 1. Web & API Security

Security assessment and authorized testing for web applications and modern APIs, including REST, GraphQL, and gRPC.

- Business-logic flaws and race-condition analysis
- Broken Object-Level Authorization (BOLA), IDOR, and object-property authorization
- Authentication and session-management weaknesses
- SQL injection and other input-handling flaws
- Server-Side Request Forgery (SSRF)
- Insecure deserialization and unsafe execution paths
- API access-control and data-exposure testing
- Review against relevant OWASP Top 10 and OWASP API Security Top 10 guidance

### 2. AI, LLM & Agent Security

Security research for AI-powered applications, autonomous agents, retrieval-augmented generation (RAG) systems, and vector databases.

- AI framework and agent architecture review
- Prompt-injection and unsafe tool-use analysis
- Sandbox boundary and execution-control research
- RAG pipeline and vector-database security
- Secret exposure and sensitive-data handling
- Static analysis of potentially unsafe code paths
- Controlled runtime validation in isolated environments
- Threat modelling for AI application components

Research examples include the Flowise and AutoGPT CVE records listed in the research table below. Findings and their impact should be interpreted using the relevant official advisories.

### 3. Android Mobile Application Security

Mobile application security research led by co-founder Ainavilli Swamy Ganesh.

- APK inspection and reverse engineering
- Java, Kotlin, and Smali analysis
- Exported Activities, Services, Broadcast Receivers, and Content Providers
- Intent handling and inter-process communication (IPC)
- Dynamic instrumentation with Frida and Objection
- SSL/TLS configuration and certificate-pinning assessment where authorized
- Local storage, cryptographic implementation, and Android Keystore review
- Hardcoded secrets and sensitive-data exposure checks

### 4. Open-Source & Software Supply-Chain Security

Security review of open-source repositories, packages, dependencies, and software components.

- Source-code auditing and root-cause analysis
- Dependency and third-party component risk review
- Software Bill of Materials (SBOM) review
- Vulnerability reproduction and affected-version validation
- Minimal proof-of-concept development
- Coordinated vulnerability disclosure with maintainers
- Remediation recommendations and patch-oriented collaboration

---

## Selected CVE Research & Public Records

The following six CVE records are included in the supplied research profile. Use the linked NVD record for the authoritative description, affected versions, references, and severity information.

| CVE | Project / Product | Research summary | Official record |
|---|---|---|---|
| [CVE-2026-70383](https://nvd.nist.gov/vuln/detail/CVE-2026-70383) | DigiDoc4 Client | Path traversal / arbitrary file overwrite; CWE-22 is listed in the supplied research notes. | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-70383) |
| [CVE-2026-73484](https://nvd.nist.gov/vuln/detail/CVE-2026-73484) | Flowise | Python sandbox escape involving insufficient restrictions around native Pandas methods, as described in the supplied notes. | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-73484) |
| [CVE-2026-22038](https://nvd.nist.gov/vuln/detail/CVE-2026-22038) | AutoGPT Platform | Sensitive API keys and authentication secrets logged in plaintext in the Stagehand integration; CWE-532 is listed in the supplied notes. | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-22038) |
| [CVE-2025-68621](https://nvd.nist.gov/vuln/detail/CVE-2025-68621) | Trilium Notes | Timing side-channel affecting sync authentication, described in the supplied notes as potentially enabling HMAC recovery; CWE-208. | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2025-68621) |
| [CVE-2025-67146](https://nvd.nist.gov/vuln/detail/CVE-2025-67146) | GYM-MANAGEMENT-SYSTEM 1.0 | Multiple SQL injection issues; supplied notes describe potential data extraction, authentication bypass, and database modification. | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2025-67146) |
| [CVE-2025-67147](https://nvd.nist.gov/vuln/detail/CVE-2025-67147) | Gym-Management-System-PHP 1.0 | Multiple SQL injection issues; supplied notes describe potential data modification, deletion, authentication bypass, and privilege escalation. | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2025-67147) |

### Related vulnerability classes

- SQL injection
- Authentication and authorization weaknesses
- Broken access control
- Path traversal and arbitrary file overwrite
- Sandbox and execution-boundary weaknesses
- Sensitive information exposure through logs
- Timing side-channel vulnerabilities
- Web and API security flaws
- AI-agent and open-source software security

**Severity caution:** Do not infer or advertise a CVSS score from the vulnerability category alone. Confirm the score and vector in the official NVD record or vendor advisory before using it in proposals, reports, or marketing material.

---

## Research Milestones & Recognition

The supplied project notes describe the following milestones:

- **NIIS / X-Road:** Security research and a reported bounty related to the X-Road ecosystem. The supplied notes state that the issue was addressed in version 7.7.1; confirm the relevant advisory and version details before publication.
- **Qdrant:** Security research and a reported paid bounty relating to a high-severity finding. Consult the official advisory for the final impact and severity.
- **ASL V6:** Public release of an AI-security assessment and red-teaming project in 2026, according to the supplied notes.
- **Responsible disclosure:** Research communications and vulnerability reports shared with maintainers through the relevant disclosure channels.
- **BSI Germany:** An acknowledgment is mentioned in the supplied company notes. Add a direct official acknowledgment link here before presenting it as independently verified.

The lab also reports experience with paid OSS security bounty programs. Any public bounty totals, exact award amounts, CVSS scores, or claims of official recognition should be supported by a public acknowledgment, disclosure page, or permission to disclose.

---

## Featured Projects & Tooling

### [ASL V6 — AI Security Assessment & Red-Teaming](https://github.com/sivaadityacoder/asl-v6)

ASL V6 is an open-source project exploring security assessment for AI applications, LLM pipelines, and agent systems.

**Focus areas**
- AST-based source-code analysis
- Detection of AI frameworks and potentially unsafe code paths
- Static analysis for unsafe sinks and execution boundaries
- Docker-based isolated runtime validation
- Security automation and structured findings

The supplied project notes describe a goal of reducing noisy findings. Any specific performance figure, such as a percentage reduction in false positives, should be accompanied by reproducible benchmark results and methodology before being treated as a verified metric.

### VulnHunt

VulnHunt is a vulnerability-research and testing project intended to automate selected parts of the security workflow.

**Focus areas**
- Reconnaissance and attack-surface organization
- Vulnerability discovery and validation
- Controlled proof-of-concept workflows
- Technical report preparation
- Research workflow automation

Use VulnHunt only against systems you own or are explicitly authorized to assess.

### CVE Research Repositories

- [CVE-2025-67146 and CVE-2025-67147](https://github.com/sivaadityacoder/CVE-2025-67146-CVE-2025-67147)
- [CVE-2025-68621](https://github.com/sivaadityacoder/CVE-2025-68621)
- [CVE-2026-22038](https://github.com/sivaadityacoder/CVE-2026-22038)

---

## Security Assessment & Research Methodology

ASL's intended workflow emphasizes authorized scope, reproducibility, clear impact analysis, and responsible disclosure.

1. **Scope and authorization** — Confirm ownership or written permission, rules of engagement, test boundaries, and handling requirements.
2. **Attack-surface mapping** — Identify relevant application components, APIs, authentication flows, dependencies, and trust boundaries.
3. **Source and behaviour review** — Inspect relevant code and application behaviour; form a testable security hypothesis.
4. **Controlled validation** — Reproduce the suspected issue in a safe environment, minimizing access to sensitive data and operational impact.
5. **Impact assessment** — Establish realistic preconditions, affected versions, security boundaries crossed, and limitations.
6. **Evidence and remediation** — Prepare a minimal proof of concept, clear reproduction steps, and practical mitigation guidance.
7. **Responsible disclosure** — Follow the vendor's policy, coordinate timelines appropriately, and share only authorized information.
8. **Retest** — Where permitted, verify the fix and document any remaining risk.

```text
Authorized scope
      ↓
Attack-surface mapping
      ↓
Source-code and behaviour review
      ↓
Hypothesis and safe reproduction
      ↓
Impact validation
      ↓
Technical report and remediation
      ↓
Coordinated disclosure and retesting
```

ASL does not endorse unauthorized access, data theft, destructive testing, or activity outside the agreed scope.

---

## Technical Skills & Tooling

| Domain | Skills and knowledge areas |
|---|---|
| Vulnerability research | Source-code review, root-cause analysis, safe PoCs, impact assessment, responsible disclosure |
| Web & API security | Authentication, authorization, BOLA/IDOR, SQL injection, XSS, SSRF, business-logic flaws, OWASP guidance |
| AI & LLM security | Agent threat modelling, prompt injection, RAG security, sandbox boundaries, vector-database security |
| Android security | APK analysis, Java/Kotlin/Smali, IPC review, Frida, Objection, local-storage review |
| Security tools | Burp Suite, Nmap, Nuclei, Metasploit, Wireshark, Docker |
| Programming and scripting | Python, Bash, PowerShell, JavaScript, SQL; Java/Kotlin in the context of Android research |
| Systems and workflow | Linux, Windows, Git, GitHub, Docker |
| Frameworks | OWASP Top 10, OWASP API Security Top 10, MITRE ATT&CK, MITRE ATLAS |

These skills reflect a combination of independent projects, hands-on labs, security research, and continued practical learning.

---

## Engagement Models

Potential engagement models for organizations and maintainers include:

1. **Application / API security assessment** — Scoped review of application behaviour, authorization, input handling, and common high-impact vulnerability classes.
2. **Source-code security review** — Manual review supported by static-analysis techniques, with findings prioritized by evidence and realistic impact.
3. **AI / LLM security assessment** — Threat modelling and authorized testing of AI application boundaries, agent tools, RAG pipelines, and sensitive-data handling.
4. **Open-source security collaboration** — Repository review, reproducible reports, responsible disclosure, and remediation-oriented collaboration.
5. **Retesting and remediation support** — Follow-up validation of agreed fixes and documentation of residual risk.

Scope, schedule, deliverables, confidentiality, data handling, and pricing should be agreed in writing before any assessment begins. Any stated delivery window depends on scope and availability and should be confirmed in the engagement agreement.

---

## Governance, Confidentiality & Privacy

Security work should be conducted under written authorization and clear rules of engagement.

- Agree the scope and permitted test methods before testing begins.
- Use an NDA or confidentiality agreement where appropriate and mutually agreed.
- Define how source code, credentials, logs, and evidence will be accessed, stored, transferred, and deleted.
- Minimize collection of personal or production data.
- Set retention and deletion expectations in the engagement agreement.
- Handle trade secrets and client information according to applicable agreements and laws.
- Align assessment criteria with relevant standards and regulations when applicable.

References to **Directive (EU) 2016/943** or the **EU AI Act** are not, by themselves, a certification or guarantee of compliance. A formal compliance assessment requires a defined scope, applicable legal analysis, and supporting evidence. Avoid describing a service as legally compliant or certified unless that claim has been independently established.

---

## Opportunities

Siva is interested in internship, junior, research, and collaborative opportunities in:

- Application security and product security
- Vulnerability research and exploit analysis
- Penetration testing / VAPT for web, API, and mobile applications
- Open-source software security
- AI / LLM security and red-teaming
- Security engineering and security consulting

ASL is also interested in working with engineering teams, open-source maintainers, and organizations that value clear technical reporting, responsible disclosure, and remediation-focused security research.

---

## Contact & Connect

### Aditya Security Labs

- **Website:** [adityasecuritylabs.tech](https://adityasecuritylabs.tech/)
- **Email:** [adityasecuritylabs@gmail.com](mailto:adityasecuritylabs@gmail.com)
- **WhatsApp:** [+91 93910 92669](https://wa.me/919391092669?text=Hello%20Aditya%20Security%20Labs%2C%20I%20would%20like%20to%20inquire%20about%20a%20security%20audit)
- **Discord:** [Join the community](https://discord.gg/ctZBaVQG)
- **GitHub:** [github.com/sivaadityacoder](https://github.com/sivaadityacoder)

### Leadership

- **Siva Aditya Panuganti:** [LinkedIn](https://www.linkedin.com/in/sivaaditya-panuganti-b67484316/) · [GitHub](https://github.com/sivaadityacoder)
- **Ainavilli Swamy Ganesh:** [LinkedIn](https://www.linkedin.com/in/ainavilli-swamy-ganesh-7870112a8/)

### Verification References

- [NVD — CVE-2026-70383](https://nvd.nist.gov/vuln/detail/CVE-2026-70383)
- [NVD — CVE-2026-73484](https://nvd.nist.gov/vuln/detail/CVE-2026-73484)
- [NVD — CVE-2026-22038](https://nvd.nist.gov/vuln/detail/CVE-2026-22038)
- [NVD — CVE-2025-68621](https://nvd.nist.gov/vuln/detail/CVE-2025-68621)
- [NVD — CVE-2025-67146](https://nvd.nist.gov/vuln/detail/CVE-2025-67146)
- [NVD — CVE-2025-67147](https://nvd.nist.gov/vuln/detail/CVE-2025-67147)

---

<div align="center">

*Aditya Security Labs · Independent security research and responsible disclosure*

</div>
