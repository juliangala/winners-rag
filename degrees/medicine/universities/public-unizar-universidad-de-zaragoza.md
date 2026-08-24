---
id: unizar
type: university
subtype: public
name: Universidad de Zaragoza
short_name: UNIZAR
degree: Medicine
last_update: 2026-05-28
valid_for_intake: 2026-2027
location:
  city: Zaragoza
  region: Aragón
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
  level: high
admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
    - intake_year: 2025-2026
      round: convocatoria_ordinaria
      score: 12.675 # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: "Zaragoza campus. Source: notasdecorte.es / Aragón (AUPV) — ANNUAL_UPDATE_REQUIRED. Note: Huesca campus 12.592 (2025-26)"
    - intake_year: 2024-2025
      round: convocatoria_ordinaria
      score: 12.738
      score_type: nota_de_admision
      notes: "Zaragoza campus, definitive (November 2024). Source: academico.unizar.es/acceso-admision-grado/corte — ANNUAL_UPDATE_REQUIRED"
    - intake_year: 2023-2024
      round: convocatoria_ordinaria
      score: 12.651
      score_type: nota_de_admision
      notes: "Zaragoza campus, definitive (October 2023). Source: academico.unizar.es/acceso-admision-grado/corte — ANNUAL_UPDATE_REQUIRED"
international_profile:
  international_students_percentage: PENDING_CONFIRMATION
  international_nationalities: []
programs:
  - id: unizar-medicina-zaragoza
    campus: Facultad de Medicina, C/ Domingo Miral s/n, Zaragoza
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
          score: 12.675 # ANNUAL_UPDATE_REQUIRED
          score_type: nota_de_admision
          notes: "Zaragoza campus. Source: notasdecorte.es / Aragón — ANNUAL_UPDATE_REQUIRED"
        - intake_year: 2024-2025
          round: convocatoria_ordinaria
          score: 12.738
          score_type: nota_de_admision
          notes: "Zaragoza campus definitive. Source: academico.unizar.es — ANNUAL_UPDATE_REQUIRED"
        - intake_year: 2023-2024
          round: convocatoria_ordinaria
          score: 12.651
          score_type: nota_de_admision
          notes: "Zaragoza campus definitive. Source: academico.unizar.es — ANNUAL_UPDATE_REQUIRED"
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
          score: 12.675 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: "notasdecorte.es / Aragón (AUPV) — ANNUAL_UPDATE_REQUIRED"
        - intake_year: 2024-2025
          score: 12.738
          round: convocatoria_ordinaria
          source: "academico.unizar.es/acceso-admision-grado/corte — ANNUAL_UPDATE_REQUIRED"
        - intake_year: 2023-2024
          score: 12.651
          round: convocatoria_ordinaria
          source: "academico.unizar.es/acceso-admision-grado/corte — ANNUAL_UPDATE_REQUIRED"
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
              notes: 60% of the nota de admisión.
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
              notes: Best 2 eligible subjects × ponderation coefficient. Max nota 14.0000. Coefficients approved by Consejo de Gobierno de la Universidad de Zaragoza, Acuerdo 31 October 2024, applicable from 2025-26 onward.
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED — Source: Acuerdo CG UNIZAR 31/10/2024 Anexo I
                Chemistry:      0.1 # ANNUAL_UPDATE_REQUIRED
                Physics:        0.1 # ANNUAL_UPDATE_REQUIRED
                Mathematics_II: 0.2 # ANNUAL_UPDATE_REQUIRED
                Drawing_II:     ANNUAL_UPDATE_REQUIRED
                History_Art:    ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
  - id: unizar-medicina-huesca
    campus: Facultad de Ciencias de la Salud y del Deporte, Huesca
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
          score: 12.592 # ANNUAL_UPDATE_REQUIRED
          score_type: nota_de_admision
          notes: "Huesca campus. Source: notasdecorte.es / Aragón — ANNUAL_UPDATE_REQUIRED"
        - intake_year: 2024-2025
          round: convocatoria_ordinaria
          score: 12.639
          score_type: nota_de_admision
          notes: "Huesca campus definitive. Source: academico.unizar.es — ANNUAL_UPDATE_REQUIRED"
        - intake_year: 2023-2024
          round: convocatoria_ordinaria
          score: 12.601
          score_type: nota_de_admision
          notes: "Huesca campus definitive. Source: academico.unizar.es — ANNUAL_UPDATE_REQUIRED"
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
          score: 12.592 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: "notasdecorte.es / Aragón — ANNUAL_UPDATE_REQUIRED"
        - intake_year: 2024-2025
          score: 12.639
          round: convocatoria_ordinaria
          source: "academico.unizar.es/acceso-admision-grado/corte — ANNUAL_UPDATE_REQUIRED"
        - intake_year: 2023-2024
          score: 12.601
          round: convocatoria_ordinaria
          source: "academico.unizar.es/acceso-admision-grado/corte — ANNUAL_UPDATE_REQUIRED"
      admission_pathways:
        - eligible_profiles:
            - Spanish EVAU (PAU) — all regional variants
            - International via PCE/UNED
            - International via Credencial UE
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
              notes: 40% of the nota de admisión.
            - component: evau_specific_phase_bonus
              enabled: true
              role: bonus_only
              maximum_bonus: 4.0
              grade_source: evau_fase_especifica
              notes: Same ponderations as Zaragoza campus — Biology 0.2, Chemistry 0.1, Physics 0.1, Mathematics II 0.2 — ANNUAL_UPDATE_REQUIRED.
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED
                Chemistry:      0.1 # ANNUAL_UPDATE_REQUIRED
                Physics:        0.1 # ANNUAL_UPDATE_REQUIRED
                Mathematics_II: 0.2 # ANNUAL_UPDATE_REQUIRED
                Drawing_II:     ANNUAL_UPDATE_REQUIRED
                History_Art:    ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---

