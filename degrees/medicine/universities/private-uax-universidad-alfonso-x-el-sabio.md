---
id: uax-medicine

type: university
subtype: private

name: Universidad Alfonso X el Sabio
short_name: UAX

degree: Medicine

last_update: 2026-05-27

valid_for_intake: 2026-2027

location:
  city: Madrid
  region: Comunidad de Madrid
  country: Spain

strategic_tags:
  - core_option
  - high_cost
  - rolling_admissions
  - early_application_advantage
  - exam_heavy
  - interview_heavy
  - academic_exam_required
  - strong_clinical_exposure
  - medium_competitiveness

admission:
  intake_month: September

  applications_open_date: ANNUAL_UPDATE_REQUIRED # Rolling process; no fixed opening date

  rolling_admissions:
    enabled: true
    estimated_end_date: ANNUAL_UPDATE_REQUIRED # Seats are limited; process runs until filled

  admission_rounds:
    enabled: false
    count: NULL
    rounds: []

  exam_required: true
  interview_required: true

academic_record:
  minimum_requirement:
    enabled: PENDING_CONFIRMATION
    grade_source: PENDING_CONFIRMATION
    minimum_grade: PENDING_CONFIRMATION
    # PAU or equivalent required to enroll; minimum grade for admission test eligibility: PENDING_CONFIRMATION

  competitive_filter:
    enabled: false
    grade_source: NULL
    approx_candidates_selected: NULL

curriculum:
  international_curriculums_accepted: PENDING_CONFIRMATION
  # International students must have credentials equivalent to Spanish Bachillerato+PAU
  # Spanish language B2 certificate required for non-native speakers

competitiveness:
  level: medium_high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: PENDING_CONFIRMATION # Not published per campus
  applicants_per_seat: PENDING_CONFIRMATION

  last_admitted_scores:
    - intake_year: PENDING_CONFIRMATION
      round: NULL
      score: PENDING_CONFIRMATION
      score_type: PENDING_CONFIRMATION
      notes: PENDING_CONFIRMATION

international_profile:
  international_students_percentage: PENDING_CONFIRMATION

  international_nationalities:
    - country: PENDING_CONFIRMATION
      percentage: PENDING_CONFIRMATION

