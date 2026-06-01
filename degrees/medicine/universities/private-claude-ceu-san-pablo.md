```md
---
id: ceu-sp-medicine

type: university
subtype: private

name: Universidad CEU San Pablo
short_name: CEU-SP

degree: Medicine

last_update: 2026-05-27

valid_for_intake: 2026-2027 # ANNUAL_UPDATE_REQUIRED

location:
  city: Madrid (Boadilla del Monte — Montepríncipe Campus)
  region: Community of Madrid
  country: Spain

strategic_tags:
  - core_option
  - exam_heavy
  - academic_record_heavy
  - english_advantage
  - rolling_admissions
  - early_application_advantage
  - bilingual_program
  - strong_clinical_exposure
  - research_oriented
  - high_cost
  - academic_exam_required
  - online_exam_available

admission:
  intake_month: September # ANNUAL_UPDATE_REQUIRED

  applications_open_date: October 15 # ANNUAL_UPDATE_REQUIRED

  rolling_admissions:
    enabled: true
    estimated_end_date: July 16, 2026 # ANNUAL_UPDATE_REQUIRED

  admission_rounds:
    enabled: true
    count: 3

    rounds:
      - round: 1
        application_deadline: November 6, 2025 # ANNUAL_UPDATE_REQUIRED
        exam_date: November 15, 2025 # ANNUAL_UPDATE_REQUIRED
        results_date: December 4, 2025 # ANNUAL_UPDATE_REQUIRED
        deposit_deadline: ANNUAL_UPDATE_REQUIRED

      - round: 2
        application_deadline: February 5, 2026 # ANNUAL_UPDATE_REQUIRED
        exam_date: February 14, 2026 # ANNUAL_UPDATE_REQUIRED
        results_date: March 4, 2026 # ANNUAL_UPDATE_REQUIRED
        deposit_deadline: ANNUAL_UPDATE_REQUIRED

      - round: 3
        application_deadline: March 25, 2026 # ANNUAL_UPDATE_REQUIRED
        exam_date: April 18, 2026 # ANNUAL_UPDATE_REQUIRED
        results_date: May 6, 2026 # ANNUAL_UPDATE_REQUIRED
        deposit_deadline: ANNUAL_UPDATE_REQUIRED

  exam_required: true
  interview_required: true

academic_record:
  minimum_requirement:
    enabled: PENDING_CONFIRMATION
    grade_source: first_year_baccalaureate
    minimum_grade: PENDING_CONFIRMATION

  competitive_filter:
    enabled: true
    grade_source: first_year_baccalaureate
    approx_candidates_selected: NULL

curriculum:
  international_curriculums_accepted: true

competitiveness:
  level: high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: 200
  applicants_per_seat: PENDING_CONFIRMATION

  last_admitted_scores:
    - intake_year: PENDING_CONFIRMATION
      round: PENDING_CONFIRMATION
      score: PENDING_CONFIRMATION
      score_type: PENDING_CONFIRMATION
      notes: No official cut-off scores published.

international_profile:
  international_students_percentage: PENDING_CONFIRMATION

  international_nationalities:
    - country: PENDING_CONFIRMATION
      percentage: PENDING_CONFIRMATION

programs:
  - id: ceu-sp-medicine-madrid

    campus: Montepríncipe Campus, Boadilla del Monte, Madrid

    modality: standard

    strategic_tags:
      - core_option
      - exam_heavy
      - academic_record_heavy
      - english_advantage
      - rolling_admissions
      - early_application_advantage
      - bilingual_program
      - strong_clinical_exposure
      - research_oriented
      - high_cost
      - academic_exam_required
      - online_exam_available

    teaching_languages:
      - Spanish
      - Spanish/English (bilingual groups — selected cohorts within the 200 seats)
      - English (new English-only group launching from 2026-27)

    regional_language_possible: false
    regional_language: NULL

    language_requirements:
      minimum_spanish_level_non_native: B2 (mandatory for bilingual track admission)

      english_required: true
      minimum_english_level: B2 (required for bilingual track; general proficiency expected across all tracks given the English component in the entrance exam)

    seats: 200

    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 200
      applicants_per_seat: PENDING_CONFIRMATION

      last_admitted_scores:
        - intake_year: PENDING_CONFIRMATION
          round: PENDING_CONFIRMATION
          score: PENDING_CONFIRMATION
          score_type: PENDING_CONFIRMATION
          notes: No official cut-off scores published.

    program_specific_admission:
      enabled: false

    evaluation_model:
      overall_model_type: pathway_based

      admission_pathways:

        - eligible_profiles:
            - Spanish Bachillerato students
            - Foreign secondary education equivalents
            - University graduates in non-health disciplines (Group 2)

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 0.60
              grade_source: first_year_baccalaureate
              minimum_required_grade: PENDING_CONFIRMATION
              notes: Only 1st-year baccalaureate grades count toward the admission score. PAU/EvAU must be passed (eliminatory prerequisite) but PAU grades are not included in the 60/40 scoring formula. Candidates without PAU results at enrollment deadline forfeit their pre-admission.

            - component: academic_exam
              enabled: true
              role: weighted
              weight: 0.40
              exam_variant: mixed_internal_exam
              exam_format: multiple_choice
              delivery_mode: hybrid
              online_conditions: Candidates may freely choose online or in-person delivery for each session. In-person at Montepríncipe Campus. Online sessions have an earlier in-person-only registration deadline.

              subjects:
                - Biology (Specific Test — combined with Chemistry)
                - Chemistry (Specific Test — combined with Biology)
                - English (General Test — separate component within the same exam)

              syllabus_alignment:
                biology:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: Internal university-designed exam. Exact syllabus scope not officially published. Likely covers standard Spanish bachillerato biology content. No sample papers publicly available.

                chemistry:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: Internal university-designed exam. Exact syllabus scope not officially published. Likely covers standard Spanish bachillerato chemistry content.

                physics:
                  scope:
                    - not_applicable
                  notes: Physics is not included in the CEU San Pablo entrance exam.

                mathematics:
                  scope:
                    - not_applicable
                  notes: Mathematics is not included in the CEU San Pablo entrance exam.

                other_subjects:
                  - subject: English (General Test)
                    scope:
                      - university_specific_syllabus
                    notes: General English proficiency test. Bilingual track requires a minimum score of 7 on this component. No negative marking applied to any part of the exam.

              exam_difficulty:
                level: PENDING_CONFIRMATION
                rationale:
                  - no_published_syllabus
                  - reasoning_based
                notes: No sample papers published. No negative marking — all questions should be answered. Up to 3 attempts (Nov, Feb, Apr); best score applies. Each attempt requires separate admission fee payment (€150).

              best_attempt_counts: 3
              notes: Three calls available per academic cycle (November, February, April). Candidates may sit all three; the highest score is used for ranking. Missing a session without cancellation forfeits the right and requires a new payment for subsequent sessions.

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
              notes: English is evaluated as the General Test component within the internal entrance exam. No separate English certificate required for the standard or bilingual admission process.

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
              weight: 0
              interview_format: structured
              delivery_mode: PENDING_CONFIRMATION
              notes: A mandatory personal interview with a faculty member is part of the application process. The interviewer evaluates academic background, language proficiency, and motivation. The interview outcome determines whether the application advances; it does not contribute to the 60/40 weighted score. Interview date can be modified up to 24 hours in advance.

            - component: complementary_points
              enabled: false
              role: bonus_only
              maximum_bonus: 0
              categories: []
              notes: No bonus or complementary points system in place.

        - eligible_profiles:
            - University graduates in Biology, Biomedicine, Pharmacy, Veterinary, Dentistry, Nursing, Physiotherapy, Optics, Psychology, Podiatry, Human Nutrition, Biotechnology, Speech Therapy, Neuroscience, Genetics, Medical Sciences, and Biochemistry (Group 3)
            - Students transferring from Medicine at another Spanish university (Group 4)

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: NULL
              grade_source: equivalent_secondary_record
              minimum_required_grade: PENDING_CONFIRMATION
              notes: Group 3 and 4 applicants are exempt from the internal entrance exam. Selection is based on academic documentation submitted. No weighted formula is published for this pathway. Group 4 (Medicine transfers) submit application from January 8 to May 24; results from June 16. Group 3 submit until July 3; results July 16.

            - component: academic_exam
              enabled: false
              role: NULL
              weight: 0
              exam_variant: NULL
              exam_format: NULL
              delivery_mode: NULL
              online_conditions: NULL
              subjects: []
              syllabus_alignment:
                biology:
                  scope:
                    - not_applicable
                  notes: Exam not required for Group 3/4.
                chemistry:
                  scope:
                    - not_applicable
                  notes: NULL
                physics:
                  scope:
                    - not_applicable
                  notes: NULL
                mathematics:
                  scope:
                    - not_applicable
                  notes: NULL
                other_subjects: []
              exam_difficulty:
                level: NULL
                rationale: []
                notes: NULL
              best_attempt_counts: NULL
              notes: Exempt from the entrance exam.

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
              notes: Not applicable.

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
              weight: 0
              interview_format: structured
              delivery_mode: PENDING_CONFIRMATION
              notes: Interview required as part of the process. Does not contribute to a weighted score formula.

            - component: complementary_points
              enabled: false
              role: bonus_only
              maximum_bonus: 0
              categories: []
              notes: NULL
---
# Universidad CEU San Pablo — Grado en Medicina

## Overview

Universidad CEU San Pablo is one of Spain's most established private medical schools, with over 50 years of continuous medical education in Madrid. The Facultad de Medicina operates from the Montepríncipe Campus in Boadilla del Monte, a purpose-built university environment approximately 15 km from central Madrid.

For the 2026-2027 intake, the program offers 200 seats across Spanish and bilingual teaching tracks, with an English-only cohort introduced for the first time. Admission is structured around three exam sessions (November, February, April), using an internal exam that covers Biology, Chemistry, and English. Critically, the weighted formula uses only 1st-year bachillerato grades — not EvAU — to represent 60% of the admission score, which is a structurally distinctive feature.

The university holds both WFME accreditation and WASC/WSCUC accreditation (2025-2031), making it the first institution in the European Union without American university status to receive the latter. It ranked in the Top 10 nationally for MIR results in 2024. These accreditations provide direct access to residency and licensing exams in the United States, Canada, Australia, and New Zealand.

The admission cost structure involves a €150 exam fee per session, a non-refundable €3,300 one-time reservation fee, and annual tuition of €19,500 at a credit price of €325 — placing it among the higher-cost private medical programs in Spain.

## Quick Evaluation

- **Seats:** 200 (Spanish, bilingual, and new English-only tracks combined)
- **Admission model:** 60% first-year bachillerato grades + 40% internal CEU exam (Biology, Chemistry, English)
- **PAU:** Mandatory prerequisite (must be passed) but not counted in the admission score
- **Exam sessions:** 3 (November, February, April) — online or in-person; best score counts
- **No negative marking** on the entrance exam — all questions should be answered
- **Interview:** Mandatory, qualitative gate — not scored in the final formula
- **WFME** accredited — global medical license eligibility
- **WASC/WSCUC** accredited (2025-2031) — first EU non-American institution; US/Canada/Australia/NZ access
- **MIR:** Top 10 nationally by results (2024)
- **Annual tuition (2026-27):** €19,500 + €3,300 one-time reservation fee
- **Bilingual track:** Spanish/English; minimum English score of 7 + B2 Spanish required
- **English-only track:** New from 2026-27 — no prior competitiveness data available
- **Applications open:** October 15 each year

## Key Facts

| Field | Value |
|---|---|
| University | Universidad CEU San Pablo |
| Degree | Grado en Medicina |
| Duration | 6 years |
| Total ECTS | 360 |
| Seats | 200 |
| Campus | Montepríncipe, Boadilla del Monte, Madrid |
| Language tracks | Spanish / Bilingual (ES/EN) / English-only (from 2026-27) |
| Annual tuition | €19,500 (2026-27) |
| Reservation fee | €3,300 (one-time, non-refundable) |
| Exam fee per session | €150 |
| Admission formula | 60% 1st-year bach + 40% internal exam |
| PAU requirement | Must be passed; not included in score |
| Accreditations | WFME, WASC/WSCUC (2025-2031) |
| MIR ranking | Top 10 (2024) |
| Employability | 95% |

## Program Options

The Grado en Medicina at CEU San Pablo operates under a single 6-year program structure (360 ECTS, Plan 2025) with three teaching-language configurations within the same 200-seat cohort:

**Spanish track:** Instruction primarily in Spanish. The standard track for domestic students following the Spanish bachillerato pathway.

**Bilingual track (Spanish/English):** A subset of seats within the 200-seat cohort. Instruction in both Spanish and English. Requires a minimum score of 7 on the English component of the entrance exam and proof of B2 Spanish level for non-native speakers. Students completing the bilingual track receive an additional Diploma Bilingüe from CEU San Pablo alongside the official degree.

**English-only group (new from 2026-27):** A fully English-delivered cohort launching for the first time in the 2026-2027 academic year. No historical competitiveness data is available for this track. Admission conditions for this track should be verified directly with the university. PENDING_CONFIRMATION on exact seat allocation within the 200.

All three tracks lead to the same official Spanish Medicine degree (Grado en Medicina, verified by ANECA) and follow the same curriculum structure under Plan 2025.

## Program Structure

The program is structured over 6 academic years with 360 ECTS credits under Plan 2025:

| ECTS Type | Credits |
|---|---|
| Basic sciences (Formación básica) | 90 |
| Core subjects (Obligatorias) | 195 |
| Electives (Optativas) | 6 |
| Clinical placements (Prácticas externas) | 61 |
| Final dissertation (TFG) | 8 |
| **Total** | **360** |

Years 1 and 2 focus on foundational biomedical sciences: Anatomy, Cell Biology, Biochemistry, Histology, Physics, Physiology, and Immunology. Practical work is conducted in small groups using fully equipped laboratories.

From Year 3, the program transitions to a hospital-based clinical learning environment, progressively increasing in complexity and autonomy. Clinical placements (Prácticas Clínicas I–IV) are distributed across Years 3 through 6, culminating in Year 6 with a 40-ECTS supervised clinical rotation with strong emphasis on clinical case resolution. A Trabajo Fin de Grado (TFG) of 8 ECTS is required in Year 6.

From Year 4 onwards, structured MIR preparation is integrated into the curriculum.

## Teaching Methodology

Teaching is designed around small-group learning, particularly for laboratory and clinical skill acquisition. The methodology combines classroom theory with hands-on laboratory sessions from the earliest years, avoiding the large-lecture-only model common in public medical schools.

From Year 3, learning is embedded in clinical settings under personal tutor supervision, with students assigned to hospital environments in a guided model rather than observational rotations alone.

The simulation infrastructure — including an on-campus hospital simulation centre, anatomy rooms with dissection facilities, genetics laboratories, histology laboratories, and cell culture labs — is integrated into the curriculum to develop procedural and diagnostic competencies before live patient contact.

The university has a dedicated mentoring infrastructure including a Buddy Program for new students and a Programa GPS personal mentoring scheme. The bilingual and English-track cohorts receive additional language-integrated instruction.

The program emphasizes Catholic values and humanistic formation, including subjects on Doctrina Social de la Iglesia and pastoral activities, which are part of the institutional identity of CEU.

## Clinical Training

Clinical training begins formally in Year 3 and extends through Year 6, with clinical placement ECTS increasing each year. CEU San Pablo's clinical network includes private and semi-public hospitals, primary care centres, and specialist institutions in the Community of Madrid:

**Hospital affiliations** (subject to ANNUAL_UPDATE_REQUIRED — network may evolve):
- Hospital Universitario Vithas Pardo-Aravaca
- Hospitales del Grupo VIAMED: Hospital Santa Elena and Hospital Fuensanta
- Hospital Universitario Nuestra Señora del Rosario
- Hospital Beata María Ana
- Hospital Universitario Infanta Cristina
- Centro Asistencial San Camilo
- Hospital Centro de Cuidados Laguna (Fundación Vianorte-Laguna)
- Centros de Salud de la Comunidad de Madrid (primary care)
- Residencias de Mayores de la Consejería de Sanidad de la Comunidad de Madrid
- SAMUR (emergency pre-hospital care)
- Additional centres under active university agreement

The on-campus Hospital Universitario de Simulación Clínica provides pre-clinical procedure training in a controlled environment before hospital rotations begin.

The clinical network is predominantly private and semi-public. Students do not rotate through large tertiary public hospitals (such as those in the SERMAS public network) as part of the standard program. This is a distinguishing feature versus programs with public hospital partnerships.

## International Recognition and Opportunities

**WFME (World Federation for Medical Education):** CEU San Pablo holds WFME accreditation, which enables graduates to apply for medical licensing and residency programs in the United States, Canada, Australia, and New Zealand.

**WASC/WSCUC accreditation (2025-2031):** CEU San Pablo received accreditation from the WASC Senior College and University Commission, recognized by the U.S. Department of Education. The university describes itself as the first institution in the European Union without American university affiliation to receive this accreditation. This was renewed for 2025-2031.

**International mobility confirmed for Medicine:** The Facultad de Medicina has specific exchange agreements including Medical College Wisconsin (USA), Università degli Studi di Roma La Sapienza (Italy), and Kristianstad University (Sweden), among others. Erasmus+ mobility is also available. The bilingual program includes a complementary Arizona University partnership component.

**Double international degrees and online international programs:** Available in the broader CEU ecosystem, though specific Medicine-track availability should be confirmed with the faculty.

The combination of WFME and WSCUC accreditation is one of the strongest international recognition profiles of any private medical school in Spain.

## Admission Model

CEU San Pablo uses a **pathway-based** admission model where the evaluation criteria differ depending on the applicant's educational background.

**Primary pathway (bachillerato and equivalent secondary education):**
The weighted score is calculated as:
- 60% — grades from 1st year of Bachillerato only (not EvAU, not 2nd year)
- 40% — CEU internal entrance exam (Biology + Chemistry Specific Test + English General Test)

The PAU/EvAU is a separate eliminatory prerequisite. Candidates who have been pre-admitted must pass the PAU ordinary call. PAU grades do not affect the 60/40 admission score.

**Exam structure:** Single internal exam with two components — a Specific Test (Biology and Chemistry, multiple choice) and a General Test (English, multiple choice). No negative marking applies to either component. The exam lasts from 10:00 to 13:00 (3 hours).

**Up to 3 attempts:** Candidates may sit all three sessions and the highest score is used. Missing a registered session without cancellation forfeits the attempt (fee not refunded); a new fee is required for subsequent sessions.

**Exempt pathway (health-related graduates):** Graduates from Medicine-adjacent degrees (Nursing, Pharmacy, Physiotherapy, Biomedicine, Veterinary, etc.) are exempt from the entrance exam. Admission is based on academic record review alone. This pathway is less relevant for typical Winners students.

**Medicine transfer pathway:** Students transferring from another university's Medicine program are exempt from the exam and follow a separate timeline.

An interview is mandatory for all pathways but functions as a qualitative assessment step, not a scored component.

## Admission Process

1. **Register online** at admision.uspceu.es from October 15. Provide personal data, academic record, and identification document.

2. **Receive PSP access** (Future Students Portal). Use the portal to track application status, schedule the exam, upload documents, and complete enrollment.

3. **Submit academic documentation and select interview date.** Interview date can be modified up to 24 hours in advance. Upload documents by the deadline for the chosen session.

4. **Sit the entrance exam** (online or in-person, Montepríncipe Campus). Pay the €150 admission fee per attempt.

5. **Await interview evaluation.** Once both the exam result and interview report are evaluated, an admission decision is issued.

6. **If admitted:** Pay the €3,300 reservation fee within the 5-day window specified in the admission notice. Failure to pay forfeits the pre-admission. This fee is non-refundable.

7. **Submit PAU results** by the university's deadline (approximately July 6 — ANNUAL_UPDATE_REQUIRED). Failure to submit implies voluntary withdrawal with no refund of advanced fees.

8. **Finalize enrollment** via the PSP: pay the enrollment fee, complete the registration form, submit bank details and sign the SEPA direct debit mandate.

Withdrawal from pre-enrollment or enrollment is only valid when communicated in writing to the Servicio de Admisión y Nuevo Alumno at info.usp@ceu.es.

## Admission Timeline

All dates are from the 2025-26 cycle and are subject to **ANNUAL_UPDATE_REQUIRED**.

| Session | Application Deadline | Exam Date | Results Published | In-person deadline |
|---|---|---|---|---|
| Session 1 | November 6, 2025 | November 15, 2025 | December 4, 2025 | October 30, 2025 |
| Session 2 | February 5, 2026 | February 14, 2026 | March 4, 2026 | January 29, 2026 |
| Session 3 | March 25, 2026 | April 18, 2026 | May 6, 2026 | March 20, 2026 |
| Group 3/4 (final) | July 3, 2026 | — | July 16, 2026 | — |

Applications for Group 1/2 open October 15. Session 1 is the earliest and typically sees the most competitive applications from the strongest academic profiles. Applying in Session 1 maximizes options: candidates who are not admitted can retake in Session 2 or 3 without losing the full cycle. Applying in Session 3 only is strategically high-risk as no further attempts remain in that cycle.

The in-person exam application deadline is earlier than the online deadline for each session — a point that catches some applicants off-guard.

## Admission Score Distribution

**Score formula for bachillerato pathway:**

$$\text{Admission Score} = 0.60 \times \text{(1st-year baccalaureate average)} + 0.40 \times \text{(CEU exam score)}$$

**Strategic implications of this structure:**

The 60% weight on 1st-year bachillerato grades is unusual among Spanish private medical schools. Most programs reference EvAU, 2nd-year bachillerato, or the full bachillerato average. Using exclusively 1st-year grades means that students who performed well in Year 1 but unevenly in Year 2 may actually benefit from this model. Conversely, students who improved significantly in Year 2 cannot use that improvement.

The 40% exam component (Biology + Chemistry + English) has no published official syllabus. The absence of negative marking is a meaningful strategic advantage: it removes the risk of guessing conservatively and rewards attempt completeness.

The English test within the 40% exam block is a differentiating factor for international students and strong English speakers. For the bilingual track specifically, a minimum of 7 on the English component acts as an additional filter, but no formal weight multiplier is disclosed for scoring purposes within that track.

Since the PAU is a separate prerequisite (not part of the 60/40 formula), admission score optimization must focus on maximizing both the 1st-year academic record and the CEU exam performance independently. A student with a strong 1st-year average but weak exam performance — or vice versa — may be at a disadvantage versus programs where EvAU compensates for record variability.

Cut-off scores for admitted cohorts are not published by the university. PENDING_CONFIRMATION on historical score distributions.

## Costs and Payment Structure

All values are for academic year 2026-27 and are subject to **ANNUAL_UPDATE_REQUIRED**.

**Annual tuition and fees (Degree in Medicine — both tracks):**

| Item | Spanish track | Bilingual track |
|---|---|---|
| Annual tuition | €19,500 | €19,500 |
| Price per ECTS credit | €325 | €325 |
| Credits (Year 1) | 60 ECTS | 60 ECTS |
| Monthly payment (9 months, Oct–Jun) | €2,166.67 | €2,166.67 |

**One-time and annual fixed fees:**

| Fee | Amount | Notes |
|---|---|---|
| Reservation fee (cuota de reserva) | €3,300 | One-time, paid at first enrollment. Non-refundable. |
| Enrollment fee Year 1 (2026-27) | €1,700 | ANNUAL_UPDATE_REQUIRED |
| Enrollment fee Year 2 (2027-28) | €4,200 | ANNUAL_UPDATE_REQUIRED — higher than other years |
| Enrollment fee Years 3–6 | €3,300/year | ANNUAL_UPDATE_REQUIRED |
| Admission exam fee | €150/session | Non-refundable. Required per attempt. |

**Total estimated cost at entry (Year 1):**

| Component | Amount |
|---|---|
| Reservation fee (one-time) | €3,300 |
| Enrollment fee Year 1 | €1,700 |
| Tuition Year 1 (60 ECTS × €325) | €19,500 |
| **Year 1 total** | **€24,500** |

**Payment options:**
- Monthly: 9 equal instalments (October–June) via SEPA direct debit
- Annual upfront: 3% discount on total academic fees (applied in September invoice)
- Credit validation fee for external credits: €40 per credit (CEU-to-CEU recognition is free)

**6-year estimated total tuition (at current 2026-27 rate, excluding fee increases):**

| Year | Annual Tuition | Enrollment Fee | Total per Year |
|---|---|---|---|
| 1 | €19,500 | €1,700 | €21,200 + €3,300 reservation |
| 2 | €19,500 | €4,200 | €23,700 |
| 3–6 | €19,500 | €3,300 | €22,800/year |

Total 6-year cost: approximately €138,800 at fixed current rates (ANNUAL_UPDATE_REQUIRED, and excluding annual price increases which are noted as possible in the official fee schedule).

## Scholarships and Financial Aid

CEU San Pablo describes its scholarship and financial aid program as "the largest investment of any university in Spain," but specific amounts and eligibility criteria for Medicine students are not detailed in publicly accessible course pages.

The main scholarship portal is at uspceu.com/admision-ayuda/becas-y-ayudas-grado (ANNUAL_UPDATE_REQUIRED). Known named scholarships (Barcia Goyanes, Marqués de Lozoya) are faculty-specific and apply to non-Medicine programs. No Medicine-specific scholarship denomination has been confirmed.

Additionally, the university participates in the general Spanish public scholarship system (MEC grants), which may be applicable to students who meet income and academic criteria.

Upfront payment of annual fees yields a 3% discount on the academic fee total (not on fixed fees such as the reservation or enrollment fee).

PENDING_CONFIRMATION: Specific scholarship types, amounts, and eligibility criteria for the Grado en Medicina.

## Accommodation and Cost of Living

The Montepríncipe Campus is located in Boadilla del Monte, approximately 15–20 km southwest of central Madrid. It is a suburban campus not directly served by the Madrid Metro. Students typically access the campus by university shuttle, bus, or private vehicle.

Students living in central Madrid face a commute and should factor in transport costs. University accommodation options on or near the Montepríncipe Campus exist but specific pricing is not listed on public-facing admissions pages.

Madrid's cost of living is among the highest in Spain, though generally lower than Barcelona. A student budget covering shared accommodation, food, transport, and study materials typically ranges from €1,000–€1,500/month in Madrid (outside university residence). Campus proximity to the university versus city-centre location will affect this significantly.

PENDING_CONFIRMATION: Official university accommodation rates and availability for Medicine students.

## International Exchange and Mobility Programs

International mobility for Medicine students has been confirmed for the following destinations (ANNUAL_UPDATE_REQUIRED — programs subject to bilateral agreement renewal):

- **Medical College Wisconsin** (USA)
- **Università degli Studi di Roma "La Sapienza"** (Italy)
- **Kristianstad University** (Sweden)
- **Erasmus+** mobility program (European network)
- **Arizona University** complement within the bilingual program structure

CEU San Pablo reports over 30 international agreements with universities and biomedical research centres globally.

The WASC/WSCUC accreditation facilitates formal recognition of the degree at accredited US institutions, which can be relevant for joint programs and alumni pursuing postgraduate pathways in North America.

Note: Specific exchange availability, semester timing, and seat allocation for Medicine should be confirmed with the Facultad de Medicina's international office before planning.

## MIR Preparation and Professional Outcomes

CEU San Pablo ranked in the **Top 10 nationally by MIR results in 2024**. The institution has consistently published this ranking metric as a core differentiator.

From Year 4, the program incorporates structured MIR preparation directly into the curriculum, building progressively toward exam readiness. This approach aims to develop both the clinical knowledge base and the exam-specific skills (high-volume multiple choice, time management, reasoning under pressure) required for strong MIR performance.

The university reports a **95% employability rate** for Medicine graduates.

PENDING_CONFIRMATION: MIR pass rate (%), top-specialty placement rates, and mean MIR score.

## Strategic Fit

### Good Fit For

- Students with a strong 1st-year bachillerato average (the entire 60% of the score is anchored to this, not EvAU)
- Students who benefit from multiple exam attempts: the 3-session structure with no negative marking and best-score-only counting is highly favorable for candidates who can improve over time
- Strong English speakers who want the English component of the CEU exam to work as an advantage, or who aim for the bilingual/English-only track
- Students targeting WFME-accredited Spanish degrees with confirmed US/Canada/Australia licensing pathway
- Students who value research exposure alongside clinical training (IMMA, international agreements)
- Students interested in studying in Madrid with a Catholic formation component
- International students (non-EU) who meet credential equivalence requirements — CEU accepts foreign secondary education and provides English-track access from 2026-27

### Less Suitable For

- Students whose strongest academic moment was 2nd-year bachillerato or EvAU (those grades do not count in CEU's formula)
- Students with budget constraints: at €24,500 in Year 1 (including fixed fees) and ~€138,800 over 6 years, this is among the more expensive options
- Students who need credit recognition from prior university studies — CEU has no published pathway for this in Medicine
- Students expecting rotation at large tertiary public hospitals in the Madrid SERMAS network — CEU's clinical network is private/semi-public
- Students applying late in the cycle (Session 3 only) with limited margin for score improvement

## Risks and Considerations

**1. Non-refundable reservation fee (€3,300).** This amount is forfeited if the student withdraws after pre-admission, regardless of circumstances outside those established in Spanish legislation. For families who apply to multiple universities, this creates a meaningful financial risk if held multiple deposits simultaneously.

**2. PAU as an independent constraint.** Admission score is locked at 60/40 based on 1st-year grades and the CEU exam. The PAU must then be passed separately as a condition of final enrollment. A student who is admitted but fails the PAU in the ordinary call loses the place (fee not refunded). Extraordinary call is not explicitly mentioned as a rescue option.

**3. 1st-year bachillerato as the academic record source.** This benefits students who peaked early but disadvantages those whose grades improved significantly in Year 2. Students should assess their profile honestly against this structure before prioritizing CEU San Pablo.

**4. No published exam syllabus.** The Bio/Chemistry entrance exam has no publicly available official syllabus or sample papers. This creates a preparation uncertainty relative to universities with published past papers or explicit topic lists.

**5. English-only track (2026-27) has no competitive track record.** Cut-off scores, seat allocation, and admission patterns for this track are unknown. Students applying to this track should be prepared for unpredictability in the first cycle.

**6. Bilingual track language gate.** Minimum score of 7 on the English component of the entrance exam and B2 Spanish proof are required for bilingual admission. Meeting the general 60/40 formula threshold is not sufficient for bilingual track placement.

**7. Year 2 enrollment fee increase.** The enrollment fee in Year 2 (2027-28 rate: €4,200) is notably higher than Year 1 (€1,700) and Years 3-6 (€3,300). This is a cash-flow consideration that can catch families off-guard if only the Year 1 cost is modeled at point of admission.

**8. Campus location.** Montepríncipe Campus is not in central Madrid. Students without a car or access to the university shuttle face a less convenient daily commute.

## Important Notes

- Applications for the **in-person exam option** have an earlier deadline than the online option in each session — this is separate from the general application deadline.
- The admission process **opens on October 15** each year; applying in Session 1 (November) offers the maximum number of retake opportunities within a single cycle.
- Missing a scheduled exam session without cancellation forfeits that session's fee and right; the student must pay again to sit the next session.
- The PAU grade submission deadline (approximately July 6 — ANNUAL_UPDATE_REQUIRED) is hard; failure to submit implies automatic withdrawal with no refund.
- The bilingual track diploma is an additional certificate — it does not produce a separate degree title.
- All three tracks (Spanish, bilingual, English) lead to the same official Grado en Medicina recognized by ANECA.
- Withdrawal from pre-enrollment or enrollment must be communicated in writing to info.usp@ceu.es to be legally effective.

## Key Insight

The structural decision to weight 60% of the admission score on 1st-year bachillerato grades exclusively — rather than EvAU or the full bachillerato — is the single most consequential feature of the CEU San Pablo admission model. It effectively decouples the admission outcome from university entrance exam (EvAU) performance, which is simultaneously an advantage for students who underperform on high-stakes standardized exams and a constraint for those whose academic trajectory improved from Year 1 to Year 2.

Combined with the no-negative-marking rule, three available exam attempts, and online delivery, the entrance exam itself is structured to reward preparation and persistence rather than penalize risk. For students who identify CEU San Pablo early and build their profile around this model, the admission path is methodical and manageable. For students applying as a late fallback, the session timing limits recovery margin significantly.

The WFME + WASC dual accreditation profile is the strongest internationally recognized combination among private Spanish medical schools, making CEU San Pablo a relevant option for international students and those with medium-to-long-term plans beyond Spain.

## Final Takeaway

Universidad CEU San Pablo offers a mature, research-active medical program in Madrid with a transparent and student-favorable rolling admissions model (3 sessions, no negative marking, best score counts). Its dual WFME and WSCUC accreditation provides the broadest international career access of any private Spanish medical school. The 2024 Top 10 MIR result is a concrete performance indicator.

The principal constraints are the premium cost structure (approximately €24,500 in Year 1, €22,800/year in Years 3-6, exclusive of living costs), the non-refundable €3,300 reservation fee, and the unique 1st-year-only academic record weighting that may not align with every student's grade profile. The new English-only track adds international accessibility but introduces uncertainty in its inaugural year.

Students with a strong 1st-year bachillerato record, solid Biology/Chemistry preparation, and meaningful English proficiency are well positioned for this program. The three-session structure makes early application and iterative improvement a viable and strategically sound approach.

## Frequently Asked Questions

**Does the EvAU/PAU grade affect admission to CEU San Pablo?**
No. The admission score uses 1st-year bachillerato grades (60%) and the CEU internal exam (40%) only. The PAU must be passed as a separate prerequisite, but the PAU grade does not influence the admission ranking or score.

**Can I take the entrance exam more than once?**
Yes. Three sessions are available (November, February, April). You may sit all three, and only the highest score is used. Each session requires a separate €150 payment. You must register for each session individually.

**Is the bilingual track an additional cost?**
No. Both Spanish and bilingual tracks are priced identically at €19,500/year for 60 ECTS (€325/credit). The bilingual track requires a minimum English component score of 7 and proof of B2 Spanish level for non-native speakers.

**What is the English-only track and when does it start?**
A new fully English-delivered cohort launches in the 2026-27 academic year. This is the first intake for this track, so no historical cut-off data or competitiveness benchmarks are available. Seat allocation within the 200 total seats is PENDING_CONFIRMATION.

**Is the reservation fee refundable?**
No. The €3,300 reservation fee is explicitly non-refundable except in circumstances established under Spanish law. It is paid once at first enrollment and does not recur in subsequent years.

**Is there clinical placement in public hospitals?**
No. CEU San Pablo's clinical network is composed of private and semi-public hospitals (Vithas, VIAMED, Infanta Cristina, etc.), primary care centres, and emergency services (SAMUR). Standard rotations in SERMAS public network hospitals are not part of the published program.

**What happens if I fail the PAU after being pre-admitted?**
The university states that candidates who have made pre-registration and fail the PAU ordinary call retain priority for enrollment upon passing the extraordinary call, as long as seats remain available. Failing the PAU entirely and not submitting results by the deadline (approximately July 6) is treated as voluntary withdrawal with no refund of advanced amounts.

**Can I validate prior university credits when enrolling at CEU San Pablo?**
Validated credit processing costs €40 per credit. Recognition between CEU group universities is free. However, the specific credit recognition policy for Medicine should be confirmed with the admissions office, as Medicine programs typically have limited recognition of prior credits.

**Does WFME accreditation mean I can work in the USA directly after graduation?**
WFME accreditation enables access to the USMLE licensing pathway and residency application processes in the US, Canada, Australia, and New Zealand. It does not automatically confer a license; it ensures the degree meets the standards required to begin those processes. WASC/WSCUC accreditation additionally facilitates formal degree recognition at US accredited institutions.

**When should I apply to maximize my chances?**
Applying in Session 1 (November) is strategically optimal because it allows two additional retake opportunities (Sessions 2 and 3) within the same cycle if needed. It also provides the earliest admission decision, which is valuable if managing multiple university applications simultaneously.
```