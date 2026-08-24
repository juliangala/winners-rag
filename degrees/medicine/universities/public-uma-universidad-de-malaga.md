---
id: uma

type: university
subtype: public

name: Universidad de Málaga
short_name: UMA

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Málaga
  region: Andalucía
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - medium_competitiveness
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
  seats: 170 # ANNUAL_UPDATE_REQUIRED — verified from official UMA degree page (Número de Plazas: 170)
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
    - intake_year: 2025-2026
      round: convocatoria_ordinaria
      score: 13.133 # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: "Source: notasdecorte.es / Junta de Andalucía DUA"
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
  - id: uma-medicina
    campus: Campus Universitario de Teatinos, Málaga
    modality: standard
    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - medium_competitiveness
      - international_friendly
    teaching_languages:
      - Spanish
    regional_language_possible: false
    regional_language: NULL
    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL
    seats: 170 # ANNUAL_UPDATE_REQUIRED — verified from official UMA degree page
    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 170
      applicants_per_seat: PENDING_CONFIRMATION
      last_admitted_scores:
        - intake_year: 2025-2026
          round: convocatoria_ordinaria
          score: 13.133 # ANNUAL_UPDATE_REQUIRED
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
          score: 13.133 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: "notasdecorte.es / Junta de Andalucía DUA"
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
              notes: Best 2 eligible subjects count. Each subject score multiplied by the university's ponderation coefficient (0.1 or 0.2). Maximum nota de admisión: 14.0000. Coefficients set by Andalucía Distrito Único. ANNUAL_UPDATE_REQUIRED.
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED — Andalucía ponderation for Medicina
                Chemistry:      0.2 # ANNUAL_UPDATE_REQUIRED — Andalucía ponderation for Medicina
                Physics:        0.2 # ANNUAL_UPDATE_REQUIRED — Andalucía ponderation for Medicina
                Mathematics_II: 0.1 # ANNUAL_UPDATE_REQUIRED — Andalucía ponderation for Medicina
                Drawing_II:     ANNUAL_UPDATE_REQUIRED
                History_Art:    ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---
# Universidad de Málaga

## Overview

The Universidad de Málaga (UMA), founded in 1972, is a public university located in one of Spain's fastest-growing Mediterranean cities. The Facultad de Medicina offers the Grado en Medicina at the Campus Universitario de Teatinos. The programme follows the national 6-year, 360 ECTS framework and is accessed exclusively via the nota de admisión system — no internal exam, no interview.

The UMA Grado en Medicina currently operates under a dual curriculum arrangement: the original Plan 2010 and a new Plan 2023, which has been progressively verified and is being implemented. Both are accredited by ANECA. With 170 officially verified seats, UMA Medicine is among the more accessible — by seat count — of Spain's public medicine programmes in Andalucía, though competition remains very high.

Málaga's position as a major international city, with a large foreign resident and visitor population, and its proximity to the Costa del Sol hospital infrastructure, creates a distinctive clinical environment. The UMA participates in Erasmus+ and has a broad international student presence across its faculties, reflecting its openness to international students.

Admission in Andalucía is managed through the Distrito Único Andaluz (DUA) system via the Junta de Andalucía, which sets unified ponderation coefficients for all Andalucía public universities.

## Quick Evaluation

- **Entry mechanism:** EVAU nota de admisión only — no internal exam, no interview
- **Competitiveness:** Very high — nota de corte consistently above 13.500
- **Programme duration:** 6 years / 360 ECTS
- **Teaching language:** Spanish only (Castellano)
- **Seats:** 170 per year (verified)
- **Clinical anchor:** Hospital Regional Universitario de Málaga + Hospital Universitario Virgen de la Victoria
- **Tuition:** Approximately 1,000–1,500 EUR/year (Andalucía regional rates) — ANNUAL_UPDATE_REQUIRED
- **International access:** Via PCE/UNED or Credencial UE; DUA manages international quota
- **Curriculum update:** New Plan 2023 verified and being implemented

## Key Facts

