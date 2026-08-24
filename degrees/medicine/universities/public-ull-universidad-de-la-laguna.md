---
id: ull

type: university
subtype: public

name: Universidad de La Laguna
short_name: ULL

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: La Laguna (Tenerife)
  region: Canarias
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - high_competitiveness
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
  seats: 130 # ANNUAL_UPDATE_REQUIRED — increased from 110 in 2024-25
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
    - intake_year: 2024-2025
      round: convocatoria_ordinaria
      score: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: 130 seats offered in 2024-25 following a 20-seat increase
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
  - id: ull-medicina
    campus: Facultad de Ciencias de la Salud — Campus de Ofra, La Laguna (Tenerife)
    modality: standard
    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - high_competitiveness
      - strong_clinical_exposure
    teaching_languages:
      - Spanish
    regional_language_possible: false
    regional_language: NULL
    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL
    seats: 130 # ANNUAL_UPDATE_REQUIRED
    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 130 # ANNUAL_UPDATE_REQUIRED
      applicants_per_seat: PENDING_CONFIRMATION
      last_admitted_scores:
        - intake_year: 2024-2025
          round: convocatoria_ordinaria
          score: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
          score_type: nota_de_admision
          notes: 130 seats offered in 2024-25
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
        - intake_year: 2024-2025
          score: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: EBAU Canarias / ULL Preinscripción
        - intake_year: 2023-2024
          score: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: EBAU Canarias / ULL Preinscripción
        - intake_year: 2022-2023
          score: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: EBAU Canarias / ULL Preinscripción
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
              notes: 40% of the nota de admisión. Maximum combined base score with Bachillerato: 10.0000. In Canarias, the exam is called EBAU.
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

# Universidad de La Laguna

## Overview

The Universidad de La Laguna (ULL) is the principal public university of the Canary Islands, located in the municipality of La Laguna on the island of Tenerife. Founded in 1792, it is one of Spain's oldest universities. Its Facultad de Ciencias de la Salud hosts the Grado en Medicina, a six-year, 360-ECTS programme delivered in Spanish.

Admission to Medicine at ULL is governed by the nota de admisión formula (EBAU in the Canary Islands), with no proprietary exam or interview. The Canary Islands operate a distinct regional admissions system with a **cupo de residentes canarios** (quota for Canarian residents), which significantly affects access dynamics for non-Canarian applicants, including students from mainland Spain and international candidates.

In the 2024-25 academic year, ULL increased the number of Medicine seats from 110 to 130 — a 20-seat expansion — responding to healthcare workforce demand projections. Medicine and Psychology were reported as the most sought-after degrees at ULL for the 2024-25 intake. The degree is recognised under EU Directive 2005/36/EC.

## Quick Evaluation

- Admission model: nota de admisión (EBAU formula) — no proprietary exam, no interview
- Seats: 130 per year as of 2024-25 (ANNUAL_UPDATE_REQUIRED — increased from 110)
- Nota de corte: PENDING_CONFIRMATION (very high, consistent with other Spanish public Medicine programmes)
- Competitiveness level: very high
- Tuition: set by Gobierno de Canarias (ANNUAL_UPDATE_REQUIRED)
- Teaching language: Spanish
- WFME accreditation: PENDING_CONFIRMATION
- EU Directive qualification: Yes
- Canarian residency quota: Yes — significantly limits non-Canarian applicant access
- International access: via PCE/UNED or Credencial UE; subject to quota restrictions
- Location: La Laguna, Tenerife (island location — requires travel from mainland Spain)

## Key Facts

