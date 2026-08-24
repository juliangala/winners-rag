---
id: ucm

type: university
subtype: public

name: Universidad Complutense de Madrid
short_name: UCM

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Madrid
  region: Comunidad de Madrid
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - medium_competitiveness
  - research_oriented
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
  seats: 320 # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION

  last_admitted_scores:
    - intake_year: 2025-2026
      round: convocatoria_ordinaria
      score: 13.100
      score_type: nota_de_admision
      notes: Verified nota de corte for 2025-26 intake. Source: notasdecorte.es. ANNUAL_UPDATE_REQUIRED.

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
  - id: ucm-medicina

    campus: Campus de Moncloa / Facultad de Medicina — Plaza de Ramón y Cajal, 28040 Madrid

    modality: standard

    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - medium_competitiveness
      - research_oriented
      - strong_clinical_exposure

    teaching_languages:
      - Spanish
      - English (partial — select lectures and TFG summary)

    regional_language_possible: false
    regional_language: NULL

    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL

    seats: 320 # ANNUAL_UPDATE_REQUIRED

    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 320
      applicants_per_seat: PENDING_CONFIRMATION

      last_admitted_scores:
        - intake_year: 2025-2026
          round: convocatoria_ordinaria
          score: 13.100
          score_type: nota_de_admision
          notes: Verified nota de corte. Source: notasdecorte.es. ANNUAL_UPDATE_REQUIRED.

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
          score: 13.100
          round: convocatoria_ordinaria
          source: notasdecorte.es (2025-26 data) # ANNUAL_UPDATE_REQUIRED — verify at DUM/comunidad.madrid

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
                Physics:        0.1 # ANNUAL_UPDATE_REQUIRED
                Mathematics_II: 0.1 # ANNUAL_UPDATE_REQUIRED
                Drawing_II:     ANNUAL_UPDATE_REQUIRED
                History_Art:    ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---

# Universidad Complutense de Madrid

## Overview

The Universidad Complutense de Madrid (UCM) is one of Spain's oldest and most prestigious public universities, with the Facultad de Medicina tracing its history to the 16th century. As the largest public university in Spain by enrollment, UCM operates within the Distrito Único de Madrid (DUM) admissions framework and offers the Grado en Medicina with 320 seats per intake — one of the largest cohorts among Spanish public medical faculties.

UCM Medicine is deeply integrated with Madrid's major public hospital network, providing students with clinical exposure from year three onwards in institutions that include national referral centres. The programme spans 6 years (360 ECTS) and is delivered primarily in Spanish, with a growing proportion of lectures offered in English — a deliberate strategy to prepare graduates for scientific literature and international postgraduate environments without imposing formal English-entry requirements.

For candidates from the Comunidad de Madrid and from the rest of Spain, UCM represents a classic flagship-university option where academic performance across Bachillerato and EVAU is the sole determinant of admission. There is no interview, no proprietary exam, and no portfolio component.

## Quick Evaluation

- **Degree:** Grado en Medicina — 6 years — 360 ECTS
- **Seats:** 320 (ANNUAL_UPDATE_REQUIRED)
- **Admission mechanism:** Nota de admisión (nota de corte model); no exam, no interview
- **Competitiveness:** Very high — Medicine at UCM consistently ranks among the most competitive programmes in the Comunidad de Madrid
- **Nota de corte (2025-26):** 13.100 out of 14.000 (source: notasdecorte.es; ANNUAL_UPDATE_REQUIRED)
- **Tuition (approximate):** ~1,000–1,500 EUR/year for EU residents; ~8,000+ EUR/year for non-EU (ANNUAL_UPDATE_REQUIRED)
- **Clinical training from:** Year 3 — in affiliated hospitals
- **Teaching language:** Spanish (English partially embedded)
- **WFME accreditation:** PENDING_CONFIRMATION (UCM is a member of the ECTS Medicine Association as of 2026)
- **International access:** Via PCE/UNED or Credencial UE

## Key Facts

