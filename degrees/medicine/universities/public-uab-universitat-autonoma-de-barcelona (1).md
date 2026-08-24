---
id: uab

type: university
subtype: public

name: Universitat Autònoma de Barcelona
short_name: UAB

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Bellaterra (Cerdanyola del Vallès)
  region: Catalunya
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - medium_competitiveness
  - research_oriented
  - strong_clinical_exposure
  - bilingual_program
  - international_friendly

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
        label: fase_ordinaria
        application_deadline: ANNUAL_UPDATE_REQUIRED
        exam_date: ANNUAL_UPDATE_REQUIRED
        results_date: ANNUAL_UPDATE_REQUIRED
        deposit_deadline: NULL

      - round: 2
        label: fase_extraordinaria
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
    - PCE/UNED (Credencial UNEDasiss)
    - Credencial UE
    - PAU Catalunya (Selectivitat)
    - Direct homologation (select countries)

competitiveness:
  level: high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: 385 # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION

  last_admitted_scores:
    - intake_year: 2025-2026
      round: fase_ordinaria
      score: 12.389
      score_type: nota_de_admision
      notes: Verified nota de tall for 2025-26. ANNUAL_UPDATE_REQUIRED.

    - intake_year: 2024-2025
      round: fase_ordinaria
      score: PENDING_CONFIRMATION
      score_type: nota_de_admision
      notes: NULL

    - intake_year: 2023-2024
      round: fase_ordinaria
      score: PENDING_CONFIRMATION
      score_type: nota_de_admision
      notes: NULL

international_profile:
  international_students_percentage: PENDING_CONFIRMATION
  international_nationalities: []

programs:
  - id: uab-medicina

    campus: Facultat de Medicina — Campus de la UAB, Bellaterra (Cerdanyola del Vallès); clinical units across Barcelona metropolitan area

    modality: standard

    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - medium_competitiveness
      - research_oriented
      - strong_clinical_exposure
      - bilingual_program
      - international_friendly

    teaching_languages:
      - Catalan
      - Spanish
      - English (partial — select subjects and international student contexts)

    regional_language_possible: true
    regional_language: Catalan

    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL

    seats: 385 # ANNUAL_UPDATE_REQUIRED

    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 385
      applicants_per_seat: PENDING_CONFIRMATION

      last_admitted_scores:
        - intake_year: 2025-2026
          round: fase_ordinaria
          score: 12.389
          score_type: nota_de_admision
          notes: Verified nota de tall. ANNUAL_UPDATE_REQUIRED.

        - intake_year: 2024-2025
          round: fase_ordinaria
          score: PENDING_CONFIRMATION
          score_type: nota_de_admision
          notes: NULL

        - intake_year: 2023-2024
          round: fase_ordinaria
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
          score: 12.389
          round: fase_ordinaria
          source: notasdecorte.es (2025-26 data) # ANNUAL_UPDATE_REQUIRED — verify at accesuniversitats.gencat.cat

        - intake_year: 2024-2025
          score: PENDING_CONFIRMATION
          round: fase_ordinaria
          source: PENDING_CONFIRMATION

        - intake_year: 2023-2024
          score: PENDING_CONFIRMATION
          round: fase_ordinaria
          source: PENDING_CONFIRMATION

      admission_pathways:
        - eligible_profiles:
            - Catalan PAU (Selectivitat)
            - EVAU from other Spanish regions
            - International via PCE/UNED (Credencial UNEDasiss)
            - International via Credencial UE
            - Direct homologation (select countries)

          components:
            - component: nota_media_bachillerato
              enabled: true
              role: weighted
              weight: 60
              grade_source: bachillerato_media
              notes: 60% of the nota de admisión.

            - component: evau_general_phase
              enabled: true
              role: weighted
              weight: 40
              grade_source: evau_fase_general
              notes: 40% of the nota de admisión. Maximum combined base score with Bachillerato is 10.0000.

            - component: evau_specific_phase_bonus
              enabled: true
              role: bonus_only
              maximum_bonus: 4.0
              grade_source: evau_fase_especifica
              notes: Best 2 eligible subjects count. Coefficient 0.1 or 0.2 per subject. Maximum nota de admisión is 14.0000. Coefficients ANNUAL_UPDATE_REQUIRED — verify at accesuniversitats.gencat.cat.
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED
                Chemistry:      0.2 # ANNUAL_UPDATE_REQUIRED
                Physics:        0.1 # ANNUAL_UPDATE_REQUIRED
                Mathematics_II: 0.1 # ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---

