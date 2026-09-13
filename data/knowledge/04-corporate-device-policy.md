---
DocumentId: POL-DEVICE-001
DocumentName: Corporate Device Policy
Category: Policy
Version: 2.1
Approved: true
Active: true
LastUpdated: 2025-11-01
---

# Corporate Device Policy

## Section 1: Purpose

This policy defines which devices may access Contoso systems and under what conditions,
covering both company-issued and personally-owned ("BYOD") devices.

## Section 2: Personally-Owned Devices (BYOD)

Personally-owned laptops and phones **may** connect to the corporate network under the
following conditions only:

- The device is enrolled in Contoso Mobile Device Management (MDM).
- The device has current OS security patches installed (within 30 days of release).
- Disk encryption is enabled.
- The device is used only for approved corporate applications (email, Teams, approved
  business apps) — not for general network browsing on the corporate VLAN.

BYOD access to the internal corporate network (as opposed to the guest network) additionally
requires the standard VPN client and MFA, the same as a company-issued device.

## Section 3: Company-Issued Device Requirements

Company-issued devices must:

- Remain on the current supported OS version.
- Have endpoint protection software active at all times.
- Not have administrative/root access removed or altered by the employee.

## Section 4: Non-Compliance

A device that fails MDM compliance checks (Section 2) will have its access to internal
systems automatically suspended until compliance is restored. This is an automated control,
not a decision made by IT support staff or this assistant.
