---
id: uhu

type: university
subtype: public

name: Universidad de Huelva
short_name: UHU

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Huelva
  region: Andalucía
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - medium_competitiveness

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
  seats: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
    - intake_year: 2025-2026
      round: convocatoria_ordinaria
      score: 13.063 # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: "Source: notasdecorte.es"
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
  - id: uhu-medicina
    campus: Campus El Carmen — Facultad de Ciencias de la Salud (UHU), Huelva
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
          score: 13.063 # ANNUAL_UPDATE_REQUIRED
          score_type: nota_de_admision
          notes: NULL
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
          score: 13.063 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: "notasdecorte.es / Junta de Andalucía DUA"
        - intake_year: 2024-2025
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: "Distrito Único Andaluz (DUA) — ANNUAL_UPDATE_REQUIRED"
        - intake_year: 2023-2024
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: "Distrito Único Andaluz (DUA) — ANNUAL_UPDATE_REQUIRED"
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
              notes: 40% of the nota de admisión. Maximum combined base score 10.0000.
            - component: evau_specific_phase_bonus
              enabled: true
              role: bonus_only
              maximum_bonus: 4.0
              grade_source: evau_fase_especifica
              notes: Best 2 eligible subjects × ponderation coefficient (0.1 or 0.2). Max nota 14.0000. Coefficients set annually by Junta de Andalucía.
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED
                Chemistry:      0.2 # ANNUAL_UPDATE_REQUIRED
                Physics:        0.2 # ANNUAL_UPDATE_REQUIRED
                Mathematics_II: 0.2 # ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---

# Universidad de Huelva (UHU) — Grado en Medicina

## Overview

The Universidad de Huelva (UHU) is a public university founded in 1993, located in Huelva, a coastal industrial and port city in western Andalucía near the Portuguese border. Its Grado en Medicina is among the most recently established public medicine programmes in Spain, launched approximately in 2020-2021 as part of the Junta de Andalucía's expansion of regional medical education capacity. The programme is delivered through the Facultad de Ciencias de la Salud on the Campus El Carmen.

Admission to Medicine at UHU is governed by the **Distrito Único Andaluz (DUA)**, the centralised admissions system of the Junta de Andalucía. There is no proprietary entrance exam, no interview, and no language test requirement beyond standard Spanish state access conditions. The process is purely score-driven, based on the nota de admisión calculated from Bachillerato grades and EVAU performance.

The principal affiliated teaching hospital is the Hospital Juan Ramón Jiménez, the main public hospital in the province of Huelva. As one of the newest Andalusian medical faculties, UHU's Medicine programme is still building its clinical infrastructure and accumulating the track record necessary to assess MIR outcomes systematically.

The nota de corte for Medicine at UHU in 2025-2026 was 13.063, the lowest among the four universities in this group and one of the more accessible public medicine thresholds in Spain by score. It remains firmly in the medium-high competitiveness band.

## Quick Evaluation

- Admission model: nota de admisión (EVAU formula) — no proprietary exam, no interview
- Seats: PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED)
- Nota de corte 2025-2026: 13.063
- Prior year notas de corte: PENDING_CONFIRMATION
- Competitiveness level: medium_high
- Tuition (approx. first year): ~757 EUR (ANNUAL_UPDATE_REQUIRED)
- Teaching language: Spanish
- Clinical training begins: Year 3 (progressively expanding)
- WFME accreditation: PENDING_CONFIRMATION
- EU Directive qualification: Yes — automatic professional recognition in EU countries
- International access: via PCE/UNED or Credencial UE

## Key Facts

