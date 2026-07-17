# Empirical Strategy

## Research Designs for Testing Institutional Translation

**Repository**

`Research-Lab/Social-Systems/Formalization/Institutional-Translation/05-Empirical-Strategy.md`

**Status**

Working Draft

**Phase**

VI — Formalization

**Purpose**

To translate the theoretical predictions of Institutional Translation into feasible empirical research designs, including measurement choices, identification strategies, estimation methods, robustness standards, and criteria for interpreting supportive, inconclusive, or contradictory evidence.

---

# 1. Purpose

The Institutional Translation framework proposes that institutions condition how heterogeneous actor characteristics are converted into opportunities, constraints, rewards, risks, and observable outcomes.

The empirical task is not merely to show that institutions correlate with outcomes.

It is to determine whether:

1. actor characteristics affect outcomes;
2. institutional conditions affect outcomes;
3. institutions alter the effect of actor characteristics;
4. the proposed translation channel can be observed;
5. the relationship survives credible identification tests;
6. static translation contributes to longer-run dynamics.

The empirical strategy should proceed sequentially.

Complex dynamic models should not be estimated before the static translation mechanism has been established.

---

# 2. Core Empirical Question

The defining empirical question is:

> Does the relationship between an actor characteristic and an outcome vary causally and systematically across institutional conditions?

The baseline model is:

[
Y_{i,j,t+1}
===========

\alpha
+
\beta h_{i,j,t}
+
\gamma I_{j,t}
+
\delta h_{i,j,t}I_{j,t}
+
\lambda^\top X_{i,j,t}
+
\mu_j
+
\tau_t
+
\varepsilon_{i,j,t+1},
]

where:

* (i) indexes actors;
* (j) indexes institutional units or jurisdictions;
* (t) indexes time;
* (h_{i,j,t}) is the selected actor characteristic;
* (I_{j,t}) is the institutional condition;
* (Y_{i,j,t+1}) is the outcome;
* (X_{i,j,t}) contains observed covariates;
* (\mu_j) represents unit effects;
* (\tau_t) represents time effects;
* (\delta) is the Institutional Translation parameter.

The baseline null hypothesis is:

[
H_0:\delta=0.
]

Rejecting this null is necessary but not sufficient to establish Institutional Translation.

---

# 3. Empirical Unit of Analysis

The unit of analysis should follow the institutional mechanism.

Possible units include:

* individuals;
* households;
* firms;
* organizations;
* schools;
* occupations;
* geographic areas;
* administrative units;
* political jurisdictions;
* cohorts.

The institutional unit may differ from the outcome unit.

For example:

* individuals may be nested within firms;
* students may be nested within schools;
* households may be nested within jurisdictions;
* firms may be nested within regulatory regimes.

The research design must state explicitly:

1. the actor-level unit;
2. the institutional-level unit;
3. the time interval;
4. the system boundary;
5. the population to which the inference applies.

---

# 4. Empirical Objects

Each study should define five empirical objects.

## Actor Characteristic

The characteristic being translated:

[
h_{i,t}.
]

Examples include:

* education;
* skill;
* initial wealth;
* health;
* identity;
* location;
* legal status;
* prior institutional position.

## Institutional Condition

The rule, regime, procedure, or implementation condition:

[
I_{j,t}.
]

## Intermediate Translation Channel

Where observable:

[
O_{i,j,t}.
]

Examples include:

* eligibility;
* access;
* assignment;
* approval;
* enforcement;
* institutional recognition.

## Final Outcome

The translated result:

[
Y_{i,j,t+1}.
]

## Relevant Environment

Observed external conditions and confounders:

[
E_{j,t}
\quad\text{or}\quad
X_{i,j,t}.
]

The theory becomes difficult to test when these objects are defined only abstractly.

---

# 5. Measurement Strategy

## 5.1 Actor Characteristics

The selected characteristic should be:

* measured before the outcome;
* conceptually distinct from the institution;
* comparable across institutional settings;
* resistant to post-treatment contamination;
* sufficiently variable within institutional units.

Where possible, multiple measures should be used to distinguish the underlying characteristic from measurement artifacts.

For example, human capital may be measured through:

* educational attainment;
* test performance;
* occupational credentials;
* prior experience.

These measures are not interchangeable and should not be combined without justification.

---

## 5.2 Institutional Conditions

Institutional measurement should distinguish among:

### Formal Institutions

Written laws, policies, rules, procedures, or eligibility requirements.

### Effective Institutions

Observed enforcement, implementation, administrative practice, and actual access.

### Perceived Institutions

