---
id: urjc

type: university
subtype: public

name: Universidad Rey Juan Carlos
short_name: URJC

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Alcorcón (Madrid)
  region: Comunidad de Madrid
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - medium_competitiveness
  - strong_clinical_exposure
  - newer_programme
  - madrid_metropolitan

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
  seats: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
    - intake_year: 2025-2026
      round: convocatoria_ordinaria
      score: 12.932 # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: Programme launched approximately 2020-21; limited historical series for a high-demand Madrid location
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
  - id: urjc-medicina
    campus: Campus de Alcorcón — Facultad de Ciencias de la Salud, Alcorcón (Madrid)
    modality: standard
    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - medium_competitiveness
      - newer_programme
      - madrid_metropolitan
    teaching_languages:
      - Spanish
    regional_language_possible: false
    regional_language: NULL
    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL
    seats: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
      applicants_per_seat: PENDING_CONFIRMATION
      last_admitted_scores:
        - intake_year: 2025-2026
          round: convocatoria_ordinaria
          score: 12.932 # ANNUAL_UPDATE_REQUIRED
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
          score: 12.932 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: notasdecorte.es / Comunidad de Madrid
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
              notes: Best 2 eligible subjects count. Each subject score multiplied by the university's ponderation coefficient (0.1 or 0.2). Maximum nota de admisión: 14.0000. Comunidad de Madrid ponderation table applies. Coefficients ANNUAL_UPDATE_REQUIRED.
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED — Comunidad de Madrid ponderation table for URJC Medicina
                Chemistry:      0.2 # ANNUAL_UPDATE_REQUIRED — Comunidad de Madrid ponderation table for URJC Medicina
                Physics:        0.1 # ANNUAL_UPDATE_REQUIRED — Comunidad de Madrid ponderation table for URJC Medicina
                Mathematics_II: 0.1 # ANNUAL_UPDATE_REQUIRED — Comunidad de Madrid ponderation table for URJC Medicina
                Drawing_II:     ANNUAL_UPDATE_REQUIRED
                History_Art:    ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---
# Universidad Rey Juan Carlos

## Overview

The Universidad Rey Juan Carlos (URJC) is a public university founded in 1996, based in the Comunidad de Madrid metropolitan area with campuses in Alcorcón, Móstoles, Fuenlabrada, Vicálvaro, and Aranjuez. URJC is one of the largest public universities in Spain, with over 50,000 students enrolled across its faculties. Its Grado en Medicina is delivered through the Facultad de Ciencias de la Salud at the Campus de Alcorcón, a health sciences campus in the southwest metropolitan area of Madrid.

URJC Medicine is a relatively recently established programme, launched approximately in 2020-21. Despite being newer than legacy medicine faculties, URJC benefits from its location in the Madrid metropolitan area, with access to an extensive network of university-affiliated hospitals managed by the Comunidad de Madrid health system. URJC holds affiliate hospital agreements with several large Madrid hospitals, providing students with broad clinical exposure across a major urban health system.

## Quick Evaluation

URJC Medicine is a **very high-competitiveness public programme** due to its Madrid location. The Comunidad de Madrid has historically been one of the most competitive regions in Spain for Medicine admissions (alongside Cataluña and the Basque Country), with nota de corte values typically in the 13.50–13.90 range at established Madrid universities (Complutense, Autónoma). As a newer programme at URJC within the same Madrid admissions pool, the nota de corte profile will be influenced by this regional dynamic.

The programme is delivered entirely in Spanish, is located within the metropolitan Madrid area (Alcorcón is 15 minutes from the city centre), and benefits from access to URJC's affiliated hospital network. For international students with strong Spanish, the Madrid location offers unparalleled professional and cultural resources alongside the university programme.

## Key Facts

