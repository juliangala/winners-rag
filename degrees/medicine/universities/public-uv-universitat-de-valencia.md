---
id: uv

type: university
subtype: public

name: Universitat de València (Estudi General)
short_name: UV

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Valencia
  region: Comunitat Valenciana
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - medium_competitiveness
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
    - EVAU Comunitat Valenciana (PAU)
    - EVAU from other Spanish regions
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
      score: 12.803
      score_type: nota_de_admision
      notes: Verified nota de corte for 2025-26 intake. Source: notasdecorte.es. ANNUAL_UPDATE_REQUIRED.

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
  - id: uv-medicina

    campus: Facultat de Medicina i Odontologia — Avinguda de Blasco Ibáñez 15, 46010 Valencia (central campus); clinical training across Hospital Clínic Universitari de Valencia and affiliated hospitals

    modality: standard

    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - medium_competitiveness
      - research_oriented
      - strong_clinical_exposure
      - bilingual_program

    teaching_languages:
      - Spanish
      - Valencian/Catalan (co-official; teaching and assessment available in both)
      - English (partial — select subjects)

    regional_language_possible: true
    regional_language: Valencian

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
          score: 12.803
          score_type: nota_de_admision
          notes: Verified nota de corte. Source: notasdecorte.es. ANNUAL_UPDATE_REQUIRED.

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
          score: 12.803
          round: fase_ordinaria
          source: notasdecorte.es (2025-26 data) # ANNUAL_UPDATE_REQUIRED — verify at AUPV (www.aupv.es)

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
            - EVAU Comunitat Valenciana (PAU)
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
              notes: Best 2 eligible subjects count. Coefficient 0.1 or 0.2 per subject. Maximum nota de admisión is 14.0000. Coefficients ANNUAL_UPDATE_REQUIRED — verify at AUPV (www.aupv.es).
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED
                Chemistry:      0.2 # ANNUAL_UPDATE_REQUIRED
                Physics:        0.1 # ANNUAL_UPDATE_REQUIRED
                Mathematics_II: 0.1 # ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---

# Universitat de València (Estudi General)

## Overview

The Universitat de València (UV) — formally the Universitat de València Estudi General — is one of Spain's oldest universities, founded in 1499, and operates as the principal public research university of the Comunitat Valenciana. Its Facultat de Medicina i Odontologia is located in central Valencia (Avinguda de Blasco Ibáñez), with clinical training delivered across the Hospital Clínic Universitari de Valencia and an affiliated hospital network covering the Valencia metropolitan area.

UV Medicine holds confirmed WFME (World Federation for Medical Education) quality accreditation — a significant formal credential for graduates planning international medical careers. The programme is delivered in Spanish and Valencian (co-official in the Comunitat Valenciana), with English progressively embedded in select subjects.

Admission is managed through AUPV (Accés a la Universitat Pública Valenciana — www.aupv.es), the Valencian public university admissions framework. UV uses the standard nota de admisión formula common to all Spanish public universities. The number of seats and nota de corte for recent cycles are PENDING_CONFIRMATION and must be verified directly at AUPV for current-cycle planning.

## Quick Evaluation

- **Degree:** Grau en Medicina — 6 years — 360 ECTS
- **Seats:** PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED — verify at AUPV)
- **Nota de corte (2025-26):** 12.803 out of 14.000 (source: notasdecorte.es; ANNUAL_UPDATE_REQUIRED)
- **Admission mechanism:** Nota de admisión (nota de corte model); no exam, no interview
- **Competitiveness:** Very high — Medicine at UV is consistently among the most competitive programmes in the Comunitat Valenciana
- **Nota de corte (current):** PENDING_CONFIRMATION — verify at www.aupv.es (ANNUAL_UPDATE_REQUIRED)
- **Tuition (approximate):** ~700–1,100 EUR/year for EU residents (Valencian tariff — historically lower than Catalan tariff; ANNUAL_UPDATE_REQUIRED)
- **Clinical training from:** Year 3 — across Hospital Clínic Universitari and affiliated hospitals
- **Teaching language:** Spanish and Valencian (co-official); English partial
- **WFME accreditation:** Confirmed
- **International access:** Via PCE/UNED Credencial or Credencial UE through AUPV