# Universidad de Zaragoza (UNIZAR) — Grado en Medicina

## Overview

The Universidad de Zaragoza (UNIZAR), founded in 1542, is one of Spain's oldest and most established public research universities, serving as the principal higher education institution of Aragón. The Facultad de Medicina offers the Grado en Medicina on its main Zaragoza campus, with an additional campus option in Huesca (Facultad de Ciencias de la Salud y del Deporte). Both campuses deliver the same 6-year, 360 ECTS program and are governed by the same admission system. A new Plan de Estudios 2024 began progressive implementation from the 2024-25 academic year. Admission is based exclusively on the nota de admisión — no additional exam, interview, or language requirement applies.

**Nota de corte data (source: notasdecorte.es / academico.unizar.es):**
- 2025-26: Zaragoza **12.675** | Huesca **12.592** (source: notasdecorte.es / Aragón) # ANNUAL_UPDATE_REQUIRED
- 2024-25: Zaragoza 12.738 | Huesca 12.639 (source: academico.unizar.es)
- 2023-24: Zaragoza 12.651 | Huesca 12.601 (source: academico.unizar.es)

Source: notasdecorte.es / academico.unizar.es/acceso-admision-grado/corte

> **Note on campus scores (2025-26):** UNIZAR offers Medicine at two campuses. The Zaragoza campus nota de corte is **12.675** and the Huesca campus (Facultad de Ciencias de la Salud y del Deporte) is **12.592** for 2025-26, per notasdecorte.es / Aragón. The Zaragoza campus consistently runs approximately 0.06–0.10 higher than Huesca. Both campuses award the same degree. Candidates should apply to both if their nota de admisión is near either threshold. All scores are ANNUAL_UPDATE_REQUIRED — verify at academico.unizar.es each cycle.

## Quick Evaluation

