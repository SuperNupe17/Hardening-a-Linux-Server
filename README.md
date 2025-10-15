# Hardening-a-Linux-Server
Hardened an Ubuntu Linux server by applying security best practices for SSH, firewall, account policies, and system logging. Configured and secured a Linux-based server environment to defend against unauthorized access, privilege escalation, and service exploitation. Implemented best practices in system configuration, network security, and user management to ensure compliance with security baselines and organizational policy.
Overview:
This project focused on securing and hardening a Linux (Ubuntu) server to reduce vulnerabilities and protect system integrity. The goal was to apply industry-standard security best practices to strengthen authentication, limit access, and enhance system logging and monitoring.

Key Objectives:

Applied system updates and patch management to ensure all software packages were current.

Configured strong password policies and account lockout settings in /etc/pam.d/common-password and /etc/login.defs.

Disabled unnecessary or insecure services to minimize the attack surface.

Edited SSH configuration (/etc/ssh/sshd_config) to enforce key-based authentication, disable root login, and limit idle session timeouts.

Implemented file permissions and ownership policies using chmod, chown, and umask.

Configured and tested the firewall (ufw) to allow only essential inbound traffic (e.g., SSH, HTTP/S).

Enabled and verified system logging through rsyslog and journald, including log rotation to prevent disk overuse.

Installed and configured intrusion detection using AIDE (Advanced Intrusion Detection Environment) to monitor critical file changes.

Documented each configuration step, including before-and-after security checks.

Tools & Technologies:

Ubuntu Server

UFW Firewall

SSH, PAM, and sudo configuration

AIDE / journald / rsyslog

Bash scripting for automation

Outcome:
By the end of the project, the Linux server met baseline security benchmarks for access control, patching, and logging. The configuration reduced exposure to brute-force attacks, improved system auditing, and ensured compliance with general hardening guidelines used in production environments.
