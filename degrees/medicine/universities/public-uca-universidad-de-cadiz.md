---
id: uca

type: university
subtype: public

name: Universidad de Cádiz
short_name: UCA

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Cádiz
  region: Andalucía
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
  seats: 110 # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
    - intake_year: 2025-2026
      round: convocatoria_ordinaria
      score: 13.157 # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: "Source: notasdecorte.es / Junta de Andalucía DUA"
    - intake_year: 2024-2025
      round: convocatoria_ordinaria
      score: 13.696 # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: NULL
    - intake_year: 2023-2024
      round: convocatoria_ordinaria
      score: 13.584 # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: NULL

international_profile:
  international_students_percentage: PENDING_CONFIRMATION
  international_nationalities: []

programs:
  - id: uca-medicina
    campus: Campus de Cádiz — Facultad de Medicina
    modality: standard
    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - medium_competitiveness
      - strong_clinical_exposure
    teaching_languages:
      - Spanish
    regional_language_possible: false
    regional_language: NULL
    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL
    seats: 110 # ANNUAL_UPDATE_REQUIRED
    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 110 # ANNUAL_UPDATE_REQUIRED
      applicants_per_seat: PENDING_CONFIRMATION
      last_admitted_scores:
        - intake_year: 2025-2026
          round: convocatoria_ordinaria
          score: 13.157 # ANNUAL_UPDATE_REQUIRED
          score_type: nota_de_admision
          notes: NULL
        - intake_year: 2024-2025
          round: convocatoria_ordinaria
          score: 13.696 # ANNUAL_UPDATE_REQUIRED
          score_type: nota_de_admision
          notes: NULL
        - intake_year: 2023-2024
          round: convocatoria_ordinaria
          score: 13.584 # ANNUAL_UPDATE_REQUIRED
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
          score: 13.157 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: "notasdecorte.es / Junta de Andalucía DUA"
        - intake_year: 2024-2025
          score: 13.696 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: Distrito Único Andaluz (DUA) — Junta de Andalucía
        - intake_year: 2023-2024
          score: 13.584 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: Distrito Único Andaluz (DUA) — Junta de Andalucía
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
              notes: Best 2 eligible subjects count. Each subject score multiplied by the ponderation coefficient (0.1 or 0.2). Maximum nota de admisión: 14.0000. Coefficients ANNUAL_UPDATE_REQUIRED.
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED
                Chemistry:      0.2 # ANNUAL_UPDATE_REQUIRED
                Physics:        0.1 # ANNUAL_UPDATE_REQUIRED
                Mathematics_II: 0.1 # ANNUAL_UPDATE_REQUIRED
                Drawing_II:     0.1 # ANNUAL_UPDATE_REQUIRED
                History_Art:    0.1 # ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---

# Universidad de Cádiz

## Overview

The Universidad de Cádiz (UCA) is one of Spain's oldest institutions for medical education, with over 250 years of continuous training of physicians. Its Facultad de Medicina operates from the main Cádiz campus and delivers the Grado en Medicina as a publicly funded, six-year degree governed by the Andalusian regional admissions system (Distrito Único Andaluz).

Access to Medicine at UCA is determined exclusively by the nota de admisión — a composite score combining Bachillerato academic record and EVAU (Selectividad) performance. There is no proprietary entrance exam, no interview, and no language test requirement. Admission is allocated centrally through the Junta de Andalucía, meaning UCA does not accept individual applications outside the regional system.

The nota de corte for Medicine at UCA has consistently ranked among the most competitive in Andalucía, reflecting the high academic demand of the programme relative to available seats. The clinical training network is built around three hospital centres in the province of Cádiz. UCA holds an EU Directive qualification, ensuring direct professional recognition across all EU member states.

## Quick Evaluation

- Admission model: nota de admisión (EVAU formula) — no proprietary exam, no interview
- Seats: approximately 110 per year (ANNUAL_UPDATE_REQUIRED)
- Nota de corte range (last 3 cycles): 13.560–13.696 out of 14.000
- Competitiveness level: very high
- Tuition: set by Junta de Andalucía (~1,000–1,600 EUR/year for residents; ANNUAL_UPDATE_REQUIRED)
- Teaching language: Spanish
- Clinical training begins: Year 3 (progressively increasing through Year 6)
- WFME accreditation: PENDING_CONFIRMATION
- EU Directive qualification: Yes — automatic professional recognition in EU countries
- International access: via PCE/UNED or Credencial UE

