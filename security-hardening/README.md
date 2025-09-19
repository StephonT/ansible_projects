This ansible project is building a security hardening: CIS-style Linux Baseline as a reusable Ansible role that I can drop into any environment (RHEL 8/9, CentOS 9, Alma/Rocky, Ubuntu LTS).

CIS = Center for Internet Security
These are step-by-step guidelines for securely configuring systems (Linux, Windows, network devices, cloud services, etc.). This role will be providing CIS hardening for a Linux system. For Linux, CIS benchmarks cover areas like:

- Boot and services (e.g., disable unused services, ensure SELinux/AppArmor is enabled).

- Authentication and Authorization (e.g./ strong password policies, lockout after a # of failed attempts)

- Network Configuration (e.g./ firewall rules, disable IPv6 if not used)

- File permissions and ownership (e.g., restrict access to /etc/passwd, /etc/shadow)

- Logging and auditing (e.g., auditd rules, rsyslog configuration)