| Parameter | Value |
|---|---|
| Official name | Universidad Complutense de Madrid |
| Degree | Grado en Medicina |
| Duration | 6 years (360 ECTS) |
| Annual seats | 320 (ANNUAL_UPDATE_REQUIRED) |
| Campus | Facultad de Medicina, Campus de Moncloa, Madrid |
| Year 1–2 location | Facultad de Medicina (Moncloa) |
| Year 3–6 location | Affiliated hospitals across Madrid |
| Teaching language | Spanish; partial English |
| Admission type | Nota de admisión (public competitive ranking) |
| No proprietary exam | Correct |
| No interview | Correct |
| Tuition (EU, indicative) | ~1,000–1,500 EUR/year (ANNUAL_UPDATE_REQUIRED) |
| Tuition (non-EU, indicative) | ~8,000+ EUR/year (ANNUAL_UPDATE_REQUIRED) |
| Established | Grado implemented 2009–2010 |

## Program Options

UCM offers a single Grado en Medicina track — there is no bilingual programme, no separate English-medium cohort, and no alternative campus. All 320 students share the same curriculum, faculty, and hospital rotation network.

The programme introduced a new study plan in 2025 (Plan 2025 / code 081P) which runs alongside the outgoing Plan 2010 (0805) for students who enrolled under the older curriculum. From 2026-27 onwards, all new students enter under Plan 2025.

Under Plan 2025: 360 ECTS total — 90 ECTS Formación Básica, 252 ECTS Obligatorias, 12 ECTS Optativas, 6 ECTS TFG.

## Program Structure

The Grado en Medicina at UCM is structured across 6 academic years, totalling 360 ECTS:

**Phase 1 — Preclínica (Years 1–2):** Core biomedical sciences taught at the Facultad de Medicina building on Moncloa campus. Subjects include Anatomy, Biochemistry, Physiology, Cell Biology, Histology, Microbiology, Immunology, Pharmacology, and Pathology. Basic laboratory and clinical skills are introduced.

**Phase 2 — Clínica (Years 3–6):** Students are assigned to affiliated hospital teaching units (Unidades Docentes Hospitalarias). Clinical subjects are taught and practised in real hospital settings, including internal medicine, surgery, obstetrics and gynaecology, paediatrics, psychiatry, and primary care. Year 6 includes a dedicated clinical rotation (Rotatorio Clínico) across multiple specialties.

**TFG (Final Degree Project):** 6 ECTS. Students may present the summary in English or Spanish; all must include an English-language abstract.

**Electives:** 12 ECTS of optional subjects are available throughout the curriculum.

## Teaching Methodology

UCM Medicine adopts a predominantly lecture-based model in preclinical years, supplemented by laboratory practice, small-group seminars (Sesiones Básico-Clínicas), and early simulated clinical skill development. From year three, learning is delivered primarily through supervised clinical attachment in hospital environments.

A distinctive feature is the integration of English-language instruction into core subject lectures without requiring formal English-entry certification. Students are assessed in English for topics delivered in that language, and the TFG abstract is mandatory in English. This approach aims to develop scientific-literature literacy progressively throughout the degree.

The programme has recently joined the ECTS Medicine Association, signalling alignment with European medical education standards.

UCM employs a mentoring system (Programa de Mentoría) pairing senior students with first-year students, and assigns a Tutor de Grado to each student cohort for academic guidance.

## Clinical Training

Clinical training at UCM is conducted across a network of major Madrid public hospitals designated as Hospitales Asociados. Students begin clinical rotations from year three and spend the majority of years 4–6 in hospital environments.

**Official affiliated hospitals (verified on UCM website):**

- Hospital Clínico San Carlos (Moncloa — adjacent to the faculty)
- Hospital 12 de Octubre (Carabanchel)
- Hospital Infanta Cristina (Parla)
- Hospital Gregorio Marañón (Retiro)
- Hospital Infanta Leonor (Vallecas)

Students are assigned to a Unidad Docente Hospitalaria (UDH) from year three. Assignment is managed by the faculty and depends on administrative processes and student preferences where applicable (ANNUAL_UPDATE_REQUIRED).

