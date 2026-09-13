---
DocumentId: KB-MFA-001
DocumentName: MFA Troubleshooting Guide
Category: Troubleshooting
Version: 1.0
Approved: true
Active: true
LastUpdated: 2026-01-10
---

# MFA Troubleshooting Guide

## Section 1: Overview

All Contoso accounts require multi-factor authentication (MFA) using the Contoso Authenticator
app. This guide covers lost-device recovery and re-enrollment.

## Section 2: Lost or New Authenticator Device

If an employee no longer has access to their registered authenticator device:

1. The employee cannot self-service a full MFA reset from a personal device for security
   reasons.
2. The employee should request a **Temporary Access Pass (TAP)** through the identity portal,
   which requires manager or IT approval and identity verification.
3. A TAP is time-limited (default 8 hours) and single-use for re-enrollment only.

## Section 3: Re-Enrolling the Authenticator App

1. Sign in using the Temporary Access Pass.
2. Navigate to Security Info in the identity portal.
3. Remove the old authenticator method only after the new device is successfully added.
4. Confirm by signing out and back in, verifying the new device receives the prompt.

## Section 4: "Number Matching" Prompts Not Arriving

If MFA push notifications are not arriving on an otherwise-working device:

- Confirm notifications are enabled for the Authenticator app in the device's OS settings.
- Confirm the device has an active internet or cellular data connection.
- As a fallback, the Authenticator app can generate a one-time code manually without needing
  a push notification, if the account was enrolled for that method.

## Section 5: What This Assistant Will Never Do

This assistant cannot issue a Temporary Access Pass, reset MFA, or bypass MFA on behalf of a
user. Those actions require identity-team verification through the identity portal.
