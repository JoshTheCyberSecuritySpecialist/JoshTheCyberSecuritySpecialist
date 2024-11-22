# System Crashes Checklist

Follow this checklist to diagnose and resolve Linux system crashes:

## Step 1: Gather Information
- [ ] Check kernel logs: `dmesg | tail`
- [ ] Review system logs: `less /var/log/syslog`
- [ ] Analyze crash dumps (if enabled): `gdb /path/to/executable core`

## Step 2: Check Resource Usage
- [ ] Verify memory availability: `free -h`
- [ ] Check disk space: `df -h`
- [ ] Monitor CPU usage: `top` or `htop`

## Step 3: Inspect Running Processes
- [ ] Identify high CPU/memory usage: `ps aux --sort=-%mem | head`
- [ ] Check for zombie processes: `ps aux | grep 'Z'`