## Key Facts

| Feature | Detail |
|---|---|
| University | Universidad de Cádiz (UCA) |
| City | Cádiz, Andalucía |
| Degree | Grado en Medicina |
| Duration | 6 years |
| ECTS | 360 |
| Annual seats | ~110 (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2024-25 | 13.696 (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2023-24 | 13.584 (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2022-23 | 13.560 (ANNUAL_UPDATE_REQUIRED) |
| Tuition (approx.) | ~1,000–1,600 EUR/year (ANNUAL_UPDATE_REQUIRED) |
| Teaching language | Spanish |
| Admission route | Nota de admisión (EVAU formula) |
| Proprietary exam | No |
| Interview | No |
| Admissions system | Distrito Único Andaluz (DUA) — Junta de Andalucía |

## Program Options

UCA offers a single Medicine programme — the Grado en Medicina — delivered in Spanish on the Cádiz campus. There is no bilingual track, no separate parallel programme, and no distance-learning option. All students follow the same curriculum structure regardless of academic background.

The programme is divided into five thematic modules plus two complementary modules, distributed across six academic years. Students from any Spanish region may apply via the Distrito Único Andaluz (DUA) system, which also coordinates inter-Andalusian university transfers. International students access through PCE/UNED or EU credential recognition pathways.

## Program Structure

The Grado en Medicina at UCA is structured across 6 years (360 ECTS total), organised into five core modules plus two complementary modules:

| Module | Content focus | ECTS |
|---|---|---|
| M1 | Morphology, structure and function of the human body | 78 |
| M2 | Social medicine, communication skills, research foundations | 39 |
| M3 | Human clinical training | 120 |
| M4 | Diagnostic and therapeutic procedures | 42 |
| M5 | Supervised clinical placements (rotatorio) + TFG (Year 6) | 60 |
| M6–M7 | Faculty-specific subjects and optional activities | 21 |

Year 6 is dedicated to the rotatorio clínico — a full-year supervised clinical rotation across hospitals and primary care centres. Each academic year comprises 60 ECTS. The programme includes 6 ECTS of optativas (electives), allowing limited specialisation within the degree.

## Teaching Methodology

UCA follows a dual teaching model that combines theoretical instruction with early and progressively expanding clinical exposure. Theoretical content is delivered via lectures and seminars at the Facultad de Medicina. Laboratory practice, dissection, and skills training are integrated from the early years.

From Year 3 onward, students progressively enter affiliated hospital settings for directed clinical practice. The final year (Year 6) functions almost entirely as a supervised clinical rotation (rotatorio), placing students across multiple departments and primary care facilities. This structure mirrors the standard Spanish public medical school model, emphasising direct patient contact as a core educational component rather than a late-stage add-on.

Problem-based learning elements and research initiation activities are embedded in Module M2 from early in the degree, preparing students for the investigative dimension of medical practice.

## Clinical Training

Clinical training at UCA is distributed across the Facultad de Medicina's affiliated hospital network in the province of Cádiz:

- **Hospital Universitario Puerta del Mar** (Cádiz) — main teaching hospital, comprehensive tertiary care
- **Hospital Universitario de Puerto Real** (Puerto Real) — secondary and tertiary level hospital
- **Hospital de Jerez de la Frontera** (Jerez de la Frontera) — regional hospital

Students also rotate through primary care centres (centros de salud) across the province during the rotatorio clínico in Year 6. The rotatorio is compulsory and constitutes 60 ECTS of the degree, covering surgery, internal medicine, obstetrics and gynaecology, paediatrics, psychiatry, family medicine, and emergency settings.

The breadth of the clinical network gives UCA students access to a range of hospital environments across the province, from a major tertiary centre to district hospitals.

## International Recognition and Opportunities

The Grado en Medicina at UCA is an official Spanish state degree conferred under the European Medical Directive (Directive 2005/36/EC), which ensures automatic professional recognition across all EU and EEA member states. Graduates do not require additional credential evaluation to practice medicine in EU countries.

WFME (World Federation for Medical Education) accreditation status: PENDING_CONFIRMATION.

UCA participates in the Erasmus+ programme. Medicine-specific Erasmus mobility agreements are subject to annual availability and bilateral partner capacity. Students interested in international placements should consult the Facultad de Medicina's international office for confirmed Medicine-eligible Erasmus destinations.

International students who obtain their degree at UCA and wish to practice outside the EU must verify the recognition requirements of their destination country independently.

## Admission Model

Admission to Medicine at UCA is governed by the **Distrito Único Andaluz (DUA)**, the centralised admissions system of the Junta de Andalucía. There is no direct application to UCA; all candidates apply through the regional portal and rank their preferred degree-university combinations.

**The nota de admisión formula:**

```
Nota de admisión = (0.6 × Nota media Bachillerato) + (0.4 × EVAU general phase grade)
                 + (best 2 specific-phase subjects × ponderation coefficient)
```

- Base score maximum: 10.0000 points
- Specific-phase bonus maximum: 4.0000 additional points (2 subjects × max 10 × 0.2 coefficient)
- Absolute maximum nota de admisión: 14.0000

**Subject ponderation coefficients at UCA (ANNUAL_UPDATE_REQUIRED):**

| Subject | Coefficient |
|---|---|
| Biology (Biología) | 0.2 |
| Chemistry (Química) | 0.2 |
| Physics (Física) | 0.1 |
| Mathematics II | 0.1 |

To maximise the nota de admisión for Medicine, candidates should prioritise sitting Biology and Chemistry in the EVAU specific phase, as these carry the highest ponderation coefficients (0.2 each) at UCA.

**International students (PCE/UNED pathway):** Students who have completed secondary education outside Spain may access the UCA via the Pruebas de Competencias Específicas (PCE) administered by UNED. PCE results replace the EVAU components of the nota de admisión formula. The same ponderation coefficients apply. Alternatively, EU secondary school graduates may present a Credencial UE for direct equivalence assessment.

## Admission Process

### For Spanish EVAU (PAU) Candidates

1. Complete Bachillerato and register for the EVAU (Selectividad) in your region.
2. Sit both the general phase and, strategically, the specific phase subjects (prioritise Biology and Chemistry for Medicine).
3. Calculate your estimated nota de admisión using the UCA formula.
4. During the DUA application window (ANNUAL_UPDATE_REQUIRED), register on the Junta de Andalucía's admissions portal and rank university-degree combinations.
5. Await pre-asignación (provisional allocation) and confirm your place within the stated deadline.
6. Complete enrolment at UCA's Facultad de Medicina.

### For International Students (PCE/UNED Pathway)

1. Verify your secondary school qualification is eligible for PCE/UNED access.
2. Register with UNED and sit the PCE examinations (typically held in May/June — ANNUAL_UPDATE_REQUIRED).
3. Request your Credencial UNED, which converts your PCE results into a nota de admisión equivalent.
4. Participate in the DUA process through the Junta de Andalucía portal using your Credencial UNED.
5. If accepted, obtain a student visa (non-EU applicants) and complete all enrolment documentation.

Note: Non-EU international students must also verify general Spanish university access requirements with the Spanish Ministry of Education prior to applying.

## Admission Timeline

All dates are ANNUAL_UPDATE_REQUIRED and subject to change by the Junta de Andalucía each cycle.

| Phase | Approximate timing |
|---|---|
| EVAU (ordinary call) | June (ANNUAL_UPDATE_REQUIRED) |
| EVAU (extraordinary call) | July (ANNUAL_UPDATE_REQUIRED) |
| DUA application window opens | Mid-June (ANNUAL_UPDATE_REQUIRED) |
| DUA provisional allocation | Late June / early July (ANNUAL_UPDATE_REQUIRED) |
| DUA definitive allocation | July (ANNUAL_UPDATE_REQUIRED) |
| Enrolment at UCA | July–September (ANNUAL_UPDATE_REQUIRED) |
| PCE/UNED examinations | May–June (ANNUAL_UPDATE_REQUIRED) |
| Academic year begins | September (ANNUAL_UPDATE_REQUIRED) |

## Admission Score Distribution

The nota de corte for Medicine at UCA has followed an upward trend over the last three recorded cycles:

| Intake year | Nota de corte | Round | Source |
|---|---|---|---|
| 2025-2026 | 13.157 | Convocatoria ordinaria | notasdecorte.es / Junta de Andalucía DUA |
| 2024-2025 | 13.696 | Convocatoria ordinaria | DUA — Junta de Andalucía (ANNUAL_UPDATE_REQUIRED) |
| 2023-2024 | 13.584 | Convocatoria ordinaria | DUA — Junta de Andalucía (ANNUAL_UPDATE_REQUIRED) |

The 2025-2026 nota de corte was 13.157, sourced from notasdecorte.es / Junta de Andalucía DUA. This represents a notable decrease from the 2024-2025 figure of 13.696.

**Strategic interpretation:**

The nota de corte dropped significantly in 2025-2026 (from 13.696 to 13.157), indicating a shift in the applicant pool or seat distribution within the DUA system. Historical scores should be treated as orientation references, not predictive thresholds. Students should target a nota de admisión with a meaningful margin above the most recent figure.

For a candidate with a Bachillerato nota media of 9.0 and an EVAU general phase score of 9.5, the base nota would be 9.30. Reaching 13.696 would require the specific-phase bonus contribution to be approximately 4.4 points — which means scoring near 10 in two subjects with 0.2 coefficients (Biology + Chemistry). This illustrates the strategic imperative of maximising specific-phase performance in the highest-weighted subjects.

The extraordinary call (September) nota de corte is typically lower than the ordinary call, as fewer seats remain. Candidates who fall short in the ordinary call should not assume the extraordinary call will provide access — Medicine seats may be fully allocated after the first call.

## Costs and Payment Structure

Tuition fees at UCA are set annually by the Junta de Andalucía (Decreto de precios públicos). Fees vary by residency status.

| Cost concept | Resident in Andalucía | Non-resident in Spain / EU | Source |
|---|---|---|---|
| Annual tuition (approx.) | ~1,000–1,200 EUR (ANNUAL_UPDATE_REQUIRED) | ~1,200–1,600 EUR (ANNUAL_UPDATE_REQUIRED) | Junta de Andalucía |
| Enrolment fees | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | UCA Secretaría |
| Compulsory services | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | UCA |
| Student union fee | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | UCA |

Non-EU international students should verify whether their residency status qualifies them for resident or non-resident fee scales. Public university tuition in Andalucía is significantly lower than private alternatives.

## Scholarships and Financial Aid

**Beca General MEC (Ministerio de Educación y Formación Profesional):**
The national general scholarship is available to students at UCA and covers tuition and a living allowance based on family income and academic performance thresholds. Applications open annually in the second half of July (ANNUAL_UPDATE_REQUIRED) through the MEC portal.

**Becas de la Junta de Andalucía:**
The regional government offers supplementary scholarships for transport, housing, and specific academic needs. These are complementary to the MEC Beca General and require separate application.

**UCA own grants (Ayudas propias de la UCA):**
The university publishes its own emergency and project-based support grants. Availability and amounts vary annually.

**Erasmus+ mobility grants:**
Students undertaking approved international placements may access Erasmus+ stipends. Eligibility depends on destination country and bilateral agreement terms.

International students from outside the EU should investigate whether they qualify for any of the above or whether home-country scholarship programmes apply to study in Spain.

## Accommodation and Cost of Living

Cádiz is a mid-sized coastal city in southwest Spain with a relatively affordable cost of living compared to Madrid or Barcelona.

| Cost concept | Estimated monthly range | Notes |
|---|---|---|
| University halls of residence (colegios mayores) | ANNUAL_UPDATE_REQUIRED | Limited places; apply early |
| Private shared flat (piso compartido) | ~350–550 EUR/room (ANNUAL_UPDATE_REQUIRED) | Most common student option |
| Private studio/single flat | ~550–850 EUR (ANNUAL_UPDATE_REQUIRED) | |
| Meals (university canteen) | ~3–6 EUR/meal (ANNUAL_UPDATE_REQUIRED) | |
| Monthly public transport pass | ANNUAL_UPDATE_REQUIRED | |
| Total estimated monthly living cost | ~700–1,100 EUR (ANNUAL_UPDATE_REQUIRED) | Highly variable by lifestyle |

Cádiz has a compact urban centre and is walkable or cycleable for most student needs. The hospital network extends across the province, so students in clinical years may face commuting to Puerto Real or Jerez de la Frontera.

## International Exchange and Mobility Programs

UCA participates in the **Erasmus+** programme and the **Programa SENECA** (Spanish national student mobility). Both are referenced in the university's academic documentation as available for Medicine students.

Medicine-specific Erasmus partner universities and confirmed Medicine-eligible destinations for a given intake year should be verified with the Facultad de Medicina's international relations office (ANNUAL_UPDATE_REQUIRED), as not all faculty-wide agreements apply to the Medicine degree.

The rotatorio clínico structure in Year 6 imposes scheduling constraints on outgoing mobility placements; students planning international exchanges should plan for Years 3–5.

## MIR Preparation and Professional Outcomes

Graduates of the Grado en Medicina at UCA are eligible to sit the **MIR (Médico Interno Residente)** national examination, which is the compulsory pathway to specialisation in Spain's public health system. The MIR is sat at the national level each year and is independent of the graduate's university of origin.

MIR pass rates specific to UCA graduates: PENDING_CONFIRMATION.

National MIR pass rates and ranking data are published annually by the Spanish Ministry of Health. Strong preparation for the MIR typically requires 1–2 years of dedicated study post-graduation. Graduates from Andalusian public universities have access to a broad public hospital network for clinical experience, which is generally considered a solid foundation for MIR preparation.

Professional employment outcomes post-specialisation: Medicine graduates who complete MIR training can access positions in the Spanish NHS (Sistema Nacional de Salud), private clinics, research institutions, the pharmaceutical industry, and public health agencies.

## Strategic Fit

### Good Fit For

- Candidates whose nota de admisión is reliably above 13.70 — the current threshold leaves little margin for candidates near the 13.696 cut-off.
- Students from Andalucía who want a public university option within the DUA system and have maximised Biology and Chemistry in the EVAU specific phase.
- International students via PCE/UNED who have achieved equivalent PCE scores, particularly in Biology and Chemistry.
- Students comfortable with a Spanish-medium clinical environment and who want early hospital exposure in a mid-sized coastal city.
- Candidates seeking a low-cost public university option with a recognised EU-Directive qualification.

### Less Suitable For

- Candidates whose nota de admisión falls below 13.50 — the probability of admission is very low based on historical trends.
- Students who need flexibility in their application, since UCA is only accessible through the DUA centralised system.
- Students who prioritise a large metropolitan city or research-intensive university environment.
- Candidates who require an English-medium or bilingual track — UCA offers no bilingual option in Medicine.

## Risks and Considerations

**Nota de corte volatility:** The nota de corte at UCA has trended upward over three consecutive cycles. Candidates targeting UCA as their primary option should treat 13.70+ as a realistic threshold for safe admission; scores between 13.50 and 13.70 carry a meaningful risk of exclusion.

**Seat volume:** With approximately 110 seats per year, UCA is one of the smaller public Medicine programmes in Spain by absolute capacity. Even minor year-to-year variation in the applicant pool can shift the nota de corte significantly.

**Regional admissions system:** Admission is exclusively through the DUA. Candidates who miss the DUA window or who submit an incomplete application cannot apply directly to UCA. International students must ensure their PCE/UNED credentials are processed in time for the DUA application deadline.

**Extraordinary call uncertainty:** Seats available in the convocatoria extraordinaria (September) are the residual from the ordinary call and may be very limited or even zero for Medicine. Do not plan admissions strategy around extraordinary call availability.

**Non-EU student access:** Non-EU international students face additional administrative steps (visa, credential homologation) that must be initiated well in advance of the academic year start.

## Important Notes

- All admission dates and nota de corte figures are ANNUAL_UPDATE_REQUIRED.
- Ponderation coefficients for the EVAU specific phase are published annually by the Junta de Andalucía and should be verified at the start of each Bachillerato Year 2.
- Tuition fees are set by the Junta de Andalucía regional decree and are ANNUAL_UPDATE_REQUIRED.
- The Facultad de Medicina is located on the main Cádiz campus. Clinical rotations extend to hospitals in Puerto Real and Jerez de la Frontera.
- Contact: secretaria.medicina@uca.es | +34 956 015 175 | medicina.uca.es

## Key Insight

UCA offers a historically prestigious and affordable public Medicine degree with strong clinical hospital connections across the province of Cádiz. However, the nota de corte has been rising consistently, and at 13.696 in 2024-25 it demands near-perfect academic and EVAU performance. The strategic lever for candidates is maximising Biology and Chemistry in the EVAU specific phase (both weighted at 0.2 at UCA), since these two subjects alone can add up to 4.0 points to the nota de admisión. Candidates who have not optimised their specific-phase subject selection will find it structurally difficult to reach the required threshold regardless of Bachillerato grades.

## Final Takeaway

The Grado en Medicina at the Universidad de Cádiz is a solid, publicly funded six-year programme with over 250 years of medical education heritage, EU Directive recognition, and access to a multi-hospital clinical network. Its public nature makes it cost-effective, and the Distrito Único Andaluz system makes the application process transparent. However, the very high nota de corte — consistently above 13.55 and rising — means this option is realistic only for candidates with demonstrated near-maximum academic performance. International students via PCE/UNED should model their expected nota de admisión carefully before targeting UCA as a primary option, particularly in light of competition from Spanish domestic candidates who may have the advantage of stronger preparation for the EVAU specific phase.

## Frequently Asked Questions

**How is the nota de admisión calculated at UCA?**
The nota de admisión = 0.6 × Bachillerato average + 0.4 × EVAU general phase grade + bonuses from up to 2 specific-phase subjects. Biology and Chemistry each carry a 0.2 coefficient at UCA, allowing a maximum bonus of 4.0 points and a theoretical maximum of 14.0000.

**What is the nota de corte for Medicine at UCA?**
In 2024-25 it was 13.696 (convocatoria ordinaria). The three-year range is 13.560–13.696. This figure is ANNUAL_UPDATE_REQUIRED and changes each cycle based on applicant pool performance.

**Can international students apply via PCE?**
Yes. International students who sit the PCE/UNED examinations receive a Credencial UNED that functions as a nota de admisión equivalent and allows participation in the Andalusian DUA admissions process on the same terms as Spanish domestic candidates.

**What are the tuition fees?**
Tuition is set annually by the Junta de Andalucía. For reference, fees for Andalusian residents have historically been approximately 1,000–1,200 EUR per year; non-resident rates are somewhat higher. Exact figures are ANNUAL_UPDATE_REQUIRED.

**When do I apply?**
Applications for the DUA are submitted after the EVAU ordinary call (approximately June). The exact window is ANNUAL_UPDATE_REQUIRED and published annually by the Junta de Andalucía.

**What are the ponderation coefficients for Medicine at UCA?**
Biology: 0.2 | Chemistry: 0.2 | Physics: 0.1 | Mathematics II: 0.1. These are ANNUAL_UPDATE_REQUIRED and should be confirmed at the start of each academic cycle via the official Junta de Andalucía table.

**What hospitals are used for clinical training?**
Hospital Universitario Puerta del Mar (Cádiz), Hospital Universitario de Puerto Real, and Hospital de Jerez de la Frontera, plus affiliated primary care centres.

**Does UCA have a bilingual Medicine programme?**
No. The degree is taught entirely in Spanish.

**What is the MIR and do UCA graduates sit it?**
The MIR (Médico Interno Residente) is the national competitive exam required to access specialist training in Spain's public health system. All Spanish Medicine graduates must sit the MIR. UCA-specific MIR pass rates are PENDING_CONFIRMATION.
