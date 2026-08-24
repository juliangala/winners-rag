---
id: ucv-medicine-valencia

type: university
subtype: private

name: Universidad Católica de Valencia San Vicente Mártir
short_name: UCV

degree: Medicine

last_update: 2026-05-27

valid_for_intake: 2026-2027

location:
  city: Valencia
  region: Comunidad Valenciana
  country: Spain

strategic_tags:
  - core_option
  - medium_competitiveness
  - exam_heavy
  - interview_heavy
  - academic_exam_required
  - onsite_exam_required
  - high_cost

admission:
  intake_month: September

  applications_open_date: "2026-03-02" # ANNUAL_UPDATE_REQUIRED

  rolling_admissions:
    enabled: false
    estimated_end_date: NULL

  admission_rounds:
    enabled: true
    count: 1

    rounds:
      - round: 1
        application_deadline: "2026-05-15" # ANNUAL_UPDATE_REQUIRED
        exam_date: "2026-06-13" # ANNUAL_UPDATE_REQUIRED
        results_date: PENDING_CONFIRMATION
        deposit_deadline: PENDING_CONFIRMATION

  exam_required: true
  interview_required: true

academic_record:
  minimum_requirement:
    enabled: true
    grade_source: mixed
    minimum_grade: 7.0
    # 7.0 = min 1º Bachillerato average for current 2ºBach students
    # PAU applicants: min combined score 12.2 (first convocatoria only)

  competitive_filter:
    enabled: true
    grade_source: mixed
    approx_candidates_selected: 500
    # Top 500 by Bachillerato grade are invited to the exam

curriculum:
  international_curriculums_accepted: PENDING_CONFIRMATION

competitiveness:
  level: medium_high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: 180
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
  - id: ucv-medicine-valencia-standard

    campus: San Carlos Borromeo, Valencia

    modality: standard

    strategic_tags:
      - core_option
      - medium_competitiveness
      - exam_heavy
      - interview_heavy
      - academic_exam_required
      - onsite_exam_required
      - high_cost

    teaching_languages:
      - Spanish

    regional_language_possible: PENDING_CONFIRMATION
    regional_language: Valencian

    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL

    seats: 180

    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 180
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
      overall_model_type: pathway_based

      admission_pathways:

        - eligible_profiles:
            - current_second_year_bachillerato_health_sciences_min_7_0_in_first_year
            - pau_first_convocatoria_2023_2024_or_2025_health_sciences_min_12_2
            - prior_year_bachillerato_retaking_pau_specific_subjects_2026

          components:
            - component: academic_record
              enabled: true
              role: both
              weight: 0.25
              grade_source: mixed
              minimum_required_grade: 7.0
              notes: "Minimum 7.0 average in 1º Bachillerato for current 2ºBach students. PAU applicants: min 12.2 combined score (first convocatoria only). Students retaking PAU specific subjects in 2026: enter process at phase 2, placement conditional on achieving ≥12.2. Bachillerato average used in final scoring formula. Grade also used as filter to select top 500 for exam."

            - component: academic_exam
              enabled: true
              role: both
              weight: 0.40
              exam_variant: onsite_internal_exam
              exam_format: multiple_choice
              delivery_mode: onsite
              online_conditions: NULL

              subjects:
                - Biology (60%)
                - Chemistry (30%)
                - Physics (10%)

              syllabus_alignment:
                biology:
                  scope:
                    - full_baccalaureate
                  notes: "60% of exam. Full bachillerato biology curriculum."

                chemistry:
                  scope:
                    - full_baccalaureate
                  notes: "30% of exam. Full bachillerato chemistry curriculum."

                physics:
                  scope:
                    - full_baccalaureate
                  notes: "10% of exam. Adapted for health sciences students, including those who did not study physics in bachillerato."

                mathematics:
                  scope:
                    - not_applicable
                  notes: "Mathematics not included in exam."

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
                notes: "Published syllabus and downloadable sample questions available on UCV website. Fixed content weights known in advance. Physics adapted for non-physics students. Standard difficulty relative to bachillerato content."

              best_attempt_counts: NULL
              notes: "100 MCQ questions. All admission phases are eliminatory — failure at any phase results in elimination."

            - component: psychometric_test
              enabled: true
              role: weighted
              weight: 0.10
              test_format: mixed
              delivery_mode: onsite
              online_conditions: NULL
              notes: "Cuestionario de aptitudes psicosociales. Administered on same day as academic exam (June 13). Scored separately as its own component."

            - component: interview
              enabled: true
              role: both
              weight: 0.25
              interview_format: oral
              delivery_mode: onsite
              notes: "Personal interview at Facultad de Medicina, C/ Quevedo 2, Valencia. Eliminatory and weighted. Conducted June 15–18. Assigned slot is automatic and cannot be changed."

        - eligible_profiles:
            - health_sciences_university_graduates_min_degree_average_8_0
            - completing_final_year_health_sciences_degree_expected_grade_8_0

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 0.65
              grade_source: PENDING_CONFIRMATION
              minimum_required_grade: 8.0
              notes: "University degree average ≥8.0 required. 3% of seats reserved for this pathway. grade_source is university degree average — not a standard bachillerato source. If degree not yet completed, placement is conditional on achieving ≥8.0 at completion."

            - component: psychometric_test
              enabled: true
              role: weighted
              weight: 0.10
              test_format: mixed
              delivery_mode: onsite
              online_conditions: NULL
              notes: "Same aptitude questionnaire as standard track. Conducted late June."

            - component: interview
              enabled: true
              role: weighted
              weight: 0.25
              interview_format: oral
              delivery_mode: onsite
              notes: "Personal interview, late June. No academic subject exam for this pathway."
