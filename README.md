# Network Port Scanning Task

## Objective
The objective of this task was to perform a network reconnaissance scan on a local network to discover open ports and analyze network exposure using Nmap.

## Tools Used
- Nmap (Network Mapper) for port scanning.

## Methodology
- Installed Nmap on the system from official website.
- Identified the local network IP range using subnetmask
- Performed a TCP SYN scan using the command:
    eg: nmap -sS 192.168.xx.x/24 -oN scan_results.txt
  
- Saved the output in text format for documentation.
- Reviewed the open ports and identified common services running on them.

## Findings
- Listed IP addresses with open ports in the network.
- Identified services running on the discovered open ports.
- Assessed potential security risks associated with exposed ports.

## Conclusion
This exercise enhanced the skills of network reconnaissance and understanding of open port vulnerabilities. The scan results help in monitoring and securing network devices by identifying unnecessary exposed services.

## Files Included
- scan_results.txt - Text file containing the scan output.


