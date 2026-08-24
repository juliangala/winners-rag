---
id: uib

type: university
subtype: public

name: Universitat de les Illes Balears
short_name: UIB

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Palma de Mallorca
  region: Islas Baleares
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
      score: 12.510
      score_type: nota_de_admision
      notes: "Source: notasdecorte.es. ANNUAL_UPDATE_REQUIRED."

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
  - id: uib-medicina
    campus: Facultat de Medicina, Campus de la UIB, Palma de Mallorca
    modality: standard
    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - medium_competitiveness
    teaching_languages:
      - Spanish
      - Catalan
    regional_language_possible: true
    regional_language: Catalan (Mallorquí variant)
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
          score: 12.510
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
          score: 12.510
          round: convocatoria_ordinaria
          source: "notasdecorte.es / UIB admissions system (uib.es/es/admissio/) — ANNUAL_UPDATE_REQUIRED"

        - intake_year: 2024-2025
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: "UIB admissions — ANNUAL_UPDATE_REQUIRED"

        - intake_year: 2023-2024
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: "UIB admissions — ANNUAL_UPDATE_REQUIRED"

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
              notes: 60% of the nota de admisión. Grades from both Bachillerato years averaged.

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
              notes: Best 2 eligible subjects × ponderation coefficient (0.1 or 0.2). Max nota 14.0000. Ponderation authority PENDING_CONFIRMATION (Consell Social de la UIB / Govern Balear).
              subject_ponderations:
                Biology:        ANNUAL_UPDATE_REQUIRED
                Chemistry:      ANNUAL_UPDATE_REQUIRED
                Physics:        ANNUAL_UPDATE_REQUIRED
                Mathematics_II: ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---

# Universitat de les Illes Balears (UIB) — Grado en Medicina

## Overview

The Universitat de les Illes Balears (UIB) is the sole public university of the Balearic Islands, located on its main campus in Palma de Mallorca. Founded in 1978, UIB is a relatively small autonomous-community university, with the Medicine degree (Facultat de Medicina) being among the newer additions to its academic portfolio. The exact launch year of the Medicine degree is PENDING_CONFIRMATION.

For the 2025-26 intake, UIB Medicine recorded a nota de corte of 12.510 (source: notasdecorte.es) — the lowest of the four universities in this file set, and the lowest among the four most recently added public Medicine programmes in this database. This places UIB in the medium-high competitiveness tier for public Medicine in Spain: the threshold is high by absolute national standards, but meaningfully below the flagship programmes in Madrid and Barcelona.

UIB's geographic context is a defining factor: Palma de Mallorca is an island city with significantly higher transportation costs, a tight housing market driven by tourism-sector pressure, and a Catalan (specifically Mallorquí)-speaking regional environment. The island setting creates both lifestyle advantages (climate, maritime environment) and practical logistical constraints (travel costs, housing, limited hospital ecosystem).

Admission to UIB Medicine is managed through the UIB's own admissions system (uib.es/es/admissio/), which operates within the national EVAU framework. There is no proprietary entrance exam and no interview. Students from mainland Spain can apply but compete alongside Balearic Islands EVAU students in a common admission process (exact quota structure PENDING_CONFIRMATION).

## Quick Evaluation

- **Degree:** Grado en Medicina — 6 years — 360 ECTS
- **Seats:** PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED)
- **Admission mechanism:** Nota de admisión (nota de corte model via UIB admissions system); no exam, no interview
- **Competitiveness:** Medium-high nationally — lowest nota de corte among the four universities in this set
- **Nota de corte (2025-26):** 12.510 out of 14.000 (source: notasdecorte.es; ANNUAL_UPDATE_REQUIRED)
- **Tuition (approximate):** ~1,205 EUR/year for EU residents (ANNUAL_UPDATE_REQUIRED)
- **Clinical training from:** Year 3 — Hospital Universitari Son Espases (main) and affiliated Balearic Islands centres
- **Teaching language:** Spanish and Catalan (Mallorquí); possibly with English elements (PENDING_CONFIRMATION)
- **WFME accreditation:** PENDING_CONFIRMATION
- **International access:** Via PCE/UNED or Credencial UE

## Key Facts

