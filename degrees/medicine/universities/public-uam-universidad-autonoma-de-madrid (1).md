---
id: uam

type: university
subtype: public

name: Universidad Autónoma de Madrid
short_name: UAM

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Madrid (Campus Cantoblanco)
  region: Comunidad de Madrid
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - high_competitiveness
  - research_oriented
  - strong_clinical_exposure
  - international_friendly
  - early_application_advantage

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
    - Early Admission (UAM-specific programme for international students)

competitiveness:
  level: very_high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: 240 # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION

  last_admitted_scores:
    - intake_year: 2025-2026
      round: convocatoria_ordinaria
      score: 12.978
      score_type: nota_de_admision
      notes: Verified nota de corte for 2025-26 intake. ANNUAL_UPDATE_REQUIRED.

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
  - id: uam-medicina

    campus: Facultad de Medicina, Campus de Cantoblanco, 28049 Madrid

    modality: standard

    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - high_competitiveness
      - research_oriented
      - strong_clinical_exposure
      - international_friendly
      - early_application_advantage

    teaching_languages:
      - Spanish
      - English (partial — bilingual tracks in select subjects and international student pathways)

    regional_language_possible: false
    regional_language: NULL

    language_requirements:
      minimum_spanish_level_non_native: B2
      english_required: false
      minimum_english_level: NULL

    seats: 240 # ANNUAL_UPDATE_REQUIRED

    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 240
      applicants_per_seat: PENDING_CONFIRMATION

      last_admitted_scores:
        - intake_year: 2025-2026
          round: convocatoria_ordinaria
          score: 12.978
          score_type: nota_de_admision
          notes: Verified nota de corte. ANNUAL_UPDATE_REQUIRED.

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
      enabled: true
      admission:
        intake_month: September # ANNUAL_UPDATE_REQUIRED
        applications_open_date: ANNUAL_UPDATE_REQUIRED
        rolling_admissions:
          enabled: false
          estimated_end_date: NULL
        admission_rounds:
          enabled: true
          count: 1
          rounds:
            - round: Early Admission
              application_deadline: ANNUAL_UPDATE_REQUIRED
              exam_date: NULL
              results_date: ANNUAL_UPDATE_REQUIRED
              deposit_deadline: ANNUAL_UPDATE_REQUIRED
        exam_required: false
        interview_required: false
      academic_record:
        minimum_requirement:
          enabled: true
          grade_source: unedasiss_credencial
          minimum_grade: NULL
        competitive_filter:
          enabled: true
          grade_source: nota_de_admision_unedasiss
          approx_candidates_selected: PENDING_CONFIRMATION

    evaluation_model:
      overall_model_type: score_based

      nota_de_corte:
        - intake_year: 2025-2026
          score: 12.978
          round: convocatoria_ordinaria
          source: DUM / UAM official data

        - intake_year: 2024-2025
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: PENDING_CONFIRMATION

        - intake_year: 2023-2024
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: PENDING_CONFIRMATION

      admission_pathways:
        - eligible_profiles:
            - Spanish EVAU (PAU) — all regional variants
            - International via PCE/UNED
            - International via Credencial UE
            - Direct homologation (select countries)
            - UAM Early Admission (international students, separate process)

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
              notes: 40% of the nota de admisión. Maximum combined base score with Bachillerato is 10.0000.

            - component: evau_specific_phase_bonus
              enabled: true
              role: bonus_only
              maximum_bonus: 4.0
              grade_source: evau_fase_especifica
              notes: Best 2 eligible subjects count. Each subject score multiplied by the university ponderation coefficient (0.1 or 0.2). Maximum nota de admisión is 14.0000. Coefficients ANNUAL_UPDATE_REQUIRED.
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED
                Chemistry:      0.2 # ANNUAL_UPDATE_REQUIRED
                Physics:        0.1 # ANNUAL_UPDATE_REQUIRED
                Mathematics_II: 0.1 # ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---

