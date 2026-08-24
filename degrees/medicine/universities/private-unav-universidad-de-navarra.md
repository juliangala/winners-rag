---
id: unav-medicine

type: university
subtype: private

degree: Medicine
country: spain
currency: EUR

name: Universidad de Navarra
short_name: UNAV
entry_year: "2027"
last_updated: "2026-08-24"
official_website: "https://www.unav.edu/web/facultad-de-medicina"

location:
  city: Pamplona
  region: Navarra
  country: Spain

campus:
  address: "C/ Irunlarrea, 1, 31008 Pamplona"
  lat: NULL
  lng: NULL
  district: "Ermitagaña / Campus Universitario (southwestern Pamplona, postcode 31008)"
  commute_from_centre: "~15 min by city bus (lines 6, 9, 23) from Casco Viejo; approx. 2.5 km / ~25 min on foot"

strategic_tags:
  - reach_option
  - high_competitiveness
  - exam_heavy
  - academic_record_heavy
  - interview_heavy
  - international_friendly
  - english_advantage
  - rolling_admissions
  - early_application_advantage
  - strong_clinical_exposure
  - research_oriented
  - high_cost
  - academic_exam_required

admission_type: mixed
# 70% faculty entrance exam + 30% nota media 1º Bachillerato (national pathway).

accepts_vocational: NULL
accepts_graduates: NULL
accepts_over_25: NULL
accepts_international_curricula: true
spanish_level: B2
english_level: PENDING_CONFIRMATION

selection_factors:
  - factor: academic_record
    weight_pct: 30
    eliminatory: true
  - factor: exam
    weight_pct: 70
    eliminatory: NULL
  - factor: interview
    weight_pct: 0
    eliminatory: false
# Weights confirmed from official admissions page (national pathway):
# 70% faculty entrance exam + 30% nota media 1º Bachillerato.
# Academic record is eliminatory: minimum ≥7.0/10 required to apply.
# Interview is 0% in the standard pathway (not scored); mandatory only for IB pathway.
# Source: https://www.unav.edu/web/grado-en-medicina/admision/perfil-de-ingreso

seats: 200
minimum_grade: 7.0
# Minimum grade of 7.0/10 in 1º Bachillerato (or equivalent) required for all pathways.
admitted_grade_range: NULL

teaching_hospital: "Clínica Universidad de Navarra (Pamplona and Madrid campuses)"
clinical_practice_start: 3
# Full rotational year at CUN (Pamplona or Madrid campus) begins Year 3.
group_size: NULL
teaching_language: es
# Primary language is Spanish. International Program (optional track) adds English-medium subjects
# and international rotations. Faculty entrance exam also available in English for international students.
# Bilingual competency applies to students on the International Program track only.
double_degrees: []
distinctive_trait: "Spain's oldest private medical faculty (est. 1954), structurally integrated
  on a single biomedical campus with the Clínica Universidad de Navarra — Spain's top-ranked private
  hospital for reputation (MRS #1, seven consecutive years) — and CIMA translational research centre;
  holds active WFME international accreditation enabling graduate training in the USA, Canada,
  Australia and New Zealand. Entrance exam is fully published (syllabus + model paper) with disclosed
  weighting: 70% exam (Biology/Chemistry/Physics/Reading comprehension), 30% academic record."
applicants_per_seat: PENDING_CONFIRMATION
rankings:
  - body: "QS World University Rankings"
    position: 151
    scope: institution
    year: 2026
    source_url: "https://www.unav.edu/web/facultad-de-medicina"
  - body: "Ranking CYD"
    position: 1
    scope: spain_overall
    year: 2026
    source_url: "https://www.unav.edu/noticias/-/contents/27/05/2026/la-universidad-primera-universidad-de-espana-segun-el-ranking-cyd/content/lovPblW1fC70/197939745"
  - body: "Ranking CYD — Medicine"
    position: 1
    scope: spain_medicine
    year: 2021
    notes: "Highest-performing faculty for Medicine in Spain across six CYD dimensions"
    source_url: "https://www.unav.edu/web/facultad-de-medicina/conoce-la-facultad/ranking-facultad-medicina"

admission:
  intake_month: September

  applications_open_date: "2026-10-01"
  # Source: https://www.unav.edu/admision-y-ayudas/grado/plazos-de-admision
  # "El 1 de octubre de 2026 se abre el plazo de admisión para el curso 2027/2028."

  rolling_admissions:
    enabled: true
    estimated_end_date: ANNUAL_UPDATE_REQUIRED
    # Medicine fills significantly faster than other degrees. For 2026-27 the degree was
    # already closed by August 2026. Apply November–March for 2027-28 to maximise chances.

  admission_rounds:
    enabled: false
    count: NULL
    rounds: []
    # UNAV uses rolling admissions with priority deadlines, not formal rounds.
    # For Medicine 2027-28: December deadline (international students only) and
    # March deadline (all students). See sittings below.

  exam_required: true
  interview_required: false
  # Interview is NOT required or scored in the standard (national or ISAT) pathway.
  # It IS mandatory for the IB Diploma pathway.

sittings:
  - date: 2026-12-12
    registration_deadline: 2026-12-09
    results_date: 2027-01-21
    deposit_deadline: 2027-02-23
    mode: online
    location: "Remote — international students studying outside Spain only"
    notes: "December round is restricted to international students for the Medicine degree.
      Format: ISAT + online faculty exam in English."
  - date: 2027-03-13
    registration_deadline: 2027-03-09
    results_date: 2027-04-15
    deposit_deadline: 2027-05-31
    mode: in_person
    location: "Pamplona, Campus Universitario"
    notes: "March round open to all students. Minimum 1º Bachillerato grade ≥7.0/10 required.
      National students sit in person in Pamplona; international (ISAT) students sit online.
      Exam scheduled in the afternoon for Medicine."

exam_format:
  question_count: 150
  subjects:
    - name: "Biology"
      weight_pct: 30
      question_count: 50
      syllabus_url: "https://www.unav.edu/documents/29044/30001346/biologia_temario-admision_MedUNAV.pdf"
    - name: "Chemistry"
      weight_pct: 30
      question_count: 50
      syllabus_url: "https://www.unav.edu/documents/29044/30001346/quimica_temario-admision_MedUNAV.pdf"
    - name: "Physics"
      weight_pct: 25
      question_count: 50
      syllabus_url: "https://www.unav.edu/documents/29044/30001346/fisica_temario-admision_MedUNAV.pdf"
    - name: "Reading comprehension (scientific article + 30 questions)"
      weight_pct: 15
      question_count: 30
      model_url: "https://www.unav.edu/documents/4588799/0/modelo-comprension-lectora.pdf"
  penalty: false
  duration_min: 180
  language: "Spanish (English for international online track)"
  notes: "6 additional reserve questions included. 5 answer options per question.
    No negative marking. No calculator permitted. Model exam published at
    https://www.unav.edu/documents/4588799/0/modelo-examen-castellano_2.pdf"

deposit:
  amount: "5,500.00"
  deadline_days: NULL
  refundable: false
  conditions: "Non-refundable except for PAU failure in 1st convocatoria (Spanish Bachillerato
    students) or international visa denial. Amount is deducted from final tuition at enrolment."