## Key Facts

| Parameter | Value |
|---|---|
| Official name | Universitat de València (Estudi General) |
| Degree | Grau en Medicina |
| Duration | 6 years (360 ECTS) |
| Annual seats | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Faculty location | Facultat de Medicina i Odontologia, Avinguda de Blasco Ibáñez 15, 46010 Valencia |
| Year 1–2 location | Facultat de Medicina (central Valencia campus) |
| Year 3–6 location | Hospital Clínic Universitari and affiliated hospitals |
| Teaching language | Spanish; Valencian (co-official); English (partial) |
| Admission system | AUPV (Accés a la Universitat Pública Valenciana) |
| No proprietary exam | Correct |
| No interview | Correct |
| Nota de corte (current) | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| WFME accreditation | Confirmed |
| Tuition (EU, indicative) | ~700–1,100 EUR/year (ANNUAL_UPDATE_REQUIRED) |
| Tuition (non-EU, indicative) | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Founded | 1499 |

## Program Options

UV offers a single Grau en Medicina programme. There is no separate bilingual cohort, no English-medium track, and no alternative campus. All students share the same curriculum structure, taught in Spanish and Valencian.

The co-official status of Valencian in the Comunitat Valenciana means that teaching, materials, and assessment may be delivered in either language. International students and students from other Spanish regions should be aware that some lectures and materials are in Valencian; adaptation to this bilingual environment is typically achievable but requires awareness.

A partial English component is progressively integrated into select subjects, consistent with the trend across Spanish public medical education.

## Program Structure

The Grau en Medicina at UV is structured across 6 academic years, totalling 360 ECTS:

**Phase 1 — Preclínica (Years 1–2):** Core biomedical sciences at the Facultat de Medicina i Odontologia on the Blasco Ibáñez campus in central Valencia. Subjects include Anatomy, Physiology, Biochemistry, Cell Biology, Histology, Immunology, Microbiology, Pharmacology, and Pathology. Clinical skills and simulated patient contact are progressively introduced.

**Phase 2 — Clínica (Years 3–6):** Students are assigned to affiliated teaching hospitals (Unitats Docents). Clinical instruction spans all major medical specialties. Year 6 includes an integrated clinical rotation (Rotatorio Clínico) across multiple departments and specialties.

**TFG (Treball de Fi de Grau / Trabajo de Fin de Grado):** Mandatory final-year research or clinical project. Language of presentation: PENDING_CONFIRMATION.

**Electives:** Optional credits available during the curriculum. Exact ECTS volume: PENDING_CONFIRMATION.

## Teaching Methodology

UV Medicine uses a traditional lecture-based structure in preclinical years, supported by laboratory practice, small-group seminars, and progressive simulation-based clinical skills development. The Facultat de Medicina has clinical simulation facilities at the Blasco Ibáñez campus.

From Year 3, teaching shifts to hospital-embedded clinical instruction, with specialist-supervised clinical attachment as the primary learning format. Small group teaching (seminaris, casos clínics) complements clinical supervision throughout the clinical phase.

The bilingual Spanish/Valencian academic environment is a distinctive feature of UV. Students engage with scientific literature in both languages and in English for international-format content.

UV's research culture — supported by connections to INCLIVA (Instituto de Investigación Sanitaria Clínica Hospital) and FISABIO (Fundació per al Foment de la Investigació Sanitària i Biomèdica de la Comunitat Valenciana) — means that clinical placements are embedded in active research environments.

## Clinical Training

UV Medicina's clinical training is centred on the Hospital Clínic Universitari de Valencia, the principal university teaching hospital, located in central Valencia. The clinical network extends to additional affiliated hospitals across the Valencian metropolitan area.

