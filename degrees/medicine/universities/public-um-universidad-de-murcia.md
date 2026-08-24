---
id: um

type: university
subtype: public

name: Universidad de Murcia
short_name: UM

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Murcia
  region: Región de Murcia
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - medium_competitiveness
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
  level: very_high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
    - intake_year: 2025-2026
      round: convocatoria_ordinaria
      score: 12.965 # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: NULL
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
  - id: um-medicina
    campus: Campus de Espinardo, Murcia
    modality: standard
    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - medium_competitiveness
    teaching_languages:
      - Spanish
    regional_language_possible: false
    regional_language: NULL
    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL
    seats: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: PENDING_CONFIRMATION
      applicants_per_seat: PENDING_CONFIRMATION
      last_admitted_scores:
        - intake_year: 2025-2026
          round: convocatoria_ordinaria
          score: 12.965 # ANNUAL_UPDATE_REQUIRED
          score_type: nota_de_admision
          notes: NULL
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
        - intake_year: 2025-2026
          score: 12.965 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: notasdecorte.es / Región de Murcia
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
# Universidad de Murcia

## Overview

The Universidad de Murcia (UM), founded in 1272, is the main public university of the Región de Murcia. Its Facultad de Medicina offers the Grado en Medicina in a single campus setting in Murcia. The degree follows the standard national framework of 6 years and 360 ECTS, with access exclusively through the nota de admisión system.

The UM Faculty of Medicine is strongly associated with the Hospital Clínico Universitario Virgen de la Arrixaca — one of the most important university hospitals in southeastern Spain — and a broader network of regional health facilities. The Murcia region has a significant private healthcare sector, giving graduates additional clinical exposure opportunities.

Admission is highly competitive. The nota de corte for Medicine at UM is consistently among the highest in the Murcia system, typically in the 13.5–13.9 range nationally. The university offers a single programme with no bilingual track and no alternative admission mechanism beyond the nota de admisión.

## Quick Evaluation

- **Entry mechanism:** EVAU nota de admisión only — no internal exam, no interview
- **Competitiveness:** Very high — nota de corte consistently above 13.500
- **Programme duration:** 6 years / 360 ECTS
- **Teaching language:** Spanish only
- **Clinical anchor:** Hospital Clínico Universitario Virgen de la Arrixaca
- **Tuition:** Approximately 1,000–1,500 EUR/year (Región de Murcia regional rates) — ANNUAL_UPDATE_REQUIRED
- **International access:** Via PCE/UNED or Credencial UE

## Key Facts

| Parameter | Value |
|---|---|
| Official degree name | Graduado/a en Medicina |
| Responsible faculty | Facultad de Medicina |
| Campus | Campus de Espinardo, Murcia |
| Duration | 6 years |
| Total ECTS | 360 |
| Teaching language | Spanish |
| Modality | Presencial (in-person) |
| Admission model | Nota de admisión (EVAU-based) |
| Exam required | No |
| Interview required | No |
| Annual seats | PENDING_CONFIRMATION — ANNUAL_UPDATE_REQUIRED |
| Nota de corte 2025-26 | 12.965 (notasdecorte.es / Región de Murcia) — ANNUAL_UPDATE_REQUIRED |
| Tuition (approx.) | ANNUAL_UPDATE_REQUIRED |
| Primary affiliated hospital | Hospital Clínico Universitario Virgen de la Arrixaca |
| Accreditation | ANECA-verified; EU Directive 2005/36/EC compliant |

## Program Options

The UM Grado en Medicina is offered at a single campus (Espinardo, Murcia). There is no bilingual track, no secondary campus, and no alternative modality. The programme is delivered entirely in Spanish.

The Faculty of Medicine is an independent faculty with its own dedicated clinical facilities linked to the hospital network. No double-degree option combining Medicine with another discipline is available.

## Program Structure

The programme follows the standard national 6-year framework (360 ECTS):

**Phase 1 — Basic Biomedical Sciences (Years 1–2):**
Core subjects include Anatomy (general, applied, neuroanatomy), Biochemistry, Cell Biology, Physiology (I and II), Histology, Embryology, Genetics, Microbiology, Immunology, Epidemiology, and introduction to Medical Psychology and Bioethics. Year 1 is predominantly theoretical and laboratory-based.

**Phase 2 — Pathophysiology and Clinical Introduction (Years 3–4):**
Physiopathology, Propedeutics, Anatomía Patológica, Farmacología Fundamental, Radiodiagnóstico, introduction to Surgical and Medical specialties (Cardiology, Pulmonology, Digestive Pathology, Nephrology, Endocrinology, Neurology, Psychiatry, Dermatology, Obstetrics and Gynaecology, Paediatrics). Increasing clinical exposure begins in Year 3.

