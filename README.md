# 🛡️ Cisco SDSI — Designing Cisco Security Infrastructure | Study & Summary Notes

[![Exam](https://img.shields.io/badge/Exam-300--745%20SDSI-1BA0D7?logo=cisco&logoColor=white)](https://www.cisco.com/site/us/en/learn/training-certifications/exams/sdsi.html)
[![Version](https://img.shields.io/badge/Blueprint-v1.0-005073)](https://learningcontent.cisco.com/documents/marketing/exam-topics/300-745-SDSI-v1.0-Public.pdf)
[![Certification](https://img.shields.io/badge/Cert-CCNP%20Security%20Concentration-049fd9?logo=cisco&logoColor=white)](https://www.cisco.com/site/us/en/learn/training-certifications/certifications/security/ccnp-security/index.html)
[![Cisco U](https://img.shields.io/badge/Course-Cisco%20U.-1BA0D7?logo=cisco&logoColor=white)](https://u.cisco.com/paths/designing-cisco-security-infrastructure-20534)
[![Blog](https://img.shields.io/badge/📖%20Blog-Read%20the%20Write--up-FF6C37)](https://blog.safeqbit.com/a-walk-through-cisco-sdsi-and-where-network-security-is-headed-in-2026/)
[![License](https://img.shields.io/badge/License-CC%20BY--4.0-lightgrey)](#-license)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](#-contributing)
[![Buy me a coffee](https://img.shields.io/badge/Buy%20me%20a%20coffee-FFDD00?logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/fqazzazee)

> 📚 Personal study guide and condensed summary notes for the **Cisco Certified Specialist – Designing Cisco Security Infrastructure (SDSI)** certification, based on the official [Cisco U. learning path](https://u.cisco.com/paths/designing-cisco-security-infrastructure-20534).
>
> The **300-745 SDSI** exam is architecture-focused — it tests *design decisions* across infrastructure, applications, risk, and automation rather than device-level CLI configuration.

---

## 📋 Table of Contents

- [About the Certification](#-about-the-certification)
- [Exam Blueprint at a Glance](#-exam-blueprint-at-a-glance)
- [Study Notes by Module](#-study-notes-by-module)
- [Blueprint → Notes Mapping](#-blueprint--notes-mapping)
- [How to Use These Notes](#-how-to-use-these-notes)
- [Official Cisco Resources](#-official-cisco-resources)
- [Additional Reading](#-additional-reading)
- [Contributing](#-contributing)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🎯 About the Certification

| | |
|---|---|
| 🪪 **Exam code** | **300-745 SDSI** |
| 📦 **Title** | Designing Cisco Security Infrastructure v1.0 |
| ⏱️ **Duration** | 90 minutes |
| 🏆 **Earns** | Cisco Certified Specialist – Designing Cisco Security Infrastructure |
| 🎓 **Counts toward** | **CCNP Security** (concentration exam) |
| 👥 **Audience** | Security architects, senior network/security engineers, consultants designing end-to-end security solutions |
| 🧭 **Focus** | Architectural decisions across infrastructure, applications, risk management, AI & automation |

The SDSI exam validates your ability to **design** security architectures: selecting the right controls, segmentation strategies, firewall placements, identity models, risk frameworks, and DevSecOps practices for real-world business and technical requirements.

> 🔗 Official exam page: **[cisco.com — SDSI](https://www.cisco.com/site/us/en/learn/training-certifications/exams/sdsi.html)**
> 📄 Official blueprint (PDF): **[300-745 SDSI v1.0 Exam Topics](https://learningcontent.cisco.com/documents/marketing/exam-topics/300-745-SDSI-v1.0-Public.pdf)**

---

## 📊 Exam Blueprint at a Glance

| # | Domain | Weight |
|:-:|--------|:------:|
| 1 | 🏗️ **Secure Infrastructure** | **30%** |
| 2 | 🧩 **Security for Applications** | **25%** |
| 3 | ⚠️ **Risk, Events, and Requirements** | **30%** |
| 4 | 🤖 **Artificial Intelligence, Automation, and DevSecOps** | **15%** |

```text
Secure Infrastructure          ██████████████████████████████  30%
Applications                   █████████████████████████       25%
Risk, Events & Requirements    ██████████████████████████████  30%
AI, Automation & DevSecOps     ███████████████                 15%
```

> ⚖️ **Takeaway:** Infrastructure and Risk dominate (60% combined). Don't under-invest in the Risk/SOC/incident-response domain — it carries the same weight as core infrastructure.

---

## 📝 Study Notes by Module

Each file contains page-level summaries plus subsection notes drawn from the Cisco U. course, including the hands-on **Design Practice Activities**.

| Module | Notes | Primary Blueprint Domain |
|:------:|-------|--------------------------|
| 01 | 🏛️ [Security Architecture Design Fundamentals](./01-security-architecture-design-fundamentals.md) | Secure Infrastructure |
| 02 | 🔐 [Security Architecture for Infrastructure Protection](./02-security-architecture-for-infrastructure-protection.md) | Secure Infrastructure |
| 03 | 🧱 [Firewall Technologies & Advanced Security Solutions](./03-firewall-technologies-and-advanced-security-solutions.md) | Secure Infrastructure / Applications |
| 04 | 🧩 [Application Security & Secure Data Flow](./04-application-security-and-secure-data-flow.md) | Security for Applications |
| 05 | ⚠️ [Risk Management & Incident Response Strategies](./05-risk-management-and-incident-response-strategies.md) | Risk, Events, and Requirements |
| 06 | 🤖 [DevSecOps Integration & Automated Security Pipelines](./06-devsecops-integration-and-automated-security-pipelines.md) | AI, Automation, and DevSecOps |

<details>
<summary>📖 <strong>What's inside each module</strong> (click to expand)</summary>

### 🏛️ 01 — Security Architecture Design Fundamentals
Definition & purpose of security architecture · components and layers (physical, network, application, data) · core technologies (firewalls, VPNs, IDS/IPS, IAM) · design principles: **least privilege, Zero Trust, defense-in-depth, security by design, visibility & observability** · 4 layered-design case studies.

### 🔐 02 — Security Architecture for Infrastructure Protection
Endpoint & client security · **IAM, 2FA & Cisco Duo, passwordless authentication** · email security · designs for **hybrid workers, IoT, SaaS, multi-cloud & data centers** · network access security (802.1X) · IoT smart-hospital, secure SaaS, and resilient multi-cloud design activities.

### 🧱 03 — Firewall Technologies & Advanced Security Solutions
Traditional firewalls vs **NGFW** · NGFW advanced features · firewalls in SaaS / multi-cloud / data center · **WAF & WAAP with CDNs** · **IDS/IPS** key features, deployment & best practices · financial data center, hybrid workforce, and OT IDS/IPS design activities.

### 🧩 04 — Application Security & Secure Data Flow
Application firewalls · **SSL offloading & decryption** · **DLP** · endpoint security in app flows · **DNS security** · cloud-native apps, **microservices, containers/Kubernetes, serverless** segmentation & microsegmentation · emerging tech: **generative AI/ML & quantum computing** impacts.

### ⚠️ 05 — Risk Management & Incident Response Strategies
SOC tooling: **SIEM, SOAR, network observability, eBPF** · risk management frameworks · **compensating controls** · **Cisco SAFE framework** · post-incident response & recovery · APT, DDoS, ransomware, and insider-breach recovery design activities.

### 🤖 06 — DevSecOps Integration & Automated Security Pipelines
**CI/CD pipeline security** · automated vulnerability scanning · **API security** · automated security testing for continuous compliance · integrating **AI/ML into DevSecOps** · 10 "Security Design with AI" tasks (threat modeling, secure code review, red-team scenarios, privacy by design, IR simulation, and more).

</details>

---

## 🗺️ Blueprint → Notes Mapping

Use this to study by exam domain and target your weak areas:

| Blueprint Domain (Weight) | Covered in |
|---------------------------|------------|
| 🏗️ **Secure Infrastructure (30%)** | [Module 01](./01-security-architecture-design-fundamentals.md) · [Module 02](./02-security-architecture-for-infrastructure-protection.md) · [Module 03](./03-firewall-technologies-and-advanced-security-solutions.md) |
| 🧩 **Security for Applications (25%)** | [Module 03](./03-firewall-technologies-and-advanced-security-solutions.md) · [Module 04](./04-application-security-and-secure-data-flow.md) |
| ⚠️ **Risk, Events, and Requirements (30%)** | [Module 05](./05-risk-management-and-incident-response-strategies.md) |
| 🤖 **AI, Automation, and DevSecOps (15%)** | [Module 06](./06-devsecops-integration-and-automated-security-pipelines.md) |

---

## 🧭 How to Use These Notes

1. ✅ **Start with the [official blueprint](https://learningcontent.cisco.com/documents/marketing/exam-topics/300-745-SDSI-v1.0-Public.pdf)** — it's the source of truth for what's testable.
2. 📺 **Watch the [Cisco U. learning path](https://u.cisco.com/paths/designing-cisco-security-infrastructure-20534)** module by module.
3. 📝 **Read the matching note file here** to reinforce and quickly review each lesson.
4. 🧠 **Work the Design Practice Activities** — SDSI is scenario/design-driven, so practice *justifying* architecture choices, not memorizing commands.
5. 🔁 **Revise by domain** using the [Blueprint → Notes Mapping](#-blueprint--notes-mapping), prioritizing the 30% domains.

> 💡 These are **summary notes**, not a replacement for the official course. They're meant to accelerate review and retention.

---

## 🔗 Official Cisco Resources

- 🎓 **Cisco U. Learning Path** — [Designing Cisco Security Infrastructure](https://u.cisco.com/paths/designing-cisco-security-infrastructure-20534)
- 🪪 **Exam Overview** — [SDSI 300-745](https://www.cisco.com/site/us/en/learn/training-certifications/exams/sdsi.html)
- 📄 **Exam Blueprint (PDF)** — [300-745 SDSI v1.0 Exam Topics](https://learningcontent.cisco.com/documents/marketing/exam-topics/300-745-SDSI-v1.0-Public.pdf)
- 📦 **CCNP Security – SDSI Bundle** — [Cisco U. Content Bundle](https://u.cisco.com/content-bundle/ccnp-security-sdsi-bundle-20626)
- 🏆 **CCNP Security Certification** — [Program overview](https://www.cisco.com/site/us/en/learn/training-certifications/certifications/security/ccnp-security/index.html)
- 🌐 **Cisco Learning Network** — [Community & study groups](https://learningnetwork.cisco.com/)
- 🛡️ **Cisco SAFE** — [Security reference architecture](https://www.cisco.com/c/en/us/solutions/enterprise/design-zone-security/landing_safe.html)

---

## 📰 Additional Reading

- ✍️ [**A Walk Through Cisco SDSI (and Where Network Security Is Headed in 2026)**](https://blog.safeqbit.com/a-walk-through-cisco-sdsi-and-where-network-security-is-headed-in-2026/) — my published write-up on the SDSI course and how it maps to 2026 network security trends. _(Draft also in this repo: [blog-article-sdsi.md](./blog-article-sdsi.md))_

---

## 🤝 Contributing

Found an error, or have a clearer way to explain a concept? Contributions are welcome:

1. 🍴 Fork the repo
2. 🌿 Create a branch (`git checkout -b improve/module-04-notes`)
3. 💾 Commit your changes
4. 🔀 Open a Pull Request

Please keep notes concise, accurate, and aligned to the official blueprint. Don't post copyrighted Cisco course content verbatim — summarize in your own words.

---

## ⚠️ Disclaimer

These are **independent, personal study notes** and are **not affiliated with, endorsed by, or sponsored by Cisco Systems, Inc.** *Cisco*, *Cisco U.*, *CCNP*, *SDSI*, *SAFE*, and *Duo* are trademarks or registered trademarks of Cisco Systems, Inc. All product names and trademarks are the property of their respective owners. Always refer to the [official Cisco exam blueprint](https://learningcontent.cisco.com/documents/marketing/exam-topics/300-745-SDSI-v1.0-Public.pdf) as the authoritative source.

---

## 📄 License

The **notes and original written content** in this repository are released under the
[**Creative Commons Attribution 4.0 International (CC BY 4.0)**](https://creativecommons.org/licenses/by/4.0/) license.
Cisco trademarks and any referenced official materials remain the property of Cisco Systems, Inc.

---

<div align="center">

⭐ **If these notes help your SDSI prep, consider starring the repo!** ⭐

☕ If they helped you pass, you can [buy me a coffee](https://buymeacoffee.com/fqazzazee).

Made with ☕ and 🛡️ while studying for **CCNP Security**

</div>