| Feature | Detail |
|---|---|
| University | Universidad de La Laguna (ULL) |
| City | La Laguna, Tenerife, Canarias |
| Degree | Grado en Medicina |
| Duration | 6 years |
| ECTS | 360 |
| Annual seats | 130 (ANNUAL_UPDATE_REQUIRED; increased from 110 in 2024-25) |
| Nota de corte 2024-25 | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2023-24 | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2022-23 | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Tuition (approx.) | ANNUAL_UPDATE_REQUIRED — Gobierno de Canarias |
| Teaching language | Spanish |
| Admission route | Nota de admisión (EBAU formula) |
| Proprietary exam | No |
| Interview | No |
| Canarian residency quota | Yes — cupo de residentes canarios applies |
| Admissions system | EBAU / ULL Preinscripción — Canary Islands |

## Program Options

ULL offers a single Medicine programme — the Grado en Medicina — delivered in Spanish at the Facultad de Ciencias de la Salud on the La Laguna campus in Tenerife. There is no bilingual track, no distance-learning option, and no parallel programme.

The admissions process in the Canary Islands is differentiated by residency status. A significant portion of the 130 available seats is reserved for students who meet the requirements of the **cupo de residentes canarios** (Canarian resident quota). Non-Canarian applicants compete for the remaining general seats, which are substantially fewer. International students must verify their quota category prior to applying.

## Program Structure

The Grado en Medicina at ULL is a 6-year (360 ECTS), fully in-person programme:

- **Teaching type:** Presencial (in-person)
- **Total ECTS:** 360
- **Duration:** 6 academic years

The programme covers the full spectrum of medical education required under EU Directive 2005/36/EC: basic biomedical sciences (Years 1–2), clinical sciences and rotations (Years 3–5), and a full clinical rotation year (Year 6). The Facultad de Ciencias de la Salud hosts Medicine alongside other health science degrees.

A Trabajo Fin de Grado (TFG) is completed in the final year. Prácticas externas (clinical placements) are integrated progressively, with the rotatorio clínico in Year 6 being the primary supervised clinical experience.

The degree also offers provision for EBAU access, access for students aged over 25, 40, and 45, and pathways for international students and students transferring from other Spanish universities (simultaneidad de estudios).

## Teaching Methodology

ULL's Medicine programme follows the standard Spanish public medical school approach: lecture-based foundational science instruction in Years 1–2, with clinical disciplines integrated from Year 3. Skills laboratories and simulation resources are available within the Facultad de Ciencias de la Salud.

Clinical teaching is integrated through progressively increasing hospital placements from Year 3, with the rotatorio clínico in Year 6 constituting the full clinical training phase. The island context means that all clinical training occurs within the Tenerife hospital network — students do not rotate to mainland Spain.

The profile of incoming students at ULL emphasises foundational sciences preparation (Biology, Chemistry, Physics, Mathematics) as well as communication skills, teamwork, and research aptitude.

## Clinical Training

Clinical training at ULL is conducted within Tenerife's public hospital network:

- **Hospital Universitario de Canarias** (La Laguna, Tenerife) — primary teaching hospital; major tertiary care centre serving the western Canary Islands
- **Hospital Universitario Nuestra Señora de Candelaria** (Santa Cruz de Tenerife) — secondary teaching hospital; large public hospital
- **Primary care centres (Centros de Salud)** across Tenerife — used for family medicine and community health rotations

The rotatorio clínico covers surgery and its specialties, obstetrics and gynaecology, paediatrics, psychiatry, family and community medicine, and emergency medicine. All clinical placements are in Tenerife. Students with plans to train or eventually practice in mainland Spain will likely sit the MIR and, if successful, be assigned to a mainland hospital for their residency, which involves relocation.

## International Recognition and Opportunities

The Grado en Medicina at ULL is an official Spanish state degree recognised under European Medical Directive 2005/36/EC, providing automatic professional recognition across all EU and EEA member states.

WFME (World Federation for Medical Education) accreditation: PENDING_CONFIRMATION.

ULL participates in the **Erasmus+** programme and the **Programa SENECA** for domestic Spanish mobility. The institution's international mobility programme (Programas de Movilidad) includes options for Medicine students, though availability of specific Medicine-eligible Erasmus destinations must be confirmed with the Facultad de Ciencias de la Salud annually (ANNUAL_UPDATE_REQUIRED).

