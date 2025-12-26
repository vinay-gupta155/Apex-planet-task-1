# Linux Cheat Sheet – Vinay

## Basics
- `pwd` – show current directory
- `ls`, `ls -l`, `ls -la` – list files
- `cd /`, `cd ~`, `cd ..` – change directory
- `mkdir lab1` – create folder
- `echo "hello vinay" > note.txt` – create file
- `cat note.txt` – show file content

## Permissions
- `ls -l` – view permissions
- `chmod +x note.txt` – add execute
- `chown msfadmin:msfadmin note.txt` – change owner

## Packages (Kali)
- `sudo apt update`
- `sudo apt install net-tools`
- `dpkg -l | head`

## Networking
- `ifconfig` – see IP
- `ping <other-VM-IP>` – test connectivity
- `netstat -tulnp` – listening ports
- `traceroute 8.8.8.8`