| Parameter | Value |
|---|---|
| Official name | Universitat de les Illes Balears |
| Short name | UIB |
| Degree | Grado en Medicina (Grau en Medicina) |
| Duration | 6 years (360 ECTS) |
| Annual seats | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Campus | Facultat de Medicina, UIB Campus, Palma de Mallorca |
| Year 1–2 location | UIB campus, Palma de Mallorca |
| Year 3–6 location | Hospital Universitari Son Espases; Hospital Son Llàtzer; affiliated Balearic centres |
| Teaching language | Spanish and Catalan (Mallorquí); English elements PENDING_CONFIRMATION |
| Admission type | Nota de admisión (UIB admissions system — uib.es/es/admissio/) |
| No proprietary exam | Correct |
| No interview | Correct |
| Tuition (EU, indicative) | ~1,205 EUR/year (ANNUAL_UPDATE_REQUIRED) |
| Tuition (non-EU, indicative) | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Founded | UIB: 1978; Medicine degree: PENDING_CONFIRMATION (exact start year) |
| Website | https://www.uib.es/es/lauib/estructura/facultats-i-escoles/fmed/ |

## Program Options

UIB offers a single Grado en Medicina track at its Palma de Mallorca campus. There is no bilingual cohort and no alternative campus. All admitted students follow the same curriculum and hospital rotation network within the Balearic Islands health system.

As a smaller autonomous-community university operating in an island ecosystem, UIB Medicine has a more limited programme scale than major peninsula universities. The seat count is PENDING_CONFIRMATION but is expected to be smaller than at UCM, UB, or UAM. This smaller cohort may create a more intimate learning environment, though it also implies a narrower hospital network and more limited specialist diversity.

Cross-regional access: candidates from mainland Spain can apply to UIB via the national EVAU framework. The specific quota mechanism (whether mainland applicants compete in a general pool or a restricted quota) is PENDING_CONFIRMATION — candidates from outside the Balearic Islands should verify admission rules with UIB before applying.

## Program Structure

The Grado en Medicina at UIB is structured across 6 academic years totalling 360 ECTS, following the Spanish national regulatory framework.

**Phase 1 — Preclínica (Years 1–2):** Core biomedical sciences delivered at the UIB campus in Palma. Subjects include Human Anatomy, Cell Biology, Biochemistry, Physiology, Histology, Microbiology, Immunology, Pharmacology, and Pathological Anatomy. Clinical skills and professionalism are introduced from the early years.

**Phase 2 — Clínica (Years 3–6):** Hospital-based clinical training in the Balearic Islands public health network (Ibsalut — Servei de Salut de les Illes Balears). Students rotate through internal medicine, surgery, obstetrics and gynaecology, paediatrics, psychiatry, primary care, and other specialties. Year 6 features an extended clinical rotation (rotatorio) period.

**TFG (Final Degree Project):** Mandatory. Language and format requirements PENDING_CONFIRMATION.

**Electives:** Optional subjects integrated within the degree plan (exact ECTS and subject list PENDING_CONFIRMATION).

## Teaching Methodology

UIB Medicine delivers instruction primarily in Spanish and Catalan (Mallorquí), reflecting the co-official language status of Catalan in the Balearic Islands. The specific ratio of Spanish to Catalan instruction and any English-medium components are PENDING_CONFIRMATION — candidates should verify with the Facultat de Medicina before enrolment.

UIB as an institution is a comprehensive regional university with a student-centred culture. The medical faculty, as a newer programme, is expected to integrate contemporary pedagogical approaches — but the detailed balance between lecture-based instruction, PBL, and simulation is PENDING_CONFIRMATION.

The island context creates a distinctive academic environment: the Balearic Islands health system (Ibsalut) is a self-contained ecosystem where students are immersed in the full primary-to-tertiary care continuum of a defined geographic region. This may be advantageous for understanding integrated healthcare delivery but limits exposure to the case volumes and sub-speciality diversity of major metropolitan hospital networks.

## Clinical Training

Clinical training at UIB takes place within the Ibsalut (Servei de Salut de les Illes Balears) network of hospitals and primary care centres. Rotations begin from Year 3.

**Primary affiliated hospitals:**

- **Hospital Universitari Son Espases** — Palma de Mallorca. The largest hospital in the Balearic Islands and the principal tertiary referral centre for the archipelago. Son Espases is a modern hospital (opened 2011) with broad specialist coverage and serves as the main UIB Medicine clinical training centre.
- **Hospital Son Llàtzer** — Palma de Mallorca. A secondary general hospital within the Palma metropolitan area; also part of the UIB clinical network.

