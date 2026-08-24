---
id: uic-medicine

type: university
subtype: private

name: Universitat Internacional de Catalunya
short_name: UIC

degree: Medicine

last_update: 2026-05-27

valid_for_intake: 2026-2027

location:
  city: Sant Cugat del Vallès
  region: Cataluña
  country: Spain

strategic_tags:
  - core_option
  - medium_competitiveness
  - academic_exam_required
  - online_exam_available
  - academic_record_heavy
  - strong_clinical_exposure
  - high_cost
  - international_friendly
  - research_oriented

admission:
  intake_month: September

  applications_open_date: PENDING_CONFIRMATION

  rolling_admissions:
    enabled: false
    estimated_end_date: NULL

  admission_rounds:
    enabled: true
    count: 1

    rounds:
      - round: 1
        application_deadline: PENDING_CONFIRMATION
        exam_date: 2026-05-09 # ANNUAL_UPDATE_REQUIRED
        results_date: PENDING_CONFIRMATION # Approx. 15 business days after exam
        deposit_deadline: PENDING_CONFIRMATION

  exam_required: true
  interview_required: true

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
  international_curriculums_accepted: true

competitiveness:
  level: medium_high

admissions_statistics:
  annual_applications: 550 # ANNUAL_UPDATE_REQUIRED
  seats: 100
  applicants_per_seat: 5.5 # ANNUAL_UPDATE_REQUIRED

  last_admitted_scores:
    - intake_year: 2025-2026
      round: 1
      score: NULL
      score_type: NULL
      notes: "2025-26 ranking published with 100 admitted students (exam 10/05/2025). Individual scores not disclosed publicly. Approximately 537 candidates sat the exam. No cut-off score available."

international_profile:
  international_students_percentage: PENDING_CONFIRMATION

  international_nationalities:
    - country: PENDING_CONFIRMATION
      percentage: PENDING_CONFIRMATION

