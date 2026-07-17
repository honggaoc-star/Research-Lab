# State Space

## Dynamic Social Systems Research Program

**Repository**

`Research-Lab/Social-Systems/Framework/State-Space.md`

**Version**

2.0

**Status**

Conceptual Architecture

**Role**

Defines the general conceptual state architecture of the Dynamic Social Systems framework.

**Related Documents**

- `Research-Lab/Social-Systems/README.md`
- `Research-Lab/Social-Systems/Framework/Four-Foundational-Axioms.md`
- `Research-Lab/Social-Systems/Framework/Transition-Mechanisms.md`
- `Research-Lab/Social-Systems/Framework/Law-of-Motion.md`
- `Research-Lab/Social-Systems/Framework/Transition-Operator.md`
- `Research-Lab/Social-Systems/Formalization/03-Minimum-State-Vector.md`

---

# Purpose

This document defines the conceptual state space of the Dynamic Social Systems framework.

Its purpose is to identify the kinds of information required to characterize a social system at a given time and to distinguish the system's current condition from the mechanisms, parameters, shocks, and decisions that govern its subsequent evolution.

This document remains deliberately conceptual.

It does not specify a unique mathematical state vector, empirical measurement model, or transition equation. Those tasks belong to the Formalization and Evidence modules.

The corresponding mathematical implementation is developed in:

`Research-Lab/Social-Systems/Formalization/03-Minimum-State-Vector.md`

---

# 1. System Boundary

A social system is a bounded collection of interacting individuals, households, organizations, institutions, and networks that allocate opportunities, resources, influence, responsibilities, and risks through decentralized decision-making and recursive feedback.

The framework is scale-flexible.

Possible system boundaries include:

- organizations;
- communities;
- cities;
- regions;
- nations;
- groups of nations;
- civilizations.

Every application must define its system boundary before specifying state variables.

The classification of a variable as internal, external, endogenous, or exogenous depends upon that boundary.

---

# 2. Definition of a State

A state is the smallest collection of current conditions sufficient, in principle, to characterize the system for the purpose of analyzing its subsequent evolution.

A state is descriptive rather than causal.

It answers:

> What is the condition of the system now?

It does not, by itself, answer:

> Why did the system reach this condition, or how will it change?

Those questions belong to transition mechanisms and the Law of Motion.

The conceptual state should contain information that is:

- temporally located;
- relevant to future evolution;
- distinct from the mechanisms that update it;
- not merely a restatement of historical events;
- capable, at least in principle, of empirical approximation.

---

# 3. Conceptual State Domains

The framework organizes the state space into five broad domains.

These domains are conceptual categories rather than fixed mathematical coordinates. Individual applications may use only a subset of them.

## A. Development State

The Development State describes the level of socially relevant capabilities, resources, and outcomes.

Illustrative dimensions include:

- income;
- productivity;
- wealth;
- education;
- health;
- technological capability;
- infrastructure;
- organizational capacity.

Development refers to the level or expected value of social outcomes, not their distribution.

---

## B. Allocation State

The Allocation State describes how opportunities, capabilities, influence, risks, and outcomes are distributed across actors and groups.

Illustrative dimensions include:

- income distribution;
- wealth distribution;
- access to education;
- access to health;
- political influence;
- mobility;
- exposure to risk;
- distribution of opportunity.

Inequality is one observable property of the Allocation State.

The Allocation State is broader than any single inequality measure.

---

## C. Institutional State

The Institutional State describes the formal and informal structures governing social interaction.

Illustrative components include:

- property-rights systems;
- legal institutions;
- political institutions;
- administrative capacity;
- organizational rules;
- enforcement capacity;
- institutional legitimacy;
- adaptive capacity;
- norms and conventions.

Institutions may function both as state variables and as components of transition mechanisms.

The distinction depends upon whether the research question concerns their current configuration or their causal operation.

---

## D. Capability State

The Capability State describes the productive, cognitive, organizational, and adaptive capacities of actors within the system.

Illustrative components include:

- human capital;
- knowledge;
- skills;
- technological competence;
- organizational capability;
- decision capacity;
- learning capacity.

Capabilities may exist at individual, organizational, institutional, or system-wide levels.

---

