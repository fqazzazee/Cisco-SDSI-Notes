# Security Architecture Design Fundamentals

Source: Cisco U. Designing Cisco Security Infrastructure path. Assessments are excluded. These notes are paraphrased from the instructional pages and organized by lesson page plus actual subsection headings.

## Module Summary

This module contains 5 lessons. Each page below includes a page-level summary and subsection-level notes drawn from the headings and instructional content on that page.

## Definition and Purpose of Security Architecture

### Introduction

**Page summary:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels.
**Key terms:** Integrity, IAM, Zero Trust, defense in depth, compliance.

### Security Architecture Components

**Page summary:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering.
**Key terms:** Integrity, IAM, Zero Trust, least privilege, defense in depth, threat modeling, firewall, VPN.

**Subsection notes**

- **Security Architecture Components:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: IAM, firewall, VPN, IDS, IPS, IDS/IPS, segmentation, IPsec. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Security Architect Responsibilities:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: IAM, firewall, VPN, segmentation, ransomware. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Security Architecture Core Components:** Explains network access control patterns: strong 802.1X authentication where possible, MAB for constrained devices, WebAuth for guest/BYOD flows, and authorization changes driven by policy. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Core Principles:** Summarizes foundational security principles and how they guide layered controls, access limits, data protection, service resilience, and risk reduction. Key terms: Integrity, Zero Trust, least privilege, defense in depth. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Threat Modeling:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: threat modeling, IDS, IPS, IDS/IPS, compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Network Security:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: firewall, IDS, IPS, IDS/IPS, segmentation, DLP, WAF, SIEM. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Identity and Access Management (IAM):** Frames identity as a core enforcement layer. Access decisions should account for user, role, device trust, authentication strength, context, and ongoing authorization. Key terms: IAM, least privilege, MFA, compliance, RBAC. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Data Security:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: ransomware, RBAC. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Security Architecture Core Components (Cont.):** Explains Security Architecture Core Components (Cont.) as a security architecture topic, focusing on where the control fits, what risk it reduces, and how it should be operated and validated. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Endpoint and Application Security:** Summarizes endpoint security controls such as hardening, anti-malware, local firewall rules, posture checks, detection/response tooling, and endpoint telemetry. Key terms: segmentation, endpoint, EDR. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Logging and Monitoring:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Key terms: audit. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Compliance and Governance:** Maps security design to compliance obligations through control evidence, accountability, monitoring, reporting, audit readiness, and documented exceptions. Key terms: segmentation, compliance, HIPAA. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Physical Security:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter. Key terms: Integrity. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Business Continuity and Disaster Recovery (BC/DR):** Uses incident-driven scenarios to show how containment, recovery, lessons learned, and architecture changes improve resilience after real attacks. Key terms: BC/DR, Talos. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **A Comprehensive Approach:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: BC/DR, compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.

### Security Architecture in Modern Networks

**Page summary:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering.
**Key terms:** CIA, Confidentiality, Integrity, Availability, IAM, Zero Trust, least privilege, defense in depth.

**Subsection notes**

