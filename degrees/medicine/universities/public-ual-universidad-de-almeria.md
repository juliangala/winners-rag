---
id: ual

type: university
subtype: public

name: Universidad de Almería
short_name: UAL

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Almería
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
      score: 13.069 # ANNUAL_UPDATE_REQUIRED
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
  - id: ual-medicina
    campus: Campus de Almería — Facultad de Ciencias de la Salud (UAL)
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
          score: 13.069 # ANNUAL_UPDATE_REQUIRED
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
          score: 13.069 # ANNUAL_UPDATE_REQUIRED
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

# Universidad de Almería (UAL) — Grado en Medicina

## Overview

The Universidad de Almería (UAL) is a public university located in Almería, the easternmost provincial capital of Andalucía. Its Grado en Medicina is among the more recently established public medicine programmes in Spain, with the degree launching approximately in 2020-2021. The programme is delivered through the Facultad de Ciencias de la Salud on the main UAL campus.

Admission to Medicine at UAL is governed by the **Distrito Único Andaluz (DUA)**, the centralised admissions system of the Junta de Andalucía. There is no proprietary entrance exam, no interview, and no language test requirement. The admissions process is transparent and score-driven, based exclusively on the nota de admisión derived from Bachillerato grades and EVAU performance. All applications are submitted through the Junta de Andalucía's regional portal.

The main affiliated teaching hospital is the Hospital Universitario Torrecárdenas, a major public hospital in Almería. As a newer Andalusian medical faculty, UAL is still building its clinical training infrastructure and MIR track record — this is a relevant consideration compared to longer-established Andalusian faculties such as the Universidad de Granada or the Universidad de Sevilla.

The nota de corte for Medicine at UAL in 2025-2026 was 13.069, placing it in the medium-high competitiveness band among Spanish public medical schools.

## Quick Evaluation

