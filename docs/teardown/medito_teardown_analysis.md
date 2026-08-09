---
created: 2026-08-05
updated: 2026-08-07
tags: [pm, teardown, medito, placement-prep, working-note]
---

# Product Teardown — Medito (working note)

Working doc for the first depth-over-volume teardown. Framework: [[Product Teardown Master Guide]].
Status as of **2026-08-07**: subject + foil locked, Medito + Headspace observation passes done, **both linkages built and the mirror closed**, Headspace's sacrifice (W) now has data behind it. Next step = Opportunity Solution Tree (Phase 4), seeded below.

---

## Subject & foil

- **Subject:** Medito — free, open-source, donation-funded nonprofit meditation app (~4.1M users, no paywall, no account required).
- **Foil:** **Headspace** — chosen because it's the *maximal contrast on the spine axis* (structured pedagogy / heavy guided funnel + hard paywall), **not** because it's more popular. Contrast-on-the-thesis-axis is the criterion, not popularity. Calm is the fallback foil (contrasts on content-flood, a different axis).
- **What a foil is:** the mirror that turns Medito's *defaults* into visible *decisions*. Not a second teardown.
- **How to use each Headspace tier:** don't pick one. **Gating/monetization axis → compare against the free tier** (the aggressive paywall *is* the philosophy). **Product/pedagogy axis → compare against premium** (the actual product a paying user lives in). Collapsing them makes the analysis mushy.

## Spine (thesis)

> **Medito deliberately refuses to gate, pressure, or hard-funnel — it bets on the user. Does that bet serve the mission, or does it quietly self-select for users who were already going to be fine?**

- **Primary axis:** open-access / low-pressure / inert-guidance (organic discovery, minimalist UI) vs. Headspace's gated, high-pressure, actively-guided funnel.
- **Secondary axis:** no paywall / no account / no lock-in vs. Headspace's hard paywall + auto-renewing subscription.
- **JTBD dimensions (implicit throughout):**
  - **Functional:** establish and sustain a meditation practice.
  - **Emotional:** feel safe, unjudged, not sold to — sanctuary.
  - **Social:** identity alignment with a free, nonprofit, open-source product — "I use something principled."

## Survival metrics (the Z candidates)