- **Security Architecture in Modern Networks:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: CIA, Confidentiality, Integrity, Availability, IAM, Zero Trust, least privilege, defense in depth. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Security Architecture Considerations:** Explains network access control patterns: strong 802.1X authentication where possible, MAB for constrained devices, WebAuth for guest/BYOD flows, and authorization changes driven by policy. Key terms: microsegmentation, ZTNA, compliance, HIPAA, ransomware. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Infrastructure Security Core Principles:** Summarizes foundational security principles and how they guide layered controls, access limits, data protection, service resilience, and risk reduction. Key terms: CIA, Confidentiality, Integrity, Availability, defense in depth. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Layered Security in an Enterprise Setting:** Explains network access control patterns: strong 802.1X authentication where possible, MAB for constrained devices, WebAuth for guest/BYOD flows, and authorization changes driven by policy. Key terms: defense in depth. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Identity and Access Management (IAM):** Frames identity as a core enforcement layer. Access decisions should account for user, role, device trust, authentication strength, context, and ongoing authorization. Key terms: IAM, Zero Trust, MFA, RADIUS, RBAC. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Data Protection:** Focuses on constrained or specialized devices that need discovery, profiling, manufacturer-intent controls, segmentation, least privilege, monitoring, and compensating controls. Key terms: IDS, DLP, SIEM, compliance, HIPAA, ransomware. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Endpoint and Application Security:** Summarizes endpoint security controls such as hardening, anti-malware, local firewall rules, posture checks, detection/response tooling, and endpoint telemetry. Key terms: IAM, endpoint, EDR, SIEM. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Monitoring and Incident Response:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: segmentation, XDR, SIEM. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Governance, Compliance, and Physical Security:** Maps security design to compliance obligations through control evidence, accountability, monitoring, reporting, audit readiness, and documented exceptions. Key terms: data center, NIST, compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Business Continuity and Disaster Recovery:** Uses incident-driven scenarios to show how containment, recovery, lessons learned, and architecture changes improve resilience after real attacks. Key terms: IAM, IDS, SIEM. Tie the subsection back to risk reduction, attacker paths, and incident visibility.

### Security Design Principles

**Page summary:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering.
**Key terms:** MFA, BCP, compliance.

**Subsection notes**

- **Security Design Principles:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: MFA, compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Security Design Considerations:** Focuses on constrained or specialized devices that need discovery, profiling, manufacturer-intent controls, segmentation, least privilege, monitoring, and compensating controls. Key terms: compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Security Strategy:** Shows how architects translate threats, business priorities, stakeholder needs, compliance obligations, and investment tradeoffs into defensible security choices. Key terms: compliance. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Risk Assessment:** Shows how architects translate threats, business priorities, stakeholder needs, compliance obligations, and investment tradeoffs into defensible security choices. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Compliance Alignment:** Maps security design to compliance obligations through control evidence, accountability, monitoring, reporting, audit readiness, and documented exceptions. Key terms: compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Scalability:** Focuses on constrained or specialized devices that need discovery, profiling, manufacturer-intent controls, segmentation, least privilege, monitoring, and compensating controls. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Business Continuity Planning (BCP) and Real-Time Monitoring:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Key terms: BCP. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Stakeholder Engagement in Security Governance:** Maps security design to compliance obligations through control evidence, accountability, monitoring, reporting, audit readiness, and documented exceptions. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Return on Investment (ROI):** Shows how architects translate threats, business priorities, stakeholder needs, compliance obligations, and investment tradeoffs into defensible security choices. Key terms: BCP. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.

### Summary

**Page summary:** Explains network access control patterns: strong 802.1X authentication where possible, MAB for constrained devices, WebAuth for guest/BYOD flows, and authorization changes driven by policy.
**Key terms:** Zero Trust, defense in depth, compliance.

## Components of Security Infrastructure

### Introduction

**Page summary:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering.
**Key terms:** Integrity, Availability, IAM, IDS, IPS, IDS/IPS, DevSecOps, API.

### Layers of Security Infrastructure: Physical, Network, Application, and Data

**Page summary:** Breaks the infrastructure into layers and shows which controls belong at each point so traffic paths, applications, data, and physical assets are protected together.
**Key terms:** Confidentiality, Integrity, Availability, IAM, Zero Trust, IDS, IPS, IDS/IPS.

**Subsection notes**

