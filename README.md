# Real_Esatate_Management_System
![image alt](https://github.com/salony-garg/Real_Esatate_Management_System/blob/main/Screenshot%202024-12-13%20184835.png?raw=true)
![image alt](https://github.com/salony-garg/Real_Esatate_Management_System/blob/main/Screenshot%202024-12-13%20184630.png?raw=true)
![image alt](https://github.com/salony-garg/Real_Esatate_Management_System/blob/main/Screenshot%202024-12-13%20184728.png?raw=true)
![image alt](https://github.com/salony-garg/Real_Esatate_Management_System/blob/main/Screenshot%202024-12-13%20184748.png?raw=true)
![image alt](https://github.com/salony-garg/Real_Esatate_Management_System/blob/main/Screenshot%202024-12-13%20184821.png?raw=true)
![image alt](https://github.com/salony-garg/Real_Esatate_Management_System/blob/main/Screenshot%202024-12-13%20184855.png?raw=true)
![image alt](https://github.com/salony-garg/Real_Esatate_Management_System/blob/main/Screenshot%202024-12-13%20192816.png?raw=true)
![image alt](https://github.com/salony-garg/Real_Esatate_Management_System/blob/main/Screenshot%202024-12-13%20192905.png?raw=true)


# sysopctl - Custom Linux Command for System Management

## Overview
sysopctl is a custom Bash-based Linux command designed for managing system services, processes, and logs. It simplifies system administration tasks by providing a user-friendly interface for system monitoring and maintenance.

## Features
- *Basic Features:*
  - --help: Display help information.
  - --version: Show version details.
- *System Operations:*
  - List running services.
  - View system load averages.
  - Start/stop system services.
  - Check disk usage.
- *Advanced Features:*
  - Monitor system processes.
  - Analyze system logs.
  - Backup system files.

## Usage
### Help
```bash
sysopctl --help

EXAMPLE COMMANDS 

sysopctl service list
sysopctl system load
sysopctl service start nginx
sysopctl backup /home/user/documents


STEPS

1. Clone the repository 
git clone <repository-url>

2. Make the script executable
chmod +x sysopctl.sh

INSTALL THE MANUAL PAGE USING

sudo cp sysopctl.1 /usr/share/man/man1/
man sysopctl

REQUIREMENTS 
	•	Bash shell
	•	Linux operating system
	•	Tools: systemctl, uptime, df, journalctl, rsync
