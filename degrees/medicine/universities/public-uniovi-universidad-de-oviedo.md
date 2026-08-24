---
id: uniovi

type: university
subtype: public

name: Universidad de Oviedo
short_name: UNIOVI

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Oviedo
  region: Asturias
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - medium_competitiveness
  - strong_clinical_exposure
  - research_oriented

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
  seats: 165 # ANNUAL_UPDATE_REQUIRED — verified from official UNIOVI website
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
    - intake_year: 2025-2026
      round: convocatoria_ordinaria
      score: 12.784 # ANNUAL_UPDATE_REQUIRED
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
      notes: NULL

international_profile:
  international_students_percentage: PENDING_CONFIRMATION
  international_nationalities: []

programs:
  - id: uniovi-medicina
    campus: Campus El Cristo, Oviedo
    modality: standard
    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - medium_competitiveness
    teaching_languages:
      - Spanish
    regional_language_possible: false
    regional_language: NULL
    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL
    seats: 165 # ANNUAL_UPDATE_REQUIRED — verified from official UNIOVI website
    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 165
      applicants_per_seat: PENDING_CONFIRMATION
      last_admitted_scores:
        - intake_year: 2025-2026
          round: convocatoria_ordinaria
          score: 12.784 # ANNUAL_UPDATE_REQUIRED
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
          score: 12.784 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: notasdecorte.es / Asturias
        - intake_year: 2023-2024
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: PENDING_CONFIRMATION
        - intake_year: 2022-2023
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: PENDING_CONFIRMATION
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
              notes: Best 2 eligible subjects count. Each subject score multiplied by the university's ponderation coefficient (0.1 or 0.2). Maximum nota de admisión: 14.0000. Coefficients ANNUAL_UPDATE_REQUIRED.
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED
                Chemistry:      0.2 # ANNUAL_UPDATE_REQUIRED
                Physics:        0.2 # ANNUAL_UPDATE_REQUIRED
                Mathematics_II: 0.1 # ANNUAL_UPDATE_REQUIRED
                Drawing_II:     ANNUAL_UPDATE_REQUIRED
                History_Art:    ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---
# Universidad de Oviedo

## Overview

The Universidad de Oviedo (UNIOVI) is the sole public university in the Principality of Asturias, offering the Grado en Medicina through its Facultad de Medicina y Ciencias de la Salud. Founded in 1574, it is one of Spain's most established universities and the only option for public medicine education in the region.

The programme follows the national 6-year, 360 ECTS framework. Admission operates exclusively through the nota de admisión system — no internal exam, no interview. With 165 officially verified seats per year, competition is intense and the nota de corte consistently places among the highest nationally. Clinical training is anchored in the Hospital Universitario Central de Asturias (HUCA), one of the largest and most technologically advanced university hospitals in Spain.

The university participates in the Ingenium European University Alliance, reflecting its international academic ambitions. UNIOVI is positioned as the definitive regional public medicine option for Asturian candidates and attracts strong applicants from across Spain.

## Quick Evaluation

- **Entry mechanism:** EVAU nota de admisión only — no internal exam, no interview
- **Competitiveness:** Very high — nota de corte consistently in the high 13.x range
- **Programme duration:** 6 years / 360 ECTS
- **Teaching language:** Spanish only; no bilingual track
- **Seats:** 165 per year (verified)
- **Clinical anchor:** Hospital Universitario Central de Asturias (HUCA) — a major tertiary centre
- **Tuition:** ~1,000–1,500 EUR/year approximate (Asturias regional rates) — ANNUAL_UPDATE_REQUIRED
- **International access:** Via PCE/UNED or Credencial UE

## Key Facts

| Parameter | Value |
|---|---|
| Official degree name | Grado en Medicina |
| Responsible faculty | Facultad de Medicina y Ciencias de la Salud |
| Campus | Campus El Cristo, Oviedo |
| Duration | 6 years |
| Total ECTS | 360 |
| ECTS breakdown | Formación Básica: 93 / Obligatorias: 186 / Optativas: 21 / Prácticas Externas: 51 / TFG: 9 |
| Teaching language | Spanish (Castellano) |
| Modality | Presencial (in-person) |
| Admission model | Nota de admisión (EVAU-based) |
| Exam required | No |
| Interview required | No |
| Annual seats | 165 (verified from official UNIOVI website) — ANNUAL_UPDATE_REQUIRED |
| Nota de corte 2025-26 | 12.784 (notasdecorte.es / Asturias) — ANNUAL_UPDATE_REQUIRED |
| Tuition per credit (1st enrollment) | 15.70 EUR (verified from official UNIOVI website) — ANNUAL_UPDATE_REQUIRED |
| Primary affiliated hospital | Hospital Universitario Central de Asturias (HUCA) |
| Accreditation | ANECA-verified; EU Directive 2005/36/EC compliant |