- **Layers of Security Infrastructure: Physical, Network, Application, and Data:** Breaks the infrastructure into layers and shows which controls belong at each point so traffic paths, applications, data, and physical assets are protected together. Key terms: segmentation, 802.1X, data center, API. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Network Infrastructure Layers:** Breaks the infrastructure into layers and shows which controls belong at each point so traffic paths, applications, data, and physical assets are protected together. Key terms: Confidentiality, Integrity, Availability. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Layered Security Design Considerations:** Explains network access control patterns: strong 802.1X authentication where possible, MAB for constrained devices, WebAuth for guest/BYOD flows, and authorization changes driven by policy. Key terms: Integrity. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Network Architectural Layer:** Explains network access control patterns: strong 802.1X authentication where possible, MAB for constrained devices, WebAuth for guest/BYOD flows, and authorization changes driven by policy. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Network Architectural Layer-Access Sublayer:** Breaks the infrastructure into layers and shows which controls belong at each point so traffic paths, applications, data, and physical assets are protected together. Key terms: segmentation, EDR, two-factor. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Network Architectural Layer-Distribution Sublayer:** Breaks the infrastructure into layers and shows which controls belong at each point so traffic paths, applications, data, and physical assets are protected together. Key terms: IDS, IPS, IDS/IPS, segmentation. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Network Architectural Layer-Core Sublayer:** Breaks the infrastructure into layers and shows which controls belong at each point so traffic paths, applications, data, and physical assets are protected together. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Physical Layer - Data Center Sublayer:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter. Key terms: Confidentiality, Integrity, data center. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Network Architectural Layer-Internet Edge Sublayer:** Breaks the infrastructure into layers and shows which controls belong at each point so traffic paths, applications, data, and physical assets are protected together. Key terms: IDS, IPS, IDS/IPS, MFA, TLS, SIEM. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Network Architectural Layer-Wide Area Network (WAN) Sublayer:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: IDS, IPS, IDS/IPS, segmentation, endpoint, IPsec, MPLS, SD-WAN. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Network Architectural Layer-Virtual Sublayer:** Breaks the infrastructure into layers and shows which controls belong at each point so traffic paths, applications, data, and physical assets are protected together. Key terms: segmentation. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Application Layer:** Breaks the infrastructure into layers and shows which controls belong at each point so traffic paths, applications, data, and physical assets are protected together. Key terms: API, RBAC. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Data Layer:** Breaks the infrastructure into layers and shows which controls belong at each point so traffic paths, applications, data, and physical assets are protected together. Key terms: DLP, ransomware. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Cloud Services Layer:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter. Key terms: IAM, Zero Trust, segmentation, CASB, compliance, ransomware. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Infrastructure Components: Endpoints, Servers, Data Centers, and Cloud Environments

**Page summary:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter.
**Key terms:** Integrity, Availability, IAM, Zero Trust, defense in depth, VPN, IDS, IPS.

**Subsection notes**

- **Infrastructure Components: Endpoints, Servers, Data Centers, and Cloud Environments:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter. Key terms: IAM, VPN, endpoint, EDR, DLP, CASB, data center, SIEM. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Network Infrastructure Components:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter. Key terms: defense in depth, data center. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Infrastructure Component Security Design Considerations:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter. Key terms: Zero Trust, defense in depth, endpoint, hybrid cloud, compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Core Infrastructure Component Security Design:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter. Key terms: defense in depth. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Endpoints:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter. Key terms: Zero Trust, endpoint, EDR. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Servers:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter. Key terms: Integrity, Availability, IDS, IPS, IDS/IPS. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Data Center:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter. Key terms: Availability, segmentation, data center. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Cloud Environments:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter. Key terms: IAM, DLP, API, compliance, RBAC. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Additional Infrastructure Components:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter. Key terms: Integrity, Zero Trust, segmentation, endpoint, SASE, data center, Kubernetes, containers. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Core Security Technologies: Firewalls, VPNs, IDS/IPS, IAM

**Page summary:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering.
**Key terms:** Confidentiality, Integrity, IAM, least privilege, firewall, VPN, IDS, IPS.

**Subsection notes**

- **Core Security Technologies: Firewalls, VPNs, IDS/IPS, IAM:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: IAM, firewall, VPN, IDS, IPS, IDS/IPS, segmentation, ISE. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Core Security Technologies in Enterprise Infrastructure:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Firewalls:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: IPS, SD-WAN. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **VPNs:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: Confidentiality, Integrity, IPsec, TLS, SSL, compliance, HIPAA. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **IDS/IPS:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: IDS, IPS, IDS/IPS, endpoint, SIEM, audit, compliance. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Identity Access Management:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: IAM, least privilege, MFA, compliance, RBAC. Tie the subsection back to risk reduction, attacker paths, and incident visibility.

