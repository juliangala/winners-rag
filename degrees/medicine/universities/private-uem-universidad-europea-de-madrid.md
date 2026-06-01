```md
---
id: uem-medicine

type: university
subtype: private

name: Universidad Europea de Madrid
short_name: UEM

degree: Medicine

last_update: 2026-05-27

valid_for_intake: 2026-2027

location:
  city: Villaviciosa de Odón
  region: Comunidad de Madrid
  country: Spain

strategic_tags:
  - academic_record_heavy
  - english_advantage
  - early_application_advantage
  - rolling_admissions
  - high_competitiveness
  - high_cost
  - international_friendly
  - strong_clinical_exposure
  - no_academic_exam

admission:
  intake_month: September

  applications_open_date: ANNUAL_UPDATE_REQUIRED

  rolling_admissions:
    enabled: true
    estimated_end_date: ANNUAL_UPDATE_REQUIRED # Historically July of the preceding academic year

  admission_rounds:
    enabled: true
    count: 3 # Three allocation rounds: ~40% / ~40% / ~20% of seats respectively

    rounds:
      - round: 1
        application_deadline: ANNUAL_UPDATE_REQUIRED
        exam_date: ANNUAL_UPDATE_REQUIRED # Multiple exam dates within the Round 1 window (historically Dec–Feb)
        results_date: ANNUAL_UPDATE_REQUIRED # Historically: January–March
        deposit_deadline: ANNUAL_UPDATE_REQUIRED # 5 business days from admission notification

      - round: 2
        application_deadline: ANNUAL_UPDATE_REQUIRED
        exam_date: ANNUAL_UPDATE_REQUIRED # Multiple exam dates within the Round 2 window (historically Feb–May)
        results_date: ANNUAL_UPDATE_REQUIRED # Historically: March–May
        deposit_deadline: ANNUAL_UPDATE_REQUIRED

      - round: 3
        application_deadline: ANNUAL_UPDATE_REQUIRED
        exam_date: ANNUAL_UPDATE_REQUIRED # Historically: July
        results_date: ANNUAL_UPDATE_REQUIRED
        deposit_deadline: ANNUAL_UPDATE_REQUIRED

  exam_required: false # No Biology/Chemistry academic exam; English test and competencies test are required
  interview_required: false

academic_record:
  minimum_requirement:
    enabled: PENDING_CONFIRMATION
    grade_source: first_year_baccalaureate
    minimum_grade: PENDING_CONFIRMATION

  competitive_filter:
    enabled: true
    grade_source: first_year_baccalaureate
    approx_candidates_selected: PENDING_CONFIRMATION

curriculum:
  international_curriculums_accepted: true # IB, EU educational systems, foreign diplomas with UNED credential or Ministry homologation

competitiveness:
  level: high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: 200
  applicants_per_seat: PENDING_CONFIRMATION

  last_admitted_scores:
    - intake_year: 2022-2023
      round: 1
      score: 8.56–8.95
      score_type: nota_media_bachillerato_primer_curso_ponderada
      notes: >
        Forum-sourced data only (casimedicos.com). 8.56 was not admitted; 8.95 was admitted in Round 1.
        Represents the weighted admission score (90% academic record + 10% English test).
        Not official UEM data. Treat as indicative only.

international_profile:
  international_students_percentage: PENDING_CONFIRMATION

  international_nationalities:
    - country: NULL
      percentage: NULL

programs:
  - id: uem-medicine-madrid

    campus: Villaviciosa de Odón (Madrid)

    modality: standard

    strategic_tags:
      - academic_record_heavy
      - english_advantage
      - early_application_advantage
      - rolling_admissions
      - high_competitiveness
      - high_cost
      - international_friendly
      - strong_clinical_exposure
      - no_academic_exam

    teaching_languages:
      - Spanish

    regional_language_possible: false
    regional_language: NULL

    language_requirements:
      minimum_spanish_level_non_native: B2 # Internal UEM Spanish test; no external certificate accepted as substitute. Eliminatory.

      english_required: false # English test is a weighted component, not a prerequisite threshold
      minimum_english_level: NULL

    seats: 200

    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 200
      applicants_per_seat: PENDING_CONFIRMATION

      last_admitted_scores:
        - intake_year: 2022-2023
          round: 1
          score: 8.56–8.95
          score_type: nota_media_bachillerato_primer_curso_ponderada
          notes: Forum-sourced (casimedicos.com). Indicative only; not official UEM data.

    program_specific_admission:
      enabled: false

    evaluation_model:
      overall_model_type: pathway_based

      admission_pathways:

        - eligible_profiles:
            - Spanish_bachillerato_EvAU
            - CFGS_health_sciences

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 0.90
              grade_source: first_year_baccalaureate
              minimum_required_grade: PENDING_CONFIRMATION
              notes: >
                Average mark of Year 1 of the Spanish bachillerato (Health Sciences branch required;
                other branches not accepted). CFGS applicants: equivalent first-year record used.
                No credit recognition is granted at enrollment — students may not validate
                subjects taken previously at any university.

            - component: academic_exam
              enabled: false
              role: NULL
              weight: NULL
              exam_variant: NULL
              exam_format: NULL
              delivery_mode: NULL
              online_conditions: NULL
              subjects: []
              syllabus_alignment:
                biology:
                  scope:
                    - not_applicable
                  notes: NULL
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
                notes: No Biology/Chemistry knowledge exam exists at UEM.
              best_attempt_counts: NULL
              notes: No academic knowledge exam required. UEM does not test subject content at admission.

            - component: english_test
              enabled: true
              role: weighted
              weight: 0.10
              test_format: mixed # Reading comprehension + grammar/vocabulary + listening
              delivery_mode: online
              online_conditions: NULL
              minimum_level: NULL
              bonus_max: NULL
              bonus_scale:
                B2: NULL
                C1: NULL
                C2: NULL
              notes: >
                Internal UEM English test (~50 minutes). Assesses reading comprehension,
                grammar/vocabulary, and listening comprehension. No external certificate
                (Cambridge, IELTS, TOEFL) accepted as substitute — all candidates must
                sit the internal test. Score is expressed as a percentage and contributes
                10% to the final admission score.

            - component: psychometric_test
              enabled: true
              role: requirement_only
              weight: 0
              test_format: multiple_choice
              delivery_mode: online
              online_conditions: >
                Must be completed online after application and payment of €150 exam fee.
                Completion is required before the candidate can book a date for the
                English/Spanish tests.
              notes: >
                Competencies and Skills Test. 30 minutes; 116 general skills questions
                + 23 study behaviour questions. Assesses intellectual aptitude, work attitudes,
                and teamwork disposition. NON-WEIGHTED — does not contribute to the
                admission score. Must be completed to proceed in the process.

            - component: interview
              enabled: false
              role: NULL
              weight: NULL
              interview_format: NULL
              delivery_mode: NULL
              notes: >
                No formal interview. However, admitted candidates are required to attend
                a campus visit (jornada de presentación) before the admission decision
                is issued. This visit is organisational, not evaluative.

            - component: complementary_points
              enabled: false
              role: bonus_only
              maximum_bonus: NULL
              categories: []
              notes: NULL

        - eligible_profiles:
            - International_students_UNED_credential
            - EU_educational_systems
            - International_baccalaureate
            - Foreign_diploma_Ministry_homologation

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 0.90
              grade_source: equivalent_secondary_record
              minimum_required_grade: PENDING_CONFIRMATION
              notes: >
                Average mark of Year 1 of the equivalent secondary diploma (Health Sciences
                branch required). For IB and EU systems: UNED credential used for validation.
                For other systems: Ministry of Education homologation required before enrollment
                (provisional volante accepted during process).

            - component: academic_exam
              enabled: false
              role: NULL
              weight: NULL
              exam_variant: NULL
              exam_format: NULL
              delivery_mode: NULL
              online_conditions: NULL
              subjects: []
              syllabus_alignment:
                biology:
                  scope:
                    - not_applicable
                  notes: NULL
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
                notes: No academic knowledge exam.
              best_attempt_counts: NULL
              notes: No academic knowledge exam.

            - component: english_test
              enabled: true
              role: weighted
              weight: 0.05
              test_format: mixed
              delivery_mode: online
              online_conditions: NULL
              minimum_level: NULL
              bonus_max: NULL
              bonus_scale:
                B2: NULL
                C1: NULL
                C2: NULL
              notes: >
                Same internal UEM English test format as EvAU pathway. Weight is 5%
                (not 10%) for international pathway. For IB applicants: "Spanish exam,
                if relevant: 5%" — suggesting Spanish-mother-tongue IB students may
                follow a different breakdown; PENDING_CONFIRMATION.
                For non-native Spanish speakers: the remaining 5% is allocated to the
                Spanish test (see complementary_points note).

            - component: psychometric_test
              enabled: true
              role: requirement_only
              weight: 0
              test_format: multiple_choice
              delivery_mode: online
              online_conditions: NULL
              notes: Same Competencies and Skills Test (30 min, 116+23 questions). Non-weighted requirement.

            - component: interview
              enabled: false
              role: NULL
              weight: NULL
              interview_format: NULL
              delivery_mode: NULL
              notes: NULL

            - component: complementary_points
              enabled: true
              role: weighted
              maximum_bonus: 0.05
              categories:
                - category: Spanish_language_test_non_native_speakers
                  max_points: 0.05
              notes: >
                For non-native Spanish speakers: an internal UEM Spanish test (B2 level,
                reading comprehension + grammar + listening) contributes 5% to the
                admission score, raising the formula to 90% academic + 5% English + 5%
                Spanish. This is eliminatory in addition to weighted: candidates who
                fail to demonstrate B2 level are automatically eliminated regardless
                of total score. Native Spanish speakers do not sit this test.
---
# Universidad Europea de Madrid

## Overview

Universidad Europea de Madrid (UEM) offers one of the most academically structured Medicine admission processes in Spain's private university sector. The defining characteristic of UEM's model is the dominance of the academic record: the average mark from the first year of bachillerato accounts for 90% of the admission score, with a 10% contribution from an internal English test. There is no Biology, Chemistry, or any subject-knowledge entrance exam.

This creates a clear, measurable selection model that strongly rewards sustained academic performance over examination preparation. Students entering with high Year 1 bachillerato averages (historically 8.5–9.0+ to be competitive in first-round offers) and solid English skills have a structured, predictable path to admission. For international students, UEM provides a clearly defined pathway via UNED credential or Ministry homologation, with the same 90% academic weight applying regardless of curriculum origin.

The degree is delivered entirely on the Villaviciosa de Odón campus (30 km southwest of Madrid) within the Facultad de Medicina, Salud y Deportes. UEM holds WFME accreditation, enabling graduates to access specialisation training in the United States, Canada, and Australia. The Society for Simulation in Healthcare (SSH) has recognised UEM's Simulated Hospital as one of the best in Europe. With 200 seats, it is among the larger private Medicine cohorts in Spain.

Admission operates on a rolling basis throughout the academic year, with exam dates offered continuously from late autumn through July. Seats are distributed roughly 40%/40%/20% across three allocation rounds, creating a strong early-application advantage. Candidates who perform well in Round 1 have an materially better probability of entry than those who delay.

## Quick Evaluation

- **Admission model**: 90% Year 1 bachillerato average + 10% internal English test. No Biology/Chemistry exam. No interview.
- **Competencies test**: Mandatory but non-weighted. Must be completed before booking the content exams.
- **Seat count**: 200 — one of the larger private Medicine cohorts in Spain.
- **Competitiveness**: High. Forum data from 2022–23 shows Round 1 cut-off between 8.56 (not admitted) and 8.95 (admitted). Current thresholds likely higher.
- **Rolling admissions**: Yes — multiple exam dates from approximately December through July. Round 1 allocates roughly 40% of seats.
- **WFME accreditation**: Confirmed. Enables specialisation access in USA, Canada, Australia.
- **Simulated Hospital**: SSH-certified as one of the best in Europe.
- **Clinical network**: SERMAS (Madrid public hospitals) + Quirónsalud + HLA Moncloa + Vithas Arturo Soria.
- **Campus**: Villaviciosa de Odón. Not central Madrid — requires commute for most students.
- **Tuition**: ANNUAL_UPDATE_REQUIRED. Historical reference: ~18,780€/year (2022–23 data); approximately €313/ECTS. Likely higher by 2026–27.
- **Language advantage**: English test counts for a real 10% — one of the few Spanish private universities where English proficiency directly impacts admission scores.
- **MIR outcomes**: PENDING_CONFIRMATION — UEM does not publish MIR pass rate figures on public pages.

## Key Facts

| Field | Value |
|---|---|
| Full name | Universidad Europea de Madrid |
| Short name | UEM |
| Location | Villaviciosa de Odón, Comunidad de Madrid |
| Campus distance from city centre | ~30 km from central Madrid |
| Degree duration | 6 years |
| Total ECTS | 360 |
| Seats (Medicine, Madrid) | 200 |
| Intake month | September |
| Language of instruction | Spanish |
| WFME accreditation | Yes |
| Exam fee | €150 (non-refundable) |
| Place reservation fee | €3,200 + €770 academic file opening = €3,970 |
| Annual tuition (2026–27) | ANNUAL_UPDATE_REQUIRED (~18,780€/year in 2022–23) |
| QS ranking (Medicine) | Top 2 private universities in Spain, QS By Subject 2025 |
| Faculty | Facultad de Medicina, Salud y Deportes |

## Program Options

UEM offers a single Medicine programme at the Villaviciosa de Odón campus, taught entirely in Spanish. There is no bilingual or English-track variant. All students follow the same curriculum; no differentiation by track exists within the degree.

The programme is campus-based and presential. Online or hybrid delivery is not available. The campus is purpose-built for health sciences and houses a Simulated Hospital, dissection laboratories, biomedical science laboratories, and research facilities on a dedicated university estate.

There is no second campus for Medicine within UEM's network. The UEC (Universidad Europea de Canarias) operates a separate Medicine degree under the same group brand but with distinct admissions, fees, and clinical network — it is a separate programme and not a campus extension of UEM.

## Program Structure

The degree spans 6 years and 360 ECTS, organised in three broadly defined phases:

Years 1–3 (Preclinical phase): foundational biomedical sciences. Year 1 covers Anatomy (12 ECTS), Physiology (12 ECTS), Biochemistry I and II, Cellular Biology, Genetics, Histology, Medical Humanities and Communication Skills, and English for Health Sciences I. Year 2 introduces Epidemiology and Biostatistics, Medical Psychology, Introduction to Clinical Practice, two large integrated modules on Morphology/Structure/Function of Organs and Systems (16 ECTS each), and English for Health Sciences II (taught in English). Year 3 covers Semiology and General Pathophysiology, General Pathological Anatomy, Diagnostic Imaging, General Pharmacology, General Microbiology, and Basics of Surgery, alongside Health Management and Public Health.

Year 4 (Transitional/Systems phase): organ-system pathology modules — Cardiovascular, Respiratory, Digestive, Haematology, Infectious Disease, Endocrine, Nephrology/Urology, and Bioethics/Legal Medicine. An elective block (9 ECTS from 9 optativas) allows specialisation across Clinical Genetics, AI-assisted Decisions, Biomedical Research, Surgical Skills, ICU, Critical Patients, Plastic Surgery, Anaesthesiology, or Interprofessional Training. Research Methodology is also compulsory in Year 4.

Years 5–6 (Clinical phase): Year 5 continues systems pathology — Rheumatology, Traumatology, Psychiatry, Neurology, Dermatology, Paediatrics, Medical Therapeutics, Gynaecology and Obstetrics, Emergencies and Toxicology, Oncology and Palliative Care, Geriatrics, and Complementary Examinations. Year 6 is entirely clinical: Atención Primaria, Internal Medicine, two Specialidades Médicas rotations, Specialidades Quirúrgicas, Urgencias, Paediatrics, General Surgery, Gynaecology and Obstetrics, Psychiatry, and the Trabajo Fin de Grado (9 ECTS). Additional optional clinical placements in Year 6 include ECOE preparation, interprofessional training, biomedical research, and surgical skills.

Total: 360 ECTS. English for Health Sciences II (Year 2, 6 ECTS) is the only module taught in English; all other instruction is in Spanish.

## Teaching Methodology

UEM's declared pedagogical model centres on experiential learning in simulated and real clinical environments from Year 1. Key features include:

The Simulated Hospital is the flagship facility — a full-scale clinical simulation environment certified by the Society for Simulation in Healthcare (SSH) as one of the best in Europe. It includes consultation rooms, emergency rooms, ICU, inpatient wards, an operating theatre, a mobile ICU, and other clinical spaces. Students begin using simulation technology from Year 1.

Interprofessional education (IPE) is structurally embedded in the programme. Medical students learn and practise alongside students from other health disciplines (nursing, physiotherapy, dentistry), mirroring real-world healthcare team dynamics. This is distinct from most Spanish private Medicine programmes where interdisciplinary practice is aspirational rather than structural.

Clinical immersion begins in Year 3 with hospital rotations at SERMAS and private partner hospitals. The student-to-teacher ratio in clinical rotations is cited as 1:2 (one professor per 1–2 students) by the university.

The faculty comprises over 1,000 active specialists, creating direct bridges between teaching and current clinical practice. 40% of Medicine professors hold a doctorate.

Facilities beyond the Simulated Hospital include 3D anatomical modelling rooms, dissection laboratory, biomedical sciences laboratories I and II, task training rooms, and interactive clinical reasoning systems.

## Clinical Training

Clinical rotations begin in Year 3. UEM operates a dual clinical network combining Madrid's public SERMAS hospitals with major private health groups:

**SERMAS (Servicio Madrileño de Salud) hospitals:**
- Hospital Universitario de Getafe
- Hospital Universitario Infanta Sofía
- Hospital Universitario Santa Cristina
- Hospital Universitario José Germain
- Hospital La Fuenfría
- 12 Centros de Atención Primaria (C.S. Américas, Isabel II, Pintores, Sector III, Pinto, Miraflores, Rosa de Luxemburgo, Reyes Católicos, Villamil, Villaviciosa, and others)

**Private network:**
- Hospital Universitario Quirónsalud Madrid (Grupo Quirónsalud)
- Hospital Universitario Quirónsalud Ruber Juan Bravo (Grupo Quirónsalud)
- Hospital Universitario HLA Moncloa (Grupo ASISA)
- Hospital Universitario Vithas Arturo Soria (Grupo Vithas)

Sanitas hospitals (La Zarzuela, La Moraleja, Virgen del Mar, BLUA Sanitas Valdebebas) are cited on the Spanish degree page as part of educational agreements, though their inclusion in the mandatory rotation schedule requires ANNUAL_UPDATE_REQUIRED verification.

Year 6 clinical rotations cover Internal Medicine, two Medical Specialties blocks, Surgical Specialties, Emergencies, Paediatrics, General Surgery, Gynaecology and Obstetrics, and Psychiatry, in addition to Atención Primaria.

## International Recognition and Opportunities

UEM holds WFME (World Federation for Medical Education) accreditation. This is a formal, confirmed accreditation with specific practical consequence: UEM graduates may apply directly for medical specialisation (residency) programmes in the United States, Canada, and Australia without needing to obtain additional degree recognition. For students whose long-term career plans include international practice, WFME status is materially significant.

ANECA accreditation within the Spanish national framework is standard.

International rankings: Top 2 private universities in Spain in Medicine (QS World University Rankings by Subject 2025). Top 5 private universities nationally in the Times Higher Education World University Rankings (Clinical and Health category, 2021 data). Number 1 in Comunidad de Madrid for teaching quality per the 2020 U-Ranking (BBVA Foundation/IVIE).

Erasmus mobility partners include Università degli Studi di Roma La Sapienza (Italy), Università degli Studi di Genova (Italy), and Univerzita Karlova v Praze, First Faculty of Medicine (Czech Republic). Summer exchange stays are available at Yale University (USA), University of California Irvine (USA), University of Liverpool (UK), and Wesley Hospital Brisbane (Australia). These agreements are university-level; their specific applicability to Medicine students in any given year is ANNUAL_UPDATE_REQUIRED.

## Admission Model

UEM's admission model is defined by maximum weighting on the academic record with a secondary English test component. There is no Biology, Chemistry, Physics, or Mathematics examination. There is no interview in the evaluative sense.

**EvAU / Spanish bachillerato pathway:**
- 90% — average mark of Year 1 of the Spanish bachillerato (Health Sciences branch only)
- 10% — internal English test (reading, grammar/vocabulary, listening; ~50 minutes; online)

**International / foreign credentials pathway:**
- 90% — average mark of Year 1 of the equivalent secondary diploma
- 5% — internal English test (same format)
- 5% — internal Spanish test (non-native Spanish speakers only; eliminatory if B2 not demonstrated)
- For IB students who are native Spanish speakers: formula breakdown PENDING_CONFIRMATION

**Competencies and Skills Test** (mandatory but non-weighted): A 30-minute online test consisting of 116 general aptitude questions and 23 study behaviour questions, assessing intellectual work, work attitude, and teamwork disposition. This test must be completed after payment of the €150 exam fee and before the candidate can book the English/Spanish tests. It does not add to the admission score.

**Campus visit** (jornada de presentación): Admitted candidates are required to attend a campus visit where they meet professors and future classmates. This is organisational, not evaluative — it does not affect the admission decision.

No credit recognition is granted at the point of enrollment. Students entering UEM Medicine may not validate subjects taken at any prior university, regardless of academic background. This is an explicit regulatory constraint stated in the official normativa.

## Admission Process

1. Submit an online application via the UEM admissions portal and choose an exam date.
2. Pay the €150 exam fee (non-refundable) via the pre-student portal.
3. Complete the Competencies and Skills Test online (available after step 2).
4. Take the English test (online, approximately 50 minutes). Non-native Spanish speakers also take the Spanish test.
5. Submit academic documentation (Year 1 bachillerato certificate or equivalent) to nuevosalumnosmedicina@universidadeuropea.es, ideally before the exam date.
6. Check admission result via the pre-student portal after 4pm on the relevant results date (results are not communicated by phone or email).
7. If admitted: pay €3,970 (€3,200 reserva de plaza + €770 apertura de expediente) within 5 business days via the pre-student portal.
8. Complete digital enrolment (sign all required documents through the portal).
9. Submit the Legal Admission Requirement (EvAU certificate / UNED credential / Ministry homologation) by the November deadline.

Candidates on the waiting list remain eligible until all seats are filled. The published admission result is not subject to appeal.

Health Sciences branch of the bachillerato is mandatory. Applications from other branches (Humanidades, Ciencias Sociales, etc.) are not accepted. International students must demonstrate B2 Spanish level in the internal UEM test; no external language certificate is accepted as a substitute.

## Admission Timeline

All dates are ANNUAL_UPDATE_REQUIRED. The following are indicative patterns based on observed 2025–26 cycle information.

| Event | Indicative timing |
|---|---|
| Applications open | Rolling — ongoing throughout the year | ANNUAL_UPDATE_REQUIRED |
| Exam fee payment | Upon application completion | ANNUAL_UPDATE_REQUIRED |
| Competencies test | Online, self-scheduled after payment | ANNUAL_UPDATE_REQUIRED |
| Exam dates (Round 1 window) | Historically: December, January, February | ANNUAL_UPDATE_REQUIRED |
| Exam dates (Round 2 window) | Historically: February, March, April, May | ANNUAL_UPDATE_REQUIRED |
| Exam dates (Round 3 window) | Historically: July | ANNUAL_UPDATE_REQUIRED |
| Round 1 results | Historically: January–March | ANNUAL_UPDATE_REQUIRED |
| Round 2 results | Historically: March–May | ANNUAL_UPDATE_REQUIRED |
| Round 3 results | Historically: July | ANNUAL_UPDATE_REQUIRED |
| Place reservation deadline | 5 business days from admission | ANNUAL_UPDATE_REQUIRED |
| Legal Admission Requirement deadline | 15 November (academic year start) | ANNUAL_UPDATE_REQUIRED |
| Course start | September 2026 | ANNUAL_UPDATE_REQUIRED |

Round 1 exam dates specifically observed for the 2025–26 cycle (as published on the UEM admissions page): 13 December, 8 January, 12 February; campus visit: 11 January; admission notification: 22 January. Subsequent rounds follow at 8-week intervals approximately.

## Admission Score Distribution

The admission score at UEM is almost entirely determined by the Year 1 bachillerato average. At 90% weighting, a candidate's academic record is the dominant variable — the English test (10%) can meaningfully shift outcomes only when two candidates have nearly identical academic marks.

**Practical implications of the 90/10 model:**

The highest-impact lever is the Year 1 academic record. Unlike models where a single high-stakes biology exam can compensate for a lower bachillerato grade (or vice versa), UEM's model offers no such compensation mechanism. A candidate with a 7.8 average in Year 1 cannot overcome the disadvantage through excellent English performance — the maximum English contribution is 10 points on a 100-point scale.

The English test is nonetheless a genuine differentiator at the margin. Given the historically narrow gap between the last admitted and first rejected candidate in Round 1 (8.56 not admitted vs. 8.95 admitted in 2022–23), the English test component can determine outcomes for candidates clustered around the cut-off.

**Round dynamics:** UEM distributes seats approximately 40%/40%/20% across rounds. This creates a structural early-application advantage: Round 1 is materially less competitive per available seat than Round 2 once Round 1 rejects have accumulated. Students with borderline grades have a stronger statistical argument for taking the exam in the first available window rather than waiting to improve language preparation.

**Cut-off estimates:** Forum data from 2022–23 placed the Round 1 cut-off between 8.56 and 8.95. By 2026–27, general upward pressure on admission scores at Spanish private universities makes thresholds of 8.5–9.0+ likely for Round 1. These are informal estimates only — UEM does not publish official cut-off data.

## Costs and Payment Structure

| Cost item | Amount | Notes |
|---|---|---|
| Admission exam fee | €150 | Non-refundable; paid before taking exams |
| Reserva de plaza | €3,200 | One-time; paid within 5 days of admission offer |
| Apertura de expediente | €770 | One-time; paid together with reserva |
| Annual tuition (2026–27) | ANNUAL_UPDATE_REQUIRED | Historical reference: ~18,780€/year (2022–23) |
| Estimated total 6-year tuition | ANNUAL_UPDATE_REQUIRED | Historical reference: ~112,680€ (6 × 18,780€) based on 2022–23 data |
| Price per ECTS (2022–23) | ~€313 | ANNUAL_UPDATE_REQUIRED |

The 2026–27 official tariff is published at `universidadeuropea.com/resources/media/documents/TARIFARIOS_GRADO_2026_2027.pdf` (ANNUAL_UPDATE_REQUIRED — PDF dynamically rendered; verify directly). The 2022–23 annual tuition of approximately €18,780 (total first-year cost ~€22,750 including one-time fees) places UEM in the mid-to-high range of Spanish private Medicine tuition, materially below UAX (€24,250/year) but above UNAV (~€20,400/year as of 2025–26).

A promotional discount of 50% on the place reservation fee (€1,600 instead of €3,200) was offered to students enrolling between February 1–28 2026. Availability of equivalent promotions in subsequent cycles is ANNUAL_UPDATE_REQUIRED.

No instalment schedule details for the annual tuition are confirmed in publicly available sources. Payment is likely structured in monthly instalments per academic year, consistent with sector norms, but this requires direct verification with UEM. ANNUAL_UPDATE_REQUIRED.

## Scholarships and Financial Aid

UEM operates a general scholarships programme covering undergraduate degrees across all faculties. Specific details for the Medicine degree — scholarship names, amounts, eligibility criteria, and whether academic merit scholarships apply to Medicine — are PENDING_CONFIRMATION. The university's scholarships page is available at universidadeuropea.com/en/admission-finance/scholarship-financial-aid/.

The UEM group also offers Becas de Excelencia and other institutional awards, but their application to Medicine specifically and any exclusion clauses (analogous to UAX's explicit Medicine exclusion from their Becas de Excelencia) must be verified directly. PENDING_CONFIRMATION.

Official Ministerio de Educación need-based grants (Becas MEC) are applicable to private university students meeting the income and academic requirements. These apply independently of the university's own scholarship programmes.

## Accommodation and Cost of Living

The Villaviciosa de Odón campus is located within a purpose-built university estate on the outskirts of Madrid, approximately 30 km from the city centre. The university operates on-campus student residences, making campus accommodation an option for students who prefer to avoid commuting. The campus itself is largely self-contained with sports, library (CRAI Dulce Chacón), cafeteria, and residential facilities.

Students choosing to live in Madrid proper face a significant daily commute (30–50 minutes depending on location and transport mode). Madrid's rental market is among the most expensive in Spain: private room rentals in shared flats typically range from €600–900/month in accessible areas, with studio apartments at €800–1,200/month. Campus residences are likely more cost-effective but availability is limited. ANNUAL_UPDATE_REQUIRED.

Villaviciosa de Odón itself has limited rental stock targeted at students; most students live either on campus or in Madrid's southwestern districts (Móstoles, Alcorcón, Leganés) for proximity to the campus.

## International Exchange and Mobility Programs

UEM's international mobility for Medicine students includes:

**Erasmus+ bilateral agreements (confirmed for the Medicine faculty):**
- Università degli Studi di Roma La Sapienza (Italy)
- Università degli Studi di Genova (Italy)
- Univerzita Karlova v Praze, First Faculty of Medicine (Czech Republic)

**Summer stays (optional, additional):**
- Yale University (USA)
- University of California Irvine (USA)
- University of Liverpool (UK)
- Wesley Hospital, Brisbane (Australia)

Specific availability of Erasmus and summer stays in any given year, application deadlines, and funding amounts are ANNUAL_UPDATE_REQUIRED. Not all mobility agreements are open to Medicine students in every cycle — students should verify directly with UEM's International Relations office.

The university promotes international experience as a differentiator, citing Yale and Wesley in marketing materials. These are primarily summer clinical observation or research placements rather than full semester exchanges, though the exact nature and selection process are PENDING_CONFIRMATION.

## MIR Preparation and Professional Outcomes

UEM does not publish verified MIR pass rate data on its public-facing degree pages. No official figure is confirmed.

The degree structure — with Year 6 dedicated entirely to clinical rotations across all major specialties — is designed to build the clinical case knowledge and reasoning skills required for the MIR. The faculty of over 1,000 active specialists and the SSH-certified Simulated Hospital are positioned as preparation assets.

Graduates are qualified to sit the MIR exam upon degree completion. Specialisation follows the national MIR competitive system. UEM has no MIR preparation programme built into the degree curriculum itself, but the clinical immersion model from Year 3 onwards is consistent with strong MIR preparation.

PENDING_CONFIRMATION: official MIR pass rate or placement statistics.

## Strategic Fit

### Good Fit For

Students with strong Year 1 bachillerato averages (8.5 or above) who benefit from a transparent, academically-centred selection model without a subject-knowledge entrance exam. UEM rewards sustained academic performance rather than exam-specific preparation.

Students with genuine English proficiency who can extract additional margin from the 10% English test weighting. At the competitive cut-off zone, English performance can be the deciding factor between admission and the waiting list.

International students from IB, EU, or other recognised secondary systems who hold WFME graduation as a target (for US, Canadian, or Australian specialisation pathways). The international admission pathway is clearly defined, and the rolling exam calendar offers flexibility in timing.

Students who value simulation-based and interprofessional clinical training from early in the programme. UEM's SSH-certified Simulated Hospital is a genuine differentiator relative to most Spanish private Medicine programmes.

Students who benefit from a larger cohort environment with broad clinical rotation exposure across both public and private hospital networks in Madrid.

### Less Suitable For

Students with Year 1 bachillerato averages below approximately 8.3–8.5. The 90% academic record weighting leaves minimal room for score recovery through other components. The English test cannot compensate for a materially lower academic record.

Students who perform significantly better in timed examination conditions than their bachillerato grades reflect. There is no academic exam component that could surface this ability.

Students who strongly prefer a city-centre campus. Villaviciosa de Odón requires daily commuting unless campus accommodation is used, which adds logistical and financial overhead.

Students who want detailed transparency on MIR outcomes before committing. UEM does not publish MIR pass rate data, unlike some competitors who promote verified statistics.

## Risks and Considerations

**High academic record dependency with no compensation mechanism**: The 90/10 model is the most academically concentrated weighting among Spain's private Medicine programmes. Students below the historical cut-off range (approximately 8.5 in Round 1) have a limited probability of entry in that round regardless of other strengths. Unlike UNAV or UCV models where a strong exam result can partially offset a lower grade, UEM offers no such pathway.

**Cut-off data opacity**: UEM does not publish official admission statistics (applicants, last admitted score, acceptance rate). Historical data is sourced from student forums (casimedicos.com) and is indicative only. The actual competitive threshold may have shifted materially since 2022–23.

**Round 1 seat scarcity creates time pressure**: With approximately 40% of seats allocated in Round 1, students who delay their application to later rounds face tighter competition. Students who wait until Round 3 (historically July) are competing for approximately 20% of seats — a structurally disadvantageous position.

**No credit recognition at enrollment**: Students entering UEM Medicine cannot validate any university subjects taken previously. This is an explicit regulatory constraint confirmed in the official normativa. Students who have completed partial degrees at other universities or CFGS programmes cannot shorten the degree based on prior university work.

**Tuition transparency**: The 2026–27 tariff PDF is not reliably accessible from public web fetches. Students and families should request the fee schedule directly from admissions. Historical tuition (~18,780€/year as of 2022–23) is a reference only.

**Campus location**: The Villaviciosa de Odón campus is not served directly by Madrid Metro. Transport options include university shuttle services and private car. Students relying on public transport face a multi-modal commute. This is a practical constraint with cost and time implications over a 6-year degree.

**Cohort size and clinical placement ratios**: With 200 students per year, UEM has one of the larger private Medicine cohorts in Spain. The claimed 1:2 student-teacher ratio in clinical rotations should be verified against actual rotation placement experience, as large cohort sizes can create scheduling pressure on limited hospital capacity.

## Important Notes

- Health Sciences branch of the bachillerato is mandatory. No exceptions for other branches regardless of academic record strength.
- The internal Spanish test for non-native speakers is eliminatory: candidates who fail to demonstrate B2 level are disqualified from the process regardless of academic record.
- The Competencies and Skills Test (non-weighted) must be completed before booking the English test. Failure to complete it blocks progression in the process.
- No external English certificate (Cambridge, IELTS, TOEFL, etc.) replaces the internal UEM English test.
- The €150 exam fee and the €3,970 place reservation are non-refundable. Students who pay and are not admitted in their chosen round may reapply in subsequent rounds.
- WFME accreditation is confirmed and operative. The university explicitly states this enables specialisation in the USA, Canada, and Australia.
- The normativa for 2026–27 is published at the official URL listed in the admission process pages. Students should review it before applying.
- Dates on the UEM admissions process pages sometimes carry references to the 2021 cycle and have not been consistently updated for current years. All dates must be confirmed directly with admissions for any specific intake year.

## Key Insight

UEM's 90% academic record weighting is the defining strategic variable for this university. It is simultaneously UEM's greatest strength and greatest constraint. For students with strong, verified academic records (Year 1 bachillerato averages of 8.5 or above), UEM offers a straightforward, transparent admission path with no biology exam preparation burden and no interview uncertainty. The rolling calendar with multiple exam dates adds flexibility that compensates for administrative complexity.

The 10% English weighting is structurally significant in a market where most Spanish private universities either ignore English performance at admission or use it only as a bonus. At UEM, a meaningful English advantage is built directly into the scoring model. For Winners' student profiles — where English preparation is already part of the curriculum — this is a genuine differentiator worth quantifying in the context of individual student scores.

The risk is the other side of the same coin: students below the cut-off range cannot buy their way in through better exam performance. UEM should be positioned as a primary target for high-achieving students and a secondary or aspirational option for those below 8.3–8.5.

## Final Takeaway

Universidad Europea de Madrid is a high-quality, WFME-accredited private Medicine programme with a transparent academic selection model and one of Spain's strongest simulation training environments. Its strengths — SSH-certified Simulated Hospital, dual public/private clinical network in Madrid, confirmed international accreditation, and rolling admission calendar — make it a strategically compelling option for academically strong candidates.

The key consideration is straightforward: UEM is the most academic-record-concentrated admission model in the Spanish private sector. Students who enter with strong Year 1 grades and good English have a well-defined, competitive path. Students without both of those factors face structural disadvantages that the model does not compensate for. For Winners students in the 8.5+ range, UEM should be a high-priority application; for those below that threshold, the programme requires realistic expectation-setting about first-round competitiveness and the value of applying early to maximise seat availability in the most favourable rounds.

## Frequently Asked Questions

**Does UEM require a Biology or Chemistry entrance exam?**
No. UEM has no Biology, Chemistry, Physics, or Mathematics knowledge exam at admission. The academic components are the bachillerato average (90%) and an internal English test (10%). This makes UEM fundamentally different from UNAV, UCV, or UAX, where science exam preparation is central to the admission strategy.

**What score do I need to be admitted?**
UEM does not publish official cut-off data. Forum-sourced data from 2022–23 indicates Round 1 admissions around the 8.56–8.95 range (weighted score). Thresholds may be higher by 2026–27 due to general score inflation in Spanish private Medicine admissions. Early application (Round 1) gives access to approximately 40% of seats; waiting for Round 3 means competing for roughly 20%.

**Does my English certificate (Cambridge, IELTS, TOEFL) count towards my admission score?**
No. UEM requires all candidates to sit its own internal English test regardless of external certificates held. There is no waiver or certificate substitution. The internal test result is what contributes the 10% weighting.

**I am an international student with an IB diploma. Can I apply?**
Yes. IB students are explicitly listed as an eligible pathway. The academic record weighting (90%) applies to the average of Year 1 of the IB diploma (Health Sciences subjects expected). UNED credential validation is available for IB qualifications. The remaining 10% is split between the English test (5%) and, if relevant, the Spanish test (5%). Students who are native Spanish speakers under the IB pathway should confirm the exact formula with UEM admissions.

**Is there an interview?**
No evaluated interview. Admitted candidates are required to attend a campus visit (jornada de presentación) before finalising enrolment, but this is an orientation meeting with professors and is not evaluative.

**Can I validate subjects I took at another university?**
No. This is an explicit regulatory condition: students admitted to UEM Medicine may not request or obtain any credit recognition for studies taken previously at any university. This applies without exception regardless of the subject or institution.

**How long does the admission process take from application to decision?**
The timeline depends on when you apply relative to the exam window. If you apply early in a round window, sit the exam, and results are published on schedule, the process from application to admission decision can take 4–8 weeks. Place reservation must be completed within 5 business days of the admission offer.

**Is WFME accreditation confirmed for UEM Medicine?**
Yes. UEM explicitly states WFME accreditation on its degree page and specifies that this enables graduates to specialise in the USA, Canada, and Australia. This is not provisional — it is currently operative.

**What is the Competencies and Skills Test?**
It is a 30-minute non-weighted online test (116 aptitude questions + 23 study behaviour questions) that must be completed after paying the €150 exam fee and before booking the English test. It assesses intellectual aptitude, work attitude, and teamwork orientation. It does not affect the admission score — it is a gateway requirement. UEM has historically noted technical issues with this test and it was suspended for one round (January 2022) due to system problems.

**What hospitals will I train in?**
Clinical rotations begin in Year 3. The confirmed network includes SERMAS public hospitals (Hospital Universitario de Getafe, Infanta Sofía, Santa Cristina, José Germain, La Fuenfría, and 12 primary care centres) and private network hospitals (Quirónsalud Madrid, Quirónsalud Ruber Juan Bravo, HLA Moncloa, Vithas Arturo Soria). Additional private group hospitals may be included depending on the academic year. Verify the current rotation schedule with UEM's Faculty for each academic year.
```