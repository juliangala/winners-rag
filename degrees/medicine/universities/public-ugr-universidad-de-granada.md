---
id: ugr

type: university
subtype: public

name: Universidad de Granada
short_name: UGR

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Granada
  region: Andalucía
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - high_competitiveness
  - research_oriented
  - strong_clinical_exposure
  - international_friendly

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
  seats: 216 # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION

  last_admitted_scores:
    - intake_year: 2024-2025
      round: convocatoria_ordinaria
      score: 13.786
      score_type: nota_de_admision
      notes: Definitiva (last admitted after wait-list resolution, November 2024) # ANNUAL_UPDATE_REQUIRED

    - intake_year: 2023-2024
      round: convocatoria_ordinaria
      score: 13.780
      score_type: nota_de_admision
      notes: NULL # ANNUAL_UPDATE_REQUIRED

    - intake_year: 2022-2023
      round: convocatoria_ordinaria
      score: 13.737
      score_type: nota_de_admision
      notes: NULL # ANNUAL_UPDATE_REQUIRED

international_profile:
  international_students_percentage: PENDING_CONFIRMATION
  international_nationalities: []

programs:
  - id: ugr-medicina

    campus: Campus de la Salud (Parque Tecnológico de la Salud), Granada

    modality: standard

    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - high_competitiveness
      - research_oriented

    teaching_languages:
      - Spanish

    regional_language_possible: false
    regional_language: NULL

    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL

    seats: 216 # ANNUAL_UPDATE_REQUIRED

    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 216 # ANNUAL_UPDATE_REQUIRED
      applicants_per_seat: PENDING_CONFIRMATION

      last_admitted_scores:
        - intake_year: 2024-2025
          round: convocatoria_ordinaria
          score: 13.786
          score_type: nota_de_admision
          notes: NULL # ANNUAL_UPDATE_REQUIRED

        - intake_year: 2023-2024
          round: convocatoria_ordinaria
          score: 13.780
          score_type: nota_de_admision
          notes: NULL # ANNUAL_UPDATE_REQUIRED

        - intake_year: 2022-2023
          round: convocatoria_ordinaria
          score: 13.737
          score_type: nota_de_admision
          notes: NULL # ANNUAL_UPDATE_REQUIRED

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
          score: 13.786
          round: convocatoria_ordinaria
          source: Distrito Único Andaluz (DUA) — juntadeandalucia.es # ANNUAL_UPDATE_REQUIRED

        - intake_year: 2023-2024
          score: 13.780
          round: convocatoria_ordinaria
          source: Distrito Único Andaluz (DUA) # ANNUAL_UPDATE_REQUIRED

        - intake_year: 2022-2023
          score: 13.737
          round: convocatoria_ordinaria
          source: Distrito Único Andaluz (DUA) # ANNUAL_UPDATE_REQUIRED

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
              notes: Best 2 eligible subjects count. Each subject score multiplied by the university's ponderation coefficient (0.1 or 0.2). Maximum nota de admisión: 14.0000. Coefficients valid from 2024-25 per DUA Resolution June 2023.
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED
                Chemistry:      0.2 # ANNUAL_UPDATE_REQUIRED
                Physics:        0.1 # ANNUAL_UPDATE_REQUIRED
                Mathematics_II: 0.1 # ANNUAL_UPDATE_REQUIRED
                Drawing_II:     0.1 # ANNUAL_UPDATE_REQUIRED
                History_Art:    0.1 # ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---
# Universidad de Granada

## Overview

The Universidad de Granada (UGR), founded in 1531, is one of Spain's largest and most internationally recognised public universities. Its Grado en Medicina, housed within the Facultad de Medicina on the Campus de la Salud (Parque Tecnológico de la Salud), consistently attracts some of Andalucía's highest-achieving science students. With a nota de corte that has remained above 13.70 for multiple consecutive cycles, admission to UGR Medicine is effectively restricted to candidates with near-perfect academic trajectories. The programme offers 360 ECTS over six years, integrates extensive clinical training through the Servicio Andaluz de Salud (SAS) hospital network, and provides access to a vibrant research environment. For academically strong candidates seeking a public university degree at the lower end of the tuition spectrum, UGR is a strategically significant — and highly competitive — target.

## Quick Evaluation

