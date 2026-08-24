---
id: ucam-medicine
type: university
subtype: private

name: "Grado en Medicina — UCAM (Universidad Católica San Antonio de Murcia)"
short_name: UCAM

degree: Medicine

last_update: "2026-05-27"
valid_for_intake: "2026-2027"

institution_type: universidad_privada
religious_affiliation: Catholic
parent_group: "Universidad Católica San Antonio de Murcia (independent Catholic university)"
ruct_code: PENDING_CONFIRMATION
year_founded_medicine: PENDING_CONFIRMATION
inaugural_cohort: false

location:
  city: "Murcia / Cartagena"
  region: "Región de Murcia"
  country: Spain

strategic_tags:
  - core_option
  - medium_competitiveness
  - exam_heavy
  - academic_record_heavy
  - high_cost
  - strong_clinical_exposure
  - academic_exam_required
  - no_academic_exam

admission:
  intake_month: September

  applications_open_date: NULL # ANNUAL_UPDATE_REQUIRED

  rolling_admissions:
    enabled: false
    estimated_end_date: NULL

  admission_rounds:
    enabled: false
    count: 1

    rounds:
      - round: 1
        application_deadline: "2026-07-03" # ANNUAL_UPDATE_REQUIRED
        exam_date: NULL # EBAU is an external national exam; no internal exam date
        results_date: "2026-07-08" # ANNUAL_UPDATE_REQUIRED
        deposit_deadline: NULL # ANNUAL_UPDATE_REQUIRED

  exam_required: false # Relies on external EBAU; no internal university exam
  interview_required: false

academic_record:
  minimum_requirement:
    enabled: true
    grade_source: pau_nota_de_admision
    minimum_grade: 11.00

  competitive_filter:
    enabled: true
    grade_source: pau_nota_de_admision
    approx_candidates_selected: 90

curriculum:
  international_curriculums_accepted: PENDING_CONFIRMATION
  total_ects: 360
  formacion_basica_ects: 66
  obligatorias_ects: 228
  optativas_ects: 6
  practicas_externas_ects: 54
  tfg_ects: 6

competitiveness:
  level: medium

admissions_statistics:
  annual_applications: NULL
  seats: 90
  applicants_per_seat: NULL

  last_admitted_scores:
    - intake_year: 2025
      round: 1
      score: 11.000
      score_type: pau_nota_de_admision_minimum
      notes: "Official minimum threshold (nota de admisión ≥ 11.00). Actual admission scores historically above 11. Shared cupo único list for Murcia and Cartagena campuses."

international_profile:
  international_students_percentage: NULL
  international_nationalities: []

clinical_training:
  primary_hospital_murcia: "Hospital La Vega (Murcia)"
  primary_hospital_cartagena: "Hospital Santa Lucía (Cartagena)"
  hospital_network: "Servicio Murciano de Salud (SMS)"
  additional_hospitals:
    - "Hospital Santa María del Rosell (Cartagena — SMS)"
    - "Hospital Virgen de la Caridad (Cartagena — SMS)"
    - "Hospital Rafael Méndez (Lorca — SMS)"
  clinical_start_year: 3 # Clinical subject content (simulation-based) from Y3; formal PE hospital rotations in Y6
  pe_start_year: 6

accreditation:
  aneca_verified: true
  wfme_accredited: PENDING_CONFIRMATION

pricing:
  preadmission_fee: NULL # ANNUAL_UPDATE_REQUIRED
  reservation_fee: NULL # ANNUAL_UPDATE_REQUIRED
  annual_teaching_fees_eu: 14200 # ANNUAL_UPDATE_REQUIRED
  annual_teaching_fees_non_eu: 18900 # ANNUAL_UPDATE_REQUIRED
  price_per_ects: 236.67 # ANNUAL_UPDATE_REQUIRED
  total_degree_eu: ANNUAL_UPDATE_REQUIRED
  total_degree_non_eu: ANNUAL_UPDATE_REQUIRED

mir_outcomes:
  pass_rate: "98%"
  source: UCAM official communications

contact:
  admissions_email: "accesoportraslado@ucam.edu"
  traslado_contact: "nmatiacci@ucam.edu"
  website_murcia: "https://www.ucam.edu/estudios/grados/medicina-presencial"
  website_cartagena: "https://www.ucam.edu/cartagena/grados/medicina-presencial"
  admissions_phone: NULL # ANNUAL_UPDATE_REQUIRED

dean: NULL # ANNUAL_UPDATE_REQUIRED

