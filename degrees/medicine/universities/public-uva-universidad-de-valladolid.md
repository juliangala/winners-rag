---
id: uva

type: university
subtype: public

name: Universidad de Valladolid
short_name: UVA

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Valladolid
  region: Castilla y León
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - medium_competitiveness
  - strong_clinical_exposure
  - research_oriented

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
  seats: 260 # ANNUAL_UPDATE_REQUIRED — combined Valladolid + Palencia campuses
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
    - intake_year: 2025-2026
      round: convocatoria_ordinaria
      score: 12.720 # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: Source notasdecorte.es / Castilla y León
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
  - id: uva-medicina-valladolid
    campus: Campus Universitario Miguel Delibes, Valladolid
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
          score: 12.720 # ANNUAL_UPDATE_REQUIRED
          score_type: nota_de_admision
          notes: Source notasdecorte.es / Castilla y León
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
          score: 12.720 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: notasdecorte.es / Castilla y León
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
                Drawing_II:     0.1 # ANNUAL_UPDATE_REQUIRED
                History_Art:    ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED

  - id: uva-medicina-palencia
    campus: Campus La Yutera, Palencia
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
          score: 12.720 # ANNUAL_UPDATE_REQUIRED — Palencia campus may differ; this reflects Valladolid/regional figure
          score_type: nota_de_admision
          notes: Source notasdecorte.es / Castilla y León — ANNUAL_UPDATE_REQUIRED; verify per campus
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
          score: 12.720 # ANNUAL_UPDATE_REQUIRED — reflects Castilla y León regional figure; Palencia campus may differ
          round: convocatoria_ordinaria
          source: notasdecorte.es / Castilla y León
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
                Drawing_II:     0.1 # ANNUAL_UPDATE_REQUIRED
                History_Art:    ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---
# Universidad de Valladolid

## Overview

The Universidad de Valladolid (UVA) is one of Spain's oldest universities, founded in 1241, and offers the Grado en Medicina across two campuses: the main campus in Valladolid and a secondary campus in Palencia. Admission is entirely score-based via the Spanish nota de admisión system — no proprietary entrance exam, no interview. Competition is intense, with entry thresholds consistently among the highest in Castilla y León.

The UVA Faculty of Medicine maintains close integration with the Hospital Clínico Universitario de Valladolid and a network of affiliated hospitals, providing students with structured clinical exposure beginning in the middle years of the degree. The programme follows the standard 6-year, 360 ECTS national framework for Medicine, transitioning from basic biomedical sciences in early years to progressive clinical rotations in later years.

For international students, access is possible via PCE/UNED, Credencial UE, or direct homologation, following the national access model. UVA is positioned as a regional public option for students from Castilla y León, though it attracts applicants from across Spain given its prestige and established clinical network.

## Quick Evaluation

- **Entry mechanism:** EVAU nota de admisión only — no internal exam, no interview
- **Competitiveness:** Very high — nota de corte consistently above 13.500
- **Programme duration:** 6 years / 360 ECTS
- **Teaching language:** Spanish only
- **Two campuses:** Valladolid (main) and Palencia (secondary, smaller cohort)
- **Clinical training:** Integrated from Year 4, concentrated in Year 6 rotations
- **Tuition:** Approximately 1,000–1,500 EUR/year (Castilla y León regional rates) — ANNUAL_UPDATE_REQUIRED
- **International access:** Via PCE/UNED or Credencial UE

## Key Facts

| Parameter | Value |
|---|---|
| Official degree name | Graduado/a en Medicina |
| Responsible faculty | Facultad de Medicina |
| Main campus | Valladolid (Campus Miguel Delibes) |
| Secondary campus | Palencia (Campus La Yutera) |
| Duration | 6 years |
| Total ECTS | 360 |
| Teaching language | Spanish |
| Admission model | Nota de admisión (EVAU-based) |
| Exam required | No |
| Interview required | No |
| Annual seats (total) | PENDING_CONFIRMATION — ANNUAL_UPDATE_REQUIRED |
| Nota de corte 2025-26 | 12.720 (notasdecorte.es / Castilla y León) # ANNUAL_UPDATE_REQUIRED |
| Tuition (approx.) | ANNUAL_UPDATE_REQUIRED |
| Affiliated hospital | Hospital Clínico Universitario de Valladolid (principal) |
| Accreditation | ANECA-verified; EU Directive 2005/36/EC compliant |

