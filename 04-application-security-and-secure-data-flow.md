# Application Security and Secure Data Flow

Source: Cisco U. Designing Cisco Security Infrastructure path. Assessments are excluded. These notes are paraphrased from the instructional pages and organized by lesson page plus actual subsection headings.

## Module Summary

This module contains 3 lessons. Each page below includes a page-level summary and subsection-level notes drawn from the headings and instructional content on that page.

## Security Solutions Based on Application and Flow Data

### Introduction

**Page summary:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering.
**Key terms:** IPS, endpoint, DLP, OWASP, SSL, decryption, offloading, AVC.

### Application Firewalls

**Page summary:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering.
**Key terms:** Integrity, least privilege, firewall, IPS, endpoint, EDR, WAF, SD-WAN.

**Subsection notes**

- **Application Firewalls:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: firewall, IPS, OWASP, TLS, decryption, AVC, Security Intelligence, RBAC. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Web-Based Application Considerations:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: IPS, OWASP, AVC. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Open Web Application Security Project (OWASP):** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: IPS, OWASP, compliance, AVC. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Web Application Firewalls:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: least privilege, IPS, DevSecOps, AVC. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Intrusion Prevention Systems:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: firewall, IPS, endpoint, SD-WAN, SIEM. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **AVC:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: Integrity, firewall, endpoint, EDR, Kubernetes, serverless, AVC, supply chain. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Applying WAF, IPS, and AVC to the OWASP Top 10:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: Integrity, least privilege, IPS, WAF, API, OWASP, audit, compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.

### SSL Offloading and Decryption

**Page summary:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit.
**Key terms:** firewall, NGFW, IDS, IPS, IDS/IPS, SaaS, TLS, SSL.

**Subsection notes**

- **SSL Offloading and Decryption:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: firewall, IPS, TLS, SSL, decryption, offloading, compliance, URL filtering. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Threats Can Hide in SSL/TLS Traffic:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: TLS, SSL, decryption, offloading, compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Need for SSL Decryption:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: SSL. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **SSL Offloading:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: IPS, SSL, decryption, offloading. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **SSL Decryption Use Cases:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: TLS, SSL, decryption. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **SSLi Use Case:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: firewall, TLS, SSL, decryption, offloading, compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **SSL Decryption for URL Filtering:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: TLS, SSL, decryption, URL filtering. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Inline SSL Decryption:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: firewall, SaaS, TLS, SSL, decryption. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Inline SSL Decryption with TLS v1.3:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: firewall, TLS, SSL, decryption. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **TLS Server Identity Discovery:** Frames identity as a core enforcement layer. Access decisions should account for user, role, device trust, authentication strength, context, and ongoing authorization. Key terms: firewall, TLS, SSL, decryption. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Encrypted Visibility Engine:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: firewall, TLS, decryption. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **SSL Decryption and Offloading Design:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: firewall, NGFW, IDS, IPS, IDS/IPS, TLS, SSL, decryption. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Data Loss Prevention (DLP)

**Page summary:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit.
**Key terms:** firewall, IDS, endpoint, DLP, DNS, SaaS, API, SSL.

**Subsection notes**

- **Data Loss Prevention (DLP):** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: DLP, SAFE, compliance, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Outgoing Data Threats:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: DLP, compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Data Loss Prevention Features:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: DLP, compliance. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Email DLP:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: DLP. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Cisco Secure Email DLP Policies:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: IDS, DLP. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Web Traffic DLP:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: firewall, DLP, DNS, SaaS, API, SSL, compliance, AI. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **DLP for Data at Rest:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: endpoint, DLP, SIEM, audit, compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.

### Endpoint Security in Application Data Flows

**Page summary:** Summarizes endpoint security controls such as hardening, anti-malware, local firewall rules, posture checks, detection/response tooling, and endpoint telemetry.
**Key terms:** Confidentiality, Integrity, Availability, firewall, VPN, IDS, IPS, IDS/IPS.

**Subsection notes**