programs:
  - id: uic-medicine-sant-cugat

    campus: Campus Sant Cugat del Vallès

    modality: standard

    strategic_tags:
      - core_option
      - academic_exam_required
      - online_exam_available
      - academic_record_heavy
      - strong_clinical_exposure
      - high_cost
      - international_friendly
      - research_oriented

    teaching_languages:
      - Catalan
      - Spanish
      - English (select subjects)

    regional_language_possible: true
    regional_language: Catalan

    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION

      english_required: false
      minimum_english_level: NULL

    seats: 100

    program_statistics:
      annual_applications: 550 # ANNUAL_UPDATE_REQUIRED
      seats: 100
      applicants_per_seat: 5.5 # ANNUAL_UPDATE_REQUIRED

      last_admitted_scores:
        - intake_year: 2025-2026
          round: 1
          score: NULL
          score_type: NULL
          notes: "Score data not published. 100 students admitted from approximately 537 who sat the May 2025 exam. No cut-off score disclosed in published ranking document."

    program_specific_admission:
      enabled: false

    evaluation_model:
      overall_model_type: weighted

      admission_pathways:
        - eligible_profiles:
            - Bachillerato nacional (Year 1 or 2)
            - Bachillerato internacional (IB)
            - CFGS
            - Estudios universitarios iniciados o finalizados (Via universitaria — 15 reserved seats)

          components:
            - component: academic_record
              enabled: true
              role: weighted
              weight: 50
              grade_source: mixed # Grade from last fully completed academic year; if completing 2nd bachillerato, 2nd year grade is used once available
              minimum_required_grade: NULL
              notes: "UIC uses the grade from the student's last fully completed year. Students in 2nd bachillerato will have their 2nd year grade applied once courses end. There is no stated minimum grade threshold for access to the exam."

            - component: academic_exam
              enabled: true
              role: weighted
              weight: 25
              exam_variant: mixed_internal_exam # Onsite for Catalonia residents; online for students residing outside Catalonia
              exam_format: multiple_choice
              delivery_mode: hybrid
              online_conditions: "Students currently residing outside Catalonia may take the exam online. Students residing in Catalonia must attend Campus Sant Cugat del Vallès in person. Both formats are on the same date, in the morning (approximately 09:00–13:00)."

              subjects:
                - Biology
                - Chemistry
                - Mathematics

              syllabus_alignment:
                biology:
                  scope:
                    - first_year_baccalaureate
                  notes: "Explicitly positioned at Year 1 bachillerato level. Depth and scope confirmed publicly."

                chemistry:
                  scope:
                    - first_year_baccalaureate
                  notes: "Explicitly positioned at Year 1 bachillerato level."

                physics:
                  scope:
                    - not_applicable
                  notes: "Physics is not included in the UIC admission exam. Only Biology, Chemistry, and Mathematics."

                mathematics:
                  scope:
                    - first_year_baccalaureate
                  notes: "Explicitly positioned at Year 1 bachillerato level."

                other_subjects:
                  - subject: NULL
                    scope:
                      - not_applicable
                    notes: NULL

              exam_difficulty:
                level: medium
                rationale:
                  - first_year_only_syllabus
                  - memorization_heavy
                notes: "Content is pegged explicitly to Year 1 bachillerato across three subjects. Students completing Year 2 who covered Year 1 content are well-positioned. Students from non-science bachillerato tracks (social, humanistic, artistic) can sit but must study the science content independently — this is confirmed by the university."

              best_attempt_counts: PENDING_CONFIRMATION
              notes: "Single exam date per intake cycle. No information published on attempt limits."

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
              notes: "No English certificate required for admission. Explicitly confirmed in university FAQs."

            - component: psychometric_test
              enabled: true
              role: weighted
              weight: 25
              test_format: multiple_choice
              delivery_mode: hybrid
              online_conditions: "Same conditions as academic exam: onsite for Catalonia residents, online for students outside Catalonia."
              notes: "Test d'aptituds emocionals. Evaluates professional profile characteristics based on the candidate's personal history and responses. Completed on the same day and session as the knowledge exam. Multiple-choice format implied by FAQ confirmation that tests are tipo test."

            - component: interview
              enabled: true
              role: qualitative_only
              weight: NULL
              interview_format: structured
              delivery_mode: hybrid
              notes: "Entrevista escrita estructurada. Written format — not oral. Completed by all candidates on exam day as part of the same session. No fixed percentage weight; outcome can increase, decrease, or maintain the candidate's final ranking score by decimal points. Functions as a qualitative modifier rather than a scored component."

            - component: complementary_points
              enabled: false
              role: bonus_only
              maximum_bonus: NULL
              categories: []
              notes: NULL
---

# Universitat Internacional de Catalunya (UIC Barcelona)

## Overview

UIC Barcelona (Universitat Internacional de Catalunya) is a private university located in Sant Cugat del Vallès, in the Barcelona metropolitan area. Its Medicine degree is one of the most established private medicine programmes in Spain, having operated since the university's founding. The programme holds WFME accreditation — the first private Medicine degree in Spain to achieve this distinction — which unlocks clinical training, postgraduate access, and professional licensing in the United States and other countries that require WFME-recognised qualifications.

The admission model combines academic record weight (50%) with a structured internal exam (25% knowledge test in biology, chemistry, and mathematics at Year 1 bachillerato level) and an emotional aptitude test (25%), complemented by a written structured interview used as a qualitative modifier. Students residing outside Catalonia may take the exam online, which significantly reduces the admission barrier for international and non-resident applicants.

With approximately 550 candidates competing for 100 seats, the programme sits at medium-high competitiveness — meaningful but not prohibitive for a well-prepared student. The MIR pass rate of 99% is the strongest single indicator of programme quality available.

## Quick Evaluation

- 100 seats; approximately 550 applicants per cycle; ~5.5:1 ratio
- WFME-accredited — currently the only private Medicine degree in Spain with this distinction
- Single annual exam date (9 May 2026 for 2026-2027 intake); online option for students outside Catalonia
- Exam covers biology, chemistry, and mathematics at Year 1 bachillerato level — accessible to thorough students
- No English certificate required for admission; some subjects delivered in English
- IB, CFGS, and university transfer pathways accepted
- Tuition: €18,600 per year (2026-2027); subject to annual revision
- Beca Nemesio: 100% of Year 1, up to 80% of subsequent years for top academic performers
- 99% MIR pass rate
- More than 2,200 hours of external clinical practice; patient contact from Year 1
- Afternoon schedule (14:00–20:00) for theoretical-practical classes — unusual in the sector

