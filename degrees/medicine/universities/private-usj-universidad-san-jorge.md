---
id: usj-medicine

type: university
subtype: private

name: "Grado en Medicina — Universidad San Jorge (USJ)"
short_name: USJ

institution_type: universidad_privada
parent_university: "Grupo San Valero (Agustinos)"
ruct_code: "50012013"
year_founded_medicine: 2025
inaugural_cohort: false

degree: Medicine

last_update: "2026-05-27"

valid_for_intake: "2026-2027"

location:
  city: "Villanueva de Gállego"
  region: "Zaragoza, Aragón"
  country: Spain

strategic_tags:
  - safety_option
  - no_exam
  - academic_record_heavy
  - english_requirement
  - low_competitiveness
  - religious_institution
  - strong_simulation
  - mixed_clinical_network

admission:
  intake_month: September

  applications_open_date: ANNUAL_UPDATE_REQUIRED

  rolling_admissions:
    enabled: true
    estimated_end_date: "2026-09-30"

  admission_rounds:
    enabled: false
    count: NULL

    rounds: []

  exam_required: false
  interview_required: false

academic_record:
  minimum_requirement:
    enabled: false
    grade_source: NULL
    minimum_grade: NULL

  competitive_filter:
    enabled: true
    grade_source: first_year_baccalaureate
    approx_candidates_selected: NULL

curriculum:
  international_curriculums_accepted: PENDING_CONFIRMATION

competitiveness:
  level: low

admissions_statistics:
  annual_applications: NULL
  seats: 100
  applicants_per_seat: NULL

  last_admitted_scores:
    - intake_year: 2025
      round: NULL
      score: 5.000
      score_type: bachillerato_grade
      notes: "Nota de corte 2025 via PAU/CFGS access. Lowest practical threshold — program is very accessible."

international_profile:
  international_students_percentage: NULL
  international_nationalities:
    - country: NULL
      percentage: NULL

programs:
  - id: usj-medicine-presencial

    campus: "Villanueva de Gállego, Zaragoza (Facultad de Ciencias de la Salud)"

    modality: standard

    strategic_tags:
      - safety_option
      - no_exam
      - academic_record_heavy
      - english_requirement
      - strong_simulation
      - low_competitiveness

    teaching_languages:
      - Spanish
      - English

    regional_language_possible: false
    regional_language: NULL

    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: true
      minimum_english_level: PENDING_CONFIRMATION
      notes: "All applicants must accredit an English language level obtained within the last two years. Level not confirmed publicly; likely B2. This requirement applies to all nationalities, not only non-native Spanish speakers."

    seats: 100

    program_statistics:
      annual_applications: NULL
      seats: 100
      applicants_per_seat: NULL

      last_admitted_scores:
        - intake_year: 2025
          round: NULL
          score: 5.000
          score_type: bachillerato_grade
          notes: "Inaugural intake 2025-26. Cut-off from educaweb for PAU/CFGS pathway."

    program_specific_admission:
      enabled: false

    evaluation_model:
      overall_model_type: academic_record_only

      components:
        - component: academic_record
          enabled: true
          role: primary
          weight: 1.00
          grade_source: first_year_baccalaureate
          minimum_required_grade: NULL
          notes: "Admission is based exclusively on the 1º Bachillerato grade average. EBAU/EvAU score is NOT used in the admissions formula. Tiebreaker 1: Biology grade. Tiebreaker 2: English grade. Grade average calculated excluding Religion (if present)."

        - component: academic_exam
          enabled: false
          role: NULL
          weight: NULL
          exam_variant: NULL
          exam_format: NULL
          delivery_mode: NULL
          notes: "No internal admissions exam. USJ is one of the few Spanish private Medicine programs that does not require a university-specific written exam."

        - component: interview
          enabled: false
          role: NULL
          weight: NULL
          interview_format: NULL
          delivery_mode: NULL
          notes: NULL

        - component: english_test
          enabled: false
          role: filter
          weight: NULL
          test_format: external_certification
          delivery_mode: NULL
          online_conditions: NULL
          minimum_level: PENDING_CONFIRMATION
          bonus_max: NULL
          bonus_scale:
            B2: NULL
            C1: NULL
            C2: NULL
          notes: "English level certification is a mandatory admission requirement (not a bonus). Candidates must provide a certificate obtained within the last 2 years. Specific level required is PENDING_CONFIRMATION; B2 is likely standard."

        - component: isat
          enabled: false
          role: NULL
          weight: NULL
          notes: NULL

        - component: psychometric_test
          enabled: false
          role: NULL
          weight: NULL
          notes: NULL