# Universidad Autónoma de Madrid

## Overview

The Universidad Autónoma de Madrid (UAM) is one of Spain's leading research universities, founded in 1968, and its Facultad de Medicina is consistently ranked among the top medical faculties in the country. UAM Medicine operates within the Distrito Único de Madrid (DUM) admissions framework and offers the Grado en Medicina with 240 seats per intake at its Campus de Cantoblanco, located approximately 15 km north of central Madrid.

UAM is one of the few Spanish public universities holding a confirmed WFME (World Federation for Medical Education) quality seal via ANECA accreditation — a distinction that strengthens the international recognition of the degree, particularly for graduates seeking postgraduate training outside Spain. The programme spans 6 years (360 ECTS) and is delivered primarily in Spanish, with an increasing bilingual component in select subjects and a well-established Early Admission track for international students applying before the main DUM window.

For competitive candidates, UAM Medicina offers a notable combination of research prestige, strong clinical training in major Madrid hospitals, and a slightly lower nota de corte than UCM — making it a strategically important target for candidates who score in the 12.9–13.5 range on the nota de admisión.

## Quick Evaluation

- **Degree:** Grado en Medicina — 6 years — 360 ECTS
- **Seats:** 240 (ANNUAL_UPDATE_REQUIRED)
- **Admission mechanism:** Nota de admisión (nota de corte model); no exam, no interview
- **Competitiveness:** Very high — nota de corte 12.978 for 2025-26 (ANNUAL_UPDATE_REQUIRED)
- **Nota de corte (2025-26):** 12.978 out of 14.000
- **Tuition (approximate):** ~1,000–1,500 EUR/year for EU residents; ~8,000+ EUR/year for non-EU (ANNUAL_UPDATE_REQUIRED)
- **Clinical training from:** Year 3 — in affiliated hospitals including Hospital La Paz
- **Teaching language:** Spanish (partial bilingual component in select subjects)
- **WFME accreditation:** Confirmed via ANECA
- **International access:** Via PCE/UNED, Credencial UE, or UAM Early Admission

## Key Facts

| Parameter | Value |
|---|---|
| Official name | Universidad Autónoma de Madrid |
| Degree | Grado en Medicina |
| Duration | 6 years (360 ECTS) |
| Annual seats | 240 (ANNUAL_UPDATE_REQUIRED) |
| Campus | Facultad de Medicina, Campus de Cantoblanco, 28049 Madrid |
| Year 1–2 location | Campus de Cantoblanco |
| Year 3–6 location | Affiliated hospitals (principally Hospital La Paz and network) |
| Teaching language | Spanish; partial bilingual component |
| Admission type | Nota de admisión (public competitive ranking via DUM) |
| No proprietary exam | Correct |
| No interview | Correct |
| Nota de corte 2025-26 | 12.978 (ANNUAL_UPDATE_REQUIRED) |
| WFME accreditation | Confirmed (ANECA) |
| Tuition (EU, indicative) | ~1,000–1,500 EUR/year (ANNUAL_UPDATE_REQUIRED) |
| Tuition (non-EU, indicative) | ~8,000+ EUR/year (ANNUAL_UPDATE_REQUIRED) |
| Founded | 1968 |

## Program Options

UAM offers a single Grado en Medicina track at Campus de Cantoblanco. There is no formally separate bilingual cohort or alternative campus option. All 240 students share the same curriculum, clinical rotation network, and faculty.

A bilingual element has been progressively introduced into the curriculum, with a proportion of subject content delivered in English. This does not constitute a separate English-medium programme; students are not selected based on English proficiency for the standard track.

UAM also operates an **Early Admission** process aimed specifically at international students applying before the main DUM window. This allows international candidates to secure a conditional admission offer ahead of the general competition, subject to their final UNEDasiss Credencial results meeting the threshold (ANNUAL_UPDATE_REQUIRED — programme details and timeline subject to change).