## Program Options

The UVA Grado en Medicina is offered at two campuses within Castilla y León:

**Valladolid campus (main):** Located at Campus Miguel Delibes. Houses the Facultad de Medicina with full clinical, laboratory, and simulation infrastructure. The main affiliated hospital is the Hospital Clínico Universitario de Valladolid, a large university hospital. This campus is the primary and more competitive option with higher seat availability.

**Palencia campus (secondary):** Located at Campus La Yutera. A smaller cohort is admitted at this location. Clinical rotations are carried out at the Hospital Universitario Río Carrión in Palencia. The nota de corte for Palencia may differ from Valladolid — historically, Palencia has attracted candidates with slightly lower notas de admisión, though this varies annually. Candidates must specify campus preference during the preinscripción process.

There is a single unified Grado curriculum across both campuses, with no bilingual programme option as of the last verified information.

## Program Structure

The programme spans 6 academic years (360 ECTS total), structured as follows:

**Phase 1 — Basic Biomedical Sciences (Years 1–2):** Foundational sciences including Anatomy, Biochemistry, Cell Biology, Histology, Physiology, Genetics, Microbiology, and Embryology. Predominantly lectures and practical laboratory sessions.

**Phase 2 — Clinical Sciences (Years 3–4):** Introduction to Pathology, Pharmacology, Physiopathology, Propedeutics, Surgery, Internal Medicine, and specialty pathologies. Students begin supervised clinical contact in this phase.

**Phase 3 — Clinical Rotations and Integration (Years 5–6):** Intensive clinical rotations across all main medical specialties. Year 6 is structured as full-time Prácticas Académicas Externas (external clinical practice, approximately 60 ECTS equivalent in hands-on rotations), plus completion of the Trabajo Fin de Grado (TFG).

ECTS distribution (standard national framework):
- Formación Básica: ~90 ECTS
- Obligatorias: ~180 ECTS
- Prácticas Externas: ~60 ECTS
- Optativas: ~21 ECTS
- TFG: ~9 ECTS

## Teaching Methodology

The UVA Medicine programme follows a traditional lecture-based structure in early years, progressively incorporating problem-based learning (PBL) elements and clinical case analysis in Years 3 and 4. Laboratory and dissection practicals are core components of Years 1 and 2.

From Year 3 onward, seminars and clinical rotations in simulation and hospital environments become increasingly central. Clinical skills are developed through structured hospital attachments under the supervision of faculty physicians. By Year 6, students function in a near-clinical environment, taking on supervised clinical responsibilities across the rotation network.

Research initiation is available through the TFG and elective modules, and some students engage with university research groups early through voluntary participation schemes.

## Clinical Training

Clinical training is a defining strength of the UVA Medicine programme, supported by a multi-hospital network in the Castilla y León health system:

**Primary affiliated hospitals:**
- Hospital Clínico Universitario de Valladolid — the main teaching hospital, a major tertiary centre with over 700 beds and comprehensive specialty coverage
- Hospital Universitario Río Carrión, Palencia — primary teaching hospital for the Palencia campus cohort

**Additional clinical centres (Valladolid network):**
- Hospital Universitario Río Hortega (Valladolid)
- Centro de Salud (primary care rotations across Valladolid province)
- Various specialist outpatient and diagnostic centres affiliated with the Sacyl health system

Clinical rotations begin in Year 3 with supervised outpatient and inpatient exposure, intensifying progressively through Years 4 and 5. Year 6 is dedicated entirely to full-time Prácticas Académicas Externas, rotating through the hospital network under the direct supervision of attending physicians and academic tutors.

All clinical placements are ANNUAL_UPDATE_REQUIRED for network changes and availability.

## International Recognition and Opportunities

The UVA Grado en Medicina is an official Spanish university degree regulated under national law and compliant with European Directive 2005/36/EC on the recognition of professional qualifications. Graduates hold a degree recognised across all EU member states for the purpose of medical practice, subject to local licensing and language requirements.

The UVA is a member of the CEI Triangular E3 Campus of International Excellence, and participates in Erasmus+ mobility. Erasmus exchange for Medicine students is available but subject to bilateral agreements specific to the Facultad de Medicina — not all general university partnerships extend to clinical years. Students considering international mobility should confirm availability directly with the Facultad de Medicina's international office.

