# Firewall Configuration Project (UFW)

## Objective
To configure and test firewall rules using UFW in Linux.

## Tools Used
- Kali Linux / Linux OS
- UFW (Uncomplicated Firewall)
- Terminal / VS Code

## Steps Performed
1. Enabled firewall using UFW
2. Listed current firewall rules
3. Blocked port 23 (Telnet)
4. Allowed SSH (port 22)
5. Tested blocked port
6. Removed test rule

## Learning Outcome
Understood how firewall filters network traffic and improves system security.

## Commands Used
```bash
sudo ufw enable
sudo ufw status
sudo ufw deny 23
sudo ufw allow 22
sudo ufw delete deny 23