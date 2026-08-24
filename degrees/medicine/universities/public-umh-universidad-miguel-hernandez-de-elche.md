---
id: umh

type: university
subtype: public

name: Universidad Miguel Hernández de Elche
short_name: UMH

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: San Juan de Alicante
  region: Comunitat Valenciana
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - high_competitiveness
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
  level: high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: 120 # ANNUAL_UPDATE_REQUIRED
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

international_profile:
  international_students_percentage: PENDING_CONFIRMATION
  international_nationalities: []

programs:
  - id: umh-medicina
    campus: Campus de San Juan de Alicante
    modality: standard
    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - high_competitiveness
    teaching_languages:
      - Spanish
    regional_language_possible: true
    regional_language: Valencian
    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL
    seats: 120 # ANNUAL_UPDATE_REQUIRED
    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 120 # ANNUAL_UPDATE_REQUIRED
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
          source: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED — verify at aupv.es or umh.es
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
# Universidad Miguel Hernández de Elche

## Overview

The Universidad Miguel Hernández de Elche (UMH) is a public research university in the Comunitat Valenciana founded in 1996. Its Faculty of Medicine (Facultad de Medicina de la UMH) is located on the Campus de San Juan de Alicante — integrated within the Hospital General Universitario de Alicante (HGUA) complex — creating an exceptional model of campus-embedded clinical training that is rare among Spanish public universities. The Grado en Medicina is a six-year, 360 ECTS programme accredited through ANECA and the RUCT. UMH Medicine's most distinctive institutional feature is its co-location with a major teaching hospital from the very start of the programme: students begin clinical contact in an environment where the academic faculty and clinical staff overlap significantly. The university is strongly oriented toward innovation in medical education, having adopted competency-based models earlier than many peer institutions, and has invested substantially in medical simulation infrastructure.

## Quick Evaluation