## Program Structure

The Grado en Medicina at UAM is structured across 6 academic years, totalling 360 ECTS:

**Phase 1 — Preclínica (Years 1–2):** Core biomedical sciences at the Facultad de Medicina on Campus Cantoblanco. Subjects include Anatomy, Physiology, Biochemistry, Cell Biology, Histology, Immunology, Microbiology, Pharmacology, and Pathology. Clinical skills simulation and early patient contact modules begin in Year 2.

**Phase 2 — Clínica (Years 3–6):** Students are assigned to affiliated hospital teaching units (Unidades Docentes Hospitalarias). Clinical instruction across all major medical specialties takes place in real hospital settings. Year 6 includes a structured clinical rotation (Rotatorio Clínico) across multiple departments.

**TFG (Final Degree Project):** Mandatory final-year research or clinical project. Requirements for language of presentation: PENDING_CONFIRMATION.

**Electives:** Available during the curriculum as optional subject credits (PENDING_CONFIRMATION on total elective ECTS in current plan).

## Teaching Methodology

UAM Medicine combines a traditional lecture-based structure in preclinical years with an active integration of simulation-based clinical skills training earlier in the programme than at some peer institutions. The Facultad de Medicina at Cantoblanco has dedicated simulation and clinical skills laboratories supporting early clinical competency development.

From year three, teaching shifts to hospital-embedded, specialty-supervised clinical instruction. Small group teaching (seminarios, casos clínicos) runs alongside lecture content throughout the degree.

The partial bilingual component — whereby select subjects or lecture series are delivered in English — prepares students for engagement with international scientific literature and postgraduate environments without imposing English-entry requirements.

UAM's research culture is embedded in the degree: students are exposed to research methodology from early years, and the university's proximity to major research institutes (CSIC, IIS La Paz) generates opportunities for optional research involvement during the degree.

## Clinical Training

UAM Medicine's clinical training network is centred on the Hospital Universitario La Paz — one of Spain's largest and most respected university teaching hospitals, a designated national referral centre, and the primary ECOE (Objective Structured Clinical Examination) site for UAM Medicine graduates.

**Affiliated teaching hospitals (Unidades Docentes Hospitalarias — confirmed):**

- Hospital Universitario La Paz (principal teaching hospital — La Paz district, northern Madrid)
- Hospital Universitario de La Princesa
- Hospital Universitario Fundación Jiménez Díaz
- Hospital Universitario Puerta de Hierro Majadahonda
- Hospital Universitario de Móstoles
- Additional primary care and community health centres (ANNUAL_UPDATE_REQUIRED — network subject to annual revision)

Students are assigned to a Unidad Docente Hospitalaria from Year 3. Assignment depends on administrative and merit-based processes (ANNUAL_UPDATE_REQUIRED).

Hospital La Paz's status as a high-complexity, high-volume referral hospital provides students with exposure to specialist and rare-disease clinical environments.

## International Recognition and Opportunities

UAM Medicine holds confirmed WFME quality accreditation via ANECA — the Spanish national quality assurance agency. This accreditation is significant for graduates seeking postgraduate medical training in countries that require WFME-listed institution graduation (including the UK GMC, US ECFMG, and others).

The UAM degree (Grado en Medicina, MECES Level 3) is recognised across the EU under Directive 2005/36/EC. The WFME/ANECA seal provides additional security for graduates planning international medical careers.

**International exchange:** UAM Medicina participates in the Erasmus+ programme via the Facultad de Medicina's mobility office. Medicine-specific Erasmus slots are limited and competitive. ANNUAL_UPDATE_REQUIRED — students should verify which Medicine-specific agreements are active each year.

UAM is a member of the CIVIS European University Alliance, which includes the University of Aix-Marseille, University of Bucharest, Sapienza University of Rome, Stockholm University, and others — providing additional collaborative and mobility frameworks.

