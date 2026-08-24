---
id: uex

type: university
subtype: public

name: Universidad de Extremadura
short_name: UEX

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Badajoz
  region: Extremadura
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - high_competitiveness
  - strong_clinical_exposure

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
  seats: 135 # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION
  last_admitted_scores:
    - intake_year: 2024-2025
      round: convocatoria_ordinaria
      score: 13.728 # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: NULL
    - intake_year: 2023-2024
      round: convocatoria_ordinaria
      score: 13.678 # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: NULL
    - intake_year: 2022-2023
      round: convocatoria_ordinaria
      score: 13.620 # ANNUAL_UPDATE_REQUIRED
      score_type: nota_de_admision
      notes: NULL

international_profile:
  international_students_percentage: PENDING_CONFIRMATION
  international_nationalities: []

programs:
  - id: uex-medicina
    campus: Campus de Badajoz — Facultad de Medicina y Ciencias de la Salud
    modality: standard
    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - high_competitiveness
      - strong_clinical_exposure
    teaching_languages:
      - Spanish
    regional_language_possible: false
    regional_language: NULL
    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL
    seats: 135 # ANNUAL_UPDATE_REQUIRED
    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: 135 # ANNUAL_UPDATE_REQUIRED
      applicants_per_seat: PENDING_CONFIRMATION
      last_admitted_scores:
        - intake_year: 2024-2025
          round: convocatoria_ordinaria
          score: 13.728 # ANNUAL_UPDATE_REQUIRED
          score_type: nota_de_admision
          notes: NULL
        - intake_year: 2023-2024
          round: convocatoria_ordinaria
          score: 13.678 # ANNUAL_UPDATE_REQUIRED
          score_type: nota_de_admision
          notes: NULL
        - intake_year: 2022-2023
          round: convocatoria_ordinaria
          score: 13.620 # ANNUAL_UPDATE_REQUIRED
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
          score: 13.728 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: Servicio de Acceso y Gestión de Estudios de Grado — UEX / Junta de Extremadura
        - intake_year: 2023-2024
          score: 13.678 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: Servicio de Acceso y Gestión de Estudios de Grado — UEX / Junta de Extremadura
        - intake_year: 2022-2023
          score: 13.620 # ANNUAL_UPDATE_REQUIRED
          round: convocatoria_ordinaria
          source: Servicio de Acceso y Gestión de Estudios de Grado — UEX / Junta de Extremadura
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
              notes: Best 2 eligible subjects count. Each subject score multiplied by the ponderation coefficient (0.1 or 0.2). Maximum nota de admisión: 14.0000. Coefficients ANNUAL_UPDATE_REQUIRED.
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED
                Chemistry:      0.2 # ANNUAL_UPDATE_REQUIRED
                Physics:        0.1 # ANNUAL_UPDATE_REQUIRED
                Mathematics_II: 0.1 # ANNUAL_UPDATE_REQUIRED
                Drawing_II:     0.1 # ANNUAL_UPDATE_REQUIRED
                History_Art:    0.1 # ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---

# Universidad de Extremadura

## Overview

The Universidad de Extremadura (UEX) has operated its Facultad de Medicina y Ciencias de la Salud since October 1973, making it one of the region's founding academic institutions. The Grado en Medicina is delivered on the Badajoz campus — the sole campus offering this degree within UEX. Note that while UEX has a dual-campus structure (Badajoz and Cáceres), Medicine is offered exclusively in Badajoz.

Access to Medicine at UEX is determined by the nota de admisión, the standard Spanish public university formula combining Bachillerato grades and EVAU (Selectividad) performance. There is no proprietary entrance examination, no interview, and no minimum language requirement. Admissions are managed through the Junta de Extremadura's centralised preinscripción system.

The nota de corte for Medicine at UEX has been among the highest in Extremadura's public university system, consistently above 13.60, reflecting intense demand relative to available seats. The programme received ANECA institutional certification, and the curriculum is structured across 360 ECTS over six years, with full-year clinical rotations in Year 6.

## Quick Evaluation

