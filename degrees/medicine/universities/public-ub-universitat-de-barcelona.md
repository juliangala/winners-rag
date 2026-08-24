---
id: ub

type: university
subtype: public

name: Universitat de Barcelona
short_name: UB

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Barcelona
  region: Catalunya
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - high_competitiveness
  - research_oriented
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
  level: very_high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION

  last_admitted_scores:
    - intake_year: 2025-2026
      round: fase_ordinaria
      score: 12.505
      score_type: nota_de_admision
      notes: Verified nota de tall for 2025-26 intake (highest entry across UB cohorts). Source: notasdecorte.es. ANNUAL_UPDATE_REQUIRED.

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
  - id: ub-medicina

    campus: Facultat de Medicina i Ciències de la Salut — Campus de Bellvitge (L'Hospitalet de Llobregat) and Casanova building (Barcelona)

    modality: standard

    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - high_competitiveness
      - research_oriented
      - strong_clinical_exposure
      - bilingual_program

    teaching_languages:
      - Catalan
      - Spanish
      - English (partial — select subjects and electives)

    regional_language_possible: true
    regional_language: Catalan

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
          round: fase_ordinaria
          score: 12.505
          score_type: nota_de_admision
          notes: Verified nota de tall for 2025-26 (highest among UB cohorts). Source: notasdecorte.es. ANNUAL_UPDATE_REQUIRED.

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
          score: 12.505
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
            - Spanish/Catalan PAU (Selectivitat Catalunya)
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
              notes: 60% of the nota de admisión. Same formula as all Spanish public universities.

            - component: evau_general_phase
              enabled: true
              role: weighted
              weight: 40
              grade_source: evau_fase_general
              notes: 40% of the nota de admisión (PAU fase general in Catalunya). Maximum combined base score with Bachillerato is 10.0000.

            - component: evau_specific_phase_bonus
              enabled: true
              role: bonus_only
              maximum_bonus: 4.0
              grade_source: evau_fase_especifica
              notes: Best 2 eligible subjects count. Each subject score multiplied by the ponderation coefficient assigned by UB for Medicine (0.1 or 0.2). Maximum nota de admisión is 14.0000. Coefficients ANNUAL_UPDATE_REQUIRED — verify at accesuniversitats.gencat.cat.
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED
                Chemistry:      0.2 # ANNUAL_UPDATE_REQUIRED
                Physics:        0.1 # ANNUAL_UPDATE_REQUIRED
                Mathematics_II: 0.1 # ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---

# Universitat de Barcelona

## Overview

The Universitat de Barcelona (UB) is one of Spain's oldest and most internationally recognised universities, with its Facultat de Medicina i Ciències de la Salut operating across two campus locations: the historic Casanova building in central Barcelona and the modern Campus de Bellvitge in L'Hospitalet de Llobregat. UB Medicine is connected to a large network of affiliated teaching hospitals across the Barcelona metropolitan area, covering primary, secondary, and tertiary care environments.

Admission to UB Medicine is managed through the Catalan admissions system (accesuniversitats.gencat.cat), using the nota de admisión formula common to all Spanish public universities but applied through the Catalan PAU (Selectivitat) system. The programme is primarily taught in Catalan and Spanish, with English progressively embedded in select subjects.

UB is the flagship research university of Catalunya and consistently places highly in international rankings. The degree draws from IDIBELL (Bellvitge Biomedical Research Institute), IDIBAPS (Hospital Clínic research institute), ISGlobal, and other major research centres co-located with affiliated teaching hospitals — making it one of the strongest research environments in Spanish medical education.

## Quick Evaluation

- **Degree:** Grau en Medicina — 6 years — 360 ECTS
- **Seats:** PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED)
- **Admission mechanism:** Nota de admisión (nota de tall model); no exam, no interview
- **Competitiveness:** Very high — among the highest nota de tall in Catalunya
- **Nota de tall (2025-26):** 12.505 out of 14.000 (source: notasdecorte.es; ANNUAL_UPDATE_REQUIRED)
- **Tuition (approximate):** ~1,400–2,000 EUR/year for EU residents (Catalan tariff, ANNUAL_UPDATE_REQUIRED); non-EU significantly higher
- **Clinical training from:** Year 3 — across a large network of Barcelona metropolitan hospitals
- **Teaching language:** Catalan (primary), Spanish, English (partial)
- **WFME accreditation:** PENDING_CONFIRMATION
- **International access:** Via PCE/UNED Credencial or Credencial UE through the Catalan admissions portal

