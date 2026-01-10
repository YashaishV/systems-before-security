# IT → Networking → Systems → Security

## 60-Day Deep Foundation Roadmap (2 Hours/Day)


This is **not surface-level**. This roadmap *emphasizes*:

* Repetition
* Real labs
* Logs, configs, failures, fixes
* Admin + security thinking together

---

## ROADMAP PRINCIPLES (READ THIS FIRST)

* **2 hours/day max** (non-negotiable)
* Depth > speed
* Every concept → at least one lab
* Document everything

---

## REPO STRUCTURE (MANDATORY)

```
/it-cyber-foundation
  /week-01-02-os-fundamentals
  /week-03-04-networking
  /week-05-sysadmin
  /week-06-security-basics
  /week-07-security-ops
  /week-08-integration
  /notes
  /labs
  /configs
  /scripts
```

Daily output:

* `notes/day-XX.md`
* `labs/day-XX.md`
* screenshots / configs when possible

---

# WEEKS 1–2 — OPERATING SYSTEMS (REAL DEPTH)

**Target:** Understanding OS behavior, failures, logs, and administration.

---

## Windows (Primary)

### Topics

* Boot process
* Users, groups, policies
* Services & scheduling
* Event Viewer (Security, System, Application)
* NTFS permissions
* Patch management

### Core Resources

* [https://learn.microsoft.com/en-us/windows-server/](https://learn.microsoft.com/en-us/windows-server/)
* [https://learn.microsoft.com/en-us/sysinternals/](https://learn.microsoft.com/en-us/sysinternals/)
* [https://www.youtube.com/@NTFAQGuy](https://www.youtube.com/@NTFAQGuy)

### Practice Labs

* Create standard vs admin users
* Break permissions → fix access
* Track failed logins via Event Viewer
* Disable/enable services safely

---

## Linux (Admin View)

### Topics

* Filesystem hierarchy
* Users, groups, sudo
* Permissions & ACLs
* Services & logs

### Core Resources

* [https://linuxjourney.com/](https://linuxjourney.com/)
* [https://training.linuxfoundation.org/resources/free-courses/](https://training.linuxfoundation.org/resources/free-courses/)
* [https://ubuntu.com/tutorials](https://ubuntu.com/tutorials)

### Practice Labs

* Create users & groups
* Break permissions → recover
* Analyze `/var/log/auth.log`

---

# WEEKS 3–4 — NETWORKING (STRONG CORE)

**Target:** Diagnose and reason networks confidently.

---

## Core Networking

### Topics

* OSI & TCP/IP mapping
* IP addressing & subnetting
* ARP, ICMP
* DNS & DHCP internals

### Resources

* [https://www.cloudflare.com/learning/network-layer/](https://www.cloudflare.com/learning/network-layer/)
* [https://subnettingpractice.com/](https://subnettingpractice.com/)
* [https://www.youtube.com/@NetworkChuck](https://www.youtube.com/@NetworkChuck)

### Practice

* Manual subnet design
* DNS failure simulation
* Tracing packets

---

## Hands-on Networking

### Tools

* Cisco Packet Tracer
* Wireshark

### Resources

* [https://www.netacad.com/courses/packet-tracer](https://www.netacad.com/courses/packet-tracer)
* [https://www.wireshark.org/docs/](https://www.wireshark.org/docs/)
* [https://www.youtube.com/@ChrisGreer](https://www.youtube.com/@ChrisGreer)

### Labs

* Build LAN
* Capture DNS, HTTP traffic
* Identify abnormal packets

---

# WEEK 5 — SYSTEM & NETWORK ADMINISTRATION

**Target:** Be able to operate smoothly

---

## Identity & Access

* Active Directory concepts
* RBAC
* Least privilege

Resources:

* [https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/)

Labs:

* User onboarding/offboarding
* Access review simulation

---

## IT Operations

* Ticket lifecycle
* Root Cause Analysis
* Change management

Resources:

* [https://www.atlassian.com/incident-management](https://www.atlassian.com/incident-management)

Labs:

* Write incident tickets
* Perform RCA on failures

---

# WEEK 6 — SECURITY FOUNDATIONS (REAL WORLD)

**Target:** Understanding why security controls exist.

---

## Security Fundamentals

* CIA Triad
* Threat modeling
* Vulnerabilities

Resources:

* [https://www.nist.gov/cyberframework](https://www.nist.gov/cyberframework)
* [https://owasp.org/www-project-top-ten/](https://owasp.org/www-project-top-ten/)

Labs:

* Map threats to assets

---

## Malware & Attacks

Resources:

* [https://www.malwarebytes.com/cybersecurity](https://www.malwarebytes.com/cybersecurity)
* [https://attack.mitre.org/](https://attack.mitre.org/)

Labs:

* Study real attack chains

---

# WEEK 7 — SECURITY OPERATIONS

**Target:** SOC‑level exp.

---

## Logs & SIEM

* Log sources
* Correlation

Resources:

* [https://www.splunk.com/en_us/resources/what-is-siem.html](https://www.splunk.com/en_us/resources/what-is-siem.html)
* [https://tryhackme.com/path/outline/soc-level-1](https://tryhackme.com/path/outline/soc-level-1)

Labs:

* Identify suspicious login patterns

---

## Incident Response

Resources:

* [https://www.sans.org/white-papers/incident-handlers-handbook/](https://www.sans.org/white-papers/incident-handlers-handbook/)

Labs:

* Write IR playbooks

---

# WEEK 8 — INTEGRATION & JOB READINESS

**Target:** Connect IT + Security seamlessly.

---

## Home Lab (Lightweight)

* VirtualBox
* Linux + Windows VMs

Resources:

* [https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads)

---

## Attack Awareness (Defensive Focus)

Resources:

* [https://tryhackme.com/path/outline/presecurity](https://tryhackme.com/path/outline/presecurity)

---

## Final Deliverables

* 60 days of notes
* Labs & configs
* Clear role direction

---

## FINAL TRUTH

> Trust the process, hold the vision