programs:
  - id: uax-medicine-madrid

    campus: Villanueva de la Cañada, Madrid

    modality: standard

    strategic_tags:
      - core_option
      - high_cost
      - rolling_admissions
      - early_application_advantage
      - exam_heavy
      - interview_heavy
      - academic_exam_required
      - strong_clinical_exposure

    teaching_languages:
      - Spanish

    regional_language_possible: false
    regional_language: NULL

    language_requirements:
      minimum_spanish_level_non_native: B2
      # Students without B2 Spanish must complete UAX's Spanish language accompaniment program:
      # 2,400€ (year 1), 800€ (years 2 and 3)
      english_required: false
      minimum_english_level: NULL

    seats: PENDING_CONFIRMATION

    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: PENDING_CONFIRMATION
      applicants_per_seat: PENDING_CONFIRMATION

      last_admitted_scores:
        - intake_year: PENDING_CONFIRMATION
          round: NULL
          score: PENDING_CONFIRMATION
          score_type: PENDING_CONFIRMATION
          notes: PENDING_CONFIRMATION

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
          rounds:
            - round: NULL
              application_deadline: NULL
              exam_date: NULL
              results_date: NULL
              deposit_deadline: NULL
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
      overall_model_type: PENDING_CONFIRMATION
      # Model appears to be weighted (exam + interview) but scoring formula not published

      admission_pathways:
        - eligible_profiles:
            - bachillerato_pau_health_sciences
            - fp_grade_superior_equivalent
            - mayores_25_anos_access
            - international_equivalent_secondary_plus_pau_equivalent

          components:
            - component: academic_exam
              enabled: true
              role: weighted
              weight: PENDING_CONFIRMATION
              exam_variant: onsite_internal_exam
              exam_format: multiple_choice
              delivery_mode: conditional_online
              online_conditions: "General UAX admissions policy allows presencial or online test. Whether online option applies specifically to the Medicine exam is PENDING_CONFIRMATION."

              subjects:
                - Biology (30 questions)
                - Chemistry (20 questions)

              syllabus_alignment:
                biology:
                  scope:
                    - full_baccalaureate
                  notes: "30 MCQ questions. Standard Bachillerato biology curriculum. No further syllabus breakdown published."

                chemistry:
                  scope:
                    - full_baccalaureate
                  notes: "20 MCQ questions. Standard Bachillerato chemistry curriculum."

                physics:
                  scope:
                    - not_applicable
                  notes: "Physics not included in UAX Medicine exam."

                mathematics:
                  scope:
                    - not_applicable
                  notes: "Mathematics not included."

                other_subjects:
                  - subject: NULL
                    scope:
                      - not_applicable
                    notes: NULL

              exam_difficulty:
                level: medium
                rationale:
                  - full_baccalaureate_scope
                  - memorization_heavy
                notes: "50 total MCQ (30 biology + 20 chemistry). Standard Bachillerato scope. No sample questions or detailed syllabus published beyond subject names."

              best_attempt_counts: NULL
              notes: "Rolling exam scheduling: available Monday–Friday at 10:00h and 16:00h, and some Saturdays. Specific test fee: 125€."

            - component: interview
              enabled: true
              role: PENDING_CONFIRMATION
              weight: PENDING_CONFIRMATION
              interview_format: PENDING_CONFIRMATION
              delivery_mode: PENDING_CONFIRMATION
              notes: "Personal interview is the second and final phase of the admission test. Whether eliminatory, its weight in the final score, and its format are PENDING_CONFIRMATION."

  - id: uax-medicine-oviedo

    campus: Centro Universitario Alfonso X el Sabio Asturias, Oviedo

    modality: standard

    strategic_tags:
      - core_option
      - high_cost
      - rolling_admissions
      - early_application_advantage
      - exam_heavy
      - interview_heavy
      - academic_exam_required

    teaching_languages:
      - Spanish

    regional_language_possible: false
    regional_language: NULL

    language_requirements:
      minimum_spanish_level_non_native: B2
      english_required: false
      minimum_english_level: NULL

    seats: PENDING_CONFIRMATION

    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: PENDING_CONFIRMATION
      applicants_per_seat: PENDING_CONFIRMATION

      last_admitted_scores:
        - intake_year: PENDING_CONFIRMATION
          round: NULL
          score: PENDING_CONFIRMATION
          score_type: PENDING_CONFIRMATION
          notes: "Oviedo campus is new for 2026-27. No prior intake data exists."

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
          rounds:
            - round: NULL
              application_deadline: NULL
              exam_date: NULL
              results_date: NULL
              deposit_deadline: NULL
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
      overall_model_type: PENDING_CONFIRMATION

      admission_pathways:
        - eligible_profiles:
            - bachillerato_pau_health_sciences
            - fp_grade_superior_equivalent
            - mayores_25_anos_access
            - international_equivalent_secondary_plus_pau_equivalent

          components:
            - component: academic_exam
              enabled: true
              role: weighted
              weight: PENDING_CONFIRMATION
              exam_variant: onsite_internal_exam
              exam_format: multiple_choice
              delivery_mode: conditional_online
              online_conditions: "Same as Madrid campus. PENDING_CONFIRMATION for Medicine-specific online availability."

              subjects:
                - Biology (30 questions)
                - Chemistry (20 questions)

              syllabus_alignment:
                biology:
                  scope:
                    - full_baccalaureate
                  notes: "Same exam format as Madrid campus."

                chemistry:
                  scope:
                    - full_baccalaureate
                  notes: "Same exam format as Madrid campus."

                physics:
                  scope:
                    - not_applicable
                  notes: NULL

                mathematics:
                  scope:
                    - not_applicable
                  notes: NULL

                other_subjects:
                  - subject: NULL
                    scope:
                      - not_applicable
                    notes: NULL

              exam_difficulty:
                level: medium
                rationale:
                  - full_baccalaureate_scope
                  - memorization_heavy
                notes: "Same exam as Madrid campus."

              best_attempt_counts: NULL
              notes: "Rolling scheduling. 125€ test fee. Oviedo campus new for 26/27 — limited precedent for exam logistics at this location."

            - component: interview
              enabled: true
              role: PENDING_CONFIRMATION
              weight: PENDING_CONFIRMATION
              interview_format: PENDING_CONFIRMATION
              delivery_mode: PENDING_CONFIRMATION
              notes: "Personal interview. Same model as Madrid. Specific format at Oviedo campus: PENDING_CONFIRMATION."
---

# Universidad Alfonso X el Sabio (UAX)

## Overview

The Universidad Alfonso X el Sabio (UAX) is one of Spain's most established private universities, offering a Medicine degree at its main campus in Villanueva de la Cañada (Madrid) and, as of the 2026-27 intake, at a new affiliated center in Oviedo (Asturias). UAX presents itself as the leading private Medicine institution in Spain — citing a #1 ranking among private universities according to ConSalud — and backs this positioning with a 96% MIR pass rate, 1,800 documented practical hours, and infrastructure claims including the largest Virtual Simulation Hospital in Europe.

At 24,250€ per year for 2026-27, UAX is among the most expensive private Medicine programs available in Spain. This price point positions it at the premium end of the private sector, significantly above mid-market alternatives. The admission model operates on rolling admissions with no fixed exam dates: admission tests run Monday through Friday and some Saturdays, making timing of application strategically relevant but not tied to annual cycles.