The hospital network covers primary and specialised care, including several national referral centres, giving students access to complex and rare case volumes.

## International Recognition and Opportunities

The UCM Facultad de Medicina has been accepted as a member of the ECTS Medicine Association (as confirmed in May 2026), indicating alignment with European medical education quality frameworks.

**WFME accreditation status:** PENDING_CONFIRMATION — the UCM website does not currently display a WFME quality seal, unlike UAM (which holds a confirmed ANECA-WFME seal).

The UCM degree (Grado en Medicina, MECES Level 3) provides direct access to doctoral studies in Spain. The qualification is recognised across the EU under Directive 2005/36/EC as a regulated healthcare profession.

**International exchange:** UCM Medicina participates in the Erasmus+ programme (Oficina de Movilidad). An updated list of partner institutions is published annually. ANNUAL_UPDATE_REQUIRED — students should verify which Medicine-specific Erasmus agreements are active for their cohort year.

The university is a founding member of the UNA Europa alliance of European research universities, which provides collaborative research and student mobility opportunities.

## Admission Model

UCM Medicine is part of Spain's public university admissions system, administered through the Distrito Único de Madrid (DUM) framework. Admission is determined exclusively by the nota de admisión — there is no proprietary entrance exam, no interview, and no portfolio.

**The nota de admisión formula:**

```
Nota de admisión = 0.6 × Nota media de Bachillerato
                 + 0.4 × Nota EVAU (fase general)
                 + up to 4.0 bonus points from EVAU fase específica
```

- **Base score maximum:** 10.0000 (Bachillerato + EVAU general phase combined)
- **Maximum nota de admisión:** 14.0000 (with full specific-phase bonus)
- **Specific phase:** The best 2 eligible subjects are selected. Each subject grade is multiplied by the ponderation coefficient (0.1 or 0.2) assigned by UCM to that subject for Medicine. Biology and Chemistry typically receive coefficient 0.2 at most Madrid universities (ANNUAL_UPDATE_REQUIRED — verify in the official UCM/DUM ponderation table each year).

**Access routes:**
- Spanish Bachillerato + EVAU (PAU): standard route
- FP Grado Superior + EVAU specific phase: valid, nota calculated on GPA
- International via PCE/UNED (Credencial UNEDasiss): valid; covers EU-system Bachilleratos and non-EU with homologation
- International via Credencial UE: valid for EU Bachillerato holders meeting their national university entry requirements
- Direct homologation (select countries): valid; check DUM requirements

**International students note:** All international candidates applying via DUM must demonstrate Spanish language proficiency at B2 level or above. This requirement applies to all non-native Spanish speakers accessing Comunidad de Madrid universities.

## Admission Process

### For Spanish PAU students

1. Complete Bachillerato (Years 1–2) and register for EVAU.
2. Sit EVAU: mandatory general phase + optional specific phase (strongly recommended — up to 4 bonus points).
3. Receive nota de admisión from the EVAU authority.
4. Submit preinscripción (university application) through the Comunidad de Madrid DUM portal during the designated window (ANNUAL_UPDATE_REQUIRED for exact dates).
5. List UCM Medicina in your degree preferences (up to 10 options across Madrid universities).
6. Await results of the ordinaria convocatoria assignment.
7. If not admitted in ordinaria, apply for a waiting list place and/or the extraordinaria convocatoria.
8. If admitted: complete enrolment (matrícula) within the published deadline.

### For international PCE/UNED students

1. Obtain a recognised secondary qualification equivalent to Spanish Bachillerato.
2. Apply to UNEDasiss for a Credencial (Acreditación). This involves submitting transcripts and, if applicable, requesting subject recognition.
3. Sit PCE (Pruebas de Competencias Específicas) at UNED for subjects applicable to Medicine — Biology and Chemistry are the most strategically valuable (coefficient 0.2 each at most Madrid universities; ANNUAL_UPDATE_REQUIRED).
4. Receive final UNEDasiss Credencial with calificación (5–10 scale, serving as CAU equivalent).
5. Submit preinscripción through the DUM portal (same window as Spanish students).
6. If applying from outside Spain: verify B2 Spanish requirement and Early Admission timeline (Early Admission UAM is a separate process for UAM; UCM uses the standard DUM process).
7. If admitted: complete enrolment and arrange visa/NIE if applicable.

