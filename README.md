# NETWORK-PORT-SCANNER

The Network Port Scanner is a robust Cyber Security project designed to empower cybersecurity professionals, network administrators, and ethical hackers in conducting comprehensive network assessments. 

Developed with a focus on security and efficiency, this tool leverages advanced scanning techniques to identify open ports on target hosts and provides insights into the services running on those ports.

The project plays a pivotal role in network vulnerability assessment and penetration testing activities. 

This project, initiated as an internship project by 1Stop, allows you to explore and assess the security of networked systems by identifying open ports and the services running on them.

Features:

Port Discovery: Quickly discover open ports on a target host.

Service Identification: Identify services running on open ports for a deeper understanding of network services.

Customizable Scans: Tailor your scans by specifying a list of ports relevant to your security objectives.

Command-Line Interface (CLI): Easy-to-use CLI for efficient scanning and integration into scripts.

Getting Started:

Installation:

Clone the repository: git clone https://github.com/your_username/network-port-scanner.git
Navigate to the project directory: cd network-port-scanner

Dependencies:

Ensure you have Python installed.

Install required packages: pip install -r requirements.txt

Usage:

Run the scanner: python network_port_scanner.py -o <host_ip_address> -p <comma_separated_port_list>

Examples:

Scan common ports: python network_port_scanner.py -o 192.168.1.1 -p 80,443,22

Customize ports: python network_port_scanner.py -o 10.0.0.1 -p 8080,8443

Applications:

Security Assessments: Identify potential vulnerabilities in networked systems.

Penetration Testing: Simulate cyber-attacks to evaluate network defenses.

Educational Purposes: Learn about port scanning and service identification in cybersecurity.
