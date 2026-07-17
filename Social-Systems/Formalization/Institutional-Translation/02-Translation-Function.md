# Translation Function

## Functional Forms for Institutional Translation

**Repository**

`Research-Lab/Social-Systems/Formalization/Institutional-Translation/02-Translation-Function.md`

**Status**

Working Draft

**Phase**

VI — Formalization

**Purpose**

To define and compare alternative functional representations of Institutional Translation, establish criteria for selecting among them, and determine which mathematical forms can represent meaningful institutional mechanisms without sacrificing interpretability, tractability, or falsifiability.

---

# 1. Purpose of This Document

The Baseline Model represented Institutional Translation through a linear interaction:

[
Y_{i,t+1}
=========

\alpha
+
\beta h_{i,t}
+
\gamma I_t
+
\delta h_{i,t}I_t
+
\varepsilon_{i,t+1}.
]

This model provides the simplest test of whether institutions change the effect of an actor characteristic.

However, institutional processes are not necessarily linear.

Institutions may:

* impose eligibility thresholds;
* create ceilings or floors;
* produce discontinuous access;
* amplify advantages cumulatively;
* compress differences;
* operate differently across regimes;
* affect probabilities rather than continuous outcomes;
* translate characteristics through intermediate opportunities;
* distribute risk asymmetrically.

The objective of this document is therefore to ask:

> Which functional form best represents the institutional mechanism under investigation?

The goal is not to identify one universal translation function.

Different institutional processes may require different forms.

The governing rule is:

> Use the simplest function that represents the substantive mechanism and generates distinguishable implications.

---

# 2. General Translation Representation

Let:

* (h_{i,t}) denote a selected actor characteristic;
* (I_t) denote the relevant institutional state;
* (E_t) denote external conditions;
* (Y_{i,t+1}) denote an observable outcome.

Institutional Translation is represented generally by:

[
Y_{i,t+1}
=========

\Phi(h_{i,t};I_t,E_t)
+
\varepsilon_{i,t+1}.
]

The semicolon emphasizes that the institutional state conditions the mapping from the actor characteristic to the outcome.

The characteristic gradient is:

[
m(h,I,E)
========

\frac{\partial \Phi(h;I,E)}{\partial h}.
]

Institutional Translation exists when this gradient varies with the institutional state:

[
\frac{\partial m(h,I,E)}{\partial I}
====================================

\frac{\partial^2 \Phi(h;I,E)}
{\partial h,\partial I}
\neq 0.
]

This cross-partial condition is useful for smooth functions.

It is not applicable without modification to discontinuous or purely discrete institutional mechanisms.

---

# 3. Requirements for a Translation Function

A valid translation function should identify:

1. the actor characteristic being translated;
2. the relevant institutional rule or configuration;
3. the channel through which translation occurs;
4. the outcome produced;
5. the expected direction or shape of the mapping;
6. the domain over which the function applies;
7. the observations capable of contradicting it.

A function should not be selected merely because it fits the data well.

It should correspond to an institutionally meaningful process.

---

# 4. Model 0 — No Institutional Translation

The null model is:

[
Y_{i,t+1}
=========

f(h_{i,t},E_t)
+
\varepsilon_{i,t+1}.
]

The actor-characteristic mapping is independent of institutions:

[
\frac{\partial^2Y}
{\partial h,\partial I}
=======================

0.

]

This remains the fundamental benchmark.

A proposed translation function must outperform or conceptually improve upon this simpler explanation.

---

# 5. Model 1 — Additive Institutional Shift

An institution may shift outcomes without changing the characteristic gradient:

[
Y_{i,t+1}
=========

f(h_{i,t},E_t)
+
g(I_t)
+
\varepsilon_{i,t+1}.
]

The marginal characteristic effect is:

[
\frac{\partial Y}{\partial h}
=============================

f_h(h,E),
]

which does not depend on (I).

This model recognizes institutional influence but does not represent Institutional Translation in the narrower sense.

It should remain the immediate benchmark for every translation model.

---

# 6. Model 2 — Linear Translation

The linear translation function is:

[
\Phi(h;I,E)
===========

\alpha
+
\beta h
+
\gamma I
+
\delta hI
+
\lambda^{\top}E.
]

The characteristic gradient is:

[
\frac{\partial \Phi}{\partial h}
================================

\beta+\delta I.
]

The institutional gradient is:

[
\frac{\partial \Phi}{\partial I}
================================

\gamma+\delta h.
]

The cross-partial is constant:

[
\frac{\partial^2\Phi}
{\partial h,\partial I}
=======================

\delta.
]

## Interpretation

The institutional state changes the characteristic gradient by the same amount throughout the observed range.

## Appropriate Uses

The linear form is appropriate when:

* the relevant ranges are limited;
* no threshold is theoretically expected;
* translation effects are approximately constant;
* interpretability is a priority;
* the model serves as a first approximation.

## Limitations

The form may be inappropriate when:

* effects saturate;
* eligibility changes discontinuously;
* institutions create floors or ceilings;
* the effect varies at different characteristic levels;
* outcomes are bounded or discrete.

## Baseline Status

The linear form remains the preferred first specification unless the mechanism clearly requires another structure.

---

# 7. Model 3 — Nonlinear Characteristic Translation

Institutions may alter a nonlinear characteristic–outcome relationship:

[
\Phi(h;I,E)
===========

\alpha
+
f(h)
+
g(I)
+
q(h,I)
+
\lambda^{\top}E.
]

One simple quadratic specification is:

[
\Phi(h;I,E)
===========

\alpha
+
\beta_1 h
+
\beta_2 h^2
+
\gamma I
+
\delta_1 hI
+
\delta_2 h^2I
+
\lambda^{\top}E.
]

The characteristic gradient is:

[
\frac{\partial \Phi}{\partial h}
================================

\beta_1
+
2\beta_2 h
+
\delta_1 I
+
2\delta_2 hI.
]

The institutional translation effect varies across characteristic levels.

## Interpretation

Institutions may have little effect at low levels of a characteristic but large effects at high levels, or the reverse.

## Possible Mechanisms

* high skill produces disproportionate rewards only under particular labor institutions;
* wealth compounds more rapidly after crossing an institutional access threshold;
* education yields diminishing returns under one regime and increasing returns under another;
* network access matters only after minimum capability is achieved.

## Risk

Polynomial forms may fit complex patterns without representing a clear institutional mechanism.

Higher-order terms should not be added automatically.

---

# 8. Model 4 — Multiplicative Translation

A multiplicative function may be written:

[
\Phi(h;I)
=========

\kappa h^{\beta}I^{\gamma},
]

for positive (h), (I), and (\kappa).

Taking logarithms gives:

[
\log \Phi
=========

\log\kappa
+
\beta\log h
+
\gamma\log I.
]

This simple multiplicative form does not necessarily contain translation in the strict cross-partial sense because the institution and characteristic enter jointly but with fixed elasticities.

A more explicit multiplicative translation form is:

[
\Phi(h;I)
=========

\kappa h^{\beta+\delta I}.
]

Then:

[
\frac{\partial \log \Phi}
{\partial \log h}
=================

\beta+\delta I.
]

## Interpretation

Institutions change the elasticity of outcomes with respect to the actor characteristic.

## Appropriate Uses

The form may be suitable for:

* wealth accumulation;
* productivity;
* scale-dependent returns;
* proportional growth;
* compounding advantage.

## Limitations

It generally requires positive variables and can imply implausible explosive effects.

It should be used only when proportional relationships have substantive meaning.

---

# 9. Model 5 — Saturating Translation

Institutional opportunities or rewards may have upper bounds.

A saturating function may be represented by:

[
\Phi(h;I)
=========

\alpha
+
\frac{K(I)h}{c(I)+h}.
]

Here:

* (K(I)) is the institution-dependent maximum effect;
* (c(I)) determines the characteristic level at which half the maximum is reached.

The characteristic gradient is:

[
\frac{\partial \Phi}{\partial h}
================================

\frac{K(I)c(I)}
{\left[c(I)+h\right]^2}.
]

## Interpretation

Institutions may influence:

* the maximum attainable outcome;
* the speed at which the maximum is approached;
* both.

## Possible Applications