curriculum:
  total_ects: 360
  duration_years: 6
  formacion_basica_ects: 90
  obligatorias_ects: 198
  optativas_ects: 12
  practicas_externas_ects: 54
  tfg_ects: 6
  language: "Spanish (primary); English (Medical English Y1, selected electives)"
  modality: presencial

  year_1:
    total_ects: 60
    subjects:
      - name: "Anatomía I (Anatomía General y Embriología)"
        ects: 6
        type: formacion_basica
        semester: 1C
      - name: "Biología Celular"
        ects: 6
        type: formacion_basica
        semester: 1C
      - name: "Bioquímica Humana"
        ects: 6
        type: formacion_basica
        semester: 1C
      - name: "Fisiología I (Biofísica)"
        ects: 6
        type: formacion_basica
        semester: 1C
      - name: "Historia de la Medicina y Gestión Sanitaria"
        ects: 3
        type: formacion_basica
        semester: 1C
      - name: "Medical English"
        ects: 3
        type: obligatoria
        language: English
        semester: 1C
      - name: "Anatomía II (Anatomía del Aparato Locomotor)"
        ects: 6
        type: formacion_basica
        semester: 2C
      - name: "Fisiología II (Fisiología Renal, de la Sangre e Inmunología)"
        ects: 6
        type: formacion_basica
        semester: 2C
      - name: "Histología I (Histología General)"
        ects: 6
        type: formacion_basica
        semester: 2C
      - name: "Investigación, Documentación y Nuevas Tecnologías de la Información Biomédica"
        ects: 3
        type: formacion_basica
        semester: 2C
      - name: "Pensamiento Social Cristiano"
        ects: 3
        type: obligatoria
        semester: 2C
      - name: "Psicología Médica"
        ects: 6
        type: formacion_basica
        semester: 2C

  year_2:
    total_ects: 60
    subjects:
      - name: "Anatomía III (Esplacnología)"
        ects: 6
        type: formacion_basica
        semester: 1C
      - name: "Fisiología III (Fisiología Cardiocirculatoria, Respiratoria y Digestiva)"
        ects: 6
        type: formacion_basica
        semester: 1C
      - name: "Histología II (Histología Orgánica)"
        ects: 6
        type: formacion_basica
        semester: 1C
      - name: "Microbiología y Parasitología"
        ects: 6
        type: formacion_basica
        semester: 1C
      - name: "Procedimientos Diagnósticos y Terapéuticos Físicos I (Bases Físicas de las Radiaciones y Diagnóstico por Imagen)"
        ects: 6
        type: obligatoria
        semester: 1C
      - name: "Anatomía IV (Neuroanatomía)"
        ects: 6
        type: formacion_basica
        semester: 2C
      - name: "Fisiología IV (Fisiología del Sistema Nervioso, Sistema Tegumentario y Sistema Endocrino. Nutrición)"
        ects: 6
        type: formacion_basica
        semester: 2C
      - name: "Comunicación Asistencial y Ética Médica"
        ects: 6
        type: obligatoria
        semester: 2C
      - name: "Fisiopatología y Semiología"
        ects: 9
        type: obligatoria
        semester: 2C
      - name: "Medicina Física y Rehabilitación"
        ects: 3
        type: obligatoria
        semester: 2C

  year_3:
    total_ects: 60
    subjects:
      - name: "Bioestadística"
        ects: 6
        type: obligatoria
        semester: 1C
      - name: "Anatomía Patológica"
        ects: 6
        type: obligatoria
        semester: 1C
      - name: "Bases de la Cirugía, Anestesia y Reanimación"
        ects: 6
        type: obligatoria
        semester: 1C
      - name: "Farmacología I (Farmacología Básica)"
        ects: 6
        type: obligatoria
        semester: 1C
      - name: "Procedimientos Diagnósticos y Terapéuticos Físicos II (Medicina Nuclear. Radioterapia)"
        ects: 6
        type: obligatoria
        semester: 1C
      - name: "Especialidades Médicas (Hematología. Oncología. Inmunopatología)"
        ects: 12
        type: obligatoria
        semester: 2C
      - name: "Especialidades Quirúrgicas (Otorrinolaringología, Oftalmología, Dermatología)"
        ects: 12
        type: obligatoria
        semester: 2C
      - name: "Farmacología II (Farmacología Clínica)"
        ects: 6
        type: obligatoria
        semester: 2C

  year_4:
    total_ects: 60
    subjects:
      - name: "Medicina de Familia, Paliativa y Urgencias"
        ects: 12
        type: obligatoria
        semester: 1C
      - name: "Patología Médico-Quirúrgica I (Cardiovascular. Endocrinología y Nutrición)"
        ects: 12
        type: obligatoria
        semester: 1C
      - name: "Psiquiatría"
        ects: 6
        type: obligatoria
        semester: 1C
      - name: "Prácticas Tuteladas Rotatorio I"
        ects: 9
        type: practicas_externas
        semester: A
      - name: "Patología Médico-Quirúrgica II (Neumología. Neurología)"
        ects: 12
        type: obligatoria
        semester: 2C
      - name: "Patología Médico-Quirúrgica III (Gastroenterología y Hepatología)"
        ects: 9
        type: obligatoria
        semester: 2C

  year_5:
    total_ects: 60
    subjects:
      - name: "Geriatría y Patología Infecciosa"
        ects: 9
        type: obligatoria
        semester: 1C
      - name: "Obstetricia y Ginecología"
        ects: 9
        type: obligatoria
        semester: 1C
      - name: "Patología Médico-Quirúrgica IV (Traumatología, Reumatología y Nefrourología)"
        ects: 12
        type: obligatoria
        semester: 1C
      - name: "Medicina Preventiva, Salud Pública, Epidemiología"
        ects: 9
        type: obligatoria
        semester: 2C
      - name: "Pediatría"
        ects: 9
        type: obligatoria
        semester: 2C
      - name: "Prácticas Tuteladas Rotatorio II"
        ects: 6
        type: practicas_externas
        semester: 2C
      - name: "Optativa Y5 — elección 1 [OPT]"
        ects: 3
        type: optativa
        semester: 2C
        notes: "Choose 1 of 6 options: Adicciones, Comunicación y Divulgación Científica, Cuidados Paliativos, Gestión Sanitaria, Microbiología Avanzada, Neurobiología."
      - name: "Optativa Y5 — elección 2 [OPT]"
        ects: 3
        type: optativa
        semester: 2C
        notes: "Choose a second elective from the same pool as above."

  year_6:
    total_ects: 60
    subjects:
      - name: "Toxicología, Medicina Legal y Forense"
        ects: 9
        type: obligatoria
        semester: 1C
      - name: "Prácticas Tuteladas Rotatorio III"
        ects: 39
        type: practicas_externas
        semester: A
      - name: "Trabajo Fin de Grado"
        ects: 6
        type: tfg
        semester: A
      - name: "Optativa Y6 — elección 1 [OPT]"
        ects: 3
        type: optativa
        semester: 1C
        notes: "Choose 1 of 6 options: Anestesiología y Reanimación, Atención al Paciente Crítico, Genética Médica e Inmunología, Investigación Científica en Medicina, Medicina Laboral, Nutrición y Dietética."
      - name: "Optativa Y6 — elección 2 [OPT]"
        ects: 3
        type: optativa
        semester: 1C
        notes: "Choose a second elective from the same pool as above."

