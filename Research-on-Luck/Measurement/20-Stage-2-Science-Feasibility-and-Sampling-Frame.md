# Stage 2 Science Feasibility and Sampling Frame

## Status

**Step 6 design record, Version 0.2 — STOP original Stage 2 Science scaling; separate redesign only by explicit decision**

This record implements the condition established by the [pilot decision gate](19-Pilot-Decision-Gate-and-Stage-2-Direction.md). It evaluates whether the Science domain presently supports an outcome-independent episode population suitable for a larger study of recognition without realization.

The initial design decision was divided:

- **Yes:** Science was the best domain in which to test whether a sampling frame could be constructed.
- **No:** the current repository case corpus was not itself a sampling frame and could not be converted into one retrospectively.
- **Initial decision:** permit only bounded Stage 2A candidate-frame reconnaissance.

That reconnaissance is now complete. None of the three bounded candidates supplies an outcome-independent denominator containing both recognized and unrecognized scientific opportunities. The current decision is therefore to **stop the original Stage 2 Science scaling attempt**.

## Decision Question

> Can the project define, enumerate, and document a Science opportunity-episode population without selecting episodes because their outcomes, fame, or fit with the framework are already known?

A usable frame must support:

1. episode identification before outcome classification;
2. consistent focal systems and levels;
3. recoverable pre-outcome information;
4. comparable opportunity, decision, and outcome windows;
5. both positive and negative trajectories;
6. independent measurement of authority, resources, and capability;
7. transparent missingness and archival selection;
8. and a feasible reliability design.

## Relationship to the Existing Science Corpus

The [Science domain](../Empirical%20Studies/Science/README.md) contains purposefully selected historical cases and a thematic treatment of [unrealized scientific opportunities](../Empirical%20Studies/Science/13-Unrealized-Scientific-Opportunities.md). The broader [Empirical Studies architecture](../Empirical%20Studies/README.md) explicitly describes the corpus as mechanism-oriented rather than representative.

That corpus remains valuable for:

- construct development;
- episode-boundary diagnostics;
- identifying competing explanations;
- locating failure modes;
- calibration of evidence rules;
- and generating frame requirements.

It is not suitable for:

- estimating prevalence;
- estimating a recognition effect;
- comparing outcome frequencies;
- constructing a denominator;
- or claiming representativeness.

FLEM-01 and CF-01 should therefore remain benchmark and calibration episodes. The other existing Science narratives may be used to test proposed boundaries, but they must not be treated as sampled observations unless they independently enter a prospectively defined frame.

## Feasibility Findings

### 1. Conceptual feasibility — passed provisionally

The opportunity episode remains a workable unit:

> a bounded relationship between a specified scientific actor or collective and a candidate empirical, theoretical, or developmental possibility during a stated interval.

FLEM-01 and CF-01 show that potential, access, recognition, pursuit, realization, and foreclosure can be separated provisionally. Science also supplies domain-specific evidence channels—laboratory records, proposals, correspondence, conference records, preprints, publications, replications, funding decisions, and institutional documents—that may locate those stages.

### 2. Population feasibility — not yet passed

The repository does not presently contain an enumerated population from which opportunity episodes can be selected without reference to outcome. The existing cases were chosen for explanatory and comparative value.

“Scientific opportunities” in general is not an enumerable population. A Stage 2 frame must be anchored to an observable entry process such as a defined submission, proposal, experiment, claim, program, or institutional decision stream.

### 3. Evidence feasibility — plausible but unverified

Science offers unusually strong documentary possibilities, but availability is likely uneven:

- successful work is more likely to be published, preserved, cited, and digitized;
- rejected or abandoned work may remain private or disappear;
- laboratory and institutional archives vary in access and completeness;
- retrospective accounts are selected by later importance;
- and pre-outcome evidence may be inseparable from later editorial or archival curation.

Evidence feasibility must therefore be tested on an enumerated mini-frame containing outcomes not selected in advance.

### 4. Comparison feasibility — plausible if the frame is narrow

Comparability is unlikely across all scientific fields, institutions, and historical periods. Instruments, publication norms, funding structures, decision authority, and realization horizons differ too much.

A usable initial frame should hold several of these dimensions constant:

- scientific field or problem class;
- institution or decision venue;
- entry channel;
- calendar period;
- focal-system level;
- documentary regime;
- and outcome horizon.

### 5. Tier 3 review feasibility — passed at the design level

The Version 0.2 architecture can scale through:

- coordinator preflight;
- a double-coded reliability subsample;
- exception review;
- disagreement-only adjudication;
- aggregate missingness and validity checks;
- and independent audit only when a material trigger applies.