# Universitat Autònoma de Barcelona

## Overview

The Universitat Autònoma de Barcelona (UAB) is one of Spain's leading research universities, founded in 1968, and its Facultat de Medicina is accredited with the highest quality rating (Excel·lent) by AQU Catalunya — the Catalan university quality agency — and holds confirmed WFME (World Federation for Medical Education) accreditation. The Grado en Medicina at UAB is among the largest-intake public Medicine programmes in Spain, with 385 seats per year, offered at the self-contained Campus de la UAB in Bellaterra (Cerdanyola del Vallès), with clinical training distributed across five major hospital teaching units in the Barcelona metropolitan area.

Admission is managed through the Catalan accesuniversitats.gencat.cat portal. The nota de tall for 2025-26 was 12.389 — the lowest among major Barcelona public medicine programmes — making UAB the most accessible of the three principal Barcelona public medical faculties (UB, UAB) for candidates with strong but not exceptional scores. The programme is taught primarily in Catalan and Spanish, with English integration in select subjects.

## Quick Evaluation

- **Degree:** Grau en Medicina — 6 years — 360 ECTS
- **Seats:** 385 (ANNUAL_UPDATE_REQUIRED)
- **Admission mechanism:** Nota de admisión (nota de tall model); no exam, no interview
- **Competitiveness:** High — nota de tall 12.389 for 2025-26 (ANNUAL_UPDATE_REQUIRED)
- **Nota de tall (2025-26):** 12.389 out of 14.000
- **Tuition (approximate):** ~1,400–2,000 EUR/year for EU residents (Catalan tariff, ANNUAL_UPDATE_REQUIRED)
- **Clinical training from:** Year 3 — across five principal hospital teaching units
- **Teaching language:** Catalan (primary), Spanish, English (partial)
- **WFME accreditation:** Confirmed (AQU Catalunya — Excel·lent rating)
- **International access:** Via PCE/UNED Credencial or Credencial UE through accesuniversitats portal

## Key Facts

| Parameter | Value |
|---|---|
| Official name | Universitat Autònoma de Barcelona |
| Degree | Grau en Medicina |
| Duration | 6 years (360 ECTS) |
| Annual seats | 385 (ANNUAL_UPDATE_REQUIRED) |
| Preclinical campus | Campus de la UAB, Bellaterra (Cerdanyola del Vallès) |
| Clinical units | Germans Trias i Pujol (Badalona), Parc Taulí (Sabadell), Sant Pau (Barcelona), Vall d'Hebron (Barcelona) + basic sciences unit (Bellaterra) |
| Teaching language | Catalan (primary); Spanish; English (partial) |
| Admission system | Catalan PAU / accesuniversitats.gencat.cat |
| No proprietary exam | Correct |
| No interview | Correct |
| Nota de tall 2025-26 | 12.389 (ANNUAL_UPDATE_REQUIRED) |
| WFME accreditation | Confirmed (AQU Catalunya — Excel·lent) |
| AQU quality rating | Excel·lent |
| Tuition (EU, indicative) | ~1,400–2,000 EUR/year (ANNUAL_UPDATE_REQUIRED) |
| Tuition (non-EU, indicative) | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Founded | 1968 |

## Program Options

UAB offers a single Grau en Medicina track. There is no separate bilingual cohort, no English-medium programme, and no alternative campus track. All 385 students share the same curriculum structure, taught in Catalan and Spanish.

