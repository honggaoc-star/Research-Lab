# Fleming and Penicillin — Independent RC2 Boundary Re-Audit Record

## Status

**Completed bounded re-audit for FLEM-01-B-AUDIT, Version 1.1 — RC2 edition, 20 July 2026**

**Record status: LOCKED ON SUBMISSION**

This review addresses only `AUD-C01`, `AUD-M01`, RC2 scope integrity, and changed repository-relative links. It does not perform Pass B coding, adjudicate classifications, or determine what the historical evidence ultimately proves.

## RC2 Finding Re-Audit

| Prior finding | Corrected? | Verification evidence | New issue introduced? | Reviewer conclusion |
|---|---|---|---|---|
| `AUD-C01` | **Yes** | Files 07, 08, and 11 reproduce identical 01A–01D wording: (01A) scientific characterization of the antibacterial substance; (01B) use of selective inhibition as a bacteriological isolation tool; (01C) local therapeutic or antiseptic application against susceptible microbes; and (01D) development as a stable, purified, systemically administered, scalable medicine. File 11 also preserves the candidate-separation rule. Its provenance identifies FLEM-01-A Version 1.0, the `Candidate Opportunities` section, branch `main`, and source blob SHA `1ac4dadedf38bbe31f3c57970068549f90689c77`. Direct inspection of that blob confirms the wording and separation rule exactly. File 11 contains no coder entries, stage codes, adjudication reasoning, outcome evidence, or proposed Pass B classifications. | **No** | The outcome-free manifest provides the authoritative comparison required by the release gate without exposing excluded materials. `AUD-C01` is resolved. |
| `AUD-M01` | **Yes** | F-B3 printed pp. 41–42 state that penicillin quality improved, clinical usage increased, and civilian distribution “was made possible” on 1 May 1944. F-B3-03 in file 08 now reproduces that enablement wording. Its relevance field says “enabled civilian access,” and its limitation expressly states that the passage does not establish that actual civilian distribution began on that date. No other RC2 wording reviewed converts enablement into documented commencement, receipt, prescribing, or use. | **No** | F-B3-03 is faithful to the source and preserves the material limitation. `AUD-M01` is resolved. |

## RC2 Integrity Check

| RC2 integrity check | Pass / fail / indeterminate | Evidence or problem |
|---|---|---|
| Changes are confined to the two finding dispositions and related version, link, status, and audit-gate updates | **Pass** | Repository commit diffs show the substantive evidence edit is confined to F-B3-03. Other changes add the outcome-free manifest, reproduce the unchanged candidate wording in file 08, and update RC2 status, disposition, version, link, and re-audit language. |
| No candidate, threshold, horizon, source boundary, evidence ID, or undisputed evidence claim changed | **Pass** | The four candidate definitions are unchanged. The 31 December 1945 horizon, realization thresholds, attribution boundary, core-source bundle, evidence IDs, and undisputed claim rows remain unchanged. F-B3-03 retains its evidence ID and locator while correcting only the overstated distribution paraphrase and related limitation. |
| New and changed repository-relative links resolve | **Pass** | Verified the affected links among files 07, 08, 09, 10, 11, and 12, together with file 11’s link to file 03. Each target resolves on `main`. |
| No material scope drift introduced by RC2 | **Pass** | RC2 implements the exact corrections required by `AUD-C01` and `AUD-M01`. No newly discovered critical, major, minor, or observational issue was found within the bounded re-audit scope. |

## Decision

| Decision field | Reviewer entry |
|---|---|
| Decision | **Approve for freeze as Version 1.0** |
| Critical findings | 0 unresolved |
| Major findings | 0 unresolved |
| Minor findings | 0 |
| Observations | 0 |
| Conditions before freeze | Preserve this completed record verbatim as the locked RC2 re-audit record; apply only the administrative version/status changes required to freeze RC2 as Version 1.0. |
| Recommended packet version after disposition | **Version 1.0 — frozen** |

## Independence and Submission Record

| Field | Reviewer entry |
|---|---|
| Reviewer identifier | New independent RC2 boundary reviewer — AI-assisted review instance |
| Date completed | 20 July 2026 |
| Role or relationship to project | Independent reviewer for this bounded RC2 re-audit only |
| Prior involvement in FLEM-01 packet construction or coding | None in this review instance; did not construct or revise the packet and did not perform Pass A or Pass B coding or adjudication |
| Prior familiarity with penicillin history | General background familiarity disclosed; it was not used as audit evidence |
| Materials reviewed | Files 07, 08, 09, 10, 11, and the administrative RC1 disposition in file 12; the exact file-03 source blob identified by file 11; relevant RC2 repository commit diffs; and F-B3 printed pp. 41–42 through the official govinfo transcription of the supplied report |
| External materials consulted | None beyond repository administration/history needed for scope verification and the official alternate-format transcription of the supplied F-B3 report |
| Excluded materials consulted | None. No coder records, Pass A adjudication, empirical case narrative, biographies, Nobel materials, later histories, or proposed Pass B classifications were consulted. |
| Potential conflicts or limitations | Direct PDF extraction was unavailable in the review interface; F-B3 wording and printed-page placement were verified through the official govinfo HTML transcription of the same supplied government report. |
| Independence declaration | I completed this bounded RC2 re-audit without participating in construction or coding of the materials under review and without access to proposed Pass B classifications. |

## Lock Statement

This completed RC2 re-audit is **locked on submission** and must be preserved verbatim. Any later correction or qualification belongs in a separate disposition record.