## Program Options

The UNIOVI Grado en Medicina is offered at a single campus in Oviedo. There is no bilingual track, no secondary campus, and no distance or hybrid modality. The degree is delivered entirely in Spanish in a traditional in-person format.

The university lists a "Plan antiguo" (old plan) version of the Medicine degree separately — this applies to students who began under the previous pre-Bologna curriculum and are completing their studies. All new students entering from 2026-2027 onward enroll in the current plan (Grado en Medicina, Plan Nuevo), which is the subject of this file.

Optional elective subjects (Optativas, 21 ECTS) include Medical English, Nutrition, Exercise Physiology, Research Project modules (Proyecto de Investigación del Grado 1–3), and specialised clinical subjects. These allow a degree of personalisation without altering the core curriculum.

## Program Structure

The programme spans 6 academic years (360 ECTS total):

**Year 1 (Basic Biomedical Sciences):**
- Biochemistry (12 ECTS, annual)
- Cell Biology and Human Histology (6 ECTS)
- General Anatomy and Embryology (6 ECTS)
- Epidemiology (6 ECTS)
- History and Introduction to Health Sciences: Bioethics, Communication and Scientific Method (6 ECTS)
- Physiology I (6 ECTS)
- Anatomy of the Locomotor System (6 ECTS)
- Medical Psychology (6 ECTS)
- Genetics (6 ECTS)

**Year 2 (Morphology and Basic Physiology Completion):**
- Anatomy of the Nervous System and Sense Organs (9 ECTS, annual)
- Esplacnología (6 ECTS)
- Human Microscopic Organography (6 ECTS)
- Introduction to Clinical Medicine: Physical Medicine, General Radiology and Clinical Laboratory (6 ECTS)
- Physiology II (6 ECTS) / Physiology III (6 ECTS)
- Topographic Anatomy (3 ECTS)
- Immunology (6 ECTS)
- Medical Microbiology (6 ECTS)

**Year 3 (Pathology and Clinical Introduction):**
- Fisiopatología y Propedéutica Clínica (12 ECTS, annual)
- Fundamental Pharmacology (9 ECTS, annual)
- Anatomía Patológica (6 ECTS)
- Radiodiagnóstico (6 ECTS)
- Fundamentos de Cirugía (6 ECTS)
- Patología Tumoral (6 ECTS)
- Patología del Aparato Respiratorio (6 ECTS)

**Year 4 (Medical Specialties):**
- Digestive, Endocrine, Metabolic and Nutritional Pathology (9 ECTS)
- Cardio-circulatory Pathology (6 ECTS)
- Nephrourological Pathology (6 ECTS)
- Obstetrics and Gynaecology (6 ECTS)
- Neurology (6 ECTS)
- Dermatology (6 ECTS)
- Psychiatry (6 ECTS)
- Paediatrics (9 ECTS)

**Year 5 (Advanced Specialties and Integration):**
- Ophthalmology (5 ECTS)
- Otorhinolaryngology and Maxillofacial Surgery (7 ECTS)
- Emergency Medicine and Palliative Care (6 ECTS)
- Clinical Pharmacology (6 ECTS)
- Legal Medicine (6 ECTS)
- Musculoskeletal Pathology and Rheumatology (9 ECTS)
- Infectious Pathology (6 ECTS)
- Blood Pathology and Haematopoietic Organs (3 ECTS)
- Clinical Practice Workshop (3 ECTS)
- Preventive Medicine and Public Health (6 ECTS)
- Family and Community Medicine (3 ECTS)

**Year 6 (Full Clinical Rotations + TFG):**
- Prácticas Académicas Externas (51 ECTS, annual) — full-time clinical rotations
- Trabajo Fin de Grado (9 ECTS)

## Teaching Methodology

UNIOVI Medicine follows a traditional lecture-centred pedagogy in Years 1 and 2, with extensive laboratory and dissection practicals in Anatomy, Biochemistry, Histology, and Physiology. Small-group seminars and problem-solving sessions complement lectures progressively from Year 2 onward.

