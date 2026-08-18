# Feedback, Path Dependence, and Regime Change

## Purpose

This document formalizes recursive change: feedback, amplification, attenuation, cumulative advantage and disadvantage, path dependence, thresholds, lock-in, resilience, and regime transition.

These concepts describe different dynamic structures and should not be used interchangeably.

---

## 1. Feedback

Feedback exists when a consequence changes conditions that influence later instances of the process.

\[
X_{t+1}=F(X_t,E_t), \qquad E_{t+1}=G(E_t,X_{t+1}).
\]

Here \(X_t\) is system state, \(E_t\) is environmental state, and \(F\) and \(G\) are transition functions.

Feedback may operate within a system, between system and environment, across systems, or across levels.

---

## 2. Reinforcing and Countervailing Feedback

A feedback loop is **reinforcing** when an initial change increases subsequent change in the same direction.

It is **countervailing** when later effects oppose the initial change.

The labels do not mean desirable and undesirable.

A local representation is:

\[
X_{t+1}=X_t+\alpha X_t,
\]

where \(\alpha>0\) represents local reinforcement and \(\alpha<0\) represents local countervailing adjustment.

Real systems usually contain bounds, delays, saturation, competing loops, and changing parameters.

---

## 3. Dynamic Outcomes

### Amplification

A difference grows over successive transitions.

### Attenuation

A difference decreases.

### Stabilization

A state or difference persists within a bounded range.

### Reversal

The direction or evaluative sign changes.

### Dissipation

The effect becomes negligible at the selected horizon.

### Transformation

The process changes the structure that determines future transitions.

These outcomes should be defined relative to a baseline, system, variable, and horizon.

---

## 4. Cumulative Advantage and Disadvantage

Let \(D_{ij}(t)\) be the difference between systems \(i\) and \(j\).

Cumulative advantage exists when:

\[
|D_{ij}(t+1)|>|D_{ij}(t)|
\]

through a mechanism that links earlier advantage to later access, resources, information, or returns.

The inequality alone does not identify the mechanism. Common shocks, selection, measurement change, or initial heterogeneity may produce similar patterns.

Cumulative disadvantage may occur through restricted opportunity, adverse exposure, resource loss, exclusion, or weakened response capacity.

---

## 5. Path Dependence

A process is path-dependent when earlier states or transitions affect later feasible alternatives or transition rules, beyond what is captured by the current aggregate state.

In shorthand:

\[
P(X_{t+1}\mid X_t,\mathcal{H}_t)\neq P(X_{t+1}\mid X_t),
\]

where \(\mathcal{H}_t\) is relevant history.

Historical sequence alone is not sufficient. The model must identify memory, increasing returns, sunk costs, coordination, learning, institutionalization, or another mechanism carrying history forward.

---

## 6. Thresholds and Nonlinearity

A threshold exists when transition behavior changes after a variable crosses a critical value \(c\).

\[
X_{t+1}=
\begin{cases}
F_1(X_t,E_t), & X_t<c,\\
F_2(X_t,E_t), & X_t\ge c.
\end{cases}
\]

Thresholds may concern adoption, coordination, legitimacy, resource sufficiency, network reach, or institutional stress.

Empirical evidence should distinguish genuine thresholds from arbitrary categorization.

---

## 7. Lock-In

Lock-in occurs when a path becomes difficult to leave even when alternatives appear attractive.

Mechanisms include:

- switching costs;
- complementary investments;
- standards;
- network effects;
- legal commitments;
- political power;
- learned routines;
- and foreclosed alternatives.

Lock-in does not imply permanence or inefficiency. Both claims require additional standards and evidence.

---

## 8. Resilience

Resilience concerns a system’s capacity to absorb disturbance, recover, adapt, or transform while preserving specified functions or identity.

Different forms include:

- resistance;
- recovery;
- adaptation;
- and transformation.

A system may appear resilient at an aggregate level while imposing concentrated losses on components. Models should specify what is preserved, for whom, and over what horizon.

---

## 9. State Change and Regime Change

A **state change** occurs within a stable transition structure.

A **regime change** alters transition rules, boundaries, governing parameters, or the set of feasible states.

Let \(\theta_t\) represent the regime parameters of transition function \(F\):

\[
X_{t+1}=F(X_t,E_t;\theta_t).
\]

A regime transition occurs when:

\[
\theta_{t+1}\neq\theta_t
\]

in a substantively meaningful way.

Not every large outcome is a regime change. The model should show that the structure of future transitions has changed.

---

## 10. Endogenous Regime Transition

Regime change may emerge from accumulated interaction:

\[
\theta_{t+1}=H(\theta_t,X_t,E_t,J_t).
\]

This representation permits recursive feedback, nonlinear adjustment, institutional translation, and adaptation to alter the rules of the system.

Exogenous shocks may trigger transitions, but whether they do so depends on prior state, thresholds, institutions, and response.

---

## 11. Selection and Survivorship

Selection changes which systems, practices, or observations remain visible.

Observed persistence may reflect:

- capability;
- environmental fit;
- timing;
- inherited position;
- power;
- institutional protection;
- or favorable exposure.

Survival does not establish superiority. Formal models should represent the selection process and, where possible, compare non-survivors and unrealized alternatives.

---

## 12. Luck Across Recursive Dynamics

A small uncertain exposure may be amplified through feedback. An adverse exposure may be attenuated by institutions. An initially favorable path may create lock-in or fragility. A missed opportunity may become permanently foreclosed.

Luck attribution should therefore identify:

- initial variation;
- exposure;
- feedback mechanism;
- persistence;
- alternative paths;
- and evaluation horizon.

The initial event alone is not the full explanation.

---

## 13. Measurement Bridge

Future measurement should seek evidence for:

- loop direction;
- delay;
- saturation;
- historical memory;
- transition thresholds;
- switching costs;
- changing feasible sets;
- regime parameters;
- and selection into observation.

Time-series resemblance to feedback or path dependence is not sufficient without mechanism evidence.

---

## Conclusion

Feedback makes consequences recursive. Path dependence makes history structurally relevant. Thresholds and lock-in alter accessibility. Resilience describes persistence, recovery, adaptation, or transformation. Regime change alters the transition structure itself.

Separating these concepts supports stronger explanations of how contingent variation becomes amplified, suppressed, reversed, or stabilized into long-term trajectories.
