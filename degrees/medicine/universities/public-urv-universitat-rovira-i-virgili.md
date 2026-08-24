---
id: urv

type: university
subtype: public

name: Universitat Rovira i Virgili
short_name: URV

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Reus
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
  - id: urv-medicina
    campus: Campus de Ciències de la Salut (Reus)
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
# Universitat Rovira i Virgili

## Overview

The Universitat Rovira i Virgili (URV) is a public research university based in Tarragona, with multiple campuses across the Camp de Tarragona and Terres de l'Ebre regions. Its Grado en Medicina (Grau en Medicina) is delivered on the **Campus de Ciències de la Salut in Reus** — a dedicated health sciences campus that co-locates the Faculty of Medicine with the Hospital Universitari Sant Joan de Reus. The programme is a six-year, 360 ECTS degree, fully verified by ANECA and registered in the RUCT. URV Medicine is distinctive within the Catalan university system for being based in Reus (not in Barcelona or one of the major Catalan metropolitan centres), creating a more intimate academic environment while maintaining full integration with a university hospital clinical network. The programme is taught in Catalan as the primary language of instruction, with Spanish also used, and is part of the broader Catalan PAU (Selectivitat) admissions framework managed through accesuniversitats.gencat.cat.

## Quick Evaluation

| Feature | Detail |
|---|---|
| Seats (plazas) | 60 (ANNUAL_UPDATE_REQUIRED) |
| Nota de tall 2024-25 | PENDING_CONFIRMATION |
| Teaching language(s) | Catalan (primary) / Spanish |
| Annual tuition (approx.) | ANNUAL_UPDATE_REQUIRED — set by Generalitat de Catalunya decree |
| Admission model | Nota d'accés (PAU-based) — no proprietary exam, no interview |
| Clinical exposure | Strong — Hospital Universitari Sant Joan de Reus and network |
| ECTS | 360 |
| Duration | 6 years |

## Key Facts