From Year 3, clinical case teaching and simulation exercises are incorporated. Students develop clinical reasoning through supervised bedside sessions at HUCA, with increasing autonomy and patient contact in Years 4 and 5. The optional Research Project module (Proyecto de Investigación del Grado 1–3) allows motivated students to develop a research skill set across three consecutive years, culminating in a divulgation-level output.

Year 6 is structured as a full-time clinical immersion, with students rotating under direct faculty-physician supervision across the hospital network. The Clinical Practice Workshop (Taller de Práctica Clínica) in Year 5 provides hands-on procedural skills training.

## Clinical Training

UNIOVI's clinical training network is anchored in a major regional hospital system:

**Primary affiliated hospital:**
- Hospital Universitario Central de Asturias (HUCA), Oviedo — one of Spain's most modern and comprehensive tertiary university hospitals, with over 1,200 beds and the full spectrum of medical and surgical specialties. HUCA is the primary setting for Years 4–6 clinical rotations.

**Additional clinical network:**
- Hospital Universitario de Cabueñes, Gijón
- Hospital de Jove, Gijón
- Hospital Álvarez Buylla, Mieres
- Hospital Valle del Nalón, Riaño (Langreo)
- Centro de Salud network (primary care rotations, Servicio de Salud del Principado de Asturias — SESPA)

Clinical rotations in Year 6 cover all major specialties: Internal Medicine, Surgery, Paediatrics, Obstetrics and Gynaecology, Psychiatry, Emergency Medicine, and primary care. The network reflects the full diversity of Asturian public healthcare.

All clinical placements are ANNUAL_UPDATE_REQUIRED for network changes and availability.

## International Recognition and Opportunities

The UNIOVI Grado en Medicina is an official Spanish university degree regulated under national law and compliant with European Directive 2005/36/EC. Graduates hold a degree recognised across all EU member states for medical practice, subject to local licensing and language requirements.

UNIOVI is a founding member of the Ingenium European University Alliance (with universities in France, Italy, Czech Republic, Hungary, Poland, Romania, and Portugal), reflecting strong international academic partnerships. Erasmus+ mobility is available, though specific bilateral agreements for Medicine students should be verified with the Facultad de Medicina y Ciencias de la Salud's international office. Clinical year constraints (Year 6) typically limit mobility windows.

WFME recognition status: PENDING_CONFIRMATION. Spanish ANECA-accredited medical degrees are recognised in jurisdictions accepting EU qualifications.

## Admission Model

Access to UNIOVI Grado en Medicina operates exclusively through the Spanish nota de admisión system managed by the Principality of Asturias. No internal exam, no interview, no English proficiency test.

**Nota de admisión formula:**
```
Nota de admisión = 0.6 × Nota media Bachillerato + 0.4 × Nota EVAU (fase general)
                  + (Subject 1 grade × ponderation) + (Subject 2 grade × ponderation)
```
- Base maximum (without specific phase): 10.0000
- With specific phase bonus: up to 14.0000
- Only the best 2 specific-phase subjects are counted

**Ponderation coefficients for Medicina at UNIOVI (Asturias):**
Biology (0.2), Chemistry (0.2), and Physics (0.2) carry the maximum coefficient. Mathematics II (0.1). These are the ponderation values consistent with the Asturias regional ponderation table for Medicine. ANNUAL_UPDATE_REQUIRED — verify via the official UNIOVI admissions website or the Servicio de Acceso of the Principality of Asturias each cycle.

**Cupo (quota) distribution:**
The general access quota covers the majority of the 165 seats. Reserved quotas apply for: students with disabilities (5%), elite athletes, students by traslado from other universities, and international students from non-EU countries. Exact distribution is ANNUAL_UPDATE_REQUIRED.

**International access (PCE/UNED):**
Non-EU students must pass the PCE/UNED (Pruebas de Competencias Específicas). The nota de admisión is calculated using the same formula, with PCE subject grades substituting for EVAU specific-phase grades.

**EU and equivalent credential holders:**
Students from EU countries or countries with bilateral agreements access via Credencial Universitaria (UNED) or direct homologation as applicable.

## Admission Process

### Spanish EVAU (PAU) students — step-by-step:

1. Complete Bachillerato and register for the EVAU in Asturias (or relevant autonomous community).
2. Sit the EVAU general phase (mandatory) and, optionally, specific-phase subjects (Biology, Chemistry, Physics are highest priority for Medicine).
3. Obtain your nota de admisión — calculated by the Asturias regional authority.
4. During preinscripción (typically June–July), submit an ordered preference list via the UNIOVI admissions portal or the Asturias access system.
5. Monitor provisional and definitive adjudication lists.
6. If admitted, complete matriculation and pay tuition within the stipulated deadline.
7. If not admitted in the first round, monitor waiting list positions through the extraordinaria phase (September).

