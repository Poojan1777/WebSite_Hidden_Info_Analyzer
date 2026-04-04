# WebSite_Hidden_Info_Analyzer

Website Security Analyzer is a Python-based cybersecurity reconnaissance tool that analyzes a target website and extracts useful security and OSINT information.

The tool performs multiple automated checks including email extraction, contact discovery, metadata analysis, security header validation, technology detection, subdomain discovery, and directory brute forcing. It generates a detailed HTML security report that can be viewed in a web browser.

This project is designed for learning purposes and demonstrates practical concepts used in cybersecurity reconnaissance and web security analysis.

Features
• Email extraction from website pages
• Contact/phone number discovery
• Website metadata analysis
• Security header misconfiguration detection
• HTTP header information leak detection
• Technology detection (WordPress, React, PHP, Apache, Nginx)
• Subdomain enumeration using DNS
• Hidden directory brute forcing
• Automated HTML security dashboard report


🛠 Technologies Used
Python
Requests
BeautifulSoup
DNSPython
HTML/CSS


▶ Usage
pip install requests beautifulsoup4 dnspython
python web_analyzer.py


📊 Output

The tool generates an HTML security report containing:

Security headers analysis
HTTP header inspection
Technology fingerprinting
Subdomains discovered
Hidden directories
Emails and contacts found


⚠ Disclaimer
This tool is developed for educational and ethical security testing purposes only.
Do not use it against websites without proper authorization.


⭐ Bonus (Recommended for GitHub)

Add topics/tags in GitHub repo:

cybersecurity
python
osint
web-security
security-tools
devsecops
reconnaissance
bug-bounty
