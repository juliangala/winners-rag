---
id: blanquerna-medicine

type: university
subtype: private

name: Facultat de Ciències de la Salut Blanquerna-URL
short_name: Blanquerna

degree: Medicine

last_update: 2026-05-27

valid_for_intake: 2026-2027

location:
  city: Barcelona
  region: Cataluña
  country: Spain

strategic_tags:
  - core_option
  - rolling_admissions
  - early_application_advantage
  - exam_heavy
  - bilingual_program
  - high_cost
  - academic_exam_required
  - onsite_exam_required
  - strong_clinical_exposure

admission:
  intake_month: September

  applications_open_date: 2025-10-31 # ANNUAL_UPDATE_REQUIRED

  rolling_admissions:
    enabled: true
    estimated_end_date: 2026-06-30 # ANNUAL_UPDATE_REQUIRED — closes earlier if all seats filled

  admission_rounds:
    enabled: true
    count: 3

    rounds:
      - round: 1
        application_deadline: NULL
        exam_date: 2025-12-13 # ANNUAL_UPDATE_REQUIRED — CLOSED for 2025-26 cycle
        results_date: NULL
        deposit_deadline: NULL

      - round: 2
        application_deadline: NULL
        exam_date: 2026-02-21 # ANNUAL_UPDATE_REQUIRED — CLOSED for 2025-26 cycle
        results_date: NULL
        deposit_deadline: NULL

      - round: 3
        application_deadline: 2026-06-30 # ANNUAL_UPDATE_REQUIRED
        exam_date: 2026-07-02 # ANNUAL_UPDATE_REQUIRED
        results_date: NULL
        deposit_deadline: NULL

  exam_required: true
  interview_required: false

academic_record:
  minimum_requirement:
    enabled: false
    grade_source: NULL
    minimum_grade: NULL

  competitive_filter:
    enabled: false
    grade_source: NULL
    approx_candidates_selected: NULL

curriculum:
  international_curriculums_accepted:
    - Bachillerato nacional (Year 1 or complete)
    - PAU
    - CFGS
    - Estudios universitarios finalizados (via CAO)
    - Bachillerato Internacional (IB)
    - EEES-equivalent credentials via UNED credential
    - Non-EEES with homologated secondary title from Ministerio de Educación or Generalitat de Catalunya

competitiveness:
  level: PENDING_CONFIRMATION # Inaugural cohort 2026-27; no historical admission data available

admissions_statistics:
  annual_applications: NULL # ANNUAL_UPDATE_REQUIRED — new degree, no historical data
  seats: NULL # Not published by the university
  applicants_per_seat: NULL # ANNUAL_UPDATE_REQUIRED — new degree

  last_admitted_scores:
    - intake_year: 2026-2027
      round: NULL
      score: 8.0 # ANNUAL_UPDATE_REQUIRED — published minimum threshold on the 0-10 admission scale
      score_type: admission_score_minimum
      notes: University states admission requires ≥ 8.0/10 composite score. If this threshold leaves fewer than 40% of seats filled after a round, the cut-off is lowered until 40% of seats are covered. Score is maintained across rounds; students who do not gain admission in one round automatically carry their score to the next.

international_profile:
  international_students_percentage: NULL # ANNUAL_UPDATE_REQUIRED — new degree
  international_nationalities:
    - country: NULL
      percentage: NULL