## E. Coordination State

The Coordination State describes the system's capacity for interaction, cooperation, communication, and collective action.

Illustrative components include:

- social trust;
- network structure;
- cooperation;
- information flows;
- collective-action capacity;
- coordination norms;
- conflict intensity;
- coalition structure.

Coordination is distinct from institutions, although institutional arrangements strongly influence it.

---

# 4. Cross-Cutting State Properties

Several properties cut across all five domains.

## Observable and Latent Components

Some state variables are directly observable.

Examples include:

- population;
- income;
- employment;
- educational attainment;
- public expenditure.

Other state variables are latent.

Examples include:

- beliefs;
- expectations;
- perceived legitimacy;
- social cohesion;
- institutional credibility;
- perceived fairness.

Latent components may be approximated through:

- surveys;
- behavioral indicators;
- archival evidence;
- composite indices;
- statistical latent-variable models.

---

## Individual and Aggregate Components

The state space may contain variables measured at different levels.

Examples include:

- individual endowments;
- household resources;
- organizational capability;
- regional infrastructure;
- national institutions.

Aggregation should not be assumed to preserve all relevant information.

Where heterogeneity matters, distributions or group-specific states may be required rather than averages alone.

---

## Stocks, Flows, and Memory

The conceptual state may include:

- **stocks** — accumulated quantities such as wealth, human capital, or infrastructure;
- **flows** — current rates such as income, migration, investment, or policy expenditure;
- **memory variables** — persistent historical effects such as legal precedent, institutional reputation, organizational routines, or inherited trust.

Flows belong in the state only when their current levels affect future evolution independently of the stocks they modify.

Memory variables belong in the state when past events continue to affect future transitions and cannot be reconstructed adequately from other current variables.

---

# 5. Endogenous and Exogenous Conditions

The framework distinguishes between endogenous state variables and exogenous conditions.

## Endogenous Conditions

Endogenous conditions are generated or modified within the system.

Examples include:

- institutional arrangements;
- allocation;
- political coalitions;
- organizational structures;
- capabilities;
- beliefs;
- social trust.

## Exogenous Conditions

Exogenous conditions originate outside the chosen system boundary.

Examples include:

- natural disasters;
- foreign geopolitical shocks;
- external technological breakthroughs;
- pandemics;
- climatic events.

The same variable may be endogenous in one application and exogenous in another.

For example, technological change may be exogenous to a local organization but endogenous to a national innovation system.

---

# 6. State Space and Admissibility

Let the conceptual state space be denoted by:

\[
\Omega.
\]

Not every theoretically imaginable combination of state variables belongs to the admissible state space.

A state may be excluded because it is:

- physically impossible;
- logically inconsistent;
- institutionally infeasible;
- incompatible with accounting identities;
- outside the defined system boundary;
- inconsistent with required probability or population constraints.

Formal implementations must therefore define an admissible state space:

\[
\mathbf{X}_t \in \Omega.
\]

The Transition Operator must map admissible states into admissible states.

---

# 7. State versus Mechanism

The distinction between state and mechanism is central.

A state variable describes a condition.

A transition mechanism describes a process that changes one or more conditions.

Examples:

| Concept | State interpretation | Mechanism interpretation |
|---|---|---|
| Institutions | current institutional configuration | institutional translation or reform |
| Trust | current level of trust | trust formation or erosion |
| Human capital | accumulated capability stock | education and learning |
| Political power | current distribution of influence | coalition formation or political feedback |
| Technology | current technological capability | innovation or diffusion |

The same broad concept may appear in both categories, but it must not play both roles ambiguously within a single formal model.

---

# 8. Development and Allocation

Version 2 adopts the following conceptual position:

- Development and Allocation remain distinct analytical dimensions of the social state.
- Neither is assumed to be reducible to the other.
- Their mathematical status may vary across bounded formal models.
- A particular application may treat one as a state variable and the other as a derived observable, but that choice must be justified.

The general framework therefore preserves both dimensions while allowing formal implementations to impose parsimony.

This avoids prematurely assuming either that:

- development is always fundamental; or
- development is always emergent.

The appropriate representation is application-dependent and subject to empirical validation.

---

# 9. Criteria for State Inclusion

