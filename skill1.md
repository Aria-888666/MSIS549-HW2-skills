---
name: decision-problem-structurer
description: Transform messy user input into a structured decision model. Use when a user provides a business or personal decision problem.
---

## Decision Problem Structurer

### Purpose

Convert unstructured decision descriptions into a formal, analyzable structure suitable for systematic evaluation.

---

### When to Use

Use when:
- The user provides a messy or partially defined decision.
- Objectives, constraints, or tradeoffs are unclear.
- The decision requires structured framing before evaluation.

---

### Inputs

- Raw user description of the decision

---

### Outputs

Produce the following labeled sections:

- **Decision Question**
- **Objective Function**
- **Constraints**
- **Stakeholders**
- **Provided Alternatives**
- **Missing Information**
- **Decision Type Classification**

---

### Step-by-Step Behavior

1. Extract the core decision question.
2. Define the objective.
3. Identify constraints (budget, timeline, risk tolerance, resources).
4. Identify stakeholders and their incentives.
5. List alternatives.
6. Identify necessary missing information to the decision.
7. Classify the decision type:
   - Risk (probabilities known)
   - Uncertainty (probabilities unknown)
   - Multi-criteria tradeoff
   - Strategic / long-term positioning

---

#### Constraints

- Do NOT use fake data.
- Explicitly flag assumptions.
- If the objective is ambiguous, ask 2–4 concise clarification questions before proceeding.

---

### Failure Modes

- Unplausible user goals.
- Fabricating constraints.
- Missing implicit tradeoffs.
- Proceeding without sufficient clarity.

If critical information is missing, return clarification questions instead of continuing.