The Early Admission programme reflects UAM's institutional commitment to international student recruitment, making it structurally more accessible for international candidates than UCM's purely DUM-standard process.

## Admission Model

UAM Medicine is part of Spain's public university admissions system, coordinated through the Distrito Único de Madrid (DUM). Admission is determined exclusively by the nota de admisión — there is no proprietary entrance exam, no interview, and no portfolio component.

**The nota de admisión formula:**

```
Nota de admisión = 0.6 × Nota media de Bachillerato
                 + 0.4 × Nota EVAU (fase general)
                 + up to 4.0 bonus points from EVAU fase específica
```

- **Base score maximum:** 10.0000 (Bachillerato + EVAU general phase combined)
- **Maximum nota de admisión:** 14.0000 (with full specific-phase bonus)
- **Specific phase:** The best 2 eligible subjects count. Each subject grade is multiplied by the ponderation coefficient assigned by UAM (0.1 or 0.2). Biology and Chemistry receive 0.2 at UAM (ANNUAL_UPDATE_REQUIRED — verify the official DUM ponderation table each year).

**Access routes:**
- Spanish Bachillerato + EVAU (PAU): standard route via DUM
- FP Grado Superior + EVAU specific phase: valid
- International via PCE/UNED (Credencial UNEDasiss): valid; applies via DUM standard process
- International via Credencial UE: valid
- UAM Early Admission: specific international student route — separate process, earlier deadline (ANNUAL_UPDATE_REQUIRED)
- Direct homologation (select countries): valid via DUM

**Language requirement:** All candidates applying via DUM must demonstrate B2 Spanish proficiency if not native speakers.

## Admission Process

### For Spanish PAU students

1. Complete Bachillerato (Years 1–2) and register for EVAU.
2. Sit EVAU: mandatory general phase + optional specific phase (strongly recommended — up to 4 bonus points).
3. Receive nota de admisión.
4. Submit preinscripción through the Comunidad de Madrid DUM portal (ANNUAL_UPDATE_REQUIRED for exact dates).
5. List UAM Medicina in your degree preferences (up to 10 options across Madrid universities).
6. Await ordinaria convocatoria assignment results.
7. If not admitted in ordinaria, apply for extraordinaria convocatoria.
8. If admitted: complete enrolment (matrícula) within the published deadline.

### For international PCE/UNED students (standard route)

1. Obtain a recognised secondary qualification.
2. Apply to UNEDasiss for a Credencial. Submit transcripts and request subject recognition.
3. Sit PCE (Pruebas de Competencias Específicas) — Biology and Chemistry are most strategically valuable (coefficient 0.2 each; ANNUAL_UPDATE_REQUIRED).
4. Receive UNEDasiss Credencial with final calificación.
5. Submit preinscripción through DUM portal (same window as Spanish students).
6. If admitted: complete enrolment and arrange visa/NIE if required.

### For international students via UAM Early Admission

1. Apply directly to UAM through its international admissions office (separate from DUM) before the Early Admission deadline (ANNUAL_UPDATE_REQUIRED).
2. Submit UNEDasiss Credencial or equivalent qualification documentation.
3. Receive conditional admission offer from UAM, subject to final Credencial results meeting the required threshold.
4. Confirm acceptance and pay reservation deposit within the UAM-specified deadline (ANNUAL_UPDATE_REQUIRED).
5. Complete full enrolment when final academic results are confirmed.

Note: The Early Admission pathway gives international students a significant planning advantage — confirmed conditional offers can be obtained months before the DUM general process concludes. ANNUAL_UPDATE_REQUIRED — programme terms, deadlines and availability are subject to annual change.

## Admission Timeline

All dates are approximate and ANNUAL_UPDATE_REQUIRED. Verify each year at the Comunidad de Madrid DUM portal and UAM's international admissions page.

