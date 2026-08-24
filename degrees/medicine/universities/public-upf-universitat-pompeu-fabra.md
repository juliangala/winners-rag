---
id: upf

type: university
subtype: public

name: Universitat Pompeu Fabra
short_name: UPF

degree: Medicine

last_update: 2026-05-28

valid_for_intake: 2026-2027

location:
  city: Barcelona
  region: Catalunya
  country: Spain

strategic_tags:
  - no_academic_exam
  - academic_record_heavy
  - medium_competitiveness
  - research_oriented
  - trilingual_programme

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
  level: medium_high

admissions_statistics:
  annual_applications: PENDING_CONFIRMATION
  seats: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
  applicants_per_seat: PENDING_CONFIRMATION

  last_admitted_scores:
    - intake_year: 2025-2026
      round: convocatoria_ordinaria
      score: 12.516
      score_type: nota_de_admision
      notes: "Source: notasdecorte.es. ANNUAL_UPDATE_REQUIRED."

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

international_profile:
  international_students_percentage: PENDING_CONFIRMATION
  international_nationalities: []

programs:
  - id: upf-medicina
    campus: CEXS — Department of Medicine and Life Sciences, Campus Mar (Barcelona)
    modality: standard
    strategic_tags:
      - no_academic_exam
      - academic_record_heavy
      - medium_competitiveness
      - research_oriented
      - trilingual_programme
    teaching_languages:
      - Spanish
      - Catalan
      - English
    regional_language_possible: true
    regional_language: Catalan
    language_requirements:
      minimum_spanish_level_non_native: PENDING_CONFIRMATION
      english_required: false
      minimum_english_level: NULL
    seats: PENDING_CONFIRMATION # ANNUAL_UPDATE_REQUIRED
    program_statistics:
      annual_applications: PENDING_CONFIRMATION
      seats: PENDING_CONFIRMATION
      applicants_per_seat: PENDING_CONFIRMATION
      last_admitted_scores:
        - intake_year: 2025-2026
          round: convocatoria_ordinaria
          score: 12.516
          score_type: nota_de_admision
          notes: NULL
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
          score: 12.516
          round: convocatoria_ordinaria
          source: "notasdecorte.es / ACCES (accesuniversitats.gencat.cat) — ANNUAL_UPDATE_REQUIRED"

        - intake_year: 2024-2025
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: "ACCES (Catalunya) — ANNUAL_UPDATE_REQUIRED"

        - intake_year: 2023-2024
          score: PENDING_CONFIRMATION
          round: convocatoria_ordinaria
          source: "ACCES (Catalunya) — ANNUAL_UPDATE_REQUIRED"

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
              notes: 60% of the nota de admisión. Grades from both Bachillerato years averaged.

            - component: evau_general_phase
              enabled: true
              role: weighted
              weight: 40
              grade_source: evau_fase_general
              notes: 40% of the nota de admisión. Maximum combined base score 10.0000.

            - component: evau_specific_phase_bonus
              enabled: true
              role: bonus_only
              maximum_bonus: 4.0
              grade_source: evau_fase_especifica
              notes: Best 2 eligible subjects × ponderation coefficient (0.1 or 0.2). Max nota 14.0000. Coefficients set annually by Consell Interuniversitari de Catalunya (CIC).
              subject_ponderations:
                Biology:        0.2 # ANNUAL_UPDATE_REQUIRED
                Chemistry:      0.2 # ANNUAL_UPDATE_REQUIRED
                Physics:        0.1 # ANNUAL_UPDATE_REQUIRED
                Mathematics_II: 0.2 # ANNUAL_UPDATE_REQUIRED
                other:          ANNUAL_UPDATE_REQUIRED
---

# Universitat Pompeu Fabra (UPF) — Grado en Medicina

## Overview

The Universitat Pompeu Fabra (UPF) is a public research university founded in 1990 in Barcelona, Cataluña. Despite being one of Spain's youngest universities, UPF has consistently ranked as Spain's top university by research impact per faculty member across multiple international rankings, including THE Young University Rankings and QS. The Grado en Medicina is hosted within UPF's Department of Medicine and Life Sciences (CEXS — Ciències Experimentals i de la Salut), located at the Campus Mar in the Barceloneta/Eixample waterfront area of Barcelona.

