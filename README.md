# Task-1-Port-Scan
This task focuses on scanning a local network using Nmap to identify active devices and open ports. A TCP SYN scan was performed on the IP range 192.168.1.0/24 to understand network exposure and potential security risks. The results were saved and analyzed as part of a cybersecurity learning project.

# Task 1 – Network Port Scanning using Nmap

## Objective:
To discover open ports in my local network using Nmap and understand basic network exposure.

## Tools Used:
- Nmap (TCP SYN Scan) / ## Tools Used

- [Nmap - Kali Linux Tools](https://www.kali.org/tools/nmap/) – Used for scanning the local network and discovering open ports.

- Command Prompt (Windows)

## My IP Range:
- Detected local IP: 192.168.1.9
- Scanned range: 192.168.1.0/24

## Command Used:
```bash
nmap -sS 192.168.1.0/24
