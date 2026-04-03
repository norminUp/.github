# NorminUp — Next-Generation SaaS Monitoring Platform

[Version Française](README.fr.md)

![NorminUp Banner](https://img.shields.io/badge/NorminUp-v1.1.0-10B981?style=for-the-badge&logo=activity)
![Status](https://img.shields.io/badge/Status-Operational-10B981?style=for-the-badge)
![License](https://img.shields.io/badge/License-Proprietary-blue?style=for-the-badge)

**NorminUp** is a high-end SaaS monitoring solution designed for total visibility and distributed resilience. Combining state-of-the-art **Glassmorphism** aesthetics with industrial diagnostic intelligence, NorminUp allows companies to secure their critical infrastructure with surgical precision.

---

## 1. Visual Experience & UX
NorminUp redefines the monitoring interface with a native **Dark Mode** design and exceptional fluidity.
*   **Glassmorphism Identity**: Frosted cards, background blurs, and ultra-thin borders for a modern, focused interface.
- **Status Widgets**: Embeddable dynamic widgets to display service status directly on your customer sites.
- **Behavioral Animations**: Smooth micro-interactions and radar pulses for immersive real-time feedback.

---

## 2. Multimodal Monitoring & Protocols
Beyond simple "pinging," NorminUp monitors over **11 types of protocols**:
- **Web & API**: HTTP/S (GET/POST), WebSocket (WSS), Heartbeats.
- **Network & DNS**: TCP, ICMP (Ping), DNS (Propagation), Domain (Whois/Expiration).
- **Business Services**: Discord Bots (Presence), Docker (Runtime), Databases (MySQL/Redis), Payment Gateways.
- **Rapid-Fire Verification**: Intelligent network "blip" filtering through incremental retries before alert confirmation.

---

## 3. Diagnostics
In case of an incident, NorminUp doesn't just report the failure; it analyzes it in depth:
*   **MD5 Content Integrity**: Detection of "Shadow Hacks" by comparing page fingerprints with previous states.
*   **SSL Chain Audit**: Full certificate analysis, including issuer and validity dates.
*   **Redirect Chain Trace**: Complete audit of redirection chains (up to 5 levels) to detect infinite loops.
*   **Security Header Scoring**: Real-time evaluation of HSTS, CSP, X-Frame-Options, and XSS-Protection headers.

---

## 4. Edge Resilience & P2P
A unique distributed architecture for unfailing reliability:
- **Distributed Consensus**: Edge agents communicate with each other via the **Gossip** protocol to confirm an outage from multiple geographic points (eliminating false positives).
- **Survival Mode**: If the master server is unreachable, agents switch to total autonomy to send alerts directly via SMTP, Slack, or Discord.
- **Edge Analytics**: Local metric buffering during temporary network disconnections.

---

## 5. Infrastructure & Extension
- **Dynamic SSL (Caddy Ask)** : Automated SSL certificate management for custom domains (CNAME).
- **Self-Healing Docker**: Automated remediation (container restarts) via the Dockerode API.
- **Public API & Reference**: Full documentation for programmatic integration of monitoring services.

---

<p align="center">
  <b>NorminUp SaaS</b> • Excellence in infrastructural resilience. <br>
  <i>© 2026. All rights reserved.</i>
</p>