WFME (World Federation for Medical Education) recognition status: PENDING_CONFIRMATION. Spanish medical degrees from ANECA-accredited universities are generally recognised in jurisdictions that accept EU degrees, including Latin American countries through bilateral agreements.

## Admission Model

Access to the UVA Grado en Medicina operates entirely through the Spanish nota de admisión system. There is no internal entrance examination, no interview, and no English proficiency requirement.

**Nota de admisión formula:**
```
Nota de admisión = 0.6 × Nota media Bachillerato + 0.4 × Nota EVAU (fase general)
                  + (Subject 1 grade × ponderation) + (Subject 2 grade × ponderation)
```
- Base maximum (without specific phase): 10.0000
- With specific phase bonus: up to 14.0000
- Only the best 2 specific-phase subjects are counted

**Ponderation coefficients for Medicina at UVA (Castilla y León):**
The regional ponderation table for Castilla y León applies. Biology (0.2), Chemistry (0.2), and Physics (0.2) are the most strategically relevant subjects for Medicine applicants, as they carry the maximum coefficient and generate the largest bonus. Mathematics II carries a lower coefficient (0.1). Candidates should verify the annually published ponderation table issued by the Universidad de Valladolid / Castilla y León admission authority, as these are ANNUAL_UPDATE_REQUIRED.

**Cupo (quota) distribution:**
Spanish public universities allocate seats across access quotas. The general access quota (acceso general) covers the majority of seats. Reserved quotas exist for: students with disabilities (5%), elite or high-performance athletes, students from other universities by traslado, and international students from non-EU countries. The exact distribution is ANNUAL_UPDATE_REQUIRED.

**International access (PCE/UNED):**
Non-EU students who have completed secondary education equivalent to Spanish Bachillerato must pass the PCE/UNED (Pruebas de Competencias Específicas) administered by UNED. The nota de admisión is calculated using the same formula, with PCE subject grades substituting for EVAU specific-phase grades. A valid PCE credential is required prior to preinscripción.

**EU and equivalent credential holders (Credencial UE):**
Students from EU member states or countries with bilateral agreements (including most Latin American countries) may access Spanish universities via the Credencial Universitaria issued by UNED or through direct homologation, depending on their country. Their nota de admisión is computed equivalently.

## Admission Process

### Spanish EVAU (PAU) students — step-by-step:

1. Complete Bachillerato and register for the EVAU in Castilla y León (or the relevant autonomous community).
2. Sit the EVAU general phase (mandatory) and, optionally, specific-phase subjects (Biology, Chemistry, Physics, Mathematics II recommended for Medicine).
3. Obtain your nota de admisión — calculated automatically by the regional authority.
4. During the preinscripción period (typically June–July), submit an ordered list of degree and campus preferences via the University of Valladolid admission portal (or the regional access system).
5. Lists of admitted candidates (provisionales and definitivas) are published in stages. Monitor publication dates.
6. If admitted, complete matriculation within the established deadline and pay the first instalment of tuition fees.
7. If not admitted in the first allocation, monitor waiting list positions during the extraordinaria phase (September).

### International students (PCE/UNED) — step-by-step:

1. Verify that your home-country secondary qualification is eligible for access via PCE/UNED or direct homologation.
2. Register with UNED and sit the PCE examinations for the required subjects (Spanish language and two to four science subjects relevant to Medicine are strongly recommended).
3. Obtain your nota de acceso and, if applicable, calculate nota de admisión with PCE-specific phase subjects.
4. Check the UVA's opening date for international student preinscripción. International applicants typically have a separate quota and sometimes a different application window.
5. Submit the application with all required documentation (PCE credential, certified translations, passport, academic records).
6. Await resolution and, if admitted, proceed to matriculation.

## Admission Timeline

All dates are ANNUAL_UPDATE_REQUIRED. Approximate annual calendar:

| Stage | Approximate date |
|---|---|
| EVAU (general + specific phase) | June — ANNUAL_UPDATE_REQUIRED |
| Nota de admisión calculation | Late June — ANNUAL_UPDATE_REQUIRED |
| Preinscripción period opens | Late June – early July — ANNUAL_UPDATE_REQUIRED |
| Preinscripción deadline (ordinaria) | Early July — ANNUAL_UPDATE_REQUIRED |
| First adjudication list published | Mid-July — ANNUAL_UPDATE_REQUIRED |
| Waiting list rounds | July–August — ANNUAL_UPDATE_REQUIRED |
| EVAU extraordinaria (September round) | September — ANNUAL_UPDATE_REQUIRED |
| Extraordinaria preinscripción | September — ANNUAL_UPDATE_REQUIRED |
| Final adjudication (extraordinaria) | September–October — ANNUAL_UPDATE_REQUIRED |
| Academic year start | Mid-September — ANNUAL_UPDATE_REQUIRED |

