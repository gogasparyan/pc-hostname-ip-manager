# pc-hostname-ip-manager

# Classroom Network Automation

This project automates the setup of classroom PCs by generating unique hostnames, assigning local IP addresses from a central server, and updating configurations when needed.

## 🛠️ Features

- Hostname generation for multiple classroom computers
- Automatic IP address assignment from a local DHCP or static pool
- Update functionality for existing hostnames or IPs
- Command-line interface for batch operations

## 🚀 Technologies Used

- Python 3.x
- `os`, `subprocess`, `ipaddress`, etc. (mention actual libraries used)
- Local networking tools (mention if any: e.g., `nmap`, `ifconfig`, etc.)

## 🧪 Example Usage

```bash
# Generate hostnames for lab-1
python hostname_generator.py --lab lab-1 --count 30

# Assign IPs automatically
python assign_ips.py --range 192.168.1.100-192.168.1.200

# Update hostname/IP
python update_config.py --hostname PC-01 --new-ip 192.168.1.150
