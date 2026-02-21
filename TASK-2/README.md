# Task 2: Configuring a Basic Firewall Using UFW

## Objective
The purpose of this task is to set up and manage a simple firewall configuration using UFW (Uncomplicated Firewall) on a Kali Linux system. The goal is to permit secure SSH access while restricting HTTP traffic.

## Tools & Environment
- Kali Linux
- UFW (Uncomplicated Firewall)

## Implementation Steps

### 1. Activating the Firewall
The firewall was enabled to start filtering incoming and outgoing network traffic.

### 2. Allowing SSH Access
Port 22 was allowed to enable secure remote login through SSH.

### 3. Blocking HTTP Traffic
Port 80 was denied to prevent web (HTTP) traffic from accessing the system.

### 4. Checking Firewall Status
The firewall configuration and active rules were verified using:

ufw status

## Outcome
- Secure Shell (SSH) traffic on port 22 is permitted.
- HTTP traffic on port 80 is successfully blocked.
- The firewall is enabled and actively enforcing the defined rules.

## Security Overview
By allowing only necessary services and restricting unwanted ports, the system’s exposure to potential threats is minimized. Proper firewall configuration strengthens system security by controlling network access and preventing unauthorized connections.

## Conclusion
The firewall was successfully configured using UFW. The system now allows secure remote access via SSH while blocking HTTP traffic, improving overall network protection.
