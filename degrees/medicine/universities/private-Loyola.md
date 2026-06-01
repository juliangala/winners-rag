---
id: loyola-medicine
type: university
subtype: private

name: "Grado en Medicina — Universidad Loyola (Compañía de Jesús)"
short_name: Loyola

degree: Medicine

last_update: "2026-05-27"
valid_for_intake: "2026-2027"

institution_type: universidad_privada
religious_affiliation: "Catholic — Jesuit (Compañía de Jesús)"
parent_group: "Red de universidades jesuitas (UNIJES / IAJU) — 190+ universities worldwide"
ruct_code: PENDING_CONFIRMATION
year_founded_medicine: 2023
inaugural_cohort: true # First cohort began November 2023; fourth cohort in 2026-27

location:
  city: "Dos Hermanas"
  region: "Sevilla, Andalucía"
  country: Spain

strategic_tags:
  - core_option
  - medium_high_competitiveness
  - exam_heavy
  - academic_record_heavy
  - academic_exam_required
  - english_advantage
  - high_cost
  - strong_clinical_exposure

admission:
  intake_month: September

  applications_open_date: NULL # ANNUAL_UPDATE_REQUIRED — applications open via online platform

  rolling_admissions:
    enabled: false
    estimated_end_date: NULL

  admission_rounds:
    enabled: true
    count: 2

    rounds:
      - round: 1
        application_deadline: NULL # ANNUAL_UPDATE_REQUIRED
        exam_date: "2026-01-31" # ANNUAL_UPDATE_REQUIRED — presential in Córdoba and Sevilla
        results_date: "2026-02-09" # ANNUAL_UPDATE_REQUIRED
        deposit_deadline: NULL # ANNUAL_UPDATE_REQUIRED

      - round: 2
        application_deadline: NULL # ANNUAL_UPDATE_REQUIRED
        exam_date: "2026-02-14" # ANNUAL_UPDATE_REQUIRED — presential in Córdoba and Sevilla
        results_date: "2026-02-23" # ANNUAL_UPDATE_REQUIRED
        deposit_deadline: NULL # ANNUAL_UPDATE_REQUIRED

  exam_required: true
  interview_required: false

academic_record:
  minimum_requirement:
    enabled: false
    grade_source: NULL
    minimum_grade: NULL

  competitive_filter:
    enabled: true
    grade_source: first_year_baccalaureate
    approx_candidates_selected: 60

curriculum:
  international_curriculums_accepted: PENDING_CONFIRMATION
  total_ects: 360
  formacion_basica_ects: 102
  obligatorias_ects: 189
  optativas_ects: 9
  practicas_externas_ects: 54
  tfg_ects: 6
  curriculum_model: ABP # Problem-Based Learning (Aprendizaje Basado en Problemas)

competitiveness:
  level: medium_high

admissions_statistics:
  annual_applications: NULL # 1,400+ applicants across all Health Science programs in first call (2023); Medicine subset unknown
  seats: 60
  applicants_per_seat: NULL # ANNUAL_UPDATE_REQUIRED

  last_admitted_scores:
    - intake_year: 2025
      round: NULL
      score: PENDING_CONFIRMATION
      score_type: loyola_admission_composite
      notes: "Loyola does not publish official admission scores. Composite = 65% nota de 1º Bachillerato + 35% internal aptitude and English test."

international_profile:
  international_students_percentage: NULL
  international_nationalities: []

clinical_training:
  primary_hospitals:
    - "Hospital San Agustín (Dos Hermanas, Sevilla)"
    - "Hospitales de San Juan de Dios (Andalucía network)"
  hospital_network: PENDING_CONFIRMATION # Additional hospital agreements not fully disclosed
  clinical_start_year: 6 # Formal PE hospital rotations in Y6; simulation-based clinical skills from Y1
  pe_rotations_year: 6
  pe_rotations_count: 11
  pe_rotation_services:
    - "Medicina Interna"
    - "Dermatología"
    - "Oftalmología"
    - "Otorrinolaringología"
    - "Psiquiatría"
    - "Cirugía"
    - "Obstetricia y Ginecología"
    - "Medicina Familiar y Comunitaria"
    - "Urgencias y Emergencias"
    - "Pediatría"

accreditation:
  aneca_verified: true # BOE published February 2024; Consejo de Ministros approval December 2023
  wfme_accredited: PENDING_CONFIRMATION

pricing:
  application_fee: 50 # EUR — non-refundable; ANNUAL_UPDATE_REQUIRED
  reservation_fee: 2300 # EUR — applied toward total; ANNUAL_UPDATE_REQUIRED
  enrollment_fee: 700 # EUR — annual matriculation; ANNUAL_UPDATE_REQUIRED
  price_per_ects: 244 # EUR; ANNUAL_UPDATE_REQUIRED (2026-27)
  annual_ects_y1: 60
  annual_teaching_fees_y1: 15340 # EUR total first year (matrícula included); ANNUAL_UPDATE_REQUIRED
  total_degree: ANNUAL_UPDATE_REQUIRED # ~92,000 EUR estimated across 6 years