Preclinical years (1–2) are taught at the UAB Campus de la UAB in Bellaterra, a self-contained university campus with residential infrastructure. Clinical years (3–6) are distributed across the five principal Unitats Docents Hospitalàries (UDH) in the Barcelona metropolitan area.

The large annual intake (385 seats) is notable: it is significantly larger than typical Medicine cohorts at comparable research universities. This reflects a deliberate policy of providing broad access to public medical education in Catalunya.

## Program Structure

The Grau en Medicina at UAB is structured across 6 academic years, totalling 360 ECTS:

**Phase 1 — Preclínica (Years 1–2):** Core biomedical sciences at the Campus de la UAB (Bellaterra). Subjects include Anatomy, Physiology, Biochemistry, Cell Biology, Histology, Immunology, Microbiology, Pharmacology, and Pathology. Clinical skills and simulated patient contact are introduced progressively.

**Phase 2 — Clínica (Years 3–6):** Students are assigned to one of the Unitats Docents Hospitalàries (UDH). The UDH delivers all clinical specialty teaching in a hospital-embedded setting. Year 6 includes a structured clinical rotation (Pràcticum Clínic / Rotatori) across multiple departments.

**TFG (Treball de Fi de Grau):** Mandatory final-year research or clinical project. Language of presentation: PENDING_CONFIRMATION.

**Electives:** Optional subject credits are available. Exact ECTS volume: PENDING_CONFIRMATION.

## Teaching Methodology

UAB Medicine uses a traditional lecture-based structure in preclinical years, supplemented by laboratory practice, small-group seminars, and progressive simulation-based clinical skills training. The campus has clinical skills and simulation laboratories supporting early competency development.

From Year 3, all teaching shifts to hospital-embedded clinical instruction within the assigned UDH. Small group teaching (seminaris, casos clínics) supplements specialist clinical supervision throughout the clinical phase.

UAB's research culture — supported by proximity to the Institut d'Investigació Germans Trias i Pujol (IGTP), Institut de Recerca de l'Hospital de la Santa Creu i Sant Pau, and VHIR (Vall d'Hebron Institut de Recerca) — means that students in clinical placements are exposed to active research environments.

English-language integration is present in select subjects. The degree is not English-taught, but scientific literature and some content is delivered in English, progressively building literacy for international postgraduate contexts.

## Clinical Training

UAB Medicine's clinical training is structured around five principal Unitats Docents Hospitalàries (UDH), each a major hospital with its own research institute. This distributed network covers northern and north-eastern Barcelona metropolitan area hospitals.

**Principal Unitats Docents Hospitalàries (confirmed):**

