# Relationship Types

## Purpose

This document establishes a working taxonomy for formal relationships in the **Research on Luck** architecture.

Concepts are analytical nodes. Relationships connect those nodes and express claims that can be clarified, bounded, and tested. A list of concepts is not yet a theory; theory begins when the project specifies how concepts are related and under what conditions.

The taxonomy contains five relationship types:

1. Constitutive
2. Causal
3. Enabling
4. Constraining
5. Feedback

These types are analytical roles, not mutually exclusive natural categories. The same pair of concepts may be related differently in different models, at different levels, or over different time horizons.

---

## 1. Formal Objects

A bounded model should distinguish:

- **Variable** — a quantity or category that can take different values.
- **State** — the configuration of relevant variables at a specified time.
- **Event** — a temporally located change.
- **Relationship** — a specified connection among formal objects.
- **Mechanism** — a process explaining how a relationship produces change.
- **Assumption** — a condition accepted provisionally within the model.
- **Hypothesis** — a relationship claim exposed to evaluation.
- **Prediction** — an observable implication conditional on assumptions and initial conditions.

A relationship is not a mechanism by itself. “Resources affect adaptation” is a relationship claim; a mechanism must specify how resources change search, learning, coordination, or response.

---

## 2. Constitutive Relationships

A constitutive relationship states that one concept forms part of the definition or composition of another.

If concept (A) is constitutive of concept (B), then (B) cannot be represented as intended without (A).

Examples:

- system boundary is constitutive of what counts as environment;
- access is constitutive of an accessible opportunity;
- successive states are constitutive of a trajectory;
- an evaluative standpoint is constitutive of “good” or “bad” luck.

Constitutive relationships do not automatically imply temporal causation. Defining a trajectory through states does not mean the concept of state causes the trajectory.

Formalization should identify whether a relationship is definitional, compositional, or classificatory and should avoid testing definitions as if they were causal hypotheses.

---

## 3. Causal Relationships

A causal relationship states that changing (A), under specified conditions, changes the distribution or value of (B).

A general representation is:

[
B_{t+1}=f(A_t,C_t,U_t),
]

where:

- (B_{t+1}) is the later value of the affected quantity;
- (A_t) is the candidate causal input;
- (C_t) represents relevant conditions;
- (U_t) represents unresolved or unobserved influences;
- and (f) is a transition relationship.

This notation does not prove causality. Identification requires additional assumptions, design, and evidence.

Causal claims should state:

- focal system and level;
- temporal order;
- intervention or contrast;
- mechanism;
- boundary conditions;
- relevant alternative explanations;
- and expected observable implications.

Luck should not appear as an undefined causal variable.

---

## 4. Enabling Relationships

An enabling relationship states that (A) makes a process, interaction, or transition feasible without being sufficient to produce it.

Examples include:

- information enabling recognition;
- infrastructure enabling interaction;
- legal permission enabling access;
- resources enabling experimentation;
- network connection enabling diffusion.

One useful representation is a feasibility indicator:

[
F_i(a,t)=1,
]

where (F_i(a,t)=1) means action or transition (a) is feasible for system (i) at time (t). An enabling condition may change (F_i) from 0 to 1 while leaving the actual choice or result unresolved.

Enabling relationships should not be mistaken for deterministic causes. An enabled opportunity may remain unrecognized, unchosen, or unsuccessfully pursued.

---

## 5. Constraining Relationships

A constraining relationship states that (A) limits feasible interactions, actions, or transitions.

Let (mathcal{A}_i(t)) denote the set of actions accessible to system (i) at time (t). A constraint may reduce this set:

[
mathcal{A}_i^{,C}(t)subseteq mathcal{A}_i(t).
]

Constraints can be physical, informational, institutional, resource-based, temporal, political, or capability-related.

Constraints are not necessarily harmful. Standards, safeguards, and commitment devices may restrict action while supporting coordination or resilience. Evaluation requires a system, objective, and horizon.

Enabling and constraining relationships may coexist. An institution may enable market exchange while constraining admissible behavior.

---

## 6. Feedback Relationships

A feedback relationship exists when the consequence of a process changes conditions that affect later iterations of that process.

A minimal recursive representation is:

[
X_{t+1}=f(X_t,E_t), qquad E_{t+1}=g(E_t,X_{t+1}),
]

where:

- (X_t) is the system state;
- (E_t) is the environmental state;
- (f) describes system transition;
- and (g) describes environmental change partly produced by the system.

Feedback may be:

- reinforcing;
- countervailing;
- stabilizing;
- destabilizing;
- delayed;
- cross-level;
- or nonlinear.

“Positive” and “negative” feedback refer to direction, not desirability.

Feedback claims should specify the loop, time delay, sign, scale, saturation, and stopping conditions.

---

## 7. Relationships Across the Architecture

| Layer connection | Typical relationship roles |
| --- | --- |
| Primitives → Derived conditions | Constitutive, enabling, constraining |
| Derived conditions → Capabilities | Enabling, constraining, causal |
| Capabilities → Dynamic processes | Enabling, causal |
| Dynamic processes → Long-term effects | Causal, feedback |
| Long-term effects → Outcome evaluation | Constitutive, evidentiary |
| Outcomes → later system/environment | Feedback |

This table is a guide, not a rule. A concept may serve as a state in one model and a mechanism in another.

---

## 8. Boundary Conditions

A relationship should state where it is expected to hold.

Boundary conditions may include:

- level of analysis;
- system type;
- environmental regime;
- uncertainty structure;
- institutional setting;
- resource range;
- network configuration;
- time horizon;
- and threshold conditions.

A relationship that holds in one domain should not be promoted as universal merely because analogous language appears elsewhere.

---

## 9. Relationship-Specification Template

Each formal relationship should document:

1. **Name**
2. **Type** — constitutive, causal, enabling, constraining, feedback
3. **Source node**
4. **Target node**
5. **Focal system**
6. **Level and boundary**
7. **Time index and horizon**
8. **Initial conditions**
9. **Mechanism**
10. **Uncertainty**
11. **Moderators and constraints**
12. **Expected direction or form**
13. **Alternative explanations**
14. **Observable implications**
15. **Failure or revision conditions**
16. **Evidence status**

This template separates clarity from confirmation. A precisely specified relationship may still be unsupported.

---

## 10. Relationship to Luck

Luck is not an additional relationship type.

The attribution of luck follows when consequential variation in a system’s state, accessible opportunities, constraints, relationships, or trajectory arises through interaction under uncertainty and is not fully determined by prior intention, capability, or action.

Formal models should therefore represent:

- the system;
- environment;
- interaction;
- uncertainty;
- relevant relationships;
- and trajectory change.

Luck is then an interpretation of the modeled sequence, not a free-standing force or residual error term.

---

## Conclusion

The relationship taxonomy turns the conceptual architecture into a set of bounded claims.

Constitutive relationships define or compose concepts. Causal relationships describe change. Enabling and constraining relationships alter feasible transitions. Feedback relationships make consequences recursive.

The taxonomy is useful only if it improves formal clarity, empirical discrimination, and revision. It remains a working structure rather than a validated general theory.