academic_record:
  minimum_requirement:
    enabled: true
    grade_source: "first_year_baccalaureate"
    minimum_grade: 7.0
    notes: "Grade ≥7.0/10 in 1º Bachillerato (or equivalent) is required to apply across
      all admission pathways. Students below this threshold are not eligible."

  competitive_filter:
    enabled: true
    grade_source: full_baccalaureate
    approx_candidates_selected: PENDING_CONFIRMATION

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: 200
  applicants_per_seat: PENDING_CONFIRMATION

  last_admitted_scores:
    - intake_year: PENDING_CONFIRMATION
      round: NULL
      score: PENDING_CONFIRMATION
      score_type: PENDING_CONFIRMATION
      notes: PENDING_CONFIRMATION

curriculum:
  international_curriculums_accepted: true

competitiveness:
  level: high

pricing:
  tuition_year1: "20,400.00"
  tuition_year1_non_eu: NULL
  annual_increase_pct: NULL
  price_per_ects: "340.00"
  non_tuition_fees:
    - concept: "Preinscripción"
      amount: "100.00"
      frequency: once
    - concept: "Secretaría"
      amount: "95.00"
      frequency: annual
  payment_options:
    - method: "Pago único"
      notes: "5% early payment discount (deadline: approximately 10 February — ANNUAL_UPDATE_REQUIRED)"
    - method: "Pago fraccionado"
      notes: "Via miUNAV portal"
    - method: "Préstamos bancarios — Banco Sabadell, Santander, Bankinter, BBVA, CaixaBank, Caja Rural Navarra, Kutxabank, IMAGIN"
      notes: "Special conditions for UNAV students"
    - method: "US Federal Direct Loans"
      notes: "Subsidized, Unsubsidized, PLUS Loans — for eligible US students"
    - method: "Crédito Educativo Banco Pichincha"
      notes: "For Ecuadorian students"

scholarships:
  - name: "Becas Prof. Jiménez Vargas"
    amount_or_pct: NULL
    criteria: "Excellent Bachillerato academic record and limited financial resources. Specific
      to the Facultad de Medicina. Funded by alumni and faculty supporters. Application is
      competitive and separate from the degree application."
    deadline: NULL
    stackable: NULL
    source_url: "https://www.unav.edu/documents/10162/33066811/Programa-de-Becas-Medicina_Prof-Jimenez-Vargas.pdf"
  - name: "Becas Alumni"
    amount_or_pct: NULL
    criteria: "Excellent Bachillerato academic record and documented financial need. Covers
      tuition, accommodation, and other costs on a fully personalised basis following an
      in-depth family financial assessment."
    deadline: NULL
    stackable: NULL
    source_url: "https://www.unav.edu/documents/10162/36127911/Normativa-Beca-Alumni.pdf"
  - name: "Programa de Ayudas Universidad de Navarra"
    amount_or_pct: NULL
    criteria: "Good academic record and proven financial need. Personalised grant
      complementing family contribution to allow the student to study at UNAV."
    deadline: NULL
    stackable: NULL
    source_url: "https://www.unav.edu/documents/10162/33066811/programa-ayudas-univesidad-navarra.pdf"
  - name: "Matrícula de Honor"
    amount_or_pct: "16%"
    criteria: "16% reduction on first-year tuition for students with Matrícula de Honor in
      2º Bachillerato. During the degree, each Matrícula de Honor grade earned generates an
      automatic ~16% discount on equivalent credits in the following enrolment. Not combinable
      with Familia Numerosa discount."
    deadline: NULL
    stackable: false
  - name: "Descuento Familia Numerosa"
    amount_or_pct: NULL
    criteria: "Reductions calculated by number of family members simultaneously enrolled at
      UNAV and their position in the family group."
    deadline: NULL
    stackable: NULL
    source_url: "https://www.unav.edu/documents/10162/33299838/bases-descuento-familia-numerosa.pdf"
  - name: "Descuento pago anticipado"
    amount_or_pct: "5%"
    criteria: "Full tuition payment before the disclosed early-payment deadline (approximately
      10 February — ANNUAL_UPDATE_REQUIRED). Available to admitted first-year students only."
    deadline: ANNUAL_UPDATE_REQUIRED
    stackable: NULL
    source_url: "https://www.unav.edu/documents/10162/33299838/descuento_por_pronto_pago.pdf"

sources:
  tuition: "https://www.unav.edu/admision-y-ayudas/grado/cuanto-cuesta-estudiar-en-la-universidad/precios-de-primer-curso"
  seats: "https://www.unav.edu/web/grado-en-medicina/admision/perfil-de-ingreso"
  # No dedicated seats-count page published. 200 seats figure referenced in general admissions info.
  calendar: "https://www.unav.edu/admision-y-ayudas/grado/plazos-de-admision"
  scholarships: "https://www.unav.edu/admision-y-ayudas/grado/becas-y-ayudas"

residence:
  own_residence: NULL
  location: NULL
  price_min: NULL
  price_max: NULL
  first_year_place: NULL

international_profile:
  international_students_percentage: PENDING_CONFIRMATION

  international_nationalities:
    - country: PENDING_CONFIRMATION
      percentage: PENDING_CONFIRMATION

