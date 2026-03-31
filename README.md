 SOC Blue Team Home Lab – Network Recon & Security Analysis

 Overview

This project simulates a real-world SOC (Security Operations Center) environment to monitor, detect, and analyze network activity.
It demonstrates how security analysts identify exposed services, investigate network traffic, and review authentication logs within a controlled lab environment.

⸻

 Objective

To understand how SOC analysts:
	•	Identify active hosts in a network
	•	Detect exposed services and potential attack surfaces
	•	Analyze network traffic behavior
	•	Investigate Windows authentication logs for suspicious activity

⸻

 Tools & Technologies
	•	Kali Linux
	•	Windows 10 VM
	•	VirtualBox
	•	Nmap
	•	Wireshark
	•	Windows Event Viewer

⸻

 Investigation Process

1️ Network Reconnaissance (Kali Linux)
	•	Performed host discovery in an isolated network
	•	Scanned for open ports and running services using Nmap
	•	Identified exposed services that may increase attack surface

⸻

2️ Network Traffic Analysis (Wireshark)
	•	Captured live network traffic (ICMP packets)
	•	Analyzed source and destination IP communication
	•	Observed request/response behavior in real time

⸻

3️ Windows Event Log Analysis
	•	Investigated Security logs using Event Viewer
	•	Reviewed authentication events:
	•	Event ID 4624 (Successful login)
	•	Event ID 4625 (Failed login attempts)
	•	Event ID 4634 (Logoff events)

⸻

 SOC Findings & Analysis
	•	Exposed services increase potential attack surface if not properly secured
	•	Continuous failed login attempts may indicate brute-force activity
	•	ICMP traffic helps validate network connectivity and detect scanning behavior
	•	Centralized log monitoring is essential for early threat detection

⸻

 Skills Demonstrated
	•	SOC Monitoring Fundamentals
	•	Network Reconnaissance
	•	Traffic Analysis
	•	Log Investigation
	•	Threat Detection Thinking
	•	Attack Surface Identification

⸻

 Conclusion

This lab demonstrates foundational SOC analyst skills by simulating real-world security monitoring tasks, including network scanning, traffic inspection, and security log analysis.
It reflects practical understanding of how threats are detected and analyzed in enterprise environments.


# Lab Diagram
https://github.com/blueabeer/Kali-Network-Recon-Lab-Nmap-Service-Discovery-/blob/main/kali%20final%20result.png

Final Nmap scan result showing open TCP port (4444) detected in the target machine.

##  Real-World Relevance
This lab simulates SOC analyst tasks such as network monitoring, traffic analysis, and security log investigation commonly used in enterprise environments.
