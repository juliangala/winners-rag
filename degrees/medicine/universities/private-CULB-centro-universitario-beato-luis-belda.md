---
id: culb-medicine
name: "Grado en Medicina — Centro Universitario Beato Luis Belda (adscrito a Universidad San Pablo-CEU)"
short_name: CULB
valid_for_intake: "2026-2027"
last_updated: "2026-05-27"
source_urls:
  - "https://beatoluisbelda.es/grado-medicina-mallorca/"
  - "https://beatoluisbelda.es/admision/admision-grado-medicina/"
  - "https://beatoluisbelda.es/admision/precios/"
  - "https://beatoluisbelda.es/admision/becas-y-ayudas/"
  - "https://beatoluisbelda.es/grado-medicina-mallorca/plan-de-estudios-medicina/"
  - "https://beatoluisbelda.es/servicios/movilidad-internacional/"

location:
  city: Palma
  region: Illes Balears
  country: Spain
  campus_address: "Carrer d'Antonia Martínez Fiol, 1, Nort, 07010 Palma"
  admissions_office: "Passeig de Mallorca, 14, 07012 Palma"
  island_location: true

institution_type: centro_universitario_adscrito
parent_university: Universidad San Pablo-CEU
ruct_code: "07009151"
religious_affiliation: Catholic (Fundación CEU)
year_founded_medicine: 2026
inaugural_cohort: true

competitiveness:
  level: low
  notes: "Brand new center (inaugural 2026); admission for 2026-27 already closed after two rounds. No historical data. Selection does not use EBAU scores."

admissions_statistics:
  seats: 55
  annual_applications: NULL
  admission_rate: NULL
  typical_admitted_grade: NULL
  cutoff_score_last_year: NULL

admission:
  status_2026_27: CLOSED
  status_note: "Both convocatorias (February and April 2026) have concluded. Enrollment from June 2026; waitlist management July 2026."
  rolling_admissions:
    enabled: true
    rounds: 2
    round_1_date: "February 2026"
    round_2_date: "2026-04-18"
    estimated_end_date: ANNUAL_UPDATE_REQUIRED
  exam_required: true
  exam_modality: "presencial_or_online"
  interview_required: false

programs:
  - id: culb-medicine-palma
    campus: "Campus Palma — Centro Universitario Beato Luis Belda"
    modality: presencial
    teaching_languages:
      - Spanish
    ects: 360
    duration_years: 6
    seats: 55
    degree_conferred_by: "Universidad San Pablo-CEU"
    evaluation_model:
      overall_model_type: weighted_score
      selection_formula_note: "60% Y1 Bachillerato grades + 40% internal exam (Biology/Chemistry + English test). EBAU/PAU not counted in selection formula."
      components:
        - component: academic_record
          enabled: true
          role: weighted
          weight: 0.60
          grade_source: bachillerato_y1_only
          notes: "Only 1st year (1º) Bachillerato grades used. 2nd year Bachillerato and EBAU/PAU are excluded from the selection score, though a passed EBAU fase general is required for final enrollment."
        - component: academic_exam
          enabled: true
          role: weighted
          weight: PENDING_CONFIRMATION
          combined_with_english_weight: 0.40
          content: "Biology and Chemistry MCQ test"
          delivery_mode: presencial_or_online
          notes: "Internal exam; two convocatorias per year. Combined weight with English test = 40%. Individual split not published."
        - component: english_test
          enabled: true
          role: weighted
          weight: PENDING_CONFIRMATION
          combined_with_exam_weight: 0.40
          test_format: mcq_reading_comprehension
          delivery_mode: presencial_or_online
          notes: "Administered in the same session as the Biology/Chemistry test. Individual weight within the 40% not published."
        - component: interview
          enabled: false
        - component: psychometric_test
          enabled: false
        - component: complementary_points
          enabled: false
      exam_exemptions:
        enabled: true
        exempt_profiles:
          - "Graduates in Biology, Biomedicine, Biochemistry, Bioengineering, Microbiology, Medical Sciences, Pharmacy, Veterinary Medicine, Dentistry, Optics, Psychology, Podiatry, Human Nutrition and Dietetics, Biotechnology, Speech Therapy, Neuroscience, Nursing, or Physiotherapy"
          - "Medicine students requesting a transfer (traslado de expediente) from another Spanish university"
        selection_for_exempt: "Based solely on academic documentation submitted during the admissions process"

curriculum:
  total_ects: 360
  formacion_basica_ects: 90
  obligatorias_ects: 195
  optativas_ects: 6
  practicas_externas_ects: 61
  tfg_ects: 8
  clinical_rotations_by_year:
    - year: 3
      subject: "Prácticas Clínicas I"
      ects: 5
    - year: 4
      subject: "Prácticas Clínicas II"
      ects: 6
    - year: 5
      subject: "Prácticas Clínicas III"
      ects: 10
    - year: 6
      subject: "Prácticas Clínicas IV"
      ects: 40
  tfg_integration: "TFG linked to research groups from Year 4"
  humanities_subjects:
    - "Hombre y Mundo Moderno (Y1)"
    - "Humanidades Médicas (Y1)"
    - "Claves de Historia Contemporánea (Y2)"
    - "Doctrina Social de la Iglesia (Y2)"