programs:
  - id: unav-medicine-pamplona

    campus: Pamplona

    modality: standard

    strategic_tags:
      - high_competitiveness
      - exam_heavy
      - academic_record_heavy
      - international_friendly
      - early_application_advantage
      - strong_clinical_exposure
      - research_oriented
      - high_cost
      - academic_exam_required

    teaching_languages:
      - Spanish
      - English

    regional_language_possible: false
    regional_language: NULL

    language_requirements:
      minimum_spanish_level_non_native: B2

      english_required: true
      minimum_english_level: PENDING_CONFIRMATION
      # English level required specifically for the International Program track.
      # Requirements published at:
      # https://www.unav.edu/documents/10162/34708156/acreditar-nivel-de-ingles-fac-medicina.pdf

    seats: 200

    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 200
      applicants_per_seat: PENDING_CONFIRMATION

      last_admitted_scores:
        - intake_year: PENDING_CONFIRMATION
          round: NULL
          score: PENDING_CONFIRMATION
          score_type: PENDING_CONFIRMATION
          notes: PENDING_CONFIRMATION

    program_specific_admission:
      enabled: false

    evaluation_model:
      overall_model_type: "mixed"
      # Three distinct admission pathways. Primary pathway (national/in-person):
      # 70% faculty exam + 30% academic record (1º Bachillerato nota media).

      admission_pathways:
        - id: national_standard
          label: "Standard — National / In-person (Pamplona)"
          eligible_profiles:
            - "Students in Spanish 2º Bachillerato — PAU 1st convocatoria (June) mandatory"
            - "International students studying in Spain"

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 30
              grade_source: first_year_baccalaureate
              minimum_required_grade: 7.0
              notes: "Nota media of official subjects from 1º Bachillerato (or equivalent).
                Minimum ≥7.0/10 required to submit application. Grades certified by the student's
                educational centre."

            - component: academic_exam
              enabled: true
              role: weighted
              weight: 70
              exam_variant: onsite_internal_exam
              delivery_mode: in_person
              location: "Pamplona, Campus Universitario"
              question_count: 150
              duration_min: 180
              penalty: false
              language: "Spanish"

              subjects:
                - name: "Biology"
                  weight_pct: 30
                  question_count: 50
                  syllabus_url: "https://www.unav.edu/documents/29044/30001346/biologia_temario-admision_MedUNAV.pdf"
                - name: "Chemistry"
                  weight_pct: 30
                  question_count: 50
                  syllabus_url: "https://www.unav.edu/documents/29044/30001346/quimica_temario-admision_MedUNAV.pdf"
                - name: "Physics"
                  weight_pct: 25
                  question_count: 50
                  syllabus_url: "https://www.unav.edu/documents/29044/30001346/fisica_temario-admision_MedUNAV.pdf"
                - name: "Reading comprehension (scientific article)"
                  weight_pct: 15
                  question_count: 30

              exam_difficulty:
                level: PENDING_CONFIRMATION
                notes: "Published syllabi available for all three science subjects. Model exam
                  (castellano) available. No negative marking. 5 options per question. No
                  calculator. 6 reserve questions included."

              best_attempt_counts: PENDING_CONFIRMATION
              notes: "Model exam: https://www.unav.edu/documents/4588799/0/modelo-examen-castellano_2.pdf"

            - component: interview
              enabled: false
              role: NULL
              weight: 0
              notes: "No interview in standard national pathway."

            - component: isat
              enabled: false
              role: NULL
              weight: NULL
              notes: "ISAT not used in this pathway."

            - component: english_test
              enabled: false
              role: requirement_only
              weight: NULL
              notes: "English test not required for standard national pathway. Required for
                International Program track (post-admission requirement)."

            - component: psychometric_test
              enabled: false
              role: NULL
              weight: NULL
              notes: NULL

            - component: complementary_points
              enabled: false
              role: bonus_only
              maximum_bonus: NULL
              categories: []
              notes: NULL

        - id: international_isat
          label: "International — ISAT + Online Exam"
          eligible_profiles:
            - "Students studying OUTSIDE Spain (any nationality)"

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 30
              grade_source: first_year_baccalaureate
              minimum_required_grade: 7.0
              notes: "Nota media of official subjects from 1º Bachillerato (or equivalent). ≥7.0/10 required."

            - component: isat
              enabled: true
              role: weighted
              weight: 30
              notes: "ISAT (International Scholarship and Aptitude Test, administered by ACER).
                Valid sittings: January, July/August, or October/November. Student must share
                results directly with UNAV. Results available approximately 2 weeks after exam close.
                Info: https://isat.acer.org"

            - component: academic_exam
              enabled: true
              role: weighted
              weight: 40
              exam_variant: online_internal_exam
              delivery_mode: online
              online_conditions: "Proctored via webcam, microphone, and screen monitoring
                (Google Chrome required). Time: approximately 14:30 h peninsular Spanish time."
              question_count: 150
              duration_min: 180
              penalty: false
              language: "English"

              subjects:
                - name: "Biology"
                  weight_pct: 35
                  question_count: 50
                - name: "Chemistry"
                  weight_pct: 35
                  question_count: 50
                - name: "Physics"
                  weight_pct: 30
                  question_count: 50

              notes: "Subject weightings differ from national pathway (Bio 35%, Chem 35%, Physics 30%;
                no reading comprehension component). No negative marking. No calculator."

            - component: interview
              enabled: PENDING_CONFIRMATION
              role: qualitative_only
              weight: 0
              notes: "Faculty may conduct an interview at its discretion ('si lo considera necesario').
                Not standard for all candidates."

            - component: spanish_test
              enabled: true
              role: requirement_only
              notes: "Online Spanish language test required for candidates whose native language
                is not Spanish."

        - id: ib_diploma
          label: "International Baccalaureate (IB) Diploma"
          eligible_profiles:
            - "Students completing the IB Diploma (any country)"

          components:
            - component: ib_score
              enabled: true
              role: eliminatory
              minimum_total_predicted: 37
              minimum_biology_hl: 6
              minimum_chemistry_hl: 6
              notes: "Predicted grades used at application; final grades must confirm requirements
                by 10 July of the admission year. No faculty entrance exam required for IB candidates."

            - component: interview
              enabled: true
              role: eliminatory
              delivery_mode: online
              format: "Personal video interview (Skype) with UNAV Admissions team"
              notes: "Mandatory for all IB candidates. Evaluates fit with MedUNAV admission profile.
                Must be completed after submission and verification of predicted grades."

            - component: academic_exam
              enabled: false
              notes: "IB candidates do NOT sit the faculty entrance exam or ISAT."

      # IMPORTANT — PAU RULE: For students from Spanish 2º Bachillerato, passing the PAU
      # in the 1st convocatoria (June) is a binary pass/fail REQUIREMENT specific to Medicine,
      # Nursing, and Psychology at UNAV. It is NOT a scored component of the admission formula.
      # Failure in June is immediately disqualifying for that academic cycle. The 5,500 EUR
      # first deposit is refunded only in this specific case.
