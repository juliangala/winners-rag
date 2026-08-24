---
id: usc

type: university
subtype: public

name: Universidade de Santiago de Compostela
short_name: USC

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Santiago de Compostela
  region: Galicia
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - medium_competitiveness
  - research_oriented
  - strong_clinical_exposure

admission:
  intake_month: September # ANNUAL_UPDATE_REQUIRED
  applications_open_date: ANNUAL_UPDATE_REQUIRED
  rolling_admissions:
    enabled: false
    estimated_end_date: NULL
  admission_rounds:
    enabled: true
    count: 2
    rounds:
      - round: 1
        label: convocatoria_ordinaria
        application_deadline: ANNUAL_UPDATE_REQUIRED
        exam_date: ANNUAL_UPDATE_REQUIRED
        results_date: ANNUAL_UPDATE_REQUIRED
        deposit_deadline: NULL
      - round: 2
        label: convocatoria_extraordinaria
        application_deadline: ANNUAL_UPDATE_REQUIRED
        exam_date: ANNUAL_UPDATE_REQUIRED
        results_date: ANNUAL_UPDATE_REQUIRED
        deposit_deadline: NULL
  exam_required: false
  interview_required: false

academic_record:
  minimum_requirement:
    enabled: true
    grade_source: bachillerato_media
    minimum_grade: NULL
  competitive_filter:
    enabled: true
    grade_source: nota_de_admision
    approx_candidates_selected: PENDING_CONFIRMATION

curriculum:
  international_curriculums_accepted:
    - PCE/UNED
    - Credencial UE
    - Direct homologation (select countries)

competitiveness:
  level: medium_high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: 350 # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
    - intake_year: 2024-2025
      round: convocatoria_ordinaria
      score: 12.612
      score_type: nota_de_admision
      notes: Source usc.gal/es/admision/graos/notas-corte # ANNUAL_UPDATE_REQUIRED
    - intake_year: 2023-2024
      round: convocatoria_ordinaria
      score: PENDING_CONFIRMATION
      score_type: nota_de_admision
      notes: NULL
    - intake_year: 2022-2023
      round: convocatoria_ordinaria
      score: PENDING_CONFIRMATION
      score_type: nota_de_admision
      notes: NULL

international_profile:
  international_students_percentage: PENDING_CONFIRMATION
  international_nationalities: []