A distinctive feature of UAX Medicine is its early integration of Digital Health as a formal Year 3 subject, its UAXmakers educational model (interdisciplinary case-based learning involving real hospital challenges), and a bundled Advanced CPR Diploma included in the degree from 2026-27. The Oviedo campus, new for 26/27, operates under an affiliated center structure (Centro Adscrito) and its curriculum plan is still undergoing formal modification under Decreto 110/2025 of the Principado de Asturias.

## Quick Evaluation

- **Campuses:** Madrid (Villanueva de la Cañada, established) and Oviedo (new from 2026-27, affiliated center)
- **Tuition:** 24,250€/year (2026-27) — among the highest in Spanish private Medicine
- **Admission model:** Rolling — Biology+Chemistry MCQ test (50 questions) + personal interview; no fixed exam dates
- **Exam fee:** 125€ (payable before sitting the specific Medicine exam)
- **MIR stats:** 96% pass rate (UAX-published); 90%+ graduates doing MIR in "best hospitals in Spain"
- **Clinical training:** 1,800 practical hours; 38+ specialty rotations; Virtual Simulation Hospital (2,000m²)
- **Digital Health:** Dedicated subject in Year 3; claims to be first Spanish faculty with formal Digital Medicine training
- **WFME accreditation:** PENDING_CONFIRMATION
- **Oviedo risk:** Brand new campus for 26/27; curriculum still being formally modified; no prior track record
- **Key gap:** Seats per campus, scoring formula, and minimum grade requirements not published

## Key Facts

| Feature | Value |
|---|---|
| Full name | Universidad Alfonso X el Sabio |
| Short name | UAX |
| Faculty | Facultad de Medicina y Ciencias de la Salud |
| Main campus | Villanueva de la Cañada, Madrid |
| Secondary campus | Centro Universitario UAX Asturias, Oviedo (from 26/27) |
| ECTS | 360 |
| Duration | 6 years |
| Language | Spanish |
| Seats (Madrid) | PENDING_CONFIRMATION |
| Seats (Oviedo) | PENDING_CONFIRMATION |
| Annual tuition 2026-27 | 24,250€ — ANNUAL_UPDATE_REQUIRED |
| Reserva de plaza | 3,000€ — ANNUAL_UPDATE_REQUIRED |
| Matrícula | 1,350€ — ANNUAL_UPDATE_REQUIRED |
| Monthly installments | 10 × 1,990€ — ANNUAL_UPDATE_REQUIRED |
| Admission test fee | 125€ (specific Medicine exam) |
| Practical hours | 1,800 |
| Clinical rotations | 38+ specialties |
| Virtual Hospital | >2,000m², claimed largest in Europe |
| MIR pass rate | 96% (UAX-published) — ANNUAL_UPDATE_REQUIRED |
| Academic year start | September — ANNUAL_UPDATE_REQUIRED |

## Program Options

**Madrid (Villanueva de la Cañada):** The established program, operating since UAX launched its Medicine faculty. All six years delivered at the Madrid campus, with clinical rotations at affiliated hospitals in the Comunidad de Madrid. Uses the UAXmakers educational model and has the Virtual Simulation Hospital on campus.

**Oviedo (Centro Universitario Alfonso X el Sabio Asturias):** A new campus intake opening for 2026-27, authorized by Decreto 110/2025 of the Principado de Asturias. The degree plan is described as "in process of modification" for delivery at this affiliated center. Clinical rotations use Asturian hospitals. Students enrolled at Oviedo are integrated into the UAX academic system but the campus operates as a centro adscrito, not a direct UAX faculty. No prior intake history exists.

The two programs share the same brand, curriculum framework, admission process, and tuition pricing structure. Prospective students should consider Oviedo's first-year status as a material risk factor and verify the finalized curriculum plan before committing.

There is also a Programa de Acceso a Medicina — a UAX-run preparatory program that grants guaranteed admission to the Medicine degree upon successful completion of all subjects. Details on cost, duration, and exact terms of the access guarantee are available on the UAX website. This represents an alternative entry route for students who do not pass the standard admission test.

## Program Structure

**Years 1–2 — Biomedical Foundation.** Year 1 (60 ECTS): Morfología I and II, Biología, Bioquímica I, Estadística, Bioética, Genética, Inmunología, Historia de la Medicina. Year 2 (60 ECTS): Morfología III and IV, Microbiología, Bioquímica II, Biofísica y Radiología Básica, Psicología Médica, plus 6 ECTS elective. Pre-clinical phase with no hospital contact.

**Year 3 — Transition and First Clinical Tools.** 60 ECTS: Anatomía Patológica, Farmacología, Procedimientos Médico-Quirúrgicos Generales, Bases jurídicas, Epidemiología, Salud Digital (Digital Health, 5 ECTS OB), Medicina Física y Rehabilitación, Medicina Preventiva. Digital Health as a formal integrated subject sets UAX apart from most Spanish private Medicine programs.

