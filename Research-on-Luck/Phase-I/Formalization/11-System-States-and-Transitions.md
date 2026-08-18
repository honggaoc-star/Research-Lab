# System States and Transitions

## Purpose

This document formalizes system state, environmental state, interaction, transition, and trajectory without assuming equilibrium or a single modeling language.

The notation is deliberately minimal. It can support state-space, stochastic, causal, network, dynamic-system, or agent-based formulations when those tools fit the research question.

---

## 1. Focal System and Boundary

Let (i) identify the focal system and (t) identify time.

The analytical boundary determines what is represented as internal to the system and what is represented as environment. Because the boundary is chosen for a question, it must be stated before variables are classified.

A model should identify:

- focal system;
- level of analysis;
- internal components;
- relevant environment;
- boundary-changing processes;
- and time horizon.

The same entity may be a system in one model and part of the environment in another.

---

## 2. System State

Let:

[
X_i(t)
]

denote the state of system (i) at time (t).

The state may contain components such as:

[
X_i(t)={K_i(t),R_i(t),I_i(t),N_i(t),Q_i(t)},
]

where:

- (K_i(t)) represents capabilities;
- (R_i(t)) represents resources;
- (I_i(t)) represents information;
- (N_i(t)) represents relationships or network position;
- (Q_i(t)) represents relevant rules, routines, or internal structure.

These components are illustrative. A bounded model should include only what the question requires.

A state is not an outcome. “Outcome” adds an evaluative standpoint and horizon.

---

## 3. Environmental State

Let:

[
E_i(t)
]

denote the environmental state relevant to system (i) at time (t).

It may include institutions, other systems, technologies, markets, physical conditions, knowledge, and resource distributions.

The subscript (i) emphasizes that relevance may differ across systems. Two systems can inhabit a common larger environment while facing different effective environments because of location, access, institutions, or networks.

---

## 4. Interaction State

Let:

[
J_i(t)
]

denote the interaction state or set of interactions connecting system (i) to its environment at time (t).

Interactions may include exposure, communication, exchange, conflict, cooperation, experimentation, observation, or intervention.

A useful decomposition is:

[
J_i(t)=h(X_i(t),E_i(t),A_i(t),eta_i(t)),
]

where:

- (A_i(t)) is action or non-action by the system;
- (eta_i(t)) represents uncertainty affecting interaction;
- and (h) is an interaction rule.

This distinguishes an environmental event from system-specific exposure.

---

## 5. Transition Function

A general system transition is:

[
X_i(t+1)=Fig(X_i(t),E_i(t),J_i(t),arepsilon_i(t)ig),
]

where:

- (F) is the system transition function;
- and (arepsilon_i(t)) represents unresolved variation in the transition.

The environment may also change:

[
E_i(t+1)=Gig(E_i(t),X_i(t),J_i(t),
u_i(t)ig),
]

where:

- (G) is the environmental transition function;
- and (
u_i(t)) represents unresolved environmental variation.

Together these equations permit mutual change rather than treating the environment as permanently exogenous.

---

## 6. Exogenous and Endogenous Change

A change is **exogenous relative to a model** when it is generated outside the modeled system and transition structure.

A change is **endogenous** when it is produced within that structure.

Exogeneity is therefore model-relative, not an absolute property of an event.

An institutional decision may be exogenous to an individual model but endogenous to a political-system model. A technological shock may be external to a firm but generated within an innovation ecosystem.

Models should state which processes are excluded, because omitted endogeneity can be mistaken for luck.

---

## 7. Trajectory

The trajectory of system (i) over horizon (T) is:

[
mathcal{T}_i(T)={X_i(0),X_i(1),ldots,X_i(T)}.
]

A trajectory includes the sequence of states, not only the terminal state (X_i(T)).

Two systems may arrive at similar terminal states through different trajectories, with different costs, capabilities, vulnerabilities, and future opportunity landscapes.

Luck attribution should therefore specify whether the relevant consequence concerns:

- an immediate transition;
- persistence across several transitions;
- a changed branch;
- or a transformed regime.

---

## 8. Transition Sequences and Branching

Under uncertainty, a state may have several accessible successors.

Let:

[
Gamma_i(X_i(t),E_i(t))
]

denote the set of feasible next states for system (i).

A realized next state is one member of that set. Unrealized states remain analytically relevant when they were feasible ex ante.

Counterfactual comparison should be restricted to states in a defensible feasible set. It should not treat every imaginable alternative as equally available.

---

## 9. Nested Systems and Levels

Suppose an individual (i) is nested within organization (o), which is nested within institution (m).

Their states may be represented separately:

[
X_i(t),quad X_o(t),quad X_m(t).
]

Cross-level transition terms should be explicit rather than folded into a single residual.

For example, an institutional rule can constrain organizational action, while accumulated organizational behavior can feed back into institutional reform.

Aggregation is not neutral. System-level resilience may coexist with unequal component-level loss.

---

## 10. Time and Multiple Scales

Processes operate on different clocks:

- exposure may be immediate;
- learning may be gradual;
- institutional change may be slow;
- feedback may be delayed;
- regime transition may be discontinuous.

A model may use discrete time, continuous time, or event time. The choice should match the mechanism.

Using a common time index does not imply that all processes move at the same speed.

---

## 11. Equilibrium Is Optional

The architecture does not assume that systems converge to equilibrium.

Relevant behaviors include:

- temporary stability;
- oscillation;
- persistent change;
- path dependence;
- threshold transition;
- adaptation;
- lock-in;
- and transformation.

Equilibrium analysis may be useful for a bounded question, but it should not be treated as the default description of adaptive systems under uncertainty.

---

## 12. Boundary Change and Transformation

The system boundary itself may change through merger, fragmentation, institutionalization, coalition, or reclassification.

Let (B_i(t)) denote the boundary rule for system (i). Then transformation may include:

[
B_i(t+1)
eq B_i(t).
]

This is more than movement within a fixed state space. It may change what counts as system, environment, component, or interaction.

Models of regime change should state whether variables change within a fixed architecture or whether the architecture itself changes.

---

## 13. Luck Sequence

The state-transition representation supports:

- **Luck Potential:** several feasible transitions exist under uncertainty;
- **Luck Realization:** interaction produces one trajectory branch;
- **Luck Attribution:** the realized branch is evaluated relative to feasible alternatives and prior control.

Luck is not (arepsilon_i(t)) or (
u_i(t)). Those terms may contain stochastic variation, measurement error, omitted mechanisms, or misspecification.

---

## 14. Minimum State-Transition Specification

A bounded model should state:

1. system and boundary;
2. environmental scope;
3. state variables;
4. interaction variables;
5. time scale;
6. transition functions;
7. uncertainty structure;
8. feasible alternatives;
9. endogenous and exogenous components;
10. feedback;
11. outcome horizon;
12. and revision conditions.

---

## Conclusion

System states describe configurations at times; transitions describe change; trajectories preserve sequence.

By representing system, environment, and interaction jointly, the framework can study uncertain and recursive change without reducing luck to a shock term or assuming equilibrium, fixed boundaries, or isolated outcomes.