* educational credentials and occupational access;
* credit capacity;
* administrative benefit levels;
* organizational promotion ladders;
* licensing regimes.

## Advantages

The model naturally represents diminishing returns and institutional ceilings.

## Limitations

The parameters may be difficult to identify without broad characteristic variation.

---

# 10. Model 6 — Threshold Translation

Some institutions act through explicit eligibility rules.

Let (h^\ast(I)) denote an institution-dependent threshold.

A deterministic threshold model is:

[
\Phi(h;I)
=========

\begin{cases}
\phi_0(h,I), & h<h^\ast(I),[4pt]
\phi_1(h,I), & h\geq h^\ast(I).
\end{cases}
]

A simple version is:

[
Y
=

\alpha
+
\beta h
+
\tau
\mathbf{1}
\left{
h\geq h^\ast(I)
\right}
+
\varepsilon.
]

## Interpretation

Institutions translate characteristics by determining whether actors cross a gate.

## Possible Mechanisms

* admission cutoffs;
* benefit eligibility;
* occupational licensing;
* voting eligibility;
* credit-score thresholds;
* promotion requirements;
* legal-status classifications.

## Institutional Translation

Institutions may alter:

* the threshold (h^\ast(I));
* the reward after crossing it;
* the slope below or above it;
* enforcement of the threshold.

## Advantages

Threshold models closely match many explicit institutional rules.

## Limitations

Formal thresholds may differ from effective thresholds.

Actors may manipulate or sort around the cutoff.

---

# 11. Model 7 — Smooth Threshold Translation

Institutional gates may operate probabilistically rather than deterministically.

Let access probability be:

[
\Pr(O_{i,t}=1)
==============

F
\left(
a
+
b h_{i,t}
+
c I_t
+
d h_{i,t}I_t
\right),
]

where (F) is a cumulative distribution function such as the logistic or normal distribution.

The final outcome may be:

[
Y_{i,t+1}
=========

q
+
rO_{i,t}
+
s h_{i,t}
+
\varepsilon_{i,t+1}.
]

## Interpretation

Institutions alter the probability that a characteristic produces access to an opportunity.

## Appropriate Uses

* hiring;
* admission;
* credit approval;
* benefit take-up;
* promotion;
* political candidacy;
* enforcement exposure.

## Advantage

The function represents uncertainty, discretion, and unobserved institutional judgments.

## Limitation

The reduced-form interaction may not identify the precise decision process without mechanism evidence.

---

# 12. Model 8 — Regime-Specific Translation

Let:

[
R_t\in{1,\ldots,R}
]

identify the institutional regime.

The translation function is:

[
Y_{i,t+1}
=========

\Phi_{R_t}(h_{i,t},E_t)
+
\varepsilon_{i,t+1}.
]

Each regime may have a distinct mapping.

For a linear regime model:

[
Y_{i,t+1}
=========

\alpha_{R_t}
+
\beta_{R_t}h_{i,t}
+
\lambda_{R_t}^{\top}E_t
+
\varepsilon_{i,t+1}.
]

## Interpretation

Institutional systems may differ in ways that cannot be summarized by one scalar institutional index.

## Appropriate Uses

* legal-system types;
* welfare regimes;
* property-right regimes;
* electoral systems;
* educational systems;
* organizational governance types.

## Advantages

The form allows broad institutional differences without forcing an artificial ordering.

## Limitations

Regime indicators may combine many mechanisms.

The model may identify differences without explaining which institutional feature produces them.

---

# 13. Model 9 — Piecewise Institutional Translation

Institutions may create several ranges rather than one threshold.

A piecewise-linear form is:

[
\Phi(h;I)
=========

\alpha
+
\beta_1 h
+
\sum_{k=1}^{K}
\delta_k
(h-\kappa_k(I))_+,
]

where:

[
(x)_+
=====

\max(x,0),
]

and (\kappa_k(I)) are institution-dependent knots.

## Interpretation

The characteristic gradient changes after institutional cutoffs or stages.

## Possible Applications

* progressive tax systems;
* benefit phase-outs;
* educational stages;
* promotion ladders;
* legal liability schedules;
* regulatory tiers.