Actor expectations regarding enforcement, opportunity, or institutional reliability.

The preferred measurement hierarchy is:

1. effective institutional practice;
2. formal rules supplemented by implementation evidence;
3. broad institutional indices;
4. perception measures.

Broad composite indices should be used cautiously because they may obscure the specific translation mechanism.

---

## 5.3 Translation Channels

The empirical design should measure an intermediate opportunity when possible.

Examples include:

* application eligibility;
* interview invitation;
* credit approval;
* school placement;
* licensing approval;
* enforcement action;
* promotion consideration;
* benefit receipt.

A mechanism model may be written:

[
O_{i,j,t}
=========

\Omega(h_{i,j,t};I_{j,t})
+
u_{i,j,t},
]

followed by:

[
Y_{i,j,t+1}
===========

\Gamma(O_{i,j,t},h_{i,j,t},I_{j,t})
+
v_{i,j,t+1}.
]

Observing the intermediate channel substantially strengthens the interpretation of the translation coefficient.

---

## 5.4 Outcomes

Outcomes should match the time horizon and institutional process.

Possible outcome types include:

* continuous outcomes;
* binary outcomes;
* ordered outcomes;
* durations;
* transitions;
* distributions;
* risks or tail events.

The study should distinguish:

* immediate institutional outputs;
* intermediate outcomes;
* long-run outcomes.

For example:

[
\text{eligibility}
\rightarrow
\text{access}
\rightarrow
\text{employment}
\rightarrow
\text{earnings}.
]

Estimating only the final outcome may conceal the stage at which translation occurs.

---

# 6. Baseline Estimation Sequence

Empirical analysis should begin with nested models.

## Model A — Characteristic Only

[
Y_{i,j,t+1}
===========

\alpha
+
\beta h_{i,j,t}
+
\lambda^\top X_{i,j,t}
+
\varepsilon_{i,j,t+1}.
]

## Model B — Additive Institution

[
Y_{i,j,t+1}
===========

\alpha
+
\beta h_{i,j,t}
+
\gamma I_{j,t}
+
\lambda^\top X_{i,j,t}
+
\varepsilon_{i,j,t+1}.
]

## Model C — Institutional Translation

[
Y_{i,j,t+1}
===========

\alpha
+
\beta h_{i,j,t}
+
\gamma I_{j,t}
+
\delta h_{i,j,t}I_{j,t}
+
\lambda^\top X_{i,j,t}
+
\varepsilon_{i,j,t+1}.
]

## Model D — Mechanism Model

[
O_{i,j,t}
=========

\Omega(h_{i,j,t};I_{j,t},X_{i,j,t})
+
u_{i,j,t},
]

[
Y_{i,j,t+1}
===========

\Gamma(O_{i,j,t},h_{i,j,t},I_{j,t},X_{i,j,t})
+
v_{i,j,t+1}.
]

This sequence identifies what additional explanatory content is contributed by each layer.

---

# 7. Interpretation of the Interaction

The coefficient:

[
\delta
]

should not be interpreted in isolation.

The relevant marginal effect is:

[
\frac{\partial \mathbb{E}[Y]}
{\partial h}
============

\beta+\delta I.
]

For discrete institutions, the study should report:

* predicted outcomes by regime;
* characteristic gradients by regime;
* institutional effects at substantively meaningful characteristic levels;
* confidence intervals for all marginal effects.

For nonlinear models, the interaction coefficient may not equal the interaction effect.

The study should calculate and display the relevant marginal effects directly.

---

# 8. Centering and Reference Values

Because the direct-effect parameters depend on reference values, continuous variables should be centered substantively.

Let:

[
\tilde h_{i,t}
==============

h_{i,t}-h^\ast,
]

and:

[
\tilde I_{j,t}
==============

I_{j,t}-I^\ast,
]

where (h^\ast) and (I^\ast) are meaningful reference values.

Possible references include:

* the population mean;
* a policy threshold;
* the median actor;
* the pre-reform regime;
* a theoretically defined baseline.

Centering improves interpretation but does not alter the underlying interaction estimate.

---

# 9. Identification Problem

The principal causal challenge is that institutions are rarely assigned randomly.

The observed interaction:

[
h_{i,t}I_{j,t}
]

may reflect:

* actor sorting;
* institutional selection;
* omitted contextual factors;
* reverse causation;
* measurement error;
* correlated shocks;
* preexisting differential trends.

A credible design must explain why the estimated translation difference is attributable to institutions rather than these alternatives.

---

# 10. Identification Strategy Hierarchy