**Year 4 — Applied Clinical Sciences I.** 60 ECTS: Clínica Práctica I, Obstetricia y Ginecología, Patología Cardiovascular/Neumológica/Neurológica, Dermatología, Patología Infecciosa, Oftalmología, Otorrinolaringología. First sustained clinical rotations.

**Year 5 — Applied Clinical Sciences II.** 60 ECTS: Clínica Práctica II, Pediatría, Digestivo, Reumatología-Traumatología, Endocrinología, Uro-Nefrológica, Psiquiatría, Onco-Hematología y Genética Clínica.

**Year 6 — Intensive Clinical Phase and TFG.** 66 ECTS: Clínica Práctica III (36 ECTS), Trabajo de Fin de Grado (6 ECTS), Farmacología Clínica y Toxicología, Primary Care and Geriatrics, plus 6 ECTS elective. The heaviest clinical year, with Year 5 and 6 including Family and Community Medicine rotations at Primary Care centres throughout the Comunidad de Madrid.

**Plan 2026:** A revised curriculum plan is being phased in from Year 1 of the 2026-27 cohort, replacing the current plan one year at a time through 2031-32. Students entering in 26-27 will be the first cohort to follow the new Plan from Year 1; their upper-year counterparts will complete the existing plan. The exact changes in Plan 2026 are not yet published.

Total official practical hours: 1,800.

## Teaching Methodology

UAX uses the UAXmakers Educational Model: students from multiple health sciences degrees collaborate in interdisciplinary teams to address real clinical challenges issued by partner hospitals. This project-based component supplements the conventional lecture structure.

A dedicated UAX Skill School program runs throughout the degree, awarding a Professional Certificate in five competencies: Analytical Thinking, Leadership and Ethics, Working in Agility and Diverse Teams, Storytelling, and Disruptive Thinking. This certificate is included in the degree cost and appears on the student's official record.

The Digital Medicine integration — including telemedicine, wearable health monitoring, clinical data analysis, predictive medicine, and digital waiting list management — is incorporated as a formal curriculum subject (Year 3), not merely as a supplementary module. UAX claims to be the first Spanish medical faculty to formally integrate Digital Medicine at this depth.

UAX claims that more than 90% of the professors teaching in the first years of the Medicine degree also practise clinically, maintaining direct hospital connections alongside their academic roles.

## Clinical Training

**Madrid:** Clinical rotations are distributed across five named affiliated hospital units, covering 38+ medical and surgical specialties. Named centers: Hospital Universitario Severo Ochoa (Leganés), Hospital San Francisco de Asís (Madrid), Hospital Universitario del Tajo (Aranjuez), Quirónsalud hospitals, Hospital de la Cruz Roja. From Year 5, family medicine training takes place at Primary Care Centres across the Comunidad de Madrid. Total: 1,800 practical hours.

**Oviedo:** Clinical rotations at hospitals in the Principado de Asturias. Named centers: Hospital Vital Álvarez Buylla (Mieres), Clínica Asturias, Hospital Begoña, Hospital Gijón, Hospital Covadonga. UAX states there are additional centers beyond those named. As Oviedo is a new campus from 26/27, the full clinical network and confirmed rotation slots are PENDING_CONFIRMATION. ANNUAL_UPDATE_REQUIRED.

**Virtual Simulation Hospital (Madrid):** An on-campus facility of more than 2,000m² described as the largest virtual simulation hospital in Europe. It replicates hospital room dynamics for procedural and diagnostic training using tools including Body Interact, Practicum Script, Portal SECTRA, a human dissection room, and specialized laboratories. The Virtual Hospital supports simulation throughout the degree, in addition to real hospital placements.

**Advanced CPR Diploma:** Bundled with the degree (listed as "Grado en Medicina + Diploma Avanzado de RCP"), providing high-level resuscitation training as an integrated component.

ANNUAL_UPDATE_REQUIRED: Clinical center lists and rotation capacities may change each academic year.

## International Recognition and Opportunities

**WFME Accreditation:** PENDING_CONFIRMATION. Not mentioned on any publicly available UAX Medicine page. Students intending to practice in WFME-requiring jurisdictions (United States, Canada, certain Middle Eastern countries) should verify directly with UAX or the relevant foreign regulatory authority before enrolling.

**Spanish national recognition:** Official degree, eligible for MIR examination and EU-wide professional recognition. The Medicine degree is governed by Orden ECI/332/2008 of February 13.

**Erasmus+ and international mobility:** UAX has an international office (Oficina de Relaciones Internacionales) and offers Erasmus+ (both studies and practices), international exchange programs outside Europe (Study Abroad, Mundus), and SICUE national mobility. Whether Erasmus or mobility agreements apply specifically to Medicine students — and which destinations are available — is PENDING_CONFIRMATION. Flywire is available for international tuition payments for non-EU students.

**Rankings:** UAX claims the #1 position among Spanish private universities for Medicine training, citing ConSalud rankings. Independent verification and methodology details are not published alongside this claim.

