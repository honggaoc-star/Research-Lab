# Opportunity Dynamics

## Purpose

This document formalizes opportunity and constraint as dynamic relationships between a system and its environment.

An opportunity is not an external object that guarantees benefit. It is a feasible system–environment relationship that could expand accessible trajectories relative to an objective and horizon. A constraint restricts feasible interactions or trajectories.

---

## 1. Opportunity Landscape

For system \(i\) at time \(t\), let:

\[
\Omega_i(t)
\]

denote its opportunity landscape: the structured set of potentially relevant interactions and transitions.

The landscape depends on:

\[
\Omega_i(t)=\Phi\big(X_i(t),E_i(t),J_i(t),U_i(t)\big),
\]

where \(X_i(t)\) is system state, \(E_i(t)\) is environmental state, \(J_i(t)\) is the interaction structure, \(U_i(t)\) is uncertainty, and \(\Phi\) maps these conditions into a set of possible opportunities.

The landscape is system-relative and time-dependent.

---

## 2. Constraints and Feasible Sets

Let \(\mathcal{A}_i(t)\) be the actions imaginable to system \(i\), and let \(\mathcal{F}_i(t)\) be the subset feasible under current constraints:

\[
\mathcal{F}_i(t)\subseteq \mathcal{A}_i(t).
\]

Constraints may arise from resources, information, capability, institutions, physical conditions, timing, network position, or other systems.

Feasibility does not imply recognition, choice, or success.

---

## 3. Opportunity Stages

For opportunity \(o\), define indicators:

- \(P_{io}(t)\): potential relation exists;
- \(A_{io}(t)\): opportunity is accessible;
- \(R_{io}(t)\): opportunity is recognized;
- \(C_{io}(t)\): system commits to pursuit;
- \(Z_{io}(t)\): opportunity is realized.

Each indicator equals 1 when the condition holds and 0 otherwise.

A common sequence is:

\[
P\rightarrow A\rightarrow R\rightarrow C\rightarrow Z.
\]

The sequence is not universal. Recognition may precede access; pursuit may create the opportunity; realization may be partial.

---

## 4. Recognition

Recognition is not equivalent to opportunity existence.

Let:

\[
R_{io}(t)=r\big(I_i(t),K_i(t),S_i(t),o,\xi_i(t)\big),
\]

where \(I_i(t)\) is information, \(K_i(t)\) is relevant capability, \(S_i(t)\) is search or attention, \(o\) identifies the opportunity, \(\xi_i(t)\) represents uncertainty in recognition, and \(r\) is a recognition rule.

This permits missed and misrecognized opportunities without assuming that non-recognition proves incapacity.

---

## 5. Pursuit and Realization

Let \(a_{io}(t)\) represent action taken toward opportunity \(o\).

\[
Z_{io}(t+1)=z\big(a_{io}(t),X_i(t),E_i(t),J_i(t),\epsilon_{io}(t)\big),
\]

where \(z\) is the realization function and \(\epsilon_{io}(t)\) captures unresolved variation.

Capability affects realization, but environmental response, timing, institutions, and interaction also matter.

A realized opportunity does not prove unique capability. A failed pursuit does not prove that pursuit was unreasonable ex ante.

---

## 6. Foreclosure and Expiration

Let \(D_{io}(t)=1\) mean opportunity \(o\) is foreclosed or expired for system \(i\).

Foreclosure may result from delay, prior commitments, resource depletion, institutional prohibition, competitors, technological change, or path-dependent transition.

Once foreclosed, an opportunity may disappear from the feasible set even if it remains conceptually imaginable.

---

## 7. Unrealized Opportunity

An unrealized opportunity satisfies, at minimum:

\[
P_{io}(t)=1,\qquad Z_{io}(t+1)=0.
\]

This broad category includes inaccessible, unrecognized, rejected, unsuccessfully pursued, interrupted, and foreclosed opportunities.

Empirical work should not aggregate these mechanisms without justification. Evidence for unrealized opportunity is often weaker than evidence for realization, so models should express uncertainty rather than false precision.

---

## 8. Counterfactual Trajectories

Let \(\mathcal{T}_i^{a}\) denote the trajectory under action or interaction \(a\).

\[
\Delta_i(a,b)=V(\mathcal{T}_i^{a})-V(\mathcal{T}_i^{b}),
\]

where \(a\) and \(b\) are feasible alternatives, \(V\) is an explicitly defined evaluation function, and \(\Delta_i(a,b)\) is their evaluated difference.

The contrast is meaningful only if both alternatives were defensibly feasible from the ex ante state. Counterfactual models should state identification assumptions and uncertainty.

---

## 9. Opportunity Creation and Migration

Systems may change their own landscapes:

\[
\Omega_i(t+1)=H\big(\Omega_i(t),X_i(t+1),E_i(t+1),J_i(t+1)\big).
\]

Search, innovation, coordination, and institutional change may create opportunities rather than merely reveal them.

Opportunity may migrate between systems through diffusion, imitation, competition, regulation, or changing access. One system’s realization may enable, constrain, or foreclose another’s.

---

## 10. Timing and Windows

Let \([t_o^{open},t_o^{close}]\) represent the interval during which opportunity \(o\) is accessible.

A system may possess capability before complementary conditions exist or acquire resources after the window closes. Timing should be modeled as a relationship among system state, environment, and opportunity window.

---

## 11. Institutions and Distribution

Institutions affect which opportunities enter feasible sets, who receives information, access conditions, costs, permissions, risk allocation, and returns.

Opportunity landscapes are distributed, not uniform. Formal models should distinguish aggregate opportunity growth from distribution across systems.

---

## 12. Luck Potential, Realization, and Attribution

- **Luck Potential:** uncertainty exists across feasible opportunity and constraint relations.
- **Luck Realization:** interaction selects or produces a trajectory, leaving alternatives unrealized.
- **Luck Attribution:** the realized trajectory is evaluated relative to ex ante feasibility, capability, intention, and control.

Luck is not represented by the opportunity indicator or the realization residual alone.

---

## 13. Measurement Bridge

Future measurement should seek indicators for potential, access, recognition, pursuit, realization, foreclosure, constraints, timing, and counterfactual feasibility.

Observed success records realization but often leaves earlier stages unobserved. Case design should seek contemporaneous evidence where possible.

---

## Conclusion

Opportunity dynamics formalizes a sequence from potential through access, recognition, pursuit, realization, or foreclosure.

The framework keeps opportunity relational, preserves unrealized alternatives, and makes clear that capability, institutions, timing, interaction, and uncertainty jointly shape trajectories.
