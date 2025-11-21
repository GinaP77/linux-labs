# Linux Practice Labs

Hands-on Linux practice covering core system commands, permissions, navigation, and networking essentials.

## 🧩 Topics Covered
- File navigation (cd, ls, pwd)
- File creation + editing (touch, nano)
- Permissions (chmod, chown)
- Basic networking tools (ping, ifconfig, ip)
- Bash scripting basics

## 📁 Files Included
- basic-commands.md
- permissions.md
- networking.md
- bash-practice.sh

More labs will be added as I continue learning Linux for cybersecurity.

# Basic Linux Commands

## Navigation
- `pwd` — Show current directory
- `ls` — List files
- `cd` — Change directory

## File Management
- `touch file.txt` — Create a file
- `mkdir folder` — Create a folder
- `rm file.txt` — Remove file
- `rm -r folder` — Remove folder
- `cp file1 file2` — Copy a file
- `mv file1 file2` — Move/rename a file

## Viewing Files
- `cat file.txt`
- `less file.txt`

# Linux Permissions

## chmod Examples
- `chmod 755 file.txt`
- `chmod 644 file.txt`

## Ownership
- `chown user file.txt`
- `chgrp group file.txt`

# Linux Networking Commands

- `ip a` — Show IP addresses  
- `ifconfig` — Show network interfaces  
- `ping google.com` — Test connectivity  
- `traceroute google.com` — Trace route  
- `netstat -tulpn` — Show open ports  

bash-practice.sh
#!/bin/bash

echo "Welcome to my Linux practice script!"
echo "Today's date is: $(date)"
echo "Your current directory is: $(pwd)"
echo "Here are your files:"
ls -la
