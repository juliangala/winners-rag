---
id: ulpgc

type: university
subtype: public

name: Universidad de Las Palmas de Gran Canaria
short_name: ULPGC

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Las Palmas de Gran Canaria
  region: Canarias
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
      score: 12.594 # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: Source notasdecorte.es / Canarias
    - intake_year: 2023-2024
      round: convocatoria_ordinaria
      score: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: NULL
    - intake_year: 2022-2023
      round: convocatoria_ordinaria
      score: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: NULL

international_profile:
  international_students_percentage: PENDING_CONFIRMATION
  international_nationalities: []

programs:
  - id: ulpgc-medicina
    campus: Campus Universitario de San Cristóbal — Facultad de Ciencias de la Salud, Las Palmas de Gran Canaria
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
    seats: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
      applicants_per_seat: PENDING_CONFIRMATION
      last_admitted_scores:
        - intake_year: 2025-2026
          round: convocatoria_ordinaria
          score: 12.594 # ANNUAL_UPDATE_REQUIRED
          score_type: nota_de_admision
          notes: Source notasdecorte.es / Canarias
        - intake_year: 2023-2024
          round: convocatoria_ordinaria
          score: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
          score_type: nota_de_admision
          notes: NULL
        - intake_year: 2022-2023
          round: convocatoria_ordinaria
          score: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
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
          score: 12.594 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: notasdecorte.es / Canarias
        - intake_year: 2023-2024
          score: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: EBAU Canarias / ULPGC Preinscripción
        - intake_year: 2022-2023
          score: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: EBAU Canarias / ULPGC Preinscripción
      admission_pathways:
        - eligible_profiles:
            - Spanish EVAU/EBAU (PAU) — all regional variants including Canarian EBAU
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
              notes: 40% of the nota de admisión. In Canarias, the exam is called EBAU. Maximum combined base score with Bachillerato: 10.0000.
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

# Universidad de Las Palmas de Gran Canaria

## Overview

The Universidad de Las Palmas de Gran Canaria (ULPGC) is a public university located in Las Palmas de Gran Canaria, the capital of Gran Canaria and the most populous city in the Canary Islands. Its Facultad de Ciencias de la Salud offers the Grado en Medicina, a six-year, 360-ECTS programme delivered in Spanish.

ULPGC is one of two public universities in the Canary Islands offering a Medicine degree (the other being ULL in La Laguna, Tenerife). While both operate under the same Canarian admissions system — including the nota de admisión (EBAU) formula and the **cupo de residentes canarios** (quota for Canarian residents) — they serve distinct geographic areas: ULPGC serves Gran Canaria and the eastern islands, while ULL serves Tenerife and the western islands.

Admission to Medicine at ULPGC is governed by the nota de admisión formula with no proprietary exam or interview. The cupo de residentes canarios significantly affects access for non-Canarian and international applicants, who compete for a substantially smaller share of available seats. The degree is recognised under EU Directive 2005/36/EC.

## Quick Evaluation

- Admission model: nota de admisión (EBAU formula) — no proprietary exam, no interview
- Seats: PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED — typically in the range of 90–120)
- Nota de corte: PENDING_CONFIRMATION (very high; consistent with other Spanish public Medicine programmes)
- Competitiveness level: very high
- Tuition: set by Gobierno de Canarias (ANNUAL_UPDATE_REQUIRED)
- Teaching language: Spanish
- WFME accreditation: PENDING_CONFIRMATION
- EU Directive qualification: Yes
- Canarian residency quota: Yes — cupo de residentes canarios applies
- International access: via PCE/UNED or Credencial UE; subject to quota restrictions
- Location: Las Palmas de Gran Canaria (island — Gran Canaria; requires travel from mainland Spain)

## Key Facts

