---
title: "Cyber Security"
layout: cybersecurity
author_profile: true
---
---
title: "My Insights into Azure Security Fundamentals & Core Infrastructure Services"
date: 2025-06-11
author: "Anne Musau"
tags: ["Azure", "Cloud Security", "Infrastructure", "Microsoft"]
---

# Azure Security Fundamentals & Core Infrastructure Services

## Introduction

After completing a deep dive into Microsoft’s security modules, it became clear how comprehensive Azure’s approach to cloud security really is. This article is a brief reflection of key concepts and tools explored throughout the learning journey.

## Security Concepts

- **Shared Responsibility Model**: Cloud security is a joint effort—while the provider secures the infrastructure, customers are responsible for protecting data, identities, and configurations.
- **Defense-in-Depth**: A layered security strategy is used to provide multiple lines of defense, including firewalls, encryption, and identity protection.
- **Zero Trust Model**: This model assumes breach and enforces verification at every access point, eliminating implicit trust within the network.
- **Encryption & Hashing**: Encryption protects data at rest and in transit, while hashing ensures data integrity.
- **Governance, Risk, and Compliance (GRC)**: These elements help align technical controls with organizational policies and regulatory requirements.
- **CIA Triad**: Confidentiality, Integrity, and Availability are the foundation of all security strategies.
- **Risk Management**: A structured process of identifying, assessing, and mitigating potential threats is essential to maintaining secure systems.

## Azure Security Tools

Several Azure-native tools are available to strengthen security posture:

- **Azure DDoS Protection**: Automatically mitigates distributed denial-of-service attacks to ensure availability.
- **Azure Firewall & Web Application Firewall (WAF)**: Provide centralized, scalable protection against network and web-based attacks.
- **Network Security Groups (NSGs)**: Enable control of traffic flow at the subnet and virtual machine level.
- **Azure Bastion**: Offers secure RDP and SSH access to virtual machines without exposing them to the public internet.
- **Azure Key Vault**: A secure service for storing secrets, keys, and certificates.

## Security Management in Practice

Azure also offers integrated services for managing and monitoring security:

- **Cloud Security Posture Management (CSPM)**: Continuously assesses resource configurations and identifies potential vulnerabilities.
- **Cloud Workload Protection**: Secures workloads such as virtual machines and containers against known threats.
- **DevOps Security**: Security tools can be integrated directly into CI/CD pipelines to enforce policies and detect issues early in the development lifecycle.

## Conclusion

These foundational security principles and Azure tools support the development of secure, resilient cloud environments. With a clear strategy and the right services in place, organizations can confidently protect their infrastructure and data in the cloud.