clinical_training:
  primary_hospital: "Juaneda Hospitales (Mallorca)"
  additional_hospitals: []
  simulation_center: true
  anatomy_room: true
  research_labs: true

accreditation:
  aneca_verified: PENDING_CONFIRMATION
  aneca_note: "As of curriculum publication, the degree was still awaiting final administrative authorization ('una vez obtenidas las preceptivas autorizaciones administrativas'). Verify before enrollment."
  wfme_accredited: PENDING_CONFIRMATION
  wfme_note: "Universidad San Pablo-CEU holds WFME accreditation (since March 2024). CULB is an adscribed center; coverage for Medicine at CULB specifically should be confirmed directly."
  eu_recognized: true

pricing:
  currency: EUR
  reservation_fee: 2900
  reservation_refundable: false
  enrollment_fee_y1: 1500
  annual_teaching_fees_y1: 17955
  total_first_year: 22355
  fractionation: "Teaching fees fractionable in up to 9 monthly payments"
  estimated_annual_teaching_fee_subsequent_years: PENDING_CONFIRMATION
  estimated_total_6_years: PENDING_CONFIRMATION
  notes: "Price table published for Y1 only (60 ECTS). Subsequent years not published as of intake 2026-27."

scholarships:
  - name: "Becas CEU Merit"
    type: merit
    coverage: "Partial to full discount on teaching fees (enseñanzas)"
    full_coverage_requirement: "Bachillerato average ≥ 9.0"
    minimum_grade_to_apply: 8.0
    renewable: true
    notes: "Does not cover reservation, enrollment fee, or other administrative charges"
  - name: "Becas CEU Merit — Discapacidad"
    type: disability
    coverage: "100% or 65% of teaching fees"
    notes: "Complemented by AENE support service"
  - name: "Ayudas Benéfico-Docentes"
    type: need_based
    maximum_amount_eur: 7500
    application_deadline: ANNUAL_UPDATE_REQUIRED
    notes: "Need-based; includes families experiencing unemployment, income reduction, or single-parent households. Specific provision for large families (familias numerosas)."
  - name: "Becas CEU Merit — Deportistas"
    type: sports
    modalities: ["CEU Merit 100 (100% fee exemption)", "CEU Merit 65 (65% discount)", "Beca CEU Apoyo Deportistas (30% discount)"]
    target: "Elite athletes and promising young athletes"
  - name: "Préstamo Total Carrera — Banco Santander"
    type: loan
    maximum_amount_eur: 80000
    grace_period_years: 6
    notes: "Repayment deferred until after graduation"
  - name: "Préstamo Matrícula — Banco Santander"
    type: loan
    maximum_amount_eur_per_year: 12000
    repayment_months: 10
  - name: "Seguro de Continuidad de Estudios"
    type: insurance
    cost: free
    notes: "Covers tuition in case of death of the financially responsible parent or guardian"

international:
  erasmus_plus: true
  sicue: true
  ceu_global_campus: true
  ceu_global_campus_note: "Access to CEU San Pablo's international agreements with US universities (Bilingual International Programs, Online International Programs, Professional International Programs)"
  santander_open_academy: true
  specific_partner_universities: []

student_life:
  campus_location: "Palma de Mallorca (island)"
  island_note: "Mallorca is accessible by flight or ferry; mainland students must factor travel logistics and higher accommodation costs into planning"
  services:
    - "Servicio de Orientación Universitaria (SOU)"
    - "Carreras Profesionales (career services)"
    - "Biblioteca"
    - "Centro de Idiomas"
    - "Servicio de Deportes"
    - "Pastoral y Voluntariado"
    - "Acompañamiento (mentoring)"
    - "AENE — Atención a Estudiantes con Necesidades Educativas Especiales"
  hospitality_program: true
  hospitality_note: "CULB offers a 'Hospitality' service to assist students relocating to Mallorca"

contact:
  phone: "+34 871 080 280"
  whatsapp: "+34 911 650 144"
  admissions_portal: "https://admision.beatoluisbelda.es/"
  website: "https://beatoluisbelda.es"

tags:
  - private_medicine
  - spain
  - balearic_islands
  - mallorca
  - ceu_network
  - adscribed_center
  - inaugural_cohort
  - no_ebau_selection
  - rolling_admissions
  - small_class
---

# Centro Universitario Beato Luis Belda — Grado en Medicina (CULB)

## Overview

Centro Universitario Beato Luis Belda (CULB) is the first and only higher education institution offering a Medicine degree in the Balearic Islands. Located in Palma, Mallorca, it is a private centro universitario adscribed to Universidad San Pablo-CEU — one of the largest Catholic university networks in Spain. The degree is conferred by CEU San Pablo, not by CULB itself.

The inaugural Medicine cohort begins in September 2026, making CULB the newest Medicine program in Spain at the time of writing. The center offers 55 seats per year — the smallest class size of any Medicine program in the country — which is both a pedagogical choice (small-group, personalized teaching) and a structural constraint of a brand new institution building its academic and clinical infrastructure.