- Admission model: nota de admisión (EVAU formula) — no proprietary exam, no interview
- Seats: PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED)
- Nota de corte 2025-2026: 13.069
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
| University | Universidad de Almería (UAL) |
| City | Almería, Andalucía |
| Degree | Grado en Medicina |
| Duration | 6 years |
| ECTS | 360 |
| Annual seats | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2025-2026 | 13.069 (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2024-2025 | PENDING_CONFIRMATION |
| Nota de corte 2023-2024 | PENDING_CONFIRMATION |
| Tuition (approx. first year) | ~757 EUR (ANNUAL_UPDATE_REQUIRED) |
| Teaching language | Spanish |
| Admission route | Nota de admisión (EVAU formula) |
| Admissions system | Distrito Único Andaluz (DUA) — Junta de Andalucía |
| Proprietary exam | No |
| Interview | No |
| Main teaching hospital | Hospital Universitario Torrecárdenas |

## Program Options

UAL offers a single Grado en Medicina programme, delivered entirely in Spanish on the main Almería campus. There is no bilingual track, no English-medium option, no distance-learning variant, and no parallel international programme. All students follow a unified six-year curriculum regardless of their geographic or academic background.

The programme is accessible via the DUA portal (Junta de Andalucía) for Spanish EVAU candidates and via PCE/UNED or Credencial UE for international students. UAL is one of four newer Andalusian universities to have launched a Medicine programme in recent years, alongside Jaén and Huelva, representing a regional expansion of public medical education capacity.

## Program Structure

The Grado en Medicina at UAL follows the standard Spanish public medical degree structure across 6 years (360 ECTS):

| Year | Main focus |
|---|---|
| Year 1 | Foundational biomedical sciences: anatomy, physiology, biochemistry, cell biology, histology |
| Year 2 | Pathophysiology, pharmacology, microbiology, immunology, genetics |
| Year 3 | Introduction to clinical medicine; first supervised hospital placements begin |
| Year 4 | Core clinical disciplines: internal medicine, surgery, paediatrics, obstetrics and gynaecology |
| Year 5 | Advanced clinical rotations across medical and surgical specialities |
| Year 6 | Rotatorio clínico (full-year supervised clinical rotation) + TFG (Final Degree Project) |

Each academic year comprises approximately 60 ECTS. The final year is dedicated almost entirely to supervised clinical rotation across hospital departments and primary care centres within UAL's affiliated network.

## Teaching Methodology

UAL applies the standard Spanish public medical school teaching model: theoretical instruction via lectures and seminars, laboratory-based practical work (anatomy dissection, histology, microbiology), clinical skills simulation, and progressively increasing direct patient contact from Year 3 onward.

Problem-based learning elements and research methodology are integrated into the curriculum from the early years. The Year 6 rotatorio clínico represents the degree's primary applied clinical component, placing students in direct supervised contact with patients across multiple disciplines and care settings.

As a newer faculty, UAL's pedagogical model is still maturing, and the specific teaching methodologies and resource availability may evolve as the programme develops.

## Clinical Training

Clinical training at UAL is anchored primarily in the following hospital:

- **Hospital Universitario Torrecárdenas** (Almería) — main teaching hospital, comprehensive tertiary care, the primary acute care facility in the province of Almería
- Additional affiliated primary care centres and health facilities in the province of Almería (PENDING_CONFIRMATION for full network list)

The rotatorio clínico in Year 6 covers surgery, internal medicine, paediatrics, obstetrics and gynaecology, psychiatry, family medicine, and emergency settings within the affiliated network. As one of the newer Andalusian medical faculties, the clinical network at UAL may be more limited in breadth than those of longer-established faculties (e.g., Universidad de Granada, Universidad de Sevilla). Prospective students should verify the current clinical network scope directly with the UAL Facultad de Ciencias de la Salud.

## International Recognition and Opportunities

The Grado en Medicina at UAL is an official Spanish state degree conferred under the European Medical Directive (Directive 2005/36/EC), which ensures automatic professional recognition across all EU and EEA member states without additional credential evaluation.

WFME (World Federation for Medical Education) accreditation status: PENDING_CONFIRMATION.

UAL participates in the Erasmus+ programme at the institutional level. Confirmed Medicine-specific Erasmus mobility agreements are PENDING_CONFIRMATION and should be verified with the Facultad de Ciencias de la Salud international relations office. As a newer faculty, confirmed Medicine-eligible exchange destinations may be limited.

International students who obtain their degree at UAL and wish to practice outside the EU must verify the recognition requirements of their destination country independently.

## Admission Model

Admission to Medicine at UAL is governed by the **Distrito Único Andaluz (DUA)**, the centralised admissions system of the Junta de Andalucía, managed by the **Comisión del Distrito Único Universitario de Andalucía**. Candidates apply through the regional portal and rank their preferred degree-university combinations. There is no direct application to UAL.

**The nota de admisión formula:**

```
Nota de admisión = (0.6 × Nota media Bachillerato) + (0.4 × EVAU general phase grade)
                 + (best 2 specific-phase subjects × ponderation coefficient)
```

- Base score maximum: 10.0000 points
- Specific-phase bonus maximum: 4.0000 additional points
- Absolute maximum nota de admisión: 14.0000

**Subject ponderation coefficients for Medicine at UAL / Andalucía (ANNUAL_UPDATE_REQUIRED):**

| Subject | Coefficient |
|---|---|
| Biology (Biología) | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Chemistry (Química) | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Physics (Física) | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Mathematics II | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Other | ANNUAL_UPDATE_REQUIRED |

In Andalucía, the main science subjects (Biology, Chemistry, Physics, Mathematics II) all carry a 0.2 ponderation coefficient for Medicine. This differs from some other regions where coefficients are differentiated. Candidates should prioritise Biology and Chemistry as the most directly relevant subjects, while also noting that Physics and Mathematics II provide equivalent coefficient value.

**International students (PCE/UNED pathway):** Students with secondary education completed outside Spain may access UAL via the Pruebas de Competencias Específicas (PCE) administered by UNED. Alternatively, EU secondary school graduates may present a Credencial UE for direct equivalence assessment.

## Admission Process

### For Spanish EVAU (PAU) Candidates

1. Complete Bachillerato and register for the EVAU in your region.
2. Sit both the general phase and, strategically, the specific-phase subjects with the highest ponderation coefficients for Medicine in Andalucía — Biology, Chemistry, Physics, and/or Mathematics II (all 0.2, ANNUAL_UPDATE_REQUIRED).
3. Calculate your estimated nota de admisión using the Andalusian DUA formula.
4. During the DUA application window (ANNUAL_UPDATE_REQUIRED), register on the Junta de Andalucía's admissions portal and rank university-degree combinations, including UAL Medicine.
5. Await provisional allocation and confirm your place within the stated deadline.
6. Complete enrolment at UAL's Facultad de Ciencias de la Salud.

### For International Students (PCE/UNED Pathway)

1. Verify your secondary school qualification is eligible for PCE/UNED access.
2. Register with UNED and sit the PCE examinations (typically May/June — ANNUAL_UPDATE_REQUIRED).
3. Request your Credencial UNED, converting PCE results into a nota de admisión equivalent.
4. Participate in the DUA process through the Junta de Andalucía portal using your Credencial UNED.
5. If accepted, obtain a student visa (non-EU applicants) and complete all enrolment documentation at UAL.

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
| Enrolment at UAL | July–September (ANNUAL_UPDATE_REQUIRED) |
| PCE/UNED examinations | May–June (ANNUAL_UPDATE_REQUIRED) |
| Academic year begins | September (ANNUAL_UPDATE_REQUIRED) |

## Admission Score Distribution

| Intake year | Nota de corte | Round | Source |
|---|---|---|---|
| 2025-2026 | 13.069 | Convocatoria ordinaria | notasdecorte.es / Junta de Andalucía DUA |
| 2024-2025 | PENDING_CONFIRMATION | Convocatoria ordinaria | ANNUAL_UPDATE_REQUIRED |
| 2023-2024 | PENDING_CONFIRMATION | Convocatoria ordinaria | ANNUAL_UPDATE_REQUIRED |

The 2025-2026 nota de corte was 13.069. Historical data for prior cycles is PENDING_CONFIRMATION given the programme's recent establishment.

**Strategic interpretation:**

A nota de corte of 13.069 sits in the medium-high range for Spanish public medical schools. With the Andalusian ponderation structure — where Biology, Chemistry, Physics, and Mathematics II all carry a 0.2 coefficient — the specific-phase bonus strategy is less differentiated than in some other regions: any two of these four subjects will yield the maximum possible bonus contribution. The competitive lever therefore shifts more heavily toward Bachillerato average and EVAU general phase performance.

For a candidate with a Bachillerato nota media of 9.0 and an EVAU general phase grade of 9.5, the base nota de admisión would be 9.30. Reaching 13.069 requires a specific-phase bonus of approximately 3.769 points — achievable by scoring approximately 9.4 in two subjects with a 0.2 coefficient each. This is demanding but realistic for well-prepared candidates.

Given the limited historical data, year-to-year volatility in the nota de corte cannot be assessed reliably. Candidates should plan for a nota de admisión with a meaningful margin above 13.069.

## Costs and Payment Structure

Tuition fees at UAL are set annually by the Junta de Andalucía (Decreto de precios públicos). The approximate first-year tuition is 757 EUR.

| Cost concept | Approximate amount | Notes |
|---|---|---|
| Annual tuition (first year, approx.) | ~757 EUR (ANNUAL_UPDATE_REQUIRED) | Set by Junta de Andalucía |
| Annual tuition (subsequent years) | ANNUAL_UPDATE_REQUIRED | May differ from first year |
| Enrolment and administrative fees | ANNUAL_UPDATE_REQUIRED | UAL Secretaría |
| Compulsory services fee | ANNUAL_UPDATE_REQUIRED | UAL |
| Student union fee | ANNUAL_UPDATE_REQUIRED | UAL |
| Non-resident / EU international surcharge | ANNUAL_UPDATE_REQUIRED | Verify with UAL admissions |

Public university tuition in Andalucía is among the lowest in Spain for residents. Non-EU international students should verify whether their residency status qualifies for resident or non-resident fee scales.

## Scholarships and Financial Aid

**Beca General MEC (Ministerio de Educación y Formación Profesional):**
The national general scholarship is available to students at UAL and covers tuition plus a living allowance based on family income and academic performance thresholds. Applications open annually in late July (ANNUAL_UPDATE_REQUIRED) through the MEC portal.

**Becas de la Junta de Andalucía:**
The regional government offers supplementary aid for transport, housing, and academic needs. These are complementary to the MEC Beca General and require separate application through the Junta de Andalucía portal.

**UAL own grants (Ayudas propias de la UAL):**
The university publishes its own emergency and project-based support grants annually. Availability and amounts vary.

**Erasmus+ mobility grants:**
Students undertaking approved international placements may access Erasmus+ stipends subject to bilateral agreement terms and Medicine-specific eligibility.

International students from outside the EU should investigate whether they qualify for any of the above or whether home-country scholarship programmes apply to study in Spain.

## Accommodation and Cost of Living

Almería is a provincial capital in southeastern Spain with one of the lower costs of living among Spanish university cities.

| Cost concept | Estimated monthly range | Notes |
|---|---|---|
| University halls of residence (colegios mayores) | ANNUAL_UPDATE_REQUIRED | Limited places; apply early |
| Private shared flat (piso compartido) | ~250–450 EUR/room (ANNUAL_UPDATE_REQUIRED) | Most common student option |
| Private studio/single flat | ~450–700 EUR (ANNUAL_UPDATE_REQUIRED) | |
| Meals (university canteen) | ~3–5 EUR/meal (ANNUAL_UPDATE_REQUIRED) | |
| Monthly public transport pass | ANNUAL_UPDATE_REQUIRED | |
| Total estimated monthly living cost | ~550–900 EUR (ANNUAL_UPDATE_REQUIRED) | Highly variable by lifestyle |

Almería has a compact urban centre and the UAL campus is located to the west of the city. The main teaching hospital (Hospital Universitario Torrecárdenas) is accessible from both the campus and the city centre. The relatively low cost of living is one of the material cost advantages of choosing UAL over universities in larger Spanish cities.

## International Exchange and Mobility Programs

UAL participates in the Erasmus+ programme at the institutional level. Confirmed Medicine-specific Erasmus agreements and eligible partner institutions for a given intake year are PENDING_CONFIRMATION. Given the relative novelty of the Medicine faculty, the portfolio of confirmed Medicine-eligible exchange agreements may be limited.

Students planning international exchanges should contact the Facultad de Ciencias de la Salud international relations office (ANNUAL_UPDATE_REQUIRED) and plan mobility for Years 3–5, as the Year 6 rotatorio clínico imposes scheduling constraints on outgoing placements.

## MIR Preparation and Professional Outcomes

Graduates of the Grado en Medicina at UAL are eligible to sit the **MIR (Médico Interno Residente)** national examination, the compulsory pathway to specialisation in Spain's public health system. The MIR is sat at the national level each year and is independent of the graduate's university of origin.

MIR pass rates specific to UAL Medicine graduates: PENDING_CONFIRMATION (the programme is too recently established for multi-year cohort data to be publicly available).

As UAL's first Medicine cohorts approach graduation, MIR outcome data will become available. Prospective students should factor this absence of established track record into their decision when comparing UAL against longer-established Andalusian faculties.

Standard post-graduation pathway: MIR examination — speciality residency — employment in the Sistema Nacional de Salud, private practice, research, or public health.

## Strategic Fit

### Good Fit For

- Candidates with a nota de admisión reliably above 13.10, providing a meaningful margin above the 2025-2026 nota de corte of 13.069.
- Students from Andalucía who want a public university option within the DUA system and who have sat Biology and/or Chemistry in the EVAU specific phase.
- International students via PCE/UNED who have achieved equivalent scores and want a very cost-effective public university option in southern Spain.
- Candidates who value one of the lowest cost-of-living environments among Spanish university cities.
- Students open to a newer medical programme that is still building its clinical reputation and track record.

### Less Suitable For

- Candidates whose nota de admisión falls below 12.90 — the probability of admission based on the 2025-2026 nota de corte is low.
- Students who prioritise a long-established MIR track record or a clinical network with confirmed broad depth across multiple specialities.
- Candidates who need flexibility in their application, since UAL is only accessible through the DUA centralised system.
- Students who require an English-medium or bilingual teaching environment.

## Risks and Considerations

**Newer programme — limited track record:** The Medicine programme at UAL was launched approximately in 2020-2021. There are limited cohort data on MIR performance, limited multi-year nota de corte history, and the clinical network may still be expanding. This is a genuine differentiator versus older Andalusian faculties.

**Nota de corte volatility:** With limited historical data, the 2025-2026 figure of 13.069 cannot be interpreted as a stable multi-year baseline. Year-to-year fluctuation may be pronounced.

**Clinical infrastructure depth:** As one of the newer Andalusian medicine programmes, the affiliated hospital network may be less developed than at universities such as Granada, Sevilla, or Córdoba. The Hospital Universitario Torrecárdenas is a legitimate tertiary hospital, but the overall breadth of clinical placements should be verified directly with the faculty.

**Regional admissions system:** Admission is exclusively through the DUA. Candidates who miss the application window or submit incomplete applications cannot apply directly to UAL. International students must ensure PCE/UNED credentials are processed ahead of the DUA deadline.

**Extraordinary call:** Seats available in the convocatoria extraordinaria (September) are residual from the ordinary call and may be very limited or zero for Medicine. Do not plan strategy around extraordinary call availability.

## Important Notes

- All admission dates and nota de corte figures are ANNUAL_UPDATE_REQUIRED.
- Ponderation coefficients for the EVAU specific phase are published annually by the Junta de Andalucía and should be verified at the start of each Bachillerato Year 2.
- Tuition fees are set by the Junta de Andalucía regional decree and are ANNUAL_UPDATE_REQUIRED.
- The Facultad de Ciencias de la Salud is located on the main UAL campus in Almería.
- Main teaching hospital: Hospital Universitario Torrecárdenas (Almería).
- UAL website: PENDING_CONFIRMATION.

## Key Insight

UAL's Grado en Medicina combines one of the lowest tuition fees among Spanish public medical schools (~757 EUR/year) with a cost-of-living environment that is among the most affordable in Spain. The nota de corte of 13.069 in 2025-2026 places it at the accessible end of the medium-high competitiveness band. The key strategic consideration is the programme's relative youth: without a multi-year MIR track record or a fully developed clinical network comparable to older Andalusian faculties, candidates must weigh cost-accessibility advantages against outcome-verification limitations. In Andalucía, the ponderation coefficients for Biology, Chemistry, Physics, and Mathematics II are all 0.2 for Medicine — meaning that specific-phase strategy is less subject-differentiated than in other regions, and overall Bachillerato and EVAU general phase performance becomes proportionally more important as a competitive lever.

## Final Takeaway

The Grado en Medicina at the Universidad de Almería is a publicly funded, EU Directive-compliant six-year degree at one of Spain's newer medical faculties. Its primary advantages are very low tuition costs, an affordable city environment, and access through the transparent Andalusian DUA system. The nota de corte of 13.069 makes it one of the more accessible public medicine programmes in Spain by score threshold, though still demanding for most candidates. The programme's relative youth means MIR outcomes and clinical breadth remain PENDING_CONFIRMATION — candidates who are outcome-focused should weight this against the cost advantages. International students via PCE/UNED should model their nota de admisión carefully and note that in Andalucía, Biology, Chemistry, Physics, and Mathematics II all carry equal 0.2 ponderation coefficients for Medicine, making the general-phase and Bachillerato components especially decisive in the competitive ranking.

## Frequently Asked Questions

**How is the nota de admisión calculated at UAL?**
The nota de admisión = 0.6 × Bachillerato average + 0.4 × EVAU general phase grade + bonuses from up to 2 specific-phase subjects. In Andalucía, Biology, Chemistry, Physics, and Mathematics II all carry a 0.2 coefficient for Medicine (ANNUAL_UPDATE_REQUIRED).

**What is the nota de corte for Medicine at UAL?**
In 2025-2026 it was 13.069 (convocatoria ordinaria). Historical data for prior cycles is PENDING_CONFIRMATION. This figure is ANNUAL_UPDATE_REQUIRED.

**Can international students apply via PCE?**
Yes. International students who sit the PCE/UNED examinations receive a Credencial UNED that functions as a nota de admisión equivalent, allowing participation in the Junta de Andalucía DUA admissions process.

**What are the tuition fees?**
The approximate first-year tuition is 757 EUR, set by the Junta de Andalucía. Exact figures are ANNUAL_UPDATE_REQUIRED.

**When do I apply?**
Applications for the DUA are submitted after the EVAU ordinary call in June. The exact window is ANNUAL_UPDATE_REQUIRED and published annually by the Junta de Andalucía.

**What are the ponderation coefficients for Medicine at UAL?**
In Andalucía: Biology 0.2, Chemistry 0.2, Physics 0.2, Mathematics II 0.2. All are ANNUAL_UPDATE_REQUIRED and should be confirmed via the official Junta de Andalucía table each cycle.

**What hospital is used for clinical training?**
The main teaching hospital is the Hospital Universitario Torrecárdenas (Almería). Additional affiliated health centres in the province are PENDING_CONFIRMATION.

**Does UAL have a bilingual Medicine programme?**
No. The degree is taught entirely in Spanish.

**What is the MIR and do UAL graduates sit it?**
The MIR (Médico Interno Residente) is the national competitive exam required to access specialist training in Spain. All Spanish Medicine graduates must sit the MIR. UAL-specific MIR pass rates are PENDING_CONFIRMATION as the first cohorts are still progressing through the programme.

**Why is UAL's tuition lower than other regions?**
Public university tuition in Andalucía is set by the Junta de Andalucía at rates that are among the lowest in Spain for resident students. The ~757 EUR/year figure reflects this regional policy, not a reduction in programme quality.