clinical_training:
  primary_hospital: "Hospital Quirónsalud Zaragoza"
  hospital_network: "Grupo Quirónsalud + Servicio Aragonés de Salud (SALUD)"
  additional_hospitals:
    - "Hospital de Calatayud (SALUD — public)"
  primary_care_centers:
    - "Centro de Salud Parque Roma (Zaragoza)"
    - "Centro de Salud Puerta del Carmen (Zaragoza)"
    - "Centro de Salud Barrio de Jesús (Zaragoza)"
  clinical_start_year: 4
  simulation_center: true
  simulation_center_name: "Espacio de Competencias Clínicas Avanzadas"
  simulation_features:
    - "Boxes de urgencias"
    - "UCI"
    - "Quirófano"
    - "Sala de consulta"
    - "Sala de disección"
    - "Laboratorios"
    - "Mesa Anatómica Digital (Anatomage)"

accreditation:
  aneca_verified: true
  wfme_accredited: PENDING_CONFIRMATION

pricing:
  preadmission_fee: 195
  preadmission_fee_refundable: false
  reservation_fee: 3500
  reservation_fee_notes: "Reserva de plaza fee; likely credited toward first-year tuition. Confirm with USJ admissions."
  annual_teaching_fees_y1: 18000
  price_per_ects: 300
  total_first_year: ANNUAL_UPDATE_REQUIRED
  notes: "Annual fee 18,000 EUR (300 EUR/ECTS × 60 ECTS). Second and subsequent enrolments of a failed subject carry a 20% surcharge. Total first-year cost including fees ANNUAL_UPDATE_REQUIRED."

contact:
  admissions_phone: "+34 976 077 584"
  website: "https://www.usj.es/estudios/grados/medicina"
  preadmission_url: "https://www.usj.es/estudios/grados/medicina"

dean: "Antonio Francisco Laclériga Giménez (Director de la Titulación)"

hospital_simulado: true
---

# Universidad San Jorge (USJ) — Grado en Medicina

## Overview

Universidad San Jorge (USJ) is a private Catholic university in Villanueva de Gállego, Zaragoza, belonging to Grupo San Valero (Augustinian order). It launched its Medicine degree with the first cohort in September 2025, making the 2026-27 intake its second year of operation.