programs:
  - id: blanquerna-medicine-barcelona

    campus: Campus Salut Blanquerna-URL — c/ Padilla 326 i Travessera de Gràcia 401, 08025 Barcelona

    modality: bilingual

    strategic_tags:
      - rolling_admissions
      - early_application_advantage
      - exam_heavy
      - bilingual_program
      - high_cost
      - onsite_exam_required
      - strong_clinical_exposure

    teaching_languages:
      - Catalan
      - Spanish

    regional_language_possible: true
    regional_language: Catalan

    language_requirements:
      minimum_spanish_level_non_native: B2
      english_required: false
      minimum_english_level: NULL

    seats: NULL # Not published; ANNUAL_UPDATE_REQUIRED

    program_statistics:
      annual_applications: NULL
      seats: NULL
      applicants_per_seat: NULL

      last_admitted_scores:
        - intake_year: 2026-2027
          round: NULL
          score: 8.0
          score_type: admission_score_minimum
          notes: Minimum composite admission score published as ≥ 8.0/10. New degree; no prior intake data available.

    program_specific_admission:
      enabled: false

    evaluation_model:
      overall_model_type: weighted

      admission_pathways:
        - eligible_profiles:
            - Bachillerato nacional (Year 1 or complete)
            - PAU
            - CFGS
            - Estudios universitarios finalizados (CAO)
            - Bachillerato Internacional (IB)
            - EEES equivalent

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 30
              grade_source: mixed # BAT Y1 or complete, PAU, CFGS, or CAO depending on applicant status at time of application
              minimum_required_grade: NULL
              notes: The grade source is whichever credential the student holds at time of application. Students who have not yet completed PAU or CFGS may enroll conditionally (matrícula condicionada); their academic record grade is calculated from whatever they have submitted. No published minimum academic record threshold; filtering occurs via the composite admission score.

            - component: academic_exam
              enabled: true
              role: weighted
              weight: 35 # 50% of the 70% admission test block = 35% of total admission score
              exam_variant: onsite_internal_exam
              exam_format: multiple_choice
              delivery_mode: onsite
              online_conditions: NULL

              subjects:
                - Biology
                - Chemistry
                - Mathematics
                - English
                - General culture / current affairs

              syllabus_alignment:
                biology:
                  scope:
                    - first_year_baccalaureate
                  notes: Biology evaluated at Y1 bachillerato curriculum level

                chemistry:
                  scope:
                    - first_year_baccalaureate
                  notes: Chemistry evaluated at Y1 bachillerato curriculum level

                physics:
                  scope:
                    - not_applicable
                  notes: Physics is not part of this exam

                mathematics:
                  scope:
                    - first_year_baccalaureate
                  notes: Mathematics evaluated at Y1 bachillerato curriculum level

                other_subjects:
                  - subject: English
                    scope:
                      - first_year_baccalaureate
                    notes: English proficiency tested at approximately Y1 bachillerato level

                  - subject: General culture / Ciències del Món Contemporani
                    scope:
                      - university_specific_syllabus
                    notes: Actualitat i cultura general — no formal syllabus published; tests current affairs awareness and general scientific literacy

              exam_difficulty:
                level: medium
                rationale:
                  - first_year_only_syllabus
                  - multidisciplinary_exam
                  - reasoning_based
                notes: Five subject areas at Y1 level, including English and general culture. Breadth is the primary challenge rather than depth. Total exam session (both components) estimated at ≈ 2h30.

              best_attempt_counts: NULL # Score retained across rounds; students may sit a later round at no additional exam cost if already registered
              notes: Represents 50% of the admission test block and 35% of the overall admission score. Sat simultaneously with the psychometric_test component in a single ≈ 2h30 session.

            - component: psychometric_test
              enabled: true
              role: weighted
              weight: 35 # 50% of the 70% admission test block = 35% of total admission score
              test_format: multiple_choice
              delivery_mode: onsite
              online_conditions: NULL
              notes: Evaluates personal, ethical and vocational alignment with the Medicine degree profile, plus reading comprehension. Multiple-choice format. Sat in the same session as the academic_exam (combined ≈ 2h30). Score is maintained across rounds.

            - component: isat
              enabled: false
              role: NULL
              weight: NULL
              notes: NULL

            - component: english_test
              enabled: false
              role: NULL
              weight: NULL
              notes: NULL

            - component: interview
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
---

# Blanquerna-URL — Facultat de Ciències de la Salut

## Overview

Blanquerna is the health sciences faculty of Universitat Ramon Llull (URL), a private Catholic university in Barcelona with roots in the Jesuit educational tradition. The Medicine degree is an entirely new program launching its inaugural cohort in September 2026, making Blanquerna the most recently launched private Medicine degree in Spain for the 2026-27 cycle.

The admission model is strongly exam-weighted: 70% of the composite score derives from two written tests sat on the same day — a knowledge test (Bio, Chem, Math, English, general culture) and a personal/vocational aptitude test — with only 30% from the academic record. This structure systematically benefits students who test well regardless of secondary school grades, and disadvantages those who rely primarily on strong academic records.

The program is academically grounded in a humanistic-scientific balance that the university brands as "high tech, high touch, high commitment." Clinically, students rotate through a curated network of private and semi-public hospitals led by Quirónsalud and Fundació Hospitalàries. The teaching language is primarily Catalan with Spanish as a parallel option, requiring B2 proficiency in at least one of the two.

Because no graduates have existed yet, MIR outcomes, dropout rates, and actual cut-off histories are all PENDING_CONFIRMATION. The university's standing within URL's broader academic ecosystem — collaborating with IQS, La Salle, Esade, and the Institut Borja de Bioètica — is a genuine differentiator, but its impact on the Medicine degree's quality is still to be demonstrated.

## Quick Evaluation

