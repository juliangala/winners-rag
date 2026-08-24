---
id: uah

type: university
subtype: public

name: Universidad de Alcalá
short_name: UAH

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Alcalá de Henares
  region: Comunidad de Madrid
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
  level: high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION

  last_admitted_scores:
    - intake_year: 2025-2026
      round: convocatoria_ordinaria
      score: 12.871
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
  - id: uah-medicina
    campus: Facultad de Medicina y Ciencias de la Salud, Campus de Alcalá de Henares
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
          score: 12.871
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
          score: 12.871
          round: convocatoria_ordinaria
          source: "notasdecorte.es / Distrito Único de Madrid (DUM) — ANNUAL_UPDATE_REQUIRED"

        - intake_year: 2024-2025
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: "Distrito Único de Madrid (DUM) — ANNUAL_UPDATE_REQUIRED"

        - intake_year: 2023-2024
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: "Distrito Único de Madrid (DUM) — ANNUAL_UPDATE_REQUIRED"

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
              notes: Best 2 eligible subjects × ponderation coefficient (0.1 or 0.2). Max nota 14.0000. Coefficients set annually by Comisión de Acceso a la Universidad de Madrid.
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED
                Chemistry:      0.2 # ANNUAL_UPDATE_REQUIRED
                Physics:        0.2 # ANNUAL_UPDATE_REQUIRED
                Mathematics_II: 0.2 # ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---

# Universidad de Alcalá (UAH) — Grado en Medicina

## Overview

The Universidad de Alcalá (UAH) is one of Spain's oldest universities — founded in 1293 and refounded in its modern form in 1977 — located in Alcalá de Henares, a UNESCO World Heritage city approximately 30 kilometres east of Madrid. The Facultad de Medicina y Ciencias de la Salud offers the Grado en Medicina within the framework of the Comunidad de Madrid's Distrito Único de Madrid (DUM) admissions system.

UAH Medicine is the third most competitive Medicine programme in the Madrid public university offer after UCM and UAM, with a 2025-26 nota de corte of 12.871 (source: notasdecorte.es). This places it firmly in the high-competitiveness tier — accessible to well-prepared candidates who fall just below the UCM and UAM thresholds, while remaining substantially above the national average for public Medicine programmes.

The degree spans 6 years (360 ECTS) and is delivered primarily in Spanish. Clinical training takes place in affiliated hospitals in the Alcalá de Henares corridor and the broader eastern Madrid region, most notably the Hospital Universitario Ramón y Cajal and the Hospital Universitario Príncipe de Asturias.

## Quick Evaluation

- **Degree:** Grado en Medicina — 6 years — 360 ECTS
- **Seats:** PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED)
- **Admission mechanism:** Nota de admisión (nota de corte model); no exam, no interview
- **Competitiveness:** High — 3rd highest nota de corte among Madrid public Medicine programmes in 2025-26
- **Nota de corte (2025-26):** 12.871 out of 14.000 (source: notasdecorte.es; ANNUAL_UPDATE_REQUIRED)
- **Tuition (approximate):** ~1,241 EUR/year for EU residents (ANNUAL_UPDATE_REQUIRED)
- **Clinical training from:** Year 3 — in affiliated hospitals (Hospital Ramón y Cajal, Hospital Príncipe de Asturias)
- **Teaching language:** Spanish (bilingual elements PENDING_CONFIRMATION)
- **WFME accreditation:** PENDING_CONFIRMATION
- **International access:** Via PCE/UNED or Credencial UE

## Key Facts

| Parameter | Value |
|---|---|
| Official name | Universidad de Alcalá |
| Short name | UAH |
| Degree | Grado en Medicina |
| Duration | 6 years (360 ECTS) |
| Annual seats | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Campus | Facultad de Medicina y Ciencias de la Salud, Alcalá de Henares |
| Year 1–2 location | Faculty premises, Alcalá de Henares |
| Year 3–6 location | Affiliated hospitals (Ramón y Cajal, Príncipe de Asturias, network TBC) |
| Teaching language | Spanish; bilingual elements PENDING_CONFIRMATION |
| Admission type | Nota de admisión (DUM — Distrito Único de Madrid) |
| No proprietary exam | Correct |
| No interview | Correct |
| Tuition (EU, indicative) | ~1,241 EUR/year (ANNUAL_UPDATE_REQUIRED) |
| Tuition (non-EU, indicative) | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Founded (modern) | 1977 (historically: 1293) |
| Website | http://medicinaycienciasdelasalud.uah.es/ |

