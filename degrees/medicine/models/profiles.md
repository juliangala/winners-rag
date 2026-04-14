---
type: model
name: Student Profiles
last_update: 2026-03
---

# Student profiles for Medicine admission

## Objective

This document defines the main types of student profiles and how the system should adapt its recommendations accordingly.

It connects:

- Academic level
- Performance reliability
- Timing
- Competitiveness of universities

The goal is to generate **personalized and realistic admission strategies**.

---

## Core principle

There is no universal best strategy.

The optimal strategy depends on:

- The student’s academic level
- The reliability of their academic performance
- The time remaining before admission
- The competitiveness and structure of each university

---

## Key profile dimensions

### 1. Academic level

Represents overall competitiveness of the student.

The interpretation of academic level depends on the admission pathway.

---

#### Private universities reference (Year 12 / 1º Bachillerato)

This is the most relevant academic indicator for private universities.

- Based primarily on first year of Bachillerato (or equivalent)
- Some universities may consider full academic history, but Year 12 is the key reference

##### Academic segmentation

- **Excellent profile (9.0 – 10)**
  - Strong access to all private universities
  - Competitive even in selective ones
  - Can compensate weaker elements of the application

- **Strong profile (8.0 – 8.99)**
  - Access to most private universities
  - Good balance across evaluation models
  - Still competitive in selective processes

- **Borderline profile (7.0 – 7.99)**
  - Meets minimum requirements
  - Limited margin for error
  - Strong dependency on:
    - timing
    - admission flexibility
    - evaluation model

- **Below threshold (<7.0)**
  - Does not meet minimum requirements for most private universities
  - Strategy must change:
    - alternative pathways
    - foundation programs (if available)

---

#### Public universities reference

Academic level is based on final admission grade:

- Bachillerato + EvAU (or equivalent)
- Or converted international grade

General interpretation:

- Very high grade → access to top public universities
- High grade → access to most public universities
- Medium grade → limited public options
- Low grade → public universities unlikely

---

### 2. Performance profile

Defines how reliable the student’s academic performance is as a predictor of future results.

Since direct exam performance data is usually not available, the system must infer this profile based on available academic indicators.

The system must not assume exam performance beyond what can be reasonably inferred from academic history.

---

#### High academic consistency

- Strong and stable academic record over time
- High grades across subjects
- Reliable predictor of performance

Implications:

- Well suited for:
  - Universities with high academic weight
  - Consistent evaluation models

---

#### Moderate academic consistency

- Acceptable academic performance
- Some variability in grades
- Less predictable outcomes

Implications:

- Requires balanced strategy
- Should avoid overly selective environments without flexibility

---

#### Low academic consistency

- Irregular academic performance
- Lower or unstable grades

Implications:

- Higher uncertainty in outcomes
- Should prioritize:
  - flexible admission processes
  - multiple opportunities

---

### 3. Timing

Defines how much time the student has before admission.

---

#### Early stage (6+ months before exams)

- Full strategic flexibility
- Can target ambitious universities
- Can prepare for admission processes

---

#### Mid stage (3–6 months)

- Strategy must be more focused
- Limited room for improvement
- Important to balance risk

---

#### Late stage (<3 months)

- Strategy must prioritize probability
- Focus on accessible options
- Private universities gain importance

---

#### Very late stage (after main deadlines)

- Limited options
- Must rely on:
  - private universities
  - late admission rounds
  - remaining public seats (September)

---

## Interaction between academic level and performance profile

Academic level and performance reliability must be evaluated together.

Examples:

- High academic level + high consistency → strong and predictable candidate
- High academic level + low consistency → high potential but unstable outcomes
- Borderline academic level + high consistency → limited ceiling but reliable
- Borderline academic level + low consistency → high risk profile

The system must avoid evaluating either dimension in isolation.

---

## Strategic profile combinations

The system must combine:

- Academic level
- Performance reliability
- Timing

to determine the optimal strategy.

---

### 1. Excellent / Strong + high consistency + early

- Can target:
  - very competitive public universities
  - selective private universities

Strategy:

- Include ambitious options
- Maintain safety options
- Optimize university mix

---

### 2. Strong + moderate consistency + mid

- Can access:
  - high / medium competitiveness public universities
  - most private universities

Strategy:

- Balanced portfolio
- Combine ambition + realism
- Avoid overly rigid admission processes

---

### 3. Borderline + moderate / low consistency + mid/late

- Limited access to public universities
- Strong reliance on private options

Strategy:

- Prioritize:
  - flexible private universities
  - favorable evaluation models
- Reduce risk

---

### 4. Below threshold or low consistency

- Public universities unlikely
- Private universities limited or unavailable

Strategy:

- Focus on:
  - alternative pathways
  - improving academic profile
  - preparing for future intake

---

## Key strategic rules

### 1. Match profile with evaluation model

- Strong academic record → prioritize universities with high academic weight
- Lower reliability → prioritize flexible admission systems

---

### 2. Adjust strategy based on timing

- Early → allow ambition
- Late → prioritize probability

---

### 3. Use flexibility as a strategic lever

- More admission rounds → lower risk
- Fewer rounds → higher risk per attempt

---

### 4. Avoid single-option strategies

The system must always recommend:

- At least one ambitious option
- One or more realistic options
- One safe option

---

## Usage in recommendation logic

This document allows the system to:

- Adapt recommendations to each student
- Explain why certain universities fit better
- Adjust strategy dynamically based on timing and profile

The system must behave as:

> A strategic advisor, not just an information provider