| Feature | Detail |
|---|---|
| Seats (plazas) | 120 (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2024-25 | PENDING_CONFIRMATION |
| Teaching language(s) | Spanish (Valencian co-official) |
| Annual tuition (approx.) | ANNUAL_UPDATE_REQUIRED — set by Generalitat Valenciana decree |
| Admission model | Nota de admisión (EVAU-based) — no proprietary exam, no interview |
| Clinical exposure | Exceptional — campus embedded in HGUA hospital complex |
| ECTS | 360 |
| Duration | 6 years |

## Key Facts

| Field | Value |
|---|---|
| Degree | Grado en Medicina |
| Campus | Campus de San Juan de Alicante |
| Seats (plazas ofertadas) | 120 (ANNUAL_UPDATE_REQUIRED) |
| Tuition per year | ANNUAL_UPDATE_REQUIRED |
| Admission model | Score-based (nota de admisión) |
| Proprietary exam | No |
| Interview | No |
| Teaching languages | Spanish (Valencian also used in some contexts) |
| Regional health system | FISABIO / GVA Salut (Generalitat Valenciana) |
| Admissions contact | umh.es/contenido/Estudios |

## Program Options

UMH offers a single Grado en Medicina programme on the San Juan de Alicante campus. There is no separate English-medium or bilingual Medicine track. Instruction is in Spanish; Valencian may appear in some administrative or clinical contexts as the co-official language of the region. No English proficiency test is required for admission. International PCE/UNED students are incorporated into the standard single cohort.

## Program Structure

The Grado en Medicina at UMH spans six academic years with 360 ECTS, structured around a competency-based, clinical-integration model:

- **Years 1–2 (Basic and pre-clinical sciences):** Human morphology and function; biochemistry; physiology; histology; anatomy; cell biology; genetics; microbiology; immunology; public health; epidemiology; medical psychology; biostatistics. Early contact with the clinical environment through structured visits and skills labs begins in year 1 given the campus-hospital integration.
- **Years 3–4 (Clinical sciences integration):** Pathology; pharmacology; internal medicine modules; surgery; paediatrics; gynaecology and obstetrics; radiology; neurology; psychiatry; ENT; ophthalmology; dermatology; clinical skills expansion. Supervised clinical contact increases progressively.
- **Years 5–6 (Advanced clinical training and rotations):** Structured rotations across all major clinical specialties in HGUA and affiliated network hospitals. Year 6 is the full clinical rotation year (equivalent to the clerkship model). TFG (Trabajo Fin de Grado) is completed in the final year.
- **Elective components:** Optional subjects and clinical electives are available within the programme structure.

ECTS distribution: Formación básica, Obligatorias, Prácticas externas clínicas, Optativas, TFG — full breakdown available at umh.es.

## Teaching Methodology

UMH Medicine uses a hybrid approach combining traditional lecture-based teaching with competency-based and problem-oriented learning methods. The physical co-location of the faculty with HGUA enables early and sustained clinical immersion that is a key differentiator from faculties with dedicated preclinical campuses separate from hospital environments. Clinical skills laboratories and simulation infrastructure are extensively used throughout the curriculum. Small-group tutorials, case-based learning, and structured ECOE-type clinical assessments are embedded across all years. The pedagogical model explicitly aligns with European standards under Directive 2005/36/EC.

## Clinical Training

UMH Medicine's primary clinical training environment is:

- **Hospital General Universitario de Alicante (HGUA):** The university's campus is integrated within this major tertiary referral hospital — a feature unique to UMH among Spanish public Medicine faculties. HGUA is managed under the Conselleria de Sanitat de la Generalitat Valenciana and serves as a major specialised care centre for the province of Alicante.

Additional clinical training sites include:
- Hospital Universitario del Vinalopó (Elche) — secondary affiliate
- Hospital de la Marina Baixa (Villajoyosa) — rotating placements
- Primary care centres (centros de salud) in the DGSP GVA network across the Alicante / Valencian health areas
- Psychiatric units and specialist outpatient clinics affiliated with GVA Salut

The campus-hospital integration model means students are in direct contact with active clinical areas from early years, with formal clinical rotations beginning progressively from year 3 and becoming full-time in year 6.

## International Recognition and Opportunities

UMH Medicine is registered in the Spanish RUCT and recognised under EU Directive 2005/36/EC, providing automatic EEA-wide professional recognition for graduates. The university participates in the Erasmus+ programme with bilateral agreements covering European universities across health sciences. UMH's innovation in medical education has attracted international attention and academic partnerships, particularly within the context of FISABIO (Fundación para el Fomento de la Investigación Sanitaria y Biomédica de la Comunitat Valenciana), which provides research infrastructure accessible to students and faculty. The SICUE domestic exchange programme is available for intra-Spanish mobility.

## Admission Model

UMH Medicine admission is governed exclusively by the **nota de admisión**, calculated as follows:

```
Nota de admisión = 0.6 × Nota media Bachillerato
                 + 0.4 × EVAU general phase score
                 + best 2 specific-phase subjects × ponderation coefficient
```

- **Maximum base score:** 10.0000
- **Maximum nota de admisión (with specific-phase bonus):** 14.0000
- **No proprietary exam, no interview, no English test**

**Specific-phase ponderation coefficients for UMH Medicine (ANNUAL_UPDATE_REQUIRED):**

| Subject | Coefficient |
|---|---|
| Biology (Biología) | 0.2 |
| Chemistry (Química) | 0.2 |
| Physics (Física) | 0.2 |
| Mathematics II | 0.1 |
| Other subjects | ANNUAL_UPDATE_REQUIRED |

Coefficients must be confirmed annually at umh.es before the PAU-CV registration period. The Comunitat Valenciana ponderation tables are published by the Consell de Coordinació Universitària / Acceso UV system.

**International students (PCE/UNED route):** International applicants use PCE/UNED or Credencial UE to construct a nota de admisión equivalent. The process mirrors the standard formula. The Valencian admissions system (AUPV / Conselleria d'Innovació, Universitats) processes applications from PCE holders in the same general quota as domestic students.

## Admission Process

### Spanish PAU (EVAU) students

1. Complete Bachillerato and sit the PAU-CV (Prueba de Acceso a la Universidad — Comunitat Valenciana), managed by the Conselleria d'Innovació, Universitats, Ciència i Societat Digital.
2. Sit specific-phase subjects: Biology (0.2) and Chemistry (0.2) are the highest-value subjects for Medicine at UMH. Physics (0.2) also carries the maximum coefficient and is strongly recommended as a third subject.
3. Calculate your nota de admisión using the standard formula and verify against UMH Medicine's nota de corte from the most recent cycle.
4. Apply for university places through the AUPV (Acceso a la Universitat Politècnica de València and Valencian universities) portal or the Valencian university admissions system in June/July.
5. Rankings are processed based on nota de admisión in descending order; places are allocated to candidates above the nota de corte.
6. The September extraordinaria round offers any remaining seats after the ordinaria allocation.
7. Confirm enrolment (matrícula) at UMH within the stated deadline.

### International PCE/UNED students

1. Register with UNED for PCE examinations (January–March for June sitting).
2. Select a minimum of five PCE subjects; prioritise Biology, Chemistry, and Physics for UMH Medicine.
3. Sit PCE exams (May/June ordinaria; September extraordinaria).
4. Obtain PCE certificate and calculate nota de admisión equivalent.
5. Apply via the Valencian admissions system presenting PCE certificate and secondary education documentation.
6. If nota de admisión equivalent meets the nota de corte, apply for enrolment at UMH.
7. Complete Spanish secondary diploma homologation if required.

## Admission Timeline

| Phase | Approximate dates | Notes |
|---|---|---|
| PAU-CV — ordinaria | June (ANNUAL_UPDATE_REQUIRED) | Set by Generalitat Valenciana |
| Valencian admissions application | Late June / July (ANNUAL_UPDATE_REQUIRED) | AUPV / Conselleria portal |
| Ordinaria assignment results | July (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| Enrolment confirmation | July–August (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| PAU-CV — extraordinaria | September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| Extraordinaria results / enrolment | September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| Academic year start | September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |
| PCE registration (UNED) | January–March (ANNUAL_UPDATE_REQUIRED) | For international applicants |
| PCE exams | May–June / September (ANNUAL_UPDATE_REQUIRED) | ANNUAL_UPDATE_REQUIRED |

## Admission Score Distribution

### Nota de corte history

| Intake year | Round | Nota de corte | Source |
|---|---|---|---|
| 2024-2025 | Convocatoria ordinaria | PENDING_CONFIRMATION | PENDING_CONFIRMATION |
| 2023-2024 | Convocatoria ordinaria | PENDING_CONFIRMATION | PENDING_CONFIRMATION |
| 2022-2023 | Convocatoria ordinaria | PENDING_CONFIRMATION | PENDING_CONFIRMATION |

**Trend analysis:** UMH Medicine is consistently among the higher-competitiveness public Medicine programmes in the Comunitat Valenciana, with nota de corte data typically available through the AUPV system or Conselleria portal. With approximately 120 seats, UMH is a smaller-cohort faculty, which historically produces higher nota de corte thresholds than larger faculties. The Valencian PAU applicant pool and the strong reputation of the campus-hospital integration model keep demand elevated. Candidates should obtain verified nota de corte history from aupv.es or the UMH admissions office before targeting this university. As a working estimate based on institutional profile and cohort size, UMH Medicine is expected to have a nota de corte in the range of 13.0–13.7 in recent cycles — PENDING_CONFIRMATION from primary sources.

**Practical implication:** UMH is a high-competitiveness target requiring a nota de admisión well above 13.0. Candidates below 13.0 should treat this as a reach option.

## Costs and Payment Structure

Public university fees at UMH are set by the Generalitat Valenciana by annual decree. The Comunitat Valenciana has historically maintained competitive public tuition rates.

| Fee component | Approximate amount | Notes |
|---|---|---|
| Annual tuition (tasas académicas) | ANNUAL_UPDATE_REQUIRED | Set by Generalitat Valenciana |
| Enrolment fee (secretaría) | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Academic services fee | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Total estimated annual cost | ~1,000–1,800 EUR | ANNUAL_UPDATE_REQUIRED — typical Valenciana range |
| Registration for PAU-CV (domestic) | ANNUAL_UPDATE_REQUIRED | Paid to Generalitat, not to UMH |
| PCE registration (international) | ANNUAL_UPDATE_REQUIRED | Paid to UNED |

Confirm the exact tuition figure via the UMH secretaría or the Generalitat Valenciana official fee tables before enrolment.

## Scholarships and Financial Aid

- **MEC Beca General:** The primary national scholarship for public university students. Awarded on academic performance and household income. Covers tuition and variable maintenance. Apply annually via the MEFP portal.
- **Becas Generalitat Valenciana:** The Valencian regional government offers complementary scholarships for Valencian residents and for students at Valencian public universities. Check the GVA portal annually.
- **UMH own grants:** UMH administers emergency grants and collaboration scholarships for enrolled students. Check umh.es for current offerings.
- **ERASMUS+ grants:** Available during mobility periods (typically years 4–5). Amounts vary by destination.
- **International students:** PCE/UNED applicants may technically qualify for MEC Beca General under residency and income conditions, but eligibility for international students is typically limited.

## Accommodation and Cost of Living

San Juan de Alicante is a small municipality adjacent to the city of Alicante. The campus is set within the HGUA hospital complex, which is well-connected to Alicante city by public transport.

| Category | Estimated monthly cost | Notes |
|---|---|---|
| University residence (if available) | ANNUAL_UPDATE_REQUIRED | Limited availability — enquire at umh.es |
| Private shared flat in Alicante | ~350–600 EUR/month | Most common option for students |
| Private studio in Alicante area | ~550–800 EUR/month | ANNUAL_UPDATE_REQUIRED |
| Food (self-catering + canteen) | ~200–350 EUR/month | University canteen available on campus |
| Transport (local bus / TRAM) | ~30–50 EUR/month | Good connections to Alicante city |
| Total monthly estimated budget | ~620–1,000 EUR | Excluding tuition |

Alicante city offers a wide range of student housing options within reasonable commuting distance of the campus. The Mediterranean climate and relatively low cost of living compared to Madrid or Barcelona are positive factors for budget planning.

## International Exchange and Mobility Programs

- **Erasmus+:** UMH has bilateral Erasmus+ agreements with European universities across health sciences. Exchanges typically occur in years 4–5.
- **SICUE:** Domestic exchange programme enabling students to spend one or two semesters at another Spanish Faculty of Medicine.
- **FISABIO partnerships:** UMH students can engage with the FISABIO research infrastructure and international research collaborations in the biomedical field.
- **International clinical electives:** The UMH International Office facilitates individual clinical rotation arrangements at partner institutions upon request.

## MIR Preparation and Professional Outcomes

UMH does not publish a disaggregated MIR pass rate at the faculty level. Graduates sit the national MIR examination alongside all other Spanish medical graduates. The competency-based curriculum and early clinical immersion model that characterises UMH Medicine are broadly considered advantageous for MIR preparation, as clinical reasoning skills are embedded earlier than in more lecture-heavy traditional curricula.

Professional pathways for UMH graduates:
- MIR specialist training (primary route)
- Academic and research medicine (FISABIO, UMH doctoral programmes)
- EU practice (automatic recognition under Directive 2005/36/EC)
- General practice via MIR Family Medicine

## Strategic Fit

### Good Fit For

- Candidates with a nota de admisión firmly above 13.0 (verify exact nota de corte annually) who want a clinical immersion model from the earliest years of study.
- Students attracted by the unique campus-hospital integration and early clinical contact at HGUA.
- Valencian students or students comfortable with the Alicante/Valencia region's Mediterranean environment and lifestyle.
- International PCE candidates with a nota de admisión equivalent above 13.0 seeking a competitive-entry public university at public tuition rates.
- Students interested in biomedical research via FISABIO and UMH's research groups.

### Less Suitable For

- Candidates whose nota de admisión is below 13.0 — UMH Medicine is a high-competitiveness programme with limited seats (approximately 120).
- Students who prefer a large, multi-campus university environment with more programme variety on the same campus.
- Candidates requiring English-medium instruction — no English track is available.
- Students who need guaranteed admission without sitting EVAU or PCE.

## Risks and Considerations

1. **Nota de corte data gap:** PENDING_CONFIRMATION data for the nota de corte in this file reflects the rate-limited research session. Students must verify the current nota de corte directly with UMH or through the AUPV system before planning their application strategy.
2. **Small cohort dynamics:** With approximately 120 seats, UMH Medicine produces high competition per seat. A small year-on-year shift in applicant quality can move the nota de corte significantly.
3. **Valencian regional applicant priority:** The Valencian admissions system may apply preferential quotas for PAU-CV students from the region. Out-of-region candidates should verify their effective competition status.
4. **Campus location:** The campus is in San Juan de Alicante, not in the city of Elche (which is where UMH's main institutional seat is located). Students should confirm the exact campus address and transportation options before committing.
5. **PCE documentation deadlines:** International PCE students applying to the Valencian system face multiple administrative steps across UNED and the Valencian Conselleria. Document submission deadlines must be tracked carefully.

## Important Notes

- The Faculty of Medicine is located on the Campus de San Juan de Alicante, adjacent to the Hospital General Universitario de Alicante — not on the Elche campus.
- Ponderation coefficients are published by UMH annually and must be confirmed at umh.es each autumn before registering for specific-phase EVAU subjects.
- The Valencian admissions system is managed by the Conselleria d'Innovació, Universitats, Ciència i Societat Digital (GVA) and processed through the AUPV or equivalent portal. Always verify the correct portal for the relevant cycle.
- No pre-admission deposit is required at UMH.

## Key Insight

UMH Medicine's defining feature — and its key competitive differentiator within Spain's public Medicine landscape — is the physical integration of the Faculty with HGUA. This produces a quality of clinical immersion that is structurally impossible to replicate at faculties with standalone preclinical campuses. The trade-off is a smaller seat count (~120), which drives the nota de corte higher than larger regional public faculties. For a candidate who can meet the nota de corte (expected to be above 13.0 in recent cycles), UMH represents one of Spain's strongest value propositions in public Medicine: high clinical quality, competitive research environment, Mediterranean location, and public tuition rates.

## Final Takeaway

UMH is a focused, clinically immersive public Medicine faculty with a distinctive campus-hospital integration model at HGUA. With approximately 120 seats, it is among the smaller public Medicine cohorts in Spain, producing a nota de corte in the high-competitiveness range. Tuition is set at public Valencian rates. No exam, no interview — admission is entirely nota de admisión based. Biology and Chemistry are the priority specific-phase subjects (both 0.2 coefficient). Candidates with a nota de admisión above 13.0 should seriously evaluate UMH as a high-quality, lower-cost alternative to private Medicine in Spain.

## Frequently Asked Questions

**Q: How is the nota de admisión calculated for UMH Medicine?**
A: Nota de admisión = 0.6 × Bachillerato average + 0.4 × EVAU general phase score + (up to 2 specific-phase subjects × coefficient). Base maximum: 10.0000. With specific-phase bonus: 14.0000.

**Q: What is the nota de corte for UMH Medicine?**
A: The nota de corte is PENDING_CONFIRMATION for recent cycles in this file — a temporary gap due to web access constraints during research. Verify the current and historical nota de corte at the AUPV portal (aupv.es) or the UMH admissions page (umh.es) before planning your application.

**Q: Which EVAU subjects are most valuable at UMH?**
A: Biology (0.2), Chemistry (0.2), and Physics (0.2) all carry the maximum coefficient. Prioritise Biology and Chemistry in the specific phase, with Physics as a strong third option. Coefficients are ANNUAL_UPDATE_REQUIRED.

**Q: Can international students apply via PCE/UNED?**
A: Yes. International students without a Spanish EVAU apply via PCE/UNED or Credencial UE. The nota de admisión equivalent is calculated using the same formula and compared against the nota de corte. PCE applicants compete in the general quota.

**Q: Where is the Medicine Faculty located?**
A: On the Campus de San Juan de Alicante, which is co-located with the Hospital General Universitario de Alicante (HGUA). This is in the municipality of San Juan de Alicante, approximately 10 km from Alicante city centre, not in Elche (where UMH's main administrative campus is located).

**Q: What are the tuition fees?**
A: Set annually by the Generalitat Valenciana. Broadly in the range of 1,000–1,800 EUR per year for Health Sciences programmes at Valencian public universities. Confirm the exact figure at umh.es or the GVA official fee tables before enrolment.

**Q: Is there an exam or interview?**
A: No. Admission is determined exclusively by the nota de admisión. There is no proprietary university entrance exam and no interview.

**Q: When do I apply?**
A: Applications are submitted through the Valencian admissions portal in late June / early July following the PAU-CV ordinaria results. A September window may open for remaining seats after the extraordinaria. International PCE students must register with UNED months in advance (typically January–March).