| Feature | Detail |
|---|---|
| University | Universidad de Las Palmas de Gran Canaria (ULPGC) |
| City | Las Palmas de Gran Canaria, Canarias |
| Degree | Grado en Medicina |
| Duration | 6 years |
| ECTS | 360 |
| Annual seats | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2025-26 | 12.594 (notasdecorte.es / Canarias) # ANNUAL_UPDATE_REQUIRED |
| Nota de corte 2023-24 | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2022-23 | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Tuition (approx.) | ANNUAL_UPDATE_REQUIRED — Gobierno de Canarias |
| Teaching language | Spanish |
| Admission route | Nota de admisión (EBAU formula) |
| Proprietary exam | No |
| Interview | No |
| Canarian residency quota | Yes — cupo de residentes canarios applies |
| Admissions system | EBAU / ULPGC Preinscripción — Canary Islands |

## Program Options

ULPGC offers a single Medicine programme — the Grado en Medicina — delivered in Spanish at the Facultad de Ciencias de la Salud on the main campus in Las Palmas de Gran Canaria. There is no bilingual track, no distance-learning option, and no parallel programme.

The cupo de residentes canarios significantly shapes access dynamics. A substantial share of available seats is reserved for students who are legal residents of the Canary Islands. Non-Canarian applicants — including most international students — compete for the remaining general seats, which are considerably fewer. International applicants should verify their quota category carefully before applying.

As the Medicine faculty serving Gran Canaria, ULPGC receives applications primarily from the eastern Canary Islands (Gran Canaria, Fuerteventura, Lanzarote). Non-Canarian candidates may apply through the general Spanish admissions pathway.

## Program Structure

The Grado en Medicina at ULPGC is a 6-year (360 ECTS), fully in-person programme:

- **Teaching type:** Presencial (in-person)
- **Total ECTS:** 360
- **Duration:** 6 academic years

The programme follows the standard Spanish medical curriculum structure mandated by EU Directive 2005/36/EC:
- **Years 1–2:** Foundational biomedical sciences (Anatomy, Physiology, Biochemistry, Histology, Genetics, Microbiology, Immunology, Pharmacology foundations)
- **Years 3–5:** Clinical sciences (Internal Medicine, Surgery, Obstetrics and Gynaecology, Paediatrics, Psychiatry, Neurology, Radiology, and integrated clinical placements)
- **Year 6:** Rotatorio clínico — full-year supervised clinical rotation across all major specialities

The Trabajo Fin de Grado (TFG) is completed in the final year. All clinical placements occur within Gran Canaria's public hospital network.

## Teaching Methodology

ULPGC's Medicine programme follows the standard Spanish public medical school model: lecture-based foundational science instruction in Years 1–2, with clinical disciplines integrated progressively from Year 3. Laboratory and clinical skills facilities are available within the Facultad de Ciencias de la Salud.

The final year (Year 6) is structured as a full-time supervised rotatorio clínico at the primary affiliated teaching hospital (Hospital Universitario de Gran Canaria Doctor Negrín) and other affiliated centres. Early clinical contact and skills training are integrated from mid-degree.

Gran Canaria's position as the commercial and administrative capital of the eastern Canary Islands means the city has a large and complex public healthcare infrastructure — providing diverse clinical training opportunities.

## Clinical Training

Clinical training at ULPGC takes place within Gran Canaria's public hospital network:

- **Hospital Universitario de Gran Canaria Doctor Negrín** (Las Palmas de Gran Canaria) — primary teaching hospital; one of the two major tertiary care centres in the Canary Islands
- **Hospital Universitario Insular de Gran Canaria** (Las Palmas de Gran Canaria) — secondary teaching hospital
- **Primary care centres (Centros de Salud)** across Gran Canaria — for family medicine and community health rotations

The rotatorio clínico in Year 6 covers surgery and specialties, obstetrics and gynaecology, paediatrics, psychiatry, internal medicine, family and community medicine, and emergency medicine. All clinical training is island-based on Gran Canaria.

## International Recognition and Opportunities

The Grado en Medicina at ULPGC is an official Spanish state degree recognised under European Medical Directive 2005/36/EC, providing automatic professional recognition across all EU and EEA member states.

WFME (World Federation for Medical Education) accreditation: PENDING_CONFIRMATION.

ULPGC participates in the **Erasmus+** programme and the **Programa SENECA** for national student mobility. Medicine-specific Erasmus mobility destinations must be confirmed annually with the Facultad de Ciencias de la Salud's international office (ANNUAL_UPDATE_REQUIRED).

