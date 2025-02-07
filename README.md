# Nmap-OpenVAS-Automation
A Python tool that automates network vulnerability scanning using Nmap and OpenVAS. This script simplifies the process of finding security vulnerabilities, creating detailed reports, and making network security assessments more efficient.

**Dependencies**
**Required Software:**
Nmap: Used for network scanning.
OpenVAS: Used for vulnerability scanning.
**Python Libraries:**
python-nmap: Enables interaction with Nmap from Python.
subprocess: Executes system commands.
xml.etree.ElementTree: Parses Nmap’s XML output.

**Key Features**
**Automated Nmap Scans**
Scans for open ports, services, and operating system details.
Saves results in XML format for easy analysis and further processing.
**OpenVAS Integration**
Initiates vulnerability scans using OpenVAS for in-depth security analysis.
Requires a configured OpenVAS server and valid credentials.
