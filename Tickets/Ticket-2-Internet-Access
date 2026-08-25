# Ticket 2 — User Cannot Access Internet

## Issue
User reported being unable to access the internet from their workstation.

## User Impact
The user was unable to access websites and required network connectivity to perform their work.

## Troubleshooting Performed

Confirmed the user's network connection.
Checked the workstation's IP configuration.
Released the current DHCP address using:
  `ipconfig /release`
Renewed the DHCP address using:
  `ipconfig /renew`
Tested connectivity to the local gateway using:
  `ping 192.168.1.1`
Tested external network connectivity using:
  `ping 8.8.8.8`
Tested DNS/name resolution using:
  `ping google.com`
Reviewed the complete network configuration using:
  `ipconfig /all`
Tested DNS resolution using:
  `nslookup google.com`
Tested DNS resolution against Google's DNS server using:
  `nslookup google.com 8.8.8.8`

## Findings

The troubleshooting process was used to determine whether the issue was related to DHCP, the local network gateway, internet connectivity, or DNS resolution.

## Resolution

Network connectivity and DNS functionality were verified through the troubleshooting tests. The user was able to access websites after troubleshooting.

## Ticket Status
**Resolved**

## Skills Demonstrated

Windows network troubleshooting
DHCP troubleshooting
DNS troubleshooting
TCP/IP fundamentals
Command Prompt
`ipconfig`
`ping`
`nslookup`
Network connectivity testing
- Ticket documentation
