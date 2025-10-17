# internship-task-8-elevatelabs
VPN Privacy Protection Analysis
Cybersecurity Internship Project - Elevate Labs
Institution: GD Goenka University
📋 Project Overview
This repository contains a comprehensive analysis of Virtual Private Network (VPN) technology and its effectiveness in protecting user privacy and securing internet communications. The project demonstrates hands-on implementation of ProtonVPN to showcase IP address masking capabilities, encrypted traffic routing, and geolocation spoofing.

🎯 Objectives
The primary goals of this analysis were to:

🔒 Protect user privacy through IP address masking

🔐 Secure internet communications via encrypted tunneling

🌐 Demonstrate real-world applications of privacy protection tools

📊 Analyze performance trade-offs in VPN implementation

🔬 Methodology
VPN Service Selection
Selected Provider: ProtonVPN (Free Tier)

Rationale:

Reputable security standards

Transparent privacy policy

Free tier availability for educational purposes

Strong encryption protocols (WireGuard)

Testing Infrastructure
The analysis was conducted on a Windows-based system following this methodology:

Baseline IP Documentation - Initial IP address and geolocation recording

VPN Connection Establishment - Secure tunnel creation to Canadian server

IP Verification - Post-connection IP address and location verification

Traffic Analysis - Encrypted communication confirmation

🛠️ Technical Implementation
Original Network Configuration
Parameter	Value
IPv4 Address	103.94.67.178
IPv6 Address	2001:4860:7:805::a1
ISP	Google LLC
Location	Mumbai, Maharashtra, India
Service Type	Data Center/Transit
VPN Connection Details
Parameter	Value
Server	CA-FREE#3 (Canada)
Protocol	WireGuard
Tunnel IP	185.98.171.237
Server Load	91%
Status	Successfully Connected
Post-Connection Network State
Parameter	Value
Masked IP	185.98.171.237
ISP	Proton AG
Location	Canada
Service Type	VPN Server
🔍 Key Findings
Privacy Protection Effectiveness
✅ Complete IP Address Obfuscation

True IP address (103.94.67.178) completely hidden from external services

Successful geolocation spoofing from Mumbai, India to Canada

Original ISP (Google LLC) replaced with VPN provider (Proton AG)

✅ Traffic Encryption Verification

HTTPS protocol compatibility maintained

Secure DNS queries routed through VPN infrastructure

Active encrypted data transmission confirmed

Security Benefits Demonstrated
Geographic Privacy - Complete location masking prevents tracking and targeting

ISP Traffic Hiding - Internet service provider cannot monitor browsing destinations

Public WiFi Protection - Encrypted tunnel protects against network eavesdropping

Censorship Circumvention - Geographic restrictions bypassed through server selection

📊 Performance Analysis
Connection Metrics
Stability: Maintained consistent connection throughout testing period

Latency: Expected increase due to traffic routing through Canadian servers

Bandwidth: Free tier restrictions observed but sufficient for basic privacy needs

Download Speed: 224 B/s (during testing)

Upload Speed: 256 B/s (during testing)

⚠️ Limitations & Considerations
Free Tier Restrictions
🚫 Limited server selection with higher load percentages

🐌 Reduced connection speeds compared to premium tiers

🌍 Restricted geographic server options

📱 Single device limitation

Privacy Trade-offs
Trust Requirement: Users must trust VPN provider's no-logs policy

Traffic Concentration: All traffic routes through VPN provider's infrastructure

Legal Compliance: VPN providers subject to jurisdiction-specific requirements

💼 Practical Applications
Public WiFi Security - Essential protection on unsecured networks

Geographic Content Access - Bypassing region-specific restrictions

Privacy-Conscious Browsing - Protection from ISP monitoring

Business Communications - Secure remote access to corporate networks

📈 Results Summary
Metric	Before VPN	After VPN
IPv4 Address	103.94.67.178	185.98.171.237
ISP	Google LLC	Proton AG
Location	Mumbai, India	Canada
Service Type	Data Center/Transit	VPN Server
Privacy Level	Exposed	Protected ✅
🎓 Educational Value
This project provided hands-on experience in:

Network Security Implementation - Practical experience with privacy tools

Traffic Analysis Techniques - Understanding network monitoring and verification

Privacy Technology Assessment - Critical evaluation of security solutions

Cybersecurity Best Practices - Real-world implementation of protection measures

🏆 Conclusions
The analysis successfully demonstrated VPN technology's effectiveness in protecting user privacy and securing internet communications. ProtonVPN's free tier provided adequate functionality for educational purposes and basic privacy protection needs.

Key Takeaways
✅ IP masking and geolocation concealment achieved successfully
✅ Secure traffic routing confirmed through monitoring tools
✅ User-friendly interface suitable for non-technical users
✅ Acceptable performance trade-offs for privacy benefits gained

🔗 Professional Recommendations
For cybersecurity professionals and privacy-conscious users:

VPN Integration - Incorporate VPN usage into standard security protocols

Provider Evaluation - Thoroughly research privacy policies and technical capabilities

Use Case Assessment - Match VPN features to specific security requirements

Performance Testing - Conduct regular speed and reliability assessments

📁 Repository Contents
Project report documentation

Network configuration screenshots

Before/After VPN connection analysis

Technical specifications and findings

🔐 Technologies Used
VPN Service: ProtonVPN (Free Tier)

Protocol: WireGuard

OS: Windows

Testing Tools: IP verification services, Network monitoring tools

👤 Author
Cybersecurity Student
BTech CSE - Cybersecurity Specialization
GD Goenka University

📜 License
This project is created for educational purposes as part of cybersecurity internship training.
