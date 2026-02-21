# Task 1: Network Scanning Using Nmap

## Objective
This task focuses on performing a basic network scan using Nmap on a local Kali Linux machine. The goal is to identify open ports and detect any active services running on the system.

## Environment & Tools
- Nmap
- Kali Linux (running on VirtualBox)

## Procedure

### 1. Checking Nmap Installation
To confirm that Nmap was installed correctly, the following command was executed:

nmap --version

### 2. Performing a Basic Scan
A simple scan was performed on the local machine using:

nmap localhost

This command scans the most common 1000 TCP ports.

### 3. Service Version Detection
To gather more detailed information about possible running services, the following command was used:

nmap -sV localhost

This helps in identifying service names and versions if any ports are open.

### 4. Saving the Output
The scan results were saved into a text file for documentation and future reference.

## Scan Results
- The system (127.0.0.1) responded successfully.
- All scanned TCP ports were found to be closed.
- No active network services were detected during the scan.

## Security Analysis
Since all ports are closed, there are no exposed services on the local machine. This reduces potential vulnerabilities and limits external access risks. Conducting periodic network scans is a good security practice to ensure that only necessary services are active and the system remains protected.

## Conclusion
The network scanning task was successfully completed using Nmap. The system showed no open ports, indicating a secure and properly configured local environment.