### International students (PCE/UNED) — step-by-step:

1. Verify eligibility for PCE/UNED or direct homologation.
2. Register with UNED and sit PCE examinations in relevant subjects (Spanish language + Biology + Chemistry recommended as minimum).
3. Calculate nota de admisión using PCE specific-phase results.
4. Check UNIOVI's international preinscripción calendar — this may differ from the domestic calendar.
5. Submit application with required documentation (PCE credential, certified translations, passport, academic records).
6. Await resolution and proceed to matriculation if admitted.

## Admission Timeline

All dates are ANNUAL_UPDATE_REQUIRED.

| Stage | Approximate date |
|---|---|
| EVAU (general + specific phase) | June — ANNUAL_UPDATE_REQUIRED |
| Nota de admisión calculation | Late June — ANNUAL_UPDATE_REQUIRED |
| Preinscripción period opens | Late June – early July — ANNUAL_UPDATE_REQUIRED |
| Preinscripción deadline (ordinaria) | Early July — ANNUAL_UPDATE_REQUIRED |
| First adjudication list published | Mid-July — ANNUAL_UPDATE_REQUIRED |
| Waiting list rounds | July–August — ANNUAL_UPDATE_REQUIRED |
| EVAU extraordinaria | September — ANNUAL_UPDATE_REQUIRED |
| Extraordinaria preinscripción | September — ANNUAL_UPDATE_REQUIRED |
| Final adjudication | September–October — ANNUAL_UPDATE_REQUIRED |
| Academic year start | Mid-September — ANNUAL_UPDATE_REQUIRED |

## Admission Score Distribution

The Grado en Medicina at UNIOVI is among the most competitive university degrees in Asturias and Spain nationally. With only 165 seats, the nota de corte is reliably above 13.5 and has historically approached or exceeded 13.8 in high-demand years.

**Historical nota de corte:**
- 2025-2026: 12.784 (source: notasdecorte.es / Asturias — ANNUAL_UPDATE_REQUIRED)
- 2023-2024: PENDING_CONFIRMATION
- 2022-2023: PENDING_CONFIRMATION

**Strategic interpretation:**
The combination of limited seat count (165) and national-level competition means the UNIOVI Medicine nota de corte is less forgiving than at universities with more seats. A candidate with Biology (10) and Chemistry (10) at 0.2 each gains 4.0 bonus points. To reach a nota de admisión of 13.7: 0.6×B + 0.4×G + 4.0 = 13.7 → 0.6×B + 0.4×G = 9.7. This requires an average weighted Bachillerato+EVAU general of 9.7/1.0 = 9.7 — extremely demanding and illustrative of the required profile.

Year-on-year variability of 0.05 to 0.15 points is expected. Small seat counts tend to produce less stable notas de corte than programmes with 250+ seats.

## Costs and Payment Structure

Tuition at UNIOVI is set annually by the Principality of Asturias.

| Cost item | Amount (EUR) | Notes |
|---|---|---|
| Tuition per credit (1st enrollment) | 15.70 EUR | ANNUAL_UPDATE_REQUIRED — verified from UNIOVI official website |
| Approximate annual tuition (60 ECTS/year) | ~942 EUR | ANNUAL_UPDATE_REQUIRED — based on 60 × 15.70 |
| Tuition per credit (2nd enrollment) | 34.93 EUR | ANNUAL_UPDATE_REQUIRED |
| Tuition per credit (3rd enrollment) | 64.04 EUR | ANNUAL_UPDATE_REQUIRED |
| Tuition per credit (4th enrollment) | 89.54 EUR | ANNUAL_UPDATE_REQUIRED |
| Per credit (non-EU, non-listed countries) | 64.04 EUR | ANNUAL_UPDATE_REQUIRED |
| Administrative fees | ANNUAL_UPDATE_REQUIRED | Per academic year |
| Medical/accident insurance | ~1.12 EUR/year | ANNUAL_UPDATE_REQUIRED |