| Feature | Detail |
|---|---|
| University | Universidad de Huelva (UHU) |
| City | Huelva, Andalucía |
| Degree | Grado en Medicina |
| Duration | 6 years |
| ECTS | 360 |
| Annual seats | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2025-2026 | 13.063 (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2024-2025 | PENDING_CONFIRMATION |
| Nota de corte 2023-2024 | PENDING_CONFIRMATION |
| Tuition (approx. first year) | ~757 EUR (ANNUAL_UPDATE_REQUIRED) |
| Teaching language | Spanish |
| Admission route | Nota de admisión (EVAU formula) |
| Admissions system | Distrito Único Andaluz (DUA) — Junta de Andalucía |
| Proprietary exam | No |
| Interview | No |
| Main teaching hospital | Hospital Juan Ramón Jiménez |

## Program Options

UHU offers a single Grado en Medicina programme, delivered entirely in Spanish on the main Huelva campus. There is no bilingual track, no English-medium option, no distance-learning variant, and no parallel international programme. All students follow a unified six-year curriculum.

The programme is accessible via the DUA portal (Junta de Andalucía) for Spanish EVAU candidates and via PCE/UNED or Credencial UE for international students. UHU's Medicine programme is one of three newly created Andalusian medicine faculties (alongside UAL and UJAEN), all launched in response to regional demand for expanded medical education capacity.

## Program Structure

The Grado en Medicina at UHU follows the standard Spanish public medical degree structure across 6 years (360 ECTS):

| Year | Main focus |
|---|---|
| Year 1 | Foundational biomedical sciences: anatomy, physiology, biochemistry, cell biology, histology |
| Year 2 | Pathophysiology, pharmacology, microbiology, immunology, genetics |
| Year 3 | Introduction to clinical medicine; first supervised hospital placements begin |
| Year 4 | Core clinical disciplines: internal medicine, surgery, paediatrics, obstetrics and gynaecology |
| Year 5 | Advanced clinical rotations across medical and surgical specialities |
| Year 6 | Rotatorio clínico (full-year supervised clinical rotation across departments and primary care) + TFG |

Each academic year comprises approximately 60 ECTS. The Year 6 rotatorio clínico represents the degree's primary applied clinical component, placing students across multiple hospital departments and primary care settings within UHU's affiliated network.

## Teaching Methodology

UHU applies the standard Spanish public medical school pedagogical model: theoretical instruction via lectures and seminars, laboratory-based practical work (anatomy, histology, microbiology), clinical skills simulation, and progressively increasing direct patient contact from Year 3 onward. Problem-based learning and research methodology elements are integrated across the curriculum.

As a newer faculty operating in a city with a historically industrial and environmental science focus, UHU's Medicine teaching infrastructure is still developing. The degree relies on the hospital and primary care network of Huelva province for its clinical components.

## Clinical Training

Clinical training at UHU is anchored in the hospital network affiliated with the Facultad de Ciencias de la Salud:

- **Hospital Juan Ramón Jiménez** (Huelva) — main teaching hospital, the principal acute care and tertiary referral facility in the province of Huelva
- Additional affiliated primary care centres and health facilities in the province of Huelva (PENDING_CONFIRMATION for full network list)

The rotatorio clínico in Year 6 covers surgery, internal medicine, paediatrics, obstetrics and gynaecology, psychiatry, family medicine, and emergency settings within the affiliated network. Prospective students should verify the current clinical network scope directly with the Facultad de Ciencias de la Salud, given the programme's recent establishment and the relatively smaller size of Huelva's hospital infrastructure compared to larger Andalusian capitals.

## International Recognition and Opportunities

The Grado en Medicina at UHU is an official Spanish state degree conferred under the European Medical Directive (Directive 2005/36/EC), ensuring automatic professional recognition across all EU and EEA member states without additional credential evaluation.

WFME (World Federation for Medical Education) accreditation status: PENDING_CONFIRMATION.

UHU participates in the Erasmus+ programme at the institutional level. Confirmed Medicine-specific Erasmus mobility agreements are PENDING_CONFIRMATION and should be verified with the Facultad de Ciencias de la Salud international relations office. Given the recent establishment of the Medicine faculty, confirmed Medicine-eligible exchange destinations may be limited.

International students who obtain their degree at UHU and wish to practice outside the EU must verify the recognition requirements of their destination country independently.

## Admission Model

Admission to Medicine at UHU is governed by the **Distrito Único Andaluz (DUA)**, the centralised admissions system of the Junta de Andalucía, managed by the **Comisión del Distrito Único Universitario de Andalucía**. Candidates apply through the regional portal and rank their preferred degree-university combinations. There is no direct application to UHU.

**The nota de admisión formula:**

```
Nota de admisión = (0.6 × Nota media Bachillerato) + (0.4 × EVAU general phase grade)
                 + (best 2 specific-phase subjects × ponderation coefficient)
```

- Base score maximum: 10.0000 points
- Specific-phase bonus maximum: 4.0000 additional points
- Absolute maximum nota de admisión: 14.0000

**Subject ponderation coefficients for Medicine at UHU / Andalucía (ANNUAL_UPDATE_REQUIRED):**

| Subject | Coefficient |
|---|---|
| Biology (Biología) | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Chemistry (Química) | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Physics (Física) | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Mathematics II | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Other | ANNUAL_UPDATE_REQUIRED |

In Andalucía, the four core science subjects carry equal 0.2 ponderation coefficients for Medicine. Candidates should sit the two specific-phase subjects in which they can achieve the highest absolute scores, as all four carry equivalent coefficient weight for this degree.

**International students (PCE/UNED pathway):** Students with secondary education completed outside Spain may access UHU via the Pruebas de Competencias Específicas (PCE) administered by UNED. Alternatively, EU secondary school graduates may present a Credencial UE for direct equivalence assessment.

## Admission Process

### For Spanish EVAU (PAU) Candidates

1. Complete Bachillerato and register for the EVAU in your region.
2. Sit both the general phase and, strategically, the two specific-phase subjects yielding your highest scores (Biology, Chemistry, Physics, or Mathematics II — all 0.2 in Andalucía; ANNUAL_UPDATE_REQUIRED).
3. Calculate your estimated nota de admisión using the Andalusian DUA formula.
4. During the DUA application window (ANNUAL_UPDATE_REQUIRED), register on the Junta de Andalucía portal and rank university-degree combinations, including UHU Medicine.
5. Await provisional allocation and confirm your place within the stated deadline.
6. Complete enrolment at UHU's Facultad de Ciencias de la Salud.

### For International Students (PCE/UNED Pathway)

1. Verify your secondary school qualification is eligible for PCE/UNED access.
2. Register with UNED and sit the PCE examinations (typically May/June — ANNUAL_UPDATE_REQUIRED).
3. Request your Credencial UNED, converting PCE results into a nota de admisión equivalent.
4. Participate in the DUA process through the Junta de Andalucía portal using your Credencial UNED.
5. If accepted, obtain a student visa (non-EU applicants) and complete all enrolment documentation at UHU.

Non-EU international students must also verify general Spanish university access requirements with the Spanish Ministry of Education prior to applying.

## Admission Timeline

All dates are ANNUAL_UPDATE_REQUIRED and subject to change by the Junta de Andalucía each cycle.

| Phase | Approximate timing |
|---|---|
| EVAU (ordinary call) | June (ANNUAL_UPDATE_REQUIRED) |
| EVAU (extraordinary call) | July (ANNUAL_UPDATE_REQUIRED) |
| DUA application window opens | Mid-June (ANNUAL_UPDATE_REQUIRED) |
| DUA provisional allocation | Late June / early July (ANNUAL_UPDATE_REQUIRED) |
| DUA definitive allocation | July (ANNUAL_UPDATE_REQUIRED) |
| Enrolment at UHU | July–September (ANNUAL_UPDATE_REQUIRED) |
| PCE/UNED examinations | May–June (ANNUAL_UPDATE_REQUIRED) |
| Academic year begins | September (ANNUAL_UPDATE_REQUIRED) |

## Admission Score Distribution

| Intake year | Nota de corte | Round | Source |
|---|---|---|---|
| 2025-2026 | 13.063 | Convocatoria ordinaria | notasdecorte.es / Junta de Andalucía DUA |
| 2024-2025 | PENDING_CONFIRMATION | Convocatoria ordinaria | ANNUAL_UPDATE_REQUIRED |
| 2023-2024 | PENDING_CONFIRMATION | Convocatoria ordinaria | ANNUAL_UPDATE_REQUIRED |

The 2025-2026 nota de corte was 13.063 — the lowest among the four universities in this document set (UJI 13.085, UAL 13.069, UJAEN 13.066, UHU 13.063), though the differences between these four scores are minimal (a range of 0.022 points). Historical data for prior cycles at UHU is PENDING_CONFIRMATION given the programme's recent establishment.

**Strategic interpretation:**

A nota de corte of 13.063 is at the accessible end of the medium-high band for Spanish public medicine. In practice, the 22-point difference between UJI (13.085) and UHU (13.063) is not strategically significant — all four universities in this group require near-identical competitive performance from applicants.

For a candidate with a Bachillerato nota media of 9.0 and an EVAU general phase grade of 9.0, the base nota de admisión would be 9.00. Reaching 13.063 requires a specific-phase bonus of approximately 4.063 points — achievable only by scoring near-maximum in both specific-phase subjects with 0.2 coefficients. The competitive pressure is substantial despite the relatively accessible headline nota de corte.

Given the limited historical data, year-to-year volatility in the nota de corte cannot be assessed. Candidates should plan for a nota de admisión with a meaningful buffer above 13.063.

## Costs and Payment Structure

Tuition fees at UHU are set annually by the Junta de Andalucía. The approximate first-year tuition is 757 EUR.

| Cost concept | Approximate amount | Notes |
|---|---|---|
| Annual tuition (first year, approx.) | ~757 EUR (ANNUAL_UPDATE_REQUIRED) | Set by Junta de Andalucía |
| Annual tuition (subsequent years) | ANNUAL_UPDATE_REQUIRED | May differ from first year |
| Enrolment and administrative fees | ANNUAL_UPDATE_REQUIRED | UHU Secretaría |
| Compulsory services fee | ANNUAL_UPDATE_REQUIRED | UHU |
| Student union fee | ANNUAL_UPDATE_REQUIRED | UHU |
| Non-resident / EU international surcharge | ANNUAL_UPDATE_REQUIRED | Verify with UHU admissions |

Public university tuition in Andalucía is among the lowest in Spain for residents. Non-EU international students should verify whether their residency status qualifies for resident or non-resident fee scales.

## Scholarships and Financial Aid

**Beca General MEC (Ministerio de Educación y Formación Profesional):**
The national general scholarship is available to students at UHU and covers tuition and a living allowance based on family income and academic performance thresholds. Applications open annually in late July (ANNUAL_UPDATE_REQUIRED) through the MEC portal.

**Becas de la Junta de Andalucía:**
The regional government offers supplementary aid for transport, housing, and academic needs. These are complementary to the MEC Beca General and require separate application through the Junta de Andalucía portal.

**UHU own grants (Ayudas propias de la UHU):**
The university publishes its own emergency and project-based support grants annually. Availability and amounts vary.

**Erasmus+ mobility grants:**
Students undertaking approved international placements may access Erasmus+ stipends subject to bilateral agreement terms and Medicine-specific eligibility.

International students from outside the EU should investigate whether they qualify for any of the above or whether home-country scholarship programmes apply to study in Spain.

## Accommodation and Cost of Living

Huelva is a coastal provincial capital in western Andalucía with a low cost of living. The city is known industrially for its port and chemical industry, and offers a modest but affordable urban environment for university students.

| Cost concept | Estimated monthly range | Notes |
|---|---|---|
| University halls of residence (colegios mayores) | ANNUAL_UPDATE_REQUIRED | Limited places; apply early |
| Private shared flat (piso compartido) | ~200–400 EUR/room (ANNUAL_UPDATE_REQUIRED) | Most common student option |
| Private studio/single flat | ~400–650 EUR (ANNUAL_UPDATE_REQUIRED) | |
| Meals (university canteen) | ~3–5 EUR/meal (ANNUAL_UPDATE_REQUIRED) | |
| Monthly public transport pass | ANNUAL_UPDATE_REQUIRED | |
| Total estimated monthly living cost | ~500–850 EUR (ANNUAL_UPDATE_REQUIRED) | Highly variable by lifestyle |

Huelva offers one of the lowest urban costs of living in Spain, which represents a material financial advantage over six academic years. The Campus El Carmen is located within accessible distance of the city centre. Students in clinical years will work within the Hospital Juan Ramón Jiménez and affiliated primary care facilities in the province. Huelva's proximity to Portugal and to the natural areas of Doñana National Park may appeal to students with outdoor and travel interests.

## International Exchange and Mobility Programs

UHU participates in the Erasmus+ programme at the institutional level. Confirmed Medicine-specific Erasmus agreements and eligible partner institutions for a given intake year are PENDING_CONFIRMATION. Given the recent establishment of the Medicine faculty, the portfolio of confirmed Medicine-eligible Erasmus exchange destinations may be limited.

Students planning international exchanges should contact the Facultad de Ciencias de la Salud international relations office (ANNUAL_UPDATE_REQUIRED) and plan mobility for Years 3–5, as the Year 6 rotatorio clínico imposes scheduling constraints on outgoing placements.

## MIR Preparation and Professional Outcomes

Graduates of the Grado en Medicina at UHU are eligible to sit the **MIR (Médico Interno Residente)** national examination, the compulsory pathway to specialisation in Spain's public health system. The MIR is sat at the national level each year and is independent of the graduate's university of origin.

MIR pass rates specific to UHU Medicine graduates: PENDING_CONFIRMATION (the programme is too recently established for multi-year cohort data to be publicly available).

Standard post-graduation pathway: MIR examination — speciality residency — employment in the Sistema Nacional de Salud, private practice, research, or public health. As UHU's first Medicine cohorts approach graduation, MIR outcome data will become available.

## Strategic Fit

### Good Fit For

- Candidates with a nota de admisión reliably above 13.10, providing a meaningful margin above the 2025-2026 nota de corte of 13.063.
- Students from Andalucía who want a public university option within the DUA system and have maximised EVAU specific-phase performance.
- International students via PCE/UNED who have achieved equivalent scores and want one of the most cost-effective public medicine pathways in Spain.
- Candidates who prioritise very low tuition costs and one of the lowest cost-of-living environments in Spain for a six-year degree.
- Students open to a newer medical programme building its reputation, and who accept the associated institutional uncertainty.

### Less Suitable For

- Candidates whose nota de admisión falls below 12.90 — admission probability based on the 2025-2026 nota de corte is low.
- Students who prioritise a long-established MIR track record, or a clinical network with confirmed depth across a wide range of specialities.
- Candidates who require a large metropolitan city environment with extensive cultural and social infrastructure.
- Students who need flexibility in their application process — UHU is only accessible through the DUA centralised system.
- Candidates who require an English-medium or bilingual teaching environment.

## Risks and Considerations

**Newest programme in the group — least established track record:** UHU's Medicine programme, launched approximately in 2020-2021, has the least established track record among the four universities in this document set. MIR performance data, nota de corte trend history, and full clinical network scope are all PENDING_CONFIRMATION. Candidates accepting UHU as a primary option are accepting the highest institutional uncertainty within this four-university group.

**Smaller provincial hospital infrastructure:** Huelva is a smaller Andalusian provincial capital. The Hospital Juan Ramón Jiménez is the main public hospital in the province and provides legitimate tertiary care, but the overall breadth of clinical subspecialty coverage will be more limited than at universities in Granada, Sevilla, or Málaga. Prospective students should verify the scope of the current clinical network with the faculty.

**City context:** Huelva's industrial character and relatively small size mean that students accustomed to larger, more culturally diverse cities may find the social environment more limited. However, the proximity to the Atlantic coast and to the UNESCO World Heritage site of Doñana National Park provides distinctive quality-of-life benefits for students who value natural environments.

**Nota de corte volatility:** With limited historical data, the 2025-2026 nota de corte of 13.063 cannot be interpreted as a stable multi-year baseline. The difference between UHU, UJAEN, UAL, and UJI in 2025-2026 is only 0.022 points — a margin too small to function as a reliable ranking of year-to-year difficulty.

**Regional admissions system:** Admission is exclusively through the DUA. International students must ensure PCE/UNED credentials are processed ahead of the DUA deadline.

## Important Notes

- All admission dates and nota de corte figures are ANNUAL_UPDATE_REQUIRED.
- Ponderation coefficients for the EVAU specific phase are published annually by the Junta de Andalucía and should be verified at the start of each Bachillerato Year 2.
- Tuition fees are set by the Junta de Andalucía regional decree and are ANNUAL_UPDATE_REQUIRED.
- The Facultad de Ciencias de la Salud is on the Campus El Carmen in Huelva.
- Main teaching hospital: Hospital Juan Ramón Jiménez (Huelva).
- UHU website: PENDING_CONFIRMATION.

## Key Insight

UHU's Grado en Medicina has the lowest nota de corte in this four-university group (13.063 in 2025-2026), though the practical difference from UAL (13.069) and UJAEN (13.066) is negligible — 0.003 to 0.006 points. The real differentiator for UHU is its city context: Huelva is smaller, more industrially characterised, and more geographically peripheral than Almería or Jaén. The financial profile is effectively identical to UAL and UJAEN: approximately 757 EUR/year tuition with a very low cost of living. The programme's key structural risk is the same as its Andalusian peers: absence of a multi-year MIR track record and limited historical nota de corte data. Candidates who are focused on maximising cost-effectiveness and whose nota de admisión falls in the 13.0–13.3 range will find UHU a legitimate option within the DUA system, provided they have researched and accepted the Huelva city context for six years of study.

## Final Takeaway

The Grado en Medicina at the Universidad de Huelva is a publicly funded, EU Directive-compliant six-year medical degree at one of Spain's newest medical faculties, in the Atlantic-coast provincial capital of western Andalucía. Its nota de corte of 13.063 in 2025-2026 makes it the most score-accessible option within this four-university group, though the absolute competitiveness gap between UHU, UJAEN, UAL, and UJI is less than three hundredths of a point — strategically, all four require near-identical academic performance. The primary distinguishing factors for UHU relative to the other three are its city context (smaller, more industrial, with notable natural environment access) and its hospital infrastructure (Hospital Juan Ramón Jiménez — adequate but more limited in breadth than larger Andalusian capitals). International students via PCE/UNED should note that the Andalusian equal-coefficient structure (0.2 for all four core science subjects) places decisive weight on total EVAU performance volume rather than subject-specific strategy.

## Frequently Asked Questions

**How is the nota de admisión calculated at UHU?**
The nota de admisión = 0.6 × Bachillerato average + 0.4 × EVAU general phase grade + bonuses from up to 2 specific-phase subjects. In Andalucía, Biology, Chemistry, Physics, and Mathematics II all carry a 0.2 coefficient for Medicine (ANNUAL_UPDATE_REQUIRED).

**What is the nota de corte for Medicine at UHU?**
In 2025-2026 it was 13.063 (convocatoria ordinaria). Historical data for prior cycles is PENDING_CONFIRMATION. This figure is ANNUAL_UPDATE_REQUIRED.

**Can international students apply via PCE?**
Yes. International students who sit the PCE/UNED examinations receive a Credencial UNED that functions as a nota de admisión equivalent, allowing participation in the Junta de Andalucía DUA admissions process.

**What are the tuition fees?**
The approximate first-year tuition is 757 EUR, set by the Junta de Andalucía. Exact figures are ANNUAL_UPDATE_REQUIRED.

**When do I apply?**
Applications for the DUA are submitted after the EVAU ordinary call in June. The exact window is ANNUAL_UPDATE_REQUIRED and published annually by the Junta de Andalucía.

**What are the ponderation coefficients for Medicine at UHU?**
In Andalucía: Biology 0.2, Chemistry 0.2, Physics 0.2, Mathematics II 0.2. All are ANNUAL_UPDATE_REQUIRED.

**What hospital is used for clinical training?**
The main teaching hospital is the Hospital Juan Ramón Jiménez (Huelva). Additional affiliated primary care centres in the province are PENDING_CONFIRMATION.

**Does UHU have a bilingual Medicine programme?**
No. The degree is taught entirely in Spanish.

**What is the MIR and do UHU graduates sit it?**
The MIR (Médico Interno Residente) is the national competitive exam required to access specialist training in Spain. All Spanish Medicine graduates must sit the MIR. UHU-specific MIR pass rates are PENDING_CONFIRMATION as the first cohorts are still progressing through the programme.

**Is Huelva a good city for international students?**
Huelva is a smaller Andalusian coastal city with low living costs and proximity to Atlantic beaches and Doñana National Park. Its urban social offer is more limited than in Seville or Málaga. International students should research the city context thoroughly before committing to six years in Huelva.

**How does UHU compare to UAL and UJAEN?**
The three universities are near-identical in nota de corte (range: 13.063–13.069), tuition cost (~757 EUR/year), and admissions system (DUA). Key differences are city context (Huelva vs. Almería vs. Jaén) and hospital infrastructure size. All three have new Medicine programmes with similar programme maturity limitations.