## Program Options

UAH offers a single Grado en Medicina track. There is no separate bilingual cohort, no alternative campus, and no distinct tracks for domestic versus international students. All students entering through the DUM follow the same 6-year curriculum at the Alcalá de Henares campus.

There are no documented alternative entry pathways beyond the standard DUM competition. Students with specific needs (e.g., disability quota, athlete quota) should verify quota seat availability through the DUM framework.

## Program Structure

The Grado en Medicina at UAH is structured across 6 academic years totalling 360 ECTS, in line with Spanish Royal Decree 1393/2007 and the Medicine-specific regulation.

**Phase 1 — Preclínica (Years 1–2):** Core biomedical sciences delivered at the Facultad de Medicina y Ciencias de la Salud in Alcalá de Henares. Key subjects include Human Anatomy, Biochemistry, Physiology, Cell Biology, Histology and Embryology, Microbiology, Immunology, Pharmacology, and Pathological Anatomy. Students are introduced to clinical skills and professionalism from early stages.

**Phase 2 — Clínica (Years 3–6):** Clinical subjects delivered in affiliated teaching hospitals. Students rotate across internal medicine, surgery, paediatrics, obstetrics and gynaecology, psychiatry, primary care, and other specialties. Year 6 typically features an extended clinical rotation period.

**TFG (Final Degree Project):** A mandatory final project component. Language requirements PENDING_CONFIRMATION.

**Electives:** Optional subjects are available within the degree plan (exact ECTS and subject list PENDING_CONFIRMATION).

## Teaching Methodology

UAH Medicine employs a methodology combining traditional lecture-based instruction in preclinical years with progressively more clinical, practice-oriented teaching as students advance through the degree. Small-group seminars, laboratory work, and skills simulation are incorporated throughout the curriculum.

UAH as an institution has historically emphasised its connection to the Spanish Enlightenment tradition of learning — the original Universidad Complutense was founded in Alcalá before moving to Madrid. The medical faculty retains a research-active orientation, with links to IRYCIS (Instituto Ramón y Cajal de Investigación Sanitaria), the research arm affiliated with the Hospital Universitario Ramón y Cajal.

The extent of English-medium instruction within the UAH Medicine curriculum is PENDING_CONFIRMATION. No formally designated bilingual group has been confirmed as of the date of this file.

## Clinical Training

Clinical training at UAH takes place primarily in the Unidades Docentes Hospitalarias (UDH) affiliated with the Facultad de Medicina y Ciencias de la Salud. Clinical rotations begin from Year 3.

**Primary affiliated hospitals:**

- **Hospital Universitario Ramón y Cajal** — Madrid (Chamartín district). A major tertiary referral hospital within the national health system (SERMAS), and one of Spain's leading research hospitals through its affiliation with IRYCIS. Although located in Madrid city, it serves as a principal UAH clinical training site.
- **Hospital Universitario Príncipe de Asturias** — Alcalá de Henares. The main public hospital of the Alcalá de Henares area and geographically proximate to the UAH campus.

Additional affiliated centres within the eastern Comunidad de Madrid health network may include primary care centres and smaller hospitals (PENDING_CONFIRMATION — verify current UDH list at the faculty website or through the Madrid SERMAS network).

IRYCIS affiliation provides research internship opportunities alongside clinical training for interested students.

## International Recognition and Opportunities

The UAH Grado en Medicina complies with European Directive 2005/36/EC on the recognition of professional qualifications, enabling graduates to seek medical licences across EU/EEA member states under the regulated professions framework.

**WFME accreditation:** PENDING_CONFIRMATION — verify current status at the UAH faculty website.

**Erasmus+ mobility:** UAH participates in the Erasmus+ programme. The availability of Medicine-specific bilateral agreements is PENDING_CONFIRMATION — students should verify with the faculty's international relations office which slots are open for Medicine students and from which year of study.

**Research networks:** UAH's affiliation with IRYCIS and its membership in various Spanish research consortia provides a research environment for students interested in pursuing scientific careers alongside clinical training.

The university's historic prestige and UNESCO World Heritage city status give UAH a distinctive cultural profile that may interest internationally minded candidates, though this does not directly translate into formal international academic agreements specific to Medicine.

## Admission Model