**Quality certifications:** PENDING_CONFIRMATION for institution-level certifications applicable to the Medicine faculty.

## Admission Model

UAX operates a rolling admission model with no fixed annual exam calendar. Admission to Medicine proceeds through the following stages:

1. **Contact and advisor orientation:** A UAX advisor guides applicants through the available pathways, eligibility, and timing.
2. **Admission test (Prueba Específica de Medicina):** A 50-question MCQ test in two sections — Biology (30 questions) and Chemistry (20 questions) — sitting as scientific aptitude evaluation. Fee: 125€, payable before the test. Tests run Monday–Friday at 10:00h and 16:00h, and some Saturdays.
3. **Personal interview:** A personal interview as the second component of the specific admission test. Weight and format: PENDING_CONFIRMATION.
4. **Admission decision:** Based on combined test and interview performance. Scoring formula and minimum required score: PENDING_CONFIRMATION.
5. **Place reservation and enrollment:** Once admitted, candidates pay the reserva de plaza (3,000€) and matrícula (1,350€), then complete administrative enrollment.

**Alternative entry pathway — Programa de Acceso a Medicina:** UAX offers a dedicated pre-Medicine access program. Students who pass all subjects in this program receive a guaranteed place in the Medicine degree, bypassing the standard admission test. Cost and duration of the access program: available on UAX website; PENDING_CONFIRMATION for inclusion in this file.

**PAU requirement:** Applicants must hold a Bachillerato title and PAU pass (or accredited equivalent) to be eligible. Students without these qualifications must use the Acceso Mayores de 25 Años pathway or another official access route.

## Admission Process

1. **Request information / first contact:** Fill in the online form, call +34 91 910 01 70, or visit UAX Madrid. An advisor will respond to guide the process.
2. **Confirm eligibility:** Verify that your academic credentials (Bachillerato + PAU or equivalent) meet UAX's requirements. Non-Spanish credentials require evaluation.
3. **Pay the admission test fee (125€):** Transfer to Banco Santander (ES88-0049-5984-90-2210092481), indicating full name and DNI in the reference.
4. **Schedule and sit the test:** Monday–Friday at 10:00h or 16:00h (some Saturdays). Bring: DNI/residence card + official compulsory academic certificate + payment proof.
5. **Personal interview:** Second phase, conducted on the same day or scheduled separately — PENDING_CONFIRMATION on timing.
6. **Receive admission decision:** UAX evaluates test + interview and communicates admission.
7. **Reserve place:** Pay 3,000€ reserva de plaza before the deadline communicated.
8. **Formalize enrollment (matrícula):** Pay 1,350€ and complete required legal documentation including proof of PAU access, DNI, and academic certificates.
9. **Begin monthly payments:** First monthly installment (1,990€) due before classes start, then 9 further monthly installments.

International students should contact UAX to clarify credential recognition before beginning: Tel +34 91 910 01 70 / admisiones@uax.es.

## Admission Timeline

| Stage | Timing | Notes |
|---|---|---|
| Applications / first contact | Year-round | Rolling; earlier is better for seat availability — ANNUAL_UPDATE_REQUIRED |
| Admission test scheduling | Mon–Fri 10h/16h + some Saturdays | No fixed date; by appointment — ANNUAL_UPDATE_REQUIRED |
| Admission test fee payment | Before sitting test | 125€; bank transfer |
| Interview | Same session or TBD | PENDING_CONFIRMATION |
| Admission decision | After test + interview | Timeline not published |
| Reserva de plaza payment | After admission | 3,000€ — ANNUAL_UPDATE_REQUIRED |
| Matrícula payment | After reserva | 1,350€ — ANNUAL_UPDATE_REQUIRED |
| First monthly installment | Before class start | 1,990€ — ANNUAL_UPDATE_REQUIRED |
| Academic year start | September | ANNUAL_UPDATE_REQUIRED |
| Places available while seats remain | Year-round until filled | ANNUAL_UPDATE_REQUIRED |

## Admission Score Distribution

UAX does not publish a scoring formula for its Medicine admission process. The publicly available information confirms two components — a 50-question Biology+Chemistry MCQ test and a personal interview — but does not specify their relative weights, minimum passing scores, or whether either component is eliminatory.

This absence of a published scoring formula has two strategic implications. First, applicants cannot calculate their probability of admission based on a practice test score alone — the interview's contribution is unknown and uncontrollable. Second, there is no documented way to compare UAX admission competitiveness to other programs using quantitative benchmarks.

What can be inferred from the rolling model: UAX likely admits candidates as soon as they meet an unstated threshold, with priority going to those who apply earliest in the cycle, up to seat capacity. Under this model, being the first eligible candidate in a given intake period is as strategically valuable as having the highest score. Early application reduces the risk of being displaced by other candidates.

The Programa de Acceso a Medicina pathway bypasses this uncertainty entirely — students who complete all access program subjects receive guaranteed placement. For students uncertain about their Biology/Chemistry exam performance, the access program may represent a more reliable route, at the cost of an additional preparation year.