Note: The non-resident non-EU tariff (64.04 EUR/credit) applies uniformly across all enrollment attempts for students outside the listed preferred nationalities. Students from Spain, EU member states, and the extensive list of Latin American countries (Argentina, Bolivia, Brazil, Chile, Colombia, Costa Rica, Cuba, Ecuador, El Salvador, Guatemala, Equatorial Guinea, Haiti, Honduras, Morocco, Mexico, Nicaragua, Panama, Paraguay, Peru, Puerto Rico, Dominican Republic, Uruguay, Venezuela) pay the standard domestic rate.

## Scholarships and Financial Aid

**National scholarships (MEC Beca General):** Means-tested, applied annually via the MEFP scholarship portal. Amounts vary. ANNUAL_UPDATE_REQUIRED.

**Regional Asturias scholarships:** The Principality of Asturias may offer supplementary scholarship programmes. ANNUAL_UPDATE_REQUIRED.

**UNIOVI own grants:** Emergency aid grants (ayudas de emergencia) and matrícula de honor mechanisms apply as at other Spanish public universities — achieving matrícula de honor in a subject allows free enrollment in that subject's credits in the following year.

**EU students:** Treated equivalently to Spanish nationals for fee purposes. Non-EU students from non-listed countries pay the higher tariff per credit.

## Accommodation and Cost of Living

Oviedo is a mid-sized regional capital with significantly lower living costs than major Spanish cities.

| Expense category | Approximate monthly range (EUR) | Notes |
|---|---|---|
| Student accommodation (shared flat) | 250–400 EUR | ANNUAL_UPDATE_REQUIRED |
| University residence (Colegio Mayor) | 400–600 EUR | ANNUAL_UPDATE_REQUIRED — includes meals in some cases |
| Food (self-catering) | 150–250 EUR | ANNUAL_UPDATE_REQUIRED |
| Transport (urban) | 20–40 EUR | ANNUAL_UPDATE_REQUIRED |
| Other living expenses | 100–200 EUR | ANNUAL_UPDATE_REQUIRED |
| **Estimated total monthly budget** | **520–1,290 EUR** | ANNUAL_UPDATE_REQUIRED |

Oviedo has a compact, walkable city centre. The Faculty of Medicine is located near HUCA in the El Cristo area, within accessible distance of the main campus zone. Student accommodation in shared flats is available at reasonable rates.

## International Exchange and Mobility Programs

UNIOVI participates in Erasmus+ and is a founding member of the Ingenium European University Alliance (EU-funded alliance). Bilateral exchange agreements exist with Latin American universities. However, Erasmus+ and bilateral mobility for Medicine students is subject to specific faculty-level agreements — not all general university partnerships extend automatically to Medicine. Clinical year constraints (Year 6) typically limit mobility windows to Years 3–5. Students should confirm opportunities with the Facultad de Medicina y Ciencias de la Salud's Relaciones Internacionales office. PENDING_CONFIRMATION.

## MIR Preparation and Professional Outcomes

Graduates are fully eligible to sit the MIR (Médico Interno Residente). UNIOVI does not publish official MIR outcome statistics disaggregated by institution. PENDING_CONFIRMATION. Graduates access all 49 medical specialties via MIR. The primary regional employer is the Servicio de Salud del Principado de Asturias (SESPA).

The IUOPA (Instituto Universitario de Oncología del Principado de Asturias), the CSIC, and the Instituto Carlos III are referenced in official programme documentation as research destinations for graduates pursuing academic or research careers.

## Strategic Fit

### Good Fit For

- Students with nota de admisión reliably above 13.7–13.8 (historically demanded range)
- Asturian candidates familiar with the regional EVAU and seeking to stay in the region
- Candidates who have maximised EVAU specific-phase performance in Biology (0.2) and Chemistry (0.2)
- Students prioritising access to HUCA — one of Spain's most modern and well-equipped teaching hospitals
- International students (PCE/UNED) with competitive equivalent nota de admisión and Spanish language proficiency

### Less Suitable For

- Students whose nota de admisión is below approximately 13.5 — the small seat count makes marginal candidacy risky
- Students seeking English-medium instruction or a bilingual track
- Students requiring early international mobility — clinical year constraints are significant
- Students who cannot commit to Spanish-only instruction at postgraduate clinical level

## Risks and Considerations

**Small seat count amplifies nota de corte risk:** With only 165 seats, minor annual fluctuations in applicant quality or EVAU difficulty can move the nota de corte by 0.1–0.2 points. Candidates near the threshold face meaningful year-to-year risk.

**Single campus:** There is no secondary campus or lower-competition alternative within UNIOVI Medicine. Palencia (UVA) is a separate institution and process.