UAH Medicine is part of Spain's public university admissions system, administered through the Distrito Único de Madrid (DUM). Admission is determined exclusively by the nota de admisión — there is no proprietary entrance exam, no interview, and no portfolio.

All five Madrid public universities offering Medicine (UCM, UAM, UAH, URJC, and the CUD defence university) participate in the same DUM framework. Candidates rank preferences and compete across the pool on nota de admisión alone.

**The nota de admisión formula:**

```
Nota de admisión = 0.6 × Nota media de Bachillerato
                 + 0.4 × Nota EVAU (fase general)
                 + up to 4.0 bonus points from EVAU fase específica
```

- **Base score maximum:** 10.0000
- **Maximum nota de admisión:** 14.0000 (with full specific-phase bonus)
- **Specific phase:** Best 2 eligible subjects selected. Each subject grade × ponderation coefficient (0.1 or 0.2) set annually by the Comisión de Acceso a la Universidad de Madrid.

**Ponderation coefficients for Medicine at UAH (ANNUAL_UPDATE_REQUIRED — verify at the official DUM ponderation table):**

Biology: 0.2, Chemistry: 0.2, Physics: 0.2, Mathematics II: 0.2 (all ANNUAL_UPDATE_REQUIRED).

**Access routes:**
- Spanish Bachillerato + EVAU (PAU): standard route
- FP Grado Superior + EVAU specific phase: valid
- International via PCE/UNED (Credencial UNEDasiss): valid
- International via Credencial UE: valid for EU Bachillerato holders
- Direct homologation (select countries): valid; check DUM requirements

## Admission Process

### For Spanish PAU students

1. Complete Bachillerato and sit EVAU: mandatory general phase + optional specific phase (strongly recommended for Biology and Chemistry).
2. Receive nota de admisión from the EVAU authority.
3. Submit preinscripción through the DUM portal (admisión.comunidad.madrid) during the designated window (ANNUAL_UPDATE_REQUIRED).
4. List UAH Medicina in your degree preferences among up to 10 options in Madrid.
5. Await results of the ordinaria convocatoria assignment.
6. If not admitted in the ordinaria: await the extraordinaria convocatoria or consider alternative universities.
7. If admitted: complete enrolment (matrícula) within the published deadline at UAH.

### For international PCE/UNED students

1. Obtain a secondary qualification equivalent to Spanish Bachillerato.
2. Apply to UNEDasiss for a Credencial (Acreditación). Submit transcripts and request subject recognition as applicable.
3. Sit PCE at UNED for subjects relevant to Medicine — Biology and Chemistry are most strategically valuable (coefficient 0.2 each; ANNUAL_UPDATE_REQUIRED).
4. Receive final UNEDasiss Credencial with calificación (5–10 scale).
5. Submit preinscripción through the DUM portal using the same window as Spanish students.
6. If admitted: complete enrolment and arrange visa/NIE if applicable.

## Admission Timeline

All dates are approximate based on standard DUM calendar patterns. All dates are ANNUAL_UPDATE_REQUIRED — verify at the official Comunidad de Madrid admissions portal (admisión.comunidad.madrid).

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

UAH Medicine's nota de corte for 2025-26 was 12.871 (source: notasdecorte.es; ANNUAL_UPDATE_REQUIRED). This positions UAH as the third most competitive Medicine programme in the Comunidad de Madrid after UCM (13.100) and UAM (12.978 — PENDING_CONFIRMATION for UAM 2025-26 figure), and before URJC.

**Historical trend (ANNUAL_UPDATE_REQUIRED):**

| Intake Year | Nota de Corte | Source |
|---|---|---|
| 2025-2026 | 12.871 | notasdecorte.es (verified) |
| 2024-2025 | PENDING_CONFIRMATION | — |
| 2023-2024 | PENDING_CONFIRMATION | — |

**What this means strategically:**

A nota de admisión of 12.871 represents a high academic threshold. Candidates must combine a strong Bachillerato average with solid EVAU general-phase performance and near-optimal specific-phase bonus maximisation. To reach 12.871:
- A Bachillerato average of 9.0 and EVAU general phase of 8.5 produces a base of ~8.7; Biology and Chemistry PCE/EVAU scores of 9.5 each with coefficient 0.2 would add 3.8 bonus points, yielding approximately 12.5 — still below the threshold.
- Candidates typically need Bachillerato averages of 9.5+ combined with Biology and Chemistry specific-phase scores of 9.5–10 to reach this range.

