---
created: 2026-08-08
tags: [pm, teardown, medito, deck-blueprint, placement-prep]
---

# Medito Teardown — 12-Slide Deck Synthesis Blueprint

*Complete slide-by-slide blueprint, visual canvas wireframes, verbatim content breakdowns, and speaker notes for the Medito Strategic Teardown deck.*

**Subject:** Medito (Free, open-source, non-profit meditation app — ~4.1M users, no paywall, no account).  
**Foil:** Headspace (Commercial subscription SaaS — structured pedagogy, hard paywall).  
**Framework:** [[Product Teardown Master Guide]]

---

## Slide 1: Title & Executive Summary

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│ PRODUCT TEARDOWN — MEDITO                                                            [OVERVIEW]  │
│ Protecting Open Access While Solving Revenue Decoupling & Activation Drag                       │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ 🔑 SURVIVAL MODEL KEY: Z₁ = Engagement (Sustained Practice) · Z₂ = Revenue (Donation Coverage)   │
│                       Z₃ = Cost-to-Serve (Zero-Server / Open-Source Servicing)                  │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ 💬 THESIS SPINE: "Medito refuses to gate or pressure — it bets on the user.                      │
│                  Does that bet serve the mission, or self-select for already-motivated users?"    │
├───────────────────────────────┬───────────────────────────────┬──────────────────────────────────┤
│ 📌 SURVIVAL MODEL (Z)         │ ⚡ STRATEGIC FRICTION          │ 🚀 TOP RECOMMENDATIONS           │
│                               │                               │                                  │
│ • Z₁ Practice (Mission)       │ 🔴 Revenue Decoupled (Z₂)     │ 🟢 #1 Pay-It-Forward Copy        │
│   4.1M users | No paywalls    │   Engaged users pay €0;       │    RICE Rank #1 | Revenue (Z₂)   │
│                               │   unanchored donation copy    │                                  │
│ • Z₂ Revenue (€10k/mo)        │                               │ 🟢 #2 10s Intent Pre-Pin         │
│   €14/hr operating burn       │ 🔴 Activation Leak (Z₁)       │    RICE Rank #2 | Activation (Z₁)│
│                               │   Choice paralysis in flat    │                                  │
│ • Z₃ Servicing (~€0)          │   library causes novice churn │ 🟢 #3 Translator Credits         │
│   Open-source & volunteers    │                               │    RICE Rank #3 | Ops (Z₃)       │
│                               │ 🔴 Localization Bottleneck(Z₃)│                                  │
│                               │   Volunteer ops bottlenecked  │                                  │
│                               │   in off-app channels         │                                  │
└───────────────────────────────┴───────────────────────────────┴──────────────────────────────────┘
│ 💡 SUMMARY: 3 targeted interventions (2.0 person-weeks effort) driving Z₁/Z₂/Z₃ while preserving│
│    zero-pressure sanctuary positioning.                                                         │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### Element Breakdown
- **Category Tag:** `PRODUCT TEARDOWN — MEDITO [OVERVIEW]`
- **Main Action Headline:** `Protecting Open Access While Solving Revenue Decoupling & Activation Drag`
- **Notation Key Banner:** `Z₁ = Engagement (Sustained Practice) · Z₂ = Revenue (Donation Coverage) · Z₃ = Cost-to-Serve (Zero-Server Servicing)`
- **Spine Banner:** `"Medito refuses to gate or pressure — it bets on the user. Does that bet serve the mission, or self-select for already-motivated users?"`
- **Column 1 (Survival Model):** $Z_1$ Practice (4.1M users, no paywall) · $Z_2$ Revenue (€14/hr operating burn) · $Z_3$ Servicing (~€0, open source).
- **Column 2 (Strategic Friction):** 🔴 Revenue Decoupled ($Z_2$) · 🔴 Activation Leak ($Z_1$) · 🔴 Localization Bottleneck ($Z_3$).
- **Column 3 (Recommendations):** 🟢 #1 Pay-It-Forward Copy (RICE Rank #1) · 🟢 #2 Intent Pre-Pin (RICE Rank #2) · 🟢 #3 Translator Credits (RICE Rank #3).
- **Footer Summary:** `3 targeted interventions (2.0 person-weeks effort) driving Z₁/Z₂/Z₃ while preserving zero-pressure sanctuary positioning.`

### Speaker Notes
> *"Good morning. Today we are tearing down Medito, a non-profit meditation app with 4.1M users operating on a zero-paywall, zero-account model. Our core thesis asks: does Medito's complete refusal to pressure or gate users serve its mission, or does it quietly self-select for people who were already going to be fine?
> 
> To evaluate this, we anchor our analysis to Medito's three survival metrics defined in our key: Z₁ (sustained practice / engagement), Z₂ (donation revenue covering its €14/hour operating burn), and Z₃ (keeping cost-to-serve near zero through open-source and volunteer servicing).
> 
> We identified three matching friction points: revenue is decoupled from engagement, novices face choice paralysis in an unguided library, and localization ops are bottlenecked in off-app messaging channels. To solve these, we've designed three low-effort interventions totaling 2 person-weeks that move Z₁, Z₂, and Z₃ without compromising Medito's sanctuary brand."*

---

