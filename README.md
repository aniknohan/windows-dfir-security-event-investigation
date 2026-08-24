# Windows DFIR Security Event Investigation

<p align="center">

**Windows Digital Forensics & Incident Response Case Study**

Windows Security Event Log Analysis • Account Investigation • Timeline Reconstruction • Evidence Correlation

</p>

<p align="center">

![Windows](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![DFIR](https://img.shields.io/badge/Focus-DFIR-critical?style=for-the-badge)
![Digital Forensics](https://img.shields.io/badge/Domain-Digital%20Forensics-blue?style=for-the-badge)
![Incident Response](https://img.shields.io/badge/Focus-Incident%20Response-orange?style=for-the-badge)
![Evidence](https://img.shields.io/badge/Evidence-137%20Screenshots-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

</p>

---

# 📌 Project Overview

This repository documents a hands-on **Windows Digital Forensics and Incident Response (DFIR)** investigation focused on reconstructing activity associated with the local Windows account:

```text
DFIR-Test
```

The investigation uses the **Windows Security Event Log** as the primary source of evidence and correlates those events with supporting Windows forensic artifacts.

The investigation covers:

- Account creation and configuration
- Account enablement
- Password-management activity
- Group membership changes
- Authentication
- Explicit credential use
- Successful interactive logon
- Credential Manager activity
- Cryptographic operations
- Key-management activity
- Account enumeration
- Group enumeration
- Process creation analysis
- PowerShell investigation
- Chrome browser artifacts
- Download artifacts
- Prefetch artifacts
- LNK artifacts
- Jump Lists
- ZimmermanTools analysis
- Timeline reconstruction
- EVTX metadata
- SHA-256 evidence verification
- User-initiated logoff

The repository contains **137 screenshots** documenting the investigation and supporting the documented findings.

> **Forensic principle:** Individual Windows events are interpreted in context and correlated with supporting evidence. A single event is not automatically treated as proof of malicious activity.

---

# 🔎 Investigation Scenario

The investigation was conducted in a controlled Windows environment.

The primary investigative subject was the local account:

```text
DFIR-Test
```

The objective was to reconstruct what activity could be established from the available Windows forensic evidence.

The investigation began with artifact identification and Windows Security Event Log analysis and progressed through authentication correlation, credential-related activity, discovery activity, process investigation, browser analysis, Windows artifact examination, timeline reconstruction, and evidence-integrity verification.

The investigation follows an evidence-first methodology:

```text
COLLECT
   ↓
IDENTIFY
   ↓
ANALYZE
   ↓
CORRELATE
   ↓
RECONSTRUCT
   ↓
VERIFY
   ↓
REPORT
```

---

# 🎯 Investigation Objectives

The investigation objectives were to:

- Identify the available forensic artifacts.
- Examine Windows Security Event Log activity.
- Reconstruct the `DFIR-Test` account lifecycle.
- Identify account creation and configuration activity.
- Analyze authentication activity.
- Correlate explicit credential use with successful authentication.
- Identify the relevant Logon ID.
- Investigate Credential Manager activity.
- Analyze cryptographic and key-management events.
- Identify account and group enumeration.
- Investigate Event ID `4688` process creation activity.
- Examine PowerShell-related evidence.
- Analyze Chrome browser artifacts.
- Examine download artifacts.
- Analyze Prefetch artifacts.
- Analyze LNK artifacts.
- Analyze Jump List artifacts.
- Use ZimmermanTools to support forensic analysis.
- Reconstruct a chronological timeline.
- Verify EVTX evidence integrity.
- Calculate and document SHA-256 hashes.
- Produce an evidence-based forensic assessment.

---

# 🗂️ Investigation Scope

## Primary Account

```text
DFIR-Test
```

## Primary Evidence Source

```text
Security.evtx
```

Windows Security Event Log analysis forms the core of the investigation.

## Supporting Evidence

| Evidence Source | Purpose |
|---|---|
| Windows Security Event Log | Account, authentication, discovery, process, and session analysis |
| Chrome artifacts | Browser activity |
| Download artifacts | Download activity and metadata |
| Prefetch | Application execution context |
| LNK artifacts | File and application references |
| Jump Lists | Application and user-activity context |
| PowerShell evidence | PowerShell investigation |
| Event ID 4688 | Process creation analysis |
| ZimmermanTools | Windows forensic artifact analysis |
| EVTX metadata | Evidence documentation |
| SHA-256 | Evidence integrity verification |

---

# 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| Windows Event Viewer | Security Event Log analysis |
| Windows Security Event Log | Primary forensic evidence |
| PowerShell | Forensic analysis and validation |
| Chrome artifacts | Browser investigation |
| Prefetch | Execution-related artifact analysis |
| LNK files | File/application artifact analysis |
| Jump Lists | User/application activity analysis |
| ZimmermanTools | Windows forensic analysis |
| SHA-256 | Evidence integrity verification |
| GitHub | Evidence and investigation documentation |

---

# 🧭 Investigation Workflow

The investigation followed the following workflow:

### Phase 1 — Evidence Collection

Identify and document available Windows forensic artifacts.

### Phase 2 — Security Event Analysis

Examine relevant Windows Security Event IDs and associated account information.

### Phase 3 — Account Investigation

Reconstruct the lifecycle of the `DFIR-Test` account.

### Phase 4 — Authentication Analysis

Correlate Event IDs `4648` and `4624` and identify the associated Logon ID.

### Phase 5 — Credential & Cryptographic Analysis

Examine Credential Manager, cryptographic, and key-management activity.

### Phase 6 — Discovery Analysis

Investigate account and group enumeration events.

### Phase 7 — Process & PowerShell Analysis

Examine Event ID `4688` and PowerShell-related evidence.

### Phase 8 — Browser & Windows Artifact Analysis

Analyze Chrome, downloads, Prefetch, LNK, and Jump List evidence.

### Phase 9 — ZimmermanTools Analysis

Use ZimmermanTools output to support forensic artifact and timeline analysis.

### Phase 10 — Timeline Reconstruction

Correlate timestamps, Event IDs, account identifiers, and Logon IDs.

### Phase 11 — Evidence Integrity

Document EVTX metadata and SHA-256 evidence verification.

### Phase 12 — Final Assessment

Separate observed evidence from analyst interpretation and produce the final investigative assessment.

---

# 📁 Repository Structure

```text
windows-dfir-security-event-investigation/
│
├── README.md
│
├── analysis/
│   ├── investigation-findings.md
│   └── security-event-timeline.md
│
└── evidence/
    └── screenshots/
        ├── 01-...
        ├── 02-...
        ├── ...
        ├── 136-...
        └── 137-...
```

---

# 📚 Investigation Documentation

The repository contains dedicated analysis documents supporting this case study.

## Investigation Findings

The investigation findings document contains the detailed analytical assessment of the Windows Security Event Log evidence.

➡️ **[Read the Complete Investigation Findings](analysis/investigation-findings.md)**

---

## Security Event Timeline

The timeline document reconstructs the chronological activity associated with `DFIR-Test`.

➡️ **[Read the Complete Security Event Timeline](analysis/security-event-timeline.md)**

---

# 🔐 Account Lifecycle Analysis

The initial account-management activity occurred at:

```text
2026-08-22 13:25:37
```

The following events were identified:

| Event ID | Activity |
|---:|---|
| `4720` | DFIR-Test account created |
| `4722` | DFIR-Test account enabled |
| `4724` | Password reset attempted |
| `4728` | Security-enabled global group membership changed |
| `4732` | DFIR-Test added to Builtin Users group |
| `4738` | DFIR-Test account changed |

These events establish the observed creation and configuration phase of the account.

---

# 🔑 Authentication Analysis

At:

```text
2026-08-22 13:36:18
```

the investigation identified two important authentication events.

| Event ID | Activity |
|---:|---|
| `4648` | Explicit credentials used |
| `4624` | Successful interactive logon |

The associated Logon ID documented during the investigation was:

```text
0xA8119D
```

The Logon ID was used as a correlation point when examining subsequent activity within the observed session.

---

# 🔐 Credential & Cryptographic Activity

Shortly after authentication, the Security Event Log recorded:

| Event ID | Activity |
|---:|---|
| `5379` | Credential Manager credentials read |
| `5061` | Cryptographic operation |
| `5058` | Key file operation |
| `5059` | Key migration operation |

The events occurred within seconds of the successful logon.

They are documented as observed forensic activity and are not independently classified as malicious.

---

# 🔍 Account & Group Discovery

Later activity included:

| Event ID | Activity |
|---:|---|
| `4799` | Administrators group membership enumerated |
| `4797` | Local account blank-password queries |
| `4798` | User local-group membership enumeration |

These events document account and group discovery activity within the observed investigation window.

---

# ⚙️ Process Creation Analysis

Event ID `4688` process-creation activity was investigated as part of the broader forensic analysis.

The investigation included:

- Process-creation searches
- Process summaries
- Process analysis
- Event ID frequency analysis
- Searches associated with `DFIR-Test`
- Documentation of searches producing no matching results

Negative results were retained as part of the evidence trail.

A negative search result does not establish that the corresponding activity did or did not occur outside the searched evidence.

---

# 💻 PowerShell Investigation

PowerShell-related evidence was examined as part of the process and execution investigation.

The evidence includes PowerShell-related forensic analysis and supporting Windows event information.

PowerShell evidence was evaluated together with the Security Event Log and other artifacts rather than treated as an isolated finding.

---

# 🌐 Browser & Download Analysis

Chrome artifacts were examined to identify supporting browser and download activity.

The investigation includes analysis of:

- Browser history
- Download activity
- Download URLs
- Download timestamps
- Download state
- Download target paths
- Related browser activity
- ZimmermanTools-related browser evidence

Browser evidence provides supporting temporal and activity context for the broader investigation.

---

# 🚀 Prefetch Analysis

Prefetch artifacts were examined to provide application-execution and timeline context.

The investigation includes:

- Prefetch artifact identification
- Prefetch timeline information
- Execution-related analysis

Prefetch artifacts were interpreted together with other evidence sources.

---

# 📄 LNK Artifact Analysis

LNK artifacts were examined for additional file and application context.

The investigation includes:

- LNK artifact identification
- Target paths
- Timeline information
- File references
- Application references

LNK evidence was used as supporting forensic context.

---

# 📑 Jump List Analysis

Jump List artifacts were examined for additional application and user-activity context.

The investigation includes:

- Jump List file references
- Application-related activity
- Timeline context

These artifacts were considered together with other Windows forensic evidence.

---

# 🧰 ZimmermanTools Analysis

ZimmermanTools was used to support analysis of Windows forensic artifacts and timeline information.

The evidence collection includes ZimmermanTools-related:

- Browser analysis
- Execution/timeline analysis
- Artifact-directory analysis
- Supporting forensic evidence

ZimmermanTools results were interpreted alongside the underlying Windows evidence.

---

# 🧾 EVTX Metadata & Integrity

Evidence-integrity analysis was performed on the event-log evidence.

The investigation documents:

- EVTX metadata
- File information
- SHA-256 hashing
- SHA-256 verification
- Evidence-directory information

The purpose of this stage was to provide an integrity-verification layer for the analyzed event-log evidence.

---

# 🕒 Reconstructed Security Event Timeline

The principal Security Event activity was reconstructed as follows:

| Timestamp | Event ID | Activity |
|---|---:|---|
| `2026-08-22 13:25:37` | 4720 | DFIR-Test account created |
| `2026-08-22 13:25:37` | 4722 | DFIR-Test account enabled |
| `2026-08-22 13:25:37` | 4724 | Password reset attempted |
| `2026-08-22 13:25:37` | 4728 | Security-enabled global group membership changed |
| `2026-08-22 13:25:37` | 4732 | DFIR-Test added to Builtin Users group |
| `2026-08-22 13:25:37` | 4738 | DFIR-Test account changed |
| `2026-08-22 13:36:18` | 4648 | Explicit credentials used |
| `2026-08-22 13:36:18` | 4624 | Successful interactive logon |
| `2026-08-22 13:36:20` | 5379 | Credential Manager credentials read |
| `2026-08-22 13:36:21` | 5061 | Cryptographic operation |
| `2026-08-22 13:36:21` | 5058 | Key file operation |
| `2026-08-22 13:36:21` | 5059 | Key migration operation |
| `2026-08-22 13:36:58` | 4799 | Administrators group membership enumerated |
| `2026-08-22 13:49:49` | 4797 | Local account blank-password queries |
| `2026-08-22 13:49:50` | 4798 | User local-group membership enumeration |
| `2026-08-22 13:50:55` | 4647 | DFIR-Test initiated logoff |

### Observed Session

**Start:** `13:36:18`

**End:** `13:50:55`

**Duration:** approximately **14 minutes 37 seconds**

➡️ **[View Detailed Security Event Timeline](analysis/security-event-timeline.md)**

---

# 🔗 Evidence Correlation

The investigation did not rely on a single evidence source.

The analytical relationship between the major evidence categories can be represented as:

```text
                 WINDOWS SECURITY EVENTS
                           │
                           ▼
                  ACCOUNT LIFECYCLE
                           │
                           ▼
                    AUTHENTICATION
                           │
                           ▼
              CREDENTIAL / CRYPTO ACTIVITY
                           │
                           ▼
                  DISCOVERY ACTIVITY
                           │
             ┌─────────────┼─────────────┐
             ▼             ▼             ▼
         PROCESS       POWERSHELL     BROWSER
         ANALYSIS      ANALYSIS       ANALYSIS
             │             │             │
             └─────────────┼─────────────┘
                           ▼
                  WINDOWS ARTIFACTS
                ┌──────────┼──────────┐
                ▼          ▼          ▼
            PREFETCH      LNK      JUMP LISTS
                │          │          │
                └──────────┼──────────┘
                           ▼
                    ZIMMERMANTOOLS
                           │
                           ▼
                  TIMELINE RECONSTRUCTION
                           │
                           ▼
                    INTEGRITY CHECK
                           │
                           ▼
                  FINAL INVESTIGATION
```

This approach separates:

```text
Observed Evidence
       ↓
Correlated Activity
       ↓
Analyst Interpretation
```

---

# 🖼️ Evidence Collection

## 137 Numbered Investigation Screenshots

This repository contains **137 numbered forensic evidence screenshots** documenting the investigation from initial artifact collection through Security Event Log analysis, artifact correlation, timeline reconstruction, and evidence-integrity verification.

Each screenshot is preserved in:

`evidence/screenshots/`

The screenshots are numbered from **01 through 137** so that every visual artifact can be correlated with the corresponding evidence explanation.

### 📸 Browse All 137 Screenshots

➡️ **[Open the Complete 137-Screenshot Evidence Collection](evidence/screenshots/)**

This opens the repository directory containing all numbered PNG evidence files.

### 📝 Evidence Explanations

Every screenshot has a corresponding evidence entry explaining:

- What the screenshot shows
- Why the evidence matters
- Its role in the investigation
- The forensic context in which it should be interpreted

➡️ **[Open the Complete 137-Screenshot Evidence Notes](evidence/evidence-notes.md)**

### 🔗 Evidence-to-Screenshot Navigation

The evidence documentation follows the same numbering system as the screenshot files.

| Evidence | Screenshot | Documentation |
|---|---|---|
| 001 | `01-windows-dfir-lab-directory-structure.png` | Evidence 001 |
| 002 | `02-evidence-artifact-inventory.png` | Evidence 002 |
| 003 | `03-prefetch-artifact-inventory.png` | Evidence 003 |
| ... | ... | ... |
| 135 | `135-windows-dfir-lab-directory-tree-part-2.png` | Evidence 135 |
| 136 | `136-zimmerman-tools-correlated-execution-timeline.png` | Evidence 136 |
| 137 | `137-zimmerman-tools-empty-directory-evidence.png` | Evidence 137 |

> **Evidence navigation:** Open the evidence notes to review the explanation for each numbered artifact, then select the corresponding screenshot filename to open the original PNG evidence.

### 📂 Evidence Organization

```text
evidence/
├── evidence-notes.md
└── screenshots/
    ├── 01-*.png
    ├── 02-*.png
    ├── 03-*.png
    ├── ...
    ├── 135-*.png
    ├── 136-*.png
    └── 137-*.png

---

# 📂 Complete Investigation Access

The repository separates the visual evidence, evidence explanations, analytical findings, and reconstructed timeline so that the investigation can be reviewed systematically.

| Resource | Purpose |
|---|---|
| 📸 [137 Evidence Screenshots](evidence/screenshots/) | Complete numbered visual evidence collection |
| 📝 [Evidence Notes](evidence/evidence-notes.md) | Explanations and forensic context for the 137 screenshots |
| 🔎 [Investigation Findings](analysis/investigation-findings.md) | Consolidated analytical findings |
| 🕒 [Security Event Timeline](analysis/security-event-timeline.md) | Reconstructed chronological activity |

### Recommended Review Order

```text
README
  ↓
Evidence Notes
  ↓
137 Evidence Screenshots
  ↓
Investigation Findings
  ↓
Security Event Timeline
  ↓
Final Assessment

---

# 📸 Evidence Coverage

The 137 screenshots document the investigation across the following areas:

| Evidence Area | Coverage |
|---|---|
| Investigation Workspace | Lab environment and evidence locations |
| Artifact Inventory | Identification of available forensic artifacts |
| Security Events | Windows Security Event Log analysis |
| Account Lifecycle | Account creation and configuration |
| Authentication | Events 4624 and 4648 |
| Logon Correlation | Logon ID and timestamp correlation |
| Credential Activity | Credential Manager evidence |
| Cryptographic Activity | Events 5058, 5059, and 5061 |
| Discovery | Events 4797, 4798, and 4799 |
| Process Analysis | Event 4688 investigation |
| PowerShell | PowerShell-related analysis |
| Chrome | Browser artifact analysis |
| Downloads | Download artifact analysis |
| Prefetch | Execution artifact analysis |
| LNK | File/application artifact analysis |
| Jump Lists | User/application artifact analysis |
| ZimmermanTools | Forensic analysis and timeline evidence |
| Timeline | Chronological reconstruction |
| EVTX | Event-log metadata |
| SHA-256 | Evidence-integrity verification |

---

# 📂 Complete Evidence Access

The screenshots are maintained separately from the analytical documents so that the evidence can be reviewed directly without making the main case narrative unnecessarily difficult to navigate.

### Primary Evidence

➡️ **[Open All 137 Screenshots](evidence/screenshots/)**

### Findings

➡️ **[Open Investigation Findings](analysis/investigation-findings.md)**

### Timeline

➡️ **[Open Security Event Timeline](analysis/security-event-timeline.md)**

---

# 🔬 Recommended Evidence Review Path

For someone reviewing this project for the first time:

### 01 — Start Here

Read this README to understand the investigation scope and methodology.

### 02 — Review the Findings

➡️ [Investigation Findings](analysis/investigation-findings.md)

Review the documented analytical conclusions.

### 03 — Review the Timeline

➡️ [Security Event Timeline](analysis/security-event-timeline.md)

Follow the chronological reconstruction.

### 04 — Validate the Evidence

➡️ [Open the 137 Evidence Screenshots](evidence/screenshots/)

Review the underlying screenshots supporting the investigation.

### 05 — Correlate

Compare the evidence with:

- Event IDs
- Timestamps
- Account information
- Logon ID
- Browser artifacts
- Execution artifacts
- Windows forensic artifacts
- ZimmermanTools evidence
- Integrity evidence

---

# 🧠 Key Investigation Observations

The investigation established the following major observations:

### Account Activity

The `DFIR-Test` account was created, enabled, modified, and associated with group-membership changes.

### Authentication

Explicit credential use and successful interactive logon were recorded at `13:36:18`.

### Session Correlation

The documented Logon ID was:

```text
0xA8119D
```

This identifier was used to correlate activity within the observed session.

### Credential Activity

Credential Manager activity was recorded shortly after authentication.

### Cryptographic Activity

Cryptographic and key-related events were recorded shortly after the successful logon.

### Discovery

Account and group enumeration activity was recorded later in the observed session.

### Session Termination

Event `4647` recorded a user-initiated logoff at `13:50:55`.

---

# 📊 Overall Investigation Assessment

The available Windows Security Event Log evidence supports reconstruction of a coherent sequence of:

```text
Account Management
        ↓
Authentication
        ↓
Credential / Cryptographic Activity
        ↓
Account & Group Discovery
        ↓
Session Termination
```

The supporting forensic artifacts provide additional context through:

```text
Browser
Downloads
Prefetch
LNK
Jump Lists
PowerShell
Process Analysis
ZimmermanTools
EVTX Metadata
SHA-256 Integrity
```

The investigation does **not** claim that every observed event represents malicious activity.

Instead, the assessment distinguishes between:

- What the evidence directly shows
- What can be correlated across artifacts
- What can reasonably be concluded from the available evidence

This approach supports a more defensible DFIR investigation.

---

# 🛡️ Evidence-First Investigation Principles

This project follows several core forensic principles:

### Evidence Before Interpretation

Artifacts are examined before conclusions are drawn.

### Correlation Over Isolation

Events are correlated using timestamps, account information, Logon IDs, and supporting artifacts.

### Document Negative Results

Searches that produce no relevant results are documented rather than silently omitted.

### Preserve Evidence Integrity

EVTX metadata and SHA-256 verification are documented as part of the investigation.

### Separate Observation From Assessment

The project distinguishes observed forensic evidence from analyst interpretation.

---

# 🧰 DFIR Skills Demonstrated

## Windows Forensics

- Windows Security Event Log analysis
- Windows Event ID investigation
- Account lifecycle reconstruction
- Authentication analysis
- Logon ID correlation
- Session reconstruction
- Process creation analysis
- PowerShell investigation

## Digital Forensics

- Browser artifact analysis
- Download artifact analysis
- Prefetch analysis
- LNK analysis
- Jump List analysis
- Windows artifact correlation
- EVTX analysis
- Timeline reconstruction

## Incident Response

- Account investigation
- Authentication investigation
- Discovery analysis
- Credential-related event analysis
- Activity reconstruction
- Cross-artifact correlation
- Evidence-based assessment

## Evidence Handling

- Evidence collection
- Artifact inventory
- Evidence documentation
- SHA-256 hashing
- Integrity verification
- Negative-result documentation
- Forensic reporting

## Tools

- Windows Event Viewer
- PowerShell
- ZimmermanTools
- GitHub

---

# 📚 What This Project Demonstrates

This project demonstrates the ability to move from raw Windows forensic evidence toward a structured investigative conclusion.

The workflow demonstrates:

```text
Raw Evidence
     ↓
Artifact Examination
     ↓
Event Analysis
     ↓
Correlation
     ↓
Timeline
     ↓
Assessment
     ↓
Documentation
```

The goal is not simply to identify individual Event IDs.

The goal is to understand how multiple pieces of evidence relate to one another and contribute to a defensible reconstruction of activity.

---

# 💡 Project Takeaways

This investigation reinforced several important DFIR concepts:

- Windows Security Events must be interpreted in context.
- Authentication events become more useful when correlated with Logon IDs.
- Account and group enumeration can provide important activity context.
- Browser and Windows artifacts can provide supporting timeline information.
- Process and PowerShell analysis should be correlated with other evidence.
- Negative search results can be valuable when properly documented.
- Evidence integrity should be verified and documented.
- A forensic conclusion should distinguish observation from interpretation.
- A strong DFIR report should allow another analyst to follow the evidence trail.

---

# 📈 Investigation Status

| Component | Status |
|---|---|
| Evidence collection | ✅ Complete |
| Security Event analysis | ✅ Complete |
| Account lifecycle analysis | ✅ Complete |
| Authentication analysis | ✅ Complete |
| Credential analysis | ✅ Complete |
| Discovery analysis | ✅ Complete |
| Process analysis | ✅ Complete |
| PowerShell investigation | ✅ Complete |
| Browser analysis | ✅ Complete |
| Prefetch analysis | ✅ Complete |
| LNK analysis | ✅ Complete |
| Jump List analysis | ✅ Complete |
| ZimmermanTools analysis | ✅ Complete |
| Timeline reconstruction | ✅ Complete |
| EVTX metadata analysis | ✅ Complete |
| SHA-256 integrity verification | ✅ Complete |
| Evidence screenshots | ✅ 137 / 137 |
| Investigation findings | ✅ Complete |
| Documentation | ✅ Complete |

---

# ⚠️ Disclaimer

This repository is intended for:

- Defensive cybersecurity education
- Digital forensics practice
- Incident response practice
- SOC/DFIR portfolio demonstration

The investigation was performed in a controlled environment.

The documented evidence represents the artifacts available within this investigation and should not be interpreted as evidence from a real production environment.

Individual events and artifacts should be interpreted within their investigative context.

---

# 👤 Author

## Anik Nohan

**Windows DFIR / SOC Analyst Portfolio**

### Focus Areas

`Windows DFIR` · `Digital Forensics` · `Incident Response` · `Security Event Analysis` · `Timeline Reconstruction` · `Evidence Correlation`

---

# ⭐ Project Navigation

| Section | Link |
|---|---|
| 📌 Project Overview | [Start Here](#-project-overview) |
| 🎯 Objectives | [Investigation Objectives](#-investigation-objectives) |
| 🔎 Scope | [Investigation Scope](#-investigation-scope) |
| 🛠️ Tools | [Tools & Technologies](#️-tools--technologies) |
| 🧭 Methodology | [Investigation Workflow](#-investigation-workflow) |
| 🔐 Account Analysis | [Account Lifecycle](#-account-lifecycle-analysis) |
| 🔑 Authentication | [Authentication Analysis](#-authentication-analysis) |
| 🔍 Discovery | [Account & Group Discovery](#-account--group-discovery) |
| 🕒 Timeline | [Reconstructed Timeline](#-reconstructed-security-event-timeline) |
| 🧩 Correlation | [Evidence Correlation](#-evidence-correlation) |
| 📸 Evidence | [137 Screenshots](#-evidence-collection) |
| 🧠 Findings | [Key Observations](#-key-investigation-observations) |
| 🛡️ Assessment | [Overall Assessment](#-overall-investigation-assessment) |
| 🧰 Skills | [DFIR Skills](#-dfir-skills-demonstrated) |
| 📊 Status | [Project Status](#-investigation-status) |

---

# End of Investigation

**Evidence → Analysis → Correlation → Timeline → Assessment**

**137 evidence screenshots preserved as the supporting investigation record.**