The preferred hierarchy is:

1. randomized institutional variation;
2. natural experiments or plausibly exogenous reforms;
3. discontinuities created by institutional boundaries or thresholds;
4. phased or staggered implementation;
5. longitudinal within-unit institutional change;
6. matched comparative institutional cases;
7. cross-sectional observational comparison.

Lower-ranked designs may still be useful, but causal claims should be narrower.

---

# 11. Randomized Institutional Variation

The strongest design occurs when an institutional procedure is randomly assigned.

Examples may include random variation in:

* application review systems;
* information rules;
* assignment procedures;
* enforcement intensity;
* access mechanisms;
* administrative processes.

A randomized translation design estimates:

[
Y_i
===

\alpha
+
\beta h_i
+
\gamma T_i
+
\delta h_iT_i
+
\varepsilon_i,
]

where:

[
T_i\in{0,1}
]

is randomly assigned institutional exposure.

The interaction identifies whether the institutional treatment changes the return to the actor characteristic.

Randomization of a narrow procedure does not necessarily identify the effect of an entire institutional regime.

---

# 12. Difference-in-Differences

Suppose an institutional reform affects treated units but not comparison units.

The basic model is:

[
Y_{i,j,t}
=========

\alpha
+
\beta h_{i,j,t}
+
\gamma
\left(
Treat_j\times Post_t
\right)
+
\delta
\left(
h_{i,j,t}\times Treat_j\times Post_t
\right)
+
\mu_j
+
\tau_t
+
\varepsilon_{i,j,t}.
]

The triple interaction:

[
\delta
]

tests whether the reform changes the characteristic gradient.

The identifying assumption is not merely parallel trends in average outcomes.

It requires parallel trends in the characteristic–outcome relationship absent reform.

This can be written:

[
\Delta
\left(
\frac{\partial Y}{\partial h}
\right)_{Treated}
=================

\Delta
\left(
\frac{\partial Y}{\partial h}
\right)_{Control}
]

in the absence of treatment.

This stronger requirement should be tested through pre-reform event-study coefficients.

---

# 13. Event-Study Design

A dynamic reform model is:

[
Y_{i,j,t}
=========

\alpha
+
\beta h_{i,j,t}
+
\sum_{k\neq -1}
\gamma_k D_{j,t}^{k}
+
\sum_{k\neq -1}
\delta_k
\left(
h_{i,j,t}D_{j,t}^{k}
\right)
+
\mu_j
+
\tau_t
+
\varepsilon_{i,j,t},
]

where (D_{j,t}^{k}) indicates time relative to reform.

The coefficients:

[
\delta_k
]

trace the evolution of the translation effect.

This design can test:

* pre-trends;
* implementation lags;
* gradual accumulation;
* temporary effects;
* intervention decay;
* long-run persistence.

The timing of reform exposure must be measured accurately.

---

# 14. Regression Discontinuity

Institutions often operate through eligibility thresholds.

Suppose treatment changes at:

[
h=c.
]

A regression-discontinuity design compares actors near the threshold.

The outcome equation may be:

[
Y_i
===

\alpha
+
\tau D_i
+
f(h_i-c)
+
D_i g(h_i-c)
+
\varepsilon_i,
]

where:

[
D_i
===

\mathbf{1}{h_i\geq c}.
]

This identifies the local effect of crossing the institutional threshold.

To test translation rather than only treatment, the design may examine whether subsequent returns to other predetermined characteristics differ across the cutoff.

Threshold manipulation, sorting, and institutional discretion must be assessed.

---

# 15. Geographic and Administrative Boundaries

Adjacent areas may face different institutional rules despite similar environments.

A boundary design compares actors near a jurisdictional border.

The strategy is strongest where:

* actors cannot easily sort;
* the boundary does not coincide with major economic differences;
* institutions change sharply;
* measurement is consistent across both sides.

The model may estimate:

[
Y_{i,j}
=======

\alpha
+
\beta h_i
+
\gamma I_j
+
\delta h_iI_j
+
f(distance_i)
+
\varepsilon_{i,j}.
]

The central parameter remains the differential characteristic gradient.

---

# 16. Instrumental Variables

An instrumental variable may be used when institutional exposure is endogenous.

Let:

[
Z_{j,t}
]

predict institutional exposure but affect outcomes only through the institution.

The first stage is:

[
I_{j,t}
=======

\pi_0
+
\pi_1Z_{j,t}
+
\pi_2X_{j,t}
+
u_{j,t}.
]

Because the model contains:

[
h_{i,t}I_{j,t},
]

