---
# =============================================================
# WINNERS EDUCATION — University MD Template (v2)
# Degree: Medicine | Market: Spain | Scope: Private universities
# Generated: 2026-08-21 | Source: winners-university-data-fields.md v2
#
# CONFIRMED CONVENTIONS (2026-08-21):
#   entry_year          = SECOND year of the academic cycle (e.g. "2026-2027" → "2027")
#   last_updated        = with 'd' (dateModified in schema)
#   non_tuition_fees    = structured list — old scattered fields DELETED (not deprecated)
#   exam_format.subjects = list of objects {name, weight_pct} — not flat strings
#   campus / residence  = nested blocks — not flat prefixed fields
#
# PLACEHOLDERS:
#   NULL                  = field known to exist but value not yet captured
#   PENDING_CONFIRMATION  = value exists but needs official verification
#   []                    = empty list (no items yet known)
#   ANNUAL_UPDATE_REQUIRED = comment flag on fields that change every intake cycle
#
# NEVER hand-write computed fields:
#   - 6-year total cost (derive from tuition_year1 + annual_increase_pct)
#   - days_until_next_exam (derived from sittings[].date)
#   - university_count aggregates
#   - "cheapest in the city" flag
# =============================================================

# ── SECTION 0: Identity & Scalability ──────────────────────────────────────
id: TEMPLATE-medicine           # e.g. ucam-medicine | unav-medicine
type: university
subtype: private                # private | public
degree: medicine                # enum: medicine | dentistry (future)
country: spain                  # enum: spain | france (future)
currency: EUR                   # constant — never changes

name: "Grado en Medicina — ACRONYM (Official Spanish Name)"
short_name: ACRONYM             # e.g. UCAM | UNAV | CEU-SP

entry_year: "2027"              # Year the student STARTS (= second year of academic cycle)
                                # "2026-2027" → "2027". ANNUAL_UPDATE_REQUIRED
last_updated: "YYYY-MM-DD"      # ISO date of last edit — feeds dateModified in schema
official_website: "https://..."  # Canonical admissions URL; sameAs in CollegeOrUniversity schema

# ── Institution metadata ──────────────────────────────────────────────────
institution_type: universidad_privada
religious_affiliation: NULL     # e.g. Catholic | Opus Dei | NULL
parent_group: NULL              # e.g. "Grupo CEU" | NULL
ruct_code: NULL                 # Registro de Universidades, Centros y Títulos
year_founded_medicine: NULL     # Year the Medicine degree was first delivered
inaugural_cohort: false         # true = first cohort still in progress

# ── Location ─────────────────────────────────────────────────────────────
location:
  city: "City"
  region: "Region"
  country: spain

# ── SECTION 6: Campus ────────────────────────────────────────────────────
campus:
  address: NULL                 # Full street address — never changes
  lat: NULL                     # Decimal degrees — never changes
  lng: NULL                     # Decimal degrees — never changes
  district: NULL                # Neighbourhood / suburb e.g. "Bormujos" | "Villaviciosa de Odón"
  commute_from_centre: NULL     # e.g. "35 min by Cercanías from Atocha"

# ── Strategic tags ────────────────────────────────────────────────────────
# Web filters and badge system reads these directly.
strategic_tags:
  - core_option
  # Competitiveness:    low_competitiveness | medium_competitiveness | high_competitiveness
  # Admission model:    exam_heavy | academic_record_heavy | mixed_model | no_exam
  # Exam delivery:      academic_exam_required | online_exam_available
  # Interview:          interview_required
  # Language:           english_advantage | bilingual_program | catalan_required
  # Admissions flow:    rolling_admissions | early_application_advantage
  # Cost:               high_cost | mid_cost | low_cost
  # Clinical:           strong_clinical_exposure

# ── SECTION 1b: Admission type — most structural field ──────────────────
# Drives: page template variant, listing badge ("Sin examen de acceso"),
# prep-service link visibility, access page H1.
# Values:
#   exam             = university runs its own internal entrance exam
#   academic_record  = no university exam; selection based on grades/external public exam only
#   mixed            = internal university exam + academic record weighted together
admission_type: NULL

# ── SECTION 5: Entry routes ──────────────────────────────────────────────
accepts_vocational: NULL        # bool — FP / Ciclo Formativo Superior en Salud
accepts_graduates: NULL         # bool — University graduates (titulados) — Group 2 pathway
accepts_over_25: NULL           # bool — Prueba de Acceso para Mayores de 25 años
accepts_international_curricula: NULL  # bool or list of accepted foreign education systems
spanish_level: NULL             # min level for non-native speakers: B1 | B2 | C1 | eliminatory | NULL
english_level: NULL             # min required: B1 | B2 | C1 | NULL