The admissions model is distinctive in the Spanish private Medicine landscape: selection is based 60% on 1st year Bachillerato grades and 40% on an internal exam (Biology/Chemistry MCQ + English test). EBAU/PAU scores do not count toward the selection score. This makes CULB one of the few private Medicine schools in Spain where the national university entrance exam is irrelevant to the competitive selection formula — a meaningful access pathway for students with strong academic records who underperformed in the EvAU.

---

## Quick Evaluation

| Dimension | Assessment |
|---|---|
| Competitive pressure | Very low (new center; no historical cut-off data; rolling process) |
| Selection model | Transparent, published formula: 60% Y1 Bachillerato + 40% internal exam |
| EBAU relevance | None for selection; required only to certify legal access to university |
| Clinical training | Juaneda Hospitales as primary partner (established private hospital group in Mallorca) |
| Accreditation | Adscribed to CEU San Pablo (WFME-accredited since 2024); CULB-specific coverage PENDING_CONFIRMATION |
| Track record | Zero — inaugural cohort; no graduates, no MIR data, no alumni |
| Location factor | Island — significant logistical and cost premium for mainland Spain students |
| Price | 17,955 EUR/year in teaching fees (Y1); 22,355 EUR total Y1 including reservation and enrollment |
| Class size | 55 seats — smallest in Spain |
| Scholarships | Merit (up to 100%), need-based (up to 7,500 EUR), sports, disability |

---

## Key Facts

