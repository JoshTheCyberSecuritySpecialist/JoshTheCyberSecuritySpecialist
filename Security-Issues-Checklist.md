# Security Issues Checklist

## Step 1: Inspect Logs
- [ ] Review SSH logs: `cat /var/log/auth.log | grep sshd`
- [ ] Check system logs for suspicious activity: `grep -i "failed" /var/log/syslog`

## Step 2: Verify Access Control
- [ ] Check file permissions: `ls -l`
- [ ] Verify sudo access: `sudo -l`

## Step 3: Detect Malware
- [ ] Scan for rootkits: `chkrootkit`
- [ ] Inspect open ports: `netstat -tulnp`
