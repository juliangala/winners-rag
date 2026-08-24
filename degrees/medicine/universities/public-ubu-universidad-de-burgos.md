---
id: ubu

type: university
subtype: public

name: Universidad de Burgos
short_name: UBU

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Burgos
  region: Castilla y León
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - medium_high_competitiveness
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
  level: high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: 72 # ANNUAL_UPDATE_REQUIRED — confirmed from official UBU website
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
    - intake_year: 2024-2025
      round: convocatoria_ordinaria
      score: PENDING_CONFIRMATION
      score_type: nota_de_admision
      notes: Programme launched approximately 2021-22; limited historical series
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
  - id: ubu-medicina
    campus: Facultad de Ciencias de la Salud — Paseo de los Comendadores s/n (Hospital Militar), Burgos
    modality: standard
    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - high_competitiveness
      - newer_programme
    teaching_languages:
      - Spanish
    regional_language_possible: false
    regional_language: NULL
    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL
    seats: 72 # ANNUAL_UPDATE_REQUIRED — confirmed from official UBU website
    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 72 # ANNUAL_UPDATE_REQUIRED
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
        - intake_year: 2024-2025
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: PENDING_CONFIRMATION # Castilla y León admissions portal ANNUAL_UPDATE_REQUIRED
        - intake_year: 2023-2024
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
        - intake_year: 2022-2023
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
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
              notes: Best 2 eligible subjects count. Each subject score multiplied by the university's ponderation coefficient (0.1 or 0.2). Maximum nota de admisión: 14.0000. Castilla y León ponderation table applies. Coefficients ANNUAL_UPDATE_REQUIRED.
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED — Castilla y León ponderation table for UBU Medicina
                Chemistry:      0.2 # ANNUAL_UPDATE_REQUIRED — Castilla y León ponderation table for UBU Medicina
                Physics:        0.1 # ANNUAL_UPDATE_REQUIRED — Castilla y León ponderation table for UBU Medicina
                Mathematics_II: 0.1 # ANNUAL_UPDATE_REQUIRED — Castilla y León ponderation table for UBU Medicina
                Drawing_II:     ANNUAL_UPDATE_REQUIRED
                History_Art:    ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---
# Universidad de Burgos

## Overview

The Universidad de Burgos (UBU) is a public university founded in 1994, serving the provinces of Burgos, Palencia, and Soria in the Castilla y León autonomous community. UBU has approximately 8,000 students and is classified as a medium-sized regional university with a practical, professionally oriented educational model. Its Grado en Medicina, offered through the Facultad de Ciencias de la Salud, is one of the newest public medicine programmes in Spain, launched in approximately 2021-22. The programme admits 72 students per year and is delivered in Spanish.

The Burgos Medicine faculty builds on the existing clinical infrastructure of the province, using the Hospital Universitario de Burgos (HUBU) as its primary teaching hospital. HUBU is a modern tertiary-care hospital that opened in 2012, providing a contemporary clinical training environment.

## Quick Evaluation

UBU Medicine is a **high-competitiveness public programme** by Spanish standards, though its nota de corte may be somewhat lower than at Medicine programmes in larger Spanish cities (Madrid, Barcelona, Valencia) due to the regional location and smaller applicant pool specific to Burgos. The programme is taught entirely in Spanish, which is a clear advantage for non-Catalan international students. With 72 seats, the cohort is slightly larger than some newer regional programmes. The programme's key strength is the use of a modern university hospital as the core clinical training site.

## Key Facts

