# Case 002: Port Scan Detection

## Summary
Unusual network traffic indicated port scanning activity from a test host.

## Symptoms
- Multiple connection attempts to sequential ports  
- Increased ICMP traffic  

## Investigation
- Captured traffic using Wireshark  
- Verified scan pattern using Kali VM  
- Filtered logs to isolate suspicious activity  

## Root Cause
Simulated port scanning by lab attacker VM  

## Resolution
- Documented scan patterns and affected hosts  
- Confirmed no actual services were compromised  

## Outcome
Successfully detected and reported port scan activity, demonstrating network monitoring and anomaly detection skills.
