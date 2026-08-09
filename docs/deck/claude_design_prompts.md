# Claude Design Prompts — Medito Teardown (12-Slide Deck)

*A step-by-step prompt guide for generating the 12-slide presentation in Claude Design. Includes master setup rules, exact prompt copy for each slide, and file attachment instructions.*

---

## Master Setup & Global Context

Before generating individual slides, feed Claude Design the global design tokens and layout system.

### Files to Share with Claude Design for Initial Context:
- [`Medito Teardown — Slide Design Reference.md`](file:///G:/College/PROJECTS/Product%20Teardowns/Medito/Medito%20Teardown%20%E2%80%94%20Slide%20Design%20Reference.md)

### Master System Prompt (Paste this first or include with Slide 1):
```text
You are an expert presentation designer creating a high-stakes 16:9 product teardown deck for "Medito" (a non-profit meditation app).

DESIGN SYSTEM & RULES:
- Canvas: Warm off-white background (#FAF9F6 / warm-50). Clean, warm, non-sterile.
- Text: Primary ink black (#1C1917) for titles/headers; Secondary dark brown/gray (#57534E) for body copy; Faint gray (#A8A29E) for uppercase section labels.
- Accent: Medito Violet (#6D5DD3) for key numbers, active badges, callout borders, and focus elements. Supporting Lavender (#9B8FE8) for light fills.
- Cards & Containers: White background (#FFFFFF) with 1px border (#D4D0C8), no drop shadow.
- Screenshots: Mobile screenshots must sit inside a dark ink frame (#1C1917) with 12px rounded corners to create device contrast against the warm canvas.
- Typography: Instrument Serif for display headlines (use italics for key emphasis words); DM Sans (400/500) for body, labels, and tables.
- Layout: Clean, grid-aligned, high contrast, generous white space (64px horizontal margins). No generic corporate shapes or gradient text.
```

---

## Step-by-Step Slide Prompts

---

### Slide 1: Title & Executive Summary
- **Slide Type:** Title & Overview
- **Files to Attach:** None

#### Prompt:
```text
Create Slide 1 (16:9 aspect ratio) following our Medito Light Design System (#FAF9F6 background).

HEADER:
- Category Tag (top left, DM Sans uppercase 12px #A8A29E): PRODUCT TEARDOWN — MEDITO
- Main Headline (Instrument Serif 36px #1C1917): Protecting Open Access While Solving *Revenue Decoupling* & Activation Drag
- Subtitle Quote (Italic Instrument Serif 16px #57534E with #6D5DD3 left accent border):
  "Medito refuses to gate or pressure — it bets on the user. Does that bet serve the mission, or self-select for already-motivated users?"

CONTENT LAYOUT (3 Equal White Cards, 1px #D4D0C8 border, 16px padding):
- Card 1 — Survival Model ($Z$):
  * Header (#6D5DD3): 01 / Survival Model ($Z$)
  * Bullets:
    • Z₁ Practice: 4.1M users, zero paywall
    • Z₂ Revenue: €14/hr operating burn
    • Z₃ Servicing: ~€0, open source
- Card 2 — Strategic Friction:
  * Header (#D97706 Amber): 02 / Strategic Friction
  * Bullets:
    • 🔴 Revenue Decoupled ($Z_2$)
    • 🔴 Activation Leak ($Z_1$)
    • 🔴 Localization Bottleneck ($Z_3$)
- Card 3 — Recommendations:
  * Header (#059669 Emerald): 03 / Recommendations
  * Bullets:
    • 🟢 #1 Pay-It-Forward Copy (RICE #1)
    • 🟢 #2 Intent Pre-Pin (RICE #2)
    • 🟢 #3 Translator Credits (RICE #3)

FOOTER BAR (Full-width #F3F1EC container at bottom):
- Text (DM Sans 13px #1C1917): "3 targeted interventions (2.0 person-weeks effort) driving Z₁/Z₂/Z₃ while preserving zero-pressure sanctuary positioning."
```

---

### Slide 2: Strategic Positioning & The Foil Mirror
- **Slide Type:** Symmetric Comparison Table
- **Files to Attach:** None

#### Prompt:
```text
Create Slide 2 (16:9 aspect ratio) on #FAF9F6 background.

HEADER:
- Category Tag: 02 / STRATEGIC POSITIONING
- Action Headline (Instrument Serif 32px #1C1917): Two Opposite Structural Bets: Each App Sacrifices Exactly What the Other Protects
- Methodology Callout (DM Sans 13px #57534E): "Foil Tier Alignment: Compare Headspace Free Tier for Gating/Monetization, Premium Tier for Pedagogy."

MAIN CONTENT (5-Row Comparison Table):
- Header Row (#F3F1EC bg, DM Sans 13px Bold #1C1917): [Dimension | Medito | Headspace (Foil)]
- Row 1: Business Ground | Non-Profit Foundation | Venture-Backed Commercial
- Row 2: What It Built | Ungated Library + Minimalist Guidance | Hard Paywall + Structured Pedagogy (Basics 1-3)
- Row 3: Protected Asset | Open Access & User Trust (Z₁) | Forecastable Subscription Revenue
- Row 4: Sacrificed Asset | Revenue Certainty & Salaried R&D | Top-Funnel Reach & Billing Trust
- Row 5: Trust Footprint | 0 Billing Grievances (No paywall layer) | 1.4/5 Trustpilot (Billing & cancellation friction)

FOOTER CALLOUT (#FFFFFF card, 1px #6D5DD3 border):
- Text (DM Sans 13px #1C1917): "Consistent with an operational adaptation — GitHub (meditohq/medito-app) & Telegram disclosures confirm €14/hr burn constrains salaried R&D, making open source necessary."
```

---

### Slide 3: NGO Economics & The Structural Bet
- **Slide Type:** 3-Card Financial Risk Breakdown
- **Files to Attach:** None

#### Prompt:
```text
Create Slide 3 (16:9 aspect ratio) on #FAF9F6 background.

HEADER:
- Category Tag: 03 / NGO ECONOMICS
- Action Headline (Instrument Serif 32px #1C1917): Decoupled Revenue & Unforecastable Cashflow Force Cost-to-Serve ($Z_3$) as Survival Metric
- Cost Reconciliation Banner (#F3F1EC bg, 13px #57534E): "Audio content is non-rival (fixed cost amortizes with scale), but aggregate CDN bandwidth scales linearly with active listening hours."

CONTENT LAYOUT (3 Columns / White Cards with 1px #D4D0C8 border):
- Column 1 — Revenue Decoupling:
  * Badge (#6D5DD3 bg, White text): Structural Risk 01
  * Title (DM Sans Bold 16px #1C1917): Engagement ≠ Monetization
  * Body (#57534E): Power users pay ₹0. Medito cannot rely on product engagement to drive subscription conversion. Retention motive is purely mission-driven.
- Column 2 — Unforecastable Cashflow:
  * Badge (#6D5DD3 bg, White text): Structural Risk 02
  * Title (DM Sans Bold 16px #1C1917): Lumpy Income Caps R&D
  * Body (#57534E): Variable donation stream prevents salaried R&D. Open-source dev & volunteer translators are forced adaptations to keep fixed burn low.
- Column 3 — Free-Rider Decay (Hypothesis):
  * Badge (#D97706 bg, White text): Strategic Risk 03
  * Title (DM Sans Bold 16px #1C1917): Diffusion of Responsibility
  * Body (#57534E): As user base grows (4.1M+), individual donor conversion rate decays because users assume others fund the app.

BOTTOM BANNER (#1C1917 Dark bg, White text, 16px padding):
- Highlight Text (DM Sans 15px Bold #9B8FE8): "$Z_3$ (Cost-to-Serve Near Zero) is Medito's load-bearing survival metric. If cost-to-serve outruns donation coverage, the foundation dies."
```

---

### Slide 4: Firsthand Walkthrough & Inferred Funnel Map
- **Slide Type:** User Journey & Unbundling Analysis
- **Files to Attach:**
  - `Screenshot_20260807-102602_Medito.png` (Medito Home screen)
  - `Screenshot_20260807-102800_Medito.png` (Medito Course screen)

#### Prompt:
```text
Create Slide 4 (16:9 aspect ratio) on #FAF9F6 background.

HEADER:
- Category Tag: 04 / FIRSTHAND WALKTHROUGH
- Action Headline (Instrument Serif 32px #1C1917): Unbundling "Minimalism": Low-Noise is a Feature; Low-Guidance is an Under-Investment
- Job Story Banner (#F3F1EC bg, 13px #57534E): "When I open Medito as a beginner, I want clear guidance on where to start so I can build a daily habit without feeling overwhelmed."

LAYOUT (Left 60%: Onboarding Funnel Nodes | Right 40%: App Screenshots in Dark #1C1917 Frames):
- Left Side — 4 Onboarding Funnel Nodes (Horizontal flow with arrows):
  1. Install App → 2. Ungated Home (Screenshot L2) → 3. Browse Flat Library → 4. Start Session (Screenshot L7)
  * Callout Node 2 (🔴 UX Friction): "Guidance present ('Your Daily', Pinned Path) but INERT — sits as static choice."
  * Callout Node 3 (🟠 Funnel Risk): "Novice Activation Drag: 50+ unguided packs cause choice paralysis for beginners."

- Right Side — Attached Screenshots (`102602` Home & `102800` Course) inside dark #1C1917 phone frames with lavender callout lines pointing to the flat catalog.

BOTTOM CALLOUT CARD (#FFFFFF bg, 1px #6D5DD3 border):
- Unbundling Thesis:
  * 🟢 Low Noise (Zero ads, zero push guilt, zero paywalls) = SANCTUARY FEATURE (Protects Z₁)
  * 🔴 Low Guidance (No intent matching, flat structure) = DESIGN UNDER-INVESTMENT (Creates activation leak)
```

---

### Slide 5: Root Cause Deconstruction & The Nested Linkages
- **Slide Type:** Foil Side-by-Side & Causal Chain Diagram
- **Files to Attach:**
  - `Screenshot_20260807-102602_Medito.png` (Medito Ungated Home)
  - `WhatsApp Image 2026-08-09 at 19.06.36.jpeg` (Headspace Locked Grid)
  - `WhatsApp Image 2026-08-09 at 19.06.36 (1).jpeg` (Headspace Paywall)

#### Prompt:
```text
Create Slide 5 (16:9 aspect ratio) on #FAF9F6 background.

HEADER:
- Category Tag: 05 / ROOT CAUSE DIAGNOSIS
- Action Headline (Instrument Serif 32px #1C1917): One Causal Spine: Non-Profit Model (Root) Structurally Constrains Guidance Design
- Subtitle: "Why Medito avoided heavy ML guidance engines and how our solutions remain Z₃-aware."

LEFT SIDE — Side-by-Side Screenshot Comparison (Dark Frames #1C1917):
- Frame A (Medito `102602`): Label "Medito: Ungated & Low-Assist" (100% free, low guidance burn)
- Frame B (Headspace Foil `WhatsApp Paywall/Grid`): Label "Headspace: Hard Paywall & High-Assist" (Aggressive monetization funds ML guidance)

RIGHT SIDE — Nested Causal Linkages Diagram (Stacked White Cards):
- Linkage 2 (Structural Root):
  * Box: NGO Ground → Protect Free Access (Z₁) → Sacrifices Forecastable Revenue
- Linkage 1 (Design Symptom):
  * Box: Low Revenue Predictability → Protect Cost-to-Serve (Z₃) → Trades Away Salaried ML Guidance Engine
- Diagnostic Insight Box (#F3F1EC bg, 1px #6D5DD3 border):
  * "Heavy ML personalization (Headspace Ebb AI pattern) was avoided because recurring backend infrastructure violates Z₃. Solution #2 (Intent Pre-Pin) is 100% client-side by design."

FOOTER CHAIN (#1C1917 bg, White text):
"NGO Model → Unforecastable Revenue → Zero-Cost Servicing Constraint ($Z_3$) → Low-Assist UI → Self-Selection for Power Users"
```

---

### Slide 6: Opportunity Solution Tree & RICE Prioritization Engine
- **Slide Type:** RICE Prioritization Table & Confidence Rubric
- **Files to Attach:** None

#### Prompt:
```text
Create Slide 6 (16:9 aspect ratio) on #FAF9F6 background.

HEADER:
- Category Tag: 06 / PRIORITIZATION ENGINE
- Action Headline (Instrument Serif 32px #1C1917): RICE Scoring Anchored to Precedent Rubric Selects Revenue, Activation, and Ops Interventions

TOP RUBRIC BANNER (#F3F1EC bg, 12px #57534E):
"Confidence Rubric: Tier 1 (1.0 - Hard Internal Data) | Tier 2 (0.8 - Precedent Anchored) | Tier 3 (0.5 - Soft Precedent) | Tier 4 (0.2 - Speculative)"

MAIN RICE TABLE (7 Rows, White cards / #F3F1EC header):
Columns: [Rank | Opportunity & Solution | Reach | Impact | Confidence | Effort (Wks) | RICE Score | Strategic Role]

Row 1 (#6D5DD3 Highlight): #1 | Item 4: Value-Anchored Donation Copy | 7 | 3.0 | 0.8 (Tier 2: Value Anchoring) | 0.5 | 33.6 | Primary Deep Dive (Slide 7) — Z₂ Revenue
Row 2 (#6D5DD3 Highlight): #2 | Item 1: Intent Pre-Pin Activation | 10 | 2.0 | 0.8 (Tier 2: PLG Intake) | 1.0 | 16.0 | Secondary Deep Dive (Slide 8) — Z₁ Activation
Row 3 (#6D5DD3 Highlight): #3 | Item 5: Contextual Translator Credits | 2 | 2.0 | 0.8 (Tier 2: OS Attribution) | 0.5 | 6.4 | Tertiary Deep Dive (Slide 9) — Z₃ Servicing
Row 4 (Muted): #4 | Item 7: Personalized Streak Share Fix | 3 | 1.0 | 0.8 | 0.5 | 4.8 | Quick Win (Backlog v1.1)
Row 5 (Muted): #5 | Item 3: Dynamic Local State Matching | 7 | 1.5 | 0.8 | 2.0 | 4.2 | Phase 2 Candidate (v2.0)
Row 6 (Muted): #6 | Item 6: Calendar Milestone Integration | 3 | 1.0 | 0.5 | 1.0 | 1.5 | Dropped (Niche power users)
Row 7 (Muted): #7 | Item 2: Post-Course Pathing Prompt | 2 | 1.0 | 0.5 | 0.75 | 1.3 | Dropped (Low reach)

FOOTER SUMMARY: "Selected v1.0 Core Release: #1, #2, #3 total 2.0 person-weeks engineering effort."
```

---

### Slide 7: Deep Dive #1 — Value-Anchored Pay-It-Forward Donation Copy
- **Slide Type:** Before/After Mockup & Derivation Deep Dive
- **Files to Attach:**
  - `Screenshot_20260807-102555_Medito.png` (Current Post-Session Overlay)

#### Prompt:
```text
Create Slide 7 (16:9 aspect ratio) on #FAF9F6 background.

HEADER:
- Category Tag: 07 / DEEP DIVE #1 (RICE SCORE: 33.6)
- Action Headline (Instrument Serif 32px #1C1917): Replacing Generic Pleas with Value-Anchored Copy to Drive $Z_2$ Revenue Without Pressure

LAYOUT (Left 45%: Before/After UI Mockups | Right 55%: Derivation & Guardrails):

LEFT SIDE — UI Mockup Cards (Dark #1C1917 Frames):
- BEFORE (`Screenshot_20260807-102555_Medito.png`): Labeled 🔴 Current Generic Plea ("Loving Medito? Let's Keep the Zen Flowing!")
- AFTER (Proposed Mockup Card): Labeled 🟢 Proposed Value-Anchored Copy:
  Card text: "You've completed 70 minutes on Medito. €5 funds 20 minutes of Medito's operational uptime." [Donate Now Button]

RIGHT SIDE — 3 Analysis Cards:
- Card 1 — Operational Burn Derivation:
  * Formula: €14/hr foundation burn → €0.233/min → €5 donation = 21.4 mins (~20 mins) of organizational operational uptime.
  * Note: Grounds copy in real organizational costs without violating non-rival audio physics.
- Card 2 — Sanctuary Guardrails:
  * Collapsible card, single-tap skip, retreats for 7 days if dismissed twice. Zero guilt messaging.
- Card 3 — Implementation Specs:
  * 100% on-device calculation (0 server cost, 2-day build effort).

FOOTER METRIC BADGES:
- Primary Metric: Post-Session Donor Conversion % (Target: ≥ +15%)
- Counter-Metric (Amber): Guilt Churn Rate (< 1.5% threshold)
```

---

### Slide 8: Deep Dive #2 — Intent Pre-Pin Activation
- **Slide Type:** 2-Screen Flow & Client-Side Logic
- **Files to Attach:**
  - `Screenshot_20260807-102602_Medito.png` (Current Home for "After" state comparison)

#### Prompt:
```text
Create Slide 8 (16:9 aspect ratio) on #FAF9F6 background.

HEADER:
- Category Tag: 08 / DEEP DIVE #2 (RICE SCORE: 16.0)
- Action Headline (Instrument Serif 32px #1C1917): Replacing Flat Library Entry with Lightweight Intent Pre-Pin to Solve Choice Paralysis

LAYOUT (Left 50%: 2-Step Wireframe Flow | Right 50%: Technical & Metric Architecture):

LEFT SIDE — 2 Wireframe Screen Cards (Dark Frames #1C1917):
- Step 1: 10-Second Intake Card:
  * Question 1: "What brings you to Medito?" [Anxiety | Sleep | Basics | Focus]
  * Question 2: "Meditation experience?" [Beginner | Intermediate]
  * Top right: Prominent "Skip to Library →" button (Sanctuary escape hatch).
- Step 2: Pre-Pinned Home Screen:
  * Shows Medito Home (`102602`) with top path card dynamically set to "YOUR PINNED PATH: Basics 1 (Session 1/10)".

RIGHT SIDE — Technical & Metric Cards:
- Card 1 — $Z_3$-Aware Technical Specs:
  * 100% Client-Side lookup matrix. Static JSON routing. Zero user account required. Zero server API calls. 1.0 person-week build effort.
- Card 2 — Metric Hierarchy:
  * L2 Diagnostic: Intake Completion % (Target ≥ 80%), First-Session Start %
  * L1 Mission Driver: D7 Pack Completion % (Target ≥ +10%)
  * Guardrail (Amber): Session Abandonment Rate (< 5.0% threshold)
```

---

### Slide 9: Deep Dive #3 — Contextual Translator Credits & Invites
- **Slide Type:** In-App Attribution Mockup & Open Source Ops
- **Files to Attach:**
  - `Screenshot_20260807-102748_Medito.png` (Emergency Pack Detail)
  - `Screenshot_20260807-102800_Medito.png` (Course Detail)

#### Prompt:
```text
Create Slide 9 (16:9 aspect ratio) on #FAF9F6 background.

HEADER:
- Category Tag: 09 / DEEP DIVE #3 (RICE SCORE: 6.4)
- Action Headline (Instrument Serif 32px #1C1917): Unlocking Localization Through In-App Attribution to Protect Zero-Cost Servicing ($Z_3$)

LAYOUT (Left 45%: UI Attribution Placement | Right 55%: Open-Source Research & Guardrails):

LEFT SIDE — UI Placement Cards (Dark Frames #1C1917):
- Placement A (Audio Pack Footer):
  * Audio player bottom text: "Translated with care by Maria S. & Medito Community. [Contribute →]"
- Placement B (Language Settings):
  * Incomplete language row: "Spanish (60% complete) — Help us translate [Join Volunteer Team →]"

RIGHT SIDE — 3 Analysis Cards:
- Card 1 — Open-Source Attribution Precedent:
  * Research shows public contributor recognition increases volunteer recruitment & retention by establishing social proof.
- Card 2 — Privacy & Sanctuary Guardrail:
  * Attribution is strictly OPT-IN. Default credit: "Medito Community". Requires explicit volunteer consent during GitHub/Telegram onboarding.
- Card 3 — Technical Specs:
  * Static JSON string bundle addition (0 server overhead, 0.5 person-weeks build effort).

FOOTER METRIC BADGES:
- Primary Driver: Target Language Completion % (Target: ≥ +20%)
- L2 Diagnostic: Invite CTR %, Volunteer Retention %
- Guardrail (Amber): Translation Quality Flag Rate (< 5.0%)
```

---

### Slide 10: Trade-off & Constraint Evaluation
- **Slide Type:** Reversibility Matrix & Engineering Budget
- **Files to Attach:** None

#### Prompt:
```text
Create Slide 10 (16:9 aspect ratio) on #FAF9F6 background.

HEADER:
- Category Tag: 10 / ARCHITECTURAL CONSTRAINT EVALUATION
- Action Headline (Instrument Serif 32px #1C1917): Shipping 100% Reversible Two-Way Doors Within a 2.0 Person-Week Engineering Budget

TOP COMPARISON CARDS (Two Columns):
- Left Card (🟢 Two-Way Doors Selected):
  * Rec #1 (Donation Copy): 100% on-device string flag. Reversible in minutes via feature flag.
  * Rec #2 (Intent Pre-Pin): Client-side routing matrix. 100% skippable, reversible via feature flag.
  * Rec #3 (Translator Credits): Static JSON bundle addition. Reversible via remote config.
- Right Card (🔴 One-Way Door Evaluated & REJECTED):
  * Feature: Server-Side ML Recommendation Engine (Headspace Ebb AI pattern for Rec #2).
  * Why Rejected: Required DB schema migration & ongoing server burn, violating $Z_3$. Deliberately traded away dynamic personalization accuracy for zero-backend reversibility.

BOTTOM LAYOUT (Engineering Allocation & Deferred Scope):
- Engineering Budget Card (#F3F1EC bg):
  * Total Budget: 2.0 Person-Weeks (Rec #1: 0.5 wks + Rec #2: 1.0 wks + Rec #3: 0.5 wks).
- Deferred Scope Table:
  * ❌ Item 6: Calendar Integration (1.0 wk effort — dropped, niche calendar power-users)
  * ❌ Item 2: Post-Course Pathing (0.75 wk effort — dropped, low reach)
  * ⏸️ Item 3: Dynamic Local State Matching (2.0 wk effort — deferred to v2.0)
```

---

### Slide 11: Metric Architecture & Success Criteria
- **Slide Type:** Full Metric Tree Hierarchy
- **Files to Attach:** None

#### Prompt:
```text
Create Slide 11 (16:9 aspect ratio) on #FAF9F6 background.

HEADER:
- Category Tag: 11 / METRIC ARCHITECTURE
- Action Headline (Instrument Serif 32px #1C1917): Anchoring Growth to Monthly Active Practice Hours (MAPH) While Protecting Sanctuary Guardrails

MAIN CONTENT — Vertical Metric Tree Diagram (Stacked Cards with Connector Arrows):

1. NORTH STAR METRIC (Top Card, #1C1917 Dark bg, White text, Violet border):
   * Monthly Active Practice Hours (MAPH)
   * Rationale: Measures true user value delivered ($Z_1$). DAU is a vanity metric; revenue is a survival constraint, not the mission.

2. L1 PRIMARY DRIVERS (3 Cards side-by-side):
   * Card A (Mission Driver): D7 Pack Completion Rate (%) → Input into MAPH
   * Card B (Survival Driver - $Z_2$): Post-Session Donor Conversion % → Funds operating burn
   * Card C (Survival Driver - $Z_3$): Target Language Completion % → Expands global reach at zero cost

3. L2 OPERATIONAL DIAGNOSTICS (3 Cards matching L1 drivers):
   * Card A: Intake Completion % (≥ 80%), First-Session Start %
   * Card B: Value Copy Banner CTR %, Pay-it-Forward Share %
   * Card C: In-App Invite CTR %, Contributor Retention Rate

4. COUNTER-METRIC GUARDRAILS (Bottom Full-Width Card, Amber/Red accents):
   * 🛡️ Guilt Churn Rate (< 1.5% max) — Ensures donation experiments never erode user trust
   * 🛡️ Session Abandonment Rate (< 5.0% max) — Ensures intake flow doesn't block users
   * 🛡️ Translation Quality Flag Rate (< 5.0% max) — Ensures volunteer quality
   * 🛡️ Infrastructure Cost per MAU (€0.00 add) — Hard $Z_3$ boundary constraint
```

---

### Slide 12: GTM, Validation Experiments & Kill Criteria
- **Slide Type:** Roadmap, Experiment Specs & Guardrail Rules
- **Files to Attach:** None

#### Prompt:
```text
Create Slide 12 (16:9 aspect ratio) on #FAF9F6 background.

HEADER:
- Category Tag: 12 / GO-TO-MARKET & EXPERIMENTAL VALIDATION
- Action Headline (Instrument Serif 32px #1C1917): Low-Cost 10% Cohort Validation with Explicit Kill Criteria to Protect Sanctuary Trust

TOP ROADMAP TIMELINE (3 Phases, Horizontal cards):
- Phase 1 (W1-W3): Silent 10% Cohort A/B Tests (New installs only)
- Phase 2 (W4-W5): 100% Rollout + Spanish/German Translator Pilot
- Phase 3 (W6+): Backlog v1.1 Review (Streak share fix evaluation)

MIDDLE EXPERIMENT SPECS (3 Cards with Methodological Fixes):
- Exp #1 (Value Copy): 10% new install cohort, 14 days → Target: ≥ +15% Donor Conversion %
- Exp #2 (Intent Pre-Pin): 21 Days with 7-Day Fixed Cohort Intake Gate (admit Days 1–7; Days 8–21 allow full 14 days for D7 checkpoints) → Target: ≥ +10% D7 Completion %
- Exp #3 (Translator Credits): Direct Pilot in ES/DE Settings vs FR/IT Control pairs → Target: ≥ +20% Target Language Completion %

BOTTOM KILL CRITERIA CARD (#FFFFFF bg, 2px #D97706 Amber border):
- Explicit Rollback Triggers:
  * Kill Rec #1 IF Guilt Churn > 1.5%
  * Kill Rec #2 IF Session Abandonment > 5.0% OR Intake Bounce > 2.0%
  * Kill Rec #3 IF Translation Quality Flag Rate > 5.0%
```

---

## Instructions for Mirroring Project Files

All thinking files and blueprints are now mirrored into `G:\College\PROJECTS\Product Teardowns\Medito\`:
1. `Product Teardown — Medito.md`
2. `Medito Teardown — 12-Slide Deck Blueprint.md`
3. `Product Teardown Master Guide.md`
4. `Medito Teardown — Slide Design Reference.md`
5. `Claude Design Prompts — Medito Teardown.md`
6. `medito_teardown_audit.md`
7. `medito_sync_changelist.md`
8. `medito_polish_changelist.md`