## Advantage

The form can represent institutional schedules directly.

## Limitation

Too many knots can make the model descriptive rather than explanatory.

---

# 14. Model 10 — Rank-Based Translation

Some institutions translate relative position rather than absolute characteristics.

Let:

[
r_{i,t}
=======

F_{H,t}(h_{i,t})
]

denote the actor’s rank in the characteristic distribution.

The translation function becomes:

[
Y_{i,t+1}
=========

\Phi(r_{i,t};I_t,E_t)
+
\varepsilon_{i,t+1}.
]

## Interpretation

Institutions may reward:

* top ranks;
* relative credentials;
* tournament position;
* competitive standing;
* scarcity-based status.

## Possible Applications

* university admissions;
* promotions;
* tournaments;
* political-list placement;
* scarce professional positions.

## Distinction

Two actors with the same absolute characteristic may receive different outcomes if their relative rank differs across systems or cohorts.

## Limitation

Rank-based models may obscure absolute capability changes.

---

# 15. Model 11 — Distribution-Dependent Translation

Institutions may condition outcomes not only on an actor’s characteristic but also on the population distribution:

[
Y_{i,t+1}
=========

\Phi
\left(
h_{i,t};
I_t,
F_{H,t},
E_t
\right)
+
\varepsilon_{i,t+1}.
]

## Interpretation

The value of an actor characteristic may depend on:

* scarcity;
* congestion;
* competition;
* credential inflation;
* group composition;
* aggregate resource constraints.

## Example

The return to a degree may decline as the share of degree holders rises, with the extent of decline depending on labor-market institutions.

## Importance

This form begins to connect individual translation with allocation and endogenous transition dynamics.

## Limitation

It introduces equilibrium and reflection problems and should not be part of the first baseline unless clearly required.

---

# 16. Model 12 — Translation through Intermediate Opportunity

Let:

[
O_{i,t}
=======

\Omega(h_{i,t};I_t,E_t)
+
u_{i,t}
]

represent an opportunity, eligibility, assignment, or constraint.

The final outcome is:

[
Y_{i,t+1}
=========

\Gamma(O_{i,t},h_{i,t},E_t)
+
v_{i,t+1}.
]

The composed translation function is:

[
\Phi
====

\Gamma\circ\Omega.
]

Thus:

[
Y_{i,t+1}
=========

\Gamma
\left(
\Omega(h_{i,t};I_t,E_t),
h_{i,t},
E_t
\right)
+
\eta_{i,t+1}.
]

## Interpretation

Institutions first translate characteristics into access or position.

That intermediate state then affects the final outcome.

## Examples

* skill translated into employment access, then earnings;
* wealth translated into credit access, then investment returns;
* test performance translated into admission, then educational attainment;
* identity translated into enforcement exposure, then economic risk.

## Scientific Advantage

This structure permits direct testing of the proposed institutional mechanism rather than relying entirely on a reduced-form interaction.

---

# 17. Model 13 — Sequential Translation

Many institutional processes contain multiple stages.

Let:

[
O_{i,t}^{(1)}
=============

\Omega_1(h_{i,t};I_t^{(1)}),
]

[
O_{i,t}^{(2)}
=============

\Omega_2
\left(
O_{i,t}^{(1)},h_{i,t};
I_t^{(2)}
\right),
]

and:

[
Y_{i,t+1}
=========

\Gamma
\left(
O_{i,t}^{(2)},h_{i,t}
\right)
+
\varepsilon_{i,t+1}.
]

## Interpretation

An actor characteristic may be translated through several institutional gates.

For example:

[
\text{education}
\rightarrow
\text{credential recognition}
\rightarrow
\text{occupational access}
\rightarrow
\text{earnings}.
]

## Advantage

The model can identify where translation loss or amplification occurs.

## Limitation

Sequential models require substantially more data and introduce multiple selection stages.

They should follow rather than precede the baseline model.

---

# 18. Model 14 — Stochastic Translation

Institutions may not determine outcomes mechanically.

A stochastic translation function may be represented as:

[
Y_{i,t+1}
\sim
p
\left(
y
\mid
h_{i,t},I_t,E_t
\right).
]