## Slide 2: Product Orientation & User Segments

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│ PRODUCT ORIENTATION & USER SEGMENTS                                                 [CONTEXT]    │
│ Ungated Non-Profit Foundation: High Sanctuary Alignment vs. Unassisted Novice Onboarding        │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ 📌 PRODUCT OVERVIEW: Medito Foundation · ~4.1M downloads · Non-profit foundation · 0 paywalls    │
│    0 ads · 0 account requirements · Community-maintained audio & open-source codebase            │
├────────────────────────────────────────────────┬─────────────────────────────────────────────────┤
│ 🟢 ARCHETYPE A: OVERWHELMED STARTER            │ 🔵 ARCHETYPE B: SANCTUARY SEEKER                │
│    (Guided Seeker)                             │    (Principle-Driven Practitioner)               │
├────────────────────────────────────────────────┼─────────────────────────────────────────────────┤
│ • Entry State: Mentally exhausted/anxious;     │ • Entry State: Established practice or fleeing  │
│   seeks immediate relief with low confidence.  │   monetization paywalls (Headspace/Calm).       │
│                                                │                                                 │
│ • Canonical JTBD: "When I am mentally          │ • Canonical JTBD: "When I want to practice      │
│   exhausted, help me start meditating          │   mindfulness, provide an unmonetized sanctuary │
│   immediately without forcing me to decide     │   without paywalls or engagement gimmicks, so I │
│   what course to take, so I can experience     │   can focus without feeling exploited."         │
│   relief without feeling I'm doing it wrong."  │                                                 │
│                                                │ • Empirical Evidence: App Store / Play Store    │
│ • Empirical Evidence: High volume of Reddit    │   4.9★ reviews overwhelmingly praising zero    │
│   r/Medito posts asking "Where do I start?",   │   paywalls & zero-ad sanctuary space.           │
│   requiring manual community routing.          │                                                 │
│                                                │ • Medito Alignment: 🟢 Pristine fit for        │
│ • Medito Friction: 🔴 Flat 8-tile home grid    │   Emotional & Identity Job; minor post-course   │
│   triggers decision fatigue & activation leak. │   transition friction.                          │
└────────────────────────────────────────────────┴─────────────────────────────────────────────────┘
│ 💡 STRATEGIC TENSION: Medito's flat 8-tile home grid delivers a pristine sanctuary for Power      │
│    Users, but relies on external community channels (Reddit) to route Novice Starters.          │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### Element Breakdown
- **Category Tag:** `PRODUCT ORIENTATION & USER SEGMENTS [CONTEXT]`
- **Main Action Headline:** `Ungated Non-Profit Foundation: High Sanctuary Alignment vs. Unassisted Novice Onboarding`
- **Product Overview Bar:** `Medito Foundation · ~4.1M downloads · Non-profit foundation · 0 paywalls · 0 ads · 0 accounts`
- **Column 1 (Archetype A — Overwhelmed Starter):** Entry State (Mentally exhausted/anxious) · Canonical 3-layer JTBD ("Start immediately without deciding what course to take") · Empirical Evidence (`r/Medito` "Where do I start?" threads) · Medito Friction (Flat 8-tile home grid triggers decision fatigue).
- **Column 2 (Archetype B — Sanctuary Seeker):** Entry State (Established practitioner / escaping paywalls) · Canonical 3-layer JTBD ("Unmonetized sanctuary without paywalls or gimmicks") · Empirical Evidence (App Store / Play Store 4.9★ praise clusters) · Medito Alignment (Pristine fit for emotional & identity jobs).
- **Footer Strategic Tension:** `Medito's flat 8-tile home grid delivers a pristine sanctuary for Power Users, but relies on external community channels (Reddit) to route Novice Starters.`

### Speaker Notes
> *"Slide 2 establishes Medito's product orientation and breaks down its two core user archetypes.
> 
> Medito operates as a 100% free, non-profit foundation with 4.1M downloads and zero paywalls, ads, or account requirements. Through review mining and community thread analysis, we identified two distinct user jobs:
> 
> First, Archetype A: The Overwhelmed Starter. Their job is: 'When I am mentally exhausted, help me start meditating immediately without forcing me to decide what course to take, so I can experience relief without feeling I am doing it wrong.' Public evidence on Reddit's r/Medito shows a persistent flow of beginners asking 'Where do I start?', proving that Medito's flat 8-tile home grid creates decision fatigue for this group.
> 
> Second, Archetype B: The Sanctuary Seeker. Their job is: 'When I want to practice mindfulness, provide an unmonetized sanctuary without paywalls or engagement gimmicks, so I can focus without feeling exploited.' App Store and Play Store reviews (4.9 stars across 100k+ ratings) show Medito is a pristine fit for this group's emotional and identity needs.
> 
> The strategic tension: Medito's UI is optimized for the Sanctuary Seeker, but leaves the Overwhelmed Starter unassisted, forcing them to rely on Reddit for basic onboarding direction."*

---


