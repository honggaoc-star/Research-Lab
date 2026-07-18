# Evidence

## Historical, Empirical, and Data Foundations of the Dynamic Social Systems Research Program

**Repository**

`Research-Lab/Social-Systems/Evidence/README.md`

**Status**

Active Development


**Purpose**

To organize historical cases, empirical research, data documentation, and comparative tests used to evaluate the propositions and formal models of the Dynamic Social Systems framework.

---

# 1. Role of the Evidence Folder

The `Evidence/` folder contains the research materials used to test the Dynamic Social Systems framework.

It is distinct from:

* `Literature/`, which reviews existing scholarship;
* `Validation/`, which defines propositions, falsification criteria, and testing protocols;
* `Formalization/`, which develops mathematical and computational models;
* `Applications/`, which applies the framework to substantive domains.

The Evidence phase asks:

> Do the framework’s propositions and mechanisms correspond to observable historical and empirical patterns?

Evidence should be used to challenge the framework rather than merely illustrate it.

---

# 2. Folder Structure

```text
Research-Lab/Social-Systems/Evidence/
├── README.md
├── Historical/
├── Empirical/
└── Data/
```

## Historical

Contains completed historical case studies, comparative histories, process tracing, and historically grounded counterfactual analysis.

## Empirical

Contains research designs, statistical analyses, identification strategies, model comparisons, robustness tests, and empirical results.

## Data

Contains data dictionaries, source maps, variable definitions, provenance records, transformation notes, and reproducibility documentation.

Large raw datasets should not automatically be stored in the repository.

Where appropriate, the repository should contain instructions for obtaining or reconstructing the data.

---

# 3. Relationship to Validation

The Evidence phase is governed by:

`Research-Lab/Social-Systems/Validation/`

Relevant documents include:

* `04-Testable-Propositions.md`;
* `05-Falsification-Criteria.md`;
* `06-Historical-Validation.md`;
* `07-Readiness-Assessment.md`;
* `08-Validation-Summary.md`.

The Validation phase established what should be tested.

The Evidence folder records the actual testing work.

For example:

* `Validation/06-Historical-Validation.md` defines the historical-testing protocol;
* `Evidence/Historical/` contains completed historical analyses conducted under that protocol.

---

# 4. Evidence Standards

Evidence should be evaluated according to:

* relevance;
* validity;
* reliability;
* temporal ordering;
* causal identification;
* measurement quality;
* source provenance;
* robustness;
* comparability;
* reproducibility;
* capacity to distinguish competing explanations.

Evidence that is merely consistent with the framework is not sufficient.

The analysis should determine whether the framework explains more than simpler alternatives.

---

# 5. Historical Evidence

Historical analysis should identify:

1. system boundary;
2. time period;
3. initial state;
4. institutional structure;
5. relevant actor heterogeneity;
6. shock, reform, or transition;
7. predicted mechanism;
8. observed trajectory;
9. competing explanations;
10. contradictory evidence;
11. counterfactual;
12. validation judgment.

Historical cases should be classified as:

* supportive;
* partially supportive;
* inconclusive;
* contradictory;
* outside scope.

---

# 6. Historical Case Selection

The historical portfolio should include multiple case types.

## Supportive Cases

Cases in which predicted mechanisms appear clearly.

---

## Negative Cases

Cases in which the framework predicts a mechanism that does not appear.

---

## Divergent Cases

Cases with similar starting conditions but different later trajectories.

---

## Convergent Cases

Cases with different starting conditions but similar outcomes.

---

## Interrupted Cases

Cases in which external shocks disrupt the expected process.

---

## Boundary Cases

Cases where the framework applies only weakly.

---

## Rival-Explanation Cases

Cases where a simpler theory may be sufficient.

Case selection should not be limited to favorable examples.

---

# 7. Initial Historical Priorities

The first historical portfolio should remain limited.

Recommended case families include:

## Institutional Divergence

Comparable systems that developed different institutional and distributional trajectories.

## Land or Education Reform

Institutional reforms with measurable long-run effects on development, allocation, or mobility.

## Crisis and Recovery

Comparable shocks followed by different institutional responses and recovery paths.

These cases offer strong opportunities to examine:

* Institutional Translation;
* recursive feedback;
* endogenous transition dynamics;
* adaptive capacity;
* unequal shock amplification;
* development–allocation co-evolution.

---

# 8. Empirical Evidence

Empirical research should translate propositions into measurable relationships.

Possible methods include:

* panel analysis;
* cohort analysis;
* multilevel modeling;
* transition matrices;
* event studies;
* difference-in-differences;
* regression discontinuity;
* synthetic controls;
* instrumental variables;
* survival analysis;
* network analysis;
* structural estimation;
* comparative institutional analysis;
* simulation-to-data comparison.

Method selection should follow the research question rather than the availability of a preferred technique.

---

# 9. Empirical Research Template

Each empirical project should include:

## Research Question

What proposition or mechanism is being tested?

## Hypothesis

What directional or conditional relationship is expected?

## System Boundary

Which population, jurisdiction, institution, or period is included?

## Unit of Analysis

What entity is observed?

## Variables

How are states, mechanisms, institutions, and observables measured?

## Identification Strategy

How is the proposed effect distinguished from confounding factors?

## Benchmark

Which simpler theory or model serves as a comparator?

## Results

What does the evidence show?

## Robustness

Do results survive alternative specifications and measurements?

## Mechanism Test

Does evidence support the proposed mechanism rather than only the outcome?

## Contradictory Evidence

What findings weaken the proposition?

## Validation Judgment

Should the proposition be retained, narrowed, revised, or rejected?

---

# 10. Data Principles

All data work should preserve:

* provenance;
* versioning;
* reproducibility;
* transparent transformations;
* consistent units;
* clear variable definitions;
* temporal alignment;
* geographic alignment;
* disclosure of missingness;
* disclosure of measurement error.

Every dataset or data source should have a corresponding data note.

---

# 11. Data Documentation

A data note should contain:

* dataset name;
* provider;
* access date;
* coverage;
* unit of observation;
* time period;
* geographic scope;
* file format;
* variable dictionary;
* transformations;
* exclusions;
* missing-data treatment;
* licensing or access restrictions;
* known limitations;
* reproducibility instructions.

Recommended path:

```text
Research-Lab/Social-Systems/Evidence/Data/
└── <Dataset-Name>-Data-Note.md
```

---

# 12. Source Hierarchy

Evidence should generally prioritize:

1. official administrative records;
2. original datasets;
3. archival records;
4. peer-reviewed empirical research;
5. authoritative historical syntheses;
6. credible institutional reports;
7. secondary summaries;
8. anecdotal evidence.

Lower-level sources may still be useful but should not carry central causal claims without corroboration.

---

# 13. Mechanism Evidence

Observed correlations do not automatically validate the framework.

Mechanism evidence should identify the sequence through which change occurred.

For example, evidence for recursive feedback should show:

1. an initial outcome;
2. a change in resources, beliefs, power, or institutions;
3. a subsequent change in opportunities or transition probabilities;
4. persistence beyond the original event.

Mechanism analysis may use:

* temporal ordering;
* mediation analysis;
* archival evidence;
* process tracing;
* institutional records;
* behavioral response data;
* policy sequences.

---

# 14. Comparative Benchmarking

Every major evidence project should compare the framework with at least one alternative explanation.

Possible alternatives include:

* Human Capital Theory;
* Institutional Economics;
* Political Economy;
* Behavioral Economics;
* Evolutionary Economics;
* Complexity Science;
* Distribution Dynamics;
* fixed-parameter transition models;
* exogenous shock models.

The framework should not receive credit for explaining a pattern already fully explained by a simpler model.

---

# 15. Negative and Null Results

Negative results should be preserved.

They may show that:

* a proposition does not hold;
* a mechanism applies only under narrower conditions;
* a state variable is unnecessary;
* an institutional measure is invalid;
* an alternative theory performs better;
* the framework has been overgeneralized.

Negative evidence is part of validation rather than evidence of project failure.

Relevant artifacts should be retained unless they contain invalid or irreproducible work.

---

# 16. Counterfactual Evidence

Counterfactual analysis should be historically or empirically disciplined.

A counterfactual should specify:

* the variable or institution changed;
* why the alternative was feasible;
* the mechanism affected;
* the predicted immediate consequence;
* subsequent feedback;
* uncertainty;
* competing counterfactual pathways.

Counterfactual conclusions should not be stated more strongly than the available design permits.

---

# 17. Relationship to Formalization

Evidence should inform model development.

Relevant formal work is stored in:

`Research-Lab/Social-Systems/Formalization/`

The relationship should be iterative:

1. formalization generates predictions;
2. evidence tests those predictions;
3. results identify model weaknesses;
4. the model is narrowed, revised, or rejected;
5. further evidence evaluates the revision.

Formalization should not proceed independently of evidence for long periods.

---

# 18. Relationship to Applications

Evidence may be organized around substantive applications stored in:

`Research-Lab/Social-Systems/Applications/`

For example, evidence concerning inequality may examine:

* income and wealth distributions;
* institutional returns to education;
* intergenerational mobility;
* housing and land regimes;
* unequal shock exposure;
* political feedback from concentration.

Application-specific evidence should still follow the common validation standards.

---

# 19. Relationship to the Working Paper

Only evidence that directly supports the manuscript’s core contribution should be integrated into:

`Research-Lab/Social-Systems/Working-Paper/`

Supporting analyses may remain in the Evidence folder.

The working paper should accurately distinguish among:

* descriptive evidence;
* causal evidence;
* mechanism evidence;
* historical interpretation;
* suggestive patterns;
* unresolved uncertainty.

---

# 20. Reproducibility

Empirical work should be reproducible where legally and technically possible.

A reproducible project should identify:

* source data;
* access instructions;
* software requirements;
* scripts;
* execution order;
* random seeds;
* model specifications;
* output locations;
* expected results;
* known sources of variation.

Sensitive or proprietary data should be documented without being improperly distributed.

---

# 21. Evidence Review

Each major evidence artifact should receive review for:

* factual accuracy;
* source quality;
* causal reasoning;
* measurement validity;
* robustness;
* alternative explanations;
* consistency with prior predictions;
* selective reporting;
* overstatement.

The `Red-Team/` folder may contain adversarial reviews of major evidence claims.

---

# 22. Success Criteria

The Evidence phase will be considered successful when it produces:

* at least one completed historical case under the validation protocol;
* at least one empirical or quasi-empirical test of a priority proposition;
* explicit comparison with a simpler theory;
* evidence concerning the proposed mechanism;
* documented negative or contradictory findings;
* reproducible data documentation;
* a clear judgment about whether the framework adds explanatory value.

---

# 23. Failure Criteria

The evidence strategy should be reconsidered if:

* core concepts cannot be measured or inferred;
* proposed mechanisms leave no observable traces;
* results depend on selective case choice;
* the framework adds no value beyond existing theories;
* historical analysis remains retrospective description;
* data limitations prevent meaningful discrimination;
* definitions vary across projects;
* contradictory evidence is repeatedly excluded.

---

# Current Priority

The initial Evidence phase should identify one historical comparison and one empirical design related to:

> Endogenous Transition Dynamics

The immediate question is whether institutional changes can be shown to modify mobility, persistence, or other transition probabilities over time.
