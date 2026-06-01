```md
---
id: ceu-f3-medicine

type: university
subtype: private

name: Universidad CEU Fernando III
short_name: CEU-F3

degree: Medicine

last_update: 2026-05-27

valid_for_intake: 2027-2028 # ANNUAL_UPDATE_REQUIRED — admission for 2026-2027 is already closed

location:
  city: Bormujos (Sevilla)
  region: Andalusia
  country: Spain

strategic_tags:
  - safety_option
  - exam_heavy
  - english_advantage
  - rolling_admissions
  - early_application_advantage
  - strong_clinical_exposure
  - high_cost
  - academic_exam_required
  - onsite_exam_required
  - interview_heavy

admission:
  intake_month: September # ANNUAL_UPDATE_REQUIRED

  applications_open_date: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED — rolling process, typically opens autumn prior year

  rolling_admissions:
    enabled: true
    estimated_end_date: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED — closes when 60 seats fill; 2026/2027 cohort already closed

  admission_rounds:
    enabled: false
    count: NULL

    rounds: []

  exam_required: true
  interview_required: true

academic_record:
  minimum_requirement:
    enabled: false
    grade_source: NULL
    minimum_grade: NULL

  competitive_filter:
    enabled: true
    grade_source: PENDING_CONFIRMATION # Academic record evaluated holistically in the interview — no published minimum or formula
    approx_candidates_selected: NULL

curriculum:
  international_curriculums_accepted: true

competitiveness:
  level: medium_high # Program launched 2025 (first cohort); 60 seats; 2026-27 already full — data insufficient to determine precise level

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION # New program (launched 2025); no published statistics
  seats: 60
  applicants_per_seat: PENDING_CONFIRMATION

  last_admitted_scores:
    - intake_year: PENDING_CONFIRMATION
      round: PENDING_CONFIRMATION
      score: PENDING_CONFIRMATION
      score_type: PENDING_CONFIRMATION
      notes: No cut-off scores published. Admission is holistic (interview + exam). 2026-27 cohort already closed at full capacity.

international_profile:
  international_students_percentage: PENDING_CONFIRMATION

  international_nationalities:
    - country: PENDING_CONFIRMATION
      percentage: PENDING_CONFIRMATION

programs:
  - id: ceu-f3-medicine-sevilla

    campus: Campus Universitario CEU Andalucía, Bormujos (Sevilla)

    modality: standard

    strategic_tags:
      - safety_option
      - exam_heavy
      - english_advantage
      - rolling_admissions
      - early_application_advantage
      - strong_clinical_exposure
      - high_cost
      - academic_exam_required
      - onsite_exam_required
      - interview_heavy

    teaching_languages:
      - Spanish

    regional_language_possible: false
    regional_language: NULL

    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION

      english_required: false # English is tested within the internal exam (25% of exam score), not as a separate certificate requirement
      minimum_english_level: NULL # B1 level is the content standard tested in the exam; no separate certificate required

    seats: 60

    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 60
      applicants_per_seat: PENDING_CONFIRMATION

      last_admitted_scores:
        - intake_year: PENDING_CONFIRMATION
          round: PENDING_CONFIRMATION
          score: PENDING_CONFIRMATION
          score_type: PENDING_CONFIRMATION
          notes: No published cut-off data. New program (first cohort 2025-26).

    program_specific_admission:
      enabled: false

    evaluation_model:
      overall_model_type: holistic # Interview-based process: a professor evaluates academic record, language level, and motivation. An internal entrance exam also exists but no published formula combining exam + academic record.

      admission_pathways:
        - eligible_profiles:
            - Spanish Bachillerato students who have passed PEvAU (Selectividad)
            - Foreign secondary education equivalents with Spanish credential or homologación
            - CFGS/FP Grade Superior graduates (priority to health-related branches if oversubscribed)
            - University graduates with degree
            - Mayores de 25/45 años (passed access exam)
            - Mayores de 40 with relevant work experience (evaluated case by case)
            - Transfer students (traslado de expediente, minimum 30 ECTS convalidable)

          components:
            - component: academic_record
              enabled: true
              role: qualitative_only
              weight: NULL # Not published — evaluated holistically within the interview process
              grade_source: PENDING_CONFIRMATION # Academic record assessed by the interviewing professor; no formal grade source specified
              minimum_required_grade: NULL
              notes: The professor evaluates the candidate's academic record during the interview. PEvAU must have been passed for Spanish bachillerato students, but the PEvAU grade's role in ranking is not published. No minimum grade threshold stated. Academic record is one of three factors assessed holistically (alongside language level and motivation/interest).

            - component: academic_exam
              enabled: true
              role: qualitative_only # Exam content document is published; role in admission ranking is not published numerically
              weight: NULL
              exam_variant: onsite_internal_exam
              exam_format: multiple_choice
              delivery_mode: onsite # Assumed in-person at Bormujos campus; delivery mode not explicitly stated on public pages
              online_conditions: PENDING_CONFIRMATION

              subjects:
                - Biology — 2nd year Bachillerato (LOMLOE) (40% of exam)
                - Chemistry — 2nd year Bachillerato (LOMLOE) (30% of exam)
                - English — B1 CEFR level (25% of exam)
                - Scientific reasoning and comprehension of scientific texts (5% of exam)

              syllabus_alignment:
                biology:
                  scope:
                    - second_year_baccalaureate
                  notes: "Explicitly stated: 'Biología 2º de bachillerato (LOMLOE)'. Covers: biomolecules, molecular genetics, cell biology (membrane, organelles, cell cycle, mitosis/meiosis), metabolism (aerobic + anaerobic), biotechnology (PCR, CRISPR, etc.), immunology. Weighted at 40% of exam."

                chemistry:
                  scope:
                    - second_year_baccalaureate
                  notes: "Explicitly stated: 'Química 2º de bachillerato (LOMLOE)'. Covers: atomic structure, periodic table, chemical bonds, thermodynamics, kinetics, equilibrium, acid-base reactions, redox reactions, organic chemistry (isomers, reactivity, polymers). Weighted at 30% of exam."

                physics:
                  scope:
                    - not_applicable
                  notes: Physics is not included in the UF3 entrance exam. This differentiates UF3 from CEU Cardenal Herrera (which includes Physics/Math) and aligns with CEU San Pablo (which also excludes Physics).

                mathematics:
                  scope:
                    - not_applicable
                  notes: Mathematics is not included in the entrance exam.

                other_subjects:
                  - subject: English (B1 CEFR)
                    scope:
                      - university_specific_syllabus
                    notes: English at B1 CEFR level is explicitly included as 25% of the exam. This is the most distinctive feature of the UF3 exam versus all other Spanish private medical school entrance exams reviewed. English is tested within the internal exam (not as a separate certificate). Students with strong English have a significant structural advantage.

                  - subject: Scientific reasoning and comprehension of scientific texts
                    scope:
                      - university_specific_syllabus
                    notes: 5% of exam. Evaluates capacity for reasoning and comprehension of scientific articles. Not content-dependent.

              exam_difficulty:
                level: PENDING_CONFIRMATION
                rationale:
                  - second_year_content
                  - memorization_heavy
                  - reasoning_based
                notes: Biology and Chemistry are both explicitly 2nd-year baccalaureate LOMLOE. No Physics or Mathematics. The 25% English component is the largest single differentiator — students without B1-level English are structurally disadvantaged. The 5% reasoning component tests academic aptitude. No information on negative marking or question count.

              best_attempt_counts: PENDING_CONFIRMATION
              notes: Admission is rolling (limited seats). Specific exam session dates not published on public pages. The exam content document is published at uf3ceu.es/examen-admision/contenidos-examen-medicina-uf3.pdf.

            - component: isat
              enabled: false
              role: NULL
              weight: 0
              exam_format: NULL
              delivery_mode: NULL
              online_conditions: NULL
              best_attempt_counts: NULL
              notes: Not required.

            - component: english_test
              enabled: false
              role: NULL
              weight: 0
              test_format: NULL
              delivery_mode: NULL
              online_conditions: NULL
              minimum_level: NULL
              bonus_max: NULL
              bonus_scale:
                B2: NULL
                C1: NULL
                C2: NULL
              notes: English is tested as an integral component of the internal entrance exam (25% of exam score) — not as a separate certificate. No standalone English certificate is required.

            - component: psychometric_test
              enabled: false
              role: NULL
              weight: 0
              test_format: NULL
              delivery_mode: NULL
              online_conditions: NULL
              notes: Not required.

            - component: interview
              enabled: true
              role: qualitative_only
              weight: NULL
              interview_format: oral
              delivery_mode: onsite
              notes: A personal interview with a professor from the Medicine faculty is a mandatory part of the admission process. The professor evaluates three factors — academic record, language level, and interest in the degree. The resolution of the application ("Apto con plaza", "Apto en lista de espera", or "No apto") is explicitly stated to be based on the interview report. The interview also informs candidates about recognition of prior credits and degree specifics.

            - component: complementary_points
              enabled: false
              role: bonus_only
              maximum_bonus: NULL
              categories: []
              notes: No complementary points system found in published admission documentation.
---
# Universidad CEU Fernando III — Grado en Medicina

## Overview

Universidad CEU Fernando III (UF3) is the private medical school of the CEU group in Andalusia, located in Bormujos (greater Sevilla). The Grado en Medicina was launched in the 2025-26 academic year — the most recently established Medicine program among all private Spanish universities in this analysis — and offers 60 seats per cohort. Admission for the 2026/2027 cycle is already closed at capacity, making UF3 one of the most operationally relevant options specifically for the 2027/2028 intake.

The program is delivered in Spanish in afternoon-shift format at the dedicated Campus Universitario CEU Andalucía in Bormujos. The admission process is holistic: candidates attend an interview with a professor who evaluates academic record, language level, and motivation, and there is a published internal entrance exam covering Biology (40%), Chemistry (30%), English B1 (25%), and scientific reasoning (5%). This English component — built directly into the exam — is structurally unique among Spanish private medical school entrance tests.

The clinical training model centers on a purpose-built Hospital de Simulación on campus with mandatory rotations under personalized supervision, complemented by a clinical network in the Sevilla area. Annual tuition for 2026-27 is €15,500 (Year 1), among the lower end of the private medicine spectrum in Spain, and the Nemesio Díez Foundation provides six full-first-year-tuition scholarships annually.

As the only private Medicine school in Andalusia, UF3 occupies a geographically unique position for students from southern Spain.

## Quick Evaluation

- **Seats:** 60
- **Location:** Bormujos (Sevilla), Campus CEU Andalucía — only private Medicine school in Andalusia
- **Program start:** 2025-26 (first cohort — brand new program)
- **2026/2027 status: CLOSED** — admission at full capacity for this cycle
- **Relevant intake:** 2027/2028 onwards
- **Admission model:** Holistic — interview + internal exam; no published numerical formula
- **Exam:** Biology (40%) + Chemistry (30%) + English B1 (25%) + Scientific reasoning (5%)
- **English in exam:** 25% of exam is English B1 — unique among Spanish private medical school exams
- **No Physics, no Mathematics** in exam
- **Interview:** Mandatory; evaluates academic record, language level, motivation
- **Annual tuition (Year 1, 2026-27):** €15,500 (reserva €1,950 + matrícula €650 + 60 ECTS × €215)
- **Credit price:** €215
- **Scholarship:** 6 × €12,900 (Fundación Nemesio Díez) for first-year students
- **Clinical practice:** 1,665 hours; mandatory Hospital de Simulación rotations
- **International exchanges:** Available from Year 3 via CEU network
- **WFME accreditation:** PENDING_CONFIRMATION
- **Schedule:** Afternoon shift (Turno tarde)

## Key Facts

| Field | Value |
|---|---|
| University | Universidad CEU Fernando III (UF3) |
| Degree | Grado en Medicina |
| Duration | 6 years |
| Total ECTS | 360 |
| Seats | 60 |
| Campus | Campus CEU Andalucía, Bormujos (Sevilla) |
| Language | Spanish |
| Schedule | Afternoon shift (Turno tarde) |
| Academic year started | 2025-26 (first cohort) |
| 2026/2027 admission | Closed — at capacity |
| Annual tuition (Year 1, 2026-27) | €15,500 |
| Credit price | €215 |
| Reservation fee | €1,950 |
| Enrollment fee (matrícula) | €650 |
| Nemesio Díez Foundation scholarships | 6 × €12,900/year |
| Admission model | Holistic (interview + internal exam) |
| Exam English component | 25% of internal exam (B1 CEFR) |
| Clinical hours | 1,665 |
| Simulation Hospital | Own dedicated building, mandatory rotations |
| WFME | PENDING_CONFIRMATION |
| ANECA | Verified (Informe de Verificación published) |

## Program Options

There is a single program: the Grado en Medicina in Spanish, delivered in person at the Bormujos campus in afternoon-shift format. There is no bilingual track, no parallel campus, and no online modality.

The afternoon-shift structure (Turno tarde) is relatively uncommon for Medicine programs in Spain. This is a logistical distinction that may affect students with morning employment commitments, family obligations, or travel arrangements, and may influence campus culture and peer dynamics compared to standard morning-shift programs.

The combined track "Grado en Medicina + Diploma Universitario de Experto en Medicina Clínica y Diagnóstica" is available at CEU Cardenal Herrera (sibling institution) but has not been mentioned for UF3. PENDING_CONFIRMATION whether a similar dual-award track applies here.

## Program Structure

The program follows the standard six-year, 360-ECTS Spanish Medicine structure mandated by Order CIN/2137/2008.

| Feature | Detail |
|---|---|
| Duration | 6 years |
| Total ECTS | 360 |
| Subject breakdown | PENDING_CONFIRMATION — plan de estudios page exists but detailed ECTS breakdown not extracted |
| Clinical practice hours | 1,665 (explicitly stated by university) |
| Simulation Hospital integration | Mandatory rotations in all areas from Year 1 |
| RUCT registry entry | Available (study code 1500370) |

The Faculty of Ciencias de la Salud y de la Vida houses the Medicine degree. The program was designed with a strong emphasis on early practical skills acquisition and ethical/humanistic training. It incorporates subject areas related to human rights, gender equality, disability inclusion, and democratic values — explicitly stated as formal curriculum components.

## Teaching Methodology

The program is built around three pillars: early skills-based learning, simulation-based training, and a values-integrated approach to medical education.

**Hospital de Simulación:** The university has built a dedicated simulation hospital with state-of-the-art simulators. Rotations through all simulated areas are mandatory for all students. A distinctive feature is the **Debriefing Dirigido** method — students record their simulation sessions and then review and discuss the case in depth with their tutors. This promotes critical reflection on clinical decisions and is described as a cornerstone of the learning methodology.

**Practice from Day One:** The program emphasizes equipping students with technical skills and practical competencies from the first year. The 1,665-hour clinical practice total ensures substantial hands-on experience through the degree.

**Humanistic orientation:** The program is framed within the CEU group's Christian humanist values tradition. An initiative called "Aula Moscati — Medicina y Fe" explores the intersection of science, faith, and medical vocation through the lives of physician role models. This dimension is more pronounced at UF3 than at other CEU campuses.

**Active faculty:** The teaching staff are described as having a high percentage of active practicing clinicians (professors in practice) with research capacity, ensuring direct connection between academic content and current clinical reality.

**International exchanges:** From Year 3, students can participate in stays at international universities in the CEU network, with agreements adjusted to the local plan de estudios of each destination to ensure credit compatibility.

## Clinical Training

Clinical training runs throughout the full 6-year program. The program explicitly states 1,665 hours of clinical experience across the degree.

**Clinical hospital network** (Sevilla metropolitan area; ANNUAL_UPDATE_REQUIRED):
- Hospital Vithas (Sevilla)
- Hospital San Juan de Dios de Bormujos y Nervión
- Hospital Viamed Dos Hermanas
- Hospital Fátima
- Additional agreements cited in areas of social deficit, including Palliative Medicine and Family Medicine (proactively sought by the university)

The combination of Hospital Vithas and Hospital San Juan de Dios represents a mix of private and charitable healthcare providers. The stated focus on Palliative Medicine and Family Medicine reflects a values-driven clinical placement strategy — areas often underrepresented in purely commercially oriented networks.

The **Hospital de Simulación** on the Bormujos campus complements hospital rotations with pre-clinical and simulation-based learning, providing students with a controlled environment for developing procedural skills before deploying them in real clinical settings.

## International Recognition and Opportunities

**ANECA accreditation:** The program holds an "Informe de Verificación Favorable" from ANECA (the Spanish quality agency for university programs). The Verificación report is publicly accessible.

**RUCT registry:** The degree is officially registered with the Spanish Ministry of Education (study code 1500370).

**WFME accreditation:** PENDING_CONFIRMATION — WFME status was not confirmed in any published UF3 materials reviewed. Families planning international licensing pathways (US, Canada, Australia, New Zealand) should verify this directly with the university before enrolling.

**International exchanges:** Available from Year 3 through CEU network agreements. Specific destination universities and Medicine-specific exchange seats: PENDING_CONFIRMATION.

**CEU network:** UF3 belongs to the CEU group (the largest private education institution in Spain), which includes partner universities in Barcelona (UAO CEU), Madrid (USP CEU), and Valencia (CEU UCH). Cross-campus academic relationships and student mobility within the network are available.

## Admission Model

The UF3 admission model is **holistic**: there is no publicly disclosed numerical formula combining scores. The process has two assessable elements — a personal interview and an internal entrance exam — but the weighting of these elements and their relationship to the academic record in the final decision is not published.

**Interview component:**
A professor from the Medicine faculty conducts a personal interview. The professor explicitly evaluates three factors:
1. The candidate's academic record (expediente académico)
2. Language level
3. Interest in and motivation for the Medicine degree

The admission resolution ("Apto con plaza", "Apto en lista de espera", or "No apto") is stated to be based on the interview report.

**Entrance exam component:**
A formal entrance exam (Examen de Admisión) exists with published content. The exam consists of multiple-choice questions with four options (one correct). The subject distribution within the exam is:

$$\text{Exam distribution: } \underbrace{40\%}_{\text{Biology (2nd yr bach)}} + \underbrace{30\%}_{\text{Chemistry (2nd yr bach)}} + \underbrace{25\%}_{\text{English B1}} + \underbrace{5\%}_{\text{Scientific reasoning}}$$

The relationship between the exam score and the interview evaluation in the final ranking decision is not published.

**Key structural features:**
- English B1 (25% of exam) is tested directly within the internal exam — candidates do not submit a separate English certificate. This is unique among all major Spanish private medical school entrance exams reviewed.
- Biology and Chemistry are explicitly 2nd-year baccalaureate LOMLOE content (not 1st year, not university-specific).
- No Physics, no Mathematics.
- No complementary points or bonus system documented.
- PEvAU (Selectividad) must have been passed for Spanish bachillerato students — access route requirement, not a ranking factor per published information.

## Admission Process

1. **Fill in the online admission form** at admision.uf3ceu.es. Credentials for the student intranet are sent by email.

2. **Schedule a personal interview** with a professor from the Medicine degree. Select a date and time in the last section of the admission form.

3. **Attend the interview.** The professor evaluates academic record, language level, and interest in Medicine. Sits the internal entrance exam (timing relative to interview: PENDING_CONFIRMATION).

4. **Receive the admission resolution:**
   - **Apto con plaza:** Admitted; instructions provided to reserve the place.
   - **Apto en lista de espera:** On the waitlist; next steps communicated.
   - **No apto:** Not admitted (insufficient seats available or evaluation outcome).

5. **Reserve the place** (if admitted): Pay the €1,950 reservation fee via bank deposit (effective in 24h) or credit card (immediate). Free school insurance (seguro de escolaridad) automatically activated at enrollment — covers full tuition costs in case of death of a parent or legal guardian.

6. **Complete enrollment** through the Portal del Nuevo Alumno once all access requirements are met.

For **CFGS students**: admission possible regardless of professional family, but if oversubscribed, priority is given to health-related tracks. Credit convalidation available.

For **transfer students (traslado)**: minimum 30 ECTS convalidable required.

For **graduates**: conditional enrollment possible while homologación from the Ministry is pending.

## Admission Timeline

All dates are subject to **ANNUAL_UPDATE_REQUIRED**. The process is rolling (first-come, first-served within the 60-seat limit). Specific dates for the entrance exam sessions in 2026-27 were not published on public pages.

| Event | Status |
|---|---|
| 2025-26 intake | Completed (first cohort) |
| 2026-27 intake | **Closed — at full capacity** |
| 2027-28 applications open | PENDING_CONFIRMATION — likely autumn 2026 |
| Admission process | Rolling (no formal rounds) |
| Exam session dates (2027-28) | PENDING_CONFIRMATION — ANNUAL_UPDATE_REQUIRED |

The fact that the 2026-27 cycle closed before late May 2026 confirms demand exceeds supply. For the 2027-28 cycle, applying as early as possible once applications open is strongly recommended — this is definitively an early_application_advantage situation.

## Admission Score Distribution

No numerical formula is published. Rankings are determined holistically based on the professor's interview report, which incorporates assessment of the academic record, language ability, and motivation. The entrance exam presumably informs the interview but the mechanism is not public.

**Strategic implications:**

The 25% English weight in the exam is the single most distinctive quantitative feature. In the context of competitive applicants who are otherwise similar in Biology and Chemistry preparation, a strong English command (B1 content) can represent a meaningful differentiation. Students with English-medium education backgrounds or certified B1+ English have a structural preparation advantage in this specific exam.

The 2nd-year-only bachillerato syllabus for Biology and Chemistry means there is no Year 1 chemistry or biology content to prepare — preparation is concentrated on the 2nd-year LOMLOE curriculum only.

The absence of Physics and Mathematics from the exam narrows the preparation scope considerably versus CEU Cardenal Herrera (which includes Physics/Math at 20% of its exam).

The holistic, interview-based model introduces subjectivity that quantitative models do not. Motivation, communication, and demonstrated interest in medicine are genuine admission factors here.

## Costs and Payment Structure

**2026-27 confirmed fees (Grado en Medicina):**

| Fee | Amount | Notes |
|---|---|---|
| Reserva de plaza | €1,950 | One-time, paid on admission |
| Matrícula (enrollment) | €650 | Annual |
| Credit price | €215 | Per ECTS credit |
| Honorarios — 60 ECTS (1st year) | €12,900 | Payable in up to 9 installments (Oct–Jun) |
| **Total Year 1** | **€15,500** | Reserva + matrícula + honorarios |

**6-year cost estimate (at fixed 2026-27 credit rate):**

| Year | Honorarios (60 ECTS) | Other Fees | Total |
|---|---|---|---|
| 1 | €12,900 | €1,950 + €650 | €15,500 |
| 2–6 | €12,900 | €650 (matrícula) | €13,550/year |

Total 6-year estimate: **~€83,250** (ANNUAL_UPDATE_REQUIRED — credit price may increase annually). This is approximately €26K less than CEU Cardenal Herrera (Castellón) and ~€55K less than CEU San Pablo over 6 years — making UF3 among the more affordable private Medicine options in Spain.

**Credit recognition fees:**
- 1st-year subjects: €70/recognised credit
- Years 2–6 subjects: €215/recognised credit (full price)

**Repeating students:** 10% surcharge on 2nd enrollment of a subject, 20% on 3rd, 30% on 4th+.

**Payment options:**
- Up to 9 monthly installments for honorarios (October–June)
- Lump sum payment available on request
- Financing options via university-facilitated banking partnerships

## Scholarships and Financial Aid

**Fundación Nemesio Díez scholarships:** Six (6) scholarships of €12,900 each are offered annually to first-year Medicine students, in partnership with the Nemesio Díez Foundation. A scholarship of €12,900 covers the full honorarios (academic fees) for Year 1, leaving only the reservation fee (€1,950) and enrollment fee (€650) for the student to pay. This is the most significant direct financial support program documented for Medicine at UF3. Eligibility criteria and application process: PENDING_CONFIRMATION — ANNUAL_UPDATE_REQUIRED.

**School insurance (seguro de escolaridad):** All enrolled students receive free coverage that guarantees continuation of studies at no cost in case of death of a parent or legal guardian. No medical questionnaire required. Automatic activation.

**General MEC grants:** Applicable for students meeting income and academic thresholds.

**Financing lines:** CEU Fernando III has partnerships with banking institutions for student financing of monthly payments.

PENDING_CONFIRMATION: Additional Medicine-specific scholarship programs, academic merit scholarships, or sibling/family discount schemes.

## Accommodation and Cost of Living

**Bormujos and Sevilla:** The Bormujos campus is located in a suburban area approximately 8–10 km west of Sevilla city centre, well connected via public transport (bus lines into the city). Most students will live in Sevilla and commute to campus.

Sevilla is one of Spain's most student-friendly cities in terms of cost of living. Shared accommodation typically ranges from €300–€500/month. A full student monthly budget (accommodation, food, transport, materials) is approximately €700–€1,000/month — significantly lower than Madrid or Barcelona.

PENDING_CONFIRMATION: Official university accommodation options or residence agreements on or near the Bormujos campus.

## International Exchange and Mobility Programs

**CEU network exchanges:** International exchange stays are available to Medicine students from Year 3 onwards, through agreements with partner universities in the CEU network. Exchange agreements are described as adjusted to the local plan de estudios of each destination to ensure credit compatibility.

Specific named Medicine exchange destinations and seat allocations: PENDING_CONFIRMATION.

**Erasmus+:** Available as part of UF3's general mobility program. Applicability specifically to Medicine: PENDING_CONFIRMATION.

**Note on WFME:** If WFME accreditation is confirmed, graduates would be eligible for licensing and residency pathways in the US, Canada, Australia, and New Zealand. This has not been confirmed in UF3's published materials and must be verified before enrolling with this objective.

## MIR Preparation and Professional Outcomes

As the program's first cohort (2025-26) is currently completing its first academic year, no MIR preparation outcomes, pass rates, or placement data exist yet.

MIR preparation integration into the curriculum: PENDING_CONFIRMATION — not specifically described in public-facing materials as at CEU Cardenal Herrera (which has the formal AMIR partnership). Given this is a brand-new program, formal MIR preparation partnerships may not yet be in place.

**Professional recognition:** Graduates receive the official Spanish Grado en Medicina title (Order CIN/2137/2008), which entitles them to register as physicians in Spain (colegiación) and practice as licensed medical doctors. The degree enables access to the MIR examination for specialisation.

PENDING_CONFIRMATION: MIR preparation partnerships, external coaching agreements, and long-term alumni outcomes data.

## Strategic Fit

### Good Fit For

- Students from Andalusia (Sevilla, Málaga, Granada, Cádiz, Córdoba, Almería, Huelva, Jaén) who want to study Medicine close to home — UF3 is the only private Medicine program in Andalusia
- Students with strong English (B1+) who benefit from the 25% English component in the exam — a structural advantage versus applicants without English preparation
- Students who have studied full 2nd-year bachillerato Biology and Chemistry (LOMLOE) — the exam is explicitly limited to this scope
- Students who prefer a holistic, interview-based admission process over a purely numerical scoring model
- Families seeking the most affordable private Medicine option — at ~€83K total over 6 years, UF3 is among the lowest-cost private Medicine programs in Spain
- Students applying for the 2027/2028 cycle (2026/2027 is already closed)
- Students interested in early clinical contact and simulation-based training from Year 1
- Applicants who qualify for a Nemesio Díez Foundation scholarship (effectively making Year 1 cost ~€2,600 instead of €15,500)

### Less Suitable For

- Students who need admission in 2026/2027 — that cycle is already closed at capacity
- Students who chose an Arts or Social Sciences bachillerato — while Physics is absent, Biology and Chemistry are both required at 2nd-year LOMLOE level
- Students without English preparation — 25% of the exam is English B1, which is non-trivial
- Students seeking a confirmed WFME-accredited program — this has not been verified for UF3 and cannot be assumed
- Students who need a morning-shift program — UF3 Medicine is afternoon-only (Turno tarde)
- Students who want established MIR preparation infrastructure — the program is too new to have track record or formal MIR partnerships
- Students who want a bilingual or international program — there is no bilingual track and limited published international data

## Risks and Considerations

**1. Completely new program — no track record.** The first cohort enrolled in 2025-26. There are no graduates, no MIR data, no alumni outcomes, no cut-off score history, and no published competitiveness benchmarks. The full quality picture will only emerge over 6-8 years. Families making a decision now are committing based on design and promise, not performance evidence.

**2. WFME accreditation unconfirmed.** Among the private medical schools reviewed, WFME accreditation is a standard differentiator for international licensing aspirations. UF3 has not published WFME status. Without WFME, graduates are restricted from certain international licensing pathways (US, Canada, Australia, New Zealand). This must be confirmed before enrolling with these goals.

**3. Admission is holistic with no published formula.** The absence of a numerical formula makes it impossible to predict admission outcomes based on scores alone. The interview introduces a subjective evaluation component. This is good for candidates with strong communication and motivation, but creates uncertainty for quantitatively strong candidates who may be weaker in the interview format.

**4. 2026/2027 admission closed.** Students who are currently in 2nd year bachillerato (graduating June 2026) cannot apply for the upcoming cycle at UF3. This file is only operationally relevant for 2027/2028 planning or beyond.

**5. Afternoon-shift schedule.** The Turno tarde (afternoon) is unusual and may create logistical complications for students living far from Bormujos, or affect peer cohort culture and extracurricular engagement relative to morning-shift programs.

**6. Clinical hospital network is limited.** The confirmed clinical partners (Vithas, San Juan de Dios, Viamed, Fátima) do not include major public tertiary referral centres such as Hospital Virgen del Rocío or Hospital Virgen de la Macarena (Sevilla's main public hospitals). Agreements with public hospitals are described as a strategic goal but are not confirmed. Students who specifically value training in large public tertiary hospitals should verify this.

**7. No bonus or complementary points system.** Unlike CEU San Pablo or CEU Cardenal Herrera, no bonus points system is documented at UF3. The interview holistic model is the primary differentiator.

**8. Small cohort (60 seats) with rapid fill-up.** The program filled at capacity in its second year (2026/2027). As the only private Medicine school in Andalusia, regional demand may be high, and competition is likely to intensify as the program builds reputation.

## Important Notes

- The 2026/2027 Medicine cohort at UF3 is **already closed at full capacity**. The next available intake is 2027/2028.
- The English component (25% of the exam) is tested directly within the internal entrance exam — not as a separate certificate. Students do not need to submit an English qualification independently.
- Biology and Chemistry in the exam are explicitly **2nd-year baccalaureate LOMLOE** — not full bachillerato or university-specific syllabus. Preparation should focus on 2nd-year content only.
- Physics and Mathematics are **not** part of the UF3 exam — unlike CEU Cardenal Herrera.
- PEvAU/Selectividad must have been passed as a prerequisite for Spanish bachillerato students to enroll, but the PEvAU grade's role in ranking is not published.
- Transfer students (traslado) need a minimum of 30 ECTS that can be convalidated at UF3.
- The program is in the **afternoon shift** (Turno tarde) — students should plan accordingly for commuting, work schedules, and daily routines.
- 6 Nemesio Díez Foundation scholarships of €12,900 each are available annually for first-year students — application and eligibility criteria should be requested from the admissions office at the time of applying.

## Key Insight

UF3 is structurally the most regionally accessible private Medicine option for Andalusian students, and the most linguistically distinctive in terms of exam design — no other private Spanish medical school entrance exam includes a 25% English component baked into the test itself. This creates a genuine advantage for candidates with strong English (IB, bilingual secondary, or simply good English preparation), while creating a comparable disadvantage for those who have not focused on English.

The program's newness is both its biggest risk and its biggest opportunity. The fact that the 2026/2027 cohort is already closed suggests strong demand, but there is no evidence base yet for program quality, MIR outcomes, or competitive outcomes. Families accepting the early-adopter risk are getting the most cost-efficient private Medicine option in southern Spain; families who need certainty should wait for track record or focus on more established programs.

## Final Takeaway

Universidad CEU Fernando III offers the only private Medicine degree in Andalusia, making it geographically relevant for a large segment of the Spanish student population that would otherwise need to relocate to Madrid, Valencia, or Navarra. At ~€83K total over 6 years, it is among the most affordable private Medicine programs in Spain.

The admission process is holistic and interview-based, with an internal exam that uniquely includes a 25% English component at B1 CEFR level alongside Biology (40%) and Chemistry (30%). The program is new (first cohort 2025-26) and the 2026/2027 intake is already closed — making this file relevant primarily for 2027/2028 planning.

The program's value proposition is real and regionally distinctive, but families should verify WFME accreditation status before committing, and should accept that there is currently no outcomes data to validate the clinical or professional preparation quality.

## Frequently Asked Questions

**Is the UF3 Medicine degree accepting applications for 2026/2027?**
No. The degree page explicitly states "Admisión cerrada para el curso 2026/2027." All 60 places have been filled. The next available intake is 2027/2028 — applications for that cycle are expected to open in autumn 2026 (ANNUAL_UPDATE_REQUIRED).

**Why is there an English component in the entrance exam?**
The UF3 entrance exam explicitly includes 25% English content at B1 CEFR level as an integral component of the multiple-choice exam. This is unique among major Spanish private medical school entrance tests. The university does not publicly explain the rationale, but it likely reflects the CEU group's emphasis on international preparation and the growing use of English in scientific literature and clinical communication.

**Do I need an English certificate to apply?**
No. English is tested within the internal entrance exam itself — you do not need to submit a separate IELTS, Cambridge, or other external certificate. Candidates prepare for the B1-level English content as part of the exam preparation.

**Is UF3 Medicine WFME-accredited?**
WFME accreditation status for UF3 is unconfirmed in publicly available materials. Families planning for international medical licensing (US, Canada, Australia, New Zealand) must contact the university directly to verify current WFME status before enrolling.

**Is this a morning or afternoon program?**
Afternoon (Turno tarde). This is explicitly stated in the official degree information. Students should factor this into transport, work, and scheduling decisions.

**What is the Nemesio Díez Foundation scholarship?**
The university offers 6 scholarships of €12,900 each per year for first-year Medicine students, in partnership with the Fundación Nemesio Díez. A full scholarship covers the entire honorarios component of Year 1 tuition. Only 6 scholarships are available per cohort of 60 students — a 10% scholarship rate for those who receive one. Application criteria and deadlines: PENDING_CONFIRMATION — contact the admissions office.

**How does the interview work? What is evaluated?**
A professor from the Medicine faculty conducts an individual interview. The professor evaluates: (1) academic record, (2) language level, and (3) interest in the Medicine degree. The admission decision is based on the professor's report. Students should be prepared to discuss their academic trajectory, language abilities, and motivation for studying Medicine.

**Are there clinical practices from Year 1?**
Yes. The program emphasizes "formación práctica desde el primer día" — practical training from the first day. The Hospital de Simulación on campus provides mandatory rotations with personalized tutoring. Clinical network agreements extend this into real hospital settings throughout the degree (1,665 hours total).

**Is Physics or Mathematics tested in the entrance exam?**
No. The UF3 entrance exam covers Biology (40%), Chemistry (30%), English (25%), and Scientific reasoning (5%). Physics and Mathematics are not included. Students who did not study Physics in bachillerato are not disadvantaged at UF3 in that respect — unlike CEU Cardenal Herrera.

**What is the total cost over 6 years?**
At the 2026-27 credit rate (€215/credit, 60 ECTS/year), the estimated 6-year total is approximately €83,250 — comprising €15,500 in Year 1 (including the €1,950 reservation fee) and approximately €13,550 per year in Years 2-6. Credit prices may increase annually (ANNUAL_UPDATE_REQUIRED). UF3 is among the least expensive private Medicine programs in Spain.
```