A candidate variable should be included in a bounded state representation only if it satisfies the following criteria.

1. **Current-condition criterion**  
   It describes the present condition of the system rather than merely a causal process.

2. **Predictive-relevance criterion**  
   It contributes information relevant to subsequent evolution.

3. **Non-redundancy criterion**  
   It cannot be reconstructed adequately from the remaining state variables.

4. **Conceptual-clarity criterion**  
   Its meaning and role are clearly defined.

5. **Boundary-consistency criterion**  
   It belongs inside the chosen system boundary.

6. **Empirical-access criterion**  
   It can, at least in principle, be observed, proxied, or estimated.

7. **Parsimony criterion**  
   Its inclusion improves explanatory or predictive adequacy enough to justify the additional complexity.

Variables failing these criteria should be treated as:

- parameters;
- mechanisms;
- shocks;
- observables;
- derived quantities;
- or excluded variables.

---

# 10. Relationship to Formalization

This document defines the conceptual architecture.

The formal problem is narrower:

> What is the smallest state vector sufficient to generate the dynamics of a specified model?

That problem is addressed in:

`Research-Lab/Social-Systems/Formalization/03-Minimum-State-Vector.md`

A formal state vector may be written as:

\[
\mathbf{X}_t
=
\begin{bmatrix}
X_{1,t} \\
X_{2,t} \\
\vdots \\
X_{n,t}
\end{bmatrix}
\in \Omega.
\]

The formal model must justify:

- each included component;
- each excluded conceptual domain;
- the dimension of the vector;
- the relationship between latent and observed variables;
- the treatment of shocks and parameters;
- the sufficiency of the state for dynamic evolution.

The conceptual framework is intentionally broader than any one formal state vector.

---

# 11. Relationship to the Law of Motion

The state space defines what the system is at time \(t\).

The Law of Motion defines how that state changes:

\[
\mathbf{X}_{t+1}
=
\mathbf{F}
\left(
\mathbf{X}_t,
\boldsymbol{\theta},
\boldsymbol{\varepsilon}_t
\right).
\]

The state vector, structural parameters, and shocks must remain conceptually distinct.

- \(\mathbf{X}_t\) describes the current system state;
- \(\boldsymbol{\theta}\) describes structural characteristics treated as fixed or slowly varying within the model;
- \(\boldsymbol{\varepsilon}_t\) describes external disturbances or innovations;
- \(\mathbf{F}\) describes the transition process.

---

# 12. Relationship to Evidence

The Evidence module translates conceptual state domains into measurable indicators.

Relevant tasks include:

- identifying observable proxies;
- estimating latent variables;
- documenting data provenance;
- aligning units and time scales;
- testing whether candidate variables add explanatory or predictive value;
- determining whether omitted domains create systematic model failure.

Evidence may justify:

- adding a state component;
- removing a redundant component;
- narrowing a definition;
- treating a variable as a mechanism rather than a state;
- changing the system boundary.

---

# 13. Scope and Limitations

The conceptual state space is not intended to:

- enumerate every socially relevant variable;
- prescribe one universal state vector;
- eliminate application-specific judgment;
- assume complete observability;
- guarantee empirical identification;
- replace transition mechanisms or causal analysis.

Its role is to provide a disciplined conceptual architecture from which bounded formal models can be derived.

---

# 14. Working Principle

The objective is not to maximize the dimensionality of the state space.

The objective is to preserve enough information to explain and predict system evolution while minimizing conceptual and mathematical complexity.

Accordingly:

> The Framework defines the broad conceptual domains of state; each formal model must identify the minimum sufficient subset required for its specific research question.

---

# 15. Version 2 Revision Summary

Version 2:

- reclassifies the document as conceptual architecture rather than a Phase III validation draft;
- distinguishes the conceptual state space from the formal Minimum State Vector;
- removes obsolete dependencies on `Framework-Validation.md`;
- preserves Development and Allocation as distinct analytical dimensions without fixing their role in every formal model;
- adds stocks, flows, and memory variables;
- clarifies state-versus-mechanism ambiguity;
- defines admissibility and state-space constraints;
- adds explicit links to Formalization, Evidence, and the Law of Motion;
- replaces the former future-document roadmap with the repository's current 
