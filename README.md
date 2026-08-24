# Windows DFIR Security Event Investigation

A hands-on Windows Digital Forensics and Incident Response (DFIR) investigation focused on reconstructing user activity from Windows Security Event Log and supporting Windows forensic artifacts.

The investigation centers on the `DFIR-Test` local account and reconstructs activity spanning account creation, account configuration, authentication, credential-related activity, cryptographic operations, account and group discovery, process-analysis validation, browser activity, and session termination.

The repository contains **137 numbered evidence screenshots** documenting the investigation from initial artifact collection through timeline reconstruction, evidence integrity verification, and final forensic correlation.

---

## Investigation Objective

The objective of this investigation was to reconstruct and analyze activity associated with the `DFIR-Test` account using Windows forensic evidence.

The investigation focused on:

- Windows Security Event Log analysis
- Account creation and configuration
- Authentication and interactive logon activity
- Explicit credential use
- Credential Manager activity
- Cryptographic and key-management events
- Account and group enumeration
- Process creation analysis
- PowerShell-related evidence
- Chrome browser artifacts
- Download and timestamp correlation
- Prefetch artifacts
- LNK artifacts
- Jump List artifacts
- ZimmermanTools forensic analysis
- Timeline reconstruction
- Logon ID correlation
- EVTX metadata
- SHA-256 evidence integrity verification
- Cross-artifact correlation
- Evidence-based DFIR reporting

The investigation uses multiple artifacts to establish context rather than treating a single Windows event as proof of malicious activity.

---

# Investigation Overview

The investigation followed a structured forensic workflow:

```text
Evidence Collection
        |
        v
Artifact Inventory
        |
        v
Windows Security Event Analysis
        |
        v
Account / Authentication Analysis
        |
        v
Browser Artifact Analysis
        |
        v
Prefetch / LNK / Jump List Analysis
        |
        v
Process / PowerShell Analysis
        |
        v
ZimmermanTools Analysis
        |
        v
Timeline Reconstruction
        |
        v
Cross-Artifact Correlation
        |
        v
Evidence Integrity Verification
        |
        v
Investigation Findings