- **Inaugural degree**: First cohort September 2026 — no MIR data, no historical cut-offs, no graduate outcomes
- **Admission formula**: 30% academic record + 35% knowledge exam + 35% aptitude/vocational test
- **Exam scope**: Y1 bachillerato level (Bio, Chem, Math, English, general culture) — multiple choice
- **Onsite exams only**: All exam dates require physical presence in Barcelona
- **Rolling admissions with 3 rounds**: December 2025 (closed), February 2026 (closed), July 2026 (open)
- **Published minimum threshold**: Admission score ≥ 8.0/10 required to be admitted
- **Tuition**: 315 EUR/ECTS × 60 ECTS = 18,900 EUR/year (2026-27) — subject to annual revision
- **Strong scholarship program**: Top scorer eligible for 95% Year 1 tuition coverage
- **Language of instruction**: Catalan primary, Spanish parallel — B2 minimum required
- **Seats**: Not published
- **MIR outcomes**: Not available (new degree)

## Key Facts

| Field | Value |
|---|---|
| University | Facultat de Ciències de la Salut Blanquerna-URL |
| City | Barcelona |
| Campus | c/ Padilla 326 + Travessera de Gràcia 401, 08025 Barcelona |
| Duration | 6 years |
| Total ECTS | 360 |
| Teaching languages | Catalan (primary), Spanish (parallel) |
| Language requirement | B2 in Catalan or Spanish |
| Year 1-2 schedule | Morning: 9:00–14:00 h (some afternoon lab sessions) |
| Year 3-6 schedule | Afternoon: 14:00–19:00 h |
| Tuition 2026-27 | 315 EUR/ECTS → 18,900 EUR/year (Year 1) |
| Application fee | 50 EUR (non-refundable) |
| Admission formula | 30% academic + 70% tests (split 50/50 between knowledge and aptitude) |
| Minimum admission score | ≥ 8.0/10 |
| Exam format | Multiple choice, onsite, ≈ 2h30 |
| Exam dates 2025-26 | Dec 13 2025 (closed), Feb 21 2026 (closed), Jul 2 2026 (open) |
| Accreditation | AQU Catalunya verification (national) |
| MIR outcomes | Not available — inaugural degree |
| Seats | Not published |

## Program Options

There is one campus and one program track. The degree is delivered on two buildings of the Campus Salut Blanquerna-URL in Barcelona — c/ Padilla 326 (Eixample) and Travessera de Gràcia 401 (Gràcia), a short walk apart.

The program is classified as bilingual: Catalan is the primary teaching language, with Spanish used in parallel throughout the curriculum. No English-medium track exists. Students who prefer one language over the other should confirm subject-by-subject availability with the faculty, as individual professors may lean toward one language.

There are no reported separate pathways by academic background (BAT, CFGS, CAO/university transfer). All profiles compete under the same 30/70 formula, though the academic record component will use the grade source appropriate to each applicant's credential type.

## Program Structure

The degree runs for 6 academic years over 360 ECTS, organized as follows:

| Year | Formació bàsica | Obligatòria | Optativa | Pràctiques ext. | TFG | Total |
|---|---|---|---|---|---|---|
| 1 | 60 | — | — | — | — | 60 |
| 2 | 30 | 27 | 3 | — | — | 60 |
| 3 | — | 48 | — | 12 | — | 60 |
| 4 | — | 48 | — | 12 | — | 60 |
| 5 | — | 45 | 3 | 12 | — | 60 |
| 6 | — | 33 | 3 | 15 | 9 | 60 |
| **Total** | **90** | **201** | **9** | **51** | **9** | **360** |

**Year 1–2** cover foundational biomedical sciences (Biochemistry, Cell Biology, Anatomy, Embryology, Molecular Biology, Genetics, Physiology, Pharmacology, Pathology, Microbiology) alongside humanistic and communication modules.

**Year 3** marks the transition to clinical sciences with Semiologia, Diagnostic Imaging, and the start of external clinical rotations (Pràctiques Externes I, 12 ECTS).

**Years 4–5** introduce major clinical specialties: Cardiology, Respiratory, Infectious Diseases, Dermatology, Psychiatry, Gynaecology, Traumatology, Paediatrics, and Oncology.

**Year 6** is distinctly forward-looking: AI and Robotics in Health, Clinical Leadership and Health Management, Planetary Health, Palliative Care, and the Treball de Fi de Grau (TFG, 9 ECTS), alongside the largest clinical rotation block (15 ECTS, Pràctiques Externes IV).

Elective credits (9 ECTS total, distributed across Y2, Y5, Y6) allow some degree of specialization. The program includes a notable humanistic thread — Fonaments Humanístics de la Medicina runs across Years 1, 2, and 3 — reflecting the university's values-based educational philosophy.

## Teaching Methodology

The faculty describes three defining educational pillars: high scientific and technological knowledge, deep humanistic training in doctor-patient communication, and strong social commitment to integral patient care. This framework, borrowed from URL's institutional identity, translates operationally into a curriculum that balances hard science with ethics, communication, and social medicine.