mir_outcomes:
  pass_rate: PENDING_CONFIRMATION # First cohort graduates in ~2029; no MIR data yet

contact:
  phone: "+34 900 101 077"
  admissions_email: "admisiones@uloyola.es"
  website: "https://www.uloyola.es/grados/grado-medicina"
  campus_address: "Avda. de las Universidades, 2 — 41704 Dos Hermanas, Sevilla"

dean: NULL # ANNUAL_UPDATE_REQUIRED

programs:
  - id: loyola-medicine-sevilla
    campus: "Dos Hermanas (Sevilla) — Campus principal"
    modality: standard

    strategic_tags:
      - core_option
      - medium_high_competitiveness
      - exam_heavy
      - academic_record_heavy
      - academic_exam_required
      - english_advantage
      - high_cost
      - strong_clinical_exposure

    teaching_languages:
      - Spanish

    regional_language_possible: false
    regional_language: NULL

    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: true
      minimum_english_level: NULL # English tested in admissions; no minimum certification required

    seats: 60

    program_statistics:
      annual_applications: NULL
      seats: 60
      applicants_per_seat: NULL
      last_admitted_scores:
        - intake_year: 2025
          round: NULL
          score: PENDING_CONFIRMATION
          score_type: loyola_admission_composite
          notes: "No official score data published. High demand (1,400+ applicants for health sciences in first call, 2023)."

    program_specific_admission:
      enabled: false

    evaluation_model:
      overall_model_type: weighted

      admission_pathways:
        - eligible_profiles:
            - bachillerato_students
            - international_equivalents

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 0.65
              grade_source: first_year_baccalaureate
              minimum_required_grade: NULL
              notes: "65% of the admission score = nota media de 1º Bachillerato (scale 0–10). Only 1º Bachillerato grade is used — NOT the EBAU/PAU score."

            - component: academic_exam
              enabled: true
              role: weighted
              weight: 0.20
              exam_variant: onsite_internal_exam
              exam_format: multiple_choice
              delivery_mode: onsite
              online_conditions: NULL
              subjects:
                - "Psychotechnic test: mathematics, statistics, probability, logical reasoning, spelling/language"
                - "Personality assessment (Likert scale)"
              syllabus_alignment:
                biology:
                  scope:
                    - not_applicable
                  notes: "Biology not specifically tested. Aptitude exam focuses on numeracy, logic, and reasoning — not science content."
                chemistry:
                  scope:
                    - not_applicable
                  notes: "Chemistry not tested."
                physics:
                  scope:
                    - not_applicable
                  notes: "Physics not specifically tested; basic numeracy and statistics included."
                mathematics:
                  scope:
                    - first_year_baccalaureate
                  notes: "Basic mathematics, statistics, and probability tested — not advanced calculus."
                other_subjects: []
              exam_difficulty:
                level: medium
                rationale:
                  - reasoning_based
                  - memorization_heavy
                notes: "Psychotechnic + personality format. No published syllabus for science content. Difficulty comparable to standard psychometric aptitude tests."
              best_attempt_counts: NULL
              notes: "Aptitude test is ~70% of the 35% exam weight. Exam is presential (Dos Hermanas / Córdoba campuses). Duration ~90 minutes for this component."

            - component: english_test
              enabled: true
              role: weighted
              weight: 0.15
              test_format: mixed
              delivery_mode: onsite
              online_conditions: NULL
              minimum_level: NULL
              bonus_max: NULL
              bonus_scale:
                B2: NULL
                C1: NULL
                C2: NULL
              notes: "English test (~30% of the 35% exam weight): multiple-choice grammar questions + listening comprehension (audio). No official certificate required. Test taken alongside the aptitude test on the same day. Estimated duration ~45 minutes."
---

# Loyola — Grado en Medicina (Universidad Loyola, Compañía de Jesús)

## Overview

Universidad Loyola is the first private institution in Andalucía to obtain authorisation to teach Medicine. It admitted its inaugural cohort in November 2023, making it the newest active Medicine degree in Spain at the time of this writing. By the 2026-27 intake, the programme will be entering its fourth year — a fact with significant strategic implications: no MIR outcome data exists yet, WFME accreditation is unconfirmed, and institutional processes are still being established.

Loyola's differentiation rests on two pillars: pedagogical and geographic. The pedagogical model is ABP (Problem-Based Learning / Aprendizaje Basado en Problemas), drawing inspiration from McMaster, Maastricht, and Aalborg — universities internationally recognised for this format. The geographic pillar is uniqueness: there is no other private Medicine degree in Andalucía, giving Loyola a monopoly position in a region historically underserved by private alternatives to the very competitive public University of Sevilla Medicine programme.