---
# Universidad de Navarra

## Overview

The Facultad de Medicina of the Universidad de Navarra (UNAV) is the oldest and most internationally recognised private medicine faculty in Spain, founded in 1954. It operates within a unique biomedical campus — the Campus Biomédico — that structurally integrates the faculty with the Clínica Universidad de Navarra (CUN) and the Centro de Investigación Médica Aplicada (CIMA), two world-class clinical and research institutions.

UNAV holds WFME (World Federation for Medical Education) international quality accreditation, which is a decisive differentiator: graduates can access specialisation or clinical placements in the United States, Canada, Australia, and New Zealand — a requirement that became mandatory from 2024 onward. The university ranks #151 globally (QS 2026) and first in Spain overall (CYD 2026).

The degree — 360 ECTS, 6 years, in-person, Pamplona — is taught in Spanish with a significant English component. It admits 200 students per year through a rolling, exam-based admissions process. Tuition is 340€ per ECTS, totalling 20,400€ per year in the first course.

For students with strong academic profiles, international career ambitions, or an interest in research alongside clinical training, UNAV is typically the highest-credential private medicine option available in Spain — and the reference point against which other private programmes are measured.

## Quick Evaluation

- **Seats:** 200 per year — single campus, Pamplona
- **Tuition 2026-27:** 340€/ECTS — 20,400€/year (first course) + 95€ secretaría fees
- **Duration:** 6 years, 360 ECTS, fully in-person
- **Languages:** Spanish + English (bilingual components)
- **Admissions:** Rolling (opens 1 October 2026 for 2027-28). Published exam: 150 MCQs — Biology (30%), Chemistry (30%), Physics (25%), Reading comprehension (15%); no negative marking; ~3 hours. Weighting: 70% exam + 30% Bachillerato grade. PAU mandatory for Spanish students in 1st convocatoria.
- **Key differentiator:** WFME accreditation — enables specialisation in USA, Canada, Australia, New Zealand from 2024
- **Clinical training:** Full rotational year at Clínica Universidad de Navarra from year 3; simulation centre from year 1
- **Research:** Harvard-advised curriculum; integrated with CIMA
- **Competitiveness:** High — minimum 7.0/10 in 1º Bachillerato required to apply
- **Scholarships:** Becas Prof. Jiménez Vargas (Medicine-specific) + Becas Alumni

## Key Facts

| Field | Value |
|---|---|
| University | Universidad de Navarra |
| Short name | UNAV |
| Campus | Pamplona (single campus for Medicine) |
| Address | C/ Irunlarrea, 1, 31008 Pamplona |
| Total ECTS | 360 |
| Duration | 6 years |
| Modality | In-person (presencial) |
| Teaching languages | Spanish + English |
| Seats per year | 200 |
| Annual tuition — Year 1 (2026-27) | 20,400€ (340€/ECTS × 60 ECTS) `ANNUAL_UPDATE_REQUIRED` |
| Secretaría fees | +95€/year `ANNUAL_UPDATE_REQUIRED` |
| WFME accreditation | Yes (confirmed active) |
| QS World Ranking | #151 (QS 2026) |
| CYD Spain Ranking | #1 (2026) |
| CYD Medicine Spain | #1 (2021) |
| Employability rate | 99% (university-wide) |
| Founded | 1954 |
| Application opens (2027-28) | 1 October 2026 |
| Application fee | 100€ (non-refundable) |
| First deposit on admission | 5,500€ (non-refundable — deducted from final tuition) |
| International partners | 29 confirmed |

## Program Options

UNAV offers a single official Medicine degree at its Pamplona campus, with optional academic enhancement tracks available to enrolled students:

**Standard Medicine (Grado en Medicina)** — the core degree, 360 ECTS, 6 years, 200 seats. All students follow the same curriculum and are subject to the same admission process.

**International Program in Medicine** — an optional track within the standard degree, not a separate admission. Adds internationally focused coursework, English-medium instruction, and international clinical rotations. Students signal interest during the application, but admission conditions are identical. Tuition: 340€/ECTS (same as standard).

**Diploma Quirúrgico** — a complementary diploma available to enrolled students. Includes surgical theory-practice subjects and targeted simulation training (laparoscopic, surgical techniques) at the Centro de Simulación. Does not require a separate admissions process.

**Diploma en Investigación Biomédica** — a complementary diploma available to enrolled students. Delivered through research placements at UNAV faculties, the Clínica Universidad de Navarra, and CIMA, under a research tutor.

These diplomas are pursued by students already enrolled — they do not require separate admission, and they do not substantially extend the degree duration. They represent differentiating credentials for students targeting surgical or research specialisations.

## Program Structure

The degree is organised into five core modules plus an optional module, across 6 years and 360 ECTS:

- **Módulo I — Morfología, estructura y función del cuerpo humano:** Foundational biomedical sciences — anatomy, histology, physiology, cell biology, biochemistry.
- **Módulo II — Medicina social, habilidades de comunicación e iniciación a la investigación:** Epidemiology, research methodology, communication skills, medical ethics, public health.
- **Módulo III — Formación clínica humana:** Core clinical disciplines — internal medicine, surgery, obstetrics, paediatrics, psychiatry, and related fields.
- **Módulo IV — Procedimientos diagnósticos y terapéuticos:** Diagnostic and therapeutic procedures, pharmacology, imaging, and clinical protocols.
- **Módulo V — Estancias tuteladas y Trabajo Fin de Grado (TFG):** Supervised clinical placements and the final degree dissertation.
- **Módulo VI — Optativas:** Elective subjects.

**Year 3 is structurally distinctive:** the entire third year is a full rotational clinical year at the Clínica Universidad de Navarra — students choose between the Pamplona or Madrid campus. This early full-year clinical immersion, before the traditional clinical phases of years 4–6, is a deliberate pedagogical feature that differentiates UNAV from most Spanish medical schools.