- **Endpoint Security in Application Data Flows:** Summarizes endpoint security controls such as hardening, anti-malware, local firewall rules, posture checks, detection/response tooling, and endpoint telemetry. Key terms: firewall, VPN, endpoint, EDR, SAFE, compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Endpoint Data Security Matters:** Summarizes endpoint security controls such as hardening, anti-malware, local firewall rules, posture checks, detection/response tooling, and endpoint telemetry. Key terms: endpoint, audit. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Endpoint Security Solutions:** Summarizes endpoint security controls such as hardening, anti-malware, local firewall rules, posture checks, detection/response tooling, and endpoint telemetry. Key terms: endpoint, EDR. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Anti-virus and Anti-Malware Software:** Summarizes endpoint security controls such as hardening, anti-malware, local firewall rules, posture checks, detection/response tooling, and endpoint telemetry. Key terms: Confidentiality, Integrity, Availability, endpoint, compliance, ransomware. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Endpoint Firewalls:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: firewall, endpoint. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Endpoint Detection & Response (EDR):** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: Confidentiality, Integrity, IDS, IPS, IDS/IPS, endpoint, EDR. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Data Encryption:** Summarizes endpoint security controls such as hardening, anti-malware, local firewall rules, posture checks, detection/response tooling, and endpoint telemetry. Key terms: TLS, decryption. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Policy Enforcement and Remote Control:** Focuses on constrained or specialized devices that need discovery, profiling, manufacturer-intent controls, segmentation, least privilege, monitoring, and compensating controls. Key terms: Confidentiality, Integrity, endpoint. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Integrated Endpoint Security Platforms:** Summarizes endpoint security controls such as hardening, anti-malware, local firewall rules, posture checks, detection/response tooling, and endpoint telemetry. Key terms: endpoint, EDR, ransomware. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Endpoint Data Security in Use:** Summarizes endpoint security controls such as hardening, anti-malware, local firewall rules, posture checks, detection/response tooling, and endpoint telemetry. Key terms: Integrity, Availability, firewall, endpoint, EDR, DLP, compliance, ransomware. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### DNS Security

**Page summary:** Explains DNS-layer defense as an early control point for blocking malicious destinations, phishing infrastructure, command-and-control lookups, and risky content categories.
**Key terms:** Availability, firewall, VPN, endpoint, DNS, audit, compliance, ransomware.

**Subsection notes**

- **DNS Security:** Explains DNS-layer defense as an early control point for blocking malicious destinations, phishing infrastructure, command-and-control lookups, and risky content categories. Key terms: firewall, DNS, ransomware, Talos. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Known Protocols, Unknown Threats:** Focuses on constrained or specialized devices that need discovery, profiling, manufacturer-intent controls, segmentation, least privilege, monitoring, and compensating controls. Key terms: DNS. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Understanding DNS and Its Role in Application Connectivity:** Explains DNS-layer defense as an early control point for blocking malicious destinations, phishing infrastructure, command-and-control lookups, and risky content categories. Key terms: DNS. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **How Cybercriminals Exploit DNS:** Explains DNS-layer defense as an early control point for blocking malicious destinations, phishing infrastructure, command-and-control lookups, and risky content categories. Key terms: DNS. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Phishing Campaigns and Malvertising Threats:** Explains DNS-layer defense as an early control point for blocking malicious destinations, phishing infrastructure, command-and-control lookups, and risky content categories. Key terms: DNS. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **DNS Protections for Enterprise:** Explains network access control patterns: strong 802.1X authentication where possible, MAB for constrained devices, WebAuth for guest/BYOD flows, and authorization changes driven by policy. Key terms: DNS, ransomware, Talos, Security Intelligence, telemetry. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Zero-Day Protection:** Focuses on constrained or specialized devices that need discovery, profiling, manufacturer-intent controls, segmentation, least privilege, monitoring, and compensating controls. Key terms: endpoint, DNS, ransomware, Talos, telemetry. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Expanding Protection with Category-Based Blocking:** Focuses on constrained or specialized devices that need discovery, profiling, manufacturer-intent controls, segmentation, least privilege, monitoring, and compensating controls. Key terms: DNS, audit, compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Design Considerations for DNS Protections:** Focuses on constrained or specialized devices that need discovery, profiling, manufacturer-intent controls, segmentation, least privilege, monitoring, and compensating controls. Key terms: Availability, VPN, endpoint, DNS, Security Intelligence, telemetry. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Design Practice Activity 1: Designing a Resilient Web Application Firewall Architecture

