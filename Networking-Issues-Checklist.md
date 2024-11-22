# Networking Issues Checklist

## Step 1: Check Physical Connectivity
- [ ] Verify cables and interface: `ip link show`
- [ ] Ensure the interface is up: `sudo ifconfig eth0 up`

## Step 2: Test Connectivity
- [ ] Ping a known IP: `ping 8.8.8.8`
- [ ] Test DNS resolution: `nslookup google.com`

## Step 3: Inspect Routing
- [ ] Check the routing table: `ip route`
- [ ] Verify the default gateway: `ping <gateway-IP>`

## Step 4: Debug with Tools
- [ ] Use `traceroute` to identify network hops.
- [ ] Analyze traffic with `tcpdump`.