| Phase | Approximate Period |
|---|---|
| UAM Early Admission window (international) | February–April (ANNUAL_UPDATE_REQUIRED) |
| EVAU ordinaria (Madrid) | June (ANNUAL_UPDATE_REQUIRED) |
| EVAU extraordinaria (Madrid) | July (ANNUAL_UPDATE_REQUIRED) |
| DUM preinscripción ordinaria | June–July (ANNUAL_UPDATE_REQUIRED) |
| DUM results ordinaria | July (ANNUAL_UPDATE_REQUIRED) |
| Enrolment window | July–September (ANNUAL_UPDATE_REQUIRED) |
| DUM preinscripción extraordinaria | August–September (ANNUAL_UPDATE_REQUIRED) |
| Academic year begins | September (ANNUAL_UPDATE_REQUIRED) |
| PCE/UNED sessions | February and June (ANNUAL_UPDATE_REQUIRED) |

## Admission Score Distribution

The nota de corte for UAM Medicina in 2025-26 was **12.978** out of 14.000 — the lowest confirmed nota de corte among the major Madrid public medicine faculties in that cycle, making UAM the most accessible of the three main Madrid public Medicine programmes (UCM, UAM, and the private universities) for candidates with near-perfect but not absolute scores.

**What this means strategically:**

A nota de admisión of 12.978 in 2025-26 was the minimum required for admission. In practice, the margin above the nota de corte in oversubscribed programmes is often very small — a 0.01 advantage over the last admitted student is sufficient for admission, but candidates below the threshold are excluded regardless of other qualities.

To reach the UAM competitive range (12.8–13.2), candidates typically need:
- A Bachillerato average of approximately 8.5–9.5
- A solid EVAU general phase result (8.0+)
- Specific-phase results in Biology and Chemistry in the 8.0–10.0 range (coefficient 0.2 each)

**Ponderation coefficients for Medicine at UAM (ANNUAL_UPDATE_REQUIRED — verify at the DUM official ponderation table):**

| Subject | Coefficient |
|---|---|
| Biology | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Chemistry | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Physics | 0.1 (ANNUAL_UPDATE_REQUIRED) |
| Mathematics II | 0.1 (ANNUAL_UPDATE_REQUIRED) |

**Score trend:** The nota de corte at UAM has historically been lower than at UCM due to the smaller seat count relative to applicant pool distribution. UAM's nota de corte fluctuates across cycles (PENDING_CONFIRMATION for multi-year trend data). Candidates should plan for the score to be in the 12.9–13.3 range in future cycles and not rely on the 12.978 figure as a floor.

**For PCE/UNED international students:** The nota de admisión via UNEDasiss is calculated in the same way. Biology and Chemistry PCEs (coefficient 0.2 each) are the critical variables. The Early Admission route can provide security before final DUM competition, but the underlying nota de admisión must still meet UAM's threshold.

## Costs and Payment Structure

Tuition fees at UAM are set by the Comunidad de Madrid via regional decree and are subject to annual revision. Medicine is classified as an "experimental" branch, carrying the highest per-credit tariff tier in the Comunidad de Madrid's fee structure.

| Fee Concept | EU/EEA Students | Non-EU Students | Notes |
|---|---|---|---|
| Annual tuition (per year, approx.) | ~1,000–1,500 EUR | ~8,000–12,000 EUR | ANNUAL_UPDATE_REQUIRED |
| Per-credit fee (experimental branch) | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | Medicine = experimental branch (highest tier) |
| Enrolment / administrative fees | ~100–200 EUR | ~100–200 EUR | ANNUAL_UPDATE_REQUIRED |
| Student insurance (seguro escolar) | ~1.12 EUR | ~1.12 EUR | ANNUAL_UPDATE_REQUIRED |
| Repeat enrolment surcharge | Higher per-credit rate | Higher per-credit rate | Applies from 2nd enrolment in same subject |

Non-EU students pay significantly higher fees under the extracomunitario tariff (ANNUAL_UPDATE_REQUIRED — verify current decreto de tasas for Comunidad de Madrid).

