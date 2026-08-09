# Medito Teardown — Slide Design Reference

*Design tokens, brand language, and visual inventory for building the 12-slide deck in Claude Design.*

---

## 1. Brand Color Palette

### App (Dark Mode — primary surface)

| Token | Hex | Usage |
|:------|:----|:------|
| `app-bg` | `#1A1A2E` / `#0D0D0D` | Main background — near-black with a faint blue-violet tint |
| `app-surface` | `#2A2A3C` | Cards, tiles, icon containers — raised surface |
| `app-accent` | `#9B8FE8` / `#A78BFA` | Primary accent — soft lavender/periwinkle. Used for: streak checkmarks, donation card bg, "All" filter chip, Share button, play button, active tab underline |
| `app-text-primary` | `#FFFFFF` | Headings, stats, session titles |
| `app-text-secondary` | `#9CA3AF` / `#A0A0B8` | Subtitles, descriptions, monospace labels |
| `app-divider` | `#3A3A4C` | Thin separator lines between list items |

### Website (Light + Dark sections)

| Token | Hex | CSS Variable | Usage |
|:------|:----|:-------------|:------|
| `warm-50` | `#FAF9F6` | `bg-warm-50` | Light section background — warm off-white |
| `warm-100` | `#F3F1EC` | `bg-warm-100` | Alternate light section (e.g., "Why we exist") |
| `warm-200` | `#D4D0C8` | `text-warm-200` | Muted text on dark backgrounds |
| `ink` | `#1C1917` | `bg-ink`, `text-ink` | Dark sections (header, footer, stats bar) — warm near-black |
| `ink-light` | `#57534E` | `text-ink-light` | Body text on light backgrounds |
| `ink-faint` | `#A8A29E` | `text-ink-faint` | Uppercase section labels, legal text |
| `cta` | `#6D5DD3` | `bg-cta` | CTA sections, donate banner, QR float — a **medium violet**, slightly deeper than the app accent |
| `cta-hover` | `#5B4DBF` | `bg-cta-hover` | Hover state on CTA buttons |

### Derived Slide Palette — Light Mode (recommendation)

| Role | Hex | Rationale |
|:-----|:----|:----------|
| **Slide background** | `#FAF9F6` | `warm-50` — the website's primary canvas. Clean, warm, not sterile white |
| **Alternate section bg** | `#F3F1EC` | `warm-100` — for contrast sections, callout boxes, table backgrounds |
| **Card/container** | `#FFFFFF` | Pure white cards on the warm bg — matches website's bordered card pattern |
| **Card border** | `#D4D0C8` | `warm-200` — 1px borders, no shadows, clean rectangular aesthetic |
| **Primary accent** | `#6D5DD3` | `cta` violet — headlines, key numbers, RICE badges, active elements |
| **Secondary accent** | `#9B8FE8` | Lighter lavender — supporting highlights, chart fills, pill backgrounds |
| **Text primary** | `#1C1917` | `ink` — all headings and key copy |
| **Text secondary** | `#57534E` | `ink-light` — body text, descriptions, source citations |
| **Text tertiary** | `#A8A29E` | `ink-faint` — uppercase section labels, footnotes |
| **Screenshot frame** | `#1C1917` | `ink` — dark frames around app screenshots create contrast on the light canvas |
| **Warning/alert** | `#D97706` | Darkened amber — counter-metrics, caution flags (ensures readability on light bg) |
| **Success/positive** | `#059669` | Darkened emerald — metric impact arrows, positive deltas (ensures readability on light bg) |

---

## 2. Typography

### Website
- **Display / Headings:** **Instrument Serif** (Google Fonts) — italic for emphasis words ("mindful", "compassionate"). Clamp-scaled: `clamp(2.5rem, 8vw, 3.75rem)` for H1, `clamp(1.5rem, 5vw, 2rem)` for H2.
- **Body / UI:** **DM Sans** (Google Fonts) — weights 400 (regular) and 500 (medium). Sizes 13px–16px. Tight tracking on the logo lockup.
- **Section labels:** DM Sans 13px, uppercase, `tracking-[0.1em]`, `text-ink-faint`.

### App
- System sans-serif (likely Roboto on Android). No custom font visible. Monospace used for subtitle/description lines (e.g., "Form a consistent habit").

