# DevSecOps Integration and Automated Security Pipelines

Source: Cisco U. Designing Cisco Security Infrastructure path. Assessments are excluded. These notes are paraphrased from the instructional pages and organized by lesson page plus actual subsection headings.

## Module Summary

This module contains 3 lessons. Each page below includes a page-level summary and subsection-level notes drawn from the headings and instructional content on that page.

## DevSecOps Integration

### Introduction

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** containers, DevSecOps, CI/CD, IaC, compliance, secrets.

### Continuous Integration/Continuous Delivery (CI/CD) Pipeline Security

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** Confidentiality, Integrity, Availability, IAM, least privilege, IDS, MFA, Kubernetes.

**Subsection notes**

- **Continuous Integration/Continuous Delivery (CI/CD) Pipeline Security:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: Confidentiality, Integrity, Availability, CI/CD, IaC, compliance, secrets. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Lifecycle Security Management:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: Confidentiality, Integrity, Availability, CI/CD. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **CI/CD Pipeline Security:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: least privilege, CI/CD, supply chain, secrets. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Importance of CI/CD Pipeline Security:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: Integrity, CI/CD, compliance, HIPAA, secrets. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Source Code Security:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: Integrity, MFA, audit, compliance, supply chain, RBAC. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Secrets Management:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: CI/CD, API, audit, compliance, secrets. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Dependency Management:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: CI/CD, OWASP, compliance, supply chain. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **IaC Security:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: IAM, least privilege, CI/CD, IaC, compliance, secrets, policy-as-code. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Container Security:** Summarizes cloud-native security: service isolation, workload identity, network policy, image security, secrets, RBAC, runtime monitoring, and supply-chain protection. Key terms: Integrity, least privilege, Kubernetes, containers, CI/CD, RBAC. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Continuous Monitoring and Incident Response:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: IDS, DevSecOps, SIEM, observability, telemetry. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Infrastructure Security Policy Design for CI/CD:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: Integrity, IAM, least privilege, MFA, Kubernetes, CI/CD, SIEM, NIST. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Automated Vulnerability Scanning

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** endpoint, CI/CD, TLS, SSL, SIEM, NIST, compliance, HIPAA.

**Subsection notes**

- **Automated Vulnerability Scanning:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: endpoint, CI/CD, SIEM, NIST, compliance, HIPAA. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Detecting Vulnerabilities at Scale:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **What Is Vulnerability Scanning?:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: CI/CD, NIST, compliance, HIPAA. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Common Vulnerabilities Identified Through Scanning:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: CI/CD, TLS, SSL. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Types of Vulnerability Scans:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Vulnerability Scanning Process:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Vulnerability Scanning Best Practices:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: endpoint, compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Challenges and Considerations:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: endpoint, SIEM, NIST, compliance, HIPAA. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.

### API Security

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** Integrity, Availability, firewall, endpoint, WAF, microservices, DevSecOps, CI/CD.

**Subsection notes**

- **API Security:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: Integrity, CI/CD, API, compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **API Security Considerations:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: Integrity, Availability, API. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Understanding APIs:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: API. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Core API Security Strategies:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: firewall, WAF, API. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Automated Vulnerability Scanning of APIs:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: endpoint, microservices, DevSecOps, CI/CD, API, OWASP, compliance. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **API Vulnerability Scanning in the Development Lifecycle:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: firewall, WAF, CI/CD, API, OWASP, compliance, secrets. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.

### Summary

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** Integrity, CI/CD, API.

## Secure Automated Workflows and Pipelines

### Introduction

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** DevSecOps, CI/CD, API, SOAR, compliance, telemetry, AI, ML.

### Automated Security Testing for Continuous Compliance

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** Integrity, least privilege, DevSecOps, CI/CD, IaC, SAFE, audit, compliance.

**Subsection notes**

- **Automated Security Testing for Continuous Compliance:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: Integrity, least privilege, CI/CD, IaC, audit, compliance, policy-as-code. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Why Use Automated Security Testing?:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: CI/CD, compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Automated Workflows and Their Risk Landscape:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: CI/CD, IaC, compliance, HIPAA. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Automated Security Testing Benefits:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: least privilege, CI/CD, compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Automated Security Testing Integration Strategies:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: DevSecOps, CI/CD, IaC, SAFE, compliance, supply chain. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.

### Integrating DevSecOps Workflows with AI/ML for Enhanced Security Posture

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** endpoint, EDR, DevSecOps, CI/CD, SIEM, NIST, MITRE ATT&CK, audit.

**Subsection notes**

- **Integrating DevSecOps Workflows with AI/ML for Enhanced Security Posture:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: DevSecOps, AI, ML. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Improving DevSecOps with AI/ML:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: DevSecOps, CI/CD, compliance, AI, ML. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Understanding Automated Workflows and Their Risk Landscape:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: DevSecOps, AI, ML. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Embedding AI/ML in CI/CD Pipelines for Early Threat Detection:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: DevSecOps, CI/CD, AI, ML. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Real-Time Anomaly Detection Across the Software Lifecycle:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: endpoint, EDR, DevSecOps, SIEM, AI, ML. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Continuous Learning and Model Training on New Threat Intelligence:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: endpoint, NIST, MITRE ATT&CK, compliance, telemetry, AI, ML. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Transparency and Auditability of AI/ML-Based Decisions:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: NIST, audit, compliance, AI, ML. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Balancing Automation with Human Oversight:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: DevSecOps, CI/CD, AI, ML. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.