programs:
  - id: ucam-medicine-murcia
    campus: "Murcia — Campus de Los Jerónimos"
    modality: standard

    strategic_tags:
      - core_option
      - medium_competitiveness
      - academic_exam_required
      - exam_heavy
      - high_cost
      - strong_clinical_exposure

    teaching_languages:
      - Spanish

    regional_language_possible: false
    regional_language: NULL

    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL

    seats: NULL # Part of shared 90-seat total; campus breakdown PENDING_CONFIRMATION

    program_statistics:
      annual_applications: NULL
      seats: NULL
      applicants_per_seat: NULL
      last_admitted_scores:
        - intake_year: 2025
          round: 1
          score: PENDING_CONFIRMATION
          score_type: pau_nota_de_admision
          notes: "Unified cupo único for both campuses. Minimum 11.00. Informal forum data suggests last admitted ~12.5–13.0 in Murcia campus for 2024-25."

    program_specific_admission:
      enabled: false

    evaluation_model:
      overall_model_type: weighted

      admission_pathways:
        - eligible_profiles:
            - bachillerato_plus_pau_ebau

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 0.60
              grade_source: full_baccalaureate
              minimum_required_grade: NULL
              notes: "NMB: nota media de bachillerato. Weight 0.6 in standard Spanish PAU formula."

            - component: academic_exam
              enabled: true
              role: weighted
              weight: 0.40
              exam_variant: PENDING_CONFIRMATION
              exam_format: mixed
              delivery_mode: onsite
              online_conditions: NULL
              subjects:
                - "PAU/EBAU Fase Obligatoria — Calificación Fase General (CFG): weight 0.4"
                - "Biología (ponderación 0.2)"
                - "Física (ponderación 0.2)"
                - "Matemáticas II (ponderación 0.2)"
                - "Química (ponderación 0.2)"
              syllabus_alignment:
                biology:
                  scope:
                    - second_year_baccalaureate
                  notes: "Standard Spanish EBAU Biology (2º Bachillerato)"
                chemistry:
                  scope:
                    - second_year_baccalaureate
                  notes: "Standard Spanish EBAU Chemistry (2º Bachillerato)"
                physics:
                  scope:
                    - second_year_baccalaureate
                  notes: "Standard Spanish EBAU Physics (2º Bachillerato)"
                mathematics:
                  scope:
                    - second_year_baccalaureate
                  notes: "Matemáticas II (EBAU standard)"
                other_subjects: []
              exam_difficulty:
                level: medium
                rationale:
                  - second_year_content
                notes: "External national EBAU. Difficulty is equivalent to standard Spanish university access exam."
              best_attempt_counts: NULL
              notes: "Formula: Nota Admisión = 0.6×NMB + 0.4×CFG + a×M1 + b×M2. Phase voluntaria ponderación subjects: Bio, Física, Mat II, Química (all 0.2). Only ORDINARIA 2025-2026 accepted for current year; prior two years both ORDINARIA and EXTRAORDINARIA valid."

        - eligible_profiles:
            - traslado_de_expediente

          components:
            - component: academic_record
              enabled: true
              role: eliminatory
              weight: NULL
              grade_source: full_baccalaureate
              minimum_required_grade: 8.00
              notes: "Bachillerato grade minimum 8.0. Minimum 30 ECTS recognized in UCAM plan required (legal requirement)."

            - component: interview
              enabled: true
              role: requirement_only
              weight: NULL
              interview_format: oral
              delivery_mode: onsite
              notes: "Mandatory personal interview. Contact nmatiacci@ucam.edu before July 3 to schedule."

  - id: ucam-medicine-cartagena
    campus: "Cartagena"
    modality: standard

    strategic_tags:
      - core_option
      - medium_competitiveness
      - academic_exam_required
      - exam_heavy
      - high_cost
      - strong_clinical_exposure

    teaching_languages:
      - Spanish

    regional_language_possible: false
    regional_language: NULL

    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL

    seats: NULL # Part of shared 90-seat total; campus breakdown PENDING_CONFIRMATION

    program_statistics:
      annual_applications: NULL
      seats: NULL
      applicants_per_seat: NULL
      last_admitted_scores:
        - intake_year: 2025
          round: 1
          score: PENDING_CONFIRMATION
          score_type: pau_nota_de_admision
          notes: "Unified cupo único with Murcia. Minimum 11.00. Informal forum data suggests last admitted ~11.8–12.5 in Cartagena campus for 2024-25."

    program_specific_admission:
      enabled: false

    evaluation_model:
      overall_model_type: weighted

      admission_pathways:
        - eligible_profiles:
            - bachillerato_plus_pau_ebau

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 0.60
              grade_source: full_baccalaureate
              minimum_required_grade: NULL
              notes: "Same formula as Murcia campus. NMB weight 0.6."

            - component: academic_exam
              enabled: true
              role: weighted
              weight: 0.40
              exam_variant: PENDING_CONFIRMATION
              exam_format: mixed
              delivery_mode: onsite
              online_conditions: NULL
              subjects:
                - "PAU/EBAU Fase Obligatoria (CFG): weight 0.4"
                - "Biología (ponderación 0.2)"
                - "Física (ponderación 0.2)"
                - "Matemáticas II (ponderación 0.2)"
                - "Química (ponderación 0.2)"
              syllabus_alignment:
                biology:
                  scope:
                    - second_year_baccalaureate
                  notes: "Standard EBAU Biology"
                chemistry:
                  scope:
                    - second_year_baccalaureate
                  notes: "Standard EBAU Chemistry"
                physics:
                  scope:
                    - second_year_baccalaureate
                  notes: "Standard EBAU Physics"
                mathematics:
                  scope:
                    - second_year_baccalaureate
                  notes: "Matemáticas II (EBAU)"
                other_subjects: []
              exam_difficulty:
                level: medium
                rationale:
                  - second_year_content
                notes: "External national EBAU."
              best_attempt_counts: NULL
              notes: "Identical admission model to Murcia campus. Cartagena historically slightly lower last-admitted scores."

        - eligible_profiles:
            - traslado_de_expediente

          components:
            - component: academic_record
              enabled: true
              role: eliminatory
              weight: NULL
              grade_source: full_baccalaureate
              minimum_required_grade: 8.00
              notes: "Same traslado requirements as Murcia campus."

            - component: interview
              enabled: true
              role: requirement_only
              weight: NULL
              interview_format: oral
              delivery_mode: onsite
              notes: "Mandatory personal interview for traslado track."