## Key Facts

| Field | Value |
|---|---|
| Official name | Universitat Internacional de Catalunya |
| Short name | UIC Barcelona |
| Location | Campus Sant Cugat del Vallès, Cataluña, Spain |
| Degree | Grau en Medicina (official) |
| Duration | 6 years (12 semesters) |
| Total ECTS | 360 |
| Seats | 100 |
| Tuition Year 1 | €18,600 (2026-2027) — ANNUAL_UPDATE_REQUIRED |
| Teaching languages | Catalan, Spanish, English (select subjects) |
| Schedule | Theoretical-practical: afternoon (14:00–20:00); clinical practice: variable |
| WFME accreditation | Yes — first private Spanish Medicine degree to obtain it |
| MIR pass rate | 99% |
| Clinical practice hours | 2,200+ external hours |
| International exam option | Yes — online for students residing outside Catalonia |
| English required for admission | No |

## Program Options

There is a single Medicine programme at UIC Barcelona, delivered on Campus Sant Cugat del Vallès. There is no bilingual track or separate international programme. The programme is taught primarily in Catalan and Spanish, with a subset of subjects delivered in English — making the overall teaching environment trilingual in practice.

Within the 100 available seats, 15 are explicitly reserved for students entering via the Via universitaria (candidates who have already started or completed another university degree). There is no separate programme for these students; they follow the same curriculum upon admission.