---

# Universidad Católica de Valencia San Vicente Mártir (UCV)

## Overview

The Universidad Católica de Valencia San Vicente Mártir (UCV) offers one of Spain's most established private Medicine programs, operating from its San Carlos Borromeo campus in central Valencia. Founded on Catholic humanistic principles, UCV integrates scientific and clinical training with an explicit emphasis on professional ethics and holistic patient care.

The Grado en Medicina offers 180 seats through a multi-phase eliminatory admission model that combines a Bachillerato grade filter, an onsite internal exam, a psychometric questionnaire, and a personal interview — four sequential steps where failure at any stage ends the candidacy. At 14,440€ per year for 2026-27, UCV sits below several private Medicine competitors on price while operating a transparent admission structure with a published exam syllabus and downloadable sample questions.

UCV has one of the most extensively documented clinical networks among Spanish private Medicine programs: 1,010 declared rotation slots across 15 affiliated centers in the Comunidad Valenciana, with an officially confirmed 1:1 tutor-student ratio in external rotations. The Catholic institutional identity is present across academic framing, pastoral services, and program philosophy, but does not restrict access to students of other backgrounds.

## Quick Evaluation

- **Location:** Valencia, urban center, well connected nationally
- **Seats:** 180
- **Tuition:** 14,440€/year (2026-27) — mid-low range for Spanish private Medicine
- **Admission model:** Multi-phase eliminatory — grade filter (top 500) → onsite exam → interview
- **Exam:** 100 MCQ onsite (60% biology, 30% chemistry, 10% physics); published syllabus and sample questions available
- **Interview:** Personal oral interview (25% of final score); fully eliminatory
- **Scoring:** 25% academic record + 40% exam + 10% aptitude questionnaire + 25% interview
- **Clinical network:** 1,010 slots across 15 centers; 54 ECTS of external rotations; 1:1 tutor ratio
- **WFME accreditation:** PENDING_CONFIRMATION
- **Mobility programs:** EU-CONEXUS, Erasmus+, MUNDUS, SICUE — Medicine-specific availability PENDING_CONFIRMATION
- **MIR statistics:** PENDING_CONFIRMATION
- **Catholic university:** Integral humanistic formation; not religiously exclusive

## Key Facts

| Feature | Value |
|---|---|
| Full name | Universidad Católica de Valencia San Vicente Mártir |
| Short name | UCV |
| Faculty | Facultad de Medicina y Ciencias de la Salud |
| Campus | San Carlos Borromeo, Valencia (C/ Quevedo, 2) |
| ECTS | 360 |
| Duration | 6 years |
| Language | Spanish |
| Seats | 180 |
| Tuition 2026-27 | 14,440€/year — ANNUAL_UPDATE_REQUIRED |
| Application fee | 50€ (confirmation payment at phase 4) |
| PAU threshold for placement | ≥12.2 (first convocatoria only) |
| Min 1º Bach grade to register | 7.0 |
| Top-500 exam filter | Yes — only top 500 by Bach. grade invited to exam |
| Clinical ECTS (external) | 54 |
| Hospital Virtual | Yes — simulation center, optional diplomas |
| RUCT code | 2500542 |
| Erasmus code | E VALENCI11 |
| Academic year start 2026-27 | 7 September 2026 — ANNUAL_UPDATE_REQUIRED |

## Program Options

UCV offers a single Medicine program:

- **Program:** Grado en Medicina — standard track, Spanish-language, in-person
- **Campus:** San Carlos Borromeo, Valencia
- **Seats:** 180
- **Schedule:** Morning and afternoon

