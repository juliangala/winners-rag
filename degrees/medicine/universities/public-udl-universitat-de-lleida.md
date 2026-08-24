---
id: udl

type: university
subtype: public

name: Universitat de Lleida
short_name: UdL

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Lleida
  region: Cataluña
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - high_competitiveness
  - strong_clinical_exposure
  - bilingual_program

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
  level: high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: 60 # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
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
    - intake_year: 2022-2023
      round: convocatoria_ordinaria
      score: PENDING_CONFIRMATION
      score_type: nota_de_admision
      notes: NULL

international_profile:
  international_students_percentage: PENDING_CONFIRMATION
  international_nationalities: []

programs:
  - id: udl-medicina
    campus: Campus de Ciències de la Salut (Lleida)
    modality: standard
    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - high_competitiveness
      - bilingual_program
    teaching_languages:
      - Catalan
      - Spanish
    regional_language_possible: true
    regional_language: Catalan
    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL
    seats: 60 # ANNUAL_UPDATE_REQUIRED
    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 60 # ANNUAL_UPDATE_REQUIRED
      applicants_per_seat: PENDING_CONFIRMATION
      last_admitted_scores:
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
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED — verify at accesuniversitats.gencat.cat
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
# Universitat de Lleida

## Overview

The Universitat de Lleida (UdL) is a public university located in Lleida, the capital of the westernmost province of Cataluña, bordering Aragón. Its Grau en Medicina (Grado en Medicina) is delivered at the Faculty of Medicine (Facultat de Medicina) on the Campus de Ciències de la Salut, co-located with the Hospital Universitari Arnau de Vilanova de Lleida — the principal university hospital serving the Lleida and Alt Pirineu health regions. The programme is a six-year, 360 ECTS degree, fully verified by ANECA and registered in the RUCT. UdL Medicine is one of the smallest-cohort public Medicine programmes in Spain (approximately 60 seats), which creates a highly personalised academic environment with close faculty-student ratios and strong early clinical integration. Teaching is conducted primarily in Catalan, with Spanish also used throughout. The programme is part of the Catalan PAU (Selectivitat) admissions framework, managed through accesuniversitats.gencat.cat.

## Quick Evaluation

| Feature | Detail |
|---|---|
| Seats (plazas) | 60 (ANNUAL_UPDATE_REQUIRED) |
| Nota de tall 2024-25 | PENDING_CONFIRMATION |
| Teaching language(s) | Catalan (primary) / Spanish |
| Annual tuition (approx.) | ANNUAL_UPDATE_REQUIRED — set by Generalitat de Catalunya decree |
| Admission model | Nota d'accés (PAU-based) — no proprietary exam, no interview |
| Clinical exposure | Strong — Hospital Universitari Arnau de Vilanova and network |
| ECTS | 360 |
| Duration | 6 years |

## Key Facts

