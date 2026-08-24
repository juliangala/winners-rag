---
id: ufv-medicina-madrid

type: university
subtype: private

name: Universidad Francisco de Vitoria
short_name: UFV

degree: Medicine

last_update: 2026-05-27

valid_for_intake: 2026-2027

location:
  city: Pozuelo de Alarcón (Madrid)
  region: Comunidad de Madrid
  country: Spain

strategic_tags:
  - core_option
  - high_competitiveness
  - interview_heavy
  - exam_heavy
  - academic_record_heavy
  - english_advantage
  - early_application_advantage
  - strong_clinical_exposure
  - high_cost
  - international_friendly
  - onsite_exam_required

admission:
  intake_month: September # ANNUAL_UPDATE_REQUIRED

  applications_open_date: ANNUAL_UPDATE_REQUIRED

  rolling_admissions:
    enabled: true
    estimated_end_date: ANNUAL_UPDATE_REQUIRED # Two admission lists: February and July

  admission_rounds:
    enabled: true
    count: 2

    rounds:
      - round: 1
        application_deadline: 2026-02-03 # ANNUAL_UPDATE_REQUIRED (1st Bachillerato grades deadline)
        exam_date: ANNUAL_UPDATE_REQUIRED # Multiple onsite dates: March–April sessions
        results_date: 2026-02-18 # ANNUAL_UPDATE_REQUIRED
        deposit_deadline: ANNUAL_UPDATE_REQUIRED

      - round: 2
        application_deadline: 2026-06-25 # ANNUAL_UPDATE_REQUIRED (PAU deadline)
        exam_date: ANNUAL_UPDATE_REQUIRED # Multiple onsite dates: March–June sessions
        results_date: 2026-07-01 # ANNUAL_UPDATE_REQUIRED
        deposit_deadline: ANNUAL_UPDATE_REQUIRED

  exam_required: true
  interview_required: true # Selective — called by committee only; eliminatory if called

academic_record:
  minimum_requirement:
    enabled: false
    grade_source: NULL
    minimum_grade: NULL

  competitive_filter:
    enabled: true
    grade_source: first_year_baccalaureate # Round 1; PAU for Round 2
    approx_candidates_selected: PENDING_CONFIRMATION

curriculum:
  international_curriculums_accepted: true # Credencial UE, homologación no-UE, PCE/UNED accepted

competitiveness:
  level: high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: 160 # ANNUAL_UPDATE_REQUIRED (155 via routes A/B/C + max 5 via route D; E/F from vacancies)
  applicants_per_seat: PENDING_CONFIRMATION

  last_admitted_scores:
    - intake_year: ANNUAL_UPDATE_REQUIRED
      round: ANNUAL_UPDATE_REQUIRED
      score: PENDING_CONFIRMATION
      score_type: composite_score
      notes: Score combines academic record (65–70%) + psychometric test (25–30%) + English level (5%)

international_profile:
  international_students_percentage: PENDING_CONFIRMATION

  international_nationalities:
    - country: PENDING_CONFIRMATION
      percentage: PENDING_CONFIRMATION