The ULL degree is taught and recognised in Spanish and covers all EU-mandated medical competencies.

## Admission Model

Admission to Medicine at ULL is governed by the **EBAU (Evaluación del Bachillerato para el Acceso a la Universidad)** — the Canarian equivalent of the EVAU — and coordinated through ULL's preinscripción system.

**The nota de admisión formula:**

```
Nota de admisión = (0.6 × Nota media Bachillerato) + (0.4 × EBAU general phase grade)
                 + (best 2 specific-phase subjects × ponderation coefficient)
```

- Base score maximum: 10.0000 points
- Specific-phase bonus maximum: 4.0000 additional points
- Absolute maximum nota de admisión: 14.0000

**Subject ponderation coefficients at ULL for Medicine (ANNUAL_UPDATE_REQUIRED):**

| Subject | Coefficient |
|---|---|
| Biology (Biología) | 0.2 |
| Chemistry (Química) | 0.2 |
| Physics (Física) | 0.1 |
| Mathematics II | 0.1 |

**Critical admission factor — Cupo de residentes canarios:**

The Canary Islands apply a **regional residency quota** that reserves a substantial share of university seats for students who are legal residents of the Canary Islands. This quota operates as follows:

- **Canarian residents** compete for the general seat pool plus the residency quota seats — effectively having access to the majority of available places.
- **Non-Canarian Spanish students** compete only for the general (non-quota) seats — a significantly smaller portion of the 130 total places.
- **International students** must verify their quota category based on their residency status in the Canary Islands.

Non-Canarian applicants and international students should verify their exact quota category before applying, as competition for the general (non-quota) seats is structurally more intense and may result in a higher effective nota de corte for non-residents compared to Canarian residents.

**International students (PCE/UNED pathway):** International candidates access ULL through PCE/UNED, generating a Credencial UNED as the nota de admisión equivalent. The same ponderation coefficients apply. International students must verify their quota status: those not legally resident in the Canary Islands compete in the general seat pool.

## Admission Process

### For Spanish EVAU/EBAU Candidates

1. Complete Bachillerato and sit the EBAU in the Canary Islands (or EVAU in any other Spanish region).
2. Sit the specific phase — prioritise Biology and Chemistry.
3. Calculate your nota de admisión using ULL's ponderation coefficients.
4. Determine your quota category (Canarian resident vs. general).
5. Apply through ULL's preinscripción portal during the official application window (ANNUAL_UPDATE_REQUIRED).
6. Await provisional and definitive assignment. Confirm enrolment within the stated deadline.

### For International Students (PCE/UNED Pathway)

1. Verify eligibility for PCE/UNED access.
2. Sit the PCE examinations with UNED (typically May–June — ANNUAL_UPDATE_REQUIRED).
3. Obtain the Credencial UNED as the nota de admisión equivalent.
4. **Determine quota status:** International students not residing in the Canary Islands compete for general (non-quota) seats, which are fewer in number.
5. Apply through ULL's preinscripción portal.
6. If admitted, arrange student visa (non-EU applicants) and complete enrolment.

## Admission Timeline

All dates are ANNUAL_UPDATE_REQUIRED.

| Phase | Approximate timing |
|---|---|
| EBAU (ordinary call — Canarias) | June (ANNUAL_UPDATE_REQUIRED) |
| EBAU (extraordinary call) | July (ANNUAL_UPDATE_REQUIRED) |
| ULL preinscripción window opens | Mid-June (ANNUAL_UPDATE_REQUIRED) |
| Provisional assignment | Late June / early July (ANNUAL_UPDATE_REQUIRED) |
| Definitive assignment | July (ANNUAL_UPDATE_REQUIRED) |
| Enrolment formalisation | July–September (ANNUAL_UPDATE_REQUIRED) |
| PCE/UNED examinations | May–June (ANNUAL_UPDATE_REQUIRED) |
| Academic year begins | September (ANNUAL_UPDATE_REQUIRED) |

