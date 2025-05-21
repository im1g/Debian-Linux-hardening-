# Debian-Linux-hardening
Overview
This project includes two dedicated shell scripts aimed at significantly improving the security posture of systems running Ubuntu or other Debian-based Linux distributions. One script handles general system hardening, while the other secures the system bootloader using GRUB configuration tweaks. The current release aligns more closely with widely accepted security frameworks such as DISA STIG and CIS Benchmarks.

The primary objective is to offer a practical, security-focused toolkit that remains approachable for everyday desktop users. While the scripts apply enterprise-grade security practices, care has been taken to ensure ease of use and clarity in implementation. If you run into issues, Reach out to me on discord @im1g

Scripts Included
improved_harden_linux.sh: The main hardening utility that applies a wide range of security configurations.

update_grub_config.sh: Enhances boot-time security by modifying GRUB parameters.

Each script supports:

--dry-run: Preview changes without applying them

--version: Display script version

--help: Show usage guide and instructions

Key Features
Optional full system update and upgrade

Configuration of UFW (Uncomplicated Firewall)

Installation and basic setup of Fail2Ban

Deployment and update of ClamAV antivirus

Option to disable root login safely

Removal of redundant or insecure packages

Setup of a detailed auditing system

Disabling of rarely used or legacy filesystems

GRUB bootloader hardening

Adjustable IPv6 settings

AppArmor security profile activation

Network Time Protocol (NTP) configuration

Installation of AIDE for intrusion detection

Tightening of kernel parameters using sysctl

Setup of automatic security patches

Additional hardening such as:

Disabling core dumps

Enforcing strong SSH policies

Setting strong password complexity rules

Enabling process accounting for monitoring

Requirements
To run these scripts, you will need:

A Debian-based distribution (Ubuntu 18.04 or newer recommended)

Administrative privileges (sudo or root access)

Active internet connection (for downloading and updating packages)