## Costs and Payment Structure

| Concept | Amount | Notes |
|---|---|---|
| Annual tuition 2026-27 | 24,250€ | Highest reported annual price in Spanish private Medicine — ANNUAL_UPDATE_REQUIRED |
| Reserva de plaza | 3,000€/year | Payable each academic year — ANNUAL_UPDATE_REQUIRED |
| Matrícula | 1,350€/year | Payable each academic year — ANNUAL_UPDATE_REQUIRED |
| Monthly installments (docencia) | 10 × 1,990€/year | = 19,900€/year in tuition installments — ANNUAL_UPDATE_REQUIRED |
| Total Year 1 cost | 24,250€ | Reserva + Matrícula + 10 cuotas — ANNUAL_UPDATE_REQUIRED |
| Total degree estimate | ~145,500€ | 6 × 24,250€, assuming flat pricing — ANNUAL_UPDATE_REQUIRED |
| Admission test fee | 125€ | One-time, per test attempt; paid before sitting exam |
| Spanish language program (Year 1, non-native) | 2,400€ | Required for non-B2 Spanish speakers |
| Spanish language program (Years 2–3) | 800€/year | Required for non-B2 speakers continuing the program |
| Transport to clinical centers | Additional | Not included in tuition |
| Clinical attire and equipment | Additional | Lab coat, scrubs, clinical footwear not included |
| Books and study materials | Additional | Not included |

**Discounts and financial aid (no accumulation except pronto pago):**

| Aid type | Amount | Notes |
|---|---|---|
| Pronto pago (full year upfront) | 2% on docencia | Compatible with other discounts |
| Continuidad de estudios | Up to 25% on docencia | For prior UAX qualification holders |
| Alumni UAX | 10% | For UAX graduates enrolling in new degree |
| Familiares de estudiantes UAX | 5% | Direct family up to 2nd degree |
| Deportistas de élite | 20–50% | Elite athletes |
| OEI (Iberoamérica) | 50% on docencia | Iberoamerican nationals or legal residents in OEI countries |

**Note on Becas de Excelencia:** UAX's institutional excellence scholarships explicitly exclude the Grado en Medicina. Students should not factor this scholarship into financial planning for the Medicine degree.

**Financing:** UAX works with multiple financial institutions to offer payment plans. Contact admisiones@uax.es for details.

**Payment methods:** TPV online, Bizum, Flywire (international), bank card on campus, bank transfer (PagoNxt personalised account), cash deposit to Banco Santander account ES50 0049 1958 81 2210000511.

## Scholarships and Financial Aid

No Medicine-specific scholarship program equivalent to UNAV's Becas Prof. Jiménez Vargas has been identified for UAX Medicine.

The Becas de Excelencia UAX — the university's main merit scholarship — explicitly excludes the Grado en Medicina.

Available scholarships and financial aid compatible with UAX Medicine:

- **Becas MEC (Ministerio de Educación):** Standard national university scholarship. Requires passing ≥50% of enrolled credits in Year 1 and ≥65% in subsequent years. UAX Medicine students may qualify if they meet the academic conditions.
- **Becas de Excelencia de la Comunidad de Madrid:** For students with excellent academic records. Application submitted to the Consejería de Educación.
- **Santander Complemento de Prácticas (2025, II Edición):** Employability support for enrolled degree students.
- **Becas OEI:** 50% discount on docencia for Iberoamerican nationals or legal residents in OEI countries.
- **Ayuda deportistas de élite:** 20–50% discount. Requires UAX elite athlete classification.
- **Continuidad de estudios UAX:** Up to 25% for students with prior UAX qualifications enrolling in another program.

All UAX aid programs are limited by availability and subject to conditions reviewed annually. Contact: admisiones@uax.es / +34 91 910 01 70.

## Accommodation and Cost of Living

**Madrid (Villanueva de la Cañada):** The UAX main campus is located in Villanueva de la Cañada, a suburban municipality 25–30 km west of central Madrid. Accessible by Cercanías (C-10) and by car.

| Concept | Estimated range | Notes |
|---|---|---|
| Campus/nearby private room | 400–700€/month | University residences on or near campus — ANNUAL_UPDATE_REQUIRED |
| Madrid city private room (shared flat) | 600–900€/month | Higher cost; longer commute to campus |
| Meals | 250–400€/month | |
| Transport (Cercanías + metro) | 40–70€/month | Student pass available |
| Books and materials | 600–900€/year | Estimated |
| **Total monthly living (excl. tuition)** | **~700–1,200€** | Location-dependent |

**Oviedo:** A mid-sized city with significantly lower cost of living than Madrid. Private room rentals near the city center run approximately 300–500€/month. The UAX Asturias campus is new for 26/27; accommodation infrastructure is PENDING_CONFIRMATION.

## International Exchange and Mobility Programs