- **Unitat Docent Hospital Universitari Germans Trias i Pujol** (Badalona) — major tertiary hospital; houses Institut d'Investigació Germans Trias i Pujol (IGTP)
- **Unitat Docent Parc Taulí** (Sabadell) — large hospital serving the Vallès Occidental; houses Institut de Recerca i Innovació Parc Taulí (I3PT)
- **Unitat Docent Hospital de la Santa Creu i Sant Pau** (Barcelona) — historic Barcelona teaching hospital, UNESCO World Heritage site building; houses Institut de Recerca de Sant Pau
- **Unitat Docent Hospital Universitari Vall d'Hebron** (Barcelona) — one of Spain's largest hospital complexes, designated national referral centre for multiple specialties; houses VHIR (Vall d'Hebron Institut de Recerca)
- **Unitat Docent de Ciències Morfològiques Bàsiques** (Bellaterra campus) — anatomy and morphological sciences unit at the preclinical campus

Additional primary care and community health centre placements are included across the curriculum (ANNUAL_UPDATE_REQUIRED — network subject to annual revision).

Students are assigned to one primary UDH from Year 3. The assignment process depends on administrative and merit-based criteria (ANNUAL_UPDATE_REQUIRED).

Vall d'Hebron's status as one of Spain's largest and most complex hospital complexes — covering trauma, transplants, rare diseases, and paediatrics — provides UAB students assigned to that unit with exposure to extremely high clinical complexity.

## International Recognition and Opportunities

UAB Medicine holds confirmed WFME quality accreditation through AQU Catalunya (Agència per a la Qualitat del Sistema Universitari de Catalunya). AQU awarded the programme its highest quality rating: **Excel·lent**. This is a significant formal indicator of programme quality and is directly relevant to graduates planning international medical careers.

The WFME accreditation via AQU is specifically important for graduates seeking postgraduate medical training in countries that require WFME-listed institution graduation, including the UK (GMC), USA (ECFMG), Canada, Australia, and others.

The UAB degree (Grau en Medicina, MECES Level 3) is recognised across the EU under Directive 2005/36/EC.

**International exchange:** UAB Medicina participates in the Erasmus+ programme. The Facultat de Medicina manages Medicine-specific mobility agreements. Exchange periods are typically available from Year 3 (clinical phase). ANNUAL_UPDATE_REQUIRED — verify Medicine-specific Erasmus slots at the faculty mobility office.

UAB has Erasmus+ partnerships with multiple European medical faculties and participates in the Europaeum network (alongside Oxford, Leiden, Paris I, etc.), which may generate additional collaborative and research opportunities.

## Admission Model

UAB Medicine is part of Catalunya's public university admissions system, coordinated through the accesuniversitats.gencat.cat portal. Admission is determined exclusively by the nota de admisión (nota de tall in Catalan) — there is no proprietary entrance exam, no interview, and no portfolio component.

**The nota de admisión formula:**

```
Nota de admisión = 0.6 × Nota media de Bachillerato
                 + 0.4 × Nota PAU (fase general)
                 + up to 4.0 bonus points from PAU fase específica
```

- **Base score maximum:** 10.0000 (Bachillerato + PAU general phase combined)
- **Maximum nota de admisión:** 14.0000 (with full specific-phase bonus)
- **Specific phase:** Best 2 eligible subjects count. Each subject grade is multiplied by the UAB ponderation coefficient (0.1 or 0.2). Biology and Chemistry receive 0.2 (ANNUAL_UPDATE_REQUIRED — verify at accesuniversitats.gencat.cat each year).

**Access routes:**
- PAU Catalunya (Selectivitat): standard route for Catalan Batxillerat students
- EVAU from other Spanish regions: valid; equivalent calculation applies
- International via PCE/UNED (Credencial UNEDasiss): valid; applies via accesuniversitats portal
- International via Credencial UE: valid
- Direct homologation (select countries): valid

## Admission Process

### For Catalan PAU students

1. Complete Batxillerat and register for PAU (Selectivitat).
2. Sit PAU: mandatory general phase + optional specific phase (strongly recommended — up to 4 bonus points).
3. Receive nota de admisión.
4. Submit preinscripció through accesuniversitats.gencat.cat during the designated window (ANNUAL_UPDATE_REQUIRED for exact dates).
5. List UAB Medicina in your degree preferences.
6. Await results of the fase ordinaria assignment.
7. If not admitted in fase ordinaria, apply for fase extraordinaria.
8. If admitted: complete matriculació within the published deadline.

### For students from other Spanish regions

1. Sit EVAU in your region. Confirm that your specific-phase results are accepted by the Catalan system with the appropriate ponderation coefficients for Medicine at UAB.
2. Apply through accesuniversitats.gencat.cat with your nota de admisión.
3. Compete in the same applicant pool as Catalan students.

### For international PCE/UNED students

1. Obtain a UNEDasiss Credencial. Sit PCE in Biology and Chemistry (coefficient 0.2 each; ANNUAL_UPDATE_REQUIRED).
2. Apply through accesuniversitats.gencat.cat with the Credencial calificación.
3. Verify Catalan-specific requirements for international applicants at accesuniversitats (ANNUAL_UPDATE_REQUIRED).
4. If admitted: arrange NIE, visa if applicable, and housing.

## Admission Timeline

All dates are approximate and ANNUAL_UPDATE_REQUIRED. Verify each year at accesuniversitats.gencat.cat and the UAB Faculty of Medicine admissions page.

| Phase | Approximate Period |
|---|---|
| PAU Catalunya (Selectivitat) — ordinary | June (ANNUAL_UPDATE_REQUIRED) |
| PAU Catalunya (Selectivitat) — extraordinary | July (ANNUAL_UPDATE_REQUIRED) |
| accesuniversitats preinscripció ordinaria | June–July (ANNUAL_UPDATE_REQUIRED) |
| Results fase ordinaria | July (ANNUAL_UPDATE_REQUIRED) |
| Enrolment (matriculació) window | July–September (ANNUAL_UPDATE_REQUIRED) |
| Results fase extraordinaria | August–September (ANNUAL_UPDATE_REQUIRED) |
| Academic year begins | September (ANNUAL_UPDATE_REQUIRED) |
| PCE/UNED sessions | February and June (ANNUAL_UPDATE_REQUIRED) |

## Admission Score Distribution

The nota de tall for UAB Medicina in 2025-26 was **12.389** out of 14.000. This is the lowest among the major Barcelona-area public Medicine programmes, making UAB the most accessible Catalan public Medicine faculty for candidates with solid but not exceptional notas de admisión.

**What this means strategically:**

A nota de admisión of 12.389 in 2025-26 was the minimum required for admission. For planning purposes, candidates should target a nota de admisión of at least 12.6–12.8 to have a reasonable buffer above the historical threshold — which can shift in either direction depending on the applicant pool.

To reach the UAB competitive range (12.3–12.8), candidates typically need:
- A Bachillerato average of approximately 8.0–9.0
- A solid PAU general phase result (7.5+)
- Specific-phase results in Biology and Chemistry in the 8.0–10.0 range (coefficient 0.2 each)

**Ponderation coefficients for Medicine at UAB (ANNUAL_UPDATE_REQUIRED — verify at accesuniversitats.gencat.cat):**

| Subject | Coefficient |
|---|---|
| Biology | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Chemistry | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Physics | 0.1 (ANNUAL_UPDATE_REQUIRED) |
| Mathematics II | 0.1 (ANNUAL_UPDATE_REQUIRED) |

**Score trend:** The nota de tall at UAB has historically been lower than at UB for Medicine in the same intake year. With 385 seats — an unusually large cohort — more students are admitted from a slightly broader score range. This does not mean UAB is easy to access; it remains very competitive. However, it represents a meaningful strategic opportunity for candidates whose nota de admisión places them in the 12.5–12.9 range, where UCM, UAM, and UB Medicine are typically out of reach.

**For PCE/UNED international students:** The same formula applies. Biology and Chemistry PCE results at coefficient 0.2 each are the primary levers. Reaching 12.389 from a UNEDasiss base requires strong — though not perfect — PCE scores, making UAB a more realistic target than UCM, UAM, or UB for international students with very strong but not exceptional PCE results.

## Costs and Payment Structure

Tuition fees at UAB are set by the Generalitat de Catalunya via regional decree and are subject to annual revision. Medicine is classified as an experimental branch, carrying the highest per-credit tariff tier.

| Fee Concept | EU/EEA Students | Non-EU Students | Notes |
|---|---|---|---|
| Annual tuition (per year, approx.) | ~1,400–2,000 EUR | PENDING_CONFIRMATION | ANNUAL_UPDATE_REQUIRED — Catalan tariff |
| Per-credit fee (experimental branch) | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | Medicine = experimental branch |
| Enrolment / administrative fees | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Student insurance | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Repeat enrolment surcharge | Higher per-credit rate | Higher per-credit rate | Applies from 2nd enrolment in same subject |

Non-EU students face significantly higher fees under the Catalan extracomunitario tariff. PENDING_CONFIRMATION for current figures — ANNUAL_UPDATE_REQUIRED.

## Scholarships and Financial Aid

**National level:**
- **Beca General MEC:** Available to students meeting income and academic thresholds. Annual application via the MEFP portal (ANNUAL_UPDATE_REQUIRED).
- **Beca Movilidad (Erasmus+):** Available for approved exchange periods.

**Regional level (Generalitat de Catalunya):**
- **Beques Equitat (Catalunya):** Need-based tuition reduction grants from the Generalitat. ANNUAL_UPDATE_REQUIRED — verify at agaur.gencat.cat.
- Additional Catalan regional scholarship programmes: PENDING_CONFIRMATION.

**University level:**
- UAB has internal scholarship and emergency aid mechanisms. Details at uab.cat/becas (ANNUAL_UPDATE_REQUIRED).

Scholarship eligibility requires passing a minimum number of ECTS per year.

## Accommodation and Cost of Living

UAB is notable for its self-contained campus. Campus de la UAB has a full residential infrastructure including the Vila Universitària (student housing complex), multiple residences, shops, sports facilities, and services entirely within the campus perimeter in Bellaterra. This makes it one of the most self-sufficient university campuses in Spain.

| Cost Category | Approximate Monthly Range | Notes |
|---|---|---|
| Vila Universitària (on-campus apartments) | 400–700 EUR | ANNUAL_UPDATE_REQUIRED — very competitive; apply early |
| On-campus student residences | 500–900 EUR | ANNUAL_UPDATE_REQUIRED |
| Off-campus shared flat (Bellaterra / Cerdanyola area) | 400–650 EUR | ANNUAL_UPDATE_REQUIRED — significantly cheaper than Barcelona |
| Shared flat in Barcelona (for clinical years) | 650–1,000 EUR | ANNUAL_UPDATE_REQUIRED |
| Food (self-catering or campus canteen) | 200–350 EUR | ANNUAL_UPDATE_REQUIRED |
| Public transport (FGC train to Barcelona) | 20–40 EUR | ANNUAL_UPDATE_REQUIRED |
| Books / materials (Year 1 estimate) | 200–400 EUR | ANNUAL_UPDATE_REQUIRED |

Campus de la UAB is connected to Barcelona via FGC (Ferrocarrils de la Generalitat de Catalunya) from Bellaterra station. Journey time to Barcelona centre (Plaça Catalunya) is approximately 30–35 minutes.

During preclinical years, students can live on campus in Bellaterra at a significantly lower cost than Barcelona city. During clinical years (3–6), some students relocate closer to their assigned UDH — particularly for units at Vall d'Hebron or Sant Pau in Barcelona, or Germans Trias in Badalona.

## International Exchange and Mobility Programs

UAB Medicina participates in the Erasmus+ programme via the Facultat de Medicina's mobility office. Exchange periods in the clinical phase (from Year 3) are the most common format.

UAB participates in the Europaeum network (alongside the Universities of Oxford, Leiden, Geneva, Warsaw, Bonn, and others), providing research and academic collaboration opportunities at a high level.

**Important limitation:** Not all UAB university-level Erasmus agreements extend to Medicine. Medicine-specific slots are limited and competitive. Students should verify current Medicine-applicable agreements with the Facultat de Medicina's Oficina de Relacions Internacionals (ANNUAL_UPDATE_REQUIRED).

Incoming international exchange students to UAB Medicine: PENDING_CONFIRMATION on formal incoming exchange structure for the Medicine degree.

## MIR Preparation and Professional Outcomes

UAB graduates are eligible to sit the MIR (Médico Interno Residente) examination after completing the Grau en Medicina.

**MIR results for UAB graduates:** PENDING_CONFIRMATION — UAB does not publish programme-specific MIR pass rates or ranking distributions in a readily verifiable public format as of the date of this file.

**General context:** The clinical training network at UAB — particularly Vall d'Hebron (one of Spain's largest hospital complexes) and Germans Trias i Pujol — is considered strong preparation for the MIR. Access to active research environments (VHIR, IGTP) supports graduates who pursue academic or research-oriented medical careers.

