# DFIR Evidence Notes

## Complete 137-Screenshot Evidence Index

This document provides an evidence-by-evidence guide to the 137 numbered screenshots in `evidence/screenshots/`.

**Important:** The descriptions below are grounded in the screenshot filenames and the investigation context provided in the repository screenshots. They explain the documented forensic purpose without claiming details that are not visible from the filename alone.

---

## Evidence 001 — Windows DFIR lab directory structure

**Screenshot:** [`01-windows-dfir-lab-directory-structure.png`](screenshots/01-windows-dfir-lab-directory-structure.png)

### What This Shows
Documents the organization of the DFIR investigation workspace and the locations used to store forensic evidence.

### Why It Matters
Establishes the investigation workspace and provides context for the artifact collection workflow.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 002 — Evidence artifact inventory

**Screenshot:** [`02-evidence-artifact-inventory.png`](screenshots/02-evidence-artifact-inventory.png)

### What This Shows
Documents the collected forensic artifacts available for analysis.

### Why It Matters
Establishes the evidence set used throughout the investigation.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 003 — Prefetch artifact inventory

**Screenshot:** [`03-prefetch-artifact-inventory.png`](screenshots/03-prefetch-artifact-inventory.png)

### What This Shows
Documents the available Windows Prefetch artifacts.

### Why It Matters
Supports later execution-timeline and program-execution analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 004 — LNK artifact inventory

**Screenshot:** [`04-lnk-artifact-inventory.png`](screenshots/04-lnk-artifact-inventory.png)

### What This Shows
Documents collected Windows shortcut (LNK) artifacts.

### Why It Matters
Supports shortcut and target-path analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 005 — Chrome artifact inventory

**Screenshot:** [`05-chrome-artifact-inventory.png`](screenshots/05-chrome-artifact-inventory.png)

### What This Shows
Documents the available Chrome browser artifacts.

### Why It Matters
Provides the browser-artifact evidence set for later correlation.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 006 — Chrome artifact metadata

**Screenshot:** [`06-chrome-artifact-metadata.png`](screenshots/06-chrome-artifact-metadata.png)

### What This Shows
Documents metadata associated with the Chrome artifacts.

### Why It Matters
Provides contextual information for browser timeline analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 007 — Authentication timeline

**Screenshot:** [`07-authentication-timeline.png`](screenshots/07-authentication-timeline.png)

### What This Shows
Documents the authentication-related timeline used in the investigation.

### Why It Matters
Provides temporal context for account and logon activity.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 008 — Prefetch execution timeline

**Screenshot:** [`08-prefetch-execution-timeline.png`](screenshots/08-prefetch-execution-timeline.png)

### What This Shows
Documents execution timing derived from Prefetch artifacts.

### Why It Matters
Supports correlation of program execution with Security Event activity.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 009 — LNK artifact timeline

**Screenshot:** [`09-lnk-artifact-timeline.png`](screenshots/09-lnk-artifact-timeline.png)

### What This Shows
Documents the timeline associated with LNK artifacts.

### Why It Matters
Supports correlation between shortcut activity and other forensic artifacts.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 010 — LNK target paths

**Screenshot:** [`10-lnk-target-paths.png`](screenshots/10-lnk-target-paths.png)

### What This Shows
Documents target paths identified from LNK artifacts.

### Why It Matters
Helps determine what files or programs the shortcuts referenced.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 011 — Jump List file references

**Screenshot:** [`11-jumplist-file-references.png`](screenshots/11-jumplist-file-references.png)

### What This Shows
Documents file references identified in Jump List artifacts.

### Why It Matters
Provides additional evidence of recently accessed files and application activity.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 012 — Chrome download URL correlation

**Screenshot:** [`12-chrome-download-url-correlation.png`](screenshots/12-chrome-download-url-correlation.png)

### What This Shows
Documents correlation between a Chrome download and its source URL.

### Why It Matters
Links browser download activity to the corresponding web resource.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 013 — Chrome download UTC timestamps

**Screenshot:** [`13-chrome-download-timestamps-utc.png`](screenshots/13-chrome-download-timestamps-utc.png)

### What This Shows
Documents UTC timestamps associated with Chrome download activity.

### Why It Matters
Supports accurate cross-artifact timeline correlation.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 014 — Chrome history and ZimmermanTools timeline

**Screenshot:** [`14-chrome-history-zimmermantoools-timeline.png`](screenshots/14-chrome-history-zimmermantoools-timeline.png)

### What This Shows
Documents browser history associated with ZimmermanTools activity.

### Why It Matters
Correlates web browsing with forensic-tool research or acquisition activity.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 015 — Chrome history script visit

**Screenshot:** [`15-chrome-history-zimmermantools-script-visit.png`](screenshots/15-chrome-history-zimmermantools-script-visit.png)

### What This Shows
Documents a browser visit associated with a ZimmermanTools script.

### Why It Matters
Provides browser-history evidence relevant to tool/script acquisition.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 016 — Filtered Chrome GitHub ZimmermanTools history

**Screenshot:** [`16-chrome-github-zimmermantools-filtered-history.png`](screenshots/16-chrome-github-zimmermantools-filtered-history.png)

### What This Shows
Documents filtered browser history for ZimmermanTools GitHub activity.

### Why It Matters
Supports attribution of browser activity to the identified repository/resource.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 017 — Security Event 4624 Microsoft account cached interactive logon

**Screenshot:** [`17-security-event-4624-microsoft-account-cached-interactive-logon.png`](screenshots/17-security-event-4624-microsoft-account-cached-interactive-logon.png)

### What This Shows
Documents an Event 4624 interactive-logon record involving a Microsoft account.