the interaction may also require an instrument such as:

[
h_{i,t}Z_{j,t}.
]

The exclusion restriction is demanding.

The instrument must not alter the characteristic gradient through another channel.

Instrumental-variable estimates should therefore be used only where the institutional mechanism and exclusion argument are unusually strong.

---

# 17. Fixed-Effects Designs

Panel data permit control for time-invariant unobserved heterogeneity.

A two-way fixed-effects model is:

[
Y_{i,j,t+1}
===========

\alpha
+
\beta h_{i,j,t}
+
\gamma I_{j,t}
+
\delta h_{i,j,t}I_{j,t}
+
\mu_i
+
\tau_t
+
\varepsilon_{i,j,t+1}.
]

Actor fixed effects help control for stable unobserved actor traits.

Institutional-unit fixed effects help control for stable jurisdictional characteristics.

However, fixed effects do not solve:

* time-varying confounding;
* anticipatory behavior;
* endogenous institutional change;
* measurement error;
* selective migration.

They should not be treated as a complete identification strategy.

---

# 18. Multilevel Models

Institutional Translation often involves actors nested within institutions.

A multilevel model may allow the characteristic gradient to vary across institutional units:

[
Y_{i,j}
=======

\alpha_j
+
\beta_j h_{i,j}
+
\varepsilon_{i,j},
]

with:

[
\alpha_j
========

a_0+a_1I_j+u_j,
]

and:

[
\beta_j
=======

b_0+b_1I_j+v_j.
]

The parameter:

[
b_1
]

tests whether institutional conditions explain variation in the characteristic gradient.

Multilevel models are especially useful when institutional variation is continuous and observed across many units.

They remain observational unless supported by a causal design.

---

# 19. Actor Sorting

Actors may select into institutions based on characteristics or expected returns.

Examples include:

* migration;
* school choice;
* occupational selection;
* firm selection;
* jurisdiction shopping;
* organizational exit.

Sorting may generate apparent translation effects even when institutions do not causally alter the mapping.

Potential responses include:

* using predetermined residence or assignment;
* restricting analysis to nonmovers;
* modeling institutional choice;
* inverse-probability weighting;
* matching;
* boundary designs;
* instrumental variables;
* exploiting reforms affecting existing populations;
* comparing intent-to-treat exposure.

Results should be reported both with and without samples affected by sorting where feasible.

---

# 20. Institutional Endogeneity

Institutions may arise in response to prior outcomes or characteristic distributions.

A jurisdiction may adopt a policy because:

* inequality increased;
* labor-market returns changed;
* political coalitions shifted;
* economic shocks occurred;
* administrative capacity improved.

Potential responses include:

* pre-reform trend analysis;
* institutional histories;
* political-process controls;
* lagged institutional measures;
* reform-specific identification;
* synthetic controls;
* matched reform cases;
* process tracing.

Lagging an institutional variable does not by itself resolve endogeneity.

---

# 21. Measurement Error

Measurement error in (h), (I), or both may distort the translation coefficient.

Institutional variables are especially vulnerable because formal indices may poorly measure effective practice.

Recommended responses include:

* triangulating multiple measures;
* validating indices against administrative evidence;
* separating formal and effective institutions;
* using direct procedural measures;
* testing alternative operationalizations;
* estimating measurement models where appropriate;
* reporting sensitivity to institutional coding decisions.

Interaction terms can magnify measurement error.

Accordingly, reliability of the underlying variables should be assessed before interpreting the interaction.

---

# 22. Formal versus Effective Institutions

Where data permit, estimate:

[
Y_{i,j,t+1}
===========

\alpha
+
\beta h_{i,j,t}
+
\gamma_F I_{j,t}^{F}
+
\gamma_E I_{j,t}^{E}
+
\delta_Fh_{i,j,t}I_{j,t}^{F}
+
\delta_Eh_{i,j,t}I_{j,t}^{E}
+
\varepsilon_{i,j,t+1}.
]

This design asks whether translation is associated with:

* written rules;
* actual enforcement;
* both.

A strong implementation-gap prediction is:

[
|\delta_E|>|\delta_F|
]

where formal rules are weakly enforced.

This inequality is not universal and should be treated as a scope-dependent hypothesis.

---

# 23. Mechanism Identification

A credible mechanism test should examine whether institutional exposure changes an intermediate channel.

The first-stage mechanism equation is:

[
O_{i,j,t}
=========

a
+
b h_{i,j,t}
+
c I_{j,t}
+
d h_{i,j,t}I_{j,t}
+
u_{i,j,t}.
]

