# Evidence Base — NCPD 2026 Proposal

Working memo for the writing team. Numbers here are for §3 (Concept & Background)
and §7 (Impact). Every figure has a source line — check the source before quoting
in the final document. Thai disability-registration figures come from NADT / DEP
annual reports; national prevalence from the NSO 2022 Disability Survey; employment
outcomes and the AT evidence from peer-reviewed literature.

Framing locked: **independence-first, employment as a key outcome.**
Target population: **working-age adults (15–59) with cognitive / memory disability**
— intellectual disability, traumatic brain injury, early-onset dementia, post-stroke
cognitive impairment. The mirror's daily-living support (medication, orientation,
routines) is positioned as the *foundation* that makes learning skills and holding a
job possible.

---

## 1. The problem — scale (Thailand)

| Figure | Value | Source |
|---|---|---|
| People with disability, national survey (2022, Washington Group method) | ~4.19 million (6.0% of population) | NSO 2022 Disability Survey / UNICEF Thailand 2023 |
| Registered (hold disability ID card) | ~2.14 million (3.23% of population) | DEP / Dept. of Provincial Administration, Dec 2021 |
| Unregistered gap | ~46% of PWD have no ID card → excluded from support | UNDP 2022 |
| Working-age PWD (15–59) | ~855,000 | NADT 2565 (2022) report |
| Intellectual disability (registered) | ~145,514 (6.81% of registered PWD) | NADT 2565 |
| Mental / behavioural disability (registered) | ~166,503 (7.79%) | NADT 2565 |
| Disability allowance | 800 baht/month ≈ 29% of the national poverty line | MDPI 2026 (Econ.) / UNICEF Thailand 2020 |

> Cognitive-type disability (intellectual + mental/behavioural + learning + autism
> categories) is a substantial and under-served slice of the ~855k working-age group.
> Note the two lenses: register categories (ID-card holders) vs. the larger
> functional-difficulty population the 2022 survey captured, which explicitly includes
> difficulty **remembering**.

## 2. The problem — employment exclusion

| Figure | Value | Source |
|---|---|---|
| Working-age PWD employed | only **36.3%** | Cheausuwantavee & Keeratiphanthawong 2021; UNDP 2022 (via MDPI 2026) |
| In competitive labour markets | merely **8%** | JPSS study (Thaijo) |
| In formal-sector work | **6.2%** | same |
| DEP snapshot (Mar 2023) | 311,259 of 857,117 working-age PWD have jobs | Nation Thailand, Dec 2023 |
| Quota system | 1 PWD per 100 employees; employers often pay fines instead of hiring | Minority Rights Group; PDEA 2007 §33–35 |
| Global benchmark | people with IDD are **3–4× less likely** to have a job | Verdonschot et al. 2009 |
| Global wage gap | disabled workers earn **12% less/hour** (26% in low/middle-income countries) | ILO 2024 |

## 3. Why current solutions fall short
- Disability allowance is far below the poverty line — income support, not a path to work.
- Quota law is weakly enforced; concessions (§35) substitute for real employment (§33).
- Existing assistive tech for cognition is **phone/tablet apps** → require the person to
  remember to open them, carry a device, and manage setup. Abandonment is high when
  setup is complex or support staff aren't trained ("the app doesn't fail, the
  implementation does").
- Adoption gap = the opportunity: in the US only **14%** of people with IDD use special
  technology for employment tasks, and **<9%** of vocational-rehab participants receive
  any AT service. Same under-provision exists in Thailand.

## 3A. Feature surface to keep in the proposal
The proposal should name concrete features, not only the prompting mechanism:
- **Calendar and tasks:** day/time, appointments, daily checklist, medication schedule.
- **Weather context:** weather panel translated into action cues ("bring umbrella",
  "wear uniform/raincoat", "hot day: water bottle").
- **Context features:** prompts chosen from schedule, weather, place/presence, last
  completed step, and current routine.
- **Remembering support:** family photos, short personal notes, and caregiver-authored
  "stuff to remember" cards.
- **Faces and names:** optional locally stored cards for familiar people; treat as a
  privacy-sensitive prototype feature, not cloud face surveillance.
- **Caregiver push messages:** one-way simple messages/reminders from family or job
  coach, displayed at the right time/context.
- **Logging:** done/delayed/skipped/help-needed completion log for caregiver review.
- **Personalization:** preferred cue style, prompt level, routines, and completion
  history are stored per user; prompt-fading adapts transparently from the log.
- **MagicMirror role:** MagicMirror is the display shell for clock/calendar/weather/task
  modules; MindMirror adds the assistive prompt engine, personalization, content packs,
  and logging layer.

## 4. Why the innovation works (evidence AT helps)
- **Meta-analysis (Morash-Macneil / PMC8115596):** applied cognitive technology improves
  employment-related outcomes for people with intellectual & developmental disability.
- **Randall et al. 2025 (J. Applied Research in Intellectual Disabilities):** AT
  increases task completion and independence in both work and home environments; job
  coaches report clients using task-list devices feel "more confident in their abilities."
- **Prompting devices** (iPod/smartphone step-by-step + reminders) let workers transition
  autonomously through vocational tasks and initiate daily activities *without a caregiver
  present* (multiple single-case + pilot studies; e.g. smartphone reminder system,
  PMC8468302; N-CAPS factory-assembly prompting, 2016).
- Take-home for our design: the mirror is an **ambient, always-on prompting system** that
  removes the two failure points of app-based AT — remembering to use it, and carrying it.

## 5. "From Learning to Earning" — the causal line for §3
Independent daily routines (meds, orientation, self-care)  →  reliable enough to train
and re-learn work tasks  →  hold a job / retain employment  →  income + dignity + reduced
lifetime care cost. Every link above has a supporting citation in this memo.

## 6. Impact numbers we can *claim* in §7 (frame as targets, not measured results)
Round 1 is concept screening, so §7 should mix **context statistics** (real, cited above)
with **projected targets** stated honestly as goals:
- Baseline to beat: 36.3% employment / 8% competitive-market participation.
- Projected: X% improvement in independent completion of a daily routine (task-time
  reduction is a clean metric — cite prompting-device studies as precedent).
- Caregiver hours reclaimed per week (secondary impact).
- # of users reachable given ~855k working-age PWD, cognitive slice ≈ tens of thousands.
Fill X with prototype pilot data if/when the technical team has it; otherwise state as
a measurable objective.

---

### Source shortlist (for the reference list)
1. National Statistical Office & UNICEF Thailand (2023). *The 2022 Disability Survey.*
2. NADT — Report on Disability Situation in Thailand 2565 (2022).
3. Cheausuwantavee & Keeratiphanthawong (2021); UNDP (2022) — employment outcomes.
4. JPSS — *Employment for Persons with Disabilities in Thailand* (Thaijo).
5. ILO (2024) — global disability wage gap.
6. Verdonschot et al. (2009) — IDD employment likelihood.
7. Morash-Macneil et al. — meta-analysis, technology & IDD employment outcomes (PMC8115596).
8. Randall et al. (2025) — AT use/barriers, home & workplace (JARID; PMC11521110).
9. Persons with Disabilities Empowerment Act B.E. 2550 (2007), §33–35.