For the 2025-26 intake, UPF Medicine recorded a nota de corte of 12.516 (source: notasdecorte.es), placing it in the medium-high competitiveness tier for public Medicine in Spain. This is lower than the UAH (12.871) and UA (12.718) figures, making UPF an attractive access point for candidates with strong academic records who cannot reach the top Madrid or major Catalan university thresholds (UB and UAB historically carry higher notas de corte in Barcelona).

A defining feature of UPF Medicine is its genuinely trilingual teaching environment — Spanish, Catalan, and English — reflecting UPF's institutional commitment to international academic culture and research excellence. This is not a cosmetic bilingual label: significant portions of the curriculum are delivered in English, and the programme is embedded within an internationally active research environment.

## Quick Evaluation

- **Degree:** Grado en Medicina — 6 years — 360 ECTS
- **Seats:** PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED)
- **Admission mechanism:** Nota de admisión (nota de corte model via ACCES); no exam, no interview
- **Competitiveness:** Medium-high — lower nota de corte than UB/UAB but high nationally; UPF's research profile elevates its strategic value
- **Nota de corte (2025-26):** 12.516 out of 14.000 (source: notasdecorte.es; ANNUAL_UPDATE_REQUIRED)
- **Tuition (approximate):** ~1,108 EUR/year for EU residents (ANNUAL_UPDATE_REQUIRED)
- **Clinical training from:** Year 3 — Hospital del Mar and affiliated Barcelona hospitals (PENDING_CONFIRMATION on full network)
- **Teaching language:** Trilingual: Spanish, Catalan, English
- **WFME accreditation:** PENDING_CONFIRMATION
- **International access:** Via PCE/UNED or Credencial UE

## Key Facts

| Parameter | Value |
|---|---|
| Official name | Universitat Pompeu Fabra |
| Short name | UPF |
| Degree | Grado en Medicina (Grau en Medicina) |
| Duration | 6 years (360 ECTS) |
| Annual seats | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Campus | Campus Mar, Barcelona (Department of Medicine and Life Sciences — CEXS) |
| Year 1–2 location | Campus Mar, Barcelona |
| Year 3–6 location | Hospital del Mar and affiliated hospitals (PENDING_CONFIRMATION on full network) |
| Teaching language | Spanish, Catalan, English (trilingual) |
| Admission type | Nota de admisión (ACCES — Catalan admissions system) |
| No proprietary exam | Correct |
| No interview | Correct |
| Tuition (EU, indicative) | ~1,108 EUR/year (ANNUAL_UPDATE_REQUIRED) |
| Tuition (non-EU, indicative) | PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED) |
| Founded | 1990 |
| Website | http://www.upf.edu/biomed/ |

## Program Options

UPF offers a single Grado en Medicina track at the Campus Mar. There is no separate international cohort, though the programme is genuinely trilingual and internationally oriented. All admitted students follow the same curriculum.

UPF's Medicine programme is distinctive within the Spanish public university landscape in its trilingual delivery and deep research integration. This is not a traditional medicine school environment: students are immersed in a research-active faculty from Year 1, with close proximity to UPF's internationally recognised biomedical research departments.

## Program Structure

The Grado en Medicina at UPF is structured across 6 academic years totalling 360 ECTS, in accordance with Spanish national requirements for Medicine degrees.

**Phase 1 — Preclínica (Years 1–2):** Core biomedical sciences delivered at Campus Mar. Subjects include Cell Biology, Biochemistry, Human Anatomy, Physiology, Genetics, Microbiology, Immunology, Pharmacology, and Pathophysiology. A distinctive feature is the early integration of research methodology and epidemiology, reflecting UPF's research culture. English-medium instruction is present from Year 1.