### Why It Matters
Provides authentication evidence and distinguishes the observed logon context.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 018 — DFIR-Test account creation — Event 4720

**Screenshot:** [`18-security-event-4720-dfir-test-account-created.png`](screenshots/18-security-event-4720-dfir-test-account-created.png)

### What This Shows
Documents creation of the DFIR-Test account.

### Why It Matters
Establishes the beginning of the account lifecycle.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 019 — DFIR-Test account enabled — Event 4722

**Screenshot:** [`19-security-event-4722-dfir-test-account-enabled.png`](screenshots/19-security-event-4722-dfir-test-account-enabled.png)

### What This Shows
Documents enabling of the DFIR-Test account.

### Why It Matters
Shows the account was enabled for use after creation.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 020 — DFIR-Test password reset attempt — Event 4724

**Screenshot:** [`20-security-event-4724-dfir-test-password-reset-attempt.png`](screenshots/20-security-event-4724-dfir-test-password-reset-attempt.png)

### What This Shows
Documents a password-reset attempt associated with DFIR-Test.

### Why It Matters
Adds account-configuration context to the investigation.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 021 — DFIR-Test logoff summary — Event 4647

**Screenshot:** [`21-dfir-test-event-4647-logoff-summary.png`](screenshots/21-dfir-test-event-4647-logoff-summary.png)

### What This Shows
Documents the DFIR-Test user-initiated logoff event.

### Why It Matters
Provides evidence of session termination.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 022 — SYSTEM special privileges — Event 4672

**Screenshot:** [`22-special-privileges-event-4672-system.png`](screenshots/22-special-privileges-event-4672-system.png)

### What This Shows
Documents an Event 4672 special-privileges assignment associated with SYSTEM.

### Why It Matters
Provides context for privileged security activity in the host environment.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 023 — DFIR-Test user logoff — Event 4647

**Screenshot:** [`23-dfir-test-event-4647-user-logoff.png`](screenshots/23-dfir-test-event-4647-user-logoff.png)

### What This Shows
Documents the DFIR-Test user logoff record.

### Why It Matters
Corroborates the end of the observed user session.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 024 — Microsoft account special privileges — Event 4672

**Screenshot:** [`24-special-privileges-microsoft-account-4672.png`](screenshots/24-special-privileges-microsoft-account-4672.png)

### What This Shows
Documents an Event 4672 special-privileges record for a Microsoft account.

### Why It Matters
Provides additional privileged-session context.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 025 — DFIR-Test account creation and Logon ID correlation

**Screenshot:** [`25-dfir-test-event-4720-account-creation-logon-id-correlation.png`](screenshots/25-dfir-test-event-4720-account-creation-logon-id-correlation.png)

### What This Shows
Documents correlation between account creation evidence and a Logon ID.

### Why It Matters
Supports linking account activity with later session activity.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 026 — DFIR-Test correlated session timeline

**Screenshot:** [`26-dfir-test-correlated-session-timeline.png`](screenshots/26-dfir-test-correlated-session-timeline.png)

### What This Shows
Documents a correlated timeline for the DFIR-Test session.

### Why It Matters
Provides a consolidated temporal view of related events.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 027 — DFIR-Test added to Users group — Event 4732

**Screenshot:** [`27-dfir-test-added-to-users-group-4732.png`](screenshots/27-dfir-test-added-to-users-group-4732.png)

### What This Shows
Documents DFIR-Test membership in the Users group.

### Why It Matters
Provides account/group configuration evidence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 028 — DFIR-Test session duration

**Screenshot:** [`28-dfir-test-session-duration.png`](screenshots/28-dfir-test-session-duration.png)

### What This Shows
Documents the calculated duration of the observed DFIR-Test session.

### Why It Matters
Supports the reconstructed session timeline.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 029 — DFIR-Test explicit credentials — Event 4648

**Screenshot:** [`29-dfir-test-event-4648-explicit-credentials.png`](screenshots/29-dfir-test-event-4648-explicit-credentials.png)

### What This Shows
Documents use of explicit credentials associated with DFIR-Test.

### Why It Matters
Provides authentication evidence for credential use.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 030 — No DFIR-Test Administrators membership

**Screenshot:** [`30-no-dfir-test-administrators-membership-4732.png`](screenshots/30-no-dfir-test-administrators-membership-4732.png)

### What This Shows
Documents the absence of DFIR-Test membership in the Administrators group in the referenced check.

### Why It Matters
Helps constrain the interpretation of the account's privilege level.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 031 — DFIR-Test Event 4648/4624 authentication correlation

**Screenshot:** [`31-dfir-test-4648-4624-authentication-correlation.png`](screenshots/31-dfir-test-4648-4624-authentication-correlation.png)

### What This Shows
Documents correlation between explicit credential use and successful logon.

### Why It Matters
Strengthens the authentication timeline by linking related event records.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 032 — No DFIR-Test special privileges — Event 4672

**Screenshot:** [`32-no-dfir-test-special-privileges-4672.png`](screenshots/32-no-dfir-test-special-privileges-4672.png)

### What This Shows
Documents the referenced negative check for special-privilege assignment to DFIR-Test.

### Why It Matters
Helps distinguish ordinary authentication from privileged-logon evidence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 033 — DFIR-Test blank-password query — Event 4797

**Screenshot:** [`33-dfir-test-event-4797-blank-password-query.png`](screenshots/33-dfir-test-event-4797-blank-password-query.png)

### What This Shows
Documents an Event 4797 local-account blank-password query.

### Why It Matters
Provides account-discovery evidence during the session.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 034 — No DFIR-Test process-creation events — Event 4688

**Screenshot:** [`34-no-process-creation-events-dfir-test-4688.png`](screenshots/34-no-process-creation-events-dfir-test-4688.png)

