# Fleming and Penicillin — RC1 Boundary-Audit Findings Disposition

## Status

**Disposition Version 1.0 — RC2 issued 20 July 2026**

This record responds to the immutable [locked RC1 boundary audit](10-Fleming-Penicillin-Pass-B-Independent-Boundary-Audit-Locked.md). It does not edit, reinterpret, or overwrite the reviewer's findings.

The reviewer returned RC1 for revision with:

- one critical finding, `AUD-C01`;
- one major finding, `AUD-M01`;
- no minor findings;
- and no observations.

## Disposition Summary

| Finding | Required correction | Disposition | RC2 material | Status |
|---|---|---|---|---|
| AUD-C01 | Supply an outcome-free authoritative Pass A candidate-boundary reference and obtain independent comparison | Created a narrow manifest containing only exact 01A–01D wording, the separation rule, frozen packet provenance, and source blob SHA | [11 — Frozen Pass A Candidate-Boundary Manifest](11-Fleming-Penicillin-Frozen-Pass-A-Candidate-Boundary-Manifest.md); linked from files 07 and 09 | Implemented; independent re-audit pending |
| AUD-M01 | Replace the claim that civilian distribution began on 1 May 1944 with the source's “was made possible” wording and inspect related access language | Revised F-B3-03 to state enablement, changed relevance to “enabled civilian access,” and added an explicit limitation that actual distribution beginning on that date is not established | [08 — RC2 Evidence Inventory](08-Fleming-Penicillin-Pass-B-Claim-Level-Evidence-Inventory.md) | Implemented; independent re-audit pending |

## AUD-C01 — Candidate-Boundary Verification

### Reviewer finding

The RC1 audit required exact comparison to the frozen Pass A candidate wording but did not permit a source containing that authoritative boundary. Cross-file consistency between files 07 and 08 could not establish fidelity to Pass A.

### Corrective action

File 11 now supplies:

- the exact four candidate definitions;
- the instruction not to assume recognition of one candidate entails another;
- the frozen source packet identifier and version;
- a link to the non-coded source instrument;
- and the source blob SHA `1ac4dadedf38bbe31f3c57970068549f90689c77`.

It contains no coder entries, stage codes, agreement statistics, adjudication reasoning, outcome evidence, or Pass B classifications.

### Scope control

No candidate wording, threshold, horizon, or code was changed. File 07 now points to the manifest as provenance for the wording already present. File 09 permits the manifest as the sole Pass A boundary reference for re-audit.

### Required verification

A new independent reviewer must compare 01A–01D in files 07 and 08 against file 11 and confirm that file 11 is sufficiently narrow and outcome-free.

## AUD-M01 — Civilian-Distribution Paraphrase

### Reviewer finding

F-B3-03 converted the War Production Board statement that civilian distribution “was made possible” on 1 May 1944 into the stronger claim that distribution “began” on that date.

### Corrective action

F-B3-03 now states:

> The report states that quality improved, clinical use increased, and civilian distribution was made possible on 1 May 1944.

The relevance field now says **enabled civilian access**, not **access transition**. The limitation field now states that “made possible” does not establish that actual civilian distribution began on that date.

### Scope control

No other evidence ID or claim was changed. The corrected wording does not assert actual civilian distribution, receipt, prescribing, or use on 1 May 1944.

### Required verification

A new independent reviewer must compare the revised F-B3-03 row to printed pp. 41–42 of F-B3 and confirm that enablement is not restated as realized distribution elsewhere in the RC2 materials.

## Version and Audit Consequences

| File | RC1 status | RC2 action |
|---|---|---|
| 07 — Pass B coder packet | Version 1.0-RC1 | Advanced to Version 1.0-RC2; links finding record, boundary manifest, and re-audit gate |
| 08 — Evidence inventory | Version 1.0-RC1 | Advanced to Version 1.0-RC2; corrects F-B3-03 and records both finding dispositions |
| 09 — Audit instrument | Version 1.0 | Advanced to Version 1.1; adds file 11 and a bounded RC2 re-audit form |
| 10 — Locked RC1 audit | Locked | Preserved verbatim; no edit permitted |
| 11 — Candidate-boundary manifest | Not present | Added as Version 1.0 |

## Freeze Decision

**RC2 is not frozen and must not be released for Pass B coding.**

Freeze as Version 1.0 is authorized only if a new independent reviewer:

1. verifies `AUD-C01` and `AUD-M01` as corrected;
2. confirms that no new critical or major issue was introduced;
3. confirms that changes remained within the documented disposition scope;
4. and submits a locked approval record.

Any failure or newly discovered material problem returns the packet for RC3.