| Parameter | Value |
|---|---|
| Official degree name | Graduado/a en Medicina |
| Responsible faculty | Facultad de Medicina |
| Campus | Campus Universitario de Teatinos, Málaga |
| Duration | 6 years |
| Total ECTS | 360 |
| Teaching language | Spanish (Castellano) |
| Modality | Presencial (in-person), profesión regulada |
| Admission model | Nota de admisión via Distrito Único Andaluz (DUA) |
| Exam required | No |
| Interview required | No |
| Annual seats | 170 (verified from official UMA website) — ANNUAL_UPDATE_REQUIRED |
| Nota de corte 2024-25 | PENDING_CONFIRMATION |
| Tuition (approx.) | ANNUAL_UPDATE_REQUIRED |
| Primary affiliated hospitals | Hospital Regional Universitario de Málaga; Hospital Universitario Virgen de la Victoria |
| Accreditation | ANECA-verified (Plan 2010 BOE 05/03/2013; Plan 2023 verified 29/09/2025); EU Directive 2005/36/EC compliant |

## Program Options

The UMA Grado en Medicina is offered at a single campus (Teatinos, Málaga). There is no bilingual track and no secondary campus. The programme is delivered entirely in Spanish.

**Curriculum transition:** UMA is transitioning from Plan 2010 (the original curriculum, implanted in 2010) to the new Plan 2023 (verified September 2025). Students entering from 2025-2026 onward may be under the new plan. Students who began under Plan 2010 and have not completed it follow an adaptation pathway (Adaptación Plan 2010-2023). New students should confirm which plan they will enter under at matriculation. ANNUAL_UPDATE_REQUIRED.

Both plans are accredited by ANECA and provide the same legal title (Graduado/a en Medicina) recognised across the EU.

## Program Structure

The programme spans 6 academic years (360 ECTS total), following the standard national framework:

**Phase 1 — Basic Biomedical Sciences (Years 1–2):**
Core subjects include Anatomy and Embryology, Biochemistry, Cell Biology, Physiology, Histology, Genetics, Microbiology, Immunology, Epidemiology and Biostatistics, History of Medicine, and introduction to the doctor-patient relationship and Bioethics. Predominantly lecture-based with extensive laboratory practicals (histology, anatomy dissection, biochemistry).

**Phase 2 — Pathophysiology and Clinical Sciences (Years 3–4):**
Physiopathology, Propedeutics and Clinical Semiology, Anatomía Patológica, Fundamental Pharmacology, Radiodiagnóstico, and introduction to all major clinical specialties: Internal Medicine, Surgery, Obstetrics and Gynaecology, Paediatrics, Psychiatry, Neurology, Dermatology, Orthopaedics, Ophthalmology, Otorhinolaryngology. Increasing clinical contact from Year 3.

**Phase 3 — Clinical Rotations and Integration (Years 5–6):**
Comprehensive Prácticas Académicas Externas (rotations) across the hospital and primary care network. Year 6 is full-time clinical. Trabajo Fin de Grado (TFG) completed in Year 6.

ECTS distribution (standard national framework):
- Formación Básica: ~90 ECTS
- Obligatorias: ~180 ECTS
- Prácticas Externas: ~60 ECTS
- Optativas: ~21 ECTS
- TFG: ~9 ECTS

## Teaching Methodology

The UMA Grado en Medicina combines traditional lecture-based teaching in early years with practical sessions in anatomy, histology, biochemistry and physiology laboratories. Problem-based learning (PBL) and case-based seminars are progressively integrated from Year 2 onward.

From Year 3, students transition to a mixed environment of classroom-hospital teaching, including supervised clinical seminars and skills workshops. A clinical simulation laboratory is available within the Faculty. The new Plan 2023 (being implemented) may introduce updated pedagogical approaches; students should review the verified curriculum document (Memoria de Verificación del Título, Plan 2023, available on the UMA website).

Research initiation occurs through the TFG (mandatory) and through optional engagement with the Instituto de Investigación Biomédica de Málaga y Plataforma en Nanomedicina (IBIMA Plataforma BIONAND), the main biomedical research institute affiliated with UMA and the Málaga public health system.

## Clinical Training

The UMA Medicine programme benefits from Málaga's diverse and large hospital infrastructure:

**Primary affiliated hospitals:**
- Hospital Regional Universitario de Málaga — the primary regional teaching hospital, the largest in Málaga province, a major tertiary centre with comprehensive specialty coverage
- Hospital Universitario Virgen de la Victoria (El Chorro campus / Campanillas) — a major university hospital in the western Málaga health area