- **Full name:** Grado en Medicina — Centro Universitario Beato Luis Belda
- **Short name:** CULB
- **Parent university:** Universidad San Pablo-CEU (degree conferred by CEU San Pablo)
- **RUCT code:** 07009151
- **Location:** Palma, Illes Balears (Mallorca, Spain)
- **Campus:** Carrer d'Antonia Martínez Fiol, 1 (main academic campus); Passeig de Mallorca, 14 (admissions office)
- **Degree:** Grado en Medicina (360 ECTS, 6 years)
- **Teaching language:** Spanish
- **Seats per year:** 55
- **Inaugural cohort:** September 2026
- **Admission 2026-27 status:** CLOSED (both convocatorias concluded April 2026)
- **Clinical partner:** Juaneda Hospitales (Mallorca)
- **Religious affiliation:** Catholic (Fundación CEU Luis Belda)
- **Contact:** +34 871 080 280 | [admision.beatoluisbelda.es](https://admision.beatoluisbelda.es/)

---

## Program Options

CULB currently offers a single Medicine program:

**Grado en Medicina — Palma (standard track)**
- Campus: Palma, Illes Balears
- Duration: 6 years (360 ECTS)
- Modality: In-person (presencial)
- Language: Spanish
- Seats: 55
- Degree conferred by: Universidad San Pablo-CEU

There is no bilingual, online, or satellite campus option. The program is offered exclusively in Spanish at a single campus in Palma.

---

## Program Structure

The curriculum follows the standard Spanish Medicine degree structure mandated by the Ministerio de Universidades, with a CEU-specific pedagogical overlay emphasizing humanistic formation and research integration.

**Credit distribution:**

| Category | ECTS |
|---|---|
| Formación Básica | 90 |
| Obligatorias | 195 |
| Optativas | 6 |
| Prácticas Externas | 61 |
| Trabajo Fin de Grado | 8 |
| **Total** | **360** |

**Year-by-year overview:**

*Year 1:* Core biomedical foundations — Cell Biology, General Biochemistry, Metabolic Biochemistry, General Physiology, Histology, Embryology, Medical Physics, General Anatomy, plus two CEU humanities subjects (Hombre y Mundo Moderno; Humanidades Médicas) and Medicina Integrada I.

*Year 2:* Systems anatomy and physiology, Molecular Biology, Genetics, Immunology, Psychology, plus CEU-specific subjects (Doctrina Social de la Iglesia; Claves de Historia Contemporánea) and Medicina Integrada II.

*Year 3:* Pathological Anatomy, Surgery and Anesthesia, Basic Pharmacology, Pathophysiology and Semiology, Microbiology and Parasitology, Radiology, Nutrition, Digital Health, Family Medicine, and first clinical rotation (Prácticas Clínicas I, 5 ECTS).

*Year 4:* Core clinical subjects — Obstetrics and Gynecology, Ophthalmology, ENT, Geriatrics and Palliative Care, Preventive Medicine, Research Methodology I, plus three Medical-Surgical Pathology blocks and clinical rotation II (6 ECTS).

*Year 5:* Dermatology, Clinical Pharmacology, Research Methodology II, five additional Medical-Surgical Pathology blocks, Pediatrics, Psychiatry, Rehabilitation, and clinical rotation III (10 ECTS).

*Year 6:* Legal and Forensic Medicine, Medical-Surgical Pathology VII, the major clinical rotation (Prácticas Clínicas IV, 40 ECTS), and the TFG (8 ECTS).

**Optativas (6 ECTS total — choose from 14 options):** Bases of Health Economics, Bases of Medical Optics, Legal Bases of Healthcare, Bioethics, Clinical Ultrasound, Clinical Genetics, Great Books, Modern Language (6 ECTS), Introduction to Experimental Medicine, Introduction to Christianity, Occupational Medicine, Medicine and Artificial Intelligence, Medicine and Humanism, Advanced Therapies.

The TFG is integrated into research groups from Year 4, meaning students begin their research trajectory in the second half of the degree rather than treating it as a final-year standalone project.

---

## Teaching Methodology

CULB applies the CEU San Pablo pedagogical model, adapted for a small-cohort setting:

**Small-group learning:** With 55 students per year, group sizes in seminars, clinical simulations, and lab sessions are significantly smaller than the 100–200 seat cohorts typical of other Spanish private Medicine schools. This is the most structurally distinguishing pedagogical feature.

**CEU humanist formation:** The curriculum includes several compulsory humanities and social science subjects that are part of CEU's institutional identity (Humanidades Médicas, Doctrina Social de la Iglesia, Hombre y Mundo Moderno). These are non-negotiable for all students regardless of personal affiliation.

**"Medicina Integrada" thread:** Three subjects labeled Medicina Integrada (I, II, III — 3 ECTS each across Years 1–3) serve as integrative modules connecting basic sciences with clinical reasoning progressively.

**Research integration:** TFG and research group participation begin in Year 4, earlier than many programs where research is concentrated in Year 6.

**Simulation and labs:** The center has a dedicated simulation center, anatomy room, research laboratories, and clinical practice areas on campus.

**Digital health:** Salud Digital is a standalone subject in Year 3 — a curriculum element reflecting the CEU network's push toward technology integration in clinical education.

---

## Clinical Training

Clinical training is structured across Years 3–6, with a total of 61 ECTS in external clinical placements:

| Year | Subject | ECTS |
|---|---|---|
| 3 | Prácticas Clínicas I | 5 |
| 4 | Prácticas Clínicas II | 6 |
| 5 | Prácticas Clínicas III | 10 |
| 6 | Prácticas Clínicas IV | 40 |

**Primary clinical partner: Juaneda Hospitales**

Juaneda Hospitales is a well-established private hospital group operating in Mallorca. It is the primary (and, as far as publicly available information shows, only confirmed) clinical training partner for CULB Medicine students. The partnership is specifically mentioned in the institution's own navigation structure and promotional materials.

The absence of public information about agreements with any public hospital on the island (Hospital Universitari Son Espases, Hospital de Manacor, etc.) is notable. As a new institution, the full scope of the clinical network is likely still being developed.

For context: Juaneda Hospitales operates several facilities in Palma (Hospital Juaneda Palma, Clínica Juaneda, and the Juaneda Inca facility), providing a range of clinical specialties but not the breadth and case volume of a large public teaching hospital. Students should understand that the clinical experience may differ structurally from what students at CEU San Pablo's Madrid campus receive through Hospital Universitario Moncloa or other partners.

**Important:** No information is available on international clinical rotation agreements specific to the Medicine program at CULB.

---

## International Recognition and Opportunities

**Degree recognition:**
The degree is conferred by Universidad San Pablo-CEU, which holds WFME (World Federation for Medical Education) accreditation since March 2024. However, CULB itself is an adscribed center, and whether this WFME coverage explicitly extends to Medicine degrees awarded through CULB-based training should be confirmed directly with the institution before enrollment.

**EU recognition:** Degrees conferred by CEU San Pablo are recognized within the EU under the Directive 2005/36/EC professional qualification framework. This enables graduates to practice medicine in other EU member states following national homologation procedures.

**Administrative authorization pending:** As of the time the curriculum was published on the CULB website, the degree was explicitly stated to be contingent on "las preceptivas autorizaciones administrativas conforme a la normativa universitaria aplicable." Prospective students must confirm that full ANECA/ministerial authorization has been obtained before committing.

---

## Admission Model

The CULB Medicine admission model is among the most transparent in Spain for private university Medicine:

**Selection formula:**

| Component | Weight |
|---|---|
| 1st year (1º) Bachillerato average grade | 60% |
| Internal exam (Biology + Chemistry MCQ + English test) | 40% |
| EBAU/PAU | Not counted in selection formula |

**Key characteristics:**

1. **EBAU exclusion from scoring:** The national university entrance exam is explicitly excluded from the selection formula. It is required only to certify legal access to the university after being offered a place — not to compete for it. This is structurally identical to CULB's sister CEU campuses in other cities (Blanquerna uses a comparable model).

2. **1st year Bachillerato only:** The academic record component uses only 1st year Bachillerato grades — not the final 2nd year or the blended average. Students who performed best in Year 1 and less strongly in Year 2 are effectively advantaged.

3. **Two-part internal exam:**
   - *Prueba específica:* MCQ test on Biology and Chemistry, assessing foundational knowledge for Medicine studies.
   - *Prueba de Inglés:* Language comprehension and level assessment.
   - Both parts are taken in the same exam session.
   - The exam can be taken online or in-person.
   - The individual weight split between the specific exam and the English test within the 40% component is not publicly disclosed.

4. **Two convocatorias per academic year:** Candidates can sit the exam in one or both rounds (February and April). If admitted in a lower-preference track and then pass the second sitting, amounts paid can be transferred.

5. **Exam exemptions:** A specific set of candidates is exempt from the internal exam entirely. Exempt profiles include graduates in a range of bioscience degrees (Biology, Biomedicine, Biochemistry, Nursing, Physiotherapy, etc.) and Medicine students transferring from another Spanish university. Exempt candidates are evaluated solely on their submitted academic documentation.

6. **Waitlist:** Enrollment begins June 2026; waitlist management occurs in July 2026.

---

## Admission Process

The admission process is managed through CULB's admissions portal ([admision.beatoluisbelda.es](https://admision.beatoluisbelda.es/)) and consists of five sequential steps:

**Step 1 — Application:** Complete the online application form. This creates a personal account on the Portal del Futuro Alumno, which tracks the entire process.

**Step 2 — Document submission and exam preparation:** Depending on access pathway, the portal specifies required documentation. Non-exempt candidates prepare for and sit the internal exam (Biology/Chemistry + English) in one of the two convocatorias.

**Step 3 — Evaluation and scoring:** For candidates who sit the exam, scores are calculated as 60% Bachillerato Y1 + 40% exam. For exempt candidates, scoring is based on academic documentation alone.

**Step 4 — Reservation:** Candidates offered a place have five days to pay the reservation deposit of 2,900 EUR (by card or bank transfer via the portal). The deposit is non-refundable under all circumstances.

**Step 5 — Enrollment:** Enrollment is formalized from June 2026 onward, after the candidate presents proof of having passed the EBAU fase general (convocatoria ordinaria, June) and received final administrative admission. Candidates who fail to submit EBAU results by the specified deadline (approximately July 6, 2026) are considered to have voluntarily relinquished their place with no refund.

**Vías de acceso:**
- Bachillerato + PAU/EBAU (standard route — exam required)
- Ciclo Formativo de Grado Superior (exam required)
- University graduate — bioscience degrees listed above (exam exempt)
- University graduate — other degrees (exam required)
- Medicine transfer from another Spanish university (exam exempt)

---

## Admission Timeline

Dates below reflect the 2026-27 intake. Both rounds are closed as of the publication of this file. Dates for the 2027-28 intake are not yet published.

| Milestone | Date |
|---|---|
| Application portal opens | ANNUAL_UPDATE_REQUIRED |
| Round 1 exam | February 2026 |
| Round 2 exam | April 18, 2026 |
| Admission process closed | April 12, 2026 (confirmed) |
| Enrollment period opens | June 2026 |
| EBAU results submission deadline | ~July 6, 2026 (indicative) |
| Waitlist management | July 2026 |
| Academic year begins | September 2026 |

**Status note:** The 2026-27 admission process is fully closed. No new applications for Medicine at CULB are possible for 2026-27. Students interested in 2027-28 should contact the admissions office directly to receive notification when the next cycle opens.

---

## Admission Score Distribution

No historical data is available. CULB is an inaugural program. No published cut-off scores, no admitted cohort grade distributions, and no application volume data exist for any prior year.

The theoretical minimum competitive profile — based solely on the published formula — would be a candidate with a strong 1st year Bachillerato average (since it counts for 60%) who also passes the Biology/Chemistry and English components of the internal exam. Because both the exam and the Bachillerato grades are specific to each candidate rather than benchmarked externally (like the PAU), there is no publicly available reference point.

For context: given the 55-seat capacity, the island location, and the institution's complete lack of track record, competitive pressure is expected to be significantly lower than at established private Medicine schools with decades of reputation.

---

## Costs and Payment Structure

**Year 1 cost breakdown:**

| Item | Amount |
|---|---|
| Reservation deposit (cuota de reserva) | 2,900 EUR |
| Enrollment fee (matrícula) | 1,500 EUR |
| Teaching fees — Year 1 (60 ECTS) | 17,955 EUR |
| **Total Year 1** | **22,355 EUR** |

**Payment structure:**
- Reservation: paid within 5 days of admission offer, by card or bank transfer. Non-refundable.
- Enrollment fee: paid when formalizing enrollment after EBAU results.
- Teaching fees: fractionable in up to 9 monthly installments.

**Multi-year cost:**
Published prices cover Year 1 only (60 ECTS = 17,955 EUR in teaching fees). Costs for Years 2–6 are not published as of the 2026-27 cycle. Based on the Year 1 ECTS unit cost (17,955 ÷ 60 = 299.25 EUR/ECTS) and the degree's total 360 ECTS, a rough estimate for total teaching fees across six years would be approximately 107,730 EUR, though this is not confirmed by CULB. Total estimated cost including enrollment fees for all years is PENDING_CONFIRMATION.

**Important:** CULB's prices are exclusive of living costs in Mallorca. Accommodation, transport, and living expenses in Palma add considerably to the total financial commitment — see Accommodation section below.

---

## Scholarships and Financial Aid

**CEU Merit Scholarships** (merit-based):
- Eligibility: Final Bachillerato or equivalent average ≥ 8.0 (out of 10), plus passing the admissions process.
- Benefit: Partial to full discount on teaching fees. Full coverage (100%) available for candidates with Bachillerato average ≥ 9.0.
- Renewable: Yes, subject to maintaining academic performance, full-time enrollment, and institutional participation requirements.
- Does not cover: reservation deposit, enrollment fee, or other administrative charges.

**CEU Merit Discapacidad** (disability):
- Modalities: Merit 100 (full fee exemption) and Merit 65 (65% discount).
- Complemented by AENE support service for academic and personal accompaniment.

**Ayudas Benéfico-Docentes** (need-based):
- For students with documented socioeconomic or family hardship (unemployment, income drop, single-parent households, etc.).
- Maximum award: 7,500 EUR per year.
- Requires: enrollment in at least 60 ECTS; satisfactory academic performance; annual re-application.
- Special provision for large families (familias numerosas) with fixed amounts.
- Application deadline: annual (deadline for 2026-27 was May 28, 2026).

**CEU Merit Deportistas** (sports excellence):
- Three tiers: CEU Merit 100 (100% fee exemption), CEU Merit 65 (65% discount), Beca CEU Apoyo Deportistas (30% discount).
- Target: elite athletes and young athletes with demonstrable sports credentials.
- Requires maintaining both academic and sports standards year-on-year.

**Banco Santander financing:**
- *Préstamo Total Carrera:* Up to 80,000 EUR; up to 6-year carencia (no repayment until after graduation).
- *Préstamo Matrícula:* Up to 12,000 EUR/year; repayable in up to 10 months.

**Seguro de Continuidad de Estudios:**
Provided free of charge to all enrolled students. Covers tuition continuation in the event of death of the parent or guardian responsible for fee payment.

---

## Accommodation and Cost of Living

CULB does not operate a student residence. Students must arrange private accommodation in Palma.

**Palma accommodation context:**
Palma de Mallorca has experienced significant real estate price inflation in recent years due to tourism demand and limited housing supply. Rental costs for students are substantially higher than in most Spanish mainland university cities.

- Typical monthly rent for a room in a shared apartment: approximately 600–900 EUR depending on location and season.
- Studio or single apartment: 900–1,400 EUR/month in Palma.
- Summer months may push prices higher due to tourist demand, though academic year rentals follow different dynamics.

**CULB Hospitality program:**
The institution offers a "Hospitality" service specifically to assist incoming students — particularly those relocating from mainland Spain — with the logistics of settling in Mallorca. This includes orientation support and connects students with accommodation resources.

**Island logistics:**
Students traveling home to mainland Spain must account for flight or ferry costs. Flights from Palma to Madrid/Barcelona typically range from 30 to 150 EUR one-way depending on timing. For students from Morocco, Latin America, or France, Palma is a secondary airport with fewer direct international connections than Madrid or Barcelona.

**Estimated annual student budget (living costs only):** 12,000–18,000 EUR depending on accommodation choice, lifestyle, and travel frequency. This is in addition to tuition fees.

---

## International Exchange and Mobility Programs

**Erasmus+ (academic mobility):**
CULB participates in Erasmus+, enabling students to study a portion of their degree at a partner European university. Requirements include EU citizenship or residency permit, enrollment in a CULB degree, meeting annual mobility call requirements, and demonstrating the language level required by the destination institution.

**Erasmus+ (professional placements):**
Students and recent graduates can access Erasmus+ work placement opportunities across Europe (2–12 months, full-time).

**SICUE (national mobility):**
Participation in the Sistema de Intercambio entre Centros Universitarios de España. Allows credit-recognized study at other Spanish universities. No separate financial grant; academic recognition guaranteed.

**CEU Global Campus:**
As an adscribed center of CEU San Pablo, CULB students can access international programs negotiated by CEU San Pablo's global network. Available tracks include:
- Bilingual International Programs (dual-language study abroad)
- Online International Programs (distance-learning courses with partner universities)
- Professional International Programs (postgraduate certificates with US universities)

Students should confirm with CULB which specific CEU Global Campus programs are open to Medicine students on the CULB campus, as some programs may be restricted to CEU San Pablo's main Madrid campuses.

**Santander Open Academy:**
Access to Banco Santander's scholarship and mobility program offering grants for study abroad, research placements, and international internships.

**Named partner universities:** No specific international university partnerships have been published for CULB Medicine as of this filing.

---

## MIR Preparation and Professional Outcomes

No data is available. CULB's inaugural Medicine cohort begins in September 2026. The first graduates will sit the MIR examination no earlier than 2032 (assuming a 6-year degree with 1 gap year preparation typical of Medicine graduates in Spain).

**What is known:**
- CEU San Pablo's Madrid Medicine campus (Facultad de Medicina y Cirugía, CEU San Pablo) has an established MIR track record as one of Spain's oldest private Medicine schools. CULB students benefit from academic alignment with the same degree conferring institution and its pedagogical methodology.
- CEU San Pablo's MIR preparation resources may be available to CULB students, but this has not been confirmed in any published materials for the Palma campus.

**Professional outcomes:**
- Degree conferred by CEU San Pablo, an EU-recognized institution. Full EU professional recognition applies.
- Clinical rotations at Juaneda Hospitales provide exposure to private hospital medicine — a specific clinical context that may differ from the public hospital experience that forms the basis of the MIR exam's clinical scenarios.

---

## Strategic Fit

### Good Fit For

**Students with strong 1st year Bachillerato grades but weak EBAU results.** The selection formula gives 60% weight to Y1 Bachillerato and zero weight to EBAU. A student with a 9.0 average in 1º Bachillerato and a 10.0 in the internal exam achieves a maximum competitive score regardless of their EvAU performance.

**Students from the Balearic Islands who want to study Medicine at home.** CULB is the only Medicine program in the archipelago. For students with family, social, or financial ties to Mallorca, this eliminates the need for relocation to the mainland.

**Students with bioscience degrees seeking a second entry into Medicine.** Those with degrees in Biology, Pharmacy, Nursing, Physiotherapy, and several other fields are exempt from the internal exam and evaluated solely on their academic record — a streamlined entry path.

**Students who prioritize small cohorts and personalized attention.** 55 students per year is the smallest Medicine class size in Spain. The pedagogical model is explicitly built around this constraint, with small seminars, simulation, and direct faculty access.

**Students comfortable with Catholic university values.** The CEU model includes compulsory humanities subjects with Catholic intellectual tradition (Doctrina Social de la Iglesia, Humanidades Médicas). Students who are comfortable with or indifferent to this framework will not experience it as an obstacle.

**Students who value pioneering a program.** The inaugural cohort has no seniors, no established traditions, and no alumni network — but also has direct access to founding faculty, the ability to shape institutional culture, and potentially stronger faculty attention during the formative years.

### Less Suitable For

**Students who need a verified track record before committing.** CULB has zero historical data. No MIR results, no graduate employment data, no cut-off scores, no alumni reviews. All claims about quality are forward-looking and unverifiable.

**Students who require full WFME or ANECA certainty before enrolling.** Both the degree's administrative authorization and WFME coverage through CEU San Pablo are marked as PENDING_CONFIRMATION. Students planning to practice medicine in countries with strict WFME requirements must seek explicit written confirmation from CULB before enrolling.

**Students on mainland Spain who cannot financially absorb island living costs.** Adding 12,000–18,000 EUR/year in living costs to a 17,955 EUR/year tuition fee creates total annual outflows of 30,000–36,000 EUR — among the highest of any private Medicine program in Spain once accommodation is factored in.

**Students who need broad clinical hospital exposure from Year 1.** The clinical training network is effectively a single private hospital group in Mallorca. Case volume and specialty breadth may be limited compared to what students access at CEU Madrid, UNAV Pamplona, or UIC Barcelona with access to large university hospital networks.

**Students from Morocco, France, or Latin America who expect easy direct access.** Palma is not a major international hub. Getting to CULB requires routing through Barcelona or Madrid. This affects both routine travel and the practical experience of being an international student in Spain.

---

## Risks and Considerations

**1. Administrative authorization pending**
The curriculum was published with an explicit caveat that the degree is subject to obtaining all required administrative authorizations. Before paying any fees, prospective students for 2027-28 must confirm that full ANECA/ministerial authorization has been granted and that the degree is formally verified.

**2. Clinical network concentration risk**
All clinical training is currently routed through Juaneda Hospitales. A single private hospital group as the sole clinical partner is a structural vulnerability. In the event of a contractual disruption, no backup hospital network is publicly identified. This is normal for a new institution but is a real risk.

**3. No institutional track record**
Every claim CULB makes about teaching quality, graduate outcomes, and MIR preparation is aspirational. There are no data points to validate. The first 3–4 cohorts are making a high-stakes bet on an unproven institution. This is categorically different from the risk profile of UNAV (founded 1954) or UIC (founded 1997).

**4. CEU adscription, not full university**
CULB does not grant its own degrees. It is an adscribed center. If the adscription agreement with CEU San Pablo were to change, the degree-awarding structure could be affected. This is a low-probability scenario but worth understanding.

**5. Island isolation and cost**
Mallorca's strong tourism-driven economy makes it one of Spain's most expensive regions for rentals. Students should budget conservatively for housing.

**6. Limited optionality if dissatisfied**
Transferring out of CULB Medicine to another Spanish private Medicine school would require meeting that school's own credit recognition policies. Given that CULB's curriculum is CEU San Pablo-aligned, transfers to another CEU campus may be more viable than transfers to non-CEU institutions.

---

## Important Notes

- **2026-27 admission is CLOSED.** The last exam convocatoria was April 18, 2026. No further intake is possible for the current academic year. Students must wait for the 2027-28 cycle.
- **Reservation deposit (2,900 EUR) is non-refundable under all circumstances**, including failure to pass EBAU. This differs from some other Spanish private Medicine schools that offer conditional refunds.
- **The 60% weighting on Y1 Bachillerato uses only 1st year grades**, not a combined Bachillerato average or a EBAU-blended score. Students should confirm their Y1 transcript is in order before applying.
- **Exam exemptions are broad.** Students with any of the listed bioscience degrees do not need to sit the internal exam — a non-obvious pathway that reduces the barrier to entry significantly for career changers.
- **The degree is formally conferred by CEU San Pablo**, not CULB. The diploma will read Universidad San Pablo-CEU, which has established international recognition value within the CEU network.
- **The "Hospitality" program** is a practical service for mainland Spain students relocating to Mallorca. It is not a scholarship or financial aid program.

---

## Key Insight

CULB is a zero-track-record bet on a CEU-backed institution in a unique geographic market: the only Medicine degree in the Balearic Islands. Its selection model is a structural advantage for candidates with strong Y1 Bachillerato grades who underperformed in the EvAU — the EBAU score has no bearing on who gets admitted. For that specific student profile, CULB may be one of the most accessible routes into private Medicine in Spain.

The trade-offs are real: an unproven clinical network, unverified WFME coverage at the CULB level, island living costs that are among the highest in Spain, and no graduates to demonstrate outcomes. Students who enroll in 2026-27 or 2027-28 are effectively pioneering a program. That carries both risk and the potential for stronger faculty relationships and institutional shaping than is possible at an established school with 20 years of inertia.

---

## Final Takeaway

For the right candidate — a student from the Balearic Islands, or a mainland Spanish student with strong Y1 Bachillerato grades and a weak EBAU, who is comfortable with Catholic university values and can manage island living costs — CULB offers a legitimate route into Medicine at a new CEU-network institution with 55-student cohorts and no prior admission competition to benchmark against. For students who need an established track record, verified accreditation, or proximity to major mainland Spanish cities, CULB carries risks that are difficult to evaluate from the outside. Confirm administrative authorizations and WFME coverage in writing before committing the 2,900 EUR non-refundable reservation.

---

## Frequently Asked Questions

**Is CULB a full university?**
No. It is a *centro universitario adscrito* to Universidad San Pablo-CEU. It does not grant its own degrees. The Grado en Medicina diploma is conferred by CEU San Pablo, not CULB. This is a common model in Spain (Blanquerna is adscribed to Universitat Ramon Llull, for example) and does not diminish the legal validity of the degree, but it means CULB itself has no independent degree-awarding authority.

**Does CULB Medicine have WFME accreditation?**
Universidad San Pablo-CEU holds WFME accreditation since March 2024. Whether this explicitly covers training delivered through CULB (as an adscribed center in Palma) requires direct confirmation from the institution. Do not assume it is covered without written confirmation.

**My EBAU score is low. Can I still be admitted?**
Yes. EBAU/PAU scores are not part of the selection formula. The score that matters is your 1st year Bachillerato average (60% weight) and your internal exam result (40% weight). You do need to have passed the EBAU *fase general* to formalize enrollment, but the score does not affect your competitive ranking.

**Which Bachillerato grades are used — 1st year, 2nd year, or both?**
Only 1st year (1º Bachillerato) grades are used in the selection formula. 2nd year grades are not part of the calculation.

**Can I take the exam online?**
Yes. The internal exam (Biology/Chemistry + English test) can be taken either in-person (presencial) or online. Both modalities are officially offered.

**What happens if I am admitted but then fail the EBAU?**
You must present a passed EBAU *fase general* (at minimum) to finalize enrollment. If you do not present your EBAU result by the stated deadline (~July 6, 2026), your place is forfeited and your reservation deposit is not refunded.

**Is the Medicine degree only in Spanish?**
Yes. The program is entirely in Spanish. There is no bilingual or English-track option for the Medicine degree at CULB.

**Can I apply if I already have a degree in Nursing?**
Yes, and you are exempt from the internal exam. Nursing graduates are on the list of bioscience degree holders who bypass the Biology/Chemistry + English test. Your application is evaluated solely on your academic documentation (degree grade, etc.).

**How large is the class?**
55 students per year. This is the smallest Medicine cohort in Spain and is a defining feature of CULB's pedagogical model.

**What is the Hospitality program?**
A practical relocation support service for students moving to Mallorca, not a financial aid program. It helps incoming students navigate accommodation, logistics, and integration into the Palma campus environment.

**Are there MIR preparation resources at CULB?**
Not published. CEU San Pablo's main Madrid campus has established MIR preparation resources, but whether and how these extend to CULB students has not been confirmed in public materials. Ask directly during the admissions process.

**Can I transfer to another university if CULB doesn't work out?**
In principle, yes — Spanish university law allows credit recognition transfers. In practice, each receiving institution decides which CULB credits to recognize and how many years you would need to repeat. Transfers within the CEU network (to CEU San Pablo's Madrid campuses) may be more straightforward than transfers to non-CEU institutions. Confirm transfer policies with prospective destination schools before enrolling.