programs:
  - id: ufv-medicina-madrid-standard

    campus: Pozuelo de Alarcón (Madrid)

    modality: standard

    strategic_tags:
      - core_option
      - high_competitiveness
      - interview_heavy
      - exam_heavy
      - academic_record_heavy
      - english_advantage
      - early_application_advantage
      - strong_clinical_exposure
      - high_cost
      - international_friendly
      - onsite_exam_required

    teaching_languages:
      - Spanish

    regional_language_possible: false
    regional_language: NULL

    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION

      english_required: false # English test is part of the admission scoring, not a prerequisite
      minimum_english_level: NULL

    seats: 160 # ANNUAL_UPDATE_REQUIRED

    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 160
      applicants_per_seat: PENDING_CONFIRMATION

      last_admitted_scores:
        - intake_year: ANNUAL_UPDATE_REQUIRED
          round: ANNUAL_UPDATE_REQUIRED
          score: PENDING_CONFIRMATION
          score_type: composite_score
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
      overall_model_type: weighted

      admission_pathways:
        - eligible_profiles:
            - Spanish Bachillerato + PAU (Route A) — Round 1
            - International Bachillerato / Credencial UE (Route B) — Round 1

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 65 # Round 1: 65% of 1st year Bachillerato
              grade_source: first_year_baccalaureate
              minimum_required_grade: NULL
              notes: For Round 1, only candidates currently in their final Bachillerato year from science/health or technology branch are considered. PAU ponderating subjects — Biology, Chemistry, Physics, Mathematics II (best 2 count).

            - component: psychometric_test
              enabled: true
              role: weighted
              weight: 30 # Round 1: 30%
              test_format: multiple_choice
              delivery_mode: onsite # Online only for students outside mainland Spain
              online_conditions: Must contact admisionmedicina@ufv.es with subject 'Prueba online'
              notes: Aptitude/psychometric test (prueba psicotécnica tipo test). Approx. 2 hours total session. Valid for 5 years — prior test takers exempt from re-sitting.

            - component: english_test
              enabled: true
              role: weighted
              weight: 5 # Round 1 and Round 2
              test_format: multiple_choice
              delivery_mode: onsite
              online_conditions: Same online exception as psychometric test
              minimum_level: NULL
              bonus_max: NULL
              bonus_scale:
                B2: NULL
                C1: NULL
                C2: NULL
              notes: English proficiency test — determines CEFR level. All candidates must sit this test regardless of existing certificates.

            - component: interview
              enabled: true
              role: eliminatory # Called only if UFV committee deems necessary; eliminatory if summoned
              weight: NULL
              interview_format: online
              delivery_mode: online
              notes: Not called for all candidates. UFV selects whom to interview. Mandatory if called — automatic withdrawal if not attended. Conducted on a different day from the main test.

            - component: complementary_points
              enabled: true
              role: bonus_only
              maximum_bonus: PENDING_CONFIRMATION
              categories:
                - category: Regnum Christi affiliated schools
                  max_points: PENDING_CONFIRMATION
                - category: CETYS or UFV current/former students
                  max_points: PENDING_CONFIRMATION
                - category: Siblings currently enrolled at UFV
                  max_points: PENDING_CONFIRMATION
                - category: Children of UFV employees
                  max_points: PENDING_CONFIRMATION
              notes: Additional points (vínculos UFV) awarded for institutional affiliation.

        - eligible_profiles:
            - Spanish Bachillerato + PAU (Route A) — Round 2
            - International Bachillerato / Credencial UE (Route B) — Round 2
            - University transcript transfer (Route C) — Round 2

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 70 # Round 2: PAU / Credencial UE / Homologación + PCE
              grade_source: mixed # PAU for Spanish; Credencial UE or homologación+PCE for international
              minimum_required_grade: NULL
              notes: PAU subjects ponderating — Biology, Chemistry, Physics, Mathematics II (best 2 count). Phase-specific scores valid 2 years.

            - component: psychometric_test
              enabled: true
              role: weighted
              weight: 25 # Round 2: 25%
              test_format: multiple_choice
              delivery_mode: onsite
              online_conditions: Available online for candidates outside mainland Spain
              notes: Same UFV aptitude test. Exempt if taken within last 5 years.

            - component: english_test
              enabled: true
              role: weighted
              weight: 5
              test_format: multiple_choice
              delivery_mode: onsite
              online_conditions: Available online for candidates outside mainland Spain
              minimum_level: NULL
              bonus_max: NULL
              bonus_scale:
                B2: NULL
                C1: NULL
                C2: NULL
              notes: Same English test as Round 1.

        - eligible_profiles:
            - University degree holders (Route D)
            - Medicine transfer from Spanish university (Route E)
            - Medicine transfer from foreign university (Route F)

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 70
              grade_source: equivalent_secondary_record # University transcript / Medicine transcript
              minimum_required_grade: NULL
              notes: For Route D — completed university degree or CFGS. For E/F — Medicine academic record. UFV reserves the right not to fill all Route D places if quality threshold not met.

            - component: psychometric_test
              enabled: true
              role: weighted
              weight: 25
              test_format: multiple_choice
              delivery_mode: onsite
              online_conditions: Available online for candidates outside mainland Spain
              notes: Same UFV aptitude test.

            - component: english_test
              enabled: true
              role: weighted
              weight: 5
              test_format: multiple_choice
              delivery_mode: onsite
              online_conditions: NULL
              minimum_level: NULL
              bonus_max: NULL
              bonus_scale:
                B2: NULL
                C1: NULL
                C2: NULL
              notes: NULL
---
# Universidad Francisco de Vitoria — Medicine

## Overview