| Attribute | Details |
|---|---|
| Full Name | Universidad de Burgos — Grado en Medicina |
| Location | Burgos, Castilla y León, Spain |
| Type | Public university |
| Programme Status | Active — approximately since 2021-22 |
| Duration | 6 years |
| Total ECTS | 360 ECTS |
| Seats | 72 per year (confirmed — ANNUAL_UPDATE_REQUIRED) |
| Teaching Language | Spanish |
| Admission | Nota de admisión (EVAU/PAU-based) — no exam, no interview |
| Annual Tuition | PENDING_CONFIRMATION — regulated by Junta de Castilla y León (ANNUAL_UPDATE_REQUIRED) |
| Main Teaching Hospital | Hospital Universitario de Burgos (HUBU) |
| Nota de corte (2024-25) | PENDING_CONFIRMATION |

## Program Options

UBU offers a single Grado en Medicina, a standard 6-year programme structured in accordance with Ministerial Order ECI/332/2008. The programme is delivered entirely in Spanish. There are no dual-degree or English-language track variants.

## Program Structure

The programme follows the national Spanish medicine curriculum framework:

- **Years 1–2 (Basic and Biomedical Sciences):** Human Anatomy, Biochemistry, Cell Biology, Physiology, Histology, Genetics, Biostatistics. Heavy preclinical load with laboratory components. UBU has specifically highlighted integration of Artificial Intelligence and future medicine perspectives, personalised medicine, and evidence-based approaches from early years.
- **Years 3–4 (Pathological and Clinical Sciences):** Pathology, Pharmacology, Microbiology, Immunology, Introduction to clinical reasoning and clinical skills. Hospital Virtual simulations are used.
- **Years 5–6 (Clinical Rotations and External Practicum):** Full hospital rotations across all major specialisms at Hospital Universitario de Burgos and associated primary care centres. Supervised patient management and Trabajo Fin de Grado.

Total: 360 ECTS over 6 years.

A distinctive feature of UBU's programme design is the explicit incorporation of **Hospital Virtual** (clinical simulation) infrastructure and an emphasis on future medicine themes (precision medicine, digital health, AI in medicine) embedded throughout the curriculum.

## Teaching Methodology

UBU Medicine employs a contemporary methodology designed at programme inception:

- **Problem-Based and Case-Based Learning:** Clinical scenarios introduced from year 1.
- **Hospital Virtual:** Simulation laboratory for clinical skills, procedural training, and OSCE-format assessments.
- **Bedside teaching:** Integrated supervised hospital practice from years 3–4 onward.
- **Research and evidence integration:** Emphasis on evidence-based medicine and research methodology embedded across years.
- **Family and Community Medicine perspective:** Explicit inclusion of primary care and community health perspectives from early in the curriculum.

Faculty members are drawn from the Universidad de Burgos academic staff and clinicians from the Hospital Universitario de Burgos network.

## Clinical Training

Clinical training is primarily delivered at the **Hospital Universitario de Burgos (HUBU)**, a modern tertiary referral hospital inaugurated in 2012. HUBU serves approximately 380,000 people across the Burgos health area and offers comprehensive secondary and tertiary services including:

- Emergency medicine, intensive care (ICU/UCI)
- Medical specialisms: cardiology, neurology, gastroenterology, pneumology, nephrology, rheumatology, endocrinology
- Surgical specialisms: general surgery, orthopaedics, neurosurgery, urology, ophthalmology, ENT
- Paediatrics and neonatology
- Gynaecology and obstetrics
- Oncology and haematology
- Psychiatry and mental health

Additional clinical training sites include:

- Primary care centres (Centros de Salud) across Burgos province, managed by the Sacyl network (Sanidad de Castilla y León)
- Hospital Santa Cruz (medium complexity, Burgos) for selected rotations

The modernity of HUBU and its relatively high capacity relative to the 72-student cohort is considered an advantage for clinical training quality.

## International Recognition and Opportunities

The UBU Grado en Medicina is verified under the Spanish Ministry of Education framework (Ministerial Order ECI/332/2008) and is automatically recognised across EU member states under the EU professional qualifications directive.

Non-EU graduates must pursue bilateral homologation procedures in their target country. All Spanish Medicine graduates must pass the MIR examination to access specialist training in Spain.