---

# UCAM — Grado en Medicina (Universidad Católica San Antonio de Murcia)

## Overview

UCAM (Universidad Católica San Antonio de Murcia) is an independent Catholic private university offering the Grado en Medicina across two campuses: Murcia (Campus de Los Jerónimos) and Cartagena. Both campuses share a unified admission list, the same curriculum, and the same pricing structure.

UCAM occupies a strategically distinct position in the Spanish private medicine landscape: it is one of the few private universities that relies entirely on the external EBAU (PAU) for admission — no internal exam, no interview, no English filter. This makes UCAM uniquely accessible to students who have already optimised their EBAU score and are looking for a confirmed path to medicine without additional parallel preparation. The minimum threshold is a nota de admisión of 11.00, but actual last-admitted scores historically range between approximately 11.8 and 13.0 depending on campus and cohort.

The Catholic identity of the institution is substantive rather than cosmetic: the curriculum includes Teología I and II, Doctrina Social de la Iglesia, Deontología Médica, and Ética Médica y Bioética I — mandatory across all years. Students who are uncomfortable with a religiously embedded academic environment should factor this carefully into their decision.

Clinical infrastructure is strong, anchored by agreements with the Servicio Murciano de Salud (SMS): Hospital La Vega (Murcia), Hospital Santa Lucía, Hospital Santa María del Rosell, Hospital Virgen de la Caridad (all Cartagena), and Hospital Rafael Méndez (Lorca). The MIR pass rate of 98% is UCAM's most cited competitive metric and reflects solid preparation outcomes.

At 14,200 EUR/year (EU students), UCAM sits at the lower end of private Spanish medicine fees, making it a relevant cost-efficiency option within the private sector.

---

## Quick Evaluation

- **Admission model:** EBAU/PAU only — no internal exam, no interview, no English requirement
- **Minimum score:** Nota de admisión ≥ 11.00
- **Seats:** 90 total across Murcia and Cartagena campuses (unified list)
- **Price:** 14,200 EUR/year (EU) / 18,900 EUR/year (non-EU) — 236.67 EUR/ECTS
- **Duration:** 6 years / 360 ECTS
- **Religious identity:** Catholic — mandatory theology and ethics modules every year
- **MIR outcomes:** 98% pass rate (official communications)
- **Clinical network:** Servicio Murciano de Salud — regional public hospital network
- **Practical learning:** Labster virtual labs, Mesa Anatómica Digital, Aula de Realidad Virtual, Sala de Anatomía
- **Competitiveness level:** Medium — scores above 11.0 required; Murcia campus historically more competitive than Cartagena

---

## Key Facts

| Field | Value |
|---|---|
| Full name | Universidad Católica San Antonio de Murcia |
| Short name | UCAM |
| Affiliation | Independent Catholic university |
| Campuses | Murcia (Los Jerónimos) · Cartagena |
| Degree | Grado en Medicina (360 ECTS, 6 years) |
| Seats | 90 total (shared cupo único list) |
| Annual fee (EU) | 14,200 EUR / ANNUAL_UPDATE_REQUIRED |
| Annual fee (non-EU) | 18,900 EUR / ANNUAL_UPDATE_REQUIRED |
| Price per ECTS | 236.67 EUR / ANNUAL_UPDATE_REQUIRED |
| Admission model | EBAU/PAU — no internal exam |
| Minimum admission score | 11.00 (nota de admisión) |
| Application deadline | 3 July 2026 / ANNUAL_UPDATE_REQUIRED |
| First results list | 8 July 2026 / ANNUAL_UPDATE_REQUIRED |
| MIR pass rate | 98% |
| ANECA | Verified |
| WFME | PENDING_CONFIRMATION |

---

## Program Options

UCAM offers a single Medicine curriculum delivered at two physically separate campuses. Admission is via a unified ranked list (cupo único): applicants rank their campus preference and are assigned based on nota de admisión score and preference order.

**Murcia — Campus de Los Jerónimos**
The main campus, located in the Guadalupe neighbourhood on the outskirts of Murcia. Full facilities including the Sala de Anatomía, Mesa Anatómica Digital, Aula de Realidad Virtual, Sala de Microscopios, Labster virtual lab access, and a hospital connection to Hospital La Vega. Historically higher last-admitted scores than Cartagena, likely reflecting higher demand.