The difference between UAH (12.871) and UCM (13.100) is approximately 0.23 points — a meaningful margin in a system where total scores cluster densely. Candidates who fall just below the UCM and UAM thresholds should position UAH as a serious primary option rather than a fallback.

**Ponderation coefficients for Medicine at UAH (ANNUAL_UPDATE_REQUIRED):**

| Subject | Coefficient |
|---|---|
| Biology | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Chemistry | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Physics | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Mathematics II | 0.2 (ANNUAL_UPDATE_REQUIRED) |

Note that Madrid applies coefficient 0.2 to all four main science subjects for Medicine, giving candidates somewhat more flexibility in which two specific-phase subjects to prioritise compared to regions where only Biology and Chemistry carry the maximum coefficient.

## Costs and Payment Structure

Tuition fees at UAH are set by the Comunidad de Madrid via regional decree and are subject to annual revision. Medicine is classified as an "experimental" branch of knowledge (rama experimental), carrying the highest per-credit rates in the regional tariff structure.

| Fee Concept | EU/EEA Students | Non-EU Students | Notes |
|---|---|---|---|
| Annual tuition (per year, approx.) | ~1,241 EUR | PENDING_CONFIRMATION | ANNUAL_UPDATE_REQUIRED |
| Per-credit fee (experimental branch) | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | Medicine = experimental branch; higher per-credit rate |
| Enrolment / administrative fees | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Student insurance (seguro escolar) | ~1.12 EUR | ~1.12 EUR | ANNUAL_UPDATE_REQUIRED |
| Repeat enrolment surcharge | Higher per-credit rate | Higher per-credit rate | Applies from 2nd enrolment in same subject |

The indicative first-year figure of ~1,241 EUR aligns with the standard Madrid public university experimental-branch rate and is consistent with other Madrid public Medicine programmes. Non-EU tuition is significantly higher (PENDING_CONFIRMATION — verify at the Comunidad de Madrid official decreto de tasas).

## Scholarships and Financial Aid

**National level:**
- **Beca General MEC:** Available to all students enrolled in public university degrees meeting income and academic thresholds. Covers partial tuition and may include a living stipend. Applications submitted annually via the MEFP scholarship portal (ANNUAL_UPDATE_REQUIRED).
- **Beca Movilidad (Erasmus+):** Available for approved Erasmus exchange periods.

**Regional level (Comunidad de Madrid):**
- The Comunidad de Madrid offers supplementary grants for students who do not receive sufficient MEC funding. PENDING_CONFIRMATION — verify current programmes at the Comunidad de Madrid education portal (ANNUAL_UPDATE_REQUIRED).

**University level:**
- UAH has internal scholarship and emergency aid mechanisms. Details at uah.es/becas (ANNUAL_UPDATE_REQUIRED).
- UAH participates in various private foundation scholarship programmes — verify current offerings with the UAH student services office.

**Research grants:** Students interested in research can access IRYCIS and UAH-affiliated research fellowship opportunities during their clinical years. PENDING_CONFIRMATION on formal student research grant programmes.

## Accommodation and Cost of Living

Alcalá de Henares offers a significantly more affordable cost of living than central Madrid, which is a practical advantage for students who choose to reside in the city rather than commute from Madrid.

| Cost Category | Approximate Monthly Range | Notes |
|---|---|---|
| Shared flat room (Alcalá de Henares) | 350–550 EUR | ANNUAL_UPDATE_REQUIRED — lower than Madrid city |
| Shared flat room (commuting from Madrid) | 600–900 EUR | ANNUAL_UPDATE_REQUIRED |
| University residence (if available) | PENDING_CONFIRMATION | ANNUAL_UPDATE_REQUIRED |
| Food (self-catering, Alcalá) | 180–300 EUR | ANNUAL_UPDATE_REQUIRED |
| Public transport (Cercanías Madrid–Alcalá) | 30–50 EUR/month | ANNUAL_UPDATE_REQUIRED — varies by zone and abono type |
| Books / materials (Year 1 estimate) | 200–400 EUR | ANNUAL_UPDATE_REQUIRED |

Alcalá de Henares is well connected to Madrid via Cercanías (regional rail), making it feasible for students to commute from Madrid or to access Madrid-based social and cultural life on a regular basis. Students assigned to the Hospital Ramón y Cajal for clinical rotations will need to budget for travel within the Madrid commuter rail network.

## International Exchange and Mobility Programs