### What This Shows
Documents the referenced negative check for Event 4688 process creation associated with DFIR-Test.

### Why It Matters
Helps define the limits of process-creation evidence for the account.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 035 — DFIR-Test Administrators enumeration — Event 4799

**Screenshot:** [`35-dfir-test-event-4799-administrators-enumeration.png`](screenshots/35-dfir-test-event-4799-administrators-enumeration.png)

### What This Shows
Documents Administrators group membership enumeration.

### Why It Matters
Provides evidence of group-discovery activity.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 036 — No failed DFIR-Test logons — Event 4625

**Screenshot:** [`36-no-failed-logons-dfir-test-4625.png`](screenshots/36-no-failed-logons-dfir-test-4625.png)

### What This Shows
Documents the referenced negative check for failed logons.

### Why It Matters
Helps characterize the authentication sequence as observed.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 037 — DFIR-Test user group enumeration — Event 4798

**Screenshot:** [`37-dfir-test-event-4798-user-group-enumeration.png`](screenshots/37-dfir-test-event-4798-user-group-enumeration.png)

### What This Shows
Documents user local-group membership enumeration.

### Why It Matters
Provides evidence of local group-discovery activity.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 038 — DFIR-Test blank-password query — Event 4797

**Screenshot:** [`38-dfir-test-event-4797-blank-password-query.png`](screenshots/38-dfir-test-event-4797-blank-password-query.png)

### What This Shows
Documents an Event 4797 blank-password query associated with the investigation.

### Why It Matters
Provides additional account-discovery evidence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 039 — DFIR-Test account enumeration — Event 4797

**Screenshot:** [`39-dfir-test-event-4797-account-enumeration.png`](screenshots/39-dfir-test-event-4797-account-enumeration.png)

### What This Shows
Documents account-enumeration activity associated with Event 4797.

### Why It Matters
Supports analysis of local-account discovery behavior.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 040 — DFIR-Test account discovery timeline

**Screenshot:** [`40-dfir-test-account-discovery-timeline.png`](screenshots/40-dfir-test-account-discovery-timeline.png)

### What This Shows
Documents the temporal sequence of account-discovery events.

### Why It Matters
Correlates enumeration activity within the broader session.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 041 — DFIR-Test global group membership — Event 4728

**Screenshot:** [`41-dfir-test-global-group-membership-4728.png`](screenshots/41-dfir-test-global-group-membership-4728.png)

### What This Shows
Documents a security-enabled global group membership change.

### Why It Matters
Provides evidence of group-membership modification during account configuration.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 042 — DFIR-Test added to Users — Event 4732

**Screenshot:** [`42-dfir-test-added-to-users-4732.png`](screenshots/42-dfir-test-added-to-users-4732.png)

### What This Shows
Documents addition of DFIR-Test to the Users group.

### Why It Matters
Supports account configuration findings.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 043 — DFIR-Test Users group membership — Event 4732

**Screenshot:** [`43-dfir-test-added-to-users-group-4732.png`](screenshots/43-dfir-test-added-to-users-group-4732.png)

### What This Shows
Documents DFIR-Test Users-group membership.

### Why It Matters
Provides corroborating group-membership evidence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 044 — DFIR-Test account changed — Event 4738

**Screenshot:** [`44-dfir-test-account-changed-4738.png`](screenshots/44-dfir-test-account-changed-4738.png)

### What This Shows
Documents an account-change event for DFIR-Test.

### Why It Matters
Completes the account configuration evidence set.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 045 — Chrome download ChatGPT referrer

**Screenshot:** [`45-chrome-download-chatgpt-referrer.png`](screenshots/45-chrome-download-chatgpt-referrer.png)

### What This Shows
Documents a Chrome download with the recorded ChatGPT referrer context.

### Why It Matters
Supports browser-source correlation for the downloaded artifact.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 046 — Chrome download completion state

**Screenshot:** [`46-chrome-download-completion-state.png`](screenshots/46-chrome-download-completion-state.png)

### What This Shows
Documents the completion state of a Chrome download.

### Why It Matters
Helps establish whether the browser recorded the download as completed.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 047 — Chrome download and NTFS timestamp correlation

**Screenshot:** [`47-chrome-download-ntfs-timestamp-correlation.png`](screenshots/47-chrome-download-ntfs-timestamp-correlation.png)

### What This Shows
Documents correlation between browser download timing and NTFS timestamps.

### Why It Matters
Links browser activity with filesystem timing.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 048 — Chrome ZimmermanTools download-tab URL

**Screenshot:** [`48-chrome-download-tab-url-zimmermantools.png`](screenshots/48-chrome-download-tab-url-zimmermantools.png)

### What This Shows
Documents the browser tab URL associated with the ZimmermanTools download.

### Why It Matters
Connects the downloaded artifact to its browser source.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 049 — Chrome Get-ZimmermanTools download target path

**Screenshot:** [`49-chrome-download-target-path-get-zimmermantools.png`](screenshots/49-chrome-download-target-path-get-zimmermantools.png)

### What This Shows
Documents the target path for the Get-ZimmermanTools download.

### Why It Matters
Identifies where the downloaded artifact was stored.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 050 — Chrome GitHub ZimmermanTools script visit

**Screenshot:** [`50-chrome-github-zimmermantools-script-visit.png`](screenshots/50-chrome-github-zimmermantools-script-visit.png)

### What This Shows
Documents a browser visit to a ZimmermanTools GitHub script/resource.

### Why It Matters
Provides acquisition-context evidence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 051 — Chrome history Get-ZimmermanTools GitHub visit

**Screenshot:** [`51-chrome-history-get-zimmermantools-github-163745.png`](screenshots/51-chrome-history-get-zimmermantools-github-163745.png)