**Cartagena**
Located in the coastal city of Cartagena (~50 km from Murcia). Shares the full curriculum but clinical training is anchored in Hospital Santa Lucía, Hospital Santa María del Rosell, and Hospital Virgen de la Caridad — all within the Servicio Murciano de Salud network. Historically slightly lower last-admitted scores, making it a more accessible entry point for the same program.

There is no bilingual or English-track variant. No online modality exists. Both campuses teach exclusively in Spanish.

---

## Program Structure

The degree covers 360 ECTS distributed across six years following the standard Spanish medicine degree structure:

| Block | ECTS |
|---|---|
| Formación Básica (BA) | 66 |
| Obligatorias (OB) | 228 |
| Optativas (OP) | 6 |
| Prácticas Externas (PE) | 54 |
| Trabajo Fin de Grado (TFG) | 6 |
| **Total** | **360** |

**Note on ECTS module size:** UCAM uses non-standard 4.5 ECTS modules for many subjects, particularly from Y2 onward. This affects course count per year but not total credit accumulation.

**Year-by-year summary:**

**Year 1 — Foundational Sciences**
Anatomía Humana I and II (6 BA each), Biología Celular (6 BA), Bioquímica (6 BA), Biología Molecular (6 BA), Fisiología Humana I (6 BA), Embriología Humana (3 BA), Bioestadística (6 BA), Fisiología y Técnicas de Laboratorio (3 BA), Principios de Nutrición (3 BA), Historia de la Medicina (3 OB), Teología I (3 OB), + 1 OP subject (3 ECTS: Humanidades or Ética Fundamental).

**Year 2 — Morphology, Physiology and Basic Pathology**
Neuroanatomía I and II (4.5 BA each), Histología (6 BA), Fisiología Humana II and III (6 BA each), Genética Humana (4.5 OB), Psicología Médica (6 BA), Microbiología Médica (6 BA), Patología General I (4.5 OB), Anatomía Patológica (6 OB), Teología II (3 OB), Doctrina Social de la Iglesia (3 OB).

**Year 3 — Introduction to Clinical Medicine**
All obligatorias: Deontología Médica (3 OB), Documentación Médica (3 OB), Patología General II (4.5 OB), Farmacología (6 OB), Diagnóstico por la Imagen I (4.5 OB), Fundamentos de Cirugía (6 OB), Ética Médica y Bioética I (3 OB), Obstetricia y Ginecología I (4.5 OB), ORL (4.5 OB), Aparato Cardiocirculatorio (6 OB), Aparato Digestivo (6 OB), Aparato Respiratorio (4.5 OB), Aparato Locomotor y Reumatología I (4.5 OB).

**Year 4 — Clinical Specialties**
All obligatorias (all 4.5 OB unless noted): Dermatología, Obstetricia y Ginecología II, Aparato Locomotor y Reumatología II, Enfermedades Infecciosas, Toxicología Clínica, Hematología, Nefro-Urología, Psiquiatría, Alergia e Inmunología, Oncología y Medicina Paliativa; Endocrinología y Nutrición Clínica (6 OB), Neurología (6 OB), Medicina de Urgencia (3 OB).

**Year 5 — Advanced Clinical and Community Medicine**
Metodología de la Investigación (3 OB), Medicina Legal (4.5 OB), Medicina Preventiva y Salud Pública (6 OB), Pediatría I (4.5 OB), Geriatría y Gerontología (3 OB), Farmacología Clínica (4.5 OB), Anestesia y Reanimación (4.5 OB), Gestión Sanitaria (3 OB), Pediatría II (4.5 OB), Oftalmología (6 OB), Medicina Familiar y Comunitaria (3 OB), Diagnóstico por la Imagen II (6 OB), Bioquímica y Genética Clínica (4.5 OB), + 1 OP subject (3 ECTS: Enfermedades Infecciosas Tropicales or Medicina del Deporte).

**Year 6 — Clinical Rotations and TFG**
54 ECTS of Prácticas Externas (hospital rotations): Urgencias (9), Obstetricia y Ginecología (6), Atención Primaria (6), Clínica Médica (12), Clínica Quirúrgica (12), Pediatría (6), Salud Mental (3). Plus Trabajo Fin de Grado (6 ECTS).

---

## Teaching Methodology

UCAM promotes what it describes as "transversal clinical teaching" — all clinical subjects from Y3 include both a theoretical component and 4 hours of simulation/practical skills per subject per week. This is intended to bridge basic science learning and clinical application before formal hospital rotations begin in Y6.

Simulation infrastructure: Sala de Anatomía (cadaveric dissection), Mesa Anatómica Digital (3D anatomical workstation), Simulador Clínico de Enfermería, Aula de Realidad Virtual, Sala de Microscopios. Labster virtual laboratory platform provides digital lab simulations accessible outside class hours.

The Catholic character of the institution integrates with curriculum design: ethics, deontology, and social doctrine modules are not electives but mandatory subjects distributed across Years 1–3. Students who proceed without engaging with this content cannot pass the degree.