The required sample size cannot be fixed until the frame size, category distribution, and evidence burden are known.

## Candidate Frame Families

These are frame families for reconnaissance, not approved populations.

| Frame family | Entry rule | Main advantage | Main risk | Current disposition |
|---|---|---|---|---|
| Defined proposal or grant cohort | All eligible submissions to one program in a fixed period | Clear denominator and decision record | Access restrictions; proposal is already a form of recognition | Investigate |
| Defined claim or publication cohort | All items entering a specified journal, conference, registry, or claim stream | Enumerability and dated records | Excludes unarticulated and unpublished opportunities | Investigate |
| Defined laboratory or institutional project cohort | All qualifying projects opened in one documented unit and period | Rich process and authority evidence | Local idiosyncrasy and archival incompleteness | Investigate |
| Defined replication or validation cohort | All claims entering a bounded replication process | Clear pursuit and credibility transitions | Narrow construct; recognition may precede frame entry | Investigate |
| Existing famous-case corpus | Repository cases selected for mechanism value | Familiar and already developed | Outcome, fame, survival, and framework-fit selection | Reject as Stage 2 frame |
| Open-ended history of “missed discoveries” | Retrospectively identified unrealized opportunities | Negative-case visibility | No defensible denominator; severe hindsight selection | Reject as Stage 2 frame |

No frame family should be chosen because it promises favorable findings. Selection should be based on enumerability, evidence symmetry, construct relevance, and manageable heterogeneity.

## Preferred Initial Direction

The preferred direction is a **bounded documentary cohort** anchored to one observable entry channel, one scientific field or problem class, and one limited period.

The entry channel should generate a list that exists independently of later success. Examples include all eligible proposals, submissions, registered studies, formally opened projects, or claims entering a defined validation process.

This preference does not select a specific archive, institution, journal, registry, or dataset. Stage 2A must compare concrete candidates before one is frozen.

## Minimum Frame Specification

A proposed frame must record:

| Field | Required specification |
|---|---|
| Frame identifier | Stable name and version |
| Source-generated list | The record that enumerates eligible entries |
| Scientific domain | Field, problem class, or institutional scope |
| Entry channel | How an episode enters the population |
| Calendar window | Fixed opening and closing dates |
| Focal system | Individual, team, laboratory, institution, or community |
| Candidate unit | Claim, proposal, experiment, project, or decision episode |
| Inclusion rule | Rule applicable without outcome knowledge |
| Exclusion rule | Narrow, auditable, and reason-coded |
| Deduplication rule | Treatment of resubmissions, linked claims, or nested projects |
| Pre-outcome cutoff | Evidence boundary for Pass A |
| Decision point | Event separating recognition from later pursuit |
| Outcome horizon | Common or rule-governed follow-up period |
| Realization criterion | Defined before outcome coding |
| Evidence inventory | Expected sources for every included entry |
| Missingness fields | Absence, restricted access, loss, and ambiguity |
| Competing variables | Authority, resources, capability, institutional position, and documentation |
| Selection risks | Known coverage and survival mechanisms |
| Frame owner | Person responsible for freeze and change control |

## Inclusion Rules

An entry should be eligible only if:

1. it appears on the source-generated list within the fixed window;
2. a focal system and candidate possibility can be stated without using later success;
3. the entry channel and initial date are recoverable;
4. the episode can receive a pre-outcome cutoff;
5. at least the potential, access, and recognition questions are meaningful;
6. pursuit and realization can be evaluated under stated rules, including indeterminate status;
7. and inclusion does not depend on fame, citation impact, validation, failure, or later historical importance.

Entries should remain eligible when the outcome is negative, absent, delayed, contested, or missing.

## Exclusion Rules

Exclusion is permitted only for a pre-specified reason:

- duplicate or inseparable entry;
- outside the field, venue, or time window;
- no identifiable focal system;
- no bounded candidate possibility;
- legally or practically inaccessible core record;
- evidence loss so severe that all relevant stages would be indeterminate;
- or a frame-definition error documented before outcome analysis.

“Unimportant,” “unsuccessful,” “not influential,” “not a discovery,” and “does not fit the theory” are prohibited exclusion reasons.

Every exclusion must remain in a disposition log so the denominator and potential selection effects are visible.

## Outcome and Stage Coverage

The frame should permit, but must not quota-sample after outcomes are known:

- access without demonstrated recognition;
- contested recognition;
- recognition without pursuit;
- delayed or partial pursuit;
- pursuit without realization;
- recognition followed by realization;
- premature or false recognition;
- foreclosure;
- and indeterminate trajectories.

