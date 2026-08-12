---
created: 2026-08-11
tags: [pm, teardown, medito, claude-design-prompts, rework]
---

# Medito Teardown — Claude Design Prompts & Delta Tracker

*Claude Design generation prompts and exact delta logs for transforming Medito Teardown slides into final visual layouts.*

---

## Overview

This note tracks the exact prompt instructions for Claude Design (or visual generator tools) to render each slide of the 12-slide Medito teardown. As we iterate slide-by-slide, each section logs:
1. **Delta (What Changed):** Explicit list of edits made from the legacy/working version.
2. **Claude Design Prompt:** Copy-paste ready prompt specifying layout structure, hierarchy, typography, colors, and content containers.

---

## Slide 1: Title, Executive Summary & Z-Key

### Delta (What Changed)
- Added `[OVERVIEW]` section tag in header.
- Added top **Survival Model Notation Key Banner** explicitly defining $Z_1, Z_2, Z_3$ ($Z_1$ = Engagement/Practice, $Z_2$ = Revenue/Donation Coverage, $Z_3$ = Cost-to-Serve/Zero-Server Servicing).
- Fixed currency symbol error (changed `₹0` to `€0`).

### Claude Design Prompt

```text
Create a clean, dark-mode 16:9 executive presentation slide for a Product Teardown of "Medito" (a non-profit meditation app).

Header:
- Top Left Category: "PRODUCT TEARDOWN — MEDITO"
- Top Right Tag: "[OVERVIEW]"
- Main Headline (Bold 28px): "Protecting Open Access While Solving Revenue Decoupling & Activation Drag"

Key Banner (Full width sub-header box with subtle border):
- Icon: 🔑 "SURVIVAL MODEL KEY: Z₁ = Engagement (Sustained Practice) · Z₂ = Revenue (Donation Coverage) · Z₃ = Cost-to-Serve (Zero-Server / Open-Source Servicing)"

Spine Banner (Highlighted text box, muted background):
- Icon: 💬 "THESIS SPINE: 'Medito refuses to gate or pressure — it bets on the user. Does that bet serve the mission, or self-select for already-motivated users?'"

Three-Column Body Grid:
- Column 1: Header "📌 SURVIVAL MODEL (Z)"
  • Z₁ Practice (Mission): 4.1M users | No paywalls
  • Z₂ Revenue (€10k/mo): €14/hr operating burn
  • Z₃ Servicing (~€0): Open-source & volunteers
- Column 2: Header "⚡ STRATEGIC FRICTION"
  • 🔴 Revenue Decoupled (Z₂): Engaged users pay €0; unanchored donation copy
  • 🔴 Activation Leak (Z₁): Choice paralysis in flat library causes novice churn
  • 🔴 Localization Bottleneck (Z₃): Volunteer ops bottlenecked in off-app channels
- Column 3: Header "🚀 TOP RECOMMENDATIONS"
  • 🟢 #1 Pay-It-Forward Copy (RICE Rank #1 | Revenue Z₂)
  • 🟢 #2 10s Intent Pre-Pin (RICE Rank #2 | Activation Z₁)
  • 🟢 #3 Translator Credits (RICE Rank #3 | Ops Z₃)

Footer (Full-width callout bar at bottom):
- 💡 "SUMMARY: 3 targeted interventions (2.0 person-weeks effort) driving Z₁/Z₂/Z₃ while preserving zero-pressure sanctuary positioning."

Visual Style: Premium tech product presentation, dark slate (#0F172A) background, crisp white typography, green accents for recommendations, red accents for friction points, structured card containers.
```

---

## Slide 2: Product Orientation & User Segments

### Delta (What Changed)
- Replaced legacy Strategic Positioning slide with consolidated **Product Orientation & User Segments** (`[CONTEXT]`).
- Integrated 3-layered Christensen/Ulwick JTBD statements for Archetype A (Overwhelmed Starter) and Archetype B (Sanctuary Seeker).
- Grounded both archetypes in empirical evidence signals (`r/Medito` Reddit beginner threads vs App Store / Play Store 4.9★ review clusters) instead of unverified percentages.
- Highlighted friction point: Medito's flat 8-tile home grid creates decision fatigue for beginners.

### Claude Design Prompt

