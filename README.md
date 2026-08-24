# Windows DFIR Security Event Investigation

> **Windows Digital Forensics & Incident Response case study focused on reconstructing activity associated with the `DFIR-Test` local account.**

This investigation analyzes Windows Security Event Log evidence and supporting Windows forensic artifacts to reconstruct account activity, authentication, credential-related activity, discovery behavior, process analysis, browser activity, and session termination.

**137 numbered evidence screenshots** document the investigation from artifact collection through timeline reconstruction and evidence-integrity verification.

---

## Executive Summary

The investigation reconstructed a sequence of activity associated with the `DFIR-Test` account.

The observed activity includes:

- Account creation and configuration
- Authentication and interactive logon
- Explicit credential use
- Credential Manager activity
- Cryptographic and key-management events
- Account and group enumeration
- Process-creation analysis
- PowerShell-related investigation
- Browser and download artifacts
- Prefetch, LNK, and Jump List analysis
- ZimmermanTools analysis
- Timeline correlation
- EVTX metadata and SHA-256 integrity verification
- User-initiated logoff

The investigation focuses on **correlating multiple forensic artifacts** rather than treating an individual Windows event as independent proof of malicious activity.

---

## Investigation Scope

**Primary account:** `DFIR-Test`

**Primary evidence source:** Windows Security Event Log

**Supporting artifacts:**

- Security Event Log (`Security.evtx`)
- Chrome browser artifacts
- Download artifacts
- Prefetch
- LNK files
- Jump Lists
- PowerShell evidence
- Process creation events
- ZimmermanTools output
- EVTX metadata
- SHA-256 integrity evidence

---

## Investigation Workflow

| Phase | Objective |
|---|---|
| Evidence Collection | Identify and document available forensic artifacts |
| Event Analysis | Examine relevant Windows Security Event IDs |
| Account Analysis | Reconstruct account creation and configuration |
| Authentication Analysis | Correlate explicit credentials and successful logon |
| Artifact Analysis | Examine browser, Prefetch, LNK, and Jump List evidence |
| Process Analysis | Investigate Event 4688 and PowerShell-related activity |
| Timeline Reconstruction | Correlate timestamps and account identifiers |
| Integrity Verification | Document EVTX metadata and SHA-256 verification |
| Findings | Produce an evidence-based investigative assessment |

---

# Key Findings

### Account Creation & Configuration

At `13:25:37`, Windows recorded multiple account-management events associated with `DFIR-Test`:

| Event | Activity |
|---:|---|
| 4720 | Account created |
| 4722 | Account enabled |
| 4724 | Password reset attempted |
| 4728 | Security-enabled global group membership changed |
| 4732 | Account added to Builtin Users group |
| 4738 | Account changed |

---

### Authentication

At `13:36:18`:

- **Event 4648** — explicit credentials used
- **Event 4624** — successful interactive logon

**Logon ID:**

```text
0xA8119D