The Grado en Medicina at Universidad Francisco de Vitoria (UFV) is a six-year, 360 ECTS programme offered on a single campus in Pozuelo de Alarcón, on the outskirts of Madrid. UFV is a Catholic, Regnum Christi-affiliated institution whose Medicine degree is framed around a distinctive "Medical Humanities" philosophy — integrating physical, psychological, spiritual, and social dimensions of healthcare alongside the standard biomedical curriculum.

The programme stands out for early clinical exposure from Year 1, a well-articulated network of hospital agreements (eight university hospitals, sixteen health centres), strong MIR pass rates, and a top national ranking in teaching quality (CYD Ranking, 2020). The admission model is multi-component — combining academic record, a proprietary psychometric aptitude test, and an English proficiency test — with two structured admission rounds spread across the academic year, making early-year application strategically advantageous.

UFV has established a large intake of 160 places per cohort, which is above average for private Medicine programmes in Spain, reflecting its capacity to absorb a meaningful volume of domestic and international candidates. The campus is self-contained and purpose-built, with clinical simulation infrastructure that includes operating theatres, ICUs, emergency suites, and ambulance facilities integrated into the curriculum.

For international students, UFV accepts Credencial UE, non-EU homologation, and PCE/UNED scores, and offers an online exam option for candidates located outside mainland Spain — a practical differentiator relative to programmes requiring mandatory onsite attendance.

## Quick Evaluation

- **Seats:** 160 (155 via Routes A/B/C + max 5 via Route D; Routes E/F from vacancies)
- **Admission model:** Weighted composite — 65–70% academic record + 25–30% psychometric aptitude test + 5% English test
- **Rounds:** 2 — Round 1 (February results) for current Bachillerato students; Round 2 (July results) open to all
- **Selective interview:** Not universal — called by committee; eliminatory if summoned
- **Annual tuition:** €20,400 (Year 1) — ANNUAL_UPDATE_REQUIRED
- **Registration fee:** €170 (non-refundable); place deposit €4,250 (non-refundable)
- **Clinical network:** 8 university hospitals + 16 specialised centres across Madrid
- **MIR outcomes:** Stated strong results; specific pass rates PENDING_CONFIRMATION
- **International access:** Credencial UE, homologación + PCE accepted; online exam available for non-mainland candidates
- **Campus:** Single campus, Pozuelo de Alarcón (Madrid), residential feel with sports and pastoral infrastructure

## Key Facts

| Field | Value |
|---|---|
| Degree | Grado en Medicina (360 ECTS, 6 years) |
| Campus | Pozuelo de Alarcón, Madrid |
| Seats (2026–27) | 160 — ANNUAL_UPDATE_REQUIRED |
| Annual tuition (Year 1) | €20,400 — ANNUAL_UPDATE_REQUIRED |
| Registration fee | €170 (non-refundable) |
| Place deposit | €4,250 (non-refundable, deducted from tuition) |
| Admission rounds | 2 (February + July) |
| Exam required | Yes — proprietary psychometric aptitude test + English test |
| Interview | Selective (called by committee only) |
| International access | Credencial UE, homologación + PCE/UNED |
| Affiliated institution | Regnum Christi (Catholic) |
| Contact | admisionmedicina@ufv.es |

## Program Options

UFV offers a single Medicine degree programme at its Pozuelo de Alarcón campus. There is no bilingual or English-medium track. Teaching is conducted entirely in Spanish.

Students may optionally complement their degree with a minor in Business Management (gestión empresarial), which provides exposure to healthcare economics, strategy, and management — an unusual option for a Medicine programme and relevant for students interested in health sector leadership or administration.

There is no separate international track, though the programme includes integrated international clinical rotation opportunities and exchange agreements through the university's broader network.

## Program Structure

The programme spans six years across twelve semesters, structured into three broad phases:

**Preclinical Phase (Years 1–2):** Foundational basic sciences — Anatomy (1 & 2), Physiology (1 & 2), Biochemistry, Biology, Genetics, Embryology, Histology, Microbiology and Parasitology, Biostatistics, and Human Psychology. All years incorporate a Medical Humanities thread (modules 1–4) and interpersonal competency training.

**Transitional Phase (Years 3–4):** Progression to applied biomedical subjects — General Pathology, Pathological Anatomy, General Pharmacology, Clinical Methods (semiology and communication), Diagnostic Procedures (physical medicine and radiodiagnostics), Introduction to Surgery, Introduction to Primary Care, Psychiatry, Preventive Medicine, Forensic Medicine, and a set of system-specific pathology modules (cardiovascular, respiratory, digestive, dermatology, geriatrics, ophthalmology, otorhinolaryngology).