If one or more categories do not appear naturally, that is a descriptive feature of the bounded frame, not a reason to import famous cases.

## Evidence-Feasibility Test

Before freezing the full frame, Stage 2A should take a small **enumeration-order feasibility slice** from each serious candidate frame.

The slice must be selected by a mechanical rule independent of outcome, such as the first eligible entries after a pre-specified date or a reproducible random selection from the full source list.

For each entry, test:

- whether the source-generated list can be reproduced;
- whether the focal system and episode boundary are stable;
- whether pre-outcome evidence can be separated from later information;
- whether authority and resources are documented independently;
- whether realization criteria and horizons are comparable;
- whether negative and unresolved trajectories leave recoverable records;
- how much evidence is inaccessible or missing;
- and how long packet construction requires.

This exercise is evidence reconnaissance, not substantive hypothesis testing. Its codes should not be pooled with the later study unless the protocol explicitly freezes that treatment before analysis.

## Reliability Plan

After a frame passes feasibility:

1. freeze the population list, eligibility rules, and outcome horizon;
2. retain all entries in a disposition ledger;
3. double-code a pre-specified reliability subsample selected independently of outcome and document availability;
4. oversample only pre-specified high-risk boundary types for reliability testing, not for prevalence estimation;
5. report raw agreement for every stage, final category, focal-system level, and confidence field;
6. calculate a reliability coefficient only if the number and distribution of episodes support it;
7. adjudicate substantive disagreements under the frozen rules;
8. review exceptions for outcome leakage, actor-boundary instability, conjunctive candidates, and source conflict;
9. audit missingness and exclusions across the full frame;
10. keep confirmatory estimates separate from diagnostic and reliability samples.

## Competing Explanations and Required Covariates

Recognition should not be interpreted as an independent cause merely because it precedes pursuit or realization.

At minimum, record:

- information access;
- prior knowledge or specialization;
- decision authority;
- staffing and funding;
- instrument or infrastructure access;
- institutional position;
- collaboration network;
- perceived feasibility and value;
- uncertainty at the decision point;
- documentation intensity;
- and evidence survival or access.

The study should first establish distributions, stage separability, and missingness. Any causal or predictive modeling requires a later identification decision and should not be presumed by this design.

## Bias and Missingness Register

Stage 2A must explicitly assess:

| Risk | Diagnostic question |
|---|---|
| Outcome selection | Could an entry appear in the frame only because its result became known? |
| Fame selection | Are visible actors or claims more likely to be enumerated? |
| Publication selection | Are rejected, null, or abandoned entries absent? |
| Archival survival | Does documentation persist differentially by outcome or institution? |
| Access restriction | Are confidential or proprietary records systematically missing? |
| Citation selection | Does later attention determine which records can be found? |
| Actor-level selection | Are individuals visible while teams or institutions disappear? |
| Temporal selection | Do evidence practices change within the window? |
| Framework-fit selection | Were entries retained because they illustrate preferred categories? |
| Attrition | Do episodes disappear before the outcome horizon? |

Missingness should be coded as a study variable, not treated as a clerical inconvenience.

## Decision Gates

### GO to substantive Stage 2 coding

Proceed only if one concrete frame:

- has a reproducible source-generated denominator;
- applies inclusion without outcome knowledge;
- yields stable episode and focal-system boundaries;
- provides separable pre-outcome evidence for a substantial majority of an outcome-independent feasibility slice;
- supports rule-governed outcome horizons and realization criteria;
- preserves exclusions and missing entries in a disposition ledger;
- documents authority, resources, and capability independently of recognition;
- and can be executed within a bounded evidence and coding burden.

“Substantial majority” must be converted into a numerical threshold after reconnaissance reveals the realistic evidence regime and before the decisive feasibility slice is evaluated.

### NARROW

Narrow the field, entry channel, period, focal-system level, or question if a plausible denominator exists but comparability or evidence coverage is too heterogeneous.

### REDESIGN

Redesign the unit or construct if entries are enumerable but opportunity episodes cannot be bounded without outcome information, or if recognition is already guaranteed by the frame’s entry rule.

### STOP

Stop Stage 2 Science if:

- no concrete frame has an outcome-independent denominator;
- negative and unresolved entries are systematically unrecoverable;
- pre-outcome evidence is available mainly for successful or famous episodes;
- exclusions would dominate or conceal the population;
- recognition cannot be separated from frame entry, authority, or pursuit;
- or the feasible design cannot answer more than the two completed benchmark episodes already answer.

Stopping Stage 2 Science would not invalidate the pilot. It would show that the construct is not presently scalable under an adequate sampling design.

## Stage 2A Candidate-Frame Reconnaissance