There is no bilingual track, no satellite campus for Medicine, and no online or hybrid modality. All instruction takes place at the San Carlos Borromeo campus or at affiliated clinical centers throughout the Comunidad Valenciana.

A separate pathway (3% of seats) exists for university graduates from health sciences degrees, with a distinct scoring formula and no academic subject exam requirement.

## Program Structure

**Years 1–2 — Basic Sciences.** Foundational biomedical sciences: anatomy, biochemistry, histology, physiology, immunology, embryology. Strong pre-clinical science base before clinical exposure begins.

**Year 3 — Introduction to Clinical Practice.** First external clinical rotations: Clínica Práctica Patología General (3 ECTS) and Clínica Práctica Cirugía Menor (3 ECTS). Continued theoretical and pathology subjects alongside the first real clinical environment contact.

**Year 4 — Applied Clinical Sciences.** Hospital rotations integrated within full applied modules: Medicina y Cirugía del Aparato Cardiocirculatorio, Medicina y Cirugía del Aparato Locomotor, and Obstetricia y Ginecología. A substantial theoretical and practical year.

**Year 5 — Clinical Specialties I and First ECOE.** Clínica Práctica Especialidades I (Psychiatry/Dermatology, 3 ECTS). First ECOE (objective structured clinical examination) with standardized patients. Typical year for Erasmus or EU-CONEXUS mobility.

**Year 6 — Intensive Clinical Rotations and Final ECOE.** Eight specialty rotation blocks (6 ECTS each): Obstetrics/Paediatrics/Allergy; Cardiovascular/Respiratory/ENT; Infectious Disease/Neurology/Nephrology; Locomotor/Rheumatology/Rehabilitation; Ophthalmology/Oncology/Palliative Care; plus Family Medicine (6 ECTS), Hospital Emergency (6 ECTS), and Geriatrics (3 ECTS). Total 6th-year clinical ECTS: 45. Final ECOE with 20 structured stations.

Total external clinical ECTS: 54. Additionally, optional simulation-based university diplomas (Preclinicum in year 2; Clinicum I/III/IV in years 3/5/6) are available at the Hospital Virtual. These are not part of the official degree plan, are separately priced, and appear on the European Diploma Supplement (SET).

## Teaching Methodology

UCV's pedagogical model combines conventional lecture-based teaching in the pre-clinical phase with competency-based clinical training and structured ECOE evaluation in the later years. The Catholic institutional identity shapes the framing of medical training as a vocation, with explicit integration of ethics, communication, and holistic patient care dimensions across the curriculum.

The 1:1 tutor-to-student ratio in all external clinical rotations is a structurally confirmed feature, not a marketing claim — it is stated in the official external rotations documentation. This level of individual supervision in clinical placements is notable within the Spanish private Medicine sector.

ECOE evaluation is used in year 5 (Psiquiatría/Dermatología) and year 6 (final 20-station exam). In year 6 clinical subjects, the ECOE accounts for 70% of the grade, with clinical attendance making up the remaining 30%. This model rewards competency demonstration over written knowledge recall in the clinical phase and provides students with structured preparation for standardized assessment formats.

The Hospital Virtual simulation center supports optional Preclinicum and Clinicum diplomas, providing simulated patient interaction experiences. These are supplementary to the formal degree and voluntary.

## Clinical Training

UCV maintains one of the most transparently documented clinical networks among Spanish private Medicine programs. External clinical placements cover 54 ECTS distributed across years 3, 4, 5, and 6. The confirmed clinical centers and their declared rotation capacities:

| Center | Rotation slots |
|---|---|
| Departamento de Salud Manises | 260 |
| Hospital Imed Valencia | 175 |
| Hospital Vithas Valencia | 116 |
| Hospital IVO (Instituto Valenciano de Oncología) | 90 |
| Departamento de Salud La Ribera | 84 |
| Hospital Casa de Salud | 67 |
| Departamento de Salud La Fe | 64 |
| Hospital Quirónsalud Valencia | 48 |
| Departamento de Salud Xàtiva-Ontinyent | 39 |
| Departamento de Salud Gandía | 30 |
| Departamento de Salud Hospital General Valencia | 17 |
| Departamento de Salud Requena | 10 |
| Departamento de Salud Peset | 8 |
| Hospital HLA Jerez | 1 |
| Hospital Viamed Sevilla | 1 |
| **Total** | **1,010** |

The network combines public health departments (Departamentos de Salud), major private hospitals (Imed, Vithas, Quirónsalud, Casa de Salud), and the specialist Instituto Valenciano de Oncología. Geographic coverage is predominantly within the Comunidad Valenciana, with isolated slots in Andalusia.

