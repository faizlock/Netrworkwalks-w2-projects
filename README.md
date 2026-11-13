Penetration Testing Report 
        
Footprinting & Network Scanning Phases

W2-PM-FINAL | CYBERSECURITY | NETWORKWALKS

Field	Detail
Pentester Name (Cybersecurity Professional)	Faizan Afridi
Program/Batch	B082-Networkwalks
Date	17 August 2026
Modules Completed	W2-PM1 (Multiple Kali Tools)W2-PM5 (Zenmap Scanning)
Client/Target	1. Networkwalks (secured written permission)2. My own local LAN Network
Permission secured from client?	Yes

⸻

Phase 1: Footprinting

Objective

The objective of this phase was to gather information about the authorized target before performing network scanning.

Tools Used

* Kali Linux
* Nmap
* Zenmap
* WHOIS
* DNS tools

Activities

* Identified target information
* Performed basic network reconnaissance
* Identified available hosts
* Collected network-related information

⸻

Phase 2: Network Scanning

Zenmap / Nmap Scanning

Performed authorized network scanning to identify:

* Live hosts
* Open ports
* Running services
* Service versions
* Potential attack surface

Commands Used

nmap -sV <target-ip>
nmap -sC -sV <target-ip>

All scanning was performed only against authorized targets.

⸻

Findings

Finding	Description	Risk
Open Ports	Identified accessible ports	Medium
Running Services	Identified services running on discovered ports	Medium
Host Discovery	Identified active hosts on the network	Informational

⸻

Evidence

Zenmap Scan

Add your screenshot here:

![Zenmap Scan](screenshots/zenmap-scan.png)

Nmap Results

Add your terminal screenshot here:

![Nmap Results](screenshots/nmap-results.png)

⸻

Conclusion

This project provided practical experience with footprinting, network reconnaissance, host discovery, port scanning, service enumeration, and basic attack-surface identification using Kali Linux and Nmap/Zenmap.

Tools: Kali Linux | Nmap | Zenmap
Focus: Footprinting & Network Scanning