**Phase 3 — Clinical Rotations and Integration (Years 5–6):**
Advanced specialty modules and comprehensive Prácticas Académicas Externas (clinical rotations). Year 6 is primarily clinical, rotating across the hospital and primary care network. Trabajo Fin de Grado (TFG) is completed in Year 6.

ECTS distribution (standard national framework):
- Formación Básica: ~90 ECTS
- Obligatorias: ~180 ECTS
- Prácticas Externas: ~60 ECTS
- Optativas: ~21 ECTS
- TFG: ~9 ECTS

## Teaching Methodology

UM Medicine uses a traditional lecture-based approach in Years 1 and 2, supplemented by practical sessions in anatomy and histology laboratories. From Year 3 onward, clinical seminars, case-based learning, and skills workshops are progressively integrated.

Clinical teaching involves supervised patient contact at affiliated hospitals from Year 3 through Year 6, with Year 6 consisting entirely of full-time structured clinical rotations. Simulation facilities are available within the Faculty for procedural skills training before hospital attachment.

Research opportunities exist through the TFG and through connection to research groups linked to the Instituto Murciano de Investigación Biosanitaria (IMIB-Arrixaca), which is co-located with the teaching hospital.

## Clinical Training

The UM Medicine programme's clinical network is one of the strongest in southeastern Spain:

**Primary affiliated hospital:**
- Hospital Clínico Universitario Virgen de la Arrixaca, El Palmar (Murcia) — a major regional tertiary centre and the main university teaching hospital. IMIB-Arrixaca is located within this complex, creating a research-clinical integration environment.

**Additional clinical network:**
- Hospital General Universitario Morales Meseguer, Murcia
- Hospital General Universitario Rafael Méndez, Lorca
- Hospital General Universitario Santa Lucía, Cartagena
- Hospital Universitario Los Arcos del Mar Menor, San Javier
- Centros de Salud (primary care rotations, Servicio Murciano de Salud — SMS)

Clinical exposure begins in Year 3 with supervised bedside teaching, intensifying through Years 4 and 5, and reaching full-time immersion in Year 6 rotations across all major specialties.

All clinical placements ANNUAL_UPDATE_REQUIRED.

## International Recognition and Opportunities

The UM Grado en Medicina is an official Spanish university degree regulated under national law and compliant with European Directive 2005/36/EC. Graduates hold a degree recognised across all EU member states for medical practice.

The UM participates in Erasmus+ and maintains bilateral agreements with European and Latin American universities. Mobility for Medicine students is subject to faculty-level bilateral agreements — not all general UM partnerships extend to the Facultad de Medicina. Clinical year constraints (Year 6) typically limit mobility windows. Students should verify available options with the faculty's international office. PENDING_CONFIRMATION.

WFME recognition status: PENDING_CONFIRMATION.

## Admission Model

Access to UM Grado en Medicina operates exclusively through the nota de admisión system, managed by the Región de Murcia admissions authority. No internal exam, no interview, no English proficiency test.

**Nota de admisión formula:**
```
Nota de admisión = 0.6 × Nota media Bachillerato + 0.4 × Nota EVAU (fase general)
                  + (Subject 1 grade × ponderation) + (Subject 2 grade × ponderation)
```
- Base maximum: 10.0000; with specific phase bonus: up to 14.0000
- Only the best 2 specific-phase subjects are counted

**Ponderation coefficients for Medicina at UM (Región de Murcia):**
Biology (0.2), Chemistry (0.2), Physics (0.2) carry the maximum coefficient. Mathematics II (0.1). ANNUAL_UPDATE_REQUIRED — verify via the Comisión Gestora de los Procesos de Acceso y Preinscripción de las Universidades Públicas de la Región de Murcia.

**Cupo distribution:**
General access quota covers the majority of seats. Reserved quotas for: students with disabilities (5%), elite athletes, traslado students, and non-EU international students. Exact distribution ANNUAL_UPDATE_REQUIRED.

**International access (PCE/UNED):**
Non-EU students must pass the PCE/UNED. Nota de admisión calculated identically to domestic students.

**EU students and equivalent credential holders:**
Via Credencial UE (UNED) or direct homologation.

## Admission Process

### Spanish EVAU (PAU) students:

1. Complete Bachillerato and register for EVAU in Murcia (or relevant autonomous community).
2. Sit EVAU general phase and specific-phase subjects (Biology, Chemistry, Physics recommended).
3. Obtain nota de admisión from the regional authority.
4. Submit ordered preference list via the Murcia admissions system during preinscripción (June–July).
5. Monitor provisional and definitive adjudication lists.
6. If admitted, complete matriculation within the stipulated deadline.
7. If not admitted, monitor waiting list through extraordinaria phase (September).

### International students (PCE/UNED):

