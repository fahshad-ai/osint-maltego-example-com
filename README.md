OSINT Attack Surface Mapping using Maltego
Overview

This project demonstrates a complete OSINT-based reconnaissance of the public domain example.com using Maltego and open-source intelligence tools.
The aim is to identify publicly exposed infrastructure and assess attack surface risks without performing any intrusive security actions.

Objectives

Discover and map DNS records, subdomains, and IP infrastructure

Identify phishing, spoofing, and supply-chain related security risks

Understand attacker reconnaissance methodology

Produce a professional written cybersecurity investigation report

Tools Used
Tool	Purpose

Maltego CE	Infrastructure mapping and entity relationship analysis
crt.sh	Certificate transparency lookup
DNSTwister	Typo-squatting & domain impersonation detection
IntelligenceX	Breach and data exposure analysis
Whois Lookup	Domain information gathering

Methodology (Day-Wise Summary)
Day	Task Completed
Day 1	Setup & project planning
Day 2	DNS and web infrastructure footprinting
Day 3	Subdomain discovery and graph expansion
Day 4	Threat intelligence and breach checks
Day 5	Certificate transparency and typo-squatting analysis
Day 6	Attack surface and risk categorization
Day 7	Final summary and recommendations



Key Findings

Multiple mail and test servers were discovered, increasing phishing and initial access risks

Presence of login-related and support-style subdomains increases impersonation risk

Public VPN endpoint exposure could enable unauthorized internal access if exploited

Dependencies on external services create supply chain threat vectors

OSINT alone provided detailed network exposure insight without direct probing

Deliverables Included
Folder	Description
Screenshots	Visual evidence of OSINT workflow and results
Notes	Day-by-day investigation notes and observations
Graph	Maltego investigation graph export
Final Report	Complete OSINT report in PDF format
Resources	Tools and reference links used

This structure allows recruiters or security reviewers to easily validate findings and process.

Security Recommendations

Enforce DMARC, SPF, and DKIM for email authentication

Monitor and pre-register high-risk typosquatted domains

Reduce unnecessary public DNS exposure

Conduct periodic OSINT-based infrastructure reviews

Provide anti-phishing awareness training to users

Skills Demonstrated

OSINT investigation and documentation

Threat intelligence and attack-surface analysis

Maltego graph-based reconnaissance

Security reporting and presentation

Version control and cybersecurity portfolio building

Author

Fahshad
Cybersecurity Student | OSINT & Threat Intelligence Learner
(fahshadaju@gmail.com, https://www.linkedin.com/in/fahshad-m-48134a1aa/ )


Disclaimer

This project was performed strictly using public information.
No exploitation, scanning, or unauthorized access was conducted.
The sole purpose of this research is cybersecurity education and ethical analysis.
