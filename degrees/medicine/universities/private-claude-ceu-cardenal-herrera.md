```md
---
id: ceu-ch-medicine

type: university
subtype: private

name: Universidad CEU Cardenal Herrera
short_name: CEU-CH

degree: Medicine

last_update: 2026-05-27

valid_for_intake: 2026-2027 # ANNUAL_UPDATE_REQUIRED

location:
  city: Castellón de la Plana / Valencia (Alfara del Patriarca)
  region: Valencian Community
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
  - onsite_exam_required

admission:
  intake_month: September # ANNUAL_UPDATE_REQUIRED

  applications_open_date: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED — process typically begins November

  rolling_admissions:
    enabled: true
    estimated_end_date: August 14, 2026 # ANNUAL_UPDATE_REQUIRED — waitlist active until this date

  admission_rounds:
    enabled: true
    count: 2

    rounds:
      - round: 1
        application_deadline: January 26, 2026 # ANNUAL_UPDATE_REQUIRED (23:59)
        exam_date: January 31, 2026 # ANNUAL_UPDATE_REQUIRED
        results_date: February 11, 2026 # ANNUAL_UPDATE_REQUIRED
        deposit_deadline: ANNUAL_UPDATE_REQUIRED # 7 natural days from admission notice

      - round: 2
        application_deadline: April 20, 2026 # ANNUAL_UPDATE_REQUIRED
        exam_date: April 25, 2026 # ANNUAL_UPDATE_REQUIRED
        results_date: May 7, 2026 # ANNUAL_UPDATE_REQUIRED
        deposit_deadline: ANNUAL_UPDATE_REQUIRED # 7 natural days from admission notice

  exam_required: true
  interview_required: false

academic_record:
  minimum_requirement:
    enabled: true
    grade_source: first_year_baccalaureate
    minimum_grade: 7 # Out of 10; applies to bachillerato, foreign equivalent, and university graduate routes

  competitive_filter:
    enabled: true
    grade_source: first_year_baccalaureate
    approx_candidates_selected: NULL

curriculum:
  international_curriculums_accepted: true

competitiveness:
  level: high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION # Castellón session 1 alone: 443 applicants reported
  seats: 70 # Castellón campus confirmed; Valencia seats PENDING_CONFIRMATION
  applicants_per_seat: PENDING_CONFIRMATION

  last_admitted_scores:
    - intake_year: PENDING_CONFIRMATION
      round: PENDING_CONFIRMATION
      score: PENDING_CONFIRMATION
      score_type: PENDING_CONFIRMATION
      notes: No official cut-off scores published. Reported 443 applicants for Castellón campus (inaugural intake).

international_profile:
  international_students_percentage: PENDING_CONFIRMATION

  international_nationalities:
    - country: PENDING_CONFIRMATION
      percentage: PENDING_CONFIRMATION

programs:
  - id: ceu-ch-medicine-castellon

    campus: Castellón Campus, Castellón de la Plana

    modality: standard

    strategic_tags:
      - core_option
      - exam_heavy
      - academic_record_heavy
      - rolling_admissions
      - early_application_advantage
      - strong_clinical_exposure
      - high_cost
      - academic_exam_required
      - onsite_exam_required

    teaching_languages:
      - Spanish

    regional_language_possible: true
    regional_language: Valencian (Catalan) — context only; instruction is in Spanish

    language_requirements:
      minimum_spanish_level_non_native: B1 (required for non-native Spanish speakers)

      english_required: false
      minimum_english_level: NULL

    seats: 70

    program_statistics:
      annual_applications: PENDING_CONFIRMATION # 443 applicants reported in inaugural intake across sessions
      seats: 70
      applicants_per_seat: PENDING_CONFIRMATION # Approximately 6:1 ratio based on 443 reported applicants

      last_admitted_scores:
        - intake_year: PENDING_CONFIRMATION
          round: PENDING_CONFIRMATION
          score: PENDING_CONFIRMATION
          score_type: PENDING_CONFIRMATION
          notes: No official cut-off scores published.

    program_specific_admission:
      enabled: false

    evaluation_model:
      overall_model_type: weighted_plus_bonus

      admission_pathways:
        - eligible_profiles:
            - Spanish Bachillerato students
            - Foreign secondary education equivalents (studied in Spain in the Spanish system)
            - CFGS/FP graduates (minimum grade 9; health-related branch)
            - University graduates in health-related fields (minimum grade 7)
            - Mayores de 25/45 años (minimum grade 9, passed access exam in health branch)
            - Students from non-completed university studies (minimum grade 7 in 1st year bach)

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 0.60
              grade_source: first_year_baccalaureate
              minimum_required_grade: 7
              notes: Only 1st-year baccalaureate grades (or equivalent) are used in the admission formula. PAU/Selectividad must be passed as a separate eliminatory prerequisite but PAU grades do not contribute to the scoring formula. Failure to pass PAU results in loss of admission and waitlist position.

            - component: academic_exam
              enabled: true
              role: weighted
              weight: 0.40
              exam_variant: onsite_internal_exam
              exam_format: multiple_choice
              delivery_mode: onsite
              online_conditions: NULL — EPAM is always in-person at Castellón campus. International candidates who studied outside the Spanish system take EPOAM online instead.

              subjects:
                - Biology (35 questions)
                - Chemistry (15 questions)
                - Physics and Mathematics (15 questions, combined)
                - Reading Comprehension of a Scientific Article (10 questions)

              syllabus_alignment:
                biology:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: University-designed internal exam (EPAM). 35 of 75 questions. Exact syllabus not published. Likely covers Spanish bachillerato biology content.

                chemistry:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: University-designed internal exam. 15 of 75 questions.

                physics:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: Physics and Mathematics are combined into a 15-question block. Physics/Math is present in the EPAM — a notable difference from CEU San Pablo which does not include physics or math.

                mathematics:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: Combined with Physics in a 15-question block.

                other_subjects:
                  - subject: Reading Comprehension (Scientific Article)
                    scope:
                      - university_specific_syllabus
                    notes: 10 questions based on a published scientific article. Tests academic reading ability in Spanish (or English for non-native Spanish speakers). No prior topic knowledge required.

              exam_difficulty:
                level: PENDING_CONFIRMATION
                rationale:
                  - no_published_syllabus
                  - reasoning_based
                  - physics_required
                  - mathematics_required
                notes: EPAM covers 4 subject areas including Physics/Mathematics, which distinguishes it from other private medical school exams that focus only on Biology and Chemistry. No negative marking applied. Exam available in English for non-native Spanish speakers.

              best_attempt_counts: 2
              notes: Two sessions per academic cycle (January 31 and April 25). Both scores are submitted; the highest is used. Each session requires a separate €75 fee. Missing a registered session forfeits that session's right; re-registration and new fee required for the second session.

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
              notes: English level not part of the scoring formula for the Spanish (Castellón) track.

            - component: psychometric_test
              enabled: false
              role: NULL
              weight: 0
              test_format: NULL
              delivery_mode: NULL
              online_conditions: NULL
              notes: Not required.

            - component: interview
              enabled: false
              role: NULL
              weight: 0
              interview_format: NULL
              delivery_mode: NULL
              notes: No interview required for Medicina (Castellón). Interview is part of the general CEU UCH admissions process for other degrees but not for Medicine specifically.

            - component: complementary_points
              enabled: true
              role: bonus_only
              maximum_bonus: 2
              categories:
                - category: CEU school alumni (primary + secondary)
                  max_points: 1.5
                - category: CEU CFGS
                  max_points: 0.45
                - category: CEU university graduates or students
                  max_points: 1.0
                - category: Siblings or first-degree relatives at CEU
                  max_points: 0.5
                - category: Children of CEU employees or clinical tutors
                  max_points: 1.0
                - category: Municipal registration (empadronamiento) in Castellón province
                  max_points: 0.5
              notes: All categories are cumulative up to the 2-point maximum. CEU loyalty bonus (school, CFGS, university) can reach up to 1.5 pts. The empadronamiento bonus (0.5 pts) applies to the Castellón campus specifically. These bonus points can meaningfully affect final ranking, especially when competition is tight.

        - eligible_profiles:
            - International candidates who completed pre-university studies outside Spain and outside the Spanish educational system (EPOAM route)

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 0.60
              grade_source: equivalent_secondary_record
              minimum_required_grade: 7
              notes: Same 60% weighting applies using equivalent foreign academic record. Must have credential (homologación) or equivalent. EPOAM candidates cannot later switch to EPAM.

            - component: academic_exam
              enabled: true
              role: weighted
              weight: 0.40
              exam_variant: online_internal_exam
              exam_format: multiple_choice
              delivery_mode: online
              online_conditions: EPOAM is fully online. Same structure as EPAM (75 questions, 120 min, Biology 35/Chemistry 15/Physics-Math 15/Reading 10). Available in English for non-native Spanish speakers.

              subjects:
                - Biology (35 questions)
                - Chemistry (15 questions)
                - Physics and Mathematics (15 questions)
                - Reading Comprehension of a Scientific Article (10 questions)

              syllabus_alignment:
                biology:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: Same as EPAM.
                chemistry:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: Same as EPAM.
                physics:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: Same as EPAM.
                mathematics:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: Same as EPAM.
                other_subjects:
                  - subject: Reading Comprehension (Scientific Article)
                    scope:
                      - university_specific_syllabus
                    notes: Same as EPAM.

              exam_difficulty:
                level: PENDING_CONFIRMATION
                rationale:
                  - no_published_syllabus
                  - reasoning_based
                notes: Same structure as EPAM, online format.

              best_attempt_counts: 2
              notes: Two sessions (January 31 and April 25). Highest score used.

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
              notes: Not applicable for Spanish track.

            - component: psychometric_test
              enabled: false
              role: NULL
              weight: 0
              test_format: NULL
              delivery_mode: NULL
              online_conditions: NULL
              notes: Not required.

            - component: interview
              enabled: false
              role: NULL
              weight: 0
              interview_format: NULL
              delivery_mode: NULL
              notes: Not required.

            - component: complementary_points
              enabled: true
              role: bonus_only
              maximum_bonus: 2
              categories:
                - category: CEU school alumni
                  max_points: 1.5
                - category: CEU CFGS
                  max_points: 0.45
                - category: CEU university graduates or students
                  max_points: 1.0
                - category: Siblings or first-degree relatives at CEU
                  max_points: 0.5
                - category: Children of CEU employees or clinical tutors
                  max_points: 1.0
                - category: Municipal registration in Castellón province
                  max_points: 0.5
              notes: Same cumulative 2-point maximum.

  - id: ceu-ch-medicine-valencia

    campus: Valencia Campus (Alfara del Patriarca / Moncada), Valencia

    modality: bilingual

    strategic_tags:
      - core_option
      - exam_heavy
      - academic_record_heavy
      - english_advantage
      - rolling_admissions
      - early_application_advantage
      - bilingual_program
      - strong_clinical_exposure
      - high_cost
      - academic_exam_required
      - onsite_exam_required

    teaching_languages:
      - Spanish
      - English (first 2 years + part of Year 3 — approximately 165 ECTS total in English)

    regional_language_possible: true
    regional_language: Valencian (Catalan) — context only; not a teaching language

    language_requirements:
      minimum_spanish_level_non_native: B1 (required for all; additional points for higher Spanish levels for non-native speakers)

      english_required: true
      minimum_english_level: B1 (minimum to sit the entrance exam for the bilingual track)

    seats: PENDING_CONFIRMATION # Valencia bilingual seat allocation not published on official pages

    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: PENDING_CONFIRMATION
      applicants_per_seat: PENDING_CONFIRMATION

      last_admitted_scores:
        - intake_year: PENDING_CONFIRMATION
          round: PENDING_CONFIRMATION
          score: PENDING_CONFIRMATION
          score_type: PENDING_CONFIRMATION
          notes: No official cut-off scores published for Valencia bilingual track.

    program_specific_admission:
      enabled: false

    evaluation_model:
      overall_model_type: weighted_plus_bonus

      admission_pathways:
        - eligible_profiles:
            - Spanish Bachillerato students with certified English B1 or above
            - Foreign secondary education equivalents with certified English B1 or above
            - CFGS/FP graduates (minimum grade 9; health-related branch)
            - University graduates in health-related fields (minimum grade 7)

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 0.60
              grade_source: first_year_baccalaureate
              minimum_required_grade: 7
              notes: Same 60% academic record weighting as the Castellón track. Only 1st-year baccalaureate grades count. PAU required as eliminatory prerequisite; grade not included in formula.

            - component: academic_exam
              enabled: true
              role: weighted
              weight: 0.35
              exam_variant: onsite_internal_exam
              exam_format: multiple_choice
              delivery_mode: onsite
              online_conditions: NULL — EPAM is in-person at Alfara del Patriarca campus. International candidates via EPOAM take it online.

              subjects:
                - Biology (35 questions)
                - Chemistry (15 questions)
                - Physics and Mathematics (15 questions, combined)
                - Reading Comprehension of a Scientific Article (10 questions)

              syllabus_alignment:
                biology:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: Same exam as Castellón track; Biology 35 questions.

                chemistry:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: Chemistry 15 questions.

                physics:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: Physics/Math 15 questions combined.

                mathematics:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: Combined with Physics.

                other_subjects:
                  - subject: Reading Comprehension (Scientific Article)
                    scope:
                      - university_specific_syllabus
                    notes: 10 questions. Available in English for non-native Spanish speakers.

              exam_difficulty:
                level: PENDING_CONFIRMATION
                rationale:
                  - no_published_syllabus
                  - reasoning_based
                  - physics_required
                  - mathematics_required
                notes: Identical exam to Castellón EPAM. The exam weight is reduced to 35% vs 40% for Castellón to accommodate the 5% English level component.

              best_attempt_counts: 2
              notes: Same two sessions (January 31 and April 25). Best score used. €75 per session.

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
              enabled: true
              role: weighted
              weight: 0.05
              test_format: certificate
              delivery_mode: not_applicable
              online_conditions: NULL
              minimum_level: B1 (required to sit the exam; B1 = 0 points in formula)
              bonus_max: NULL
              bonus_scale:
                B2: 0.02 # 2% = 0.2 points on a 10-point scale
                C1: 0.04 # 4% = 0.4 points
                C2: 0.05 # 5% = 0.5 points (maximum)
              notes: English certification required at B1 minimum to sit the entrance exam for the bilingual track. B1 is a gate requirement only (0 points). Higher levels (B2, C1, C2) contribute up to 0.5 points on a 10-point scale. CEU UCH offers English level tests through its language service at set dates throughout the year for candidates without existing certificates.

            - component: psychometric_test
              enabled: false
              role: NULL
              weight: 0
              test_format: NULL
              delivery_mode: NULL
              online_conditions: NULL
              notes: Not required.

            - component: interview
              enabled: false
              role: NULL
              weight: 0
              interview_format: NULL
              delivery_mode: NULL
              notes: No interview required for Medicine bilingual track.

            - component: complementary_points
              enabled: true
              role: bonus_only
              maximum_bonus: 2
              categories:
                - category: CEU school alumni (primary + secondary)
                  max_points: 1.5
                - category: CEU CFGS
                  max_points: 0.45
                - category: CEU university graduates or students
                  max_points: 1.0
                - category: Siblings or first-degree relatives at CEU
                  max_points: 0.5
                - category: Children of CEU employees or clinical tutors
                  max_points: 1.0
                - category: Municipal registration (empadronamiento) in Valencia province
                  max_points: 0.5
                - category: Spanish language certification (non-native speakers applying to bilingual track)
                  max_points: 1.2
              notes: All categories cumulative up to 2-point maximum. For the bilingual track, non-native Spanish speakers can receive up to 1.2 complementary points for Spanish certification level (A1=0.2, A2=0.4, B1=0.6, B2=0.8, C1=1.0, C2=1.2). Empadronamiento bonus applies to Valencia province for this campus.
---
# Universidad CEU Cardenal Herrera — Grado en Medicina / Grado en Medicine

## Overview

Universidad CEU Cardenal Herrera (CEU UCH) offers the Grado en Medicina across two campuses in the Valencian Community: a Spanish-language program at the Castellón campus (70 confirmed seats) and a bilingual Spanish/English program at the Valencia campus in Alfara del Patriarca. Both programs are WFME-accredited and follow the same 6-year, 360-ECTS curriculum structure.

CEU UCH is notably positioned as the most international university in the Valencian Community, with students from over 100 nationalities. The programs stand out for clinical practices from Year 1, a pioneering US clinical rotation program (Chicago and New York), and integrated MIR preparation from Year 3 through a formal partnership with the AMIR academy. The university is also one of the few in Spain to partner with the Fundación para la Formación de la Organización Médica Colegial (FFOMC) in Medicine program design.

The admission model is built around a two-session structure (January and April) using an internal exam (EPAM) that covers Biology, Chemistry, Physics/Mathematics, and Reading Comprehension of a scientific article. Notably, Physics and Mathematics are included — making this exam structurally broader than most private medical school entrance tests. The formula weights 60% academic record (1st-year bachillerato) and 40% exam for Castellón, or 35% exam + 5% English level for Valencia bilingual.

Annual tuition at the Castellón campus is confirmed at €18,850 (2026-27) with a credit price of €230 — among the more accessible pricing structures for private medicine in Spain.

## Quick Evaluation

- **Seats:** 70 (Castellón, confirmed); PENDING_CONFIRMATION (Valencia bilingual)
- **Two campuses:** Castellón (Spanish) and Alfara del Patriarca/Valencia (Bilingual ES/EN)
- **Admission formula (Castellón):** 60% 1st-year bach + 40% EPAM + up to 2 bonus pts
- **Admission formula (Valencia):** 60% 1st-year bach + 35% EPAM + 5% English level + up to 2 bonus pts
- **PAU:** Must be passed separately; grade not counted
- **Exam (EPAM):** Biology (35Q) + Chemistry (15Q) + Physics/Math (15Q) + Reading comprehension (10Q) — 75 questions, 120 min, in-person, no negative marking
- **Two exam sessions:** January 31 and April 25; best score used
- **No interview** for Medicine
- **WFME** accredited — both campuses
- **Annual tuition (Castellón 2026-27):** €18,850 total / €230 per credit
- **Practices from Year 1**
- **MIR prep from Year 3** via AMIR academy
- **US Clinical Rotation Program** (Chicago and New York) — first in Spain
- **Diploma Universitario de Experto en Medicina Clínica y Diagnóstica** — free from Year 3
- **Minimum grade:** 7 (1st-year bach); B1 English for bilingual track

## Key Facts

| Field | Value |
|---|---|
| University | Universidad CEU Cardenal Herrera (CEU UCH) |
| Degree | Grado en Medicina (Castellón) / Grado en Medicine (Valencia bilingual) |
| Duration | 6 years |
| Total ECTS | 360 |
| Seats (Castellón) | 70 |
| Seats (Valencia bilingual) | PENDING_CONFIRMATION |
| Campuses | Castellón / Alfara del Patriarca (Valencia) |
| Language | Spanish (Castellón) / Bilingual ES/EN (Valencia) |
| Annual tuition (Castellón 2026-27) | €18,850 |
| Credit price (Castellón) | €230 |
| Exam fee per session | €75 |
| Admission formula (Castellón) | 60% bach + 40% exam + 2 bonus |
| Admission formula (Valencia) | 60% bach + 35% exam + 5% English + 2 bonus |
| PAU requirement | Must be passed; not included in score |
| Accreditation | WFME (both campuses) |
| MIR preparation | From Year 3 with AMIR academy |
| Practices | From Year 1 |
| US Rotations | Chicago and New York (first in Spain) |

## Program Options

CEU UCH offers two distinct Medicine programs:

**Grado en Medicina — Castellón Campus (Spanish):**
Full program in Spanish. 70 seats. Located in Castellón de la Plana. Standard Spanish admission pathway (EPAM in-person, 40% exam weight). Tuition €18,850/year.

**Grado en Medicine — Valencia Campus (Bilingual Spanish/English):**
Bilingual program at Alfara del Patriarca (greater Valencia). Instruction in English during the first two years and part of Year 3 (approximately 165 ECTS in English total); remaining years in Spanish. Seat allocation not published. Requires minimum B1 English certification to apply. Tuition figures for the bilingual track not publicly available in page text (ANNUAL_UPDATE_REQUIRED; typically higher than Spanish track due to bilingual surcharge model).

**Diploma Universitario de Experto en Medicina Clínica y Diagnóstica:**
Both campuses offer this additional diploma free of charge from Year 3. It runs in parallel with the degree and is designed to accelerate clinical competency. This dual-award option appears in the formal plan de estudios as a combined track (e.g., "Grado (grupo en inglés/español) + DUE en Medicina Clínica y Diagnóstica"). This is a distinctive free add-on not offered by most competitors.

Candidates may apply to both campuses simultaneously. If admitted for the first-preference campus, the second preference is removed. If admitted for the second preference only, the candidate is placed on the waitlist for the first.

## Program Structure

Both programs share the same 6-year, 360-ECTS structure under Plan 2025:

| ECTS Type | Credits |
|---|---|
| Basic sciences | PENDING_CONFIRMATION — plan de estudios loaded dynamically on website |
| Core clinical subjects | PENDING_CONFIRMATION |
| Electives | PENDING_CONFIRMATION |
| Clinical placements | PENDING_CONFIRMATION |
| Final dissertation (TFG) | PENDING_CONFIRMATION |
| **Total** | **360** |

The program integrates clinical exposure from Year 1 — earlier than most private medical programs, which typically begin clinical placements in Year 3. Years 1 and 2 combine foundational biomedical sciences with early practical contact. The bilingual track delivers the first two years and part of Year 3 (approximately 165 ECTS) in English.

Structured MIR preparation begins from Year 3 in partnership with AMIR academy, integrating exam-readiness training progressively through the final three years.

The TFG (Final Dissertation) and the option to obtain the free Diploma Universitario de Experto en Medicina Clínica y Diagnóstica are both formally incorporated into the plan de estudios tracks.

## Teaching Methodology

Teaching emphasizes early clinical contact (from Year 1), simulation-based training, small-group laboratory work, and progressive clinical autonomy. The methodology is explicitly structured to train students toward MIR readiness as an integrated outcome rather than a post-graduation add-on.

Two Advanced Clinical Simulation Centers on campus are equipped with hospital-grade mannequins and procedure rooms modeled after real hospital environments (rooms, operating theatres). The ECOE (Objective Structured Clinical Examination) assessments are accredited by the Conferencia Nacional de Decanos de las Facultades de Medicina Española.

The bilingual track integrates English-medium instruction at the conceptual and clinical reasoning level, not merely as a language overlay. Free English classes are available to all enrolled students throughout the degree.

The university's program design was developed in collaboration with the FFOMC (Fundación para la Formación de la Organización Médica Colegial), making CEU UCH one of the few Spanish medical schools to have formal input from the Spanish medical professional body in its curriculum.

A Plan de Excelencia Académica is available for top-performing students, involving additional competency development in collaboration with high-profile companies.

## Clinical Training

Clinical training starts from Year 1 and expands across the full 6 years. CEU UCH works with over 20 public and private health centres in the Valencian Community.

**Clinical network** (subject to ANNUAL_UPDATE_REQUIRED — partnerships may evolve):
- Hospital General de Castellón
- Hospital La Fe (Valencia)
- Hospital General de Alicante
- Hospital General de Elche
- Hospital La Magdalena
- Hospital La Ribera
- Hospital Marina Baixa
- Hospital Torrevieja Salud
- IVO (Instituto Valenciano de Oncología)
- IMED
- Quirón Salud (Valencia network)
- Vithas (Valencia network)
- Consorci Hospitalari Castelló
- Savia
- Dénia Salut
- CVF
- Hospital Beata (Baviera)
- UNIMAT
- GVA FIM
- Additional centres under active agreement

The mix of public hospital affiliations (La Fe, Hospital General de Castellón, Hospital General de Alicante, Hospital General de Elche) is a distinguishing feature versus programs with exclusively private clinical networks.

**US Clinical Rotation Program (Programa CEU UCH – AMOpportunities):** Described by the university as the first clinical rotation program in the USA offered by a Spanish university. Students complete rotations in prestigious hospitals and health centres in Chicago and New York. This is a concrete international clinical credential that differentiates this program from most competitors.

The on-campus simulation centres supplement hospital rotations with pre-clinical skills development.

## International Recognition and Opportunities

**WFME (World Federation for Medical Education):** Both the Castellón and Valencia programs hold WFME accreditation, enabling graduates to apply for medical licensing and residency programs in the United States, Canada, Australia, and New Zealand.

**THE World University Ranking:** CEU is ranked among the top 600 universities globally and 9th nationally in the THE World University Ranking.

**ANECA and AVAP accreditation:** Both campuses hold institutional accreditation from ANECA and evaluation by AVAP (Agència Valenciana d'Avaluació i Prospectiva).

**CeQuInt** quality seal (EU-level international quality label).

**International mobility:** The university describes itself as the most international university in the Valencian Community, with over 100 student nationalities. A Global Citizen Program certification is available. Erasmus+ and international exchange programs are available (specific Medicine exchanges: PENDING_CONFIRMATION for named destinations).

**US Clinical Rotation Program** provides confirmed access to clinical rotations in Chicago and New York hospitals — a direct international clinical experience within the degree structure.

## Admission Model

CEU UCH uses a **weighted-plus-bonus** model with two distinct formulas depending on campus.

**Castellón (Spanish track):**
$$\text{Score} = 0.60 \times \text{(1st-year bach average)} + 0.40 \times \text{(EPAM score)} + \text{bonus (0–2 pts)}$$

**Valencia (Bilingual track):**
$$\text{Score} = 0.60 \times \text{(1st-year bach average)} + 0.35 \times \text{(EPAM score)} + 0.05 \times \text{(English level)} + \text{bonus (0–2 pts)}$$

In both cases, the PAU/Selectividad is a mandatory external prerequisite — must be passed in the June session — but the PAU grade is excluded from the formula. Failing PAU or failing to submit it by the university deadline results in loss of the admission and any waitlist position.

**EPAM structure (both campuses — same exam):**
- 75 multiple-choice questions
- 120 minutes
- Biology: 35 questions
- Chemistry: 15 questions
- Physics and Mathematics: 15 questions (combined block)
- Reading Comprehension of a scientific article: 10 questions
- No negative marking
- Available in English for non-native Spanish speakers
- In-person at the campus of the chosen program preference (Castellón or Alfara del Patriarca)

**EPOAM:** International candidates who studied outside Spain and outside the Spanish system take the same exam online. EPOAM → EPAM switching is not permitted.

**No interview** is required for Medicine (unlike most other degrees at CEU UCH).

The bonus points system (up to 2 additional points) favors students from the CEU school network, CEU alumni families, and those registered in the respective province. These can be determinant in close competitions.

## Admission Process

1. **Register online** at admision.uchceu.es. Select preference order: Medicina Castellón and/or Medicine bilingüe Valencia.

2. **Receive intranet credentials** via email. Use the intranet portal to manage the full application.

3. **Pay the €75 exam fee** via credit card through the intranet.

4. **Upload documentation** within the session deadline (January 26 for Session 1; April 20 for Session 2).

5. **Sit the EPAM** in-person at the campus corresponding to first preference. Exam: 13:00, 120 minutes.

6. **Receive admission resolution** (February 11 for Session 1; May 7 for Session 2). If waitlisted: 48-hour response window when a place becomes available.

7. **If admitted:** 7 natural days to make the first payment (plaza reservation). University contacts for enrollment within 15 natural days of that payment.

8. **Submit PAU results.** Must pass PAU/Selectividad in the June ordinary call (or provide the equivalent credential for foreign bachillerato). Failure results in loss of admission and waitlist position.

9. **Finalize enrollment** through the intranet.

For **Medicine transfer students** (traslado de expediente from another Medicine program): separate timeline — documentation deadline July 2, resolution from July 16. Minimum 30 ECTS completed.

Withdrawal from the reservation must be communicated in writing. Refund of reservation fee is possible if requested before June 16, 2026, or via 14-day legal right of withdrawal after payment (for reservations made after June 16).

## Admission Timeline

All dates are from the 2025-26 cycle and are subject to **ANNUAL_UPDATE_REQUIRED**.

| Event | Session 1 | Session 2 |
|---|---|---|
| Documentation deadline | January 26, 2026 (23:59) | April 20, 2026 |
| Exam (EPAM/EPOAM) | January 31, 2026 | April 25, 2026 |
| Admission results | February 11, 2026 | May 7, 2026 |
| Reservation payment window | 7 natural days from notice | 7 natural days from notice |
| PAU deadline | June session (extraordinary call for exceptional cases) | — |
| Transfer applications (traslado) | January 8 – July 2, 2026 | Resolution from July 16 |
| Waitlist closes | Approximately August 14, 2026 | — |

With only two sessions (versus three at some competitors), the strategic risk of applying in Session 2 only is significant: no further attempts remain in that cycle. Applying in Session 1 is optimal as it allows a second attempt with the highest score used.

CEU UCH offers English/Spanish level tests through its language service at six dates (November 19, December 17, January 14, February 11, March 4, April 15) — useful for candidates who need to certify their English level for the bilingual track or Spanish level for complementary points.

## Admission Score Distribution

**Castellón formula:**

$$\text{Score} = 0.60 \times \text{(1st-year bach)} + 0.40 \times \text{(EPAM)} + \text{bonus (0–2)}$$

**Valencia bilingual formula:**

$$\text{Score} = 0.60 \times \text{(1st-year bach)} + 0.35 \times \text{(EPAM)} + 0.05 \times \text{(English)} + \text{bonus (0–2)}$$

**Strategic implications:**

The inclusion of Physics and Mathematics in the EPAM is the most critical structural difference versus other private medical school exams. Students who have a strong Science Bachillerato background (Biology + Chemistry + Physics) are well suited. Students who chose an Arts or Social Sciences bachillerato stream may face an unexpected challenge in the Physics/Math block.

The Reading Comprehension component (10 of 75 questions) is unusual. It tests academic literacy over a scientific article — language comprehension and critical reading rather than memorized content. This is less preparation-sensitive than the science questions and should not be a primary focus of study, but it is non-negligible at 13% of the exam.

The 60% academic weight (1st-year bach only) reflects the same structural characteristic as CEU San Pablo — PAU/EvAU performance is irrelevant to ranking. A student with a strong Year 1 record but weak Year 2 trajectory may benefit.

The bonus system (up to 2 points) can significantly affect ranking in a cohort of 70 seats. CEU school alumni with maximum loyalty points (1.5 pts) plus empadronamiento (0.5 pts) could reach the 2-point cap — a 2-point advantage on a 10-point scale is structurally meaningful.

For the bilingual track (Valencia), a C2 English level contributes only 0.5 points out of 10 — the exam weight is where the real competition lies. However, the minimum B1 gate eliminates candidates below that level, which reduces competing volume.

Cut-off scores are not published. PENDING_CONFIRMATION for historical admission distributions.

## Costs and Payment Structure

All values for **Castellón campus 2026-27** are confirmed from official honorarios document. Valencia bilingual campus tuition: PENDING_CONFIRMATION — not available on public pages, typically higher due to bilingual track premium.

**Castellón campus — annual fee breakdown:**

| Fee | Amount | Notes |
|---|---|---|
| Reservation fee (reserva de plaza) | €2,000 | One-time first payment on admission. |
| Inscripción | €2,300 | Paid July 1 – September 15. |
| Apertura de expediente | €750 | One-time, new students only. Paid with inscripción. |
| Academic fees (honorarios) — 60 ECTS | €13,800 | Paid monthly Oct–Jun (9 installments). |
| Monthly installment | €1,533.33 | Oct–Jun. |
| **Total Year 1** | **€18,850** | Reservation + inscripción + apertura + honorarios |
| Price per credit | €230 | Same for all 6 years at current rates |
| Exam fee | €75/session | Non-refundable. |
| Hospitality Pack (international students not residing in Spain) | €600 | One-time, mandatory for non-residents. |

**Total 6-year estimate (Castellón, at fixed 2026-27 credit rate):**

| Year | Honorarios (60 ECTS) | Fixed Fees | Total |
|---|---|---|---|
| 1 | €13,800 | €2,000 + €2,300 + €750 = €5,050 | €18,850 |
| 2 | €13,800 | €2,000 + €2,300 = €4,300 | €18,100 |
| 3–6 | €13,800 | €2,000 + €2,300 = €4,300 | €18,100/year |

Total 6-year cost estimate: approximately €109,350 (ANNUAL_UPDATE_REQUIRED — credit prices may increase annually). Compared to CEU San Pablo (€138,800), this represents a meaningful cost differential of approximately €30,000 over 6 years.

**Payment options:**
- Monthly: 9 equal installments (October–June) via bank account (SEPA) or credit card
- Upfront: possible via request to Administración de Alumnos
- Financing: CEU UCH has banking credit lines for study financing
- Large family discount: 30% off the inscripción amount (general); 60% (special category)

**Valencia bilingual campus — ANNUAL_UPDATE_REQUIRED:** Official tuition PDF for Valencia was not accessible from public pages. The administrative norms confirm that bilingual programs may carry a higher per-course price. Families should request the current honorarios document for the Medicine bilingual track directly from the admissions office.

## Scholarships and Financial Aid

**CEU Merit Program:** The university's flagship scholarship offers over 100 scholarships per year with reductions of 75% or 100% on the total annual fees. Described as the "only scholarship program in Spain where you know if you receive the scholarship before enrolling." Specific eligibility criteria and application process: ANNUAL_UPDATE_REQUIRED.

**Becas de Colaboración:** Students may earn compensation for collaborating in various university departments. Available to both national and international students.

**Large family (familia numerosa) discount:** 30% off inscripción (general category); 60% off inscripción (special category). Applied to the inscripción concept only, not total tuition.

**Complementary points system:** While not technically a scholarship, the bonus point system disproportionately benefits students from CEU school backgrounds — providing indirect financial value to families who have already invested in the CEU ecosystem.

**General Spanish scholarship system (MEC grants):** Applicable for students meeting income and academic criteria.

**Banking credit lines:** Available through university-facilitated partnerships for students who need to finance monthly payments.

PENDING_CONFIRMATION: Medicine-specific scholarship amounts, eligibility requirements, and award rates.

## Accommodation and Cost of Living

**Castellón:** Castellón de la Plana is a coastal city in the Valencian Community with a significantly lower cost of living than Madrid or Barcelona. Shared accommodation typically ranges from €350–€550/month. Public transport is well developed within the city. A full student monthly budget (accommodation, food, transport, materials) is approximately €700–€1,100/month.

**Valencia (Alfara del Patriarca campus):** Alfara del Patriarca is a suburban municipality approximately 8 km north of Valencia. The area is served by bus and light rail (MetroValencia). Students typically choose to live in Valencia city and commute. Valencia's cost of living is moderate — shared accommodation €450–€750/month. Monthly student budget approximately €900–€1,300.

PENDING_CONFIRMATION: Official CEU UCH university accommodation pricing and availability for Medicine students.

## International Exchange and Mobility Programs

**US Clinical Rotation Program (Programa CEU UCH – AMOpportunities):** Medical students can complete supervised clinical rotations in hospitals and health centres in Chicago and New York. This is described by CEU UCH as the first such program offered by a Spanish university — a concrete differentiator for students with aspirations in North America.

**Erasmus+ and general mobility:** Available as part of the CEU network. Specific named Medicine exchange destinations: PENDING_CONFIRMATION.

**Global Citizen Program:** A structured certification for international engagement, available to all enrolled students.

**WFME accreditation** enables graduates to access the USMLE and licensing exam pathways in the US, Canada, Australia, and New Zealand.

Note: Specific exchange availability, semester timing, and seat allocation for Medicine should be confirmed with the international office at the respective campus.

## MIR Preparation and Professional Outcomes

MIR preparation is integrated from Year 3 through a formal partnership with **AMIR academy**, one of Spain's leading MIR preparation providers. AMIR is described as having one of the best MIR success rates in Spain in recent years.

CEU UCH has reported individual graduates placing in the Top 10 nationally in the MIR exam.

From Year 3, students progressively build both clinical knowledge and exam strategy (multiple-choice reasoning, time management, content mastery under pressure) needed for strong MIR performance.

The free Diploma Universitario de Experto en Medicina Clínica y Diagnóstica (available from Year 3) is designed explicitly to improve clinical and diagnostic competency — complementing the standard curriculum with focused professional training.

PENDING_CONFIRMATION: MIR pass rate (%), mean MIR score, top-specialty placement rates.

## Strategic Fit

### Good Fit For

- Students with a strong 1st-year bachillerato record who want the largest component (60%) to reflect early academic performance rather than EvAU
- Science-track bachillerato students with Biology + Chemistry + Physics — all three are directly tested in the EPAM
- Students based in or willing to relocate to the Valencian Community (Castellón or Valencia)
- Families seeking lower overall 6-year cost than Madrid-based private medicine programs (Castellón ~€109K vs others at €130–140K)
- Students who prioritize clinical exposure from Year 1 — earlier than most competitors
- Students targeting WFME accreditation with confirmed US/Canada/Australia pathway
- International students (especially those from English-speaking countries or with strong English) who target the bilingual Valencia track
- Students who want integrated MIR preparation via a professional academy (AMIR) from Year 3
- Students interested in US clinical rotations as part of the degree structure

### Less Suitable For

- Students who completed an Arts or Social Sciences bachillerato — Physics/Mathematics in the EPAM creates a significant gap versus Biology/Chemistry-only exams at other universities
- Students applying only to Session 2 (April) — no further attempt available within that cycle
- Students who need a Madrid-based option — CEU UCH is Valencian Community only
- Students who need a large bilingual or English-only group from Year 1 (Valencia track is English in the first two years but reverts to Spanish from Year 3 onwards for most content)
- Families requiring Valencia bilingual track tuition transparency before committing — pricing not publicly detailed

## Risks and Considerations

**1. Physics and Mathematics in the entrance exam.** The EPAM includes a 15-question Physics/Math block — no other major private medical school entrance exam in this analysis includes Physics. This creates a significant preparation demand for students who have not studied Physics in bachillerato or who deprioritized it.

**2. Only two exam sessions.** CEU UCH offers fewer retake opportunities than some competitors (2 vs 3 at CEU San Pablo). Session 2 is the final opportunity within a cycle; there is no third rescue call.

**3. In-person-only EPAM.** Unlike CEU San Pablo, which offers hybrid delivery, the EPAM for candidates with Spanish system studies is always in-person. This is a logistical constraint for international students or students based far from Castellón or Alfara del Patriarca (though EPOAM resolves this for true international candidates).

**4. PAU as independent constraint.** The same structural risk as CEU San Pablo — the PAU must be passed independently. Failure means loss of admission regardless of EPAM performance or rank position.

**5. Castellón is a newly launched program.** The Castellón campus Medicine degree is relatively recent (443 reported applicants for its inaugural intake). Cut-off scores and competitive benchmarks are not yet established. This creates uncertainty for planning but also potential opportunity if competition is lower than at established programs.

**6. Valencia bilingual tuition not publicly available.** Families applying for the bilingual track cannot determine the full cost from public pages — requires direct contact with the university.

**7. Bonus points favor CEU ecosystem candidates.** Students with no prior CEU school affiliation and not residing in Valencia or Castellón province have access to 0 bonus points, while CEU alumni families can reach the 2-point cap. In a cohort of 70 seats, 2 points can represent the margin between admission and waitlist.

**8. Bilingual program: English instruction tapers after Year 3.** Approximately 165 of 360 ECTS are in English. From Year 3 onwards, clinical training and most subjects revert to Spanish. Students who chose the bilingual track primarily to study in English should factor this into their expectations.

**9. EPOAM restriction.** International candidates who take the EPOAM (online) cannot switch to the EPAM. This can be relevant if a student later establishes Spanish residency or changes their preference between sessions.

## Important Notes

- The minimum grade of 7 (out of 10) on 1st-year bachillerato is an eliminatory threshold — candidates below this score are not eligible regardless of exam performance.
- Both sessions use the same exam format; EPAM and EPOAM are structurally identical (same questions, same timing, different delivery mode).
- Bilingual track (Valencia) requires minimum B1 English certification before sitting the exam. B1 is a gate requirement — it scores 0 points in the 5% English component. Only B2 and above contribute actual score points.
- CEU UCH offers its own language certification sessions at set dates throughout the year, which can be used to obtain the required English certificate for the bilingual track.
- The 14-day legal right of withdrawal (derecho de desistimiento) applies after reservation payment — relevant for families comparing multiple offers simultaneously.
- International students (non-Spanish residents) must pay an additional €600 Hospitality Pack at admission.
- Credit recognition from other universities follows a fee structure: €500 base for equivalent-degree cases; 25% of credit value for non-equivalent cases. CEU-to-CEU transfers are free.

## Key Insight

CEU Cardenal Herrera's EPAM is the most academically demanding entrance exam among the universities in this analysis, largely because it includes Physics and Mathematics — a 20% block of a 75-question test that most competitors have removed. This is simultaneously the biggest risk (for students without strong Physics) and the biggest differentiator: students who excelled in all four science subjects and mastered them for the Spanish bachillerato are at a structural advantage versus peers who focused only on Biology and Chemistry. The reading comprehension component further distinguishes the exam as one that tests academic aptitude, not just content knowledge.

Combined with practices from Year 1, the AMIR partnership, and the US clinical rotation program, CEU UCH makes a strong case as a clinically integrated medical program with genuine international reach — at a price point (€109K over 6 years in Castellón) that is meaningfully lower than Madrid-based alternatives.

## Final Takeaway

CEU Cardenal Herrera offers two distinct Medical programs in the Valencian Community, both with WFME accreditation and a clinical training model that starts in Year 1. The Castellón campus is the more accessible financially and has confirmed seat capacity (70 places). The Valencia bilingual track adds English-medium instruction and a distinct profile for internationally oriented students.

The entrance exam (EPAM) is unusually broad — Biology, Chemistry, Physics/Mathematics, and Reading Comprehension — making it a poor fit for students without a full Science bachillerato background, but a strong fit for students who genuinely mastered the Spanish science curriculum. The two-session structure and in-person delivery limit flexibility compared to some competitors.

At ~€109K over 6 years (Castellón) with practices from Year 1, AMIR-backed MIR preparation, and access to US clinical rotations, the value proposition is among the stronger in the Spanish private medicine landscape for students whose profile matches this model.

## Frequently Asked Questions

**What is the difference between the Castellón and Valencia programs?**
Castellón is a Spanish-only track with confirmed 70 seats. Valencia is a bilingual Spanish/English track with instruction in English for approximately 165 ECTS (mainly Years 1–3). Both lead to the same official Spanish Medicine degree and hold WFME accreditation. The admission formula differs: Castellón weights the exam at 40%; Valencia weights it at 35% plus 5% English level.

**Does the EPAM include Physics? Do I need Physics background?**
Yes. The EPAM includes 15 questions on Physics and Mathematics combined (out of 75 total). This is unique among major private medical school entrance exams in Spain. Students without a Physics background face a structural disadvantage. Students from a full Science bachillerato (Biology, Chemistry, Physics) are well positioned.

**Can I apply to both campuses simultaneously?**
Yes. You can indicate both preferences (Castellón Spanish and Valencia bilingual) in order of priority. If admitted for your first preference, the second is removed. If waitlisted for the first but admitted for the second, you can hold the second place while awaiting the first. Candidates can appear on both admissions lists simultaneously.

**Is the entrance exam in English available?**
The EPAM and EPOAM can be taken in English for non-native Spanish speakers. This applies to all candidates who prefer to answer in English. It does not affect the exam content or scoring.

**What is the minimum English level for the bilingual track?**
B1 certified English is the minimum requirement to sit the entrance exam for the Medicine bilingual track (Valencia). B1 scores 0 points in the formula. B2 adds 0.2 points, C1 adds 0.4 points, and C2 adds 0.5 points on a 10-point scale.

**Do the bonus points (complementary points) really matter?**
Yes, significantly. With 70 seats in Castellón and the maximum bonus being 2 points (on a 10-point scale), the bonus can shift a candidate from waitlisted to admitted in close competition. CEU school alumni who can claim the full loyalty bonus (1.5 pts) plus empadronamiento (0.5 pts) reach the 2-point cap automatically. Candidates with no CEU background and not registered in Castellón province receive 0 bonus points.

**Is there a reservation fee? Can I get it back?**
The reservation fee (€2,000 for Castellón) is paid to secure the place after admission. It can be refunded if withdrawal is requested before June 16, 2026. After that date, the legal right of withdrawal (14 days from payment) applies for reservations made after June 16. Beyond these windows, the fee is generally not refundable.

**What happens if I fail the PAU after being admitted?**
You lose your admission place and waitlist position. The PAU is a mandatory prerequisite — it must be passed in the ordinary June call (or the equivalent foreign bachillerato credential). Failure to pass or to submit results by the university's deadline results in automatic loss of all rights derived from admission.

**Does WFME accreditation apply to both campuses?**
Yes. CEU UCH explicitly states that "el Grado en Medicina en Valencia y Castellón ha obtenido el Sello Internacional de Calidad de la WFME." Both programs are WFME-accredited and enable access to US, Canadian, Australian, and New Zealand licensing and residency pathways.

**What is the Diploma Universitario de Experto en Medicina Clínica y Diagnóstica?**
It is a free additional diploma available to all Medicine students from Year 3, designed to accelerate clinical and diagnostic competency. It runs in parallel with the degree and is offered at no extra cost. Completing it results in a dual-award alongside the Grado en Medicina.
```