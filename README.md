# local_network_port_scanner

 🔍 Local Network Port Scanning Project

## 📌 Objective
Identify open ports and services running on devices in your local network using Nmap and Wireshark to assess potential security risks.

## 🛠️ Tools Used
- **Nmap** – for port scanning
- **Wireshark** – for packet analysis
- **Linux/Windows Terminal** – to run commands

## 🧪 Steps Performed
1. Installed Nmap on your system.
2. Identified the local network IP range (e.g., `192.168.1.0/24`).
3. Scanned the network with:
   nmap -sS 192.168.1.0/24
4. Recorded all discovered devices and open ports. 
    PORT     STATE SERVICE
    135/tcp  open  msrpc
    139/tcp  open  netbios-ssn
    445/tcp  open  microsoft-ds
    3306/tcp open  mysql
    8000/tcp open  http-alt
    8089/tcp open  unknown
5. Used Wireshark to monitor traffic during the scan.

6. Analyzed services running on:
    Port 135 (MSRPC)
    Port 139 (NetBIOS-SSN)
    Port 445 (Microsoft-DS)
    Port 3306 (MySQL)
    Port 8000 (HTTP-alt)
    Port 8089 (Unknown)


SECURITY RECOMMENDATIONS

Close unnecessary ports.
Use a firewall to filter external traffic.
Keep services up-to-date and properly configured.
Use strong credentials for all systems.

📚 LEARNINGS

Network scanning techniques.
Identifying common open ports.
Security implications of exposed services.
Analyzing traffic behavior using Wireshark.