| Dimension | Assessment |
|---|---|
| Academic prestige | High — established research university, oldest in Aragón |
| Competitiveness | High — nota de corte stable around 12.6–12.8 (lower than Andalucía) |
| Clinical training | Strong — network of Zaragoza university hospitals |
| International exposure | Good — active Erasmus program, international exchange |
| Cost of living | Low to moderate — Zaragoza is affordable by national standards |
| Two campuses | Zaragoza (main, higher nota) and Huesca (secondary, slightly lower nota) |

## Key Facts

| Field | Detail |
|---|---|
| Full name | Universidad de Zaragoza |
| Acronym | UNIZAR |
| Faculty | Facultad de Medicina (Zaragoza); Facultad de Ciencias de la Salud y del Deporte (Huesca) |
| Founded | 1542 |
| Degree | Grado en Medicina |
| Duration | 6 years |
| Total ECTS | 360 |
| Teaching language | Spanish |
| Location (main) | Zaragoza, Aragón |
| Location (secondary) | Huesca, Aragón |
| Accreditation | ANECA; Bologna-compliant EU degree |
| Admissions system | Aragón regional admissions system |
| Current study plan | Plan 2024 (progressive implementation from 2024-25); Plan 2008 being phased out |

## Program Options

UNIZAR offers the Grado en Medicina on two campuses within Aragón:

1. **Zaragoza campus** (Facultad de Medicina) — main campus; higher nota de corte; larger clinical teaching network.
2. **Huesca campus** (Facultad de Ciencias de la Salud y del Deporte) — secondary campus; slightly lower nota de corte (typically ~0.05–0.10 below Zaragoza); same degree, same quality standards.

Both campuses award an identical degree. Students apply separately to each campus through the UNIZAR admissions system and should include both as preferences if feasible.

## Program Structure

From 2024-25, UNIZAR is progressively implementing the **Plan de Estudios 2024** (verified by BOE November 2024). The new plan is being rolled out one year at a time, beginning with Year 1 in 2024-25. The previous Plan 2008 continues for students enrolled before 2024-25.

The new Plan 2024 follows the national Orden ECI/332/2008 framework and organizes the degree into modules:

| Year | Key Content Areas |
|---|---|
| Year 1 | Human Anatomy & Histology, Biochemistry, Biostatistics, Cell Biology & Genetics, General Physiology |
| Year 2 | Medical Physiology, Applied Anatomy, Immunology, Medical Communication & Bioethics |
| Year 3 | Pathological Anatomy, Pharmacology, Microbiology, Surgery Fundamentals, Psychiatry, Internal Medicine Foundations |
| Year 4 | Cardiology, Respiratory Medicine, Neurology, Ophthalmology, ENT, Dermatology, Radiology, Urology |
| Year 5 | Preventive Medicine & Public Health, Obstetrics, Gynaecology, Paediatrics, Endocrinology, Legal Medicine |
| Year 6 | Full clinical rotations (ECOE clinical competency assessment) + Final Year Project (TFG) |

A formal ECOE (Evaluación Clínica Objetiva Estructurada) assessment evaluates competencies acquired during clinical rotations — an important feature that validates clinical skill acquisition.

## Teaching Methodology

The UNIZAR Medicine program combines lecture-based teaching, practical laboratory sessions, clinical simulation, problem-based learning components, and progressive hospital integration from the mid-years. The Facultad de Medicina has anatomical laboratories, clinical simulation rooms, and a biomedical library. Year 6 is predominantly dedicated to supervised clinical rotations with the ECOE assessment at the end. The university operates a Moodle-based virtual campus (ADD) for digital course support.

## Clinical Training

Clinical training is conducted through the Aragonese health system hospital network (SALUD — Servicio Aragonés de Salud) under the framework agreement between UNIZAR and the Government of Aragón:

- **Hospital Universitario Miguel Servet** — major tertiary referral centre, Zaragoza; primary teaching hospital for the Zaragoza campus
- **Hospital Clínico Universitario Lozano Blesa** — university hospital, Zaragoza; second principal teaching hospital
- **Hospital Universitario San Jorge** — Huesca; primary teaching hospital for the Huesca campus
- **Centros de Salud (Primary Care)** — Aragonese Health Service primary care centres; Year 6 Primary Care rotation