```text
Create a clean, dark-mode 16:9 presentation slide for Slide 2 of the Medito Product Teardown.

Header:
- Top Left Category: "PRODUCT ORIENTATION & USER SEGMENTS"
- Top Right Tag: "[CONTEXT]"
- Main Headline (Bold 28px): "Ungated Non-Profit Foundation: High Sanctuary Alignment vs. Unassisted Novice Onboarding"

Product Overview Sub-Header Bar (Full width, dark slate container):
- "📌 PRODUCT OVERVIEW: Medito Foundation · ~4.1M downloads · Non-profit foundation · 0 paywalls · 0 ads · 0 account requirements · Community-maintained audio & open-source codebase"

Two-Column Archetype Comparison Grid (Equal width cards):
- Left Card (Green accent border): "🟢 ARCHETYPE A: OVERWHELMED STARTER (Guided Seeker)"
  • Entry State: Mentally exhausted/anxious; seeks immediate relief with low confidence.
  • Canonical JTBD: "When I am mentally exhausted, help me start meditating immediately without forcing me to decide what course to take, so I can experience relief without feeling I'm doing it wrong."
  • Empirical Evidence: High volume of Reddit r/Medito posts asking "Where do I start?", requiring manual community routing.
  • Medito Friction: 🔴 Flat 8-tile home grid triggers decision fatigue & activation leak.

- Right Card (Blue accent border): "🔵 ARCHETYPE B: SANCTUARY SEEKER (Principle-Driven Practitioner)"
  • Entry State: Established practice or fleeing monetization paywalls (Headspace/Calm).
  • Canonical JTBD: "When I want to practice mindfulness, provide an unmonetized sanctuary without paywalls or engagement gimmicks, so I can focus without feeling exploited."
  • Empirical Evidence: App Store / Play Store 4.9★ reviews overwhelmingly praising zero paywalls & zero-ad sanctuary space.
  • Medito Alignment: 🟢 Pristine fit for Emotional & Identity Job; minor post-course transition friction.

Footer Callout (Full width banner at bottom):
- 💡 "STRATEGIC TENSION: Medito's flat 8-tile home grid delivers a pristine sanctuary for Power Users, but relies on external community channels (Reddit) to route Novice Starters."

Visual Style: Dark slate (#0F172A), clean two-column comparison card layout, green/blue archetype accents, crisp white typography.
```

---

## Slide 3: Competitive Foil & Problem Evidence

### Delta (What Changed)
- Replaced old NGO Economics slide with consolidated **Competitive Foil & Problem Evidence** (`[CONTEXT]`). (Old NGO Economics merged into Slide 5 Root Cause Spine).
- Integrated balanced rating citations: Medito (iOS App Store 4.9★ / Google Play Store 4.8★) vs. Headspace (App Store 4.8★ for core pedagogy vs. Trustpilot 1.4/5 for aggressive billing).
- Grounded strategic symmetry in empirical evidence (App Store/Play Store reviews, Trustpilot grievances, Reddit `r/Medito` "Where do I start?" support threads).

### Claude Design Prompt

```text
Create a clean, dark-mode 16:9 presentation slide for Slide 3 of the Medito Product Teardown.

Header:
- Top Left Category: "COMPETITIVE FOIL & PROBLEM EVIDENCE"
- Top Right Tag: "[CONTEXT]"
- Main Headline (Bold 28px): "Two Structural Bets: Each App Sacrifices Exactly What the Other Protects"

Methodology Sub-Header Bar (Full width, dark slate container):
- "📐 FOIL METHODOLOGY: Headspace selected as maximal contrast on gating & guidance. Tier Defense: Free Tier exposes monetization paywalls; Premium Tier exposes pedagogy depth."

Comparison Table & Evidence Signals Grid (2 Columns: Medito Subject vs Headspace Foil):
- Row 1: Business Model
  • Medito: Non-profit foundation
  • Headspace: Venture-backed SaaS ($69.99/yr sub)
- Row 2: What it Built
  • Medito: 100% ungated, no accounts
  • Headspace: Day-1 hard paywall, sticky trial
- Row 3: Protected Asset
  • Medito: Z₁ Universal Access & User Trust
  • Headspace: Subscription Revenue / LTV
- Row 4: Sacrificed Asset
  • Medito: Revenue Certainty & R&D Capital
  • Headspace: Top-Funnel Conversion & Goodwill

Empirical Evidence Section (Structured callout cards):
- Left Card (Medito Signals):
  • iOS App Store: 4.9★ | Google Play Store: 4.8★ (Overwhelming praise for 0 paywalls/ads)
  • Reddit r/Medito: High frequency of "Where do I start?" beginner posts
- Right Card (Headspace Signals):
  • iOS App Store: 4.8★ (1M+ reviews praising Andy's core pedagogy)
  • Trustpilot: 1.4/5 (500+ reviews citing aggressive billing & hard cancellation)
  • Content Depth: 500+ structured sessions

Footer Callout (Full width banner at bottom):
- 💡 "SYMMETRIC BETS: Headspace protects revenue certainty at the cost of user trust (1.4 Trustpilot). Medito protects universal access at the cost of revenue predictability and onboarding R&D."

Visual Style: Dark slate (#0F172A), structured contrast table, green accents for Medito, red accents for Headspace, clean typography.
```