Institutional Translation occurs when the conditional distribution changes with institutions:

[
p(y\mid h,I_1,E)
\neq
p(y\mid h,I_0,E).
]

Institutions may affect:

* the conditional mean;
* the conditional variance;
* tail probabilities;
* skewness;
* exposure to extreme outcomes.

## Importance

Institutions may translate the same characteristic into similar average outcomes but very different risks.

## Example

Two labor regimes may offer similar expected earnings but different probabilities of unemployment or catastrophic loss.

---

# 19. Model 15 — Quantile Translation

Institutional effects may differ across the outcome distribution.

A conditional quantile model is:

[
Q_{\tau}
(Y_{i,t+1}\mid h_{i,t},I_t,E_t)
===============================

\alpha_{\tau}
+
\beta_{\tau}h_{i,t}
+
\gamma_{\tau}I_t
+
\delta_{\tau}h_{i,t}I_t
+
\lambda_{\tau}^{\top}E_t.
]

## Interpretation

Institutional Translation may be stronger at:

* the bottom of the outcome distribution;
* the middle;
* the top;
* the tails.

## Application

A labor institution may compress low-end penalties while leaving top-end rewards unchanged.

## Advantage

The model provides a richer allocation analysis than mean regression alone.

## Limitation

Quantile heterogeneity should be linked to an institutional mechanism rather than treated as purely statistical variation.

---

# 20. Model 16 — Group-Specific Translation

Suppose actors belong to groups:

[
g_i\in{1,\ldots,G}.
]

The translation function may be:

[
Y_{i,t+1}
=========

\Phi
\left(
h_{i,t};
I_t,g_i,E_t
\right)
+
\varepsilon_{i,t+1}.
]

A linear form is:

[
Y
=

\alpha
+
\beta h
+
\gamma I
+
\zeta g
+
\delta hI
+
\eta hIg
+
\varepsilon.
]

## Interpretation

The same institution may translate the same characteristic differently across groups.

## Possible Mechanisms

* differential enforcement;
* discrimination;
* unequal information;
* segmented institutions;
* geographic implementation;
* group-specific network access.

## Risk

Group-specific effects can become descriptive unless the differential institutional mechanism is identified.

---

# 21. Model 17 — Formal and Effective Translation

Let:

* (I_t^F) denote formal institutions;
* (I_t^E) denote effective institutional practice.

The translation function becomes:

[
Y_{i,t+1}
=========

\Phi
\left(
h_{i,t};
I_t^F,I_t^E,E_t
\right)
+
\varepsilon_{i,t+1}.
]

A linear form is:

[
Y
=

\alpha
+
\beta h
+
\gamma_F I^F
+
\gamma_E I^E
+
\delta_F hI^F
+
\delta_E hI^E
+
\varepsilon.
]

## Interpretation

Formal reform may change written rules without changing the effective translation mapping.

## Testable Implication

Where implementation remains stable:

[
\delta_E
]

should explain outcomes more strongly than:

[
\delta_F.
]

## Importance

This distinction is essential in settings where enforcement, administrative capacity, discretion, or informal practices matter.

---

# 22. Model 18 — Institutionally Allocated Risk

Suppose the outcome contains a reward and a risk component:

[
Y_{i,t+1}
=========

## R_{i,t+1}

C_{i,t+1}.
]

Institutions may translate characteristics differently into each component:

[
R_{i,t+1}
=========

\Phi_R(h_{i,t};I_t,E_t)
+
\varepsilon^R_{i,t+1},
]

[
C_{i,t+1}
=========

\Phi_C(h_{i,t};I_t,E_t)
+
\varepsilon^C_{i,t+1}.
]

## Interpretation

An institution may increase expected rewards while also increasing exposure to loss.

## Application

* entrepreneurship;
* credit;
* employment protection;
* health insurance;
* legal liability;
* investment systems.

## Advantage

The model prevents a single net outcome from concealing institutionally allocated risk.

---

# 23. Model 19 — Dynamic Translation Function

The translation function may itself evolve:

[
\Phi_{t+1}
==========

\Psi
\left(
\Phi_t,
A_{t+1},
B_t,
P_t,
L_t,
E_t
\right).
]

