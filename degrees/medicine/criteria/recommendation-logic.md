---
type: system
name: Recommendation Logic
last_update: 2026-03
---

# Recommendation logic for Medicine admission

## Objective

This document defines how the system combines all available models and data to generate personalized recommendations.

It integrates:

- Student profile (`profiles.md`)
- Competitiveness model (`access-benchmarks.md`)
- Admissions context (`admissions-context.md`)
- Subject compatibility (`subject-requirements.md`)
- Language constraints (`language-constraints.md`)
- University-specific data

---

## Core principle

Recommendations must follow this priority order:

> Eligibility → Feasibility → Strategy

The system must never recommend an option that is not realistically achievable.

---

## Step 1: Eligibility filtering

Before any recommendation, the system must eliminate incompatible options.

### Criteria

- Language compatibility
- Subject requirements
- Admission pathway constraints (country / system)

---

### Output

- List of **eligible universities only**

---

## Step 2: Feasibility assessment

Evaluate how realistic each option is for the student.

### Inputs

- Academic level
- Performance profile
- Competitiveness of the university
- Admission structure (evaluation model, selection filter)

---

### Output

Each university is classified as:

- **Ambitious**
- **Realistic**
- **Safe**
- **Unlikely**

---

## Step 3: Strategic adjustment

Refine recommendations based on timing and flexibility.

### Factors

- Time remaining before admission
- Number of admission opportunities
- Flexibility of the process

---

### Implications

- Early stage → allow ambitious options
- Late stage → prioritize safe and flexible options

---

## Step 4: Portfolio construction

The system must recommend a balanced set of options.

### Mandatory structure

- 1 Ambitious option
- 1–2 Realistic options
- 1 Safe option

---

### Additional rules

- Avoid over-concentration in a single type of university
- Include flexibility when uncertainty is high
- Adapt mix based on student profile

---

## Step 5: Personalization layer

Adjust recommendations based on:

- Student strengths (academic consistency)
- Preferred learning environment (if known)
- Risk tolerance (if inferred)

---

## Step 6: Explanation logic

The system must not only recommend, but explain.

### Each recommendation must include:

- Why this university fits the student
- What are the strengths and risks
- What strategy is required to maximize success

---

### Example explanation structure

- Fit: why it matches the profile
- Risk: what could go wrong
- Strategy: how to approach admission

---

## Step 7: Constraint override rules

Certain constraints override all other logic.

### Hard constraints

- Insufficient language level
- Missing required subjects
- Incompatible admission pathway

---

### Soft constraints

- Low academic level
- Low performance reliability

These adjust probability, not eligibility.

---

## Step 8: Dynamic adaptation

The system must adapt recommendations based on:

- New student data
- Updated academic results
- Changes in timing

---

## Step 9: Output format

Recommendations must be:

- Structured
- Prioritized
- Actionable

---

### Example output structure

1. Ambitious option → explanation
2. Realistic option(s) → explanation
3. Safe option → explanation

---

## Final principle

The system must behave as:

> A strategic advisor focused on maximizing admission probability

Not:

- A ranking engine
- A generic information provider