---

## Slide 4: Firsthand Walkthrough & Inferred Funnel Map

### Delta (What Changed)
- Added `[DIAGNOSIS]` section tag in header.
- Updated Job Story banner with canonical 3-layered Archetype A JTBD statement.
- Grounded Medito onboarding journey nodes in empirical UI evidence: `[Flat 8-Tile Home Grid]` referencing the 8 home icons (*Your Daily, Sleep, Timer, Course, etc.*).
- Updated funnel friction callout to cite empirical `r/Medito` beginner support threads.
- Refined Headspace onboarding contrast node to `[Forced Basics 1 Onboarding]`.

### Claude Design Prompt

```text
Create a clean, dark-mode 16:9 presentation slide for Slide 4 of the Medito Product Teardown.

Header:
- Top Left Category: "FIRSTHAND WALKTHROUGH & INFERRED FUNNEL MAP"
- Top Right Tag: "[DIAGNOSIS]"
- Main Headline (Bold 28px): "Unbundling 'Minimalism': Low Noise is a Sanctuary Feature; Low Guidance is an Under-Investment"

JTBD Sub-Header Banner (Full width container with subtle icon):
- 👤 "OVERWHELMED STARTER JTBD: 'When I am mentally exhausted, help me start meditating immediately without forcing me to decide what course to take, so I can feel calm without fearing I'm wrong.'"

Top Diagram Container: Medito Firsthand User Journey (Flow chart layout)
- Step 1: [ Install App ] (Subtext: Zero friction)
- Step 2: [ Zero Account / Paywall ] (Subtext: Ungated access, Z₁ protected)
- Step 3: [ Flat 8-Tile Home Grid ] (Subtext: Your Daily, Sleep, Timer, Course... Choice paralysis)
- Step 4: [ Inert Guidance ] (Subtext: Guidance present, but doesn't drive)
- Branching Callouts:
  • 🔴 Observed UX Friction: Guidance is Inert (Tiles present, but don't drive)
  • 🟠 Inferred Funnel Risk: Novice Activation Drag (Drop-off to r/Medito for manual advice)

Bottom Diagram Container: Headspace Foil Onboarding Contrast
- Flow: [ Install ] ──► [ Hard Paywall Prompts ] ──► [ Forced Basics 1 Onboarding ] ──► [ Driven Pedagogy ]
- Subtext nodes: High friction/bounce ──► Structured 10-day path ──► Progressive (Basics 1 ──► 2)

Footer Callout (Full width banner at bottom):
- 💡 "UNBUNDLING INSIGHT: Low Noise (no ad spam / no push guilt) is a genuine feature protecting Z₁. Low Guidance (flat 8-tile menu without intent-matching) is an R&D under-investment causing churn."

Visual Style: Dark slate (#0F172A), process flow nodes, red/orange friction highlights, clear diagrammatic hierarchy.
```

---

## Slide 5: Root Cause Spine & Economics

### Delta (What Changed)
- Merged old Slide 3 (NGO Economics) directly into Slide 5's Causal Spine to eliminate structural repetition.
- Added explicit **Financial Disambiguation Banner**: €122k/yr total org opex (€14/hr continuous burn across foundation, audio, legal, and server costs) vs. near-zero server cost-to-serve ($Z_3$).
- Specified screenshot layout placements: cropped Medito donation ask sheet embedded at Step 2; cropped 8-tile home grid embedded at Step 4.
- Added $Z_3$ Architectural Constraint box explaining why heavy server-side ML recommendation engines (Headspace Ebb AI pattern) are non-viable.

### Claude Design Prompt

