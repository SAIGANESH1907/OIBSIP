# Task 7 – Vulnerability Scanning with Nikto

## Objective
The objective of this task is to perform vulnerability scanning on a web server using the Nikto tool and identify possible security issues.

## Tool Used
Nikto – an open-source web server vulnerability scanner used to detect:
- Outdated server software
- Security misconfigurations
- Dangerous files and scripts
- Missing security headers

## Environment
Operating System: Kali Linux  
Tool: Nikto

## Target Website
http://testphp.vulnweb.com

## Commands Used

Install Nikto:
sudo apt install nikto

Run vulnerability scan:
nikto -h http://testphp.vulnweb.com

Save scan results:
nikto -h http://testphp.vulnweb.com -o nikto_scan_results.txt

View results:
cat nikto_scan_results.txt

## Results
The Nikto scan analyzed the target web server and detected several potential security issues such as missing security headers and possible server configuration weaknesses.

## Conclusion
Nikto is a useful tool for identifying vulnerabilities in web servers. Regular vulnerability scanning helps organizations detect and fix security issues before attackers exploit them.
