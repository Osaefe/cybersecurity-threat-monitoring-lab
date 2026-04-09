# Case 001: Brute Force Login Attempt

## Summary
Multiple failed login attempts were detected on a Windows VM over a 10-minute period.

## Symptoms
- Account lockouts  
- Repeated failed RDP login alerts  

## Investigation
- Monitored Windows Event Viewer Security logs  
- Captured network packets with Wireshark  
- Identified repeated login attempts from a single IP (simulated attacker machine)  

## Root Cause
Simulated brute-force login attempt on a test VM  

## Resolution
- Account temporarily locked for security  
- Alerts documented in incident report  

## Outcome
Incident mitigated and logged successfully. Skills demonstrated include threat detection, log monitoring, and incident documentation.