## Admission Score Distribution

The Grado en Medicina at UVA is among the most competitive degrees in Castilla y León and in Spain nationally. Nota de corte values for Medicine consistently fall in the 13.500–13.900 range nationally, and UVA is no exception.

**Historical nota de corte (indicative — verify against official sources):**
- 2025-2026: 12.720 (source: notasdecorte.es / Castilla y León) # ANNUAL_UPDATE_REQUIRED
- 2023-2024: PENDING_CONFIRMATION
- 2022-2023: PENDING_CONFIRMATION

**Strategic interpretation:**
The verified 2025-26 nota de corte of 12.720 places UVA Medicine in the medium-competitiveness band, notably lower than historically projected ranges (13.5–13.9). A student with a 9.5 bachillerato average and solid EVAU scores in Biology and Chemistry (both 0.2 coefficients) should be competitive. Candidates should verify the figure per campus (Valladolid vs. Palencia may differ) via the UVA admissions portal each cycle.

The Palencia campus historically has a slightly lower nota de corte than Valladolid in the same cycle. Candidates close to the threshold should rank Palencia second if Valladolid is their primary preference.

Year-on-year variability of 0.05 to 0.15 points in the nota de corte is normal and driven by cohort size, seat fluctuation, and regional EVAU difficulty. No linear trend can be safely assumed.

## Costs and Payment Structure

Tuition at UVA is set annually by the Junta de Castilla y León. The following figures are indicative and ANNUAL_UPDATE_REQUIRED.

| Cost item | Amount (EUR) | Notes |
|---|---|---|
| Annual tuition (first enrollment per subject credit) | ANNUAL_UPDATE_REQUIRED | Set by Decreto de Precios Públicos, Castilla y León |
| Approximate annual tuition (full year) | ~1,000–1,500 EUR | ANNUAL_UPDATE_REQUIRED — varies by number of credits enrolled |
| Second enrollment per credit | ANNUAL_UPDATE_REQUIRED | Higher rate applies |
| Administrative fees (matriculation, certificates) | ANNUAL_UPDATE_REQUIRED | Per academic year |
| Medical/accident insurance | ~1.12 EUR/year | ANNUAL_UPDATE_REQUIRED |
| Student representation fee | ANNUAL_UPDATE_REQUIRED | Optional/mandatory depending on regulation |

Castilla y León regional public university tuition is among the higher-priced in Spain relative to other autonomous communities, but remains significantly below private institution costs.

## Scholarships and Financial Aid

**National scholarships (MEC Beca General):**
The Ministerio de Educación y Formación Profesional offers the Beca General annually. Eligibility is means-tested based on household income and academic performance. Amounts vary significantly. Students must apply via the MEFP scholarship portal annually. ANNUAL_UPDATE_REQUIRED.

**Regional Castilla y León scholarships:**
The Junta de Castilla y León operates supplementary scholarship programmes for students at Castilian-Leonese universities. Details and eligibility criteria are ANNUAL_UPDATE_REQUIRED.

**UVA own grants and aid:**
The Universidad de Valladolid offers a limited number of emergency aid grants (ayudas de emergencia) and partial fee waiver schemes. Students with academic excellence may qualify for reduction of tuition via the "matrícula de honor" mechanism — a student who achieves matricula de honor in a subject enrolls in that subject's credit hours at zero cost in the following year.

**EU students:** EU citizens are treated equivalently to Spanish nationals for fee purposes. Non-EU international students may pay differentiated (higher) rates depending on regional pricing regulation.

## Accommodation and Cost of Living

Valladolid is a mid-sized regional capital with a significantly lower cost of living than Madrid or Barcelona.