```text
Create a clean, dark-mode 16:9 presentation slide for Slide 5 of the Medito Product Teardown.

Header:
- Top Left Category: "ROOT CAUSE SPINE & ECONOMICS"
- Top Right Tag: "[DIAGNOSIS]"
- Main Headline (Bold 28px): "One Causal Spine: NGO Operating Economics Force Zero-Cost Servicing (Z₃) as a Structural Constraint"

Financial Disambiguation Sub-Header Bar (Full width dark container with euro icon):
- 💶 "FINANCIAL DISAMBIGUATION: Total Org Opex = €122k/yr (€14/hr continuous burn). Unforecastable donation cashflow forces R&D to stay open-source & cost-to-serve (Z₃) near €0."

Main Causal Spine Diagram (Horizontal 4-node flow chart with embedded cropped UI cards):
- Node 1: [ 1. NGO Foundation ] ── Universal free access protected: Z₁
- Node 2: [ 2. Decoupled Revenue ] ── Top 1% users pay €0; unforecastable cash
  • Embedded Visual: 🖼️ Cropped screenshot of Medito's month-end in-app donation prompt sheet
- Node 3: [ 3. Cost-to-Serve Z₃ ] ── Must stay near €0; open-source R&D & volunteer ops
- Node 4: [ 4. Low-Assist UI ] ── Flat 8-tile menu; inert guidance
  • Embedded Visual: 🖼️ Cropped screenshot of Medito's 8-tile home grid (Your Daily, Sleep, Timer, Course...)
- Terminal Outcome Node: 🔴 Novice Activation Drag (Self-selects for power users; the spine's core question)

Architectural Constraint Callout Box (Subtle border box below diagram):
- ⚖️ "Z₃ ARCHITECTURAL CONSTRAINT: Server-side ML recommendation engines (Headspace Ebb AI pattern) add recurring server burn, violating Z₃. All 3 proposed interventions (Intent Pre-Pin, Pay-It-Forward Copy, Translator Credits) are 100% client-side / static logic — zero recurring server cost by design."

Footer Callout (Full width banner at bottom):
- 💡 "CAUSAL SPINE PAYOFF: NGO Ground ──► Unforecastable Revenue ──► Protect Z₃ (Zero Server Burn) ──► Low-Assist UI ──► Novice Activation Drag (Grounded in €122k/yr foundation finances)."

Visual Style: Dark slate (#0F172A), horizontal process flow, embedded tightly-cropped UI component cards, red accent for activation drag, crisp white typography.
```

---

## Slide 6: Success Definition & Metric Architecture

### Delta (What Changed)
- Moved Metric Architecture up to Slide 6 (ahead of Slide 7 RICE Matrix) so Impact scoring has an explicit metric definition.
- Added `[STRATEGY]` section tag in header.
- Established **Monthly Active Practice Hours (MAPH)** as North Star (rejecting DAU/MAU app-open vanity metrics).
- Defined explicit 3-lever L1 Metric Hierarchy ($Z_1$ Activation, $Z_2$ Revenue, $Z_3$ Ops).
- Added explicit **$Z_3$ Infra Bounding Rule**: client-side audio caching caps server cost at $\le €0.002$/MAU as MAPH grows.

### Claude Design Prompt

```text
Create a clean, dark-mode 16:9 presentation slide for Slide 6 of the Medito Product Teardown.

Header:
- Top Left Category: "SUCCESS DEFINITION & METRIC ARCHITECTURE"
- Top Right Tag: "[STRATEGY]"
- Main Headline (Bold 28px): "Anchoring Mission Success to MAPH While Bounding Infrastructure Cost per MAU (Z₃)"

North Star Sub-Header Banner (Highlighted green accent box):
- 🎯 "NORTH STAR METRIC: Monthly Active Practice Hours (MAPH) — Total completed audio meditation hours/month across all users. Measures true mission (Z₁), rejecting empty app-open vanity traffic."

Three-Column L1 Metric Hierarchy Grid:
- Left Column: "📈 L1 MISSION DRIVERS (Z₁)"
  • D7 Pack Completion Rate (%) — % of new installs completing ≥1 multi-session pack
- Middle Column: "💶 L1 REVENUE DRIVERS (Z₂)"
  • Post-Session Donor Conversion Rate (%) & Monthly Donation MRR (€)
- Right Column: "⚡ L1 OPS DRIVERS (Z₃)"
  • Active Volunteer Translator Retention Rate (%) & String Completion %

Guardrails & Bounding Box (Subtle border box below grid):
- 🛡️ "GUARDRAIL METRICS & MAPH-VS-Z₃ BOUNDING LOGIC:
  • Sanctuary Guardrail: Guilt Churn Rate (24-hr uninstall rate following a donation prompt).
  • Z₃ Infra Bounding Rule: CDN bandwidth scales linearly with MAPH. To protect Z₃, audio caching caps server cost-to-serve at ≤ €0.002 per active user/month regardless of MAPH growth."

Footer Callout (Full width banner at bottom):
- 💡 "METRIC ALIGNMENT: Interventions #1, #2, and #3 map 1-to-1 to L1 Revenue, L1 Activation, and L1 Ops levers before RICE scoring on Slide 7."

Visual Style: Dark slate (#0F172A), clean metric dashboard layout, green North Star highlight, 3 distinct L1 driver cards, crisp white typography.
```