## Admission Timeline

All dates are approximate based on standard DUM calendar patterns and are ANNUAL_UPDATE_REQUIRED. Verify each year at the Comunidad de Madrid admissions portal.

| Phase | Approximate Period |
|---|---|
| EVAU ordinaria (Madrid) | June (ANNUAL_UPDATE_REQUIRED) |
| EVAU extraordinaria (Madrid) | July (ANNUAL_UPDATE_REQUIRED) |
| DUM preinscripción ordinaria | June–July (ANNUAL_UPDATE_REQUIRED) |
| DUM results ordinaria | July (ANNUAL_UPDATE_REQUIRED) |
| Enrolment window | July–September (ANNUAL_UPDATE_REQUIRED) |
| DUM preinscripción extraordinaria | August–September (ANNUAL_UPDATE_REQUIRED) |
| Academic year begins | September (ANNUAL_UPDATE_REQUIRED) |
| PCE/UNED sessions | February and June (ANNUAL_UPDATE_REQUIRED) |

## Admission Score Distribution

UCM Medicina is one of the most competitive public Medicine programmes in Spain. The nota de corte for the 2025-26 intake was 13.100 (source: notasdecorte.es), down from the historically cited 13.5–13.9+ range of previous cycles. This may reflect expanded seat capacity or EVAU score distribution shifts; candidates should not plan around 13.100 as a permanent floor since the nota de corte changes annually.

**Historical trend (ANNUAL_UPDATE_REQUIRED):**

| Intake Year | Nota de Corte | Source |
|---|---|---|
| 2025-2026 | 13.100 | notasdecorte.es (verified) |
| 2024-2025 | PENDING_CONFIRMATION | — |
| 2023-2024 | PENDING_CONFIRMATION | — |

**What this means strategically:**

A candidate who holds a nota de admisión below ~13.000 has very limited admission probability at UCM in current competitive cycles. To reach the competitive range, candidates typically need:
- A Bachillerato average of approximately 9.0–10.0
- A solid EVAU general phase result (8.5+)
- Specific-phase results in Biology and Chemistry close to 9.0–10.0 each, combined with coefficient 0.2

**Ponderation coefficients for Medicine at UCM (ANNUAL_UPDATE_REQUIRED — verify at the DUM official ponderation table):**

| Subject | Coefficient |
|---|---|
| Biology | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Chemistry | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Physics | 0.1 (ANNUAL_UPDATE_REQUIRED) |
| Mathematics II | 0.1 (ANNUAL_UPDATE_REQUIRED) |

**Score trend:** Notas de corte for public Medicine in Madrid have remained stable in the very high range for multiple consecutive years, reflecting constant oversubscription. Candidates should not rely on downward fluctuation as a planning assumption.

**For PCE/UNED international students:** The nota de admisión is calculated using the UNEDasiss Credencial (5–10 scale) as the base, plus PCE subject ponderations. Reaching a nota de admisión above 13.5 from a UNEDasiss base requires near-perfect PCE results in Biology and Chemistry combined.

## Costs and Payment Structure

Tuition fees at UCM are set by the Comunidad de Madrid via regional decree and are subject to annual revision. The figures below are indicative based on the public university fee structure in Madrid.

| Fee Concept | EU/EEA Students | Non-EU Students | Notes |
|---|---|---|---|
| Annual tuition (per year, approx.) | ~1,000–1,500 EUR | ~8,000–12,000 EUR | ANNUAL_UPDATE_REQUIRED |
| Per-credit fee (experimental branch) | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | Medicine is classified as experimental branch (tasas más altas) |
| Enrolment / administrative fees | ~100–200 EUR | ~100–200 EUR | ANNUAL_UPDATE_REQUIRED |
| Student insurance (seguro escolar) | ~1.12 EUR | ~1.12 EUR | ANNUAL_UPDATE_REQUIRED |
| Repeat enrolment surcharge | Higher per-credit rate | Higher per-credit rate | Applies from 2nd enrolment in same subject |

