---
DocumentId: KB-TEAMS-001
DocumentName: Teams Troubleshooting Guide
Category: Troubleshooting
Version: 1.0
Approved: true
Active: true
LastUpdated: 2026-01-05
---

# Teams Troubleshooting Guide

## Section 1: Overview

This guide covers common Contoso Teams issues: sign-in failures, audio/video problems, and how
outages are communicated.

## Section 2: Sign-In Failures

1. Confirm the employee can sign in to Outlook/email with the same account — if email also
   fails, this is an identity issue, not a Teams-specific issue.
2. Clear the Teams cache (sign out, close Teams completely, reopen).
3. If sign-in fails only on Teams and only on one device, reinstalling the Teams client
   usually resolves it.

## Section 3: Audio/Video Issues

- Confirm the correct microphone/camera is selected in Teams device settings, not just the OS
  default.
- For choppy audio during calls, ask whether the employee is on VPN — VPN adds latency for
  real-time audio/video and disconnecting from VPN (while keeping normal internet) often
  resolves quality issues for calls that do not require internal resources.
- Camera not detected: confirm no other application (e.g., a second video app) is already
  using the camera.

## Section 4: Known Outage Communication

When Teams has a known, current outage, the status will be reflected as "Outage" or
"Degraded" in the service status system. This assistant must check current status before
telling an employee that "Teams is down" — it must never assume an outage from a single
user's report alone.

## Section 5: Escalation

If sign-in fails and email also fails and status shows Teams as Operational, escalate as an
account/identity issue, not a Teams issue.