programs:
  - id: usc-medicina
    campus: Santiago de Compostela
    modality: standard
    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - medium_competitiveness
    teaching_languages:
      - Spanish
      - Galician
    regional_language_possible: true
    regional_language: Galician
    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL
    seats: 350 # ANNUAL_UPDATE_REQUIRED
    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 350 # ANNUAL_UPDATE_REQUIRED
      applicants_per_seat: PENDING_CONFIRMATION
      last_admitted_scores:
        - intake_year: 2024-2025
          round: convocatoria_ordinaria
          score: 12.612
          score_type: nota_de_admision
          notes: Source usc.gal/es/admision/graos/notas-corte # ANNUAL_UPDATE_REQUIRED
        - intake_year: 2023-2024
          round: convocatoria_ordinaria
          score: PENDING_CONFIRMATION
          score_type: nota_de_admision
          notes: NULL
        - intake_year: 2022-2023
          round: convocatoria_ordinaria
          score: PENDING_CONFIRMATION
          score_type: nota_de_admision
          notes: NULL
    program_specific_admission:
      enabled: false
      admission:
        intake_month: NULL
        applications_open_date: NULL
        rolling_admissions:
          enabled: NULL
          estimated_end_date: NULL
        admission_rounds:
          enabled: NULL
          count: NULL
          rounds: []
        exam_required: NULL
        interview_required: NULL
      academic_record:
        minimum_requirement:
          enabled: NULL
          grade_source: NULL
          minimum_grade: NULL
        competitive_filter:
          enabled: NULL
          grade_source: NULL
          approx_candidates_selected: NULL
    evaluation_model:
      overall_model_type: score_based
      nota_de_corte:
        - intake_year: 2024-2025
          score: 12.612
          round: convocatoria_ordinaria
          source: USC official admissions page (usc.gal) # ANNUAL_UPDATE_REQUIRED
        - intake_year: 2023-2024
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: PENDING_CONFIRMATION
        - intake_year: 2022-2023
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: PENDING_CONFIRMATION
      admission_pathways:
        - eligible_profiles:
            - Spanish EVAU (PAU) — all regional variants
            - International via PCE/UNED
            - International via Credencial UE
            - Direct homologation (select countries)
          components:
            - component: nota_media_bachillerato
              enabled: true
              role: weighted
              weight: 60
              grade_source: bachillerato_media
              notes: 60% of the nota de admisión. Grades from all 2 Bachillerato years averaged.
            - component: evau_general_phase
              enabled: true
              role: weighted
              weight: 40
              grade_source: evau_fase_general
              notes: 40% of the nota de admisión. Maximum combined base score with Bachillerato: 10.0000.
            - component: evau_specific_phase_bonus
              enabled: true
              role: bonus_only
              maximum_bonus: 4.0
              grade_source: evau_fase_especifica
              notes: Best 2 eligible subjects count. Each subject score multiplied by the university's ponderation coefficient (0.1 or 0.2). Maximum nota de admisión: 14.0000. Coefficients ANNUAL_UPDATE_REQUIRED.
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED
                Chemistry:      0.2 # ANNUAL_UPDATE_REQUIRED
                Physics:        0.2 # ANNUAL_UPDATE_REQUIRED
                Mathematics_II: 0.1 # ANNUAL_UPDATE_REQUIRED
                Drawing_II:     ANNUAL_UPDATE_REQUIRED
                History_Art:    ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---
# Universidade de Santiago de Compostela

## Overview

The Universidade de Santiago de Compostela (USC) is one of Spain's oldest and most prestigious research universities, with roots in medical education dating to 1648. The Facultad de Medicina y Odontología — the sole institution responsible for training physicians and dentists in Galicia — houses the Grado en Medicina within a six-year, 360 ECTS programme accredited under RUCT code 2502221. The curriculum is structured in three phases: a basic sciences foundation (years 1–2), an integrated clinical sciences phase (years 3–5), and an immersive clinical rotation year (year 6). USC is a member of the EUniWell European university alliance and holds the HR Excellence in Research award, reflecting a strong institutional research culture embedded directly in undergraduate medical education. Instruction is delivered in both Spanish (Castilian) and Galician, and students may interact with faculty in either language. The clinical training network is anchored by the Complejo Hospitalario Universitario de Santiago de Compostela (CHUS), one of the largest public hospital complexes in Galicia, along with a network of primary care and specialist centres affiliated with the Galician Health Service (SERGAS).

## Quick Evaluation

