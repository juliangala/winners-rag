---
id: ule

type: university
subtype: public

name: Universidad de León
short_name: ULE

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: León
  region: Castilla y León
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - new_programme_unverified

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
  level: PENDING_CONFIRMATION # No nota de corte data available — programme is new

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
    - intake_year: 2025-2026
      round: convocatoria_ordinaria
      score: PENDING_CONFIRMATION # No data on notasdecorte.es — programme is new
      score_type: nota_de_admision
      notes: "Source: notasdecorte.es shows no data (shown as '...') — programme may not have completed a full admissions cycle"
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
  - id: ule-medicina
    campus: Facultad de Medicina de León, Campus de Vegazana, León
    modality: standard
    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - new_programme_unverified
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
          score: PENDING_CONFIRMATION
          score_type: nota_de_admision
          notes: "notasdecorte.es shows no data — programme is new or cycle incomplete"
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
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: "notasdecorte.es — no data available / Castilla y León admissions system"
        - intake_year: 2024-2025
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: "Castilla y León — ANNUAL_UPDATE_REQUIRED"
        - intake_year: 2023-2024
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: "Castilla y León — ANNUAL_UPDATE_REQUIRED"
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
              notes: 40% of the nota de admisión. Max base 10.0000.
            - component: evau_specific_phase_bonus
              enabled: true
              role: bonus_only
              maximum_bonus: 4.0
              grade_source: evau_fase_especifica
              notes: Best 2 eligible subjects × coefficient. Max nota 14.0000. Coefficients ANNUAL_UPDATE_REQUIRED — verify at ule.es or the Castilla y León admissions portal.
              subject_ponderations:
                Biology:        ANNUAL_UPDATE_REQUIRED
                Chemistry:      ANNUAL_UPDATE_REQUIRED
                Physics:        ANNUAL_UPDATE_REQUIRED
                Mathematics_II: ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---
# Universidad de León (ULE) — Grado en Medicina

## Overview

The Universidad de León (ULE) is a public university located in León, in the autonomous community of Castilla y León. The Grado en Medicina at ULE is a recent addition to the Spanish public Medicine landscape — the programme appears to have commenced in 2024-2025 or 2025-2026 and has not yet completed a full admissions cycle with published nota de corte data. As of May 2026, notasdecorte.es shows no score data for ULE Medicine (displayed as "..."), indicating the programme is either in its inaugural intake or has not yet published official results. This file is a structured placeholder — it should be updated as data becomes available. ULE is a comprehensive teaching university with established faculties across sciences, humanities, engineering, and health. The main campus is located at Campus de Vegazana on the outskirts of the city. The clinical training base is expected to be the Complejo Asistencial Universitario de León (CAULE), the primary hospital network of León province.

**Important for WinnersEducation.ai users:** ULE Medicine is flagged as an unproven new programme. No nota de corte, seat count, or MIR outcome data is currently available. This file is maintained for tracking purposes and should not be used to build application strategies until verified data is published.

## Quick Evaluation

| Feature | Detail |
|---|---|
| Seats (plazas) | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2025-26 | PENDING_CONFIRMATION — no data on notasdecorte.es |
| Teaching language(s) | Spanish |
| Annual tuition (approx.) | PENDING_CONFIRMATION — set by Junta de Castilla y León |
| Admission model | Nota de admisión (EVAU-based) — no proprietary exam, no interview |
| Clinical exposure | PENDING_CONFIRMATION — likely CAULE (Complejo Asistencial Universitario de León) |
| ECTS | 360 |
| Duration | 6 years |
| Programme maturity | New — no track record available |

## Key Facts

| Field | Value |
|---|---|
| Degree | Grado en Medicina |
| Campus | Campus de Vegazana, León (PENDING_CONFIRMATION) |
| Seats (plazas ofertadas) | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Tuition per year | PENDING_CONFIRMATION — Castilla y León public rates |
| Admission model | Score-based (nota de admisión) |
| Proprietary exam | No |
| Interview | No |
| Teaching language | Spanish |
| Regional health system | SACYL (Sanidad de Castilla y León) |
| Clinical hospital | CAULE — Complejo Asistencial Universitario de León (PENDING_CONFIRMATION) |
| Admissions contact | PENDING_CONFIRMATION — ule.es |
| Programme status | New — no published nota de corte |

## Program Options

