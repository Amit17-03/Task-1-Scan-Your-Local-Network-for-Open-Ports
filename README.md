# Task-1-Scan-Your-Local-Network-for-Open-Ports
1. Installed Nmap from the [official site](https://nmap.org/download.html)
2.  Found the local IP range using:
    ipconfig
3. Ran the scan using:
   nmap -sS 192.168.1.0/24 -oN local_scan.txt