- Admission model: nota de admisión (EVAU formula) — no proprietary exam, no interview
- Seats: approximately 135 per year (ANNUAL_UPDATE_REQUIRED)
- Nota de corte range (last 3 cycles): 13.620–13.728 out of 14.000
- Competitiveness level: very high
- Tuition: set by Junta de Extremadura (~1,000–1,500 EUR/year; ANNUAL_UPDATE_REQUIRED)
- Teaching language: Spanish
- Campus: Badajoz only (Medicine is not offered on the Cáceres campus)
- ANECA certification: confirmed
- EU Directive qualification: Yes
- International access: via PCE/UNED or Credencial UE

## Key Facts

| Feature | Detail |
|---|---|
| University | Universidad de Extremadura (UEX) |
| City | Badajoz, Extremadura |
| Degree | Grado en Medicina |
| Duration | 6 years |
| ECTS | 360 |
| Annual seats | ~135 (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2024-25 | 13.728 (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2023-24 | 13.678 (ANNUAL_UPDATE_REQUIRED) |
| Nota de corte 2022-23 | 13.620 (ANNUAL_UPDATE_REQUIRED) |
| Tuition (approx.) | ~1,000–1,500 EUR/year (ANNUAL_UPDATE_REQUIRED) |
| Teaching language | Spanish |
| Admission route | Nota de admisión (EVAU formula) |
| Proprietary exam | No |
| Interview | No |
| Campus for Medicine | Badajoz only |
| Admissions system | Servicio de Acceso UEX / Junta de Extremadura |

## Program Options

UEX offers a single Medicine programme — the Grado en Medicina — located exclusively on the Badajoz campus. There is no parallel programme on the Cáceres campus, no bilingual track, and no distance-learning option. Prospective students from Cáceres or other parts of Extremadura must relocate to Badajoz.

A new plan de estudios (Plan 0218) has been progressively implemented, replacing the prior Plan 0212 which entered extinction in 2025-26. Students entering from 2025-26 onward are enrolled in Plan 0218. The transition means that some course offerings listed under Plan 0218 are still in progressive rollout ("implantación progresiva") in Years 2–6.

## Program Structure

The Grado en Medicina at UEX is structured over 6 years (360 ECTS total):

| Credit type | ECTS |
|---|---|
| Formación básica | 96 |
| Obligatoria | 198 |
| Optativa | 6 |
| Prácticas externas | 54 |
| Trabajo Fin de Grado | 6 |
| **Total** | **360** |

Year 1 covers foundational biomedical sciences: Anatomy I and II, Biochemistry, Cytology and Histology, Medical Physics, Biostatistics, History of Medicine, Bioethics, Immunology, and Basic Physiology — all structured as formación básica subjects of 6 ECTS each.

Clinical rotations (Prácticas Externas, 54 ECTS) take place in Year 6, covering surgery, internal medicine, obstetrics and gynaecology, paediatrics, psychiatry, family medicine, and emergency medicine. The Trabajo Fin de Grado (TFG, 6 ECTS) is also completed in Year 6.

Optional subjects (6 ECTS) available from Year 1 Semester 2 include Informática Médica and Inglés para Ciencias de la Salud.

## Teaching Methodology

UEX follows the standard Spanish public medical school model: lecture-based theoretical instruction in the early years, progressively integrated with laboratory and practical components from Year 1. The plan de estudios emphasises basic science foundations (Anatomy, Physiology, Biochemistry, Histology) in the first two years before transitioning to clinical disciplines.

From Year 3 onward, clinical subjects such as Diagnóstico por Imagen, Farmacología, and Patología Quirúrgica bring students into contact with hospital environments. The final year (Year 6) is structured as a full-time supervised clinical rotation. Skills laboratories and simulation training are embedded within the Facultad's infrastructure, which includes dedicated laboratory and clinical practice spaces at the Badajoz campus.

Research foundations are introduced early through courses such as Bioestadística and Historia de la Medicina, Bioética y Deontología.

## Clinical Training

Clinical training at UEX is anchored in the Complejo Hospitalario Universitario de Badajoz (CHU Badajoz), which is the primary affiliated teaching hospital. The hospital complex serves as the main site for clinical specialities, surgery, obstetrics, paediatrics, and emergency training.

Additional clinical placements are conducted at:

- **Complejo Hospitalario Universitario de Badajoz (CHU Badajoz)** — primary teaching hospital; comprehensive tertiary and quaternary care
- **Primary care centres (Centros de Salud)** across the Badajoz health area — used during family medicine rotations in Year 6

The 54 ECTS of prácticas externas in Year 6 are distributed across the following clinical disciplines: surgery and specialties, internal medicine and specialties, obstetrics and gynaecology, paediatrics and paediatric surgery, psychiatry, family and community medicine/emergency, and an elective rotation in procedures/research groups.

## International Recognition and Opportunities

The Grado en Medicina at UEX is an official Spanish state degree regulated under European Medical Directive 2005/36/EC, ensuring automatic professional recognition across all EU member states.

UEX holds **ANECA Institutional Certification** for the Facultad de Medicina y Ciencias de la Salud, which validates the institution's internal quality assurance system. WFME accreditation status: PENDING_CONFIRMATION.

UEX participates in international mobility programmes. The Facultad de Medicina publishes Programas de Movilidad information for Medicine students. Medicine-specific Erasmus destinations should be confirmed directly with the Facultad for each intake year (ANNUAL_UPDATE_REQUIRED).

## Admission Model

Admission to Medicine at UEX is managed through the **Servicio de Acceso y Gestión de Estudios de Grado** (alumnado.unex.es), which coordinates preinscripción on behalf of the Junta de Extremadura.

**The nota de admisión formula:**

```
Nota de admisión = (0.6 × Nota media Bachillerato) + (0.4 × EVAU general phase grade)
                 + (best 2 specific-phase subjects × ponderation coefficient)
```

- Base score maximum: 10.0000 points
- Specific-phase bonus maximum: 4.0000 additional points
- Absolute maximum nota de admisión: 14.0000

**Subject ponderation coefficients at UEX for Medicine (ANNUAL_UPDATE_REQUIRED):**

| Subject | Coefficient |
|---|---|
| Biology (Biología) | 0.2 |
| Chemistry (Química) | 0.2 |
| Physics (Física) | 0.1 |
| Mathematics II | 0.1 |

As with all Spanish public universities, Biology and Chemistry are the highest-weighted subjects for Medicine at UEX. Candidates should sit both in the EVAU specific phase to maximise their nota de admisión.

**International students (PCE/UNED pathway):** International candidates who have not completed Spanish Bachillerato may access UEX via the PCE/UNED examinations, which generate a Credencial UNED equivalent to the nota de admisión. The same ponderation coefficients apply. EU-educated students may also use the Credencial UE pathway.

## Admission Process

### For Spanish EVAU (PAU) Candidates

1. Complete Bachillerato (any Spanish region) and sit the EVAU.
2. Sit the specific phase with Biology and Chemistry to maximise the nota de admisión.
3. Calculate your nota de admisión with UEX's ponderation coefficients.
4. Access the preinscripción portal (alumnado.unex.es) during the official application window (ANNUAL_UPDATE_REQUIRED) and submit ranked preferences.
5. Await provisional and definitive assignment results.
6. Confirm and formalise enrolment at the Facultad de Medicina y Ciencias de la Salud in Badajoz.

### For International Students (PCE/UNED Pathway)

1. Verify that your secondary qualification is eligible for PCE/UNED access.
2. Register with UNED and sit the PCE examinations (typically May–June — ANNUAL_UPDATE_REQUIRED).
3. Obtain the Credencial UNED, which converts PCE scores into a nota de admisión equivalent.
4. Apply through the UEX preinscripción portal with the Credencial UNED.
5. If admitted, arrange student visa (non-EU) and complete all required enrolment documentation.

## Admission Timeline

All dates are ANNUAL_UPDATE_REQUIRED and vary by academic year.

| Phase | Approximate timing |
|---|---|
| EVAU (ordinary call — Extremadura) | June (ANNUAL_UPDATE_REQUIRED) |
| EVAU (extraordinary call) | July (ANNUAL_UPDATE_REQUIRED) |
| Preinscripción window opens | Mid-June (ANNUAL_UPDATE_REQUIRED) |
| Provisional assignment | Late June / early July (ANNUAL_UPDATE_REQUIRED) |
| Definitive assignment | July (ANNUAL_UPDATE_REQUIRED) |
| Enrolment formalisation | July–September (ANNUAL_UPDATE_REQUIRED) |
| PCE/UNED examinations | May–June (ANNUAL_UPDATE_REQUIRED) |
| Academic year begins | September (ANNUAL_UPDATE_REQUIRED) |

## Admission Score Distribution

The nota de corte for Medicine at UEX has maintained an upward trajectory over the three recorded cycles:

| Intake year | Nota de corte | Round | Source |
|---|---|---|---|
| 2024-2025 | 13.728 | Convocatoria ordinaria | UEX Servicio de Acceso / Junta de Extremadura (ANNUAL_UPDATE_REQUIRED) |
| 2023-2024 | 13.678 | Convocatoria ordinaria | UEX Servicio de Acceso / Junta de Extremadura (ANNUAL_UPDATE_REQUIRED) |
| 2022-2023 | 13.620 | Convocatoria ordinaria | UEX Servicio de Acceso / Junta de Extremadura (ANNUAL_UPDATE_REQUIRED) |

**Strategic interpretation:**

The nota de corte has risen by approximately 0.108 points over three cycles, suggesting a stable upward pressure driven by demand that exceeds seat supply. At 13.728, UEX's Medicine threshold is slightly higher than UCA's and reflects Extremadura's relatively limited seat count for a region-wide applicant pool.

Despite having ~135 seats (a moderately sized cohort for a public programme), the concentration of applicants and the relatively small pool of universities in Extremadura creates a very high-pressure admission environment. Candidates from outside Extremadura may compete effectively via the general preinscripción process, but should be aware that regional demand is strong.

The extraordinary call's residual seat availability for Medicine is typically minimal — candidates should not strategise around September admission.

## Costs and Payment Structure

Tuition fees at UEX are set annually by the Junta de Extremadura. Rates are among the lowest in Spain for public universities.

| Cost concept | Extremadura resident | Non-resident / EU | Source |
|---|---|---|---|
| Annual tuition (approx.) | ~1,000–1,300 EUR (ANNUAL_UPDATE_REQUIRED) | ~1,300–1,500 EUR (ANNUAL_UPDATE_REQUIRED) | Junta de Extremadura |
| Enrolment and administrative fees | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | UEX Secretaría |
| Compulsory services | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | UEX |
| Student union fee | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | UEX |

Badajoz is a city with a low cost of living relative to the Spanish national average, making UEX one of the most affordable combinations of tuition and living costs for Medicine in Spain.

## Scholarships and Financial Aid

**Beca General MEC:**
All UEX students are eligible for the national Beca General from the Ministerio de Educación y Formación Profesional. It covers tuition and provides a living allowance subject to family income and academic performance conditions. Applications open annually (typically July — ANNUAL_UPDATE_REQUIRED) via the ministerial portal.

**Becas de la Junta de Extremadura:**
The regional government offers supplementary grants for mobility, housing, and academic excellence. Details are published annually on the Junta de Extremadura portal.

**UEX own grants:**
The university maintains its own programme of emergency grants and academic support. Availability is ANNUAL_UPDATE_REQUIRED.

**Erasmus+ mobility stipends:**
Students completing approved outgoing mobility placements may access Erasmus+ funding. Confirm Medicine-eligible destinations with the Facultad de Medicina.

## Accommodation and Cost of Living

Badajoz is a mid-sized city in western Extremadura, bordering Portugal, with one of the lowest costs of living among Spanish university cities.

| Cost concept | Estimated monthly range | Notes |
|---|---|---|
| University halls of residence (colegios mayores) | ANNUAL_UPDATE_REQUIRED | Limited capacity; early application advised |
| Private shared flat (piso compartido) | ~280–450 EUR/room (ANNUAL_UPDATE_REQUIRED) | Most common student option |
| Private studio | ~450–700 EUR (ANNUAL_UPDATE_REQUIRED) | |
| University canteen meals | ~3–5 EUR/meal (ANNUAL_UPDATE_REQUIRED) | |
| Monthly public transport | ANNUAL_UPDATE_REQUIRED | |
| Total estimated monthly living cost | ~600–950 EUR (ANNUAL_UPDATE_REQUIRED) | Highly variable by lifestyle |

The proximity to Portugal (Elvas border) and the relatively compact urban structure of Badajoz make the city manageable for students. Clinical rotations are concentrated at CHU Badajoz, which is accessible from most student accommodation areas.

## International Exchange and Mobility Programs

UEX participates in Erasmus+ and other international mobility programmes. The Facultad de Medicina publishes its Programas de Movilidad annually. Medicine-specific Erasmus partners must be confirmed with the Facultad each year (ANNUAL_UPDATE_REQUIRED), as not all university-wide agreements are available for Medicine.

The SENECA programme (Spanish national inter-university mobility) may also be available for domestic Spanish students seeking to study a semester at another Spanish public university.

Year 6's clinical rotation structure constrains outgoing international mobility to Years 3–5. Students with international mobility ambitions should plan accordingly.

## MIR Preparation and Professional Outcomes

All UEX Medicine graduates are eligible to sit the national **MIR (Médico Interno Residente)** examination, which is the required pathway to specialisation in Spain's public health system.

MIR pass rates specific to UEX graduates: PENDING_CONFIRMATION.

The CHU Badajoz provides a broad tertiary care clinical environment that prepares students for the clinical case-based reasoning required in the MIR. Extremadura's public hospital network, while smaller than those in major urban regions, covers the full range of medical and surgical specialities necessary for degree completion and MIR preparation.

Post-MIR, graduates may practise in Spain's Sistema Nacional de Salud, private clinics, or pursue research and academic careers.

## Strategic Fit

### Good Fit For

- Candidates with a nota de admisión consistently above 13.73 who want a cost-effective, ANECA-certified public Medicine programme.
- Students from Extremadura or Portugal who prefer proximity to home and one of the lowest living costs in Spain.
- International students via PCE/UNED who have optimised Biology and Chemistry and whose nota de admisión equivalent exceeds the UEX threshold.
- Candidates comfortable with Badajoz as a long-term study location (6 years) and with a Spanish-only curriculum.
- Students seeking a public programme with a stable, well-established clinical training structure.

### Less Suitable For

- Candidates whose nota de admisión falls below 13.60 — historical data suggests access is unlikely.
- Students who require a metropolitan or cosmopolitan city environment during their studies.
- Students who want a bilingual or English-medium option — UEX offers no bilingual Medicine track.
- Candidates who need to study Medicine in Cáceres specifically — the UEX Medicine degree is in Badajoz only.

## Risks and Considerations

**Nota de corte trajectory:** The nota de corte has risen by 0.108 points over three cycles. If this trend continues, candidates targeting UEX should plan for a 2025-26 threshold potentially above 13.75. This leaves minimal margin for candidates scoring in the 13.60–13.72 range.

**Plan de estudios transition:** UEX is progressively implementing Plan 0218, replacing the extinguished Plan 0212. Students entering in 2025-26 onward are on Plan 0218, which still has subjects listed as "not yet offered" in Years 2–6. This transition does not affect educational outcomes but means course structures may evolve during a student's degree.

**Single-campus limitation:** Medicine is available only in Badajoz. Students who anticipated studying in Cáceres must recalibrate. Relocation to Badajoz is mandatory.

**Extraordinary call seats:** Like all public Medicine programmes in Spain, available seats in the September extraordinary call may be very limited or exhausted after the ordinary call. Do not rely on this pathway.

**Regional admissions:** The preinscripción system managed by UEX/Junta de Extremadura has different administrative procedures from Andalucía's DUA or Cantabria's systems. International students must navigate the Extremadura-specific process.

## Important Notes

- Medicine at UEX is offered exclusively on the Badajoz campus (Avenida de Elvas s/n, Badajoz).
- Plan 0218 is being progressively implemented; students should verify which subjects are offered in their year of entry.
- All nota de corte figures and seats are ANNUAL_UPDATE_REQUIRED.
- Ponderation coefficients for the EVAU specific phase are set by the Junta de Extremadura annually.
- Contact: secretaria_medi@unex.es | +34 924 289 461 | medicina.unex.es

## Key Insight

UEX's Medicine programme in Badajoz combines very low tuition costs with a well-established clinical training structure built around one of Extremadura's primary teaching hospitals. However, the nota de corte has been rising and is among the highest in the region. The competitive barrier is real: at 13.728 in 2024-25, only candidates who have maximised both their Bachillerato record and EVAU specific-phase performance (particularly Biology and Chemistry at 0.2 each) have a realistic prospect of admission. The programme's particular advantage for international and EU students is the low total cost of studying (tuition + living expenses), which makes it one of the most affordable public Medicine options in Spain.

## Final Takeaway

The Grado en Medicina at the Universidad de Extremadura offers a publicly funded, ANECA-certified, EU-Directive-recognised six-year degree in one of Spain's most affordable university cities. The programme is delivered solely in Badajoz, with a structured clinical training network anchored at the CHU Badajoz. The admission threshold — consistently above 13.62 and trending upward — makes this programme accessible only to high-performing candidates. Students seeking cost-effectiveness combined with a stable public medical education framework will find UEX strategically compelling, provided their academic scores support it. International students via PCE/UNED should model their nota de admisión carefully and ensure they have sat Biology and Chemistry in the specific phase.

## Frequently Asked Questions

**How is the nota de admisión calculated at UEX?**
Nota de admisión = 0.6 × Bachillerato average + 0.4 × EVAU general phase grade + bonuses from up to 2 specific-phase subjects. At UEX, Biology and Chemistry each carry a 0.2 coefficient, enabling a maximum bonus of 4.0 points and a theoretical maximum of 14.0000.

**What is the nota de corte for Medicine at UEX?**
In 2024-25 it was 13.728 (convocatoria ordinaria). The three-year range is 13.620–13.728. This is ANNUAL_UPDATE_REQUIRED.

**Is Medicine available on both UEX campuses (Badajoz and Cáceres)?**
No. The Grado en Medicina is offered exclusively on the Badajoz campus. Cáceres hosts other UEX faculties but not Medicine.

**Can international students apply via PCE?**
Yes. PCE/UNED examinations generate a Credencial UNED that is equivalent to the nota de admisión and allows participation in the UEX preinscripción process under the same conditions as Spanish domestic candidates.

**What are the tuition fees?**
Set annually by the Junta de Extremadura. Approximate range: 1,000–1,500 EUR/year depending on residency status. Exact figures are ANNUAL_UPDATE_REQUIRED.

**When do I apply?**
Applications are submitted through the preinscripción portal (alumnado.unex.es) after the EVAU ordinary call in June. Exact window is ANNUAL_UPDATE_REQUIRED.

**What are the ponderation coefficients at UEX?**
Biology: 0.2 | Chemistry: 0.2 | Physics: 0.1 | Mathematics II: 0.1 (ANNUAL_UPDATE_REQUIRED).

**What hospital is used for clinical training?**
The primary teaching hospital is the Complejo Hospitalario Universitario de Badajoz (CHU Badajoz), supplemented by primary care centres in the Badajoz health area.

**Is there a bilingual track?**
No. The degree is delivered entirely in Spanish.

**What is the MIR?**
The MIR (Médico Interno Residente) is the national exam for access to medical specialisation in Spain's public health system. All UEX Medicine graduates are eligible to sit it. UEX-specific MIR pass rates are PENDING_CONFIRMATION.
