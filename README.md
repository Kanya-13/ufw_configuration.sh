# Basic UFW Firewall Configuration

This project automates a minimal firewall setup for Ubuntu using UFW. It allows SSH access while blocking HTTP access.

Files Included

- `ufw_configuration.sh`: Shell script to configure the firewall.
- `ufw-status.txt`: Screenshot-proof of firewall status after setup.

 ✔️ What It Does

1. Updates package list and installs UFW.
2. Sets default policies: deny incoming, allow outgoing.
3. Allows SSH (port 22).
4. Denies HTTP (port 80).
5. Enables UFW.
6. Saves current firewall status to `ufw-status.txt`.

Usage

```bash
chmod +x ufw_configuration.sh
./ufw_configuration.sh
