#  Port Scanner
Port scanners are valuable tools in diagnosing network and connectivity issues. However, attackers use port scanners to detect possible access points for infiltration and to identify what kinds of devices you are running on the network, like firewalls, proxy servers or VPN servers.

## Port Scanning Basics
* Open, Accepted: The computer responds and asks if there is anything it can do for you.
* Closed, Not Listening: The computer responds that “This port is currently in use and unavailable at this time.”
* Filtered, Dropped, Blocked: The computer doesn’t even bother to respond.

## Ping Scanner
The simplest port scans are ping scans. A ping is an Internet Control Message Protocol (ICMP) echo request – you are looking for any ICMP replies, which indicates that the target is alive. A ping scan is an automated blast of many ICMP echo requests to different targets to see who responds. Ping scans aren’t technically port scanning techniques, as the best you can get back is that there is a computer on the other end, but it’s related and usually the first task before you do a port scan.

## TCP Connect
This port scanning technique is basically the same as the TCP Half-Open scan, but instead of leaving the target hanging, the port scanner completes the TCP connection.

## UDP
UDP scans are slower than TCP scans, but there are plenty of exploitable UDP services that attackers can use, DNS exfiltration, for example. Defenders need to protect their UDP ports with the same voracity as their TCP ports.

## Why Should You Run a Port Scan?
You should run port scans proactively to detect and close all possible vulnerabilities that attackers might exploit.

