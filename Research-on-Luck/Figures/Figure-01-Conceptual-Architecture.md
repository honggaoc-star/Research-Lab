# Figure 1 — Conceptual Architecture of Systems Under Uncertainty

> **Version:** 2.1  
> **Status:** Canonical Markdown specification; PNG regeneration pending.  
> **Interpretation:** Layers organize analytical roles. Arrows indicate possible relationships, not a universal causal or temporal sequence.

## Working Primitives

| System | Environment | Interaction | Uncertainty |
|---|---|---|---|
| Bounded focal configuration | Relevant conditions outside the boundary | Relations among systems, components, and environments | Unresolved states, transitions, or outcomes relative to an information set |

The four primitives are coequal starting points. None is derived from another by the figure.

## Layered Architecture

~~~mermaid
flowchart TB
    P["Layer 0: Working Primitives"]
    D["Layer 1: Derived Conditions"]
    C["Layer 2: System Capabilities"]
    R["Layer 3: Dynamic Processes"]
    L["Layer 4: Long-Term Effects"]
    E["Layer 5: Outcome Evaluation"]

    P --> D
    D --> C
    C --> R
    R --> L
    L --> E
    E -. "feedback and revised boundaries" .-> P
    R -. "cross-layer feedback" .-> D
~~~

Solid arrows provide a reading order, not a claim that every process follows all layers. Feedback, enabling, constraining, constitutive, and causal relationships may connect any relevant layers.

## Layer Contents

| Layer | Illustrative constructs |
|---|---|
| Working Primitives | System, Environment, Interaction, Uncertainty |
| Derived Conditions | Opportunity, Constraint, Exposure, Information, Resources, Risk, Contingency |
| System Capabilities | Perception, Search, Learning, Coordination, Adaptive Capacity |
| Dynamic Processes | Recognition, Pursuit, Response, Adaptation, Discovery, Innovation, Selection, Realization |
| Long-Term Effects | Feedback, Path Dependence, Accumulation, Resilience, Transformation, Regime Change |
| Outcome Evaluation | Outcome, Reference, Counterfactual, Unrealized Alternative, Luck Attribution |

## Luck Sequence

~~~mermaid
flowchart LR
    A["Ex ante: Luck Potential"]
    B["Transition: Luck Realization"]
    C["Ex post: Luck Attribution"]

    A --> B --> C
~~~

- **Luck Potential:** uncertainty, exposure, feasible alternatives, and possible consequences.
- **Luck Realization:** interactions, mechanisms, responses, selection, state changes, and feedback.
- **Luck Attribution:** relational evaluation against a reference and feasible alternatives.

Luck is not shown as a force connecting the layers because it is not a primitive or mechanism.

## Key Guardrails

- Opportunity is relational, not automatically created by uncertainty.
- Capability is distinct from performance.
- Adaptation is not automatically beneficial.
- Path dependence requires a reinforcing mechanism.
- Survival does not establish superiority.
- Unrealized alternatives must be feasible ex ante.
- Attribution does not replace causal explanation.

## Repository Role

Figure 1 is the shared architectural map. Foundations defines its constructs; Formalization specifies relationships; Measurement operationalizes them; Empirical and Comparative Studies assess evidence; General Theory states provisional propositions.
