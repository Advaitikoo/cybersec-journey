\# Cybersecurity Journey



\*\*Started:\*\* May 10, 2026  

\*\*Background:\*\* AI/ML developer pivoting to cybersecurity  

\*\*Goal:\*\* SOC analyst or security engineering role within 6 months



\## Why I'm Switching



Built AI tools (RAG systems, chatbots) and kept finding security gaps I didn't know how to fix — hardcoded API keys, no input validation, exposed endpoints. Got obsessed with understanding why those mattered and how to prevent them.



\## Current Status



| Skill | Level | Evidence |

|-------|-------|----------|

| Linux | Beginner | Ubuntu daily driver (switching today) |

| Networking | Beginner | Roadmap.sh course in progress |

| Security tools | None | Starting TryHackMe |

| Scripting | Basic Python | Previous AI projects |



\## 30-Day Goals (May 10 - June 10)



\- \[ ] Complete TryHackMe Pre-Security path

\- \[ ] Complete TryHackMe Complete Beginner path

\- \[ ] Set up home lab: Kali VM + target VMs

\- \[ ] Write 5 CTF writeups

\- \[ ] Build one security tool (TBD)



\## 60-Day Goals (May 10 - July 10)



\- \[ ] Rank in top 10% on TryHackMe

\- \[ ] 10 published CTF writeups

\- \[ ] Functional home lab with documented network diagram

\- \[ ] Security audit of one old AI project

\- \[ ] Apply to 20 SOC analyst roles



\## Daily Log



\### 2026-05-10

\- Created this repo

\- Started roadmap.sh ethical hacking course

\- Switching to Ubuntu daily driver in the next week 

\- First TryHackMe room



\## Resources



\- \[TryHackMe](https://tryhackme.com)

\- \[Roadmap.sh Course](https://roadmap.sh/ai/course/ethical-hacking-and-penetration-testing-a-career-pathway)

\- \[PortSwigger Web Security Academy](https://portswigger.net/web-security)


### 2026-05-10 (evening)
- Completed basic intro TryHackMe rooms
- Learned: Networking basics — IP addresses, MAC addresses, MAC spoofing, ping
- MAC spoofing: changing your network interface's MAC address to impersonate another device or bypass filtering
- Ping: basic connectivity test using ICMP echo requests
- Started Pre-Security path
- Tomorrow: Continue Pre-Security, Ubuntu install

  

## Roadmap.sh Ethical Hacking — Lesson 4: Essential Command-Line Interface (CLI) for Network Diagnostics (Windows & Linux)

**Completed:** May 14, 2026

**What I learned:**
- Testing Connectivity using ping and traceroute
- IP Configuration and interface using ipconfig
- Checking Active Connections using Netstat
- Host Discovery and DNS Enumeration

**SOC lens (how to detect/prevent):**
- - **Ping sweeps:** Monitor for sequential ICMP requests across subnets — indicator of reconnaissance
- **Traceroute:** Harder to detect directly, but TTL anomalies or unusual paths can flag tunneling
- **Netstat on endpoints:** EDR tools should baseline normal connections, alert on new listening ports or unusual outbound sessions
- **DNS enumeration:** Log and alert on high-volume DNS queries, zone transfer attempts (AXFR), and subdomain brute-forcing patterns
- **Key takeaway:** Reconnaissance is invisible unless you're logging and correlating. Most orgs don't watch DNS closely enough.

**Hands-on practice:** None yet — theory only

**Time spent:** ~45 min

**Next:** Lesson 5



## Roadmap.sh Ethical Hacking — Lesson 5: Data Protection Essentials: Encryption, Backups, and Secure Authentication

**Completed:** May 15, 2026

**What I learned:**
- Encryption and its 2 main types - Symmetric and Asymmetric
- Using Hash Functions for data integrity
- Secure authorization and what is needed for a secure multi factor authentication (MFA)
- Data Backups and the 3-2-1 rule
- What the industry standard tools are for all above processes 

**Hands-on practice:** None yet — theory only

**Time spent:** ~45 min

**Next:** Lesson 6 

**Note:** Skipped daily commit yesterday. Back on track today.
