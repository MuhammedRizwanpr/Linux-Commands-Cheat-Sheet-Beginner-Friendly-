# 🐧 Linux Commands Cheat Sheet (Beginner Friendly)

This is my learning journey of Linux basics.  
Here I collected **most used Linux commands** with **simple explanations**.  
It’s like my personal reference and study notes.  

---

## 📂 File & Directory Management

| Command | Example | Description |
|---------|---------|-------------|
| `pwd` | `pwd` | Show current working directory. |
| `ls` | `ls -l` | List files/folders (`-l` long format, `-a` show hidden). |
| `cd` | `cd /home/user` | Change directory. |
| `mkdir` | `mkdir newdir` | Create new directory. |
| `rmdir` | `rmdir emptydir` | Remove empty directory. |
| `rm -r` | `rm -r folder` | Remove directory with files inside. |
| `touch` | `touch file.txt` | Create empty file. |
| `cp` | `cp file.txt backup.txt` | Copy file. |
| `mv` | `mv file.txt /tmp/` | Move or rename file. |
| `find` | `find / -name file.txt` | Find file by name. |

---

## 📑 File Viewing & Editing

| Command | Example | Description |
|---------|---------|-------------|
| `cat` | `cat file.txt` | View file content. |
| `less` | `less file.txt` | Scroll through file (q to quit). |
| `head` | `head -n 10 file.txt` | Show first 10 lines. |
| `tail` | `tail -n 10 file.txt` | Show last 10 lines. |
| `wc` | `wc -l file.txt` | Count lines/words/chars. |
| `strings` | `strings binaryfile` | Extract readable text from binary. |
| `xxd` | `xxd file` | View file in hex + ASCII. |

---

## 🔑 Permissions & Ownership

| Command | Example | Description |
|---------|---------|-------------|
| `ls -l` |  | See file permissions. |
| `chmod` | `chmod 755 file.sh` | Change file permissions. |
| `chown` | `chown user file.txt` | Change file owner. |
| `chgrp` | `chgrp group file.txt` | Change group ownership. |

---

## ⚙️ System Info & Monitoring

| Command | Example | Description |
|---------|---------|-------------|
| `top` | `top` | Show running processes live. |
| `htop` | `htop` | Better version of `top` (needs install). |
| `df -h` | `df -h` | Show disk usage. |
| `du -sh folder` | `du -sh /home` | Show size of a folder. |
| `free -h` | `free -h` | Show memory usage. |
| `uptime` | `uptime` | Show system uptime. |
| `vmstat` | `vmstat 5` | Show CPU, memory every 5 sec. |

---

## 🌐 Networking

| Command | Example | Description |
|---------|---------|-------------|
| `ifconfig` | `ifconfig` | Show network interfaces (deprecated). |
| `ip addr` | `ip addr show` | Show IP addresses. |
| `ping` | `ping google.com` | Test connectivity. |
| `netstat -tulnp` | | Show open ports (deprecated). |
| `ss -tulnp` | | Show open ports (modern). |
| `traceroute` | `traceroute google.com` | Show network hops. |
| `nslookup` | `nslookup google.com` | DNS lookup. |
| `nmap` | `nmap 192.168.1.1` | Scan open ports. |

---

## 📦 Archiving & Compression

| Command | Example | Description |
|---------|---------|-------------|
| `tar` | `tar -cf files.tar file1 file2` | Archive files. |
| `tar -xf` | `tar -xf files.tar` | Extract archive. |
| `gzip` | `gzip file.txt` | Compress file. |
| `gunzip` | `gunzip file.txt.gz` | Decompress file. |
| `zip` | `zip archive.zip file.txt` | Zip file. |
| `unzip` | `unzip archive.zip` | Unzip file. |

---

## 🛠️ Process Management

| Command | Example | Description |
|---------|---------|-------------|
| `ps aux` | | Show all processes. |
| `kill` | `kill 1234` | Kill process by PID. |
| `kill -9` | `kill -9 1234` | Force kill process. |

---

## 🔒 User & Group Management

| Command | Example | Description |
|---------|---------|-------------|
| `whoami` | | Show current user. |
| `id` | | Show user ID and groups. |
| `groups` | | Show groups of current user. |
| `adduser` | `sudo adduser newuser` | Create new user. |
| `groupadd` | `sudo groupadd devs` | Create new group. |
| `usermod -aG` | `sudo usermod -aG devs newuser` | Add user to group. |

---

## 📜 Logs

| Command | Example | Description |
|---------|---------|-------------|
| `tail -f /var/log/syslog` | | Watch system log live. |
| `grep "Failed password" /var/log/auth.log` | | Search for failed logins. |

---

## 🧰 Useful Shortcuts

- `Ctrl + C` → Kill running command.  
- `Ctrl + D` → Logout / End input.  
- `Ctrl + L` → Clear screen.  
- `!!` → Run last command again.  
- `history` → Show command history.  

---

✨ This README is part of my Linux learning journey.  
I’ll keep updating it as I learn more. 🚀
