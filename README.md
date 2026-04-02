# Born2beRoot — 42 Project

A system administration project from the 42 school curriculum. Set up a virtual machine with a secure server configuration using **Debian** or **Rocky Linux**.

## Topics Covered

- Virtual machine setup (VirtualBox/UTM)
- Disk partitioning with LVM and encryption
- sudo configuration and policies
- UFW firewall setup
- SSH service configuration
- Password policy enforcement
- User and group management
- Crontab and monitoring script

## Security Configuration

- Strong password policy (length, complexity, expiration)
- Sudo rules and logging
- SSH on custom port (4242)
- Root login disabled via SSH
- UFW firewall with minimal open ports
- AppArmor enabled

## Monitoring Script

A bash script that runs every 10 minutes via cron, displaying:
- OS architecture and kernel version
- CPU and RAM usage
- Disk usage
- Active connections
- Number of users logged in
- Network info (IP, MAC)
- Number of sudo commands executed

## Author

**Houssame El Bandoudi** — [GitHub](https://github.com/HOUSSAMEELBANDOUDI) | 42 Student (hel-band)
