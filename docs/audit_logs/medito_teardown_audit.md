# Medito Teardown — Execution Audit

*Audit of [Product Teardown — Medito.md](file:///G:/College/Obsidian/BRIAN/Career/Product%20Teardown%20%E2%80%94%20Medito.md) and [12-Slide Deck Blueprint](file:///G:/College/Obsidian/BRIAN/Career/Medito%20Teardown%20%E2%80%94%2012-Slide%20Deck%20Blueprint.md) against [Product Teardown Master Guide](file:///G:/College/Obsidian/BRIAN/Career/Product%20Teardown%20Master%20Guide.md).*

Coverage: all 6 phases of the Guide's workflow, the 7-Point Rubric, the 10-Slide Blueprint (expanded to 12), the 5 Evaluation Lenses, and the Execution Rules. Every section below states what it checked.

---

## 1. 7-Point Rubric Scorecard

| # | Criterion | Verdict | Evidence |
|:--|:----------|:--------|:---------|
| 1 | **Problem Validity** | ✅ Strong | Problems sourced from firsthand app walkthrough (both Medito & Headspace), Telegram financial disclosures, GitHub repo, App Store vs Trustpilot sentiment split. Not theoretical. |
| 2 | **Context Understanding** | ✅ Strong | Business model (NGO, donation-funded, €14/hr burn), target user, revenue structure, and open-source constraint all researched *before* any criticism. Economics section was stress-tested and corrected mid-process (the "every user is pure cost" retraction). |
| 3 | **Deep Customer Insight (JTBD)** | ✅ Strong | Job Story defined clearly in Phase 2. Three JTBD dimensions aren't explicitly labeled (functional/emotional/social), but the working note's spine implicitly covers the emotional ("sanctuary") and social ("not being sold to") dimensions via the foil contrast. |
| 4 | **Root Cause Alignment** | ✅ Excellent | The nested linkage model (Linkage 2 → Linkage 1) is tighter than what the Guide's worked examples demonstrate. The causal spine — NGO model → unforecastable revenue → Z₃ constraint → low-assist UI → self-selection — directly maps fixes to drivers, not symptoms. Slide 5 closes this loop explicitly. |
| 5 | **Stakeholder Awareness** | ✅ Strong | Z₃ as load-bearing survival metric, open-source volunteer constraint, 100% client-side architecture for all 3 recs, privacy-first (zero PII). Engineering effort estimated per-solution. |
| 6 | **Prioritization Discipline** | ✅ Excellent | 7 opportunities identified → 3 shipped, 2 backlogged, 2 dropped with explicit rationale. RICE scores calculated with a 4-Tier Evidence Rubric anchoring confidence — goes beyond the Guide's worked examples which use gut-feel confidence %. |
| 7 | **Explicit Trade-offs** | ✅ Excellent | Slide 10 is dedicated to this. Evaluated and *rejected* a one-way door (server-side ML for Rec #2), defended the sacrifice (lower personalization accuracy to preserve Z₃). Dropped scope is named. Kill criteria are numeric. |

**Rubric summary: 7/7 criteria met.** Criteria 4, 6, and 7 exceed the bar set by the Guide's own worked examples.

---

## 2. 6-Phase Workflow Coverage

| Phase | Guide Requirement | Working Note | Deck Blueprint | Gap? |
|:------|:-----------------|:-------------|:---------------|:-----|
| **Phase 1: Context & Hypothesis** | Research business model, target audience, revenue driver. Formulate hypothesis. | ✅ Spine thesis + Z₁/Z₂/Z₃ survival metrics + foil selection rationale. | ✅ Slide 1 (thesis banner) + Slide 2 (foil) + Slide 3 (economics). | None. |
| **Phase 2: Instrumented Walkthrough** | Record user flow. Map Job Story. | ✅ Firsthand passes on both Medito and Headspace. Job Story defined. "Low noise vs low guidance" unbundling. | ✅ Slide 4 — funnel map, job story banner, foil contrast. | None. |
| **Phase 3: Multi-Lens Deconstruction** | Analyze through 5 lenses. Identify intentional trade-offs. | ⚠️ Partial — see Lens Audit below. | ✅ Slide 5 (RCA nested linkages). | Lens gaps in the working note — but the deck compensates. |
| **Phase 4: Opportunity Mapping (OST)** | Map to Outcome → Opportunities → Solutions → Experiments. | ✅ 7 opportunities, each with solution + experiment. | ✅ Slide 6 — full OST + RICE matrix. | None. |
| **Phase 5: Prioritization & Metric Architecture** | RICE scoring. North Star + L1/L2 + counter-metrics. | ✅ Complete RICE table + full metric hierarchy with counter-metrics. | ✅ Slide 6 (RICE) + Slide 11 (metric architecture). | None. |
| **Phase 6: Slide Deck Synthesis** | 10–12 slide linear deck. | ✅ Points to the deck blueprint. | ✅ 12 slides, each with wireframe + element breakdown + speaker notes. | None. |

---

## 3. 5 Evaluation Lenses — Explicit Coverage Audit

The Guide mandates analyzing through 5 lenses. Here's where each lens appears:

| Lens | Where in the Working Note | Where in the Deck | Assessment |
|:-----|:--------------------------|:-------------------|:-----------|
| **1. Strategic / Market** | Spine thesis, foil selection ("maximal contrast on spine axis"), positioning (what Medito says yes/no to). | Slide 2 symmetry matrix. | ✅ Covered well. |
| **2. Growth & Funnel** | Referral mechanics ("value-artifact, not incentive funnel"), organic discovery. | Slide 4 funnel map. | ✅ Covered. |
| **3. Retention & Loops** | Streak + rolling consistency score, "gentle" retention mechanics, no punishing loops. | Slide 4 (inert guidance), Opportunity 2 (post-course momentum), Opportunity 6 (re-engagement). | ✅ Covered. |
| **4. Monetization & Economics** | Full economics section (marginal cost, revenue decoupling, free-rider hypothesis). Donation copy analysis. | Slide 3 (economics), Slide 7 (donation deep dive). | ✅ Covered in depth. |
| **5. Technical & Data Model** | One-way/two-way door analysis appears in Slide 10 but is *not explicitly labeled in the working note's Phase 3*. Client-side architecture specs throughout. | Slide 10 (two-way doors shipped, one-way door rejected). | ⚠️ Minor gap — the working note's Phase 3 doesn't have a labeled "Technical & Data Model" section the way the Duolingo example does. The analysis exists but is scattered across OST solutions rather than consolidated under a lens header. |

> [!NOTE]
> The technical lens content is all *present* — Z₃-aware client-side design, zero-DB architecture, one-way door rejection — it's just distributed across Phases 4–5 and the deck rather than appearing as a named section under Phase 3. For the working note as an internal doc, this is fine. If someone were auditing the raw note against the Guide's checklist, they'd have to hunt for it.

---

## 4. Slide Blueprint vs. Guide's 10-Slide Template

The Guide prescribes a specific 10-slide structure. The Medito deck uses 12 slides. Here's the mapping:

| Guide Slide | Guide Title | Medito Deck Slide(s) | Faithful? |
|:------------|:-----------|:---------------------|:----------|
| 1 | Title & Executive Summary | Slide 1 | ✅ Thesis, 3 recs, total effort, metric impact — all on page 1. |
| 2 | Company & Market Context | Slides 2 + 3 | ✅ Split into foil mirror (Slide 2) and NGO economics (Slide 3). Justified: the economics are deep enough to need their own slide. |
| 3 | User Journey & Funnel Map | Slide 4 | ✅ Firsthand walkthrough, job story, funnel flow, foil contrast. |
| 4 | Root Cause Analysis | Slide 5 | ✅ Nested linkage model with Z₃ reconciliation. |
| 5 | Opportunity Solution Tree | Slide 6 | ✅ Full OST + RICE matrix + evidence rubric. |
| 6 | Proposed Solution Deep Dive | Slides 7, 8, 9 | ✅ Three deep dives (one per rec). Guide says "the #1 recommended solution" — deck does all 3. The extra slides are justified by the "one idea per slide" rule. |
| 7 | Trade-off & Constraint Evaluation | Slide 10 | ✅ Two-way doors, one-way door rejection, deferred scope, eng budget. |
| 8 | GTM & Adoption Strategy | Slide 12 (combined) | ✅ 6-week phased rollout. |
| 9 | Metrics & Success Criteria | Slide 11 | ✅ Full metric hierarchy with North Star, L1/L2, counter-metrics. |
| 10 | Validation & Next Steps | Slide 12 (combined) | ✅ Experiment specs, cohort methodology, kill criteria. |

> [!TIP]
> The expansion from 10 → 12 slides is clean. Guide's own rule is "max 12 slides" and "if a slide requires two distinct headlines, split it." The 3 deep-dive slides and the economics split both pass this test.

---

## 5. Execution Rules Compliance

| Rule | Status | Notes |
|:-----|:-------|:------|
| **One Idea Per Slide** | ✅ | Each slide has a single action headline. No double-thesis slides. |
| **Visual Over Text** | ✅ | ASCII wireframes, funnel diagrams, tables, UI mockups throughout. No prose walls on any slide canvas. |
| **Max 12 Slides** | ✅ | Exactly 12. |
| **Page 1 Summary** | ✅ | Slide 1 has thesis, Z-model, 3 frictions, 3 recs, total effort, and summary footer. Passes the 30-second test. |

---

## 6. Content Consistency: Working Note ↔ Deck Blueprint

Checked for contradictions and drift between the raw analysis and the slide synthesis.

| Item | Working Note | Deck Blueprint | Consistent? |
|:-----|:-------------|:---------------|:------------|
| RICE #1 score | 42.0 | 33.6 | ⚠️ **Discrepancy.** Working note uses Confidence 1.0 (Tier 1) → 7×3.0×1.0/0.5 = 42.0. Deck uses 0.8 (Tier 2) → 7×3.0×0.8/0.5 = 33.6. |
| RICE #3 score | 8.0 | 6.4 | ⚠️ **Same pattern.** Working note: 2×2.0×1.0/0.5 = 8.0. Deck: 2×2.0×0.8/0.5 = 6.4. |
| Confidence tier labeling | Items #1 and #3 scored at Tier 1 (1.0) citing "Telegram" as hard data source | Items #1 and #3 scored at Tier 2 (0.8) citing "Value Anchoring" and "OS Attribution" as precedent-validated | ⚠️ **Tier assignment shifted between documents.** |
| RICE rankings | #1 thru #7 order identical | Same order | ✅ |
| Solution descriptions | Match | Match | ✅ |
| Metric architecture | Match | Match (expanded with Z-anchor column) | ✅ |
| Counter-metrics | Match | Match (adds Infrastructure Cost/MAU) | ✅ (additive, not contradictory) |
| Effort estimates | Match | Match | ✅ |
| Kill criteria | Not in working note | In Slide 12 | ✅ (deck is the synthesis; kill criteria belong there) |

> [!IMPORTANT]
> **The RICE score discrepancy is the single material inconsistency.** Items #1 and #3 were downgraded from Tier 1 (1.0) to Tier 2 (0.8) between the working note and the deck without updating the working note. This is likely an intentional correction during the loop engineering (Telegram financial disclosures are evidence of *burn rate*, not direct evidence of *copy effectiveness* — so Tier 2 "behavioral econ precedent" is arguably the more defensible anchor). But the working note still shows the old scores.
>
> **Recommended fix:** Update the working note's RICE table to match the deck's Tier 2 confidence assignments, or add a note explaining the revision.

---

## 7. What the Guide's Worked Examples Do That This Teardown Does Better

Worth noting — this isn't just "meets the bar":

1. **Nested linkage model** (Linkage 2 drives Linkage 1) — the Duolingo/Blinkit examples don't build nested causal chains. The Medito teardown's root-cause spine is structurally deeper.
2. **4-Tier Evidence Rubric** with named precedent anchors per solution — the Guide's RICE uses ad hoc confidence percentages ("60%", "40%"). The Medito teardown formalizes the rubric and cites the behavioral/product pattern backing each tier.
3. **Explicit kill criteria with numeric thresholds** — the Guide's examples say "kill if no lift by day 14." The Medito deck specifies "kill if Guilt Churn Rate increases by >1.5%."
4. **Foil as a structural instrument** (not just "competitor comparison") — the Guide's Blinkit teardown compares against Zepto/Instamart as market rivals. The Medito teardown uses Headspace as a *mirror* designed to make Medito's defaults visible as decisions, with a defended tier-comparison methodology.
5. **Counter-metric guardrails** are more specific — the Guide's examples mention "Plus cancellation rate" loosely. The Medito teardown defines 4 named guardrails with Z-anchors.

---

## 8. Things to Watch / Minor Flags

| # | Flag | Severity | Detail |
|:--|:-----|:---------|:-------|
| 1 | **RICE score mismatch** | Medium | See Section 6. Working note shows 42.0/8.0; deck shows 33.6/6.4. Sync the confidence tier. |
| 2 | **Technical lens not labeled in Phase 3** | Low | Content exists but is distributed. Consider adding a "Technical & Data Model" subheader to the working note's observation section for checklist compliance. |
| 3 | **JTBD 3-dimension labels missing** | Low | The Guide defines Functional/Emotional/Social dimensions. The teardown covers all three implicitly (functional = "find calm"; emotional = "sanctuary, not sold to"; social = "using a free nonprofit app") but doesn't label them. Adding the labels would make the alignment explicit. |
| 4 | **Speaker notes reference "Slide 7/8/9" for deep dives** | Info | If the final deck reorders or merges slides, these cross-references will break. Not an issue now. |
| 5 | **Opportunity 4's €5 = 20 mins derivation** | Info | The working note says "€5 funds 20 mins of calm for the community." The deck correctly clarifies this as "20 mins of Medito's operational uptime" (not user meditation time). The working note phrasing is slightly ambiguous — "calm for the community" could be misread. |

---

## Verdict

This is a well-executed teardown. It meets all 7 rubric criteria, covers all 6 phases, stays within the 12-slide cap, and in several dimensions (causal depth, evidence-grounded RICE, kill criteria, foil methodology) exceeds the standard set by the Guide's own worked examples.

The one action item: **sync the RICE confidence tiers between the working note and the deck** so the scores match. Everything else is polish-level.
