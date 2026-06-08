# 🛡️ Automated Linux Server Hardening Script

**Author:** Abdul Rehman | Network & Information Security Engineer

## 📌 What is this?
This is an automated production-ready Bash script designed to secure and harden Linux servers (Ubuntu/Debian) immediately after deployment. It automates critical baseline security practices to minimize the attack surface against automated bots and malicious actors.

## 💼 Business Value (Why clients need this)
When businesses deploy new cloud servers, they are targeted by automated brute-force bots within minutes. This script protects critical infrastructure by providing:
* **Brute-Force Mitigation:** Installs and configures Fail2Ban to automatically jail malicious IPs.
* **Firewall Lockdown:** Implements a strict default-deny firewall policy using UFW, exposing only essential web ports (SSH, HTTP, HTTPS).
* **Identity Protection:** Disables root login via SSH to ensure compliance and unauthorized access attempts.

## 🚀 How to use
1. Download the script to your fresh server: `wget https://raw.githubusercontent.com/cybersecurity-with-abdulrehman/Linux-Server-Hardening-Script/main/server_hardening.sh`
2. Make it executable: `chmod +x server_hardening.sh`
3. Run with root privileges: `sudo ./server_hardening.sh`