**Additional clinical network:**
- Hospital Civil (Málaga, historic teaching centre)
- Hospital Materno-Infantil (part of the Regional University Hospital complex)
- Hospital Universitario Costa del Sol, Marbella
- Hospital Comarcal de la Axarquía, Vélez-Málaga
- Centros de Salud (primary care rotations, Sistema Sanitario Público de Andalucía — SSPA)

The Málaga hospital network reflects a large and diverse patient population, including significant international and tourism-related healthcare demand, which provides students with exposure to a wide range of clinical presentations.

All clinical placements ANNUAL_UPDATE_REQUIRED.

## International Recognition and Opportunities

The UMA Grado en Medicina is regulated under national law and compliant with European Directive 2005/36/EC. Graduates hold a degree recognised across all EU member states.

UMA has a well-established international presence and participates in Erasmus+. It holds accreditations including the ACEEU Entrepreneurship Excellence Label and the ODS (UN Sustainable Development Goals) leadership recognition. The university's international hub (WelcomeToUMA) reflects its strategic orientation toward international students.

Erasmus+ mobility for Medicine students is subject to bilateral agreements at the faculty level — not all general UMA partnerships extend to the Facultad de Medicina. Clinical year constraints (Year 6) typically limit mobility windows. Students should confirm opportunities with the Facultad de Medicina. PENDING_CONFIRMATION.

WFME recognition status: PENDING_CONFIRMATION.

## Admission Model

Access to UMA Grado en Medicina operates through the Distrito Único Andaluz (DUA) system managed by the Junta de Andalucía. No internal exam, no interview, no English proficiency test.

**Nota de admisión formula:**
```
Nota de admisión = 0.6 × Nota media Bachillerato + 0.4 × Nota EVAU/PEvAU (fase general)
                  + (Subject 1 grade × ponderation) + (Subject 2 grade × ponderation)
```
- Base maximum: 10.0000; with specific phase bonus: up to 14.0000
- Only the best 2 specific-phase subjects are counted

**Ponderation coefficients for Medicina at UMA (Andalucía — DUA):**
The ponderations are set by the Comisión del Distrito Único Universitario de Andalucía and apply uniformly across all Andalucía public universities for Medicine. Biology (0.2), Chemistry (0.2), Physics (0.2) carry the maximum coefficient. Mathematics II (0.1).

These ponderations were established for 2024-2025 onward and are subject to annual review. The relevant DUA resolution is published in the BOJA annually. ANNUAL_UPDATE_REQUIRED.

**Cupo distribution (Andalucía):**
The DUA manages seat allocation across all Andalucía public universities. Quotas include: general access (majority), students with disabilities (5%), elite athletes, traslado students, and international students from non-EU countries. The international student quota for Andalucía is managed separately with its own calendar and score floor. ANNUAL_UPDATE_REQUIRED.

**International access:**
Non-EU students access via PCE/UNED or through the DUA's international student pathway. Their nota de admisión or equivalent score is calculated in the standard way. International preinscripción in Andalucía operates through the juntadeandalucia.es/economiaconocimientoempresasyuniversidad portal (DUA).

**EU students and equivalent credential holders:**
Via Credencial UE or direct homologation. The DUA sets the minimum nota required for international students from EU countries in each cycle. ANNUAL_UPDATE_REQUIRED.

## Admission Process

### Spanish EVAU (PEvAU) students — step-by-step:

1. Complete Bachillerato and register for the PEvAU (Prueba de Evaluación del Bachillerato para el Acceso a la Universidad) in Andalucía or the EVAU in another autonomous community.
2. Sit the general phase (mandatory) and, optionally, specific-phase subjects (Biology, Chemistry, Physics recommended).
3. Obtain nota de admisión — calculated by the Andalucía regional authority.
4. During preinscripción (June–July), submit an ordered list of degree preferences through the DUA portal (juntadeandalucia.es/sguit).
5. Monitor provisional and definitive adjudication lists (published in stages through to November).
6. If admitted, complete matriculation at UMA within the established deadline.
7. If not admitted in the first round, monitor waiting list positions through the extraordinaria phase (September).

### International students (PCE/UNED and equivalents) — step-by-step:

1. Verify eligibility for access via PCE/UNED or the DUA international pathway.
2. If PCE/UNED: register with UNED and sit PCE examinations in required subjects (Spanish language + Biology + Chemistry strongly recommended).
3. Obtain nota de acceso and calculate nota de admisión with PCE specific-phase subjects.
4. Check the DUA's international preinscripción calendar — this operates on a different window from domestic preinscripción.
5. Submit the application through the DUA international portal with all required documentation.
6. Await resolution and, if admitted, complete matriculation at UMA.

## Admission Timeline

All dates are ANNUAL_UPDATE_REQUIRED. Approximate annual calendar (Andalucía PEvAU cycle):

| Stage | Approximate date |
|---|---|
| PEvAU (general + specific phase) | June — ANNUAL_UPDATE_REQUIRED |
| Nota de admisión calculation | Late June — ANNUAL_UPDATE_REQUIRED |
| DUA preinscripción opens | Late June — ANNUAL_UPDATE_REQUIRED |
| DUA preinscripción deadline (ordinaria) | Early July — ANNUAL_UPDATE_REQUIRED |
| First adjudication list (provisional) | Mid-July — ANNUAL_UPDATE_REQUIRED |
| Waiting list rounds | July–August — ANNUAL_UPDATE_REQUIRED |
| PEvAU extraordinaria | September — ANNUAL_UPDATE_REQUIRED |
| Extraordinaria preinscripción | September — ANNUAL_UPDATE_REQUIRED |
| Final adjudication | September–November — ANNUAL_UPDATE_REQUIRED |
| Academic year start | Mid-September — ANNUAL_UPDATE_REQUIRED |

## Admission Score Distribution

The Grado en Medicina at UMA, managed through the Andalucía DUA system, is consistently among the most competitive degrees in the district. The nota de corte for Medicine in Andalucía is reliably in the 13.5–13.9 range.

**Historical nota de corte (UMA — verify via DUA):**
- 2025-2026: 13.133 (source: notasdecorte.es / Junta de Andalucía DUA)
- 2023-2024: PENDING_CONFIRMATION
- 2022-2023: PENDING_CONFIRMATION

The 2025-2026 nota de corte was 13.133, sourced from notasdecorte.es / Junta de Andalucía DUA.

**Strategic interpretation:**
With 170 seats and DUA-wide competition (all Andalucía candidates compete across all Andalucía Medicine degrees simultaneously), the nota de corte reflects the strongest applicants across the entire district. Candidates who rank UMA Medicine as first choice compete against those who rank any Andalucía medicine degree above UMA. This DUA structure means the effective nota de corte is influenced by system-wide demand rather than UMA-specific factors alone.

Biology (0.2) and Chemistry (0.2) are the dominant specific-phase subjects. A perfect score in both (10 × 0.2 + 10 × 0.2 = 4.0 bonus) combined with a high base score (≥9.5) is typically required to be competitive.

The DUA publishes historical notas de corte at the page: juntadeandalucia.es/economiaconocimientoempresasyuniversidad/sguit/?q=grados&d=g_not_cor_anteriores_top.php

## Costs and Payment Structure

Tuition at UMA is set annually by the Junta de Andalucía. Andalucía has among the lower public university tuition rates in Spain.

| Cost item | Amount (EUR) | Notes |
|---|---|---|
| Annual tuition (approx. first enrollment) | ~750–1,200 EUR | ANNUAL_UPDATE_REQUIRED — Andalucía public university rates, set by Decreto de la Junta |
| Per credit (2nd enrollment) | ANNUAL_UPDATE_REQUIRED | Higher rate |
| Per credit (3rd enrollment) | ANNUAL_UPDATE_REQUIRED | Higher rate |
| Administrative fees | ANNUAL_UPDATE_REQUIRED | Per academic year |
| Medical/accident insurance | ~1.12 EUR/year | ANNUAL_UPDATE_REQUIRED |

Note: Andalucía public university tuition is historically lower than many other autonomous communities, making UMA one of the more affordable public medicine options in Spain by tuition cost.

## Scholarships and Financial Aid

**MEC Beca General:** National means-tested scholarship, applied annually via the MEFP scholarship portal. ANNUAL_UPDATE_REQUIRED.

**Junta de Andalucía scholarship:** The Junta de Andalucía administers its own complementary scholarship programme for Andalucía public university students. ANNUAL_UPDATE_REQUIRED.

