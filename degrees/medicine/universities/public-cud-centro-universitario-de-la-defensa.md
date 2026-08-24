---
id: cud

type: university
subtype: public

name: Centro Universitario de la Defensa de Madrid
short_name: CUD Madrid

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
  - restricted_access_military_only
  - not_applicable_civilian_students

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
  exam_required: false # Standard EVAU — military selection process applies additionally
  interview_required: PENDING_CONFIRMATION # Military selection may include aptitude/medical assessment

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
  level: PENDING_CONFIRMATION # Restricted military access makes civilian comparison inapplicable

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED — restricted to military candidates
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
    - intake_year: 2025-2026
      round: convocatoria_ordinaria
      score: 12.379 # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: "Source: notasdecorte.es / Comunidad de Madrid — military access restrictions apply"
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
  - id: cud-medicina
    campus: Centro Universitario de la Defensa de Madrid — Hospital Central de la Defensa Gómez Ulla, Madrid
    modality: standard
    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - restricted_access_military_only
      - not_applicable_civilian_students
    teaching_languages:
      - Spanish
    regional_language_possible: false
    regional_language: NULL
    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL
    seats: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED — military career path only
    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: PENDING_CONFIRMATION
      applicants_per_seat: PENDING_CONFIRMATION
      last_admitted_scores:
        - intake_year: 2025-2026
          round: convocatoria_ordinaria
          score: 12.379 # ANNUAL_UPDATE_REQUIRED
          score_type: nota_de_admision
          notes: "Source: notasdecorte.es — military career restriction applies"
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
          score: 12.379 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: "notasdecorte.es / Comunidad de Madrid — adscrito UAH — military access"
        - intake_year: 2024-2025
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: "Comunidad de Madrid / UAH — ANNUAL_UPDATE_REQUIRED"
        - intake_year: 2023-2024
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: "Comunidad de Madrid / UAH — ANNUAL_UPDATE_REQUIRED"
      admission_pathways:
        - eligible_profiles:
            - Spanish EVAU (PAU) — Comunidad de Madrid
            - International via PCE/UNED
            - International via Credencial UE
            - Direct homologation (select countries)
            - CRITICAL — military career selection process applies independently of nota de admisión
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
              notes: Best 2 eligible subjects × coefficient. Max nota 14.0000. Coefficients ANNUAL_UPDATE_REQUIRED — verify at uah.es or cud.uah.es.
              subject_ponderations:
                Biology:        ANNUAL_UPDATE_REQUIRED
                Chemistry:      ANNUAL_UPDATE_REQUIRED
                Physics:        ANNUAL_UPDATE_REQUIRED
                Mathematics_II: ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---
# Centro Universitario de la Defensa de Madrid (CUD Madrid) — Grado en Medicina

## Overview

The Centro Universitario de la Defensa de Madrid (CUD Madrid) is a public higher education institution attached to the Universidad de Alcalá (UAH) and operated under the Spanish Ministry of Defence (Ministerio de Defensa). It offers a Grado en Medicina specifically designed for officers of the Cuerpo Militar de Sanidad — the Spanish Armed Forces' Medical Corps. The programme is a six-year, 360 ECTS degree accredited under ANECA and registered in the RUCT, awarding a UAH-validated degree. Clinical training is delivered primarily at the Hospital Central de la Defensa "Gómez Ulla" in Madrid, the flagship military hospital of the Spanish Armed Forces. Teaching is conducted entirely in Spanish.

**Critical context for WinnersEducation.ai users:** CUD Madrid is a highly specialised, access-restricted institution. Admission is linked to an active military career pathway with the Spanish Armed Forces. Civilian students — including international students applying via PCE/UNED — do **not** have access to this programme through standard civil EVAU channels. This file exists as a reference entry; CUD Medicine is not a realistic option for the vast majority of students supported by Winners.

## Quick Evaluation

