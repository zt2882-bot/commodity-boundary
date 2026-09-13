# Paper 3: Marginal Return as the System's Switch Signal

**Core thesis**: marginal return is the single, objective, measurable switch signal for "commodity-boundary control" — it downgrades "when to communalize, when to marketize" from subjective decision to a system-state judgment
**Tools**: threshold functions, signal detection, state-switch criteria
**Falsifiable corollary**: if marginal return cannot be measured accurately, in real time, and trustworthily, the whole "commodity-boundary control" framework loses its trigger signal and degrades into an unexecutable design

---

## Abstract

The previous paper proposed the operation of "dynamic commodity-boundary control," but left one question unanswered: **what signal triggers "moving out" and "returning"?** This paper's answer: **marginal return.** Marginal return is the only signal satisfying three conditions simultaneously — it is **objective** (independent of any person's subjective judgment), **measurable** (computable from economic data), and **continuous** (trackable in real time). This paper argues: marginal return, as a switch signal, downgrades "when to communalize, when to marketize" from an ideological debate into a computable system-state judgment.

## 1. Why "Marginal Return," Not Something Else

The question "when to move the surplus out of the commodity category" has historically been argued as an **ideological question**:

- The left says: communalize at all times (planning);
- The right says: never communalize (market);
- Result: neither persuades the other, because both use **faith**, not **signal.**

This paper's entry point: the "when" question needs not faith, but a signal. And the candidate signals are:

| Candidate | Objective? | Measurable? | Continuous? | Verdict |
|---|---|---|---|---|
| Ideology | no | no | no | reject |
| Capacity utilization | yes | yes | yes | usable, but indirect |
| Price | yes | yes | yes | usable, but lagging |
| **Marginal return** | **yes** | **yes** | **yes** | **optimal** |

Marginal return is the **most direct** signal — it directly measures "how much does one more unit of resource recover." When marginal return approaches zero, it means "continuing production is no longer profitable," which is precisely the definition of "surplus."

## 2. Formalization: Marginal Return as a Threshold Signal

Let a product's marginal return be $r$, and define two thresholds:

- $r \le 0$: the **surplus region** — continued production is unprofitable, triggering "move out of the commodity category";
- $r > \theta$ (with $\theta > 0$): the **normal region** — production is profitable, triggering "return to the commodity category";
- $0 < r \le \theta$: the **observation region** — no switch, keep the status quo.

**Switch rules** (a state machine with hysteresis, to avoid frequent oscillation):

$$\text{state} = \begin{cases} \text{commodity (market)} & r > \theta \\ \text{public asset (labor exchange)} & r \le 0 \\ \text{keep previous state} & 0 < r \le \theta \end{cases}$$

**The meaning of hysteresis**: $\theta > 0$ rather than $\theta = 0$ is to prevent the system from oscillating back and forth near the critical point. This design is called a **Schmitt trigger** in cybernetics — the entry and exit thresholds differ, so the system stays stable.

## 3. Why This Signal "Downgrades" the Debate

The core value of the marginal-return signal is that it turns "when to communalize" from a **value judgment** into a **fact judgment**:

- No longer need to argue "is communalization right" — only answer "is marginal return approaching zero";
- No longer need to argue "is marketization right" — only answer "has marginal return recovered."

**This is not ideological neutrality, but replacing "stance" with "signal."** When "when to switch" depends on a measurable number rather than a person's stance, the whole debate downgrades from a "war of faith" into a "war of measurement" — and a war of measurement can be settled by data.

## 4. A Real Threshold: Data Credibility

Marginal return's effectiveness as a signal **depends entirely on data credibility**:

- Who measures marginal return? (the data collector)
- Who judges "approaching zero"? (the judge)
- Can the data be manipulated? (stakeholders have incentives to forge data)

These three questions are the hardest threshold from theory to grounding. If the data can be manipulated by capital or power, the signal "marginal return has hit zero" will be infinitely postponed — capital will always say "not yet."

**This is precisely why this framework needs a tamper-proof data substrate** — a recording system where the "marginal return" signal **cannot be forged, cannot be tampered with, and is traceable.** This is what Paper 8 (the execution layer) must solve, and where this framework connects to "temporal causal anchoring" technology.

## 5. Falsifiable Corollary

> **Proposition**: if marginal return can be measured accurately, in real time, and trustworthily, then "commodity-boundary control" has an objective switch signal, and the system can stably switch between "market" and "public asset" states, avoiding collapse.
> **Contrapositive**: if marginal-return data can be manipulated by stakeholders (capital says "not yet," power says "already"), then the switch signal is distorted, and the framework degrades into an unexecutable design.

The converse is falsifiable: if a system with trustworthy marginal-return data still cannot complete the "market/public" two-state switch, then "marginal return signal" is insufficient to drive state transfer, and another signal must be sought.

## Conclusion

Marginal return is this framework's **only heartbeat.** It downgrades "when to communalize, when to marketize" from an ideological debate into a computable threshold judgment. But it also stakes the framework's entire fate on one thing: **whether this signal can be measured trustworthily.** And that thing is exactly what the next layer — the execution layer — must solve.

---

*Paper 3 of the "Commodity Boundary Game" series.*
