---
created: 2026-08-10
tags: [pm, teardown, medito, rework-spec, placement-prep]
---

# Medito Teardown — Master Rework Specification & Execution Plan (12-Slide Conventional Blueprint)

*Static reference document containing the MECE breakdown of all feedback, updated 12-slide macro arc, quantitative corrections, and 4-tier execution roadmap.*

---

## 1. Executive Summary of Revisions

This specification incorporates external product feedback, quantitative audits, and structural reviews while adhering strictly to a conventional **12-slide format**.

### What We Are Preserving (The Core Strength)
- **Central Product Insight:** Unbundling "low noise" (a sanctuary feature) from "low guidance" (an under-investment).
- **Sanctuary Alignment:** Zero paywalls, zero soft-gating, zero pressure tactics.
- **Client-Side Technical Architecture:** Zero-server, zero-database additions protecting $Z_3$ (Cost-to-Serve).
- **Reversibility & Guardrails:** Hard rollback triggers, two-way doors, and "Guilt Churn Rate" counter-metric.
- **RICE Instrument & Speaker Notes:** Preserved intact with calibrated confidence tiers.

### What We Are Fixing (The Weak Spots)
1. **Macro Flow & Navigation:** Maintaining a 12-slide structure by consolidating related concepts into dual-purpose cards (Product + User Segments on Slide 2, Foil Matrix + Empirical Evidence on Slide 3, RICE + Reversibility on Slide 7) and adding a top breadcrumb strip.
2. **Order of Operations:** Moving Metric Architecture (Slide 6) ahead of RICE (Slide 7) so "Impact" has an explicit referent before scoring.
3. **Quantitative Rigor:** Disambiguating €14/hr operating burn, reframing Rec #1 donation copy away from organization uptime to the published "<1% donor rate", and addressing North Star vs. CDN cost tension.
4. **Typesetting & Craft:** Tightening loose leading/line-height, fixing vertical card grid alignments, and fixing currency symbol errors (₹ $\rightarrow$ €).

---