Students also complete the **Core Curriculum** — a set of transversal humanities, ethics, and critical thinking subjects common to all UNAV degrees — integrated throughout the programme.

## Teaching Methodology

UNAV's teaching model is described as patient-centred. Its structural features are as follows:

**Simulation from year 1:** All Medicine students access the Centro de Simulación from their first year, developing practical clinical skills in a controlled environment before hospital contact. This produces early, standardised competency.

**Personalised mentoring system:** Each student is assigned an academic mentor (asesor académico) from enrolment, providing individual guidance throughout the degree. From year 3, a dedicated clinical tutor is assigned to support clinical training objectives. This two-tier mentoring system — academic and clinical — is unusual in the Spanish university context.

**Harvard-advised curriculum:** The curriculum was developed with advisory input from Harvard University. This reflects a commitment to research integration, problem-based learning approaches, and clinical thinking rather than purely memorisation-driven teaching.

**Core Curriculum:** Transversal subjects in philosophy, ethics, and critical thinking are woven into all years of the degree. This is a defining feature of the UNAV model — not supplementary, but structurally embedded.

**Campus Biomédico integration:** The physical and institutional proximity to CUN and CIMA enables a research-to-clinical continuum that standalone medical schools cannot replicate. Student-organised academic congresses (surgery, oncology, international cooperation) reinforce the intellectual culture.

## Clinical Training

UNAV's clinical infrastructure is one of its most important strategic differentiators.

**Clínica Universidad de Navarra (CUN):** A private university hospital operating across Pamplona and Madrid. The first hospital in Spain to receive Joint Commission International (JCI) accreditation. Over 50 medical departments and services, more than 2,800 dedicated professionals. Year 3 rotations take place entirely at CUN — students choose their preferred campus. Ranked Spain's top private hospital for reputation for seven consecutive years (Monitor de Reputación Sanitaria).

**Broad hospital network:** Beyond CUN, students rotate through a diverse network of public and private hospitals across Spain, including large national reference centres, regional hospitals, and primary care facilities. Specific hospital names and rotation structures are subject to annual revision. `ANNUAL_UPDATE_REQUIRED`

**CIMA (Centro de Investigación Médica Aplicada):** Students pursuing the Diploma en Investigación Biomédica access research placements at CIMA — a leading translational biomedical research centre operating under the same institutional umbrella as UNAV and CUN.

**Laboratorio de Ingeniería Médica:** An interdisciplinary teaching laboratory combining medicine and biomedical engineering, connected to both faculty departments and CUN clinical services.

**Centro de Simulación:** Clinical skills training from year 1, with standardised competency development before hospital contact. Covers surgical techniques, laparoscopic skills, and general clinical procedures.

## International Recognition and Opportunities

**WFME accreditation:** Confirmed active. UNAV is among the first Spanish medicine faculties to hold the WFME International Quality Seal. From 2024, this accreditation is a prerequisite for pursuing specialist training or clinical placements in the USA, Canada, Australia, and New Zealand. This is the single most practically significant international credential a Spanish private medicine faculty can hold for students with global ambitions.

**QS World Rankings:** #151 globally (QS 2026); top 100 in 7 academic disciplines. Internationally recognised academic reputation that transfers to graduate-level professional recognition.

**29 international partner institutions:** Whether specific mobility agreements apply to the Medicine degree requires confirmation. `PENDING_CONFIRMATION` Medical student mobility is structurally complex (clinical credit validation, licensing constraints), and university-wide partnership numbers should not be assumed to apply directly to Medicine.

**International Program in Medicine:** The primary structured vehicle for international academic experience at UNAV. It operates as an optional track — not an exchange programme — and includes international clinical rotations and increased English-medium instruction. No separate admissions process.

**US Federal Financial Aid:** UNAV participates in the William D. Ford Federal Direct Loan Program (US Department of Education), accepting Subsidized Loans, Unsubsidized Loans, and PLUS Loans. This is relevant for US citizens and permanent residents.

## Admission Model

UNAV operates a rolling, proprietary admissions model with a faculty-specific entrance exam. Applications open 1 October 2026 for entry in September 2027. There are no fixed admission rounds — applications are processed with priority deadlines, and offers are made as places are filled. **Early application is structurally advantageous and strategically critical.**

Three admission pathways exist depending on the applicant's profile:

### Pathway 1 — Standard (National / In-person, Pamplona)

For students in Spanish Bachillerato and for international students studying in Spain.

**Final admission score = 70% faculty exam + 30% nota media 1º Bachillerato**

**Faculty entrance exam (70%):** A proprietary exam, approximately 3 hours, in-person in Pamplona. 150 multiple-choice questions (5 options each, no negative marking):
- Biology: 50 questions — weight 30% of exam
- Chemistry: 50 questions — weight 30% of exam
- Physics: 50 questions — weight 25% of exam
- Reading comprehension (scientific article + 30 questions) — weight 15% of exam

Syllabi are published for all three science subjects. A model exam is available. No calculator permitted.

**Academic record (30%):** Nota media of official subjects from 1º Bachillerato (or equivalent) as certified by the student's educational centre. Minimum grade of 7.0/10 required to be eligible to apply.

**PAU (Prueba de Acceso a la Universidad):** For Spanish 2º Bachillerato students, passing the PAU in the **1st convocatoria (June)** is mandatory — a binary pass/fail requirement specific to Medicine, Nursing, and Psychology at UNAV. The PAU result is NOT a scored component of the admission formula. Failure in June disqualifies the student for that academic cycle.

**Interview:** Not required in the standard pathway.

### Pathway 2 — International (ISAT + Online Exam)

For students studying outside Spain (any nationality).

**Final admission score = 30% ISAT + 40% online faculty exam + 30% nota media 1º Bachillerato**

The ISAT (International Scholarship and Aptitude Test, ACER) is taken externally (valid sittings: January, July/August, or October/November). The faculty online exam is 150 MCQs in English: Biology (50q, 35%), Chemistry (50q, 35%), Physics (50q, 30%); no reading comprehension component. A Spanish language test is required for non-native Spanish speakers. The faculty may also conduct an interview at its discretion.

### Pathway 3 — IB Diploma

For students completing the International Baccalaureate Diploma (any country).