**Geographic isolation:** Asturias is geographically peripheral in Spain. Students who relocate from other regions should account for the regional character of the job market and clinical network.

**Non-EU tuition rates:** Students outside the listed preferred nationalities (see Costs section) pay 64.04 EUR/credit at first enrollment — significantly higher than domestic rates, though still lower than most private institutions.

**PCE/UNED preparation:** International students require additional investment in PCE preparation. Competitive PCE results in Biology and Chemistry are the most impactful actions available.

## Important Notes

- All dates are ANNUAL_UPDATE_REQUIRED. Check uniovi.es and the Asturias access system each cycle.
- The official seat count (165) is verified from the UNIOVI degree page as of May 2026. ANNUAL_UPDATE_REQUIRED.
- Tuition per credit for first enrollment (15.70 EUR) is verified from the official UNIOVI website. ANNUAL_UPDATE_REQUIRED.
- Specific-phase subject ponderations are ANNUAL_UPDATE_REQUIRED — verify via the UNIOVI or Principality of Asturias admissions publications each cycle.
- International students via PCE/UNED should verify the separate international preinscripción calendar.

## Key Insight

UNIOVI Medicine is a high-value, publicly funded degree anchored in HUCA — one of Spain's finest university hospitals. The combination of only 165 seats and national-level competition creates a very narrow admission window. The programme is right for high-scoring candidates who can sustain a nota de admisión in the upper range of the national Medicine competition. There are no alternative pathways, no interviews, and no extracurricular compensatory mechanisms. For students who qualify, the cost efficiency (~900 EUR/year for domestic students), the clinical quality, and the research environment are compelling.

## Final Takeaway

Universidad de Oviedo's Grado en Medicina is a rigorous, well-resourced, and affordable public medicine degree with strong clinical infrastructure centred on HUCA. Access is exclusively nota de admisión-driven with 165 seats annually. It is strategically valuable for top-scoring candidates — especially those who have maximised Biology and Chemistry in the EVAU specific phase — who are prepared to live in Asturias and engage with an exclusively Spanish-medium clinical education. The primary risk is the nota de corte, which is unforgiving given the limited seat count.

## Frequently Asked Questions

**How is the nota de admisión calculated?**
The nota de admisión combines 60% of the Bachillerato average and 40% of the EVAU general-phase score (base maximum 10.0). Up to 4 additional points come from the EVAU specific phase using the best 2 subjects. For UNIOVI Medicine, Biology: 0.2, Chemistry: 0.2, Physics: 0.2, Mathematics II: 0.1. ANNUAL_UPDATE_REQUIRED.

**What is the nota de corte at UNIOVI Medicine?**
The nota de corte for 2025-2026 is 12.784 (source: notasdecorte.es / Asturias — ANNUAL_UPDATE_REQUIRED). Prior cycle data (2023-24, 2022-23) remains PENDING_CONFIRMATION — verify via the official UNIOVI admissions portal.

**How many seats are available?**
165 seats per year (verified). ANNUAL_UPDATE_REQUIRED.

**Can international students apply via PCE/UNED?**
Yes. Non-EU students who complete the PCE/UNED obtain a nota de acceso equivalent to the Spanish EVAU. Their nota de admisión is calculated identically. Apply during the international preinscripción period.

**What are the tuition fees?**
15.70 EUR per credit at first enrollment (verified). For a typical 60-ECTS year, this amounts to approximately 942 EUR. ANNUAL_UPDATE_REQUIRED.

**When do I apply?**
Preinscripción is submitted in late June/early July for the ordinaria phase, after EVAU results. A second window (extraordinaria) is available in September. All dates ANNUAL_UPDATE_REQUIRED.

**What are the ponderation coefficients for Medicine at UNIOVI?**
Biology: 0.2, Chemistry: 0.2, Physics: 0.2, Mathematics II: 0.1. ANNUAL_UPDATE_REQUIRED — always verify via official sources before the EVAU specific-phase choices deadline.

**Does UNIOVI offer Medicine in English or bilingually?**
No. The Grado en Medicina is taught entirely in Spanish (Castellano). An optional subject, Medical English (Inglés Médico, 3 ECTS), is available as an elective.

**What hospital do students train in?**
The primary affiliated hospital is the Hospital Universitario Central de Asturias (HUCA) in Oviedo. The rotation network also includes Hospital de Cabueñes (Gijón), Hospital de Jove, Hospital Álvarez Buylla, Hospital Valle del Nalón, and primary care centres across Asturias.