UBU participates in the **Erasmus+ programme** and the national **SICUE** mobility scheme. Given the programme's recent launch, the specific portfolio of Erasmus+ clinical partners for Medicine students may still be developing. UBU's international office (Servicio de Relaciones Internacionales) can provide current partnership details.

International students access UBU Medicine through PCE/UNED, Credencial UE, or direct homologation, under the Castilla y León admissions system coordinated by the Comisión Gestora (distrito único for Castilla y León universities).

## Admission Model

UBU Medicine uses the **standard Spanish public university admissions model**. There is no proprietary examination, no interview, and no portfolio component.

**Nota de admisión formula:**

```
Nota de admisión = 0.6 × Nota media Bachillerato + 0.4 × EVAU general phase
                  + up to 2 specific-phase subjects × ponderation coefficient
```

- Base maximum: **10.0000**
- Maximum with specific-phase bonus: **14.0000**

**Ponderation coefficients for UBU Medicine (Castilla y León):**

| Subject | Coefficient |
|---|---|
| Biology | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Chemistry | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Physics | 0.1 (ANNUAL_UPDATE_REQUIRED) |
| Mathematics II | 0.1 (ANNUAL_UPDATE_REQUIRED) |

Verify current coefficients via the Castilla y León universities access system or directly at UBU's admissions page before the EVAU cycle.

**PCE/UNED access:** International students with equivalent qualifications may access UBU through the PCE/UNED route, applying the same nota de admisión formula. Application is made through the Castilla y León university access commission (UBUNET/Secretaría Virtual — distrito único CyL).

## Admission Process

### For Spanish PAU (EVAU) Students

1. Complete Bachillerato and sit the EVAU (PAU) in any Spanish region (regional variants are mutually accepted for CyL university applications, with appropriate cross-regional coefficient adjustments).
2. Compute your nota de admisión: prioritise Biology and Chemistry as specific-phase subjects (coefficient 0.2).
3. In June–July, submit your application to the Castilla y León unified admissions process (distrito único). Rank UBU Medicine among your degree preferences.
4. Monitor published assignment lists. Accept your place within the stated deadline.
5. Enrol at UBU's Facultad de Ciencias de la Salud for the September intake.

### For International Students (PCE/UNED Route)

1. Register for PCE/UNED examinations (deadlines typically February–March for May examinations).
2. Sit general-phase and specific-phase PCE subjects. Biology and Chemistry are recommended for maximum bonus.
3. Obtain UNED certificate and apply via the Castilla y León unified admissions process.
4. Provide certified translations of academic records as required.
5. If admitted, enrol at UBU and satisfy any administrative requirements.

**Language note:** The programme is fully in Spanish. No Catalan is required. International students must have sufficient Spanish proficiency to follow medical instruction — a B2/C1 level is the practical minimum, though no formal Spanish test is required at admission.

## Admission Timeline

| Event | Approximate Date |
|---|---|
| EVAU / PAU examination (ordinaria) | June (ANNUAL_UPDATE_REQUIRED) |
| CyL unified application window | Late June to early July (ANNUAL_UPDATE_REQUIRED) |
| Assignment results (ordinaria) | Mid July (ANNUAL_UPDATE_REQUIRED) |
| EVAU extraordinaria | September (ANNUAL_UPDATE_REQUIRED) |
| Extraordinaria assignments | September (ANNUAL_UPDATE_REQUIRED) |
| Academic year begins | September (ANNUAL_UPDATE_REQUIRED) |

All dates are indicative and ANNUAL_UPDATE_REQUIRED. Verify at ubu.es/acceso-admision-y-matricula.

## Admission Score Distribution

UBU Medicine is a newer programme with a limited historical nota de corte series.

| Intake Year | Convocatoria | Nota de corte | Source |
|---|---|---|---|
| 2024-2025 | Ordinaria | PENDING_CONFIRMATION | Castilla y León admissions system |
| 2023-2024 | Ordinaria | PENDING_CONFIRMATION | Castilla y León admissions system |
| 2022-2023 | Ordinaria | PENDING_CONFIRMATION | Castilla y León admissions system |

