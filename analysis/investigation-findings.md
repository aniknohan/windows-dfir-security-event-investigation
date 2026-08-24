# Investigation Findings

## Executive Summary

Analysis of the Windows Security event log identified a sequence of activity associated with the `DFIR-Test` local account.

The evidence shows account creation and configuration followed by authentication, credential-related activity, security-group enumeration, local-account discovery, and an eventual user-initiated logoff.

## Key Findings

### 1. Account Creation and Configuration

At `13:25:37`, Windows recorded several account-management events involving `DFIR-Test`:

- Event ID 4720 — account created
- Event ID 4722 — account enabled
- Event ID 4724 — password reset attempted
- Event ID 4732 — account added to the Builtin Users group
- Event ID 4738 — account changed

These events establish the creation and initial configuration of the account.

### 2. Authentication

At `13:36:18`, Event ID 4648 recorded the use of explicit credentials associated with `DFIR-Test`.

Event ID 4624 at the same timestamp recorded a successful interactive logon.

The associated Logon ID was:

`0xA8119D`

This identifier was used to correlate subsequent activity within the session.

### 3. Credential and Cryptographic Activity

Shortly after authentication, the log recorded:

- Event ID 5379 — Credential Manager credentials read
- Event ID 5061 — cryptographic operation
- Event ID 5058 — key file operation
- Event ID 5059 — key migration operation

These events occurred within seconds of the successful logon and form part of the reconstructed session activity.

### 4. Account and Group Discovery

Later activity included:

- Event ID 4799 — Administrators group membership enumeration
- Event ID 4797 — local-account blank-password queries
- Event ID 4798 — user local-group membership enumeration

Together, these events demonstrate account and group discovery activity during the session.

### 5. Session Termination

Event ID 4647 recorded a user-initiated logoff for `DFIR-Test` at `13:50:55`.

The reconstructed session from successful logon to logoff lasted approximately **14 minutes and 37 seconds**.

## Assessment

The Windows Security log provides sufficient evidence to reconstruct a coherent sequence of account-management, authentication, credential-related, discovery, and logoff activity associated with `DFIR-Test`.

The investigation demonstrates the use of Windows Event IDs, timestamps, account identifiers, and Logon ID correlation to reconstruct activity from a Windows Security event log.