**Page summary:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering.
**Key terms:** Availability, firewall, IPS, endpoint, DNS, WAF, CDN, SaaS.

**Subsection notes**

- **Design Practice Activity 1: Designing a Resilient Web Application Firewall Architecture:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: Availability, firewall, IPS, endpoint, DNS, WAF, CDN, SaaS. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Design Practice Activity 2: Secure SSL/TLS Decryption Strategy in a Privacy-Conscious Environment

**Page summary:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit.
**Key terms:** firewall, VPN, segmentation, endpoint, DNS, SaaS, TLS, SSL.

**Subsection notes**

- **Design Practice Activity 2: Secure SSL/TLS Decryption Strategy in a Privacy-Conscious Environment:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: firewall, VPN, segmentation, endpoint, DNS, SaaS, TLS, SSL. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Design Practice Activity 3: DNS-Layer Defense Integration in a Remote and Hybrid Workforce

**Page summary:** Focuses on constrained or specialized devices that need discovery, profiling, manufacturer-intent controls, segmentation, least privilege, monitoring, and compensating controls.
**Key terms:** Availability, firewall, VPN, endpoint, EDR, DNS, SD-WAN, SaaS.

**Subsection notes**

- **Design Practice Activity 3: DNS-Layer Defense Integration in a Remote and Hybrid Workforce:** Focuses on constrained or specialized devices that need discovery, profiling, manufacturer-intent controls, segmentation, least privilege, monitoring, and compensating controls. Key terms: Availability, firewall, VPN, endpoint, EDR, DNS, SD-WAN, SaaS. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Design Practice Activity 4: Designing Endpoint Security Enforcement in a Hybrid Enterprise

**Page summary:** Explains network access control patterns: strong 802.1X authentication where possible, MAB for constrained devices, WebAuth for guest/BYOD flows, and authorization changes driven by policy.
**Key terms:** firewall, VPN, segmentation, endpoint, DLP, DNS, MFA, ISE.

**Subsection notes**

- **Design Practice Activity 4: Designing Endpoint Security Enforcement in a Hybrid Enterprise:** Explains network access control patterns: strong 802.1X authentication where possible, MAB for constrained devices, WebAuth for guest/BYOD flows, and authorization changes driven by policy. Key terms: firewall, VPN, segmentation, endpoint, DNS, ISE, audit, compliance. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Incident Response & SOC Integration:** Explains network access control patterns: strong 802.1X authentication where possible, MAB for constrained devices, WebAuth for guest/BYOD flows, and authorization changes driven by policy. Key terms: firewall, VPN, segmentation, endpoint, DLP, DNS, MFA, ISE. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Summary

**Page summary:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering.
**Key terms:** IPS, endpoint, EDR, DLP, DNS, OWASP, SSL, decryption.

## Security for Cloud-Native Applications, Microservices, and Containers

### Introduction

**Page summary:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse.
**Key terms:** segmentation, microsegmentation, containers, microservices, serverless.

### Microservices Security and Segmentation

**Page summary:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse.
**Key terms:** Integrity, IAM, Zero Trust, least privilege, firewall, IPS, segmentation, MFA.

**Subsection notes**

- **Microservices Security and Segmentation:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: least privilege, segmentation, containers, microservices, CI/CD, API, observability, supply chain. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Rapid Response to Business Needs:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: containers, microservices. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Software Development with Microservices and Containerization:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: RADIUS, multi-cloud, Kubernetes, containers, microservices, CI/CD. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Microservices and Container Security Challenges:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: Integrity, containers, microservices, API, TLS. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Network Segmentation and Service Isolation:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: least privilege, segmentation, Kubernetes, containers, microservices, TLS, observability, compliance. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Identity and Access Management (IAM):** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: IAM, Zero Trust, least privilege, Kubernetes, containers, microservices, CI/CD, API. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Container Image Security:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: Kubernetes, containers, microservices, CI/CD, supply chain, secrets. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Software Supply Chain Security:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: Integrity, least privilege, MFA, Kubernetes, microservices, CI/CD, OWASP, NIST. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Monitoring and Incident Response:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: Integrity, IAM, least privilege, firewall, IPS, segmentation, multi-cloud, Kubernetes. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Containers and Kubernetes Security