Medicine in Spain is classified as an "experimental" branch of knowledge, which carries higher per-credit rates than humanities or social science degrees under regional tariff structures.

Non-EU students (extracomunitarios) pay significantly higher fees, currently in the range of €8,000+ per year at UCM (ANNUAL_UPDATE_REQUIRED — verify the current decreto de tasas for Comunidad de Madrid).

## Scholarships and Financial Aid

**National level:**
- **Beca General MEC (Ministerio de Educación y Formación Profesional):** Available to all students enrolled in public university degrees meeting income and academic thresholds. Covers partial tuition and may include a living stipend. Applications submitted annually via the MEFP scholarship portal (ANNUAL_UPDATE_REQUIRED).
- **Beca Movilidad (Erasmus+):** Available for approved Erasmus exchange periods at partner universities.

**Regional level (Comunidad de Madrid):**
- The Comunidad de Madrid offers supplementary grants for students who do not qualify for or receive insufficient MEC funding. PENDING_CONFIRMATION — verify current programmes at the Comunidad de Madrid education portal (ANNUAL_UPDATE_REQUIRED).

**University level:**
- UCM has internal scholarship and emergency aid mechanisms via its general student services. Details at ucm.es/becas (ANNUAL_UPDATE_REQUIRED).
- UCM participates in Banco Santander scholarship programmes for students with economic need.

**Important note:** Scholarship eligibility typically requires academic performance thresholds. Students who fail to pass a minimum number of ECTS per year risk losing their MEC scholarship.

## Accommodation and Cost of Living

Madrid is one of Spain's most expensive cities for student living. Candidates should budget realistically:

| Cost Category | Approximate Monthly Range | Notes |
|---|---|---|
| Shared flat room (piso compartido) | 600–900 EUR | ANNUAL_UPDATE_REQUIRED — Madrid rental market is volatile |
| University residence / colegio mayor | 700–1,200 EUR | ANNUAL_UPDATE_REQUIRED |
| Food (self-catering) | 200–350 EUR | ANNUAL_UPDATE_REQUIRED |
| Public transport (abono joven) | 20–30 EUR | ANNUAL_UPDATE_REQUIRED |
| Books / materials (Year 1 estimate) | 200–400 EUR | ANNUAL_UPDATE_REQUIRED |

UCM Moncloa campus is located in the university district (Ciudad Universitaria), which has a concentration of colegios mayores and student housing. The campus is connected to central Madrid via Metro (line 6, Moncloa).

Candidatos from outside Madrid should factor in relocation and initial setup costs. Madrid's rental market has tightened significantly in recent years; early accommodation search (from June) is strongly advised.

## International Exchange and Mobility Programs

UCM Medicina participates in the Erasmus+ programme via the Facultad de Medicina's Oficina de Movilidad. Exchange periods are available from Year 3 onwards (clinical phase). Partner institutions are European medical faculties.

UCM is also a member of the UNA Europa alliance (with KU Leuven, University of Edinburgh, Université Paris 1, and others), which may generate collaborative opportunities beyond standard Erasmus.

**Important limitation:** Erasmus and bilateral exchange slots for Medicine specifically are limited and competitive. Not all university-level mobility agreements extend to the Medicine degree. Students should verify with the Oficina de Movilidad which Medicine-specific slots are available and what academic prerequisites apply (ANNUAL_UPDATE_REQUIRED).

International incoming students to UCM Medicine: PENDING_CONFIRMATION on formal incoming exchange programme for Medicine.

## MIR Preparation and Professional Outcomes

The MIR (Médico Interno Residente) examination is the national postgraduate specialisation gateway in Spain. UCM graduates are eligible to sit the MIR after completing the Grado en Medicina.

**MIR pass rate for UCM graduates:** PENDING_CONFIRMATION — UCM does not publicly publish programme-specific MIR pass rates or ranking distributions in a readily verifiable format as of the date of this file.