# ── SECTION 1b: Selection factors — summary for web ─────────────────────
# Root-level summary consumed by university page section 1 and access page.
# Detailed per-pathway breakdown stays in programs[].evaluation_model (RAG).
selection_factors:
  - factor: NULL                # exam | academic_record | interview | psychometric | competency_test | language_test
    weight_pct: NULL            # 0–100 or "not_published"; 0 = present but non-scoring
    eliminatory: NULL           # bool — true if this factor can block admission regardless of total score

# ── SECTION 1b: Seats & key thresholds ──────────────────────────────────
seats: NULL                     # Total seats all campuses — mirrors admissions_statistics.seats
                                # ANNUAL_UPDATE_REQUIRED
minimum_grade: NULL             # Published minimum threshold or null ("not published")
                                # mirrors academic_record.minimum_requirement.minimum_grade
admitted_grade_range: NULL      # Optional string e.g. "11.0–13.5" — only if reliable data exists

# ── SECTION 2: Differentiation ───────────────────────────────────────────
teaching_hospital: NULL         # "Hospital Name (City)" — primary teaching hospital
                                # mirrors clinical_training.primary_hospital / teaching_hospital
clinical_practice_start: NULL   # Year of degree: 2 | 3 | 4 | 5
                                # mirrors clinical_training.clinical_start_year
group_size: NULL                # Approximate students per practical group / seminar
teaching_language: NULL         # es | en | bilingual | es+ca | es+eu
double_degrees: []              # e.g. ["Medicine + Dentistry"] | []
distinctive_trait: NULL         # 1–2 free-text lines — what genuinely sets this university apart
applicants_per_seat: NULL       # Ratio — ANNUAL_UPDATE_REQUIRED
rankings:                       # Only verifiable claims with a source URL
  - body: NULL                  # e.g. "CYD" | "QS" | "THE" | "ShanghaiRanking"
    position: NULL              # e.g. "Top 5 Medicine Spain" | 2
    year: NULL
    source_url: NULL            # Direct link to the ranking page — required for E-E-A-T

# ── Admission process ────────────────────────────────────────────────────
admission:
  intake_month: September       # ANNUAL_UPDATE_REQUIRED
  applications_open_date: NULL  # ANNUAL_UPDATE_REQUIRED

  rolling_admissions:
    enabled: false
    estimated_end_date: NULL    # ANNUAL_UPDATE_REQUIRED

  admission_rounds:
    enabled: false
    count: NULL

  exam_required: NULL           # bool
  interview_required: NULL      # bool

# ── SECTION 4: Sittings — primary structure for web/listing/pillar ───────
# This is the canonical list for the "next exam" column, access page,
# and unified calendar on the pillar page.
# Derives from admission_rounds.rounds — admission_rounds.rounds is kept for RAG detail.
# ANNUAL_UPDATE_REQUIRED every September.
sittings:
  - date: NULL                  # ISO date — exam date (or campus visit date if no exam)
    registration_deadline: NULL # ISO date — last day to register for this sitting
    results_date: NULL          # ISO date — when results are published
    deposit_deadline: NULL      # ISO date — deadline to pay deposit after acceptance
    mode: NULL                  # in_person | online | hybrid
    location: NULL              # City / campus (for in_person or hybrid; null if online)

# ── SECTION 4: Exam format ───────────────────────────────────────────────
# Consumed by the access page. Leave all NULL if exam_required: false.
exam_format:
  question_count: NULL
  subjects:
    - name: NULL                # Subject name e.g. "Biología" | "Química" | "English"
      weight_pct: NULL          # % of total exam score; null if equal weighting or not published
  penalty: NULL                 # false | "-0.25" | "-1/3" | description string
  duration_min: NULL            # Total duration in minutes
  language: NULL                # es | en | bilingual

# ── SECTION 4: Deposit ───────────────────────────────────────────────────
# Real figure for the specific university — replaces generic "deposit range" text.
# Consumed by access page.
deposit:
  amount: NULL                  # EUR — ANNUAL_UPDATE_REQUIRED
  deadline_days: NULL           # Business days after results notification to pay
  refundable: NULL              # bool
  conditions: NULL              # Free text — e.g. "Refundable only if visa denied"

# ── Academic record ──────────────────────────────────────────────────────
academic_record:
  minimum_requirement:
    enabled: NULL
    grade_source: NULL          # pau_nota_de_admision | first_year_baccalaureate | full_baccalaureate
    minimum_grade: NULL

  competitive_filter:
    enabled: NULL
    grade_source: NULL
    approx_candidates_selected: NULL

# ── Admissions statistics ─────────────────────────────────────────────────
admissions_statistics:
  annual_applications: NULL
  seats: NULL                   # Source of truth for root-level seats field above
  applicants_per_seat: NULL     # ANNUAL_UPDATE_REQUIRED

  last_admitted_scores:
    - intake_year: NULL
      round: NULL
      score: NULL
      score_type: NULL          # pau_nota_de_admision | weighted_formula | internal_score
      notes: NULL