| Field | Value |
|---|---|
| Degree | Grau en Medicina / Grado en Medicina |
| Campus | Campus de Ciències de la Salut, Reus |
| Seats (plazas ofertadas) | 60 (ANNUAL_UPDATE_REQUIRED) |
| Tuition per year | ANNUAL_UPDATE_REQUIRED |
| Admission model | Score-based (nota d'accés) |
| Proprietary exam | No |
| Interview | No |
| Teaching languages | Catalan (primary), Spanish |
| Regional health system | ICS / SISCAT (Institut Català de la Salut) |
| Admissions platform | accesuniversitats.gencat.cat |
| Admissions contact | urv.cat |

## Program Options

URV offers a single Grau en Medicina programme at the Reus campus. There is no separate English-medium or Spanish-only Medicine track. The primary language of instruction is Catalan, which is standard for public Catalan universities. Spanish is used alongside Catalan in many teaching contexts. No English proficiency test is required for admission. International students applying via PCE/UNED are incorporated into the standard cohort; non-Catalan-speaking students should be aware of the Catalan-language academic environment and take this into account in their preparation.

## Program Structure

The Grau en Medicina at URV spans six academic years with 360 ECTS:

- **Years 1–2 (Basic biomedical sciences):** Anatomy, cell biology and genetics, histology, biochemistry and molecular biology, physiology, biophysics, biostatistics, immunology, microbiology, epidemiology and public health, medical psychology, communication skills in healthcare. Laboratory practicals and early skills training begin from year 1.
- **Years 3–4 (Pathophysiology and clinical sciences):** General and special pathology, pharmacology, radiology, internal medicine, surgery, gynaecology and obstetrics, paediatrics, psychiatry, neurology, dermatology, ophthalmology, ENT. Structured clinical contact begins progressively in year 3 through supervised hospital placements at Sant Joan de Reus.
- **Years 5–6 (Advanced clinical training):** Full clinical rotations across all major specialties within the URV clinical network. Year 6 is the dedicated clinical rotation year. TFG (Treball de Fi de Grau / Trabajo Fin de Grado) is completed in the final year.
- **Elective subjects:** Optional components are available within the degree framework.

Full ECTS breakdown available at urv.cat/medicina.

## Teaching Methodology

URV Medicine employs a hybrid teaching model: structured lectures form the backbone of preclinical years, while Problem-Based Learning (PBL) elements, case-based tutorials, and clinical simulation are progressively integrated from years 2–3. The small cohort size (approximately 60 students per year) enables more personalised teaching and closer faculty-student interaction than is possible in larger Catalan Medicine faculties. The Reus campus health sciences cluster enables sustained contact with clinical staff from the hospital and primary care network from early in the programme. Year 6 is entirely clinical.

## Clinical Training

Clinical training at URV Medicine is centred on:

- **Hospital Universitari Sant Joan de Reus:** The primary university hospital for URV Medicine, located adjacent to the Campus de Ciències de la Salut in Reus. A general and specialty referral hospital serving the Camp de Tarragona area, affiliated with the Institut Català de la Salut (ICS).
- **Hospital Universitari de Tarragona Joan XXIII:** A secondary clinical training centre, a major tertiary hospital in Tarragona city managed under ICS.
- **Hospital del Vendrell and other SISCAT network centres:** Additional rotation sites for specialised and community medicine.
- **Primary care centres (CAPs — Centres d'Atenció Primària):** SISCAT primary care units in the Tarragona / Camp de Tarragona area for family medicine and community health rotations.

The proximity of all clinical training sites and the small cohort size enable high-quality, individualised clinical exposure throughout the programme.

## International Recognition and Opportunities

URV Medicine is registered in the Spanish RUCT and recognised under EU Directive 2005/36/EC, providing automatic EEA-wide professional recognition for graduates. The university is an active Erasmus+ participant with bilateral agreements across European health sciences faculties. URV has developed significant international research partnerships, particularly in oncology, environmental health, and nutrition — research areas in which it has strong national visibility. The SICUE domestic exchange programme is available for intra-Spanish mobility. URV's position within the Catalan university system also provides access to collaborative frameworks with other Catalan universities.

## Admission Model

URV Medicine admission follows the standard Catalan PAU (Selectivitat) model, governed by the **nota d'accés** (equivalent to the nota de admisión nationally):

```
Nota d'accés = 0.6 × Nota mitjana Batxillerat
             + 0.4 × PAU general phase score (fase general)
             + best 2 specific-phase subjects × ponderation coefficient
```

In Catalan PAU terminology, the **nota de tall** (nota de corte) is the lowest nota d'accés admitted in the previous convocatoria.

- **Maximum base score:** 10.0000
- **Maximum nota d'accés (with specific-phase bonus):** 14.0000
- **No proprietary exam, no interview, no English test**

**Specific-phase ponderation coefficients for URV Medicine (ANNUAL_UPDATE_REQUIRED):**

| Subject | Coefficient |
|---|---|
| Biology (Biologia) | 0.2 |
| Chemistry (Química) | 0.2 |
| Physics (Física) | 0.2 |
| Mathematics II | 0.1 |
| Other subjects | ANNUAL_UPDATE_REQUIRED |

Catalan PAU ponderation tables are published annually by the Generalitat de Catalunya via accesuniversitats.gencat.cat. Verify each cycle before PAU registration.

**International students (PCE/UNED route):** International applicants use PCE/UNED or Credencial UE. The Catalan university admissions system (accesuniversitats.gencat.cat) processes PCE applications using the standard nota d'accés equivalent formula. PCE applicants compete in the general quota at URV Medicine.

## Admission Process

### Spanish PAU (Selectivitat) students — Catalan and non-Catalan

1. Catalan students sit the PAU (Selectivitat) administered by the Generalitat de Catalunya. Students from other Spanish regions may apply using their regional PAU score — the Catalan admissions system accepts EVAU from all regions, computing a nota d'accés equivalent.
2. Sit specific-phase subjects: Biology (0.2) and Chemistry (0.2) are the priority subjects. Physics (0.2) is also recommended as a third specific-phase subject.
3. Calculate the nota d'accés and compare against the nota de tall for URV Medicine.
4. Apply through the Catalan pre-enrolment system (preinscripció universitària) via accesuniversitats.gencat.cat in late June / early July.
5. The Catalan system processes applications in descending nota d'accés order and allocates places in multiple assignment rounds (assignació).
6. Confirm enrolment at URV within the stated deadline.

### International PCE/UNED students

1. Register with UNED for PCE examinations (January–March for June sitting).
2. Select five PCE subjects; prioritise Biology, Chemistry, and Physics.
3. Sit PCE exams (May/June ordinaria; September extraordinaria).
4. Obtain PCE certificate and apply through the Catalan pre-enrolment system, presenting the PCE nota d'accés equivalent.
5. If nota d'accés equivalent meets the nota de tall, proceed with enrolment at URV.
6. Complete secondary education diploma homologation if required.

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

**Trend analysis:** URV Medicine has approximately 60 seats — making it one of the smallest public Medicine cohorts in Cataluña and in Spain overall. This small cohort size typically drives a higher nota de tall relative to larger Catalan faculties. Within the Catalan system, URV Medicine historically operates in a high-competitiveness band. Nota de tall data for URV (and all Catalan degrees) is publicly available at accesuniversitats.gencat.cat — students should access this directly for the most recent three cycles. Based on cohort size and institutional positioning, URV Medicine's nota de tall is estimated in the range of 13.0–13.8 in recent cycles — PENDING_CONFIRMATION from primary sources. Verify with the Catalan system before planning your application.

**Practical implication:** With approximately 60 seats, URV Medicine is highly selective. Candidates should target a nota d'accés well above 13.0 (verify the exact nota de tall annually). The small cohort creates meaningful year-on-year nota de tall variability — a candidate's margin above the historical minimum should be substantial.

## Costs and Payment Structure

Public university fees at URV are set by the Generalitat de Catalunya by annual decree. Catalan public university fees have been subject to policy changes over recent years; confirm the current rate before enrolment.

| Fee component | Approximate amount | Notes |
|---|---|---|
| Annual tuition (taxes acadèmiques) | ANNUAL_UPDATE_REQUIRED | Set by Generalitat de Catalunya |
| Enrolment fee (secretaria) | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Academic services fee | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Total estimated annual cost | ~1,400–2,200 EUR | ANNUAL_UPDATE_REQUIRED — Catalan public fees tend to be higher than some other regions |
| Registration for PAU/Selectivitat | ANNUAL_UPDATE_REQUIRED | Paid to Generalitat, not to URV |
| PCE registration (international) | ANNUAL_UPDATE_REQUIRED | Paid to UNED |

Catalan public university tuition has historically been among the higher rates within Spain's public university system, though still dramatically lower than any private Medicine programme. Confirm the exact figure at urv.cat or the Generalitat de Catalunya official fee tables before enrolment.

## Scholarships and Financial Aid

- **MEC Beca General:** National scholarship for public university students. Awarded on academic performance and household income. Apply annually via the MEFP portal.
- **Beques Generalitat de Catalunya (AGAUR):** The Catalan government agency AGAUR administers a range of scholarships for Catalan university students, including mobility grants and complementary aid. Check the AGAUR portal annually.
- **URV own grants:** URV administers institutional grants and emergency support for enrolled students. Check urv.cat/beques.
- **ERASMUS+ grants:** Available during mobility periods (typically years 4–5). Amounts vary by destination.
- **International students:** PCE/UNED applicants may qualify for MEC Beca General under specific residency and income conditions. Most international students will not qualify for Catalan-specific regional scholarships.

## Accommodation and Cost of Living

Reus is a mid-sized city in the Camp de Tarragona, approximately 10 km from Tarragona city and 100 km from Barcelona. The cost of living is moderate by Catalan standards and significantly lower than Barcelona.

| Category | Estimated monthly cost | Notes |
|---|---|---|
| University residence (Residència URV, if available) | ANNUAL_UPDATE_REQUIRED | Limited availability — check urv.cat |
| Private shared flat in Reus | ~300–500 EUR/month | Affordable relative to Barcelona |
| Private studio in Reus | ~450–700 EUR/month | ANNUAL_UPDATE_REQUIRED |
| Food (self-catering + canteen) | ~200–350 EUR/month | University canteen available |
| Transport (local / bus to Tarragona) | ~20–50 EUR/month | Good regional connections |
| Total monthly estimated budget | ~550–900 EUR | Excluding tuition |

Reus offers a pleasant mid-sized city environment with easy access to the Costa Daurada (Mediterranean coast) and good rail connections to Tarragona and Barcelona. The cost of living is substantially lower than Barcelona, making URV an attractive option for budget-conscious students within the Catalan system.

## International Exchange and Mobility Programs

- **Erasmus+:** URV has bilateral Erasmus+ agreements with European universities for Medicine and health sciences. Exchanges typically occur in years 4–5.
- **SICUE:** Domestic exchange programme for intra-Spanish mobility.
- **International research partnerships:** URV has active international research collaborations, particularly in oncology, nutrition, and environmental health. Students interested in research can engage with the Institut d'Investigació Sanitària Pere Virgili (IISPV), the hospital-affiliated research institute.
- **IISPV:** The Institut d'Investigació Sanitària Pere Virgili (linked to Hospital Universitari Sant Joan de Reus) provides research infrastructure accessible to advanced students.

## MIR Preparation and Professional Outcomes

URV does not publish a disaggregated MIR pass rate by faculty. Graduates sit the national MIR examination alongside all other Spanish medical graduates. The small cohort size (approximately 60 per year) means that URV Medicine produces a relatively small annual cohort of graduates; personalised academic support and close faculty relationships are often cited as advantages. URV's clinical training network (Sant Joan de Reus + Joan XXIII Tarragona) provides solid exposure to a wide range of specialties.

Professional pathways for URV graduates:
- MIR specialist training (primary route, competing nationally)
- Research and academic medicine (IISPV, URV doctoral programmes)
- EU practice (automatic recognition under Directive 2005/36/EC)
- General practice via MIR Family Medicine

## Strategic Fit

### Good Fit For

- Candidates with a nota d'accés well above 13.0 (verify nota de tall annually at accesuniversitats.gencat.cat) who want a small-cohort, personalised Catalan public Medicine degree.
- Students comfortable with Catalan as the primary language of instruction and the bilingual Catalan/Spanish academic environment.
- Students attracted to a university hospital-integrated clinical environment in a smaller city setting (Reus) with lower cost of living than Barcelona.
- International PCE candidates with a nota d'accés equivalent above 13.0 who are comfortable with the Catalan language context.
- Students interested in biomedical research opportunities through IISPV and URV's research infrastructure.

### Less Suitable For

- Candidates whose nota d'accés is below 13.0 — URV Medicine has approximately 60 seats, making it very competitive.
- Students who are not comfortable with Catalan as the primary language of instruction; while Spanish is also used, Catalan predominates in many academic contexts at Catalan public universities.
- Candidates requiring English-medium instruction — no English track is available.
- Students who prefer a very large university with broad programme diversity and metropolitan campus life (Reus is a smaller city environment).

## Risks and Considerations

1. **Nota de tall data gap:** Nota de tall values for URV Medicine are PENDING_CONFIRMATION in this file. Historical nota de tall data is publicly available at accesuniversitats.gencat.cat — students must access this directly before planning their application.
2. **Very small cohort:** With approximately 60 seats, URV Medicine has one of Spain's smallest public Medicine cohorts. Year-on-year nota de tall variability can be significant. Candidates should build a substantial margin above the historical minimum.
3. **Catalan language requirement (practical):** While there is no formal Catalan language admission requirement, the primary language of instruction is Catalan. Non-Catalan-speaking students (including international PCE candidates) should plan for language adaptation in the first year.
4. **Catalan PAU system for non-Catalan applicants:** Students from other Spanish regions who want to apply via URV must ensure their regional PAU results are accepted and correctly computed by the Catalan preinscripció system. Verify with accesuniversitats.gencat.cat.
5. **Higher Catalan public tuition:** Catalan public university fees have historically been among Spain's highest (still dramatically lower than private). Confirm the current rate before committing.

## Important Notes

- URV Medicine is taught at the Reus Campus de Ciències de la Salut — not at the main URV campus in Tarragona.
- The programme is officially designated as "Grau en Medicina" in Catalan; Spanish equivalent: "Grado en Medicina."
- Catalan PAU ponderation tables are published annually by the Generalitat de Catalunya and must be verified at accesuniversitats.gencat.cat before each EVAU/PAU registration cycle.
- Nota de tall data for all Catalan degrees is published at accesuniversitats.gencat.cat — this is the authoritative source for URV Medicine nota de tall history.
- No pre-admission deposit is required at URV.

## Key Insight

URV Medicine is a small, hospital-integrated public Medicine programme in Reus with approximately 60 seats per year — one of Spain's smallest Medicine cohorts. This creates a personalised academic environment and strong clinical integration with Hospital Universitari Sant Joan de Reus, but also means the nota de tall is high and year-on-year variability is significant. For candidates who are firmly above the nota de tall threshold (expected to be above 13.0 in recent cycles), URV offers an excellent combination of small-cohort quality, solid clinical training, research access through IISPV, and lower cost of living than Barcelona. The Catalan language environment is a factor to assess carefully for non-Catalan-speaking applicants.

## Final Takeaway

URV Medicine is a focused, high-quality, small-cohort public Medicine programme delivered in Reus (Tarragona), Cataluña. Clinical training is centred on Hospital Universitari Sant Joan de Reus. Instruction is primarily in Catalan, with Spanish also used. Approximately 60 seats per year drives a high nota de tall. Admission is entirely nota d'accés based — no exam, no interview. Nota de tall is PENDING_CONFIRMATION (verify at accesuniversitats.gencat.cat). For candidates with nota d'accés well above 13.0 who are comfortable with the Catalan academic environment, URV represents a strong-value public Medicine option within the Catalan system.

## Frequently Asked Questions

**Q: How is the nota d'accés calculated for URV Medicine?**
A: Nota d'accés = 0.6 × Batxillerat average + 0.4 × PAU general phase score + (up to 2 specific-phase subjects × ponderation coefficient). Base maximum: 10.0000. With specific-phase bonus: 14.0000.

**Q: What is the nota de tall for URV Medicine?**
A: PENDING_CONFIRMATION for all recent cycles in this file. The authoritative source for URV Medicine nota de tall history is accesuniversitats.gencat.cat — access this directly before planning your application.

**Q: Where is URV Medicine delivered?**
A: At the Campus de Ciències de la Salut in Reus — adjacent to Hospital Universitari Sant Joan de Reus. This is not at URV's main campus in Tarragona.

**Q: Is teaching in Catalan or Spanish?**
A: Catalan is the primary language of instruction at URV, as at all Catalan public universities. Spanish is also used in many contexts. Non-Catalan speakers should plan for language adaptation. No English-medium track is available.

**Q: Which PAU/Selectivitat subjects are most valuable at URV?**
A: Biology (0.2), Chemistry (0.2), and Physics (0.2) all carry the maximum coefficient. Prioritise Biology and Chemistry in the specific phase. Coefficients are ANNUAL_UPDATE_REQUIRED — verify at accesuniversitats.gencat.cat.

**Q: Can international students apply via PCE/UNED?**
A: Yes. PCE/UNED applicants construct a nota d'accés equivalent and apply through the Catalan preinscripció system (accesuniversitats.gencat.cat). They compete in the general quota.

**Q: What are the tuition fees?**
A: Set annually by the Generalitat de Catalunya. Catalan public university fees are typically among Spain's higher public rates (still far below any private programme) — estimated in the range of 1,400–2,200 EUR per year. Confirm at urv.cat or the Generalitat de Catalunya fee tables.

**Q: Is there an interview or entrance exam?**
A: No. Admission is determined exclusively by the nota d'accés. No proprietary exam and no interview.