Additional affiliated centres within the Ibsalut network may include:
- Hospital de Inca (Mallorca)
- Hospital de Manacor (Mallorca)
- Primary care centres across Mallorca

Clinical rotation to hospitals on other Balearic Islands (Ibiza, Menorca, Formentera) is PENDING_CONFIRMATION.

Hospital Universitari Son Espases is the dominant clinical training environment. As the only major tertiary hospital in the islands, it handles a broad case mix but with lower absolute case volumes in rare and sub-specialised conditions compared to mainland referral centres. The islands' population (approximately 1.2 million) is significantly smaller than Madrid or Barcelona metropolitan areas.

## International Recognition and Opportunities

The UIB Grado en Medicina complies with European Directive 2005/36/EC on the recognition of professional qualifications, enabling graduates to seek medical licences across EU/EEA member states under the regulated professions framework.

**WFME accreditation:** PENDING_CONFIRMATION — verify current status at the UIB Facultat de Medicina website.

**Erasmus+ mobility:** UIB participates in the Erasmus+ programme at the institutional level. Medicine-specific bilateral agreements are PENDING_CONFIRMATION — students should verify with the Facultat de Medicina's international office which partner medical faculties are active and from which study year exchange is permitted.

UIB's island location and smaller institutional size may result in a smaller volume of Medicine-specific Erasmus slots compared to major mainland universities. This is PENDING_CONFIRMATION.

The Balearic Islands receive a significant volume of international tourism and have a notable presence of non-Spanish-speaking residents (German, British, Nordic communities). While this does not directly translate into formal academic internationalisation, it creates a cosmopolitan social environment.

## Admission Model

UIB Medicine operates within the national EVAU admissions framework. Candidates apply through the UIB admissions portal (uib.es/es/admissio/). Admission is determined exclusively by the nota de admisión — there is no proprietary entrance exam and no interview.

**The nota de admisión formula:**

```
Nota de admisión = 0.6 × Nota media de Bachillerato
                 + 0.4 × Nota EVAU (fase general)
                 + up to 4.0 bonus points from EVAU fase específica
```

- **Base score maximum:** 10.0000
- **Maximum nota de admisión:** 14.0000 (with full specific-phase bonus)
- **Specific phase:** Best 2 eligible subjects selected. Each subject grade × ponderation coefficient (0.1 or 0.2) set annually. Ponderation authority: PENDING_CONFIRMATION (Consell Social de la UIB / Govern Balear).

**Ponderation coefficients for Medicine at UIB (ANNUAL_UPDATE_REQUIRED — verify at the official UIB ponderation table):**

Biology: ANNUAL_UPDATE_REQUIRED, Chemistry: ANNUAL_UPDATE_REQUIRED, Physics: ANNUAL_UPDATE_REQUIRED, Mathematics II: ANNUAL_UPDATE_REQUIRED.

**Note on cross-regional applicants:** The specific rules for students who sat EVAU in other Spanish regions applying to UIB Medicine are PENDING_CONFIRMATION. Whether they compete in the general pool or a specific quota must be verified at the UIB admissions office before applying. This is particularly important for mainland Spanish and international candidates.

**Access routes:**
- Balearic Islands EVAU (PAU): standard route
- EVAU from other Spanish regions: valid (PENDING_CONFIRMATION on quota rules)
- FP Grado Superior + EVAU specific phase: valid
- International via PCE/UNED (Credencial UNEDasiss): valid (PENDING_CONFIRMATION on specific UIB process)
- International via Credencial UE: valid
- Direct homologation (select countries): valid; check UIB requirements

## Admission Process

### For Spanish PAU students (Balearic Islands EVAU)

1. Complete Bachillerato and sit EVAU (Balearic Islands PAU).
2. Receive nota de admisión from the EVAU authority.
3. Submit preinscripció through the UIB admissions portal (uib.es/es/admissio/) during the designated window (ANNUAL_UPDATE_REQUIRED).
4. List UIB Medicina in your degree preferences.
5. Await results of the ordinaria convocatoria.
6. If not admitted in the ordinaria: apply for the extraordinaria convocatoria.
7. If admitted: complete enrolment (matrícula) at UIB within the published deadline.

### For Spanish PAU students (other regions)

1. Verify cross-regional admission rules and applicable quotas at UIB (PENDING_CONFIRMATION).
2. Sit EVAU in your home region and obtain nota de admisión.
3. Apply through UIB admissions portal following their cross-regional process (ANNUAL_UPDATE_REQUIRED).
4. If admitted: complete enrolment. Factor in relocation and island living costs.