### What This Shows
Documents the recorded browser history entry for the ZimmermanTools GitHub resource.

### Why It Matters
Provides timestamped browsing evidence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 052 — Chrome history Get-ZimmermanTools PS1 visit

**Screenshot:** [`52-chrome-history-get-zimmermantools-ps1-163757.png`](screenshots/52-chrome-history-get-zimmermantools-ps1-163757.png)

### What This Shows
Documents the recorded browser history entry for the PowerShell script resource.

### Why It Matters
Supports correlation between browser research and PowerShell tooling.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 053 — Chrome history network last-visit time

**Screenshot:** [`53-chrome-history-network-last-visit-time.png`](screenshots/53-chrome-history-network-last-visit-time.png)

### What This Shows
Documents browser-history last-visit timing information.

### Why It Matters
Supports browser timeline reconstruction.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 054 — Chrome history network security report

**Screenshot:** [`54-chrome-history-network-security-report.png`](screenshots/54-chrome-history-network-security-report.png)

### What This Shows
Documents Chrome network/security-report history information.

### Why It Matters
Provides additional browser-artifact context.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 055 — Chrome ChatGPT-to-GitHub timeline

**Screenshot:** [`55-chrome-timeline-chatgpt-to-github.png`](screenshots/55-chrome-timeline-chatgpt-to-github.png)

### What This Shows
Documents browser timeline correlation between ChatGPT and GitHub activity.

### Why It Matters
Provides temporal context for web-based investigation/tool research.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 056 — Chrome ZimmermanTools download metadata

**Screenshot:** [`56-chrome-zimmermantools-download-metadata.png`](screenshots/56-chrome-zimmermantools-download-metadata.png)

### What This Shows
Documents metadata associated with the ZimmermanTools download.

### Why It Matters
Supports identification and timeline analysis of the downloaded artifact.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 057 — Chrome ZimmermanTools download timestamp

**Screenshot:** [`57-chrome-zimmermantools-download-time-163808.png`](screenshots/57-chrome-zimmermantools-download-time-163808.png)

### What This Shows
Documents the recorded download time for ZimmermanTools.

### Why It Matters
Provides a precise browser timestamp for cross-artifact correlation.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 058 — Credential Manager enumeration — Event 5379

**Screenshot:** [`58-credential-manager-5379-enumeration.png`](screenshots/58-credential-manager-5379-enumeration.png)

### What This Shows
Documents Credential Manager credential-access activity.

### Why It Matters
Provides evidence of credential-related activity after authentication.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 059 — DFIR-Test key file operation — Event 5058

**Screenshot:** [`59-dfir-test-5058-key-file-operation.png`](screenshots/59-dfir-test-5058-key-file-operation.png)

### What This Shows
Documents a key-file operation associated with the investigation.

### Why It Matters
Provides cryptographic/key-management context.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 060 — DFIR-Test key migration — Event 5059

**Screenshot:** [`60-dfir-test-5059-key-migration-operation.png`](screenshots/60-dfir-test-5059-key-migration-operation.png)

### What This Shows
Documents a key-migration operation.

### Why It Matters
Provides additional cryptographic activity context.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 061 — DFIR-Test cryptographic operation — Event 5061

**Screenshot:** [`61-dfir-test-5061-cryptographic-operation.png`](screenshots/61-dfir-test-5061-cryptographic-operation.png)

### What This Shows
Documents a cryptographic operation.

### Why It Matters
Adds cryptographic activity to the reconstructed session.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 062 — DFIR-Test account creation timeline

**Screenshot:** [`62-dfir-test-account-creation-timeline.png`](screenshots/62-dfir-test-account-creation-timeline.png)

### What This Shows
Documents the timeline surrounding DFIR-Test account creation.

### Why It Matters
Provides temporal context for account-management events.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 063 — DFIR-Test Credential Manager enumeration

**Screenshot:** [`63-dfir-test-credential-manager-enumeration.png`](screenshots/63-dfir-test-credential-manager-enumeration.png)

### What This Shows
Documents Credential Manager enumeration associated with DFIR-Test.

### Why It Matters
Supports credential-related session analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 064 — DFIR-Test logon session timeline

**Screenshot:** [`64-dfir-test-logon-session-timeline.png`](screenshots/64-dfir-test-logon-session-timeline.png)

### What This Shows
Documents the timeline of the DFIR-Test logon session.

### Why It Matters
Supports correlation of authentication and subsequent activity.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 065 — DFIR-Test successful logon — Event 4624

**Screenshot:** [`65-dfir-test-successful-logon-4624.png`](screenshots/65-dfir-test-successful-logon-4624.png)

### What This Shows
Documents the successful interactive logon for DFIR-Test.

### Why It Matters
Establishes the authenticated session.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 066 — Detailed Event 4624 DFIR-Test successful logon

**Screenshot:** [`66-event-4624-dfir-test-successful-logon.png`](screenshots/66-event-4624-dfir-test-successful-logon.png)

### What This Shows
Documents detailed fields from the successful logon event.

### Why It Matters
Provides event-level authentication details for correlation.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 067 — Prefetch and Security evidence hash manifest

**Screenshot:** [`67-evidence-hash-manifest-prefetch-security.png`](screenshots/67-evidence-hash-manifest-prefetch-security.png)

### What This Shows
Documents hashes recorded for Prefetch and Security evidence.

### Why It Matters
Supports evidence integrity and reproducibility.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 068 — SHA-256 evidence hash manifest

**Screenshot:** [`68-evidence-hash-manifest-sha256.png`](screenshots/68-evidence-hash-manifest-sha256.png)

### What This Shows
Documents SHA-256 hash verification for the evidence manifest.