# ── Curriculum ───────────────────────────────────────────────────────────
curriculum:
  total_ects: 360
  formacion_basica_ects: NULL
  obligatorias_ects: NULL
  optativas_ects: NULL
  practicas_externas_ects: NULL
  tfg_ects: NULL
  international_curriculums_accepted: NULL

# ── Competitiveness ──────────────────────────────────────────────────────
competitiveness:
  level: NULL                   # low | medium | high

# ── SECTION 1: Total cost ─────────────────────────────────────────────────
# Old scattered fee fields (preadmission_fee, apertura_expediente, seguro_escolar,
# reservation_fee, admission_test_fee, annual_teaching_fees_eu/non_eu) are DELETED
# and replaced by the structured fields below.
pricing:
  tuition_year1: NULL           # Annual teaching fee — EU students — ANNUAL_UPDATE_REQUIRED
  tuition_year1_non_eu: NULL    # Annual teaching fee — non-EU students — ANNUAL_UPDATE_REQUIRED
  annual_increase_pct: NULL     # % YoY increase — used to compute 6-year total (never hand-write total)
  price_per_ects: NULL          # EUR per ECTS — ANNUAL_UPDATE_REQUIRED

  non_tuition_fees:             # All one-off and recurring fees except tuition — ANNUAL_UPDATE_REQUIRED
    - concept: NULL             # "Preinscripción" | "Reserva de plaza" | "Apertura de expediente"
                                # "Seguro escolar" | "Tasa de examen de admisión"
      amount: NULL              # EUR
      frequency: NULL           # once | annual

  payment_options:
    instalments_available: NULL # bool
    instalment_options: NULL    # Free text — describe plans available, any exclusions

# ── SECTION 3: Scholarships ──────────────────────────────────────────────
# Structured list replacing any free-text scholarship mentions.
# ANNUAL_UPDATE_REQUIRED
scholarships:
  - name: NULL                  # Official scholarship / discount programme name
    amount_or_pct: NULL         # e.g. "3,000 EUR/year" | "20%" | "Full tuition"
    criteria: NULL              # Eligibility conditions (1–2 lines)
    deadline: NULL              # ISO date or null if rolling / at enrolment
    stackable: NULL             # bool — can be combined with other discounts?

# ── SECTION 8: Sources — E-E-A-T + GEO ──────────────────────────────────
# Deep links to the EXACT official page or PDF each figure comes from.
# Never the homepage. Rendered as discreet "Fuente ↗" next to volatile data.
# Also doubles as the annual update checklist: broken link = data is stale.
# Normal links, target="_blank", no nofollow. Broken-link check quarterly.
# ANNUAL_UPDATE_REQUIRED alongside each figure.
sources:
  tuition: NULL                 # URL → official tuition fee page or PDF
  seats: NULL                   # URL → official seats / places page
  calendar: NULL                # URL → official admissions calendar / dates
  scholarships: NULL            # URL → official scholarships page

# ── Clinical training ─────────────────────────────────────────────────────
clinical_training:
  teaching_hospital: NULL       # Source of truth for root-level teaching_hospital
  hospital_network: NULL        # e.g. "Servicio Madrileño de Salud (SERMAS)"
  additional_hospitals: []
  clinical_start_year: NULL     # Source of truth for root-level clinical_practice_start
  pe_start_year: NULL           # Year of degree when Prácticas Externas begin (typically Y6)

# ── SECTION 6: Residence ─────────────────────────────────────────────────
residence:
  own_residence: NULL           # bool — does the university own/operate a student residence?
  location: NULL                # City / address — only if own_residence: true
  price_min: NULL               # EUR/month — only if own_residence: true — ANNUAL_UPDATE_REQUIRED
  price_max: NULL               # EUR/month — only if own_residence: true — ANNUAL_UPDATE_REQUIRED
  first_year_place: NULL        # bool or note e.g. "Guaranteed if requested before 2027-07-01"

# ── Accreditation ─────────────────────────────────────────────────────────
accreditation:
  aneca_verified: NULL
  wfme_accredited: NULL

# ── MIR outcomes ─────────────────────────────────────────────────────────
mir_outcomes:
  pass_rate: NULL               # e.g. "98%" — cite source in sources.* or below
  source: NULL

# ── International profile ─────────────────────────────────────────────────
international_profile:
  international_students_percentage: NULL
  international_nationalities: []

# ── Contact ───────────────────────────────────────────────────────────────
contact:
  phone: NULL
  whatsapp: NULL
  admissions_email: NULL
  website: NULL