## Admission Score Distribution

Nota de corte data for ULL Medicine:

| Intake year | Nota de corte | Round | Notes |
|---|---|---|---|
| 2024-2025 | PENDING_CONFIRMATION | Convocatoria ordinaria | 130 seats (20-seat increase from prior year) |
| 2023-2024 | PENDING_CONFIRMATION | Convocatoria ordinaria | ~110 seats |
| 2022-2023 | PENDING_CONFIRMATION | Convocatoria ordinaria | ~110 seats |

Source: EBAU Canarias / ULL Preinscripción (ANNUAL_UPDATE_REQUIRED)

**Strategic interpretation:**

The 20-seat increase to 130 in 2024-25 may have slightly moderated competitive pressure compared to prior years. However, the nota de corte for Medicine in the Canary Islands has historically been very high — consistent with the national range of 13.5–13.9 for public Medicine programmes. The expansion of seats may produce a marginal reduction in the nota de corte, but this effect depends on changes in the total applicant pool.

The **cupo de residentes canarios** is the most strategically significant factor for non-Canarian candidates. The effective nota de corte for general-pool seats (accessible to non-residents and most international students) may be higher than the overall published nota de corte, since general seats are a subset of total capacity.

Nota de corte data is published by ULL's admissions system (acceso.ull.es) and the Canarian education authorities annually (ANNUAL_UPDATE_REQUIRED).

## Costs and Payment Structure

Tuition fees at ULL are set annually by the Gobierno de Canarias. The Canary Islands historically maintain one of the lowest public university tuition rates in Spain.

| Cost concept | Canarian resident | Non-resident / EU | Source |
|---|---|---|---|
| Annual tuition (approx.) | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | Gobierno de Canarias |
| Enrolment and administrative fees | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | ULL |
| Compulsory services | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | ULL |
| Student union fee | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | ULL |

Tuition fees in the Canary Islands benefit from regional bonuses. Canarian residents typically pay below-national-average rates. Non-residents pay higher rates, but still within the public university range. Exact figures must be confirmed annually via the Gobierno de Canarias decree (ANNUAL_UPDATE_REQUIRED).

## Scholarships and Financial Aid

**Beca General MEC:**
ULL students are eligible for the national Beca General from the Ministerio de Educación y Formación Profesional. Applications open annually in July (ANNUAL_UPDATE_REQUIRED) via the MEC portal.

**Becas del Gobierno de Canarias:**
The Canarian regional government offers supplementary scholarships for transport (including inter-island travel), housing, and academic merit. These are particularly relevant given the island geography, which can add transport costs for non-Tenerife Canarian students.

**ULL own grants:**
The university provides emergency support grants and academic performance recognition. Availability is ANNUAL_UPDATE_REQUIRED.

**Erasmus+ mobility:**
Students may access Erasmus+ funding for confirmed outgoing mobility placements. Availability for Medicine-specific placements must be confirmed annually.

## Accommodation and Cost of Living

La Laguna is a UNESCO World Heritage city adjacent to Santa Cruz de Tenerife, the island's capital. Living costs in Tenerife are moderate by Spanish standards but include specific island-related costs (inter-island travel, imported goods).

| Cost concept | Estimated monthly range | Notes |
|---|---|---|
| University halls of residence (colegios mayores) | ANNUAL_UPDATE_REQUIRED | Limited capacity |
| Private shared flat (piso compartido) | ~350–550 EUR/room (ANNUAL_UPDATE_REQUIRED) | Most common student option |
| Private studio | ~550–800 EUR (ANNUAL_UPDATE_REQUIRED) | |
| University canteen meals | ~3–6 EUR/meal (ANNUAL_UPDATE_REQUIRED) | |
| Monthly public transport (Tenerife) | ANNUAL_UPDATE_REQUIRED | Tram/bus network available |
| Flights to mainland Spain | ANNUAL_UPDATE_REQUIRED | Variable; budget for trips home |
| Total estimated monthly living cost | ~750–1,150 EUR (ANNUAL_UPDATE_REQUIRED) | Highly variable |