UAH participates in the Erasmus+ programme at the institutional level. The availability of Medicine-specific Erasmus bilateral agreements is PENDING_CONFIRMATION — students should contact the Facultad de Medicina y Ciencias de la Salud's international relations office to verify which partner institutions are active for Medicine students and from which year of study exchange is permitted.

UAH is a member of various Spanish and European university networks. Specific alliances with direct implications for Medicine students are PENDING_CONFIRMATION.

Research mobility: Through IRYCIS affiliation, students in later clinical years may access research stays at partner institutions or national research centres. These opportunities are competitive and not guaranteed to all students.

## MIR Preparation and Professional Outcomes

The MIR (Médico Interno Residente) examination is the national gateway to medical specialisation in Spain. All UAH Grado en Medicina graduates are eligible to sit the MIR.

**MIR pass rate for UAH graduates:** PENDING_CONFIRMATION — UAH does not publicly publish programme-specific MIR pass rates in a readily verifiable format as of the date of this file.

**General context:** Clinical training at major Madrid referral hospitals (Ramón y Cajal, Príncipe de Asturias) provides exposure to complex case volumes and specialist environments that support MIR preparation. The Hospital Ramón y Cajal is particularly recognised for its research culture and specialist training across multiple disciplines.

Post-MIR, graduates can specialise within the Sistema Nacional de Salud or pursue private medicine, research, or academic careers. UAH's research environment through IRYCIS provides an additional pathway for graduates interested in combining clinical and scientific careers.

## Strategic Fit

### Good Fit For

- Candidates with a nota de admisión between approximately 12.87 and 13.00, for whom UAH is a genuine primary option (not just a fallback) within the DUM competition.
- Students who did not reach UCM or UAM thresholds but have a solid academic record and can compete at the UAH level.
- Candidates who value living in a more affordable, historically significant university city (Alcalá de Henares) rather than central Madrid, while retaining excellent transport links to the capital.
- International students (PCE/UNED route) who have achieved strong Biology and Chemistry scores and hold a competitive UNEDasiss Credencial above ~12.5.
- Students interested in research, given UAH's IRYCIS affiliation and hospital research infrastructure.
- Candidates who prefer a slightly smaller-cohort environment compared to UCM's 320-seat programme (PENDING_CONFIRMATION on UAH seat count).

### Less Suitable For

- Candidates whose nota de admisión is below approximately 12.7 — the URJC or other regional universities may be a more realistic match.
- Students expecting a bilingual or English-medium track — no confirmed bilingual cohort at UAH Medicine.
- Candidates who require accommodation in a city with the full cultural and social infrastructure of central Madrid — Alcalá de Henares is a smaller city, albeit well connected.
- International students with limited Spanish — the degree is primarily in Spanish and DUM requires B2 Spanish competency.

## Risks and Considerations

1. **Nota de corte variability:** The 2025-26 nota de corte of 12.871 is not a stable floor. It shifts annually with the applicant pool composition and EVAU score distributions. Candidates should plan with a buffer above the most recent confirmed figure.

2. **DUM competition dynamics:** All five Madrid public Medicine programmes share the same DUM pool. A candidate listing UAH second (after UCM or UAM) may be assigned to UAH only if they fall below the UCM/UAM thresholds. Score planning must account for this cascade mechanism.

3. **Seat count uncertainty:** The exact number of Medicine seats at UAH is PENDING_CONFIRMATION. Seat counts can be revised annually by the Comunidad de Madrid.

4. **Hospital assignment logistics:** Students assigned to Hospital Ramón y Cajal (located in Madrid city) for clinical rotations will need to commute from Alcalá de Henares or arrange accommodation closer to the hospital. Travel time and cost should be budgeted.

5. **Non-EU tuition:** Non-EU students face significantly higher fees. PENDING_CONFIRMATION on the exact non-EU rate at UAH.

6. **PCE/UNED threshold:** International students via PCE must achieve strong specific-phase scores in Biology and Chemistry to approach the nota de admisión of 12.871. Near-perfect PCE results are required.

7. **Limited historical data:** Fewer cycles of independently tracked nota de corte data for UAH Medicine compared to UCM or UAM may reduce the precision of trend analysis for strategic planning.

## Important Notes

