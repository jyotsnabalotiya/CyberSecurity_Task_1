# CyberSecurity_Task_1
# Task 1 – Local Port Scanning

This repository contains my submission for *Task 1* of the Cyber Security internship.

## Tools Used
- Nmap
- Wireshark

## What I Did
- Used Nmap to perform a TCP SYN scan on my local network to identify active hosts and their open ports.
- Captured the packets in Wireshark while the scan was running to observe SYN and SYN-ACK traffic.

## Command used
   ```bash
      nmap -sS 192.168.56.0/24 -oN task1_port.txt