The ULPGC degree covers all EU-mandated medical competencies and is taught in Spanish.

## Admission Model

Admission to Medicine at ULPGC is governed by the **EBAU (Evaluación del Bachillerato para el Acceso a la Universidad)** — the Canarian equivalent of the EVAU — coordinated through ULPGC's preinscripción system.

**The nota de admisión formula:**

```
Nota de admisión = (0.6 × Nota media Bachillerato) + (0.4 × EBAU general phase grade)
                 + (best 2 specific-phase subjects × ponderation coefficient)
```

- Base score maximum: 10.0000 points
- Specific-phase bonus maximum: 4.0000 additional points
- Absolute maximum nota de admisión: 14.0000

**Subject ponderation coefficients at ULPGC for Medicine (ANNUAL_UPDATE_REQUIRED):**

| Subject | Coefficient |
|---|---|
| Biology (Biología) | 0.2 |
| Chemistry (Química) | 0.2 |
| Physics (Física) | 0.1 |
| Mathematics II | 0.1 |

**Critical admission factor — Cupo de residentes canarios:**

Like ULL, ULPGC applies the **regional residency quota** that reserves a substantial share of Medicine seats for legal residents of the Canary Islands:

- **Canarian residents** have access to the full quota plus general seat pool.
- **Non-Canarian Spanish students and most international students** compete only for the general (non-quota) seats — a smaller share of total capacity.
- **International students** must verify their legal residency status in the Canary Islands to determine which quota category applies to them.

The effective nota de corte for non-residents may therefore be higher than the published overall nota de corte, as competition for general-pool seats is more concentrated.

**International students (PCE/UNED pathway):** International candidates access ULPGC through the PCE/UNED examination pathway, which generates a Credencial UNED equivalent to the nota de admisión. The same ponderation coefficients apply. International students not residing in the Canary Islands compete for general-pool seats only.

## Admission Process

### For Spanish EVAU/EBAU Candidates

1. Complete Bachillerato and sit the EBAU (Canary Islands) or EVAU (other Spanish regions).
2. Sit the specific phase — prioritise Biology and Chemistry (both 0.2 coefficient).
3. Calculate your nota de admisión using ULPGC's ponderation table.
4. Determine your quota category (Canarian resident vs. general pool).
5. Apply through ULPGC's preinscripción portal during the official application window (ANNUAL_UPDATE_REQUIRED).
6. Await provisional and definitive assignment results. Confirm enrolment within the stated deadline.

### For International Students (PCE/UNED Pathway)

1. Verify PCE/UNED eligibility for your secondary qualification.
2. Register with UNED and sit PCE examinations (typically May–June — ANNUAL_UPDATE_REQUIRED).
3. Obtain the Credencial UNED as the nota de admisión equivalent.
4. **Verify quota status:** Most international applicants not residing in the Canary Islands compete for general (non-quota) seats only.
5. Apply through ULPGC's preinscripción portal with the Credencial UNED.
6. If admitted, arrange student visa (non-EU applicants) and complete enrolment documentation.

## Admission Timeline

All dates are ANNUAL_UPDATE_REQUIRED.

| Phase | Approximate timing |
|---|---|
| EBAU (ordinary call — Canarias) | June (ANNUAL_UPDATE_REQUIRED) |
| EBAU (extraordinary call) | July (ANNUAL_UPDATE_REQUIRED) |
| ULPGC preinscripción window opens | Mid-June (ANNUAL_UPDATE_REQUIRED) |
| Provisional assignment | Late June / early July (ANNUAL_UPDATE_REQUIRED) |
| Definitive assignment | July (ANNUAL_UPDATE_REQUIRED) |
| Enrolment formalisation | July–September (ANNUAL_UPDATE_REQUIRED) |
| PCE/UNED examinations | May–June (ANNUAL_UPDATE_REQUIRED) |
| Academic year begins | September (ANNUAL_UPDATE_REQUIRED) |

## Admission Score Distribution

Nota de corte data for ULPGC Medicine:

| Intake year | Nota de corte | Round | Notes |
|---|---|---|---|
| 2025-2026 | **12.594** | Convocatoria ordinaria | notasdecorte.es / Canarias # ANNUAL_UPDATE_REQUIRED |
| 2023-2024 | PENDING_CONFIRMATION | Convocatoria ordinaria | ANNUAL_UPDATE_REQUIRED |
| 2022-2023 | PENDING_CONFIRMATION | Convocatoria ordinaria | ANNUAL_UPDATE_REQUIRED |

Source: notasdecorte.es / EBAU Canarias / ULPGC Preinscripción (ANNUAL_UPDATE_REQUIRED)

**Strategic interpretation:**

The verified 2025-26 nota de corte for ULPGC Medicine is 12.594 (source: notasdecorte.es / Canarias), placing it in the medium-competitiveness band — notably lower than previously estimated ranges (13.5–13.9). This represents a significant change in competitive dynamics. The **cupo de residentes canarios** remains the most strategically significant variable for non-Canarian applicants, as general-pool seats are fewer in number.

The **cupo de residentes canarios** is the most strategically significant variable for non-Canarian applicants. Non-residents compete for a subset of total seats, which may create a higher effective threshold in the general pool than the published nota de corte for the overall cohort would suggest.

The dual-university structure of Canarian Medicine (ULL on Tenerife, ULPGC on Gran Canaria) means that Canarian applicants effectively choose between two institutions serving their geographic area, while non-Canarian and international applicants may apply to either or both, but face quota constraints at both.

## Costs and Payment Structure

Tuition fees at ULPGC are set annually by the Gobierno de Canarias. Rates are among the lowest in Spain for public universities.

| Cost concept | Canarian resident | Non-resident / EU | Source |
|---|---|---|---|
| Annual tuition (approx.) | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | Gobierno de Canarias |
| Enrolment and administrative fees | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | ULPGC |
| Compulsory services | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | ULPGC |
| Student union fee | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | ULPGC |

As with all Canarian public universities, tuition is set by regional government decree (ANNUAL_UPDATE_REQUIRED). Canarian residents typically benefit from subsidised rates. Non-residents pay higher but still publicly regulated fees.

## Scholarships and Financial Aid

**Beca General MEC:**
ULPGC students are eligible for the national Beca General from the Ministerio de Educación y Formación Profesional. Applications open annually in July (ANNUAL_UPDATE_REQUIRED) via the MEC portal.

**Becas del Gobierno de Canarias:**
The regional government offers supplementary scholarships, including transport subsidies relevant to island living (intra-island, inter-island, and mainland travel). These are published annually (ANNUAL_UPDATE_REQUIRED).

**ULPGC own grants:**
The university provides emergency support and academic merit grants. Availability and amounts are ANNUAL_UPDATE_REQUIRED.

**Erasmus+ mobility:**
Students may access Erasmus+ funding for confirmed outgoing placements. Medicine-specific destinations must be confirmed annually with the Facultad.

## Accommodation and Cost of Living

Las Palmas de Gran Canaria is the largest city in the Canary Islands and one of Spain's largest cities by population. It offers a full urban infrastructure with moderate living costs, warm climate year-round, and a cosmopolitan Atlantic character.

| Cost concept | Estimated monthly range | Notes |
|---|---|---|
| University halls of residence (colegios mayores / residencias) | ANNUAL_UPDATE_REQUIRED | Limited capacity |
| Private shared flat (piso compartido) | ~350–550 EUR/room (ANNUAL_UPDATE_REQUIRED) | Most common student option |
| Private studio | ~550–800 EUR (ANNUAL_UPDATE_REQUIRED) | |
| University canteen meals | ~3–6 EUR/meal (ANNUAL_UPDATE_REQUIRED) | |
| Monthly public transport (Las Palmas) | ANNUAL_UPDATE_REQUIRED | Bus network available |
| Flights to mainland Spain | ANNUAL_UPDATE_REQUIRED | ~2–3 hours; budget for periodic travel |
| Total estimated monthly living cost | ~750–1,150 EUR (ANNUAL_UPDATE_REQUIRED) | Highly variable |