The outcome equation is:

[
Y_{i,t+1}
=========

\Phi_t(h_{i,t};I_t,E_t)
+
\varepsilon_{i,t+1}.
]

## Interpretation

Current outcomes may change:

* institutional enforcement;
* political pressure;
* behavioral strategies;
* administrative learning;
* future translation rules.

## Importance

This is the bridge to Endogenous Transition Dynamics.

## Limitation

Dynamic translation should not be introduced until the static translation mapping has been operationalized and tested.

---

# 24. Functional-Form Comparison

| Form                     | Primary mechanism                  | Main advantage                | Main risk                     |
| ------------------------ | ---------------------------------- | ----------------------------- | ----------------------------- |
| Additive                 | Institutional shift                | Simple benchmark              | No translation                |
| Linear interaction       | Constant conditional effect        | Highly interpretable          | May be too restrictive        |
| Nonlinear                | Varying characteristic gradient    | Captures curvature            | Overfitting                   |
| Multiplicative           | Proportional amplification         | Natural for growth            | Explosive implications        |
| Saturating               | Institutional ceiling              | Captures diminishing returns  | Parameter identification      |
| Threshold                | Eligibility gate                   | Direct institutional meaning  | Sorting and manipulation      |
| Smooth threshold         | Probabilistic access               | Captures discretion           | Mechanism ambiguity           |
| Regime-specific          | Distinct institutional systems     | Flexible comparison           | Bundled mechanisms            |
| Piecewise                | Institutional schedules            | Matches explicit rules        | Too many cutoffs              |
| Rank-based               | Relative position                  | Fits tournaments and scarcity | Hides absolute change         |
| Distribution-dependent   | Scarcity and congestion            | Links micro and macro         | Equilibrium complexity        |
| Intermediate opportunity | Mediated translation               | Strong mechanism test         | Data intensive                |
| Sequential               | Multiple institutional gates       | Locates translation stages    | Selection complexity          |
| Stochastic               | Risk allocation                    | Captures full distribution    | Harder estimation             |
| Quantile                 | Outcome-distribution heterogeneity | Allocation detail             | Statistical without mechanism |
| Group-specific           | Differential implementation        | Captures segmentation         | Descriptive proliferation     |
| Formal/effective         | Implementation gap                 | Institutionally realistic     | Measurement difficulty        |
| Risk–reward              | Separate benefits and exposure     | Richer outcome structure      | Additional variables          |
| Dynamic                  | Evolving translation rules         | Connects to feedback          | Premature complexity          |

---

# 25. Functional-Form Selection Rule

A model should select its translation function through the following sequence.

## Step 1 — Identify the Institutional Rule

Is the relevant institution:

* a continuous incentive;
* a threshold;
* a categorical regime;
* a schedule;
* an assignment process;
* an enforcement process;
* a sequence of gates?

## Step 2 — Identify the Translated Object

Does the institution translate:

* absolute characteristics;
* rank;
* group membership;
* a distributional position;
* risk exposure;
* access probability?

## Step 3 — Identify the Outcome Type

Is the outcome:

* continuous;
* binary;
* categorical;
* bounded;
* censored;
* a duration;
* a distribution;
* a transition probability?

## Step 4 — Select the Simplest Consistent Form

Begin with the lowest-complexity function that represents the mechanism.

## Step 5 — Compare with Benchmarks

Compare against:

* no institution;
* additive institution;
* linear translation.

## Step 6 — Add Complexity Only When Required

A richer function is justified only when:

* theory predicts it;
* institutional rules imply it;
* diagnostics reject the simpler form;
* predictions improve;
* evidence supports the mechanism.

---

# 26. Nested Model Strategy

Where possible, models should be nested.

For example:

## Model A

[
Y
=

\alpha+\beta h+\varepsilon.
]

## Model B

[
Y
=

\alpha+\beta h+\gamma I+\varepsilon.
]

## Model C

[
Y
=

\alpha+\beta h+\gamma I+\delta hI+\varepsilon.
]

## Model D

