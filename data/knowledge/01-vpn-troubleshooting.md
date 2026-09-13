---
DocumentId: KB-VPN-001
DocumentName: VPN Troubleshooting Guide
Category: Troubleshooting
Version: 1.0
Approved: true
Active: true
LastUpdated: 2026-01-10
---

# VPN Troubleshooting Guide

## Section 1: Overview

Contoso employees use the corporate VPN client ("Contoso Secure Connect") to reach internal
systems from outside the office network. This guide covers the most common connection
failures and the steps an employee can try before escalating to IT.

## Section 2: Common Error Codes

| Error Code | Meaning | First Step |
|---|---|---|
| 691 | Authentication failed (wrong username/password, or account locked) | Verify credentials; if MFA-enrolled, confirm the authenticator prompt was approved. |
| 619 | Connection interrupted between client and VPN server | Check local internet connectivity, then retry. |
| 800 | Unable to establish a VPN connection at all | Restart Contoso Secure Connect; confirm no other VPN client is running. |
| 429 | Too many connection attempts in a short period | Wait 5 minutes before retrying; repeated triggering may indicate a credential problem. |

## Section 3: Resetting the VPN Client

1. Close Contoso Secure Connect completely (check the system tray, not just the window).
2. Restart the application.
3. Re-enter your corporate username (not your email alias) and password.
4. Approve the MFA prompt on your registered device within 60 seconds.
5. If the connection still fails after two attempts, do not keep retrying — proceed to escalation.

## Section 4: Escalation Path

If VPN access is still unavailable after following Section 3, check current VPN service status
before assuming a personal device problem. If status shows an active outage, no further
troubleshooting is required — wait for resolution. Otherwise, open a support request with the
exact error code and the time the issue started.