The admission model is distinctly different from most Spanish private medicine universities: 65% of the score comes from the nota de 1º Bachillerato (not EBAU/PAU), and 35% from an internal aptitude and English test. Students who excel academically in Bachillerato but did not sit or optimise the EBAU are particularly well-positioned here. The programme attracts very high demand — over 1,400 applicants competed across Loyola's health science degrees in the first open call in 2023.

At 15,340 EUR/year (60 ECTS × 244 EUR + 700 EUR matrícula), Loyola is among the more expensive private medicine options in Spain. The Jesuit identity permeates the programme through its pedagogical approach, ethical framework, and international university network — but unlike UCAM, does not mandate specific religious curriculum modules.

---

## Quick Evaluation

- **Admission model:** 65% nota de 1º Bachillerato + 35% internal test (aptitude + English)
- **No EBAU/PAU score used** — distinctive in the Spanish private medicine market
- **Exam format:** Psychotechnic + personality + English listening/grammar (presential, ~2.5 hours)
- **Exam dates 2026:** 31 January and 14 February (two rounds available)
- **Seats:** 60
- **Price per ECTS:** 244 EUR — total first year: ~15,340 EUR
- **Duration:** 6 years / 360 ECTS
- **Teaching method:** ABP (Problem-Based Learning) — Jesuit pedagogical model
- **Religious identity:** Jesuit — no mandatory theology modules (unlike UCAM), but Ignatian pedagogy embedded in methodology
- **MIR outcomes:** Not yet available (first cohort graduates ~2029)
- **Accreditation:** ANECA verified (Dec 2023); WFME PENDING_CONFIRMATION
- **Newest programme:** First private Medicine in Andalucía; programme in its 4th year in 2026-27

---

## Key Facts

| Field | Value |
|---|---|
| Full name | Universidad Loyola (Compañía de Jesús) |
| Short name | Loyola |
| Affiliation | Jesuit (UNIJES / IAJU) |
| Campus | Dos Hermanas (Sevilla) |
| Degree | Grado en Medicina (360 ECTS, 6 years) |
| Seats | 60 |
| Annual fee (Y1) | 15,340 EUR (matrícula included) / ANNUAL_UPDATE_REQUIRED |
| Price per ECTS | 244 EUR / ANNUAL_UPDATE_REQUIRED |
| Reservation fee | 2,300 EUR (applied toward total) / ANNUAL_UPDATE_REQUIRED |
| Enrollment fee | 700 EUR / ANNUAL_UPDATE_REQUIRED |
| Application fee | 50 EUR (non-refundable) |
| Admission model | 65% nota 1º Bachillerato + 35% internal test |
| Exam type | Psychotechnic + English (presential, no science content) |
| Exam dates 2026 | 31 January / 14 February — ANNUAL_UPDATE_REQUIRED |
| Teaching method | ABP (Problem-Based Learning) |
| ANECA | Verified (BOE Feb 2024) |
| WFME | PENDING_CONFIRMATION |
| MIR data | Not yet available — first graduates ~2029 |
| Year founded (Medicine) | 2023 |

---

## Program Options

Loyola offers a single Medicine programme delivered exclusively at the Dos Hermanas campus (Sevilla). There is no Córdoba or Granada campus variant for Medicine. The Córdoba and Granada campuses are used only as examination venues for the admission tests.

There is no bilingual track, no online variant, and no double-degree option currently involving Medicine. The programme is entirely Spanish-medium.

The Jesuit network (UNIJES/IAJU) provides international institutional connections — 190+ universities across 45 countries — but international mobility specifically for Medicine students requires individual verification (see International Exchange section).

---

## Program Structure

The degree covers 360 ECTS across six years, structured in five credit blocks:

| Block | ECTS |
|---|---|
| Formación Básica (FB) | 102 |
| Obligatorias (OB) | 189 |
| Optativas (OP) | 9 |
| Prácticas Externas (PE) | 54 |
| Trabajo Fin de Grado (TFG) | 6 |
| **Total** | **360** |

The programme organises content into six BOE-level thematic modules rather than traditional subject silos (consistent with the ABP methodology):

1. **Morfología, estructura y función del cuerpo humano** — Biological sciences foundations; anatomy, physiology, histology, embryology.
2. **Medicina social, habilidades de comunicación e iniciación a la investigación** — Public health, psychosocial aspects, communication skills, biomedicine.
3. **Formación clínica humana** — Clinical sciences integrated across systems; patient-centred learning.
4. **Procedimientos diagnósticos y terapéuticos** — Diagnostic and therapeutic procedures.
5. **Optativas** — Two tracks: *Avances en Medicina* and *Ampliación en Humanidades* (9 ECTS total).
6. **Prácticas externas** — Hospital rotations in Year 6 (54 ECTS).