### Design Case Study Activity 1: Migrating from Flat Network to Layered Design

**Page summary:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering.
**Key terms:** firewall, IDS, IPS, IDS/IPS, segmentation, endpoint, MPLS, SD-WAN.

**Subsection notes**

- **Design Case Study Activity 1: Migrating from Flat Network to Layered Design:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: firewall, IDS, IPS, IDS/IPS, segmentation, endpoint, SIEM, telemetry. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Designing the Layered Architecture:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: IDS, segmentation, endpoint. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Firewall and IDS/IPS Placement:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: firewall, IDS, IPS, IDS/IPS, segmentation, endpoint, SIEM, telemetry. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Isolating IoT and OT Traffic:** Focuses on constrained or specialized devices that need discovery, profiling, manufacturer-intent controls, segmentation, least privilege, monitoring, and compensating controls. Key terms: firewall, IDS, segmentation, SIEM. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **WAN Connectivity and Branch Integration:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: firewall, IDS, segmentation, endpoint, MPLS, SD-WAN, SIEM, audit. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Design Case Study Activity 2: Securing the Edge

**Page summary:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering.
**Key terms:** Zero Trust, least privilege, firewall, NGFW, VPN, IDS, IPS, IDS/IPS.

**Subsection notes**

- **Design Case Study Activity 2: Securing the Edge:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: Zero Trust, least privilege, firewall, NGFW, VPN, IDS, IPS, IDS/IPS. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Design Case Study Activity 3: Micro-Segmentation in a Virtualized Data Center

**Page summary:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter.
**Key terms:** Zero Trust, firewall, NGFW, segmentation, EDR, DLP, DNS, MFA.

**Subsection notes**

- **Design Case Study Activity 3: Micro-Segmentation in a Virtualized Data Center:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter. Key terms: firewall, segmentation, DLP, MFA, data center, audit, compliance, ransomware. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **North-South & East-West Traffic Protection:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter. Key terms: Zero Trust, NGFW, segmentation, EDR, data center, SIEM, SAFE, audit. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Multi-Data Center Security Strategy:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter. Key terms: firewall, segmentation, data center, SIEM, BC/DR, compliance, telemetry. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Segmentation & Zero-Trust Design:** Addresses distributed application and workload security, where identity, configuration governance, segmentation, visibility, and consistent policy matter more than a single perimeter. Key terms: Zero Trust, firewall, segmentation, DNS, data center, audit. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Design Case Study Activity 4: Endpoint and Insider Threat Response

**Page summary:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels.
**Key terms:** Zero Trust, VPN, endpoint, EDR, DLP, CASB, MFA, SaaS.

**Subsection notes**

- **Design Case Study Activity 4: Endpoint and Insider Threat Response:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: Zero Trust, endpoint, EDR, MFA, SIEM, telemetry, RBAC. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Endpoint Threat Detection Strategy:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: Zero Trust, endpoint, EDR, MFA, SIEM, compliance, telemetry, RBAC. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Insider Alerting:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: VPN, endpoint, EDR, DLP, SIEM, telemetry, ML. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Designing DLP for Insider Threat Defense:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: endpoint, DLP, CASB, SaaS. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Summary

**Page summary:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering.
**Key terms:** IAM.

## Security Design Principles

### Introduction

**Page summary:** Explains network access control patterns: strong 802.1X authentication where possible, MAB for constrained devices, WebAuth for guest/BYOD flows, and authorization changes driven by policy.
**Key terms:** Integrity, Zero Trust, least privilege, observability.

### Least Privilege and Zero Trust Models

**Page summary:** Frames identity as a core enforcement layer. Access decisions should account for user, role, device trust, authentication strength, context, and ongoing authorization.
**Key terms:** IAM, Zero Trust, least privilege, firewall, VPN, segmentation, microsegmentation, endpoint.

**Subsection notes**