1. Verify eligibility for PCE/UNED or direct homologation.
2. Sit PCE examinations (Spanish language + Biology + Chemistry recommended).
3. Calculate nota de admisión using PCE results.
4. Check UM's international preinscripción calendar.
5. Submit application with required documentation.
6. Await resolution and proceed to matriculation if admitted.

## Admission Timeline

All dates are ANNUAL_UPDATE_REQUIRED.

| Stage | Approximate date |
|---|---|
| EVAU (general + specific phase) | June — ANNUAL_UPDATE_REQUIRED |
| Nota de admisión calculation | Late June — ANNUAL_UPDATE_REQUIRED |
| Preinscripción opens | Late June – early July — ANNUAL_UPDATE_REQUIRED |
| Preinscripción deadline (ordinaria) | Early July — ANNUAL_UPDATE_REQUIRED |
| First adjudication list | Mid-July — ANNUAL_UPDATE_REQUIRED |
| Waiting list rounds | July–August — ANNUAL_UPDATE_REQUIRED |
| EVAU extraordinaria | September — ANNUAL_UPDATE_REQUIRED |
| Final adjudication | September–October — ANNUAL_UPDATE_REQUIRED |
| Academic year start | Mid-September — ANNUAL_UPDATE_REQUIRED |

## Admission Score Distribution

The Grado en Medicina at UM is among the most competitive degrees in the Región de Murcia. Nota de corte values nationally for Medicine are consistently in the 13.5–13.9 range, and UM follows this pattern.

**Historical nota de corte:**
- 2025-2026: 12.965 (source: notasdecorte.es / Región de Murcia — ANNUAL_UPDATE_REQUIRED)
- 2023-2024: PENDING_CONFIRMATION
- 2022-2023: PENDING_CONFIRMATION

**Strategic interpretation:**
The standard ponderation structure (Biology and Chemistry at 0.2) means that a perfect specific-phase performance in two subjects adds 4.0 to the base score. Candidates at the margin must maximise both the Bachillerato average and EVAU general-phase results, as the specific-phase bonus — while significant — is available to all high-performing candidates, compressing the effective competitive range to the base score.

Year-on-year variability of 0.05–0.15 points is expected. Seat count fluctuations can drive larger swings in some cycles.

## Costs and Payment Structure

| Cost item | Amount (EUR) | Notes |
|---|---|---|
| Annual tuition (approx. first enrollment) | ~1,000–1,500 EUR | ANNUAL_UPDATE_REQUIRED — set by Decreto de la Región de Murcia |
| Per credit (2nd enrollment) | ANNUAL_UPDATE_REQUIRED | Higher rate |
| Administrative fees | ANNUAL_UPDATE_REQUIRED | Per academic year |
| Medical/accident insurance | ~1.12 EUR/year | ANNUAL_UPDATE_REQUIRED |

Murcia regional tuition is broadly comparable to other Spanish autonomous communities for public universities.

## Scholarships and Financial Aid

**MEC Beca General:** National means-tested scholarship. ANNUAL_UPDATE_REQUIRED.

**Regional Murcia scholarships:** The Región de Murcia may offer supplementary scholarship programmes. ANNUAL_UPDATE_REQUIRED.

**UM own grants:** Emergency aid grants and matrícula de honor mechanism (free re-enrollment in a subject the following year for matrícula de honor achievers).

**EU students:** Treated equivalently to Spanish nationals. Non-EU students may pay differentiated rates.

## Accommodation and Cost of Living

Murcia is a medium-sized regional capital with lower living costs than Madrid or Barcelona.

| Expense category | Approximate monthly range (EUR) | Notes |
|---|---|---|
| Student accommodation (shared flat) | 250–400 EUR | ANNUAL_UPDATE_REQUIRED |
| University residence | 350–600 EUR | ANNUAL_UPDATE_REQUIRED |
| Food (self-catering) | 150–250 EUR | ANNUAL_UPDATE_REQUIRED |
| Transport (urban) | 20–40 EUR | ANNUAL_UPDATE_REQUIRED |
| Other living expenses | 100–200 EUR | ANNUAL_UPDATE_REQUIRED |
| **Estimated total monthly budget** | **520–1,290 EUR** | ANNUAL_UPDATE_REQUIRED |

Note: The Hospital Virgen de la Arrixaca is located in El Palmar, approximately 6 km from the city centre. Students in clinical years may need transport to El Palmar for hospital rotations.

## International Exchange and Mobility Programs

UM participates in Erasmus+ and has bilateral agreements with European and Latin American universities. Mobility for Medicine students is subject to faculty-level bilateral agreements. Clinical year constraints typically limit mobility. Students should confirm availability with the Facultad de Medicina's international office. PENDING_CONFIRMATION.

## MIR Preparation and Professional Outcomes