The ECOE examination at the end of Year 6 is a structured clinical competency assessment conducted across the teaching hospital network, ensuring graduates meet defined clinical standards before receiving the degree.

## International Recognition and Opportunities

The UNIZAR Grado en Medicina is recognized across the EU under the Bologna Process and EU Directive 2005/36/EC. Graduates may apply for medical registration in any EU member state.

Students may participate in:

- **Erasmus+** — bilateral clinical and academic placements with European partner universities; the Facultad de Medicina has agreements with institutions in several European countries, including cooperating programs in the Philippines, Guatemala, and Nicaragua (international cooperation practicums)
- **SICUE** — national inter-university exchange within Spain
- **Bilateral agreements** — Latin American and selected non-European institutions
- **IFMSA** — international student medical exchange
- **UNIVERSA** (UNIZAR employment and internship platform)

The Facultad de Medicina at Zaragoza specifically offers international clinical cooperation practicums in Filipinas, Guatemala/Nicaragua for motivated students.

## Admission Model

Access to Grado en Medicina at UNIZAR is governed by the Aragón autonomous community admissions system, with the nota de admisión calculated using the national formula.

**Nota de admisión formula:**

```
Nota de admisión = 0.6 × Nota media Bachillerato
                 + 0.4 × EVAU fase general score
                 + best 2 specific-phase subjects × ponderation coefficient
```

- Base maximum: **10.0000**
- Maximum with bonus: **14.0000**

**Ponderation coefficients for Medicina at UNIZAR** (Zaragoza and Huesca campuses) — approved by UNIZAR Consejo de Gobierno, Acuerdo 31 October 2024, applicable from 2025-26 onward:

| Subject | Coefficient |
|---|---|
| Biology | 0.2 # ANNUAL_UPDATE_REQUIRED |
| Chemistry | 0.1 # ANNUAL_UPDATE_REQUIRED |
| Physics | 0.1 # ANNUAL_UPDATE_REQUIRED |
| Mathematics II | 0.2 # ANNUAL_UPDATE_REQUIRED |

Source: academico.unizar.es/acceso-admision-grado/ponder (Anexo I, Acuerdo CG 31/10/2024)

**Key note:** UNIZAR's ponderation structure for Medicine favors Biology and Mathematics II (0.2 each) over Chemistry and Physics (0.1 each). This differs from some other regions (e.g., Andalucía), where all four subjects carry 0.2. Students maximizing their nota de admisión for UNIZAR should prioritize Biology and Mathematics II in specific-phase preparation.

**International students (PCE/UNED):** Students with international qualifications must obtain a Credencial de Acceso through UNED via PCE exams or EU credential recognition. Apply through the Aragón admissions system.

## Admission Process

**Flow 1 — Spanish students (EVAU/PAU):**

1. Complete Bachillerato and pass the EVAU fase general.
2. Optionally sit specific-phase subjects, prioritizing Biology and Mathematics II given UNIZAR's 0.2 coefficients for these subjects.
3. Apply through the UNIZAR/Aragón admissions portal (academico.unizar.es) during the application window.
4. Apply separately to Zaragoza and Huesca campuses if including both as preferences.
5. Await adjudication — ordinary round published in July; further public call-lists through September.
6. Accept the offer and complete enrollment.
7. Complete online registration.

**Flow 2 — International students (PCE/UNED):**

1. Obtain Credencial de Acceso from UNED via PCE exams or EU credential route.
2. Apply through the Aragón admissions system for the international/foreign-student phase.
3. Provide certified and apostilled academic documents.
4. Await adjudication and complete enrollment.

## Admission Timeline

All dates are indicative. Verify at academico.unizar.es annually.