Credit recognition for students transferring from other Medicine programmes (trasllat d'expedient) is handled separately and is contingent on available places after the main admission round closes.

## Program Structure

The degree is structured over 6 years and 360 ECTS, distributed as follows:

- Formació Bàsica (Core basic sciences): 60 ECTS — concentrated in Years 1–2
- Matèries Obligatòries (Mandatory subjects): 232 ECTS — Years 1–5
- Matèries Optatives (Electives): 8 ECTS — available in later years
- Pràctiques externes (External clinical practice): 52 ECTS — Years 3–6
- Treball de Fi de Grau (Final degree project): 8 ECTS — Year 6

Years 1 and 2 focus on foundational biomedical sciences. From Year 3, formal clinical rotations are integrated as credit-bearing subjects alongside theoretical coursework. Year 6 is predominantly clinical, consisting of the Rotatori — a full clinical internship programme with rotations across specialties.

The Rotatori (Year 6) includes: Especialitats Mèdiques (9 weeks), Especialitats Quirúrgiques (9 weeks), Atenció Primària (2 weeks), Rotació Lliure (6 weeks, freely chosen), Rotació Socio-Sanitària (2 weeks), Rotació Social (2 weeks), and six 12-hour on-call shifts.

The TFG (Treball de Fi de Grau) is completed in Year 6. Students must have passed 300 ECTS before defending. Research areas include: applied sciences and clinical research, biostatistics and public health, medical education, sociology of medicine, anthropology and bioethics.

## Teaching Methodology

The programme is structured around integrated, competency-based learning. The curriculum explicitly targets three groups of competencies: clinical capability (what the doctor is able to do), professional conduct (how the doctor does it), and humanistic-ethical practice (how the doctor does it correctly). This three-axis framework underpins the pedagogical design.

Theoretical-practical classes run in the afternoon (approximately 14:00–20:00). Clinical practice sessions are separate and typically scheduled in the morning. This split-day structure is unusual among Spanish private medicine programmes and allows students to engage in hospital rotations in the morning from Year 3.

Core pedagogical principles include: disciplinary integration across subjects, interdisciplinarity, early patient contact from Year 1, and the internalisation of research as a tool for professional and social development. The programme uses advanced simulation facilities, ECOE (structured clinical objective examination) methodology, and clinical mentorship throughout the practical phases. The teaching faculty combines active clinical practitioners with academics, with 290 faculty members listed across medical departments.

## Clinical Training

Clinical training begins in Year 1 through structured contact activities, and intensifies progressively through the degree. External clinical practice totals more than 2,200 hours.

From Years 3 to 5, clinical training is organised through credit-bearing subject rotations at approved partner centres:

- Pràctica Clínica Mèdica I (Medicina Interna + Geriatria) — 5 weeks
- Pràctica Clínica Mèdica II (Especialitats mèdiques) — 4 weeks
- Pràctica Quirúrgica (Cirurgia general i especialitats quirúrgiques) — 4 weeks
- Atenció Primària at CAP centres — 2 weeks
- Pediatria — 4 weeks
- Optional practice rotations (2 weeks each): Dermatologia, Medicina Crítica / UCI, Oftalmologia, Oncologia, Traumatologia Esportiva, Demència i Recerca Translacional (Fundació ACE)

Year 6 clinical internship (Rotatori) covers Especialitats Mèdiques (9 weeks), Especialitats Quirúrgiques (9 weeks), Atenció Primària (2 weeks), Rotació Lliure (6 weeks, elective), Rotació Socio-Sanitària (2 weeks), Rotació Social (2 weeks), and six 12-hour on-call shifts.

**University (primary) clinical centres:**
Hospital Universitari General de Catalunya (HUGC), Hospital Universitari General de Granollers (HUGG), Consorci Sanitari de Terrassa (CST), ACEBA - EAP Sardenya.

**Associated clinical centres (selected):** Quironsalud (Hospital Quirón Barcelona, Centre Mèdic TEKNON, Hospital Quirón del Vallès, Hospital El Pilar), Hospital SJDD Esplugues (Nens), Mútua de Terrassa — Hospital Universitari Mutua Terrassa, Parc Sanitari Sant Joan de Déu (Sant Boi), Parc Sanitari Pere Virgili, Hospital de Mollet, HM Delfos, Clínica Corachan, Clínica Sagrada Família, Centro de Oftalmología Barraquer, Fundació ACE, multiple ICS (Institut Català de la Salut) CAP primary care centres, and Badalona Serveis Assistencials centres, among others. — ANNUAL_UPDATE_REQUIRED

## International Recognition and Opportunities

UIC Barcelona holds WFME (World Federation for Medical Education) accreditation for its Medicine degree — currently the only private Medicine degree in Spain to hold this distinction. As of 2024, WFME accreditation is a prerequisite in the United States and several other countries for clinical practice, postgraduate training access, and professional licensure. This means UIC graduates have a broader set of global professional pathways than graduates of non-WFME-accredited programmes.

The programme is also evaluated and accredited through AQU Catalunya, the Catalan quality assurance agency, under the Spanish national education framework.

WFME recognition makes UIC a strategically relevant choice for students who anticipate international careers or are seeking to maximise optionality beyond Spain and Europe.

## Admission Model

The UIC Medicine admission ranking is constructed from three scored components and one qualitative modifier:

**Academic record (50%):** The grade from the student's last fully completed academic year. For students currently in Year 2 of bachillerato, the Year 2 grade will be applied once the academic year ends. There is no stated minimum grade for admission — all candidates who complete the application and pay the exam fee are admitted to the exam.

**Knowledge test — Test específic de coneixements (25%):** Multiple-choice exam covering biology, chemistry, and mathematics at Year 1 bachillerato level. This is explicitly confirmed at this scope by the university. Students from non-science bachillerato tracks (social, humanistic, artistic) may still apply and sit the exam, but must have independently prepared the Year 1 science content.

**Emotional aptitude test — Test d'aptituds emocionals (25%):** Multiple-choice test evaluating professional profile characteristics, including aspects of the candidate's personal history and aptitudes. Completed on the same day as the knowledge test.

**Written structured interview — Entrevista escrita estructurada (qualitative modifier):** All candidates complete this on exam day. It carries no fixed percentage but can shift the final ranking score up, down, or not at all by decimal points. It functions as a tiebreaker-style modifier rather than a scored admission gate.

The overall model type is weighted for the first three components, with the interview as a qualitative overlay. Students who underperform on the knowledge or aptitude tests cannot fully compensate through the interview; the academic record and exam components together determine 100% of the quantifiable ranking.

Admission pathways: Bachillerato nacional, Bachillerato internacional (IB), CFGS, and Via universitaria (15 reserved seats). No English certificate is required for admission.

## Admission Process

1. Submit the online solicitud d'admissió via the UIC admissions platform.
2. Receive access credentials for the admissions portal.
3. Upload required documentation through the portal.
4. Await validation of documents by the admissions team.
5. Receive payment instructions for the exam fee; complete payment.
6. Sit the admission exam on the fixed date (9 May 2026 for 2026-2027 intake) — onsite at Campus Sant Cugat del Vallès for Catalonia residents; online for students residing outside Catalonia.
7. Receive result (Admès, En espera, or No admès) approximately 15 business days after the exam, via the admissions portal.
8. If admitted: download admission letter from the portal, pay the reservation fee (equivalent to one monthly tuition instalment), and complete enrolment.
9. The waiting list closes definitively approximately two weeks after the start of classes (late September–early October). — ANNUAL_UPDATE_REQUIRED

Contact: Servei d'Informació i Admissions — 935 042 000 — Anaïs Rey (arey@uic.es)

## Admission Timeline

All dates are ANNUAL_UPDATE_REQUIRED.

| Event | Date (2026-2027 intake) |
|---|---|
| Applications open | PENDING_CONFIRMATION |
| Application and document submission deadline | PENDING_CONFIRMATION |
| Exam date | 9 May 2026 |
| Results notification | Approx. 15 business days post-exam (late May–early June 2026) |
| Reservation payment deadline | PENDING_CONFIRMATION |
| Waiting list closes | Approx. 2 weeks after start of classes (late September–early October 2026) |
| Academic year starts | September 2026 |

**Historical reference:** 2025-2026 intake exam was held on 10 May 2025.

Candidates who plan to apply from outside Spain should confirm the application deadline and documentation requirements directly with the admissions office, as documentary verification timelines may be longer for international credentials.

## Admission Score Distribution

Exact cut-off scores are not publicly disclosed by UIC Barcelona. The published ranking document for 2025-2026 lists admitted students by code, access pathway, and status (Admitido / No admitido) but does not include individual scores.

Structurally, the ranking is built on a 0–10 scale (combining 50% academic record + 25% knowledge test + 25% emotional aptitude test), with the written interview as a decimal modifier. Since both the academic record and exam components are on a 10-point scale:

- A student with a 9.0 academic record contributes 4.5 points (50% × 9.0)
- A knowledge test score of 8.0 contributes 2.0 points (25% × 8.0)
- An emotional aptitude test score of 8.0 contributes 2.0 points (25% × 8.0)
- Written interview adjusts final total by a small decimal margin

In a cycle with approximately 537 exam-takers competing for 100 seats (ratio ~5.4:1), the de facto cut-off is likely above 7.0–7.5 combined, though this is an inference and not a published figure. The top 100 ranked candidates are admitted outright; positions 101 onwards enter the waiting list.

Students should not assume that strong academic records alone are sufficient given the 50% exam weight. A high academic grade does not compensate for weak exam performance if more than 100 candidates outperform on the combined score.

## Costs and Payment Structure

| Cost item | Amount | Notes |
|---|---|---|
| Tuition — Year 1 (2026-2027) | €18,600 | 310€/ECTS × 60 ECTS — ANNUAL_UPDATE_REQUIRED |
| Tuition — Years 2–6 | PENDING_CONFIRMATION | Subject to annual revision; 310€/ECTS rate applied to each year's ECTS |
| Approximate total (6 years) | ~€111,600 | Based on current rate; actual total will vary with annual revisions |
| Reservation fee | Equivalent to one monthly instalment | Paid upon admission; non-refundable except if student fails bachillerato/EBAU/PAU |
| Exam fee | PENDING_CONFIRMATION | Payable before exam date |

**Payment financing:** UIC Barcelona has agreements with three banking partners offering student loan products: Banco Santander, CaixaBank, and BBVA. Specific loan terms (interest rates, repayment periods) depend on the individual bank product and the student's profile. No UIC-internal instalment plan structure is published; financing is managed through external banking products.

## Scholarships and Financial Aid

**Beca Nemesio / Beca d'Excel·lència Acadèmica de Medicina (BEA):** UIC's flagship scholarship for Medicine. Covers 100% of Year 1 tuition and up to 80% of tuition for Years 2–6 for the highest-performing admitted students. Selection criteria are not fully published but are based on academic merit. This is the most financially significant scholarship available and materially changes the cost profile for candidates who qualify.

**Public scholarships:** Students can access MEC (Ministerio de Educación y Ciencia) scholarships through the national public aid system, and AGAUR (Agència de Gestió d'Ajuts Universitaris i de Recerca) grants through the Catalan government system. Eligibility depends on income thresholds and academic performance criteria set annually. — ANNUAL_UPDATE_REQUIRED

**Discounts (Descomptes i gratuïtats):** UIC offers additional fee reductions under specific circumstances (e.g., sibling enrolment, alumni families). Details are published annually on the university website.

## Accommodation and Cost of Living

Sant Cugat del Vallès is a well-resourced suburban town in the Barcelona metropolitan area, approximately 20 km northwest of Barcelona centre. It is connected to central Barcelona by FGC (Ferrocarrils de la Generalitat de Catalunya) train lines, with journey times of approximately 20–30 minutes.

The UIC campus is self-contained and campus-adjacent accommodation options exist. Living costs in Sant Cugat are lower than central Barcelona but higher than inland Spanish cities. Students typically have access to shared flats in the Sant Cugat/Rubí/Terrassa corridor or commute from Barcelona.

Estimated monthly living costs (accommodation + food + transport + personal): approximately €900–€1,400 depending on housing type and lifestyle. — ANNUAL_UPDATE_REQUIRED

The university has a dedicated student services team and a welcome programme (jornades de benvinguda) at the start of Year 1, with a student resources guide distributed to all incoming students.

## International Exchange and Mobility Programs

UIC Barcelona offers international mobility within the Medicine programme through Erasmus+ and bilateral agreements. A specific set of mobility criteria applies to Medicine students (not the university-wide criteria) — students should consult the programme-specific outgoing mobility requirements document.

The university explicitly states that mobility in Medicine is governed by programme-specific criteria covering destinations, academic year eligibility, GPA requirements, and language certificates. Students can access a searchable database of bilateral agreements via the university website.

Additionally, UIC offers participation in Berkeley Summer Sessions (University of California, Berkeley) as an extracurricular activity, providing exposure to a top-tier international academic environment outside the formal programme.

Incoming mobility (incoming students from partner universities) is also available within the programme.

WFME accreditation further expands the effective mobility footprint: UIC graduates are eligible for clinical training, residency programmes, and licensure in the United States and other countries that recognise WFME-accredited degrees — a form of structural international mobility beyond formal exchange agreements.

## MIR Preparation and Professional Outcomes

UIC Barcelona reports a 99% MIR (Médico Interno Residente) pass rate for its Medicine graduates — one of the highest figures publicly reported among private Spanish Medicine programmes. This figure represents the proportion of UIC graduates who pass the national MIR entrance examination, which is the standard pathway to medical specialisation in Spain.

The university attributes this result to early integration of clinical exposure, ECOE examination methodology throughout the degree, and the integration of research skills. The MIR rate is the primary measurable proxy for programme quality in the Spanish Medicine sector.

Published specialisation outcomes (which specialties UIC graduates match to, and at what ranking positions) are not publicly available. — PENDING_CONFIRMATION

## Strategic Fit

### Good Fit For

Students who have a solid but not exceptional academic record and can prepare specifically for three subjects at Year 1 bachillerato level. The 50% exam component and accessible exam scope mean that consistent preparation in biology, chemistry, and mathematics can partially offset a below-elite academic grade.

Students applying from outside Catalonia (internationally or from other Spanish regions) who benefit from the online exam option, removing the cost and logistical barrier of travelling to Barcelona for admission.

Students for whom WFME accreditation is strategically important — particularly those considering careers in the United States, Canada, or other countries with WFME requirements — or those who value the maximum optionality for future professional pathways.

Students who appreciate a research-integrated environment, a structured progression into clinical practice from Year 1, and access to a broad network of metropolitan Barcelona clinical partners.

Students targeting the Beca Nemesio who have the academic profile to qualify: the scholarship significantly changes the cost-benefit calculation for high-performing candidates.

### Less Suitable For

Students who are significantly more comfortable in Spanish than in Catalan, since Catalan is a primary teaching language. The programme is not bilingual — Catalan, Spanish, and English coexist, and students in a Catalan-language environment should be prepared to operate in Catalan daily.

Students who require a single, fixed academic record score to drive the entire ranking and prefer programmes with no exam component. UIC's 50% exam weight cannot be ignored even for students with strong grades.

Students based in Catalonia who are deterred by an afternoon class schedule (14:00–20:00 for theoretical classes). The reversed timetable affects how students organise study time, social life, and part-time work.

Students on a very tight budget who cannot access either the Beca Nemesio or banking financing: at €18,600 per year and ~€111,600 total, this is among the more expensive private Medicine programmes in Spain.

## Risks and Considerations

**No published cut-off scores.** The absence of historically published admission scores makes it structurally difficult for applicants to benchmark their competitive position. There is no equivalent of a numerus clausus publicado for UIC Medicine. Applicants operate with incomplete information on where their combined score would place them in the ranking.

**Annual tuition subject to revision.** The stated rate of 310€/ECTS is explicitly subject to annual change. Over a 6-year programme, even modest annual increases accumulate materially. Students and families should model upside tuition scenarios when planning financing, not just the current rate.

**Catalan as teaching language.** Non-native Catalan speakers — including Spanish students from outside Catalonia and most international students — will face a language adjustment. The programme is not structured to deliver content primarily in Spanish or English; Catalan operates as a full teaching language alongside Spanish.

**Afternoon timetable dependency.** The theoretical-practical class schedule (14:00–20:00) is unusual. Students who perform better with morning study hours, have family obligations in the afternoons, or wish to hold part-time employment will find this timetable constraining.

**Single exam date per cycle.** There is no second call or supplementary exam session. If a candidate cannot sit the exam on the designated date due to illness, conflict, or logistical failure, they lose the entire admission cycle. There is no confirmed policy on missed exam substitution.

**Beca Nemesio competition.** The scholarship is highly attractive but covers only a subset of admitted students. The percentage of students who receive the Beca Nemesio is not published. Applicants should not build their financial plan around receiving it without confirmed selection criteria and offer.

**Reservation non-refundability.** The reservation fee (one monthly instalment) is only refundable if the student fails bachillerato or EBAU/PAU. Students who change their mind after paying the reservation, or who are offered a preferred alternative, will lose the reservation payment.

## Important Notes

- The 2026-2027 admission exam date is 9 May 2026. — ANNUAL_UPDATE_REQUIRED
- Students residing in Catalonia sit the exam onsite at Campus Sant Cugat del Vallès; students outside Catalonia may sit online.
- 15 of the 100 seats are reserved for the Via universitaria pathway (students who have started or completed another university degree).
- No minimum academic grade is required to access the exam — all applicants who complete documentation and pay the exam fee are admitted to the test.
- The written structured interview has no fixed score weight but can shift the final ranking by decimal points.
- No English certificate is required for admission. Some subjects are taught in English; Spanish and Catalan are the primary instructional languages.
- The waiting list for admitted students closes approximately two weeks after the start of classes (late September–early October). — ANNUAL_UPDATE_REQUIRED
- Reservation fee is non-refundable except in case of failure to pass bachillerato or EBAU/PAU.

## Key Insight

UIC Barcelona's WFME accreditation — as the first and currently only private Medicine degree in Spain to hold it — is the single most structurally differentiating feature of this programme at the strategic level. For students considering an international medical career, particularly in the United States or other markets where WFME recognition affects licensure and postgraduate eligibility, this accreditation creates an optionality premium that no other private Spanish Medicine programme currently provides.

At the tactical level, UIC's exam is among the most accessible in scope within the private Spain sector: Year 1 bachillerato biology, chemistry, and mathematics, multiple-choice format, no physics, no university-specific esoteric content. A student who prepares these three subjects thoroughly and consistently over 6–9 months has a realistic path to a competitive exam score. The 50% exam weight means exam performance materially moves the needle — for better or for worse — regardless of academic record strength.

## Final Takeaway

UIC Barcelona is a strong and strategically differentiated private Medicine programme for students who value clinical breadth, research integration, and — most importantly — WFME-enabled global professional optionality. It is not the cheapest option, and the Catalan teaching environment and afternoon schedule add friction for certain profiles. But among private Spanish Medicine programmes, it offers the most internationally portable qualification currently available.

The admission path is straightforward in structure but genuinely competitive. A well-prepared candidate with a solid academic record (above 7.5/10) and targeted preparation in Year 1 biology, chemistry, and mathematics has a realistic pathway in. The Beca Nemesio can make the financial profile transformative for high-performing applicants.

The primary risks are: tuition inflation over 6 years, the absence of published cut-off data for positioning, and the non-refundability of the reservation fee for students who may be navigating multiple admission options simultaneously.

## Frequently Asked Questions

**How many students apply to UIC Medicine each year?**
Approximately 550 candidates sit the admission exam per cycle. In 2024-2025, approximately 537 sat the exam for 100 available seats.

**What is the applicant-to-seat ratio?**
Approximately 5.5:1, making this a moderately competitive programme — competitive enough that preparation matters, but accessible enough that a well-prepared student with a good academic record has a realistic chance.

**Can I take the admission exam if I am not in Catalonia?**
Yes. Students currently residing outside Catalonia — including international students and students from other Spanish regions — may take the admission exam in an online format, on the same date and at the same time as the onsite exam. This is a significant logistical advantage for non-Catalan residents.

**Do I need a B2 English certificate to apply?**
No. UIC explicitly confirms that no English certificate is required for the admission process.

**Can students from social or humanistic bachillerato apply?**
Yes. Students from any bachillerato track can apply and sit the exam. However, the knowledge test covers biology, chemistry, and mathematics at Year 1 bachillerato level. Students from non-science tracks who have not studied these subjects must prepare them independently.

**What is the Beca Nemesio?**
It is UIC's flagship academic excellence scholarship for Medicine: 100% of Year 1 tuition and up to 80% of Years 2–6 for the top-performing admitted students. It materially changes the cost profile but is awarded to a limited number of students. Selection criteria are not fully published.

**Does UIC have WFME accreditation?**
Yes. UIC Barcelona's Medicine degree is the first private Medicine degree in Spain to obtain WFME (World Federation for Medical Education) accreditation. As of 2024, this is a prerequisite for clinical training, postgraduate access, and medical licensing in the United States and other WFME-recognising countries.

**What is the MIR pass rate?**
UIC reports a 99% MIR pass rate for its Medicine graduates. This is the highest publicly stated figure among private Spanish Medicine programmes and represents graduates who pass the national MIR residency selection examination.

**When does the written structured interview take place?**
It is completed by all candidates on the same day as the admission exam (9 May 2026 for the 2026-2027 intake), as part of the same exam session. It is a written format, not an oral interview.

**What score do I need to be admitted?**
UIC does not publish cut-off scores. Based on the structure of the ranking (50% academic record, 25% knowledge test, 25% emotional aptitude test, qualitative interview modifier) and the ~5.5:1 applicant ratio, a combined score above 7.0–7.5 is likely needed to enter the top 100 — but this is an inference, not a published threshold.

**Is the reservation fee refundable?**
Only if the student does not pass bachillerato or EBAU/PAU (Spanish university entrance examination). It is not refunded if the student simply chooses not to enrol or accepts a place at another university.