**Important structural note:** Given the ABP model, the programme does not publish a traditional subject-by-subject yearly breakdown. Learning is organised around clinical problem sets that integrate content from multiple disciplines simultaneously. This is a fundamental methodological departure from traditional Medicine curricula. Students work in small groups, analyse clinical cases, and acquire theoretical knowledge as needed to solve those cases — with tutors as facilitators rather than lecturers.

**Presentiality and timetabling:** Loyola has implemented increased presential hours (up to 50% more than originally planned) and programmes some activities on Saturdays. Students should factor this into their schedule expectations.

---

## Teaching Methodology

ABP (Aprendizaje Basado en Problemas / Problem-Based Learning) is the defining feature of Loyola's Medicine programme. It is the same methodology used at McMaster University (Canada), Maastricht University (Netherlands), and Aalborg University (Denmark) — universities internationally recognised as ABP pioneers — and at Universidad de Deusto in Spain (also Jesuit).

Under ABP:
- Students receive a clinical problem or case rather than a lecture.
- Working in small groups, they identify what they need to learn to understand and resolve the case.
- Self-directed learning is core: students research independently, then reconvene to synthesise.
- Tutors guide and facilitate rather than transmit information.

This approach requires a fundamentally different learning style compared to lecture-heavy traditional Medicine programmes. Students who thrive in unstructured environments, collaborative settings, and self-directed study tend to adapt well. Students who prefer structured teacher-led instruction and clear content demarcation may find the model challenging initially.

The Jesuit pedagogical tradition (pedagogía ignaciana) underpins the broader framework: emphasis on the whole person (cura personalis), critical reflection, and social responsibility. This shapes how the institution frames medical education — as a formation of a person and a professional, not only a transfer of knowledge.

**Simulation infrastructure:** Centro de Simulación Clínica Avanzada — a purpose-built advanced clinical simulation centre including consulting rooms, skills labs, an operating theatre simulation, ICU, and hospital ward. Specialised laboratories: Anatomía, Histología y Anatomía Patológica, Biotecnología, Fisiología y Biofísica, Biomecánica.

---

## Clinical Training

Clinical training at Loyola is structured in two phases: simulation-based clinical skills throughout Years 1–5 (via the Centro de Simulación Clínica Avanzada), escalating to full-time hospital rotations in Year 6.

**Year 6 hospital rotations (54 ECTS / 11 rotations):**
- Medicina Interna
- Dermatología
- Oftalmología
- Otorrinolaringología (ORL)
- Psiquiatría
- Cirugía
- Obstetricia y Ginecología
- Medicina Familiar y Comunitaria
- Urgencias y Emergencias
- Pediatría

(Note: listed as 11 rotations across 10 specialities — one speciality may be divided into two separate rotation blocks. PENDING_CONFIRMATION on exact breakdown.)

**Confirmed hospital partners:**
- Hospital San Agustín (Dos Hermanas, Sevilla) — dedicated working commission established specifically for Medicine and Nursing students from 2024-25
- Hospitales de San Juan de Dios (Andalucía network) — formal agreement for Medicine and Nursing students

**ANNUAL_UPDATE_REQUIRED** — Hospital agreements for clinical rotations are being established progressively as the cohorts advance. The first cohort reaches Year 6 rotations in approximately 2028-29. The full rotation partner network for later cohorts (including 2026-27 intake) is still being formalised and requires ongoing verification.

The absence of a large public university hospital in the primary clinical network is a structural consideration. Hospital San Agustín (Dos Hermanas) is a smaller secondary-care hospital. Students and families should verify the full partner list for Year 6 directly with Loyola before the 2026-27 intake year.

---

## International Recognition and Opportunities

ANECA verification: The Grado en Medicina was declared official by the Consejo de Ministros (December 2023) and published in the BOE (February 2024). This provides the regulatory baseline for practice in Spain and EU mutual recognition.

**Important historical context:** In July 2023, the Consejo de Universidades initially prohibited the degree implantation following a negative evaluation by the ACCUA (Agencia Andaluza del Conocimiento). The evaluation cited doubts about infrastructure and equipment readiness. Loyola requested a review, which resolved in their favour (September 2023), enabling the Junta de Andalucía to authorise the programme (November 2023). The official plan de estudios was subsequently approved through the standard inter-ministerial process.

**WFME accreditation:** PENDING_CONFIRMATION. This is critical for students planning postgraduate training or licensure in the UK, USA, Canada, Australia, or other jurisdictions requiring WFME recognition. The programme is too young for standard WFME review cycles. Students with international postgraduate ambitions should verify this directly with Loyola before enrolling.

**International mobility:** Loyola participates in Erasmus+ with 200+ bilateral agreements across 45 countries. Whether Medicine students specifically have access to outgoing Erasmus clinical placements requires verification — Medicine programmes often have restricted mobility windows given curriculum intensity and clinical placement requirements. Confirm medicine-specific partners before enrolling.

---

## Admission Model

Loyola's admission model is unique in the Spanish private medicine market: it does not use the EBAU/PAU score. Instead:

**Admission composite:**
- **65% — Nota de 1º Bachillerato** (arithmetic mean of all 1º Bachillerato subjects, scale 0–10)
- **35% — Internal admission test** (presential, two components):
  - Aptitude test (~70% of the test weight): psychotechnics (mathematics, statistics, probability, logical reasoning, spelling/language), and personality assessment (Likert scale)
  - English test (~30% of the test weight): multiple-choice grammar + audio listening comprehension

**Key implications of this model:**
1. Students who have not sat the EBAU or who have a poor EBAU score are **not disadvantaged** here — the EBAU is irrelevant.
2. Students who performed strongly in 1º Bachillerato (before EBAU pressure) but then underperformed in EBAU examinations may find Loyola specifically advantageous.
3. Science knowledge (Biology, Chemistry, Physics) is **not tested in the exam**. The aptitude component focuses on reasoning, numeracy, and logic.
4. English proficiency is tested but requires no prior certification — the level is assessed directly in the admissions test.
5. Personality is assessed (Likert scale) but its weight in the final scoring is PENDING_CONFIRMATION.

No minimum threshold is published. Admission is competitive based on the composite score, ranked across all candidates for the 60 available seats.

---

## Admission Process

1. **Register** on the Loyola admissions platform. Obtain user credentials.
2. **Pay the application fee:** 50 EUR (non-refundable). This finalises the inscription for the chosen exam round.
3. **Upload required documentation** — specifically documents supporting the nota de 1º Bachillerato. Documentation requirements listed on the admissions platform.
4. **Select exam round:** Round 1 (31 January 2026) or Round 2 (14 February 2026). ANNUAL_UPDATE_REQUIRED.
5. **Attend the exam presentially** at the Dos Hermanas (Sevilla) campus. The Córdoba campus may also be available as a venue — confirm at registration.
6. **Receive admission result** approximately 9 days after the exam date.
7. **If admitted:** Pay the reservation fee (2,300 EUR) to secure the place. This amount is applied toward the total annual fee.
8. **Formal enrolment:** Completed in June–August before the September academic year start.

**For previously admitted students (prior intake year):** These applicants can request admission without retaking the exam. Contact admisiones@uloyola.es.

**For university transfer applicants** (traslado de expediente): A specific process applies. Medicine is explicitly excluded from the standard traslado exemption route — applicants must take the standard admissions test.

---

## Admission Timeline

| Milestone | Date (2026-27 indicative) |
|---|---|
| Round 1 exam | 31 January 2026 — ANNUAL_UPDATE_REQUIRED |
| Round 1 results | ~9 February 2026 — ANNUAL_UPDATE_REQUIRED |
| Round 2 exam | 14 February 2026 — ANNUAL_UPDATE_REQUIRED |
| Round 2 results | ~23 February 2026 — ANNUAL_UPDATE_REQUIRED |
| Reservation fee payment window | After admission confirmation — ANNUAL_UPDATE_REQUIRED |
| Formal enrolment (Phase 1) | 18–30 June 2026 — ANNUAL_UPDATE_REQUIRED |
| Formal enrolment (Phase 2) | 2 July – 31 August 2026 — ANNUAL_UPDATE_REQUIRED |
| Academic year begins | November 2026 — ANNUAL_UPDATE_REQUIRED |

**Strategic observation:** Loyola's exam schedule falls in late January and mid-February — very early compared to most private medicine universities which typically run exams from February to May. Students aiming for Loyola must have their application and documentation ready before the end of January. Missing both rounds in the same year effectively closes Loyola as an option for that intake cycle.

The early timeline also means Loyola results are known before most other private universities have even held their exams. This creates a valuable contingency logic: students admitted to Loyola in February can still pursue other universities (CEU, UNAV, UIC, etc.) through March–June, keeping multiple paths open.

---

## Admission Score Distribution

Loyola's scoring system combines two fundamentally different inputs. Understanding the strategic implications of each is essential.

**65% — Nota de 1º Bachillerato:**
This is a cumulative GPA from the first year of Bachillerato (the year before EBAU). It cannot be changed at application time. Students who received strong marks in 1º Bachillerato are structurally advantaged regardless of their EBAU performance. The scale is 0–10, contributing up to 6.5 points to the composite.

**35% — Internal admission test:**
The test is not a science exam — it tests reasoning, numerical aptitude, language, and English. Biology and Chemistry knowledge does not provide a direct advantage. A student with strong logical reasoning, good English, and attention to verbal accuracy can outperform a student with better science knowledge who has poorer aptitude test skills.

**Strategic implications:**
- A student with nota de 1º Bachillerato of 7.5 and strong test performance (e.g., 8.5/10) would have composite ≈ 7.5×0.65 + 8.5×0.35 ≈ 4.875 + 2.975 = 7.85/10.
- A student with 9.0 average in 1º Bachillerato but average test performance (6.5) scores ≈ 9.0×0.65 + 6.5×0.35 ≈ 5.85 + 2.275 = 8.125/10.
- The bachillerato grade dominates. Improving test performance by 2 points adds ~0.7 points to the composite; improving bachillerato by 2 points adds ~1.3 points.