### For international PCE/UNED students

1. Obtain a secondary qualification equivalent to Spanish Bachillerato.
2. Apply to UNEDasiss for a Credencial. Submit transcripts and request subject recognition.
3. Sit PCE at UNED for subjects relevant to Medicine — Biology and Chemistry are typically most strategically valuable (ANNUAL_UPDATE_REQUIRED — verify UIB ponderation coefficients).
4. Receive final UNEDasiss Credencial with calificación (5–10 scale).
5. Submit application through the UIB admissions process for PCE/UNED candidates (PENDING_CONFIRMATION on exact portal and process).
6. If admitted: complete enrolment, arrange visa/NIE if applicable, and plan for island relocation including transport logistics.

## Admission Timeline

All dates are approximate based on standard Spanish EVAU and UIB admission calendar patterns. All dates are ANNUAL_UPDATE_REQUIRED — verify at the UIB admissions portal (uib.es/es/admissio/).

| Phase | Approximate Period |
|---|---|
| EVAU ordinaria (Islas Baleares) | June (ANNUAL_UPDATE_REQUIRED) |
| EVAU extraordinaria (Islas Baleares) | July (ANNUAL_UPDATE_REQUIRED) |
| UIB preinscripció ordinaria | June–July (ANNUAL_UPDATE_REQUIRED) |
| UIB results ordinaria | July (ANNUAL_UPDATE_REQUIRED) |
| Enrolment window | July–September (ANNUAL_UPDATE_REQUIRED) |
| UIB preinscripció extraordinaria | August–September (ANNUAL_UPDATE_REQUIRED) |
| Academic year begins | September (ANNUAL_UPDATE_REQUIRED) |
| PCE/UNED sessions | February and June (ANNUAL_UPDATE_REQUIRED) |

## Admission Score Distribution

UIB Medicine's nota de corte for 2025-26 was 12.510 (source: notasdecorte.es; ANNUAL_UPDATE_REQUIRED). This is the lowest of the four universities in this file set — approximately 0.006 points below UPF (12.516), 0.208 below UA (12.718), and 0.361 below UAH (12.871).

**Historical trend (ANNUAL_UPDATE_REQUIRED):**

| Intake Year | Nota de Corte | Source |
|---|---|---|
| 2025-2026 | 12.510 | notasdecorte.es (verified) |
| 2024-2025 | PENDING_CONFIRMATION | — |
| 2023-2024 | PENDING_CONFIRMATION | — |

**What this means strategically:**

The nota de corte of 12.510 is almost identical to UPF's 12.516 — a difference of 0.006 points, which is negligible in practical terms. Candidates who are targeting this score range should treat UIB and UPF as essentially equivalent from an admission-threshold perspective, and choose between them based on location, programme characteristics, and personal fit.

As a newer and smaller-community Medicine faculty, UIB's nota de corte history is limited and may be less stable between cycles than more established programmes. The 2025-26 figure should not be assumed to represent a long-term floor.

**Ponderation coefficients for Medicine at UIB (ANNUAL_UPDATE_REQUIRED — verify at official UIB ponderation table):**

| Subject | Coefficient |
|---|---|
| Biology | ANNUAL_UPDATE_REQUIRED |
| Chemistry | ANNUAL_UPDATE_REQUIRED |
| Physics | ANNUAL_UPDATE_REQUIRED |
| Mathematics II | ANNUAL_UPDATE_REQUIRED |

Candidates should verify the UIB ponderation table annually, as coefficients can change. This is particularly important for PCE candidates who need to select their subject strategy before sitting exams.

## Costs and Payment Structure

Tuition fees at UIB are set by the Govern Balear via regional decree and are subject to annual revision. Medicine falls within the experimental branch (rama experimental / branca experimental), carrying higher per-credit rates.

| Fee Concept | EU/EEA Students | Non-EU Students | Notes |
|---|---|---|---|
| Annual tuition (per year, approx.) | ~1,205 EUR | PENDING_CONFIRMATION | ANNUAL_UPDATE_REQUIRED |
| Per-credit fee (experimental branch) | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | Medicine = experimental branch |
| Enrolment / administrative fees | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Student insurance (seguro escolar) | ~1.12 EUR | ~1.12 EUR | ANNUAL_UPDATE_REQUIRED |
| Repeat enrolment surcharge | Higher per-credit rate | Higher per-credit rate | Applies from 2nd enrolment in same subject |