| Attribute | Details |
|---|---|
| Full Name | Universidad Rey Juan Carlos — Grado en Medicina |
| Location | Alcorcón (Comunidad de Madrid), Spain |
| Type | Public university |
| Programme Status | Active — launched approximately 2020-21 |
| Duration | 6 years |
| Total ECTS | PENDING_CONFIRMATION (standard: 360 ECTS) |
| Seats | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Teaching Language | Spanish |
| Admission | Nota de admisión (EVAU/PAU-based) — no exam, no interview |
| Annual Tuition | PENDING_CONFIRMATION — regulated by Comunidad de Madrid (ANNUAL_UPDATE_REQUIRED) |
| Main Teaching Hospitals | URJC affiliated hospital network — Comunidad de Madrid |
| Nota de corte (2025-26) | 12.932 (notasdecorte.es / Comunidad de Madrid) — ANNUAL_UPDATE_REQUIRED |

## Program Options

URJC offers a single Grado en Medicina, a 6-year programme structured under Ministerial Order ECI/332/2008. Delivery is in Spanish. No bilingual or English-language track currently exists.

## Program Structure

The programme follows the national Medicine curriculum framework:

- **Years 1–2 (Basic Sciences):** Anatomy, Biochemistry, Cell Biology, Physiology, Histology, Genetics, Biostatistics. Laboratory-intensive with early integration of clinical reasoning foundations.
- **Years 3–4 (Pathological Sciences):** Pathology, Pharmacology, Microbiology, Immunology, Pathophysiology. Introduction to clinical examination and hospital observation.
- **Years 5–6 (Clinical Rotations):** Full supervised rotations across all major medical and surgical specialisms at URJC's affiliated hospitals. Trabajo Fin de Grado. Final external practicum.

Total: approximately 360 ECTS over 6 years (PENDING_CONFIRMATION).

The Facultad de Ciencias de la Salud at Alcorcón campus co-houses Medicine alongside Enfermería, Fisioterapia, Farmacia, Odontología, Psicología, and Terapia Ocupacional, creating an integrated health sciences environment.

## Teaching Methodology

URJC Medicine employs modern medical education methods including:

- **Case-Based and Problem-Based Learning:** Clinical case discussions integrated from early years.
- **Clinical simulation:** Skills laboratory and OSCE-format evaluations.
- **Hospital-integrated teaching:** Supervised clinical contact initiated in years 3–4, with full rotations in years 5–6 across the URJC hospital network.
- **Research integration:** Access to URJC's biomedical research groups, particularly through the Facultad de Ciencias de la Salud research units and affiliated hospital research departments.
- **Interprofessional education:** Proximity to other health science degrees (Nursing, Pharmacy, Physiotherapy) on the same campus enables interprofessional learning activities.

## Clinical Training

URJC's clinical training infrastructure is one of its defining assets. The university maintains formal university hospital affiliations with multiple Comunidad de Madrid hospitals, which is a critical differentiator relative to newer provincial programmes. Confirmed URJC affiliated hospitals include:

- **Hospital Universitario de Móstoles** — General acute hospital, southwest Madrid metropolitan area
- **Hospital Universitario Rey Juan Carlos (Móstoles)** — Modern acute hospital, opened 2012, part of Quirónsalud network under Comunidad de Madrid agreement
- **Hospital Universitario Infanta Elena (Valdemoro)** — Southern metro area
- **Hospital Universitario Infanta Cristina (Parla)** — Southern metro area, acute general hospital
- **Hospital Universitario Fundación Alcorcón (HUFA)** — Located adjacent to Alcorcón campus; a key primary clinical partner for URJC Medicine
- **Additional primary care centres** across the southwest Comunidad de Madrid area

The diversity and volume of the URJC hospital network provides students with exposure to varied patient demographics, clinical presentations, and institutional settings within a major metropolitan health system.

## International Recognition and Opportunities

The URJC Grado en Medicina is verified under the Spanish Ministry of Education framework and automatically recognised across EU member states.

URJC is a large public university with active **Erasmus+ partnerships** across Europe, active **SICUE** national exchange agreements, and participation in the **EULiST** (European Universities Linking Society and Technology) alliance, which extends partnerships across multiple European institutions.