The reconnaissance was limited to three concrete public-source families. The test asked whether each source could enumerate entries independently of later outcome **and** include the absence of recognition rather than beginning after recognition had already occurred.

| Candidate | Official source capability | Construct fit | Evidence symmetry | Decision |
|---|---|---|---|---|
| NSF proposal cohort | The [NSF Award Search](https://www.nsf.gov/funding/award-search) enumerates funded projects, while the [proposal process](https://www.nsf.gov/funding/overview) also produces declined decisions that are not exposed as a comparable public proposal corpus. | A submitted proposal evidences recognition; the public denominator is additionally selected on award. | Failed at the public-source level. | Reject |
| arXiv or bioRxiv submission cohort | arXiv provides [daily OAI-PMH metadata for all submissions](https://info.arxiv.org/help/bulk_data.html). The [bioRxiv API](https://api.biorxiv.org/) provides date-bounded preprint metadata and links to later publication where available. | Submission already evidences recognition and pursuit by the originating team. A study could examine later publication or community uptake, but not recognition versus nonrecognition under the present focal-system definition. | Strong for posted items; absent for ideas never submitted. | Redesign only |
| ClinicalTrials.gov registration cohort | ClinicalTrials.gov provides structured [study records](https://clinicaltrials.gov/data-api/about-api/study-data-structure) and visible [record histories](https://clinicaltrials.gov/study-basics/how-to-read-study-record). | Registration already evidences a recognized and substantially pursued research possibility. The frame could study completion, reporting, or realization after registration, not uneven recognition. | Stronger after registration; no denominator of unregistered opportunities. | Redesign only |

### Reconnaissance Result

The candidates reveal the same structural problem:

1. source-generated public lists become enumerable only after an actor has articulated, submitted, posted, proposed, or registered a possibility;
2. those acts are themselves evidence of recognition and usually pursuit;
3. unrecognized possibilities do not generate records by definition;
4. abandoned or rejected ideas before formal entry are not publicly enumerable in a comparable way;
5. and later attempts to reconstruct them would recreate the hindsight, fame, and archival-selection problems the design was intended to avoid.

This is not merely a data-volume problem. It is a mismatch between the original estimand and the observable entry processes.

## Final Gate Decision

**STOP the original Stage 2 Science scaling attempt.**

Do not:

- code the existing Science corpus as a sample;
- build an artificial balance of realized and unrealized cases;
- estimate the prevalence or effect of recognition;
- continue searching indefinitely for a denominator of unrecognized opportunities;
- or add further candidate-frame documents.

The completed FLEM-01 and CF-01 cycles remain valid as bounded construct and instrument tests. The stop decision concerns scalability and population inference, not the usefulness of the recognition distinction.

## Possible Redesign — Not Authorized Automatically

A different study could begin at a documented entry point and ask a narrower question, such as:

> Among publicly posted or registered scientific claims, what predicts later community recognition, continued pursuit, validation, publication, completion, or realization?

This would change:

- the focal system from the originating actor to a scientific audience, institution, or validation community;
- the recognition event from initial opportunity recognition to post-entry uptake;
- the eligible population to submitted or registered records;
- and the theoretical target from the original form of Proposition 4 to a narrower diffusion, selection, or validation relationship.

That study may be feasible with arXiv, bioRxiv, or ClinicalTrials.gov, but it is not a continuation by default. It requires a separate decision that the redesigned question is important enough to justify the work and remains sufficiently connected to Research on Luck.

## Project-Level Interpretation

The bounded reconnaissance has served its purpose. It prevented a purposive case collection from being misrepresented as a population and exposed a genuine observability limit:

> recognition can be coded within known episodes, but the prevalence and effects of recognition cannot be estimated from public records when nonrecognition leaves no enumerable trace.

This result should narrow the evidence claim for Proposition 4. It should not trigger additional exploratory case accumulation.

## Claims Authorized by This Record

This record supports the following limited conclusions:

- the recognition construct remains provisionally codeable within bounded known episodes;
- the existing Science corpus is calibration material, not a population;
- none of the three tested public-source families observes original recognition and nonrecognition symmetrically;
- and the original Stage 2 Science population design is not presently feasible.

It does not establish:

- that Proposition 4 is false;
- that recognition predicts or does not predict pursuit or realization;
- that no private or future data source could ever support the study;
- that the construct is cross-domain portable;
- or that a redesigned post-entry study should begin.

## Final Disposition

**Close Stage 2A with a STOP for the original scaling design. Preserve the pilot findings, narrow the claim, and require explicit authorization before pursuing any post-entry redesign. No file 21 is authorized.**
