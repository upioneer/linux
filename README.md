# Linux Commands Cheat Sheet

## Navigation
- List files and directories  
  `ls -l`

- Change directory  
  `cd /path/to/directory`

## Permissions
- Change the permissions of a file or directory  
  `chmod 755 filename`

- Change the owner of a file or directory  
  `chown user:group filename`

## System Information
- Display system kernel, OS, and architecture information  
  `uname -a`

- Show system information, including hostname, OS, and kernel version  
  `hostnamectl`

- Display Linux distribution information  
  `lsb_release -a`

- Show system uptime and load average  
  `uptime`

- List users currently logged into the system  
  `who`

## Performance Monitoring
- Real-time view of system processes and resource usage  
  `top`

- Enhanced version of `top` with a user-friendly interface  
  `htop`

- List all running processes with detailed information  
  `ps aux`

- Display memory usage in human-readable format  
  `free -h`

- Report virtual memory statistics  
  `vmstat`

- Show CPU and disk I/O statistics  
  `iostat`

- Collect and report system activity statistics  
  `sar`

## Hardware Specifications
- Display CPU architecture information (cores, threads, cache)  
  `lscpu`

- Show information about system memory (RAM)  
  `lsmem`

- List block devices in a tree format (e.g., hard drives, partitions)  
  `lsblk`

- Display disk usage for file systems in human-readable format  
  `df -h`

- Show disk usage for a specific directory  
  `du -sh /path/to/directory`

- List PCI devices (graphics cards, network cards)  
  `lspci`

- List USB devices connected to the system  
  `lsusb`

- Show detailed hardware information (e.g., BIOS, motherboard, processor, memory)  
  `sudo dmidecode`
