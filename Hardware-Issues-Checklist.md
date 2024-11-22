# Hardware Issues Checklist

## Step 1: Disk Issues
- [ ] Check disk health: `smartctl -a /dev/sda`
- [ ] Inspect errors in logs: `dmesg | grep -i error`
- [ ] Test read/write speeds: `hdparm -tT /dev/sda`

## Step 2: Memory Issues
- [ ] Test for errors: `memtest86+`
- [ ] Inspect memory usage: `free -m`

## Step 3: CPU Issues
- [ ] Check CPU temperature: `sensors`
- [ ] Monitor load: `uptime`