There is no confirmed English-medium track. Teaching is entirely in Spanish.

---

## Clinical Training

Clinical training at UCAM follows a structured escalation: simulation-based clinical skills from Y3, escalating to full-time hospital rotations in Y6.

**Murcia campus — Primary clinical network:**
- Hospital La Vega (Murcia) — main clinical partner
- Public hospitals via Servicio Murciano de Salud (SMS) agreement
- Primary care centres (PENDING_CONFIRMATION — specific centres not publicly listed)

**Cartagena campus — Primary clinical network:**
- Hospital Santa Lucía (Cartagena, SMS) — main clinical partner
- Hospital Santa María del Rosell (Cartagena, SMS)
- Hospital Virgen de la Caridad (Cartagena, SMS)
- Hospital Rafael Méndez (Lorca, SMS)

Both networks are anchored in the Servicio Murciano de Salud, the regional public health system. UCAM signed a formal multi-year agreement with SMS to formalise access. An additional agreement with Hospital La Vega was signed separately.

UCAM has also announced clinical agreements with institutions in Chile for international practical training — details PENDING_CONFIRMATION regarding scope and access for standard students.

Year 6 rotations cover the full clinical spectrum: Emergency Medicine (9 ECTS), Obstetrics and Gynaecology (6 ECTS), Primary Care (6 ECTS), Internal Medicine (12 ECTS), Surgery (12 ECTS), Paediatrics (6 ECTS), Mental Health (3 ECTS). Total: 54 ECTS.

**ANNUAL_UPDATE_REQUIRED** — Hospital agreements and rotation assignments may change between cohorts.

---

## International Recognition and Opportunities

UCAM holds ANECA verification for the Grado en Medicina, which is the baseline regulatory requirement for practice in Spain and EU mutual recognition.

WFME accreditation status: PENDING_CONFIRMATION. Students targeting non-EU medical licensing (UK, USA, Canada, Australia) should verify WFME status directly with UCAM before enrolling.

Regarding international mobility (Erasmus+): UCAM participates broadly in Erasmus+ at the institutional level, but confirmation that Medicine students specifically have access to outgoing Erasmus placements is PENDING_CONFIRMATION.

International clinical training agreements have been announced with institutions in Chile, but the precise scope — whether available to standard Y6 students or reserved for specific cohorts — is PENDING_CONFIRMATION.

---

## Admission Model

UCAM uses the standard Spanish EBAU (PAU) formula — the same external university access exam used for public university admissions. There is no internal university entrance exam, no interview, and no English language requirement.

**Formula:**
Nota de Admisión = 0.6 × NMB + 0.4 × CFG + a × M1 + b × M2

Where:
- **NMB** = nota media de bachillerato (GPA from 2º Bachillerato, scale 0–10)
- **CFG** = calificación de la fase obligatoria (EBAU compulsory phase score, scale 0–10)
- **M1, M2** = up to two subjects from the fase voluntaria with ponderación applied
- **a, b** = ponderación coefficient = 0.2 for each of the approved subjects

**Subjects eligible for ponderación (all coefficient 0.2):**
- Biología
- Física
- Matemáticas II
- Química

The theoretical maximum nota de admisión is 14.0 (= 0.6×10 + 0.4×10 + 0.2×10 + 0.2×10).

**Minimum threshold:** Nota de admisión ≥ 11.00.

**EBAU validity rules for 2026-27 intake:**
- Current year (2025-2026): ORDINARIA phase only — EXTRAORDINARIA not accepted.
- Prior years (2024-2025 and 2023-2024): ORDINARIA and EXTRAORDINARIA both accepted.
- Older convocatorias: phase obligatoria has indefinite validity; phase voluntaria valid for three academic years.

**Traslado de expediente track:** Open to students currently enrolled in Medicine at another Spanish or foreign university. Requirements: bachillerato grade ≥ 8.0, minimum 30 ECTS transferable to the UCAM plan. Mandatory personal interview required before admission decision.

---

## Admission Process

1. **Verify eligibility.** Obtain EBAU results. Calculate nota de admisión using the formula above. Minimum 11.00 required.
2. **Request the official EBAU document** electronically signed. If not available electronically, send a notarised photocopy by post to Secretaría Central before the deadline.
3. **Submit application.** Complete and submit the admission form. Applications for the cupo general close **3 July 2026** (ANNUAL_UPDATE_REQUIRED). Traslado applications close **2 July 2026** (ANNUAL_UPDATE_REQUIRED).
4. **For traslado applicants:** Email nmatiacci@ucam.edu before 3 July to schedule a personal interview.
5. **Receive results.** First admission list published **8 July 2026** (ANNUAL_UPDATE_REQUIRED). Traslado list: **13 July 2026** (ANNUAL_UPDATE_REQUIRED).
6. **Confirm place and pay reservation fee.** Specific amount PENDING_CONFIRMATION. ANNUAL_UPDATE_REQUIRED.
7. **Enrolment.** Formal enrolment in September before the academic year begins.

