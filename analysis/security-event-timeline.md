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

The reconstructed activity shows the progression from account creation and configuration to authentication and subsequent account/group discovery activity.

The analyzed session associated with `DFIR-Test` lasted approximately **14 minutes and 37 seconds**, from the successful logon at `13:36:18` to the user-initiated logoff at `13:50:55`.
