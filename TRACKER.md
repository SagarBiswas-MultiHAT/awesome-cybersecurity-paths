# Cybersecurity Career Readiness & Study Tracker

> **Tip:** Fork this repository and use this tracker directly on GitHub to mark your progress as you study and build your home lab.

---

## Phase 0: Core Technical Foundations

Before specializing in offensive, defensive, or GRC tracks, master these shared core competencies:

- [ ] **Computing Foundations**
  - [ ] Understand OS architecture (processes, threads, virtual memory, kernel vs user space)
  - [ ] Linux command line proficiency (bash scripting, permissions, systemd, cron, package managers)
  - [ ] Windows administration core (Active Directory, PowerShell, Registry, Event Viewer)
- [ ] **Networking Foundations**
  - [ ] OSI 7-Layer Model and TCP/IP stack in depth
  - [ ] Protocol mechanics (DNS, DHCP, ARP, HTTP/HTTPS, SSH, TLS/SSL)
  - [ ] Subnetting, routing tables, and CIDR notation
  - [ ] Packet capture and analysis using Wireshark and tcpdump
- [ ] **Basic Programming & Automation**
  - [ ] Python scripting for automation, API interaction, and log parsing
  - [ ] Bash or PowerShell scripting for system administration
  - [ ] Git version control basics (branches, commits, remotes)

---

## Phase 1: Environment & Practical Lab Setup

Practical hands-on experience is mandatory for security hiring:

- [ ] **Home Lab Deployment**
  - [ ] Set up virtualization hypervisor (VirtualBox, VMware Workstation, or Proxmox VE)
  - [ ] Deploy a Kali Linux or Parrot OS testing machine
  - [ ] Deploy a minimal Active Directory domain controller (Windows Server evaluation)
  - [ ] Deploy at least one Linux target (Ubuntu / Debian) and one Windows workstation
  - [ ] Configure isolated host-only virtual networking
- [ ] **Practice Platform Enrolment**
  - [ ] Complete beginner rooms on TryHackMe (Complete Beginner or Pre-Security path)
  - [ ] Complete introductory modules on PortSwigger Web Security Academy
  - [ ] Solve foundational blue team challenges on CyberDefenders or Blue Team Labs Online

---

## Phase 2: Pillar Selection & Deep Dive

Select your primary direction and work through the key specializations detailed in the handbook:

### Path A: Offensive Security (Red Team / Pen Testing)
- [ ] Complete Network Penetration Testing fundamentals ([Section 2.1.1](chapters/04-chapter-2.md#211-network-penetration-testing))
- [ ] Master Web Application Penetration Testing and OWASP Top 10 ([Section 2.1.3](chapters/04-chapter-2.md#213-web-application-penetration-testing))
- [ ] Practice privilege escalation techniques on Linux and Windows
- [ ] Understand Active Directory attack paths (Kerberoasting, AS-REP roasting, DCSync)
- [ ] Review the Red Team Operation Lifecycle diagram (`media/5. Red Team Operation Lifecycle.svg`)
- [ ] Target Certification: eJPT, PNPT, or OSCP

### Path B: Defensive Security (Blue Team / SOC / DFIR)
- [ ] Learn Security Operations Center (SOC) alert triage and log analysis ([Section 3.1.5](chapters/05-chapter-3.md#315-security-operations-soc))
- [ ] Master SIEM querying with Splunk (SPL) or Elastic (KQL)
- [ ] Understand Endpoint Detection and Response (EDR) telemetry and alert triage
- [ ] Practice Digital Forensics and Incident Response (DFIR) artifact analysis ([Section 3.2.1](chapters/05-chapter-3.md#321-digital-forensics))
- [ ] Review the Incident Response Lifecycle diagram (`media/6. The Incident Response Lifecycle.svg`)
- [ ] Target Certification: CompTIA Security+, BTL1, or SC-200

### Path C: Governance, Risk, and Compliance (GRC)
- [ ] Understand risk management frameworks: NIST CSF 2.0, ISO 27001, and CIS Controls
- [ ] Practice qualitative and quantitative risk assessments (FAIR methodology)
- [ ] Learn regulatory requirements: GDPR, HIPAA, PCI DSS, SOC 2
- [ ] Review the Board Strategy to Operational Control diagram (`media/10. From Board Strategy to Operational Control.svg`)
- [ ] Target Certification: CompTIA Security+, CRISC, or CISA

---

## Phase 3: Portfolio & Professional Presence

Demonstrate proof of work to employers and peers:

- [ ] Publish at least two detailed technical write-ups (lab walkthrough, tool deep dive, or incident analysis)
- [ ] Document home lab architecture with network topology diagrams
- [ ] Contribute to an open-source security project or curated tool list
- [ ] Engage with local or online infosec communities (BSides, DEF CON groups, OWASP chapters)
- [ ] Tailor your resume around concrete projects, tools used, and methodologies applied