**Clinical Phase (Years 5–6):** Full clinical immersion with compulsory hospital rotations. Year 5 includes Clinical Stays 1 (15 ECTS, 10 weeks), covering gynaecology and obstetrics, paediatrics, haematology, musculoskeletal, and nephrourinary pathology, plus an elective. Year 6 includes Clinical Internships 2 (40 ECTS), covering oncology, infectious diseases, immunology, and a Final Degree Project (TFG, 6 ECTS), plus an elective.

Total credit structure: 360 ECTS over 6 years. ECTS breakdown per year available on request.

## Teaching Methodology

UFV's pedagogical model is built around three pillars: early clinical immersion, clinical simulation, and Medical Humanities integration.

**Early Clinical Immersion:** From Year 1, students shadow physicians in hospital environments, gradually progressing from observation to active participation in clinical placements and rotations. This is a structural differentiator relative to programmes where hospital exposure is deferred to Years 3–4.

**Clinical Simulation:** UFV operates one of the first European Medicine programmes to integrate simulation systematically across the curriculum. The campus houses dedicated simulation facilities — including simulated operating theatres, ICUs, emergency units, ambulance scenarios, and primary care centres — alongside 400 m² of advanced research laboratories (flow cytometry, multiphoton microscopy, cell cultures, mass spectrometry).

**Medical Humanities:** A distinctive four-year thread (modules 1–4, one per year) addresses the patient's experience of illness in its physical, psychological, spiritual, and social dimensions. Programme activities include visits to Fontilles (leprosy hospital), academic trips to Germany and Poland (bioethics focus), and structured bioethics seminars.

**Small-group teaching** is standard, supported by personal tutor assignments. The pedagogical philosophy emphasises person-centred medicine over disease-centred approaches.

## Clinical Training

Clinical training is embedded from Year 1 and intensifies progressively through the programme. UFV's clinical network comprises eight public and private university hospitals and sixteen specialised units and health centres covering psychiatry, oncology, traumatology, palliative care, and geriatrics.

**Confirmed affiliate hospitals include:**
- Hospital Universitario Severo Ochoa (Leganés, Madrid)
- Hospital San Francisco de Asís (Madrid)
- Clínica CEMTRO (Madrid)

Additional affiliate centres: ANNUAL_UPDATE_REQUIRED — the full list of 24 partner institutions is subject to annual revision.

**International clinical rotations:** UFV's Faculty of Medicine operates an international rotation programme with 4-week placements at all UFV-affiliated hospitals, available to visiting students from partner universities. Applications open annually October–November. Duration may vary by bilateral agreement.

Clinical specialties covered across Years 3–6 include: cardiology, respiratory medicine, gastroenterology, dermatology, ophthalmology, otorhinolaryngology, psychiatry, geriatrics, neurology, endocrinology, haematology, gynaecology, obstetrics, paediatrics, traumatology, oncology, infectious diseases, immunology, emergency medicine, ICU, primary care, and forensic medicine.

## International Recognition and Opportunities

UFV's Grado en Medicina is verified and registered in the RUCT (Registro de Universidades, Centros y Títulos), the official Spanish degree registry, which is the prerequisite for MIR access and EU-wide recognition under Directive 2005/36/EC.

WFME accreditation status: PENDING_CONFIRMATION. International applicants should verify recognition in their home country independently.

UFV has over 200 exchange agreements across Europe, Asia, and the Americas, achieving an 8.4/10 student rating for international experience. Whether Medicine-specific bilateral agreements exist within this network requires PENDING_CONFIRMATION — not all university-wide agreements cover regulated degrees.