- **Least Privilege and Zero Trust Models:** Frames identity as a core enforcement layer. Access decisions should account for user, role, device trust, authentication strength, context, and ongoing authorization. Key terms: Zero Trust, least privilege, microsegmentation, endpoint, ZTNA, compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Least Privilege and Zero Trust Security Design Considerations:** Frames identity as a core enforcement layer. Access decisions should account for user, role, device trust, authentication strength, context, and ongoing authorization. Key terms: IAM, least privilege, segmentation, HIPAA, RBAC. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Zero Trust:** Frames identity as a core enforcement layer. Access decisions should account for user, role, device trust, authentication strength, context, and ongoing authorization. Key terms: IAM, Zero Trust, least privilege, firewall, VPN, microsegmentation, endpoint, EDR. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Least Privilege and Zero Trust in Use:** Frames identity as a core enforcement layer. Access decisions should account for user, role, device trust, authentication strength, context, and ongoing authorization. Key terms: Zero Trust, least privilege, MFA. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Defense-in-Depth and Multi-Layered Security Approaches

**Page summary:** Summarizes foundational security principles and how they guide layered controls, access limits, data protection, service resilience, and risk reduction.
**Key terms:** Confidentiality, Integrity, defense in depth, firewall, VPN, IDS, IPS, IDS/IPS.

**Subsection notes**

- **Defense-in-Depth and Multi-Layered Security Approaches:** Summarizes foundational security principles and how they guide layered controls, access limits, data protection, service resilience, and risk reduction. Key terms: defense in depth, firewall, VPN, IPS, DNS, 802.1X, RADIUS, data center. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **One Weak Link:** Summarizes foundational security principles and how they guide layered controls, access limits, data protection, service resilience, and risk reduction. Key terms: firewall, endpoint, WAF. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Defense-in-Depth:** Summarizes foundational security principles and how they guide layered controls, access limits, data protection, service resilience, and risk reduction. Key terms: Confidentiality, Integrity, IDS, IPS, IDS/IPS, endpoint, EDR, DLP. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Multi-Layered Security:** Summarizes foundational security principles and how they guide layered controls, access limits, data protection, service resilience, and risk reduction. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.

### Role of Encryption and Data Integrity in Security Design

**Page summary:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit.
**Key terms:** Confidentiality, Integrity, firewall, VPN, DLP, MFA, API, TLS.

**Subsection notes**

- **Role of Encryption and Data Integrity in Security Design:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: Confidentiality, Integrity, VPN, API, TLS, decryption, HIPAA. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Unprotected Enterprise Data:** Explains network access control patterns: strong 802.1X authentication where possible, MAB for constrained devices, WebAuth for guest/BYOD flows, and authorization changes driven by policy. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Data Encryption:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: Confidentiality, Integrity, API, TLS, decryption, compliance, HIPAA. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Types of Encryption:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: TLS, decryption. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Best Practices for Encryption:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Additional Data Security Measures:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: DLP, MFA. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Encryption and Data Integrity in Use:** Covers data-flow protection, including encryption, integrity, decryption strategy, DLP policy, privacy constraints, and controls for data at rest, in use, and in transit. Key terms: Integrity, firewall, VPN, TLS, decryption. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Security by Design: Embedding Security in Development Lifecycles

**Page summary:** Summarizes Layer 7 application protection, including how WAF/WAAP and CDN-integrated controls protect web apps, APIs, content delivery paths, and origin infrastructure.
**Key terms:** Integrity, IAM, least privilege, threat modeling, STRIDE, Kubernetes, DevSecOps, OWASP.

**Subsection notes**

- **Security by Design: Embedding Security in Development Lifecycles:** Summarizes Layer 7 application protection, including how WAF/WAAP and CDN-integrated controls protect web apps, APIs, content delivery paths, and origin infrastructure. Key terms: Integrity, OWASP. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Constant State of Evolution:** Explains network access control patterns: strong 802.1X authentication where possible, MAB for constrained devices, WebAuth for guest/BYOD flows, and authorization changes driven by policy. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Rushing to Meet Business Goals:** Explains network access control patterns: strong 802.1X authentication where possible, MAB for constrained devices, WebAuth for guest/BYOD flows, and authorization changes driven by policy. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Security by Design:** Summarizes Layer 7 application protection, including how WAF/WAAP and CDN-integrated controls protect web apps, APIs, content delivery paths, and origin infrastructure. Key terms: Integrity, threat modeling, STRIDE, Kubernetes, OWASP. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Embedding Security in the SDLC:** Summarizes Layer 7 application protection, including how WAF/WAAP and CDN-integrated controls protect web apps, APIs, content delivery paths, and origin infrastructure. Key terms: IAM, least privilege, threat modeling, STRIDE, OWASP, ransomware. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Infrastructure Tools with Embedded Security:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: IAM, Kubernetes, RBAC. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Adopting DevSecOps for Holistic Security:** Explains how security is embedded into delivery workflows through code review, secret protection, dependency checks, IaC validation, container scanning, API testing, and deployment gates. Key terms: DevSecOps, OWASP, NIST, compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.