| Expense category | Approximate monthly range (EUR) | Notes |
|---|---|---|
| Student accommodation (shared flat) | 250–400 EUR | ANNUAL_UPDATE_REQUIRED |
| University residence (Colegio Mayor / residencia) | 400–650 EUR | ANNUAL_UPDATE_REQUIRED — includes meals in some cases |
| Food (self-catering) | 150–250 EUR | ANNUAL_UPDATE_REQUIRED |
| Transport (urban) | 20–40 EUR | ANNUAL_UPDATE_REQUIRED |
| Other living expenses | 100–200 EUR | ANNUAL_UPDATE_REQUIRED |
| **Estimated total monthly budget** | **520–1,290 EUR** | ANNUAL_UPDATE_REQUIRED |

The UVA manages university residence options and can direct students to its housing service. Private accommodation near the Faculty of Medicine in Valladolid is generally available and affordable by Spanish standards.

Palencia is smaller and less expensive than Valladolid, with even lower accommodation costs.

## International Exchange and Mobility Programs

The UVA participates in Erasmus+ for exchange across Europe and has bilateral agreements with universities in Latin America. The university is a member of several international networks. However, mobility in Medicine is subject to specific bilateral agreements at the faculty level — not all general university partnerships extend automatically to clinical year students.

Students in Years 5 and 6 (clinical rotation phase) typically have very limited mobility windows due to the structured nature of external practicals. Any confirmed Erasmus+ or bilateral exchange for medicine students should be verified directly with the Facultad de Medicina's Relaciones Internacionales office. PENDING_CONFIRMATION.

## MIR Preparation and Professional Outcomes

Graduates of UVA Medicine are eligible to sit the MIR (Médico Interno Residente) examination, the national competitive examination for access to medical specialisation in Spain. The MIR is taken after completion of the degree and is not linked to the university's own admission or graduation process.

UVA does not publish official MIR pass rate statistics disaggregated by institution. National MIR pass rates and ranking distributions by university origin are tracked by preparatory academies and the Ministerio de Sanidad, but are not officially published by UVA itself. PENDING_CONFIRMATION.

Graduates' professional outcomes are consistent with those of other Spanish public medical graduates: access to 49 medical specialties via MIR, positions in public and private healthcare, academic medicine, research, and public health administration. Castilla y León's public health system (Sacyl) is a major employer of UVA medicine graduates.

## Strategic Fit

### Good Fit For

- Students from Castilla y León whose nota de admisión consistently exceeds 13.5 (or likely cut-off threshold for the relevant campus and year)
- Students prioritising a public university degree with established clinical infrastructure and a large affiliated teaching hospital
- Candidates who have optimised their EVAU specific-phase strategy (Biology + Chemistry at 0.2 each) to maximise the bonus component of the nota de admisión
- International students (PCE/UNED or Credencial UE holders) who have achieved a competitive equivalent nota de admisión and are willing to engage with Spanish-only instruction
- Students seeking a cost-effective public medical education in a liveable, mid-sized Spanish city

### Less Suitable For

- Students whose nota de admisión falls below the expected cut-off range (below approximately 13.5) — the public system offers no compensatory mechanism such as an interview or extracurricular profile
- Students who require English-medium instruction — UVA Medicine is Spanish-only
- Students seeking a bilingual programme or systematic international clinical exposure in early years
- Students expecting rolling admission or a flexible calendar — UVA follows a single annual cycle with strict preinscripción deadlines

## Risks and Considerations

**Nota de corte variability:** The nota de corte can fluctuate by 0.05 to 0.15 points year-on-year. A student who narrowly met the threshold in a previous year may not be admitted in the following cycle. This risk is structural and cannot be mitigated other than by achieving a comfortable margin above the historical range.

**Regional residency quota:** While Spanish public university admissions are not formally restricted by regional residency, in practice the nota de corte tends to admit the strongest candidates nationally. Students from Castilla y León who take the EVAU locally may benefit from the regional exam system, but there is no formal regional preference in the admissions ranking.

**Seat fluctuation:** The number of seats offered at each campus can change year-on-year based on hospital capacity, Ministry authorisation, and faculty planning. Candidates should verify the official seat count for each cycle.

**Palencia campus specifics:** Students admitted via Palencia complete Years 1–2 in Palencia and clinical rotations primarily at Hospital Río Carrión. The clinical network is smaller than Valladolid's. Students with a preference for Valladolid should rank it first; a Palencia offer cannot be converted to Valladolid after adjudication.