**UMA own grants and scholarships (Becas UMA):** The UMA offers its own scholarship and aid programmes, including emergency aid grants and mobility scholarships. ANNUAL_UPDATE_REQUIRED.

**EU students:** Treated equivalently to Spanish nationals for fee purposes.

**Non-EU students:** May pay differentiated rates depending on Andalucía decree pricing. ANNUAL_UPDATE_REQUIRED.

## Accommodation and Cost of Living

Málaga is a major Mediterranean city with a higher cost of living than smaller regional capitals, though still significantly below Madrid or Barcelona.

| Expense category | Approximate monthly range (EUR) | Notes |
|---|---|---|
| Student accommodation (shared flat) | 350–550 EUR | ANNUAL_UPDATE_REQUIRED — Málaga has higher rent than most Spanish provincial capitals |
| University residence (Residencia Universitaria) | 450–700 EUR | ANNUAL_UPDATE_REQUIRED |
| Food (self-catering) | 150–250 EUR | ANNUAL_UPDATE_REQUIRED |
| Transport (urban / EMT) | 30–50 EUR | ANNUAL_UPDATE_REQUIRED |
| Other living expenses | 100–200 EUR | ANNUAL_UPDATE_REQUIRED |
| **Estimated total monthly budget** | **630–1,550 EUR** | ANNUAL_UPDATE_REQUIRED |

Málaga's rental market has experienced significant inflation in recent years due to tourism demand and the growing technology sector presence. Students should plan accommodation early, particularly for proximity to Campus Teatinos and the Hospital Regional.

## International Exchange and Mobility Programs

UMA has a broad international outlook and participates in Erasmus+, SICUE (national), and bilateral agreements with Latin American and North African universities. The WelcomeToUMA hub and the Centro Internacional de Español reflect the university's infrastructure for international students.

Mobility for Medicine students is subject to faculty-level bilateral agreements with the Facultad de Medicina — confirm directly that specific exchange slots are available for Medicine students. Clinical year (Year 6) constraints typically preclude mobility in the final year. PENDING_CONFIRMATION.

## MIR Preparation and Professional Outcomes

Graduates are eligible for the MIR. UMA does not publish official MIR outcome statistics disaggregated by institution. PENDING_CONFIRMATION. Professional outcomes include access to 49 medical specialties via MIR, positions in the Sistema Sanitario Público de Andalucía (SSPA), private healthcare (including the significant private sector in Málaga and the Costa del Sol), academic medicine, and research (IBIMA Plataforma BIONAND).

## Strategic Fit

### Good Fit For

- Students whose nota de admisión consistently places above the expected cut-off for Andalucía Medicine (approximately 13.5–13.8+)
- Candidates who have maximised EVAU specific-phase in Biology (0.2) and Chemistry (0.2)
- Students seeking to study medicine in an internationally oriented, rapidly growing Mediterranean city
- International students (PCE/UNED or DUA international pathway) with a competitive nota de admisión and Spanish proficiency
- Students who benefit from Andalucía's relatively lower public university tuition rates
- Students interested in exposure to a large, diverse hospital network including a significant private healthcare sector

### Less Suitable For

- Students whose nota de admisión falls below the expected cut-off for Andalucía Medicine
- Students who require English-medium instruction
- Students expecting early international mobility in clinical years
- Students on a very tight accommodation budget (Málaga rental costs are higher than comparable Spanish cities)

## Risks and Considerations

**DUA system dynamics:** Unlike regional admissions systems where candidates apply to a single university, the Andalucía DUA means all candidates compete across all Andalucía Medicine degrees simultaneously. This can produce unexpected nota de corte movements if preferences shift.

**Nota de corte variability:** Annual fluctuations of 0.05–0.15 points are normal. Marginal candidacy is risky in this environment.

**Rising accommodation costs:** Málaga's rental market has experienced sustained price increases. Early planning and securing accommodation before the academic year is essential.

**Plan 2023 transition:** Students entering during the Plan 2010→Plan 2023 transition period should clarify which curriculum they will follow and whether adaptation provisions apply to their cohort. ANNUAL_UPDATE_REQUIRED.

**Non-EU tuition rates:** Non-EU students outside preferred nationalities may face differentiated pricing. ANNUAL_UPDATE_REQUIRED.

## Important Notes