The final outcome equation is:

[
Y_{i,j,t+1}
===========

q
+
rO_{i,j,t}
+
s h_{i,j,t}
+
v_{i,j,t+1}.
]

Evidence is stronger when:

1. the institution changes the intermediate opportunity;
2. the change differs by actor characteristic;
3. the intermediate opportunity predicts the final outcome;
4. the reduced-form translation effect decreases when the mechanism is modeled;
5. alternative channels are less consistent with the evidence.

Formal mediation analysis should be used cautiously when intermediate variables are themselves endogenous.

---

# 24. Distributional Estimation

Mean effects may conceal important translation patterns.

The empirical strategy should consider:

## Variance Effects

Does the institution change the dispersion of outcomes conditional on characteristics?

## Quantile Effects

Does translation differ across the outcome distribution?

[
Q_\tau(Y\mid h,I,X)
===================

\alpha_\tau
+
\beta_\tau h
+
\gamma_\tau I
+
\delta_\tau hI
+
\lambda_\tau^\top X.
]

## Tail Risks

Does the institution affect the probability of extreme loss or advantage?

## Mobility

Does the institution change movement across outcome ranks or states?

## Transition Matrices

Does the institutional regime alter:

[
\Pr(A_{i,t+1}=k\mid A_{i,t}=j)?
]

Distributional analysis should remain tied to the proposed translation mechanism.

---

# 25. Dynamic Empirical Strategy

Dynamic translation should be investigated only after static translation has been established.

A minimum dynamic model is:

[
Y_{i,t+1}
=========

\alpha
+
(\beta+\delta I_t)h_{i,t}
+
\gamma I_t
+
\varepsilon_{i,t+1},
]

[
h_{i,t+1}
=========

\rho_hh_{i,t}
+
\eta Y_{i,t+1}
+
\nu_{i,t+1}.
]

The central dynamic parameter is:

[
\kappa(I_t)
===========

\rho_h+\eta(\beta+\delta I_t).
]

Empirical work should test whether persistence differs across institutional environments.

---

# 26. Dynamic Panel Challenges

Including lagged outcomes or characteristics creates bias in short panels.

Potential approaches include:

* long panels with actor fixed effects;
* system or difference generalized method of moments;
* bias-corrected estimators;
* structural estimation;
* state-space models;
* cohort-level analysis;
* simulation-based methods.

Estimator choice should follow the data-generating process.

Dynamic-panel techniques should not substitute for a credible institutional identification strategy.

---

# 27. Institutional Feedback Estimation

Institutional feedback may be represented as:

[
I_{j,t+1}
=========

\rho_I I_{j,t}
+
\psi Z(A_{j,t+1})
+
\theta^\top W_{j,t}
+
\omega_{j,t+1}.
]

Here:

[
Z(A_{j,t+1})
]

is a property of the outcome allocation, such as inequality, mobility, or concentration.

Estimating:

[
\psi
]

does not establish a feedback mechanism by itself.

The study must address:

* political mediation;
* common shocks;
* institutional anticipation;
* reverse causation;
* slow-moving institutional variables.

Historical process evidence may be essential.

---

# 28. Intervention Decay

To test whether institutional effectiveness erodes over time, estimate time-specific translation effects:

[
\delta_k
]

for periods (k) following reform.

Intervention decay is suggested when:

[
|\delta_{k+1}|<|\delta_k|
]

after an initial effect, provided the decline is not caused by:

* composition change;
* differential attrition;
* measurement drift;
* unrelated later reforms;
* changing macroeconomic conditions.

Mechanism evidence should examine whether actors or organizations altered behavior in ways that reduced effective implementation.

---

# 29. Path Dependence

Path dependence can be tested by comparing systems with similar current institutions but different institutional histories.

A model may include:

[
J_{j,t}
=======

\sum_{s=0}^{K}
\rho^s I_{j,t-s},
]

where (J_{j,t}) represents accumulated institutional history.

Then estimate:

[
Y_{i,j,t+1}
===========

\Phi(h_{i,j,t};I_{j,t},J_{j,t})
+
\varepsilon_{i,j,t+1}.
]

Evidence for path dependence requires more than a significant lag.

The historical variable should correspond to a plausible mechanism such as:

* accumulated precedent;
* organizational routine;
* durable expectations;
* institutional trust;
* prior investment.

---

# 30. Survivorship and Attrition

Institutional exposure may affect whether actors remain observable.

Let:

[
R_{i,t+1}=1
]

indicate continued observation.

The selection equation is:

[
\Pr(R_{i,t+1}=1)
================

\mathcal{R}
\left(
h_{i,t},
I_t,
Y_{i,t+1},
X_{i,t}
\right).
]

Potential responses include:

* attrition analysis;
* inverse-probability weighting;
* bounds;
* selection models;
* administrative follow-up;
* inclusion of exits as substantive outcomes;
* competing-risk models.

Excluding nonsurvivors may systematically understate institutional penalties or overstate institutional rewards.

---

# 31. Heterogeneous Effects

The baseline theory already predicts heterogeneity by actor characteristic.

Further heterogeneity should be introduced cautiously.

Potential moderators include:

* group identity;
* location;
* organizational type;
* institutional implementation quality;
* initial outcome position;
* exposure duration.

A higher-order interaction such as:

[
h\times I\times G
]

should be included only when a specific differential translation mechanism is proposed.

Searching broadly across many subgroups risks producing uninterpretable or spurious findings.

---

# 32. Functional-Form Testing

The empirical model should compare:

* linear;
* threshold;
* nonlinear;
* regime-specific;
* probabilistic;
* saturating;
* distributional forms.

Selection should be based on:

* institutional rules;
* out-of-sample prediction;
* residual diagnostics;
* fit criteria;
* interpretability;
* counterfactual plausibility;
* mechanism evidence.

Flexible machine-learning methods may help detect heterogeneity but should not replace an interpretable theoretical specification.

A useful sequence is:

1. estimate the theory-specified model;
2. use flexible methods diagnostically;
3. identify systematic deviations;
4. revise the functional form transparently;
5. validate the revised model in separate data.

---

# 33. Standard Errors and Dependence

Errors may be correlated within:

* institutions;
* jurisdictions;
* cohorts;
* time periods;
* reform groups.

Standard errors should be clustered at the level at which institutional treatment varies.

Where the number of clusters is small, consider:

* small-sample corrections;
* randomization inference;
* wild-cluster bootstrap;
* permutation tests.

Serial correlation should be assessed in longitudinal policy designs.

---

# 34. Statistical Power

Interaction effects commonly require more statistical power than main effects.

Power calculations should consider:

* variation in (h);
* variation in (I);
* correlation between (h) and (I);
* institutional cluster count;
* treatment timing;
* measurement reliability;
* expected magnitude of (\delta).

A study that is underpowered to distinguish translation from an additive institutional effect should not interpret a null interaction as strong falsification.

---

# 35. Missing Data

Missingness may depend on characteristics, institutions, or outcomes.

The study should report:

* missingness rates;
* missingness by institutional regime;
* missingness by actor characteristic;
* whether missingness changes after reform;
* how missing data are handled.

Potential methods include:

* multiple imputation;
* weighting;
* bounds;
* sensitivity analysis;
* explicit missingness indicators where substantively justified.

Complete-case analysis may distort translation estimates when institutions affect data availability.

---

# 36. Robustness Standards

A credible Institutional Translation result should survive several tests.

## Measurement Robustness

Alternative definitions of:

* actor characteristics;
* institutions;
* outcomes;
* implementation.

## Sample Robustness

Alternative:

* populations;
* time windows;
* institutional units;
* mover restrictions;
* trimming rules.

## Functional Robustness

Alternative:

* linear and nonlinear forms;
* thresholds;
* regime specifications;
* transformations.

## Identification Robustness

Alternative:

* comparison groups;
* treatment timing;
* matching procedures;
* control sets;
* fixed effects.

## Inference Robustness

Alternative:

* clustering levels;
* randomization inference;
* bootstrap methods.

Robustness should evaluate plausible alternatives rather than generate an indiscriminate specification search.

---

# 37. Placebo Tests

Potential placebo tests include:

* false reform dates;
* unaffected outcomes;
* characteristics that should not be translated by the institution;
* populations not exposed to the institutional rule;
* neighboring but unaffected jurisdictions;
* pre-reform pseudo-treatments.

A convincing translation result should not appear where the proposed institutional mechanism does not operate.

---

# 38. Negative Controls

Negative-control outcomes and exposures can help detect confounding.

## Negative-Control Outcome

An outcome that shares confounders with the target outcome but should not be affected by the institution.

## Negative-Control Exposure

An institutional measure correlated with the treatment institution but not expected to affect the selected translation channel.

Negative controls should be selected from substantive institutional knowledge, not only statistical convenience.

---

# 39. Sensitivity Analysis

Where unobserved confounding remains possible, the study should quantify how strong an omitted variable would need to be to eliminate the translation estimate.

Possible approaches include:

* omitted-variable sensitivity;
* Rosenbaum-style bounds;
* coefficient-stability analysis;
* partial (R^2) measures;
* bounding under alternative selection assumptions.

Sensitivity analysis does not prove identification, but it clarifies the fragility of the result.

---

# 40. External Validity

Institutional Translation is expected to be scope dependent.

A finding from one domain should not automatically generalize to:

* another institution;
* another characteristic;
* another outcome;
* another historical period;
* another population.

External validity should be assessed through:

* replication across institutional settings;
* comparative case studies;
* meta-analysis;
* transportability analysis;
* explicit scope-condition testing.

Variation across cases may support the theory if it follows predicted institutional differences.

Unexplained instability weakens the theory.

---

# 41. Historical Evidence

Some translation mechanisms may be best studied historically.

Historical empirical strategy may combine:

* legal records;
* administrative documents;
* archival data;
* institutional timelines;
* cohort outcomes;
* quantitative reconstruction;
* process tracing;
* comparative case analysis.

Historical work should establish:

1. what formal rule changed;
2. how implementation changed;
3. which actors were affected;
4. which translation channel changed;
5. whether characteristic gradients changed;
6. whether alternative explanations fit the sequence better.

Historical evidence is especially valuable for examining path dependence, institutional feedback, and implementation divergence.

---

# 42. Mixed-Methods Strategy

Quantitative and qualitative evidence should be treated as complementary.

## Quantitative Evidence

Estimates:

* whether translation occurs;
* its magnitude;
* its distribution;
* its temporal pattern.

## Qualitative Evidence

Clarifies:

* how institutions operate;
* why formal and effective rules differ;
* how actors adapt;
* which political mechanisms drive change;
* whether the proposed channel is credible.

A mixed-method design is particularly useful when the statistical interaction is identifiable but the mechanism is not directly measured.

---

# 43. Predictive Evaluation

Institutional Translation should improve more than in-sample fit.

Models should be compared on:

* out-of-sample prediction;
* prediction across institutional regimes;
* prediction after reform;
* prediction for actor subgroups defined in advance;
* counterfactual calibration.

A complex translation model that does not improve prediction or mechanism clarity over an additive benchmark should be reconsidered.

---

# 44. Counterfactual Validation

The model should evaluate whether predicted institutional counterfactuals are consistent with observed reforms or comparable institutional environments.

For an actor with characteristic (h_i):

[
\widehat{Y}_i(I^{CF})
=====================

\widehat{\Phi}(h_i;I^{CF}).
]

The counterfactual change is:

[
\widehat{\Delta Y}_i
====================

## \widehat{Y}_i(I^{CF})

\widehat{Y}_i(I^{O}).
]

Validation should ask whether:

* predicted changes match historical reform effects;
* the model extrapolates outside observed support;
* institutional alternatives are feasible;
* actor behavior would remain unchanged;
* equilibrium effects are ignored.

Counterfactual estimates should be accompanied by explicit uncertainty and scope limitations.

---

# 45. Model Comparison

Institutional Translation should be compared with:

## Characteristics-Only Model

[
Y=f(H).
]

## Additive Institutional Model

[
Y=f(H)+g(I).
]

## Selection Model

Apparent institutional differences arise from actor sorting.

## Contextual Model

Broad environmental factors produce both institutional and outcome differences.

## Translation Model

[
Y=\Phi(H;I).
]

Comparison should consider:

* causal credibility;
* explanatory fit;
* predictive performance;
* mechanism evidence;
* parsimony;
* counterfactual usefulness.

No single criterion is sufficient.

---

# 46. Evidence Classification

Results should be classified rather than described simply as supportive or nonsupportive.

## Strong Support

Evidence shows:

* credible institutional variation;
* a stable translation effect;
* a measurable mechanism;
* benchmark improvement;
* robust and plausible counterfactuals.

## Moderate Support

Evidence shows a robust conditional institutional effect but incomplete mechanism identification or limited causal leverage.

## Suggestive Evidence

Evidence shows associations consistent with translation but substantial endogeneity or measurement concerns remain.

## Inconclusive Evidence

The study lacks adequate power, variation, measurement, or identification.

## Contradictory Evidence

Credible designs repeatedly show no translation effect or support a simpler competing explanation.

Null evidence should not be classified as falsification when the study is underpowered or institutionally uninformative.

---

# 47. Minimum Empirical Standard

A first-generation Institutional Translation study should include:

1. one clearly measured actor characteristic;
2. one bounded institutional condition;
3. one observable outcome;
4. one proposed translation channel;
5. characteristics-only and additive benchmarks;
6. an explicit interaction or equivalent conditional mapping;
7. a credible identification argument;
8. marginal-effect interpretation;
9. robustness and placebo tests;
10. stated scope and falsification conditions.

This minimum standard is preferable to a large model containing many weakly measured concepts.

---

# 48. Recommended First Study Design

The preferred first application should involve:

* a discrete institutional reform;
* actors already present before the reform;
* one predetermined characteristic;
* an observable intermediate opportunity;
* one final outcome;
* repeated observations before and after reform;
* a credible untreated comparison group.

The preferred design is therefore a mechanism-aware event study or difference-in-differences design.

A generic specification is:

[
Y_{i,j,t}
=========

\alpha
+
\beta h_{i,j}
+
\sum_{k\neq -1}\gamma_kD_{j,t}^{k}
+
\sum_{k\neq -1}
\delta_k
\left(
h_{i,j}D_{j,t}^{k}
\right)
+
\mu_j
+
\tau_t
+
\varepsilon_{i,j,t}.
]

The empirical objective is to determine whether the reform changes the characteristic gradient and whether the proposed institutional channel changes at the same time.

---

# 49. Research Workflow

Each empirical project should follow this sequence.

## Step 1 — Define the Mechanism

Specify:

[
h
\rightarrow
O
\rightarrow
Y
]

under institution (I).

## Step 2 — Define the System Boundary

Identify actors, institutions, period, and population.

## Step 3 — Construct Benchmarks

Estimate characteristics-only and additive institutional models.

## Step 4 — Establish Institutional Variation

Explain why institutional exposure is plausibly exogenous or conditionally ignorable.

## Step 5 — Estimate Translation

Estimate the conditional mapping and marginal effects.

## Step 6 — Test the Channel

Examine intermediate opportunities, assignments, or enforcement.

## Step 7 — Examine Distributional Effects

Assess mean, variance, mobility, and tails where relevant.

## Step 8 — Examine Dynamics

Test persistence, implementation lag, adaptation, or feedback only after static translation is supported.

## Step 9 — Conduct Robustness and Falsification Tests

Evaluate competing explanations directly.

## Step 10 — Classify the Evidence

Report whether results provide strong, moderate, suggestive, inconclusive, or contradictory evidence.

---

# 50. Reproducibility

Each empirical study should preserve:

* raw-data provenance;
* data-construction documentation;
* institutional coding decisions;
* analysis scripts;
* model specifications;
* exclusion decisions;
* robustness results;
* negative findings;
* replication instructions.

Exploratory analyses should be distinguished from confirmatory tests.

Where feasible, core hypotheses and primary specifications should be preregistered before final estimation.

---

# 51. Failure Conditions

The empirical strategy should be reconsidered when:

* the institutional variable does not correspond to a specific mechanism;
* the actor characteristic is measured after institutional exposure;
* institutional and actor variation cannot be separated;
* the comparison group lacks credibility;
* treatment timing is ambiguous;
* actor sorting dominates exposure;
* the interaction is underpowered;
* the mechanism is inferred only from statistical significance;
* functional complexity exceeds available data;
* counterfactuals require unsupported extrapolation.

In these cases, narrowing the question is preferable to adding controls or complexity.

---

# 52. Development Judgment

Institutional Translation is empirically testable, but the required standard is more demanding than estimating a conventional interaction term.

A credible test must establish that:

[
\frac{\partial Y}{\partial h}
]

changes with institutional exposure and that the change corresponds to a substantively identifiable institutional process.

The empirical strategy should therefore combine:

* precise institutional measurement;
* nested benchmark models;
* credible variation;
* marginal-effect analysis;
* mechanism evidence;
* distributional analysis;
* dynamic testing where justified;
* explicit falsification.

The strongest first studies will be narrow.

They will examine one institutional change, one actor characteristic, one translation channel, and one outcome.

This constraint is not a limitation of the research program.

It is the discipline required to determine whether Institutional Translation is a distinct and empirically useful mechanism.

---

# Current Priority

The next artifact should identify historical settings in which Institutional Translation can be examined with substantial institutional variation and observable before-and-after consequences:

`Research-Lab/Social-Systems/Formalization/Institutional-Translation/06-Historical-Cases.md`

That document should screen candidate cases according to:

* clarity of institutional change;
* availability of pre-change and post-change evidence;
* observability of actor characteristics;
* observability of the translation channel;
* suitability for benchmark comparison;
* potential selection and endogeneity problems;
* value for static and dynamic testing.