The Madrid location provides exceptional access to:
- WHO, EU agency satellite offices, and international health organizations with Spanish operations
- International biomedical companies and research institutes (MSD, GSK, Roche, CNIC, CNIO)
- Global professional networks centred on Spain's capital

International students access URJC Medicine through PCE/UNED, Credencial UE, or direct homologation, subject to Comunidad de Madrid unified admissions rules coordinated by the district system (comunidad.madrid admissions portal).

## Admission Model

URJC Medicine uses the **standard Spanish public university admissions model** for the Comunidad de Madrid.

**Nota de admisión formula:**

```
Nota de admisión = 0.6 × Nota media Bachillerato + 0.4 × EVAU general phase
                  + up to 2 specific-phase subjects × ponderation coefficient
```

- Base maximum: **10.0000**
- Maximum with specific-phase bonus: **14.0000**

**Ponderation coefficients for URJC Medicine (Comunidad de Madrid):**

| Subject | Coefficient |
|---|---|
| Biology | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Chemistry | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Physics | 0.1 (ANNUAL_UPDATE_REQUIRED) |
| Mathematics II | 0.1 (ANNUAL_UPDATE_REQUIRED) |

The Comunidad de Madrid publishes its annual ponderation table through the regional admissions system. Candidates must verify the current-year table at comunidad.madrid before the EVAU cycle.

**PCE/UNED access:** International students may access URJC through PCE/UNED examinations, applying the same nota de admisión formula. Application is made through the Comunidad de Madrid unified admissions process.

## Admission Process

### For Spanish PAU (EVAU) Students

1. Sit the EVAU (PAU) in any Spanish region. The Comunidad de Madrid accepts all regional variants with appropriate coefficient adjustments.
2. Compute your nota de admisión: prioritise Biology and Chemistry as specific-phase subjects (coefficient 0.2).
3. In June–July, apply through the Comunidad de Madrid unified admissions portal, ranking URJC Medicine among your degree preferences.
4. Monitor assignment results. Accept your place within the stated deadline.
5. Enrol at the Facultad de Ciencias de la Salud, Campus de Alcorcón, for the September intake.

### For International Students (PCE/UNED Route)

1. Register for PCE/UNED examinations — deadlines typically February–March for May sittings.
2. Sit general-phase and specific-phase PCE subjects. Biology and Chemistry recommended for maximum bonus.
3. Obtain UNED certificate and apply via the Comunidad de Madrid admissions system.
4. Provide certified translations of academic records as required.
5. If admitted, complete enrolment at URJC, Campus de Alcorcón.

**Language note:** Instruction is fully in Spanish. International students must have strong Spanish proficiency (B2/C1 recommended). No formal Spanish test at admission, but clinical training requires effective communication in Spanish.

## Admission Timeline

| Event | Approximate Date |
|---|---|
| EVAU / PAU examination (ordinaria) | June (ANNUAL_UPDATE_REQUIRED) |
| Comunidad de Madrid application window | Late June (ANNUAL_UPDATE_REQUIRED) |
| Assignment results (ordinaria) | Mid July (ANNUAL_UPDATE_REQUIRED) |
| EVAU extraordinaria | September (ANNUAL_UPDATE_REQUIRED) |
| Extraordinaria assignments | September (ANNUAL_UPDATE_REQUIRED) |
| Academic year begins | Late September (ANNUAL_UPDATE_REQUIRED) |

All dates are ANNUAL_UPDATE_REQUIRED. Verify at urjc.es/estudiar-en-la-urjc/admision and at comunidad.madrid admissions portal.

## Admission Score Distribution

URJC Medicine is a newer programme launched approximately 2020-21, providing a limited but growing nota de corte history.

| Intake Year | Convocatoria | Nota de corte | Source |
|---|---|---|---|
| 2025-2026 | Ordinaria | 12.932 | notasdecorte.es / Comunidad de Madrid — ANNUAL_UPDATE_REQUIRED |
| 2023-2024 | Ordinaria | PENDING_CONFIRMATION | Comunidad de Madrid admissions |
| 2022-2023 | Ordinaria | PENDING_CONFIRMATION | Comunidad de Madrid admissions |

