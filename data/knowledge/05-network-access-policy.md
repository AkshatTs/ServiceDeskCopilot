---
DocumentId: POL-NETWORK-001
DocumentName: Network Access Policy
Category: Policy
Version: 1.4
Approved: true
Active: true
LastUpdated: 2025-10-15
---

# Network Access Policy

## Section 1: Purpose

This policy governs how employees, contractors, and guests connect to Contoso's wired and
wireless networks.

## Section 2: Wired Network Access

Wired ports in Contoso offices are restricted to company-issued devices by default (802.1X
certificate-based authentication). Connecting a personal device to a wired port requires prior
approval from the workplace technology team.

## Section 3: Guest Wireless Network

The "Contoso-Guest" wireless network is available to visitors and personal devices. It is
isolated from the internal corporate network and cannot reach internal file shares, internal
web applications, or the internal ticketing system. Guest network access does not require MFA
but does require accepting the acceptable-use terms shown at first connection.

Employees may use the guest network for personal devices, but **corporate work should be
performed on the corporate network (via approved Wi-Fi or VPN)**, not the guest network, so
that security controls and monitoring apply correctly.

## Section 4: VPN Access Requirements

VPN access requires an active Contoso account, MFA enrollment, and a device meeting the
Corporate Device Policy. VPN access is automatically revoked when an employee's account is
disabled.