**What this means for preparation:** Winners students who are targeting Loyola should focus on psychotechnic reasoning skills and English listening/grammar rather than science review. This is a fundamentally different preparation pathway from exam-heavy universities.

**Published cutoff data:** Not officially disclosed by Loyola. First cohort demand (1,400+ applicants for all health science programs in 2023) suggests high competition for 60 seats. Actual admission scores are PENDING_CONFIRMATION.

---

## Costs and Payment Structure

| Cost Item | Amount | Notes |
|---|---|---|
| Application fee | 50 EUR | Non-refundable; ANNUAL_UPDATE_REQUIRED |
| Reservation fee | 2,300 EUR | Applied toward total; ANNUAL_UPDATE_REQUIRED |
| Annual enrollment fee (matrícula) | 700 EUR | ANNUAL_UPDATE_REQUIRED |
| Price per ECTS | 244 EUR | ANNUAL_UPDATE_REQUIRED (2026-27 data) |
| Annual teaching fee (60 ECTS) | 14,640 EUR | ANNUAL_UPDATE_REQUIRED |
| Total first year (matrícula included) | 15,340 EUR | ANNUAL_UPDATE_REQUIRED |
| Estimated total degree (6 years) | ~92,000 EUR | ANNUAL_UPDATE_REQUIRED — assumes flat annual fee |

**VAT:** Educational services are exempt from IVA under Spanish tax law.

**Payment structure:** The total annual fee is divided into monthly instalments (mensualidades) spread across each semester. Students who prefer alternative payment schedules should indicate this at enrolment. Bank financing agreements are available through Loyola's financial partner institutions.

**Excellence awards:** Students who obtain a nota de acceso ≥ 9.0 (in the June call) may qualify for Loyola's Premios a la Excelencia Académica. Specific amounts applicable to Medicine are PENDING_CONFIRMATION.

**Price positioning:** At 15,340 EUR/year, Loyola is above the mid-market of Spanish private medicine (UCAM at 14,200 EUR/year, some CEU programmes around 14,000–16,000 EUR/year). It is cheaper than some premium programmes (e.g., CEU San Pablo ~17,000 EUR, UNAV ~16,000 EUR) but not by a wide margin.

---

## Scholarships and Financial Aid

Loyola maintains a scholarship and financial aid programme across all its degrees, funded from the university's own resources. The stated commitment is that no academically qualified student should be prevented from studying due to financial reasons.

Specific scholarship amounts, eligibility criteria, and deadlines applicable to the Medicine degree for 2026-27 are PENDING_CONFIRMATION. Students are advised to contact the Loyola financial aid office directly after receiving an admission offer.

Spanish national MEC/Ministerio scholarships may be partially applicable to eligible students, but private university fees typically exceed covered amounts. Verify directly.

Loyola has agreements with financial institutions to facilitate payment financing for undergraduate degrees.

---

## Accommodation and Cost of Living

**Dos Hermanas:** A town of approximately 140,000 inhabitants located ~18 km south of central Sevilla. It is well connected to central Sevilla by train (Cercanías, ~20 minutes). The campus is adjacent to the main Dos Hermanas railway station.

Student accommodation near campus or in Sevilla city is available via private rental. Estimated monthly costs for a student (accommodation, food, transport, personal) range approximately 700–1,000 EUR in Dos Hermanas / southern Sevilla. Sevilla city centre is somewhat higher, approximately 800–1,200 EUR/month.

Loyola does not operate its own student residences but provides accommodation guidance through the student services office. Private student residences in Dos Hermanas and Sevilla are available.

Sevilla offers a rich cultural, social, and gastronomic environment — one of Spain's major cities. For students relocating from elsewhere in Spain or internationally, quality of life is generally high relative to cost compared to Madrid or Barcelona.

---

## International Exchange and Mobility Programs

Loyola participates in Erasmus+ with over 200 bilateral agreements spanning 45 countries across Europe, the Americas, Asia, and Africa. It also offers SICUE (national) exchanges, Erasmus+ placements (academic and professional), and external exchange programmes with partner universities.

**Critical caveat for Medicine:** Whether Medicine students specifically have access to outgoing Erasmus+ placements — particularly for clinical years — requires explicit confirmation. Medicine programmes in Spain typically have restricted mobility due to the clinical placement structure and regulatory requirements. Students interested in international exchange should request a current list of Medicine-specific Erasmus partners from the Loyola Internationalisation Office before enrolling.

The Jesuit institutional network (IAJU) connects Loyola to over 190 Jesuit universities worldwide. Whether this network provides formal academic exchange pathways for Medicine students is PENDING_CONFIRMATION.

---

## MIR Preparation and Professional Outcomes