### Slide Recommendation
- **Headlines:** Instrument Serif (or fallback: Playfair Display / DM Serif Display) — use italic for the one emphasized word per slide.
- **Body / labels:** DM Sans 400/500. Keep sizes between 14px–18px equivalent.
- **Data / metrics:** DM Sans 500, slightly larger (22px–28px), in accent color.
- **Code/technical:** JetBrains Mono or Fira Code for any technical annotations.

---

## 3. Illustration Style

Medito uses a **distinctive hand-painted illustration style** across all pack/course hero images:

- **Medium:** Gouache/acrylic-textured digital illustration — visible brushstrokes, layered paint texture
- **Palette per illustration:** Saturated, warm, maximalist — coral, teal, gold, cobalt, pink, sage. Each illustration has its own color story but they share the loose-botanical-nature vibe
- **Subject matter:** Tropical/botanical — leaves, flowers, birds, water, sky. Objects rendered in a naive/folk art style (rotary phone, alarm clock, canoe)
- **Composition:** Full-bleed hero images (top 40% of screen), content below on dark bg. Rounded corners on Featured thumbnails (8px radius)
- **Contrast to UI:** The illustrations are the *only* color-saturated elements in the entire app. Everything else is dark neutral + lavender accent. This contrast is deliberate — the art carries the warmth that the UI deliberately withholds

**For slides:** Use these illustrations as visual anchors or background bleeds where appropriate. They're the brand's visual identity. The teardown should reference the style but not recreate it — use actual screenshots instead.

---

## 4. Layout & Component Patterns

### App Layout
- **Navigation:** Bottom tab bar — 3 items: Home, Library (book icon), Settings (gear). No hamburger menu
- **Home screen:** Greeting ("Good night") + consistency score (circular progress, 78%) → pinned path card → 4×2 icon grid (Your Daily, Downloads, Timer, Sleep / Challenges, Emergency, Favorites, Course) → Featured carousel → Quote card → Shop carousel
- **Detail screens:** Full-bleed illustration hero (40%) + dark content area below. List items are full-width with thin dividers. No cards on detail screens — just flat list rows
- **Modals/overlays:** Post-session overlay with streak count, donation card (lavender bg), and mood emoji selector

### Website Layout
- **Max-width:** 768px — unusually narrow, content-first, no sidebar
- **Grid:** 1-col mobile, 2–3 col desktop for pillars and trust signals
- **Sections:** Alternating warm-50 / warm-100 / ink backgrounds. Each section has a centered uppercase label + serif heading + sans body
- **Borders:** 1px `border-warm-200` on cards, no shadows, no border-radius — clean rectangular aesthetic
- **CTA section:** Full-bleed violet (`bg-cta`) with white text
- **Transitions:** `duration-300` on all hovers — 300ms color transitions, no spring/bounce

---

## 5. Screenshot Manifest