The indicative ~1,205 EUR/year is slightly higher than Madrid public universities (~1,241 EUR/year in Madrid; ~1,108 EUR/year in Catalunya; ~1,080 EUR/year in Comunitat Valenciana), reflecting Balearic Islands tariff structures. Non-EU tuition rates are significantly higher (PENDING_CONFIRMATION — verify at the current Govern Balear decreto de tasas).

**Important note on total cost:** The headline tuition fee understates the total cost of studying at UIB for students from the Spanish mainland or abroad. Island living introduces additional costs: ferry/flight travel to and from the mainland (several times per year for most students), and a housing market that is constrained by tourism-sector competition (particularly in Palma). Students should factor these costs into their overall financial planning.

## Scholarships and Financial Aid

**National level:**
- **Beca General MEC:** Available to all students at public universities meeting income and academic criteria. Covers partial tuition and may include a living stipend. Applications via the MEFP scholarship portal annually (ANNUAL_UPDATE_REQUIRED).
- **Beca Movilidad (Erasmus+):** Available for approved Erasmus exchange periods.

**Regional level (Islas Baleares):**
- The Govern Balear offers scholarship programmes for Balearic-resident students with economic need. Students from the mainland are less likely to qualify for region-specific aid. PENDING_CONFIRMATION — verify current programmes at the Govern Balear education portal (ANNUAL_UPDATE_REQUIRED).

**University level:**
- UIB has internal scholarship and emergency aid mechanisms. Details at uib.es/beques (ANNUAL_UPDATE_REQUIRED).
- UIB participates in Santander Universities scholarship programmes and other private foundation initiatives.

**Practical note:** Students from the mainland receiving the MEC living-stipend component should verify whether the stipend levels are sufficient to cover island accommodation costs, which are generally higher than mainland provincial cities.

## Accommodation and Cost of Living

Palma de Mallorca presents a challenging accommodation market. The city is one of Spain's most expensive for rental housing outside Madrid and Barcelona, driven by high demand from tourism workers, short-term rental platforms, and a structurally limited housing stock on an island.

| Cost Category | Approximate Monthly Range | Notes |
|---|---|---|
| Shared flat room (Palma) | 450–750 EUR | ANNUAL_UPDATE_REQUIRED — Palma rental market is volatile and constrained |
| University residence (if available) | PENDING_CONFIRMATION | ANNUAL_UPDATE_REQUIRED |
| Food (self-catering) | 200–320 EUR | ANNUAL_UPDATE_REQUIRED |
| Public transport (Palma city bus / EMT) | 20–40 EUR/month | ANNUAL_UPDATE_REQUIRED |
| Ferry/flight to mainland (per trip, approx.) | 60–200 EUR | ANNUAL_UPDATE_REQUIRED — varies by season, lead time, and route |
| Books / materials (Year 1 estimate) | 200–400 EUR | ANNUAL_UPDATE_REQUIRED |

Students from the mainland should budget for 2–4 return trips to the mainland per academic year (Christmas, Easter, summer, plus any additional visits), which adds 200–800+ EUR/year in transport costs depending on booking timing and season.

UIB campus is located on the outskirts of Palma. Hospital Universitari Son Espases (clinical rotations) is a modern hospital also on the Palma periphery. Local transport within Palma and to the hospital is manageable.

## International Exchange and Mobility Programs

UIB participates in the Erasmus+ programme at the institutional level. Medicine-specific bilateral agreements are PENDING_CONFIRMATION — students should verify with the Facultat de Medicina's international office which partner institutions are active for Medicine students and from which study year.

UIB's smaller size and geographic isolation may result in a smaller volume of Medicine-specific Erasmus slots than at major mainland universities. This is expected; students with strong interest in an Erasmus exchange should confirm availability before committing to UIB.

The cosmopolitan social environment of the Balearic Islands (significant international expatriate and tourist presence) provides informal international exposure outside the formal academic programme.

## MIR Preparation and Professional Outcomes

The MIR (Médico Interno Residente) examination is the national gateway to medical specialisation in Spain. All UIB Grado en Medicina graduates are eligible to sit the MIR.

**MIR pass rate for UIB graduates:** PENDING_CONFIRMATION — UIB does not publish programme-specific MIR pass rates in a publicly verifiable format as of the date of this file. As a newer Medicine faculty, limited cohorts have completed the degree.