Travel from mainland Spain to Tenerife requires flights (approximately 2–3 hours from most Spanish cities). Students from mainland Spain should budget for travel costs to return home during academic breaks.

## International Exchange and Mobility Programs

ULL participates in **Erasmus+** and the **Programa SENECA** for national student mobility. Medicine-specific Erasmus mobility destinations must be confirmed with the Facultad de Ciencias de la Salud's international office annually (ANNUAL_UPDATE_REQUIRED).

The island location means outgoing mobility placements function differently from mainland universities — students who accept mobility placements move from an island context to mainland European universities, which may involve additional logistical planning.

Year 6's rotatorio clínico structure limits mobility to Years 3–5. Students interested in international exchange should plan placements accordingly.

## MIR Preparation and Professional Outcomes

All ULL Medicine graduates are eligible for the **MIR (Médico Interno Residente)** national examination.

MIR pass rates specific to ULL graduates: PENDING_CONFIRMATION.

The clinical training network in Tenerife — anchored at Hospital Universitario de Canarias and Hospital Universitario Nuestra Señora de Candelaria — provides comprehensive tertiary care experience. However, students who ultimately wish to specialise or practice in mainland Spain will sit the MIR and, if successful, may be assigned to a mainland hospital for their residency, which involves relocation.

Post-MIR, graduates may practise anywhere in Spain's Sistema Nacional de Salud or seek employment in private medicine, research, or public health.

## Strategic Fit

### Good Fit For

- Canarian residents (or students with established legal residency in the Canary Islands) — the cupo de residentes gives structural advantage in seat allocation.
- Candidates with a strong nota de admisión who want a publicly funded Medicine degree in a unique Atlantic island location.
- International students who are already legally resident in the Canary Islands and qualify for the residency quota.
- Students attracted to an island lifestyle in Tenerife and comfortable with island-based clinical training.
- Candidates seeking very low public university tuition fees (Canarian residents benefit from particularly favourable rates).

### Less Suitable For

- Non-Canarian Spanish students whose nota de admisión does not significantly exceed the historical nota de corte — competition for general-pool seats is structurally harder.
- International students not resident in the Canary Islands, who compete only for general-pool seats and face a higher effective nota de corte threshold.
- Students who anticipate frequent travel to mainland Spain and for whom island isolation is a significant concern.
- Candidates who require a bilingual or English-medium track.
- Students who want clinical exposure in a major mainland Spanish city or hospital network.

## Risks and Considerations

**Cupo de residentes canarios:** The regional residency quota is the most critical access risk for non-Canarian applicants. Non-resident students — including most international students applying via PCE/UNED — compete for a significantly smaller pool of general seats. This effectively raises the competitive bar for non-residents above the published nota de corte. International students must verify their exact quota classification before applying.

**Seat count change:** The increase from 110 to 130 seats in 2024-25 represents a structural change. The impact on the nota de corte for subsequent cycles is uncertain until admissions data for 2024-25 is published.

**Island-specific logistical costs:** Students from mainland Spain or internationally face recurring travel costs (flights) that are absent at mainland universities. This should be factored into total study cost calculations.

**Nota de corte uncertainty:** The nota de corte for ULL Medicine is currently PENDING_CONFIRMATION in the most recent published sources. Candidates should consult the ULL admissions portal (acceso.ull.es) for updated figures.

**Rotatorio constraint on mobility:** Year 6 clinical rotations in Tenerife prevent international mobility in the final year. Students must plan Erasmus or other exchange programmes for Years 3–5.

## Important Notes