All screenshots located at: `G:\College\PROJECTS\Product Teardowns\Medito\Screenshots\`

| # | File | Screen | Key Elements |
|:--|:-----|:-------|:-------------|
| 1 | `Screenshot_20260807-102555_Medito.png` | Post-session overlay | 7-day streak, donation card ("Loving Medito? Let's Keep the Zen Flowing!"), mood selector — **this is the exact generic copy we're proposing to replace** |
| 2 | `Screenshot_20260807-102602_Medito.png` | Home screen (top) | Greeting, 78% consistency, pinned path "YOUR PATH · Medito's Journey", 4×2 icon grid, Featured carousel |
| 3 | `Screenshot_20260807-102739_Medito.png` | Home screen (bottom) | Featured carousel, quote card (shareable), "Shop to Support" carousel |
| 4 | `Screenshot_20260807-102748_Medito.png` | Emergency pack detail | Full-bleed illustration hero, session list (Anger, Fear, Grief, Panic, Stress) |
| 5 | `Screenshot_20260807-102753_Medito.png` | Challenges | Full-bleed ocean illustration, 30-day challenges list |
| 6 | `Screenshot_20260807-102757_Medito.png` | Favorites | Light-bg screen (outlier), filter chips (All/Tracks/Packs), single favorited pack |
| 7 | `Screenshot_20260807-102800_Medito.png` | Course detail ("The Medito course") | Full-bleed landscape illustration, progressive section list |
| 8 | `Screenshot_20260807-102811_Medito.png` | Meditation timer | Illustration hero, ambient sound selector, duration picker, play button |
| 9 | `Screenshot_20260807-102815_Medito.png` | Downloads (empty) | Light-bg empty state with description text |
| 10 | `Screenshot_20260807-102820_Medito.png` | Stats | Stats card (consistency %, streaks, tracks, total time), Share button (lavender), streak toggle |

---

## 6. Design System for 12-Slide Deck

### Slide Grid
- **Aspect ratio:** 16:9 (standard presentation)
- **Content max-width:** ~900px centered (matching Medito's tight content-first layout philosophy)
- **Margins:** 64px horizontal, 48px vertical

### Slide Types (mapped to deck blueprint)

| Type | Slides | Layout |
|:-----|:-------|:-------|
| **Title** | 1, 12 | Centered Instrument Serif headline + subtitle on `warm-50`, Medito logo top-left |
| **Context** | 2, 3 | Split — left text block on `warm-50`, right screenshot in dark `ink` frame or data card on `warm-100` |
| **Walkthrough** | 4, 5 | Screenshot(s) in dark frames with annotated callouts, on `warm-50` canvas |
| **Deep Dive** | 7, 8, 9 | Before/After comparison — current screenshot left, proposed mockup right, metric badge below. Dark screenshot frames pop against the light canvas |
| **Framework** | 6 | OST diagram or RICE table on white card with `warm-200` border, accent borders on ranked items |
| **Metric** | 10 | Metric architecture diagram — Z₁/Z₂/Z₃ with arrows, counter-metrics in darkened amber |
| **Summary** | 11 | Prioritized action table — RICE scores in violet accent badges |

### Component Library (for Claude Design prompts)

- **Screenshot frame:** Dark rounded rectangle (`ink` bg, 12px radius, subtle drop shadow) containing the phone screenshot — the dark frame on the light canvas creates a natural device-like contrast without needing a phone mockup
- **Callout annotation:** Small pill badge (`cta` violet bg, white text, 8px radius) with connector line to screenshot element
- **Metric badge:** Rounded rectangle, `cta` violet bg, white bold number + `ink` label below
- **Section label:** Uppercase DM Sans 12px, letter-spacing 0.1em, `ink-faint` color — same pattern as website
- **Comparison card:** Two side-by-side dark-framed screenshots labeled "Current" (muted `warm-200` border) and "Proposed" (violet `cta` border)
- **RICE score pill:** `cta` violet bg, white text, showing score number — larger for #1 ranked item
- **Quote block:** Italic Instrument Serif, left border in `cta` violet, `ink-light` text
- **Data card:** White bg, 1px `warm-200` border, no shadow — matches website card pattern exactly
- **Table:** `warm-100` header row, white body rows, `warm-200` borders — clean and scannable

### Screenshot Usage per Slide

| Slide | Screenshot(s) to use |
|:------|:--------------------|
| Slide 3 (Medito context) | `102602` (home screen) |
| Slide 4 (User journey) | `102602` (home) → `102800` (course detail) flow |
| Slide 5 (Foil comparison) | `102602` (Medito home) vs Headspace screenshot (need external) |
| Slide 7 (Donation copy) | `102555` (post-session with generic donation card) — this is the "before" |
| Slide 8 (Intent pre-pin) | `102602` (current home, inert path card) |
| Slide 9 (Translation credits) | `102748` or `102800` (pack detail with attribution area) |
| Slide 10 (Metrics) | `102820` (stats screen — shows current metric surface) |

---

## 7. Key Design Decisions for Slides

1. **Light canvas, dark screenshots.** The slides use the website's warm off-white (`warm-50`) as the canvas. App screenshots — which are dark mode — sit inside dark `ink` frames, creating a natural contrast that makes them pop without needing device mockups. This mirrors how Medito's own website presents the app.
2. **Violet as the one accent.** Medito uses exactly one accent color family (lavender/violet). On the light canvas, lean toward the deeper `cta` violet (`#6D5DD3`) for readability over the lighter app lavender. Use darkened amber/emerald only for metric annotations.
3. **Illustrations are sacred.** Reference them in screenshots but don't try to replicate or crop them for decorative use. The folk-art style is hand-painted and distinctive.
4. **Tight, not sprawling.** Medito's entire website is 768px wide. The design language is deliberate restraint. Slides should feel focused, not busy.
5. **No gradients on text.** Text is always flat solid color against the warm canvas.
6. **Warm, not clinical.** The bg is `#FAF9F6`, not `#FFFFFF`. The card borders are `#D4D0C8`, not `#E5E7EB`. This warmth is intentional — it matches Medito's brand tone.
