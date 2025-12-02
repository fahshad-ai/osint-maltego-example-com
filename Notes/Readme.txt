Project Title

OSINT-Based Domain Footprinting & Attack Surface Mapping using Maltego

Overview

This project demonstrates an OSINT investigation using Maltego to discover publicly exposed infrastructure of a target domain.
The goal is to identify DNS records, reachable systems, public web services, and potential phishing or impersonation risks that could be exploited by attackers.

Key Objectives

Perform reconnaissance on a publicly accessible domain using only OSINT tools.

Enumerate subdomains, DNS records, servers, and service relationships.

Identify phishing, spoofing, and attack surface exposure risks.

Document findings for visibility and security improvement.

Tools & Resources Used
Tool	Purpose
Maltego CE	Infrastructure footprinting & relationship mapping
crt.sh	Certificate transparency lookup
DNSTwister	Typo-squatting domain detection
IntelligenceX	Leak and data exposure checks
HaveIBeenPwned (optional)	Exposure status for breached emails
Methodology (High-Level)

Collected primary domain information

Mapped external DNS and mail infrastructure

Extracted subdomains and service relationships

Verified active endpoints and connected IPs

Searched for phishing or impersonation risks

Documented all findings and security insights

Findings Summary
Category	Observation	Security Impact
Infrastructure Exposure	Public DNS and mail servers identified	Reconnaissance advantage for attackers
Subdomain Enumeration	Multiple user-facing domains exposed	Phishing/credential theft risk
Typo-squatting Opportunities	Similar domains available	Could host spoofed login pages
Certificate Transparency	Historical certificates exposed	Insights into internal services

Detailed results are available in the Final Report.

Deliverables Included
Folder	Description
Screenshots	Evidence from each investigation step
Notes	Day-by-day findings & observations
Graph	Maltego investigation map (.maltego export)
Final Report	Full OSINT case study in PDF
Resources	All reference tools and links used
Skills Gained

OSINT investigation using Maltego

Threat intelligence and attack surface analysis

DNS & subdomain enumeration techniques

Identifying phishing and impersonation risks

Professional security reporting skills

Author

Fahshad
Cybersecurity Student | OSINT & Pentesting Learner
(fahshadaju@gmail.com, https://www.linkedin.com/in/fahshad-m-48134a1aa/ )

Disclaimer

This analysis was conducted only on publicly available information and purely for educational and security research purposes.