---
id: uclm

type: university
subtype: public

name: Universidad de Castilla-La Mancha
short_name: UCLM

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Albacete
  region: Castilla-La Mancha
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
  level: medium_high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: 100 # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
    - intake_year: 2025-2026
      round: convocatoria_ordinaria
      score: 12.798 # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: Source — notasdecorte.es / Castilla-La Mancha (Albacete campus)
    - intake_year: 2024-2025
      round: convocatoria_ordinaria
      score: PENDING_CONFIRMATION
      score_type: nota_de_admision
      notes: NULL
    - intake_year: 2023-2024
      round: convocatoria_ordinaria
      score: PENDING_CONFIRMATION
      score_type: nota_de_admision
      notes: NULL

international_profile:
  international_students_percentage: PENDING_CONFIRMATION
  international_nationalities: []

programs:
  - id: uclm-medicina
    campus: Campus de Albacete
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
    seats: 100 # ANNUAL_UPDATE_REQUIRED
    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 100 # ANNUAL_UPDATE_REQUIRED
      applicants_per_seat: PENDING_CONFIRMATION
      last_admitted_scores:
        - intake_year: 2025-2026
          round: convocatoria_ordinaria
          score: 12.798 # ANNUAL_UPDATE_REQUIRED
          score_type: nota_de_admision
          notes: Source — notasdecorte.es / Castilla-La Mancha (Albacete campus)
        - intake_year: 2024-2025
          round: convocatoria_ordinaria
          score: PENDING_CONFIRMATION
          score_type: nota_de_admision
          notes: NULL
        - intake_year: 2023-2024
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
          score: 12.798 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: notasdecorte.es / Castilla-La Mancha (Albacete campus)
        - intake_year: 2024-2025
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED — verify at uclm.es
        - intake_year: 2023-2024
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
  - id: uclm-medicina-ciudad-real
    campus: Facultad de Medicina de Ciudad Real, Campus de Ciudad Real
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
          score: 12.869 # ANNUAL_UPDATE_REQUIRED
          score_type: nota_de_admision
          notes: Source — notasdecorte.es / Castilla-La Mancha (Ciudad Real campus)
        - intake_year: 2024-2025
          round: convocatoria_ordinaria
          score: PENDING_CONFIRMATION
          score_type: nota_de_admision
          notes: NULL
        - intake_year: 2023-2024
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
          score: 12.869 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: notasdecorte.es / Castilla-La Mancha (Ciudad Real campus)
        - intake_year: 2024-2025
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED — verify at uclm.es/cr/medicina/
        - intake_year: 2023-2024
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
# Universidad de Castilla-La Mancha

## Overview

The Universidad de Castilla-La Mancha (UCLM) is a multi-campus public university serving the autonomous community of Castilla-La Mancha, with campuses in Albacete, Ciudad Real, Cuenca, and Toledo. The Grado en Medicina is offered exclusively on the **Albacete campus**, housed in the Faculty of Medicine (Facultad de Medicina de Albacete). The programme is a six-year, 360 ECTS degree accredited under ANECA and registered in the RUCT. UCLM Medicine occupies a distinctive position in the Spanish public Medicine landscape: it is the only public Medicine faculty in Castilla-La Mancha, serving the healthcare education needs of an extensive, historically underserved region. Clinical training is delivered primarily through the Hospital General Universitario de Albacete (CHUA), one of the largest hospitals in the Castilla-La Mancha health system (SESCAM), supplemented by a network of secondary hospitals and primary care centres across the region.

## Quick Evaluation

