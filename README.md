# TASK-1 Local-Network-Port-Scanner-
This project uses Nmap to scan the local network for open ports on connected devices. It identifies active hosts and their exposed services to help assess potential security vulnerabilities within a network.

Open ports can pose significant security risks if left unmanaged. This project demonstrates how to discover such ports and understand their implications, which is essential for anyone learning about cybersecurity, ethical hacking, or network administration.

Prerequisites
- Install [Nmap](https://nmap.org/)
- (Optional) Install [Wireshark](https://www.wireshark.org/) for packet analysis

Steps
1. Identify your local IP range (192.168.1.0) 
2. Run a TCP SYN scan with the following command:(In nmap tool to scan open ports) 
   nmap -sS 192.168.1.0


Nmap scan report for Nmap scan report for 192.168.1.1

PORT     STATE SERVICE
22/tcp   open  ssh
80/tcp   open  http
443/tcp  open  https

This project is maintained by chaganti pavan teja. As part of the Cyber Security Internship by Elevate Labs in collaboration with the Ministry of MSME, Government of India