**Phase 2 — Clínica (Years 3–6):** Hospital-based clinical training in affiliated teaching hospitals. Students rotate through internal medicine, surgery, obstetrics and gynaecology, paediatrics, psychiatry, primary care, and other specialties. Clinical training occurs within the Parc de Salut Mar ecosystem and affiliated Barcelona hospitals.

**TFG (Final Degree Project):** A mandatory research-focused final project. Given UPF's research orientation, the TFG is expected to reflect a higher degree of scientific rigour than at many other institutions. Language of submission PENDING_CONFIRMATION.

**Electives:** Optional subjects available across the curriculum (PENDING_CONFIRMATION on exact ECTS and subject list).

## Teaching Methodology

UPF Medicine is structured to develop physicians with strong scientific foundations and research literacy from the outset of the degree. The methodology integrates traditional lectures with problem-based learning (PBL) elements, small-group seminars, simulation, and early exposure to research thinking.

English-medium instruction is genuinely embedded: a significant portion of lectures and assessment in both preclinical and clinical years are conducted in English, with the explicit aim of preparing graduates for international scientific literature, postgraduate programmes, and research collaboration. This is confirmed by UPF's institutional policy and its Department of Medicine and Life Sciences.

Catalan is the primary co-official language of instruction alongside Spanish; students will encounter both in clinical and classroom settings. Non-Catalan speakers are not required to have Catalan proficiency for admission, but Catalan is increasingly present in clinical environments.

UPF's research integration is structural, not incidental. The Department of Medicine and Life Sciences shares its campus with major biomedical research institutions (including IMIM — Hospital del Mar Medical Research Institute), giving students direct access to an active research ecosystem.

## Clinical Training

Clinical training at UPF takes place within the Parc de Salut Mar ecosystem and affiliated Barcelona teaching hospitals. Rotations begin from Year 3.

**Primary affiliated hospital:**