| Feature | Detail |
|---|---|
| Seats (plazas) | 100 (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2025-26 | 12.798 (notasdecorte.es / Castilla-La Mancha — Albacete campus — ANNUAL_UPDATE_REQUIRED) |
| Teaching language(s) | Spanish |
| Annual tuition (approx.) | ANNUAL_UPDATE_REQUIRED — set by Junta de Castilla-La Mancha decree |
| Admission model | Nota de admisión (EVAU-based) — no proprietary exam, no interview |
| Clinical exposure | Good — CHUA Albacete and SESCAM network |
| ECTS | 360 |
| Duration | 6 years |

## Key Facts

| Field | Value |
|---|---|
| Degree | Grado en Medicina |
| Campuses | Campus de Albacete · Campus de Ciudad Real |
| Seats (plazas ofertadas) | 100 (ANNUAL_UPDATE_REQUIRED) |
| Tuition per year | ANNUAL_UPDATE_REQUIRED |
| Admission model | Score-based (nota de admisión) |
| Proprietary exam | No |
| Interview | No |
| Teaching language | Spanish |
| Regional health system | SESCAM (Servicio de Salud de Castilla-La Mancha) |
| Admissions contact | uclm.es/estudios/grados/medicina |

## Program Options

UCLM offers the Grado en Medicina on **two campuses**: Albacete and Ciudad Real. Both programmes are delivered entirely in Spanish, follow the same national curriculum framework (Orden ECI/332/2008), and use the same Castilla-La Mancha admissions system (EvAU CLM / nota de admisión). There is no bilingual or English-medium Medicine track at either campus. No English proficiency test is required for admission. Castilla-La Mancha is a monolingual region (Spanish only — no co-official regional language).

| Feature | Albacete campus | Ciudad Real campus |
|---|---|---|
| Nota de corte 2025-2026 | 12.798 | 12.869 |
| Seats | 100 (ANNUAL_UPDATE_REQUIRED) | PENDING_CONFIRMATION |
| Clinical hospital | CHUA (Complejo Hospitalario Universitario de Albacete) | PENDING_CONFIRMATION — likely Hospital General Universitario de Ciudad Real |
| Campus website | uclm.es | uclm.es/cr/medicina/ |

Candidates should select their preferred campus when applying through the UCLM admissions system. The two campuses are academically equivalent; the nota de corte differs slightly, with Ciudad Real (12.869) marginally higher than Albacete (12.798) in the 2025-2026 cycle.

## Program Structure

The Grado en Medicina at UCLM is structured across six academic years with 360 ECTS:

- **Years 1–2 (Biomedical sciences foundation):** Anatomy, histology, physiology, biochemistry, cell biology and genetics, microbiology, immunology, public health, epidemiology, medical ethics, biostatistics, psychology, and communication skills. Laboratory and practical work begins from year 1.
- **Years 3–4 (Clinical sciences):** Pathology (general and special), pharmacology, radiology, internal medicine, surgery, gynaecology and obstetrics, paediatrics, psychiatry, neurology, dermatology, ENT, ophthalmology, and clinical skills. Structured clinical contact through hospital visits and supervised patient interactions begins in year 3.
- **Years 5–6 (Clinical rotations):** Full clinical rotations through all major specialties at CHUA Albacete and affiliated SESCAM hospitals. Year 6 is the dedicated clinical training year with rotations in internal medicine, surgery, obstetrics, paediatrics, psychiatry, family and community medicine. TFG (Trabajo Fin de Grado) is completed in the final year.
- **Electives:** Optional subjects are available within the curriculum framework.

Full ECTS distribution available at uclm.es.

## Teaching Methodology

UCLM Medicine follows a predominantly traditional lecture-based model, complemented by laboratory practicals, seminars, and clinical case discussions. Clinical skills are developed progressively, with formal hospital integration beginning in year 3. The pedagogical approach reflects the programme's role as the sole provider of public medical education in Castilla-La Mancha, balancing rigorous academic formation with practical preparation for healthcare in regional settings. The programme aligns with the directives of Orden ECI/332/2008, which establishes the minimum requirements for verified Medicine degrees in Spain.

## Clinical Training

Clinical training at UCLM Medicine is delivered through the SESCAM (Servicio de Salud de Castilla-La Mancha) network. The primary affiliated institution is:

- **Complejo Hospitalario Universitario de Albacete (CHUA):** The main clinical training hospital, a tertiary referral centre for Castilla-La Mancha with approximately 750 beds and specialised services across oncology, cardiology, neurology, surgery, and paediatrics.

Additional clinical training settings include:
- Secondary hospitals in the SESCAM network (Hospital de Hellín, Hospital Virgen de Los Llanos in Hellín, and others across the region)
- Primary care centres (centros de salud) managed by SESCAM across Albacete province
- Community medicine and family medicine rotations across the region

Year-6 rotations are primarily delivered at CHUA and affiliated SESCAM facilities.

## International Recognition and Opportunities

UCLM Medicine is registered in the Spanish RUCT and recognised under EU Directive 2005/36/EC, providing automatic EEA-wide professional recognition for graduates. The degree enables direct access to MIR and to practice throughout the European Economic Area. UCLM participates in Erasmus+ with bilateral agreements for Medicine and health sciences students. The SICUE domestic exchange programme is available for intra-Spanish mobility. UCLM has developed international partnerships particularly with Latin American universities, which may create research and exchange opportunities for enrolled students.

## Admission Model

UCLM Medicine admission is governed exclusively by the **nota de admisión**:

```
Nota de admisión = 0.6 × Nota media Bachillerato
                 + 0.4 × EVAU general phase score
                 + best 2 specific-phase subjects × ponderation coefficient
```

- **Maximum base score:** 10.0000
- **Maximum nota de admisión (with specific-phase bonus):** 14.0000
- **No proprietary exam, no interview, no English test**

**Specific-phase ponderation coefficients for UCLM Medicine (ANNUAL_UPDATE_REQUIRED):**

| Subject | Coefficient |
|---|---|
| Biology (Biología) | 0.2 |
| Chemistry (Química) | 0.2 |
| Physics (Física) | 0.2 |
| Mathematics II | 0.1 |
| Other subjects | ANNUAL_UPDATE_REQUIRED |

Coefficients are published annually by UCLM and must be verified at uclm.es before the EVAU registration period. The Castilla-La Mancha EVAU (EvAU CLM) is managed by UCLM jointly with the Junta de Castilla-La Mancha.

**International students (PCE/UNED route):** International students use PCE/UNED or Credencial UE to construct a nota de admisión equivalent. PCE applicants compete in the general quota at UCLM; there is no separately reserved international quota for Medicine.

## Admission Process

### Spanish PAU (EVAU) students

1. Complete Bachillerato and sit the EVAU Castilla-La Mancha (EvAU CLM), organised by UCLM jointly with the regional education authority.
2. Sit specific-phase subjects: Biology (0.2) and Chemistry (0.2) are the highest-coefficient subjects for Medicine at UCLM. Physics (0.2) is recommended as a third specific-phase subject.
3. Calculate the nota de admisión and compare against the nota de corte for UCLM Medicine from the most recent cycle.
4. Apply for university places through the UCLM admissions portal (pre-enrolment process — preinscripción) during the June/July window.
5. Places are allocated in descending nota de admisión order. Candidates above the nota de corte are offered places.
6. If not admitted in the ordinaria, candidates may apply again in September for remaining seats.
7. Confirm enrolment within the stated deadline.

### International PCE/UNED students

1. Register with UNED for PCE examinations (January–March for June sitting).
2. Select five PCE subjects; prioritise Biology, Chemistry, and Physics.
3. Sit PCE exams (May/June ordinaria; September extraordinaria).
4. Calculate nota de admisión equivalent and apply via UCLM's admissions portal with PCE documentation.
5. If nota de admisión equivalent meets the nota de corte, proceed with enrolment.
6. Complete homologation of secondary education diploma if required.

## Admission Timeline

| Phase | Approximate dates | Notes |
|---|---|---|
| EvAU CLM — ordinaria | June (ANNUAL_UPDATE_REQUIRED) | Managed by UCLM + Junta CLM |
| UCLM preinscripción (admissions) | Late June / July (ANNUAL_UPDATE_REQUIRED) | uclm.es portal |
| Ordinaria results | July (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| Enrolment confirmation | July–August (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| EvAU CLM — extraordinaria | September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| Extraordinaria results / enrolment | September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| Academic year start | September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| PCE registration (UNED) | January–March (ANNUAL_UPDATE_REQUIRED) | For international applicants |
| PCE exams | May–June / September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |

## Admission Score Distribution

### Nota de corte history

#### Albacete campus

| Intake year | Round | Nota de corte | Source |
|---|---|---|---|
| 2025-2026 | Convocatoria ordinaria | 12.798 | notasdecorte.es / Castilla-La Mancha — Albacete campus (ANNUAL_UPDATE_REQUIRED) |
| 2024-2025 | Convocatoria ordinaria | PENDING_CONFIRMATION | PENDING_CONFIRMATION |
| 2023-2024 | Convocatoria ordinaria | PENDING_CONFIRMATION | PENDING_CONFIRMATION |

#### Ciudad Real campus

| Intake year | Round | Nota de corte | Source |
|---|---|---|---|
| 2025-2026 | Convocatoria ordinaria | 12.869 | notasdecorte.es / Castilla-La Mancha — Ciudad Real campus (ANNUAL_UPDATE_REQUIRED) |
| 2024-2025 | Convocatoria ordinaria | PENDING_CONFIRMATION | PENDING_CONFIRMATION |
| 2023-2024 | Convocatoria ordinaria | PENDING_CONFIRMATION | PENDING_CONFIRMATION |

**Campus comparison (2025-2026):** Ciudad Real (12.869) vs Albacete (12.798) — Ciudad Real is marginally more competitive in this cycle. Both figures are ANNUAL_UPDATE_REQUIRED and must be verified at uclm.es before application.

**Trend analysis:** UCLM Medicine draws primarily from the Castilla-La Mancha regional EVAU pool, operating across two campuses. Nota de corte data must be verified at uclm.es or through UCLM's official pre-enrolment statistics, published after each convocatoria. The 2025-26 scores (Albacete 12.798; Ciudad Real 12.869) confirm the medium-high competitiveness band for both campuses. Prior-cycle data remains PENDING_CONFIRMATION for both.

**Practical implication:** Candidates with a nota de admisión above 12.8 should evaluate both UCLM campuses. Ciudad Real (12.869) requires a slightly higher score than Albacete (12.798) based on 2025-2026 data. Verify the current nota de corte for each campus before finalising the application strategy.

## Costs and Payment Structure

Public university fees at UCLM are set by the Junta de Castilla-La Mancha by annual decree.

| Fee component | Approximate amount | Notes |
|---|---|---|
| Annual tuition (tasas académicas) | ANNUAL_UPDATE_REQUIRED | Set by Junta de Castilla-La Mancha |
| Enrolment fee (secretaría) | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Academic services fee | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Total estimated annual cost | ~800–1,400 EUR | ANNUAL_UPDATE_REQUIRED — CLM fees typically among Spain's lowest |
| Registration for EvAU CLM (domestic) | ANNUAL_UPDATE_REQUIRED | Paid to UCLM, not separately |
| PCE registration (international) | ANNUAL_UPDATE_REQUIRED | Paid to UNED |

Castilla-La Mancha has historically maintained some of Spain's lowest public university tuition rates, often below the national average. Confirm the exact figure at uclm.es before enrolment.

## Scholarships and Financial Aid

- **MEC Beca General:** National scholarship for public university students. Covers tuition and may include a maintenance component. Apply via the MEFP portal.
- **Becas Junta de Castilla-La Mancha:** Regional government scholarships for CLM residents studying at public universities in the region. Check the Junta CLM portal annually.
- **UCLM own grants:** UCLM offers institutional grants and emergency aid for enrolled students. Check uclm.es/becas.
- **ERASMUS+ grants:** Available during mobility periods (typically years 4–5).
- **International students:** PCE/UNED applicants are technically eligible for MEC Beca General under residency and income requirements; in practice, eligibility for most international students is limited.

## Accommodation and Cost of Living

Albacete is a mid-sized Spanish city with a well-established university student community. The cost of living is among the lowest in Spain.

| Category | Estimated monthly cost | Notes |
|---|---|---|
| University residence (Colegios Mayores UCLM) | ANNUAL_UPDATE_REQUIRED | Available — check uclm.es/vida-universitaria |
| Private shared flat (piso compartido) | ~250–450 EUR/month | Very affordable compared to major cities |
| Private studio | ~350–550 EUR/month | ANNUAL_UPDATE_REQUIRED |
| Food (self-catering + canteen) | ~180–300 EUR/month | Low cost of living in Albacete |
| Transport (local bus) | ~15–30 EUR/month | Compact city — often walkable |
| Total monthly estimated budget | ~500–800 EUR | Excluding tuition — very low cost of living |

Albacete is one of Spain's most affordable cities for students. The low cost of living is a significant advantage, particularly for students from outside the region or international PCE students managing tight budgets.

## International Exchange and Mobility Programs

- **Erasmus+:** UCLM has bilateral Erasmus+ agreements with European institutions for health sciences. Exchanges typically occur in years 4–5.
- **SICUE:** Domestic exchange programme for intra-Spanish mobility within Spanish public universities.
- **International partnerships:** UCLM has developed relationships with Latin American universities, which may create research and academic exchange opportunities.
- **International Office:** UCLM operates an international relations office supporting outgoing and incoming mobility at all campuses.

## MIR Preparation and Professional Outcomes

UCLM does not publish a disaggregated MIR pass rate by faculty. Graduates sit the national MIR alongside all other Spanish medical graduates. As the sole public Medicine faculty in Castilla-La Mancha, UCLM trains a significant proportion of the regional medical workforce. Many graduates remain in the region for MIR residency through SESCAM training positions, though they may also compete nationally.

Professional pathways for UCLM graduates:
- MIR specialist training (primary route, national and SESCAM positions)
- Academic medicine within UCLM
- EU practice (automatic recognition under Directive 2005/36/EC)
- General practice via MIR Family Medicine

## Strategic Fit

### Good Fit For

- Candidates with a nota de admisión above 12.8–13.0 (verify nota de corte annually) who are targeting a lower-cost, lower-competition public Medicine option relative to the top national faculties.
- Students attracted to Albacete's very low cost of living — one of the most budget-friendly student environments in Spain.
- CLM residents or students comfortable with the regional university environment and willing to train and potentially work in the Castilla-La Mancha healthcare system.
- International PCE candidates who need a more accessible nota de corte threshold and want minimum living costs.
- Students who value being in a smaller, less intense city environment without sacrificing the public Medicine credential.

### Less Suitable For

- Candidates whose nota de admisión is clearly below 12.5 — UCLM Medicine is still competitive and nota de corte must be verified.
- Students seeking an English-medium programme or bilingual environment — teaching is in Spanish only.
- Candidates who want a university with strong international prestige or highly developed research infrastructure at the faculty level.
- Students requiring a large metropolitan university environment with diverse academic and social offerings.

## Risks and Considerations

1. **Nota de corte verification required:** All nota de corte values in this file are PENDING_CONFIRMATION. Students must verify the current data directly at uclm.es before planning their application.
2. **Regional applicant pool:** UCLM is heavily anchored in the CLM regional EVAU pool. Students from other regions competing via PAU from Madrid or other systems should confirm the portability of their EVAU scores to the CLM admissions process.
3. **Single-campus constraint:** Medicine is only offered in Albacete. Students expecting to access the other UCLM campuses (Ciudad Real, Toledo, Cuenca) for Medicine will find they are in Albacete exclusively for the full six years.
4. **Regional healthcare system:** Clinical training at SESCAM may be less diverse than training in larger metropolitan health systems. The scale of CHUA is adequate for full clinical formation but smaller than, for example, a Madrid or Barcelona tertiary complex.
5. **PCE process:** International PCE students must verify that their CLM EvAU/admissions process correctly handles the PCE nota de admisión equivalent. The CLM system manages admissions directly through UCLM, which may have specific documentation requirements.

## Important Notes

- Medicine at UCLM is offered exclusively on the Albacete campus — not at other UCLM campuses.
- Ponderation coefficients are ANNUAL_UPDATE_REQUIRED and must be confirmed at uclm.es each autumn.
- UCLM's admissions system (preinscripción) is university-managed, not administered by a regional coordinating body as in larger communities. Timelines may differ slightly from the national average.
- No pre-admission deposit is required.

## Key Insight

UCLM Medicine is a lower-profile but fully accredited public Medicine degree with one of Spain's most favourable cost-of-living contexts (Albacete) and tuition rates (Castilla-La Mancha regional public fees). As the only public Medicine faculty in the region, it serves a stable demand base. The nota de corte is estimated to be in the medium-high band — more accessible than top national faculties but still requiring a solid nota de admisión above 12.8. For budget-constrained students or international PCE candidates looking for a realistic entry into Spanish public Medicine, UCLM Albacete is worth careful evaluation.

## Final Takeaway

UCLM Medicine offers a fully accredited, regionally anchored public Medicine education in Albacete — Spain's most affordable major student city. Clinical training is through CHUA and the SESCAM regional network. Teaching is in Spanish only; admission is entirely nota de admisión based; no exam, no interview. Nota de corte is PENDING_CONFIRMATION (verify at uclm.es). For candidates with nota de admisión above 12.8, UCLM is a realistic target that delivers public Medicine at the lowest cost-of-living envelope in Spain.

## Frequently Asked Questions

**Q: How is the nota de admisión calculated for UCLM Medicine?**
A: Nota de admisión = 0.6 × Bachillerato average + 0.4 × EvAU general phase score + (up to 2 specific-phase subjects × coefficient). Base maximum: 10.0000. With specific-phase bonus: 14.0000.

**Q: What is the nota de corte for UCLM Medicine?**
A: For the 2025-2026 intake, the nota de corte was 12.798 for the Albacete campus (source: notasdecorte.es / Castilla-La Mancha — ANNUAL_UPDATE_REQUIRED). Note that UCLM also has a Ciudad Real campus with a 2025-2026 nota de corte of 12.869. Prior-cycle data (2024-25, 2023-24) remains PENDING_CONFIRMATION — verify at uclm.es.

**Q: Is Medicine only available in Albacete?**
A: Yes. UCLM is a multi-campus university, but the Grado en Medicina is offered exclusively on the Albacete campus.

**Q: Which EVAU subjects are most valuable at UCLM?**
A: Biology (0.2), Chemistry (0.2), and Physics (0.2) all carry the maximum coefficient. Prioritise Biology and Chemistry in the specific phase. Coefficients are ANNUAL_UPDATE_REQUIRED — verify at uclm.es.

**Q: Can international students apply via PCE/UNED?**
A: Yes. PCE/UNED applicants construct a nota de admisión equivalent and apply through UCLM's admissions system in the general quota. No separate reserved international quota has been identified at UCLM Medicine.

**Q: What are the tuition fees?**
A: Set annually by the Junta de Castilla-La Mancha. CLM has historically maintained some of Spain's lowest public university fees, estimated broadly at 800–1,400 EUR per year. Confirm the exact figure at uclm.es before enrolment.

**Q: Is the cost of living really lower than other Spanish cities?**
A: Yes. Albacete consistently ranks among Spain's most affordable cities for students. Private shared housing typically costs 250–450 EUR/month — significantly less than Madrid, Barcelona, Valencia, or even Seville.

**Q: Is there an interview or entrance exam at UCLM?**
A: No. Admission is determined exclusively by the nota de admisión. There is no proprietary university exam and no interview.