| Event | Approximate Period |
|---|---|
| EVAU ordinaria | June # ANNUAL_UPDATE_REQUIRED |
| EVAU extraordinaria | September # ANNUAL_UPDATE_REQUIRED |
| Application window | Late June # ANNUAL_UPDATE_REQUIRED |
| First adjudication (ordinary round) | July 9–10 # ANNUAL_UPDATE_REQUIRED |
| Last official public call-list | September 15–16 # ANNUAL_UPDATE_REQUIRED |
| Definitive notas published | December # ANNUAL_UPDATE_REQUIRED |
| Personal call-list period | September–October # ANNUAL_UPDATE_REQUIRED |
| Academic year begins | September # ANNUAL_UPDATE_REQUIRED |
| Foreign students deadline | ANNUAL_UPDATE_REQUIRED |

## Admission Score Distribution

UNIZAR publishes three sets of notas de corte each year: Ordinary Round (July), After Last Public Call-list (September), and Definitive (December/end of year).

**Zaragoza campus:**

| Academic Year | Nota de Corte (Definitive) | Round | Source |
|---|---|---|---|
| 2025-2026 | **12.675** | Convocatoria ordinaria | notasdecorte.es / Aragón # ANNUAL_UPDATE_REQUIRED |
| 2024-2025 | **12.738** | Convocatoria ordinaria (definitive Nov 2024) | academico.unizar.es/acceso-admision-grado/corte |
| 2023-2024 | **12.651** | Convocatoria ordinaria (definitive Oct 2023) | academico.unizar.es/acceso-admision-grado/corte |

**Huesca campus:**

| Academic Year | Nota de Corte (Definitive) | Round | Source |
|---|---|---|---|
| 2025-2026 | **12.592** | Convocatoria ordinaria | notasdecorte.es / Aragón # ANNUAL_UPDATE_REQUIRED |
| 2024-2025 | **12.639** | Convocatoria ordinaria (definitive Nov 2024) | academico.unizar.es/acceso-admision-grado/corte |
| 2023-2024 | **12.601** | Convocatoria ordinaria (definitive Oct 2023) | academico.unizar.es/acceso-admision-grado/corte |

**Trend analysis:** UNIZAR Medicine notas de corte have been remarkably stable over the three observed years, ranging from 12.577 to 12.738. The Zaragoza campus consistently runs 0.06–0.10 higher than Huesca. These scores are notably lower than the ~13.5–13.9 range typical of Andalucían faculties, making UNIZAR Medicine a strategically important option for students with strong but not top-decile EVAU performance.

## Costs and Payment Structure

Tuition fees are set by the Aragón regional government and revised annually.

| Cost Item | Approximate Amount | Notes |
|---|---|---|
| Annual tuition (1st enrolment) | ~900.00–1,200.00 EUR/year | ANNUAL_UPDATE_REQUIRED — Aragón Decreto de precios públicos |
| Repeat subject surcharge | Higher rate per credit | ANNUAL_UPDATE_REQUIRED |
| Administrative fees | ~100.00–200.00 EUR | ANNUAL_UPDATE_REQUIRED |
| Monthly living costs (Zaragoza) | ~700.00–1,000.00 EUR | Includes accommodation, food, transport, basics |
| Shared apartment (per room) | ~300.00–500.00 EUR/month | ANNUAL_UPDATE_REQUIRED — Zaragoza market rates |
| University residence | ~600.00–900.00 EUR/month | ANNUAL_UPDATE_REQUIRED |
| Monthly living costs (Huesca) | ~600.00–850.00 EUR | Lower than Zaragoza city |

Zaragoza is a mid-sized Spanish city with moderate living costs — lower than Bilbao or Madrid, broadly comparable to Sevilla, somewhat higher than smaller university cities.

## Scholarships and Financial Aid