## Key Facts

| Parameter | Value |
|---|---|
| Official name | Universitat de Barcelona |
| Degree | Grau en Medicina |
| Duration | 6 years (360 ECTS) |
| Annual seats | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Campus locations | Casanova (Barcelona) + Campus de Bellvitge (L'Hospitalet) |
| Year 1–2 location | Casanova building (Barcelona) or Bellvitge (PENDING_CONFIRMATION) |
| Year 3–6 location | Affiliated hospitals across Barcelona metropolitan area |
| Teaching language | Catalan (primary); Spanish; English (partial) |
| Admission system | Catalan PAU / accesuniversitats.gencat.cat |
| No proprietary exam | Correct |
| No interview | Correct |
| Nota de tall (2025-26) | 12.505 (ANNUAL_UPDATE_REQUIRED) |
| WFME accreditation | PENDING_CONFIRMATION |
| Tuition (EU, indicative) | ~1,400–2,000 EUR/year (ANNUAL_UPDATE_REQUIRED) |
| Tuition (non-EU, indicative) | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Founded | 1450 (university); Faculty of Medicine historical origin |

## Program Options

UB offers a single Grau en Medicina programme. There is no separate bilingual track, no English-medium cohort, and no alternative campus programme. All students enter the same curriculum.

Teaching is conducted in Catalan as the primary academic language, with Spanish also used across teaching and assessment contexts. Students who are not Catalan speakers but have strong Spanish proficiency generally manage the transition, as both languages are used and faculty adapt to students' needs; however, a working knowledge of Catalan is strategically advantageous for full participation and clinical placement integration (PENDING_CONFIRMATION — verify current language policy with the faculty admissions office).

The curriculum is structured around the two main campus sites: preclinical years are delivered at the Casanova faculty building in Barcelona's Eixample district (central Barcelona), with clinical years spanning the affiliated hospital network across the metropolitan area.

## Program Structure

The Grau en Medicina at UB is structured across 6 academic years, totalling 360 ECTS:

**Phase 1 — Preclínica (Years 1–2):** Core biomedical sciences at the Facultat de Medicina (Casanova campus, central Barcelona). Subjects include Anatomy, Physiology, Biochemistry, Cell Biology, Histology, Immunology, Microbiology, Pharmacology, and Pathology. Introductory clinical skills and simulated patient contact are progressively integrated.

**Phase 2 — Clínica (Years 3–6):** Students are assigned to Unitats Docents (teaching units) within affiliated hospitals. Clinical instruction spans all major medical specialties including internal medicine, surgery, obstetrics and gynaecology, paediatrics, psychiatry, and primary care. Final year includes integrated clinical rotations.

**TFG (Final Degree Project):** Mandatory final-year project with research or clinical focus. Language of presentation: PENDING_CONFIRMATION.

**Electives:** Optional subject credits are available. Exact ECTS volume: PENDING_CONFIRMATION.

## Teaching Methodology

UB Medicine delivers a primarily lecture-based curriculum in preclinical years, complemented by laboratory practice, small-group clinical case seminars, and progressive simulation-based clinical skills training. The faculty has clinical skills laboratories at the Casanova site and within affiliated teaching hospitals.

From year three, teaching is hospital-embedded, with specialty-supervised clinical attachment as the primary learning format. The hospital network's research intensity — through institutes such as IDIBELL, IDIBAPS, and ISGlobal — generates opportunities for students to engage with active research environments during clinical placements.

English-language integration into select subjects reflects a broader UB policy of internationalisation; the degree is not English-taught but English literacy in a scientific context is progressively developed.

The Catalan academic environment means that seminars, small group teaching, and much informal clinical communication will occur primarily in Catalan. International students should factor this into their language preparation.

## Clinical Training

UB Medicina operates one of the most extensive clinical training networks among Spanish public medical faculties. The affiliated hospital system covers primary care centres, district hospitals, and major tertiary referral centres across the Barcelona metropolitan area.

**Confirmed affiliated teaching hospitals and research institutes:**

- Hospital Clínic de Barcelona (principal tertiary hospital — central Barcelona; houses IDIBAPS research institute)
- Hospital Universitari de Bellvitge (principal campus hospital for Bellvitge-based units; houses IDIBELL research institute)
- Hospital Sant Joan de Déu (paediatric and obstetric specialisation — Esplugues de Llobregat)
- Mútua Terrassa
- Hospital de l'Esperit Sant
- Consorci Sanitari Integral (CSI)
- Hospital Municipal de Badalona
- Hospital de Viladecans
- PSSJD (Parc Sanitari Sant Joan de Déu)
- ISGlobal (Instituto de Salud Global de Barcelona — global health research)
- ICS (Institut Català de la Salut) — primary care network

Students are assigned to Unitats Docents from Year 3. Assignment processes are managed by the faculty and depend on administrative and merit-based criteria (ANNUAL_UPDATE_REQUIRED).

The combination of Hospital Clínic (one of Spain's leading research hospitals) and Hospital de Bellvitge (a major south Barcelona tertiary centre) as the two principal hubs gives UB students access to extremely high clinical complexity and research output.

## International Recognition and Opportunities

UB is a member of the League of European Research Universities (LERU) and the Coimbra Group, placing it among the most internationally recognised research universities in Spain. It consistently ranks in the top 200 globally in several international rankings.

**WFME accreditation status:** PENDING_CONFIRMATION — the UB Facultat de Medicina's WFME accreditation status was not verifiably confirmed from public sources at the time of this file's generation. Students planning international careers should verify this directly with the faculty before enrolment decisions.

The UB degree (Grau en Medicina, MECES Level 3) is recognised across the EU under Directive 2005/36/EC. The degree title in the Catalan university system is fully equivalent to Spanish Grado en Medicina for national MIR access.

**International exchange:** UB participates in the Erasmus+ programme with an extensive network of European partner universities. The Facultat de Medicina manages Medicine-specific exchange agreements separately from the general university Erasmus programme. ANNUAL_UPDATE_REQUIRED — verify Medicine-specific Erasmus slots at the faculty mobility office.

## Admission Model

UB Medicine is part of Catalunya's public university admissions system, coordinated through the accesuniversitats.gencat.cat portal. Admission is determined exclusively by the nota de admisión (referred to as nota de tall in Catalan) — there is no proprietary entrance exam, no interview, and no portfolio component.

**The nota de admisión formula (identical across all Spanish public universities):**

```
Nota de admisión = 0.6 × Nota media de Bachillerato
                 + 0.4 × Nota PAU (fase general)
                 + up to 4.0 bonus points from PAU fase específica
```

- **Base score maximum:** 10.0000 (Bachillerato + PAU general phase combined)
- **Maximum nota de admisión:** 14.0000 (with full specific-phase bonus)
- **Specific phase:** The best 2 eligible subjects count. Each subject grade is multiplied by the ponderation coefficient assigned by UB for Medicine. Biology and Chemistry typically receive 0.2 (ANNUAL_UPDATE_REQUIRED — verify at accesuniversitats.gencat.cat each year).

**Access routes:**
- PAU Catalunya (Selectivitat): standard route for Catalan Bachillerato students
- EVAU from other Spanish regions: valid; equivalent calculation applied
- International via PCE/UNED (Credencial UNEDasiss): valid; applies via accesuniversitats portal
- International via Credencial UE: valid
- Direct homologation (select countries): valid

**Language note:** Teaching is primarily in Catalan. There is no formal Catalan language admission threshold, but students who do not speak Catalan should be prepared to function in a Catalan-dominant academic environment.

## Admission Process

### For Catalan PAU students

1. Complete Batxillerat (Years 1–2) and register for PAU (Selectivitat).
2. Sit PAU: mandatory general phase + optional specific phase (strongly recommended — up to 4 bonus points).
3. Receive nota de admisión.
4. Submit preinscripció through the accesuniversitats.gencat.cat portal during the designated window (ANNUAL_UPDATE_REQUIRED for exact dates).
5. List UB Medicina in your degree preferences.
6. Await results of the fase ordinaria assignment.
7. If not admitted in fase ordinaria, apply for the fase extraordinaria.
8. If admitted: complete matriculació within the published deadline.

### For students from other Spanish regions

1. Sit EVAU in your region. Request that your specific-phase subject results be ponderado using the Catalan university coefficients for Medicine.
2. Apply through accesuniversitats.gencat.cat with your EVAU nota de admisión.
3. Note: students from other regions compete in the same pool as Catalan students. The nota de tall is identical for all applicants.

### For international PCE/UNED students

1. Obtain a UNEDasiss Credencial. Sit PCE in Biology and Chemistry (coefficient 0.2 each; ANNUAL_UPDATE_REQUIRED).
2. Apply through accesuniversitats.gencat.cat with the Credencial calificación.
3. Verify Catalan-specific requirements for international applicants at the accesuniversitats portal (ANNUAL_UPDATE_REQUIRED).
4. If admitted: arrange NIE, visa if applicable, and housing.

## Admission Timeline

All dates are approximate and ANNUAL_UPDATE_REQUIRED. Verify each year at accesuniversitats.gencat.cat and the UB Faculty of Medicine admissions page.

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

UB Medicina ranks among the programmes with the highest nota de tall in Catalunya. For the 2025-26 intake, the nota de tall was **12.505** out of 14.000 (source: notasdecorte.es; ANNUAL_UPDATE_REQUIRED — verify current and historical figures at accesuniversitats.gencat.cat).

**Historical trend (ANNUAL_UPDATE_REQUIRED):**

| Intake Year | Nota de Tall | Source |
|---|---|---|
| 2025-2026 | 12.505 | notasdecorte.es (verified) |
| 2024-2025 | PENDING_CONFIRMATION | — |
| 2023-2024 | PENDING_CONFIRMATION | — |

**What is known:**

Medicine at UB is consistently one of the most oversubscribed degree programmes in Catalunya. In recent cycles, public Medicine programmes in Barcelona have posted nota de tall values in the 13.0–13.9 range, with UB typically at the higher end of Catalan public medicine faculties.

**Ponderation coefficients for Medicine at UB (ANNUAL_UPDATE_REQUIRED — verify at accesuniversitats.gencat.cat):**

| Subject | Coefficient |
|---|---|
| Biology | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Chemistry | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Physics | 0.1 (ANNUAL_UPDATE_REQUIRED) |
| Mathematics II | 0.1 (ANNUAL_UPDATE_REQUIRED) |

**For PCE/UNED international students:** The same formula applies. Biology and Chemistry PCE results at coefficient 0.2 each are the primary levers for maximising the nota de admisión. Given the typically very high nota de tall at UB, near-perfect PCE scores are required.

**Key strategic note:** Candidates applying from outside Catalunya (via EVAU from Madrid, Andalucía, etc.) or from international routes (PCE/UNED) compete in the same pool as Catalan students. There is no reserved quota for non-Catalan or international applicants in the standard public admissions process.

## Costs and Payment Structure

Tuition fees at UB are set by the Generalitat de Catalunya via regional decree and differ from Madrid tariffs. Catalan public university fees have historically been higher than most other Spanish regions for EU-resident students.

| Fee Concept | EU/EEA Students | Non-EU Students | Notes |
|---|---|---|---|
| Annual tuition (per year, approx.) | ~1,400–2,000 EUR | PENDING_CONFIRMATION | ANNUAL_UPDATE_REQUIRED — Catalan tariff, higher than Madrid |
| Per-credit fee (experimental branch) | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | Medicine = experimental branch |
| Enrolment / administrative fees | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Student insurance | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Repeat enrolment surcharge | Higher per-credit rate | Higher per-credit rate | Applies from 2nd enrolment in same subject |

Non-EU students face significantly higher fees under the Catalan extracomunitario tariff (PENDING_CONFIRMATION for exact current figures — ANNUAL_UPDATE_REQUIRED).

Catalunya's public university fee structure has been subject to revision. Students should verify the current decreto de precios públicos from the Generalitat de Catalunya before the intake year.

## Scholarships and Financial Aid

**National level:**
- **Beca General MEC (Ministerio de Educación y Formación Profesional):** Available to students meeting income and academic thresholds. Annual application via the MEFP portal (ANNUAL_UPDATE_REQUIRED).
- **Beca Movilidad (Erasmus+):** Available for approved Erasmus exchange periods.

**Regional level (Generalitat de Catalunya):**
- **Beques Equitat (Catalunya):** The Generalitat offers need-based tuition reduction grants (beques equitat) that reduce the per-credit fee for eligible students. ANNUAL_UPDATE_REQUIRED — verify at agaur.gencat.cat.
- Additional Catalan regional scholarship programmes: PENDING_CONFIRMATION.

**University level:**
- UB has internal scholarship and emergency aid mechanisms via the Unitat d'Atenció a l'Estudiant. Details at ub.edu/becas (ANNUAL_UPDATE_REQUIRED).

Scholarship eligibility requires passing a minimum number of ECTS per year. Students who fail to pass the required minimum risk losing their MEC scholarship.

## Accommodation and Cost of Living

Barcelona is one of Spain's most expensive cities for student accommodation, with a competitive rental market that has tightened considerably in recent years.

| Cost Category | Approximate Monthly Range | Notes |
|---|---|---|
| Shared flat room (piso compartido — Barcelona) | 650–1,000 EUR | ANNUAL_UPDATE_REQUIRED — Barcelona rental market is highly volatile |
| University residence / col·legi major | 700–1,200 EUR | ANNUAL_UPDATE_REQUIRED — limited availability |
| Shared flat (L'Hospitalet / Bellvitge area) | 500–800 EUR | ANNUAL_UPDATE_REQUIRED — lower than central Barcelona |
| Food (self-catering) | 200–350 EUR | ANNUAL_UPDATE_REQUIRED |
| Public transport (T-Jove / metro + bus) | 20–40 EUR | ANNUAL_UPDATE_REQUIRED |
| Books / materials (Year 1 estimate) | 200–400 EUR | ANNUAL_UPDATE_REQUIRED |

The Casanova faculty building is in Barcelona's Eixample district (Metro: Hospital Clínic, L5). Campus de Bellvitge is in L'Hospitalet de Llobregat, accessible by Metro L1 (Bellvitge) and Renfe. Students in clinical years may need to commute to different hospitals across the metropolitan area.

Early accommodation search is strongly advised — Barcelona's rental market has historically been difficult for students starting from summer onwards. University accommodation is limited and competitive.

## International Exchange and Mobility Programs

UB participates in the Erasmus+ programme. The Facultat de Medicina manages its own Medicine-specific mobility agreements. Exchange periods are typically available from Year 3 (clinical phase).

UB's membership in LERU and the Coimbra Group provides connectivity with leading European research universities, which may generate additional research and mobility opportunities beyond standard Erasmus.

**Important limitation:** UB university-level Erasmus agreements do not automatically apply to Medicine. Students must verify Medicine-specific slots with the Oficina de Relacions Internacionals at the Facultat de Medicina. Availability is limited and competitive. ANNUAL_UPDATE_REQUIRED.

Incoming international exchange students to UB Medicine: PENDING_CONFIRMATION on formal incoming exchange structure for the Medicine degree.

## MIR Preparation and Professional Outcomes

UB graduates are eligible to sit the MIR (Médico Interno Residente) examination after completing the Grau en Medicina.

**MIR results for UB graduates:** PENDING_CONFIRMATION — UB does not publish programme-specific MIR pass rates or ranking distributions in a readily verifiable public format as of the date of this file.

**General context:** UB's clinical training network — particularly Hospital Clínic and Hospital de Bellvitge, both with strong research environments — is generally considered excellent preparation for the MIR. The research-oriented culture of the affiliated institutes (IDIBELL, IDIBAPS, ISGlobal) also positions UB graduates well for academic medicine careers.

Post-MIR, graduates can specialise within the Spanish Sistema Nacional de Salud or pursue international pathways. For graduates with international career ambitions, WFME accreditation status (PENDING_CONFIRMATION) should be verified before selecting UB over confirmed-WFME institutions.

## Strategic Fit

### Good Fit For

- Catalan PAU candidates with a nota de admisión at the top of the competitive range (historically 13.0+) who want to study in Barcelona.
- Students who are comfortable in a Catalan-speaking academic environment or are willing to develop Catalan proficiency alongside their studies.
- Research-oriented students who want access to one of Spain's most prolific medical research ecosystems (IDIBELL, IDIBAPS, ISGlobal, Hospital Clínic).
- Candidates who value UB's international reputation and LERU membership for future international career positioning.
- Students who prefer urban campus living in a major European city.

### Less Suitable For

- Candidates whose nota de admisión is below approximately 12.5 — at the 2025-26 nota de tall of 12.505, this represents the minimum threshold (ANNUAL_UPDATE_REQUIRED — verify current cycle figure before planning).
- International students with no knowledge of Spanish or Catalan — the degree is taught primarily in Catalan and Spanish; English-medium learning is only partial.
- Students with limited financial resources — Barcelona has one of the highest costs of living among Spanish university cities, and Catalan tuition tariffs for EU students are higher than in most other regions.
- Candidates who require confirmed WFME accreditation for future career plans — WFME status at UB is PENDING_CONFIRMATION as of this file.

## Risks and Considerations

1. **Nota de tall variability:** The nota de tall for UB Medicine in 2025-26 was 12.505 (source: notasdecorte.es). This is the most recent verified figure but changes annually. Candidates must verify the current intake cycle nota de tall at accesuniversitats.gencat.cat. Prior-year figures (2024-25, 2023-24) remain PENDING_CONFIRMATION.

2. **WFME accreditation uncertainty:** UB's WFME accreditation status is PENDING_CONFIRMATION. For candidates planning to seek postgraduate medical training in countries requiring WFME graduation (UK, USA, etc.), this should be verified directly with the faculty before committing to UB.

3. **Seat count uncertainty:** The number of seats at UB Medicine per intake is PENDING_CONFIRMATION. This limits the ability to estimate applicants-per-seat ratios for planning.

4. **Barcelona rental market:** Accommodation costs in Barcelona have risen sharply. Students should budget considerably more than in comparable Spanish cities and begin accommodation search well in advance of the intake.

5. **Catalan language requirement:** While there is no formal Catalan language admission test, the teaching environment is Catalan-dominant. International students or students from other Spanish regions who have not prepared for Catalan-medium instruction may face an adaptation challenge in the first year.

6. **Non-EU tuition:** Fees for non-EU students are PENDING_CONFIRMATION but are expected to be significantly higher than the EU tariff. Verify with UB's admissions office before the intake year.

7. **PCE/UNED competition:** As with UCM, reaching the nota de tall at UB via the PCE route requires near-perfect Biology and Chemistry scores. This is a structurally high-difficulty target for international candidates.

## Important Notes

- Nota de tall for 2025-26 is 12.505 (source: notasdecorte.es; ANNUAL_UPDATE_REQUIRED). All historical figures (2024-25, 2023-24) remain PENDING_CONFIRMATION — verify at accesuniversitats.gencat.cat.
- All admission dates are ANNUAL_UPDATE_REQUIRED — verify at accesuniversitats.gencat.cat and the UB Faculty of Medicine admissions page.
- WFME accreditation status at UB is PENDING_CONFIRMATION and should be verified directly with the faculty.
- Non-EU students must verify visa, NIE, and health insurance requirements.
- Teaching is primarily in Catalan. Students who are not Catalan speakers should account for this in their preparation.
- Catalan tuition tariffs for EU students are higher than Madrid tariffs — verify current decreto de precios públicos from the Generalitat de Catalunya.

## Key Insight

UB Medicina is the Barcelona flagship for research-oriented medical students who can reach the very high nota de tall threshold. Its strength lies in the depth and breadth of its affiliated hospital research ecosystem — particularly the Hospital Clínic/IDIBAPS and Bellvitge/IDIBELL axes — which are among Spain's most productive medical research environments. The programme's primary uncertainties for international candidates centre on WFME accreditation status (not confirmed) and the challenge of the Catalan academic language environment. For domestic Catalan PAU candidates, UB Medicine represents a top-tier target; for international PCE/UNED candidates, UAB (with confirmed WFME via AQU and a slightly different competitive profile) may be a more strategically transparent option.

## Final Takeaway

UB Medicina is a high-prestige, high-difficulty option for candidates who combine very high academic scores with comfort in the Barcelona/Catalan academic environment. The research ecosystem surrounding the programme is exceptional. The principal risks for international candidates are the unconfirmed WFME status, the Catalan language environment, and the extremely competitive nota de tall. Candidates should treat this as a core option only when the nota de admisión firmly exceeds the current nota de tall (12.505 in 2025-26; ANNUAL_UPDATE_REQUIRED), and should verify outstanding PENDING_CONFIRMATION fields — particularly WFME accreditation — directly with the faculty.

## Frequently Asked Questions

**What is the nota de tall for UB Medicine?**
The nota de tall (equivalent to nota de corte) for UB Medicine in the 2025-26 intake was **12.505** out of 14.000 (source: notasdecorte.es; ANNUAL_UPDATE_REQUIRED — verify at accesuniversitats.gencat.cat for current and historical figures). It changes annually based on the applicant pool. Prior-year figures (2024-25, 2023-24) remain PENDING_CONFIRMATION.

**How is the nota de admisión calculated for Catalan students?**
Nota de admisión = 0.6 × Nota media de Batxillerat + 0.4 × Nota PAU (fase general) + bonus from up to 2 specific-phase subjects (each grade × ponderation coefficient). Maximum score is 14.0000. The formula is identical to the rest of Spain.

**Is UB Medicine WFME-accredited?**
PENDING_CONFIRMATION. UB's WFME accreditation status could not be confirmed from public sources at the time of this file's generation. Candidates planning international careers should verify this directly with the Facultat de Medicina before making enrolment decisions.

**What language is the degree taught in?**
Primarily in Catalan, with Spanish also used across teaching and assessment. A partial English component exists in select subjects. There is no English-medium track. Students who do not speak Catalan but are fluent in Spanish generally manage, but Catalan proficiency is a significant advantage.

**Can international students apply via PCE?**
Yes. International students who hold a UNEDasiss Credencial can apply through accesuniversitats.gencat.cat. Biology and Chemistry PCEs (coefficient 0.2 each; ANNUAL_UPDATE_REQUIRED) are the most strategically valuable subjects. Given the very high nota de tall at UB, near-perfect PCE scores are required.

**What are the tuition fees?**
For EU/EEA students, approximately 1,400–2,000 EUR/year (ANNUAL_UPDATE_REQUIRED — Catalan tariff, higher than Madrid). For non-EU students: PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED). Verify the current Catalan decreto de precios públicos.