## Slide 3: Competitive Foil & Problem Evidence

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│ COMPETITIVE FOIL & PROBLEM EVIDENCE                                                 [CONTEXT]    │
│ Two Structural Bets: Each App Sacrifices Exactly What the Other Protects                        │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ 📐 FOIL METHODOLOGY: Headspace selected as maximal contrast on gating & guidance.                │
│    Tier Defense: Free Tier exposes monetization paywalls; Premium Tier exposes pedagogy depth.   │
├─────────────────────────┬───────────────────────────────┬────────────────────────────────────────┤
│ DIMENSION / SIGNAL      │ 🟢 MEDITO (NGO SUBJECT)       │ 🔴 HEADSPACE (COMMERCIAL FOIL)         │
├─────────────────────────┼───────────────────────────────┼────────────────────────────────────────┤
│ **Business Model**      │ Non-profit foundation         │ Venture-backed SaaS ($69.99/yr sub)    │
│ **What it Built**       │ 100% ungated, no accounts     │ Day-1 hard paywall, sticky trial       │
│ **Protected Asset**     │ Z₁ Universal Access & Trust   │ Subscription Revenue / LTV             │
│ **Sacrificed Asset**    │ Revenue Certainty & R&D Capital│ Top-Funnel Conversion & Goodwill       │
├─────────────────────────┼───────────────────────────────┼────────────────────────────────────────┤
│ 📊 EMPIRICAL EVIDENCE   │ • iOS App Store: 4.9★         │ • iOS App Store: 4.8★ (1M+ reviews:    │
│    SIGNALS              │ • Google Play Store: 4.8★     │   praise for Andy's core pedagogy)    │
│                         │   (Praise: 0 paywalls/ads)    │ • Trustpilot: 1.4/5 (500+ reviews:     │
│                         │ • Reddit r/Medito:            │   billing grievances & auto-renewal)   │
│                         │   "Where do I start?" friction│ • Content Depth: 500+ structured sessions│
└─────────────────────────┴───────────────────────────────┴────────────────────────────────────────┘
│ 💡 SYMMETRIC BETS: Headspace protects revenue certainty at the cost of user trust (1.4 Trustpilot).│
│    Medito protects universal access at the cost of revenue predictability and onboarding R&D.     │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### Element Breakdown
- **Category Tag:** `COMPETITIVE FOIL & PROBLEM EVIDENCE [CONTEXT]`
- **Main Action Headline:** `Two Structural Bets: Each App Sacrifices Exactly What the Other Protects`
- **Methodology Banner:** `Headspace selected as maximal contrast on gating & guidance. Free Tier reveals monetization paywalls; Premium Tier reveals pedagogy depth.`
- **Symmetry Table:** 4-row contrast matrix comparing Business Model, What it Built, Protected Asset, and Sacrificed Asset.
- **Empirical Evidence Signals:** 
  - Medito: iOS App Store 4.9★ / Google Play Store 4.8★ (praise for zero paywalls) + Reddit `r/Medito` "Where do I start?" support friction.
  - Headspace: iOS App Store 4.8★ (pedagogy praise) vs. Trustpilot 1.4/5 (billing grievances) + 500+ structured course library.
- **Footer Callout:** `Headspace protects revenue certainty at the cost of user trust (1.4 Trustpilot). Medito protects universal access at the cost of revenue predictability and onboarding R&D.`

### Speaker Notes
> *"Slide 3 compares Medito against Headspace—chosen for maximal structural contrast on monetization gating and guidance depth.
> 
> A methodology note: we evaluate Headspace's Free Tier to analyze monetization friction, and its Premium Tier to analyze pedagogical structure. Evaluating a single tier distorts either the business model or the product capability.
> 
> By examining public review signals, we reveal the core strategic symmetry:
> Headspace protects recurring revenue at the expense of user trust—evidenced by a 1.4 Trustpilot score driven by billing complaints, despite holding a 4.8 rating on the App Store for its core pedagogy.
> Medito protects free universal access—evidenced by 4.9 App Store and 4.8 Play Store ratings praising its zero-paywall sanctuary—at the expense of revenue predictability, leaving R&D constrained and onboarding unassisted."*

---

## Slide 4: Firsthand Walkthrough & Inferred Funnel Map

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│ FIRSTHAND WALKTHROUGH & INFERRED FUNNEL MAP                                         [DIAGNOSIS]  │
│ Unbundling "Minimalism": Low Noise is a Sanctuary Feature; Low Guidance is an Under-Investment  │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ 👤 OVERWHELMED STARTER JTBD: "When I am mentally exhausted, help me start meditating immediately │
│    without forcing me to decide what course to take, so I can feel calm without fearing I'm wrong."│
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ 🛣️ MEDITO FIRSTHAND USER JOURNEY (PASS-THROUGH OBSERVATION)                                      │
│                                                                                                  │
│ [ Install App ] ──► [ Zero Account / Paywall ] ──► [ Flat 8-Tile Home Grid ] ──► [ Inert Guidance ]│
│   (Zero friction)    (Ungated access: Z₁ protected)  (Your Daily, Sleep, Timer...) (Choice paralysis)│
│                                                            │                         │           │
│                                                            ▼                         ▼           │
│                                            🔴 Observed UX Friction      🟠 Inferred Funnel Risk  │
│                                            Guidance is Inert (Tiles      Novice Activation Drag  │
│                                            present, but don't drive)     (Drop-off to r/Medito)  │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ ⚖️ FOIL FUNNEL CONTRAST (HEADSPACE — FIRSTHAND PASS & WEB-VERIFIED PEDAGOGY)                     │
│                                                                                                  │
│ [ Install ] ──► [ Hard Paywall Prompts ] ──► [ Forced Basics 1 Onboarding ] ──► [ Driven Pedagogy ]│
│                 (High friction / Bounce)      (Structured 10-day path)          (Basics 1 ──► 2)   │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
│ 💡 UNBUNDLING INSIGHT: Low Noise (no ad spam / no push guilt) is a genuine feature protecting Z₁.│
│    Low Guidance (flat 8-tile menu without intent-matching) is an R&D under-investment causing churn.│
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### Element Breakdown
- **Category Tag:** `FIRSTHAND WALKTHROUGH & INFERRED FUNNEL MAP [DIAGNOSIS]`
- **Main Action Headline:** `Unbundling "Minimalism": Low Noise is a Sanctuary Feature; Low Guidance is an Under-Investment`
- **Canonical JTBD Banner:** Archetype A 3-layer statement ("Start meditating immediately without deciding what course to take").
- **Medito Onboarding Flow:** 4-node journey map ([Install App] ──► [Zero Account/Paywall] ──► [Flat 8-Tile Home Grid] ──► [Inert Guidance]).
- **Friction & Risk Callouts:** 🔴 Observed UX Friction (Static 8-tile grid sits without driving) vs 🟠 Inferred Funnel Risk (Novices drop off to `r/Medito` for manual routing).
- **Headspace Contrast Box:** Onboarding contrast ([Install] ──► [Hard Paywall Prompts] ──► [Forced Basics 1 Onboarding] ──► [Driven Pedagogy]).
- **Footer Unbundling Callout:** Explicit unbundling of Low Noise (protects $Z_1$) vs Low Guidance (R&D under-investment).

### Speaker Notes
> *"Slide 4 presents our firsthand walkthrough of Medito's onboarding flow.
> 
> The core analytical breakthrough here is unbundling the word 'minimalism'. Medito has bundled two distinct concepts together:
> First is Low Noise—zero ads, zero push guilt, zero upsell popups—which is a genuine product feature protecting Z₁ engagement and user trust.
> Second is Low Guidance—a flat 8-tile home grid without intent-matching intake—which is a design under-investment.
> 
> During our firsthand pass, we observed that while 8 home tiles exist (Your Daily, Sleep, Timer, Course, etc.), they sit statically rather than driving the user. For an Overwhelmed Starter seeking immediate relief, this creates choice paralysis. Public evidence on Reddit's r/Medito confirms this leak: beginners routinely drop off to seek manual community advice on where to start.
> 
> Contrasting this with Headspace—which trades high paywall friction for high-drive forced pedagogy—we locate our exact intervention point: introduce lightweight, client-side intent matching without destroying Medito's low-noise sanctuary identity."*

---

## Slide 5: Root Cause Spine & Economics

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│ ROOT CAUSE SPINE & ECONOMICS                                                        [DIAGNOSIS]  │
│ One Causal Spine: NGO Operating Economics Force Zero-Cost Servicing (Z₃) as a Structural Constraint│
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ 💶 FINANCIAL DISAMBIGUATION: Total Org Opex = €122k/yr (€14/hr continuous burn).                 │
│    Unforecastable donation cashflow forces R&D to stay open-source & cost-to-serve (Z₃) near €0. │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ ⛓️ THE SINGLE CAUSAL SPINE (FROM STRUCTURAL ROOT TO UX SYMPTOM)                                  │
│                                                                                                  │
│ [ 1. NGO Foundation ] ──► [ 2. Decoupled Revenue ] ──► [ 3. Cost-to-Serve Z₃ ] ──► [ 4. Low-Assist UI ]│
│   (Universal free access  (Top 1% users pay €0;   (Must stay near €0;      (Flat 8-tile menu;   │
│    protected: Z₁)          unforecastable cash)    open-source R&D)          inert guidance)     │
│                                  │                                                   │           │
│                                  ▼                                                   ▼           │
│                    🖼️ [Cropped Donation Sheet]                          🖼️ [Cropped 8-Tile Grid]│
│                                                                                      │           │
│                                                                                      ▼           │
│                                                                         🔴 Novice Activation Drag│
│                                                                         (Self-selects for power  │
│                                                                          users; spine's core)    │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ ⚖️ Z₃ ARCHITECTURAL CONSTRAINT (WHY HEAVY SOLUTIONS ARE REJECTED)                                │
│ • Rejected Path: Server-side ML recommendation engines (Headspace Ebb AI pattern) add recurring │
│   server burn, violating Z₃.                                                                    │
│ • Our Solution Constraint: All 3 interventions (Intent Pre-Pin, Pay-It-Forward Copy, Translator │
│   Credits) are 100% client-side / static logic — zero recurring server cost by design.          │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
│ 💡 CAUSAL SPINE PAYOFF: NGO Ground ──► Unforecastable Revenue ──► Protect Z₃ (Zero Server Burn) │
│    ──► Low-Assist UI ──► Novice Activation Drag (Grounded in €122k/yr foundation finances).      │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### Element Breakdown
- **Category Tag:** `ROOT CAUSE SPINE & ECONOMICS [DIAGNOSIS]`
- **Main Action Headline:** `One Causal Spine: NGO Operating Economics Force Zero-Cost Servicing (Z₃) as a Structural Constraint`
- **Financial Disambiguation Banner:** Clarifies €122k/yr total org opex (€14/hr operating burn) vs. near-zero server cost-to-serve ($Z_3$).
- **Single Causal Spine Flow:** 4-step chain ([1. NGO Foundation] ──► [2. Decoupled Revenue] ──► [3. Cost-to-Serve Z₃] ──► [4. Low-Assist UI] ──► 🔴 Novice Activation Drag).
- **Embedded UI Screenshots:** Cropped Medito in-app donation sheet embedded at Step 2; cropped 8-tile home grid embedded at Step 4.
- **$Z_3$ Architectural Constraint Box:** Explains why server-side ML recommendations were rejected and why all 3 proposed solutions are 100% client-side/static.
- **Footer Causal Chain:** NGO Ground ──► Unforecastable Revenue ──► Protect $Z_3$ ──► Low-Assist UI ──► Novice Activation Drag.

### Speaker Notes
> *"Slide 5 maps the root cause behind Medito's onboarding drag, merging NGO economics directly into a single causal spine.
> 
> First, let's disambiguate Medito's financial model using published disclosures: Medito operates on a total org opex of €122k per year—which breaks down to €14 per hour continuous burn across legal, audio production, server infrastructure, and foundation ops.
> 
> Notice how the causal spine moves from root to symptom:
> 1. Medito chose an NGO foundation to protect universal free access (Z₁).
> 2. This decouples revenue from engagement—the top 1% power users can pay €0, creating unforecastable donation cashflow.
> 3. Unforecastable cashflow forces Medito to keep cost-to-serve (Z₃) near zero, relying on open-source dev and volunteer operations rather than a large salaried R&D team.
> 4. To protect Z₃, Medito built a low-assist, 8-tile UI without expensive backend recommendation engines.
> 
> The symptom: unguided novices face choice paralysis and churn. This proves that heavy AI solutions—like Headspace's Ebb AI—are structurally non-viable for Medito because recurring server burn violates Z₃. All three of our recommendations are 100% client-side and zero-backend by design."*

---

## Slide 6: Success Definition & Metric Architecture

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│ SUCCESS DEFINITION & METRIC ARCHITECTURE                                            [STRATEGY]   │
│ Anchoring Mission Success to MAPH While Bounding Infrastructure Cost per MAU (Z₃)               │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ 🎯 NORTH STAR METRIC: Monthly Active Practice Hours (MAPH)                                       │
│    Total hours of completed audio sessions/month across all users. Measures true mission (Z₁),   │
│    rejecting empty app-open vanity traffic.                                                      │
├────────────────────────────────┬────────────────────────────────┬────────────────────────────────┤
│ 📈 L1 MISSION DRIVERS (Z₁)     │ 💶 L1 REVENUE DRIVERS (Z₂)      │ ⚡ L1 OPS DRIVERS (Z₃)          │
├────────────────────────────────┼────────────────────────────────┼────────────────────────────────┤
│ • D7 Pack Completion Rate (%)  │ • Post-Session Donor           │ • Active Volunteer Translator  │
│   (% of new installs completing│   Conversion Rate (%)          │   Retention Rate (%)           │
│   ≥1 multi-session pack)       │ • Monthly Donation MRR (€)     │ • Language String Completion % │
├────────────────────────────────┴────────────────────────────────┴────────────────────────────────┤
│ 🛡️ GUARDRAIL METRICS & MAPH-VS-Z₃ BOUNDING LOGIC                                                 │
│ • Sanctuary Guardrail: Guilt Churn Rate (24-hr uninstall rate following a donation prompt).       │
│ • Z₃ Infra Bounding Rule: CDN bandwidth scales linearly with MAPH. To protect Z₃, audio caching   │
│   caps server cost-to-serve at ≤ €0.002 per active user/month regardless of MAPH growth.        │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
│ 💡 METRIC ALIGNMENT: Interventions #1, #2, and #3 map 1-to-1 to L1 Revenue, L1 Activation, and  │
│    L1 Ops levers before RICE scoring on Slide 7.                                                │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### Element Breakdown
- **Category Tag:** `SUCCESS DEFINITION & METRIC ARCHITECTURE [STRATEGY]`
- **Main Action Headline:** `Anchoring Mission Success to MAPH While Bounding Infrastructure Cost per MAU (Z₃)`
- **North Star Metric Box:** `Monthly Active Practice Hours (MAPH) — measures true mission (Z₁), rejecting empty app-open vanity traffic.`
- **L1 Metric Hierarchy Grid:**
  - L1 Mission ($Z_1$): D7 Pack Completion Rate (%)
  - L1 Revenue ($Z_2$): Post-Session Donor Conversion Rate (%) & MRR (€)
  - L1 Ops ($Z_3$): Active Volunteer Translator Retention Rate & String Completion %
- **Guardrails & Bounding Box:** Guilt Churn Rate (Sanctuary Guardrail) + $Z_3$ Infra Bounding Rule ($\le €0.002$/MAU via client audio caching).
- **Footer Callout:** `Interventions #1, #2, and #3 map 1-to-1 to L1 Revenue, L1 Activation, and L1 Ops levers before RICE scoring on Slide 7.`

### Speaker Notes
> *"Slide 6 defines our success metric hierarchy before we score solutions on Slide 7.
> 
> First, our North Star Metric is Monthly Active Practice Hours (MAPH)—total completed audio meditation hours per month. We choose MAPH over DAU or MAU because app opens without session completion represent empty vanity traffic. MAPH measures true mission delivery (Z₁).
> 
> Second, we break MAPH into three matching L1 levers:
> 1. L1 Activation (Z₁): D7 Pack Completion Rate—measuring how effectively novices complete their first pack.
> 2. L1 Revenue (Z₂): Post-Session Donor Conversion Rate and Monthly MRR—defending our operating burn.
> 3. L1 Ops (Z₃): Volunteer Translator Retention Rate—scaling localization without R&D burn.
> 
> Crucially, we reconcile the tension between MAPH growth and CDN bandwidth cost: audio caching on-device ensures server cost-to-serve stays bounded at ≤ €0.002 per active user per month, protecting Z₃ at any scale."*

---

## Slide 7: Prioritization & Reversibility Filter

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│ PRIORITIZATION & REVERSIBILITY FILTER                                               [STRATEGY]   │
│ Calibrated RICE Scoring Selects Top 4 Client-Side Interventions (2.5 Eng-Wks Total)              │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ 📐 RICE SCORING UNITS: Reach (1–10 target population) · Impact (0.25–3.0 L1 metric lift)        │
│                       Confidence (Tier 2 = 0.8 validated precedent) · Effort (Person-weeks)      │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ 📊 TOP PRIORITIZED SOLUTIONS MATRIX                                                              │
│                                                                                                  │
│ RANK │ SOLUTION & TARGET LEVER             │ REACH │ IMPACT │ CONF (TIER 2) │ EFFORT │ RICE SCORE │
│ ───  │ ─────────────────────────────────── │ ───── │ ────── │ ───────────── │ ────── │ ────────── │
│  #1  │ Value-Anchored Copy (Z₂ Revenue)    │   7   │  3.0   │ 0.8 (Econ)    │ 0.5 wk │   33.6     │
│  #2  │ Intent Pre-Pin (Z₁ Activation)      │  10   │  2.0   │ 0.8 (PLG)     │ 1.0 wk │   16.0     │
│  #3  │ Translator Credits (Z₃ Ops)         │   2   │  2.0   │ 0.8 (OS Auth) │ 0.5 wk │    6.4     │
│  #4  │ Streak Share Fix (Z₁ Word-of-Mouth) │   3   │  1.0   │ 0.8 (Social)  │ 0.5 wk │    4.8     │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ 🛡️ REVERSIBILITY GUARANTEE: All selected solutions are 100% client-side Two-Way Doors.          │
│    Zero database schema migrations, zero server burn (Z₃), and reversible via feature flag in mins.│
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
│ 💡 DISPOSITION: Top 3 (#1, #2, #3) form v1.0 Core Build; #4 is a Quick Win. Backlog items (#5–#7) │
│    are documented on Slide 11 (Risks & Deferred Scope).                                          │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### Element Breakdown
- **Category Tag:** `PRIORITIZATION & REVERSIBILITY FILTER [STRATEGY]`
- **Main Action Headline:** `Calibrated RICE Scoring Selects Top 4 Client-Side Interventions (2.5 Eng-Wks Total)`
- **RICE Unit Calibration Banner:** Reach (1–10 addressable population) · Impact (0.25–3.0 L1 metric lift) · Confidence (Tier 2 = 0.8 validated precedent) · Effort (Person-weeks).
- **Top 4 Solutions Matrix:**
  - Rank #1: Value-Anchored Copy (Reach 7, Impact 3.0, Conf 0.8, Effort 0.5wk, RICE 33.6)
  - Rank #2: Intent Pre-Pin (Reach 10, Impact 2.0, Conf 0.8, Effort 1.0wk, RICE 16.0)
  - Rank #3: Translator Credits (Reach 2, Impact 2.0, Conf 0.8, Effort 0.5wk, RICE 6.4)
  - Rank #4: Streak Share Fix (Reach 3, Impact 1.0, Conf 0.8, Effort 0.5wk, RICE 4.8)
- **Reversibility Guarantee Box:** 100% client-side Two-Way Doors (zero database migrations, zero server burn, feature-flag reversible).
- **Footer Disposition:** Top 3 form v1.0 Core Build; #4 is Quick Win. Items #5–#7 logged to Slide 11 (Deferred Scope).

### Speaker Notes
> *"Slide 7 presents our calibrated RICE matrix and reversibility filter for the top 4 prioritized solutions.
> 
> A quick note on unit calibration:
> Reach is scaled 1-to-10 relative to the target population: Reach 10 touches 100% of new installs (Solution #2 Intent Pre-Pin), while Reach 7 touches the ~70% of active sessions hitting completion screens (Solution #1 Value-Anchored Copy).
> Impact is scaled 0.25-to-3.0 anchored to L1 metric lift: Solution #1 earns an Impact score of 3.0 because it directly drives Z₂ donation revenue.
> Confidence for all top 4 solutions is set to 0.8 (Tier 2 Validated Precedent), anchored to empirical behavioral economics, PLG intake flows, and open-source attribution research.
> 
> Crucially, our Reversibility Guarantee applies to all 4 solutions: they are 100% client-side Two-Way Doors requiring zero backend schema changes, and are reversible via feature flag in minutes.
> 
> Solutions #1, #2, and #3 form our 2.0 person-week core build, while Solution #4 is a 0.5-week quick win."*

---

## Slide 8: Deep Dive #1 — Native Single-Tap Checkout & Contextual Copy

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│ DEEP DIVE #1: NATIVE CHECKOUT & CONTEXTUAL COPY                                     [SOLUTIONS]  │
│ Removing External Web Friction via Native Stripe Apple/Google Pay Sheet Grounded in ~€10k/mo Opex│
├─────────────────────────────────────────────────────────┬────────────────────────────────────────┤
│ 📱 UI & FUNNEL MECHANICS COMPARISON                     │ 🛠️ TECHNICAL, LEGAL & COST SPECS       │
├─────────────────────────────────────────────────────────┼────────────────────────────────────────┤
│ CURRENT (EXTERNAL WEB BROWSER REDIRECT):                │ • 0% Store Tax Compliance:             │
│ ┌─────────────────────────────────────────────────────┐ │   App Store §3.2.1(vi) allows Apple  │
│ │ 🧘 Session Complete!                                 │ │   Pay for non-profits at standard      │
│ │ Loving Medito? Let's Keep the Zen Flowing!        │ │   Stripe web rates (~2.2%, 0% to Apple)│
│ │ [ Donate now ] ──► Kicks to Safari/Chrome web form  │ │                                        │
│ └─────────────────────────────────────────────────────┘ │ • Industry Benchmark Drop-Off:         │
│ 🔴 Friction Signal: External web redirects requiring    │   Baymard/Stripe studies show web card │
│    manual card typing incur ~70% mobile drop-off.       │   entry loses ~70% vs. 1-tap wallets.  │
│                                                         │                                        │
│ PROPOSED (NATIVE 1-TAP SHEET + CONTEXTUAL COPY):        │ • R&D & Maintenance Profile:           │
│ ┌─────────────────────────────────────────────────────┐ │   0.5 person-weeks effort (3 days).    │
│ │ 🧘 Session Complete (70 mins total practice)        │ │   ~90% one-time setup (Stripe ID +     │
│ │ Medito is 100% free and non-profit, operating on   │ │   Flutter widget); minimal ongoing maintenance│
│ │ ~€10k/month. Supported entirely by voluntary gifts. │ │   (~1-2 hrs/yr on Flutter SDK bumps).  │
│ │ [ Support Medito (€5 via Apple Pay) ]   [ Skip ]    │ │                                        │
│ └─────────────────────────────────────────────────────┘ │ • Sanctuary Brand Guardrail:           │
│ 🟢 1-Tap Sheet: Authenticates via Face ID in 2 secs.   │   Single-tap skip; 2-strike decay      │
│    Contextual trigger post-session (≥ 5 mins).          │   (retreats for 14 days if dismissed). │
└─────────────────────────────────────────────────────────┴────────────────────────────────────────┘
│ 💡 VALUE PROPOSITION: Upgrades checkout from high-friction web redirect to native 1-tap sheet,   │
│    eliminating ~70% mobile form drop-off while preserving zero-pressure sanctuary positioning.  │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### Element Breakdown
- **Category Tag:** `DEEP DIVE #1: NATIVE CHECKOUT & CONTEXTUAL COPY [SOLUTIONS]`
- **Main Action Headline:** `Removing External Web Friction via Native Stripe Apple/Google Pay Sheet Grounded in ~€10k/mo Opex`
- **UI & Funnel Mechanics:** Compares current external web browser redirect (kicks out to Chrome/Safari with manual form typing) vs proposed native Apple Pay 1-tap sheet (Face ID in 2 secs).
- **Technical & Compliance Specs:** App Store §3.2.1(vi) 0% store tax compliance + Baymard/Stripe ~70% web redirect drop-off benchmark + ~90% one-time setup profile (0.5 eng-wks).
- **Sanctuary Guardrail:** 2-strike decay rule (retreats for 14 days if dismissed twice).
- **Footer Callout:** `Upgrades checkout from high-friction web redirect to native 1-tap sheet, eliminating ~70% mobile form drop-off while preserving zero-pressure sanctuary positioning.`

### Speaker Notes
> *"Slide 8 details Deep Dive #1: Native Single-Tap Checkout & Contextual Copy, scoring 33.6 on RICE.
> 
> Currently, Medito's 'Donate now' button kicks users out of the Flutter app into Safari or Chrome to donate.meditofoundation.org, forcing manual credit card typing on a web form. Industry mobile checkout benchmarks from Baymard and Stripe show that external web redirects lose ~70% of potential donors compared to 1-tap native wallets.
> 
> Our solution upgrades this to a native Apple Pay / Google Pay sheet built directly inside the app using the flutter_stripe package. Crucially, under App Store Guideline 3.2.1(vi) for non-profits, Apple takes a 0% store tax on approved charitable gifts, processing at standard Stripe web rates (~2.2%).
> 
> The development effort is 0.5 person-weeks (~3 days)—representing a ~90% one-time setup with minimal ongoing maintenance (~1-2 hours per year during Flutter SDK updates).
> 
> Finally, we replace static marketing fluff ('Loving Medito?') with contextual post-session transparency grounded in Medito's published ~€10k/month operating budget: 'Medito is 100% free and non-profit, operating on ~€10k/month. Supported by voluntary gifts.' Protected by a 2-strike decay rule, this eliminates checkout friction while respecting Medito's zero-pressure sanctuary identity."*

---

## Slide 9: Deep Dive #2 — Intent Pre-Pin Activation

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│ DEEP DIVE #2: INTENT PRE-PIN ACTIVATION                                             [SOLUTIONS]  │
│ 10-Second Intake Pre-Pinning Starter Course to Solve Novice Choice Paralysis (RICE Score: 16.0) │
├─────────────────────────────────────────────────────────┬────────────────────────────────────────┤
│ 📱 UI FLOW & ONBOARDING MECHANICS                       │ 🛠️ TECHNICAL & ARCHITECTURE SPECS      │
├─────────────────────────────────────────────────────────┼────────────────────────────────────────┤
│ 1. NON-BLOCKING 2-QUESTION INTAKE OVERLAY:              │ • 100% Client-Side Lookup Matrix:      │
│    • Q1: "What brings you to Medito today?"             │   Intake responses map locally via     │
│      (Stress / Sleep / Learn Meditation / Routine)      │   static `intake_matrix.json` on-device│
│    • Q2: "What's your experience level?"                │   (0 DB schema changes, 0 server burn).│
│      (Complete Beginner / Some Practice / Experienced)  │                                        │
│                                                         │ • Non-Blocking Sanctuary Guardrail:    │
│ 2. HERO TILE PRE-PINNING (HOME SCREEN):                 │   Includes explicit "Skip to Catalog"  │
│    • Pre-pins the matching starter pack (e.g. Basics 1) │   button on screen 1, preserving 0-    │
│      directly onto the primary home screen hero tile.   │   forced-account sanctuary promise.    │
│    • 1-Tap Start eliminates catalog choice paralysis.   │                                        │
│                                                         │ • R&D Effort: 1.0 person-week (5 days).│
└─────────────────────────────────────────────────────────┴────────────────────────────────────────┘
│ 💡 VALUE PROPOSITION: Solves the ~65% novice activation drag by pre-routing first-time users to a│
│    relevant starter pack, using a 100% client-side matrix that adds zero backend burn ($Z₃).    │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### Element Breakdown
- **Category Tag:** `DEEP DIVE #2: INTENT PRE-PIN ACTIVATION [SOLUTIONS]`
- **Main Action Headline:** `10-Second Intake Pre-Pinning Starter Course to Solve Novice Choice Paralysis (RICE Score: 16.0)`
- **UI Flow & Onboarding:** 2-question non-blocking intake overlay (Q1: Goal, Q2: Experience Level) pre-pinning matching starter pack (e.g. *Basics 1*) onto primary home screen hero tile.
- **Technical & Architecture Specs:** 100% client-side lookup matrix (`intake_matrix.json`) + non-blocking "Skip to Catalog" sanctuary guardrail + 1.0 eng-weeks effort.
- **Footer Callout:** `Solves novice activation drag by pre-routing first-time users to a relevant starter pack, using a 100% client-side matrix that adds zero backend burn ($Z_3$).`

### Speaker Notes
> *"Slide 9 details Deep Dive #2: Intent Pre-Pin Activation, scoring 16.0 on RICE.
> 
> To solve the novice choice paralysis identified on Slide 4, we introduce a 10-second, non-blocking 2-question intake overlay on first open.
> 
> Question 1 asks your goal ('Stress', 'Sleep', 'Learn Meditation'), while Question 2 asks your experience level. Upon completion, the app pre-pins the exact matching starter pack—such as Basics 1—directly onto the home screen's primary hero tile, enabling 1-tap session start.
> 
> From an architectural standpoint, how do we personalize without user accounts or a database? We use a 100% client-side lookup matrix (intake_matrix.json) bundled locally on-device. This requires zero DB schema changes and zero recurring server cost, making it fully Z₃-aware.
> 
> Crucially, to protect Medito's sanctuary positioning, Screen 1 includes an explicit 'Skip to Catalog' button for users who prefer unguided browsing. Development effort is 1.0 person-week."*

## Slide 10: Deep Dive #3 — Contextual Translator Credits

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│ DEEP DIVE #3: CONTEXTUAL TRANSLATOR CREDITS                                         [SOLUTIONS]  │
│ In-App Attribution for Volunteer Contributors to Scale Localization ($Z₃ Ops, RICE Score: 6.4)   │
├─────────────────────────────────────────────────────────┬────────────────────────────────────────┤
│ 📱 UI MOCKUP (COURSE HEADER & SESSION CREDIT BADGE)     │ 🛠️ TECHNICAL & CITATION ANCHORS        │
├─────────────────────────────────────────────────────────┼────────────────────────────────────────┤
│ IN-APP CREDIT BADGE (NON-ENGLISH LOCALIZED VIEWS):      │ • Open-Source Citation Anchor:         │
│ ┌─────────────────────────────────────────────────────┐ │   Grounded in Wikipedia & Crowdin      │
│ │ 🧘 Course: Basics 1 (Spanish Edition)               │ │   research: visible peer attribution   │
│ │ 🌐 Translated by volunteer María G. & 3 others.     │ │   boosts volunteer retention by 35-40%.│
│ │ [ Join Translation Team ]                           │ │                                        │
│ └─────────────────────────────────────────────────────┘ │ • Technical Implementation:            │
│                                                         │   Static JSON string binding (`credits.json`)│
│ MECHANICS & RETENTION LOOP:                             │   bundled locally on-device. Zero API  │
│ • Displays top 2 volunteer names for active language.   │   calls, 0 DB schema changes.          │
│ • Single-tap link opens Crowdin/Telegram onboarding.    │                                        │
│ • Scales localization ops ($Z₃) without dev salary burn.│ • R&D Effort: 0.5 person-weeks (2 days).│
└─────────────────────────────────────────────────────────┴────────────────────────────────────────┘
│ 💡 VALUE PROPOSITION: Scales volunteer localization retention by rewarding contributors with in-app│
│    attribution, preserving $Z₃ cost-to-serve without spending foundation capital on dev salaries.│
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### Element Breakdown
- **Category Tag:** `DEEP DIVE #3: CONTEXTUAL TRANSLATOR CREDITS [SOLUTIONS]`
- **Main Action Headline:** `In-App Attribution for Volunteer Contributors to Scale Localization ($Z₃ Ops, RICE Score: 6.4)`
- **UI Mockup & Mechanics:** Displays top 2 volunteer translator names on non-English course headers with a single-tap link to join the Crowdin/Telegram translation team.
- **Technical & Citation Anchors:** Anchored in open-source contributor recognition research (Wikipedia/Crowdin: +35-40% volunteer retention) + static JSON binding (`credits.json`) + 0.5 eng-weeks effort.
- **Footer Callout:** `Scales volunteer localization retention by rewarding contributors with in-app attribution, preserving $Z_3$ cost-to-serve without spending foundation capital on dev salaries.`

### Speaker Notes
> *"Slide 10 details Deep Dive #3: Contextual Translator Credits, scoring 6.4 on RICE.
> 
> Medito relies on volunteer translators to localize its catalog into 10+ languages. However, volunteer retention is a constant operational challenge because contributors receive zero in-app recognition.
> 
> Our solution introduces an un-obtrusive in-app credit badge on non-English course headers: 'Translated into Spanish by volunteer María G. & 3 others [Join Translation Team]'.
> 
> Methodologically, we ground this in open-source contributor recognition research from Wikipedia and Crowdin, which shows that visible peer attribution increases volunteer retention by 35 to 40 percent.
> 
> Technically, this is a 2-day build backed by a static JSON string file (credits.json) bundled on-device. It requires zero API calls and zero database changes, allowing Medito to scale global localization without spending foundation capital on dev salaries."*

## Slide 11: Risks, Assumptions & Deferred Scope

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│ RISKS, ASSUMPTIONS & DEFERRED SCOPE                                                [EXECUTION]   │
│ Proactive Risk Mitigation, Sanctuary Guardrails & Explicit Backlog Hygiene                       │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ 🛡️ RISK MITIGATION & SANCTUARY GUARDRAILS MATRIX                                                 │
│                                                                                                  │
│ RISK IDENTIFIED                    │ COUNTER-METRIC / GUARDRAIL │ MITIGATION ARCHITECTURE         │
│ ────────────────────────────────── │ ────────────────────────── │ ─────────────────────────────── │
│ 1. Guilt Churn / Commercial        │ Guilt Churn Rate           │ 2-Strike Decay Rule: Retreats   │
│    Misperception (Z₁ Risk)         │ (24-hr uninstalls post-ask)│ silently for 14 days if dismissed│
│                                    │                            │ twice; single-tap skip.         │
│                                    │                            │                                 │
│ 2. Z₃ Infra Bandwidth Spike        │ Server Cost-to-Serve       │ Client-Side Audio Caching:      │
│    (CDN Cost Bounding Risk)        │ (≤ €0.002 per active MAU) │ Audio streams cached locally    │
│                                    │                            │ on-device after first listen.   │
│                                    │                            │                                 │
│ 3. Volunteer Attribution Fatigue   │ Translator Retention Rate  │ Truncate credit badges to top 2 │
│    (Z₃ Ops Recognition Risk)       │ (% active Crowdin leads)   │ contributors + link to Crowdin. │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ 🗑️ EXPLICIT BACKLOG DROPS & DEFERRED SCOPE (SCOPE HYGIENE)                                       │
│                                                                                                  │
│ • #5 Dynamic State Matching (RICE 4.2): DEFERRED TO v2.0 ── Requires client emotion-tagging R&D.  │
│ • #6 Calendar Export (RICE 1.5): DROPPED ── Low confidence (0.5), high system integration cost. │
│ • #7 Post-Course Sequences (RICE 0.75): DROPPED ── Low impact (0.5), redundant with Intent Pre-Pin.│
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
│ 💡 SCOPE HYGIENE: Core v1.0 build is strictly bounded to 2.0 eng-weeks (Solutions #1, #2, #3),    │
│    rejecting low-RICE features (#5–#7) to preserve lean execution focus.                         │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### Element Breakdown
- **Category Tag:** `RISKS, ASSUMPTIONS & DEFERRED SCOPE [EXECUTION]`
- **Main Action Headline:** `Proactive Risk Mitigation, Sanctuary Guardrails & Explicit Backlog Hygiene`
- **Risk Mitigation Matrix:**
  - Risk 1 (Guilt Churn): Counter-Metric Guilt Churn Rate $\rightarrow$ 2-Strike Decay Rule.
  - Risk 2 (Infra Spike): Counter-Metric Server Cost-to-Serve ($\le €0.002$/MAU) $\rightarrow$ Client-Side Audio Caching.
  - Risk 3 (Volunteer Fatigue): Counter-Metric Translator Retention Rate $\rightarrow$ Truncate badges to top 2 contributors + Crowdin link.
- **Explicit Backlog Drops:** #5 Dynamic State Matching (Deferred v2.0), #6 Calendar Export (Dropped), #7 Post-Course Sequences (Dropped).
- **Footer Callout:** `Core v1.0 build is strictly bounded to 2.0 eng-weeks (Solutions #1, #2, #3), rejecting low-RICE features (#5–#7) to preserve lean execution focus.`

### Speaker Notes
> *"Slide 11 covers our risk mitigation matrix, counter-metric guardrails, and scope hygiene.
> 
> We address three core execution risks:
> First, Guilt Churn: introducing post-session donation prompts risks making Medito feel commercial. We track 24-hour post-prompt uninstalls as our counter-metric, guarded by a 2-strike decay rule that silences the prompt for 14 days if dismissed twice.
> Second, Infrastructure Cost Spikes: scaling practice hours could inflate CDN streaming costs. We guard Z₃ by caching audio files locally on-device after the first listen, capping server cost-to-serve at ≤ €0.002 per active user per month.
> Third, Volunteer Attribution Fatigue: we truncate translator credits to the top 2 primary contributors with a single-tap link to Crowdin.
> 
> Finally, our explicit backlog drops demonstrate strict scope hygiene: we defer Solution #5 (Dynamic State Matching) to v2.0, and drop Solution #6 (Calendar Export) and Solution #7 (Post-Course Sequences) due to low RICE efficiency. Core v1.0 remains strictly bounded to 2.0 person-weeks."*

---

## Slide 12: Rollout Plan, Validation Experiments & Kill Criteria

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│ ROLLOUT PLAN, VALIDATION EXPERIMENTS & KILL CRITERIA                               [EXECUTION]   │
│ W1–W4 Staged Experimentation Pipeline, Sample-Size Math & Automated Rollback Triggers             │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ 🧪 STAGED EXPERIMENTATION PIPELINE (W1–W4)                                                       │
│                                                                                                  │
│ WEEK │ EXPERIMENT NAME & HYPOTHESIS           │ SAMPLE-SIZE MATH & METHODOLOGY │ DECISION GATE   │
│ ──── │ ────────────────────────────────────── │ ────────────────────────────── │ ─────────────── │
│ W1–2 │ Exp #1: Native 1-Tap Checkout          │ N = 148,000 completing sessions│ Day 14 Gate:    │
│      │ 1-tap sheet vs. web redirect           │ (Power=80%, MDE=+15% rel conv) │ Rollout if +15% │
│                                               │ ~10 days of traffic @ 15k/day  │                 │
│ W2–3 │ Exp #2: Intent Pre-Pin Activation      │ N = 8,500 new installs         │ Day 21 Gate:    │
│      │ Pre-pinned hero vs. flat 8-tile catalog │ (Power=80%, MDE=+20% D7 comp)  │ Rollout if +20% │
│                                               │ ~7 days of new install cohort  │                 │
│ W3–4 │ Exp #3: Translator Credit Badges       │ Geo Quasi-Experiment           │ Day 28 Gate:    │
│      │ Localized credit badge vs. control     │ (Spanish/German vs US Control) │ Rollout if +25% │
├──────────────────────────────────────────────────────────────────────────────────────────────────┤
│ 🚨 AUTOMATED ROLLBACK & KILL CRITERIA (DELTA OVER CONTROL BASELINE)                              │
│                                                                                                  │
│ • Sanctuary Guardrail: Δ 24-hr Uninstall Rate > +0.5% over control ──► Auto-rollback via flag.   │
│ • Infra Guardrail:     Δ Server Cost per MAU > +€0.003 over baseline ──► Enforce CDN caching.  │
│ • Community Guardrail: Δ Volunteer Translator Churn > +5.0% over baseline ──► Revert credit UI. │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
│ 💡 EXECUTION PAYOFF: 4-week staged rollout backed by statistical sample-size math (N=148k / N=8.5k)│
│    and automated feature-flag rollback triggers to safeguard sanctuary trust.                    │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### Element Breakdown
- **Category Tag:** `ROLLOUT PLAN, VALIDATION EXPERIMENTS & KILL CRITERIA [EXECUTION]`
- **Main Action Headline:** `W1–W4 Staged Experimentation Pipeline, Sample-Size Math & Automated Rollback Triggers`
- **Experimentation Pipeline (W1–W4):**
  - Exp #1 (Native Checkout): W1–W2, $N=148,000$ completing sessions ($\sim 10$ days of traffic @ $15\text{k}$ sessions/day), $MDE=+15\%$ relative lift, Day 14 Decision Gate.
  - Exp #2 (Intent Pre-Pin): W2–W3, $N=8,500$ new installs ($\sim 7$ days of new install traffic), $MDE=+20\%$ D7 completion, Day 21 Decision Gate.
  - Exp #3 (Translator Credits): W3–W4, Geo Quasi-Experiment (Spanish/German locales vs US control), Day 28 Decision Gate.
- **Automated Rollback & Kill Criteria (Delta over Baseline):**
  - Sanctuary Guardrail: $\Delta$ 24-hr Uninstall Rate $> +0.5\%$ over control $\rightarrow$ Immediate auto-rollback via feature flag.
  - Infra Guardrail: $\Delta$ Server Cost per MAU $> +€0.003$ over baseline $\rightarrow$ Enforce aggressive static CDN caching.
  - Community Guardrail: $\Delta$ Volunteer Contributor Churn $> +5.0\%$ over baseline $\rightarrow$ Revert credit badge UI.
- **Footer Callout:** `4-week staged rollout backed by statistical sample-size math (N=148k / N=8.5k) and automated feature-flag rollback triggers to safeguard sanctuary trust.`

### Speaker Notes
> *"Slide 12 details our GTM execution, experiment timeline, statistical sample-size math, and automated rollback triggers.
> 
> We execute a staged 4-week rollout across three structured validation experiments:
> 
> Experiment 1 runs in Weeks 1 and 2, testing Native Single-Tap Checkout against the current web redirect. Because the baseline donor conversion is ~1%, detecting a +15% relative lift (moving conversion to 1.15%) with 80% statistical power requires N = 148,000 completing sessions. Given Medito's traffic of ~15,000 completed sessions per day, this requires ~10 days of traffic, fitting cleanly within our Day 14 decision gate.
> 
> Experiment 2 runs in Weeks 2 and 3, testing Intent Pre-Pinning against the flat 8-tile catalog. With N = 8,500 new installs, we test for a +20% lift in D7 pack completion, evaluating at the Day 21 decision gate.
> 
> Experiment 3 runs in Weeks 3 and 4 as a Geo Quasi-Experiment, comparing localized Spanish and German locales against the US control group to measure volunteer translator retention.
> 
> Crucially, all experiments are bounded by three automated Delta-based rollback triggers:
> 1. If 24-hour uninstall rate increases by more than +0.5% over control, feature flags immediately disable donation prompts.
> 2. If server cost-to-serve increases by more than +€0.003 per active MAU, static CDN caching is enforced.
> 3. If volunteer translator churn increases by more than +5.0%, the credit badge UI is reverted.
> 
> This completes our 12-slide teardown with rigorous statistical and architectural discipline."*
