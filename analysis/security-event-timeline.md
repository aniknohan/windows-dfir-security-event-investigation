# Security Event Timeline

## Investigation Scope

Windows Security event logs were analyzed to reconstruct activity associated with the `DFIR-Test` account.

## Reconstructed Timeline

| Timestamp | Event ID | Activity |
|---|---:|---|
| 2026-08-22 13:25:37 | 4720 | DFIR-Test account created |
| 2026-08-22 13:25:37 | 4722 | DFIR-Test account enabled |
| 2026-08-22 13:25:37 | 4724 | Password reset attempted for DFIR-Test |
| 2026-08-22 13:25:37 | 4728 | Security-enabled global group membership changed |
| 2026-08-22 13:25:37 | 4732 | DFIR-Test added to Builtin Users group |
| 2026-08-22 13:25:37 | 4738 | DFIR-Test account changed |
| 2026-08-22 13:36:18 | 4648 | Explicit credentials used for DFIR-Test |
| 2026-08-22 13:36:18 | 4624 | Successful interactive logon |
| 2026-08-22 13:36:20 | 5379 | Credential Manager credentials read |
| 2026-08-22 13:36:21 | 5061 | Cryptographic operation |
| 2026-08-22 13:36:21 | 5058 | Key file operation |
| 2026-08-22 13:36:21 | 5059 | Key migration operation |
| 2026-08-22 13:36:58 | 4799 | Administrators group membership enumerated |
| 2026-08-22 13:49:49 | 4797 | Local account blank-password queries |
| 2026-08-22 13:49:50 | 4798 | User local-group membership enumeration |
| 2026-08-22 13:50:55 | 4647 | DFIR-Test initiated logoff |

## Session Summary

The reconstructed activity shows a progression from account creation and configuration to authentication, credential-related activity, cryptographic/key operations, account and group enumeration, and eventual logoff.

The `DFIR-Test` account was created, enabled, modified, and associated with group membership changes before a successful interactive logon occurred. Following authentication, the timeline records credential-related activity, cryptographic and key-management events, and subsequent local account and group enumeration.

The analyzed session associated with `DFIR-Test` lasted approximately 14 minutes and 37 seconds, from the successful logon at `13:36:18` to the user-initiated logoff at `13:50:55`.

This timeline represents a reconstruction of observed Windows Security events. Individual events should be interpreted in context and correlated with the supporting forensic artifacts rather than treated as independent proof of malicious activity.

## Key Investigation Observations

- The `DFIR-Test` account was created and enabled before the observed interactive authentication.
- Account configuration and group-membership changes occurred during the initial setup phase.
- Event `4648` records explicit credential use associated with `DFIR-Test`.
- Event `4624` records a successful interactive logon.
- Event `5379` records Credential Manager credential access during the authenticated session.
- Events `5061`, `5058`, and `5059` document cryptographic and key-related operations.
- Events `4799`, `4797`, and `4798` show subsequent account and group enumeration activity.
- Event `4647` marks the end of the observed user session through an initiated logoff.
- The timeline should be correlated with the browser, process, PowerShell, EVTX, and ZimmermanTools evidence contained in the repository.