ULE offers a single Grado en Medicina programme at its main León campus. The programme is taught entirely in Spanish. There is no bilingual track, no English-medium option, and no co-official regional language requirement (Castilla y León is Spanish-speaking, though Bable/Asturleonés is spoken in some areas with no academic implications). As a new programme, the full curriculum, elective structure, and specific module distribution are PENDING_CONFIRMATION from the official ULE Faculty of Medicine programme guide. International students applying via PCE/UNED would apply under the standard Castilla y León admissions framework.

## Program Structure

The Grado en Medicina at ULE is expected to follow the national curriculum framework established by Orden ECI/332/2008, structured across six years with 360 ECTS. As a new programme, the specific module allocation and year-by-year structure are PENDING_CONFIRMATION from official ULE documentation.

Expected general structure (consistent with national framework — verify at ule.es):

- **Years 1–2 (Biomedical sciences foundation):** Anatomy, physiology, biochemistry, histology, cell biology, genetics, microbiology, immunology, public health, epidemiology, medical ethics, biostatistics, and clinical communication. Laboratory practicals from year 1.
- **Years 3–4 (Clinical sciences):** Pathology, pharmacology, radiology, internal medicine, surgery, gynaecology and obstetrics, paediatrics, psychiatry, neurology, dermatology, ENT, and ophthalmology. Hospital contact begins in year 3.
- **Years 5–6 (Clinical rotations):** Full clinical rotations across all major specialties at CAULE and affiliated SACYL facilities. Year 6 is dedicated to supervised clinical rotations. TFG completed in final year.
- **Electives:** PENDING_CONFIRMATION.

Full ECTS distribution should be verified at ule.es when available.

## Teaching Methodology

As a new programme, detailed information on ULE Medicine's teaching methodology is PENDING_CONFIRMATION. It is expected to follow the standard Spanish medical education model: lectures, laboratory practicals, seminars, clinical case-based learning, and progressive hospital integration from year 3. ULE has established teaching infrastructure in other health sciences disciplines (nursing, veterinary medicine, biology), which provides some pedagogical foundation. The inaugural cohort's experience with faculty development, infrastructure readiness, and clinical coordination at CAULE will be a key indicator of programme quality — data on this will emerge over the 2025-2027 period.

## Clinical Training

Clinical training at ULE Medicine is expected to be delivered through the SACYL (Sanidad de Castilla y León) network in León province:

- **Complejo Asistencial Universitario de León (CAULE):** The primary hospital complex of León, comprising several merged hospital facilities and serving as the tertiary referral centre for the province and surrounding area. CAULE is expected to be the main clinical training hospital for ULE Medicine (PENDING_CONFIRMATION — formal affiliation agreement status to be verified at ule.es).
- **Secondary and primary care facilities:** SACYL-managed centres across León province are expected to provide complementary training in community medicine, family medicine, and outpatient settings.
- **Clinical infrastructure maturity risk:** As a new programme, the formal clinical affiliation agreements between ULE and CAULE may still be in development. The adequacy of clinical training delivery in the first one to two cohorts is an open question that should be monitored.

## International Recognition and Opportunities

Upon successful ANECA verification and RUCT registration, the Grado en Medicina awarded by ULE will carry the same professional recognition as all other verified Spanish Medicine degrees: automatic EEA-wide recognition under EU Directive 2005/36/EC and eligibility for the MIR examination. As a new programme, Erasmus+ bilateral agreements specific to Medicine may be limited in the early years. SICUE domestic mobility is available in principle. The programme's ANECA verification status should be confirmed at ule.es before application.

## Admission Model

ULE Medicine admission is governed by the **nota de admisión**, standard across Spanish public universities:

```
Nota de admisión = 0.6 × Nota media Bachillerato
                 + 0.4 × EVAU general phase score
                 + best 2 specific-phase subjects × ponderation coefficient
```

- **Maximum base score:** 10.0000
- **Maximum nota de admisión (with specific-phase bonus):** 14.0000
- **No proprietary exam, no interview, no English test**

Specific-phase ponderation coefficients for ULE Medicine: **ANNUAL_UPDATE_REQUIRED** — verify at ule.es or the Castilla y León admissions portal (ubu.es/acceso or equivalent system).

Admission in Castilla y León is managed through the regional university admissions system. Candidates rank their preferred universities and programmes; places are allocated in descending nota de admisión order. ULE Medicine will appear within the Castilla y León admissions portal alongside other CyL public Medicine programmes (e.g., Universidad de Valladolid, Universidad de Burgos, Universidad de Salamanca).