The program offers 100 seats annually, a 6-year (360 ECTS) presencial curriculum, and a fundamentally different admissions model to most Spanish private Medicine programs: selection is based exclusively on the 1º Bachillerato grade average, with no internal written exam and no interview. An English language certification (obtained within the last two years) is also required as a mandatory filter for all applicants.

The campus is located in Villanueva de Gállego, a small municipality approximately 15 km north of Zaragoza city center. Clinical training begins in Year 4 and rotates through Hospital Quirónsalud Zaragoza (major private), Hospital de Calatayud (public Aragonese Health Service), and three Zaragoza primary care centers. The campus hosts the Espacio de Competencias Clínicas Avanzadas, a full simulation center with emergency bays, ICU, operating theatre, and Anatomage digital dissection tables.

The program recorded a 2025 cut-off of 5.000 out of 10 — the lowest practical threshold in Spanish private Medicine. Combined with the absence of an internal exam, USJ Medicina is strategically positioned as one of the most accessible private Medicine programs in Spain.

## Quick Evaluation

- **Admission model:** 1º Bachillerato grade only. No internal exam. English certification required. Tiebreaker: Biology grade, then English grade.
- **Seats:** 100 annually.
- **Competitiveness:** Low. Cut-off 5.000 in 2025; no competitive exam gate.
- **Cost:** 18,000 EUR/year (300 EUR/ECTS). Preadmission fee 195 EUR; reservation fee 3,500 EUR.
- **Clinical integration:** From Year 4 (rotations). Full simulation centre from Year 1.
- **MIR outcomes:** Insufficient data — first cohort graduates 2031.
- **Key strength:** Lowest effective entry bar among private Medicine programs; no exam; 100 seats; strong simulation infrastructure; mixed private+public clinical network.
- **Key risk:** Very new program (2025); no MIR track record; campus is a small town 15km from Zaragoza; WFME status unconfirmed; small Aragonese clinical ecosystem; "Pensamiento Social Cristiano" mandatory subject reflects Agustinian identity.

## Key Facts

| Field | Value |
|---|---|
| Full name | Universidad San Jorge — Grado en Medicina |
| Parent institution | Grupo San Valero (Augustinian order) |
| Location | Villanueva de Gállego, Zaragoza, Aragón |
| First cohort | September 2025 |
| Degree duration | 6 years |
| Total ECTS | 360 |
| Teaching language | Spanish (primary) + English (Medical English Y1, electives) |
| Modality | Presencial |
| Annual seats | 100 |
| Admissions exam | No |
| Interview | No |
| Grade basis | 1º Bachillerato average (EBAU not used) |
| English required | Yes (certification within last 2 years) |
| Cut-off 2025 | 5.000 (bachillerato grade, PAU/CFGS pathway) |
| Clinical start year | Year 4 |
| Simulation centre | Yes (Espacio de Competencias Clínicas Avanzadas + Anatomage) |
| ANECA verified | Yes |
| WFME accredited | PENDING_CONFIRMATION |
| Price per ECTS | 300 EUR |
| Annual fee (Y1) | 18,000 EUR |
| Preadmission fee | 195 EUR |
| Reservation fee | 3,500 EUR |

## Program Options

USJ offers a single Medicine degree track: a 6-year, 360 ECTS presencial program in Spanish, with Medical English (3 ECTS, Y1) and English-language elective options. There is no bilingual track, no online option, and no double degree combining Medicine with another discipline.

The Facultad de Ciencias de la Salud at Villanueva de Gállego is a dedicated health sciences campus shared with Nursing, Physiotherapy, Pharmacy, Biomedicine, and other health programs — enabling interprofessional education (IPE) by default, as the curriculum explicitly incorporates interdisciplinary collaboration with nursing, physiotherapy, and psychology.

## Program Structure

The 360-ECTS curriculum distributes as follows: Formación básica 90 ECTS, Obligatorias 198 ECTS, Optativas 12 ECTS, Prácticas Asistenciales Externas (PAE) 54 ECTS, TFG 6 ECTS. Each year carries 60 ECTS.

**Years 1–2 — Foundational biomedical sciences:** Four-part anatomy sequence (General/Embryology, Locomotor, Esplacnology, Neuroanatomy), four-part physiology sequence (Biophysics, Renal/Haematology/Immunology, Cardiovascular/Respiratory/Digestive, Nervous/Endocrine/Dermatology), histology (general + organic), biochemistry, cell biology, microbiology and parasitology, medical psychology, and biomedical research/IT. Integrative clinical introduction begins at the end of Y2 with Fisiopatología y Semiología (9 ECTS) and Communication and Medical Ethics. Two radiology/nuclear medicine subjects (PDTF I and II) spanning Y2–Y3 provide structured diagnostic imaging preparation from early in the program. Medical English (3 ECTS, Y1) and Pensamiento Social Cristiano (3 ECTS, Y1) reflect USJ's Catholic identity and language emphasis.