Student-to-center assignment is based on academic record at the time of preference selection, with students choosing ranked preferences through UCV's intranet. The assignment is automatic and follows grade order. Students completing year 2 through year 5 can also choose the rotation period in addition to the center.

For years 5 and 6 clinical subjects, final grades are composed of clinical attendance (30%) and ECOE performance (70%). A final 6th-year ECOE with 20 stations evaluates competencies across diagnostics, treatment, communication, and clinical procedures.

ANNUAL_UPDATE_REQUIRED: The number of active rotation slots per center and the list of affiliated centers may change each academic year.

## International Recognition and Opportunities

**WFME Accreditation:** PENDING_CONFIRMATION — no confirmed WFME institutional recognition found in publicly available sources. This is a relevant data point for students intending to practice in jurisdictions that require WFME-accredited degrees (including the United States, Canada, and some Middle Eastern countries). Students targeting these destinations should verify directly with UCV or the relevant foreign regulatory authority.

**Spanish national recognition:** The degree is official and nationally recognized (RUCT code 2500542). Graduates are eligible for the MIR examination and specialist training in Spain and have EU-wide degree recognition under the ECTS framework.

**EU-CONEXUS:** UCV is a founding member of EU-CONEXUS, an Erasmus+ European University Alliance. Partner institutions include La Rochelle University (France), University of Cyprus, National Technical University of Athens, Klaipėda University (Lithuania), University of Algarve (Portugal), Kiel University (Germany), and University of Zadar (Croatia). The alliance enables joint academic activities, mobility windows, and international curricular recognition across member institutions.

**Erasmus+ for Medicine:** Erasmus/Estudios and Erasmus/Prácticas are formally listed in the Medicine degree's mobility section on UCV's website. Whether active bilateral agreements specifically covering Medicine students exist, and to which destinations, is PENDING_CONFIRMATION. Students planning mobility should contact ori@ucv.es before relying on this option.

**Quality certifications:** ISO 9001, ISO 14001, and ISO 45001 at the institutional level.

## Admission Model

UCV uses a **multi-phase, eliminatory, pathway-based model** with two tracks:

**Standard track (≥97% of seats):**
All four phases are sequentially eliminatory. Failure at any stage results in elimination from the process.

1. **Grade filter:** Top 500 applicants by Bachillerato grade are invited to take the exam.
2. **Academic exam:** 100 MCQ onsite (biology 60%, chemistry 30%, physics 10%) + aptitude questionnaire — eliminatory and weighted.
3. **Interview:** Personal oral interview at the Faculty of Medicine, Valencia — eliminatory and weighted.
4. **Final scoring:** 25% academic record + 40% exam + 10% aptitude questionnaire + 25% interview.

**University graduates track (3% of seats reserved):**
For health sciences graduates with ≥8.0 degree average. No academic subject exam. Scoring: 65% academic record + 10% aptitude questionnaire + 25% interview.

**Key eligibility rules:**
- Current 2ºBach students (health sciences branch): minimum 7.0 in 1º Bachillerato to register.
- PAU first convocatoria 2023/2024/2025 applicants: minimum combined score 12.2.
- Students retaking specific PAU subjects in 2026 to improve their grade: enter at phase 2 (bypassing grade filter); placement conditional on achieving ≥12.2 in 2026 PAU.
- Students with >30 ECTS already recognized from Medicine at another university are explicitly excluded from this process and must apply via a separate transfer route.

## Admission Process

1. **Register online** (2 March – 15 May): Submit DNI, personal data, and 1º Bachillerato average via the UCV platform. Receive username and password for the process. — ANNUAL_UPDATE_REQUIRED

2. **Submit 2º Bachillerato grades** (19 May – 3 June): Input final 2ºBach grades via the portal. Mandatory for exam eligibility assessment. — ANNUAL_UPDATE_REQUIRED

3. **Check exam eligibility** (5 June): UCV publishes the list of the top 500 candidates, accessible via individual login on the admissions platform. — ANNUAL_UPDATE_REQUIRED

4. **Pay confirmation fee** (by 8 June): 50€ payment via secure payment platform. Non-payment = automatic elimination. University graduates track candidates are exempt. — ANNUAL_UPDATE_REQUIRED

5. **On-site accreditation** (12 June, 9–14h and 16–22h): Candidates present in person at Facultad de Medicina (C/ Quevedo, 2, Valencia) with DNI and official grade certificate. No accreditation = ineligible to sit the exam. — ANNUAL_UPDATE_REQUIRED