**General context:** Clinical training at Hospital Universitari Son Espases gives students exposure to a modern tertiary hospital. The Ibsalut network is a complete, self-contained health system with primary through tertiary care. The limitation compared to mainland hospital networks is case volume and sub-specialisation depth: the Balearic Islands' 1.2 million population generates fewer rare and complex cases annually than Madrid (6.7 million) or Barcelona (5.6 million metropolitan).

Post-MIR, graduates can specialise within the Sistema Nacional de Salud. Graduates from the Balearic Islands may have a natural fit with Ibsalut positions given local clinical familiarity, but can compete nationally.

## Strategic Fit

### Good Fit For

- Candidates with a nota de admisión in the 12.51–12.75 range for whom UIB Medicine is a realistic primary target — essentially equivalent in threshold to UPF (12.516) but with a very different geographic and cultural context.
- Students who specifically want to study and live in Mallorca, value the island lifestyle, and are comfortable with island logistical constraints.
- Balearic Islands residents who qualify for regional scholarships and have lower accommodation relocation costs.
- Candidates for whom the smaller cohort and more intimate learning environment of a regional island university is a positive feature rather than a constraint.
- Students from families already based in the Balearic Islands.

### Less Suitable For

- Candidates who prioritise research environment, hospital case volume, or metropolitan-scale clinical networks — Madrid, Barcelona, and even Alicante offer broader clinical ecosystems.
- Students with constrained budgets who cannot absorb the island cost premium (higher accommodation, transport to mainland).
- Candidates who prefer a bilingual English-medium or research-intensive environment — UIB Medicine does not currently offer this in a confirmed form.
- International students who are unfamiliar with Catalan (Mallorquí) in clinical environments and who are not prepared for an island context.
- Candidates for whom cross-regional admission quota restrictions (if applicable) may complicate the application process from the mainland.

## Risks and Considerations

1. **Housing market:** Palma de Mallorca's rental market is one of Spain's tightest outside Madrid and Barcelona, driven by tourism-sector competition. Accommodation costs can approach or exceed Barcelona levels, significantly reducing the cost advantage of public tuition.

2. **Transport costs:** Students from the mainland must budget for ferry or flight costs to return home multiple times per year. Over a 6-year degree, this adds a substantial cumulative expense compared to mainland university choices.

3. **Nota de corte variability:** The 2025-26 nota de corte of 12.510 is for a newer, smaller-community Medicine degree. It can shift significantly between cycles. Candidates should plan with a buffer above the current figure.

4. **Hospital network scope:** The Ibsalut network, while complete, is limited by island geography and population size. Sub-speciality exposure, rare case volumes, and research hospital infrastructure are more limited than at major mainland tertiary centres.

5. **Cross-regional admission rules:** The specific quota and competition mechanisms for mainland and international students applying to UIB are PENDING_CONFIRMATION. Candidates from outside the Balearic Islands must clarify these rules before applying.

6. **Ponderation coefficient uncertainty:** UIB ponderation coefficients are ANNUAL_UPDATE_REQUIRED and the specific authority setting them is PENDING_CONFIRMATION. Candidates must verify the current table before finalising their PCE/EVAU subject strategy.

7. **Non-EU tuition and island access:** Non-EU students face significantly higher tuition fees AND the logistical costs of island relocation. The total annual cost for non-EU students at UIB may be higher than expected relative to comparable peninsula options.

8. **Limited MIR benchmark data:** As a newer Medicine faculty, UIB lacks multiple cohorts of MIR-sitting graduates. Verified MIR performance data is PENDING_CONFIRMATION.

## Important Notes

- All admission dates (EVAU, UIB preinscripció, enrolment) are ANNUAL_UPDATE_REQUIRED — verify at the UIB admissions portal (uib.es/es/admissio/).
- The official UIB ponderation table for Medicine specific-phase subjects is published annually and is ANNUAL_UPDATE_REQUIRED. Verify before finalising PCE or EVAU subject selection.
- Non-EU students must verify visa, NIE, and health insurance requirements separately from admission.
- Cross-regional admission rules for mainland Spanish and international candidates must be verified directly with UIB admissions before applying.
- The clinical training hospital list (UDH) within Ibsalut should be verified at the Facultat de Medicina website each intake year.
- Island logistical costs (accommodation, transport) should be modelled into the total annual budget before making a commitment to UIB.