### Visibility and Observability of Network Activities

**Page summary:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response.
**Key terms:** Integrity, Zero Trust, firewall, NGFW, VPN, IDS, IPS, IDS/IPS.

**Subsection notes**

- **Visibility and Observability of Network Activities:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Key terms: firewall, IPS, XDR, data center, API, observability, compliance, telemetry. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Lack of Network Visibility:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Key terms: Integrity, observability, compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Visibility in Network Security:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Visibility Sources and Tools:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Key terms: Integrity, firewall, NGFW, VPN, IDS, IPS, IDS/IPS, endpoint. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Observability in Network Security:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Key terms: observability. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Observability Tools:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Key terms: Zero Trust, firewall, IDS, IPS, IDS/IPS, segmentation, microsegmentation, endpoint. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Visibility and Observability Combined:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Key terms: endpoint, observability, telemetry. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Implementation Strategies:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Key terms: observability. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Visibility and Observability in Use:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Key terms: observability, compliance. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Visibility:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Observability:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Use the subsection to connect architecture placement, policy, visibility, and operations.

### Design Practice Activity 1: Zero Trust Migration for Legacy Access Control

**Page summary:** Frames identity as a core enforcement layer. Access decisions should account for user, role, device trust, authentication strength, context, and ongoing authorization.
**Key terms:** CIA, Integrity, Availability, Zero Trust, firewall, VPN, IDS, segmentation.

**Subsection notes**

- **Design Practice Activity 1: Zero Trust Migration for Legacy Access Control:** Frames identity as a core enforcement layer. Access decisions should account for user, role, device trust, authentication strength, context, and ongoing authorization. Key terms: CIA, Integrity, Availability, Zero Trust, firewall, VPN, IDS, segmentation. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Design Practice Activity 2: Designing Resilient Perimeter Security for a Hybrid Workforce

**Page summary:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering.
**Key terms:** Availability, firewall, VPN, IDS, IPS, IDS/IPS, segmentation, endpoint.

**Subsection notes**

- **Design Practice Activity 2: Designing Resilient Perimeter Security for a Hybrid Workforce:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: Availability, firewall, VPN, IDS, IPS, IDS/IPS, segmentation, endpoint. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Design Practice Activity 3: Secure Segmentation of Multi-Tenant Infrastructure

**Page summary:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering.
**Key terms:** Confidentiality, IAM, least privilege, firewall, segmentation, DNS, MFA, data center.

**Subsection notes**

- **Design Practice Activity 3: Secure Segmentation of Multi-Tenant Infrastructure:** Explains firewall selection and design with emphasis on application-aware policy, threat inspection, segmentation, centralized management, and the move beyond port/protocol filtering. Key terms: Confidentiality, IAM, least privilege, firewall, segmentation, DNS, MFA, data center. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Design Practice Activity 4: Business Continuity-Driven Security Design

**Page summary:** Treats continuity and recovery as part of secure design, emphasizing backups, redundancy, restoration order, availability objectives, and tested response plans.
**Key terms:** Availability, firewall, IDS, IPS, IDS/IPS, segmentation, endpoint, EDR.

**Subsection notes**

- **Design Practice Activity 4: Business Continuity-Driven Security Design:** Treats continuity and recovery as part of secure design, emphasizing backups, redundancy, restoration order, availability objectives, and tested response plans. Key terms: Availability, firewall, IDS, IPS, IDS/IPS, segmentation, endpoint, EDR. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### Summary