Clinical simulation begins before patient contact: students work in simulation labs and anatomy rooms — including an Anatomage 3D table — before starting external rotations in Year 3. Clinical tutoring follows a structured model with briefings, mid-briefings, and debriefings at each rotation, supervised by both clinical and academic tutors.

The Medicina i Salut Digital module in Year 2 introduces digital health competencies early. Year 6 includes a dedicated course on Artificial Intelligence and Robotics in Health, positioning graduates for an increasingly technology-mediated healthcare environment.

Personalized attention is a structural feature of Blanquerna's model: the faculty emphasizes small-group settings and direct access to professors, which is consistent with a new program likely to have smaller initial cohorts.

## Clinical Training

Clinical rotations total 51 ECTS across Years 3–6, structured as four progressive blocks (Pràctiques Externes I–IV). Rotations cover Medicine, Surgery, Medical and Surgical Specialties, Family and Community Medicine, and Psychiatry.

The confirmed clinical partner network for 2026-27 includes: ANNUAL_UPDATE_REQUIRED

- **Grup Quirónsalud**: Hospital Quirónsalud Barcelona, Hospital El Pilar, Hospital Quirónsalud Badalona
- **Fundació Hospitalàries**: Barcelona Hospital General, Barcelona Nord, Martorell, Sant Boi
- **Germanes Hospitalàries Research Foundation (FIDMAG)**
- **Primary care**: CAP Vallcarca, CAP Sant Gervasi, EAP Dreta de l'Eixample – CAP Roger de Flor
- **Parc Sanitari Sant Joan de Déu**

This network covers private hospitals (Quirónsalud), religious-order hospitals (Hospitalàries, Sant Joan de Déu), and urban primary care centers (CAPs). The combination provides exposure to both hospital and community medicine settings.

Erasmus mobility and international rotation programs are referenced on the website as possible options, but no confirmed Medicine-specific bilateral agreements have been published. Students interested in international rotations should verify availability directly with the faculty.

## International Recognition and Opportunities

Blanquerna holds AQU Catalunya verification for the Medicine degree, which is the standard national quality assurance process for Spanish university degrees. This ensures the degree meets official Spanish and EU requirements for the professional title of Médico/a.

No WFME (World Federation for Medical Education) accreditation has been announced, which means graduates seeking licensure in the United States or other jurisdictions that require WFME-accredited degrees will face additional procedural hurdles. The Título de Graduado en Medicina obtained at Blanquerna enables MIR access and full EU-wide medical practice under standard EU mutual recognition rules.

URL is a member of Aristos Campus Mundus, a network of European private universities committed to internationalization and research excellence. The Oficina de Mobilitat Internacional facilitates Erasmus and bilateral exchange programs, but their application to Medicine students specifically must be confirmed with the faculty. Students from the European Higher Education Area (EEES) and IB holders can access the degree without PAU through a UNED credential. Students outside the EEES must provide a homologated secondary title from the Spanish Ministry of Education or the Generalitat de Catalunya.

## Admission Model

Blanquerna uses a **weighted composite model** with a single published formula applicable to all eligible academic profiles:

- **30%** academic record (grade from BAT Year 1 or complete, PAU, CFGS, or CAO depending on applicant status)
- **70%** admission tests, split equally:
  - 50% of the test block = **knowledge test** (multiple choice): Biology, Chemistry, Mathematics, English, and general culture/current affairs at Y1 bachillerato level
  - 50% of the test block = **aptitude/vocational test** (multiple choice): personal, ethical and vocational alignment with the Medicine degree, plus reading comprehension

This yields an overall structure of 30% academic + 35% knowledge + 35% aptitude/vocational.

The two test components are administered in the same sitting, with a combined estimated duration of approximately 2 hours 30 minutes. Both tests are multiple choice. All exams are onsite in Barcelona; no online option is available.

A minimum composite admission score of **8.0/10** is required for admission. If a round closes with fewer than 40% of seats filled, the university will lower the cut-off until 40% of capacity is reached. Students who sit the exam and are not admitted in that round retain their score and are automatically eligible for subsequent rounds.

The admission process operates under rolling admissions: applications opened October 31, 2025 and remain open until June 30, 2026, or until all seats are filled. Three exam rounds were scheduled for 2025-26 (December 2025, February 2026, July 2026).

There is no interview component. There is no bonus for English certificates, extracurricular activities, or complementary points of any kind.

## Admission Process