| Field | Value |
|---|---|
| Degree | Grau en Medicina / Grado en Medicina |
| Campus | Campus de Ciències de la Salut, Lleida |
| Seats (plazas ofertadas) | 60 (ANNUAL_UPDATE_REQUIRED) |
| Tuition per year | ANNUAL_UPDATE_REQUIRED |
| Admission model | Score-based (nota d'accés) |
| Proprietary exam | No |
| Interview | No |
| Teaching languages | Catalan (primary), Spanish |
| Regional health system | ICS / SISCAT (Institut Català de la Salut) |
| Admissions platform | accesuniversitats.gencat.cat |
| Admissions contact | udl.cat |

## Program Options

UdL offers a single Grau en Medicina programme at the Lleida Campus de Ciències de la Salut. There is no separate English-medium or Spanish-only Medicine track. Catalan is the primary language of instruction, consistent with all Catalan public universities. Spanish is used alongside Catalan in many teaching and clinical contexts. No English proficiency test is required for admission. International PCE/UNED students are integrated into the standard cohort.

## Program Structure

The Grau en Medicina at UdL spans six academic years with 360 ECTS:

- **Years 1–2 (Basic biomedical sciences):** Anatomy (locomotor, visceral, neuroanatomy), histology and embryology, biochemistry and molecular biology, cell biology and genetics, physiology, biophysics, biostatistics, epidemiology and public health, medical psychology, communication skills. Clinical simulation and early skills labs from year 1 via the hospital-campus integration.
- **Years 3–4 (Clinical sciences and pathophysiology):** General and systematic pathology, pharmacology, radiology and medical imaging, internal medicine, surgery, gynaecology and obstetrics, paediatrics, psychiatry, neurology, dermatology, ophthalmology, ENT, geriatrics. Progressive supervised clinical exposure from year 3 at Hospital Arnau de Vilanova.
- **Years 5–6 (Advanced clinical training):** Comprehensive clinical rotations across all major specialties within the UdL clinical network. Year 6 is the full-time clinical rotation year. TFG (Treball de Fi de Grau / Trabajo Fin de Grado) in the final year.
- **Electives:** Optional subjects and extracurricular clinical placements within the degree framework.

Full ECTS distribution available at udl.cat/medicina.

## Teaching Methodology

UdL Medicine employs a hybrid pedagogical model: structured lectures for the basic sciences, complemented by laboratory practicals, seminars, clinical case sessions, and PBL (Problem-Based Learning) elements integrated progressively from year 2. The small cohort (approximately 60 students per year) is the central feature of the UdL learning environment: class sizes are small, faculty-student relationships are close, and students receive more individual attention than is typical in larger Medicine programmes. Clinical simulation facilities on campus enable early skills training. The hospital-campus integration at Arnau de Vilanova enables supervised clinical contact beginning in year 3, with year 6 fully devoted to rotations.

## Clinical Training

Clinical training at UdL Medicine is centred on:

- **Hospital Universitari Arnau de Vilanova de Lleida (HUAV):** The primary university hospital for UdL Medicine, located adjacent to the Faculty on the Campus de Ciències de la Salut. A tertiary referral hospital for the Lleida and Alta Ribagorça health regions, managed under the Institut Català de la Salut (ICS). HUAV offers specialised services including haematology, oncology, cardiology, surgery, neurology, and neonatal care.
- **Hospital de Santa Maria (Lleida):** Secondary clinical training site managed within the SISCAT network, focusing on rehabilitation, geriatrics, and community health.
- **Primary care centres (CAPs):** SISCAT primary care units in the Lleida health area for family medicine and community health rotations.
- **Hospital Comarcal del Pallars (Tremp):** Rural and mountain medicine rotations — a distinctive element of UdL's clinical training reflecting its geographic positioning at the interface of Cataluña and the Pyrenees.

The geographic context of Lleida gives UdL Medicine students exposure to both standard urban hospital medicine and rural/mountain healthcare contexts, which is unique among Catalan Medicine faculties.

## International Recognition and Opportunities

UdL Medicine is registered in the Spanish RUCT and recognised under EU Directive 2005/36/EC, providing automatic EEA-wide professional recognition for graduates. UdL participates in Erasmus+ with bilateral agreements for health sciences students. The SICUE domestic exchange programme is available for intra-Spanish mobility. UdL has research infrastructure through the Institut de Recerca Biomèdica de Lleida (IRBLleida), which is affiliated with HUAV and accessible to students interested in biomedical research during their training. IRBLleida focuses on oncology, immunology, cardiovascular disease, and neuroscience.

## Admission Model

UdL Medicine admission follows the standard Catalan PAU (Selectivitat) model, governed by the **nota d'accés**:

```
Nota d'accés = 0.6 × Nota mitjana Batxillerat
             + 0.4 × PAU general phase score (fase general)
             + best 2 specific-phase subjects × ponderation coefficient
```

The **nota de tall** (nota de corte) is the lowest nota d'accés accepted in the previous convocatoria.

- **Maximum base score:** 10.0000
- **Maximum nota d'accés (with specific-phase bonus):** 14.0000
- **No proprietary exam, no interview, no English test**

**Specific-phase ponderation coefficients for UdL Medicine (ANNUAL_UPDATE_REQUIRED):**

| Subject | Coefficient |
|---|---|
| Biology (Biologia) | 0.2 |
| Chemistry (Química) | 0.2 |
| Physics (Física) | 0.2 |
| Mathematics II | 0.1 |
| Other subjects | ANNUAL_UPDATE_REQUIRED |

Catalan PAU ponderation tables are published annually by the Generalitat de Catalunya via accesuniversitats.gencat.cat. Verify each cycle before PAU registration.

**International students (PCE/UNED route):** International applicants use PCE/UNED or Credencial UE to construct a nota d'accés equivalent. The Catalan admissions system (accesuniversitats.gencat.cat) processes PCE applications using the standard nota d'accés formula. PCE applicants compete in the general quota at UdL Medicine.

## Admission Process

### Spanish PAU (Selectivitat) students — Catalan and non-Catalan

1. Catalan students sit the PAU (Selectivitat). Non-Catalan students apply using their regional PAU score — the Catalan system accepts all regional EVAU results and computes a nota d'accés equivalent.
2. Prioritise Biology (0.2) and Chemistry (0.2) in the specific phase. Physics (0.2) is strongly recommended as a third specific-phase subject.
3. Calculate nota d'accés and compare against UdL Medicine's nota de tall.
4. Apply through the Catalan preinscripció system (accesuniversitats.gencat.cat) in late June / early July.
5. The system allocates places in descending nota d'accés order across multiple rounds.
6. Confirm enrolment at UdL within the stated deadline.

### International PCE/UNED students

1. Register with UNED for PCE examinations (January–March for June sitting).
2. Select five PCE subjects; prioritise Biology, Chemistry, and Physics.
3. Sit PCE exams (May/June ordinaria; September extraordinaria).
4. Obtain PCE certificate; calculate nota d'accés equivalent.
5. Apply through the Catalan preinscripció system with PCE documentation.
6. If nota d'accés equivalent meets the nota de tall, proceed with enrolment.
7. Complete secondary education diploma homologation if required.

## Admission Timeline

| Phase | Approximate dates | Notes |
|---|---|---|
| Catalan PAU (Selectivitat) — ordinaria | June (ANNUAL_UPDATE_REQUIRED) | Generalitat de Catalunya |
| Preinscripció universitària application | Late June / early July (ANNUAL_UPDATE_REQUIRED) | accesuniversitats.gencat.cat |
| Ordinaria assignment results | July (ANNUAL_UPDATE_REQUIRED) | Multiple rounds of assignment |
| Enrolment confirmation | July–August (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| PAU extraordinaria | September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| Extraordinaria results / enrolment | September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| Academic year start | September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| PCE registration (UNED) | January–March (ANNUAL_UPDATE_REQUIRED) | For international applicants |
| PCE exams | May–June / September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |

## Admission Score Distribution

### Nota de tall (nota de corte) history

| Intake year | Round | Nota de tall | Source |
|---|---|---|---|
| 2024-2025 | Convocatoria ordinaria | PENDING_CONFIRMATION | PENDING_CONFIRMATION |
| 2023-2024 | Convocatoria ordinaria | PENDING_CONFIRMATION | PENDING_CONFIRMATION |
| 2022-2023 | Convocatoria ordinaria | PENDING_CONFIRMATION | PENDING_CONFIRMATION |

**Trend analysis:** UdL Medicine has approximately 60 seats — one of the smallest public Medicine cohorts in Spain. This small cohort size, combined with the national demand for Medicine places in Cataluña, typically generates a nota de tall in the high-competitiveness range. Historical nota de tall data for UdL (and all Catalan degrees) is publicly available at accesuniversitats.gencat.cat — students should access this directly for verified historical data. Based on cohort size and institutional positioning within the Catalan system, UdL Medicine's nota de tall is estimated in the range of 13.0–13.8 in recent cycles — PENDING_CONFIRMATION from primary sources. Year-on-year variability with a 60-seat cohort can be significant; candidates must build a substantial margin above the historical minimum.

**Practical implication:** UdL Medicine is a high-competitiveness target. Candidates should target a nota d'accés well above 13.0 (verify the exact nota de tall annually). The small cohort means a single exceptional candidate can shift the floor slightly, making year-on-year prediction uncertain.

## Costs and Payment Structure

Public university fees at UdL are set by the Generalitat de Catalunya by annual decree.

| Fee component | Approximate amount | Notes |
|---|---|---|
| Annual tuition (taxes acadèmiques) | ANNUAL_UPDATE_REQUIRED | Set by Generalitat de Catalunya |
| Enrolment fee (secretaria) | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Academic services fee | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Total estimated annual cost | ~1,400–2,200 EUR | ANNUAL_UPDATE_REQUIRED — Catalan public fees range |
| Registration for PAU/Selectivitat | ANNUAL_UPDATE_REQUIRED | Paid to Generalitat, not to UdL |
| PCE registration (international) | ANNUAL_UPDATE_REQUIRED | Paid to UNED |

Catalan public university tuition is among Spain's higher public rates, but still dramatically below any private Medicine programme. Confirm the exact figure at udl.cat or the Generalitat de Catalunya official fee tables before enrolment.

## Scholarships and Financial Aid

- **MEC Beca General:** National scholarship for public university students. Awarded on academic performance and household income. Apply via the MEFP portal annually.
- **Beques Generalitat de Catalunya (AGAUR):** Catalan government scholarships administered by AGAUR for Catalan university students. Check the AGAUR portal annually.
- **UdL own grants:** UdL administers institutional grants and emergency aid for enrolled students. Check udl.cat/beques.
- **ERASMUS+ grants:** Available during mobility periods (typically years 4–5).
- **International students:** PCE/UNED applicants may qualify for MEC Beca General under specific residency and income conditions. Most international students will not qualify for Catalan-specific regional scholarships.

## Accommodation and Cost of Living

Lleida is a mid-sized Catalan city with a strong university culture and one of Spain's most affordable cost-of-living profiles. It is well-connected by high-speed rail (AVE) to both Barcelona (1 hour) and Madrid (2.5 hours).

| Category | Estimated monthly cost | Notes |
|---|---|---|
| University residence (Residències UdL) | ANNUAL_UPDATE_REQUIRED | Available — check udl.cat |
| Private shared flat in Lleida | ~250–450 EUR/month | Among Cataluña's most affordable cities |
| Private studio in Lleida | ~400–650 EUR/month | ANNUAL_UPDATE_REQUIRED |
| Food (self-catering + canteen) | ~180–300 EUR/month | University canteen available |
| Transport (local bus / train to Barcelona) | ~20–40 EUR/month local | AVE to Barcelona ~1 hour |
| Total monthly estimated budget | ~480–800 EUR | Excluding tuition — very competitive for Cataluña |

Lleida offers the Catalan cultural and linguistic environment at a cost of living significantly lower than Barcelona, Girona, or Tarragona. The AVE connection provides easy access to Barcelona for social and cultural activities. For Catalan-system students seeking a lower cost of living within Cataluña, Lleida is one of the most budget-friendly options.

## International Exchange and Mobility Programs

- **Erasmus+:** UdL has bilateral Erasmus+ agreements with European universities for Medicine and health sciences. Exchanges typically occur in years 4–5.
- **SICUE:** Domestic exchange programme for intra-Spanish mobility.
- **IRBLleida research engagement:** Students can engage with the Institut de Recerca Biomèdica de Lleida (IRBLleida), which is embedded in HUAV and focuses on oncology, cardiovascular disease, immunology, and neuroscience.
- **Rural medicine exposure:** UdL's geographic position (Lleida, bordering the Pyrenees) creates opportunities for rural medicine rotations, including at Hospital Comarcal del Pallars, which is unusual within Spanish public Medicine programmes.

## MIR Preparation and Professional Outcomes

UdL does not publish a disaggregated MIR pass rate by faculty. Graduates sit the national MIR examination alongside all other Spanish medical graduates. The small cohort (approximately 60 per year) is frequently cited as a structural advantage for academic performance: students benefit from small class sizes, close faculty relationships, and intensive clinical supervision. UdL graduates have access to MIR training positions across Spain and, via EU recognition, across the EEA.

Professional pathways for UdL graduates:
- MIR specialist training (primary route, competing nationally)
- Research and academic medicine (IRBLleida, UdL doctoral programmes)
- EU practice (automatic recognition under Directive 2005/36/EC)
- General practice via MIR Family Medicine
- Rural and mountain medicine (unique positioning of UdL's geographic context)

## Strategic Fit

### Good Fit For

- Candidates with a nota d'accés well above 13.0 (verify nota de tall at accesuniversitats.gencat.cat annually) who value a small-cohort, personalised Catalan public Medicine degree.
- Students comfortable with Catalan as the primary language of instruction and the bilingual Catalan/Spanish academic environment.
- Budget-conscious students within the Catalan system: Lleida offers Catalan public university education at one of Cataluña's lowest cost-of-living settings.
- International PCE candidates with nota d'accés equivalent above 13.0 who are comfortable with the Catalan language context and want lower living costs than Barcelona.
- Students interested in biomedical research through IRBLleida.
- Students interested in exposure to rural and mountain medicine contexts (unique to UdL's geographic positioning).

### Less Suitable For

- Candidates whose nota d'accés is below 13.0 — UdL Medicine has approximately 60 seats, making it very competitive.
- Students who are not comfortable with Catalan as the primary language of instruction.
- Candidates requiring English-medium instruction — no English track is available.
- Students who want a large, metropolitan university experience with extensive campus facilities and urban lifestyle.

## Risks and Considerations

1. **Nota de tall data gap:** Nota de tall values for UdL Medicine are PENDING_CONFIRMATION in this file. Historical data is publicly available at accesuniversitats.gencat.cat — students must verify directly.
2. **Very small cohort:** With approximately 60 seats, year-on-year nota de tall variability can be significant. Candidates should plan with a substantial margin above the historical minimum.
3. **Catalan language (practical):** Primary instruction is in Catalan. Non-Catalan-speaking students, including international PCE applicants, should plan for language adaptation from the start of the programme.
4. **Non-Catalan PAU applicants:** Students from other Spanish regions must verify their EVAU is correctly processed by the Catalan preinscripció system.
5. **Catalan public tuition:** Among Spain's higher public rates, though still far below private. Confirm the current figure before committing.
6. **Smaller regional clinical network:** HUAV and the Lleida SISCAT network are smaller than the mega-hospital complexes of Barcelona. Clinical exposure is solid and diverse, but the scale is smaller than a major metropolitan centre.

## Important Notes

- UdL Medicine is taught at the Campus de Ciències de la Salut in Lleida — co-located with Hospital Universitari Arnau de Vilanova.
- The programme is officially designated as "Grau en Medicina" in Catalan; Spanish equivalent: "Grado en Medicina."
- PAU ponderation tables are published annually by the Generalitat de Catalunya at accesuniversitats.gencat.cat — verify each cycle before registration.
- Nota de tall data for all Catalan degrees is published at accesuniversitats.gencat.cat — this is the authoritative source.
- No pre-admission deposit is required at UdL.

## Key Insight

UdL Medicine is a focused, small-cohort (approximately 60 seats), hospital-integrated public Medicine programme in Lleida — one of Cataluña's most budget-friendly university cities. The personalised academic environment, strong clinical integration with Hospital Arnau de Vilanova, access to IRBLleida research infrastructure, and unique exposure to rural medicine in the Pyrenean context make UdL a distinctive option within the Catalan Medicine landscape. The nota de tall is high (expected above 13.0 in recent cycles), and the small cohort creates meaningful year-on-year variability. For candidates who can clear the nota de tall and are comfortable with the Catalan academic environment, UdL offers an excellent quality-to-cost ratio within Spain's public Medicine system.

## Final Takeaway

UdL Medicine is a small, personalised, hospital-integrated public Medicine programme in Lleida, Cataluña. Clinical training is centred on Hospital Universitari Arnau de Vilanova. Instruction is primarily in Catalan, with Spanish also used. Approximately 60 seats per year drives a high nota de tall. Admission is entirely nota d'accés based — no exam, no interview. Nota de tall is PENDING_CONFIRMATION (verify at accesuniversitats.gencat.cat). For candidates with nota d'accés well above 13.0 who are comfortable with the Catalan academic context and want lower living costs than most Catalan cities, UdL is a high-value public Medicine option.

## Frequently Asked Questions

**Q: How is the nota d'accés calculated for UdL Medicine?**
A: Nota d'accés = 0.6 × Batxillerat average + 0.4 × PAU general phase score + (up to 2 specific-phase subjects × ponderation coefficient). Base maximum: 10.0000. With specific-phase bonus: 14.0000.

**Q: What is the nota de tall for UdL Medicine?**
A: PENDING_CONFIRMATION for all recent cycles in this file. The authoritative source for UdL Medicine nota de tall history is accesuniversitats.gencat.cat — access this directly before planning your application.

**Q: Where is UdL Medicine delivered?**
A: At the Campus de Ciències de la Salut in Lleida, co-located with Hospital Universitari Arnau de Vilanova de Lleida.

**Q: Is teaching in Catalan or Spanish?**
A: Catalan is the primary language of instruction at UdL, consistent with all Catalan public universities. Spanish is also used in many academic and clinical contexts. Non-Catalan speakers should plan for language adaptation. No English-medium track is available.

**Q: Which PAU/Selectivitat subjects are most valuable at UdL?**
A: Biology (0.2), Chemistry (0.2), and Physics (0.2) all carry the maximum coefficient. Prioritise Biology and Chemistry in the specific phase. Coefficients are ANNUAL_UPDATE_REQUIRED — verify at accesuniversitats.gencat.cat.

**Q: Can international students apply via PCE/UNED?**
A: Yes. PCE/UNED applicants construct a nota d'accés equivalent and apply through the Catalan preinscripció system (accesuniversitats.gencat.cat). They compete in the general quota.

**Q: What are the tuition fees?**
A: Set annually by the Generalitat de Catalunya. Catalan public university fees are among Spain's higher public rates — estimated at 1,400–2,200 EUR per year for Health Sciences. Confirm the exact figure at udl.cat or the Generalitat de Catalunya fee tables.

**Q: Is Lleida cheaper to live in than Barcelona?**
A: Yes, significantly. Lleida is one of Cataluña's most affordable university cities. Shared housing typically costs 250–450 EUR/month — compared to 500–900 EUR or more in Barcelona. The AVE high-speed train connects Lleida to Barcelona in approximately 1 hour.

**Q: Is there an interview or entrance exam?**
A: No. Admission is determined exclusively by the nota d'accés. No proprietary exam and no interview.