**Principal clinical training hospitals and units (PENDING_CONFIRMATION — verify current network at the Facultat de Medicina):**

- Hospital Clínic Universitari de València (principal teaching hospital — central Valencia; houses INCLIVA research institute)
- Hospital General Universitari de València
- Hospital Universitari i Politècnic La Fe (a major Valencian tertiary hospital — one of Spain's largest; ANNUAL_UPDATE_REQUIRED — confirm current affiliation status)
- Additional affiliated hospitals and primary care centres (ANNUAL_UPDATE_REQUIRED — network subject to annual revision)

Students are assigned to Unitats Docents from Year 3. Assignment processes depend on administrative and merit-based criteria (ANNUAL_UPDATE_REQUIRED).

The Hospital La Fe de Valencia is one of Spain's largest hospital complexes and, if included in the UV clinical network, represents a high-complexity, high-volume training environment. Affiliation status should be confirmed directly with the faculty (ANNUAL_UPDATE_REQUIRED).

## International Recognition and Opportunities

UV Medicine holds confirmed WFME quality accreditation. This is a significant formal credential for graduates planning postgraduate training in the UK, USA, Canada, Australia, and other countries that require WFME-listed institution graduation.

The UV degree (Grau en Medicina, MECES Level 3) is recognised across the EU under Directive 2005/36/EC.

**International exchange:** UV participates in the Erasmus+ programme. The Facultat de Medicina i Odontologia manages Medicine-specific mobility agreements. Exchange periods are typically available from Year 3 (clinical phase). ANNUAL_UPDATE_REQUIRED — verify Medicine-specific Erasmus slots at the faculty mobility office.

UV is a member of several international university networks and research alliances (PENDING_CONFIRMATION on current memberships relevant to Medicine). Its geographical position in Valencia — a major Mediterranean city with strong international connectivity — supports graduate internationalisation pathways.

## Admission Model

UV Medicine is part of the Comunitat Valenciana's public university admissions system, coordinated through AUPV (Accés a la Universitat Pública Valenciana — www.aupv.es). Admission is determined exclusively by the nota de admisión — there is no proprietary entrance exam, no interview, and no portfolio component.

**The nota de admisión formula (identical across all Spanish public universities):**

```
Nota de admisión = 0.6 × Nota media de Bachillerato
                 + 0.4 × Nota EVAU (fase general)
                 + up to 4.0 bonus points from EVAU fase específica
```

- **Base score maximum:** 10.0000 (Bachillerato + EVAU general phase combined)
- **Maximum nota de admisión:** 14.0000 (with full specific-phase bonus)
- **Specific phase:** Best 2 eligible subjects count. Each subject grade is multiplied by the ponderation coefficient assigned by UV for Medicine. Biology and Chemistry typically receive 0.2 (ANNUAL_UPDATE_REQUIRED — verify at AUPV each year).

**Access routes:**
- EVAU Comunitat Valenciana (PAU): standard route for Valencian Bachillerato students
- EVAU from other Spanish regions: valid; equivalent calculation applies via AUPV
- International via PCE/UNED (Credencial UNEDasiss): valid; applies via AUPV portal
- International via Credencial UE: valid
- Direct homologation (select countries): valid

**Language note:** Teaching is in Spanish and Valencian. There is no formal Valencian-language admission requirement, but candidates should be aware of the bilingual academic environment.

## Admission Process

### For Valencian PAU students

1. Complete Bachillerato and register for EVAU (PAU Comunitat Valenciana).
2. Sit EVAU: mandatory general phase + optional specific phase (strongly recommended — up to 4 bonus points).
3. Receive nota de admisión.
4. Submit preinscripció through the AUPV portal (www.aupv.es) during the designated window (ANNUAL_UPDATE_REQUIRED for exact dates).
5. List UV Medicina in your degree preferences.
6. Await results of the fase ordinaria assignment.
7. If not admitted in fase ordinaria, apply for the fase extraordinaria.
8. If admitted: complete matriculació within the published deadline.

### For students from other Spanish regions

1. Sit EVAU in your region. Confirm that specific-phase subject results are accepted via AUPV with UV's ponderation coefficients for Medicine.
2. Apply through AUPV (www.aupv.es) with your nota de admisión.
3. Compete in the same applicant pool as Valencian students.

### For international PCE/UNED students

1. Obtain a UNEDasiss Credencial. Sit PCE in Biology and Chemistry (coefficient 0.2 each; ANNUAL_UPDATE_REQUIRED).
2. Apply through AUPV with the Credencial calificación.
3. Verify Valencian-specific requirements for international applicants at AUPV (ANNUAL_UPDATE_REQUIRED).
4. If admitted: arrange NIE, visa if applicable, and housing.

## Admission Timeline

All dates are approximate and ANNUAL_UPDATE_REQUIRED. Verify each year at www.aupv.es and the UV Faculty of Medicine admissions page.

| Phase | Approximate Period |
|---|---|
| EVAU ordinaria (Comunitat Valenciana) | June (ANNUAL_UPDATE_REQUIRED) |
| EVAU extraordinaria (Comunitat Valenciana) | July (ANNUAL_UPDATE_REQUIRED) |
| AUPV preinscripció ordinaria | June–July (ANNUAL_UPDATE_REQUIRED) |
| Results fase ordinaria | July (ANNUAL_UPDATE_REQUIRED) |
| Enrolment (matriculació) window | July–September (ANNUAL_UPDATE_REQUIRED) |
| Results fase extraordinaria | August–September (ANNUAL_UPDATE_REQUIRED) |
| Academic year begins | September (ANNUAL_UPDATE_REQUIRED) |
| PCE/UNED sessions | February and June (ANNUAL_UPDATE_REQUIRED) |

## Admission Score Distribution

The nota de corte for UV Medicina in the 2025-26 intake was **12.803** out of 14.000 (source: notasdecorte.es; ANNUAL_UPDATE_REQUIRED — verify at www.aupv.es for current and historical figures). Medicine is consistently among the most competitive programmes offered at UV and at other Valencian public universities.

**Historical trend (ANNUAL_UPDATE_REQUIRED):**

| Intake Year | Nota de Corte | Source |
|---|---|---|
| 2025-2026 | 12.803 | notasdecorte.es (verified) |
| 2024-2025 | PENDING_CONFIRMATION | — |
| 2023-2024 | PENDING_CONFIRMATION | — |

**What is known:**

Public Medicine programmes in the Comunitat Valenciana are highly competitive. The 2025-26 nota de corte for UV was 12.803, positioning it in the mid-range of Spanish public Medicine programmes nationally. UV is typically among the most competitive programmes in the Valencian system given its flagship status.

**Ponderation coefficients for Medicine at UV (ANNUAL_UPDATE_REQUIRED — verify at AUPV):**

| Subject | Coefficient |
|---|---|
| Biology | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Chemistry | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Physics | 0.1 (ANNUAL_UPDATE_REQUIRED) |
| Mathematics II | 0.1 (ANNUAL_UPDATE_REQUIRED) |

**For PCE/UNED international students:** The same formula applies. Biology and Chemistry PCE results at coefficient 0.2 each are the critical levers. Given the typically very high nota de corte at UV, near-perfect PCE scores are required.

**Strategic note:** Students from other Spanish regions (EVAU from Madrid, Andalucía, Catalunya, etc.) can compete in the AUPV process using their existing EVAU scores. This makes UV a potential option for high-scoring students from outside Valencia who want to access a major Mediterranean public university with WFME accreditation and lower tuition than Catalan universities.

## Costs and Payment Structure

Tuition fees at UV are set by the Generalitat Valenciana via regional decree. The Comunitat Valenciana has historically maintained lower public university tuition tariffs than Catalunya, making UV one of the more affordable major public medicine programmes in Spain for EU-resident students.

| Fee Concept | EU/EEA Students | Non-EU Students | Notes |
|---|---|---|---|
| Annual tuition (per year, approx.) | ~700–1,100 EUR | PENDING_CONFIRMATION | ANNUAL_UPDATE_REQUIRED — Valencian tariff; lower than Catalan |
| Per-credit fee (experimental branch) | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | Medicine = experimental branch |
| Enrolment / administrative fees | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Student insurance | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Repeat enrolment surcharge | Higher per-credit rate | Higher per-credit rate | Applies from 2nd enrolment in same subject |

Non-EU students face significantly higher fees under the extracomunitario tariff. PENDING_CONFIRMATION for current figures (ANNUAL_UPDATE_REQUIRED).

The Valencian fee structure is among the most favourable for EU-resident students among major Spanish public universities offering Medicine. Verify the current decreto de tasas from the Generalitat Valenciana.

## Scholarships and Financial Aid

**National level:**
- **Beca General MEC (Ministerio de Educación y Formación Profesional):** Available to students meeting income and academic thresholds. Annual application via the MEFP portal (ANNUAL_UPDATE_REQUIRED).
- **Beca Movilidad (Erasmus+):** Available for approved Erasmus exchange periods.

**Regional level (Generalitat Valenciana):**
- The Generalitat Valenciana offers need-based scholarship support for Valencian public university students. PENDING_CONFIRMATION — verify current programmes at gva.es (ANNUAL_UPDATE_REQUIRED).

**University level:**
- UV has internal scholarship and emergency aid mechanisms. Details at uv.es/becas (ANNUAL_UPDATE_REQUIRED).

Scholarship eligibility typically requires passing a minimum number of ECTS per year.

## Accommodation and Cost of Living

Valencia is a large Mediterranean city with one of the most affordable costs of living among major Spanish university cities. This gives UV a notable financial advantage over Madrid or Barcelona for students who need to relocate.

| Cost Category | Approximate Monthly Range | Notes |
|---|---|---|
| Shared flat room (piso compartido — Valencia) | 350–600 EUR | ANNUAL_UPDATE_REQUIRED — significantly cheaper than Madrid or Barcelona |
| University residence / colegio mayor | 500–900 EUR | ANNUAL_UPDATE_REQUIRED |
| Food (self-catering) | 180–300 EUR | ANNUAL_UPDATE_REQUIRED |
| Public transport (abono jove / bus + metro) | 15–25 EUR | ANNUAL_UPDATE_REQUIRED |
| Books / materials (Year 1 estimate) | 200–400 EUR | ANNUAL_UPDATE_REQUIRED |

The Facultat de Medicina i Odontologia is located on Avinguda de Blasco Ibáñez in central Valencia, within the Pla del Real / Universitat district. This is one of the most liveable urban campus locations in Spain, with direct access to the beach (Malvarrosa, 15–20 minutes by tram), extensive public transport, and a large student population.

Valencia's rental market is considerably more accessible than Barcelona or Madrid. Students can typically find shared accommodation within 10–15 minutes' walk or cycle from the faculty.

## International Exchange and Mobility Programs

UV participates in the Erasmus+ programme. The Facultat de Medicina manages its own Medicine-specific mobility agreements. Exchange periods are typically available from Year 3 (clinical phase).

**Important limitation:** Not all UV university-level Erasmus agreements extend to Medicine. Students should verify Medicine-specific slots with the Facultat de Medicina's Oficina de Relacions Internacionals (ANNUAL_UPDATE_REQUIRED).

UV's international networks and bilateral agreements specific to the Medicine degree: PENDING_CONFIRMATION — verify current agreements at the faculty level.

Incoming international exchange students to UV Medicine: PENDING_CONFIRMATION on formal incoming exchange structure for the Medicine degree.

## MIR Preparation and Professional Outcomes

UV graduates are eligible to sit the MIR (Médico Interno Residente) examination after completing the Grau en Medicina.

**MIR results for UV graduates:** PENDING_CONFIRMATION — UV does not publish programme-specific MIR pass rates or ranking distributions in a readily verifiable public format as of the date of this file.

**General context:** UV's clinical training through Hospital Clínic Universitari de Valencia and the affiliated network is regarded as solid preparation for the MIR. The WFME accreditation seal confirms formal programme quality at an international standard.

Post-MIR, graduates can specialise within the Spanish Sistema Nacional de Salud or pursue international pathways. WFME accreditation facilitates recognition of the UV degree for postgraduate training abroad.

## Strategic Fit

### Good Fit For

- Students from Valencia or the Comunitat Valenciana who want to study at the region's flagship public university at lower tuition costs than Catalan institutions.
- Candidates from other Spanish regions or internationally (via PCE/UNED) with a very high nota de admisión who want a WFME-accredited programme outside Madrid and Barcelona.
- Students who prioritise cost of living — Valencia is significantly cheaper than Madrid and Barcelona while offering a high quality of life.
- Research-oriented students interested in the INCLIVA or FISABIO research environments affiliated with the clinical network.
- Candidates who are comfortable in a bilingual Spanish/Valencian academic environment.

### Less Suitable For

- Candidates whose nota de admisión does not reach the nota de corte for UV Medicine (12.803 in 2025-26; ANNUAL_UPDATE_REQUIRED — verify at AUPV).
- International students with no knowledge of Spanish or Valencian — the degree is taught primarily in Spanish and Valencian; English is only partially embedded.
- Students who require an English-medium or formally bilingual (Spanish/English) track — UV does not offer one.
- Candidates who prefer the academic or cultural environment of Madrid or Barcelona — Valencia is a major city but has a different character and scale from Spain's two largest urban centres.

## Risks and Considerations

1. **Nota de corte variability:** The nota de corte for UV Medicine was 12.803 in 2025-26. This is the most recent verified figure but changes annually. Candidates must verify the current intake cycle nota de corte at www.aupv.es before using UV as a planning target. Prior-year data for 2024-25 and 2023-24 remains PENDING_CONFIRMATION.

2. **Seat count not verified:** The number of seats is PENDING_CONFIRMATION. Without confirmed seat count, applicants-per-seat ratios cannot be estimated. Verify at AUPV or directly with the UV faculty.

3. **Hospital network details:** The full current clinical affiliation network — including Hospital La Fe de Valencia — requires verification with the faculty (ANNUAL_UPDATE_REQUIRED). Large Valencian hospitals have periodically changed their affiliation structures.

4. **Valencian language environment:** Teaching and assessment can occur in Valencian. Students from outside the Comunitat Valenciana without Valencian proficiency will face a practical adaptation challenge, particularly in seminars and small group settings. This risk is lower than at UB or UAB (where Catalan is the primary language), but it is real.

5. **Non-EU tuition:** Fees for non-EU students are PENDING_CONFIRMATION. Verify with the UV admissions office before the intake year.

6. **AUPV data access:** All score and seat data for UV must be verified at www.aupv.es. The dynamic nature of the AUPV system means data changes frequently and should not be referenced from secondary sources.

## Important Notes

- Nota de corte and seat count are PENDING_CONFIRMATION — both must be verified at www.aupv.es before using this file for admission planning (ANNUAL_UPDATE_REQUIRED).
- All admission dates are ANNUAL_UPDATE_REQUIRED — verify at www.aupv.es and the UV faculty admissions page.
- WFME accreditation is confirmed for UV as of the date of this file; reaccreditation cycles should be monitored.
- Non-EU students must verify visa, NIE, and health insurance requirements separately.
- Teaching occurs in both Spanish and Valencian. Candidates without Valencian proficiency should factor this into their preparation.
- Valencian public university tuition is among the most affordable in Spain — verify the current decreto de tasas from the Generalitat Valenciana.

## Key Insight

UV Medicina is a WFME-accredited public Medicine programme located in one of Spain's most liveable cities, with significantly lower accommodation costs and tuition tariffs than comparable programmes in Madrid or Barcelona. Its strategic value is strongest for candidates who are based in Valencia or the Comunitat Valenciana, or for out-of-region candidates who prioritise cost-efficiency and WFME accreditation together. The principal data gaps — nota de corte and seat count — must be resolved before UV can be used as a precise planning target. Until those figures are verified at AUPV, UV should be treated as a "strong candidate" option with confirmed WFME accreditation and favourable cost profile, contingent on score alignment with the actual threshold.

## Final Takeaway

UV Medicina combines institutional prestige (Spain's third-oldest university), WFME accreditation, and a favourable cost structure in a high-quality-of-life Mediterranean city. For candidates who can reach the nota de corte — which is PENDING_CONFIRMATION but likely in the 13.0+ range for recent cycles — UV represents excellent value relative to equivalent programmes in Madrid (higher costs) or Catalunya (higher tuition, more expensive accommodation). The bilingual Spanish/Valencian environment is manageable for most Spanish-language learners and does not constitute the same challenge as fully Catalan-dominant institutions. Verify the nota de corte at AUPV before committing to this as a primary or core option.

## Frequently Asked Questions

**What is the nota de corte for UV Medicine?**
The nota de corte for UV Medicine in 2025-26 was **12.803** out of 14.000 (source: notasdecorte.es; ANNUAL_UPDATE_REQUIRED — verify at www.aupv.es each cycle). It is the nota de admisión of the last student admitted and changes annually based on competition. Prior-year figures (2024-25, 2023-24) remain PENDING_CONFIRMATION.

**How is the nota de admisión calculated?**
Nota de admisión = 0.6 × Nota media de Bachillerato + 0.4 × Nota EVAU (fase general) + bonus from up to 2 specific-phase subjects (each grade × ponderation coefficient of 0.1 or 0.2). Maximum score is 14.0000.

**Is UV Medicine WFME-accredited?**
Yes. UV Medicina holds confirmed WFME quality accreditation. This is significant for graduates planning postgraduate training in countries requiring WFME-listed institution graduation, such as the UK, USA, Canada, and Australia.

**Can students from other Spanish regions apply to UV?**
Yes. Students from other Spanish regions who have sat EVAU can apply through AUPV using their nota de admisión. They compete in the same applicant pool as Valencian students. The same nota de corte applies to all applicants.

**Can international students apply via PCE?**
Yes. International students with a UNEDasiss Credencial can apply through AUPV. Biology and Chemistry PCEs (coefficient 0.2 each; ANNUAL_UPDATE_REQUIRED) are the most valuable specific-phase subjects. Near-perfect PCE scores are likely required given the competitive nota de corte at UV.

**What are the tuition fees?**
For EU/EEA students, approximately 700–1,100 EUR/year (ANNUAL_UPDATE_REQUIRED — Valencian tariff, among the lowest for major Spanish public universities offering Medicine). For non-EU students: PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED). Verify the current Valencian decreto de tasas.

**Is there an interview or entrance exam?**
No. Admission is based solely on the nota de admisión. There is no interview, no proprietary exam, and no portfolio requirement.

**What language is the degree taught in?**
Spanish and Valencian (co-official in the Comunitat Valenciana). A partial English component exists in select subjects. There is no English-medium track. Students without Valencian proficiency can manage, as Spanish is widely used, but Valencian appears in teaching materials and some seminars.

**Where is the faculty located?**
The Facultat de Medicina i Odontologia is at Avinguda de Blasco Ibáñez 15, 46010 Valencia — in the central university district, close to the beach and well-connected by public transport.

**What are the costs of living in Valencia?**
Valencia is significantly more affordable than Madrid or Barcelona. Shared flat rooms typically range from 350–600 EUR/month (ANNUAL_UPDATE_REQUIRED), food costs are lower, and public transport is efficient and cheap. This cost advantage is one of UV's strongest strategic differentiators for students relocating from other regions or internationally.