**Page summary:** Explains network access control patterns: strong 802.1X authentication where possible, MAB for constrained devices, WebAuth for guest/BYOD flows, and authorization changes driven by policy.
**Key terms:** Integrity, Zero Trust, least privilege, observability.

## Security and Design Frameworks

### Introduction

**Page summary:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ.
**Key terms:** SASE, SAFE, NIST, MITRE ATT&CK, CAPEC.

### MITRE ATTACK Framework

**Page summary:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ.
**Key terms:** Integrity, endpoint, DNS, MITRE ATT&CK.

**Subsection notes**

- **MITRE ATTACK Framework:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: Integrity, DNS, MITRE ATT&CK. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Risk Identification and Evaluation:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: MITRE ATT&CK. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **The MITRE ATT&CK Framework Defined:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: MITRE ATT&CK. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **MITRE ATT&CK Usage:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: endpoint, MITRE ATT&CK. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **MITRE ATT&CK Resources:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: MITRE ATT&CK. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **MITRE ATT&CK Navigator:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: MITRE ATT&CK. Tie the subsection back to risk reduction, attacker paths, and incident visibility.

### Common Attack Pattern Enumeration and Classification (CAPEC)

**Page summary:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ.
**Key terms:** threat modeling, MFA, NIST, MITRE ATT&CK, CAPEC, compliance, RBAC.

**Subsection notes**

- **Common Attack Pattern Enumeration and Classification (CAPEC):** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: MITRE ATT&CK, CAPEC. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Threat Identification and Evaluation:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: MITRE ATT&CK, CAPEC. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **CAPEC and the MITRE ATT&CK Framework:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: threat modeling, MITRE ATT&CK, CAPEC. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Role of CAPEC in Security Design:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: NIST, CAPEC, compliance. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **The CAPEC Structured Approach:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: MITRE ATT&CK, CAPEC. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **CAPEC in Use:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: MFA, MITRE ATT&CK, CAPEC, compliance, RBAC. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.

### NIST Risk Management Framework

**Page summary:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ.
**Key terms:** IDS, SIEM, NIST, MITRE ATT&CK, CAPEC, CSF, compliance.

**Subsection notes**

- **NIST Risk Management Framework:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: NIST, CSF. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Addressing Enterprise Network Risks:** Explains network access control patterns: strong 802.1X authentication where possible, MAB for constrained devices, WebAuth for guest/BYOD flows, and authorization changes driven by policy. Key terms: NIST, MITRE ATT&CK, CAPEC, CSF. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **The NIST Cybersecurity Framework Overview:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: NIST, CSF, compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **The NIST Cybersecurity Framework Core:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: NIST, CSF. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **NIST CSF Core - Functions:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: IDS, SIEM, NIST, CSF, compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **NIST CSF Core - Categories and Subcategories:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: NIST, CSF. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **NIST CSF Core - Implementation Examples:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: NIST, CSF. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **The NIST Cybersecurity Framework Profiles:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: NIST, CSF. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **The NIST Cybersecurity Framework Implementation Tiers:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: NIST, CSF, compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.

### Secure Access Service Edge (SASE)

**Page summary:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ.
**Key terms:** IAM, Zero Trust, firewall, VPN, IPS, endpoint, DLP, DNS.

**Subsection notes**

- **Secure Access Service Edge (SASE):** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: Zero Trust, firewall, VPN, IPS, DLP, DNS, SASE, CASB. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Edge Security Challenge:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: SASE. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **The SASE Model:** Covers emerging technology impacts, including AI-assisted detection and security workflows, model governance and oversight, and cryptographic planning for quantum-era risk. Key terms: SASE, SD-WAN. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Comparison of SASE and Traditional Security:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: Zero Trust, VPN, SASE. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **SASE Technologies:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: IAM, Zero Trust, firewall, DLP, SASE, CASB, ZTNA, MFA. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Benefits of SASE:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: Zero Trust, firewall, DLP, SASE, CASB, ZTNA, SD-WAN, HIPAA. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **SASE Implementation:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ. Key terms: Zero Trust, firewall, endpoint, DLP, SASE, CASB, ZTNA, SD-WAN. Tie the subsection back to risk reduction, attacker paths, and incident visibility.