Graduates are eligible for the MIR. UM does not publish official MIR outcome statistics disaggregated by institution. PENDING_CONFIRMATION. Professional outcomes include access to 49 medical specialties via MIR, positions in the Servicio Murciano de Salud (SMS), private healthcare, academic medicine, and research (IMIB-Arrixaca for research-oriented graduates).

## Strategic Fit

### Good Fit For

- Students from Murcia or neighbouring regions whose nota de admisión consistently exceeds the expected cut-off
- Candidates who have maximised EVAU specific-phase in Biology (0.2) and Chemistry (0.2)
- Students seeking access to a large, research-active teaching hospital (Virgen de la Arrixaca / IMIB-Arrixaca)
- International students (PCE/UNED) with a competitive nota de admisión and Spanish proficiency
- Students seeking affordable public medical education in a Mediterranean city with a lower cost of living

### Less Suitable For

- Students whose nota de admisión falls below the expected cut-off — no compensatory mechanism
- Students who require English-medium instruction
- Students expecting international mobility in early clinical years
- Students who cannot commit to Spanish-only instruction

## Risks and Considerations

**Nota de corte variability:** Annual fluctuations of 0.05–0.15 points are typical. Marginal candidates face binary risk.

**Seat count changes:** ANNUAL_UPDATE_REQUIRED — verify official seat numbers each cycle.

**Hospital distance:** Virgen de la Arrixaca (El Palmar) requires commuting from Murcia city centre in clinical years.

**Single campus:** No alternative UM Medicine campus or lower-competition pathway.

**PCE/UNED candidates:** Additional preparation investment required. Spanish proficiency at approximately C1 is effectively mandatory for clinical instruction.

## Important Notes

- All dates are ANNUAL_UPDATE_REQUIRED. Check um.es and the Murcia regional access system each cycle.
- Specific-phase ponderation coefficients are ANNUAL_UPDATE_REQUIRED — verify via the Comisión Gestora of the Región de Murcia before each cycle.
- International students via PCE/UNED should verify the separate international preinscripción calendar.
- Seat count is PENDING_CONFIRMATION — verify at um.es before the cycle.

## Key Insight

The UM Grado en Medicina is a well-resourced public medicine degree with a strong clinical network anchored in the Hospital Virgen de la Arrixaca and IMIB-Arrixaca. Like all Spanish public medicine programmes, admission is entirely nota de admisión-driven, with no alternative pathway. The programme is strategically relevant for high-scoring candidates who have maximised Biology and Chemistry in the EVAU specific phase and who are comfortable with Murcia's Mediterranean setting and lower cost of living.

## Final Takeaway

Universidad de Murcia offers standard-format public medicine education in the Región de Murcia, with access to a strong regional hospital network and a research-active biomedical institute. The programme is delivered entirely in Spanish, accessed via the nota de admisión system. It is a viable and cost-efficient pathway for high-scoring students in the southeast of Spain. Risks centre on nota de corte variability and seat count changes, with no alternative admission pathway available.

## Frequently Asked Questions

**How is the nota de admisión calculated?**
60% Bachillerato average + 40% EVAU general phase (base max 10.0) + best 2 specific-phase subjects multiplied by their coefficients. For UM Medicine: Biology 0.2, Chemistry 0.2, Physics 0.2, Mathematics II 0.1. Maximum: 14.0000. ANNUAL_UPDATE_REQUIRED.

**What is the nota de corte at UM Medicine?**
The nota de corte for 2025-2026 is 12.965 (source: notasdecorte.es / Región de Murcia — ANNUAL_UPDATE_REQUIRED). Prior cycle data (2023-24, 2022-23) remains PENDING_CONFIRMATION.

**Can international students apply via PCE/UNED?**
Yes. Non-EU students with PCE/UNED credentials calculate nota de admisión identically. Apply during the international preinscripción period.

**What are the tuition fees?**
Approximately 1,000–1,500 EUR/year for first enrollment. Exact figures ANNUAL_UPDATE_REQUIRED.

**When do I apply?**
Preinscripción in late June/early July (ordinaria). September extraordinaria for September EVAU candidates. All dates ANNUAL_UPDATE_REQUIRED.

**What are the ponderation coefficients?**
Biology: 0.2, Chemistry: 0.2, Physics: 0.2, Mathematics II: 0.1. ANNUAL_UPDATE_REQUIRED.

**Does UM offer Medicine in English?**
No. Taught entirely in Spanish.

**What hospitals do students train in?**
Primary: Hospital Clínico Universitario Virgen de la Arrixaca (El Palmar). Also: Hospital General Morales Meseguer, Hospital Rafael Méndez (Lorca), Hospital Santa Lucía (Cartagena), Hospital Los Arcos del Mar Menor (San Javier), and primary care centres (SMS network).