### Security Design and AI Task 1-Threat Modeling with AI Assistance

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** IAM, Zero Trust, threat modeling, STRIDE, VPN, endpoint, DNS, MFA.

**Subsection notes**

- **Security Design and AI Task 1-Threat Modeling with AI Assistance:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: Zero Trust, threat modeling, OWASP, NIST, CSF, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Threat Modeling with AI Assistance:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: AI. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Job Aids:** Covers IDS/IPS design choices: where sensors/enforcement points sit, whether traffic is monitored or blocked, how signatures are tuned, and how alerts feed response workflows. Key terms: IAM, VPN, endpoint, DNS, SD-WAN, AI. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Activity:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: IAM, STRIDE, VPN, endpoint, DNS, MFA, SD-WAN, API. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Task Summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: threat modeling, STRIDE, SD-WAN, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Security Design and AI Task 2-Secure Architecture Review

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** IAM, Zero Trust, threat modeling, firewall, VPN, IPS, segmentation, endpoint.

**Subsection notes**

- **Security Design and AI Task 2-Secure Architecture Review:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: Zero Trust, threat modeling, OWASP, NIST, CSF, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Secure Architecture Review:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: AI. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Job Aids:** Covers IDS/IPS design choices: where sensors/enforcement points sit, whether traffic is monitored or blocked, how signatures are tuned, and how alerts feed response workflows. Key terms: IAM, firewall, VPN, segmentation, endpoint, DNS, WAF, IPsec. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Activity:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: IAM, Zero Trust, SD-WAN. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Task Summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: IAM, Zero Trust, firewall, IPS, segmentation, endpoint, EDR, MFA. Tie the subsection back to risk reduction, attacker paths, and incident visibility.

### Security Design and AI Task 3-AI-Assisted Secure Code Review

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** Zero Trust, threat modeling, OWASP, NIST, CSF, AI, secrets.

**Subsection notes**

- **Security Design and AI Task 3-AI-Assisted Secure Code Review:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: Zero Trust, threat modeling, OWASP, NIST, CSF, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **AI-Assisted Secure Code Review:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: AI. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Job Aids:** Covers IDS/IPS design choices: where sensors/enforcement points sit, whether traffic is monitored or blocked, how signatures are tuned, and how alerts feed response workflows. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Activity:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: AI. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Task Summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: AI, secrets. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.

### Security Design and AI Task 4-Designing a Secure Login System

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** Zero Trust, threat modeling, MFA, WebAuthn, API, OWASP, NIST, CSF.

**Subsection notes**

- **Security Design and AI Task 4-Designing a Secure Login System:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: Zero Trust, threat modeling, OWASP, NIST, CSF, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Designing a Secure Login System:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: MFA, WebAuthn, AI. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Activity:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: MFA, WebAuthn, API. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Task Summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: MFA, WebAuthn, AI. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.

### Security Design and AI Task 5-Writing a Security Policy with ChatGPT

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** Zero Trust, threat modeling, MFA, WebAuthn, OWASP, NIST, CSF, compliance.

**Subsection notes**

- **Security Design and AI Task 5-Writing a Security Policy with ChatGPT:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: Zero Trust, threat modeling, OWASP, NIST, CSF, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Writing a Security Policy with ChatGPT:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: MFA, WebAuthn, compliance, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Job Aids:** Covers IDS/IPS design choices: where sensors/enforcement points sit, whether traffic is monitored or blocked, how signatures are tuned, and how alerts feed response workflows. Key terms: compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Activity:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Task Summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: compliance, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Security Design and AI Task 6-AI as an Adversary: Red Team Scenario Design

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** Zero Trust, threat modeling, firewall, VPN, endpoint, EDR, XDR, DNS.

**Subsection notes**

- **Security Design and AI Task 6-AI as an Adversary: Red Team Scenario Design:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: Zero Trust, threat modeling, OWASP, NIST, CSF, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **AI as an Adversary: Red Team Scenario Design:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: VPN, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Job Aids:** Covers IDS/IPS design choices: where sensors/enforcement points sit, whether traffic is monitored or blocked, how signatures are tuned, and how alerts feed response workflows. Key terms: firewall, VPN, endpoint, EDR, XDR, DNS, MFA, SIEM. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Activity:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: MITRE ATT&CK, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Task Summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: VPN, endpoint, MITRE ATT&CK, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Security Design and AI Task 7-Privacy by Design-Data Flow Analysis

**Page summary:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit.
**Key terms:** Confidentiality, Zero Trust, threat modeling, OWASP, NIST, CSF, compliance, AI.

**Subsection notes**