**Important note on data availability (as of 2026):** As of 2026, the Universidad de Burgos Medicine programme has not yet published a nota de corte via notasdecorte.es. The programme is newly established and historical data will accumulate over future intake cycles. Candidates should retrieve current figures directly from the Castilla y León admissions system or ubu.es.

**Contextual interpretation:** Medicine at public universities in Castilla y León (e.g., Universidad de Valladolid, Universidad de Salamanca) has historically required nota de admisión in the 13.50–13.90 range. As UBU is a newer and smaller-profile option in the same region, its nota de corte may be slightly more accessible, potentially in the 12.50–13.50 range, though this is an analytical inference rather than verified data. Candidates should retrieve the actual CyL nota de corte records from the admissions system.

**Trend consideration:** Awareness of newer medicine programmes tends to increase over successive years, which may drive nota de corte upward. The programme should be treated as high-competitiveness regardless of any temporary moderation in early cycles.

## Costs and Payment Structure

| Cost Item | Amount | Notes |
|---|---|---|
| Annual tuition (1st enrolment) | PENDING_CONFIRMATION EUR | Regulated by Junta de Castilla y León decree. ANNUAL_UPDATE_REQUIRED |
| Per-credit rate (Health Sciences) | PENDING_CONFIRMATION EUR/credit | CyL public universities apply a regional rate. ANNUAL_UPDATE_REQUIRED |
| Repeat credit surcharge | ANNUAL_UPDATE_REQUIRED | Higher rate for failed subjects |
| Administrative fees | PENDING_CONFIRMATION EUR | Enrolment, certificates, etc. ANNUAL_UPDATE_REQUIRED |

**Context:** Castilla y León maintains one of the lower public university tuition rate structures in Spain. Health Sciences credits are priced above general Humanities credits but below private alternatives. Exact rates are set in the annual Decreto de Precios Públicos of the Junta de Castilla y León. Candidates should check ubu.es/acceso-admision-y-matricula/matricula/matricula-de-grado/precios-publicos-de-grado/facultad-de-ciencias-de-la-salud for current figures.

## Scholarships and Financial Aid

- **Beca General MEC:** The primary national scholarship for means-tested students with adequate academic performance. Covers tuition and may include a maintenance stipend. Apply at becas.educacion.gob.es. Deadline typically September. ANNUAL_UPDATE_REQUIRED.
- **Becas de la Junta de Castilla y León:** Regional grants supplementing MEC aid, aimed at CyL residents. Details at jcyl.es.
- **UBU institutional grants:** UBU offers a limited number of excellence and equity grants. Information at ubu.es/ayudas-y-becas.
- **Erasmus+ mobility grants:** For students undertaking exchange semesters, covering part of living costs at host institutions.
- **Banco Santander / Fundación UBU:** UBU has an active university-industry partnership with Banco Santander offering competitive scholarships. Details at fundacionubu.com.

## Accommodation and Cost of Living

Burgos is a medium-sized provincial capital with one of the most affordable costs of living of any Spanish university city. Students benefit from lower rents, lower food prices, and lower transport costs compared to any major city.

| Expense Category | Estimated Monthly Range |
|---|---|
| Shared flat (room) | 250–400 EUR |
| University or managed accommodation | PENDING_CONFIRMATION EUR |
| Groceries | 120–200 EUR |
| Local transport | 20–40 EUR |
| Total estimated monthly budget | 500–800 EUR |

All figures are approximate and ANNUAL_UPDATE_REQUIRED.

Burgos is a historic Castilian city, UNESCO World Heritage listed for its Gothic cathedral and the adjacent Monastery of Las Huelgas. It is accessible from Madrid by AVE in approximately 1 hour 15 minutes.