1. **Create a user account** on the Blanquerna online registration system (single sign-on). If already registered, log in.
2. **Submit a place request (sol·licitud de plaça)** online or in person at the Servei d'Informació i Orientació a l'Estudiant (SIOE) at c/ Padilla 326.
3. **Pay the non-refundable application fee** of 50 EUR by credit/debit card (online) or cash/card (in person). Payment is processed through BBVA.
4. **Upload supporting documents** to the Dipòsit de documents:
   - Government-issued photo ID (DNI, NIE, or passport)
   - Official academic record: BAT grade transcript (Year 1 or complete), PAU, CFGS, or CAO — if available at time of application. Must include an official certificate for the academic record grade to be computed.
5. **Sit the admission exam** on one of the available exam dates (chosen at registration). Exam is in person in Barcelona. Duration ≈ 2h30 for both test components.
6. **Receive admission result** after each round. Admitted students are called to enroll (convocats a matrícula).
7. **Formalize enrollment**:
   - *Matrícula condicionada*: Available to students who have not yet completed PAU or CFGS. Reserves the place subject to delivering the final access credential later. If access is not obtained in June, the student can opt out (tuition refunded, minus the 50 EUR application fee) or remain on the waiting list until September.
   - *Matrícula definitiva*: For students who already hold their final access credential. Place is confirmed once enrollment is formalized and first payment made.
8. **Upload final access documentation** to the Dipòsit de documents if not already submitted at step 4. The place is not definitive until this is complete and first payment is made.

Students who are not admitted in one round maintain their score automatically and are considered in subsequent rounds without re-applying or re-paying.

For any enrollment question: suportmatricula@blanquerna.url.edu

## Admission Timeline

All dates below are ANNUAL_UPDATE_REQUIRED.

| Event | Date (2025-26 cycle) |
|---|---|
| Applications open | 2025-10-31 |
| Exam Round 1 | 2025-12-13 (CLOSED) |
| Exam Round 2 | 2026-02-21 (CLOSED) |
| Exam Round 3 | 2026-07-02 |
| Application deadline | 2026-06-30 (or earlier if seats fill) |
| Program start | September 2026 |

The first two rounds are now closed for the 2025-26 admissions cycle. Students applying in 2026 for the September 2026 cohort must sit the July 2 exam. Future intake cycles will likely offer three rounds again from October/November.

Rolling admissions reward early applicants: students who sit Round 1 (December) and are admitted lock in their place months before students who wait for later rounds. However, since Round 3 is still available at July 2, students who have not yet applied still have a pathway for the inaugural cohort.

## Admission Score Distribution

The 30/70 weighting structure is the defining feature of Blanquerna's admission model. With academic record contributing only 30%, the effective differentiation happens almost entirely on exam day:

- A student with BAT grade 7.0/10 scoring 8.5/10 on the exam achieves: 0.30 × 7.0 + 0.70 × 8.5 = 2.1 + 5.95 = **8.05/10** (just above the cut-off)
- A student with BAT grade 9.0/10 scoring 8.0/10 on the exam achieves: 0.30 × 9.0 + 0.70 × 8.0 = 2.7 + 5.6 = **8.30/10**
- A student with BAT grade 6.5/10 scoring 9.0/10 on the exam achieves: 0.30 × 6.5 + 0.70 × 9.0 = 1.95 + 6.3 = **8.25/10**

This math shows that exam performance dominates the outcome: improving by 0.5 points on the exam (3.5 points in total score) outweighs a full 2.5-point academic record advantage (only 0.75 points in total score). Students with average academic records but strong test preparation can realistically compete with top-grade applicants.

The aptitude/vocational component (35% of total) is equally weighted to the knowledge component. This is unusual: most universities separate "hard science" from "soft skills" in a way that favors the former. At Blanquerna, personal fit, ethics, vocational alignment, and reading comprehension collectively carry the same weight as Biology, Chemistry, Math, and English. Students who underperform in the vocational component cannot fully compensate with knowledge exam strength.

The published minimum threshold of 8.0/10 functions as an effective floor. Below 8.0, no admission is possible regardless of the seat situation, though the 40% rule allows for some softening in low-demand rounds. For the inaugural cohort, the actual competitive floor is unknown; it may be lower than at established programs if demand is lower than expected.

No historical cut-off data exists for this program. Score distribution norms, average exam results, and actual seat allocation outcomes will only become available after the 2026-27 cycle closes.

## Costs and Payment Structure

| Item | Amount | Notes |
|---|---|---|
| Application fee | 50 EUR | Non-refundable, paid at time of sol·licitud de plaça |
| Price per ECTS (2026-27) | 315 EUR | ANNUAL_UPDATE_REQUIRED |
| Year 1 tuition (60 ECTS) | 18,900 EUR | ANNUAL_UPDATE_REQUIRED |
| Estimated 6-year total | ~113,400 EUR | At current rate; ANNUAL_UPDATE_REQUIRED |

All per-credit and total figures are subject to annual revision. The university states that the price per credit is updated each academic year for all enrolled years.

