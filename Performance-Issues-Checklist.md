# Performance Issues Checklist

## Step 1: Identify Bottlenecks
- [ ] Check disk IO: `iotop`
- [ ] Analyze CPU usage: `sar -u`
- [ ] Inspect memory usage: `vmstat`

## Step 2: Optimize Services
- [ ] Check web server performance (e.g., Nginx): `ab -n 1000 -c 10 http://localhost/`
- [ ] Optimize database queries (e.g., MySQL): `EXPLAIN <query>`