[
Y
=

\alpha
+
\beta_1 h
+
\beta_2h^2
+
\gamma I
+
\delta_1hI
+
\delta_2h^2I
+
\varepsilon.
]

This sequence makes clear what each layer of complexity contributes.

Non-nested functions should be compared through prediction, fit, information criteria, mechanism evidence, and counterfactual performance.

---

# 27. Interpretability Requirement

A translation function should permit substantive interpretation.

The model should answer:

* Which characteristic is being translated?
* Which institution performs the translation?
* Through which channel?
* At what characteristic levels is the institutional effect strongest?
* Does the institution compress, amplify, gate, reverse, or redistribute risk?
* Which actors are most affected?
* Which counterfactual institutional change is meaningful?

A function that cannot answer these questions may be statistically useful but theoretically weak.

---

# 28. Falsification across Functional Forms

A functional-form claim should be weakened when:

* the predicted shape is not observed;
* simpler nested models perform equally well;
* thresholds do not correspond to actual institutional rules;
* regime differences disappear after selection adjustment;
* intermediate opportunities do not mediate the outcome;
* translation effects are unstable outside the estimation sample;
* formal institutions matter but effective institutions do not in implausible ways;
* the function produces counterfactuals inconsistent with observed reforms;
* additional complexity provides fit without interpretable mechanism gain.

---

# 29. No Universal Functional Form

Institutional Translation should not be defined by one equation.

Its stable theoretical content is:

> Institutions condition the mapping from heterogeneous actor characteristics to social outcomes.

The mathematical representation depends on:

* the institutional mechanism;
* the actor characteristic;
* the outcome;
* the system boundary;
* the time scale;
* the available evidence.

Therefore, the framework should preserve one general operator:

[
\Phi(h;I,E),
]

while allowing multiple disciplined functional instantiations.

---

# 30. Recommended First-Generation Hierarchy

The first generation of Institutional Translation work should use the following hierarchy.

## Tier 1 — Baseline

* additive benchmark;
* linear interaction;
* binary or continuous institutional measure.

## Tier 2 — Mechanism

* intermediate opportunity;
* formal versus effective institution;
* threshold or regime form when institutionally explicit.

## Tier 3 — Distribution

* stochastic;
* quantile;
* risk–reward;
* allocation consequences.

## Tier 4 — Dynamics

* distribution-dependent translation;
* sequential translation;
* evolving translation function.

The project should not move to a higher tier merely because it is mathematically richer.

---

# 31. Preliminary Modeling Decision

For the first substantive application, the preferred starting point remains:

[
Y_{i,t+1}
=========

\alpha
+
\beta h_{i,t}
+
\gamma I_t
+
\delta h_{i,t}I_t
+
\varepsilon_{i,t+1}.
]

This should be supplemented by an intermediate-opportunity equation when the institutional channel can be observed:

[
O_{i,t}
=======

\Omega(h_{i,t};I_t)
+
u_{i,t},
]

[
Y_{i,t+1}
=========

\Gamma(O_{i,t},h_{i,t})
+
v_{i,t+1}.
]

A threshold, regime, nonlinear, or stochastic form should replace the baseline only when the institutional mechanism requires it.

---

# 32. Development Judgment

Institutional Translation can be represented by a family of functions rather than a single universal specification.

The baseline linear interaction provides a necessary starting point because it distinguishes:

* characteristic effects;
* direct institutional effects;
* conditional institutional effects.

However, the theoretical contribution does not depend on that particular form.

The contribution depends on identifying an institutionally meaningful mapping whose functional structure corresponds to actual rules, procedures, enforcement, access, assignment, rewards, or risks.

Functional flexibility must therefore be balanced against:

* parsimony;
* mechanism clarity;
* interpretability;
* empirical identification;
* falsifiability.

---

# Current Priority

The next artifact should introduce recursive change while preserving the baseline translation structure:

`Research-Lab/Social-Systems/Formalization/Institutional-Translation/03-Dynamic-Extension.md`

That document should examine:

* how translated outcomes alter future actor characteristics;
* how allocation affects institutional change;
* how political and behavioral responses modify the translation function;
* how formal and effective institutions diverge over time;
* when translation generates persistence, amplification, compression, or regime change.