| Scholarship | Awarding Body | Criteria | Notes |
|---|---|---|---|
| Beca General MEC | Ministerio de Educación y FP | Income + academic thresholds | Primary national aid — ANNUAL_UPDATE_REQUIRED |
| Aragón Government grants | Gobierno de Aragón | Aragon residency + academic criteria | ANNUAL_UPDATE_REQUIRED |
| UNIZAR institutional grants | Universidad de Zaragoza | Specific academic or social criteria | ANNUAL_UPDATE_REQUIRED |
| Erasmus+ mobility | EU / UNIZAR International Office | Academic standing + language skills | ANNUAL_UPDATE_REQUIRED |
| SENECA national mobility | Ministerio de Educación | National exchange participants | ANNUAL_UPDATE_REQUIRED |

## Accommodation and Cost of Living

- **University residences:** Several options in Zaragoza; approx. 600.00–900.00 EUR/month.
- **Private shared apartments:** Most common; approx. 300.00–500.00 EUR/month per room in Zaragoza; lower in Huesca.
- **UNIZAR housing guidance:** Available through student services and CIU (Centro de Información Universitaria).

## International Exchange and Mobility Programs

| Program | Scope |
|---|---|
| Erasmus+ | European clinical and academic placements; bilateral agreements |
| SICUE | National inter-university exchange within Spain |
| International cooperation practicums | Philippines, Guatemala/Nicaragua (voluntary clinical placements) |
| UNIVERSA | UNIZAR employment and internship platform |
| IFMSA | Student-led international medical exchange |

## MIR Preparation and Professional Outcomes

The Grado en Medicina qualifies graduates to sit the **MIR** national examination for access to medical specialization in Spain.

- **MIR pass rates for UNIZAR graduates:** PENDING_CONFIRMATION — consult ANECA quality reports and UNIZAR quality indicators
- The formal **ECOE** (Evaluación Clínica Objetiva Estructurada) at the end of Year 6 is a distinguishing feature of UNIZAR's program — it validates clinical competency acquisition in a structured format that mirrors post-graduate assessment standards
- Clinical training through Hospital Universitario Miguel Servet (a major tertiary referral centre) and Hospital Clínico Lozano Blesa provides broad clinical caseload exposure

Graduates may pursue MIR specialization, general practice, biomedical research, or international practice within the EU.

## Strategic Fit

### Good Fit For

- Students with nota de admisión in the 12.6–13.4 range for whom UNIZAR Medicine is accessible while Andalucían and other very high-nota faculties are not
- Students who value verified, publicly available nota de corte data for planning purposes — UNIZAR publishes three official nota tables per year
- Students interested in the ECOE clinical competency assessment as an additional validation of clinical skills
- International students via PCE/UNED who cannot reach the 13.5+ threshold of Andalucían faculties
- Students attracted to Zaragoza's central Iberian location (equidistant between Madrid, Barcelona, Bilbao, and Valencia)

### Less Suitable For

- Students whose nota de admisión falls below approximately 12.6 (the Huesca minimum)
- Students requiring instruction in a language other than Spanish
- Students seeking the highest-prestige national ranking for their faculty

## Risks and Considerations

1. **Nota de corte volatility:** While UNIZAR's notas have been relatively stable (12.6–12.8), year-to-year fluctuation remains possible if seat counts change or applicant volumes shift.
2. **New plan implementation:** The Plan 2024 is being introduced progressively — students entering in 2026-27 will be the third cohort under the new plan; some year-specific information may not yet be fully established.
3. **Huesca vs. Zaragoza distinction:** The two campuses have separate notas de corte; students should apply to both if strategically feasible.
4. **PCE/UNED pathway:** International students must follow the Aragón admissions calendar for foreign students.
5. **Extraordinary admission procedure 2025-26:** UNIZAR issued an extraordinary admission procedure for Medicine in 2025-26 under a Ministry of Health subsidy for increasing Medicine seats (RD 901/2025). Students should monitor seat counts at academico.unizar.es for 2026-27 to determine whether an expanded seat count persists.

## Important Notes