- **Type:** Public university | Grado en Medicina (360 ECTS, 6 years)
- **Admission model:** Nota de admisión only — no proprietary exam, no interview
- **Nota de corte 2024-25:** 13.786 (convocatoria ordinaria) — requires near-perfect EVAU performance with maximum specific-phase bonus
- **Seats:** approximately 216 per year (ANNUAL_UPDATE_REQUIRED)
- **Tuition:** approximately 1,100–1,200 EUR/year (Andalucía regional tariff, ANNUAL_UPDATE_REQUIRED)
- **Teaching language:** Spanish
- **Clinical network:** Servicio Andaluz de Salud (SAS) — Hospital Universitario Virgen de las Nieves, Hospital Clínico Universitario San Cecilio, and associated centres
- **International access:** Yes — PCE/UNED, Credencial UE, or homologation
- **WFME accreditation:** PENDING_CONFIRMATION

## Key Facts

| Feature | Detail |
|---|---|
| University founded | 1531 |
| Faculty | Facultad de Medicina |
| Campus | Campus de la Salud, Parque Tecnológico de la Salud, Granada |
| Programme | Grado en Medicina |
| Duration | 6 years |
| Total ECTS | 360 (including 15 elective credits) |
| Seats (2025-26) | ~216 (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2024-25 | 13.786 |
| Nota de corte 2023-24 | 13.780 |
| Nota de corte 2022-23 | 13.737 |
| Tuition (approx.) | 1,100–1,200 EUR/year (ANNUAL_UPDATE_REQUIRED) |
| Teaching language | Spanish |
| International rankings | Top-ranked Spanish university in multiple subject areas (Shanghai, QS) |
| Erasmus destinations | First Erasmus destination among Spanish universities |

## Program Options

UGR offers a single Grado en Medicina delivered entirely in Spanish on the Campus de la Salud in Granada. There are no bilingual tracks, no satellite campuses, and no online modality. The degree is a single integrated programme: all students follow the same structured six-year curriculum. Optional subjects (15 ECTS) allow limited specialisation in areas such as medical imaging, exercise physiology, and medical English (levels I and II are available as elective courses). There are no competing tracks or dual degrees for Medicine at UGR.

## Program Structure

The Grado en Medicina at UGR consists of 360 ECTS distributed across six academic years:

- **Years 1–2 (Basic Sciences):** Foundations in human anatomy (I, II, III), physiology (general, medical I and II), biochemistry, histology, cell biology, embryology, immunology, biostatistics, and psychology. Year 2 introduces clinical communication and research methodology early in the curriculum.
- **Years 3–4 (Preclinical and Clinical Integration):** Pathological anatomy, pharmacology, microbiology and parasitology, surgery, psychiatry, medical imaging and radiology, and disease-system pathology (cardiovascular, respiratory, oncology, haematology, dermatology, neurology, urology, and ENT). Radiología y Medicina Física (10 ECTS) is a notably heavy module in Year 4.
- **Years 5–6 (Clinical Training and Professional Competences):** Clinical rotations begin. Year 5 covers obstetrics, paediatrics, preventive medicine, public health, endocrinology, family medicine, forensic medicine, and legal medicine. Year 6 is dedicated to the rotatorio (clinical practicum), with structured rotations in medical pathology, surgical pathology, emergency medicine, obstetrics and gynaecology, psychiatry, paediatrics, and primary care (Atención Primaria). A Trabajo Fin de Grado (TFG) is completed in Year 6.

Elective credits (15 ECTS) may be accumulated across multiple years from a portfolio that includes epidemiology, advanced medical statistics, tissue engineering, medical English, exercise physiology, and palliative care.

## Teaching Methodology

UGR Medicine combines traditional lecture-based instruction with problem-based and case-based learning formats, particularly from Year 2 onwards. The introduction of clinical communication (Comunicación Médica) in Year 2 reflects an early patient-centred approach. Simulation-based training and small-group practicals are embedded throughout. Research literacy is integrated from Year 2 via Fundamentos de la Investigación en Salud y Bioética. The university's affiliation with the Parque Tecnológico de la Salud — an ecosystem combining hospital, research institutes, and faculty — creates proximity between teaching and applied biomedical research. Students have access to library resources at the Biblioteca de Medicina y Ciencias de la Salud and digital learning platforms.

## Clinical Training

Clinical exposure begins formally in Year 4 and intensifies in Years 5 and 6. The rotatorio in Year 6 constitutes the core clinical practicum and covers the principal medical and surgical specialties in rotation. Clinical training is delivered within the Servicio Andaluz de Salud (SAS) network, which includes:

- **Hospital Universitario Virgen de las Nieves** (primary teaching hospital, adjacent to Campus de la Salud)
- **Hospital Clínico Universitario San Cecilio** (second major teaching hospital on the same campus)
- **Centros de Salud (Atención Primaria)** in the Granada metropolitan area

The colocation of two major teaching hospitals with the faculty on the same campus provides unusually direct access to clinical settings from early in the degree. The rotatorio includes hospital emergency rotations (Urgencias Hospitalarias) and primary care rotations. ECOE (Objective Structured Clinical Examination) assessment is conducted to evaluate clinical competencies at the programme's conclusion.

## International Recognition and Opportunities

UGR holds the Arqus European University Alliance membership, which facilitates academic exchange within a network of nine European research universities. UGR is historically the top Spanish university by volume of Erasmus participants (both outgoing and incoming). Within Medicine specifically, Erasmus+ exchange opportunities exist subject to bilateral agreements with receiving faculties — candidates should confirm availability of Medicine-specific Erasmus placements directly with the faculty's Movilidad office (ANNUAL_UPDATE_REQUIRED).

WFME accreditation status for the Grado en Medicina at UGR is PENDING_CONFIRMATION. Candidates requiring WFME-accredited degrees for postgraduate licensing in the United States or Canada must verify this before enrolling.

The UGR degree is recognised across the European Union under the relevant EU Directive on professional qualifications (Directive 2005/36/EC). MIR access is fully valid for all graduates. International graduates in medicine from non-EU countries seeking to practice in Spain must follow the standard homologation process via the Ministerio de Sanidad.

## Admission Model

UGR Medicine uses the standard Spanish public university admission model for undergraduate degrees: the **nota de admisión**. No proprietary entrance examination, aptitude test, interview, or portfolio is required.

**Formula:**
```
Nota de admisión = 0.6 × Nota media Bachillerato + 0.4 × Nota EVAU fase general
                  + (Subject A score × coefficient) + (Subject B score × coefficient)
```

- The base maximum (without specific-phase subjects) is **10.0000**.
- The maximum with specific-phase bonus is **14.0000**.
- Up to two specific-phase subjects may be added. Only subjects with an assigned ponderation coefficient for the degree are eligible.
- At UGR (and all Andalucía universities), the ponderation coefficients for Medicine are: **Biology 0.2, Chemistry 0.2, Physics 0.1, Mathematics II 0.1** (valid from 2024-25; ANNUAL_UPDATE_REQUIRED per annual DUA resolution).
- The optimal strategy is to take and maximise Biology and Chemistry in the EVAU specific phase, as both carry the maximum coefficient of 0.2.

**International students (PCE/UNED):** Students from non-EU educational systems who do not hold an EU-equivalent Bachillerato may access Spanish public universities via the PCE (Prueba de Competencias Específicas) administered by UNED. The nota de admisión is calculated using the same formula once a valid grade equivalence is established. EU students with recognised secondary credentials compete directly in the Fase de Extranjeros managed by the Distrito Único Andaluz (DUA).

## Admission Process

### Spanish PAU (EVAU) Candidates

1. Complete Bachillerato (or equivalent) in Spain.
2. Register and sit the EVAU (PAU) in Andalucía (or the relevant regional variant). Take Biology and Chemistry in the specific phase to maximise ponderation.
3. Receive grades and calculate your nota de admisión.
4. Submit university admission preferences via the Distrito Único Andaluz (DUA) portal (juntadeandalucia.es/economiaconocimientoempresasyuniversidad/sguit/) during the designated preinscripción period (typically June/July, ANNUAL_UPDATE_REQUIRED).
5. List UGR Medicina as one of your preferences in order of priority, alongside alternative choices.
6. Results of the first adjudicación are published in July. Check assignment and confirm matriculation within the stated deadline.
7. Students not assigned in the first round may remain on the waiting list (listas de espera) through subsequent adjudicaciones in August and October.
8. Complete formal matriculation (automatrícula) via the UGR virtual office.

### International Candidates (PCE/UNED)

1. Contact UNED to verify eligibility for the PCE based on your educational system and country.
2. Register for the PCE in the relevant subjects (Biology, Chemistry, and Spanish Language are typical requirements for Medicine).
3. Obtain a valid nota de acceso equivalent from UNED or your national educational authority.
4. Apply to the Fase de Extranjeros via the DUA portal during the designated international application window (typically before the Spanish convocatoria ordinaria).
5. If assigned, complete matriculation at UGR.
6. Students with EU credentials (Credencial UE or Bachillerato Europeo) follow the same DUA pathway with their credencial as the basis for scoring.

## Admission Timeline

All dates are indicative and subject to annual revision by the DUA and UGR. (ANNUAL_UPDATE_REQUIRED)

| Event | Approximate Timing |
|---|---|
| EVAU ordinaria (exams) | June (ANNUAL_UPDATE_REQUIRED) |
| DUA preinscripción opens | Mid-June (ANNUAL_UPDATE_REQUIRED) |
| DUA preinscripción deadline | Late June (ANNUAL_UPDATE_REQUIRED) |
| First adjudicación published | Early July (ANNUAL_UPDATE_REQUIRED) |
| EVAU extraordinaria (exams) | September (ANNUAL_UPDATE_REQUIRED) |
| Second adjudicación (Sept.) | Mid-September (ANNUAL_UPDATE_REQUIRED) |
| Final waiting list resolution | October–November (ANNUAL_UPDATE_REQUIRED) |
| Matriculation period | July (for first round), September (for second round) (ANNUAL_UPDATE_REQUIRED) |
| Academic year starts | September (ANNUAL_UPDATE_REQUIRED) |

## Admission Score Distribution

UGR Medicine is among the most competitive public university programmes in Spain. The nota de corte has exceeded 13.70 for at least three consecutive cycles, indicating that candidates require an extremely strong combination of Bachillerato grades and specific-phase EVAU performance.

| Intake Year | Nota de Corte | Round |
|---|---|---|
| 2024-2025 | 13.786 | Convocatoria ordinaria |
| 2023-2024 | 13.780 | Convocatoria ordinaria |
| 2022-2023 | 13.737 | Convocatoria ordinaria |

**Strategic interpretation:**

- A nota de corte above 13.70 in three consecutive years signals exceptional stability at the upper end of the admissible range. This is not a fluctuating borderline.
- A candidate targeting UGR Medicine realistically needs a nota de admisión of **13.800 or above** to feel confident — the precise cut-off varies each cycle depending on demand and seat allocation.
- The theoretical maximum is 14.0000. Achieving 13.786 requires, for example: a Bachillerato average of 9.5, a general-phase EVAU average of 9.0, and two specific-phase subjects scored at 9.43 each (× 0.2 coefficient = 1.886 bonus each) — or equivalent combinations.
- In practical terms, candidates typically need: Bachillerato average ≥ 9.5, EVAU general ≥ 9.0, and specific-phase scores close to 10 in Biology and Chemistry (each multiplied by 0.2).
- The nota de corte published by the DUA represents the **lowest score admitted after all waiting-list rounds are resolved** (the final list published in October/November). The initial July list may show a slightly lower figure.
- No extraordinary convocatoria nota de corte is routinely published as a separate figure; the definitive value applies regardless of which convocatoria the candidate used.

## Costs and Payment Structure

| Cost Item | Amount | Notes |
|---|---|---|
| Annual tuition (Year 1) | ~1,100–1,200 EUR | Set by Junta de Andalucía; ANNUAL_UPDATE_REQUIRED |
| Annual tuition (Years 2–6) | ~1,100–1,200 EUR | Same regional tariff applies; ANNUAL_UPDATE_REQUIRED |
| EVAU registration fee | ~100–120 EUR | One-time; regional tariff; ANNUAL_UPDATE_REQUIRED |
| Academic services fee | Included in tuition | ANNUAL_UPDATE_REQUIRED |
| Student card / ID | Included | ANNUAL_UPDATE_REQUIRED |
| Estimated total degree cost (tuition only) | ~6,600–7,200 EUR | Over 6 years; does not include living costs |

EU/EEA students who have completed their secondary education in Spain pay the same tariff as domestic students. Non-EU students may face different tariffs — confirm with UGR Servicio de Acceso, Admisión y Permanencia (SAAP).

## Scholarships and Financial Aid

- **Beca General MEC (Ministerio de Educación):** The main national scholarship for university students. Covers a portion of tuition and provides a living allowance. Eligibility is income-based and academic-performance-based. Applications open annually in August/September (ANNUAL_UPDATE_REQUIRED). All UGR Medicine students are eligible to apply.
- **Becas de excelencia Junta de Andalucía:** Complementary regional scholarship for high-performing Andalucian students. PENDING_CONFIRMATION of current availability and amounts.
- **UGR own grants and emergency aid:** The University of Granada administers a limited number of emergency social aid grants. Contact UGR's Vicerrectorado de Estudiantes for current programmes (ANNUAL_UPDATE_REQUIRED).
- **Erasmus+ mobility stipends:** Students who undertake approved Erasmus exchanges receive a monthly stipend to offset costs. Amounts depend on destination country (ANNUAL_UPDATE_REQUIRED).
- **SICUE mobility:** National exchange programme enabling UGR students to spend one semester at another Spanish university. Applicable to some clinical or preclinical years subject to faculty agreement.

## Accommodation and Cost of Living

Granada is one of Spain's most affordable university cities. Cost of living estimates (ANNUAL_UPDATE_REQUIRED):

| Expense | Monthly Estimate |
|---|---|
| Private room in shared flat | 300–450 EUR |
| University residence (residencia universitaria) | 450–650 EUR |
| Food (cooking at home) | 150–250 EUR |
| Transport (bus pass) | 15–30 EUR |
| Total estimated monthly living cost | 500–800 EUR |

UGR operates a Servicio de Alojamiento that connects students with university-affiliated residences and private accommodation listings. The Campus de la Salud is accessible via public bus. Granada's compact size makes cycling feasible for many students.

## International Exchange and Mobility Programs

UGR participates in the Erasmus+ programme and is Spain's leading university by number of outgoing Erasmus students. Within the Arqus Alliance (nine European universities), structured exchange opportunities exist. For Medicine specifically, exchange placements must be confirmed with the Facultad de Medicina's Movilidad coordinator, as clinical year rotations impose constraints on semester-length absences. The faculty offers both outgoing (Desde la UGR) and incoming (Hacia la UGR) Erasmus Medicine programmes, subject to bilateral agreements with partner institutions. Students interested in international mobility are advised to contact the faculty's international relations office early (ANNUAL_UPDATE_REQUIRED regarding active Medicine-specific Erasmus partners).

## MIR Preparation and Professional Outcomes

UGR Medicine graduates are eligible to sit the MIR (Médico Interno Residente) national exam upon graduation. MIR pass rates and ranking distributions specific to UGR are PENDING_CONFIRMATION in publicly verifiable form. However, UGR is consistently associated with strong MIR outcomes, given the high entry standard of its cohort: a candidate who achieved a nota de admisión above 13.70 typically demonstrates strong academic capacity. The MIR exam rewards encyclopaedic knowledge and analytical reasoning, both of which are cultivated by UGR's six-year curriculum. Upon passing the MIR, graduates access residency positions in Spain's public hospital system. The UGR degree is fully recognised for medical practice in the European Union and in countries with bilateral agreements with Spain.

## Strategic Fit

### Good Fit For

- Candidates with a nota de admisión consistently at or above 13.80, who want a public university degree at minimal cost.
- Students who have optimised their EVAU specific phase in Biology and Chemistry and can demonstrate a near-maximum score combination.
- Candidates who value Granada's international university environment and extensive Erasmus network.
- Students intending to practice in Spain's public health system, where the MIR is the primary gateway to specialisation.
- Families seeking a high-prestige medicine degree at approximately 1,100–1,200 EUR/year.
- International students comfortable studying in Spanish, who meet the nota de admisión threshold through PCE/UNED.

### Less Suitable For

- Candidates with nota de admisión below 13.50, for whom UGR Medicine is not a realistic option regardless of effort invested in applications.
- Students who require the degree to be available in English or need bilingual instruction.
- Applicants who wish to attend a university with a confirmed WFME accreditation for U.S./Canada medical licensing eligibility (verify WFME status before applying).
- Candidates who prefer small cohort sizes or highly individualised mentoring — UGR is a large university with large cohorts.

## Risks and Considerations

- **Nota de corte variability:** While the UGR nota de corte has been stable at 13.73–13.79, it can shift upward or downward by a few hundredths each cycle depending on seat count, national EVAU difficulty, and applicant pool. A score that secured admission in one year may not suffice the next.
- **Seat allocation changes:** The regional government (Junta de Andalucía) determines the annual seat offering. Seat reductions directly push the nota de corte higher. Monitor the official DUA announcement each spring.
- **Regional residency quotas:** Andalucía operates a Distrito Único (unified district) system, meaning students from any Spanish region may apply. However, regional preference may apply within quotas in some configurations — verify annually.
- **Waiting list risk:** Many candidates are assigned places through the listas de espera (October/November resolution). Students must remain available and flexible with their plans until the final list is published.
- **No fallback within UGR:** There is no supplementary or evening Medicina programme at UGR. If not admitted, the only pathway is retaking EVAU or applying elsewhere.
- **Living cost inflation:** Granada's affordability advantage is eroding gradually as the city becomes more popular with tourists and remote workers. Accommodation costs have risen in recent years.

## Important Notes

- Nota de corte values are **definitive** after the full waiting-list process concludes (November). Initial July figures may be slightly lower.
- Ponderación coefficients are set by the DUA annually. While Biology 0.2 and Chemistry 0.2 have been stable, check the official DUA resolution each year before committing exam subject choices.
- UGR's Servicio de Acceso, Admisión y Permanencia (SAAP) is the official contact for all admission queries: saap.ugr.es.
- International students applying via PCE/UNED must confirm the UNED registration deadlines independently — these occur earlier than Spanish EVAU deadlines.
- The definitive nota de corte for any given year is only published after the final adjudicación (October/November). Mid-year values circulating on unofficial sites are indicative only.

## Key Insight

UGR Medicine is a viable target only for candidates who can realistically project a nota de admisión at or above 13.80. The sustained high nota de corte reflects genuine demand and limited seats — there is no admissions strategy or timing advantage that circumvents the numerical threshold. Candidates who meet this bar gain access to a well-resourced public medicine degree, a rich clinical network via the SAS hospital system, and a low-cost academic environment in a vibrant university city with exceptional Erasmus connectivity. For those who fall short of the threshold, no amount of application strategy alters the outcome: the system is entirely formulaic.

## Final Takeaway

The Grado en Medicina at UGR is one of Spain's most selective public medicine programmes, with a nota de corte that has remained above 13.73 for multiple years. Its strengths include: public pricing (~1,100–1,200 EUR/year), access to major SAS teaching hospitals on-campus at the Parque Tecnológico de la Salud, a rich research environment, and Spain's leading Erasmus participation. Its key risk is precisely its attractiveness: competition is intense, the nota de corte is among the highest in the country, and the admissions model is fully non-negotiable. Candidates who meet the bar will find UGR an excellent gateway to a Spanish medical career; those who do not need to redirect their attention to alternative institutions.

## Frequently Asked Questions

**How is the nota de admisión calculated?**
The formula is: 0.6 × Bachillerato average + 0.4 × EVAU general phase grade + (up to two specific-phase subject scores × their ponderation coefficient). The base maximum is 10.0. Adding specific-phase subjects with Biology (0.2) and Chemistry (0.2) brings the theoretical maximum to 14.0.

**What is the nota de corte and what does it mean?**
The nota de corte is the nota de admisión of the last student admitted in the final waiting-list round of the previous cycle. It is not a guaranteed minimum — it is a historical reference point that varies annually. A score above last year's nota de corte does not guarantee admission; it is an indicator of the level of competition.

**What ponderation coefficients apply at UGR for Medicine?**
For the 2024-25 cycle (and projected forward): Biology 0.2, Chemistry 0.2, Physics 0.1, Mathematics II 0.1. Always verify these against the annual DUA resolution, as they are subject to change.

**Can international students apply to UGR Medicine via PCE?**
Yes. Students from non-EU educational systems may sit the PCE (Prueba de Competencias Específicas) administered by UNED to obtain a valid nota de acceso. EU students with a recognised secondary credential apply via the Credencial UE or homologation pathway through the DUA Fase de Extranjeros.

**What are the tuition fees?**
Approximately 1,100–1,200 EUR per academic year, set by the Junta de Andalucía. This is significantly lower than private medicine universities in Spain. Exact amounts are published annually (ANNUAL_UPDATE_REQUIRED).

**When do I apply?**
Applications are submitted via the DUA preinscripción portal in June/July following the EVAU ordinaria. A second window opens after the EVAU extraordinaria in September. Exact dates are published annually by the Junta de Andalucía (ANNUAL_UPDATE_REQUIRED).

**Is UGR Medicine accredited by WFME?**
WFME accreditation status for UGR Medicine is PENDING_CONFIRMATION. Candidates who require WFME accreditation for postgraduate licensing in the United States or Canada must verify this directly with the Facultad de Medicina before enrolling.

**Is there an entrance exam or interview?**
No. Admission is based exclusively on the nota de admisión formula. There is no additional exam, interview, or portfolio requirement.