**Page summary:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse.
**Key terms:** least privilege, firewall, segmentation, microsegmentation, RADIUS, Kubernetes, containers, microservices.

**Subsection notes**

- **Containers and Kubernetes Security:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: segmentation, Kubernetes, containers, microservices, API, audit, compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Managing Containers for Application Deployment:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: segmentation, RADIUS, Kubernetes, containers, microservices. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Segmentation in Containerized Environments:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: least privilege, segmentation, microsegmentation, Kubernetes, containers, API, audit, compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Kubernetes and Its Components:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: segmentation, Kubernetes, containers. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Kubernetes Network Policies:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: least privilege, segmentation, RADIUS, Kubernetes. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Security Benefits of Network Segmentation in Kubernetes:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: firewall, segmentation, microsegmentation, Kubernetes, microservices, observability, eBPF, compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.

### Serverless Architecture

**Page summary:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse.
**Key terms:** IAM, least privilege, containers, serverless, DevSecOps, CI/CD, API, OWASP.

**Subsection notes**

- **Serverless Architecture:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: IAM, least privilege, serverless, observability. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Move to Serverless Architecture:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: containers, serverless. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Introduction to Serverless Architecture:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: containers, serverless, API. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Security Considerations in Serverless Architecture:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: IAM, least privilege, serverless, API, compliance, HIPAA. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Best Practices for Securing Serverless Applications:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse. Key terms: IAM, least privilege, serverless, DevSecOps, CI/CD, API, OWASP, TLS. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.

### Summary

**Page summary:** Shows how enforcement moves closer to endpoints and workloads, using host or distributed firewall policy to control traffic where perimeter-only designs are too coarse.
**Key terms:** containers, microservices.

## Emerging Technologies in Application Security

### Introduction

**Page summary:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels.
**Key terms:** AI, quantum.

### Generative Artificial Intelligence (AI) and Machine Learning

**Page summary:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk.
**Key terms:** firewall, segmentation, endpoint, XDR, DNS, SD-WAN, SaaS, hybrid cloud.

**Subsection notes**

- **Generative Artificial Intelligence (AI) and Machine Learning:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: firewall, endpoint, XDR, hybrid cloud, telemetry, AI, ML. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Need for Advanced Cognitive Capabilities:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **AI and Machine Learning:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **AI in Network Infrastructure Security:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: DDoS, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Benefits of AI in Infrastructure Security:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: AI. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **AI-Driven Security Management Products:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: endpoint, XDR, DNS, SIEM, Talos, Security Intelligence, telemetry, AI. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **AI-Enabled Monitoring and Response Tools:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: firewall, XDR, SD-WAN, SaaS, SIEM, SOAR, TID, telemetry. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Impact of AI in Security Practices:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: firewall, segmentation, compliance, AI. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Quantum Computing Security Impacts

**Page summary:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk.
**Key terms:** Confidentiality, Integrity, VPN, data center, TLS, decryption, SAFE, NIST.

**Subsection notes**

- **Quantum Computing Security Impacts:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: VPN, decryption, NIST, quantum. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Threats of Tomorrow:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: Confidentiality, Integrity, quantum. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Quantum Computing vs. Classical Computing:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: quantum. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Application Domains with Quantum Advantage:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: AI, PQC, quantum, Shor. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Example: Shor's Algorithm for Integer Factorization:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: data center, quantum, Shor. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Implications for Current Security Methods:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: Confidentiality, Integrity, PQC, quantum. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **PQC:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: Confidentiality, Integrity, NIST, PQC, quantum, Shor. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Recommendations for Security Professionals:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: Confidentiality, TLS, decryption, SAFE, NIST, compliance, PQC, quantum. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Summary

**Page summary:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels.
**Key terms:** decryption, AI, quantum.

