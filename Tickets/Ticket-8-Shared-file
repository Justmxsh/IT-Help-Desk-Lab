# Ticket 8 — Shared Drive Access

## Issue
User reported being unable to access a company shared drive.

## User Impact
The user could not access files required for their project, while other employees were still able to access the shared drive.

## Troubleshooting Performed

Confirmed the user had working internet access.
Asked for the exact error message.
Tested the shared drive directly using:
  `\\fileserver\shared`
Confirmed the user had previously been able to access the drive.\
Confirmed the user was logged into the correct company account using:
  `whoami`
Verified the account as:
  `company\Sarah`
Checked existing network connections using:
  `net use`
Confirmed there were no existing mapped network connections.
Tested connectivity to the file server using:
  `ping fileserver`
Confirmed 0% packet loss.
Tested DNS resolution using:
  `nslookup fileserver`
Confirmed `fileserver` resolved to `192.168.1.20`.
Confirmed other employees could access the shared drive.
Confirmed the user was expected to have access through the Project Alpha group.
Determined that Active Directory group membership could not be verified because Tier 1 did not have access to the AD management console.

## Findings

The file server was reachable and DNS resolution was working correctly. The issue appeared to be specific to the user's access permissions.

Further investigation of the user's Active Directory group membership and/or shared-drive permissions was required.

## Resolution

Documented the troubleshooting performed and escalated the ticket to the appropriate team responsible for Active Directory and file-share permissions.

## Ticket Status
**Escalated**

## Skills Demonstrated

Windows troubleshooting
Network troubleshooting
DNS troubleshooting
File-share troubleshooting
Active Directory concepts
Access control
Command Prompt
`whoami`
`net use`
`ping`
`nslookup`
Incident documentation
- Ticket escalation