**Year 3 — Pre-clinical transition:** Biostatistics, Anatomy Pathology, Surgery Fundamentals/Anaesthesia, Pharmacology (basic + clinical), and two large integrated blocks: Especialidades Médicas (Hematology, Oncology, Immunopathology — 12 ECTS) and Especialidades Quirúrgicas (ORL, Ophthalmology, Dermatology — 12 ECTS).

**Years 4–5 — Clinical medicine:** Major integrated clinical blocks covering all primary specialties. Y4 introduces PAE (Rotatorio I, 9 ECTS). Subject structure uses multi-specialty integrated modules: Medicina de Familia/Paliativa/Urgencias (12 ECTS), three Patología Médico-Quirúrgica blocks covering cardiovascular/endocrinology, respiratory/neurology, and gastroenterology/hepatology; Y5 covers geriatrics/infectious diseases, obstetrics/gynaecology, traumatology/rheumatology/nephrology, preventive medicine, and paediatrics. Y5 includes PAE Rotatorio II (6 ECTS) and 6 ECTS of electives (2 subjects chosen from 6 options).

**Year 6 — Hospital immersion:** Toxicología, Medicina Legal y Forense (9 ECTS), Prácticas Tuteladas Rotatorio III (39 ECTS — the largest single PAE block in the degree), TFG (6 ECTS), and 6 ECTS of electives (2 subjects from 6 options).

**Elective portfolio (12 ECTS total across Y5 and Y6):** Y5 options: Adicciones, Comunicación y Divulgación Científica, Cuidados Paliativos, Gestión Sanitaria, Microbiología Avanzada, Neurobiología. Y6 options: Anestesiología y Reanimación, Atención al Paciente Crítico, Genética Médica e Inmunología, Investigación Científica en Medicina, Medicina Laboral, Nutrición y Dietética.

## Teaching Methodology

USJ's pedagogical model combines three explicit frameworks: Problem-Based Learning (ABP/PBL), Service Learning (ApS, integrating coursework with community service projects), and Maker Education (translating abstract concepts into tangible student-built projects). This combination is unusual among Spanish private Medicine programs, which typically rely more heavily on traditional lecture formats.

ABP is positioned as the primary active methodology. Students work through clinical problem scenarios before they have the complete knowledge base to resolve them — a constructivist approach intended to accelerate diagnostic reasoning development. The Espacio de Competencias Clínicas Avanzadas (simulation centre) is integrated into the curriculum from Year 1, with simulation exercises corresponding to each academic subject rather than being a standalone activity in later years.

The interprofessional dimension is built into the campus architecture: Medicine students share facilities with Nursing, Physiotherapy, and Pharmacy students, and the curriculum includes collaborative clinical exercises reflecting real multi-disciplinary team structures.

Research methodology is embedded throughout: Investigación, Documentación y Nuevas TIC Biomédica (3 ECTS, Y1) and Bioestadística (6 ECTS, Y3) provide quantitative and information-science foundations. The Y6 elective "Investigación Científica en Medicina" (3 ECTS) offers a dedicated research track for students interested in academic medicine.

## Clinical Training

Clinical rotations are structured across three years:

**Year 4 — PAE Rotatorio I (9 ECTS):** First hospital rotations. Annual delivery (not semester-bound), allowing integration with classroom learning across the full academic year.

**Year 5 — PAE Rotatorio II (6 ECTS):** Second rotation block, semester 2.

**Year 6 — PAE Rotatorio III (39 ECTS):** Near-full-year clinical immersion — the largest single module in the degree. Annual delivery. At 39 ECTS this block represents 65% of the final year's credits and provides systematic exposure to the full range of clinical specialties.