## Scholarships and Financial Aid

**National level:**
- **Beca General MEC (Ministerio de Educación y Formación Profesional):** Available to students meeting income and academic performance thresholds. Covers partial tuition and may include a living stipend. Annual application via the MEFP portal (ANNUAL_UPDATE_REQUIRED).
- **Beca Movilidad (Erasmus+):** Available for approved Erasmus exchange periods.

**Regional level (Comunidad de Madrid):**
- Supplementary grants are available for students who do not qualify for or receive insufficient MEC support. PENDING_CONFIRMATION — verify at the Comunidad de Madrid education portal (ANNUAL_UPDATE_REQUIRED).

**University level:**
- UAM has internal scholarship and emergency aid mechanisms. Details at uam.es/becas (ANNUAL_UPDATE_REQUIRED).
- UAM participates in Banco Santander scholarship programmes.

**For international students:** UAM's international admissions office may have scholarship or fee-support information specific to Early Admission candidates. PENDING_CONFIRMATION — verify directly with UAM international admissions.

Scholarship eligibility typically requires passing a minimum number of ECTS per year; failure to meet this threshold can result in loss of MEC scholarship.

## Accommodation and Cost of Living

UAM's Campus de Cantoblanco is located approximately 15 km north of central Madrid, in a suburban setting. The campus has on-site residential infrastructure (Colegios Mayores within the campus grounds), which distinguishes it from UCM's urban location.

| Cost Category | Approximate Monthly Range | Notes |
|---|---|---|
| Campus residence / colegio mayor (Cantoblanco) | 600–1,000 EUR | ANNUAL_UPDATE_REQUIRED — availability is competitive |
| Shared flat room in nearby areas | 500–800 EUR | ANNUAL_UPDATE_REQUIRED — lower than central Madrid |
| Shared flat room in central Madrid | 650–950 EUR | ANNUAL_UPDATE_REQUIRED |
| Food (self-catering) | 200–350 EUR | ANNUAL_UPDATE_REQUIRED |
| Public transport (Cercanías + Metro, abono joven) | 20–30 EUR | ANNUAL_UPDATE_REQUIRED |
| Books / materials (Year 1 estimate) | 200–400 EUR | ANNUAL_UPDATE_REQUIRED |

Campus Cantoblanco is connected to central Madrid via Cercanías (line C-4, Cantoblanco Universidad stop) and by Metro (line 9 to Ciudad Universitaria interchange). Journey time to Sol or Nuevos Ministerios is approximately 30–40 minutes.

On-campus accommodation gives students the option of a lower-cost, campus-integrated lifestyle compared to renting in central Madrid. Priority for campus residence places typically goes to first-year students; early application is advisable (ANNUAL_UPDATE_REQUIRED).

## International Exchange and Mobility Programs

UAM Medicina participates in the Erasmus+ programme via the Facultad de Medicina's mobility office. Exchange periods in the clinical phase (from Year 3) are the most common format.

UAM is a member of the CIVIS European University Alliance, potentially offering mobility and collaborative research opportunities beyond standard Erasmus partnerships.

**Important limitation:** Not all UAM university-level Erasmus agreements extend to Medicine. Medicine-specific slots are limited and competitive; students should verify current Medicine-applicable agreements with the Facultad de Medicina's Oficina de Relaciones Internacionales (ANNUAL_UPDATE_REQUIRED).

Incoming international exchange students to UAM Medicine: PENDING_CONFIRMATION on formal incoming exchange structure for the Medicine degree.

## MIR Preparation and Professional Outcomes

The MIR (Médico Interno Residente) examination is the national gateway to medical specialisation in Spain. UAM graduates are eligible to sit the MIR after completing the Grado en Medicina.

**MIR results for UAM graduates:** PENDING_CONFIRMATION — UAM does not publish programme-specific MIR pass rates or ranking distributions in a readily verifiable public format as of the date of this file.

