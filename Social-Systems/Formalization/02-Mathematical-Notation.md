# Mathematical Notation

## Standard Mathematical Language for the Dynamic Social Systems Framework

**Repository**

`Research-Lab/Social-Systems/Formalization/02-Mathematical-Notation.md`

**Status**

Working Draft

**Phase**

VI — Formalization

**Purpose**

To establish a consistent mathematical notation for the Dynamic Social Systems framework that will be used throughout all formal models, simulations, empirical specifications, and future working papers.

---

# 1. Purpose of This Document

One of the most common problems in large theoretical projects is notation drift.

Different models gradually begin using different symbols for the same concept, making comparison difficult and increasing unnecessary complexity.

The purpose of this document is to establish a common mathematical language before individual models are developed.

The notation defined here should remain stable whenever possible.

Future models may introduce additional symbols when required, but existing definitions should not be changed without strong justification.

---

# 2. General Principles

The notation should satisfy several principles.

## Simplicity

Use familiar mathematical symbols whenever possible.

---

## Consistency

A symbol should represent one concept throughout the research program.

---

## Hierarchy

General concepts receive simple notation.

Application-specific variables receive subscripts or superscripts.

---

## Expandability

The notation should accommodate future applications without redefining existing symbols.

---

## Domain Independence

Symbols should represent abstract concepts rather than application-specific quantities.

For example,

(A_t)

represents **allocation**, not income inequality specifically.

---

# 3. Time

Time is represented by

[
t=0,1,2,\ldots
]

Discrete time is adopted initially because:

* institutional changes are episodic;
* policy changes occur at identifiable intervals;
* historical comparison is naturally period based;
* empirical panel data are generally discrete.

Continuous-time models may be developed later when appropriate.

---

# 4. Social System

The complete social system is represented by

[
S_t
]

where

(S_t)

denotes the complete state of the social system at time (t).

This is the highest-level object in the framework.

Every formal model specifies only part of (S_t).

---

# 5. State Variables

The social state consists of several broad categories.

Rather than fixing the exact mathematical structure now, we define the principal notation.

| Symbol | Meaning                                    |
| ------ | ------------------------------------------ |
| (H_t)  | Heterogeneity                              |
| (I_t)  | Institutions                               |
| (D_t)  | Development                                |
| (A_t)  | Allocation                                 |
| (B_t)  | Behavioral state                           |
| (P_t)  | Political state                            |
| (N_t)  | Network structure                          |
| (L_t)  | Institutional learning / adaptive capacity |
| (E_t)  | External conditions or shocks              |

These variables are conceptual state categories.

The exact contents of each variable depend on the application.

---

# 6. Heterogeneity

Heterogeneity is represented by

[
H_t
]

At the individual level,

[
H_{i,t}
]

represents the heterogeneous characteristics of actor (i).

Possible components include:

* capability;
* education;
* health;
* wealth;
* preferences;
* identity;
* information;
* social position;
* networks;
* inherited resources.

Future models may decompose

[
H_{i,t}
]

into explicit vectors.

---

# 7. Institutions

Institutions are represented by

[
I_t
]

Institutions include:

* legal systems;
* property rights;
* political rules;
* governance structures;
* organizational rules;
* social norms.

Institutions perform two functions.

First,

they are components of the current state.

Second,

they influence future transitions.

This dual role is fundamental to the framework.

---

# 8. Development

Development is represented by

[
D_t
]

Development refers to the level or expected value of selected social outcomes.

Examples include:

* productivity;
* income;
* health;
* education;
* innovation;
* capability.

The precise interpretation depends upon the application.

---

# 9. Allocation

Allocation is represented by

[
A_t
]

Allocation describes the distribution of:

* opportunities;
* capabilities;
* income;
* wealth;
* authority;
* risk;
* social outcomes.

Important clarification:

Allocation is **not** identical to inequality.

Inequality is an observable property of allocation.

---

# 10. Behavioral State

Behavioral conditions are represented by

[
B_t
]

Behavior includes:

* expectations;
* norms;
* strategic adaptation;
* learning;
* role activation;
* decision rules.

Behavior changes through time.

It is not assumed to be fixed.

---

# 11. Political State

Political conditions are represented by

[
P_t
]

Possible components include:

* political influence;
* coalition structure;
* voting behavior;
* representation;
* policy priorities.

Political variables influence institutions and are themselves affected by outcomes.

---

# 12. Network Structure

Networks are represented by

[
N_t
]

Networks include:

* social networks;
* organizational connections;
* information networks;
* economic relationships.

Network structure may influence:

* opportunity;
* diffusion;
* innovation;
* mobility.

---

# 13. Institutional Learning

Institutional adaptive capacity is represented by

[
L_t
]

Possible components include:

* information acquisition;
* error detection;
* decision revision;
* implementation;
* learning;
* legitimacy.

Later models may decompose

[
L_t
]

into several variables.

---

# 14. External Conditions

External influences are represented by

[
E_t
]

Examples include:

* technological change;
* war;
* pandemics;
* natural disasters;
* demographic change;
* international conditions.