### Why It Matters
Provides integrity-verification evidence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 069 — Filesystem ZimmermanTools timestamp correlation

**Screenshot:** [`69-filesystem-zimmerman-timestamp-correlation.png`](screenshots/69-filesystem-zimmerman-timestamp-correlation.png)

### What This Shows
Documents filesystem timestamp correlation involving ZimmermanTools artifacts.

### Why It Matters
Links filesystem timing with tool acquisition or execution activity.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 070 — Investigation report created

**Screenshot:** [`70-investigation-report-created.png`](screenshots/70-investigation-report-created.png)

### What This Shows
Documents creation of the investigation report artifact.

### Why It Matters
Establishes the final reporting stage of the workflow.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 071 — Investigation report SHA-256

**Screenshot:** [`71-investigation-report-sha256.png`](screenshots/71-investigation-report-sha256.png)

### What This Shows
Documents SHA-256 integrity verification for the investigation report.

### Why It Matters
Supports integrity of the final report.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 072 — Investigation timeline SHA-256

**Screenshot:** [`72-investigation-timeline-sha256.png`](screenshots/72-investigation-timeline-sha256.png)

### What This Shows
Documents SHA-256 integrity verification for the investigation timeline.

### Why It Matters
Supports integrity of the reconstructed timeline.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 073 — Security EVTX file metadata

**Screenshot:** [`73-security-evtx-file-metadata.png`](screenshots/73-security-evtx-file-metadata.png)

### What This Shows
Documents metadata for the Windows Security EVTX file.

### Why It Matters
Provides source-file context and supports evidence validation.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 074 — Linked Logon ID 0x630B8 event correlation

**Screenshot:** [`74-linked-logon-0x630B8-event-correlation.png`](screenshots/74-linked-logon-0x630B8-event-correlation.png)

### What This Shows
Documents correlation of events sharing the referenced Logon ID.

### Why It Matters
Supports session reconstruction through identifier correlation.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 075 — Logon ID 0x630F9 event correlation

**Screenshot:** [`75-logon-id-0x630F9-event-correlation.png`](screenshots/75-logon-id-0x630F9-event-correlation.png)

### What This Shows
Documents event correlation using the referenced Logon ID.

### Why It Matters
Provides additional session-correlation evidence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 076 — PowerShell Get-ZimmermanTools SHA-256

**Screenshot:** [`76-powershell-get-zimmermantools-sha256.png`](screenshots/76-powershell-get-zimmermantools-sha256.png)

### What This Shows
Documents SHA-256 evidence associated with the Get-ZimmermanTools PowerShell activity.

### Why It Matters
Supports integrity verification of the relevant script/artifact.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 077 — Get-ZimmermanTools Zone.Identifier

**Screenshot:** [`77-powershell-get-zimmermantools-zone-identifier.png`](screenshots/77-powershell-get-zimmermantools-zone-identifier.png)

### What This Shows
Documents the Zone.Identifier metadata associated with the downloaded tool/script.

### Why It Matters
Provides provenance information about the downloaded file.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 078 — PowerShell PSReadLine ZimmermanTools command history

**Screenshot:** [`78-powershell-psreadline-zimmerman-command-history.png`](screenshots/78-powershell-psreadline-zimmerman-command-history.png)

### What This Shows
Documents PSReadLine command-history evidence involving ZimmermanTools.

### Why It Matters
Provides command-line activity context.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 079 — PowerShell PSReadLine ZimmermanTools execution history

**Screenshot:** [`79-powershell-psreadline-zimmerman-execution-history.png`](screenshots/79-powershell-psreadline-zimmerman-execution-history.png)

### What This Shows
Documents PowerShell execution-history evidence involving ZimmermanTools.

### Why It Matters
Supports reconstruction of tool execution activity.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 080 — PowerShell ZimmermanTools empty directory

**Screenshot:** [`80-powershell-zimmermantools-empty-directory.png`](screenshots/80-powershell-zimmermantools-empty-directory.png)

### What This Shows
Documents an empty directory associated with ZimmermanTools.

### Why It Matters
Provides filesystem context and helps explain artifact availability.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 081 — PowerShell ZimmermanTools Event 4100 count

**Screenshot:** [`81-powershell-zimmermantools-event-4100-count.png`](screenshots/81-powershell-zimmermantools-event-4100-count.png)

### What This Shows
Documents the count or occurrence of PowerShell Event 4100 records.

### Why It Matters
Supports analysis of PowerShell engine/error-related activity.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 082 — PowerShell ZimmermanTools Event 4100

**Screenshot:** [`82-powershell-zimmermantools-event-4100.png`](screenshots/82-powershell-zimmermantools-event-4100.png)

### What This Shows
Documents a PowerShell Event 4100 record.

### Why It Matters
Provides event-level PowerShell evidence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 083 — ZimmermanTools filesystem timestamps

**Screenshot:** [`83-powershell-zimmermantools-filesystem-timestamps.png`](screenshots/83-powershell-zimmermantools-filesystem-timestamps.png)

### What This Shows
Documents filesystem timestamps associated with ZimmermanTools artifacts.

### Why It Matters
Supports temporal correlation of tool-related files.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 084 — First ZimmermanTools PowerShell Event 4100 error details

**Screenshot:** [`84-powershell-zimmermantools-first-4100-error-details.png`](screenshots/84-powershell-zimmermantools-first-4100-error-details.png)

### What This Shows
Documents detailed information from the first relevant Event 4100 record.

### Why It Matters
Provides context for PowerShell execution/error analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 085 — First ZimmermanTools PowerShell Event 4100

**Screenshot:** [`85-powershell-zimmermantools-first-event-4100.png`](screenshots/85-powershell-zimmermantools-first-event-4100.png)