**International students (PCE/UNED route):** International students use PCE/UNED or Credencial UE to construct a nota de admisión equivalent. PCE applicants compete in the general quota. No separately reserved international quota has been identified at ULE Medicine.

## Admission Process

### Spanish PAU (EVAU) students

1. Complete Bachillerato and sit the relevant EVAU (any Spanish regional variant is accepted for CyL admissions — confirm portability at ule.es).
2. Sit specific-phase subjects: Biology and Chemistry carry the highest coefficients for Medicine at most CyL universities — verify ULE's specific coefficients at ule.es (ANNUAL_UPDATE_REQUIRED).
3. Calculate nota de admisión and compare against any available benchmarks for ULE Medicine.
4. Apply through the Castilla y León regional admissions system (portal to be confirmed — ANNUAL_UPDATE_REQUIRED).
5. Places are allocated in descending nota de admisión order.
6. If not admitted in the ordinaria, reapply in the extraordinaria (September).
7. Confirm enrolment within the stated deadline.

### International PCE/UNED students

1. Register with UNED for PCE examinations.
2. Prioritise Biology, Chemistry, and Physics in the PCE subject selection.
3. Sit PCE exams and calculate nota de admisión equivalent.
4. Apply via the Castilla y León admissions system with PCE documentation.
5. Verify whether CAULE affiliation and programme accreditation are fully confirmed before committing to ULE.
6. Complete homologation of secondary education diploma if required.

## Admission Timeline

