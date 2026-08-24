---
id: udg

type: university
subtype: public

name: Universitat de Girona
short_name: UdG

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Girona
  region: Cataluña
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - high_competitiveness
  - strong_clinical_exposure
  - newer_programme

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
  seats: 60 # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
    - intake_year: 2024-2025
      round: convocatoria_ordinaria
      score: PENDING_CONFIRMATION
      score_type: nota_de_admision
      notes: Programme admitted first cohort in 2022-23; historical data series is limited
    - intake_year: 2023-2024
      round: convocatoria_ordinaria
      score: PENDING_CONFIRMATION
      score_type: nota_de_admision
      notes: NULL
    - intake_year: 2022-2023
      round: convocatoria_ordinaria
      score: PENDING_CONFIRMATION
      score_type: nota_de_admision
      notes: Inaugural cohort intake

international_profile:
  international_students_percentage: PENDING_CONFIRMATION
  international_nationalities: []

programs:
  - id: udg-medicina
    campus: Campus Montilivi / Campus Barri Vell — clinical rotations at Hospital Universitari de Girona Dr. Josep Trueta
    modality: standard
    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - high_competitiveness
      - newer_programme
    teaching_languages:
      - Catalan
      - Spanish
    regional_language_possible: true
    regional_language: Catalan
    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL
    seats: 60 # ANNUAL_UPDATE_REQUIRED
    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 60 # ANNUAL_UPDATE_REQUIRED
      applicants_per_seat: PENDING_CONFIRMATION
      last_admitted_scores:
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
        - intake_year: 2022-2023
          round: convocatoria_ordinaria
          score: PENDING_CONFIRMATION
          score_type: nota_de_admision
          notes: Inaugural cohort
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
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: accesuniversitats.gencat.cat # ANNUAL_UPDATE_REQUIRED
        - intake_year: 2023-2024
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: accesuniversitats.gencat.cat # ANNUAL_UPDATE_REQUIRED
        - intake_year: 2022-2023
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: accesuniversitats.gencat.cat # ANNUAL_UPDATE_REQUIRED
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
              notes: Best 2 eligible subjects count. Each subject score multiplied by the university's ponderation coefficient (0.1 or 0.2). Maximum nota de admisión: 14.0000. Cataluña uses a unified ponderation table for all public universities. Coefficients ANNUAL_UPDATE_REQUIRED.
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED — Cataluña ponderation table
                Chemistry:      0.2 # ANNUAL_UPDATE_REQUIRED — Cataluña ponderation table
                Physics:        0.1 # ANNUAL_UPDATE_REQUIRED — Cataluña ponderation table
                Mathematics_II: 0.1 # ANNUAL_UPDATE_REQUIRED — Cataluña ponderation table
                Drawing_II:     ANNUAL_UPDATE_REQUIRED
                History_Art:    ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---
# Universitat de Girona

## Overview

The Universitat de Girona (UdG) is a public research university founded in 1991, located in the city of Girona in the Cataluña autonomous community. UdG is a mid-sized institution with approximately 17,000 students enrolled across its faculties. Its Grado en Medicina is one of the newest public medicine programmes in Spain, having admitted its inaugural cohort in the 2022-23 academic year. The programme is based at the Faculty of Medicine and integrates clinical training at the Hospital Universitari de Girona Dr. Josep Trueta, the main teaching hospital in the Girona province.

The UdG Medicine programme was created in response to the chronic shortage of physicians in Cataluña's Girona region and represents a deliberate institutional investment in health sciences. Because it is newly established, the programme does not yet have a full graduating cohort, and historical MIR pass rate data is unavailable. However, the faculty draws on UdG's existing research capacity and the Girona health network for clinical placement.

## Quick Evaluation

UdG Medicine is a **high-competitiveness public programme** with a small cohort of approximately 60 seats. Admission is purely score-based through the Catalan EVAU (PAU) system and the nota de admisión formula. There is no proprietary entrance exam or interview. The teaching language is primarily Catalan, with Spanish also used, which is a factor international students must account for. Given the very limited number of seats and the high demand for Medicine in Cataluña, the nota de corte is expected to be in the range typical of other Catalan public medicine programmes (13.5–14.0 on a 14-point scale), though confirmed historical figures are pending publication by the Catalan admissions system.

