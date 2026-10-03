# CompTIA Security+ SY0-701

This section documents my hands-on laboratory work and practical training while preparing for the **CompTIA Security+ SY0-701** certification.

The goal is to go beyond theoretical study by implementing, testing, troubleshooting, and documenting security concepts from the certification objectives in a **dedicated virtualized cybersecurity home-lab environment**.

[Back to Cybersecurity Portfolio](../)

---

## Lab Environment

The Security+ labs are performed primarily in a virtualized environment built with **Proxmox**.

### Platforms and Operating Systems

- Kali Linux
- Ubuntu Server
- Windows 11
- pfSense
- OpenWrt

### Security and Network Tools

- UFW
- OpenSSH
- Nginx
- Wireshark
- PowerShell Get-FileHash
- auditd, auditctl, and ausearch

**Wazuh** is planned for later monitoring-focused labs as the environment expands.

### Areas Practiced

- Network segmentation
- Host-based firewall configuration
- Access control
- File integrity verification
- Authentication, authorization, and accounting
- Linux user, group, and file-permission administration
- Security auditing and deception
- Security logging and event analysis
- Positive and negative testing
- Secure service configuration
- Troubleshooting
- Backup, recovery, and service validation

The environment will continue evolving as additional Security+ objectives and cybersecurity scenarios are implemented.

---

## Security+ Labs

### Domain 1 - General Security Concepts

| Objective | Lab | Topics | Status |
|---|---|---|---|
| 1.1 | [Security Controls](Labs/01-Security-Controls/) | Preventive, detective, directive, compensating, and corrective controls | Completed |
| 1.2 | [Fundamental Security Concepts](Labs/02-Fundamental-Security-Concepts/) | Integrity, authentication, authorization, accounting, deception, and auditing | Completed |
| 1.3 | [Change Management](Labs/03-Change-Management/) | Change planning, impact analysis, controlled scope changes, dependencies, version control, and backout validation | Completed |

Additional laboratories will be added as I progress through the Security+ SY0-701 objectives.

---

## Practical Approach

Each laboratory is designed around practical implementation and validation rather than configuration alone.

The general methodology includes:

1. Define the security objective.
2. Establish a known-good baseline.
3. Implement the security control.
4. Validate expected behavior.
5. Perform positive and negative testing.
6. Generate and analyze security evidence.
7. Troubleshoot failures when applicable.
8. Restore or recover the environment.
9. Document commands, results, and lessons learned.

---

## Skills Demonstrated in Current Labs

The completed labs currently document practical experience with:

- Linux administration
- Host-based firewall configuration
- Access-control enforcement
- SHA-256 file-integrity verification
- Linux user and group administration
- Unix ownership and permissions
- Authentication and accounting log review
- auditd file-access monitoring
- Honeyfile-based deception
- Firewall logging
- Security event analysis
- Positive and negative validation testing
- SSH service configuration
- Web-service configuration and validation
- Troubleshooting
- Backup and recovery
- Security-control classification
- Change planning and impact analysis
- Controlled scope changes and dependency troubleshooting
- Git-based configuration version control
- Service restart and post-change validation
- Backout planning and firewall-rule cleanup

This section will expand as additional Security+ labs are completed.

---

## Documentation

Each lab contains its own `README.md` and supporting evidence. Depending on the objective, documentation includes:

- Lab objectives
- Environment details
- Commands and configuration changes
- Step-by-step implementation
- Screenshots and evidence
- Positive and negative tests
- Troubleshooting analysis
- Security+ concept mapping
- Lessons learned
- Final validation

This repository is intended to serve both as a record of my Security+ preparation and as evidence of practical cybersecurity skills.