### What This Shows
Documents the first relevant Event 4100 record.

### Why It Matters
Establishes the initial observed PowerShell event in this evidence set.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 086 — ZimmermanTools script attribution — Event 4100

**Screenshot:** [`86-powershell-zimmermantools-script-attribution-4100.png`](screenshots/86-powershell-zimmermantools-script-attribution-4100.png)

### What This Shows
Documents attribution information linking Event 4100 activity to the script/tool context.

### Why It Matters
Supports interpretation of PowerShell-related evidence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 087 — Reports directory created

**Screenshot:** [`87-reports-directory-created.png`](screenshots/87-reports-directory-created.png)

### What This Shows
Documents creation of the investigation reports directory.

### Why It Matters
Shows organization of generated forensic reporting artifacts.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 088 — Security EVTX Event ID summary

**Screenshot:** [`88-security-evtx-event-log-summary.png`](screenshots/88-security-evtx-event-log-summary.png)

### What This Shows
Documents a summary of Event IDs present in the Security EVTX evidence.

### Why It Matters
Provides an overview of the event population used for investigation.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 089 — Event 4624 logon-type summary

**Screenshot:** [`89-security-event-4624-logon-type-summary.png`](screenshots/89-security-event-4624-logon-type-summary.png)

### What This Shows
Documents a summary of Event 4624 logon types.

### Why It Matters
Supports authentication-pattern analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 090 — Event 4624 logon-type details

**Screenshot:** [`90-security-event-4624-logon-type-details.png`](screenshots/90-security-event-4624-logon-type-details.png)

### What This Shows
Documents detailed Event 4624 logon-type information.

### Why It Matters
Provides context for interpreting successful logons.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 091 — DFIR-Test successful logons — Event 4624

**Screenshot:** [`91-security-event-4624-dfir-test-logons.png`](screenshots/91-security-event-4624-dfir-test-logons.png)

### What This Shows
Documents Event 4624 logons associated with DFIR-Test.

### Why It Matters
Provides direct authentication evidence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 092 — DFIR-Test special privileges check — Event 4672

**Screenshot:** [`92-security-event-4672-dfir-test-special-privileges.png`](screenshots/92-security-event-4672-dfir-test-special-privileges.png)

### What This Shows
Documents the referenced Event 4672 privilege-assignment check.

### Why It Matters
Helps evaluate whether DFIR-Test received special privileges.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 093 — DFIR-Test explicit credentials — Event 4648

**Screenshot:** [`93-security-event-4648-dfir-test-explicit-credentials.png`](screenshots/93-security-event-4648-dfir-test-explicit-credentials.png)

### What This Shows
Documents explicit credential use by DFIR-Test.

### Why It Matters
Supports authentication correlation.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 094 — DFIR-Test Credential Manager — Event 5379

**Screenshot:** [`94-security-event-5379-dfir-test-credential-manager.png`](screenshots/94-security-event-5379-dfir-test-credential-manager.png)

### What This Shows
Documents Credential Manager activity associated with DFIR-Test.

### Why It Matters
Supports credential-access analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 095 — DFIR-Test key-file operation — Event 5058

**Screenshot:** [`95-security-event-5058-dfir-test-key-file-operation.png`](screenshots/95-security-event-5058-dfir-test-key-file-operation.png)

### What This Shows
Documents Event 5058 key-file activity.

### Why It Matters
Supports cryptographic/key-management analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 096 — DFIR-Test key migration — Event 5059

**Screenshot:** [`96-security-event-5059-dfir-test-key-migration-operation.png`](screenshots/96-security-event-5059-dfir-test-key-migration-operation.png)

### What This Shows
Documents Event 5059 key-migration activity.

### Why It Matters
Supports cryptographic/key-management analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 097 — DFIR-Test cryptographic operation — Event 5061

**Screenshot:** [`97-security-event-5061-dfir-test-cryptographic-operation.png`](screenshots/97-security-event-5061-dfir-test-cryptographic-operation.png)

### What This Shows
Documents Event 5061 cryptographic activity.

### Why It Matters
Supports cryptographic activity analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 098 — DFIR-Test group membership enumeration — Event 4799

**Screenshot:** [`98-security-event-4799-dfir-test-group-membership.png`](screenshots/98-security-event-4799-dfir-test-group-membership.png)

### What This Shows
Documents Event 4799 group-membership enumeration.

### Why It Matters
Supports account/group discovery analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 099 — DFIR-Test user-group enumeration — Event 4798

**Screenshot:** [`99-security-event-4798-dfir-test-user-group-enumeration.png`](screenshots/99-security-event-4798-dfir-test-user-group-enumeration.png)

### What This Shows
Documents Event 4798 local-group enumeration.

### Why It Matters
Supports account/group discovery analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 100 — DFIR-Test blank-password query — Event 4797

**Screenshot:** [`100-security-event-4797-dfir-test-blank-password-query.png`](screenshots/100-security-event-4797-dfir-test-blank-password-query.png)

### What This Shows
Documents Event 4797 local-account blank-password queries.

### Why It Matters
Supports local-account discovery analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 101 — DFIR-Test user logoff — Event 4647

**Screenshot:** [`101-security-event-4647-dfir-test-user-logoff.png`](screenshots/101-security-event-4647-dfir-test-user-logoff.png)

### What This Shows
Documents the DFIR-Test initiated logoff.

### Why It Matters
Marks session termination.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 102 — DFIR-Test Security session timeline

**Screenshot:** [`102-security-event-dfir-test-session-timeline.png`](screenshots/102-security-event-dfir-test-session-timeline.png)

### What This Shows
Documents a consolidated Security Event session timeline.

### Why It Matters
Supports correlation across the account's observed events.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 103 — DFIR-Test account activity summary