Minimum requirements: predicted score ≥ 37 points, Biology HL ≥ 6, Chemistry HL ≥ 6. No faculty entrance exam required. A mandatory personal video interview with the UNAV Admissions team is part of the process. Admission is conditional on achieving final IB grades by 10 July of the admission year.

## Admission Process

1. Register on the **miUNAV portal** (miportal.unav.edu)
2. Submit the application form with required documentation:
   - Grades from 1º Bachillerato (or equivalent) — minimum 7.0/10 required
   - Passport-size photograph
   - DNI (front and back) or equivalent national ID
   - Proof of 100€ application fee payment (non-refundable) — via card or bank transfer
3. Receive exam date, time, and location once the application is complete
4. Sit the faculty entrance exam (~3 hours — in-person Pamplona or online depending on pathway)
5. Receive decision via miUNAV portal
6. Pay first deposit (**5,500€** — non-refundable except for PAU failure in 1st convocatoria or international visa denial; deducted from final tuition at enrolment)
7. Pass the PAU in 1st convocatoria (June) — mandatory for Spanish Bachillerato students
8. Formalise enrolment with full documentation and tuition payment

Applying to multiple degrees requires a separate form per application after the second, with an additional 100€ fee for the third application onward.

## Admission Timeline — 2027-28 Entry

All dates are confirmed from the official admissions calendar. `ANNUAL_UPDATE_REQUIRED` for future cycles.

| Event | Date |
|---|---|
| Applications open (2027-28 cycle) | 1 October 2026 |
| December deadline (international students only) | 9 December 2026 |
| December exam | 12 December 2026 |
| December results | 21 January 2027 |
| December deposit deadline | 23 February 2027 |
| March deadline (all students — minimum grade ≥7) | 9 March 2027 |
| March exam | 13 March 2027 |
| March results | 15 April 2027 |
| March deposit deadline | 31 May 2027 |
| Rolling phase (remaining seats) | From 15 April 2027, exams every Thursday |
| PAU — 1st convocatoria (Spanish students) | June 2027 |
| Academic year starts | September 2027 |

**Note:** The December round is restricted to international students for Medicine. Spanish national students apply in the March round (deadline 9 March 2027). Students who apply in November–December are processing their applications when the largest share of seats is still available.

## Admission Score Distribution

The admission formula for the national pathway is publicly confirmed:

| Component | Weight |
|---|---|
| Faculty entrance exam (Biology 30%, Chemistry 30%, Physics 25%, Reading 15%) | 70% |
| Nota media 1º Bachillerato | 30% |

For the international (ISAT) pathway: ISAT 30% + Online faculty exam 40% + Academic record 30%.

PAU performance operates as a binary pass/fail requirement for Spanish students — not a weighted scoring element.

For preparation strategy, the faculty exam should be treated as the primary target. Published syllabi are available for Biology, Chemistry, and Physics. A model exam and model reading comprehension exercise are available on the faculty website.

## Costs and Payment Structure

All costs are subject to annual review. `ANNUAL_UPDATE_REQUIRED`

### Tuition 2026-2027 — First Year

| Item | Amount |
|---|---|
| Tuition — Medicina (60 ECTS × 340€/ECTS) | 20,400.00€ `ANNUAL_UPDATE_REQUIRED` |
| Secretaría fees | +95.00€ `ANNUAL_UPDATE_REQUIRED` |
| **Total first year** | **~20,495.00€** `ANNUAL_UPDATE_REQUIRED` |

Subsequent year costs are published in a separate PDF on the UNAV website. `ANNUAL_UPDATE_REQUIRED`

Medicina + International Program carries the same per-ECTS price (340€). `PENDING_CONFIRMATION` for total credits and any additional costs associated with the international track.

### Payment Options

| Method | Notes |
|---|---|
| Single full payment | 5% early payment discount (deadline: approximately 10 February — `ANNUAL_UPDATE_REQUIRED`) |
| Fractionated payment | Terms via miUNAV portal |
| Bank loans — Banco Sabadell, Santander, Bankinter, BBVA, CaixaBank, Caja Rural Navarra, Kutxabank, IMAGIN | Special conditions for UNAV students |
| US Federal Direct Loans | Subsidized, Unsubsidized, PLUS Loans — for eligible US students |
| Ecuador — Crédito Educativo (Banco Pichincha) | For Ecuadorian students |

### Additional Costs

| Item | Amount |
|---|---|
| Application fee | 100€ (non-refundable) |
| First enrolment deposit | 5,500€ non-refundable (refunded only for PAU failure in 1st convocatoria or visa denial; deducted from final tuition) |
| Accommodation — Pamplona | PENDING_CONFIRMATION |
| Monthly living costs — Pamplona | PENDING_CONFIRMATION |

## Scholarships and Financial Aid

UNAV operates one of the most developed private scholarship programmes in Spanish higher education, with several instruments specifically targeting Medicine students.

**Becas Alumni:** The flagship programme, funded by alumni, companies, and institutions. Covers tuition, accommodation, and other costs on a fully personalised basis following an in-depth family financial assessment. Targeted at students with excellent Bachillerato academic records and documented financial need. Normativa: https://www.unav.edu/documents/10162/36127911/Normativa-Beca-Alumni.pdf

**Becas Prof. Jiménez Vargas:** A scholarship programme **specific to the Facultad de Medicina**, named after a distinguished professor. Aimed at students who aspire to Medicine, have an excellent Bachillerato academic record, and limited financial resources. Funded by alumni and faculty supporters. Application is competitive and separate from the degree application. Programme document: https://www.unav.edu/documents/10162/33066811/Programa-de-Becas-Medicina_Prof-Jimenez-Vargas.pdf

**Programa de Ayudas Universidad de Navarra:** A university-wide personalised grant programme for students with a good academic record and proven financial need. Normativa: https://www.unav.edu/documents/10162/33066811/programa-ayudas-univesidad-navarra.pdf

**Matrícula de Honor:** Students who obtained a Matrícula de Honor in 2º Bachillerato receive a 16% reduction on first-year tuition. During the degree, each Matrícula de Honor grade earned in a subject generates an automatic ~16% discount on the equivalent credits in the following enrolment. Not combinable with Familia Numerosa discounts.

**Familia Numerosa discounts:** Reductions calculated by number of family members simultaneously enrolled at UNAV and their family position. Bases: https://www.unav.edu/documents/10162/33299838/bases-descuento-familia-numerosa.pdf