Las Palmas de Gran Canaria benefits from year-round warm temperatures and a larger urban infrastructure than La Laguna. Students from mainland Spain should budget for flight costs to return home during academic breaks.

## International Exchange and Mobility Programs

ULPGC participates in **Erasmus+** and the **Programa SENECA** for national student mobility. Medicine-specific Erasmus partner universities must be confirmed annually with the Facultad de Ciencias de la Salud's international office (ANNUAL_UPDATE_REQUIRED).

The island context introduces additional logistical considerations for outgoing mobility placements, as students travel from Gran Canaria to mainland Europe or mainland Spain. Year 6 clinical rotations on Gran Canaria preclude international mobility in the final year; students should plan exchange placements for Years 3–5.

## MIR Preparation and Professional Outcomes

All ULPGC Medicine graduates are eligible for the **MIR (Médico Interno Residente)** national examination.

MIR pass rates specific to ULPGC graduates: PENDING_CONFIRMATION.

Clinical training at Hospital Universitario de Gran Canaria Doctor Negrín and Hospital Universitario Insular de Gran Canaria provides exposure to comprehensive tertiary care in a large regional healthcare system. Students completing their degree in Gran Canaria who wish to specialise or practice in mainland Spain will sit the MIR nationally and, if successful, may be assigned to any Spanish hospital for residency.

Post-MIR, graduates may practise in Spain's Sistema Nacional de Salud, private medicine, research, or public health.

## Strategic Fit

### Good Fit For

- Canarian residents of Gran Canaria and the eastern islands who benefit from the cupo de residentes and want to study near home.
- Candidates with a high nota de admisión who are attracted to studying in a large, warm Atlantic city.
- International students who are already legally resident in the Canary Islands and qualify for the residency quota.
- Students seeking publicly funded, EU-Directive-recognised Medicine at very low tuition costs (Canarian residents).
- Candidates comfortable with island-based clinical training in Gran Canaria's hospital network.

### Less Suitable For

- Non-Canarian Spanish students and international students not resident in the Canary Islands — quota constraints reduce effective seat availability and raise the competitive threshold.
- Students who want to study in mainland Spain or who value proximity to the Spanish mainland.
- Candidates who require a bilingual or English-medium programme.
- Students who want to apply to multiple institutions without quota constraints — the Canary Islands system is structured around regional residence.

## Risks and Considerations

**Cupo de residentes canarios:** As with ULL, the residency quota at ULPGC is the primary strategic risk for non-Canarian and international applicants. General-pool seats (accessible to non-residents) are a minority of total capacity. International students must determine their quota category — and the effective nota de corte threshold for their pool — before committing to ULPGC as a target.

**Nota de corte data:** All nota de corte figures for ULPGC Medicine are currently PENDING_CONFIRMATION. Candidates should consult the ULPGC admissions portal directly for the most recent data (ANNUAL_UPDATE_REQUIRED).

**Seat count uncertainty:** The number of available Medicine seats at ULPGC is PENDING_CONFIRMATION and ANNUAL_UPDATE_REQUIRED. Seat counts in the Canary Islands can be subject to regional government decisions.

**Island-specific costs:** Recurring flight costs for mainland-connected students and the island's import-dependent economy add marginal living costs compared to mainland Spanish universities.

**Clinical training geography:** All clinical placements are on Gran Canaria. Students who ultimately wish to practise or specialise in mainland Spain will face relocation after completing the degree and MIR.

## Important Notes

- The cupo de residentes canarios applies at ULPGC and materially affects seat access for non-Canarian applicants. Verify quota category before applying.
- All nota de corte and seat count data is PENDING_CONFIRMATION and ANNUAL_UPDATE_REQUIRED — consult the ULPGC admissions portal.
- Tuition is set by the Gobierno de Canarias and is ANNUAL_UPDATE_REQUIRED.
- Ponderation coefficients for the EBAU specific phase are published annually by the Canarian education authorities.
- The Facultad de Ciencias de la Salud is located at the Campus Universitario de San Cristóbal, Las Palmas de Gran Canaria.
- University website: ulpgc.es

## Key Insight