**Payment options (Year 1):**

The university offers installment payment at 0% interest. Two structures are described:

From the main website (preferred/detailed version):
- 20% of total at enrollment (within 2 business days)
- 10% of total by May 30, 2026
- 70% in 9 monthly installments (October 2026 to June 2027) by direct debit

From the PDF brochure (slightly different framing):
- 20% at enrollment
- 10% in May 2026
- 70% in 10 monthly installments (September 2026 to June 2027)

Single lump-sum payment at enrollment is also available. Discounts for large/single-parent families (5%), disability >33% (5%), and Família Blanquerna alumni network (5%) are non-cumulative. Documentation must be submitted to Secretaria Acadèmica by September 30, 2026.

**External financing:** ImaginBank offers a Préstamo Skills&Education for students at Blanquerna. Beques Santander-URL are also available. No specific terms or caps are published.

## Scholarships and Financial Aid

Blanquerna operates a multi-tier scholarship and aid system. The most strategically relevant for high-performing Medicine applicants:

**Excellence prizes (Premis a l'excel·lència)** — based purely on admission exam score:
- **1st place** (highest admission score): 95% tuition coverage Year 1; 75% in subsequent years if academic conditions maintained
- **2nd–5th place**: 50% tuition coverage Year 1; maintained in subsequent years if conditions met

**Academic excellence prize** — based on secondary school/PAU record:
- 50% tuition discount, Year 1 and renewable through to graduation if academic standing maintained

**Sports excellence prize:**
- 50% tuition discount for federated athletes with podium results and good BAT/CFGS grades

**Need-based financial aids (Ajuts Blanquerna):**
- 11 awards ranging from 20% to 80% of tuition, calculated on a combination of admission score and family income
- Renewable each year if eligibility conditions are maintained
- Available for Year 1 students (initial grant) and for renewal from Year 2 onwards

**Additional supports:**
- Ajuts puntuals: emergency financial aid for enrolled students facing sudden economic hardship
- Ajuts per a persones refugiades o desplaçades: up to 50% for up to 6 students affected by international conflict (renewable subject to personal situation review)
- Ajuts a la mobilitat internacional: for Erasmus and exchange program participants
- AGAUR (Catalan government) grants for official degrees
- Ministerio de Educación y Formación Profesional (MEFP) national scholarships
- Govern andorrà, Govern de les Illes Balears, País Basc regional grants for students from those territories

The top-scorer scholarship (95% Year 1) makes Blanquerna potentially one of the most accessible programs financially for the single best-performing applicant in any given cycle. For most students, the relevant consideration is the 20–80% need-based aid band.

## Accommodation and Cost of Living

Blanquerna does not appear to operate a university residence or campus accommodation. Barcelona is one of Spain's most expensive cities for students.

| Cost item | Estimated range | Notes |
|---|---|---|
| Shared apartment room | 600–900 EUR/month | ANNUAL_UPDATE_REQUIRED — central Barcelona (Eixample, Gràcia) |
| Studio apartment | 900–1,400 EUR/month | ANNUAL_UPDATE_REQUIRED |
| Monthly transport pass | ≈ 20 EUR/month | T-Jove or equivalent zone 1 transit pass |
| Monthly living expenses (food, utilities, misc.) | 400–700 EUR/month | ANNUAL_UPDATE_REQUIRED |

Students from Catalonia or the Barcelona metropolitan area may commute from home, which substantially reduces the cost burden. Non-resident students should budget 1,000–1,600 EUR/month for accommodation and living expenses on top of tuition.

## International Exchange and Mobility Programs

Blanquerna's Oficina de Mobilitat Internacional manages Erasmus and bilateral exchange agreements across its faculties. International mobility opportunities are referenced in the Medicine degree page and the Ajuts Blanquerna a la mobilitat internacional exist for exchange participants.

However, no Medicine-specific Erasmus agreements or bilateral partnerships have been confirmed as of the last update. Given that this is an inaugural degree (first cohort September 2026), international mobility pipelines specific to Medicine are likely under development. Students interested in an international rotation or semester abroad should contact the faculty directly to verify what is available for Years 3–6.

Incoming international students wishing to study at Blanquerna via Erasmus would follow standard URL Erasmus protocols; details for Medicine specifically are PENDING_CONFIRMATION.

## MIR Preparation and Professional Outcomes

MIR outcomes are PENDING_CONFIRMATION. The degree launched its inaugural cohort in September 2026; the first graduates will not sit the MIR until approximately 2032–2033. No historical pass rate or ranking data exists for this program.

The curriculum's clinical design — strong clinical rotation volume (51 ECTS), structured simulation labs, dedicated Semiologia and Clínica Integrada modules, and a Year 6 focus on Urgencies, Intensive Care, Preventive Medicine, and Bioethics — is in principle aligned with MIR content areas. The Year 6 course on AI and Robotics in Health positions graduates ahead of an increasingly technology-informed MIR assessment landscape.

Professional outlets post-graduation follow the standard Spanish medicine pathway: MIR examination → medical specialty residency in the public or concerted system, or private practice within the Quirónsalud ecosystem or other private networks, with the Blanquerna clinical network as a natural starting point.

International professional practice in EU countries follows standard EU mutual recognition of medical qualifications. For non-EU practice (US, Canada, UK, etc.) additional licensing steps apply; the absence of WFME accreditation at Blanquerna is a relevant variable for students with these ambitions.

## Strategic Fit

### Good Fit For

- Students in or near **Barcelona** who want a values-based, humanist medical education within a well-resourced private university ecosystem (URL: IQS, La Salle, Esade, Institut Borja de Bioètica)
- Students with **average-to-good academic records** but strong exam performance — the 30/70 weighting heavily rewards test-day performance over grades
- Students who **function well in Catalan or Spanish** (B2 minimum required) and prefer a bilingual learning environment
- Students targeting the **July 2026 round** (only remaining round for the inaugural cohort) who need a late-cycle option
- Students who want **early certainty**: conditional enrollment allows securing a place before PAU results, useful for late-June PAU takers
- Students motivated by **social mission, ethics, and humanistic medicine** — the URL/Blanquerna educational identity is deeply values-driven and structurally reinforced throughout the curriculum
- Students with strong **aptitude/personality test** profiles who would be disadvantaged by pure-knowledge exams — the 35% vocational component levels the playing field

### Less Suitable For

- Students who **cannot travel to Barcelona** for the exam — no online or remote option is available for any of the three rounds
- Students with **very high academic records (9+)** who expect the academic component to be their primary differentiator — at 30% weight, a 9.5 vs 7.5 BAT grade difference is worth only 0.6 points in the total score
- Students seeking a **proven program with MIR data** — none exists for Blanquerna, and won't for at least 6 years
- Students planning to practice in the **United States or other WFME-requiring jurisdictions** — WFME accreditation is not confirmed for this program
- Students who **require English-medium instruction** or have low Catalan/Spanish proficiency — there is no English track and B2 is required
- Students whose families **cannot absorb the 18,900 EUR/year cost** without scholarship confirmation — given the inaugural year, scholarship selection processes and actual availability rates are unproven

## Risks and Considerations

**Inaugural degree risk**: Blanquerna's Medicine program starts from zero in September 2026. There is no MIR track record, no established alumni network, no published cut-off history, and no data on dropout or completion rates. Any quality assessments at this point are prospective and institutional — not empirical.

**Unknown seat count**: The university has not published the number of available places. This makes it impossible to assess actual competitiveness or calculate the applicant-to-seat ratio.

**Onsite-only exams**: All three exam rounds require presence in Barcelona. Students based outside Catalonia face travel costs and logistics not required at universities offering online or hybrid exam options. This is a meaningful access barrier compared to UIC, which offers online exams for non-Catalonia residents.

**Schedule structure**: Years 1–2 are morning (9–14h), then Years 3–6 shift permanently to afternoon (14–19h). This schedule shift has personal planning implications for students who have arranged accommodation, part-time work, or family commitments around morning availability.

**Catalan-primary teaching**: Students who are not comfortable in Catalan may find the learning environment demanding despite Spanish being available. The registration process and most official communications default to Catalan.

**No interviews, no portfolio, no bonus points**: The model is fully determined by grades + exam. There is no mechanism to demonstrate research experience, extraordinary motivation, or non-academic achievements. This is a double-edged sword: simple and transparent, but limiting for students whose strengths lie outside standard academic metrics.

**Annual price revision**: The 315 EUR/ECTS rate applies only to Year 1 of the 2026-27 cohort. The university explicitly states that prices are updated each year. Over a 6-year degree, total cost trajectory is not guaranteed.

**Hospital network in development**: The clinical partners listed are credible institutions, but as a new program, the depth and organization of the rotation program has not yet been validated by multiple cohort cycles.

## Important Notes

- The application fee of 50 EUR is non-refundable even if the student does not ultimately enroll.
- The Round 3 exam date (July 2, 2026) is currently the only remaining opportunity for the inaugural September 2026 cohort. No additional rounds have been announced.
- Students admitted conditionally (matrícula condicionada) who fail to obtain their PAU/CFGS by June will be placed on a waiting list until September; if access credentials are not obtained by September, the tuition payment is refunded but the 50 EUR application fee is not.
- The 8.0/10 minimum admission score threshold is composite (academic + exam), not exam-only.
- Discounts for large families, disability, and Família Blanquerna are mutually exclusive (non-cumulative) and must be documented at Secretaria Acadèmica by September 30, 2026.
- International students from EEES countries must obtain a UNED credential (Credencial UNED) before enrolling. Non-EEES students must present homologation of their secondary degree — a process that can take more than three months and should be initiated in parallel with the admission process.

## Key Insight

Blanquerna is entering the private Medicine market as a values-driven, humanistically-framed new entrant with institutional backing from one of Catalonia's most respected private university systems. The admission model is analytically unusual: the equal weighting of a vocational aptitude test and a knowledge test at 35% each — with academic record at only 30% — means that on exam day, who you are matters as much as what you know.

For the inaugural cohort, the most significant strategic variable is not the program itself — it is the absence of data. Every metric that matters to strategic decision-making (MIR results, actual cut-offs, seat fill rates, scholarship allocation outcomes) is unknown. Students choosing Blanquerna for September 2026 are making a bet on institutional quality and potential, not on demonstrated outcomes. That bet may well pay off. But it should be made with clear eyes.

## Final Takeaway

Blanquerna's Medicine degree is a credible new entrant with real structural strengths: a well-resourced university ecosystem (URL), a strong clinical partner network (Quirónsalud, Hospitalàries, Sant Joan de Déu), a differentiated admission model that rewards exam performance over grades, and a scholarship structure that can make the top score genuinely transformative financially. The humanistic-technological curriculum framework is coherent and forward-looking.

The program's defining weakness is chronological: it is new. No MIR outcomes, no cut-off history, no graduate cohort, no peer-reviewed evidence of educational efficacy. For students who need certainty, established programs remain the safer bet. For students who want to be part of a founding cohort within a serious institution, or whose profile fits the 30/70 exam-heavy model, Blanquerna for September 2026 is a legitimate and strategically interesting option — particularly if the July 2 exam represents a last opportunity in their cycle.

## Frequently Asked Questions

**Is Blanquerna a new university?**
No. Blanquerna is the health sciences faculty of Universitat Ramon Llull, a private university founded in 1990 and part of a broader network that includes ESADE, IQS, and La Salle. However, the Grau en Medicina is a new degree launching its first cohort in September 2026.

**Does Blanquerna require an entrance exam?**
Yes. 70% of the admission score comes from two multiple-choice tests sat in the same session (≈ 2h30): a knowledge test (Bio, Chem, Math, English, general culture) and a personal/vocational aptitude test. Both are multiple choice and must be taken on-site in Barcelona.

**Can international students take the exam online?**
No. All exam dates require physical presence in Barcelona. There is no remote or online exam option.

**What is the minimum score to be admitted?**
The published minimum composite admission score (30% academic + 70% exam) is 8.0/10. This threshold may be lowered by the university in a round if fewer than 40% of seats are filled.

**Is Catalan mandatory?**
B2 proficiency in Catalan or Spanish is required to follow classes. Teaching is conducted in both languages, with Catalan as the primary. Students who do not speak Catalan but have strong Spanish will likely manage, but should expect significant Catalan exposure in lectures, materials, and communications.

**What are the MIR results at Blanquerna?**
There are no MIR results. The program launches in September 2026 and the first graduates will not sit the MIR until approximately 2032–2033.

**Can I apply if I haven't finished my PAU yet?**
Yes. The matrícula condicionada option allows students who have applied for a place to enroll before obtaining their PAU or CFGS results, securing their place subject to presenting the credential later. If the access credential is not obtained, the tuition payment (but not the 50 EUR application fee) is refunded.

**Is there a scholarship for the top scorer?**
Yes. The student with the highest admission score receives a scholarship covering 95% of Year 1 tuition, renewable at 75% for subsequent years if academic performance conditions are maintained.

**What hospitals will students rotate through?**
Confirmed clinical partners include Quirónsalud Barcelona, El Pilar, and Badalona; Fundació Hospitalàries (Barcelona, Nord, Martorell, Sant Boi); FIDMAG Germanes Hospitalàries; CAP Vallcarca, CAP Sant Gervasi, CAP Roger de Flor; and Parc Sanitari Sant Joan de Déu.

**What is the difference between Blanquerna and UIC for Medicine?**
Both are Barcelona-area private Medicine degrees with similar tuition and Catalan-language environments, but they differ significantly in admission model (UIC: 50% academic + 25% knowledge + 25% emotional aptitude + written interview; Blanquerna: 30% academic + 35% knowledge + 35% vocational aptitude), exam delivery (UIC offers hybrid/online; Blanquerna is onsite only), accreditation (UIC holds WFME; Blanquerna holds AQU Catalunya), and program maturity (UIC has a track record; Blanquerna is inaugural in 2026).