## Key Insight

UIB Medicine is effectively the same admission threshold as UPF (0.006 nota de corte points apart in 2025-26), but offers a fundamentally different academic and life context: a small island university in Palma de Mallorca versus Spain's top-ranked research institution in central Barcelona. The choice between them for a candidate in the 12.51–12.52 nota de admisión range is not primarily an academic quality question — it is a personal fit question about lifestyle, language environment, cost structure, and career orientation. UIB is appropriate for candidates who specifically value the island setting or have a pre-existing connection to the Balearic Islands. For most mainland or international candidates comparing options at this nota de corte level, UPF's research environment, English-medium instruction, and Barcelona location offer advantages that UIB cannot match, unless the island context is a deliberate positive choice.

## Final Takeaway

UIB Medicine offers public Medicine access in a distinctive island setting at essentially the same admission threshold as UPF. The programme provides solid clinical training within the Ibsalut network through Hospital Universitari Son Espases — a modern, well-equipped tertiary hospital. The practical risks are real: Palma's constrained housing market and island transport costs create a total annual budget that may rival or exceed mainland alternatives. Candidates choosing UIB should do so with a clear understanding of the island context, and specifically because the Balearic Islands environment is a positive factor — not a default consequence of the admission score. For candidates at this score threshold with no particular connection to the islands, UPF should be evaluated as a first comparison point before committing to UIB.

## Frequently Asked Questions

**How is the nota de admisión calculated?**
The nota de admisión = 0.6 × Nota media de Bachillerato + 0.4 × Nota EVAU (fase general) + bonus from up to 2 specific-phase subjects (each subject grade × ponderation coefficient of 0.1 or 0.2). The maximum score is 14.0000.

**What is the nota de corte for UIB Medicine?**
For the 2025-26 intake, the nota de corte was 12.510 (source: notasdecorte.es). It is not a fixed threshold — it changes annually. Historical data for prior cycles is PENDING_CONFIRMATION. As a newer degree programme, nota de corte data from multiple prior cycles is limited.

**Can students from mainland Spain apply to UIB Medicine?**
Yes, Spanish students from all regions can apply. The specific quota mechanism and whether mainland EVAU students compete in a general pool alongside Balearic Islands students is PENDING_CONFIRMATION — candidates must verify with UIB admissions before applying.

**Can international students apply via PCE?**
Yes. International students who obtain a UNEDasiss Credencial and sit PCE can apply. Ponderation coefficients for Biology and Chemistry at UIB are ANNUAL_UPDATE_REQUIRED — verify the UIB ponderation table before choosing PCE subjects. The specific PCE application process for UIB is PENDING_CONFIRMATION.

**What are the tuition fees?**
For EU/EEA students, approximately 1,205 EUR/year (ANNUAL_UPDATE_REQUIRED). For non-EU students, PENDING_CONFIRMATION. This headline figure excludes island transport costs and the Palma accommodation premium — both of which increase the total annual cost significantly.

**When do I apply?**
Applications (preinscripció) are submitted through the UIB admissions portal (uib.es/es/admissio/) in June–July for the ordinaria convocatoria. An extraordinaria convocatoria follows in August–September. All dates are ANNUAL_UPDATE_REQUIRED.

**Is Catalan (Mallorquí) required?**
No Catalan proficiency is required for admission. However, Catalan (specifically the Mallorquí variant) is co-official in the Balearic Islands and is used in UIB classes and increasingly in clinical settings. Students who cannot function in Catalan may face practical challenges in hospital rotations. Non-Catalan speakers should factor this into their decision.

**Is there an interview or entrance exam?**
No. UIB Medicine admission is based solely on the nota de admisión. There is no interview, proprietary exam, or portfolio requirement.

**When does clinical training begin?**
From Year 3. Years 1–2 are taught at the UIB campus in Palma de Mallorca. From Year 3, students rotate through the Ibsalut hospital network, primarily Hospital Universitari Son Espases and Hospital Son Llàtzer.

**How expensive is it to live in Palma de Mallorca as a student?**
Palma is significantly more expensive for accommodation than most Spanish mainland provincial cities, with shared flat rooms ranging from approximately 450–750 EUR/month (ANNUAL_UPDATE_REQUIRED). The housing market is constrained by tourism-sector competition. Students from the mainland must also budget for return travel (ferry or flight) several times per year, adding an estimated 200–800+ EUR/year in transport costs.