- All dates are ANNUAL_UPDATE_REQUIRED. Check uma.es and the DUA portal (juntadeandalucia.es/sguit) each cycle.
- Seat count (170) is verified from the official UMA degree page. ANNUAL_UPDATE_REQUIRED.
- Ponderation coefficients are set by the Comisión del Distrito Único Universitario de Andalucía and are ANNUAL_UPDATE_REQUIRED — verify via the DUA annual publication in the BOJA.
- International students should use the DUA international preinscripción process, not the domestic calendar.
- The new Plan 2023 Memoria de Verificación is available at uma.es/media/files/MV_Medicina_29-09-2025.pdf.

## Key Insight

The UMA Grado en Medicina is a competitive, cost-efficient, and internationally situated public medicine programme with access to a large and diverse clinical network in one of Spain's fastest-growing cities. The DUA system creates a regional competition pool broader than any single university, which can make the nota de corte less predictable than in single-region systems. For high-scoring candidates, UMA combines affordable Andalucía tuition, strong clinical infrastructure, and a uniquely Mediterranean setting. The primary strategic risk is the nota de corte, which is determined by the entire Andalucía applicant pool, not just UMA applicants.

## Final Takeaway

Universidad de Málaga's Grado en Medicina is a publicly funded, nationally accredited medicine degree with 170 seats, delivered in Spanish, accessed via the Andalucía DUA nota de admisión system. It is strategically valuable for top-scoring candidates who have maximised Biology and Chemistry in the EVAU specific phase, are comfortable with Málaga's Mediterranean setting, and want access to a large, diverse clinical network including private hospital exposure. The transition from Plan 2010 to Plan 2023 adds a variable to track in upcoming cycles. Accommodation costs are higher than in comparable Spanish cities and should be budgeted accordingly.

## Frequently Asked Questions

**How is the nota de admisión calculated?**
60% Bachillerato average + 40% EVAU general phase (base max 10.0) + best 2 specific-phase subjects × coefficients. For Andalucía Medicine (including UMA): Biology 0.2, Chemistry 0.2, Physics 0.2, Mathematics II 0.1. Maximum: 14.0000. ANNUAL_UPDATE_REQUIRED.

**What is the nota de corte at UMA Medicine?**
Consistently in the high 13.x range. Specific values for recent cycles are PENDING_CONFIRMATION — verify via the DUA historical notas de corte database.

**How does the Andalucía DUA system work?**
All Andalucía public university Medicine seats are competed for in a single unified system. Applicants submit an ordered preference list of all degree-campus combinations they want to be considered for, including UMA Medicine. Admission is granted to the highest-ranked eligible option in the preference list for each candidate, sorted by nota de admisión.

**How many seats are available?**
170 per year (verified). ANNUAL_UPDATE_REQUIRED.

**Can international students apply?**
Yes. Non-EU students access via PCE/UNED or the DUA international pathway. EU students via Credencial UE. All must meet the nota de admisión threshold. International preinscripción is managed through the DUA portal.

**What are the tuition fees?**
Andalucía public university tuition is among the lower in Spain. Approximate annual cost for first enrollment: 750–1,200 EUR. Exact figures ANNUAL_UPDATE_REQUIRED.

**When do I apply?**
Preinscripción through the DUA portal in late June/early July (ordinaria). A September extraordinaria window follows. All dates ANNUAL_UPDATE_REQUIRED.

**What are the ponderation coefficients for Medicine at UMA?**
Biology: 0.2, Chemistry: 0.2, Physics: 0.2, Mathematics II: 0.1. These are set by the Comisión del Distrito Único de Andalucía and are ANNUAL_UPDATE_REQUIRED.

**Does UMA offer Medicine in English?**
No. The Grado en Medicina is taught entirely in Spanish (Castellano).

**What hospitals do students train in?**
Primary: Hospital Regional Universitario de Málaga and Hospital Universitario Virgen de la Victoria. Also: Hospital Civil, Hospital Materno-Infantil, Hospital Costa del Sol (Marbella), Hospital de la Axarquía (Vélez-Málaga), and primary care centres (SSPA).

**Which curriculum plan am I entering?**
New students from 2025-2026 onward are expected to enter under Plan 2023. Students who began under Plan 2010 follow an adaptation pathway. Confirm with the Facultad de Medicina at matriculation. ANNUAL_UPDATE_REQUIRED.
