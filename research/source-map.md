# Source Map — reconciled evidence for the NCPD 2026 proposal

Merges the two research inputs into one place, keyed to proposal sections:
- **`evidence-base.md`** → Thailand-specific numbers (prevalence, employment
  exclusion, policy, the "From Learning to Earning" causal line). Web-sourced;
  verify each figure at its source line before final submission.
- **`leapspace.md`** → international peer-reviewed backbone (efficacy of
  prompting tech, smart-mirror prior art, adoption barriers). 61 DOI refs;
  10 load-bearing DOIs spot-checked against Crossref — all resolve, titles match.
  LeapSpace ref numbers below are written as **L#**.

The two are complementary, not redundant: LeapSpace explicitly flags that its
prevalence/employment data is region-thin — that gap is exactly what the
Thailand memo fills. Use Thailand numbers for scale/need, LeapSpace refs for
"the technology works."

---

## Verified — the four load-bearing peer-reviewed sources
Confirmed real via Crossref (title + journal + year match):
- **L7/L22 Kang et al. 2025**, *J. Alzheimer's Disease* — smart-mirror cognitive
  training is feasible and improves cognitive scores (MoCA-K), recall, orientation.
  → **This is our concept validation: a smart mirror for cognition has been built and tested.**
- **L38 Dorado Chaparro et al. 2021**, *Sensors* — SHAPES smart mirror for
  independent living. → Direct prior art for the form factor.
- **L10 O'Neill et al. 2018**, *J. Head Trauma Rehab* — **RCT**: micro-prompting
  reduces support needed by people with severe acquired brain injury in ADLs.
  → Highest-tier evidence for the prompting claim.
- **L44 Sauer et al. 2010** — systematic review: AT improves **employment
  outcomes** for people with cognitive disability. → Lets §7 claim an employment effect.

---

## Section-by-section: what to say + what backs it

### §3 Concept & Background
| Claim | Number / evidence | Source |
|---|---|---|
| Scale of disability in Thailand | ~4.19M PWD (6%), ~855k working-age | evidence-base §1 |
| Cognitive-type slice is large & under-served | ~145k intellectual + ~167k mental/behavioural (registered) | evidence-base §1 |
| Employment exclusion (the core problem) | only 36.3% employed; 8% competitive market | evidence-base §2 |
| Cognitive deficits *cause* the work exclusion | memory/executive function predict return-to-work | L1, L5, L24, L25, L34 |
| Current AT fails: app/device dependence, abandonment | complexity, digital literacy, no support → abandonment | L16, L17, L18, L40 |
| Why ambient/always-on tech | removes "remember to open it" + "carry it" failure points | L7, L11, L39 |
| "From Learning to Earning" link | independence → trainable → employable (causal chain) | evidence-base §5 + L44 |

### §4 Objectives — no new numbers; flows from §3.

### §5 Target Users
| Field | Content | Source |
|---|---|---|
| Disability type | intellectual disability, TBI, post-stroke cognitive impairment, early dementia | L1–L6 |
| Age range | working-age 15–59 | evidence-base §1 |
| Est. number | cognitive slice of ~855k working-age PWD ≈ tens of thousands | evidence-base §1 |
| Prevalence context (global) | TBI 60.4% unemployed at 2y (L2); post-stroke cognitive impairment common (L3); ID 1.5%–10.4/1000 (L4) | L2, L3, L4 |

### §6 Methods (teammate) — hand him these for prior art / design justification
- Smart-mirror precedent: **L7 Kang 2025**, **L38 Dorado Chaparro 2021**, IoM concept **L15/L59 Fatima**.
- Prompting design that works: context-aware/location-based beats fixed-time (L11, L12, L13); multimodal audio+visual preferred (L39); avoid menu depth / cognitive overload (L16, L40).
- Workplace prompting precedent: **L46 Mihailidis N-CAPS** (factory assembly), L12/L45 Chang (vocational tasks).

### §7 Impact — mix real context stats with honestly-labelled targets
| Impact claim | Backing | Source |
|---|---|---|
| Baseline to beat | 36.3% employment / 8% competitive | evidence-base §2 |
| AT improves independence in daily tasks | scoping review + RCT | L9, L10 |
| AT improves job performance / task completion | systematic review + pilots | L44, L45, L46 |
| Prompting reduces caregiver reliance | video/audio prompting studies | L41, L42, L43 |
| **Honest caveat to state** | long-term employment-retention evidence is still thin | L21, L53 (and LeapSpace's own gap note) |

### §8 Feasibility
- Cost/affordability + privacy-by-design answer the adoption barriers (L17, L19, L20, L57).
- Co-design + training as adoption strategy (L17, L20, L60) — cite as our deployment plan.

---

## Honest limitations to acknowledge (turn into strength, don't hide)
1. Smart-mirror efficacy evidence is mostly **feasibility/short-term**, not long-term employment retention (LeapSpace §4, §6). → Frame our pilot as addressing this gap.
2. No **direct** head-to-head of smart mirror vs. other prompting modalities exists yet. → Positions us as novel, not derivative.
3. Thailand cognitive-disability employment data is coarse (register categories vs. functional-difficulty survey differ). → State which lens each number uses.

## Reference handling for the final document
LeapSpace's 61 refs are real and citable. For the submission: pull only the
~20 we actually cite (the ones mapped above), renumber them, and merge with the
Thai policy/statistics sources from evidence-base.md into one reference list.
Do NOT paste all 61 — most are supporting depth we don't need in 10 pages.