UAX has a formal international infrastructure including an Oficina de Relaciones Internacionales and the following mobility programs: Erasmus+ Estudios, Erasmus+ Prácticas, Study Abroad (non-European exchanges), Mundus Santander, and SICUE+ national mobility.

Whether active agreements covering Medicine students specifically exist, how many places are available, and whether credits obtained abroad are fully recognized within the Medicine degree plan is PENDING_CONFIRMATION for all programs. UAX's mobility search tool is at uax.adv-pub.moveonfr.com/homepage/. Students planning to use mobility should contact the Oficina de Relaciones Internacionales before relying on this option.

## MIR Preparation and Professional Outcomes

UAX positions MIR preparation as a core institutional differentiator for its Medicine program. Published figures:

- **MIR exam pass rate:** 96% (UAX-published — ANNUAL_UPDATE_REQUIRED)
- **Graduates doing MIR specialties:** "More than 90% are doing the MIR speciality in the best hospitals in Spain" (UAX-published)
- **Total physicians trained:** 400+ (cumulative)
- **MIR preparation format:** Workshops, tests, and simulations throughout the degree; a "specific preparation programme" integrated from the first year

The ECOE evaluation format in clinical years and the year-round clinical simulation at the Virtual Hospital supports standardized clinical competency assessment aligned with MIR expectations.

What is not published: average MIR national ranking position, percentile or specialty placement breakdown, year-by-year MIR pass rates, number of annual graduates.

The 96% MIR pass rate is UAX's most prominent outcome claim. This figure is not independently verified in publicly available sources. Students for whom MIR preparation quality is a primary selection criterion should request source data and methodology from UAX admissions before committing.

## Strategic Fit

### Good Fit For

- Students who want flexibility in exam timing — rolling admissions allow preparation and testing without a single annual deadline
- Students prioritizing clinical volume and variety — 1,800 hours and 38+ specialties with named hospital affiliations in both Madrid and Oviedo
- Students attracted by integrated Digital Medicine training (telemedicine, predictive medicine, wearables) as a formal part of the curriculum from Year 3
- Students seeking strong MIR preparation with published outcome statistics as a primary criterion
- Students who can afford premium pricing (24,250€/year) and for whom financial considerations are secondary
- International students from Iberoamerican countries who qualify for the OEI 50% tuition discount — at approximately 12,125€/year effective cost, the program becomes price-competitive
- Students from the Principado de Asturias interested in studying and training locally (Oviedo campus) — conditional on verifying program finalization

### Less Suitable For

- Students whose budget has a ceiling well below 24,250€/year — UAX has limited scholarship coverage for Medicine specifically, and the main excellence scholarship explicitly excludes Medicine
- Students who require confirmed WFME accreditation for postgraduate plans in the United States, Canada, or WFME-requiring jurisdictions
- Students who want a fixed exam calendar to plan preparation around — UAX's rolling model offers flexibility but not predictable structure
- Students considering the Oviedo campus who need program certainty — the curriculum is still being modified for 26/27 and there is no prior intake history at this campus
- Students seeking a bilingual or English-medium program
- Students for whom specific exam dates and published scoring rubrics are important for calibrating their preparation strategy

## Risks and Considerations

**Price is the highest in the market without confirmed offsetting advantages.** At 24,250€/year (~145,500€ total), UAX charges significantly more than most Spanish private Medicine programs. The MIR pass rate (96%) and clinical infrastructure justify a premium, but WFME status and exact class sizes are not confirmed. Students paying premium price without confirming WFME coverage or total seat count are accepting unquantified risk.

**Scoring formula and minimum thresholds are not published.** There is no way to predict in advance whether a student will be admitted based on exam performance alone. This lack of transparency makes preparation harder to calibrate and admission probability difficult to assess.

**Oviedo campus is genuinely new for 26/27.** The plan de estudios is formally described as "en proceso de modificación" under Decreto 110/2025. Students enrolling at Oviedo in 26/27 will be the first cohort. There is no prior intake, no established clinical rotation precedent, and no track record to evaluate. The risk is not theoretical — a brand new campus for a regulated healthcare degree carries implementation risk.

**Rolling admissions do not mean unlimited seats.** The rolling model creates a false sense of perpetual availability. Once seats fill, the process closes. Students who delay application assuming year-round access may find no remaining places for the intake they target.

**The Becas de Excelencia exclusion is a meaningful financial signal.** The explicit carve-out of Medicine from UAX's main scholarship program means effective scholarship coverage for Medicine students is narrower than the general UAX scholarship portfolio suggests.

**Plan 2026 transition.** Students entering in 26/27 follow the new Plan 2026 from Year 1. The exact curricular changes are not yet published. This introduces some uncertainty for 26/27 entrants specifically.

## Important Notes