6. **Exam day** (Saturday 13 June, 9:00h, onsite): 100 MCQ academic test + aptitude questionnaire. — ANNUAL_UPDATE_REQUIRED

7. **Interview notification** (13 June, afternoon): Candidates who progress receive their interview date/time via email and website login.

8. **Personal interview** (15–18 June, onsite): Assigned time slot is automatic and non-transferable. — ANNUAL_UPDATE_REQUIRED

9. **Results** (after 18 June): Published via individual login on the platform. Admitted students receive instructions for reservation and enrollment.

10. **Waiting list:** Candidates who sat the interview and scored ≥5 are placed on a waiting list for remaining seats.

International students should contact admissions@ucv.es or nuevosalumnos@ucv.es (Tel: +34 96 192 75 90) to clarify credential recognition requirements before registering.

## Admission Timeline

| Stage | Date | Notes |
|---|---|---|
| Registration opens | 2 March 2026 | ANNUAL_UPDATE_REQUIRED |
| Registration closes | 15 May 2026 | ANNUAL_UPDATE_REQUIRED |
| Grade submission window | 19 May – 3 June 2026 | ANNUAL_UPDATE_REQUIRED |
| Exam eligibility notification | 5 June 2026 | Top 500 by Bachillerato grade — ANNUAL_UPDATE_REQUIRED |
| Confirmation fee payment deadline | 8 June 2026 | 50€ — ANNUAL_UPDATE_REQUIRED |
| On-site accreditation | 12 June 2026 | C/ Quevedo 2, Valencia — ANNUAL_UPDATE_REQUIRED |
| Academic exam + aptitude test | 13 June 2026, 9:00h | Onsite — ANNUAL_UPDATE_REQUIRED |
| Interview notifications | 13 June 2026, afternoon | ANNUAL_UPDATE_REQUIRED |
| Personal interviews | 15–18 June 2026 | Onsite, slots assigned — ANNUAL_UPDATE_REQUIRED |
| Results | After 18 June 2026 | PENDING_CONFIRMATION — ANNUAL_UPDATE_REQUIRED |
| Academic year start | 7 September 2026 | ANNUAL_UPDATE_REQUIRED |

## Admission Score Distribution

UCV's 25/40/10/25 scoring formula prioritizes active evaluation (exam + interview = 65%) over academic record (25%). The strategic implications:

**The exam is the primary differentiator (40%).** A strong Bachillerato average is necessary to clear the top-500 filter, but once past that gate, exam performance is the dominant factor in final scoring. Students who clear the grade filter but perform poorly on the exam will not be competitive. The published syllabus and downloadable sample questions on UCV's website make exam preparation more tractable than for programs with unpublished or university-specific curricula.

**The interview is a decisive elimination gate (25%).** Combined with the exam, active evaluation components account for 65% of the final score. But unlike the exam — where a below-average score still contributes weighted points — the interview is also eliminatory. A failing interview score ends the candidacy entirely. Students who prepare for the exam but neglect interview readiness are at serious risk of elimination at the final stage.

**The grade filter (top 500) determines who competes.** The Bachillerato grade is used not as a direct scoring component but as a binary access gate. The precise cutoff grade to enter the top 500 changes annually based on applicant volume and is not published in advance. Students with Bachillerato averages in the 7.5–8.5 range operate with uncertainty about their eligibility for the exam and should not assume access without monitoring competition levels for the relevant intake year. ANNUAL_UPDATE_REQUIRED.

**PAU score threshold (12.2) is a qualifier, not a differentiator.** For applicants who already hold PAU results, the 12.2 threshold is a binary condition for placement — it neither improves nor reduces one's scoring position among other PAU applicants. The competitive variable for those applicants is the top-500 Bachillerato grade filter, not the PAU score itself.

**University graduates pathway (65% academic record):** Strongly favors candidates with near-perfect degree averages (9.0+). With 3% of 180 seats, approximately 5–6 seats are available via this route, making it highly selective in practice.

## Costs and Payment Structure

| Concept | Amount | Notes |
|---|---|---|
| Annual tuition (2026-27) | 14,440€ | ANNUAL_UPDATE_REQUIRED |
| Application confirmation fee | 50€ | Phase 4 payment; not refundable upon voluntary withdrawal |
| Total degree estimate | ~86,640€ | 6 years × 14,440€ — ANNUAL_UPDATE_REQUIRED |
| Optional simulation diplomas (Clinicum series) | PENDING_CONFIRMATION | Preclinicum / Clinicum I/III/IV — separately priced, not included in tuition |
| Registration/administrative fees | PENDING_CONFIRMATION | See official Tasas Académicas PDF at ucv.es — ANNUAL_UPDATE_REQUIRED |