**Campus preference:** Applicants indicate a campus preference (Murcia or Cartagena) at the point of application. The unified ranking list allocates places by score and preference.

---

## Admission Timeline

| Milestone | Date (2026-27 indicative) |
|---|---|
| Application deadline (cupo general) | 3 July 2026 — ANNUAL_UPDATE_REQUIRED |
| Application deadline (traslado) | 2 July 2026 — ANNUAL_UPDATE_REQUIRED |
| First results list (cupo general) | 8 July 2026 — ANNUAL_UPDATE_REQUIRED |
| Results list (traslado) | 13 July 2026 — ANNUAL_UPDATE_REQUIRED |
| Academic year begins | September 2026 — ANNUAL_UPDATE_REQUIRED |

**Key strategic observation:** UCAM admission happens entirely in July, after EBAU results are published in June. This means students know their exact nota de admisión before applying — there is no speculative application phase. Students who do not make the UCAM cutoff in July can still pursue alternative paths before the September public university clearing rounds.

---

## Admission Score Distribution

UCAM's scoring model is entirely transparent and calculable before applying. Unlike universities with internal exams or holistic reviews, UCAM's admission decision reduces to one number: the nota de admisión.

**Score architecture:**
- 60% of the score derives from the bachillerato GPA — a value accumulated over two years and not improvable at application time.
- 40% comes from the EBAU compulsory phase — improvable only by retaking the exam.
- Up to 4 additional points come from the fase voluntaria ponderación (2 subjects × 0.2 × max 10 = 2 points each).

**Strategic implication:** For students near the 11.00 floor, maximising ponderación subjects (Biology, Chemistry, Physics, Mathematics II) in the fase voluntaria can be decisive. A student with NMB=8.5 and CFG=7.5 achieves only 8.5×0.6 + 7.5×0.4 = 5.1 + 3.0 = 8.1 — below 11.0 even with maximum ponderación. The formula requires a strong combined base.

**Campus-specific cutoff pattern (historical — informal data only):**
- Murcia campus: historically higher demand; last admitted scores reported approximately 12.5–13.0 range in recent intakes.
- Cartagena campus: lower demand; last admitted scores reported approximately 11.8–12.5 range.
- **ANNUAL_UPDATE_REQUIRED** — These figures are not officially published by UCAM and should be treated as approximate.

For international students whose secondary education is equivalent to Spanish bachillerato and who have taken the PCE (Pruebas de Competencias Específicas) through UNED: UCAM's admission policy for this profile is PENDING_CONFIRMATION.

---

## Costs and Payment Structure

| Cost Item | Amount | Notes |
|---|---|---|
| Annual teaching fee (EU students) | 14,200 EUR | ANNUAL_UPDATE_REQUIRED |
| Annual teaching fee (non-EU students) | 18,900 EUR | ANNUAL_UPDATE_REQUIRED |
| Price per ECTS | 236.67 EUR | ANNUAL_UPDATE_REQUIRED |
| Pre-admission reservation fee | NULL | ANNUAL_UPDATE_REQUIRED |
| Enrolment/administrative fee | NULL | ANNUAL_UPDATE_REQUIRED |
| Total degree cost (EU, 6 years) | ~85,200 EUR (estimated) | ANNUAL_UPDATE_REQUIRED — assumes flat annual fee |
| Total degree cost (non-EU, 6 years) | ~113,400 EUR (estimated) | ANNUAL_UPDATE_REQUIRED — assumes flat annual fee |

**VAT:** Services classified as educational are exempt from IVA under Spanish tax law.

**Price positioning:** At 14,200 EUR/year, UCAM is among the lower-cost private Medicine degrees in Spain. For reference, comparable programs at other private universities range from approximately 14,000 to 22,000 EUR/year. The non-EU surcharge (18,900 EUR/year) is significant and should be factored in by all non-EU applicants.

**Payment structure details** (fractionation options, direct debit terms): PENDING_CONFIRMATION — contact Secretaría Central directly.

---

## Scholarships and Financial Aid

UCAM offers a general scholarship programme across all its degrees, but specific eligibility, amounts, and deadlines applicable to Medicine students are PENDING_CONFIRMATION.

Spanish national scholarships (MEC/Ministerio de Educación) may be partially applicable depending on income thresholds, but private university fees often exceed covered amounts. Students are advised to verify directly.

No degree-specific merit scholarship for Medicine has been identified in public UCAM communications. ANNUAL_UPDATE_REQUIRED.

---

## Accommodation and Cost of Living

**Murcia:** Mid-sized regional capital with relatively moderate living costs by Spanish standards. Estimated monthly costs for a student (room, food, transport, personal) range approximately 700–1,100 EUR, depending on accommodation type. UCAM does not operate its own residences but maintains an accommodation portal for students. Student residences and shared flats are available in the Los Jerónimos–Guadalupe area near campus.

**Cartagena:** Smaller coastal city, generally lower accommodation costs than Murcia. Estimated monthly costs approximately 600–900 EUR. Clinical hospitals are centrally located in Cartagena, reducing transport costs for clinical years.