### Summary

**Page summary:** Explains how frameworks and risk methods guide control selection, architecture mapping, governance, and documented tradeoffs when requirements or constraints differ.
**Key terms:** SASE, NIST, MITRE ATT&CK, CAPEC.

## Compliance and Regulatory Requirements

### Introduction

**Page summary:** Maps security design to compliance obligations through control evidence, accountability, monitoring, reporting, audit readiness, and documented exceptions.
**Key terms:** compliance.

### Regulatory Compliance for Security Designs

**Page summary:** Maps security design to compliance obligations through control evidence, accountability, monitoring, reporting, audit readiness, and documented exceptions.
**Key terms:** Confidentiality, Integrity, Availability, segmentation, NIST, audit, compliance, HIPAA.

**Subsection notes**

- **Regulatory Compliance for Security Designs:** Maps security design to compliance obligations through control evidence, accountability, monitoring, reporting, audit readiness, and documented exceptions. Key terms: Integrity, segmentation, audit, compliance, HIPAA. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Compliance Requirements:** Maps security design to compliance obligations through control evidence, accountability, monitoring, reporting, audit readiness, and documented exceptions. Key terms: Confidentiality, Integrity, audit, compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Industry-Specific Regulations:** Maps security design to compliance obligations through control evidence, accountability, monitoring, reporting, audit readiness, and documented exceptions. Key terms: Confidentiality, Integrity, Availability, NIST, compliance, HIPAA. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Regional and Local Regulations:** Maps security design to compliance obligations through control evidence, accountability, monitoring, reporting, audit readiness, and documented exceptions. Key terms: compliance. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Information Security Standards:** Maps security design to compliance obligations through control evidence, accountability, monitoring, reporting, audit readiness, and documented exceptions. Key terms: NIST, compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Regulatory Compliance Practices:** Maps security design to compliance obligations through control evidence, accountability, monitoring, reporting, audit readiness, and documented exceptions. Key terms: segmentation, compliance. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Compliance Documentation and Accountability:** Maps security design to compliance obligations through control evidence, accountability, monitoring, reporting, audit readiness, and documented exceptions. Key terms: compliance, HIPAA. Tie the subsection back to risk reduction, attacker paths, and incident visibility.

### Compliance Monitoring and Reporting

**Page summary:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response.
**Key terms:** Integrity, IAM, least privilege, endpoint, EDR, DLP, MFA, SIEM.

**Subsection notes**

- **Compliance Monitoring and Reporting:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Key terms: Integrity, compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Challenges to Meeting Compliance Requirements:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Key terms: compliance, HIPAA. Use the subsection to connect architecture placement, policy, visibility, and operations.
- **Compliance Monitoring Strategies:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Key terms: compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Real-Time Surveillance and Automated Monitoring:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Integration of Compliance Tools:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Key terms: IAM, endpoint, EDR, SIEM, NIST, audit, compliance, HIPAA. Tie the subsection back to risk reduction, attacker paths, and incident visibility.
- **Periodic Internal and External Audits:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Key terms: audit, compliance, HIPAA. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.
- **Incident Response and Documentation:** Summarizes secure connectivity design, balancing encryption, authentication, routing, failover, application performance, segmentation, and inspection across remote access, WAN, and cloud tunnels. Key terms: Integrity, least privilege, DLP, MFA, compliance, ransomware. Use this as scenario practice: identify the requirement, choose controls, and defend the tradeoff.
- **Compliance Reporting Best Practices:** Connects architecture to operations by summarizing how telemetry, event correlation, automation, observability, and runtime instrumentation support detection and response. Key terms: compliance. Pay attention to design considerations, best practices, operational limits, and measurable outcomes.

### Summary

**Page summary:** Maps security design to compliance obligations through control evidence, accountability, monitoring, reporting, audit readiness, and documented exceptions.
**Key terms:** audit, compliance.