- **Z₁ — sustained meditation behavior** (the mission: people actually practicing over time).
- **Z₂ — donation coverage** (the month-end "we're behind on costs" message *is* the conversion event).
- **Z₃ — cost-to-serve near zero** (why the library is small/curated; why it's open source). **For a donation-funded nonprofit, Z₃ may be *the* survival metric — if cost-to-serve outruns donation coverage, the app dies. A survival metric does not have to be customer-facing.**

## The linkages (the instrument, now built)

### Linkage 1 — Medito's design bet (repaired)

> **Medito built [a minimalist, low-assist design] to protect [Z₃ — cost-to-serve / dev-sustainability, what a donation-funded foundation lives or dies on], trading away [the activation of users who'd need scaffolding to ever start — a slice of Z₁].**

- Z was repaired: the earlier "protect genuineness / organic discovery" was a **value, not a survival metric.** Pinned to Z₃.
- **Two things were bundled inside the word "minimalist" — keep them separate:**
  1. **Low *noise*** (no gamification, no notification spam, no upsell) — a *genuine feature* for a meditation app; protects Z₁ for everyone.
  2. **Low *guidance*** (no orientation, weak course-selection help) — *not* a feature; the cost-driven under-investment; this is the real W.
- ⚠️ **Do NOT assert motive.** Whether the minimalism is principled or a constraint-made-peace-with is **unknowable** — state the *observed effect* ("under-scaffolds discovery, worst for those who need help most"), never the *intent* ("dresses a constraint as a virtue"). Retracted the loaded framing per the Record Philosophy.

### Linkage 2 — Medito's structural bet (the root)

> **Medito built [an app on nonprofit/donation ground] to protect [users' free access to good meditation material — the mission, Z₁], trading away [any mandatory monetization → forecastable revenue].**

- **The two are NESTED, not parallel.** Linkage 2 is the root; Linkage 1 is its symptom: NGO model → can't fund heavy onboarding/support/content → forced into minimalist low-assist design → self-selects for the already-self-directed → the spine's exact worry. **One causal spine, top to bottom; everything threads through the money.**

### Mirror — Headspace's bet (the foil's payoff)

> **Headspace built [gate-before-value + sticky negative-option trial] to protect [revenue predictability / LTV — a subscription business's survival metric], trading away [the top-of-funnel that bounces at the wall having never tasted value, PLUS trust/goodwill].**

- **Symmetric to Medito on one axis: revenue-certainty ↔ open-access.** Medito protects access, sacrifices revenue-certainty (its revenue is *decoupled* from engagement — the most-engaged user can pay ₹0). Headspace protects revenue-certainty, sacrifices top-funnel + trust. **Two opposite bets, same axis, each sacrificing exactly what the other protects.** That symmetry is the thesis.

## Economics — corrected (stress-tested and rebuilt)

- **Marginal cost per user ≈ cents/month** — content is a non-rival good (recorded once), dev is volunteer/open-source, only audio bandwidth/CDN scales. Growth likely *helps* funding (amortizes fixed cost over a bigger donor pool). *(Earlier "every user is pure cost" claim was wrong — corrected.)*
- **What survives as the strategic risk — two things:**
  1. **Revenue is decoupled from engagement.** Unlike a paywall, the most-engaged user may donate ₹0. Medito *cannot use revenue as a reason to retain anyone* — retention motive is purely mission.
  2. **Donation revenue is unforecastable → caps reinvestment.** Can't hold a salaried team on lumpy income → **open source + volunteers is the *forced adaptation*, not just a value.** Can't outspend Headspace on content or acquisition.
- **Flagged as hypothesis, not fact:** donor *conversion rate* may decay as the base grows (free-rider / diffusion of responsibility) → revenue grows sub-linearly. Check, don't assert.

## Headspace observation pass (2026-08-07)

**Firsthand (Vedant's flow):**
- Multiple subscribe screens shown **before a single second of service**, on first open.
- **Every course gated**; tapping a locked course re-throws the same paywall — jarring.
- App opens *to* a subscribe prompt basically every time — sub pushed at every opportunity.
- The trial mechanic reads as negative-option: rely on users forgetting to cancel / friction to cancel.
- **India lock-in (firsthand, needs one re-check):** the flow surfaced only a ~₹900 annual commitment — no visible monthly option, so no low-commitment way to try the true product then leave.

**Web-verified (2026, sourced — secondhand until confirmed):**
- **Library:** a **500–1,000+** range depending on source (~400 core sessions for subscribers). Sources disagree; carry the range, not a number.
- **Structure:** genuine guided pedagogy — Basics 1→2 progressive courses, then Series + Singles organized by topic (stress, work, relationships, fear). This is the guidance layer Medito lacks.
- **2026 shift:** one review ([Sunrise Digest](https://thesunrisedigest.com/morning/headspace-review-2026/), *attributed not fact*) says Headspace's content has **stopped growing for ~18 months**, slower than Calm / Ten Percent Happier. What they *did* ship in 2026: **Ebb AI** — a personalization layer that reads your state (stress/energy/time) and adapts session selection. **→ content volume is no longer the battleground; navigation/personalization is.**
- **Pricing:** US $12.99/mo · $69.99/yr. **India ₹899 first year** (promo). Student (incl. India) **85% off → ~$9.99/yr**. Monthly plan exists in the model (7-day trial vs 14-day annual) — but whether India's storefront offers monthly vs. annual-only is **unconfirmed**; Vedant's firsthand annual-only flow is the better evidence there.
- **Sentiment split (the W, quantified):** **App Store 4.8/5** (1M+ reviews, the *product*) vs. **Trustpilot 1.4/5** (the *company's billing/conduct*). Complaints cluster on exactly the predicted three: aggressive auto-renewal, cancellation deliberately hard (website-only, not in-app), poor support. *(Trustpilot is structurally complaint-skewed — happy users don't post there — so read it as "the company-conduct grievance venue," not "everyone hates Headspace." The gap between 4.8 and 1.4 IS the product-vs-monetization split.)*

**The honest framing (do not drift into "incumbent bad"):** Headspace built a *genuinely superior product* (structured, research-backed, Andy Puddicombe's teaching rated industry-leading) and **wrapped it in a deliberately adversarial monetization layer.** Both are real; hold both.

## Key observations — Medito

- No paywall, no account required — full value ungated.
- Low noise, low pressure — value discovery is organic; no bombardment.
- **Guidance exists but is INERT** (corrected from "no guidance"): home tiles (Your Daily, Course, Challenges) + a pinnable path that tracks progress on one pinned pack (swipe to skip a meditation). But it's **ground-covering, not driving** — the feature exists to *have* the feature; Vedant has never used it. So: "guidance present but doesn't drive," not "guidance absent."
- Referral = **value-artifact, not incentive funnel**: shareable quote cards + a "discover calmness for FREE" share message. No reward to referrer.
- Funding: donations + shop; gentle month-end "behind on costs" ask — appreciated-if-you-can, no guilt.
- Retention metrics are *gentle*: streak + editable rolling consistency score (incl. off-app sessions). Not punishing.
- High-quality library, curated small; new packs added occasionally.
- **Open source** — repo: https://github.com/meditohq/medito-app (community contributors; possible way in for Vedant).

### Technical & Data Model observations
- **All proposed solutions are two-way doors:** client-side state, static JSON bundles, frontend string flags — zero DB schema changes, zero server API calls, reversible via feature flag in minutes.
- **One-way door evaluated and rejected:** server-side ML recommendation engine (Headspace Ebb AI pattern) for the intent pre-pin — would require DB schema migration + ongoing server burn, violating Z₃. Deliberately traded away dynamic personalization accuracy for zero-backend reversibility.
- **Data model constraint:** Medito has no user accounts and collects zero PII. Any solution requiring server-side user state is structurally incompatible with the current architecture — this is a hard constraint, not a preference.

## Phase 4 — Opportunity Solution Tree (OST)

- **Outcome:** Increase sustained active practice ($Z_1$) and defend donation/cost sustainability ($Z_2/Z_3$) without compromising Medito's zero-pressure, sanctuary brand identity.

### Opportunity 1: Choice paralysis at activation
*Novice users open the app to a flat library without scaffolding, leading to early drop-off before experiencing core value.*
- **Solution 1A — 10-Second Intent Pre-Pin:** A 2-question, non-blocking intake flow ("What brings you here?" + "Prior practice?") that pre-pins a starter pack to the home screen path. 100% client-side.
- **Experiment 1A:** A/B test default flat home vs. 2-question pre-pin on new installs. Measure D7 course completion and D7 retention.

### Opportunity 2: Post-course momentum drop
*Upon finishing a starter pack, users face an abrupt transition back to unguided browsing.*
- **Solution 2A — Progressive Milestone Sequences:** Visual "next step" pathways (e.g., *Basics 1 → Handling Stress → Daily Practice*) that auto-suggest the next pack upon completion.
- **Experiment 2A:** Roll out auto-suggested next pack to 50% of users completing *Basics 1*. Measure D14 second-pack start rate.

### Opportunity 3: Navigation friction for situational intent (Ebb AI Counterpoint)
*Headspace's 2026 Ebb AI proved navigation/state-matching beats adding 500 tracks. Medito has good audio, but relies on static category browsing.*
- **Solution 3A — Dynamic Local State Matching:** 1-tap situation chips (*"Anxious"*, *"5 mins before work"*, *"Can't sleep"*) that filter existing audio metadata locally on-device. Zero new audio cost ($Z_3$).
- **Experiment 3A:** A/B test home screen situation chips vs. static grid. Measure time-to-session-start and session completion rate.

### Opportunity 4: Unanchored donation copy ($Z_2$ Revenue)
*Medito requires €14/hr (~€10k/mo) to operate. Current in-app post-session donation prompt relies on generic pleas ("Loving Medito? Let's Keep the Zen Flowing!"), missing cumulative value-anchoring.*
- **Solution 4A — Value-Anchored Pay-It-Forward Copy:** Replace generic text with dynamic cumulative value copy (*"You've completed 70 mins on Medito. €5 funds 20 mins of Medito's operational uptime"*). Keeps the card collapsible and non-blocking.
- **Experiment 4A:** A/B test static generic copy vs. dynamic value-anchored pay-it-forward copy on post-session completion screens. Measure donor conversion rate and monthly donation volume ($Z_2$).

### Opportunity 5: Friction in volunteer translation recruitment & retention ($Z_3$ Ops)
*Medito uses Telegram, WhatsApp, and Google Sheets for community translations, but in-app contribution banners were noisy and Git/PRs are too technical for non-coder translators.*
- **Solution 5A — Contextual In-App Invites & Contributor Credits:** Surface a clean invite link inside Language Settings when an incomplete language is selected + add in-app translator credits (*"Translated with care by [Volunteer/Community]"*) in settings and pack footers.
- **Experiment 5A:** Track conversion rate from Language Settings to Telegram translation groups + volunteer retention post-attribution rollout.

### Opportunity 6: Re-engagement without push notification spam
*Medito deprecated daily push reminders to prevent guilt-driven churn and notification spam.*
- **Solution 6A — System Integration & Milestone Calendar Export:** Offer 1-click calendar export (*"Add recurring mindfulness block to Google/Apple Calendar"*) in Settings (alongside Health Connect) and contextually at 1hr/5hr practice milestones. Applies a 2-strike decay rule (if dismissed twice, retreats silently to Settings).
- **Experiment 6A:** Prompt 1hr practice completers with calendar export option. Measure D30 retention difference between calendar-synced vs non-synced cohorts.

### Opportunity 7: Passive organic referral loops
*Streak screen share button currently outputs a generic dry text link ("Try Medito for free"), missing the user's personal accomplishment.*
- **Solution 7A — Mission-Framed Milestone Share Fix:** Fix the Streak Screen share button to generate dynamic, mission-framed copy (*"Completed 30 days of calm on Medito — 100% free, non-profit, no paywalls"*). Converts user pride into zero-CAC word-of-mouth acquisition ($Z_3$).
- **Experiment 7A:** Update streak share handler string template. Measure share button click-through rate and incoming referral install conversion.

---

## Phase 5 — Prioritization & RICE Matrix

Prioritization formula: $\text{RICE Score} = \frac{\text{Reach} \times \text{Impact} \times \text{Confidence}}{\text{Effort}}$.
Confidence is strictly anchored to the **4-Tier Evidence Rubric** (Tier 1: 1.0 Hard Data · Tier 2: 0.8 Observed Signal / Competitor Validation · Tier 3: 0.5 Pure Hypothesis · Tier 4: 0.2 Speculation).

### Complete RICE Matrix

| Rank | Opportunity & Solution | Reach (1–10) | Impact (0.25–3) | Confidence (Tier) | Effort (Wks) | RICE Score | Strategic Rationale / Deck Role |
| :---: | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| **#1** | **Item 4: Value-Anchored Donation Copy** | 7 | 3.0 | 0.8 (Tier 2: Value Anchoring) | 0.5 | **33.6** | **Primary Deep Dive (Slide 7)** — Direct $Z_2$ revenue impact, Tier 2 evidence (behavioral econ precedent on anchored donation copy), 2-day dev effort. |
| **#2** | **Item 1: Intent Pre-Pin Activation** | 10 | 2.0 | 0.8 (Tier 2: Walkthrough) | 1.0 | **16.0** | **Secondary Deep Dive (Slide 8)** — Touches 100% of new installs, fixes choice paralysis ($Z_1$). |
| **#3** | **Item 5: Contextual Translation & Credits** | 2 | 2.0 | 0.8 (Tier 2: OS Attribution) | 0.5 | **6.4** | **Tertiary Deep Dive (Slide 9)** — High $Z_3$ ops leverage, Tier 2 evidence (open-source attribution precedent), 3-day dev effort. |
| **#4** | **Item 7: Personalized Streak Share Fix** | 3 | 1.0 | 0.8 (Tier 2: Walkthrough) | 0.5 | **4.8** | *Quick Win* — Low-hanging fruit fix for existing UI share gap. |
| **#5** | **Item 3: Dynamic Local State Matching** | 7 | 1.5 | 0.8 (Tier 2: Headspace) | 2.0 | **4.2** | *Phase 2 Candidate* — Ebb AI counterpoint, solid home screen UX. |
| **#6** | **Item 6: Calendar Milestone Integration** | 3 | 1.0 | 0.5 (Tier 3: Hypothesis) | 1.0 | **1.5** | *Deferred* — Low confidence, niche calendar power-users. |
| **#7** | **Item 2: Post-Course Milestone Sequences**| 3 | 0.5 | 0.5 (Tier 3: Hypothesis) | 1.0 | **0.75** | *Deferred* — Low incremental lift for already-motivated completers. |


---

## Phase 5 — Metric Architecture

Metric hierarchy mapping Medito's top 3 prioritized solutions directly to its core survival metrics ($Z_1$ sustained practice, $Z_2$ donation coverage, $Z_3$ cost-to-serve).

### 1. North Star Metric
- **Monthly Active Practice Hours (MAPH):** Total hours of audio meditation completed across all users per month.
  - **Why this over DAU/MAU?** App opens without session completion represent empty vanity traffic.
  - **Why this over Total Revenue (€)?** Medito is a non-profit foundation; revenue ($Z_2$) is a survival constraint to keep the servers running, while practice duration ($Z_1$) is the mission.

### 2. L1 Driver Metrics (Input Levers)
- **L1.1 Activation Lift ($Z_1$):** **D7 Pack Completion Rate (%)** — % of new installs completing $\ge 1$ multi-session pack within 7 days. *(Driven by Solution #2: 10-Second Intent Pre-Pin).*
- **L1.2 Monetization Conversion ($Z_2$):** **Post-Session Donor Conversion Rate (%) & MRR (€)** — % of users converting to one-time/recurring donors post-session. *(Driven by Solution #1: Value-Anchored Copy).*
- **L1.3 Ops & Localization Scalability ($Z_3$):** **Active Volunteer Translator Retention Rate & String Completion %** — % of target language strings translated and active volunteer retention in Telegram. *(Driven by Solution #3: In-App Credits & Invites).*

### 3. L2 Operational Metrics (Feature Diagnostics)
- **Pre-Pin Intake Completion Rate (%) & First-Session Start Rate (%):** % of new installs completing the 2-question intake AND % starting the pre-pinned pack within 5 minutes (isolates friction vs. relevance).
- **Pay-it-Forward Banner CTR (%):** Click-through rate on the dynamic value-anchored post-session card.
- **Language Settings Invite Link CTR (%):** Conversion rate from incomplete language settings to Telegram volunteer portal.
- **Streak Share Button CTR (%):** Conversion from streak view to external social share action.

### 4. Counter-Metrics / Guardrail Metrics
- **Guilt Churn Rate (Sanctuary Guardrail):** 24-hour uninstall or session drop-off rate immediately following a donation prompt.
  - *Purpose:* Ensures value-anchored donation copy never degrades Medito's zero-pressure sanctuary positioning.
- **Session Abandonment Rate (UX Guardrail):** % of started meditation sessions exited before the 80% mark.
  - *Purpose:* Ensures pre-pinned starter packs don't force mismatched audio onto users.
- **Infrastructure Cost per Active User (€/MAU) ($Z_3$ Guardrail):** Server/CDN billing divided by MAU.
  - *Purpose:* Verifies that local intake state and dynamic copy logic add zero backend overhead.

---

## Phase 6 — Deck Blueprint

The complete 12-slide synthesis blueprint, visual wireframes, verbatim element breakdowns, and speaker notes are locked in:
→ [[Medito Teardown — 12-Slide Deck Blueprint]]

---

## Status & Next Action

Medito Teardown is **100% complete across all 6 phases**. Ready for presentation deck building or next teardown/track pass.

## Connected to

- [[Medito Teardown — 12-Slide Deck Blueprint]] — complete 12-slide deck synthesis blueprint.
- [[Product Teardown Master Guide]] — the framework this executes.