**General context:** UAM's clinical training in Hospital La Paz and its network of affiliated high-complexity hospitals is widely regarded as strong preparation for the MIR. The hospital's status as a national referral centre exposes students to complex clinical scenarios that are relevant to MIR examination content.

UAM's strong research culture also supports graduates who pursue academic medicine or research careers post-MIR, with connections to CSIC institutes and the IIS La Paz research institute co-located with the teaching hospital.

## Strategic Fit

### Good Fit For

- Candidates with a nota de admisión in the 12.9–13.5 range who may not reach UCM's typical threshold but are competitive for UAM.
- Students who value WFME accreditation as a strategic asset for future international medical career options.
- International candidates using the PCE/UNED route who want to benefit from the UAM Early Admission pathway as a planning safety net.
- Research-oriented students who want access to a campus embedded in a strong research university environment with connections to major research institutes.
- Students comfortable with a campus-based suburban living environment rather than a central urban location.
- Candidates who want proximity to Hospital La Paz — one of Spain's most prestigious university teaching hospitals.

### Less Suitable For

- Candidates whose nota de admisión is below 12.8 — competition for the remaining seats at UAM in recent cycles has been very high; other regions or private universities may present better fit.
- Students who require a formal English-medium track — UAM does not offer a separate English-taught Medicine programme.
- International students with limited Spanish proficiency — the degree is primarily in Spanish and B2 Spanish is required for DUM admission.
- Students who prefer a highly urban campus environment with direct city-centre immersion — Cantoblanco is suburban and requires commuting to central Madrid.

## Risks and Considerations

1. **Nota de corte variability:** The nota de corte of 12.978 for 2025-26 reflects one specific competitive cycle. It can shift in either direction depending on the applicant pool and EVAU score distributions. Candidates targeting UAM should not plan exclusively on the 2025-26 figure; build a buffer of at least 0.1–0.2 above any historical nota de corte.

2. **Seat count:** 240 seats is smaller than UCM's 320. A relatively small number of additional high-scoring applicants in any given year can raise the nota de corte meaningfully. ANNUAL_UPDATE_REQUIRED.

3. **Early Admission terms:** The UAM Early Admission programme offers conditional admission to international students. The specific terms, thresholds, and availability of this pathway change annually. ANNUAL_UPDATE_REQUIRED — candidates must verify current Early Admission terms directly with UAM's international office.

4. **Hospital assignment:** Assignment to specific clinical hospitals from Year 3 is not individually guaranteed. Placement in Hospital La Paz (the most prestigious teaching unit) versus other affiliated hospitals depends on administrative and merit-based processes.

5. **Non-EU tuition exposure:** Non-EU students pay fees significantly higher than EU-rate students. The Comunidad de Madrid's extracomunitario tariff applies.

6. **PCE/UNED score requirements:** While the nota de corte at UAM is lower than UCM's, it still requires very high PCE scores in Biology and Chemistry to reach the threshold from a UNEDasiss base. This remains a high-difficulty target for international students.

7. **Campus location logistics:** Campus Cantoblanco is not in central Madrid. Students without on-campus accommodation face daily commutes. In clinical years (3–6), students may be assigned to hospitals located in different parts of Madrid, adding further commute complexity.

## Important Notes

- All admission dates (EVAU, DUM preinscripción, UAM Early Admission, enrolment) are ANNUAL_UPDATE_REQUIRED and must be verified at the official Comunidad de Madrid DUM portal and UAM's admissions pages.
- The official ponderation table for UAM Medicine specific-phase subjects is published annually by the DUM and is ANNUAL_UPDATE_REQUIRED.
- Non-EU students must verify visa, NIE, and health insurance requirements separately from admission.
- WFME accreditation via ANECA is confirmed for UAM as of the date of this file; reaccreditation cycles should be monitored.
- The UAM Early Admission programme is specifically for international candidates and operates on a different timeline to the standard DUM process. Do not conflate the two.

## Key Insight