**Early payment discount:** 5% reduction on full tuition for students paying in full before the disclosed deadline (approximately 10 February — `ANNUAL_UPDATE_REQUIRED`). Available to admitted first-year students only.

**Estudio de Coste y Becas:** A personalised cost and scholarship assessment tool available to all applicants during the admissions process. By providing family income data, Bachillerato grades, and geographic origin, applicants receive a tailored cost estimate with scholarship eligibility information. Strongly recommended for any applicant concerned about affordability. Access via miportal.unav.edu.

## Accommodation and Cost of Living

Pamplona is a medium-sized Navarrese city with a moderate cost of living relative to Madrid or Barcelona.

| Item | Estimate |
|---|---|
| Student accommodation (university residence or private) | PENDING_CONFIRMATION |
| Monthly living costs — food, transport, miscellaneous | PENDING_CONFIRMATION |
| Total estimated annual living costs | PENDING_CONFIRMATION |

UNAV provides a housing search service for students. `PENDING_CONFIRMATION` for specific options and costs. Scholarship packages under Becas Alumni may cover accommodation — students should factor this into financial planning from the application stage.

## International Exchange and Mobility Programs

**29 confirmed international partner institutions:** Whether specific Erasmus+ or bilateral agreements apply to the Medicine degree requires direct confirmation with the faculty. Medical student mobility is structurally complex due to clinical credit validation requirements and licensing constraints across jurisdictions. University-wide partnership counts do not automatically translate to Medicine-specific mobility options. `PENDING_CONFIRMATION`

**International Program in Medicine:** The most accessible and structured pathway for international academic experience at UNAV. It is an optional track within the degree — not an exchange programme — and includes international clinical rotations and English-medium instruction. No separate admissions process.

**Research mobility via CIMA and CUN:** Students enrolled in the Diploma en Investigación Biomédica may access research placements with international partners through CIMA. Specific details require confirmation. `PENDING_CONFIRMATION`

## MIR Preparation and Professional Outcomes

UNAV does not publish specific MIR (Médico Interno Residente) ranking statistics. `PENDING_CONFIRMATION`

The university reports a 99% employability rate at institutional level, which covers all degrees and should not be interpreted as a Medicine-specific figure.

The degree's clinical training architecture — simulation from year 1, full clinical immersion year 3, diverse hospital rotations in years 4–6, and integration with CUN — is structurally aligned with MIR preparation. However, the absence of published MIR-specific outcome data prevents numerical comparison. `PENDING_CONFIRMATION`

**WFME accreditation** opens post-degree pathways beyond the MIR: specialisation routes in the USA (USMLE), Canada (MCCQE), Australia (AMC), and New Zealand. For internationally oriented graduates, these pathways represent concrete professional mobility that most Spanish medicine degrees cannot offer.

## Strategic Fit

### Good Fit For
- Students with a 1º Bachillerato grade ≥7.0/10 (eligibility threshold) and a strong academic profile overall
- Students for whom WFME accreditation and international career options are a priority
- Students who want to prepare for a published, transparent exam (Biology, Chemistry, Physics + Reading comprehension) with disclosed weighting
- Students interested in research alongside clinical training, particularly via the Diploma en Investigación Biomédica
- International students seeking a Spanish degree with global professional recognition
- Students eligible for Becas Prof. Jiménez Vargas or Becas Alumni who need financial support
- Students or families with the financial capacity for 20,400€/year, or access to bank financing
- Students who value a structured, humanist, personalised educational environment
- Students applying early in the cycle (October–March) to maximise rolling admissions advantages
- Students interested in surgical specialisation who would benefit from the Diploma Quirúrgico

### Less Suitable For
- Students with a 1º Bachillerato grade below 7.0/10 (ineligible to apply)
- Spanish Bachillerato students who have not passed or are uncertain about passing the PAU in 1st convocatoria
- Students seeking the most financially accessible private medicine option in Spain
- Students who need a guaranteed place by a specific date and cannot tolerate rolling admissions uncertainty
- Students applying late in the cycle (after March–April)

## Risks and Considerations

**Rolling admissions and late application risk:** UNAV fills its 200 seats progressively throughout the year. For 2026-27, Medicine was already closed by August 2026. Students applying after March–April face materially lower probability of securing a place, regardless of their academic profile. This is a structural feature, not a policy that can be navigated around.

**PAU 1st convocatoria rule:** For Spanish 2º Bachillerato students, failing the PAU in June is immediately disqualifying for that cycle — a stricter rule than at most other private universities, specific to Medicine, Nursing, and Psychology. This must be factored into planning from the outset. Students who fail in June cannot resit in September and still access UNAV Medicine that year.

**Exam is published but still demanding:** UNAV now publishes the exam syllabi (Biology, Chemistry, Physics) and a model exam. The reading comprehension section (15%) involves a scientific article in Spanish. The exam is proprietary and scored — strong science preparation is required. The absence of past papers (beyond the model) means preparation must rely on syllabi and textbooks.

**Non-refundable financial exposure:** The 100€ application fee and the first deposit (5,500€) are non-refundable in most circumstances. Speculative applicants who are still awaiting other university results should be aware of the financial commitment.

**High cost with limited published benchmarking data:** At 20,400€/year, UNAV is among the most expensive private Medicine programmes in Spain. Scholarship competition is real. Students should complete the Estudio de Coste y Becas early to understand their realistic net annual cost.

## Important Notes

- Minimum 1º Bachillerato grade of 7.0/10 is required to apply — students below this are not eligible
- PAU 1st convocatoria (June) is mandatory for Spanish Bachillerato students — failure disqualifies for that cycle
- Applications open 1 October 2026 for the 2027-28 entry year — apply as early as possible
- December round (exam 12 December 2026) is for international students only; March round (exam 13 March 2027) is for all students
- Application fee: 100€ non-refundable. First deposit: 5,500€ non-refundable (PAU failure or visa denial are the only exceptions)
- Complete the Estudio de Coste y Becas during the admissions process to get a personalised cost and scholarship estimate
- WFME accreditation is active and confirmed — it enables international specialisation from 2024 onward
- Diploma Quirúrgico and Diploma en Investigación Biomédica do not require separate admissions — they are pursued within the enrolled degree
- Medicina and Medicina + International Program carry the same tuition price per ECTS (340€)
- UNAV participates in US Federal Direct Loan program — relevant for eligible US students