## 2. MECE Categorization of Rework Action Items

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
────────────────────── MECE CATEGORIZATION OF MEDITO TEARDOWN REWORK ──────────────────────────────
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
  ├── CATEGORY 1: Macro Sequence & Navigation (12-Slide Arc)
  │   ├── 1.1 Breadcrumb navigation strip across every slide using predictable section titles
  │   ├── 1.2 $Z_1/Z_2/Z_3$ key added directly to Cover / Title Slide
  │   ├── 1.3 Merge old Slide 3 (NGO Economics) into Slide 5 (Root Cause Spine) to eliminate duplicate logic
  │   ├── 1.4 Re-sequence slides so Users, Evidence, and Metric Architecture precede RICE & Reversibility
  │   └── 1.5 Strip repetitive metric callout bars from Deep Dive Slides (Slides 8–10)
  │
  ├── CATEGORY 2: Grounding & Evidence (Consolidated 12-Slide Integrations)
  │   ├── 2.1 Slide 2: Integrate User Segments (Novice vs. Power User split, sizing, & JTBD) with Product Intro
  │   ├── 2.2 Slide 3: Integrate Empirical Evidence (App Store/Play Store reviews, GitHub issues) with Foil Matrix
  │   ├── 2.3 Slide 7: Integrate Reversibility Filter / Two-Way Doors into RICE Prioritization Table
  │   └── 2.4 Slide 11: Consolidated Risks, Assumptions & Deferred Scope (Guardrails & Backlog drops #4–#7)
  │
  ├── CATEGORY 3: Quantitative & Analytical Rigor
  │   ├── 3.1 Disambiguate €14/hr burn (Infra Cost-to-Serve vs. Total Org Opex €122k/yr) using published finances
  │   ├── 3.2 Reframe Rec #1 Anchor from "org uptime per euro" to Medito's published "<1% of 4.1M users donate"
  │   ├── 3.3 Address MAPH vs. $Z_3$ Burn Tension: add bounding logic on Metric Architecture slide
  │   ├── 3.4 Experimentation Math: add sample-size lines, expand Phase 1 to W1–W4, label Exp #3 as Geo Quasi-Exp
  │   └── 3.5 RICE Calibration: define explicit units for Reach & Impact; document Reach 7 vs 10 inversion
  │
  ├── CATEGORY 4: Fact Accuracy & Sourcing
  │   ├── 4.1 Fix currency symbol error (₹ $\rightarrow$ €) on cover and economics slides
  │   ├── 4.2 Balance Competitive Foil: cite both Trustpilot (1.5/5) and App Store (4.8/5) to show billing vs product gap
  │   └── 4.3 Add citation anchor for Slide 10 "research shows" or downgrade confidence score to 0.5
  │
  └── CATEGORY 5: Visual Production & Typesetting Polish
      ├── 5.1 Tighten leading / line-height to eliminate orphan single words ("scale.", "driven.", "max).")
      ├── 5.2 Fix vertical grid alignment across cards (Slide 7 budget card, Slide 8 baseline, Slide 12 Exp #1 header)
      └── 5.3 Crop or replace unreadable 180px phone screenshots on Slide 5
```

---

## 3. The Target 12-Slide Macro Blueprint

| Slide # | Breadcrumb Section | Slide Title & Core Focus | Integration Strategy |
| :--- | :--- | :--- | :--- |
| **Slide 1** | **Overview** | **Title, Strategic Context & $Z$-Key** <br>Medito Strategic Teardown ground + legend for Engagement ($Z_1$), Revenue ($Z_2$), Servicing Cost ($Z_3$). | Added Notation Key & Lean Executive Grounding |
| **Slide 2** | **Context** | **Product Orientation & User Segments** <br>What Medito is + Novice vs. Power User split (sizes, habits, JTBD). | **Consolidated:** Combines Product Intro with User Segment Sizing |
| **Slide 3** | **Context** | **Competitive Foil & Problem Evidence** <br>Headspace matrix (App Store vs. Trustpilot gap) + review mining data signals. | **Consolidated:** Combines Foil Matrix with Empirical Review Signals |
| **Slide 4** | **Diagnosis** | **Firsthand Journey Walkthrough** <br>Onboarding flow mapping: Low-Noise sanctuary feature vs. Low-Guidance under-investment. | Refined onboarding map backed by Slide 3 evidence |
| **Slide 5** | **Diagnosis** | **Root Cause Spine & Economics** <br>One causal spine: NGO ground $\rightarrow$ unforecastable cashflow $\rightarrow$ $Z_3$ zero-cost servicing $\rightarrow$ inert guidance. | **Merged:** Absorbs old Slide 3 economics into causal spine |
| **Slide 6** | **Strategy** | **Success Definition & Metric Architecture** <br>North Star (MAPH), L1/L2 Drivers, $Z_3$ Infra Bounding Guardrails. | **Moved Up:** Positions metric criteria before RICE scoring |
| **Slide 7** | **Strategy** | **Prioritization & Reversibility Filter** <br>Calibrated RICE scoring table integrated with Two-Way Door / Effort classifications. | **Consolidated:** Integrates RICE Table with Reversibility Filter |
| **Slide 8** | **Solutions** | **Deep Dive #1: Value-Anchored Donation Copy** <br>Replacing generic pleas with "<1% donate" social proof copy ($Z_2$ Revenue). | Refined (Stripped metric box; reframed donation anchor) |
| **Slide 9** | **Solutions** | **Deep Dive #2: Intent Pre-Pin Activation** <br>10-second intake pre-pinning starter course to home screen ($Z_1$ Activation). | Refined (Stripped metric box; client-side lookup matrix) |
| **Slide 10** | **Solutions** | **Deep Dive #3: Contextual Translator Credits** <br>In-app attribution for volunteer localization contributors ($Z_3$ Ops). | Refined (Stripped metric box; anchored citation/confidence) |
| **Slide 11** | **Execution** | **Risks, Assumptions & Deferred Scope** <br>Consolidated risk matrix, guardrails, and explicit backlog drops (#4–#7). | **Consolidated:** Clean scope hygiene & risk summary |
| **Slide 12** | **Execution** | **Rollout Plan, Experiments & Rollback Triggers** <br>W1–W4 experiment timeline, sample-size math, geo quasi-exp label, rollback triggers. | Refined (Fixed 0-day decision gate, sample size, alignment) |

---

## 4. 4-Tier Work Roadmap & Time Costs

### Tier 1 — Structure & Navigation (Est. Time: ~2.5 Hours)
1. Add predictable breadcrumb navigation bar to top of all 12 slides (`Overview` $\rightarrow$ `Context` $\rightarrow$ `Diagnosis` $\rightarrow$ `Strategy` $\rightarrow$ `Solutions` $\rightarrow$ `Execution`).
2. Add a clear 1-line $Z_1/Z_2/Z_3$ legend to Slide 1.
3. Merge old Slide 3 (NGO Economics) into Slide 5 (Root Cause Spine) to kill structural repetition.

### Tier 2 — Grounding & Evidence (Est. Time: ~6 Hours)
1. Build **Slide 2 (Product & Users)**: Size novice vs. power user split; define JTBD for guided vs. unguided users alongside product intro.
2. Build **Slide 3 (Foil & Evidence)**: Synthesize App Store/Play Store review themes, GitHub issue logs, and Telegram community feedback into Headspace foil comparison.
3. Move **Metric Architecture (Slide 6)** ahead of **RICE Matrix (Slide 7)** so "Impact" has a clear referent before scoring.
4. Integrate Reversibility/Two-Way Door badges directly into **Slide 7 (RICE Matrix)**.
5. Build **Slide 11 (Risks & Deferred Scope)** to consolidate guardrails and document dropped backlog items (#4–#7).
6. Strip metric repetition boxes from Deep Dive Slides (Slides 8–10).

### Tier 3 — Analytical & Quantitative Fixes (Est. Time: ~3 Hours)
1. Split €14/hr into **Infra Cost-to-Serve** vs. **Total Org Opex (€122k/yr)**, citing Medito's official published financial page.
2. Reframe Rec #1 copy to: *"You're 1 of 4.1M users. Fewer than 1 in 100 has ever donated."*
3. Add bounding logic on Slide 6 showing how $Z_3$ infra cost per MAU is capped as MAPH scales.
4. Fix Slide 12 Experimentation Math: add baseline rates, sample size requirements, extend Phase 1 to W1–W4, and label Exp #3 as a Geo Quasi-Experiment.
5. Add unit definitions for Reach and Impact on Slide 7; explain why post-session banner Reach (7) differs from onboarding Reach (10).

### Tier 4 — Correctness & Polish (Est. Time: ~2 Hours)
1. Replace ₹ with € on cover and economic breakdown cards.
2. Cite both Trustpilot (1.5/5) and App Store (4.8/5) for Headspace to demonstrate product vs. billing divergence.
3. Add research source for Slide 10 (Translator Credits) or adjust confidence score to 0.5.
4. Tighten card leading/line-height to eliminate single orphan words.
5. Adjust vertical card alignment across Slides 7, 8, and 12.
6. Crop Slide 5 phone screenshots to relevant UI components.

---

## 5. Next Steps for Pair-Working

We will execute this specification section by section:
- **Part 1:** Review & validate Category 1 & Macro Sequence (Slides 1–6).
- **Part 2:** Review & validate Category 2 & Grounding Integrations (Slides 2, 3, 7, 11).
- **Part 3:** Review & validate Category 3 (Quantitative & Analytical Rigor).
- **Part 4:** Review & validate Category 4 & 5 (Fact Accuracy, Sourcing & Polish).