**Available discounts** (applied primarily to the enrollment fee component, not full tuition — verify scope with UCV):

| Discount type | Amount |
|---|---|
| Pronto pago (full year upfront) | 3% on total annual price — compatible with others |
| Familias Numerosas (special category) | 100% on enrollment fee |
| Familias Numerosas (general category) | 50% on enrollment fee |
| Familia Monoparental Especial | 100% on enrollment fee |
| Discapacidad (≥33%) | 100% on enrollment fee |
| Unidad Familiar (2+ members enrolled) | 50% on lower tuition — ANNUAL_UPDATE_REQUIRED |
| Alumni (≥60 ECTS completed at UCV) | 10% on total degree cost |
| Deportistas de Élite | 100% on enrollment fee |

**Financing options:** Partnership agreements with Banco Santander, Imagin (CaixaBank), CajaMar, Bankinter, and Caixa Popular for student loans at preferential rates.

Note: discounts are not applicable to new entrants for 2026-27 enrollment fee in most categories — verify current applicability with UCV financial aid office (descuentos@ucv.es).

## Scholarships and Financial Aid

UCV allocates approximately 4.7M€ annually across its scholarship and financial aid programs. No Medicine-specific scholarship (comparable to UNAV's Becas Prof. Jiménez Vargas) was identified in publicly available sources.

**Performance-based scholarships:**
- Beca de Excelencia UCV — for high-performing continuing students
- Beca Primero de Grado — for new entrants meeting academic criteria
- Beca Santander Excelencia 360º — Santander-funded academic excellence program (2026 edition available)

**Need-based support:**
- Beca Ayuda UCV — internal financial aid, need-assessed
- Becas del Ministerio de Educación — national general scholarship
- Becas de la Generalitat Valenciana — regional scholarship for Valencia residents
- Beca Santander Ayuda Económica (25/26 and 26/27 editions)

**Collaboration scholarships (from 2nd year):**
- Beca Colaboración UCV — participation in faculty or research activities
- Beca de Colaboración MEFP — national ministry collaboration grant

**Specific groups:**
- Beca UCV Capacitas — for students with recognized disabilities
- Becas UCV-FCAPA
- Becas y Ayudas Deportivos — for competitive athletes
- Beca Extraordinaria DANA — emergency scholarship for students from families affected by the 2024 Valencia flooding (ANNUAL_UPDATE_REQUIRED)

Contact: becas@ucv.es. The volume of available aid (4.7M€ total, not Medicine-specific) suggests meaningful per-student amounts are available, but competition across all degree programs is relevant context.

## Accommodation and Cost of Living

Valencia is Spain's third-largest city, with a lower cost of living than Madrid or Barcelona. Estimated monthly costs for a Medicine student:

| Concept | Estimated range | Notes |
|---|---|---|
| Private room (shared flat) | 350–600€/month | Varies significantly by neighborhood and proximity to C/ Quevedo campus |
| University residence | PENDING_CONFIRMATION | UCV has accommodation agreements (e.g. Residencia Anunciata) — ANNUAL_UPDATE_REQUIRED |
| Meals | 200–350€/month | Mix of home cooking and university cafeteria |
| Public transport | 20–40€/month | EMT bus and metro; student pass available |
| Books and materials | 500–800€/year | Estimated |
| **Total monthly living (excl. tuition)** | **~600–1,000€** | |

The Facultad de Medicina (C/ Quevedo, 2) is located in central Valencia, accessible by metro (Línea 5, Xàtiva) and multiple bus lines. For students from outside Valencia, verifying accommodation availability before September is strongly recommended given the high density of university students in the city. UCV's international office (ori@ucv.es) can provide housing guidance for incoming international students.

## International Exchange and Mobility Programs

UCV is a member of EU-CONEXUS (Erasmus+ European University Alliance) and holds Erasmus+ accreditation (code E VALENCI11). The following mobility programs are formally listed for the Medicine degree:

- **Erasmus+ Studies** — semester or year exchange at a European partner university
- **Erasmus+ Practices** — internship or clinical placement at a European institution
- **Mundus Santander Studies** — bilateral exchange outside Europe
- **Mundus Santander Practices** — international extracurricular placement
- **SICUE** — national mobility within Spain
- **EU-CONEXUS Minors** — joint interdisciplinary modules within the EU-CONEXUS alliance (La Rochelle, Kiel, Nicosia, Athens NTUA, Klaipėda, Algarve, Zadar)

**Critical limitation:** Whether active bilateral agreements specifically for Medicine students exist, how many places are available, and whether credits obtained abroad are fully recognized within the Medicine degree plan is PENDING_CONFIRMATION for all programs listed. Students planning to use mobility should contact UCV's international office before relying on this option: ori@ucv.es / outgoing@ucv.es.

## MIR Preparation and Professional Outcomes

UCV promotes active MIR preparation as an institutional priority, stating that MIR readiness is embedded from the first year of the degree. The specific structure of this preparation — whether via dedicated MIR-prep sessions, integrated MCQ-format assessments, or extracurricular programs — is PENDING_CONFIRMATION for formal curricular integration.

The ECOE model used in years 5 and 6, culminating in a 20-station structured clinical examination in the final year, provides preparation for competency-based assessment relevant to MIR qualification expectations.

**Available outcome data:**
- Employment rate within 1 year of graduation: 82% (UCV-published figure — ANNUAL_UPDATE_REQUIRED)
- MIR pass rate: PENDING_CONFIRMATION
- Average MIR national ranking position: PENDING_CONFIRMATION
- Number of annual graduates: PENDING_CONFIRMATION

The 82% first-year employment rate is the only publicly available outcome metric. Without MIR-specific statistics, comparative assessment of preparation effectiveness against other programs is not possible from public data. Students for whom MIR outcomes are a primary decision criterion should request this information directly from UCV admissions or faculty.

## Strategic Fit

### Good Fit For

- Students who are strong in biology and chemistry and benefit from a transparent, structured exam format with published syllabus and sample questions
- Students whose Bachillerato average is solid but not exceptional — UCV's exam-weighted model allows performance-based differentiation beyond academic record
- Students for whom the price of UNAV or other higher-cost programs is a constraint — 14,440€/year positions UCV as accessible relative to much of the private sector
- Students who are comfortable being present in Valencia for multiple consecutive days in June (accreditation, exam, interview)
- Students interested in extensive and well-documented clinical rotations in the Valencian public and private health network
- Students for whom Catholic educational values and integral human formation are compatible or personally attractive
- Students from Valencia and the Comunidad Valenciana who can leverage familiarity with the clinical network for rotation placement
- Health sciences graduates with a degree average ≥8.0 who prefer the 3% reserved pathway without a subject knowledge exam

### Less Suitable For

- Students who cannot be physically present in Valencia across multiple days in June
- International students without Spanish PAU first-convocatoria results or equivalent — the admission process is built around Spanish secondary education, and international credential acceptance is PENDING_CONFIRMATION
- Students who require confirmed WFME accreditation for postgraduate plans in the United States, Canada, or other WFME-requiring jurisdictions
- Students seeking a bilingual or English-medium Medicine program
- Students whose Bachillerato average is unlikely to reach the top-500 grade filter — a strong exam cannot compensate for being excluded from the exam itself
- Students for whom published MIR ranking statistics are a decisive selection criterion

## Risks and Considerations

**Multi-point elimination risk.** Four sequentially eliminatory phases mean that a strong candidate can be eliminated by a scheduling failure (missing the June 12 accreditation deadline), a payment lapse (missing the 50€ confirmation), or a poor interview — regardless of academic qualifications. The process requires disciplined operational management across multiple fixed dates in June.

**The interview is under-prepared by most applicants.** Despite carrying 25% of the final score and being fully eliminatory, the personal interview receives less preparation attention than the academic exam among most applicants. No public rubric or preparation guide has been identified. This asymmetry between importance and preparation is a strategic opportunity for candidates who invest in interview readiness.

**Grade filter threshold is not published in advance.** The minimum Bachillerato grade needed to enter the top 500 changes annually. Students with averages in the 7.5–8.5 range face genuine uncertainty about whether they will be called to the exam. A contingency plan (backup programs) is advisable.

**WFME status unconfirmed.** Students targeting medical practice in WFME-requiring jurisdictions carry unquantified risk. This should be verified with UCV or the relevant foreign medical authority before finalizing a degree choice.

**No published MIR data.** The absence of MIR statistics makes performance comparison with other programs impossible from public sources. This is not a negative signal per se, but it limits informed comparison.

**Optional diploma costs unknown.** The Preclinicum and Clinicum simulation diplomas are optional, appear in the European Diploma Supplement, and are separately priced. Total additional cost over 6 years is PENDING_CONFIRMATION.

**Catholic institutional identity.** UCV operates under an explicitly Catholic mission embedded in its educational framing, pastoral programs, and institutional culture. Applicants who expect a secular academic environment should factor this context into their decision.

## Important Notes

- The 50€ confirmation payment (phase 4) must be made by the stated deadline — non-payment automatically eliminates the candidate with no recourse
- Physical presence in Valencia is required on at least three separate dates: June 12 (accreditation), June 13 (exam), and one assigned date June 15–18 (interview)
- The interview time slot is assigned automatically and cannot be transferred or rescheduled
- Students with more than 30 ECTS already recognized from a Medicine degree at another university are explicitly excluded from this admission process and must apply via a separate academic transfer route through Sede Electrónica UCV
- The official Tasas Académicas PDF (published annually at ucv.es) provides the complete fee breakdown — review before committing as some fee components may not be visible in the web page tuition figure
- Simulation diplomas (Clinicum series) are optional, separately priced, and appear in the European Diploma Supplement — they do not replace or supplement formal degree ECTS
- UCV certified ISO 9001 / ISO 14001 / ISO 45001

## Key Insight

UCV's most distinctive strategic feature is the structure and transparency of its admission model. The combination of a published exam syllabus (with known subject weights and downloadable sample questions) and a fully eliminatory personal interview creates an unusual dynamic: the path to admission is highly legible in advance, but it requires systematic preparation for two very different competencies — subject knowledge and personal interview performance. Students who treat only one of these as a preparation priority are exposed to full elimination at the other gate. The exam's 40% weight makes it the primary scoring differentiator; the interview's eliminatory character makes it the primary risk gate. Both must be treated as primary preparation targets simultaneously.

## Final Takeaway

UCV Medicine in Valencia is a well-established mid-tier private option with one of Spain's most extensively documented clinical networks, a transparent admission structure, and tuition pricing below many private competitors. Its primary strategic value is for students who can demonstrate both subject knowledge and personal interview competency, who are available in Valencia for the multi-day June process, and for whom the Valencian clinical environment is compatible with career goals.

The main unresolved unknowns — WFME accreditation, MIR outcomes, and exact top-500 grade cutoffs — are genuine gaps that should be verified directly with UCV before committing the program to a final shortlist. Students for whom any of these factors is decisive should not assume favorable outcomes without explicit confirmation.

## Frequently Asked Questions

**What is the minimum grade required to register for UCV Medicine admissions?**
For current 2º Bachillerato students (health sciences branch), the minimum is 7.0 in 1º Bachillerato. For applicants who already took PAU, the minimum is a combined score of 12.2 from the first convocatoria of 2023, 2024, or 2025. These are entry conditions, not admission guarantees — you still need to clear the top-500 grade filter, pass the exam, and pass the interview.

**How does the top-500 filter work?**
After grade submission (May 19–June 3), UCV ranks all registered candidates by Bachillerato grade and invites only the top 500 to take the exam. The exact cutoff grade varies each year based on total applicant volume and is not published in advance. If your grade is borderline in the 7.5–8.5 range, your eligibility for the exam cannot be guaranteed.

**What does the UCV Medicine admission exam consist of?**
100 multiple-choice questions: 60% biology, 30% chemistry, 10% physics. All content is based on the official Spanish bachillerato curriculum. UCV publishes the full exam syllabus and downloadable example questions on its website. Physics content is adapted for health sciences students, including those who did not study physics in bachillerato.

**Is the interview eliminatory?**
Yes. The interview is both eliminatory (failure = eliminated regardless of exam score) and weighted (25% of final score). It takes place in person at the Faculty of Medicine, Valencia, June 15–18. The assigned time slot cannot be changed. Interview preparation is as strategically important as exam preparation.

**Can international students apply to UCV Medicine?**
International students can apply, but the standard admission process is built around PAU first convocatoria results. International students without Spanish secondary education credentials should contact UCV admissions before registering to confirm whether their qualifications are accepted: admissions@ucv.es / Tel: +34 96 192 75 90.

**Is there a bilingual Medicine program at UCV?**
No. The program is taught entirely in Spanish. There is no bilingual or English-medium track.

**What hospitals are used for clinical rotations?**
Clinical rotations take place across 15 affiliated centers, primarily in the Comunidad Valenciana, with a total of 1,010 declared slots. The largest are Departamento de Salud Manises (260 slots), Hospital Imed Valencia (175), Hospital Vithas (116), and Hospital IVO (90). Student assignments are based on academic record and ranked preferences submitted through UCV's intranet. ANNUAL_UPDATE_REQUIRED.

**What is the annual tuition at UCV?**
14,440€ per year for the 2026-27 academic year (ANNUAL_UPDATE_REQUIRED). This positions UCV as one of the lower-priced private Medicine programs in Spain. Financing is available through agreements with Banco Santander, Imagin, CajaMar, Bankinter, and Caixa Popular.