**Contextual interpretation:** The Comunidad de Madrid is among the most competitive regions for Medicine admissions in Spain. Established Madrid Medicine faculties (Complutense, Autónoma) have historically required nota de admisión of 13.50–13.90+. URJC, as a newer and somewhat less centrally located alternative within the same admissions district, may attract slightly different score distributions. However, given the general demand for Medicine in Madrid and the large URJC applicant pool, the nota de corte is expected to be in the very-high range.

**Trend note:** The programme's visibility in the Madrid market will likely drive increasing applicant numbers over successive cycles. Candidates should not assume that being a newer programme translates to meaningfully lower score requirements in such a competitive environment.

## Costs and Payment Structure

| Cost Item | Amount | Notes |
|---|---|---|
| Annual tuition (1st enrolment) | PENDING_CONFIRMATION EUR | Regulated by Comunidad de Madrid (ANNUAL_UPDATE_REQUIRED) |
| Per-credit rate (Health Sciences) | PENDING_CONFIRMATION EUR/credit | Madrid public university regulated rate. ANNUAL_UPDATE_REQUIRED |
| Repeat credit surcharge | ANNUAL_UPDATE_REQUIRED | Higher rate for failed subjects per Madrid decree |
| Administrative fees | PENDING_CONFIRMATION EUR | Enrolment, administrative services. ANNUAL_UPDATE_REQUIRED |

**Context:** The Comunidad de Madrid has historically maintained public university tuition rates comparable to other Spanish regions, regulated annually by the Decreto de Precios Públicos. Health Sciences credits carry a higher rate than Humanities but remain substantially below private university fees. Exact rates are available at urjc.es/estudiar-en-la-urjc/precios-publicos.

EU/EEA students pay the same regulated rate as Spanish national students.

## Scholarships and Financial Aid

- **Beca General MEC:** The primary national scholarship. Means-tested with academic performance threshold. Covers tuition and may include a maintenance stipend. Apply at becas.educacion.gob.es. Deadline typically September. ANNUAL_UPDATE_REQUIRED.
- **Becas de la Comunidad de Madrid:** Regional supplementary grants for Madrid residents. Details at comunidad.madrid.
- **URJC institutional grants:** URJC manages institutional scholarships and excellence awards. Details at urjc.es/estudiar-en-la-urjc/becas-ayudas-y-premios.
- **Erasmus+ mobility grants:** For exchange semester participants.
- **EULiST alliance opportunities:** As a member of the European Universities network EULiST, URJC offers additional mobility and research funding access points.
- **Private foundations:** Fundación "la Caixa", Fundación Botín, and Madrid-based foundations offer merit- and need-based awards for university students.

## Accommodation and Cost of Living

The Campus de Alcorcón is located in the southwest metropolitan area of Madrid, approximately 15–20 minutes by metro/suburban rail from Madrid city centre (Alcorcón is connected via Metro Line 12 — MetroSur). This offers students the advantage of being in Madrid while potentially accessing lower rents in the satellite municipality.

| Expense Category | Estimated Monthly Range |
|---|---|
| Shared flat (room, Alcorcón area) | 400–650 EUR |
| Shared flat (room, Madrid city) | 600–900 EUR |
| University accommodation (if available) | PENDING_CONFIRMATION EUR |
| Groceries | 150–250 EUR |
| Transport (Metro/Cercanías monthly pass) | 30–55 EUR |
| Total estimated monthly budget | 650–1,100 EUR |

All figures are approximate and ANNUAL_UPDATE_REQUIRED. Living costs in Madrid are substantially higher than in provincial cities like Burgos or Girona. Students benefit from Alcorcón's relatively lower rental costs compared to central Madrid neighbourhoods.

## International Exchange and Mobility Programs

URJC has one of the largest Erasmus+ exchange networks among Spanish universities, reflecting its size and established international partnerships. Key programmes include:

- **Erasmus+:** Extensive European partner network. Medicine-specific clinical exchange partnerships are PENDING_CONFIRMATION but the university infrastructure for managing exchanges is well established.
- **SICUE:** National exchange with other Spanish public universities.
- **EULiST Alliance:** European Universities programme (European Commission-funded) providing expanded mobility, joint research, and collaborative study opportunities across the alliance network.
- **International students office:** URJC's Oficina Internacional manages incoming and outgoing exchange students across all faculties.

## MIR Preparation and Professional Outcomes

URJC Medicine launched approximately in 2020-21. The first cohort will complete the 6-year programme around 2026-27. As of 2026, the first graduating cohort may be just entering or completing their degree.

- **MIR pass rate:** Not yet available for URJC Medicine specifically. First MIR outcomes expected approximately 2027.
- **Graduate employment outcomes:** Not yet available.

However, URJC graduates from other health science programmes (Nursing, Physiotherapy, Pharmacy) have a track record within the Madrid health system, providing some indication of the institution's professional integration.

The Madrid location gives Medicine graduates a strategic advantage for MIR preparation: the city has the highest concentration of MIR preparatory academies and study groups in Spain, including Academias Intensivas, CTO, Amir, and others.

## Strategic Fit

### Good Fit For

- Candidates with a **nota de admisión in the very-high range (13.50+)** seeking a public Medicine option in Madrid when the principal Madrid Medicine faculties (Complutense, Autónoma) are beyond reach or over-competitive.
- Students who specifically want to **live and train in the Madrid metropolitan area**, with access to the capital's cultural, professional, and personal resources.
- Students seeking a **fully Spanish-language programme** with no regional language requirement.
- Candidates who value access to a **diverse multi-hospital clinical network** within a major metropolitan health system.
- International students with strong Spanish who want to be based in **Spain's primary international hub** for professional networks and post-graduation options.

### Less Suitable For

- Candidates with nota de admisión significantly below the expected nota de corte range — the Madrid environment does not lower competition thresholds.
- Students seeking a **smaller, more personalised university experience** — URJC is a large institution with over 50,000 students and Medicine is one of many programmes at the health sciences campus.
- Candidates who need a **long-established programme** with a documented MIR pass rate history — the programme has not yet produced MIR-sitting graduates.
- Students on a very limited budget — the Madrid metropolitan area is significantly more expensive than most alternative university cities.

## Risks and Considerations

1. **Programme immaturity:** URJC Medicine is a recently launched programme. WFME accreditation status and MIR outcomes are not yet established. The degree is verified by ANECA under national standards, but international recognition pathways that depend on WFME accreditation should be verified.

2. **Very high nota de corte competition:** Madrid is Spain's most competitive Medicine market. Even as a newer programme, URJC is unlikely to provide a meaningful score advantage over Complutense or Autónoma, and candidates should not plan on it as a lower-threshold fallback.

3. **Seat number uncertainty:** The exact number of seats is PENDING_CONFIRMATION from official URJC sources. Candidates should verify directly at urjc.es for the current cycle.

4. **Large institution dynamics:** URJC's scale means that administrative processes, tutoring, and personalised support may be less intensive than at smaller regional universities.

5. **Cost of living pressure:** Living in the Madrid area is substantially more expensive than in Burgos, Girona, or most other Spanish university cities. Budget planning must account for higher rents and general living costs.

6. **Hospital network complexity:** While the breadth of affiliated hospitals is an asset, the complexity of coordinating placements across multiple hospitals and healthcare systems may create logistical challenges that smaller, more locally integrated programmes avoid.

## Important Notes

- The URJC Medicine programme is confirmed active at the Facultad de Ciencias de la Salud, Campus de Alcorcón (verified May 2026 from the URJC website faculty listing).
- The official programme page URL structure for URJC Medicine is at: urjc.es/universidad/facultades/facultad-de-ciencias-de-la-salud/596-medicina.
- Seats and tuition are ANNUAL_UPDATE_REQUIRED. Verify at urjc.es/estudiar-en-la-urjc/precios-publicos.
- The Comunidad de Madrid publishes nota de corte data through its unified admissions system at comunidad.madrid — ANNUAL_UPDATE_REQUIRED.