Both cities are connected by train and bus (journey approximately 50 minutes). The Cartagena campus is a realistic option for students based in the Murcia region who prefer a lower-cost city environment.

---

## International Exchange and Mobility Programs

UCAM participates in the Erasmus+ programme at the institutional level. However, whether Medicine students have access to outgoing Erasmus clinical or academic placements at partner institutions is PENDING_CONFIRMATION. Students should request a list of Medicine-specific Erasmus partners from the UCAM Internationalisation Office before enrolling.

International clinical agreements with institutions in Chile have been announced. The operational details for standard degree students (as distinct from postgraduate or special programs) are PENDING_CONFIRMATION.

No confirmed information is available regarding bilateral exchange agreements with non-EU universities or specific Medicine-track international mobility programmes.

---

## MIR Preparation and Professional Outcomes

UCAM's most prominently stated outcome metric is its **98% MIR pass rate** — meaning 98% of UCAM Medicine graduates who sit the MIR (the national medical residency selection exam) pass. This figure compares favourably with the national average and is frequently cited in UCAM marketing.

**Important caveats:**
- The 98% figure refers to the pass rate (obtaining a score sufficient to qualify for a residency place) — it does not necessarily indicate average ranking position or speciality competitiveness.
- The figure is sourced from UCAM's own communications. Independent third-party verification is PENDING_CONFIRMATION.

UCAM explicitly promotes MIR preparation from Y1 as a differentiating feature, with clinical subject structure designed to reinforce long-term retention of MIR-relevant content. The 4 hours of simulation per clinical subject per week is positioned as directly reinforcing exam preparedness.

Graduates receive the título oficial de Grado en Medicina, which provides automatic licence to practise as a physician in Spain and is eligible for EU mutual recognition (after MIR residency completion).

---

## Strategic Fit

### Good Fit For

- Students who have already completed EBAU with a nota de admisión of 11.0 or above and want admission without additional exam preparation or interviews
- Students from the Región de Murcia or nearby regions who prefer proximity to home and family networks
- Students who are comfortable with or supportive of a Catholic institutional environment and mandatory theology/ethics curriculum
- Students seeking lower annual fees relative to other private Medicine options in Spain (14,200 EUR vs. sector average of ~16,000–20,000 EUR)
- Students who underperformed relative to their public university preferences and need a confirmed alternative quickly after EBAU results
- Students who want a fully Spanish-taught program with no bilingual requirements

### Less Suitable For

- Students who are not comfortable with mandatory religious curriculum (Teología I and II, Doctrina Social de la Iglesia are non-negotiable)
- Students targeting highly competitive international postgraduate licensing (WFME status unconfirmed)
- Students who have strong London, Dublin, or North American postgraduate ambitions and need WFME-confirmed accreditation from day one
- Students who cannot achieve a nota de admisión of 11.00 — there is no alternative admissions pathway
- Students requiring English-medium instruction or a bilingual track
- International students outside the EU facing 18,900 EUR/year fees without clear financial planning

---

## Risks and Considerations

**Mandatory religious curriculum.** Teología I (Y1), Teología II (Y2), Doctrina Social de la Iglesia (Y2), Deontología Médica (Y3), and Ética Médica y Bioética I (Y3) are obligatory for all students. This is not a peripheral feature — these subjects are embedded in the degree structure. Students should assess compatibility before committing.

**WFME accreditation uncertainty.** WFME accreditation is PENDING_CONFIRMATION. This matters for students targeting postgraduate training or licensure in the UK, USA, Canada, Australia, or other jurisdictions that require WFME-recognised degrees. This risk is not unique to UCAM — it applies to several Spanish private medicine programs — but it warrants explicit confirmation before enrolment.

**Unofficial cutoff data.** UCAM does not officially publish last-admitted scores by campus. The figures cited in this document (~11.8–12.5 for Cartagena; ~12.5–13.0 for Murcia) are derived from student forum reports (casiMedicos) and should be treated as approximate. A student with a nota de admisión of exactly 11.00 cannot reliably predict admission.

**Cartagena campus clinical network.** While clinically sound, Cartagena's hospital network is smaller and less specialised than the Hospital Universitario Virgen de la Arrixaca (the major tertiary referral centre in Murcia, which is not in the current UCAM agreement). Students aiming for highly specialised MIR specialities should assess whether the rotation scope is adequate.

**Campus seat allocation is opaque.** The per-campus seat breakdown is not publicly published. Students may indicate a campus preference but cannot guarantee it. This creates uncertainty for those with a strong geographic preference.

**International student pathway unclear.** UCAM has not published a clear, publicly accessible admissions pathway for students with non-Spanish secondary qualifications (PCE/UNED route). This is a significant gap for the international student profile targeted by WinnersEducation.ai.

---

## Important Notes

