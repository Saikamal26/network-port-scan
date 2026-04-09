# Network Port Scan using Nmap

## Objective
To identify open ports and analyze network exposure.

## IP Range
192.168.80.0/24

## Tools Used
- Nmap
- Wireshark

## Methodology
- Identified IP range using ifconfig
- Performed SYN scan
- Captured packets using Wireshark

## Findings
- 192.168.80.1 → Ports 80, 443
- 192.168.80.129 → Port 22

## Risk Analysis
- SSH (22) → brute-force risk
- HTTP (80) → possible vulnerabilities

## Wireshark Analysis
- Observed SYN packets
- SYN-ACK = open ports
- RST = closed ports

## Conclusion
The scan identified active devices and potential security risks.