This programme suits candidates who are Catalan residents or comfortable with the Catalan-language environment, who have very strong nota de admisión scores, and who are willing to study in a smaller-city context with direct proximity to a university hospital.

## Key Facts

| Attribute | Details |
|---|---|
| Full Name | Universitat de Girona — Grado en Medicina |
| Location | Girona, Cataluña, Spain |
| Type | Public university |
| Programme Status | Active — first cohort enrolled 2022-23 |
| Duration | 6 years |
| Total ECTS | 360 ECTS |
| Seats | Approx. 60 per year (ANNUAL_UPDATE_REQUIRED) |
| Teaching Language | Catalan (primary), Spanish |
| Admission | Nota de admisión (PAU-based) — no exam, no interview |
| Annual Tuition | PENDING_CONFIRMATION — regulated by Generalitat de Catalunya decree (ANNUAL_UPDATE_REQUIRED) |
| Main Teaching Hospital | Hospital Universitari de Girona Dr. Josep Trueta |
| Nota de corte (2024-25) | PENDING_CONFIRMATION |

## Program Options

UdG offers a single Grado en Medicina, a standard 6-year programme structured according to the Spanish Ministerial Order ECI/332/2008, which governs all Medicine degrees in Spain. There are no dual-degree or bilingual track variants.

## Program Structure

The programme follows the national framework for Medicine in Spain:

- **Years 1–2 (Basic Sciences):** Biochemistry, Cell Biology, Human Anatomy, Physiology, Histology, Genetics, Biostatistics and research methodology. Heavy lecture and laboratory component.
- **Years 3–4 (Pathological Sciences):** Pathology, Pharmacology, Microbiology, Immunology, Pathophysiology. Introduction to clinical reasoning.
- **Years 5–6 (Clinical Rotations):** Structured hospital rotations across internal medicine, surgery, paediatrics, gynaecology-obstetrics, psychiatry, and primary care. Final-year external clinical placement (Prácticum / Trabajo de Fin de Grado).

Total load: 360 ECTS distributed across 6 academic years, with approximately 60 ECTS per year.

Clinical exposure begins in years 3–4 through supervised hospital visits and full rotations from year 5 onwards, primarily at the Hospital Universitari de Girona Dr. Josep Trueta and associated Girona primary care centres.

## Teaching Methodology

UdG Medicine employs a methodology consistent with modern medical education standards, including:

- **Problem-Based Learning (PBL):** Case-based sessions to develop clinical reasoning from early years.
- **Skills laboratories:** Clinical simulation, procedural skills, and OSCE-style assessments.
- **Bedside teaching:** Supervised patient contact at Hospital Dr. Josep Trueta from year 3–4 onward.
- **Research integration:** UdG encourages students to engage with biomedical research groups, aligned with the university's research strategy.

As a newer programme, UdG has had the advantage of designing its curriculum from scratch with current pedagogical best practices rather than adapting legacy structures.

## Clinical Training

Clinical training is centred on the **Hospital Universitari de Girona Dr. Josep Trueta**, a tertiary public hospital serving the Girona province as part of the Institut Català de la Salut (ICS) network. The hospital offers full secondary and tertiary care services including surgery, oncology, cardiology, traumatology, intensive care, emergency medicine, and mother-and-child services.

Additional clinical sites include:

- Primary care centres (CAP — Centres d'Atenció Primària) in Girona and surrounding areas, managed by ICS
- Hospital Santa Caterina (Salt, Girona) — for psychiatric and long-term care rotations
- Clínica Girona (private, for selected rotations where agreements exist)

The relatively compact health network in Girona offers a distinctive clinical training environment: students benefit from high patient-per-student contact ratios compared to larger universities sharing clinical placements across many more students.

## International Recognition and Opportunities

The Grado en Medicina from UdG is an officially verified degree under the Spanish Ministerio de Educación y Formación Profesional framework (Ministerial Order ECI/332/2008). As a degree from an EU public university, it is automatically recognised across all EU member states through the EU directive on professional qualifications.

For non-EU countries, recognition depends on bilateral agreements and national homologation procedures in the target country. Graduates must pass the MIR examination in Spain to access specialist training.

UdG participates in the **Erasmus+ programme**, allowing students to undertake exchange semesters or short mobility periods at partner European universities. Given the programme's young age, the breadth of Erasmus+ clinical exchange partners specific to Medicine may still be expanding.

**International students** may access the programme through PCE/UNED examinations, Credencial UE, or direct homologation from select countries, subject to Catalan public university admissions rules managed by the Oficina d'Accés a la Universitat de Cataluña (OAU / accesuniversitats.gencat.cat).

## Admission Model

UdG Medicine uses the **standard Spanish public university admissions model** for medicine. There is no proprietary examination, no interview, and no portfolio assessment.

**Nota de admisión formula:**

```
Nota de admisión = 0.6 × Nota media Bachillerato + 0.4 × EVAU general phase
                  + up to 2 specific-phase subjects × ponderation coefficient
```

- Base maximum (without specific phase): **10.0000**
- Maximum with specific phase bonus: **14.0000**
- Candidates compete on this single score for the available seats.

**Ponderation coefficients for UdG Medicine (Cataluña):**

In Cataluña, all public universities share a unified ponderation table set annually by the Interuniversity Council of Cataluña. For Medicine, the key coefficients are:

| Subject | Coefficient |
|---|---|
| Biology | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Chemistry | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Physics | 0.1 (ANNUAL_UPDATE_REQUIRED) |
| Mathematics II | 0.1 (ANNUAL_UPDATE_REQUIRED) |

Candidates should verify the current table at accesuniversitats.gencat.cat before the EVAU cycle begins.

**PCE/UNED access:** International students who have not taken the Spanish Bachillerato may access the Catalan university system by sitting the PCE (Prueba de Competencias Específicas) through UNED. Their nota de admisión is calculated using the same formula, substituting PCE subject grades for EVAU grades. The maximum nota obtainable via PCE is also 14.0000.

## Admission Process

### For Spanish PAU (EVAU) Students

1. Complete Bachillerato and sit the EVAU (PAU) in Cataluña (or another Spanish region — all regional variants are valid for Catalan university applications).
2. Calculate your nota de admisión using the formula above. Biology and Chemistry at coefficient 0.2 provide the maximum bonus.
3. In June–July, submit your university application through the Catalan admission portal (accesuniversitats.gencat.cat). Rank Medicine at UdG among your preferences.
4. Results are published in stages (primera assignació, segona, etc.). Accept your place and pay any required confirmation deposit within the deadline.
5. Matriculate at UdG in July–September for the September intake.

### For International Students (PCE/UNED Route)

1. Register for PCE/UNED examinations — typically held in May. Register well in advance (deadlines usually in February–March).
2. Sit the general-phase PCE subjects required for the Spanish nota media equivalent, plus specific-phase subjects (Biology and Chemistry recommended for maximum bonus).
3. Obtain a PCE certificate from UNED and apply through accesuniversitats.gencat.cat during the standard application window.
4. Provide certified translations of academic records if required.
5. If admitted, complete enrolment at UdG and satisfy any language or administrative requirements.

**Note for international students:** Instruction is primarily in Catalan. Students with no prior Catalan should plan for a language adaptation period. Spanish is understood and used alongside Catalan. There is no formal Spanish-language test requirement at admission, but functional Catalan is expected for effective participation in coursework.

## Admission Timeline

| Event | Approximate Date |
|---|---|
| EVAU / PAU examination (ordinaria) | June (ANNUAL_UPDATE_REQUIRED) |
| Catalan university application window opens | Late June (ANNUAL_UPDATE_REQUIRED) |
| Application deadline (ordinaria) | Early July (ANNUAL_UPDATE_REQUIRED) |
| Primera assignació results | Mid July (ANNUAL_UPDATE_REQUIRED) |
| EVAU / PAU extraordinaria | September (ANNUAL_UPDATE_REQUIRED) |
| Extraordinaria assignments | September (ANNUAL_UPDATE_REQUIRED) |
| Academic year start | Mid-September (ANNUAL_UPDATE_REQUIRED) |

All dates are indicative. Candidates must confirm the current-year calendar at accesuniversitats.gencat.cat.

## Admission Score Distribution

Because UdG Medicine admitted its first cohort in 2022-23, the historical nota de corte dataset is limited to at most three intake cycles at the time of this file's preparation.

| Intake Year | Convocatoria | Nota de corte | Source |
|---|---|---|---|
| 2024-2025 | Ordinaria | PENDING_CONFIRMATION | accesuniversitats.gencat.cat |
| 2023-2024 | Ordinaria | PENDING_CONFIRMATION | accesuniversitats.gencat.cat |
| 2022-2023 | Ordinaria | PENDING_CONFIRMATION | accesuniversitats.gencat.cat |

**Contextual interpretation:** For comparison, other Catalan public medicine programmes (Universitat de Barcelona, UAB, URV, UdL) have historically closed between approximately 13.50 and 13.90 on the 14-point scale. Given the smaller cohort at UdG and the competitive profile of Medicine applicants in Cataluña, the nota de corte is expected to be in a similar competitive range. Candidates should treat any nota de admisión below 13.50 as unlikely to be sufficient and aim for the highest possible specific-phase bonus.

**Trend note:** As the programme matures and gains wider recognition, applicant numbers may increase and push the nota de corte upward. Early cohorts may have benefited from slightly lower competition as the programme was less well known. This dynamic should be monitored by candidates planning for 2026-27 and beyond.

## Costs and Payment Structure

| Cost Item | Amount | Notes |
|---|---|---|
| Annual tuition (1st enrolment per credit) | PENDING_CONFIRMATION EUR/credit | Set by Generalitat de Catalunya decree. ANNUAL_UPDATE_REQUIRED |
| Total estimated annual tuition | PENDING_CONFIRMATION EUR | Approx. 60 ECTS × per-credit rate. ANNUAL_UPDATE_REQUIRED |
| Repeated credit surcharge | ANNUAL_UPDATE_REQUIRED | Higher rate for repeated subjects |
| Administrative fees | PENDING_CONFIRMATION EUR | Enrolment, certificates, etc. ANNUAL_UPDATE_REQUIRED |

**Context:** Catalan public university tuition for first-enrolment credits in the Ciencias de la Salud branch is among the higher-regulated rates in Spain (above €20 per credit in recent years), but remains substantially below any private alternative. Exact per-credit rates are set annually by the Consell Interuniversitari de Cataluña. Candidates should check the current Decree of Public Prices (Decret de Preus) at the Generalitat de Catalunya for current figures.

EU/EEA students pay the same regulated rate as Spanish students. Non-EU international students may be subject to a higher rate depending on the Catalan regulation in force.

## Scholarships and Financial Aid

- **Beca General MEC (Ministerio de Educación y Formación Profesional):** The main state scholarship, means-tested with an academic performance threshold. Covers tuition fees and may include a living allowance. Applicants from any income bracket with strong grades should apply. Application via becas.educacion.gob.es. Deadline typically September. ANNUAL_UPDATE_REQUIRED.
- **Beques de la Generalitat de Catalunya:** The Catalan government supplements MEC grants and offers specific mobility and equity support programmes. Information at agaur.gencat.cat.
- **UdG own scholarships and grants:** UdG administers a limited number of institutional grants for academic excellence and social equity. Details at udg.edu.
- **Erasmus+ mobility grants:** Students can access Erasmus+ funding for exchange semesters, including stipends and fee waivers at host institutions.
- **Private foundations:** Fundació "la Caixa", Fundació Barraquer, and other Catalan foundations offer merit- or need-based awards. Candidates should research independently.

## Accommodation and Cost of Living

Girona is a mid-sized city with a significantly lower cost of living than Barcelona, yet within easy train access (approximately 35–40 minutes to Barcelona by AVE or regional rail). This makes Girona an attractive option for students seeking affordable living while remaining connected to a major metropolitan area.

| Expense Category | Estimated Monthly Range |
|---|---|
| Shared flat (room) | 400–600 EUR |
| University accommodation (if available) | PENDING_CONFIRMATION EUR |
| Groceries | 150–250 EUR |
| Transport (local) | 30–60 EUR |
| Total estimated monthly budget | 700–1,100 EUR |

All figures are approximate and ANNUAL_UPDATE_REQUIRED.

UdG operates student accommodation; availability for Medicine students should be confirmed directly with the university's housing office.

## International Exchange and Mobility Programs

UdG is a member of the Erasmus+ programme and has established partnerships with European universities. As the Medicine programme matures, bilateral agreements specific to medical student exchange are expected to develop further.

- **Erasmus+:** Exchange semesters available at partner universities in EU member states. Medicine-specific partnerships: PENDING_CONFIRMATION.
- **SICUE:** National mobility scheme within Spain, allowing temporary transfers to other Spanish public universities.
- **Elective rotations abroad:** Final-year students may be able to arrange clinical electives at foreign institutions through bilateral agreements or on an individually arranged basis, subject to academic approval.

UdG's international office (Oficina de Relacions Internacionals) provides support for outgoing and incoming exchange students.

## MIR Preparation and Professional Outcomes

As of 2026, UdG Medicine has not yet graduated its first cohort (inaugural 2022-23 cohort would complete 6 years in 2028-29). Therefore:

- **MIR pass rate:** Not yet available. No graduates have sat the MIR from this programme.
- **Graduate employment outcomes:** Not yet available.

The MIR (Médico Interno Residente) examination is the national competitive examination all Medicine graduates must pass to access specialist residency training in Spain. It is entirely independent of the university attended and tests a broad clinical and scientific knowledge base.

Students are strongly encouraged to begin MIR preparation from their third or fourth year of study. Third-party MIR preparation academies and online platforms are widely used by Spanish Medicine students regardless of university.

**For non-EU international students:** Graduates must complete the MIR process or apply for homologation of their Spanish degree in their home country. EU graduates can access practice under the EU professional qualifications directive.

## Strategic Fit

### Good Fit For

- Candidates with a **nota de admisión consistently above 13.50** who cannot access or prefer not to apply to the larger Catalan medicine faculties (UB, UAB, URV, UdL) and see UdG's smaller cohort as an opportunity.
- Students **comfortable with Catalan as a language of instruction** or willing to acquire functional Catalan prior to or during the programme.
- Candidates who prefer a **smaller university city environment** — Girona's historic centre and compact urban fabric offer a different quality of life from Barcelona.
- Students interested in **direct hospital access** — the small cohort size relative to the Hospital Trueta clinical network may translate into higher per-student clinical exposure than at higher-volume urban faculties.
- **Catalan residents** for whom UdG is their regional public university and who may benefit from quota or preference mechanisms in Catalan admissions.

### Less Suitable For

- Candidates whose nota de admisión is **below 13.50** — Medicine at any Spanish public university is highly competitive and an insufficient score will result in rejection regardless of university choice.
- Students who **do not speak Spanish or Catalan** — the programme has no official English-language track; functional bilingual competency is essential.
- Students seeking a **long-established programme** with a proven MIR track record — UdG Medicine is very new and the first cohort will not graduate until approximately 2028-29.
- Candidates seeking a **large urban campus** with extensive student services, wide Erasmus+ clinical partnerships, and an established alumni network.

## Risks and Considerations

1. **Programme immaturity:** The UdG Medicine programme launched in 2022-23. As of 2026, no cohort has graduated. WFME (World Federation for Medical Education) accreditation status and MIR outcomes are not yet established. Students bear some uncertainty risk regarding the programme's long-term reputation trajectory.

2. **Limited nota de corte history:** With only two to three completed admission cycles at time of writing, there is insufficient data to reliably predict score trends. Candidates cannot rely on a stable nota de corte baseline.

3. **Language of instruction:** Primary instruction is in Catalan. Students without prior Catalan exposure will face an additional challenge on top of the inherent difficulty of Medicine. There is no provision for Spanish-only instruction.

4. **Small regional clinical network:** While the smaller cohort-to-hospital ratio may benefit clinical exposure, the Girona health network is less diverse than those of Barcelona, Madrid, or Valencia. Students interested in rare disease specialisms or highly subspecialized rotations may find fewer options locally.

5. **Nota de corte volatility:** Newly established programmes often attract increasing applicant numbers as awareness grows, potentially driving nota de corte upward over successive years. Candidates planning for future cycles should monitor this closely.

6. **Regional residency quota:** Cataluña applies a residence-based quota that may affect non-Catalan-resident candidates. Check current OAU rules for the applicable cycle.

## Important Notes

- All admission dates and nota de corte figures are ANNUAL_UPDATE_REQUIRED. Verify directly at accesuniversitats.gencat.cat for the current cycle.
- Tuition fees are set by the Generalitat de Catalunya and are subject to annual adjustment. ANNUAL_UPDATE_REQUIRED.
- The programme's ANECA verification and accreditation status should be confirmed at the time of application.
- International students via PCE/UNED must register for PCE examinations several months before the June EVAU cycle — missing PCE registration deadlines forecloses admission for that year.

## Key Insight

UdG Medicine is a **viable but high-risk admission target** for the 2026-27 cycle. Its small seat count (approximately 60) and location in one of Spain's most academically competitive regions (Cataluña) will keep the nota de corte in the very-high range. The programme's key differentiators — smaller cohort, direct hospital integration, and a lower cost of living than Barcelona — are real advantages for candidates who qualify. However, the lack of historical MIR data and the Catalan-language environment create genuine uncertainties that candidates must weigh carefully.

## Final Takeaway

For candidates with nota de admisión above 13.50 who are comfortable studying in Catalan and interested in a smaller, more intimate university environment with direct clinical hospital access, UdG Medicine is a legitimate and potentially strategically advantageous choice among Cataluña's public medicine options. The programme is new but structurally sound. The key watchpoint for 2026-27 is confirming the nota de corte for 2024-25, as this will be the most reliable predictor of score requirements for the upcoming cycle.

## Frequently Asked Questions

**How is the nota de admisión calculated for UdG Medicine?**
The nota de admisión = 0.6 × Bachillerato average grade + 0.4 × EVAU general phase grade, plus bonuses from up to 2 specific-phase subjects multiplied by their ponderation coefficient (0.1 or 0.2). The maximum possible score is 14.0000. For Medicine at UdG, Biology and Chemistry receive coefficient 0.2 in the Catalan ponderation table, making them the most valuable specific-phase subjects.

**What is the nota de corte and what was it for UdG Medicine?**
The nota de corte is the lowest nota de admisión accepted in the last admission cycle for a given degree and university. For UdG Medicine, confirmed historical nota de corte figures are pending publication. Given the competitive profile of Catalan medicine admissions, expect a nota de corte in the range of 13.50–14.00. Check accesuniversitats.gencat.cat for the official figure each cycle.

**Can international students apply via PCE?**
Yes. International students who have not completed the Spanish Bachillerato can sit the PCE/UNED examinations (Prueba de Competencias Específicas) and use those results in the standard nota de admisión formula. They apply through the same Catalan admissions portal (accesuniversitats.gencat.cat). PCE registration deadlines are several months before the June examination — plan accordingly.

**What are the tuition fees?**
Tuition is set annually by the Generalitat de Catalunya and is regulated per credit. The exact per-credit price for Health Sciences at UdG is PENDING_CONFIRMATION and subject to ANNUAL_UPDATE_REQUIRED. Check the current Decret de Preus at the Generalitat de Catalunya website for the active rate.

**When do I apply?**
Applications for the main (ordinaria) round are submitted through accesuniversitats.gencat.cat in late June to early July, after EVAU results are published. A second (extraordinaria) round follows in September for students sitting the September EVAU. All deadlines are ANNUAL_UPDATE_REQUIRED.

**What are the ponderation coefficients at UdG?**
Cataluña uses a unified ponderation table shared by all its public universities. For Medicine, Biology and Chemistry have coefficient 0.2, while Physics and Mathematics II have coefficient 0.1. These values are set annually by the Consell Interuniversitari de Cataluña. ANNUAL_UPDATE_REQUIRED — verify at accesuniversitats.gencat.cat before the EVAU cycle.

**Is the programme taught in Catalan?**
Yes, Catalan is the primary language of instruction. Spanish is also used in teaching. There is no dedicated Spanish-only track. Non-Catalan-speaking students should plan for a language adaptation period. There is no formal language test required at admission, but functional Catalan is needed for effective study.

**When does clinical training begin?**
Clinical contact is typically introduced in years 3–4 through supervised visits, with full hospital rotations commencing in years 5–6 at the Hospital Universitari de Girona Dr. Josep Trueta and associated primary care centres.

**Does UdG Medicine have WFME accreditation?**
Given the programme's recent establishment (2022-23), WFME accreditation is PENDING_CONFIRMATION. Candidates planning international practice should verify accreditation status at the time of application. The degree is verified by ANECA under Spanish national standards.