External conditions are not assumed to be controllable by the system.

---

# 15. State Vector

The complete conceptual state may be written as

[
S_t=
(H_t,
I_t,
D_t,
A_t,
B_t,
P_t,
N_t,
L_t,
E_t)
]

This is intentionally broad.

Individual models will employ only subsets of this vector.

---

# 16. Transition Operator

The general transition operator is represented by

[
\mathcal{T}
]

The law of motion becomes

[
S_{t+1}
=======

\mathcal{T}
(
S_t,
M_t,
\Theta_t
)
]

where

* (M_t) represents active mechanisms;
* (\Theta_t) represents structural parameters.

This notation intentionally separates:

* current state;
* mechanisms;
* parameters.

---

# 17. Transition Mechanisms

Transition mechanisms are represented collectively by

[
M_t
]

Possible mechanisms include:

* Institutional Translation;
* recursive feedback;
* behavioral adaptation;
* political aggregation;
* network amplification;
* institutional learning.

Future models will specify individual mechanisms explicitly.

---

# 18. Structural Parameters

Structural parameters are represented by

[
\Theta
]

These include relatively stable characteristics such as:

* geography;
* constitutional constraints;
* technology;
* cultural persistence;
* long-run demographic conditions.

Parameters may evolve in later models but are treated as comparatively stable initially.

---

# 19. Transition Probabilities

When the system is represented discretely,

transition probabilities are written

[
P_{jk,t}
]

where

[
P_{jk,t}
========

Pr(S_{t+1}=k
\mid
S_t=j)
]

Unlike conventional Markov models,

the Dynamic Social Systems framework allows

[
P_{jk,t}
]

to evolve.

---

# 20. Actor Index

Individual actors are indexed by

[
i=1,\ldots,N
]

Organizations may later receive index

[
o
]

Institutions may receive index

[
r
]

These indices remain reserved.

---

# 21. Observables

Observable quantities receive

[
Y
]

Examples include

[
Y_t
]

or

[
Y_{i,t}
]

Examples:

* income;
* wealth;
* educational attainment;
* mobility;
* inequality indices;
* trust;
* productivity.

Observables are not identical to state variables.

They measure aspects of the state.

---

# 22. Shocks

Unexpected events are represented by

[
\varepsilon_t
]

This notation is reserved for stochastic disturbances.

These differ from

[
E_t
]

where

(E_t)

represents the broader external environment.

---

# 23. Functions

Several standard functions are reserved.

| Function      | Meaning                         |
| ------------- | ------------------------------- |
| (\mathcal{T}) | Transition operator             |
| (f(\cdot))    | General functional relationship |
| (g(\cdot))    | Alternative relationship        |
| (h(\cdot))    | Learning or updating function   |

These symbols should remain generic.

---

# 24. Positive and Normative Notation

Positive analysis concerns

[
S_t
]

Normative evaluation is represented separately.

Let

[
W(S_t)
]

denote a welfare evaluation applied to the current state.

This notation preserves the distinction between

* describing society;
* evaluating society.

The framework should not embed welfare judgments into the transition equations unless explicitly intended.

---

# 25. Reserved Symbols

The following symbols should remain reserved.

| Symbol        | Reserved Meaning       |
| ------------- | ---------------------- |
| (S)           | Social state           |
| (H)           | Heterogeneity          |
| (I)           | Institutions           |
| (D)           | Development            |
| (A)           | Allocation             |
| (B)           | Behavioral state       |
| (P)           | Political state        |
| (N)           | Networks               |
| (L)           | Institutional learning |
| (E)           | External environment   |
| (M)           | Mechanisms             |
| (\Theta)      | Structural parameters  |
| (Y)           | Observables            |
| (W)           | Welfare evaluation     |
| (\mathcal{T}) | Transition operator    |
| (\varepsilon) | Random shocks          |

These meanings should remain unchanged throughout the research program whenever possible.

---

# 26. Relationship to Future Documents

This notation serves as the common language for:

* `03-Minimum-State-Vector.md`
* Institutional Translation
* Endogenous Transition Dynamics
* Adaptive Intervention
* Integrated Dynamic Model

Future documents should extend this notation rather than replace it.

---

# 27. Future Extensions

The notation intentionally leaves room for:

* continuous-time models;
* agent-based simulations;
* network representations;
* stochastic processes;
* Bayesian updating;
* game-theoretic interaction;
* optimization models;
* control-theoretic representations.

Such extensions should preserve the meanings established here.

---

# Preliminary Conclusion

The purpose of this document is not to formalize the Dynamic Social Systems framework itself, but to establish a stable mathematical language for future formal development.

The notation introduced here separates:

* states;
* mechanisms;
* parameters;
* observables;
* welfare evaluation.

This distinction mirrors the conceptual architecture established during the Framework and Validation phases and provides a common mathematical foundation for every subsequent model in the Formalization phase.

The next step is to determine which components of the conceptual state are actually required for the first generation of formal models.

Accordingly, the next document is:

`03-Minimum-State-Vector.md`