**Screenshot:** [`103-security-event-dfir-test-account-activity-summary.png`](screenshots/103-security-event-dfir-test-account-activity-summary.png)

### What This Shows
Documents a summary of DFIR-Test account activity.

### Why It Matters
Provides a high-level view of account-related events.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 104 — DFIR-Test account lifecycle timeline

**Screenshot:** [`104-security-event-dfir-test-account-lifecycle-timeline.png`](screenshots/104-security-event-dfir-test-account-lifecycle-timeline.png)

### What This Shows
Documents the account lifecycle from creation through later activity.

### Why It Matters
Supports reconstruction of account state changes.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 105 — DFIR-Test account discovery summary

**Screenshot:** [`105-security-event-dfir-test-account-discovery-summary.png`](screenshots/105-security-event-dfir-test-account-discovery-summary.png)

### What This Shows
Documents summarized account-discovery activity.

### Why It Matters
Supports interpretation of enumeration behavior.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 106 — DFIR-Test authentication summary

**Screenshot:** [`106-security-event-dfir-test-authentication-summary.png`](screenshots/106-security-event-dfir-test-authentication-summary.png)

### What This Shows
Documents summarized authentication activity.

### Why It Matters
Provides a consolidated view of the authentication phase.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 107 — DFIR-Test failed logon — Event 4625

**Screenshot:** [`107-dfir-test-failed-logon-event-4625.png`](screenshots/107-dfir-test-failed-logon-event-4625.png)

### What This Shows
Documents an Event 4625 failed-logon record or related check.

### Why It Matters
Provides authentication evidence for evaluating failed-logon activity.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 108 — DFIR-Test bad-password failed logon — Event 4625

**Screenshot:** [`108-dfir-test-failed-logon-bad-password-event-4625.png`](screenshots/108-dfir-test-failed-logon-bad-password-event-4625.png)

### What This Shows
Documents a failed logon associated with an incorrect password.

### Why It Matters
Provides specific failed-authentication context.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 109 — DFIR-Test correlated Security Event timeline

**Screenshot:** [`109-dfir-test-correlated-security-event-timeline.png`](screenshots/109-dfir-test-correlated-security-event-timeline.png)

### What This Shows
Documents a correlated Security Event timeline for DFIR-Test.

### Why It Matters
Supports the final temporal reconstruction.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 110 — DFIR-Test account created — Event 4720

**Screenshot:** [`110-dfir-test-account-created-event-4720.png`](screenshots/110-dfir-test-account-created-event-4720.png)

### What This Shows
Documents the account creation event.

### Why It Matters
Establishes the account lifecycle start.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 111 — DFIR-Test account enabled — Event 4722

**Screenshot:** [`111-dfir-test-account-enabled-event-4722.png`](screenshots/111-dfir-test-account-enabled-event-4722.png)

### What This Shows
Documents the account-enabled event.

### Why It Matters
Establishes that the created account became enabled.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 112 — DFIR-Test password reset — Event 4724

**Screenshot:** [`112-dfir-test-password-reset-event-4724.png`](screenshots/112-dfir-test-password-reset-event-4724.png)

### What This Shows
Documents the password-reset event.

### Why It Matters
Provides account-configuration evidence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 113 — DFIR-Test global group membership — Event 4728

**Screenshot:** [`113-dfir-test-global-group-membership-event-4728.png`](screenshots/113-dfir-test-global-group-membership-event-4728.png)

### What This Shows
Documents a global group membership change involving DFIR-Test.

### Why It Matters
Supports group-membership reconstruction.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 114 — DFIR-Test Users group membership — Event 4732

**Screenshot:** [`114-dfir-test-users-group-membership-event-4732.png`](screenshots/114-dfir-test-users-group-membership-event-4732.png)

### What This Shows
Documents addition to the Users group.

### Why It Matters
Supports account privilege/group analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 115 — DFIR-Test account changed — Event 4738

**Screenshot:** [`115-dfir-test-account-changed-event-4738.png`](screenshots/115-dfir-test-account-changed-event-4738.png)

### What This Shows
Documents the account-change event.

### Why It Matters
Completes the account-management sequence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 116 — Linked logon session event correlation

**Screenshot:** [`116-linked-logon-session-event-correlation.png`](screenshots/116-linked-logon-session-event-correlation.png)

### What This Shows
Documents correlation of events belonging to a linked logon session.

### Why It Matters
Supports session reconstruction using event relationships.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 117 — Linked successful logon — Event 4624

**Screenshot:** [`117-linked-logon-successful-logon-event-4624.png`](screenshots/117-linked-logon-successful-logon-event-4624.png)

### What This Shows
Documents a successful logon associated with the linked session.

### Why It Matters
Supports authentication correlation.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 118 — Security Event 4624 no interactive logons

**Screenshot:** [`118-security-event-4624-no-interactive-logons.png`](screenshots/118-security-event-4624-no-interactive-logons.png)

### What This Shows
Documents the referenced negative check for interactive Event 4624 logons.

### Why It Matters
Helps distinguish observed logon types and scope the evidence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 119 — Successful service logon — Event 4624

**Screenshot:** [`119-security-event-4624-successful-service-logon.png`](screenshots/119-security-event-4624-successful-service-logon.png)

### What This Shows
Documents a successful service logon.

### Why It Matters
Provides context for service-account/logon-type activity.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 120 — SYSTEM special privileges — Event 4672

**Screenshot:** [`120-security-event-4672-system-special-privileges.png`](screenshots/120-security-event-4672-system-special-privileges.png)

### What This Shows
Documents SYSTEM special-privilege assignment.

### Why It Matters
Provides privileged-system context.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 121 — Local group enumeration — Event 4798