# ── Dean / Director ───────────────────────────────────────────────────────
dean: NULL                      # ANNUAL_UPDATE_REQUIRED

# ── Programs — per-campus RAG detail ─────────────────────────────────────
# Root-level fields above = single source of truth for web rendering.
# programs[] = per-campus and per-pathway detail for RAG / chat only.
programs:
  - id: TEMPLATE-medicine-campus1
    campus: "Campus Name, City"
    modality: standard          # standard | online | hybrid

    strategic_tags: []

    teaching_languages: []      # es | en | bilingual | es+ca
    regional_language_possible: false
    regional_language: NULL     # ca | eu | gl | NULL

    language_requirements:
      minimum_spanish_level_non_native: NULL
      english_required: false
      minimum_english_level: NULL

    seats: NULL                 # ANNUAL_UPDATE_REQUIRED

    program_statistics:
      annual_applications: NULL
      seats: NULL
      applicants_per_seat: NULL
      last_admitted_scores:
        - intake_year: NULL
          round: NULL
          score: NULL
          score_type: NULL
          notes: NULL

    program_specific_admission:
      enabled: false

    evaluation_model:
      overall_model_type: NULL  # weighted | eliminatory | pathway_based

      admission_pathways:
        - eligible_profiles:
            - NULL              # bachillerato_plus_pau_ebau | vocational_superior | graduates
                                # bachillerato_ciencias_salud | traslado_de_expediente | mayores_25

          components:
            - component: academic_record
              enabled: NULL
              role: NULL        # weighted | eliminatory | requirement_only
              weight: NULL      # 0.0–1.0 decimal; null if role is eliminatory
              grade_source: NULL # pau_nota_de_admision | first_year_baccalaureate | full_baccalaureate
              minimum_required_grade: NULL
              notes: NULL

            - component: academic_exam
              enabled: NULL
              role: NULL        # weighted | eliminatory | requirement_only
              weight: NULL
              exam_variant: NULL  # external_pau_ebau | internal_exam | online_internal_exam | mixed_internal_exam
              exam_format: NULL   # multiple_choice | open_questions | mixed
              delivery_mode: NULL # onsite | online | hybrid
              subjects: []
              penalty: NULL
              duration_min: NULL
              best_attempt_counts: NULL
              notes: NULL

            - component: interview
              enabled: NULL
              role: NULL        # weighted | eliminatory | qualitative_only | requirement_only
              weight: NULL      # 0 if qualitative_only
              interview_format: NULL  # structured | panel | individual
              delivery_mode: NULL
              notes: NULL

            - component: competency_test
              enabled: NULL
              role: NULL        # eliminatory_non_scoring | weighted | requirement_only
              weight: NULL
              test_name: NULL
              duration_minutes: NULL
              questions: NULL
              notes: NULL

            - component: language_test
              enabled: NULL
              role: NULL        # eliminatory_non_scoring | weighted
              weight: NULL
              minimum_level: NULL   # B1 | B2 | C1
              applies_to: NULL      # e.g. "Non-native Spanish speakers only"
              notes: NULL

---

<!-- ============================================================
  MARKDOWN PROSE SECTIONS
  Language: Professional English only
  Numbers: Anglo-Saxon format — 1,000.00 EUR (never "punto" as thousands separator)
  Use "coste" not "costo"
  No competitor mentions, no Gokoan by name
  FAQs MUST always be the final section
  ============================================================ -->

# [Full University Name] — Medicine Degree

## Overview

[2–3 paragraphs: university profile, founding year of Medicine degree, institutional character, academic philosophy, key differentiators vs. peer private universities, MIR track record if published.]

## Location and Campus

[Campus address and neighbourhood. Proximity to city centre. Commute options. Facilities relevant to Medicine. Proximity to teaching hospital.]

## Admission Process

[Narrative of the admission model. Explain admission_type in student terms. If rolling admissions: advantage of early application. If exam-based: what the exam tests. If academic-record-based: what grades count and what the typical admitted profile looks like.]

## Total Cost and Payment Options

[Narrative cost summary. Reference tuition_year1 and non_tuition_fees items by name. Payment plans in plain terms. Note any exclusions (e.g. instalments not available for Medicine at a specific campus).]

## Scholarships and Financial Aid

[Describe scholarships[] entries in prose. Eligibility, amounts, stackability, where to apply.]

## Clinical Training

[Teaching hospital, rotation schedule, simulation centre, year clinical exposure begins, any distinctive clinical features.]

## Frequently Asked Questions

**Q: What is the admission process for international students?**
A: [Answer specific to this university.]

**Q: Is the entrance exam the same every year?**
A: [Answer specific to this university.]

**Q: Can I apply if I studied outside Spain?**
A: [Answer specific to this university.]

**Q: Are there scholarships available for international students?**
A: [Answer specific to this university.]
