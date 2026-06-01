```md
---
id: ceu-ao-medicine

type: university
subtype: private

name: Universitat CEU Abat Oliba
short_name: CEU-AO

degree: Medicine

last_update: 2026-05-27

valid_for_intake: 2026-2027

location:
  city: Esplugues de Llobregat
  region: Cataluña
  country: Spain

strategic_tags:
  - core_option
  - medium_competitiveness
  - exam_heavy
  - academic_exam_required
  - onsite_exam_required
  - rolling_admissions
  - early_application_advantage
  - high_cost
  - strong_clinical_exposure

admission:
  intake_month: September

  applications_open_date: ANNUAL_UPDATE_REQUIRED # 2025-2026 intake: open from late 2025

  rolling_admissions:
    enabled: true
    estimated_end_date: ANNUAL_UPDATE_REQUIRED

  admission_rounds:
    enabled: true
    count: 2

    rounds:
      - round: 1
        application_deadline: ANNUAL_UPDATE_REQUIRED
        exam_date: 2026-02-28 # ANNUAL_UPDATE_REQUIRED
        results_date: ANNUAL_UPDATE_REQUIRED # Results communicated within 1 week of exam
        deposit_deadline: ANNUAL_UPDATE_REQUIRED

      - round: 2
        application_deadline: ANNUAL_UPDATE_REQUIRED
        exam_date: 2026-04-18 # ANNUAL_UPDATE_REQUIRED
        results_date: ANNUAL_UPDATE_REQUIRED # Results communicated within 1 week of exam
        deposit_deadline: ANNUAL_UPDATE_REQUIRED

  exam_required: true
  interview_required: false

academic_record:
  minimum_requirement:
    enabled: PENDING_CONFIRMATION
    grade_source: PENDING_CONFIRMATION
    minimum_grade: PENDING_CONFIRMATION

  competitive_filter:
    enabled: true
    grade_source: PENDING_CONFIRMATION
    approx_candidates_selected: PENDING_CONFIRMATION

curriculum:
  international_curriculums_accepted: true

competitiveness:
  level: medium

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: 50
  applicants_per_seat: PENDING_CONFIRMATION

  last_admitted_scores:
    - intake_year: 2026-2027
      round: NULL
      score: PENDING_CONFIRMATION
      score_type: PENDING_CONFIRMATION
      notes: First intake cycle. No historical admission score data available.

international_profile:
  international_students_percentage: PENDING_CONFIRMATION

  international_nationalities:
    - country: PENDING_CONFIRMATION
      percentage: PENDING_CONFIRMATION

programs:
  - id: ceu-ao-medicine-esplugues

    campus: Esplugues de Llobregat

    modality: standard

    strategic_tags:
      - core_option
      - medium_competitiveness
      - exam_heavy
      - academic_exam_required
      - onsite_exam_required
      - rolling_admissions
      - early_application_advantage
      - high_cost
      - strong_clinical_exposure

    teaching_languages:
      - Spanish

    regional_language_possible: true
    regional_language: Catalan

    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION

      english_required: false
      minimum_english_level: NULL

    seats: 50

    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 50
      applicants_per_seat: PENDING_CONFIRMATION

      last_admitted_scores:
        - intake_year: 2026-2027
          round: NULL
          score: PENDING_CONFIRMATION
          score_type: PENDING_CONFIRMATION
          notes: First intake cycle. No historical data available.

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
      overall_model_type: PENDING_CONFIRMATION # Detailed model in admission PDF (Rev_admision-medicina-CEU-ABAT-OLIBA-modificado.pdf). Based on accessible pages: presencial exam + academic record. Exact weighting not published.

      admission_pathways:
        - eligible_profiles:
            - Spanish_bachillerato
            - CFGS
            - International_equivalent

          components:
            - component: academic_record
              enabled: true
              role: PENDING_CONFIRMATION
              weight: PENDING_CONFIRMATION
              grade_source: PENDING_CONFIRMATION # Application requires 1st year bachillerato grades + partial 2nd year grades. Exact source weighting not published.
              minimum_required_grade: PENDING_CONFIRMATION
              notes: Application documentation includes bachillerato grades (Year 1 full + Year 2 partial at time of application). Exact weight vs exam score not published on accessible web pages. Full model in admission PDF.

            - component: academic_exam
              enabled: true
              role: PENDING_CONFIRMATION
              weight: PENDING_CONFIRMATION
              exam_variant: onsite_internal_exam
              exam_format: PENDING_CONFIRMATION
              delivery_mode: onsite
              online_conditions: NULL

              subjects:
                - PENDING_CONFIRMATION

              syllabus_alignment:
                biology:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: Exam subjects and syllabus scope not published on accessible pages. Available only in admission PDF.

                chemistry:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: Not confirmed from accessible sources.

                physics:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: Not confirmed whether physics is included.

                mathematics:
                  scope:
                    - PENDING_CONFIRMATION
                  notes: Not confirmed whether mathematics is included.

                other_subjects:
                  - subject: PENDING_CONFIRMATION
                    scope:
                      - PENDING_CONFIRMATION
                    notes: Complete exam structure only available in the official admission PDF which was not accessible during research.

              exam_difficulty:
                level: PENDING_CONFIRMATION
                rationale:
                  - PENDING_CONFIRMATION
                notes: First intake cycle — no historical exam data available. Exam structure not published on accessible pages.

              best_attempt_counts: PENDING_CONFIRMATION
              notes: Two exam sessions offered per intake cycle (February and April). Whether students may attempt both sessions is not confirmed. The exam is presencial (in-person) and is an exception to UAO CEU's general 100% online admission test. Exam is reported as free of charge for candidates.

            - component: isat
              enabled: false
              role: NULL
              weight: NULL
              exam_format: NULL
              delivery_mode: NULL
              online_conditions: NULL
              best_attempt_counts: NULL
              notes: NULL

            - component: english_test
              enabled: false
              role: NULL
              weight: NULL
              test_format: NULL
              delivery_mode: NULL
              online_conditions: NULL
              minimum_level: NULL
              bonus_max: NULL
              bonus_scale:
                B2: NULL
                C1: NULL
                C2: NULL
              notes: No separate English test for the standard Medicine track. UAO CEU applies an English level test only to bilingual degree programs; Medicine is Spanish-taught only.

            - component: psychometric_test
              enabled: false
              role: NULL
              weight: NULL
              test_format: NULL
              delivery_mode: NULL
              online_conditions: NULL
              notes: NULL

            - component: interview
              enabled: false
              role: NULL
              weight: NULL
              interview_format: NULL
              delivery_mode: NULL
              notes: No interview step described in the published admission process for Medicine.

            - component: complementary_points
              enabled: false
              role: bonus_only
              maximum_bonus: NULL
              categories:
                - category: NULL
                  max_points: NULL
              notes: No complementary points or bonus categories described.
---
# Universitat CEU Abat Oliba

## Overview

The Universitat CEU Abat Oliba (UAO CEU) launched its Grado en Medicina in September 2026, making it the newest private Medicine program in Spain and the first to open in Cataluña under the CEU network. The degree received a favorable evaluation from the Agència per a la Qualitat del Sistema Universitari de Catalunya (AQU Catalunya) before launch and is housed in the new Facultad de Ciencias de la Salud y de la Vida on the Esplugues de Llobregat campus — a municipality directly adjacent to Barcelona, positioned within the metropolitan area's growing biotech and pharmaceutical cluster.

With 50 seats, the program is small by design. Teaching uses active methodologies (flipped classroom, problem-based learning) with groups of 25 for seminars and 6 to 12 for practical sessions, resulting in a notably high staff-to-student ratio compared to most Spanish Medicine programs. Clinical exposure begins from Year 1, with hospital partners including Clínica Diagonal (FIATC), Hospital Universitari Clínica Teknon, Hospital SANITAS CIMA, and BSA Badalona Serveis Assistencials.

Because 2026-2027 is the inaugural cohort, there is no admissions history, no published score distribution, and no MIR outcome data. Candidates applying for this degree are effectively pioneers: the program's academic reputation and competitive profile will be established over the next several years. This represents both a genuine strategic opportunity (lower initial competitive bar, early-cohort advantages in faculty attention) and a material risk (unproven track record, unverified accreditation outcomes).

## Quick Evaluation

- **Intake**: 50 seats, one program, Spanish-taught, Esplugues de Llobregat (Barcelona metropolitan area)
- **First cohort**: September 2026 — no historical admissions data or MIR results available
- **Exam**: Required, presencial (in-person), two sessions per cycle (February and April)
- **Evaluation model**: PENDING_CONFIRMATION — detailed weighting matrix in official admission PDF, not published on accessible pages
- **Reservation fee**: €2,500 (deducted from Year 1 tuition; refundable until June 21)
- **Year 1 tuition**: €17,715 (2026-2027)
- **Key strength**: Active pedagogy, small groups, CEU network clinical infrastructure, Barcelona metropolitan location in biotech cluster
- **Key risk**: Inaugural program with no track record; WFME accreditation status unconfirmed; admission model details not published on accessible pages

## Key Facts

| Field | Value |
|---|---|
| Full name | Universitat CEU Abat Oliba |
| Short name | CEU-AO |
| Campus | Esplugues de Llobregat (Barcelona area) |
| Faculty | Facultad de Ciencias de la Salud y de la Vida |
| Degree | Grado en Medicina |
| Duration | 6 years |
| ECTS | 360 |
| Seats | 50 |
| First cohort | September 2026 |
| Teaching language | Spanish |
| Regional language | Catalan (possible) |
| Accreditation | AQU Catalunya (favorable report received) |
| WFME | PENDING_CONFIRMATION |
| Year 1 tuition | €17,715 (2026-2027) — ANNUAL_UPDATE_REQUIRED |
| Reservation fee | €2,500 (deducted from tuition) |
| Exam required | Yes — presencial, two sessions (February, April) |
| Interview | No |
| Competitiveness | Medium (inaugural cohort) |

## Program Options

UAO CEU offers a single Medicine program: a standard Spanish-taught track at the Esplugues de Llobregat campus. There is no bilingual track, no second campus, and no evening or part-time option. The entire cohort of 50 students follows the same curriculum and admission pathway.

Catalan is the co-official language of Cataluña and may be used in some administrative or teaching contexts, but the official degree program is conducted in Spanish.

## Program Structure

The degree follows a 360 ECTS, 6-year structure organized into 12 semesters of 30 ECTS each. The curriculum uses an integrated modular approach rather than the traditional discipline-by-discipline structure. In Years 1 and 2, modules group related basic sciences around anatomical systems (e.g., "De la Molécula al Órgano I–III", "Aparato Locomotor", "Sistemas Cardiovascular, Respiratorio y Renal"). From Year 3, students transition to diagnostic and clinical specialties, and from Year 4, structured clinical rotations are integrated alongside theoretical content.

**Year 1** (60 ECTS): Foundational sciences (molecular to organ approach), Aparato Locomotor, Digestivo y Nutrición, Bioestadística, Introducción a la Investigación y Epidemiología, Introducción a la Medicina y al Sistema Sanitario, Persona y Mundo Moderno.

**Year 2** (60 ECTS): Neurociencias, Sangre e Inmunología Médica, Sistema Endocrino y Reproductor, Cardiovascular/Respiratorio/Renal, Farmacología General, Comunicación y Entrevista Clínica, Seguridad del Paciente, Profesionalismo Médico y Valores Profesionales, Claves de la Historia Contemporánea, Optativa I.

**Year 3** (60 ECTS): Anatomía Patológica General, Microbiología General, Radiología y Diagnóstico por la Imagen, Genética Médica, Nuevas Tecnologías para el Diagnóstico y Tratamiento en Medicina, Fundamentos de Cirugía y Anestesiología, Semiología y Propedéutica Clínica, Bases de Medicina de Atención Primaria, Ética Médica, Optativas II–III.

**Year 4** (60 ECTS): Clinical specialties (Cardiocirculatorio, Respiratorio, Sangre, Sistema Nervioso, Digestivo, Endocrino, Psiquiatría, Geriatría/Paliativos), Doctrina Social de la Iglesia, Prácticas Clínicas I (7 ECTS) and II (5 ECTS).

**Year 5** (60 ECTS): Clinical specialties (Nefro-urinario, Enfermedades Infecciosas, Oftalmología, ORL, Dermatología, Sistema Locomotor, Oncología Médica, Medicina Legal/Forense, Medicina Preventiva y Salud Pública), Farmacología Clínica, Prácticas Clínicas III (4 ECTS) and IV (4 ECTS).

**Year 6** (60 ECTS): Obstetricia y Ginecología, Pediatría, Economía de la Salud y Gestión Sanitaria, Investigación en Salud, Trabajo Fin de Grado (6 ECTS), Prácticas Clínicas en Obstetricia y Ginecología (5 ECTS), Prácticas Clínicas en Atención Primaria (12 ECTS), Prácticas Clínicas en Pediatría (5 ECTS), Prácticas Clínicas Hospitalarias (12 ECTS).

Total structured clinical training ECTS in Years 4–6: approximately 55 ECTS (excluding TFG), with the bulk concentrated in Year 6.

Three elective subjects (Optativas I, II, III at 3 ECTS each) are distributed across Years 2–3.

## Teaching Methodology

The program positions active learning as its central methodological approach. Documented methods include the flipped classroom (aula invertida), problem-based learning (ABP), and simulation-based training from the early years. The small cohort design — 25 students per seminar group, 6 to 12 per practical session — is intended to replicate the ratios characteristic of clinical residency environments rather than the large lecture halls typical of public Medicine faculties.

The faculty emphasizes a dual scientific-humanist formation. Catholic values are embedded through subjects such as Persona y Mundo Moderno (Year 1), Claves de la Historia Contemporánea (Year 2), Profesionalismo Médico y Valores Profesionales (Year 2), and Doctrina Social de la Iglesia (Year 4). This positioning is consistent with the broader CEU network's institutional identity.

Technology is embedded structurally: "Nuevas Tecnologías para el Diagnóstico y Tratamiento en Medicina" (Year 3, 3 ECTS) is dedicated to digital medicine tools, and research methodology is introduced in Year 1 (Bioestadística Básica y Epidemiología) and returned to in Year 6 (Investigación en Salud). Communication skills are developed explicitly through "Comunicación y Entrevista Clínica" in Year 2.

## Clinical Training

Clinical exposure is described as beginning from Year 1, with progressive integration of hospital and primary care environments through the six-year program. From Year 4, formal clinical rotations (Prácticas Clínicas I–IV) are structured into the academic calendar. Year 6 is primarily clinical, with 34 ECTS in supervised placements across Obstetricia y Ginecología, Atención Primaria, Pediatría, and general Hospital rotations.

Confirmed clinical partners include:

- Clínica Diagonal (FIATC) — Barcelona
- Hospital Universitari Clínica Teknon — Barcelona
- Hospital SANITAS CIMA — Barcelona
- BSA Badalona Serveis Assistencials (hospital, primary care centers, and sociosanitary centers) — Badalona
- ACEBA (Associació Catalana d'Entitats de Base Associativa) — primary care centers, Barcelona metropolitan area

A collaboration agreement with Hospital Sant Joan de Déu (translational research) was announced in 2026, though its specific clinical teaching role for Medicine students is PENDING_CONFIRMATION.

The Esplugues de Llobregat campus benefits from its location within the Barcelona metropolitan biotech and health sciences corridor, which includes multiple research hospitals within commuting distance. Hospital-specific allocation of rotations by year and specialty is ANNUAL_UPDATE_REQUIRED as the program develops.

## International Recognition and Opportunities

The degree received a favorable evaluation from AQU Catalunya (Agència per a la Qualitat del Sistema Universitari de Catalunya) prior to launch in 2026. This regional quality agency report was a prerequisite for program authorization. Official recognition by the Spanish Ministry (ANECA verification / RUCT registration) is implied by the AQU approval process, but the specific RUCT code for the UAO CEU Medicine degree was not confirmed at the time of this file's last update.

WFME (World Federation for Medical Education) accreditation status is PENDING_CONFIRMATION. This is a material consideration for candidates intending to practice in countries that require WFME-recognized degrees for medical licensing (including the United States, Canada, and certain Gulf states).

International exchange and Erasmus opportunities for Medicine specifically are PENDING_CONFIRMATION. UAO CEU has general international mobility infrastructure (Relaciones Internacionales service), but applicability to the Medicine program — particularly given the strict sequential clinical rotation schedule — has not been confirmed.

## Admission Model

UAO CEU runs a proprietary admission process that is complementary to the PAU (EvAU) or any other official Spanish access credential. For all degree programs except Medicine, this process is conducted 100% online and includes a general culture and aptitude questionnaire. Medicine is explicitly excluded from the online process and requires an in-person exam.

The admission exam for Medicine (Prueba de Admisión Presencial) is offered on two dates per cycle — one in February and one in April — at the Esplugues de Llobregat campus. Candidates are notified of the result within one week of the exam date.

The complete scoring model — including the weighting between academic record and exam score, the exam content, and any minimum thresholds — is published in the official admission document (Rev_admision-medicina-CEU-ABAT-OLIBA-modificado.pdf), which was not extractable through publicly accessible web pages at the time of this file's last update. All evaluation weights and exam specifications are therefore marked as PENDING_CONFIRMATION.

The application documentation requires bachillerato grades from both Year 1 (complete) and Year 2 (partial, at time of application), indicating that academic record is a component of evaluation. CFGS (vocational training graduates) and international equivalent credentials are accepted as entry paths.

There is no interview component and no separate English test for the standard Spanish-taught track.

## Admission Process

1. **Application**: Submit via the Portal del Futuro Alumno (admision.uaoceu.es). Provide personal and academic data, including bachillerato Year 1 grades and partial Year 2 grades (or CFGS equivalent).
2. **Documentation upload**: DNI/NIE/passport and academic certificate(s).
3. **Exam**: Attend the presencial exam on either February 28 or April 18 at the Esplugues campus (ANNUAL_UPDATE_REQUIRED). The exam is reported as free of charge.
4. **Admission decision**: Notified within one week of the exam.
5. **Reservation**: If admission is favorable, secure the place via a €2,500 deposit through the portal. This amount is deducted from Year 1 tuition.
6. **Withdrawal window**: The deposit is refundable if the candidate formally withdraws before June 21 (ANNUAL_UPDATE_REQUIRED). This allows candidates to reserve a place before completing the EvAU (selectividad) in June.
7. **EvAU confirmation**: After completing official access exams (June), provide proof to the university.
8. **Enrollment**: Complete formal enrollment once all access requirements are met.

For candidates from outside Spain: international entry pathway documentation is handled through the admisión internacional process. Spanish language proficiency level requirements are PENDING_CONFIRMATION.

## Admission Timeline

All dates below are from the 2026-2027 inaugural intake cycle and are ANNUAL_UPDATE_REQUIRED for subsequent years.

| Event | Date |
|---|---|
| Applications open | ANNUAL_UPDATE_REQUIRED |
| Exam Session 1 | 28 February 2026 |
| Results Session 1 | ~7 March 2026 (within 1 week) |
| Exam Session 2 | 18 April 2026 |
| Results Session 2 | ~25 April 2026 (within 1 week) |
| Withdrawal deadline (refundable deposit) | 21 June 2026 |
| EvAU (selectividad) ordinary call | June 2026 |
| Enrollment deadline | ANNUAL_UPDATE_REQUIRED |
| Program start | September 2026 |

**Strategic note**: The withdrawal window closing on June 21 allows candidates to reserve a place in February or April and retain optionality through the EvAU without financial risk. This is a material advantage for candidates holding applications at multiple universities simultaneously.

## Admission Score Distribution

No historical score data exists for this program. 2026-2027 is the inaugural intake cycle.

The evaluation model weighting is PENDING_CONFIRMATION. Until the official admission PDF is verified, no score distribution or minimum competitive threshold can be stated.

What can be observed structurally:

The program is competitive by design — 50 seats, an in-person proprietary exam, and a rolling admission framework with two sessions. In the first cohort, the competitive bar is expected to be lower than for established Spanish private Medicine programs, simply because the program has no track record to attract the highest-scoring applicants exclusively. This dynamic is consistent with other inaugural cohorts observed across Spanish private Medicine schools.

The rolling structure and the refundable reservation window create a first-mover incentive: candidates who apply in the February session and secure a place are protected by the June withdrawal window at no financial cost. Applying in April increases risk if top choices also have April deadlines.

For subsequent intakes (2027-2028 onward), score distributions should be established once the first cohort admission outcomes are published.

## Costs and Payment Structure

| Item | Amount | Notes |
|---|---|---|
| Year 1 total | €17,715 | 2026-2027 — ANNUAL_UPDATE_REQUIRED |
| Reservation fee | €2,500 | Deducted from Year 1 total; refundable before June 21 |
| Estimated price per ECTS credit | ~€295 | Derived from Year 1: €17,715 / 60 ECTS — ANNUAL_UPDATE_REQUIRED |
| Estimated 6-year total | ~€106,290 | Assuming constant annual tuition — ANNUAL_UPDATE_REQUIRED |

**Payment options** (Year 1, after reservation):

| Option | Discount | Structure |
|---|---|---|
| Single payment (pago único) | 3% off tuition | Full annual amount paid at enrollment |
| Installments (pago fraccionado) | No discount stated | 5 payments across the academic year |
| Monthly financing (10 months) | 3% off tuition | Via CaixaBank at 0% interest |

Banking agreements with preferential conditions are available through Banc Sabadell, CaixaBank, and Banco Santander.

The university explicitly states that tuition obligations remain in force even if the student discontinues studies partway through the year for reasons outside the university's control. Candidates should review the full terms before signing the enrollment contract.

## Scholarships and Financial Aid

UAO CEU offers a general financial aid program for undergraduate students (Ayudas a los estudios de grado), accessible through the university website. Specific scholarships restricted to the Medicine program had not been published on accessible pages at the time of this file's last update. Given that 2026-2027 is the inaugural cohort, program-specific scholarships may be introduced in subsequent cycles.

The university also provides: CEU Apoyo a estudiantes con discapacidad; CEU Apoyo a Deportistas; housing assistance (Ayudas al alojamiento). Whether these general aid categories apply to Medicine students on the same terms as other programs is PENDING_CONFIRMATION.

Spanish state (MEC) scholarships (becas MECES) may be applicable depending on the student's socioeconomic profile and the degree's official recognition status. Candidates should verify eligibility directly with the university.

## Accommodation and Cost of Living

Esplugues de Llobregat is a municipality of approximately 47,000 inhabitants immediately west of Barcelona, connected to the city by metro (L9 Sud), bus, and cycling infrastructure. Students effectively live in the Barcelona metropolitan area for practical purposes.

Barcelona is one of the more expensive cities in Spain for student accommodation, with typical shared-flat rental costs ranging from €500–€900/month per room depending on neighborhood and proximity to campus. UAO CEU has a dedicated housing assistance service (Ayudas al alojamiento) and publishes a cost of living calculator on the Vivir en Barcelona section of its website.

The Esplugues / Gran Via corridor hosts several pharmaceutical and biotech companies (Novartis, Almirall, Bayer, Galenicum, among others), which positions students for extracurricular research and internship opportunities beyond the formal clinical rotation schedule.

## International Exchange and Mobility Programs

UAO CEU maintains general international mobility infrastructure through its Relaciones Internacionales service, including Erasmus+ agreements. However, whether these mobility agreements cover Medicine students specifically — particularly given the sequential clinical rotation requirements in Years 4–6 — is PENDING_CONFIRMATION.

The CEU network (UAO CEU, CEU San Pablo, CEU Cardenal Herrera, CEU Fernando III) provides a potential inter-campus mobility framework, though formal transfer or exchange protocols between CEU Medicine programs have not been confirmed.

International exchange opportunities tied specifically to the Esplugues campus or the Facultad de Ciencias de la Salud y de la Vida are ANNUAL_UPDATE_REQUIRED as the faculty becomes established.

## MIR Preparation and Professional Outcomes

No MIR data is available for this program. The inaugural cohort began in September 2026; the first MIR-eligible graduates will not sit the examination until 2032 at the earliest.

The program states preparation for MIR as an explicit objective ("preparar para ejercer como médico y acceder con éxito al MIR"). Whether this translates into structured MIR preparation programs within the curriculum (comparable to what AMIR or similar providers offer in partnership with other CEU schools) is PENDING_CONFIRMATION.

## Strategic Fit

### Good Fit For

- Students from Cataluña or intending to study in Barcelona, for whom CEU-AO eliminates the need to relocate to Madrid or Valencia.
- Candidates who benefit from small-group pedagogy and early clinical exposure, and for whom the 50-seat cohort is a genuine appeal rather than a consolation.
- Students with a Catholic educational background aligned with the CEU institutional identity and humanities-embedded curriculum.
- Applicants seeking a first-year advantage: the inaugural intake will likely be the least competitive cohort in the program's history, as institutional reputation is built over time.
- Students whose EvAU preparation is in progress who need to secure a Medicine place before June: the refundable reservation window is particularly valuable in this scenario.

### Less Suitable For

- Candidates prioritizing a proven MIR track record or published outcome data. No such data will exist for this program until at least 2032.
- Students requiring WFME recognition for international medical practice (US, Canada, Gulf states): WFME status is unconfirmed and may take years to obtain.
- Candidates who require full transparency over the admission formula before deciding: the evaluation model is not publicly detailed on accessible pages, which limits strategic preparation.
- Students who require a bilingual (Spanish-English) Medicine track: UAO CEU offers only Spanish-taught Medicine.
- Students already admitted to a more established private Medicine program in Spain: switching to an inaugural cohort for proximity reasons carries reputation risk that may not be offset by geographical convenience alone.

## Risks and Considerations

**Inaugural cohort risk**: Every metric that students and advisors typically use to assess a Medicine program — MIR pass rates, score distributions, alumni outcomes, faculty reputation — is absent for UAO CEU Medicine. Accepting a place here means accepting uncertainty about whether the program's execution will match its published design.

**Evaluation model opacity**: The admission scoring formula is contained in a PDF that was not accessible through standard web channels during research. Candidates should download and read the admission PDF directly before applying, as the weighting between academic record and exam may significantly affect preparation strategy.

**WFME accreditation**: The program's recognition by WFME had not been confirmed at the time of this file's last update. For students considering international medical practice — especially outside the EU — this is a decisive factor. WFME accreditation processes typically take years after a program is established.

**Tuition trajectory**: With Year 1 at €17,715, total program costs are substantial. Annual tuition increases are common across Spanish private Medicine programs. The 6-year cost projection assumes constant tuition, which is unlikely and should be treated as a floor, not an estimate.

**Barcelona cost of living**: Accommodation costs in the Barcelona metropolitan area are high relative to other Spanish cities hosting private Medicine programs. The total cost of attendance over six years (tuition + living) will be materially higher than programs located in smaller cities.

**Rolling admissions with limited seats**: 50 seats, rolling process, two sessions. If the program fills substantially in the February session, April applicants face a smaller residual cohort. Earlier application reduces risk.

## Important Notes

- Exam sessions are presencial (in-person) at Esplugues de Llobregat campus. Online exam option does NOT apply to Medicine. — ANNUAL_UPDATE_REQUIRED
- Reservation fee: €2,500, deducted from Year 1 tuition. Refundable if withdrawal before June 21. — ANNUAL_UPDATE_REQUIRED
- Both Year 1 and partial Year 2 bachillerato grades are required in the application. Early applicants should upload Year 2 interim grades as available.
- CFGS (vocational training) and international equivalent credentials are accepted entry paths.
- The university communicates admission decisions within one week of the exam date.
- Payment discounts of 3% apply for lump-sum and 10-month CaixaBank financing options.
- Catalan may be used in some administrative or teaching contexts as the co-official language of Cataluña.

## Key Insight

UAO CEU Medicine's primary strategic proposition is geographic: it is the only CEU Medicine program in Cataluña, and the only private Medicine degree physically located in the Barcelona metropolitan area. For students with strong ties to Cataluña — or for whom living in Barcelona is important — this reduces the need to apply exclusively to programs in Madrid or Valencia.

The inaugural cohort dynamic is the most significant variable. In first-year programs without track records, the competitive bar is structurally lower, the faculty-to-student ratio tends to be highest, and students receive more direct faculty attention. These early-cohort advantages erode as the program scales and reputation catches up. For a well-prepared candidate who cannot reach the score thresholds of established Madrid or Valencia programs, CEU-AO's 2026-2027 cohort may represent a structurally accessible window that will not recur.

## Final Takeaway

Universitat CEU Abat Oliba's Medicine degree offers a genuinely differentiated profile: small cohort, integrated curriculum, active pedagogy, Barcelona location, and CEU network clinical infrastructure. The program's key limitation is that it has no track record. MIR outcomes, real-world competitive scores, and accreditation status (WFME) are all pending validation over the coming years.

For candidates who are strategically positioned — strong bachillerato record, prepared for a presencial internal exam, aligned with the program's Catholic-humanist values, and comfortable with the risks of an inaugural cohort — this is a legitimate option. For candidates with access to established programs with published outcomes, accepting UAO CEU as their primary choice requires accepting a material information asymmetry that established programs do not carry.

The refundable reservation structure and the early February exam session make it feasible to include UAO CEU as a strategic hedge in a broader portfolio of applications, at manageable financial risk before the EvAU results in June.

## Frequently Asked Questions

**Is the 2026-2027 intake still open?**
The university operates a rolling admission process with two exam sessions (February and April). Availability depends on whether all 50 seats have been filled. Candidates should check the Portal de Admisión directly for current availability. — ANNUAL_UPDATE_REQUIRED

**Is the admission exam free?**
The general UAO CEU admission test is described as free. Whether this applies equally to the Medicine presencial exam is PENDING_CONFIRMATION. Contact the Servicio de Información (+34 93 253 72 00) to confirm.

**What subjects does the admission exam cover?**
The exam content is detailed in the official admission document (Rev_admision-medicina-CEU-ABAT-OLIBA-modificado.pdf), available via the university website's admission section. Exam subjects and weightings were not confirmed through accessible web pages during research.

**Can I reserve a place before my EvAU (selectividad) results?**
Yes. The reservation window remains open through June 21 (ANNUAL_UPDATE_REQUIRED). The €2,500 deposit is fully refundable if you withdraw before that date, so you can secure a place before the June EvAU without financial risk.

**Does UAO CEU Medicine have WFME accreditation?**
WFME accreditation status is PENDING_CONFIRMATION. The degree has AQU Catalunya quality accreditation, which is the prerequisite for program authorization in Cataluña. WFME is a separate international process and typically takes years after a program is established.

**Is the program taught in Spanish or Catalan?**
The official degree program is in Spanish. Catalan is the co-official language of Cataluña and may be used in some administrative or informal teaching contexts, but classes and formal assessments are in Spanish.

**Can I study Medicine at UAO CEU if I have a non-Spanish bachillerato?**
Yes — UAO CEU has an international admissions process. Specific documentation requirements and Spanish language level requirements for non-native speakers are PENDING_CONFIRMATION for Medicine specifically. Contact admisión internacional for guidance.

**What is the price per ECTS credit?**
Based on the published Year 1 total of €17,715 for 60 ECTS, the implied price per credit is approximately €295. This figure has not been independently confirmed by the university and is ANNUAL_UPDATE_REQUIRED.

**Does UAO CEU have an interview in the Medicine admission process?**
No interview is described in the published Medicine admission process. The process consists of application, presencial exam, and admission decision within one week.

**How many students are in each class?**
The total cohort is 50 students. Teaching groups are 25 for seminars and 6 to 12 for practical and laboratory sessions.
```