- Official nota de corte data: [academico.unizar.es/acceso-admision-grado/corte](https://academico.unizar.es/acceso-admision-grado/corte)
- Official ponderation coefficients: [academico.unizar.es/acceso-admision-grado/ponder](https://academico.unizar.es/acceso-admision-grado/ponder)
- Facultad de Medicina Zaragoza: medicina.unizar.es
- Plan de Estudios 2024 documentation: available at medicina.unizar.es/plan-de-estudios-del-grado-en-medicina
- An extraordinary admission procedure was activated for 2025-26 under RD 901/2025 (Ministry of Health subsidy for Medicine seat expansion); verify 2026-27 seat counts at academico.unizar.es

## Key Insight

UNIZAR Medicine is a strategically significant option for students whose nota de admisión falls in the 12.6–13.4 range — the band where Andalucían faculties are typically out of reach but a strong public Spanish medicine degree remains accessible. Its published three-stage nota de corte data is among the most transparent in Spain, enabling precise annual benchmarking. The ECOE at the end of Year 6 adds a formal clinical competency validation layer that distinguishes the program.

## Final Takeaway

UNIZAR Medicine offers a high-quality, nationally recognized public medicine degree at a nota de corte consistently 0.7–1.2 points below the most competitive Andalucían faculties, making it the strategically important "next tier" option for students with solid but not maximum EVAU performance. Students should apply to both Zaragoza and Huesca campuses to maximize admission probability. The ponderation structure (Biology 0.2, Mathematics II 0.2; Chemistry 0.1, Physics 0.1) differs from Andalucía and should shape specific-phase subject selection for students targeting UNIZAR.

## Frequently Asked Questions

**Q: How is the nota de admisión calculated for UNIZAR Medicine?**
A: Nota de admisión = 0.6 × Bachillerato average + 0.4 × EVAU fase general + up to 2 specific-phase subjects × ponderation coefficient. For UNIZAR Medicine: Biology 0.2, Chemistry 0.1, Physics 0.1, Mathematics II 0.2 (source: Acuerdo CG 31/10/2024 — ANNUAL_UPDATE_REQUIRED). Maximum: 14.0000. No additional exam or interview.

**Q: What are the verified nota de corte values for UNIZAR Medicine?**
A: Zaragoza campus: 12.675 (2025-26, source: notasdecorte.es / Aragón), 12.738 (2024-25, definitive), 12.651 (2023-24, definitive). Huesca campus: 12.592 (2025-26, source: notasdecorte.es / Aragón), 12.639 (2024-25), 12.601 (2023-24). All ANNUAL_UPDATE_REQUIRED — verify at academico.unizar.es/acceso-admision-grado/corte.

**Q: What is the difference between the Zaragoza and Huesca campuses?**
A: Both campuses deliver the same UNIZAR Grado en Medicina and award an identical degree. Zaragoza is the main campus with a larger teaching hospital network; Huesca is a smaller secondary campus. The Zaragoza nota de corte is consistently 0.06–0.10 higher than Huesca. Students should include both as preferences if competitive for one or the other.

**Q: Can international students (PCE/UNED) apply to UNIZAR Medicine?**
A: Yes. Students must obtain a Credencial de Acceso through UNED (via PCE exams or EU credential recognition) and apply through the Aragón admissions system for the foreign-student phase.

**Q: What is the annual tuition fee?**
A: Approximately 900.00–1,200.00 EUR per year for first-enrolment students (subject to annual revision by the Aragón Government).

**Q: Why does UNIZAR's nota de corte appear lower than Andalucía faculties?**
A: Nota de corte values are region-specific and depend on the applicant pool within each region's admissions system. UNIZAR draws predominantly from Aragón and neighboring regions, while Andalucían faculties draw from a much larger regional pool. This does not reflect a difference in program quality. Students from outside Aragón who are strong but not exceptional EVAU performers may find UNIZAR Medicine accessible when Andalucían faculties are not.