**General context:** UCM's large cohort (320 students per year) produces a significant absolute number of MIR candidates annually. The quality of clinical training in major Madrid referral hospitals is generally considered a strong preparation for the MIR.

Post-MIR, graduates can specialise in the Spanish national health system (Sistema Nacional de Salud) or pursue careers in private medicine, research, or academia. UCM's membership in leading research alliances (UNA Europa, Campus de Excelencia Internacional Moncloa) provides additional research pathway access.

## Strategic Fit

### Good Fit For

- Candidates with a nota de admisión at or above ~13.1, who meet the 2025-26 nota de corte with a reasonable margin (ANNUAL_UPDATE_REQUIRED — plan with a buffer above the most recent verified figure).
- Students who prioritise a public university education at a historically prestigious institution with a large, nationally recognised clinical training network.
- Candidates based in Madrid or the Comunidad de Madrid who benefit from regional residency in terms of proximity and cost of living.
- Students who are comfortable with a large-cohort learning environment and primarily lecture-based preclinical methodology.
- International candidates (PCE/UNED route) who have maximised their Biology and Chemistry PCE scores and hold a solid UNEDasiss Credencial base.
- Research-oriented students who want access to a campus embedded within a major international research alliance.

### Less Suitable For

- Candidates whose nota de admisión is below ~12.9 — at the 2025-26 nota de corte of 13.100, other Madrid universities (UAM at 12.978) or other regions may present better strategic fit for this score range.
- Students who prefer small-group or PBL-intensive learning environments in preclinical years.
- Candidates expecting a bilingual or English-medium track — UCM does not offer one formally.
- International students with limited Spanish proficiency — the degree is primarily in Spanish and the B2 Spanish requirement is enforced by DUM.
- Students with significant financial constraints who cannot access MEC scholarships — Madrid's cost of living is high and non-EU tuition is substantial.

## Risks and Considerations

1. **Nota de corte variability:** Although UCM Medicine is consistently very competitive, the exact nota de corte shifts annually based on the applicant pool and regional EVAU score distributions. A candidate who narrowly exceeded the previous year's nota de corte may not be admitted in the current cycle.

2. **Regional residency priority:** The DUM does not formally prioritise Comunidad de Madrid residents in the standard public competition — all Spanish and EU students compete equally. However, logistical advantages (proximity, lower relocation costs) benefit local students.

3. **Seat fluctuation:** The number of seats (currently 320) is set annually by the Comunidad de Madrid and can change. ANNUAL_UPDATE_REQUIRED.

4. **Hospital assignment uncertainty:** Students are assigned to specific clinical hospitals from Year 3. Assignment to the most prestigious or centrally located hospitals (e.g. Hospital Clínico San Carlos) is not guaranteed and depends on administrative processes and student merit/preference mechanisms.

5. **Non-EU tuition exposure:** Non-EU students face fees approximately 6–8x higher than EU rates. Scholarship availability for non-EU students at UCM public prices is limited.

6. **PCE/UNED competitiveness:** International students applying via PCE must achieve near-perfect specific-phase scores to reach the nota de admisión threshold for Medicine at UCM. This is a high bar that requires systematic, structured preparation.

7. **Plan transition (2025 plan):** The curriculum transition from Plan 2010 to Plan 2025 means that some comparative data, timetables, and precedents may not apply to current cohorts. ANNUAL_UPDATE_REQUIRED as the new plan is fully implemented.

## Important Notes

- All admission dates (EVAU, DUM preinscripción, enrolment) are ANNUAL_UPDATE_REQUIRED and must be verified at the official Comunidad de Madrid admissions portal.
- The official ponderation table for UCM Medicine specific-phase subjects is published annually by the DUM and is ANNUAL_UPDATE_REQUIRED.
- Non-EU students must verify visa, NIE, and health insurance requirements separately from admission.
- The new Plan de Estudios 2025 (code 081P) applies to all students entering from 2025-26 onwards.
- UCM membership in the ECTS Medicine Association (confirmed 2026) is a recent development; its practical implications for credit recognition and international mobility are PENDING_CONFIRMATION.

