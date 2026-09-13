---
DocumentId: KB-EMAIL-001
DocumentName: Email Troubleshooting Guide
Category: Troubleshooting
Version: 1.0
Approved: true
Active: true
LastUpdated: 2026-01-10
---

# Email Troubleshooting Guide

## Section 1: Overview

This guide covers common Outlook/Exchange issues for Contoso employees, including sync
failures, mailbox quota warnings, and sign-in problems.

## Section 2: Mail Not Syncing

1. Confirm you have an active network or VPN connection.
2. Check the Outlook status bar for "Disconnected" or "Needs Password" — if shown, re-enter
   your credentials.
3. Restart Outlook. Cached mode can take up to 10 minutes to resynchronize a large mailbox.
4. If sync fails for longer than 30 minutes with no error message, this may indicate a service
   issue rather than a local problem — check current Email service status before further
   troubleshooting.

## Section 3: Mailbox Quota Warnings

Standard employee mailboxes have a 50 GB quota. When a mailbox exceeds 90% of quota:

- New mail delivery is not blocked until 100% is reached.
- Employees should archive items older than 12 months using the built-in Archive feature.
- Permanent quota increases require manager approval and are handled as a separate request,
  not through this assistant.

## Section 4: Sign-In Loops

Repeated password prompts in Outlook, after credentials are confirmed correct in the browser
version of email, usually indicate a stale cached credential. Clearing the Windows Credential
Manager entry for "Contoso Mail" and restarting Outlook resolves most cases.

## Section 5: Escalation

If none of the above resolves the issue within one attempt of each relevant section, escalate
with: mailbox size, exact error text, and whether the issue also affects the mobile Outlook app.