- The admission formula uses NMB (bachillerato average, 0–10 scale) + EBAU scores, NOT the nota de acceso used for public universities. Confirm calculation method with UCAM.
- Only the ORDINARIA phase of the 2025-2026 EBAU is accepted for the 2026-27 intake. EXTRAORDINARIA results from the current year are explicitly excluded.
- The application deadline is in early July — earlier than most other private universities whose processes typically run through September. Missing this window forecloses UCAM for that intake year.
- For traslado de expediente applicants: contact nmatiacci@ucam.edu before 3 July to book the mandatory interview. Late contact may result in exclusion.
- The 90-seat total is divided between Murcia and Cartagena via a single unified list. Students who do not meet their campus preference score threshold may not be offered their preferred campus.
- ANNUAL_UPDATE_REQUIRED applies to all fee figures, deadlines, and score thresholds.

---

## Key Insight

UCAM is the most exam-predictable admission in the Spanish private medicine market. Because the formula is identical to the public university EBAU model — with no internal exam, no interview, and no English requirement — students who have already completed their EBAU know their exact score before applying. This eliminates preparation uncertainty and makes UCAM a reliable contingency plan for students who narrowly missed public university cutoffs.

The institutional Catholic identity is the principal filtering variable. For students whose values align with or are neutral toward a religious academic environment, UCAM offers good value: 14,200 EUR/year, a well-established clinical network via the Servicio Murciano de Salud, a 98% MIR pass rate, and two campuses with different historical entry-score profiles. The Cartagena campus specifically functions as a more accessible entry point within the same program.

The unresolved WFME status is the primary strategic risk for internationally mobile students.

---

## Final Takeaway

UCAM is a well-established, cost-efficient private Medicine degree whose principal differentiator is the simplicity of its admission model: EBAU score only, no extras. For students who have already maximised their EBAU performance and are looking for a confirmed seat in Medicine — particularly students based in or near Murcia — UCAM represents a credible and financially accessible option.

The 98% MIR pass rate and strong Servicio Murciano de Salud clinical network are genuine strengths. The mandatory Catholic curriculum is a genuine filter that is often underestimated by students who treat UCAM purely as a fallback.

The two-campus structure gives students meaningful optionality: Murcia for proximity to the main university campus and facilities, Cartagena for potentially lower entry scores and a more contained urban environment. For the 2026-27 intake, the operative question is whether the student's nota de admisión clears the historical threshold at their preferred campus — and whether they have submitted documentation before the hard 3 July deadline.

---

## Frequently Asked Questions

**Does UCAM have an internal entrance exam for Medicine?**
No. UCAM uses the standard Spanish EBAU (PAU) formula exclusively. No internal written exam, no oral exam, no English test, and no interview (except for traslado de expediente applicants).

**What is the minimum score to apply?**
Nota de admisión ≥ 11.00. This is the official threshold below which applications are not accepted. The actual scores of admitted students are historically higher — approximately 11.8–13.0 depending on campus and year.

**Do I need to sit Biology or Chemistry in the EBAU voluntaria phase?**
Not mandatory, but strategically important. Biology, Chemistry, Physics, and Matemáticas II are the ponderación subjects for UCAM Medicine (coefficient 0.2 each). Taking two of these in the voluntaria phase and scoring well can add up to 4 points to the nota de admisión — potentially the difference between admission and rejection.

**Is Medicine taught in English at UCAM?**
No. All teaching is in Spanish. There is no bilingual track.

**Can international students (PCE route) apply to UCAM Medicine?**
UCAM's admissions policy for students accessing via the UNED PCE (Pruebas de Competencias Específicas) is PENDING_CONFIRMATION. Students on this route should contact UCAM admissions directly before assuming equivalence.

**What does the mandatory religious content involve?**
Teología I (Y1), Teología II (Y2), Doctrina Social de la Iglesia (Y2), Deontología Médica (Y3), and Ética Médica y Bioética I (Y3) are all compulsory. These are degree subjects with grades that count toward the academic record. There is no opt-out. Students of all faiths and no faith enrol at UCAM, but the content is designed from a Catholic perspective.

**How competitive is each campus?**
Both share the same unified admission list. Murcia campus historically attracts more applicants, resulting in higher last-admitted scores (~12.5–13.0 range, informal). Cartagena historically admits slightly lower scores (~11.8–12.5 range, informal). These figures are not officially published and should be treated as approximate.

**What is UCAM's MIR pass rate?**
98%, according to UCAM's own communications. This refers to the percentage of graduates who pass the MIR exam (qualify for a residency place). It does not reflect average ranking position within the MIR or competitiveness for high-demand specialities.

**Is WFME accreditation confirmed?**
PENDING_CONFIRMATION. Students targeting non-EU postgraduate licensing or training should verify this directly with UCAM before enrolling.

**Can I choose between Murcia and Cartagena?**
Yes — applicants indicate a preference at application. However, allocation depends on nota de admisión score and the available places at each campus. A campus preference is not guaranteed. If a student's score is above the Murcia threshold, they get Murcia; if only above the Cartagena threshold, they are offered Cartagena (subject to availability). The exact per-campus seat split is not publicly disclosed.

**What are the application and results dates for 2026-27?**
Applications close 3 July 2026 (cupo general). First results list published 8 July 2026. All dates are ANNUAL_UPDATE_REQUIRED.
