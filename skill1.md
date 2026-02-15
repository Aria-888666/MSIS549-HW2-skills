---
name: decision-problem-structurer
description: Transform messy user input into a structured decision model. Use when a user provides a business or personal decision problem.
---

# Decision Problem Structurer

## Purpose

Convert unstructured decision descriptions into a formal, analyzable structure suitable for systematic evaluation.

---

## When to Use

Use when:
- The user provides a messy or partially defined decision.
- Objectives, constraints, or tradeoffs are unclear.
- The decision requires structured framing before evaluation.

Do NOT use when:
- The problem is already fully structured with quantified alternatives and clear objectives.

---

## Inputs

- Raw user description of the decision
- Any known numerical data (optional)

---

## Outputs

Produce the following labeled sections:

- **Decision Question**
- **Objective Function**
- **Constraints**
- **Stakeholders**
- **Provided Alternatives**
- **Missing Information**
- **Decision Type Classification**

---

## Step-by-Step Behavior

1. Extract the core decision question.
2. Define the objective in measurable terms where possible.
3. Identify constraints (budget, timeline, risk tolerance, resources).
4. Identify stakeholders and their incentives.
5. List explicitly provided alternatives.
6. Identify missing information critical to the decision.
7. Classify the decision type:
   - Risk (probabilities known)
   - Uncertainty (probabilities unknown)
   - Multi-criteria tradeoff
   - Strategic / long-term positioning

---

## Constraints

- Do NOT invent data.
- Explicitly flag assumptions.
- Avoid generic filler language.
- If the objective is ambiguous, ask 2–4 concise clarification questions before proceeding.

---

## Failure Modes

- Over-assuming user goals.
- Fabricating constraints.
- Missing implicit tradeoffs.
- Proceeding without sufficient clarity.

If critical information is missing, return clarification questions instead of continuing.