**Clinical sites:**
- **Hospital Quirónsalud Zaragoza:** Primary hospital partner. Quirónsalud is Spain's largest private hospital network, providing access to high volume and specialist caseload.
- **Hospital de Calatayud (SALUD):** Public hospital in the Aragonese health system (50 km from Zaragoza). Public sector exposure ensures students see a different patient and resource profile to the private sector.
- **Primary Care centers (Zaragoza):** Parque Roma, Puerta del Carmen, and Barrio de Jesús — three urban primary care centers covering diverse patient populations.
- Additional clinical agreements may be incorporated as the program grows (explicitly stated in USJ's published program description).

Total PAE: 9 + 6 + 39 = 54 ECTS, meeting the Spanish minimum requirement.

The mixed private+public+primary care network is a structural advantage: students experience hospital care in both sectors and community medicine, providing a more complete clinical preparation than programs limited to a single hospital group.

## International Recognition and Opportunities

USJ holds ANECA institutional accreditation and submitted its Medicine degree verification memoria (Memoria RUCT Verificación, March 2025). The degree is formally registered in the RUCT system (code 50012013).

**WFME accreditation:** PENDING_CONFIRMATION. As a program that launched in 2025, USJ Medicine has not yet gone through the full WFME review cycle. Students planning to practice internationally in countries with WFME requirements must verify this before enrolling.

**European recognition:** An ANECA-verified Spanish Medicine degree qualifies for EU professional recognition under Directive 2005/36/EC, enabling practice across EU member states through mutual recognition procedures.

**Erasmus+ and international exchange:** USJ has an active Erasmus+ program across its faculties. Whether Medicine-specific exchange agreements are available from Year 1 of the program is PENDING_CONFIRMATION. Minimum 60 ECTS approved is required to participate in exchange programs.

## Admission Model

USJ Medicina is one of the few Spanish private Medicine programs that selects students **without a university-specific admissions exam**. The admission formula relies solely on:

1. **1º Bachillerato grade average** — the primary selection criterion. The average is calculated excluding Religion if present. EBAU/EvAU scores are not part of the formula, making USJ accessible for students whose EBAU result underperforms their continuous academic record.

2. **English language certification** — a mandatory filter requirement, not a bonus. All applicants must present a certificate obtained within the last two years. The specific minimum level is not published explicitly; candidates should confirm directly with USJ admissions before applying.

**Tiebreaker criteria** (in order): Biology grade; English grade.

**No interview, no psychometric test, no portfolio.** The selection process is purely numerical.

This model makes USJ structurally different from programs requiring Biology/Chemistry MCQ exams or personal interviews. Students with solid Bachillerato records and a valid English certification can apply without additional preparation for university-specific tests. The trade-off is that the program is equally accessible to all students above a minimal threshold, resulting in a lower initial selectivity than exam-based programs.

## Admission Process

1. **Complete the preadmission form** online at usj.es/estudios/grados/medicina. Pay the preadmission fee (195 EUR, non-refundable).

2. **Attend an information session** (presencial at Villanueva de Gállego campus or online). This is a required step in the process.

3. **Submit English certification** — obtained within the last two years. Level PENDING_CONFIRMATION.

4. **Submit academic transcript** (certificate of grades, average calculated without Religion if applicable).

5. **Receive preadmission result** — placement or waiting list.

6. **Request formal admission** and pay the reservation fee (3,500 EUR) within the required deadline to secure the place.

7. **Formalise enrollment** — complete documentation and enrollment through USJ's administrative process.

## Admission Timeline

| Event | Indicative Timing |
|---|---|
| Applications open | ANNUAL_UPDATE_REQUIRED (rolling from early in academic year) |
| Rolling admissions deadline | 30 September 2026 (ANNUAL_UPDATE_REQUIRED) |
| Reservation fee payment deadline | Within defined period after preadmission result |
| Academic year start | September 2026 |

Admissions are rolling — places are assigned as qualifying applications arrive, not in fixed rounds. Early application is strongly advisable given the 100-seat limit.

## Admission Score Distribution

The 2025 cut-off was 5.000 out of 10 (PAU/CFGS pathway), which is the practical floor for any academic average. This means all 100 places in the inaugural cohort were filled before reaching a meaningful selective threshold.

For 2026-27 (second cohort), the cut-off may rise modestly as awareness of the program grows. Nonetheless, any student with a 1º Bachillerato average above approximately 6.0–6.5 and a valid English certificate should expect to receive an offer, subject to early application.

Students without a valid English certification are ineligible regardless of academic grade. This is the only hard filter beyond the grade ranking.

## Costs and Payment Structure

| Concept | Amount | Notes |
|---|---|---|
| Preadmission fee | 195 EUR | Non-refundable, all programs |
| Reservation fee | 3,500 EUR | Secures place; likely credited toward tuition |
| Annual teaching fee (Y1) | 18,000 EUR | 300 EUR/ECTS × 60 ECTS |
| Price per ECTS | 300 EUR | Applies to all 6 years |
| Repeat subject surcharge | +20% | On 2nd+ enrolment of same subject |
| Total first year (estimated) | ANNUAL_UPDATE_REQUIRED | Confirm exact payment schedule with USJ |

The 300 EUR/ECTS rate places USJ in the mid-range of Spanish private Medicine programs (below UAX at ~375 EUR/ECTS, comparable to CULB/UCJC range). Over 6 years the total tuition would be approximately 108,000 EUR (360 ECTS × 300 EUR/ECTS).

Payment is by direct debit (domiciliación bancaria) as the mandatory method, with an exception for new international students who cannot use domiciliación at enrollment.

## Scholarships and Financial Aid

USJ offers approximately twenty scholarship and bonus modalities for enrolled students. Available types include:

- **Ministerio de Educación scholarships** (public, compatible with USJ's own)
- **Becas a la Excelencia** — performance-based
- **Becas Accede** — accessibility/need-based
- **Beca Heraldo de Aragón** — regional newspaper partnership scholarship
- **Becas para vecinos de Villanueva de Gállego y Mancomunidad del Bajo Gállego** — local residence scholarship
- **Beca para Deportistas Universitarios** — elite athlete scholarship
- **Becas del Gobierno de Aragón** — Aragonese regional government
- **Becas específicas para miembros de la Guardia Civil**
- **Becas Zaragoza Vivienda** — housing support
- **Becas Santander** — Santander Bank partnership
- **Bonificaciones** — additional institutional discounts

Specific amounts, eligibility criteria, and application processes are ANNUAL_UPDATE_REQUIRED. Students should inquire simultaneously with admissions.

## Accommodation and Cost of Living

The USJ campus is in Villanueva de Gállego, a small municipality of approximately 4,000 residents on the A-23 Huesca motorway, 15 km north of Zaragoza. There is no train connection to Zaragoza; students typically rely on private transport, university bus service (if available), or arrange accommodation near the campus or in Zaragoza with a car.

Zaragoza is one of Spain's more affordable large cities. Estimated monthly costs for a student living in Zaragoza or near campus: 700–950 EUR/month excluding tuition (accommodation, food, transport, personal expenses). Living directly in Villanueva de Gállego would likely be cheaper but with very limited social and urban amenities.

Students from outside Aragón moving to Zaragoza will find a well-connected city with good transport links (AVE to Madrid ~1h45m, to Barcelona ~1h45m), a moderate cultural offer, and a lower cost of living than Madrid, Barcelona, or Valencia.

## International Exchange and Mobility Programs

USJ participates in Erasmus+ across its faculties. Requirements: minimum 60 ECTS approved, minimum enrollment in second year of the degree. Exchange is processed through the International Mobility Coordination team, which handles credit equivalence matching before and after the stay.

Specific Medicine exchange agreements and partner universities for the Medicine degree are PENDING_CONFIRMATION given the program's recent launch (2025). Students interested in international mobility should contact USJ's international office early in their degree to confirm options for Years 3–5.

## MIR Preparation and Professional Outcomes

The degree is structured under RD 822/2021 and qualifies graduates for MIR access upon completion. No MIR outcome data is available — the first cohort will graduate approximately in 2031.

The curriculum includes specific MIR-aligned preparation elements: Bioestadística (6 ECTS, Y3) covers a high-volume MIR topic; Farmacología is taught in two dedicated blocks (basic + clinical, Y3); the integrated Patología Médico-Quirúrgica modules in Y4–Y5 mirror the thematic structure of MIR exam question clusters. The Year 6 Rotatorio III (39 ECTS) provides extended clinical exposure across all primary MIR specialties.

**Professional exit routes:** MIR access (Médico Interno Residente), direct clinical practice (general practitioner, private clinic), hospital medicine, public sector healthcare in Aragón and nationally, research and academic careers.

## Strategic Fit

### Good Fit For

- Students with a solid 1º Bachillerato average (above ~6.0) who are not competitive for exam-based private programs and want to avoid an internal written exam entirely.
- Students whose EBAU result was below their continuous academic average — USJ's model ignores EBAU completely.
- Students based in Aragón or northern Spain who prefer a lower cost-of-living environment and proximity to family.
- Students who already hold an English certification (B2 or equivalent) obtained within the last two years.
- Students who value interprofessional education and an active/project-based learning environment from Year 1.
- Students attracted by a mixed public+private clinical network (Quirónsalud + SALUD + primary care).

### Less Suitable For

- Students who need confirmed WFME accreditation before enrollment for international medical practice.
- Students expecting a high-profile urban setting with extensive networking, cultural, and extracurricular opportunities — Villanueva de Gállego is a small campus town.
- Students without an English certification who are unwilling to obtain one before applying.
- Students who need MIR outcome data before choosing a program — none exists for USJ Medicine.
- Students targeting programs with strong MIR preparation culture and track records.

## Risks and Considerations

**Very new program:** The first cohort began in 2025. There are no graduates, no MIR outcomes, and the Years 4–6 clinical program has never been delivered. All clinical agreements, simulation quality, and faculty depth are aspirational pending operational verification.

**WFME status unconfirmed:** Students planning to practice outside Spain must verify WFME recognition before enrolling. This is a structural limitation for international-profile students.

**Campus isolation:** Villanueva de Gállego is not a city. Students without private transport have limited independent mobility. The social and professional ecosystem is narrower than in Madrid, Barcelona, Valencia, or even central Zaragoza. Students must factor transport and lifestyle into their planning.

**Low initial selectivity:** The cut-off 5.000 reflects ease of access rather than a programme decision. As awareness grows, the effective threshold will rise. Students who wait until the process is nearly full risk missing places even with relatively high grades if they apply late.

**Clinical network size:** Aragón is a large territory with a relatively small population (~1.3M). The clinical caseload across the partner hospitals, while diverse in type (private + public + primary care), is lower in absolute volume than programs based in Madrid or Barcelona. Students with strong ambitions for niche specialty exposure may find the local case mix limited.

**Agustinian institutional identity:** Pensamiento Social Cristiano is a mandatory 3-ECTS Year 1 subject. This reflects USJ's Catholic Augustinian mission. Students who object to mandatory religious/social doctrine content should evaluate this carefully before applying.

## Important Notes

- All applicants must provide an English language certification obtained within the last two years. Students without a valid certificate are ineligible regardless of academic grade. Certificates should be prepared before initiating the preadmission process.
- The Bachillerato average used for ranking must be calculated excluding Religion. Confirm with USJ whether any other subjects are excluded.
- Tiebreaker criteria in order: Biology grade first, English grade second.
- Rolling admissions with a deadline of 30 September. Early application is essential given the 100-seat limit and the absence of fixed rounds.
- The preadmission fee (195 EUR) is non-refundable.
- Clinical rotations begin in Year 4, not earlier. Students seeking earlier clinical contact should consider this relative to programs with Year 3 or earlier hospital placement.
- Repeat subject enrollment incurs a 20% ECTS price surcharge.

## Key Insight

USJ Medicina's defining feature is structural accessibility: no exam, no interview, 1º Bachillerato grade only. For students who are academically capable but disadvantaged by EBAU variability, exam anxiety, or lack of time to prepare for competitive university-specific tests, USJ removes the most common barriers to private Medicine access in Spain. The 5.000 cut-off is not a strategic choice but a market reality — the program is filling its 100 places from a pool with few selective filters.

The risk-opportunity calculus is straightforward: USJ offers a formally valid Spanish Medicine pathway with strong infrastructure (simulation center, Anatomage, mixed clinical network) at a moderate price (18,000 EUR/year) for students whose academic profile would otherwise exclude them from more competitive programs. The trade-off is a new program, an isolated campus, no international accreditation track record, and a regional clinical ecosystem smaller than Spain's major urban centers.

## Final Takeaway

For students who need a private Medicine program without a competitive entrance exam, USJ Medicina is currently the clearest option in Spain. Its 1º Bachillerato-only model, 100 seats, and 5.000 cut-off make it a reliable fallback for students who cannot clear the Biology/Chemistry MCQ bar at other institutions. The program's infrastructure is credible. The unknowns — WFME status, MIR outcomes, long-term clinical network stability — are real and require acceptance. Students who apply early, hold a valid English certificate, and have a Bachillerato average above 6.5 should consider USJ a near-certain offer at the current stage of the program's development.

## Frequently Asked Questions

**Does USJ Medicine require an internal admissions exam?**
No. USJ is one of the only Spanish private Medicine programs that does not require a university-specific written exam. Selection is based on the 1º Bachillerato grade average only.

**Is EBAU required for admission?**
No. USJ uses only the 1º Bachillerato grade, not the EBAU/EvAU result. Students with a poor EBAU but a strong continuous academic record are not disadvantaged.

**Do I need an English certification to apply?**
Yes. An English language certificate obtained within the last two years is mandatory for all applicants, regardless of nationality. The specific minimum level is PENDING_CONFIRMATION — confirm with USJ admissions before applying.

**What is the cut-off score?**
5.000 out of 10 was the 2025 cut-off. This is the practical floor. The effective threshold may increase in subsequent intakes as the program gains visibility.

**Where is the campus?**
Villanueva de Gállego, approximately 15 km north of Zaragoza city center. The campus is dedicated to Health Sciences and shared with Nursing, Physiotherapy, Pharmacy, and other health programs.

**When do clinical rotations begin?**
Year 4. The first PAE block (Rotatorio I, 9 ECTS) runs throughout Year 4 (annual delivery). Year 5 has a second rotation (6 ECTS). Year 6 is dominated by Rotatorio III (39 ECTS), providing near-full-year clinical immersion.

**Which hospitals are used for clinical training?**
Hospital Quirónsalud Zaragoza (private), Hospital de Calatayud (public, SALUD), and three Zaragoza primary care centers (Parque Roma, Puerta del Carmen, Barrio de Jesús). Additional agreements may be added as the program matures.

**Is the degree WFME accredited?**
WFME accreditation is PENDING_CONFIRMATION. The program only launched in 2025 and has not yet completed a full WFME review cycle. Students planning to practice internationally must verify WFME status before enrolling.

**What are the tuition fees?**
18,000 EUR per year (300 EUR/ECTS × 60 ECTS/year). Preadmission fee: 195 EUR (non-refundable). Reservation fee: 3,500 EUR. Repeat subject enrollment: 20% surcharge. Total first-year cost including all fees: ANNUAL_UPDATE_REQUIRED.

**Is there an interview?**
No. The process does not include a personal interview.