**PCE/UNED candidates:** International students must account for additional preparation time and cost for the PCE examinations. Spanish language proficiency at a level sufficient for academic medicine instruction (approximately C1) is effectively mandatory, though no formal requirement is published.

## Important Notes

- All dates in this file are ANNUAL_UPDATE_REQUIRED. Check uva.es and the Castilla y León regional admission portal every cycle.
- The nota de corte published for previous years is the last admitted score in the final list (noviembre), not the first allocation. It is the most accurate available benchmark.
- Specific-phase subject ponderations are set per region and per degree and are ANNUAL_UPDATE_REQUIRED — verify via the UVA admissions website before each cycle.
- International students via PCE/UNED should verify the separate international preinscripción calendar, which may differ from the Spanish PAU calendar.
- The two campuses (Valladolid and Palencia) have separate seat allocations and may have different notas de corte within the same cycle.

## Key Insight

The UVA Grado en Medicina is a reliable, affordable, and clinically well-resourced public medicine degree. However, it is entirely nota de admisión-driven, which means access depends almost entirely on a numerical score derived from Bachillerato grades and EVAU performance. There is no alternative pathway, no compensatory portfolio, and no second chance within the same cycle. Students who are marginal candidates relative to historical nota de corte thresholds face a binary outcome: admitted or waitlisted. The strategic value of UVA lies in its cost efficiency, its clinical network in Castilla y León, and its historical prestige — but only for those whose nota de admisión places them safely above the threshold.

## Final Takeaway

Universidad de Valladolid offers a standard-format, publicly funded Grado en Medicina with strong clinical infrastructure, delivered entirely in Spanish, accessed exclusively via the nota de admisión system. It is strategically valuable for high-scoring candidates from Castilla y León and nationally, for students who have maximised their EVAU specific-phase bonus in Biology and Chemistry, and for those seeking affordable public medical education in a well-connected mid-sized Spanish city. Risks are concentrated in nota de corte variability and the absence of any pathway other than the score-based ranking. International students must ensure their PCE or Credencial UE results are competitive before investing in this pathway.

## Frequently Asked Questions

**How is the nota de admisión calculated?**
The nota de admisión combines 60% of the Bachillerato average grade and 40% of the EVAU general-phase score to form the base (maximum 10.0). Up to 4 additional points can be added from the EVAU specific phase: each subject grade is multiplied by a ponderation coefficient (0.1 or 0.2 depending on the subject and degree), and the best two results are added. For UVA Medicine, Biology, Chemistry, and Physics each carry a 0.2 coefficient, making them the priority specific-phase subjects.

**What is the nota de corte?**
The nota de corte is the nota de admisión of the last candidate admitted to that degree and campus in that academic year. It is published officially after final adjudication (typically November). It serves as the benchmark reference for the next cycle but is not a guaranteed threshold — it fluctuates annually.

**Can international students apply via PCE/UNED?**
Yes. Non-EU students who complete the PCE/UNED examinations obtain a nota de acceso equivalent to the Spanish EVAU result. Their nota de admisión is calculated using the same formula. They must apply during the established international preinscripción period.

**What are the tuition fees?**
Annual tuition at UVA is set by the Junta de Castilla y León via decreto de precios públicos. The approximate annual cost for a full year of first enrollment is in the range of 1,000–1,500 EUR. Exact figures are ANNUAL_UPDATE_REQUIRED.

**When do I apply?**
Applications (preinscripción) are submitted in late June / early July for the ordinaria phase, following the EVAU results. A second window (extraordinaria) is available in September for September EVAU candidates. All dates are ANNUAL_UPDATE_REQUIRED.

**What are the ponderation coefficients for Medicine at UVA?**
Biology: 0.2, Chemistry: 0.2, Physics: 0.2, Mathematics II: 0.1. These are subject to annual review. Always verify the current ponderations via the official UVA or Castilla y León admissions publications before planning your EVAU specific-phase strategy. ANNUAL_UPDATE_REQUIRED.

**Is there a Palencia campus option and how does it differ?**
Yes. The UVA offers Medicine at a secondary campus in Palencia. The curriculum is identical but the cohort is smaller and clinical rotations are concentrated at Hospital Río Carrión. The nota de corte for Palencia may be slightly lower than Valladolid within the same cycle. Campus preference must be specified at preinscripción.

**Does UVA offer Medicine in English or bilingually?**
No. The Grado en Medicina at UVA is taught entirely in Spanish.