## Key Insight

UNAV's most strategically important asset — particularly for international students — is its active WFME accreditation. From 2024, this accreditation is a prerequisite for pursuing specialist training or clinical placements in the USA, Canada, Australia, and New Zealand. Among private Spanish medicine faculties, few hold this accreditation, and UNAV was among the first. For students with international professional ambitions, this certification alone can justify the cost differential relative to other private options.

The second structural differentiator is the Campus Biomédico model: the institutional integration of the faculty, the Clínica Universidad de Navarra (Spain's #1 ranked private hospital for reputation, seven consecutive years), and the CIMA creates a learning environment — with early clinical immersion, simulation from year 1, research access, and a full rotational year 3 — that most Spanish medical schools, public or private, cannot match in depth or coherence.

A third, underappreciated differentiator: UNAV's admission exam is now fully transparent. The syllabi for Biology, Chemistry, and Physics are published, a model exam is available, and the weighting formula (70% exam / 30% Bachillerato) is publicly confirmed. This is more preparation-friendly than some competitors whose exam content remains undisclosed.

## Final Takeaway

UNAV is the benchmark private medicine programme in Spain. It combines WFME international accreditation, a Harvard-advised curriculum, world-class clinical infrastructure at CUN and CIMA, and a structured, personalised teaching model. Tuition at 20,400€/year is among the highest in the private sector, but Medicine-specific scholarships (Becas Prof. Jiménez Vargas, Becas Alumni) and the personalised Estudio de Coste y Becas tool provide real financial mitigation pathways for strong candidates.

The main structural risks are: the rolling admissions model (which strongly rewards early applicants — applications open 1 October 2026), the PAU 1st convocatoria rule (which creates a single point of failure for Spanish students), and the 7.0/10 eligibility threshold in 1º Bachillerato. For a candidate who meets the eligibility requirements, applies early, manages these risks, and has the financial means or scholarship access, UNAV represents the strongest private Medicine credential available in Spain.

## Frequently Asked Questions

**Is the WFME accreditation confirmed and currently active?**
Yes. UNAV is one of the first Spanish medicine faculties to hold the WFME International Quality Seal. It is confirmed active. This accreditation enables graduates to pursue specialist training or clinical placements in the USA, Canada, Australia, and New Zealand — a requirement mandatory from 2024.

**What are the minimum requirements to apply?**
A grade of ≥7.0/10 in 1º Bachillerato (or equivalent) is required for all admission pathways. Students below this threshold cannot apply. There is no minimum PAU score required — PAU is a binary pass/fail requirement for Spanish Bachillerato students.

**Do international students need to take the PAU?**
No. International students do not need to sit the PAU. They apply using their equivalent secondary credentials through the ISAT + online exam pathway or the IB pathway (if applicable).

**When do applications open for 2027-28?**
Applications open on 1 October 2026. The first deadline for international students is 9 December 2026 (exam 12 December). The main March deadline (for all students) is 9 March 2027 (exam 13 March). Applying as early as possible is strongly recommended.

**What does the faculty entrance exam cover?**
The exam is proprietary to the Facultad de Medicina, approximately 3 hours, 150 multiple-choice questions (5 options, no negative marking):
- Biology: 50 questions, 30% weight — published syllabus available
- Chemistry: 50 questions, 30% weight — published syllabus available
- Physics: 50 questions, 25% weight — published syllabus available
- Reading comprehension (scientific article): 30 questions, 15% weight

A model exam is published on the faculty website. No calculator is permitted.

**How is the final admission score calculated?**
For the national (in-person) pathway: 70% faculty entrance exam + 30% nota media 1º Bachillerato. For the international (ISAT) pathway: 30% ISAT + 40% online faculty exam + 30% academic record. For IB students: based on IB predicted grades (≥37 total, ≥6 Biology HL, ≥6 Chemistry HL) plus a mandatory interview.

**Is there an interview?**
For the standard national and ISAT pathways: no mandatory interview (the faculty may interview ISAT candidates at its discretion). For the IB pathway: yes, a personal video interview is mandatory.

**What does 340€/ECTS cost in practice?**
For the first year of Medicine: 60 ECTS × 340€ = 20,400€, plus 95€ in secretaría fees. Total first-year cost: approximately 20,495€ (2026-27). `ANNUAL_UPDATE_REQUIRED` Subsequent year costs are published in a separate PDF on the UNAV website.

**What is the deposit and is it refundable?**
The first deposit is 5,500€, paid on admission. It is non-refundable except in two cases: (1) Spanish Bachillerato students who fail the PAU in the 1st convocatoria (June), and (2) international students whose visa application is denied. The amount is deducted from the final tuition at enrolment.

**Is the International Program in Medicine a separate degree or separate admission?**
No on both counts. It is an optional track within the standard Medicine degree. No separate admissions process. Students indicate their interest when applying. Tuition per ECTS is identical. English level requirements apply for this track.

**What is the Beca Prof. Jiménez Vargas?**
A scholarship specific to the Facultad de Medicina, aimed at students with an excellent Bachillerato academic record and documented financial need. Funded by faculty alumni and supporters. Application is competitive and separate from the degree application. Document: https://www.unav.edu/documents/10162/33066811/Programa-de-Becas-Medicina_Prof-Jimenez-Vargas.pdf

**Does UNAV accept US federal financial aid?**
Yes. UNAV participates in the William D. Ford Federal Direct Loan Program (US Department of Education), accepting Subsidized Loans, Unsubsidized Loans, and PLUS Loans for eligible US students.

**If I fail the PAU, can I still enrol at UNAV for Medicine that year?**
No. For Medicine specifically, UNAV requires Spanish Bachillerato students to pass the PAU in the 1st convocatoria (June). Failure in June disqualifies the applicant for that academic cycle. The 5,500€ first enrolment deposit is refunded in this specific case.

**What is the Estudio de Coste y Becas?**
A personalised cost and scholarship assessment tool available to all applicants during the admissions process. By providing family income data, Bachillerato grades, and geographic origin, you receive a tailored estimate of your net annual cost and scholarship eligibility. It is free, confidential, and strongly recommended before committing to the application. Access via miportal.unav.edu.