UAM Medicina combines research prestige, confirmed WFME accreditation, and a nota de corte that — while still very high — falls slightly below UCM's. This positions UAM as the most strategically reachable major public Medicine programme in Madrid for candidates whose nota de admisión falls in the 12.9–13.3 range. The Early Admission pathway is a structural advantage for international candidates that no other major Madrid public university replicates in the same form, making UAM the default first-choice institution for international PCE/UNED applicants targeting Madrid. The confirmed WFME seal is the single most important differentiator from UCM for candidates planning international postgraduate careers.

## Final Takeaway

UAM Medicina is the strategically optimal choice among Madrid public medical faculties for candidates whose nota de admisión does not clearly exceed UCM's historical threshold but is solidly above 12.9. The WFME/ANECA accreditation provides tangible value for internationally-oriented graduates. The Early Admission pathway reduces uncertainty for international candidates applying via PCE/UNED. The primary risks are the annually variable nota de corte and the suburban campus location, which are manageable for most candidates with realistic planning. This is a high-value, high-difficulty target that rewards careful score optimisation over speculative application.

## Frequently Asked Questions

**What is the nota de corte for UAM Medicine?**
The nota de corte for 2025-26 was 12.978 out of 14.000 (ANNUAL_UPDATE_REQUIRED — this figure changes every cycle based on the applicant pool). It is the nota de admisión of the last student admitted, not a guaranteed threshold for the following year.

**How is the nota de admisión calculated?**
Nota de admisión = 0.6 × Nota media de Bachillerato + 0.4 × Nota EVAU (fase general) + bonus from up to 2 specific-phase subjects (each subject grade × ponderation coefficient of 0.1 or 0.2). Maximum score is 14.0000.

**Is UAM Medicine WFME-accredited?**
Yes. UAM Medicina holds confirmed WFME quality accreditation via ANECA, Spain's national quality agency. This is significant for graduates planning postgraduate training in countries that require WFME-accredited institution graduation (such as the UK and USA).

**What is the UAM Early Admission programme?**
UAM Early Admission is a separate pathway for international students that allows them to receive a conditional admission offer before the main DUM process. Candidates apply directly to UAM before the Early Admission deadline, submit their UNEDasiss Credencial or equivalent, and receive a conditional offer subject to meeting the nota de admisión threshold. ANNUAL_UPDATE_REQUIRED — terms and deadlines change every cycle.

**Can international students apply via PCE?**
Yes. International students who hold a UNEDasiss Credencial and have sat PCE can apply via the standard DUM process or via UAM Early Admission. Biology and Chemistry PCEs (coefficient 0.2 each) are the most valuable specific-phase subjects for maximising the nota de admisión at UAM.

**What are the tuition fees?**
For EU/EEA students, approximately 1,000–1,500 EUR/year (ANNUAL_UPDATE_REQUIRED). For non-EU students, approximately 8,000+ EUR/year (ANNUAL_UPDATE_REQUIRED). Medicine is classified as "experimental" branch, which carries higher per-credit tariffs.

**Is there an interview or entrance exam?**
No. Admission is based solely on the nota de admisión. There is no interview, no proprietary exam, and no portfolio requirement.

**Where is the campus?**
UAM is located at Campus de Cantoblanco, approximately 15 km north of central Madrid. The campus is accessible via Cercanías (line C-4, Cantoblanco Universidad) and Metro (line 9). On-campus residential accommodation (colegios mayores) is available but competitive.

**When does clinical training begin?**
From Year 3. The first two preclinical years are taught at the Facultad de Medicina on Campus Cantoblanco. From Year 3, students are assigned to an affiliated teaching hospital (principally Hospital Universitario La Paz and the network).

**Is there an English-medium track?**
No dedicated English-medium cohort exists. A bilingual component has been progressively integrated into select subjects, but the degree is primarily taught in Spanish. B2 Spanish is required for all DUM applicants who are non-native speakers.