The AQU Excel·lent rating and WFME accreditation provide confidence in the programme's formal quality standards, which are relevant for graduates planning to sit specialisation examinations in other countries.

## Strategic Fit

### Good Fit For

- Candidates with a nota de admisión in the 12.5–12.9 range who cannot confidently target UCM, UAM, or UB Medicine but are competitive for UAB.
- Students who value confirmed WFME accreditation (AQU Excel·lent) as a guarantee for international career options — UAB's confirmed status makes it a safer choice than UB (PENDING_CONFIRMATION) for internationally-oriented candidates.
- International candidates via PCE/UNED whose nota de admisión is strong but not exceptional — UAB's lower nota de tall makes it the most achievable major public Medicine programme in Catalunya for this profile.
- Students who want a self-contained campus experience with lower accommodation costs than Barcelona city during preclinical years.
- Research-oriented students interested in the Vall d'Hebron, Germans Trias i Pujol, or Sant Pau research environments.

### Less Suitable For

- Candidates whose nota de admisión is below approximately 12.3 — UAB Medicine remains very competitive despite its lower nota de tall compared to UB.
- Students who require an English-medium or formally bilingual programme.
- International students with limited Spanish or Catalan proficiency — the degree is taught in Catalan and Spanish; English exposure is partial.
- Students who strongly prefer urban campus living — Bellaterra campus is suburban and self-contained, not a city-centre environment.
- Candidates who need verified MIR pass rate data to inform their decision — this is not publicly available from UAB.