**MIR outcomes: Not yet available.**

The first Loyola Medicine cohort enrolled in November 2023 and will complete the degree in approximately 2029. No MIR pass rate or ranking data exists at the time of this writing (May 2026).

This is the most significant factual gap relative to other private Medicine programmes in Spain, which can cite MIR pass rates of 90–99%. Prospective students cannot benchmark Loyola's postgraduate outcomes against other institutions based on evidence — only based on the university's stated preparation approach.

Loyola states that students will be supported in MIR preparation through its academic and careers services. The ABP methodology, which emphasises clinical reasoning and integration rather than memorisation, is theoretically aligned with the clinical reasoning demands of the MIR. However, empirical evidence for Loyola Medicine specifically does not yet exist.

**Employment rate (general):** Loyola reports an 88% employment rate across its graduate programmes. This figure is not Medicine-specific and should not be used to infer Medicine outcomes.

**Título oficial:** Loyola graduates receive the título oficial de Grado en Medicina, providing automatic licence to practise in Spain and EU mutual recognition.

---

## Strategic Fit

### Good Fit For

- Students from Andalucía (particularly Sevilla province) who want a private Medicine alternative without relocating to other Spanish regions
- Students who performed well in 1º Bachillerato but did not optimise the EBAU — Loyola's model rewards exactly this profile
- Students with strong psychotechnic and English skills who can outperform peers on reasoning-based tests without specific science preparation
- Students who thrive in collaborative, self-directed learning environments and are comfortable with the ABP format
- Students who value a Jesuit institutional identity, international university network, and holistic educational philosophy
- Students who want to begin the admission process very early (January) and confirm their situation before other private universities run their exams

### Less Suitable For

- Students who need an established MIR outcomes track record to make an informed decision — no data exists yet
- Students with confirmed international postgraduate ambitions requiring WFME accreditation — this is unconfirmed
- Students who prefer structured, lecture-based, syllabus-driven learning — ABP requires a fundamentally different learning approach
- Students who need to be near their families outside of Andalucía — there is no viable second campus option for Medicine
- Students who are deterred by the high cost (~15,340 EUR/year) without strong financial planning
- Students counting on Saturday-free academic schedules — Loyola explicitly programmes Saturday morning activities

---

## Risks and Considerations

**Programme immaturity.** Loyola Medicine is four years old by the 2026-27 intake. No MIR data, limited alumni network, evolving clinical hospital partnerships, and ongoing institutional process establishment. This is a meaningful risk compared to programmes with 10–20 years of track record. Students are, in effect, joining a programme that is still proving itself.

**WFME accreditation gap.** WFME accreditation is PENDING_CONFIRMATION. Loyola is not in a position to complete a standard WFME review cycle given its age. Students targeting UK Foundation Programme, US ECFMG registration, or other WFME-dependent pathways face uncertainty.

**Clinical partner network under construction.** The primary hospital partner (Hospital San Agustín) is a secondary-care community hospital, not a large tertiary university hospital. The full Year 6 rotation network for the 2026-27 cohort (who would start rotations in approximately 2031) is PENDING_CONFIRMATION. Students should verify the clinical network directly with Loyola before committing.

**Complex accreditation history.** The initial ACCUA rejection in 2023 — overturned on review — created reputational uncertainty that persists in the market. The programme is now legally and academically operating, but the history is worth noting as context for institutional robustness.

**ABP learning curve.** Students who have prepared under traditional science-heavy study methods (for other university exams) may find the ABP format disorienting initially. The model demands self-direction and tolerance for ambiguity. This is not a weakness per se, but it requires alignment between the student's learning style and the methodology.

**Saturday classes.** Loyola explicitly programmes Saturday morning activities as part of its increased presentiality model. This affects students who travel home on weekends or have Saturday commitments.

**No science exam advantage.** Students who have invested heavily in Biology and Chemistry preparation for other private university exams will find that knowledge provides minimal direct advantage in the Loyola test. The test rewards reasoning and English skills, not science content.

---

## Important Notes

- Medicine is only offered at the Dos Hermanas (Sevilla) campus. Córdoba and Granada campuses are examination venues only.
- The 50 EUR application fee is paid at inscription and is non-refundable under any circumstances.
- The 65% academic record uses only 1º Bachillerato grades — not EBAU, not 2º Bachillerato, not the combined nota de acceso.
- The exam is presential only for Medicine — unlike some other Loyola programmes that offer remote exam options.
- Reservation fee (2,300 EUR) is applied toward the total annual fee, not an extra cost on top.
- ANNUAL_UPDATE_REQUIRED applies to all fees, exam dates, and enrolment deadlines.
- Students previously admitted in a prior year can apply without retaking the exam via a specific track.

---

## Key Insight

Loyola is the only private Medicine programme in Andalucía — a position of structural advantage that is unlikely to change in the near term given the regulatory and infrastructure barriers to entry. For students based in Sevilla, Córdoba, Málaga, or the broader Andalucía region, Loyola eliminates the need to relocate to Madrid, Barcelona, Valencia, or Pamplona to access private Medicine.