- All admission dates (EVAU, DUM preinscripción, enrolment) are ANNUAL_UPDATE_REQUIRED — verify at the official Comunidad de Madrid admissions portal (admisión.comunidad.madrid).
- The official ponderation table for UAH Medicine specific-phase subjects is published annually by the Comisión de Acceso a la Universidad de Madrid and is ANNUAL_UPDATE_REQUIRED.
- Non-EU students must verify visa, NIE, and health insurance requirements separately from admission.
- The affiliated hospital list (UDH) for clinical training should be verified at the faculty website each intake year, as hospital affiliations can change.
- IRYCIS affiliation is confirmed as a research-active environment but does not guarantee individual student access to research projects.

## Key Insight

UAH Medicine occupies a clear strategic niche within the Madrid public university landscape: it is the third most competitive Medicine programme in the region, with a 2025-26 nota de corte of 12.871. The 0.229-point gap below UCM (13.100) makes UAH a meaningful option for candidates whose nota de admisión falls in the 12.87–13.0 range — a common scenario among well-prepared candidates who cannot quite reach UCM or UAM thresholds. The Alcalá de Henares location offers a lower cost of living than central Madrid while maintaining strong connectivity to the capital. Clinical training in Hospital Ramón y Cajal — one of Madrid's leading referral hospitals — provides a high-quality hospital environment that competes with those of the larger Madrid institutions.

## Final Takeaway

For candidates in the 12.87–13.05 nota de admisión range, UAH Medicine is a strategically sound primary target within the DUM system. The degree offers genuine quality through its IRYCIS-affiliated research environment and Hospital Ramón y Cajal clinical network, at a cost of living substantially below central Madrid. The key planning variable is score margin: the nota de corte of 12.871 changes annually, and candidates should not plan on marginal admission. UAH should be listed as a realistic primary option — not a safety net — by candidates who have optimised their specific-phase Biology and Chemistry scores and hold a solid Bachillerato average above 9.0.

## Frequently Asked Questions

**How is the nota de admisión calculated?**
The nota de admisión = 0.6 × Nota media de Bachillerato + 0.4 × Nota EVAU (fase general) + bonus from up to 2 specific-phase subjects (each subject grade × ponderation coefficient of 0.1 or 0.2). The maximum score is 14.0000.

**What is the nota de corte for UAH Medicine?**
For the 2025-26 intake, the nota de corte was 12.871 (source: notasdecorte.es). It is not a fixed threshold — it changes annually. Historical data for prior cycles is PENDING_CONFIRMATION. Always verify the current cycle's official figure at the DUM portal.

**Can international students apply via PCE?**
Yes. International students who obtain a UNEDasiss Credencial and sit PCE (Pruebas de Competencias Específicas) can apply through the standard DUM process. Biology and Chemistry PCEs carry coefficient 0.2 at UAH (ANNUAL_UPDATE_REQUIRED). Strong PCE scores in both subjects are required to approach the nota de admisión threshold.

**What are the tuition fees?**
For EU/EEA students, approximately 1,241 EUR/year (ANNUAL_UPDATE_REQUIRED). For non-EU students, PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED). Medicine falls in the "experimental" branch category.

**When do I apply?**
Applications (preinscripción) are submitted through the DUM portal in June–July for the ordinaria convocatoria. An extraordinaria convocatoria follows in August–September. All dates are ANNUAL_UPDATE_REQUIRED.

**What are the ponderation coefficients for Biology and Chemistry?**
Biology: 0.2, Chemistry: 0.2 (both ANNUAL_UPDATE_REQUIRED — verify at the official DUM ponderation table). Physics and Mathematics II also carry 0.2 at most Madrid universities for Medicine (ANNUAL_UPDATE_REQUIRED), providing flexibility in specific-phase subject selection.

**Is there an interview or entrance exam?**
No. UAH Medicine admission is based solely on the nota de admisión within the DUM framework. There is no interview, no proprietary exam, and no portfolio requirement.

**When does clinical training begin?**
From Year 3. Years 1–2 are taught at the Facultad de Medicina y Ciencias de la Salud in Alcalá de Henares. From Year 3, students rotate through affiliated teaching hospitals including Hospital Universitario Ramón y Cajal and Hospital Universitario Príncipe de Asturias.

**Is Alcalá de Henares far from Madrid?**
Alcalá de Henares is approximately 30 km east of Madrid and is served by Cercanías (commuter rail) with journey times of approximately 40–50 minutes to Madrid Atocha or Chamartín. Students have the option to live in Alcalá (more affordable) or commute from Madrid (higher accommodation costs but greater urban access).