- **Security Design and AI Task 7-Privacy by Design-Data Flow Analysis:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: Zero Trust, threat modeling, OWASP, NIST, CSF, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Privacy by Design-Data Flow Analysis:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: Confidentiality. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Job Aids:** Covers IDS/IPS design choices: where sensors/enforcement points sit, whether traffic is monitored or blocked, how signatures are tuned, and how alerts feed response workflows. Key terms: AI. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Activity:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: AI. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Task Summary:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: Confidentiality, compliance, AI. Tie the subsection back to risk reduction, attacker paths, and incident visibility.

### Security Design and AI Task 8-Risk Assessment Report with AI Help

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** IAM, Zero Trust, threat modeling, MFA, API, OWASP, NIST, CSF.

**Subsection notes**

- **Security Design and AI Task 8-Risk Assessment Report with AI Help:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: Zero Trust, threat modeling, OWASP, NIST, CSF, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Risk Assessment Report with AI Help:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: IAM, AI. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Job Aids:** Covers IDS/IPS design choices: where sensors/enforcement points sit, whether traffic is monitored or blocked, how signatures are tuned, and how alerts feed response workflows. Key terms: IAM, MFA, API, AI, supply chain, secrets. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Activity:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: IAM, MFA, AI. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Task Summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Security Design and AI Task 9-Designing Security Awareness Campaigns

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** Zero Trust, threat modeling, OWASP, NIST, CSF, AI.

**Subsection notes**

- **Security Design and AI Task 9-Designing Security Awareness Campaigns:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: Zero Trust, threat modeling, OWASP, NIST, CSF, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Designing Security Awareness Campaigns:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Activity:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Task Summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Security Design and AI Task 10-Incident Response Plan Simulation

**Page summary:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels.
**Key terms:** Zero Trust, threat modeling, OWASP, NIST, CSF, compliance, ransomware, AI.

**Subsection notes**

- **Security Design and AI Task 10-Incident Response Plan Simulation:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: Zero Trust, threat modeling, OWASP, NIST, CSF, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Incident Response Plan Simulation:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: ransomware, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Job Aids:** Covers IDS/IPS design choices: where sensors/enforcement points sit, whether traffic is monitored or blocked, how signatures are tuned, and how alerts feed response workflows. Key terms: ransomware. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Activity:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: compliance, ransomware, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Task Summary:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: compliance, ransomware, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Summary

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** DevSecOps, compliance, AI, ML.

## AI's Role in Securing Infrastructure

### Introduction

**Page summary:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk.
**Key terms:** API, SOAR, telemetry, AI.

### AI-Driven Threat Detection and Response

**Page summary:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels.
**Key terms:** IPS, endpoint, EDR, DNS, SIEM, SOAR, audit, compliance.

**Subsection notes**

- **AI-Driven Threat Detection and Response:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: endpoint, SOAR, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Harnessing AI to Strengthen Cybersecurity Operations:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: AI. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Threat Detection and Response:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Role of AI in Modern Cybersecurity:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: AI. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **AI-Driven Threat Detection:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: DNS, APT, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **AI-Assisted Response and Remediation:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: SOAR, AI. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Building and Deploying AI in Security Systems:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: IPS, endpoint, EDR, SIEM, SOAR, audit, compliance, telemetry. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Risks, Limitations, and Ethical Considerations:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: audit, compliance, AI. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.

### Infrastructure as Code (IaC) for Security

**Page summary:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates.
**Key terms:** IAM, firewall, segmentation, DevSecOps, CI/CD, IaC, NIST, audit.

**Subsection notes**

- **Infrastructure as Code (IaC) for Security:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: DevSecOps, IaC. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Ensuring Consistent and Repeatable Secure Environments:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: IaC. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Definition and Core Principles of IaC:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: CI/CD, IaC, audit. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Security Benefits of IaC:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: IAM, firewall, segmentation, CI/CD, IaC, NIST, audit, compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Operational Efficiency and Collaboration:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: DevSecOps, IaC, compliance. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Conclusion:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: DevSecOps, IaC, audit, compliance. Use the subsection to connect architecture placement, policy, visibility, and operations.

### Security Telemetry and Monitoring

**Page summary:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk.
**Key terms:** firewall, IDS, IPS, IDS/IPS, endpoint, EDR, XDR, DLP.

**Subsection notes**

- **Security Telemetry and Monitoring:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: XDR, DNS, API, Talos, telemetry. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Threats Don't Stay Contained:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: telemetry. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Understanding Automated Workflows and Their Risk Landscape:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: XDR, telemetry. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Security Telemetry and Monitoring:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: firewall, IDS, IPS, IDS/IPS, endpoint, EDR, XDR, API. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Global Telemetry and Automation:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: endpoint, EDR, XDR, DNS, SIEM, SOAR, telemetry. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Automation in Incident Response:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: IDS, IPS, IDS/IPS, endpoint, EDR, DLP, SIEM, SOAR. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Conclusion:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: XDR, telemetry. Tie the subsection back to risk reduction, attacker paths, and incident visibility.

### Summary

**Page summary:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk.
**Key terms:** telemetry, AI.