| Feature | Detail |
|---|---|
| Seats (plazas) | 350 (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2024-25 | 12.612 (convocatoria ordinaria) |
| Teaching language(s) | Spanish / Galician |
| Annual tuition (approx.) | ANNUAL_UPDATE_REQUIRED — set by Xunta de Galicia decree |
| Admission model | Nota de admisión (EVAU-based) — no proprietary exam, no interview |
| Clinical exposure | Broad — CHUS and SERGAS network |
| ECTS | 360 |
| Duration | 6 years |

## Key Facts

| Field | Value |
|---|---|
| Degree | Grado en Medicina (2ª edición) |
| RUCT code | 2502221 |
| Campus | Santiago de Compostela |
| Seats (plazas ofertadas) | 350 (ANNUAL_UPDATE_REQUIRED) |
| Tuition per year | ANNUAL_UPDATE_REQUIRED |
| Admission model | Score-based (nota de admisión) |
| Proprietary exam | No |
| Interview | No |
| Teaching languages | Spanish and Galician |
| Regional health system | SERGAS (Servizo Galego de Saúde) |
| Dean's office contact | medicina.decanato@usc.es |
| Admissions contact | usc.gal/es/admision/graos |

## Program Options

USC offers a single Medicine programme (Grado en Medicina, 2ª edición) delivered on the Santiago de Compostela campus. There is no separate bilingual (English-medium) track. Teaching occurs in Spanish and Galician; both co-official languages are used throughout the curriculum, and students are expected to function comfortably in a Galician-language academic environment. No English proficiency test is required for admission. International students admitted via PCE/UNED are integrated into the single standard cohort with no separate track.

## Program Structure

The Grado en Medicina is structured across six academic years with a total of 360 ECTS:

- **Basic sciences foundation (Formación básica: 90 ECTS):** Years 1–2. Core subjects include Biochemistry I and II, Physiology, Human Biology (Cytology and Genetics), Human Histology, Anatomy (locomotor, splanchnology, neuroanatomy, imaging), Biostatistics, Epidemiology, Psychology and Medical Communication, Microbiology, and Immunology.
- **Integrated clinical sciences (Obligatorias: 178.5 ECTS + optional prácticas: 13.5 ECTS):** Years 3–5. Subjects span Pathology, Pharmacology, Clinical Surgery Foundations, Radiology, Infectious Diseases, Renal Disease, Respiratory Disease, Cardiovascular Disease, Digestive Disease, Obstetrics and Gynaecology, ENT, Paediatrics I and II, Ophthalmology, Endocrinology, Rheumatology, Neurology, Psychiatry, Dermatology, Oncology, Palliative Care, Preventive Medicine, Legal Medicine, Critical Care, Anaesthesia, Orthopaedics, and Family and Community Medicine. Clinical Practical modules (Práctica Clínica I, II, III) begin in year 3.
- **Clinical rotation year (Prácticas Externas OB: 72 ECTS):** Year 6. Full-time rotations covering: Clínica Médica I (Emergency, Central Services, 12 ECTS), Clínica Médica II (9 ECTS), Clínica Quirúrgica (9 ECTS), Clínica Obstétrica y Ginecológica (6 ECTS), Clínica Pediátrica (6 ECTS), Clínica Psiquiátrica (6 ECTS), and Práctica Clínica en Medicina Familiar y Comunitaria (6 ECTS).
- **Final degree project (TFG: 6 ECTS):** Year 6. Research-oriented final project.
- **Electives (Optativas: 13.5 ECTS):** Distributed across years 2–5. Topics include Stem Cell Therapy, Bioinformatics in Medicine, Medical Genomics, Organ Transplantation, Child and Adolescent Psychiatry, Clinical Nutrition, External Internships, and Occupational Medicine.

## Teaching Methodology

USC Medicine uses a predominantly lecture-based model integrated with practical laboratory and clinical skills sessions from the early years. The programme incorporates Problem-Based Learning (PBL) elements in clinical modules from year 3 onwards, and Clinical Skills (Habilidades Clínicas) is a dedicated second-year subject that introduces structured clinical contact before the main rotation year. The Práctica Clínica I, II, and III modules in years 3–5 provide structured supervised exposure in the CHUS clinical environment. Year 6 is entirely clinical. Small-group seminars, simulation, and patient case analysis complement the lecture format throughout. The programme aligns with European standards under Directive 2005/36/EC for regulated professional training.

## Clinical Training

Clinical training is delivered through SERGAS (Servizo Galego de Saúde), the Galician public health service. The primary affiliated hospital is:

- **Complejo Hospitalario Universitario de Santiago de Compostela (CHUS):** The principal clinical training centre, comprising Hospital Clínico Universitario and Hospital Gil Casares, located adjacent to the Faculty on the main Santiago campus. CHUS is a tertiary referral centre for Galicia with specialised units in oncology, cardiology, neurology, and surgery.

Additional clinical training settings include:
- Primary care centres (centros de saúde) affiliated with SERGAS across the Santiago area
- Psychiatric facilities within the CHUS network
- Community and family medicine rotations throughout Galicia

Year-6 rotations are completed exclusively within CHUS and affiliated SERGAS units.

## International Recognition and Opportunities

USC Medicine is registered in the Spanish RUCT (Registro de Universidades, Centros y Títulos) and recognised under the EU Directive 2005/36/EC, giving graduates automatic right to practise medicine throughout the European Economic Area without additional equivalence procedures. The programme is not separately WFME-accredited as a standalone unit but operates under the broader institutional quality frameworks applicable to Spanish public universities. USC is a member of the EUniWell alliance (European University for Well-Being), providing exchange pathways with partner universities across Europe. USC participates extensively in Erasmus+ for both outgoing and incoming students, with Medicine-specific bilateral agreements across Europe. The SICUE domestic exchange programme enables mobility to other Spanish universities within agreed frameworks.

## Admission Model

USC Medicine admission is governed exclusively by the **nota de admisión**, a composite score calculated as follows:

```
Nota de admisión = 0.6 × Nota media Bachillerato
                 + 0.4 × EVAU general phase score
                 + best 2 specific-phase subjects × ponderation coefficient
```

- **Maximum base score (Bachillerato + general phase):** 10.0000
- **Maximum nota de admisión (with specific-phase bonus):** 14.0000
- **No proprietary exam, no interview, no English test**

**Specific-phase ponderation coefficients for USC Medicine (ANNUAL_UPDATE_REQUIRED):**

| Subject | Coefficient |
|---|---|
| Biology (Biología) | 0.2 |
| Chemistry (Química) | 0.2 |
| Physics (Física) | 0.2 |
| Mathematics II | 0.1 |
| Other subjects | ANNUAL_UPDATE_REQUIRED |

Coefficients published annually by USC, typically each autumn before the admissions cycle. Always verify at usc.gal before the EVAU registration period.

**International students (PCE/UNED route):** International applicants who have not taken the Spanish EVAU (PAU) must access USC through one of the following routes:
1. **PCE/UNED (Pruebas de Competencias Específicas):** Sit a minimum of five subject exams administered by UNED, plus the Spanish language and literature test if Spanish is not the student's native language. The PCE score is used to construct a nota de admisión equivalent, applying the same 0.6/0.4 formula. Ponderation coefficients for USC-specific subjects apply identically.
2. **Credencial UE:** Students from EU-system educational frameworks (e.g., French Baccalauréat, Italian Maturità) may obtain a Credencial issued by UNED or relevant regional authority, which translates their academic scores into a nota de admisión equivalent.
3. **Direct homologation:** Applicable to students from certain bilateral agreement countries (primarily Latin America); check UNED and Spanish Ministry of Education requirements annually.

PCE/UNED applicants compete in the same general quota as domestic candidates. USC does not publish a separate reserved international quota for Medicine.

## Admission Process

### Spanish PAU (EVAU) students

1. Complete Bachillerato and sit the EVAU in the Galician PAU convocatoria (managed by CIUG — Comisión Interuniversitaria de Galicia).
2. Sit specific-phase subjects: Biology and Chemistry are the highest-value subjects for Medicine at USC (coefficient 0.2 each). Sitting Physics and/or Mathematics II can provide additional bonus at the lower coefficient (0.1).
3. Calculate your nota de admisión: confirm your Bachillerato average (media de Bachillerato) from your academic transcript and combine with EVAU results using the formula.
4. In June/July (convocatoria ordinaria), apply for university places through the CIUG portal (ciug.gal). Rank your preferred degrees and universities in order of preference.
5. CIUG processes assignments based on nota de admisión in descending order. Candidates above the nota de corte are assigned places.
6. If not admitted in the ordinaria round, candidates may apply again in September (convocatoria extraordinaria) if available seats remain.
7. Confirm enrolment (matrícula) at USC within the stated deadline. No deposit is required in advance.

### International PCE/UNED students

1. Register with UNED for the PCE examinations. Deadlines are typically in January–March for the June sitting.
2. Select a minimum of five PCE subject exams. For USC Medicine, prioritise: Biology, Chemistry, Physics. Ensure you also register for the Spanish Language and Literature test if required.
3. Sit the PCE exams in May/June (ordinaria) or September (extraordinaria) at a UNED exam centre.
4. Receive your PCE results and calculate your nota de admisión equivalent using the standard formula.
5. Apply to USC via the CIUG portal during the standard admissions window, presenting your PCE certificate and supporting documentation.
6. If your nota de admisión equivalent meets or exceeds the nota de corte, you are eligible for a place in the general quota.
7. Complete homologation of your secondary education diploma if required by Spanish authorities (gestión a través del Ministerio de Educación).
8. Enrol at USC within the stated deadline.

## Admission Timeline

| Phase | Approximate dates | Notes |
|---|---|---|
| Galician EVAU (PAU) — ordinaria | June (ANNUAL_UPDATE_REQUIRED) | Set by CIUG / Xunta de Galicia |
| CIUG admissions application window | Late June / July (ANNUAL_UPDATE_REQUIRED) | ciug.gal portal |
| Ordinaria assignment results | July (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| Enrolment confirmation | July–August (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| Galician EVAU — extraordinaria | September (ANNUAL_UPDATE_REQUIRED) | Not all degrees participate |
| Extraordinaria results / enrolment | September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| Academic year start | September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| PCE registration (UNED) | January–March (ANNUAL_UPDATE_REQUIRED) | For international applicants |
| PCE exams | May–June / September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |

All dates are subject to annual revision by CIUG and the Galician regional government.

## Admission Score Distribution

### Nota de corte history

| Intake year | Round | Nota de corte | Source |
|---|---|---|---|
| 2024-2025 | Convocatoria ordinaria | **12.612** | USC official admissions page |
| 2023-2024 | Convocatoria ordinaria | PENDING_CONFIRMATION | PENDING_CONFIRMATION |
| 2022-2023 | Convocatoria ordinaria | PENDING_CONFIRMATION | PENDING_CONFIRMATION |

**Trend analysis:** The 2024-25 nota de corte of 12.612 is notably lower than what is typically observed at Spain's most competitive Medicine programmes (which often exceed 13.5). This places USC in a medium-high competitiveness band — highly competitive in absolute terms, but considerably more accessible than the top-ranked Spanish public Medicine faculties. Historically, USC Medicine has maintained a nota de corte in the range of approximately 12.5–13.2, reflecting the large cohort (350 seats — one of the largest in Spain) and the Galician applicant pool dynamics. The large seat count is the primary driver of the relatively lower nota de corte compared to faculties with 100–150 seats. Candidates with a nota de admisión comfortably above 12.8 have a reasonable expectation of admission, though year-to-year variation of ±0.3–0.5 points is normal.

**Practical implication:** USC is a realistic target for candidates whose nota de admisión is firmly above 12.8, and a stretch target for those between 12.5–12.7. Candidates with 13.0+ should treat USC as a secure option.

## Costs and Payment Structure

Public university fees at USC are set by the Xunta de Galicia by annual decree. Fees below are indicative based on the regional public pricing model and are subject to revision each academic year.

| Fee component | Approximate amount | Notes |
|---|---|---|
| Annual tuition (tasas académicas) | ANNUAL_UPDATE_REQUIRED | Set by Xunta de Galicia decree |
| Enrolment fee (secretaría) | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Academic services fee | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Total estimated annual cost | ~1,000–1,500 EUR | ANNUAL_UPDATE_REQUIRED — typical Galicia range |
| Registration for EVAU (domestic) | ANNUAL_UPDATE_REQUIRED | Paid to CIUG, not to USC |
| PCE registration (international) | ANNUAL_UPDATE_REQUIRED | Paid to UNED |

Galicia has historically maintained public university tuition among the lowest in Spain, broadly in line with the national public university range of 1,000–1,500 EUR per year for first enrolment in a Health Sciences programme. Confirm the exact figure via the USC Prezos Públicos page (usc.gal/es/admision/prezos-titulacions-academicas) before enrolment.

## Scholarships and Financial Aid

- **MEC Beca General (Ministerio de Educación y Formación Profesional):** The principal national scholarship for public university students in Spain. Awarded based on academic performance and household income. Covers tuition and may include a maintenance component (beca de cuantía variable). Apply annually via the MEFP online portal.
- **Becas Xunta de Galicia:** The Galician regional government offers additional scholarships for Galician residents studying at USC and other public universities in Galicia, including complementary grants for accommodation and transport. Check the Xunta portal annually.
- **USC own grants (Axudas USC):** USC administers its own scholarship and emergency aid programmes (Bolsas de colaboración, Fondo Social Universitario) for enrolled students facing financial hardship. Check usc.gal/es/servicios/area/becas-ayudas.
- **ERASMUS+ mobility grants:** Available to enrolled students during the exchange period (typically year 4–5). Amounts vary by destination country.
- **International students:** PCE/UNED international students are technically eligible for MEC Beca General if they meet residency and income conditions, but in practice most international candidates do not qualify. No dedicated scholarship for non-EU international Medicine students has been identified at USC.

## Accommodation and Cost of Living

Santiago de Compostela is a compact historic city with a well-established student infrastructure. The cost of living is moderate by Spanish standards.

| Category | Estimated monthly cost | Notes |
|---|---|---|
| University residence (Residencias USC) | ANNUAL_UPDATE_REQUIRED | Book early — limited places |
| Private shared flat (piso compartido) | ~350–550 EUR/month | Most common student option |
| Private studio apartment | ~500–750 EUR/month | ANNUAL_UPDATE_REQUIRED |
| Food (self-catering + university canteen) | ~200–350 EUR/month | Comedor universitario available |
| Transport (local bus) | ~20–40 EUR/month | City is walkable; campus is central |
| Total monthly estimated budget | ~600–950 EUR | Excluding tuition |

USC operates several university residences (Colexios Maiores) on or near the campus. The Colexio Maior Fonseca and others are listed at usc.gal. Early application is strongly advised, as places are limited. Most Medicine students live in private shared housing near the Facultad de Medicina, which is located in the historic city centre adjacent to Hospital Clínico Universitario.

## International Exchange and Mobility Programs

- **Erasmus+:** USC has Erasmus+ bilateral agreements with numerous European universities across medicine and health sciences programmes. Exchanges typically take place in years 3–5. Students receive an Erasmus grant and retain USC enrolment status.
- **SICUE (Sistema de Intercambio entre Centros Universitarios Españoles):** Domestic exchange programme for Spanish universities. Students may request a SICUE placement at another Spanish Faculty of Medicine for one or two semesters.
- **International clinical electives:** USC facilitates international clinical rotations through agreements with selected partner hospitals and universities, primarily under Erasmus+ and EUniWell frameworks. Individual arrangements are also possible via the USC International Office.
- **EUniWell alliance:** USC's membership in this European university consortium provides structured exchange and collaborative research opportunities with partner institutions in Cologne, Warwick, Nantes, Florence, Turku, Montpellier, and others.

## MIR Preparation and Professional Outcomes

USC does not publish disaggregated MIR (Médico Interno Residente) pass rate data at the faculty level. National MIR preparation is the standard post-graduation pathway for USC Medicine graduates. The MIR is a nationally competitive examination taken by all graduates seeking specialist training in Spain; USC graduates sit the same exam as all other Spanish medical graduates. USC has a strong research-oriented culture and several research groups within the Faculty produce output relevant to clinical training in specific specialties.

Professional outcomes for USC Medicine graduates include:
- Specialist training via MIR (the primary route)
- Research and academic medicine positions (Doctoral programmes at USC)
- General practice via the MIR Family Medicine route
- International practice (EU recognition is automatic via Directive 2005/36/EC)

MIR-specific preparation courses and groups are available through the USC Faculty and privately in Santiago.

## Strategic Fit

### Good Fit For

- Candidates with a nota de admisión firmly above 12.8 who want access to a large, established, research-active public Medicine faculty at low cost.
- Galician students (or students who have sat or can sit the Galician PAU) who are comfortable with bilingual Spanish/Galician academic environments.
- International students with a PCE nota de admisión equivalent above 12.8 who want a high-quality public university experience at dramatically lower cost than private alternatives.
- Candidates who value clinical exposure in a large tertiary hospital (CHUS) from year 3 and a fully clinical final year.
- Students interested in research-oriented medical careers, given USC's robust research group infrastructure.
- Candidates who appreciate a smaller, walkable, UNESCO World Heritage city with a strong student culture and moderate cost of living.

### Less Suitable For

- Candidates whose nota de admisión is below 12.5 — the nota de corte risk is real and the programme does not offer conditional or deferred admission.
- Students who are uncomfortable with the Galician co-official language context (some teaching, administrative materials, and faculty communication may be in Galician).
- Candidates who require English-medium instruction — no English-track is available.
- Students seeking guaranteed admission without sitting the EVAU or PCE — there are no alternative admission routes.

## Risks and Considerations

1. **Nota de corte variability:** While the 2024-25 cut-off of 12.612 is relatively accessible for a Spanish Medicine programme, year-to-year shifts of 0.3–0.5 points can occur depending on applicant volume. A candidate targeting USC with a nota of 12.7 should treat admission as probable but not certain.
2. **Galician regional residency quota:** The Galician admissions system may apply preferential quotas for Galician residents in some configurations. Verify the precise quota allocation with CIUG each cycle, as this can affect effective competition for non-resident applicants.
3. **Large cohort dynamics:** With 350 seats, USC Medicine is one of Spain's largest cohorts. While this increases admission accessibility, it also means a larger peer group in lecture-based settings during the preclinical years.
4. **PCE equivalence risk:** International students must verify that their PCE nota de admisión is calculated correctly and submitted to CIUG within the deadline. Errors in score calculation or documentation can result in non-admission even if the score is competitive.
5. **Language environment:** Non-Spanish-speaking international students face a dual-language environment. Proficiency in Spanish is a practical prerequisite; exposure to Galician is advisable.
6. **Extraordinaria nota de corte:** The September extraordinaria round typically sees few remaining places in Medicine and the effective cut-off may not differ substantially from the ordinaria. Do not rely on the extraordinaria as a fallback strategy.

## Important Notes

- The programme is designated as "2ª edición" (second edition), reflecting that this is the updated version of the USC Medicine degree plan, verified in the RUCT as of 2025.
- Decree of authorisation: Decreto 150/2010 del 16 de septiembre (DOG 23/09/10). Published in the BOE on 26 February 2026. Last accreditation: 30 October 2018.
- Ponderation coefficients published by USC are ANNUAL_UPDATE_REQUIRED and must be confirmed each autumn via the USC admissions page before registering for specific-phase EVAU subjects.
- Pre-enrolment documentation for international PCE students must be submitted to CIUG and USC within stated deadlines. Late or incomplete documentation will result in loss of the offered place.
- Mandatory Spanish-language proficiency for PCE non-native Spanish speakers: UNED Spanish Language and Literature PCE exam is the standard requirement.

## Key Insight

USC Medicine is Spain's most accessible large public Medicine faculty by nota de corte. The combination of 350 seats and the Galician applicant pool produces a cut-off around 12.6 — roughly 0.8–1.0 points below the national top-tier Medicine programmes (which cluster around 13.5–13.8). For a candidate with a nota de admisión of 12.8–13.2, USC is a realistic, high-quality option with excellent clinical infrastructure, low cost, and institutional research prestige. The large cohort and bilingual Galician/Spanish environment are the main factors to weigh. For international PCE candidates, USC represents a clear entry point into Spanish public Medicine at dramatically lower cost than any private alternative.

## Final Takeaway

USC is a well-established, research-active public Medicine faculty with one of Spain's largest Medicine cohorts, competitive nota de corte in the medium-high band (12.6 in 2024-25), and clinical training anchored in the large CHUS hospital network. Tuition is set by regional decree at public rates, making it dramatically more affordable than private Medicine in Spain. Teaching is conducted in Spanish and Galician; international students access via PCE/UNED. The nota de corte is the single decisive admission criterion — no exam, no interview, no English test. Candidates with a nota de admisión above 12.8 should seriously evaluate USC as a primary or strong secondary option.

## Frequently Asked Questions

**Q: How is the nota de admisión calculated for USC Medicine?**
A: Nota de admisión = 0.6 × Bachillerato average + 0.4 × EVAU general phase score + (up to 2 specific-phase subjects × coefficient). The base maximum is 10.0000; with specific-phase bonus, the maximum is 14.0000.

**Q: What is the nota de corte for USC Medicine?**
A: The nota de corte for 2024-25 was 12.612 (convocatoria ordinaria). This is the lowest nota de admisión accepted that cycle. It changes each year based on the applicant pool and available seats. Historical data for prior years is PENDING_CONFIRMATION in this file — always verify with the CIUG historical records.

**Q: Which EVAU specific-phase subjects are most valuable for USC Medicine?**
A: Biology and Chemistry both carry a coefficient of 0.2 (the maximum) at USC. Physics also carries 0.2. Mathematics II carries 0.1. Candidates should prioritise sitting Biology and Chemistry in the specific phase, and Physics as a third subject for maximum score potential. These coefficients are ANNUAL_UPDATE_REQUIRED.

**Q: Can international students apply via PCE/UNED?**
A: Yes. International students who have not taken the Spanish EVAU must apply via PCE/UNED (or Credencial UE for EU-system students). The PCE nota de admisión equivalent is calculated using the same formula as domestic students. PCE applicants compete in the general quota — there is no separate international reserved quota at USC Medicine.

**Q: What are the tuition fees at USC?**
A: Tuition is set annually by the Xunta de Galicia by regional decree. Galicia maintains public university fees in the approximate range of 1,000–1,500 EUR per academic year for first-enrolment Health Sciences students, subject to annual revision. Confirm the exact amount at usc.gal/es/admision/prezos-titulacions-academicas before enrolment.

**Q: When do I apply to USC Medicine?**
A: Applications through CIUG are submitted in late June / early July following the convocatoria ordinaria EVAU results. The exact deadline is published annually by CIUG (ciug.gal). A second window may open in September for the convocatoria extraordinaria if seats remain. International PCE students must complete PCE registration with UNED several months in advance (typically January–March for the June sitting).

**Q: Is there an interview or entrance exam?**
A: No. USC Medicine admission is determined exclusively by the nota de admisión. There is no proprietary university exam, no interview, and no English proficiency test required for admission.

**Q: Does USC teach in Galician or Spanish?**
A: Both. The programme uses Spanish (Castilian) and Galician (Galego) as co-official languages of instruction. Individual lecturers may teach in either language. Administrative materials, clinical settings, and SERGAS interactions also occur in both languages. Students are not required to be fluent in Galician before arrival, but comfort with the language significantly enhances the learning experience.