## Key Insight

URJC Medicine occupies a strategically interesting but challenging position: a newer public programme in Spain's most competitive Medicine market (Madrid). Its main differentiator is location — access to the Madrid metropolitan hospital network, the capital city's professional ecosystem, and Spain's richest MIR preparation environment. Candidates with nota de admisión in the very-high range who are committed to studying in Madrid and accept the absence of MIR track record data will find URJC a credible, well-resourced option. Candidates expecting a lower nota de corte relative to established Madrid alternatives should verify current data carefully before incorporating URJC into their strategy.

## Final Takeaway

URJC Medicine is a Madrid public university Medicine programme that combines a modern health sciences campus, multi-hospital clinical network, and metropolitan location with the uncertainties of a newly established programme. For candidates with very high nota de admisión scores who are set on Madrid and cannot access Complutense or Autónoma, URJC is a legitimate alternative. The programme's hospital network, interprofessional campus environment, and Madrid-based resources for MIR preparation are genuine assets. The primary risks are the absence of MIR outcome data and cost-of-living pressure.

## Frequently Asked Questions

**How is the nota de admisión calculated for URJC Medicine?**
Nota de admisión = 0.6 × Bachillerato average + 0.4 × EVAU general phase + bonus from up to 2 specific-phase subjects × ponderation coefficient. Maximum score: 14.0000. For URJC Medicine, Biology and Chemistry carry coefficient 0.2 per the Comunidad de Madrid ponderation table (ANNUAL_UPDATE_REQUIRED), making them the highest-value specific-phase subjects.

**What is the nota de corte for URJC Medicine?**
The nota de corte for URJC Medicine in 2025-2026 is 12.932 (source: notasdecorte.es / Comunidad de Madrid — ANNUAL_UPDATE_REQUIRED). Verify the official figure at the Comunidad de Madrid admissions portal (comunidad.madrid) each cycle.

**Can international students apply via PCE?**
Yes. International students sit PCE/UNED examinations and apply through the Comunidad de Madrid unified admissions system using the same nota de admisión formula. PCE registration deadlines (typically February–March) must be observed.

**What are the tuition fees?**
Tuition is set annually by the Comunidad de Madrid. The exact per-credit fee for Medicine at URJC is PENDING_CONFIRMATION and ANNUAL_UPDATE_REQUIRED. Check current prices at urjc.es/estudiar-en-la-urjc/precios-publicos.

**When do I apply?**
Applications go through the Comunidad de Madrid unified admissions portal in late June–early July after EVAU results. A second round follows in September. All dates ANNUAL_UPDATE_REQUIRED — verify at urjc.es and comunidad.madrid.

**What are the ponderation coefficients?**
For URJC Medicine (Comunidad de Madrid): Biology 0.2, Chemistry 0.2, Physics 0.1, Mathematics II 0.1 (ANNUAL_UPDATE_REQUIRED). These are set by the Comunidad de Madrid intercampus ponderation table annually. Verify current figures before the EVAU cycle.

**Is the programme in Spanish?**
Yes. URJC Medicine is fully in Spanish. There is no Catalan, Basque, or other regional language requirement. International students need strong Spanish proficiency.

**Where is the campus?**
The Facultad de Ciencias de la Salud is at the Campus de Alcorcón, Alcorcón, Comunidad de Madrid — approximately 15–20 minutes from central Madrid via Metro Line 12 (MetroSur) or Cercanías.

**Which hospitals are used for clinical training?**
URJC has affiliations with multiple Comunidad de Madrid hospitals, including Hospital Universitario Fundación Alcorcón (HUFA), Hospital Universitario Rey Juan Carlos (Móstoles), Hospital Universitario de Móstoles, Hospital Universitario Infanta Elena (Valdemoro), and Hospital Universitario Infanta Cristina (Parla), among others.

**Does URJC Medicine have MIR outcome data?**
Not yet. The first graduating cohort (approximately 2020-21 intake) will complete the degree around 2026-27. First MIR outcomes are expected approximately 2027. This is a key data point to monitor.
