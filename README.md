# Elevate_Labs_04_Firewall_Configuration_with_UFW
Configure and manage basic firewall rules using UFW on Linux.

# Linux Firewall Setup using UFW

## Task Objective
Configure and manage basic firewall rules using UFW on Linux. Block and allow specific ports, test with Nmap, fix common mistakes, and document everything for a cybersecurity portfolio.

---

## Tools Used
- **Kali Linux** – OS
- **UFW** – Uncomplicated Firewall
- **Nmap** – Port scanner

---

## What Was Done

1. Installed and enabled UFW.
2. Listed current rules.
3. Blocked port **23** (Telnet).
4. Verified the rule using **Nmap**.
5. Allowed port **22** (SSH).
6. Removed the test rule to restore the state.
7. Disabled UFW

---

## Screenshots
├── 1-ufw-status-enabled.png
├── 2-deny-port-23.png
├── 3-nmap-test-port-23.png
├── 4-allow-sshport-22.png
└── 5-delete-port-23-rule.png

---

## Files
- `ufw_commands.txt`: Contains all commands used.
- `LICENSE`: MIT License.
- `README.md`: This file.
- `screenshots`

---

## Summary
Firewalls act as barriers between your system and the network. Using UFW simplifies managing rules. This task showed how to block and allow ports, and test rules in real time.