The university participates in RCI U Education (Regnum Christi's international university network), which connects it to CETYS Universidad (Mexico) and other affiliated institutions, providing some intra-network mobility pathways.

## Admission Model

UFV uses a **multi-component weighted admission model** with two structured rounds across the academic year, allowing both early-admission (Round 1, February) and standard-cycle (Round 2, July) pathways.

**Round 1 — Early Admission (February results):** Exclusive to candidates currently in their final year of Bachillerato (or equivalent) from science/health or technology branches. The weighting is: 65% academic record (1st year Bachillerato) + 30% UFV psychometric aptitude test + 5% English test. This round rewards consistency and early preparation, and it effectively gives high-performing current Bachillerato students a head start before the PAU.

**Round 2 — Standard Admission (July results):** Open to all access routes, including candidates who did not qualify in Round 1, those from any Bachillerato branch (provided they have passed PAU phase-specific subjects), university transcript transfers, and degree holders. Weighting shifts to: 70% academic record (PAU / Credencial UE / homologación + PCE) + 25% UFV psychometric aptitude test + 5% English test.

The **psychometric aptitude test** is the proprietary differentiator in UFV's model. All candidates — regardless of access route — must sit this test onsite (with an online exception for non-mainland residents). The test lasts approximately 2 hours and is described as a multiple-choice aptitude assessment. Students who have sat the UFV test within the past 5 years are exempt from re-sitting. This creates meaningful year-on-year preparation value.

The **selective interview** introduces an eliminatory risk element: UFV's admissions committee may call any candidate for a personal online interview. Attendance is mandatory; failure to attend results in automatic withdrawal. The interview serves as a holistic judgment tool rather than a scored component, and its selection criteria are not publicly disclosed.

**Complementary points (vínculos UFV)** provide small bonuses for candidates with institutional ties — Regnum Christi-affiliated school alumni, CETYS or UFV alumni, siblings of current UFV students, and children of UFV employees. The quantitative impact of these bonuses on final ranking is not disclosed.

## Admission Process

1. Register via the online form at ufv.es/pruebas-de-admision-medicina/ — one registration only, using the candidate's name and a single email address.
2. Receive portal access credentials by email (check spam); access the Candidate Portal.
3. Upload required identity document (DNI or passport) and complete the personal data form.
4. Pay the non-refundable registration fee of €170 (no PayPal recommended). Exempt: Regnum Christi school students, current UFV students, UFV employee children.
5. Once documentation is accepted, select an exam date from the available onsite sessions. Places per session are limited — early booking advised.
6. Submit access route-specific documentation by the published deadline:
   - Route A: 1st Bachillerato grades by 3 February; PAU by 25 June — ANNUAL_UPDATE_REQUIRED
   - Routes B (Credencial UE / homologación + PCE) and C: by 24 August or 25 June depending on sub-route — ANNUAL_UPDATE_REQUIRED
   - Routes D, E, F: academic transcripts by 25 June — ANNUAL_UPDATE_REQUIRED
7. Await publication of admission list (Round 1: 18 February; Round 2: 1 July) — ANNUAL_UPDATE_REQUIRED
8. If admitted, pay the place deposit of €4,250 within the specified deadline (€3,250 first payment + €1,000 second payment). Deposit is non-refundable under all circumstances, including subsequent withdrawal.

## Admission Timeline

| Event | Date (2026–27) | Note |
|---|---|---|
| Applications open | ANNUAL_UPDATE_REQUIRED | Process typically opens in autumn of prior year |
| Registration fee | €170 | Non-refundable |
| Round 1 exam dates | March–April 2026 (multiple sessions) | ANNUAL_UPDATE_REQUIRED |
| Round 1 grade deadline (Route A) | 3 February 2026 | ANNUAL_UPDATE_REQUIRED |
| Round 1 results | 18 February 2026 | ANNUAL_UPDATE_REQUIRED |
| PAU / Round 2 documentation deadline | 25 June 2026 | ANNUAL_UPDATE_REQUIRED |
| Routes B/C international docs deadline | 24 August 2026 | ANNUAL_UPDATE_REQUIRED |
| Routes D/E/F docs deadline | 25 June 2026 | ANNUAL_UPDATE_REQUIRED |
| Round 2 results | 1 July 2026 | ANNUAL_UPDATE_REQUIRED |
| Routes E/F results | Mid-July 2026 | ANNUAL_UPDATE_REQUIRED |
| Place deposit (Round 1) | Within deadline post-notification | ANNUAL_UPDATE_REQUIRED |
| Place deposit (Round 2) | Within deadline post-notification | ANNUAL_UPDATE_REQUIRED |

Candidates who were tested in previous cycles (within 5 years) need only register by 15 June to be considered in Round 2, without re-sitting the aptitude test.

## Admission Score Distribution

The UFV model places the majority of scoring weight on factors that can be influenced before the PAU: the academic record (65% in Round 1, 70% in Round 2) and the UFV-specific aptitude test (30% in Round 1, 25% in Round 2).

The English test (5%) is a smaller differentiator but consistent across all routes and rounds. A B2 or C1 certificate does not substitute for the on-campus test; all candidates must sit it regardless of certifications held.

**Strategic reading:** A candidate with strong 1st year Bachillerato grades and good psychometric test preparation can secure a place in Round 1 without waiting for the PAU — a significant timing advantage that reduces uncertainty. Candidates who perform well on the psychometric test can compensate partially for a weaker academic record, though this is bounded by the 30% ceiling.

The PAU phase-specific subjects that count for UFV are Biology, Chemistry, Physics, and Mathematics II — specifically, the two highest-scoring approved subjects. This means candidates must prepare these four subjects to maximise their Round 2 score, which aligns well with general medicine admission strategy in Spain.

The selective interview, while not universally applied, introduces an unpredictable variable. Candidates with strong aptitude test results who are then called to interview must treat it as a serious elimination gate.

The complementary points (vínculos UFV) are unlikely to change outcomes for candidates who are not naturally within those affiliation categories, but they structurally favour Regnum Christi school alumni — a pool that feeds into UFV disproportionately.

## Costs and Payment Structure

| Concept | Amount | Notes |
|---|---|---|
| Registration fee | €170 | Non-refundable; waived for RC school students, current UFV students, UFV employee children |
| Place deposit (1st payment) | €3,250 | Non-refundable; paid upon pre-admission notification |
| Place deposit (2nd payment) | €1,000 | Non-refundable; paid within UFV-specified deadline |
| Annual tuition (Year 1) | €20,400 | ANNUAL_UPDATE_REQUIRED |
| Initial payment at enrolment | €2,500 | Deducted from annual total |
| Second initial payment | €1,000 | Part of annual total |
| Monthly instalments | €1,690 × 10 | Completing the €20,400 annual total |
| Annual tuition (Years 2–6) | ANNUAL_UPDATE_REQUIRED | Typically similar to Year 1; confirm annually |

The €4,250 deposit is deducted from the first-year tuition upon formal enrolment, but it is not refundable under any circumstances — including withdrawal after enrolment or during the degree. This is explicitly stated in the UFV admissions documentation and overrides any right-of-withdrawal protections under consumer law (Art. 103 TRLGDCU).

Over six years at the Year 1 tuition rate, the gross tuition cost is approximately €122,400, excluding registration fees, living costs, and annual adjustments.

## Scholarships and Financial Aid

UFV operates a scholarships programme through its Financial Aid Service (Servicio de Ayuda al Estudio), which offers grants and financial support based on academic excellence, personal talent, and socioeconomic circumstances. UFV positions itself as having one of the highest scholarship student percentages among Spanish private universities.

Specific scholarship amounts and conditions applicable to Medicine: ANNUAL_UPDATE_REQUIRED. Candidates interested in financial aid should contact the Financial Aid Service before committing to the admissions deposit, as the non-refundable deposit commitment precedes formal enrolment scholarship decisions.

UFV-affiliated Becas Europa scholarships may also be available. Eligibility and scope: ANNUAL_UPDATE_REQUIRED.

External scholarships from Ministerio de Educación (Beca MEC) may apply to private university tuition under the non-university private institution modality, subject to eligibility criteria. Candidates should verify current MEC coverage for private university Medicine programmes.

## Accommodation and Cost of Living

UFV's campus in Pozuelo de Alarcón is self-contained and located outside central Madrid, approximately 15–20 minutes from the city centre by public transport. The university operates its own Colegio Mayor (university hall of residence) on campus — students must apply separately and independently from the academic admission process, as selection criteria differ.

Living costs in the greater Madrid area (Pozuelo de Alarcón included) are moderately high by Spanish standards. Estimated monthly costs for a student in shared accommodation outside campus: €900–€1,200 including rent, food, transport, and personal expenses — PENDING_CONFIRMATION. Campus Colegio Mayor accommodation: ANNUAL_UPDATE_REQUIRED.

Pozuelo de Alarcón is well connected to Madrid by urban rail (Cercanías) and metro, enabling students who live in Madrid to commute. The hospital network for clinical placements is distributed across the Madrid metropolitan area, requiring some travel.

## International Exchange and Mobility Programs

UFV has an extensive international agreements network of over 200 partner universities across Europe, Asia, and the Americas, with an 8.4/10 student satisfaction rating for international experience. Whether specific bilateral exchange agreements exist for Medicine students (as opposed to the general university network) requires PENDING_CONFIRMATION — regulated degrees often operate under separate or restricted mobility frameworks.

The Erasmus+ programme is active at UFV. Medicine-specific Erasmus placements: PENDING_CONFIRMATION.

The RCI U Education network (Regnum Christi) connects UFV with CETYS Universidad (Mexico), which may offer intra-network mobility pathways for Medicine students specifically. Scope and conditions: PENDING_CONFIRMATION.

International clinical rotations for visiting students are available through UFV's Faculty of Medicine programme (4-week rotations at affiliated hospitals, October–November application window).

## MIR Preparation and Professional Outcomes

UFV explicitly promotes strong MIR outcomes as a key institutional differentiator. The programme achieves top results in MIR pass rates and in the allocation of specialist training positions across multiple examination cycles. Specific pass rate percentages and specialty allocation rankings: PENDING_CONFIRMATION (not published in standardised format).

The degree provides direct access to the MIR (Médico Interno Residente) examination — the national medical specialisation examination — which is the primary career pathway for graduates intending to specialise within Spain's public or private healthcare system.

UFV graduates report a 95% employability rate in Medicine within 12 months of graduation (source: UFV institutional data). Independent verification: PENDING_CONFIRMATION.

The postgraduate Medicine training arm (Formación Posgrado Medicina UFV) offers continuing education and specialist update programmes for practising physicians, indicating institutional investment beyond undergraduate training.

## Strategic Fit

### Good Fit For

- Students from Regnum Christi-affiliated schools who have early Bachillerato grade consistency and want to secure an admission place before the PAU.
- International students with Credencial UE or non-EU homologation who prefer a Madrid location with a dedicated online exam option for non-mainland candidates.
- Students who respond well to humanistic, person-centred teaching environments and value the pastoral and community dimension of the university experience.
- Candidates prepared for the UFV proprietary psychometric test who can treat it as a repeatable competitive advantage — particularly those retaking with prior test experience (exempt from re-sitting for 5 years).
- Profiles seeking early clinical immersion from Year 1 combined with simulation-based training, without waiting until Year 3 for hospital contact.
- Students considering a business management minor alongside Medicine, for those with long-term interest in health management or healthcare entrepreneurship.

### Less Suitable For

- Candidates who require transparent and published admission criteria at every stage — UFV's selective interview adds an unpredictable eliminatory risk that is not algorithmically disclosed.
- Students with limited financial flexibility: the €4,250 non-refundable deposit combined with €20,400 annual tuition and a non-refundable registration fee creates significant irrecoverable financial commitment before formal enrolment.
- Candidates whose strongest asset is PAU phase-specific subject scores rather than overall academic record — Round 2's 70% PAU weighting is competitive, but Round 1 already fills a substantial share of places before PAU results exist.
- Students seeking a bilingual or English-taught programme: UFV Medicine is taught entirely in Spanish.
- Candidates who are not comfortable with mandatory onsite exam attendance, unless located outside mainland Spain.

## Risks and Considerations

**Non-refundable deposit risk:** The €4,250 place deposit is non-refundable under all circumstances, including if the student later withdraws voluntarily. This is explicitly structured to preclude consumer right-of-withdrawal. Candidates should be certain of their choice before committing.

**Selective interview opacity:** UFV does not publicly disclose the criteria by which candidates are called for the personal interview, nor the content or scoring of the interview itself. A candidate with a strong composite score could be rejected at the interview stage without any avenue for appeal or transparency.

**Annual update dependency:** Seat numbers, tuition fees, exam dates, and admission criteria are all subject to annual revision. The 2026–27 figures in this file reflect the most recent verified data but must be confirmed directly with UFV each cycle.

**Hospital network variability:** The list of affiliated hospitals and clinical placement centres is subject to annual revision. Candidates should verify the current network and ensure relevant specialties are covered before committing.

**MIR data opacity:** UFV publicly claims strong MIR outcomes but does not publish standardised pass rate data that would enable comparison with other institutions. Prospective students should seek independent verification of MIR performance.

**Psychometric test preparation:** The UFV aptitude test is proprietary and not based on PAU or public syllabus content. Students without access to UFV-specific preparation materials may face an unlevelled playing field on their first attempt.

## Important Notes

- The registration fee (€170) and the place deposit (€4,250) are both non-refundable in all cases.
- Candidates may only register once; duplicate registrations result in exclusion.
- The aptitude test must be sat onsite; online option is strictly reserved for candidates living outside mainland Spain.
- Round 1 is exclusively for candidates currently in their last year of Bachillerato from science/health or technology branches — candidates from other branches cannot access Round 1 results.
- PAU phase-specific scores are valid for only 2 years — candidates with older PAU scores must verify their eligibility for Round 2.
- UFV reserves the right not to fill all Route D (university degree holders) places if the committee deems the candidates do not meet admission quality standards.
- Routes E and F (Medicine transfers) results are published in mid-July, after the main Round 2 list.
- Contact for Medicine admissions: admisionmedicina@ufv.es

## Key Insight

UFV's two-round model with an early February admission list creates a strategically important timing opportunity that most other private Medicine programmes do not offer: a strong student in their final Bachillerato year from a science or technology branch can secure a confirmed place months before the PAU — effectively de-risking the admissions outcome regardless of PAU performance. For students with consistent 1st-year Bachillerato grades (the 65% component in Round 1) and focused preparation for the UFV aptitude test, Round 1 is the primary strategic target.

The psychometric aptitude test is the most distinctive and controllable variable in the model. Unlike academic record (which reflects years of prior performance), aptitude test preparation can be structured and iterative — and the 5-year validity exemption means prior test-takers carry forward their performance without re-commitment. This creates a compound strategic advantage for candidates who invest in UFV-specific test preparation.

## Final Takeaway

UFV Medicine occupies a well-defined strategic position among Madrid's private Medicine programmes: a large, humanistically-oriented programme with strong clinical infrastructure, an early-admission pathway that rewards consistent Bachillerato students, and a distinctive aptitude-test-based evaluation that is controllable through preparation. Its Regnum Christi identity creates a culturally specific fit that is a genuine strength for aligned students and a relevant consideration for those who are not.

The principal risks are financial (the aggressive non-refundable deposit structure), transparency (selective interview opacity, undisclosed MIR data), and annual variability (seats, fees, hospital network all change yearly). Candidates treating UFV as a serious option should commit to the admissions process early, prepare specifically for the UFV aptitude test, and treat the deposit decision with full awareness of its irrecoverable nature.

## Frequently Asked Questions

**How many places does UFV Medicine offer?**
160 places for 2026–27 (155 via Routes A/B/C + maximum 5 via Route D). Routes E and F (Medicine transfers) depend on available vacancies in each year of the programme. This figure is subject to annual revision.

**Can international students with a foreign Bachillerato apply?**
Yes. UFV accepts Credencial UE (for EU or equivalent education systems), and homologación + PCE/UNED scores (for non-EU systems). International candidates follow Route B and must submit their credentials by the deadline (typically 24 August for the second list). An online exam option is available for candidates residing outside mainland Spain.

**What is the UFV aptitude test?**
A proprietary multiple-choice psychometric aptitude test administered onsite at UFV's Pozuelo de Alarcón campus (approximately 2 hours total session). It is not based on a published syllabus. Candidates who have sat the UFV test within the previous 5 years are exempt from re-sitting and only need to register by 15 June to participate in Round 2. Results are valid as long as the 5-year window applies.

**Is the personal interview compulsory?**
The interview is selective — UFV's admissions committee decides which candidates to call. However, if you are called, attendance is mandatory. Failure to attend results in automatic withdrawal from the admission process, regardless of your composite test score.

**Is the €4,250 deposit refundable if I change my mind?**
No. The deposit is non-refundable in all circumstances, including voluntary withdrawal after enrolment. UFV explicitly excludes the right of withdrawal under Article 103 of the TRLGDCU. This is a firm financial commitment.

**What PAU subjects count towards UFV's Round 2 admission?**
Biology, Chemistry, Physics, and Mathematics II. UFV counts the two highest-approved phase-specific subject scores. These scores are valid for only 2 years after the PAU is taken.

**What is the annual tuition fee?**
€20,400 for Year 1 (2026–27). Subject to annual revision. Payment is structured as an initial payment (€2,500), a second initial payment (€1,000), and ten monthly instalments of €1,690. The €4,250 deposit is deducted from the annual tuition.

**Does UFV Medicine have good MIR results?**
UFV claims strong MIR pass rates and top specialist placement allocations across multiple examination cycles. Specific published data for comparison is not available; prospective students are advised to request current MIR statistics directly from the Faculty of Medicine.

**What hospitals will I train in?**
UFV's clinical network includes eight public and private university hospitals and sixteen specialised centres. Confirmed affiliates include Hospital Universitario Severo Ochoa and Hospital San Francisco de Asís. The full updated list should be confirmed with UFV each year as network agreements are revised.

**Can I study Medicine at UFV entirely in English?**
No. The degree is taught entirely in Spanish. An English proficiency test is part of the admission scoring, and one subject (Applied Scientific English Applied to Medicine) is offered in Year 2, but the programme is not bilingual or English-medium.