## Risks and Considerations

1. **Nota de tall variability:** The nota de tall of 12.389 for 2025-26 reflects one specific cycle. It can shift upward or downward in the following year. The large seat count (385) provides some stability, but applicant pool fluctuations still affect the threshold. Always plan with a buffer above the most recent nota de tall.

2. **UDH assignment:** Assignment to one of the five UDH from Year 3 is not individually guaranteed. Placement at Vall d'Hebron (the most prestigious and complex unit) is not guaranteed and depends on administrative processes. Students should be prepared for placement at any of the five units.

3. **Catalan language environment:** Teaching is primarily in Catalan. International students or students from other Spanish regions without Catalan proficiency face an adaptation challenge in Year 1. This is a practical risk that is manageable but requires deliberate preparation.

4. **Non-EU tuition:** Fees for non-EU students are PENDING_CONFIRMATION but significantly higher than EU tariffs. Verify with the UAB admissions office before the intake year.

5. **Clinical year commuting:** During Years 3–6, students assigned to UDH units in Barcelona (Vall d'Hebron, Sant Pau) or Badalona (Germans Trias) face commutes from Bellaterra or may need to relocate, increasing living costs in clinical years.

6. **Large cohort dynamics:** 385 students is a large cohort. In preclinical years, large lecture-based formats are the norm. Students who prefer small-cohort, seminar-intensive environments may find this challenging.

## Important Notes

- Nota de tall must be verified annually at accesuniversitats.gencat.cat — the 12.389 figure applies to 2025-26 only (ANNUAL_UPDATE_REQUIRED).
- All admission dates are ANNUAL_UPDATE_REQUIRED — verify at accesuniversitats.gencat.cat and UAB's admissions pages.
- WFME accreditation via AQU Catalunya (Excel·lent rating) is confirmed as of the date of this file. Reaccreditation cycles should be monitored.
- Non-EU students must verify visa, NIE, and health insurance requirements separately from admission.
- Teaching is primarily in Catalan. Students who are not Catalan speakers should account for this in language preparation.
- On-campus accommodation (Vila Universitària) is competitive — apply early.

## Key Insight

UAB Medicina is the most accessible major public Medicine programme in Catalunya by nota de tall, and crucially holds confirmed WFME accreditation (AQU Excel·lent) — which UB has not confirmed as of this file. For international candidates applying via PCE/UNED who hold a nota de admisión in the 12.5–12.9 range, UAB is the strategically optimal Catalan target: it combines a reachable threshold, confirmed international accreditation, a large prestigious clinical network (including Vall d'Hebron), and an on-campus living environment that significantly reduces the cost burden of preclinical years. The confirmed WFME status makes UAB objectively more suitable than UB for candidates with international career plans, until UB's status is confirmed.

## Final Takeaway

UAB Medicina is a high-value, strategically well-positioned public Medicine programme for candidates who are strong but not at the absolute top of the nota de admisión scale. The combination of lower nota de tall (12.389 in 2025-26), confirmed WFME/AQU accreditation, a large prestigious hospital network, and lower cost-of-living during preclinical years makes it the most compelling option in Catalunya for the 12.5–12.9 nota de admisión profile. The principal considerations are the Catalan language environment, the need to select UDH assignments without guaranteed placement choice, and the suburban campus setting. For internationally-oriented candidates, the confirmed WFME seal at UAB versus the unconfirmed status at UB is the critical differentiator.

## Frequently Asked Questions

**What is the nota de tall for UAB Medicine?**
The nota de tall for 2025-26 was 12.389 out of 14.000 (ANNUAL_UPDATE_REQUIRED — this changes every cycle). It is the nota de admisión of the last student admitted, not a guaranteed threshold for future years. Verify at accesuniversitats.gencat.cat.

**How is the nota de admisión calculated?**
Nota de admisión = 0.6 × Nota media de Batxillerat + 0.4 × Nota PAU (fase general) + bonus from up to 2 specific-phase subjects (each grade × ponderation coefficient of 0.1 or 0.2). Maximum score is 14.0000.

**Is UAB Medicine WFME-accredited?**
Yes. UAB Medicina holds confirmed WFME quality accreditation via AQU Catalunya, which awarded the programme its highest rating: Excel·lent. This is directly relevant for graduates planning postgraduate training in the UK, USA, Canada, Australia, and other countries requiring WFME-listed institution graduation.

**How many seats does UAB Medicine have?**
385 seats per intake (ANNUAL_UPDATE_REQUIRED). This is one of the largest Medicine cohorts in Spain.

**Can international students apply via PCE?**
Yes. International students with a UNEDasiss Credencial can apply through accesuniversitats.gencat.cat. Biology and Chemistry PCEs (coefficient 0.2 each; ANNUAL_UPDATE_REQUIRED) are the most valuable specific-phase subjects. The nota de tall at UAB is more reachable via the PCE route than at UCM, UAM, or UB.

**What are the tuition fees?**
For EU/EEA students, approximately 1,400–2,000 EUR/year (ANNUAL_UPDATE_REQUIRED — Catalan tariff). For non-EU students: PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED). Verify the current Catalan decreto de precios públicos.

**Is there an interview or entrance exam?**
No. Admission is based solely on the nota de admisión. There is no interview, no proprietary exam, and no portfolio requirement.

**Where is the campus?**
The preclinical faculty is at Campus de la UAB, Bellaterra (Cerdanyola del Vallès). The campus is self-contained with on-site accommodation (Vila Universitària), restaurants, shops, and sports facilities. It is connected to Barcelona via FGC train (approx. 30–35 minutes to Plaça Catalunya). Clinical years involve placement at UDH hospitals across the Barcelona metropolitan area.

**What are the hospital teaching units?**
Five confirmed UDH: Hospital Universitari Germans Trias i Pujol (Badalona), Parc Taulí (Sabadell), Hospital de la Santa Creu i Sant Pau (Barcelona), Hospital Universitari Vall d'Hebron (Barcelona), and the Unitat de Ciències Morfològiques Bàsiques (Bellaterra). Students are assigned to one from Year 3.

**What language is the degree taught in?**
Primarily in Catalan, with Spanish also used throughout. A partial English component exists in select subjects. There is no English-medium track. Catalan proficiency is a significant practical advantage.