| Feature | Detail |
|---|---|
| Seats (plazas) | PENDING_CONFIRMATION (restricted to military candidates — ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2025-26 | 12.379 (notasdecorte.es / Comunidad de Madrid — ANNUAL_UPDATE_REQUIRED) |
| Teaching language(s) | Spanish |
| Annual tuition (approx.) | 0 € for active military personnel; not applicable for civilian students |
| Admission model | Nota de admisión (EVAU-based) + military career selection process |
| Clinical exposure | Hospital Central de la Defensa "Gómez Ulla" (Madrid) — specialised military hospital |
| ECTS | 360 |
| Duration | 6 years |
| Civilian access | NO — restricted to military career candidates |

## Key Facts

| Field | Value |
|---|---|
| Degree | Grado en Medicina |
| Campus | Centro Universitario de la Defensa de Madrid / Hospital Central de la Defensa Gómez Ulla |
| Seats (plazas ofertadas) | PENDING_CONFIRMATION (military quota — ANNUAL_UPDATE_REQUIRED) |
| Tuition per year | 0 € (military personnel only) — not applicable to civilian applicants |
| Admission model | Score-based (nota de admisión) + military selection |
| Proprietary exam | No (but military aptitude/medical selection applies) |
| Interview | PENDING_CONFIRMATION (military selection process) |
| Teaching language | Spanish |
| Awarding institution | Universidad de Alcalá (UAH) — degree validated by UAH |
| Military hospital | Hospital Central de la Defensa "Gómez Ulla", Madrid |
| Admissions contact | cud.uah.es / Ministerio de Defensa |
| Civilian access | Not available through standard EVAU process |

## Program Options

CUD Madrid offers a single Grado en Medicina programme, exclusively for candidates pursuing a career as an officer in the Cuerpo Militar de Sanidad of the Spanish Armed Forces. There is no civilian Medicine track, no bilingual programme, and no English-medium option. The programme operates under the regulatory framework of both the Ministerio de Defensa and ANECA. The awarding university is UAH (Universidad de Alcalá), which validates and registers the degree. Students are military personnel from the point of admission and are subject to military regulations and obligations throughout their studies. For all practical purposes, this programme is inaccessible to civilian domestic students and international students.

## Program Structure

The Grado en Medicina at CUD is structured across six years with 360 ECTS, following the national curriculum framework established by Orden ECI/332/2008:

- **Years 1–2 (Biomedical sciences foundation):** Anatomy, physiology, biochemistry, histology, cell biology, genetics, microbiology, immunology, public health, epidemiology, medical ethics, biostatistics, and clinical communication skills. Students combine academic study with military training.
- **Years 3–4 (Clinical sciences):** Pathology, pharmacology, radiology, internal medicine, surgery, gynaecology and obstetrics, paediatrics, psychiatry, neurology, dermatology, ENT, and ophthalmology. Clinical contact begins in year 3 at the Hospital Central de la Defensa.
- **Years 5–6 (Clinical rotations):** Full clinical rotations at Hospital Central de la Defensa "Gómez Ulla" and affiliated military and civilian health facilities. Year 6 delivers supervised rotations across all major specialties. TFG is completed in the final year.
- **Military component:** Military training, physical fitness, leadership, and Fuerzas Armadas regulations are integrated throughout the curriculum alongside the academic programme.

## Teaching Methodology

The teaching methodology at CUD Medicine combines standard Spanish medical education practices — lectures, laboratory practicals, seminars, and clinical case-based learning — with the structured discipline and schedule of a military academic institution. Class sizes are small due to the restricted intake, which provides intensive faculty-to-student ratios. The military institutional context imposes a structured and rigorous academic environment that differs significantly from civilian universities. The academic programme is equivalent in medical content to civil degree programmes, as UAH validates and accredits the degree.

## Clinical Training

Clinical training at CUD Medicine is delivered primarily through the military health network:

- **Hospital Central de la Defensa "Gómez Ulla" (Madrid):** The flagship military hospital of the Spanish Armed Forces and the principal clinical training facility for CUD Medicine students. It is a tertiary-level hospital with a broad specialty coverage, including surgery, internal medicine, traumatology, intensive care, and specialist services.
- **Affiliated facilities:** Additional training rotations may occur at civilian hospitals within the Spanish National Health System (SNS) under bilateral agreements, and at other military health installations.
- **Military medicine specifics:** Training includes elements of military and emergency medicine, disaster medicine, and operational healthcare relevant to Armed Forces deployment scenarios.

## International Recognition and Opportunities

The Grado en Medicina awarded by CUD is validated by UAH and registered in the Spanish RUCT. It is therefore recognised under EU Directive 2005/36/EC for automatic professional recognition across the EEA, in the same way as any other Spanish Medicine degree. Graduates can access the MIR examination and practice throughout the EU. However, the military career obligations accompanying the degree mean that graduates typically serve in the Armed Forces for a defined period following graduation. International exchange opportunities (Erasmus+, SICUE) exist in principle as a UAH-affiliated institution but are subject to military institutional constraints. In practice, Erasmus mobility is limited for CUD students due to the concurrent military career structure.

## Admission Model

CUD Medicine admission operates on two parallel tracks:

**1. Academic track (nota de admisión):** The same standard Spanish nota de admisión formula applies:
```
Nota de admisión = 0.6 × Nota media Bachillerato
                 + 0.4 × EVAU general phase score
                 + best 2 specific-phase subjects × ponderation coefficient
```
- Maximum base score: 10.0000
- Maximum nota de admisión (with specific-phase bonus): 14.0000
- Ponderation coefficients: ANNUAL_UPDATE_REQUIRED — verify at cud.uah.es

**2. Military selection track:** Independently of the nota de admisión, candidates must be selected as military officer candidates through the Ministerio de Defensa's competitive military access process. This process includes physical fitness tests, medical examination, psychological evaluation, and security clearance procedures. **Passing the nota de admisión threshold alone is not sufficient for admission to CUD Medicine.**

**Civilian applicants:** Civilian students cannot apply to CUD Medicine. The programme is exclusively for candidates who have been admitted to the Spanish Armed Forces officer career path via the Ministerio de Defensa selection process.

## Admission Process

### For military career candidates (Cuerpo Militar de Sanidad track)

1. Apply to the Ministerio de Defensa's officer selection process for the Cuerpo Militar de Sanidad — this is managed separately from standard university admissions.
2. Pass the military selection requirements: physical fitness, medical examination, psychological profile, and security screening.
3. Sit the EVAU (PAU) Comunidad de Madrid and calculate nota de admisión.
4. Apply to CUD Medicine through the admissions process coordinated by UAH/CUD once military selection is confirmed.
5. Places are allocated based on nota de admisión among candidates who have passed the military selection process.
6. Confirm enrolment with the Ministerio de Defensa.

### For civilian or international students

**Not applicable.** Civilian students and international PCE/UNED students do not have access to CUD Medicine through any standard civil admissions route. International students seeking Medicine in Madrid should evaluate other options (Universidad Complutense de Madrid — UCM, Universidad Autónoma de Madrid — UAM, or private universities).

## Admission Timeline

| Phase | Approximate dates | Notes |
|---|---|---|
| Ministerio de Defensa — military selection | ANNUAL_UPDATE_REQUIRED | Managed independently of standard university admissions |
| EVAU Madrid — ordinaria | June (ANNUAL_UPDATE_REQUIRED) | Standard Madrid EVAU |
| CUD admissions process | ANNUAL_UPDATE_REQUIRED | Coordinated by UAH / Ministerio de Defensa |
| Results | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Enrolment confirmation | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Academic year start | September (ANNUAL_UPDATE_REQUIRED) | Military academic calendar |

Note: The timeline is subject to the Ministerio de Defensa's annual officer selection calendar, which may differ from standard civilian university admissions timelines.

## Admission Score Distribution

### Nota de corte history

| Intake year | Round | Nota de corte | Campus | Source |
|---|---|---|---|---|
| 2025-2026 | Convocatoria ordinaria | 12.379 | CUD Madrid | notasdecorte.es / Comunidad de Madrid (ANNUAL_UPDATE_REQUIRED) |
| 2024-2025 | Convocatoria ordinaria | PENDING_CONFIRMATION | CUD Madrid | PENDING_CONFIRMATION |
| 2023-2024 | Convocatoria ordinaria | PENDING_CONFIRMATION | CUD Madrid | PENDING_CONFIRMATION |

**Critical interpretation note:** The nota de corte of 12.379 represents the minimum nota de admisión of admitted candidates in 2025-2026. However, this figure reflects only the pool of candidates who had already passed the military selection process. It is therefore **not comparable** to nota de corte figures at civilian Medicine faculties. A civilian student with a nota de admisión of 12.4 could not use this figure to assess their eligibility — they are ineligible for CUD regardless of their nota de admisión.

**Trend analysis:** With only PENDING_CONFIRMATION data for prior cycles, trend analysis is not possible. The 2025-2026 nota de corte of 12.379 positions CUD in a lower competitive band than top Madrid public faculties (UCM: ~13.0+; UAM: ~13.0+), but the restricted military applicant pool makes direct comparison with civil Medicine faculties meaningless.

## Costs and Payment Structure

| Fee component | Approximate amount | Notes |
|---|---|---|
| Annual tuition | 0 € | Covered by Ministerio de Defensa for military officer candidates |
| Living expenses during military training | PENDING_CONFIRMATION | Officers in training may receive a military salary or allowance |
| Additional academic fees | PENDING_CONFIRMATION | Verify with Ministerio de Defensa and UAH |
| Applicable to civilian students | NOT APPLICABLE | Civilian students cannot enrol |

Students admitted to CUD Medicine as officer candidates of the Cuerpo Militar de Sanidad are military personnel. Their education is funded by the Ministerio de Defensa; they do not pay tuition fees. They may also receive a salary or subsistence allowance during their training period as officer cadets. The 0 € tuition is exclusively contingent on active military status and is not available to civilian applicants under any circumstances.

## Scholarships and Financial Aid

Not applicable in the conventional sense. Military officer candidates receive state funding for their studies through the Ministerio de Defensa. Standard MEC Beca General or regional scholarships for civilian university students do not apply to CUD Medicine students. International students and civilian PCE/UNED applicants cannot access CUD and therefore cannot access its military funding model.

## Accommodation and Cost of Living

Military officer candidates studying at CUD Madrid may be housed in military accommodation facilities associated with the Ministerio de Defensa, or provided with housing allowances. The standard civilian student accommodation model does not apply. Madrid as a city has significantly higher living costs than smaller Spanish university cities.

| Category | Estimated monthly cost | Notes |
|---|---|---|
| Military accommodation | PENDING_CONFIRMATION | May be provided or subsidised — verify with Ministerio de Defensa |
| Private accommodation (Madrid) | ~600–1,200 EUR/month | For reference only — civilian context |
| Food (canteen — military) | PENDING_CONFIRMATION | Military dining facilities may apply |
| Total monthly estimated budget | PENDING_CONFIRMATION | Civilian cost of living framework does not apply |

Note: Madrid is one of Spain's most expensive cities. The zero-tuition military model significantly offsets costs for eligible candidates. Civilian students considering Medicine in Madrid at public prices should look to UCM or UAM.

## International Exchange and Mobility Programs

- **Erasmus+ and SICUE:** Formally available as a UAH-affiliated institution. In practice, military operational commitments and the structured military academic calendar significantly constrain student mobility options.
- **Military exchange programmes:** The Ministerio de Defensa may have bilateral military education agreements with NATO and EU partner military institutions. Details are PENDING_CONFIRMATION.
- **International students:** Not applicable — civilian and international students cannot enrol at CUD Medicine.

## MIR Preparation and Professional Outcomes

Graduates of CUD Medicine receive a UAH-validated Grado en Medicina and are eligible to sit the MIR examination. However, their primary career trajectory is defined by their military obligations: graduates typically serve as medical officers in the Spanish Armed Forces (Cuerpo Militar de Sanidad) for a defined service period following graduation. They may subsequently pursue MIR specialist training through civilian or military pathways, depending on their service commitments and agreements with the Ministerio de Defensa. No disaggregated MIR pass rate data for CUD graduates is publicly available. Professional recognition of the degree is valid across the EEA under Directive 2005/36/EC.

## Strategic Fit

### Good Fit For

- Candidates who are specifically pursuing a career as a medical officer in the Spanish Armed Forces (Cuerpo Militar de Sanidad) and have already passed or are preparing for the military selection process.
- Spanish nationals committed to a military career who want to study Medicine within the Armed Forces framework at zero tuition cost.
- Students who are attracted to the highly structured, disciplined environment of a military educational institution combined with medical training.
- Candidates with a nota de admisión in the 12.2–12.6 range who have successfully navigated military selection and would otherwise not reach the nota de corte threshold of top Madrid civil Medicine faculties.

### Less Suitable For

- **Civilian students — this programme is not accessible.** Any civilian student, domestic or international, who has not entered the Ministerio de Defensa's military officer selection process cannot apply to CUD Medicine.
- International PCE/UNED students — no access pathway exists for international students through standard civil admissions.
- Students seeking Medicine in Madrid through the standard public system — UCM and UAM are the appropriate targets.
- Students pursuing private Medicine — Universidad Alfonso X el Sabio, Universidad Francisco de Vitoria, or Universidad Rey Juan Carlos (private/concertada) are relevant options in Madrid.
- Winners students on the standard private university Medicine pathway — CUD is irrelevant to this group.

## Risks and Considerations

1. **Civilian inaccessibility — paramount risk:** The single most important consideration is that CUD Medicine is completely inaccessible to civilian students. Any student or advisor who sees the nota de corte of 12.379 and interprets it as an accessible public Medicine option in Madrid is making a critical error. The programme is reserved exclusively for military career candidates.
2. **Military service obligations:** Admission to CUD Medicine carries long-term military service commitments. Graduates may be required to serve in the Armed Forces for a defined period following graduation, which constrains early career flexibility relative to civil Medicine graduates.
3. **Nota de corte not comparable:** The 12.379 nota de corte reflects the military applicant pool, not the general student population. It cannot be used for benchmarking against civilian Medicine faculties.
4. **Limited data availability:** Historical nota de corte data (2024-25, 2023-24) is PENDING_CONFIRMATION. The military admissions process is less transparent than civil university systems.
5. **International students:** No pathway exists for international students. CUD should not be included in application strategies for international Medicine applicants to Spain.
6. **Military lifestyle:** The structured, hierarchical, and physically demanding environment of a military academic institution may not suit all students temperamentally, regardless of academic qualifications.

## Important Notes

- CUD Madrid is a centro adscrito público attached to Universidad de Alcalá (UAH). The degree awarded is a UAH-validated Grado en Medicina.
- Admission requires successful completion of the Ministerio de Defensa military officer selection process independently of the nota de admisión requirement.
- Tuition is 0 € exclusively for military officer candidates — this is not a civilian scholarship programme.
- The Hospital Central de la Defensa "Gómez Ulla" is the primary clinical training site — a military hospital, not a civilian SNS facility.
- Winners students should be explicitly informed that CUD Medicine is not an applicable option for their situation.
- Website: http://cud.uah.es/

## Key Insight

CUD Madrid's Grado en Medicina is a fully accredited, UAH-validated degree delivered within a military institutional framework for candidates pursuing a career in the Spanish Armed Forces Medical Corps. Its nota de corte of 12.379 (2025-2026) is among the lower thresholds for public Medicine in Madrid — but this is structurally irrelevant to civilian students because admission requires military selection, not just academic scores. The zero-tuition model is exclusively available to military officer candidates. For WinnersEducation.ai, this university represents a reference-only entry: it is not a viable pathway for any student on the standard Medicine admissions track, domestic or international.

## Final Takeaway

CUD Medicine exists at the intersection of military service and medical education. It is the only route to study Medicine free of charge within the Spanish Armed Forces structure, producing military doctors for the Cuerpo Militar de Sanidad. For the overwhelming majority of students preparing for Medicine in Spain — including all international students, PCE/UNED applicants, and students targeting private universities — CUD Madrid is not a relevant option and should not appear in application shortlists. Advisors using this file should clearly communicate to students that the 12.379 nota de corte does not translate into civilian accessibility.

## Frequently Asked Questions

**Q: Can a civilian student apply to CUD Medicine in Madrid?**
A: No. CUD Medicine is exclusively for candidates pursuing a career as military officers in the Cuerpo Militar de Sanidad. Civilian students cannot apply through any standard EVAU or PCE/UNED admissions route.

**Q: What is the nota de corte for CUD Medicine?**
A: The nota de corte for the 2025-2026 intake was 12.379 (source: notasdecorte.es / Comunidad de Madrid — ANNUAL_UPDATE_REQUIRED). This figure applies only to the restricted pool of military career candidates, not to civilian students.

**Q: Is the 0 € tuition available to any student who gains admission?**
A: No. The 0 € tuition applies exclusively to military officer candidates funded by the Ministerio de Defensa. It is not a scholarship or financial aid mechanism accessible to civilian students.

**Q: Which hospital is used for clinical training at CUD?**
A: The Hospital Central de la Defensa "Gómez Ulla" in Madrid is the primary clinical training facility. It is a military hospital, not part of the standard SNS network available to civil Medicine students.

**Q: Is the degree from CUD the same as a degree from UCM or UAM?**
A: The degree is a Grado en Medicina validated by Universidad de Alcalá (UAH) and registered in the RUCT, conferring the same professional recognition as other accredited Spanish Medicine degrees. It enables access to MIR and practice across the EEA.

**Q: Can international PCE/UNED students apply?**
A: No. International students applying via PCE/UNED to civilian public Medicine faculties in Spain have no access pathway to CUD Medicine. The military career requirement is absolute.

**Q: What happens to CUD Medicine graduates professionally?**
A: Graduates serve as medical officers in the Spanish Armed Forces for a defined period. After fulfilling their service obligations, they may pursue MIR specialist training via civilian or military pathways. The degree is valid for civilian medical practice upon completion of service commitments.

**Q: Should Winners students include CUD Madrid in their application list?**
A: No. CUD Medicine is not applicable to the student profiles served by Winners — private university track, international PCE/UNED applicants, and students without a military career pathway. This file exists for reference and institutional completeness only.