- The cupo de residentes canarios applies and materially affects seat access for non-Canarian applicants. Verify quota status before applying.
- Seat count: 130 as of 2024-25, increased from 110 (ANNUAL_UPDATE_REQUIRED).
- All nota de corte data is PENDING_CONFIRMATION and ANNUAL_UPDATE_REQUIRED — consult acceso.ull.es.
- Tuition fees are set by the Gobierno de Canarias and are ANNUAL_UPDATE_REQUIRED.
- Ponderation coefficients are published annually by the Canarian education authorities.
- Facultad de Ciencias de la Salud: C/ Sta. María Soledad, s/n, 38200 La Laguna | fcsalud@ull.es | +34 922 31 92 77

## Key Insight

ULL Medicine's defining strategic variable for non-Canarian and international candidates is the cupo de residentes canarios. This quota system means that the effective nota de corte for the general-pool seats accessible to non-residents may be meaningfully higher than the published overall nota de corte. Candidates considering ULL from outside the Canary Islands should treat this as a first-order strategic constraint, not a footnote. The programme is genuinely competitive even for Canarian residents — for non-residents and international applicants, the combination of quota restriction and high demand makes ULL Medicine one of the more difficult public programmes to access in Spain.

## Final Takeaway

The Grado en Medicina at the Universidad de La Laguna is a well-established, EU-Directive-recognised, publicly funded six-year programme on the island of Tenerife. The 2024-25 expansion to 130 seats reflects growing recognition of healthcare workforce needs in the archipelago. The cupo de residentes canarios is a structural feature of Canarian public university admissions that non-Canarian applicants must understand and factor into their strategy. International students not resident in the Canary Islands compete for a limited subset of seats. For Canarian residents with a high nota de admisión and a preference for island-based study and clinical training, ULL remains the primary and most accessible public Medicine option in the western Canary Islands.

## Frequently Asked Questions

**How is the nota de admisión calculated at ULL?**
Nota de admisión = 0.6 × Bachillerato average + 0.4 × EBAU general phase grade + bonuses from up to 2 specific-phase subjects. In the Canary Islands, the EVAU is called EBAU. Biology and Chemistry carry a 0.2 coefficient each, enabling a maximum bonus of 4.0 points and a theoretical maximum nota of 14.0000.

**What is the nota de corte for Medicine at ULL?**
PENDING_CONFIRMATION for recent cycles. The seat count increased to 130 in 2024-25. Historical nota de corte is expected to be in the 13.5–13.9 range, consistent with other Spanish public Medicine programmes. Verify at acceso.ull.es (ANNUAL_UPDATE_REQUIRED).

**What is the cupo de residentes canarios?**
The Canary Islands reserve a quota of university seats for legal residents of the archipelago. Non-Canarian students (from mainland Spain or abroad) compete only for the remaining general seats, which are fewer in number. This effectively creates a higher competitive threshold for non-residents.

**Can international students apply via PCE?**
Yes. PCE/UNED generates a Credencial UNED usable in ULL's preinscripción. However, international students not residing in the Canary Islands compete for general-pool (non-quota) seats, which are a smaller share of the 130 total places.

**How many seats does ULL Medicine have?**
130 as of 2024-25 (increased from 110). ANNUAL_UPDATE_REQUIRED.

**What are the tuition fees?**
Set by the Gobierno de Canarias annually. Canarian residents benefit from particularly low rates. Exact figures are ANNUAL_UPDATE_REQUIRED.

**When do I apply?**
Through ULL's preinscripción portal after the EBAU ordinary call in June. Exact dates are ANNUAL_UPDATE_REQUIRED.

**What hospitals are used for clinical training?**
Hospital Universitario de Canarias (La Laguna) and Hospital Universitario Nuestra Señora de Candelaria (Santa Cruz de Tenerife), plus primary care centres across Tenerife.

**Is there a bilingual track?**
No. The degree is delivered entirely in Spanish.

**What is the MIR?**
The MIR (Médico Interno Residente) is the national exam granting access to specialist training in Spain's public health system. All ULL Medicine graduates are eligible. MIR pass rates for ULL graduates are PENDING_CONFIRMATION.