ULPGC's Medicine programme serves Gran Canaria and the eastern Canary Islands within the dual-university Canarian Medicine system. Its strategic profile closely parallels ULL's — both are public, Spanish-only, very high-competitiveness programmes with cupo de residentes quotas and island-based clinical training. The principal differentiator is geography: ULPGC is the option for students oriented toward Gran Canaria and the eastern islands, while ULL serves Tenerife and the west. For non-Canarian and international applicants, the cupo de residentes is the overriding strategic concern: access to ULPGC Medicine for non-residents is structurally harder than the published nota de corte suggests, because competition is concentrated in a smaller general-pool seat allocation.

## Final Takeaway

The Grado en Medicina at the Universidad de Las Palmas de Gran Canaria is a publicly funded, EU-Directive-recognised, six-year programme delivered in Las Palmas de Gran Canaria — Spain's Atlantic island metropolis. The programme operates under the Canary Islands' EBAU admissions system and is subject to the cupo de residentes canarios, which significantly constrains access for non-Canarian and most international applicants. Nota de corte data is pending confirmation for recent cycles; candidates should consult ULPGC's admissions portal for current figures. For Gran Canarian residents with strong nota de admisión scores, ULPGC offers a cost-effective pathway to a recognised Medicine degree with local clinical training. For non-residents and international applicants, the quota system demands careful verification of quota category and realistic modeling of the general-pool nota de corte threshold before targeting ULPGC as a primary application.

## Frequently Asked Questions

**How is the nota de admisión calculated at ULPGC?**
Nota de admisión = 0.6 × Bachillerato average + 0.4 × EBAU general phase grade + bonuses from up to 2 specific-phase subjects. In the Canary Islands, the access exam is called EBAU. Biology and Chemistry carry a 0.2 coefficient each, enabling a maximum bonus of 4.0 points and a theoretical maximum of 14.0000.

**What is the nota de corte for Medicine at ULPGC?**
The verified nota de corte for 2025-26 is 12.594 (source: notasdecorte.es / Canarias). This is ANNUAL_UPDATE_REQUIRED — consult the ULPGC admissions portal for current data. Historical data for 2023-24 and 2022-23 is PENDING_CONFIRMATION.

**What is the cupo de residentes canarios?**
A quota system that reserves a significant share of university seats for legal residents of the Canary Islands. Non-Canarian students and most international students compete for the remaining general seats, which are fewer. This raises the effective competitive threshold for non-residents.

**Can international students apply via PCE?**
Yes. PCE/UNED generates a Credencial UNED equivalent to the nota de admisión. International students not residing in the Canary Islands compete for general-pool (non-quota) seats only — a smaller portion of total capacity.

**How many seats does ULPGC Medicine have?**
PENDING_CONFIRMATION. ANNUAL_UPDATE_REQUIRED — check the ULPGC admissions portal.

**What are the tuition fees?**
Set annually by the Gobierno de Canarias. Canarian residents benefit from subsidised rates. Exact figures are ANNUAL_UPDATE_REQUIRED.

**When do I apply?**
Through ULPGC's preinscripción portal after the EBAU ordinary call in June. Exact dates are ANNUAL_UPDATE_REQUIRED.

**What hospitals are used for clinical training?**
Hospital Universitario de Gran Canaria Doctor Negrín and Hospital Universitario Insular de Gran Canaria (both in Las Palmas de Gran Canaria), plus primary care centres across Gran Canaria.

**Is there a bilingual track?**
No. The degree is delivered entirely in Spanish.

**What is the MIR?**
The MIR (Médico Interno Residente) is the national competitive exam for access to medical specialisation in Spain's public health system. All ULPGC Medicine graduates are eligible. MIR pass rates for ULPGC graduates are PENDING_CONFIRMATION.

**How does ULPGC compare to ULL?**
Both are Canarian public universities with Medicine degrees, both apply the cupo de residentes canarios, and both are subject to the EBAU admissions system. ULPGC is on Gran Canaria (eastern islands); ULL is on Tenerife (western islands). ULL increased seats to 130 in 2024-25; ULPGC seat count is PENDING_CONFIRMATION. The strategic profile and admission constraints are substantially similar for non-Canarian applicants.
