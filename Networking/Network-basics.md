# Network Basics

## Learning Objective

I am learning the basic concepts of computer networking.

## Important Terms

| Term | Description |
|---|---|
| IP address | The logical address of a device on a network |
| Subnet mask | Defines the boundary of a local network |
| Default gateway | Connects the local network to other networks |
| DNS | Translates domain names into IP addresses |
| Port | Identifies a service running on a computer |

## Basic Windows Commands

### Display Network Configuration

```powershell
ipconfig
```

### Test Local Network Connectivity

```powershell
ping 127.0.0.1
```

### Test Internet Connectivity

```powershell
ping 8.8.8.8
```

### Test DNS Resolution

```powershell
nslookup google.com
```

### Display the Network Path

```powershell
tracert google.com
```

## Lab Notes

- Date: 08 September 2026
- Computer name: DESKTOP-TVS6GFR
- Operating system: Microsoft Windows 10 Pro
- IPv4 address: Private lab address
- Default gateway: Local Router
- DNS server: 8.8.8.8 (example)
- Test result:Basic network commands were tested successfully
- Problems encountered:None
- Solution:No action required

## What I Learned

I learned that an IP address identifies a device, a default gateway connects different networks, and DNS translates domain names into IP addresses.

## Security Notice

All information in this repository comes from a personal lab. No customer or production information is included.

## Networking Lab 01 — Connectivity Testing

### Objective

Test network connectivity step by step, from the local gateway to website access.

### Test Results

| Test | Result | Observation |
|---|---|---|
| Ping the local gateway | Successful | 4 packets sent, 4 replies received, 0% packet loss, average round-trip time of 8 ms |
| Ping 8.8.8.8 | Successful | 4 packets sent, 4 replies received, 0% packet loss, average round-trip time of 22 ms |
| Run nslookup google.com | Successful | The DNS resolver returned IPv4 and IPv6 addresses |
| Open https://google.com | Successful | The webpage opened successfully in the browser |

### What I Learned

- A default gateway provides a route to other networks when no more specific route applies.
- Ping tests network reachability using ICMP echo requests and replies.
- Ping measures round-trip time, not download speed.
- DNS resolves domain names to IP addresses.
- A successful DNS lookup does not guarantee that a website is accessible.
- Opening a website in a browser tests web access beyond ping and DNS resolution.
- These results describe connectivity during the test, not long-term network stability.

### Conclusion

The local gateway and the tested internet IP address were reachable.
DNS resolution returned addresses for google.com, and the webpage opened successfully over HTTPS.

### Security

This document does not include internal corporate network configuration, credentials, or customer data.