| Phase | Approximate dates | Notes |
|---|---|---|
| EVAU Castilla y León — ordinaria | June (ANNUAL_UPDATE_REQUIRED) | CyL regional EVAU |
| CyL admissions portal open | Late June / July (ANNUAL_UPDATE_REQUIRED) | PENDING_CONFIRMATION — verify at ule.es |
| Ordinaria results | July (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| Enrolment confirmation | July–August (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| EVAU — extraordinaria | September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| Extraordinaria results | September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| Academic year start | September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| PCE registration (UNED) | January–March (ANNUAL_UPDATE_REQUIRED) | For international applicants |
| PCE exams | May–June / September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |

All timeline data is PENDING_CONFIRMATION and must be verified at ule.es or the CyL admissions portal before application.

## Admission Score Distribution

### Nota de corte history

| Intake year | Round | Nota de corte | Source |
|---|---|---|---|
| 2025-2026 | Convocatoria ordinaria | PENDING_CONFIRMATION | notasdecorte.es — no data shown (programme is new) |
| 2024-2025 | Convocatoria ordinaria | PENDING_CONFIRMATION | PENDING_CONFIRMATION |
| 2023-2024 | Convocatoria ordinaria | PENDING_CONFIRMATION | PENDING_CONFIRMATION |

**Critical note on data absence:** notasdecorte.es displays no score for ULE Medicine as of May 2026 (shown as "..."). This indicates one of the following scenarios:
- The programme launched for the 2025-2026 intake and has not yet published its first nota de corte
- The programme launched for the 2024-2025 intake but data has not yet been submitted to or processed by notasdecorte.es
- The programme is in verification/accreditation phase and admissions have not yet completed

**Trend analysis:** Not possible — no data available.

**Practical implication:** Candidates cannot benchmark their nota de admisión against ULE Medicine without verified nota de corte data. This file will be updated as data becomes available through official ULE channels, the CyL admissions system, or notasdecorte.es.

## Costs and Payment Structure

Public university fees in Castilla y León are set annually by the Junta de Castilla y León by decree. Castilla y León public university fees are typically in the mid-range of Spanish public university costs.

| Fee component | Approximate amount | Notes |
|---|---|---|
| Annual tuition (tasas académicas) | PENDING_CONFIRMATION | Set by Junta de Castilla y León annually |
| Enrolment fee (secretaría) | PENDING_CONFIRMATION | ANNUAL_UPDATE_REQUIRED |
| Academic services fee | PENDING_CONFIRMATION | ANNUAL_UPDATE_REQUIRED |
| Total estimated annual cost | ~900–1,500 EUR | PENDING_CONFIRMATION — CyL rates, verify at ule.es |
| PCE registration (international) | ANNUAL_UPDATE_REQUIRED | Paid to UNED |

Note: Castilla y León public university fees are generally moderate. Exact ULE Medicine fees should be confirmed at ule.es once the programme is fully operational.

## Scholarships and Financial Aid

- **MEC Beca General:** National scholarship for public university students. Applicable to ULE Medicine students meeting residency and income requirements.
- **Becas Junta de Castilla y León:** Regional government scholarships for CyL residents studying at public universities in the region.
- **ULE institutional aid:** ULE may offer institutional grants for enrolled students. Verify at ule.es.
- **ERASMUS+ grants:** Available during mobility periods once the programme is mature enough to have established exchange agreements.
- **International students:** PCE/UNED applicants may be eligible for MEC Beca General under residency and income requirements; in practice, eligibility for most international students is limited.

## Accommodation and Cost of Living

León is a mid-sized Spanish city with a well-established student population (ULE serves approximately 8,000–10,000 students across all faculties). The cost of living is moderate to low.

| Category | Estimated monthly cost | Notes |
|---|---|---|
| University residence (Colegios Mayores ULE) | PENDING_CONFIRMATION | Verify at ule.es |
| Private shared flat (piso compartido) | ~200–380 EUR/month | León is affordable — lower than Madrid or Barcelona |
| Private studio | ~320–500 EUR/month | PENDING_CONFIRMATION |
| Food (self-catering + canteen) | ~180–280 EUR/month | Low to moderate cost of living |
| Transport (local bus) | ~15–30 EUR/month | Compact city — often walkable or cyclable |
| Total monthly estimated budget | ~450–750 EUR | Excluding tuition — favourable cost of living |

León offers a favourable cost of living for students relative to larger Spanish cities. The university campus is reasonably compact. The city has a strong gastronomic culture and established student services infrastructure.

## International Exchange and Mobility Programs

- **Erasmus+:** ULE participates in the Erasmus+ programme across its established faculties. The new Medicine programme's Erasmus+ bilateral agreements are PENDING_CONFIRMATION — verify at ule.es/internacional.
- **SICUE:** Domestic exchange programme available in principle for intra-Spanish mobility.
- **International partnerships:** ULE has existing international academic relationships, primarily in Europe and Latin America, through established faculties. Applicability to the new Medicine programme is PENDING_CONFIRMATION.
- **Note:** As a new programme, international mobility infrastructure for Medicine students may be limited in the first two to three cohorts.

## MIR Preparation and Professional Outcomes

No MIR outcome data is available for ULE Medicine graduates — the programme is too new to have produced graduates. As a standard accredited Spanish Grado en Medicina (subject to ANECA verification), graduates will be eligible to sit the MIR examination. The programme will train graduates for the SACYL regional health system and for national MIR competition. Clinical training quality and MIR preparation outcomes will only become assessable from approximately 2030 onwards (when the first cohort completes the degree). WinnersEducation.ai should track this metric as it becomes available.

## Strategic Fit

### Good Fit For

- Students who are interested in studying Medicine in a smaller, affordable Spanish city with a traditional university atmosphere, and who are comfortable with the uncertainty of a new programme.
- Candidates from Castilla y León who want to remain in the region for their medical studies and are familiar with the local SACYL healthcare system.
- Students who are tracking early-stage opportunities in new public Medicine programmes — if nota de corte data confirms an accessible threshold when published, ULE could offer a realistic entry point into public Medicine.
- Students who want to monitor this programme and apply once data is confirmed — advisors may want to keep ULE on a watchlist rather than an active shortlist.

### Less Suitable For

- Candidates who need certainty about nota de corte, seats, and programme infrastructure before committing — the absence of verified data makes ULE Medicine unsuitable for inclusion in current application strategies.
- International PCE/UNED students who need a confirmed admissions framework and historical benchmarks — ULE Medicine cannot currently provide these.
- Students seeking a programme with a proven MIR preparation track record and established clinical training network.
- Any student whose admission decision timeline does not allow for the uncertainty of a new, unverified programme.

## Risks and Considerations

1. **No nota de corte data — critical gap:** The most significant risk is the complete absence of nota de corte data for ULE Medicine. Without this, no accurate competitive benchmarking is possible. Students cannot assess their realistic chances of admission.
2. **New programme — unproven infrastructure:** ULE Medicine has no track record for curriculum delivery, clinical training quality, MIR preparation, or faculty development. The first cohorts are effectively pioneers, with all associated risks.
3. **Clinical affiliation uncertainty:** The formal clinical affiliation between ULE and CAULE may still be in development. The adequacy and quality of clinical rotations in the programme's first years is an open question.
4. **ANECA verification status:** Candidates should verify that ULE Medicine's ANECA verification is complete and the degree is formally registered in the RUCT before applying. A programme that is not fully accredited cannot award a recognised Grado en Medicina.
5. **Admissions system uncertainty:** The specific CyL admissions portal, timeline, and documentation requirements for ULE Medicine are PENDING_CONFIRMATION. International PCE applicants face additional uncertainty about how their nota de admisión equivalent will be processed.
6. **Limited scholarship and mobility infrastructure:** As a new programme, institutional scholarship support and Erasmus+ agreements specific to Medicine may not yet be fully developed.
7. **Data availability timeline:** It is unlikely that comprehensive nota de corte, seat, and outcome data will be available before the 2026-2027 application cycle at the earliest.

## Important Notes

- ULE Medicine is classified as a new programme — all data in this file is either PENDING_CONFIRMATION or estimated based on comparable CyL public university frameworks.
- The absence of nota de corte data on notasdecorte.es as of May 2026 is a factual observation, not a data error — it reflects the programme's early stage.
- This file must be updated each cycle as ULE publishes official admissions statistics and nota de corte data.
- The ANECA verification and RUCT registration status of ULE Medicine must be confirmed before advising students to apply.
- Advisors should explicitly flag to students that ULE Medicine is on a watchlist basis only until verified data is available.
- Website: PENDING_CONFIRMATION — check ule.es for the Faculty of Medicine section.

## Key Insight

ULE Medicine is an emerging public Medicine programme in León, Castilla y León, with no published nota de corte data as of May 2026. Its existence is significant — it adds a new access point to public Medicine in a region with existing programmes at Valladolid, Salamanca, and Burgos. However, the complete absence of verified data (nota de corte, seat numbers, clinical affiliation status, ANECA verification details) makes it impossible to include in active application strategies at this stage. WinnersEducation.ai should maintain this file as a tracking entry and update it as data becomes available, particularly after the 2025-2026 or 2026-2027 admissions cycle closes and official results are published.

## Final Takeaway

ULE Medicine is a placeholder opportunity — potentially interesting as a new public Medicine entry point in Castilla y León, but currently unverifiable. Advisors should not include ULE Medicine in student application shortlists until nota de corte data, seat numbers, and programme accreditation details are publicly confirmed. The programme's value proposition (affordable city, public university credential, SACYL clinical network) is theoretically sound — but without data, it cannot be responsibly recommended. Check ule.es and notasdecorte.es regularly from mid-2026 onwards for the first confirmed admission statistics.

## Frequently Asked Questions

**Q: Is ULE Medicine a real programme or still being set up?**
A: ULE Medicine appears to be a newly launched programme, likely starting in 2024-2025 or 2025-2026. It is not definitively confirmed whether the programme has yet completed its first full admissions cycle. Verify programme status at ule.es.

**Q: What is the nota de corte for ULE Medicine?**
A: PENDING_CONFIRMATION. notasdecorte.es shows no data for ULE Medicine as of May 2026. No historical nota de corte data is available from any confirmed source.

**Q: Can international students apply via PCE/UNED?**
A: In principle yes, once the programme is fully operational — international students would apply through the Castilla y León admissions system with a PCE/UNED nota de admisión equivalent. However, the specific admissions process for ULE Medicine is PENDING_CONFIRMATION.

**Q: Which hospital is used for clinical training?**
A: The Complejo Asistencial Universitario de León (CAULE) is the expected clinical training hospital (PENDING_CONFIRMATION). The formal affiliation agreement status should be verified at ule.es.

**Q: What are the tuition fees?**
A: PENDING_CONFIRMATION. Fees will be set by the Junta de Castilla y León and are expected to follow CyL public university fee scales. Verify at ule.es once available.

**Q: How does ULE compare to other public Medicine programmes in Castilla y León?**
A: Universidad de Valladolid (UVa), Universidad de Salamanca (USAL), and Universidad de Burgos (UBU) all have established public Medicine programmes in the region with published nota de corte data. ULE Medicine, as a new programme, cannot be comparatively evaluated until its own data is published.

**Q: Should Winners students apply to ULE Medicine?**
A: Not at this stage. ULE Medicine should remain on a watchlist until nota de corte, seat count, and programme accreditation data are confirmed. For the 2026-2027 cycle, advisors should check for updated data before advising students to include ULE in their applications.

**Q: Is there any risk that the programme is not fully accredited?**
A: This is a genuine risk that must be verified. Candidates should confirm that the Grado en Medicina at ULE has completed ANECA verification and is registered in the RUCT before applying. An unaccredited degree cannot be used for MIR access or professional practice.
