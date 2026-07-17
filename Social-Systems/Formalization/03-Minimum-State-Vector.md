# Minimum State Vector

## Defining the Minimum Sufficient Representation of the Dynamic Social Systems Framework

**Repository**

`Research-Lab/Social-Systems/Formalization/03-Minimum-State-Vector.md`

**Status**

Working Draft

**Phase**

VI — Formalization

**Purpose**

To identify the minimum set of state variables required to construct the first generation of formal models within the Dynamic Social Systems framework.

---

# 1. Purpose

The conceptual framework contains many important elements.

These include:

* heterogeneous actors;
* institutions;
* development;
* allocation;
* behavior;
* politics;
* networks;
* adaptive capacity;
* external conditions.

However, not every conceptual component should appear in every mathematical model.

The objective of this document is therefore not to define the complete social system.

Instead, it asks:

> **What is the smallest state representation capable of explaining the transition of interest?**

This principle is referred to as the **Minimum Sufficient State Vector (MSSV).**

---

# 2. Conceptual State versus Mathematical State

The Dynamic Social Systems framework distinguishes between two different concepts.

## Conceptual State

The conceptual framework recognizes many aspects of a social system.

A convenient representation is

[
S_t^{Conceptual}
================

(H_t,I_t,D_t,A_t,B_t,P_t,N_t,L_t,E_t).
]

This serves as the ontology of the framework.

It identifies what kinds of things may matter.

---

## Mathematical State

A mathematical model uses only those variables necessary for a specific research question.

Thus,

[
S_t^{Model}
\subseteq
S_t^{Conceptual}.
]

The mathematical state is therefore always a subset of the conceptual state.

This distinction is fundamental.

The framework is broad.

The models are intentionally narrow.

---

# 3. Principle of Minimum Sufficiency

A state variable should appear in a model only if removing it changes the model's predictions or explanatory content.

Variables should **not** be included merely because they are conceptually relevant.

The objective is scientific parsimony rather than conceptual completeness.

---

# 4. Candidate State Categories

The framework currently recognizes the following conceptual categories.

| Symbol | Category                        | Always Required? |
| ------ | ------------------------------- | ---------------: |
| (H)    | Heterogeneity                   |               No |
| (I)    | Institutions                    |               No |
| (D)    | Development                     |               No |
| (A)    | Allocation                      |               No |
| (B)    | Behavioral State                |               No |
| (P)    | Political State                 |               No |
| (N)    | Networks                        |               No |
| (L)    | Institutional Adaptive Capacity |               No |
| (E)    | External Environment            |               No |

No variable is universally mandatory.

Its inclusion depends on the mechanism under study.

---

# 5. Minimum State for the First Formalization Target

The Validation phase identified **Endogenous Transition Dynamics** as the strongest candidate for initial formalization.

For that purpose, the following state appears sufficient.

[
S_t^{(1)}
=========

(H_t,
I_t,
A_t,
E_t).
]

where

* (H_t) represents actor heterogeneity;
* (I_t) represents institutions;
* (A_t) represents allocation;
* (E_t) represents external conditions.

Notice what is absent.

* Development
* Politics
* Networks
* Adaptive Capacity

These are not assumed to be unimportant.

They are temporarily omitted because they are not required for the first reduced model.

---

# 6. Why Allocation Is Included

Allocation is retained because the framework studies transition dynamics.

Transitions occur **through** an allocation.

Without an allocation state, mobility, persistence, and inequality cannot be defined.

Allocation therefore becomes one of the core state variables of the initial model.

---

# 7. Why Development Is Deferred

Development is conceptually important.

However, it is not required to explain whether transition probabilities change.

Development becomes essential when studying:

* growth;
* productivity;
* innovation;
* welfare;
* long-run capability accumulation.

Those belong to later models.

---

# 8. Why Politics Is Deferred

Political feedback is central to the complete framework.

Nevertheless, it represents one mechanism by which institutions evolve.

The first generation of models treats institutions as given.

Political dynamics therefore remain outside the initial state vector.

They will later become endogenous.

---

# 9. Why Networks Are Deferred

Networks influence:

* information;
* opportunity;
* diffusion;
* cumulative advantage.

However, they introduce substantial mathematical complexity.

The first models should determine whether the framework functions without explicit network representation.

Network effects can later be introduced as an extension.

---

# 10. Why Adaptive Capacity Is Deferred

Institutional Adaptive Capacity is one of the most interesting concepts developed during Validation.

Nevertheless, it is a higher-order institutional property.

The first models can reasonably assume fixed institutional response.

Adaptive Capacity should therefore become a parameter or extension before becoming a full state variable.

---

# 11. Reduced State Representation

The first formalization therefore begins with

[
S_t^{(1)}
=========

(H_t,
I_t,
A_t,
E_t).
]

This should be viewed as

> the minimum sufficient state vector for the first generation of Dynamic Social Systems models.

---

# 12. Relationship to Transition Dynamics

The transition operator becomes

[
S_{t+1}^{(1)}
=============

\mathcal{T}
(
H_t,
I_t,
A_t,
E_t
).
]

Notice that the operator no longer depends on the complete conceptual state.

Only variables required by the research question are retained.

---

# 13. State Reduction Principle

Future models should follow the same discipline.

Instead of asking

> "What else should be added?"

they should ask

> "What can still be removed without losing explanatory power?"

The burden of proof lies with adding variables, not omitting them.

---

# 14. Multiple State Vectors

Different research questions require different minimum states.

Examples include:

### Institutional Translation

[
S_t
===

(H_t,I_t,E_t).
]

---

### Transition Dynamics

[
S_t
===

(H_t,I_t,A_t,E_t).
]

---

### Development–Allocation Co-evolution

[
S_t
===

(H_t,I_t,D_t,A_t,E_t).
]

---

### Adaptive Intervention

[
S_t
===

(H_t,I_t,B_t,L_t,E_t).
]

Thus, the Dynamic Social Systems framework does **not** possess a single universal mathematical state vector.

Instead, it possesses a common conceptual ontology from which application-specific minimum state vectors are derived.

---

# 15. Scientific Advantages

The Minimum Sufficient State Vector provides several advantages.

## Parsimony

Models remain interpretable.

---

## Identifiability

Fewer variables reduce estimation problems.

---

## Comparability

Different models can be compared by examining which variables are added or removed.

---

## Scalability

The framework can grow without forcing every model to become increasingly complex.

---

## Falsifiability

Variables can be shown to be unnecessary.

This strengthens rather than weakens the framework.

---

# 16. Relationship to Future Models

The Minimum State Vector serves as the foundation for every formal model developed in this research program.

Future work should begin with the smallest possible representation and introduce additional state variables only when:

* a mechanism cannot otherwise be represented;
* predictions demonstrably improve;
* historical or empirical evidence requires additional structure.

The conceptual framework therefore remains stable while mathematical models vary according to the scientific question being addressed.

---

# Preliminary Conclusion

The Dynamic Social Systems framework distinguishes between a **conceptual ontology** and a **mathematical state representation**.

The conceptual ontology identifies the full range of entities and processes relevant to social evolution.

The mathematical state vector is intentionally narrower and should contain only those variables necessary to explain the transition under investigation.

This principle of **minimum sufficient representation** becomes one of the central methodological commitments of the Formalization phase.

It ensures that future models remain tractable, comparable, and empirically testable while preserving the broader conceptual integrity of the Dynamic Social Systems framework.

The next stage of formalization is to operationalize the first major mechanism:

**Institutional Translation**.