## International Exchange and Mobility Programs

- **Erasmus+:** UBU has established Erasmus+ partnerships across EU member states. Medicine-specific exchange partnerships are PENDING_CONFIRMATION given the programme's recent launch.
- **SICUE:** National student mobility programme within Spain allowing temporary study periods at other Spanish public universities.
- **RUN-EU alliance:** UBU is a member of the RUN-EU European Universities network, providing additional opportunities for international collaboration.
- **International students programme:** UBU's Servicio de Relaciones Internacionales supports incoming and outgoing exchange students.

## MIR Preparation and Professional Outcomes

UBU Medicine is a newly established programme. The first cohort enrolled in approximately 2021-22 will not complete the 6-year degree until approximately 2027-28. Therefore:

- **MIR pass rate:** Not yet available.
- **Graduate outcomes:** Not yet available.

The MIR (Médico Interno Residente) is Spain's national post-graduate medical specialist examination. It is institution-independent and tests the full breadth of medical knowledge. All students, regardless of university, must prepare comprehensively for this examination to access specialist training.

UBU's curricular emphasis on evidence-based medicine, clinical reasoning, and the integration of AI and precision medicine themes is designed to align graduates with contemporary clinical and research demands, though this cannot yet be assessed through outcome data.

## Strategic Fit

### Good Fit For

- Candidates with a **nota de admisión likely to be competitive in the 12.50–13.50 range** (analytical estimate — verify current nota de corte before concluding) who are looking for a Spanish-language public Medicine programme with somewhat lower score thresholds than Madrid, Barcelona, or larger-city alternatives.
- Students who **prefer studying in a mid-sized, affordable Spanish city** without a major metropolitan environment.
- Students who want a **fully Spanish-language programme** (no Catalan, Basque, or Galician required).
- Candidates interested in a **newly designed curriculum** incorporating future medicine themes (AI, precision medicine, Hospital Virtual) from the outset.
- Students who value **access to a modern university hospital** (HUBU opened 2012) as a clinical training environment.

### Less Suitable For

- Candidates with nota de admisión likely to be competitive for higher-profile Medicine programmes (Salamanca, Valladolid, Complutense, etc.) for whom UBU may represent an unnecessary risk hedge.
- Students seeking a **large city environment** with extensive cultural, professional networking, and urban lifestyle options.
- Candidates who need a **long-established programme** with a documented MIR pass rate history — UBU Medicine has not yet graduated a cohort.
- Students interested in highly specialised clinical exposure in rare or complex subspecialisms that a regional hospital may not routinely provide.

## Risks and Considerations

1. **Programme immaturity:** UBU Medicine is recently established. No graduates have yet sat the MIR. WFME accreditation status should be confirmed at the time of application. The programme's long-term institutional reputation is still forming.

2. **Limited nota de corte history:** Fewer than five admission cycles have been completed. There is insufficient data to estimate trend direction with confidence.

3. **Regional location:** Burgos is a provincial city of approximately 170,000 inhabitants. Some students may find limited professional networking opportunities compared to larger academic centres. The MIR preparation ecosystem (academies, peer study groups) may be less developed locally.

4. **Hospital diversity:** HUBU is a modern hospital, but it is a single large centre. Students seeking exposure to a diverse multi-hospital clinical network may find fewer options locally than in Madrid or Barcelona.

5. **Castilla y León regional dynamics:** Domestic demand for Medicine in Castilla y León has historically been lower than in Cataluña or the Comunidad de Madrid, which may have kept scores accessible. If national awareness of UBU Medicine grows, the nota de corte may rise in coming cycles.

## Important Notes

- Seats are confirmed at 72 per year as published on the official UBU website (verified May 2026). ANNUAL_UPDATE_REQUIRED.
- Tuition per-credit rates are set by the Junta de Castilla y León annually. ANNUAL_UPDATE_REQUIRED.
- Nota de corte data for Castilla y León universities is published by the regional admissions body — check the current year's official results at ubu.es or through the CyL district system.
- All timeline information is ANNUAL_UPDATE_REQUIRED.