- Annual tuition 24,250€ applies to first-year entrants; second-year and subsequent costs are communicated at the time of auto-enrollment and may differ — verify before committing
- The Becas de Excelencia UAX are explicitly excluded for Medicine — do not plan financial aid around this scholarship
- Oviedo campus is a centro adscrito (affiliated center), not a UAX faculty campus — the institutional structure and facilities differ from Villanueva de la Cañada
- The Advanced CPR Diploma bundled with the degree is a distinguishing feature; its professional recognition beyond Spain should be verified if relevant to career plans
- Payment via Flywire is available for international students making payments from non-EU countries; bank transfer via Banco Santander account ES50-0049-1958-81-2210000511 is also available
- Non-native Spanish speakers must demonstrate B2 Spanish at admission or enroll in UAX's Spanish accompaniment program: 2,400€ in Year 1, 800€ in Years 2–3

## Key Insight

UAX's core strategic proposition is the combination of a rolling admission model (which removes the risk of missing a single make-or-break exam date) with among the strongest published MIR preparation statistics in the Spanish private sector. The 96% pass rate is UAX's most concrete differentiator and represents a meaningful outcome claim if verified. For students whose primary concern is MIR success and who can afford the premium price, UAX is a rational choice. The main decision risks are the absence of a published scoring formula (making admission probability opaque), the unconfirmed WFME status (relevant for non-European practice ambitions), and the Oviedo campus's 2026-27 first-year status (which should be treated as a new program, not an established one).

## Final Takeaway

UAX Medicine is a premium-priced, rolling-admissions program with strong MIR credentials, extensive clinical infrastructure, and a differentiated Digital Health curriculum. Its main value proposition is clarity of outcome: if the MIR pass rate claim is verified and the student can afford the cost, UAX offers a defensible path to specialist training. The Oviedo campus is a separate risk category that should be evaluated independently. The absence of a published scoring formula, WFME confirmation, and per-campus seat numbers are data gaps that warrant direct confirmation with UAX admissions before making a final decision.

## Frequently Asked Questions

**How does UAX Medicine admission work — is there a fixed exam date?**
No. UAX uses rolling admissions: the Medicine-specific exam (50 MCQ in Biology and Chemistry + a personal interview) is available Monday through Friday at 10:00h and 16:00h, and some Saturdays, throughout the year until places are filled. There is no single annual exam date. Earlier application is advisable to avoid losing a seat to other candidates.

**What does the UAX Medicine exam consist of?**
A two-part specific test: Part 1 is a 50-question multiple-choice test (30 questions on Biology, 20 on Chemistry) based on the standard Bachillerato curriculum. Part 2 is a personal interview. There is a 125€ fee payable before sitting the exam.

**Is there a minimum grade requirement to apply to UAX Medicine?**
A Bachillerato title and PAU pass (or equivalent access credential) are required. Whether a minimum Bachillerato or PAU score applies as a threshold before being allowed to sit the exam is PENDING_CONFIRMATION.

**What is the annual tuition at UAX Medicine?**
24,250€ per year for the 2026-27 academic year (ANNUAL_UPDATE_REQUIRED). This is structured as 3,000€ reserva de plaza + 1,350€ matrícula + 10 × 1,990€ monthly installments. The total 6-year estimate is ~145,500€ if pricing holds constant. UAX does not guarantee future year pricing for ongoing students.

**Does UAX have a scholarship for Medicine students?**
The main UAX Becas de Excelencia explicitly exclude the Grado en Medicina. Available options include MEC national scholarships, Comunidad de Madrid excellence scholarship, OEI (50% discount for Iberoamerican nationals), and UAX internal discounts (pronto pago 2%, continuidad up to 25%, deportistas 20–50%, familiares 5%). Contact admisiones@uax.es.

**What is UAX's MIR pass rate?**
UAX publishes a 96% MIR pass rate and states that over 90% of their graduates are undertaking MIR specialty training in "the best hospitals in Spain." These are UAX-published figures; independent verification methodology is not publicly available. Request source data directly from UAX admissions before relying on this figure as a decision criterion.

**Can I study Medicine at UAX Oviedo?**
Yes, from the 2026-27 intake. The Oviedo program operates as an affiliated center (Centro Adscrito), authorized by Decree 110/2025 of the Principado de Asturias. The curriculum plan is still being formally modified for delivery at this location. There is no prior cohort history. Students considering Oviedo should verify the finalized plan de estudios and clinical center agreements directly with UAX before enrolling.

**Does UAX Medicine have a guaranteed admission route?**
Yes. The Programa de Acceso a Medicina is a UAX-run preparatory program: students who pass all subjects receive a guaranteed place in the Medicine degree, bypassing the standard admission test. See the UAX website for cost and duration details.

**Is WFME accreditation confirmed for UAX Medicine?**
PENDING_CONFIRMATION. WFME status is not mentioned in any publicly available UAX Medicine documentation. Students intending to practice in WFME-requiring jurisdictions (United States, Canada, some Middle Eastern countries) should verify directly with UAX or the relevant foreign medical authority.