- **Hospital del Mar** — Barcelona (Barceloneta district, adjacent to Campus Mar). The main public hospital affiliated with UPF Medicine, and the clinical arm of the Parc de Salut Mar. Hospital del Mar is a major tertiary hospital with strong research integration through IMIM (Institut Hospital del Mar d'Investigacions Mèdiques).

**Additional affiliated hospitals (PENDING_CONFIRMATION — verify current UDH network at UPF CEXS):**

- Hospital de la Santa Creu i Sant Pau — a major Barcelona teaching hospital and UNESCO World Heritage site; PENDING_CONFIRMATION on current UPF affiliation status.
- Hospital Clínic — PENDING_CONFIRMATION on current UPF affiliation status.
- Additional Parc de Salut Mar network centres (PENDING_CONFIRMATION).

The proximity of Campus Mar to Hospital del Mar creates a particularly integrated teaching environment where basic science and clinical training are geographically co-located. IMIM affiliation provides structured research internship opportunities alongside clinical training.

## International Recognition and Opportunities

The UPF Grado en Medicina complies with European Directive 2005/36/EC on the recognition of professional qualifications, enabling graduates to seek medical licences across EU/EEA member states under the regulated professions framework.

**WFME accreditation:** PENDING_CONFIRMATION — verify current status at the UPF CEXS website.

**Research rankings:** UPF is consistently ranked Spain's top university by research impact per faculty member in multiple international rankings. This applies across the institution but has specific implications for Medicine: the research environment is internationally competitive and students are exposed to faculty who publish in high-impact journals.

**Erasmus+ mobility:** UPF participates in the Erasmus+ programme with a strong institutional track record across faculties. Medicine-specific bilateral agreements for Erasmus exchange are PENDING_CONFIRMATION — students should verify with the CEXS international office which partner institutions are active for Medicine students and from which study year.

**International alliances:** UPF is a member of the Young Universities for the Future of Europe (YUFE) alliance. Implications for Medicine students specifically are PENDING_CONFIRMATION.

**English-medium environment:** UPF's genuine English-medium instruction gives graduates a competitive advantage for international postgraduate programmes, research fellowships, and clinical positions in English-speaking countries.

## Admission Model

UPF Medicine participates in Spain's public university admissions system, administered through ACCES (the Catalan admissions system, accesuniversitats.gencat.cat), managed by the Consell Interuniversitari de Catalunya (CIC). Admission is determined exclusively by the nota de admisión. There is no proprietary entrance exam and no interview.

**The nota de admisión formula:**

```
Nota de admisión = 0.6 × Nota media de Bachillerato
                 + 0.4 × Nota EVAU (fase general)
                 + up to 4.0 bonus points from EVAU fase específica
```

- **Base score maximum:** 10.0000
- **Maximum nota de admisión:** 14.0000 (with full specific-phase bonus)
- **Specific phase:** Best 2 eligible subjects selected. Each subject grade × ponderation coefficient (0.1 or 0.2) set annually by CIC.

**Ponderation coefficients for Medicine at UPF (ANNUAL_UPDATE_REQUIRED — verify at official ACCES/CIC ponderation table):**

Biology: 0.2, Chemistry: 0.2, Physics: 0.1, Mathematics II: 0.2 (all ANNUAL_UPDATE_REQUIRED — verify official source each cycle).

**Note on Physics coefficient:** If confirmed, Physics carries coefficient 0.1 at UPF (vs. 0.2 for Biology, Chemistry, and Mathematics II). This makes Physics a less optimal specific-phase choice compared to Biology, Chemistry, or Mathematics II. Candidates should verify the current coefficient table at ACCES before finalising subject selection.

**Access routes:**
- Spanish Bachillerato + EVAU (PAU): standard route (including EVAU from all Spanish regions)
- FP Grado Superior + EVAU specific phase: valid
- International via PCE/UNED (Credencial UNEDasiss): valid
- International via Credencial UE: valid
- Direct homologation (select countries): valid; check ACCES requirements

## Admission Process

### For Spanish PAU students

1. Complete Bachillerato and sit EVAU: mandatory general phase + optional specific phase (strongly recommended for Biology, Chemistry, and Mathematics II — coefficient 0.2 each at UPF; ANNUAL_UPDATE_REQUIRED).
2. Receive nota de admisión from the EVAU authority.
3. Submit preinscripció (university application) through the ACCES portal (accesuniversitats.gencat.cat) during the designated window (ANNUAL_UPDATE_REQUIRED).
4. List UPF Medicina among your degree preferences in the Catalan system.
5. Await results of the ordinaria convocatoria.
6. If not admitted in the ordinaria: apply for the extraordinaria convocatoria.
7. If admitted: complete enrolment (matrícula) at UPF within the published deadline.

### For international PCE/UNED students

1. Obtain a secondary qualification equivalent to Spanish Bachillerato.
2. Apply to UNEDasiss for a Credencial. Submit transcripts and request subject recognition.
3. Sit PCE at UNED for subjects relevant to Medicine — Biology, Chemistry, and Mathematics II carry coefficient 0.2 at UPF (ANNUAL_UPDATE_REQUIRED — verify). Physics carries coefficient 0.1 (ANNUAL_UPDATE_REQUIRED).
4. Receive final UNEDasiss Credencial with calificación (5–10 scale).
5. Submit preinscripció through the ACCES portal (ANNUAL_UPDATE_REQUIRED for exact process and dates).
6. If admitted: complete enrolment and arrange visa/NIE if applicable.

## Admission Timeline

All dates are approximate based on standard ACCES/Catalan calendar patterns. All dates are ANNUAL_UPDATE_REQUIRED — verify at accesuniversitats.gencat.cat.

| Phase | Approximate Period |
|---|---|
| EVAU ordinaria (Catalunya / Selectivitat) | June (ANNUAL_UPDATE_REQUIRED) |
| EVAU extraordinaria (Catalunya) | July (ANNUAL_UPDATE_REQUIRED) |
| ACCES preinscripció ordinaria | June–July (ANNUAL_UPDATE_REQUIRED) |
| ACCES results ordinaria | July (ANNUAL_UPDATE_REQUIRED) |
| Enrolment window | July–September (ANNUAL_UPDATE_REQUIRED) |
| ACCES preinscripció extraordinaria | August–September (ANNUAL_UPDATE_REQUIRED) |
| Academic year begins | September (ANNUAL_UPDATE_REQUIRED) |
| PCE/UNED sessions | February and June (ANNUAL_UPDATE_REQUIRED) |

## Admission Score Distribution

UPF Medicine's nota de corte for 2025-26 was 12.516 (source: notasdecorte.es; ANNUAL_UPDATE_REQUIRED). This is notably lower than the established Barcelona public Medicine programmes (UB — Universidad de Barcelona, and UAB — Universitat Autònoma de Barcelona — which historically record notas de corte above 13.0; PENDING_CONFIRMATION for 2025-26 figures). This gap reflects UPF's younger institutional age and, possibly, smaller seat count rather than programme quality — UPF's research metrics are superior to those of many institutions with higher notas de corte.

**Historical trend (ANNUAL_UPDATE_REQUIRED):**

| Intake Year | Nota de Corte | Source |
|---|---|---|
| 2025-2026 | 12.516 | notasdecorte.es (verified) |
| 2024-2025 | PENDING_CONFIRMATION | — |
| 2023-2024 | PENDING_CONFIRMATION | — |

**What this means strategically:**

A nota de admisión of 12.516 is achievable for candidates with strong Bachillerato averages (9.0+) and solid specific-phase performance in Biology and Chemistry (coefficient 0.2 each) or Mathematics II (coefficient 0.2). The 0.35-point gap below UAH (12.871) and 0.20-point gap below UA (12.718) positions UPF as the most accessible of the four universities in this set from a score perspective.

The strategic insight is significant: UPF Medicine offers access to Spain's top-ranked research university for candidates with lower notas de admisión than those required for UAH, UA, UCM, UAM, UB, or UAB. For research-oriented or internationally minded candidates, this score-quality mismatch represents a genuine strategic opportunity.

**Ponderation coefficients for Medicine at UPF (ANNUAL_UPDATE_REQUIRED — verify at ACCES official table):**

| Subject | Coefficient |
|---|---|
| Biology | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Chemistry | 0.2 (ANNUAL_UPDATE_REQUIRED) |
| Physics | 0.1 (ANNUAL_UPDATE_REQUIRED) |
| Mathematics II | 0.2 (ANNUAL_UPDATE_REQUIRED) |

Candidates should prioritise Biology, Chemistry, and Mathematics II for specific-phase preparation if the 0.1 coefficient for Physics is confirmed (ANNUAL_UPDATE_REQUIRED).

## Costs and Payment Structure

Tuition fees at UPF are set by the Generalitat de Catalunya via regional decree and are subject to annual revision. Medicine falls within the experimental branch (rama experimental / branca experimental), carrying higher per-credit rates.

| Fee Concept | EU/EEA Students | Non-EU Students | Notes |
|---|---|---|---|
| Annual tuition (per year, approx.) | ~1,108 EUR | PENDING_CONFIRMATION | ANNUAL_UPDATE_REQUIRED |
| Per-credit fee (experimental branch) | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | Medicine = experimental branch; higher rate |
| Enrolment / administrative fees | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED | ANNUAL_UPDATE_REQUIRED |
| Student insurance (seguro escolar) | ~1.12 EUR | ~1.12 EUR | ANNUAL_UPDATE_REQUIRED |
| Repeat enrolment surcharge | Higher per-credit rate | Higher per-credit rate | Applies from 2nd enrolment in same subject |

The indicative ~1,108 EUR/year figure is within the standard Catalan public university tariff range. Non-EU tuition is significantly higher (PENDING_CONFIRMATION — verify at the current Generalitat de Catalunya decreto de tasas for universities).

Barcelona is one of Spain's most expensive cities for accommodation and daily living. Students must budget carefully, as the combination of public university tuition and Barcelona living costs requires realistic financial planning.

## Scholarships and Financial Aid

**National level:**
- **Beca General MEC:** Available to all students at public universities meeting income and academic criteria. Covers partial tuition and may include a living stipend. Applications via the MEFP scholarship portal annually (ANNUAL_UPDATE_REQUIRED).
- **Beca Movilidad (Erasmus+):** Available for approved Erasmus exchange periods.

**Regional level (Catalunya):**
- The Generalitat de Catalunya offers scholarship programmes for Catalan-resident students with economic need. PENDING_CONFIRMATION — verify current programmes at the Generalitat de Catalunya education portal (ANNUAL_UPDATE_REQUIRED).

**University level:**
- UPF has internal scholarship and emergency aid mechanisms. Details at upf.edu/beques (ANNUAL_UPDATE_REQUIRED).
- UPF participates in Santander Universities scholarship programmes and other private foundation initiatives.
- Research grant opportunities: through IMIM and UPF research programmes, students may access research bursaries and internship funding in later clinical years. PENDING_CONFIRMATION on formal student research grant schemes.

## Accommodation and Cost of Living

Barcelona is one of Spain's most expensive cities for student accommodation, driven by high demand and a constrained rental market. Students should budget significantly higher than at provincial university cities.

| Cost Category | Approximate Monthly Range | Notes |
|---|---|---|
| Shared flat room (Barcelona) | 600–950 EUR | ANNUAL_UPDATE_REQUIRED — Barcelona rental market is highly volatile |
| University residence / hall of residence | PENDING_CONFIRMATION | ANNUAL_UPDATE_REQUIRED |
| Food (self-catering) | 200–350 EUR | ANNUAL_UPDATE_REQUIRED |
| Public transport (T-Jove / T-usual) | 20–45 EUR/month | ANNUAL_UPDATE_REQUIRED |
| Books / materials (Year 1 estimate) | 200–400 EUR | ANNUAL_UPDATE_REQUIRED |

Campus Mar is located in central Barcelona (Barceloneta/Vila Olímpica area), offering excellent city connectivity but in one of Barcelona's most expensive residential zones. Students should begin accommodation searches early (from April–May) given the tight Barcelona rental market.

Non-EU students who do not benefit from MEC scholarship support will face the combination of non-EU tuition fees plus Barcelona living costs — a substantial total annual budget. Financial planning should be completed before committing to UPF.

## International Exchange and Mobility Programs

UPF participates in the Erasmus+ programme at the institutional level. The specific bilateral agreements for Medicine students (CEXS) are PENDING_CONFIRMATION — students should verify with the UPF CEXS international office which partner medical faculties are active and from which study year exchange is permitted.

UPF is a member of the YUFE (Young Universities for the Future of Europe) alliance, which may generate mobility opportunities beyond standard Erasmus. Implications for Medicine students are PENDING_CONFIRMATION.

UPF's genuinely international faculty (many professors with international research careers) and its English-medium instruction create a de facto international academic environment even without formal exchange. Students are regularly exposed to visiting researchers and international seminar cultures.

Research mobility: through IMIM affiliation and UPF's international research networks, students in clinical years may access research stays at partner institutions internationally. These are competitive and not guaranteed to all students.

## MIR Preparation and Professional Outcomes

The MIR (Médico Interno Residente) examination is the national gateway to medical specialisation in Spain. All UPF Grado en Medicina graduates are eligible to sit the MIR.

**MIR pass rate for UPF graduates:** PENDING_CONFIRMATION — UPF does not currently publish programme-specific MIR pass rates or ranking distributions in a readily verifiable public format as of the date of this file.

**General context:** UPF's Medicine programme combines hospital clinical training at Hospital del Mar — a solid tertiary hospital — with the institution's research culture. The research integration and scientific-literacy focus are arguably superior preparation for a science-based examination like the MIR compared to programmes that are purely clinically oriented. However, this is an analytical inference — verified MIR performance data is PENDING_CONFIRMATION.

Post-MIR, graduates can specialise within the Sistema Nacional de Salud. UPF's research environment and international networks provide a strong pathway for graduates interested in combining clinical careers with research or pursuing academic medicine internationally.

## Strategic Fit

### Good Fit For

- Research-oriented candidates who want access to Spain's highest-ranked research university environment in Medicine, at a nota de corte (12.516) lower than most equivalent programmes in Barcelona or Madrid.
- Candidates with a nota de admisión in the 12.52–12.85 range for whom UPF is a primary strategic target given the score-quality profile.
- Students who value or require English-medium instruction as part of their academic development — UPF's trilingual environment is genuinely differentiated.
- International students (PCE/UNED route) who have achieved strong Biology and Chemistry scores and seek a Barcelona-based public Medicine programme.
- Candidates planning to pursue academic medicine, research careers, or international postgraduate training (UK, US, Germany) after graduating — UPF's research profile and English fluency requirements are significant advantages.
- Students who prefer an intimate, research-focused campus (Campus Mar) over a large urban medical faculty campus.

### Less Suitable For

- Candidates whose nota de admisión exceeds ~13.0 — UB or UAB in Barcelona, or UCM/UAM in Madrid, are more appropriate targets.
- Students who require Catalan-language clinical environments to be absent — Catalan is increasingly used in Catalan clinical settings including Hospital del Mar.
- Candidates with tight budgets who cannot absorb Barcelona living costs — the city is significantly more expensive than provincial alternatives.
- Students who expect a traditional, large-cohort lecture-based medical education — UPF's environment is research-integrated and trilingual, which is a significant cultural difference.
- International students with limited English proficiency — UPF's English-medium instruction requires functional English for academic success.

## Risks and Considerations

1. **Barcelona cost of living:** The combination of public tuition (~1,108 EUR/year) and Barcelona accommodation costs (600–950 EUR/month for a shared room) creates a substantially higher total annual cost than provincial alternatives. Budget planning is critical.

2. **Nota de corte variability:** The 2025-26 nota de corte of 12.516 is not a stable floor. It can increase in future cycles as UPF's Medicine programme gains recognition and attracts a larger applicant pool. Candidates should plan with a buffer.

3. **Hospital network scope:** Hospital del Mar, while research-active through IMIM, is a medium-sized tertiary hospital. The breadth of specialist cases and sub-speciality coverage may be narrower than at very large hospitals (e.g., Hospital Clínic, Hospital Vall d'Hebron) associated with UB or UAB. PENDING_CONFIRMATION on the full UPF affiliated hospital network.

4. **Catalan language in clinical settings:** While admission does not require Catalan, clinical environments in Catalunya increasingly use Catalan as a working language. Students who cannot function in Catalan may face practical communication challenges in hospital rotations.

5. **Physics coefficient at 0.1:** If the Physics coefficient is confirmed at 0.1 (vs. 0.2 for Biology, Chemistry, Mathematics II), candidates who sat Physics as their specific-phase science subject are at a notable disadvantage. Candidates should check the current coefficient table and plan PCE/EVAU accordingly.

6. **Non-EU tuition:** Non-EU students face significantly higher fees. PENDING_CONFIRMATION on exact non-EU rate at UPF.

7. **MIR outcome data:** UPF does not publish Medicine-specific MIR performance data in a verifiable public format. The research quality of the institution does not automatically translate into superior MIR performance — the MIR tests clinical knowledge breadth that requires dedicated preparation regardless of university.

## Important Notes

- All admission dates (EVAU, ACCES preinscripció, enrolment) are ANNUAL_UPDATE_REQUIRED — verify at accesuniversitats.gencat.cat.
- The official ACCES/CIC ponderation table for UPF Medicine specific-phase subjects is published annually and is ANNUAL_UPDATE_REQUIRED. The Physics coefficient is particularly important to verify each cycle.
- Non-EU students must verify visa, NIE, and health insurance requirements separately from admission.
- The clinical training hospital list (UDH) should be verified at the UPF CEXS website each intake year — UPF's hospital affiliations may evolve as the Parc de Salut Mar network develops.
- UPF's trilingual environment requires functional Spanish and some Catalan for clinical settings; English proficiency is strongly advantageous.

## Key Insight

UPF Medicine represents a genuine strategic anomaly in the Spanish public university landscape: it offers access to Spain's top-ranked research university — consistently ranked #1 in Spain by research impact per faculty — at a nota de corte (12.516 in 2025-26) that is lower than many programmes at institutions with significantly weaker research profiles. For research-oriented, internationally minded candidates who speak or are learning English, and who can absorb Barcelona living costs, UPF Medicine is an outstanding value proposition. The key risks are financial (Barcelona is expensive) and clinical scope (Hospital del Mar, while research-active, is a medium-sized hospital). Candidates must decide whether the research-excellence and international-language environment justify the higher cost of living relative to provincial alternatives with similar admission thresholds.

## Final Takeaway

For candidates in the 12.52–12.85 nota de admisión range who are motivated by research, international exposure, and English-medium academic culture, UPF Medicine is a strategically exceptional choice among Spanish public universities. The trilingual environment, IMIM research integration, and internationally recognised research output create a learning environment substantially different from traditional Spanish medical faculties. The principal practical constraint is Barcelona's cost of living — significantly higher than Alicante, Alcalá de Henares, or Palma. Candidates who can manage the financial dimension gain access to a programme whose research profile is unmatched among public Medicine options in Spain at this nota de corte level.

## Frequently Asked Questions

**How is the nota de admisión calculated?**
The nota de admisión = 0.6 × Nota media de Bachillerato + 0.4 × Nota EVAU (fase general) + bonus from up to 2 specific-phase subjects (each subject grade × ponderation coefficient of 0.1 or 0.2). The maximum score is 14.0000.

**What is the nota de corte for UPF Medicine?**
For the 2025-26 intake, the nota de corte was 12.516 (source: notasdecorte.es). It is not a fixed threshold — it changes annually. Historical data for prior cycles is PENDING_CONFIRMATION.

**Is instruction really in English?**
Yes — a significant portion of the UPF Medicine curriculum is delivered in English. This is not a symbolic gesture: the programme is genuinely trilingual (Spanish, Catalan, English), with English instruction present from Year 1. Students who lack English proficiency will face academic difficulty.

**Can international students apply via PCE?**
Yes. International students who obtain a UNEDasiss Credencial and sit PCE can apply through ACCES. At UPF, Biology and Chemistry carry coefficient 0.2 and Mathematics II also carries 0.2, while Physics carries 0.1 (ANNUAL_UPDATE_REQUIRED — verify at ACCES). Prioritise Biology, Chemistry, and Mathematics II for PCE preparation.

**What are the tuition fees?**
For EU/EEA students, approximately 1,108 EUR/year (ANNUAL_UPDATE_REQUIRED). For non-EU students, PENDING_CONFIRMATION (ANNUAL_UPDATE_REQUIRED). Medicine falls in the "experimental" branch category.

**When do I apply?**
Applications (preinscripció) are submitted through the ACCES portal (accesuniversitats.gencat.cat) in June–July for the ordinaria convocatoria. An extraordinaria convocatoria follows in August–September. All dates are ANNUAL_UPDATE_REQUIRED.

**Is Catalan required?**
No Catalan proficiency is required for admission. However, Catalan is co-official in Catalunya and is increasingly used in clinical environments. Students studying in Barcelona and doing clinical rotations at Hospital del Mar will encounter Catalan regularly. Some functional Catalan is practically advantageous.

**Is there an interview or entrance exam?**
No. UPF Medicine admission is based solely on the nota de admisión within the ACCES framework. There is no interview, proprietary exam, or portfolio requirement.

**When does clinical training begin?**
From Year 3. Years 1–2 are taught at Campus Mar (Barcelona). From Year 3, students rotate through affiliated hospitals, primarily Hospital del Mar and the Parc de Salut Mar network.

**Why is UPF's nota de corte lower than UB or UAB if it is a top research university?**
The nota de corte reflects supply and demand in the specific admissions market. UPF is a younger institution (founded 1990), has a smaller Medicine faculty profile in public perception compared to UB (founded 1450) or UAB (founded 1968), and may offer fewer Medicine seats. Research rankings and nota de corte are not correlated in a simple linear way. For well-informed candidates, this gap represents an opportunity to access a superior research environment at a lower admission threshold.
