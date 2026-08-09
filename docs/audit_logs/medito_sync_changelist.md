# Medito Teardown — Sync Changelist

*All changes target [Product Teardown — Medito.md](file:///G:/College/Obsidian/BRIAN/Career/Product%20Teardown%20%E2%80%94%20Medito.md). The [deck blueprint](file:///G:/College/Obsidian/BRIAN/Career/Medito%20Teardown%20%E2%80%94%2012-Slide%20Deck%20Blueprint.md) has the correct values — no deck edits needed.*

---

## Change 1 — RICE Row #1: Confidence Tier + Score (Line 145)

**Problem:** Working note scores Item #1 at Tier 1 (1.0) citing "Telegram" as hard data. The deck scores it at Tier 2 (0.8) citing "Value Anchoring" (behavioral econ precedent). Telegram data proves *burn rate*, not *copy effectiveness* — Tier 2 is the defensible assignment.

**Current (L145):**
```
| **#1** | **Item 4: Value-Anchored Donation Copy** | 7 | 3.0 | 1.0 (Tier 1: Telegram) | 0.5 | **42.0** | **Primary Deep Dive (Slide 6)** — Direct $Z_2$ revenue impact, Tier 1 evidence, 2-day dev effort. |
```

**Proposed:**
```
| **#1** | **Item 4: Value-Anchored Donation Copy** | 7 | 3.0 | 0.8 (Tier 2: Value Anchoring) | 0.5 | **33.6** | **Primary Deep Dive (Slide 7)** — Direct $Z_2$ revenue impact, Tier 2 evidence (behavioral econ precedent on anchored donation copy), 2-day dev effort. |
```

**What changes:** Confidence 1.0 → 0.8, tier label Tier 1: Telegram → Tier 2: Value Anchoring, score 42.0 → 33.6, slide ref Slide 6 → Slide 7, rationale annotation updated.

---

## Change 2 — RICE Row #3: Confidence Tier + Score (Line 147)

**Problem:** Same pattern. Working note scores Item #3 at Tier 1 (1.0) citing "Telegram." The deck scores it at Tier 2 (0.8) citing "OS Attribution" (open-source attribution research). Telegram proves *volunteer ops exist*, not that *in-app attribution improves retention* — Tier 2 is correct.

**Current (L147):**
```
| **#3** | **Item 5: Contextual Translation & Credits** | 2 | 2.0 | 1.0 (Tier 1: Telegram) | 0.5 | **8.0** | **Tertiary Deep Dive (Slide 7)** — High $Z_3$ ops leverage, Tier 1 evidence, 3-day dev effort. |
```

**Proposed:**
```
| **#3** | **Item 5: Contextual Translation & Credits** | 2 | 2.0 | 0.8 (Tier 2: OS Attribution) | 0.5 | **6.4** | **Tertiary Deep Dive (Slide 9)** — High $Z_3$ ops leverage, Tier 2 evidence (open-source attribution precedent), 3-day dev effort. |
```

**What changes:** Confidence 1.0 → 0.8, tier label → Tier 2: OS Attribution, score 8.0 → 6.4, slide ref Slide 7 → Slide 9, rationale updated.

---

## Change 3 — RICE Row #2: Slide Reference (Line 146)

**Problem:** Row #2 references "Slide 6" but the deck puts Intent Pre-Pin on Slide 8.

**Current (L146):**
```
**Secondary Deep Dive (Slide 6)**
```

**Proposed:**
```
**Secondary Deep Dive (Slide 8)**
```

**What changes:** Slide ref only. Score/confidence are already correct.

---

## Change 4 — Opportunity 4 Donation Copy Phrasing (Line 116)

**Problem:** Working note says `€5 funds 20 mins of calm for the community` — ambiguous, could be misread as 20 mins of *user meditation time*. The deck correctly says `€5 funds 20 minutes of Medito's operational uptime` (Slide 7, L342). The derivation is €14/hr burn → €0.233/min → €5 ÷ €0.233 ≈ 21.4 mins of *organizational operational uptime*, not user-facing calm.

**Current (L116):**
```
€5 funds 20 mins of calm for the community
```

**Proposed:**
```
€5 funds 20 mins of Medito's operational uptime
```

**What changes:** One phrase replacement. Aligns with the deck's phrasing and the actual derivation.

---

## Summary

| # | File | Line | Type | Severity |
|:--|:-----|:-----|:-----|:---------|
| 1 | Working note | 145 | RICE score + confidence tier + slide ref | Medium — material number mismatch |
| 2 | Working note | 147 | RICE score + confidence tier + slide ref | Medium — material number mismatch |
| 3 | Working note | 146 | Slide reference | Low — pointer fix |
| 4 | Working note | 116 | Copy phrasing | Low — clarity fix |

Total: **4 edits, 1 file, 0 deck changes.**

> [!NOTE]
> The three minor polish flags from the earlier audit (label JTBD dimensions, add a Technical lens subheader, etc.) are *nice-to-haves* that don't create inconsistencies between the two documents. I've excluded them from this changelist since they're additive improvements, not sync fixes. Say the word if you want those scoped too.
