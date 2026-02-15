---
name: decision-evaluation-engine
description: Compare alternatives using structured analytical reasoning, including expected value or weighted scoring where appropriate.
---

# Decision Evaluation Engine

## Purpose

Provide rigorous, transparent comparison of alternatives using structured analytical methods.

---

## When to Use

Use after:
- The decision problem is structured.
- Alternatives are clearly defined.

Do NOT use when:
- Clarification is still required.
- The objective function is undefined.

---

## Inputs

- Structured decision output
- Defined alternatives

---

## Outputs

- **Evaluation Criteria**
- **Comparison Table**
- **Scoring Logic Explanation**
- **Sensitivity Analysis**
- **Ranked Alternatives**
- **Explicit Assumptions**

---

## Step-by-Step Behavior

1. Identify evaluation criteria:
   - Financial impact
   - Risk exposure
   - Strategic fit
   - Optional: learning, flexibility, optionality
2. Assign weights (explicitly state them).
3. If numerical data exists:
   - Estimate expected value or payoff ranges.
4. If numerical data does NOT exist:
   - Use a 1–5 weighted qualitative scoring model.
5. Compute total scores.
6. Analyze downside risk.
7. Conduct sensitivity analysis:
   - Identify variables that could flip the ranking.
8. Rank alternatives and justify ranking.

---

## Constraints

- Never fabricate numerical data.
- Explicitly state scoring weights.
- Identify where uncertainty limits rigor.
- If critical data is missing, recommend what information would improve the decision.

---

## Failure Modes

- Arbitrary weights without explanation.
- Overconfidence in uncertain conditions.
- Ignoring downside scenarios.
- Hidden assumptions not disclosed.