The admission model is the most distinctive in Spain for private Medicine: it rewards 1º Bachillerato performance and reasoning skills, ignores the EBAU entirely, and tests English communication rather than science content. For a specific profile of student — strong academic record in early Bachillerato, good aptitude test skills, comfortable in collaborative learning environments — Loyola may be the best-fit programme in Spain.

The programme immaturity is the decisive risk factor. Families making a 90,000 EUR, six-year commitment to an institution with no MIR track record and unconfirmed WFME status are taking on substantially more uncertainty than those choosing well-established programmes. This risk can be acceptable — but it must be consciously accepted, not overlooked.

---

## Final Takeaway

Universidad Loyola's Medicine programme is a high-potential, high-risk option within the Spanish private medicine landscape. Its geographic monopoly in Andalucía, early exam calendar, differentiated admission model, and Jesuit-ABP methodology create a genuinely distinctive value proposition. For the right student — strong 1º Bachillerato record, Andalucía-based, self-directed learner, comfortable with an emerging institution — it can be the optimal choice.

The unknowns are real: no MIR data, WFME unconfirmed, hospital network still developing. These are not disqualifying factors, but they shift the risk profile. Students and families choosing Loyola should do so with a clear understanding that they are enrolling in a programme that is still building its track record, not one that has already proved its outcomes.

The 50 EUR application fee and early February exam dates make Loyola a low-friction first move in the private medicine admissions season — test the fit early, then keep other options open in parallel.

---

## Frequently Asked Questions

**Does Loyola use the EBAU/PAU score for Medicine admissions?**
No. Loyola's admission composite uses the nota de 1º Bachillerato (65%) and an internal admissions test (35%). The EBAU score is not a factor. This makes Loyola's admissions model unique among Spanish private medicine universities.

**What does the Loyola admissions test consist of?**
Two components: (1) a psychotechnic aptitude test covering mathematics, statistics, probability, logical reasoning, spelling, and a personality assessment (Likert scale); (2) an English language test with multiple-choice grammar questions and listening comprehension (audio). Duration approximately 2.5 hours total. No Biology, Chemistry, or Physics tested.

**When are the exam dates for 2026-27?**
31 January 2026 (Round 1) and 14 February 2026 (Round 2). Both are presential at the Dos Hermanas (Sevilla) campus. Dates are ANNUAL_UPDATE_REQUIRED.

**Is the exam available online?**
No — Medicine exams are presential only. Some other Loyola degree exams offer a remote option, but Medicine is not among them.

**What is Loyola's MIR pass rate?**
No data exists. The first cohort (enrolled November 2023) will graduate approximately 2029. No MIR outcomes are available at the time of this writing.

**Is WFME accreditation confirmed?**
No — WFME accreditation status is PENDING_CONFIRMATION. Students planning postgraduate training or licensure in the UK, USA, Canada, or Australia should verify this directly with Loyola before enrolling.

**What is ABP and is it difficult?**
ABP (Aprendizaje Basado en Problemas / Problem-Based Learning) organises learning around clinical cases rather than lectures. Students work in small groups, identify what they need to learn, and acquire knowledge autonomously. It requires self-direction and comfort with ambiguity. It is not harder than traditional Medicine — it demands a different kind of effort and study discipline.

**Does Loyola have Saturday classes?**
Yes. Loyola explicitly programmes some Saturday morning activities as part of its increased presentiality model. Students with Saturday commitments should factor this in.

**How many students are admitted per year?**
60 seats are authorised by the Junta de Andalucía. Loyola received over 1,400 applicants across health sciences programmes in the first open call (2023). The precise number applying specifically to Medicine and the last-admitted composite score are not officially disclosed. Competition for the 60 seats is high.

**Is Loyola a Jesuit university? What does that mean practically?**
Yes — Loyola belongs to the Compañía de Jesús and is integrated in UNIJES and the international IAJU network of 190+ Jesuit universities. The Jesuit character shapes the pedagogical methodology (Ignatian pedagogy: cura personalis, reflection, social responsibility) and the international network. Unlike some Catholic universities, Loyola does not impose mandatory theology or religious studies modules — the identity is expressed through teaching philosophy rather than obligatory religious curriculum.

**Can I study Medicine at the Loyola Córdoba campus?**
No. Medicine is only available at Dos Hermanas (Sevilla). Córdoba functions as an exam venue for the admissions test but does not offer Medicine classes.

**What hospitals will I rotate in during Year 6?**
Confirmed partners include Hospital San Agustín (Dos Hermanas) and the Hospitales de San Juan de Dios network. The full rotation partner list for the 2026-27 cohort's Year 6 (approximately 2031-32) is still being established. ANNUAL_UPDATE_REQUIRED — verify the current partner list directly with Loyola.