---

## Slide 7: Prioritization & Reversibility Filter

### Delta (What Changed)
- Consolidated RICE Prioritization Table with Reversibility Guarantee onto Slide 7 (`[STRATEGY]`).
- Streamlined table to **Top 4 Solutions** (#1–#3 Core Build + #4 Quick Win), moving dropped/backlog items (#5–#7) to Slide 11.
- Defined explicit unit calibrations for Reach (1–10 target population) and Impact (0.25–3.0 L1 metric lift).
- Added explicit **Reversibility Guarantee Banner**: confirming all 4 solutions are 100% client-side Two-Way Doors.

### Claude Design Prompt

```text
Create a clean, dark-mode 16:9 presentation slide for Slide 7 of the Medito Product Teardown.

Header:
- Top Left Category: "PRIORITIZATION & REVERSIBILITY FILTER"
- Top Right Tag: "[STRATEGY]"
- Main Headline (Bold 28px): "Calibrated RICE Scoring Selects Top 4 Client-Side Interventions (2.5 Eng-Wks Total)"

Unit Calibration Sub-Header Bar (Full width container):
- 📐 "RICE SCORING UNITS: Reach (1–10 target population) · Impact (0.25–3.0 L1 metric lift) · Confidence (Tier 2 = 0.8 validated precedent) · Effort (Person-weeks)"

Top 4 Solutions Prioritization Matrix Table (Clean, scannable rows):
- Header Columns: RANK | SOLUTION & TARGET LEVER | REACH | IMPACT | CONF (TIER 2) | EFFORT | RICE SCORE
- Row #1 (Highlighted green accent): #1 | Value-Anchored Copy (Z₂ Revenue) | 7 | 3.0 | 0.8 (Econ) | 0.5 wk | 33.6
- Row #2 (Highlighted green accent): #2 | Intent Pre-Pin (Z₁ Activation) | 10 | 2.0 | 0.8 (PLG) | 1.0 wk | 16.0
- Row #3 (Highlighted green accent): #3 | Translator Credits (Z₃ Ops) | 2 | 2.0 | 0.8 (OS Auth) | 0.5 wk | 6.4
- Row #4 (Highlighted blue accent): #4 | Streak Share Fix (Z₁ Word-of-Mouth) | 3 | 1.0 | 0.8 (Social) | 0.5 wk | 4.8

Reversibility Guarantee Box (Subtle border container below table):
- 🛡️ "REVERSIBILITY GUARANTEE: All selected solutions are 100% client-side Two-Way Doors. Zero database schema migrations, zero server burn (Z₃), and reversible via feature flag in minutes."

Footer Callout (Full width banner at bottom):
- 💡 "DISPOSITION: Top 3 (#1, #2, #3) form v1.0 Core Build; #4 is a Quick Win. Backlog items (#5–#7) are documented on Slide 11 (Risks & Deferred Scope)."

Visual Style: Dark slate (#0F172A), clean tabular matrix, green highlights for core build, blue highlight for quick win, shield icon for reversibility guarantee, crisp white typography.
```

---

## Slide 8: Deep Dive #1 — Native Single-Tap Checkout & Contextual Copy

### Delta (What Changed)
- Re-scoped Deep Dive #1 from generic donation copy to **Native Single-Tap Checkout (Apple Pay / Google Pay) + Contextual Post-Session Copy**.
- Grounded checkout friction in mobile benchmarks (Baymard/Stripe: ~70% drop-off on external web redirects vs 1-tap wallets).
- Verified App Store Guideline §3.2.1(vi) compliance (0% Apple store tax for non-profit charitable donations).
- Documented R&D profile (~90% one-time setup via `flutter_stripe`, 0.5 eng-wks, minimal ~1-2 hrs/yr Flutter SDK bump maintenance).
- Replaced static marketing fluff (*"Loving Medito?"*) with post-session transparency grounded in Medito's ~€10k/month operating budget, protected by a 2-strike decay rule.

### Claude Design Prompt

```text
Create a clean, dark-mode 16:9 presentation slide for Slide 8 of the Medito Product Teardown.

Header:
- Top Left Category: "DEEP DIVE #1: NATIVE CHECKOUT & CONTEXTUAL COPY"
- Top Right Tag: "[SOLUTIONS]"
- Main Headline (Bold 28px): "Removing External Web Friction via Native Stripe Apple/Google Pay Sheet Grounded in ~€10k/mo Opex"

Two-Column Comparison & Technical Specs Grid:
- Left Column (UI & Funnel Mechanics):
  • Current Flow (Web Redirect): Show UI card with "Loving Medito? Let's Keep the Zen Flowing! [Donate now]" ──► Arrow pointing to external Chrome/Safari web form.
    - Red Callout: "🔴 Friction Signal: External web redirects requiring manual card typing incur ~70% mobile drop-off (Baymard/Stripe benchmark)."
  • Proposed Flow (Native 1-Tap Sheet): Show UI card "Session Complete (70 mins total practice). Medito is 100% free and non-profit, operating on ~€10k/month. Supported entirely by voluntary gifts. [Support Medito (€5 via Apple Pay)] [Skip]"
    - Green Callout: "🟢 1-Tap Sheet: Authenticates via Face ID in 2 secs. Contextual trigger post-session (≥ 5 mins)."

- Right Column (Technical, Legal & Cost Specs):
  • 0% Store Tax Compliance: App Store §3.2.1(vi) allows Apple Pay for non-profits at standard Stripe web rates (~2.2%, 0% to Apple).
  • Industry Benchmark Drop-Off: Baymard/Stripe studies show web card entry loses ~70% vs. 1-tap wallets.
  • R&D & Maintenance Profile: 0.5 person-weeks effort (3 days). ~90% one-time setup (Stripe ID + Flutter widget); minimal ongoing maintenance (~1-2 hrs/yr on Flutter SDK bumps).
  • Sanctuary Brand Guardrail: Single-tap skip; 2-strike decay (retreats for 14 days if dismissed twice).

Footer Callout (Full width banner at bottom):
- 💡 "VALUE PROPOSITION: Upgrades checkout from high-friction web redirect to native 1-tap sheet, eliminating ~70% mobile form drop-off while preserving zero-pressure sanctuary positioning."

Visual Style: Dark slate (#0F172A), process flow comparison, red friction vs green 1-tap highlights, crisp white typography.
```

---

## Slide 9: Deep Dive #2 — Intent Pre-Pin Activation

### Delta (What Changed)
- Re-sequenced Deep Dive #2 to Slide 9 (`[SOLUTIONS]`).
- Stripped repetitive metric callout box at bottom (Item 1.5 fix).
- Explicitly detailed **100% Client-Side Static Lookup Matrix (`intake_matrix.json`)** to answer the $Z_3$ architectural constraint (0 DB schema changes, 0 user accounts, 0 server cost).
- Added explicit **Non-Blocking Sanctuary Guardrail**: "Skip to Catalog" button on Screen 1.

### Claude Design Prompt

```text
Create a clean, dark-mode 16:9 presentation slide for Slide 9 of the Medito Product Teardown.

Header:
- Top Left Category: "DEEP DIVE #2: INTENT PRE-PIN ACTIVATION"
- Top Right Tag: "[SOLUTIONS]"
- Main Headline (Bold 28px): "10-Second Intake Pre-Pinning Starter Course to Solve Novice Choice Paralysis"

Two-Column UI Wireframe & Architecture Grid:
- Left Column (UI Flow & Onboarding Mechanics):
  • Step 1 (Intake Overlay): Show mobile mockup with 2 questions: Q1 "What brings you to Medito today?" (Stress / Sleep / Learn / Routine), Q2 "What's your experience level?" (Beginner / Practiced / Experienced).
    - Guardrail Tag: "🟢 Non-Blocking: Includes prominent 'Skip to Catalog' button."
  • Step 2 (Pre-Pinned Hero Tile): Show Medito home screen mockup with matching starter course (e.g., "Basics 1") pre-pinned directly onto the primary hero tile.

- Right Column (Technical & Architecture Specs):
  • 100% Client-Side Lookup Matrix: Intake responses map locally via static `intake_matrix.json` on-device (0 DB schema changes, 0 server burn).
  • Non-Blocking Sanctuary Guardrail: Includes explicit "Skip to Catalog" button on screen 1, preserving 0-forced-account sanctuary promise.
  • R&D Effort: 1.0 person-week (5 days).

Footer Callout (Full width banner at bottom):
- 💡 "VALUE PROPOSITION: Solves novice activation drag by pre-routing first-time users to a relevant starter pack, using a 100% client-side matrix that adds zero backend burn ($Z₃)."

Visual Style: Dark slate (#0F172A), 2-step wireframe flow, green highlight tags, clean technical spec cards, crisp white typography.
```

---

## Slide 10: Deep Dive #3 — Contextual Translator Credits

### Delta (What Changed)
- Re-sequenced Deep Dive #3 to Slide 10 (`[SOLUTIONS]`).
- Stripped repetitive metric callout box at bottom (Item 1.5 fix).
- Replaced vague "research shows" language with an explicit **Open-Source Attribution Precedent Anchor (Wikipedia/Crowdin Studies: +35-40% volunteer retention)** (Item 4.3 fix).
- Detailed static JSON binding (`credits.json`) bundled on-device for 0 server API burn ($Z_3$).

### Claude Design Prompt

```text
Create a clean, dark-mode 16:9 presentation slide for Slide 10 of the Medito Product Teardown.

Header:
- Top Left Category: "DEEP DIVE #3: CONTEXTUAL TRANSLATOR CREDITS"
- Top Right Tag: "[SOLUTIONS]"
- Main Headline (Bold 28px): "In-App Attribution for Volunteer Contributors to Scale Localization ($Z₃ Ops)"

Two-Column UI & Architecture Grid:
- Left Column (UI Mockup & Retention Mechanics):
  • In-App Credit Badge Mockup: Show localized Spanish course screen with header card "Course: Basics 1 (Spanish Edition)", sub-badge "🌐 Translated by volunteer María G. & 3 others. [Join Translation Team]".
  • Mechanics Bullet List: Displays top 2 volunteer names for active language; single-tap link opens Crowdin/Telegram onboarding; scales localization ops ($Z₃) without dev salary burn.

- Right Column (Technical & Citation Anchors):
  • Open-Source Citation Anchor: Grounded in Wikipedia & Crowdin research: visible peer attribution boosts volunteer retention by 35-40%.
  • Technical Implementation: Static JSON string binding (`credits.json`) bundled locally on-device. Zero API calls, 0 DB schema changes.
  • R&D Effort: 0.5 person-weeks (2 days).

Footer Callout (Full width banner at bottom):
- 💡 "VALUE PROPOSITION: Scales volunteer localization retention by rewarding contributors with in-app attribution, preserving $Z₃ cost-to-serve without spending foundation capital on dev salaries."

Visual Style: Dark slate (#0F172A), clean UI card mockup, badge highlight for volunteer credits, crisp white typography.
```

---

## Slide 11: Risks, Assumptions & Deferred Scope

### Delta (What Changed)
- Re-sequenced Risks, Assumptions & Deferred Scope to Slide 11 (`[EXECUTION]`).
- Consolidated 3-row Risk Mitigation Matrix (Guilt Churn $\rightarrow$ 2-Strike Decay Rule, Infra CDN Bounding $\rightarrow$ Client Audio Caching, Volunteer Fatigue $\rightarrow$ Credit Badge Truncation).
- Added explicit **3-line Scope Hygiene Box** documenting dropped/deferred items (#5 Dynamic State Matching deferred to v2.0, #6 Calendar Export dropped, #7 Post-Course Sequences dropped).

### Claude Design Prompt

```text
Create a clean, dark-mode 16:9 presentation slide for Slide 11 of the Medito Product Teardown.

Header:
- Top Left Category: "RISKS, ASSUMPTIONS & DEFERRED SCOPE"
- Top Right Tag: "[EXECUTION]"
- Main Headline (Bold 28px): "Proactive Risk Mitigation, Sanctuary Guardrails & Explicit Backlog Hygiene"

Top Container (Risk Mitigation & Sanctuary Guardrails Matrix):
- 3 Distinct Row Cards:
  • Row #1: Risk "Guilt Churn / Commercial Misperception (Z₁ Risk)" | Counter-Metric "Guilt Churn Rate (24-hr uninstalls post-ask)" | Mitigation "2-Strike Decay Rule: Retreats silently for 14 days if dismissed twice; single-tap skip."
  • Row #2: Risk "Z₃ Infra Bandwidth Spike (CDN Cost Bounding Risk)" | Counter-Metric "Server Cost-to-Serve (≤ €0.002 per active MAU)" | Mitigation "Client-Side Audio Caching: Audio streams cached locally on-device after first listen."
  • Row #3: Risk "Volunteer Attribution Fatigue (Z₃ Ops Recognition Risk)" | Counter-Metric "Translator Retention Rate (% active Crowdin leads)" | Mitigation "Truncate credit badges to top 2 contributors + link to Crowdin."

Bottom Container (Explicit Backlog Drops & Deferred Scope):
- Header: "🗑️ EXPLICIT BACKLOG DROPS & DEFERRED SCOPE (SCOPE HYGIENE)"
- Bullets:
  • #5 Dynamic State Matching (RICE 4.2): DEFERRED TO v2.0 ── Requires client emotion-tagging R&D.
  • #6 Calendar Export (RICE 1.5): DROPPED ── Low confidence (0.5), high system integration cost.
  • #7 Post-Course Sequences (RICE 0.75): DROPPED ── Low impact (0.5), redundant with Intent Pre-Pin.

Footer Callout (Full width banner at bottom):
- 💡 "SCOPE HYGIENE: Core v1.0 build is strictly bounded to 2.0 eng-weeks (Solutions #1, #2, #3), rejecting low-RICE features (#5–#7) to preserve lean execution focus."

Visual Style: Dark slate (#0F172A), structured risk table, subtle red warning indicators, clean backlog drop container, crisp white typography.
```

---

## Slide 12: Rollout Plan, Validation Experiments & Kill Criteria

### Delta (What Changed)
- Re-sequenced GTM Rollout & Experiments to Slide 12 (`[EXECUTION]`).
- Fixed decision gates (Day 14, Day 21, Day 28 decision gates).
- Re-checked statistical sample-size math for $1\%$ baseline ($N=148,000$ completing sessions @ $15\text{k}$ sessions/day over $\sim 10$ days for Exp #1; $N=8,500$ new installs for Exp #2; Power $= 80\%$).
- Explicitly labeled Exp #3 as a **Geo Quasi-Experiment** (Spanish/German locales vs US control).
- Replaced absolute rollback thresholds with **Delta ($\Delta$) over control baseline** triggers ($\Delta$ Uninstall Rate $> +0.5\%$, $\Delta$ Server cost $> +€0.003$/MAU, $\Delta$ Volunteer churn $> +5.0\%$).

### Claude Design Prompt

```text
Create a clean, dark-mode 16:9 presentation slide for Slide 12 of the Medito Product Teardown.

Header:
- Top Left Category: "ROLLOUT PLAN, VALIDATION EXPERIMENTS & KILL CRITERIA"
- Top Right Tag: "[EXECUTION]"
- Main Headline (Bold 28px): "W1–W4 Staged Experimentation Pipeline, Sample-Size Math & Automated Rollback Triggers"

Top Container (Staged Experimentation Pipeline W1–W4 Table):
- Header Columns: WEEK | EXPERIMENT NAME & HYPOTHESIS | SAMPLE-SIZE MATH & METHODOLOGY | DECISION GATE
- Row #1: W1–2 | Exp #1: Native 1-Tap Checkout (1-tap sheet vs. web redirect) | N = 148,000 completing sessions (Power = 80%, MDE = +15% rel conv; ~10 days @ 15k/day) | Day 14 Gate: Rollout if +15%
- Row #2: W2–3 | Exp #2: Intent Pre-Pin Activation (Pre-pinned hero vs. flat 8-tile catalog) | N = 8,500 new installs (Power = 80%, MDE = +20% D7 comp; ~7 days cohort) | Day 21 Gate: Rollout if +20%
- Row #3: W3–4 | Exp #3: Translator Credit Badges (Localized credit badge vs. control) | Geo Quasi-Experiment (Spanish & German locales vs US Control) | Day 28 Gate: Rollout if +25%

Bottom Container (Automated Rollback & Kill Criteria - Delta Over Baseline):
- Header: "🚨 AUTOMATED ROLLBACK & KILL CRITERIA (DELTA OVER CONTROL BASELINE)"
- Bullets:
  • Sanctuary Guardrail: Δ 24-hr Uninstall Rate > +0.5% over control ──► Immediate auto-rollback via feature flag.
  • Infra Guardrail: Δ Server Cost per MAU > +€0.003 over baseline ──► Enforce static CDN caching.
  • Community Guardrail: Δ Volunteer Contributor Churn > +5.0% over baseline ──► Revert credit badge UI.

Footer Callout (Full width banner at bottom):
- 💡 "EXECUTION PAYOFF: 4-week staged rollout backed by statistical sample-size math (N=148k / N=8.5k) and automated feature-flag rollback triggers to safeguard sanctuary trust."

Visual Style: Dark slate (#0F172A), 4-week gantt/pipeline table, green decision gates, red kill triggers, crisp white typography.
```

---

## Questions it raised
- How to ensure Claude Design maintains consistent typography across all 12 slides without style drift.

## Connected to
- [[Medito Teardown — 12-Slide Deck Blueprint]]
- [[Medito Teardown — Master Rework Spec]]
- [[Product Teardown — Medito]]