**Screenshot:** [`121-security-event-4798-local-group-enumeration.png`](screenshots/121-security-event-4798-local-group-enumeration.png)

### What This Shows
Documents local-group membership enumeration.

### Why It Matters
Supports discovery-behavior analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 122 — Group membership enumeration — Event 4799

**Screenshot:** [`122-security-event-4799-group-membership-enumeration.png`](screenshots/122-security-event-4799-group-membership-enumeration.png)

### What This Shows
Documents group-membership enumeration.

### Why It Matters
Supports discovery-behavior analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 123 — Security Event correlation timeline

**Screenshot:** [`123-security-event-correlation-timeline.png`](screenshots/123-security-event-correlation-timeline.png)

### What This Shows
Documents the correlated Security Event timeline.

### Why It Matters
Provides an integrated temporal view of relevant events.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 124 — Security Event timeline — 1233

**Screenshot:** [`124-security-event-timeline-1233.png`](screenshots/124-security-event-timeline-1233.png)

### What This Shows
Documents the referenced Security Event timeline view.

### Why It Matters
Supports temporal analysis of the event records shown.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 125 — DFIR-Test Security Event timeline

**Screenshot:** [`125-security-event-timeline-dfir-test.png`](screenshots/125-security-event-timeline-dfir-test.png)

### What This Shows
Documents the reconstructed Security Event timeline for DFIR-Test.

### Why It Matters
Provides direct evidence for the investigation timeline.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 126 — Security EVTX Event 4688 PowerShell — no results

**Screenshot:** [`126-security-evtx-4688-powershell-no-results.png`](screenshots/126-security-evtx-4688-powershell-no-results.png)

### What This Shows
Documents the referenced Event 4688 PowerShell search with no matching results.

### Why It Matters
Helps establish the absence/limitation of Event 4688 process-creation evidence for the queried context.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 127 — Security EVTX Event 4688 process summary

**Screenshot:** [`127-security-evtx-4688-process-summary.png`](screenshots/127-security-evtx-4688-process-summary.png)

### What This Shows
Documents an Event 4688 process summary.

### Why It Matters
Provides process-creation analysis context.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 128 — Security EVTX Event 4688 process creation

**Screenshot:** [`128-security-evtx-event-4688-process-creation.png`](screenshots/128-security-evtx-event-4688-process-creation.png)

### What This Shows
Documents Event 4688 process-creation evidence.

### Why It Matters
Supports process execution analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 129 — Security EVTX Event ID frequency

**Screenshot:** [`129-security-evtx-event-id-frequency.png`](screenshots/129-security-evtx-event-id-frequency.png)

### What This Shows
Documents frequency information for Security Event IDs.

### Why It Matters
Provides an overview of event prevalence in the evidence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 130 — Security EVTX evidence metadata

**Screenshot:** [`130-security-evtx-evidence-metadata.png`](screenshots/130-security-evtx-evidence-metadata.png)

### What This Shows
Documents metadata associated with the Security EVTX evidence.

### Why It Matters
Supports source validation and evidence characterization.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 131 — Security EVTX integrity verification

**Screenshot:** [`131-security-evtx-integrity-verification.png`](screenshots/131-security-evtx-integrity-verification.png)

### What This Shows
Documents integrity verification of the Security EVTX evidence.

### Why It Matters
Supports confidence that the analyzed source remained unchanged.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 132 — Security EVTX SHA-256 hash

**Screenshot:** [`132-security-evtx-sha256-hash.png`](screenshots/132-security-evtx-sha256-hash.png)

### What This Shows
Documents the SHA-256 hash associated with the Security EVTX evidence.

### Why It Matters
Provides a reproducible integrity value for the source evidence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 133 — Security EVTX SHA-256 integrity verification

**Screenshot:** [`133-security-evtx-sha256-integrity.png`](screenshots/133-security-evtx-sha256-integrity.png)

### What This Shows
Documents SHA-256 integrity verification for the Security EVTX evidence.

### Why It Matters
Provides corroborating evidence of source integrity.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 134 — Windows DFIR lab directory tree — part 1

**Screenshot:** [`134-windows-dfir-lab-directory-tree-part-1.png`](screenshots/134-windows-dfir-lab-directory-tree-part-1.png)

### What This Shows
Documents the first portion of the final DFIR lab directory tree.

### Why It Matters
Provides repository/workspace structure context.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 135 — Windows DFIR lab directory tree — part 2

**Screenshot:** [`135-windows-dfir-lab-directory-tree-part-2.png`](screenshots/135-windows-dfir-lab-directory-tree-part-2.png)

### What This Shows
Documents the second portion of the final DFIR lab directory tree.

### Why It Matters
Completes the workspace structure evidence.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 136 — ZimmermanTools correlated execution timeline

**Screenshot:** [`136-zimmerman-tools-correlated-execution-timeline.png`](screenshots/136-zimmerman-tools-correlated-execution-timeline.png)

### What This Shows
Documents a correlated execution timeline generated from ZimmermanTools-related evidence.

### Why It Matters
Supports cross-artifact execution and timeline analysis.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---

## Evidence 137 — ZimmermanTools empty directory evidence

**Screenshot:** [`137-zimmerman-tools-empty-directory-evidence.png`](screenshots/137-zimmerman-tools-empty-directory-evidence.png)

### What This Shows
Documents an empty directory associated with ZimmermanTools analysis.

### Why It Matters
Provides filesystem context and helps document the state of the artifact workspace.

### Evidence Role
This screenshot belongs to the numbered evidence chain and should be interpreted together with related Security Event, browser, filesystem, PowerShell, Prefetch, LNK, Jump List, ZimmermanTools, timeline, and integrity artifacts where applicable.

---