## Key Insight

UBU Medicine stands out as a **Spanish-language, modern, regional public programme** with a medium-high competitiveness profile. Its 72 seats, modern Hospital Universitario de Burgos, and explicitly forward-looking curriculum design make it a substantive offering — not a fallback option. For candidates who score in the 12.50–13.50 nota de admisión range and are seeking public university Medicine, UBU may represent a genuine opportunity that larger or better-known alternatives cannot match. The core risk is programme immaturity and the absence of MIR track record data.

## Final Takeaway

UBU Medicine is a credible, well-resourced public medicine programme in Castilla y León. For Spanish-speaking candidates with competitive but not top-decile nota de admisión scores, it offers an accessible path to a verified Medicine degree in an affordable city with a modern clinical hospital. Candidates should verify the current nota de corte from the CyL admissions system before making strategy decisions, and should accept that the programme's reputation and MIR outcomes are not yet established.

## Frequently Asked Questions

**How is the nota de admisión calculated for UBU Medicine?**
Nota de admisión = 0.6 × Bachillerato average + 0.4 × EVAU general phase + bonus from up to 2 specific-phase subjects × ponderation coefficient. Maximum score: 14.0000. For UBU Medicine, Biology and Chemistry carry coefficient 0.2 (ANNUAL_UPDATE_REQUIRED per CyL ponderation table), making them the highest-priority specific-phase subjects.

**What is the nota de corte for UBU Medicine?**
The nota de corte for UBU Medicine is PENDING_CONFIRMATION. As a newer programme, confirmed historical data is limited. Based on the regional context, expect a score in the high-competitiveness range. Verify the most recent official figure through the Castilla y León admissions system or at ubu.es.

**Can international students apply via PCE?**
Yes. International students can sit PCE/UNED examinations and use those results in the nota de admisión formula. They apply via the Castilla y León unified admissions system. PCE registration deadlines (typically February–March) must be respected.

**What are the tuition fees?**
Tuition is set annually by the Junta de Castilla y León and is among the lower public university rates in Spain. The exact per-credit price for Medicine at UBU is PENDING_CONFIRMATION and ANNUAL_UPDATE_REQUIRED. Check current rates at the UBU tuition page: ubu.es/acceso-admision-y-matricula/matricula/matricula-de-grado/precios-publicos-de-grado/facultad-de-ciencias-de-la-salud.

**When do I apply?**
Applications are submitted through the Castilla y León unified admissions process in late June–early July after EVAU results. A second round follows in September. All dates ANNUAL_UPDATE_REQUIRED — verify at ubu.es.

**What are the ponderation coefficients?**
For UBU Medicine: Biology 0.2, Chemistry 0.2, Physics 0.1, Mathematics II 0.1 (ANNUAL_UPDATE_REQUIRED). These are set by the Castilla y León intercampus ponderation table. Verify current figures at ubu.es before the EVAU cycle.

**Is the programme taught entirely in Spanish?**
Yes. UBU Medicine is delivered 100% in Spanish. There is no Catalan, Basque, or other co-official language requirement. This is a practical advantage for international students with strong Spanish but no experience with regional languages.

**How many seats are there?**
UBU Medicine offers 72 new-intake seats per year as confirmed on the official UBU website. This is subject to ANNUAL_UPDATE_REQUIRED.

**When does clinical training start?**
Clinical skills training and simulation begin from early years through the Hospital Virtual. Full supervised hospital rotations at Hospital Universitario de Burgos typically begin in years 5–6, with earlier supervised visits integrated from years 3–4.

**Does UBU Medicine have MIR outcome data?**
No. As of 2026, UBU Medicine has not yet graduated its first cohort. MIR pass rate data will become available when the first cohort completes the 6-year programme (approximately 2027-28).