## Key Insight

UCM Medicine is the largest-intake public Medicine degree in Madrid, offering access to a well-established clinical training network in major national referral hospitals. The nota de corte for 2025-26 was 13.100 (source: notasdecorte.es; ANNUAL_UPDATE_REQUIRED), which is lower than the historically cited range of 13.5–13.9. Admission depends almost entirely on candidates' ability to maximise their nota de admisión through strong Bachillerato grades and strategic EVAU specific-phase subject selection — particularly Biology and Chemistry (coefficient 0.2 each). There is no alternative admission mechanism: if a candidate's score does not reach the nota de corte, they are not admitted regardless of motivation, extracurricular record, or other qualities. Candidates should target a score with a clear margin above the most recent nota de corte and not plan for marginal admission.

## Final Takeaway

UCM Medicina is a strategically sound choice for strong academic performers who hold a nota de admisión above the current nota de corte. In 2025-26, the nota de corte was 13.100 — notably lower than the historically cited 13.5–13.9 range. Whether this reflects a lasting shift or a one-cycle anomaly is PENDING_CONFIRMATION. The combination of large seat availability (320 per year), major hospital clinical network, research alliance membership, and public tuition pricing makes it an objectively strong offering. The primary risk is admissions: the nota de corte leaves no margin for underperformance. Candidates should plan with a buffer above the most recent confirmed figure. International students via PCE must achieve strong specific-phase scores in Biology and Chemistry to reach this threshold.

## Frequently Asked Questions

**How is the nota de admisión calculated?**
The nota de admisión = 0.6 × Nota media de Bachillerato + 0.4 × Nota EVAU (fase general) + bonus from up to 2 specific-phase subjects (each subject grade × ponderation coefficient of 0.1 or 0.2). The maximum score is 14.0000.

**What is the nota de corte for UCM Medicine?**
The nota de corte is the nota de admisión of the last student admitted in each convocatoria. For the 2025-26 intake, the nota de corte was 13.100 (source: notasdecorte.es). It is not a fixed threshold — it changes annually based on competition. Historical cycles have ranged from approximately 13.1 to 13.9+ out of 14.000. Candidates should verify the current cycle's official figure at the DUM portal.

**Can international students apply via PCE?**
Yes. International students who obtain a UNEDasiss Credencial and sit PCE (Pruebas de Competencias Específicas) can apply through the standard DUM process. Biology and Chemistry PCEs are most strategically valuable (coefficient 0.2 each at UCM). Near-perfect PCE scores are typically required to reach the nota de admisión threshold for Medicine.

**What are the tuition fees?**
For EU/EEA students, approximately 1,000–1,500 EUR/year (ANNUAL_UPDATE_REQUIRED). For non-EU students, approximately 8,000+ EUR/year (ANNUAL_UPDATE_REQUIRED). Medicine falls in the "experimental" branch category, which carries higher per-credit rates.

**When do I apply?**
Applications (preinscripción) are submitted through the DUM portal in June–July for the ordinaria convocatoria. An extraordinaria convocatoria follows in August–September. Exact dates are ANNUAL_UPDATE_REQUIRED.

**What are the ponderation coefficients for Biology and Chemistry?**
Typically 0.2 for both Biology and Chemistry at most Madrid universities including UCM (ANNUAL_UPDATE_REQUIRED — verify the official DUM ponderation table for the current intake year, as coefficients can change).

**Is there an interview or entrance exam?**
No. UCM Medicine admission is based solely on the nota de admisión. There is no interview, no proprietary exam, and no portfolio requirement.

**When does clinical training begin?**
From Year 3. The first two years are taught at the Facultad de Medicina (Moncloa). From Year 3, students are assigned to an affiliated teaching hospital where clinical instruction takes place.

**Is there an English-medium track?**
No. There is no formally designated English-medium group. However, a growing proportion of lectures across the curriculum are delivered in English, and students are assessed in English for those specific topics. The TFG abstract is mandatory in English.
