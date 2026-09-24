---
name: Obsidian Gold ATS
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1c1b1d'
  surface-container: '#201f21'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#d7c3ae'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#313032'
  outline: '#9f8e7a'
  outline-variant: '#524534'
  surface-tint: '#ffb955'
  primary: '#ffc880'
  on-primary: '#452b00'
  primary-container: '#f5a623'
  on-primary-container: '#644000'
  inverse-primary: '#835500'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#66e1ff'
  on-tertiary: '#003640'
  tertiary-container: '#32c6e5'
  on-tertiary-container: '#004f5d'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffddb4'
  primary-fixed-dim: '#ffb955'
  on-primary-fixed: '#291800'
  on-primary-fixed-variant: '#633f00'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
  surface-base: '#0A0A0C'
  surface-raised: '#121216'
  surface-overlay: '#1A1A22'
  surface-hover: '#242430'
  border-subtle: '#272732'
  border-luminous: rgba(245, 166, 35, 0.35)
  amber-highlight: '#FFB946'
  gold-muted: '#D4AF5A'
  text-primary: '#F7F5F0'
  text-secondary: '#96907F'
  text-tertiary: '#625E54'
  status-emerald: '#10B981'
  status-cyan: '#06B6D4'
typography:
  display-hero:
    fontFamily: Newsreader
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Newsreader
    fontSize: 38px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
  headline-sm:
    fontFamily: Sora
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Sora
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Sora
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Sora
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-mono-lg:
    fontFamily: Space Mono
    fontSize: 13px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.06em
  label-mono-sm:
    fontFamily: Space Mono
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.08em
  stat-metric:
    fontFamily: Space Mono
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 36px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2.5rem
  margin: 2rem
  margin-mobile: 1.25rem
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4.5rem
---

## Brand & Style

This design system defines an ultra-premium, AI-first executive recruitment and ATS/CRM platform tailored for discerning search firms, boutique headhunters, and high-scale talent agencies. The aesthetic bridges the authoritative confidence of heritage private banking with the razor-sharp precision of high-performance developer tooling.

The visual style is characterized by:
- **Obsidian Dark-Mode Architecture:** Deep, light-absorbing obsidian foundations punctuated by low-reflectance charcoal containers rather than flat digital black.
- **Warm Gilded Accents:** Precision-engineered amber and soft gold highlights that signify enterprise intelligence, human expertise, and high deal volume.
- **Editorial vs. Monospace Tension:** High-contrast pairing of an authoritative literary serif for big-picture narratives and display hooks, contrasted immediately against utilitarian geometric monospace for metrics, terminal commands, candidate attributes, and pricing metadata.
- **Luminescent Glassmorphism:** Micro-borders with directional linear gradients, translucent overlays, and focused inner glows that emphasize the high-value "Agency" and AI intelligence features.

## Colors

The palette establishes an unapologetically dark, prestige visual environment designed to reduce fatigue during multi-hour sourcing sprints while elevating perceived deal value.

- **Background & Base Layers:** `#0A0A0C` serves as the canvas core. Stacked elements step up to `#121216` (secondary cards) and `#1A1A22` (interactive modals, tooltips, high-level tiers).
- **Primary Brand Accents:** Warm Amber `#F5A623` and `#FFB946` are applied with strict intentionality—reserved for core conversion actions, active pricing highlights, the "Most Popular" glow, and AI inference badges.
- **Status Indicators:** Micro-dots and telemetry indicators leverage vivid Emerald `#10B981` (active sync, matching models operational, live candidates) and Electric Cyan `#06B6D4` (API connectivity, candidate privacy shields).
- **Text & Contrast:** Headers leverage cream-white `#F7F5F0` to prevent harsh optical glare; secondary descriptive text utilizes the warm neutral `#96907F` for optimal legibility against dark slate backdrops.

## Typography

Typography delivers an intentional dialogue between classic editorial craftsmanship and rigorous mechanical computation:

- **Editorial Serif (Newsreader):** Used for large scale display headlines, hero banners, and value propositions. It introduces human warmth, prestige, and executive polish. Italicized words within serif headlines (e.g. *shortlist*, *paid back*) serve as emotional focal points.
- **Modern Sans (Sora):** Serves as the functional workhorse for body copy, card headings, interactive controls, and modal dialogs, ensuring clarity at small sizes.
- **Monospace (Space Mono):** Used for all technical indicators: feature pill badges, system status labels, pricing tiers, numerical metrics, table headers, and AI log streams. Always rendered with uppercase tracking for high legibility.

## Layout & Spacing

The spatial architecture leverages a centered 12-column grid system capped at a maximum width of 1200px for balanced reading rhythm and structured dashboard clarity.

- **Desktop (1024px+):** 12 columns with 24px (1.5rem) gutters and 32px (2rem) canvas margins. Section pacing alternates between dense component modules (`space-2xl` gap) and breathing room between functional sections (`space-3xl`).
- **Tablet (768px - 1023px):** 8 columns with 16px (1rem) gutters. Pricing cards transition from a horizontal 3-column row to a 2+1 stacked arrangement.
- **Mobile (< 768px):** 4 columns with 16px gutters and 20px outer margin. Layout elements collapse strictly to vertical stacks. Key pricing tiers present the flagship Agency tier at the top or center with prominent visual elevation.

## Elevation & Depth

Visual hierarchy is constructed through luminous edge lighting and subtle translucent surfaces rather than heavy drop shadows:

- **Surface Tiers:**
  - `Level 0 (Canvas):` Deep obsidian `#0A0A0C`.
  - `Level 1 (Panels & Cards):` Charcoal slate `#121216` enclosed in a 1px hairline border of `#272732`.
  - `Level 2 (Interactive Floating Layers):` Semi-translucent `#1A1A22` backed by a `backdrop-filter: blur(16px)` layer.
- **Border Lighting & Radiance:**
  - Standard cards utilize quiet low-contrast borders: `border: 1px solid rgba(255, 255, 255, 0.07)`.
  - The flagship "Agency" card features an active gradient hairline: `linear-gradient(180deg, rgba(245, 166, 35, 0.6) 0%, rgba(245, 166, 35, 0.1) 100%)` accompanied by a localized ambient top-glow (`box-shadow: 0 -24px 60px -12px rgba(245, 166, 35, 0.15)`).
- **Subtle Inner Gleam:** Premium containers incorporate an inset directional highlight (`box-shadow: inset 0 1px 0 0 rgba(255, 255, 255, 0.08)`), emulating precision-milled dark anodized hardware.

## Shapes

The design uses a refined geometric scale (`roundedness: 2`) that balances modern software aesthetics with crisp enterprise authority:

- **Cards and Outer Containers:** Standardized on `rounded-lg` (16px / 1rem) for an ergonomic, polished enclosure.
- **Buttons, Toggles, and Badges:** Standardized on `rounded-md` (8px / 0.5rem) to maintain distinct clickable tactility. Status pills and interactive billing switcher tabs leverage fully rounded pill geometry (`rounded-full` / 9999px) for quick scanning.
- **Input Fields & Modal Dialogs:** Calibrated to 10px-12px corner radii to match nested card proportions.

## Components

### Buttons
- **Primary (CTA / Booking):** Background `#F5A623`, foreground `#0A0A0C` (Sora, 600 weight). Subtle top border highlight (`rgba(255, 255, 255, 0.3)`). Hover: background `#FFB946`, shadow `0 0 20px rgba(245, 166, 35, 0.35)`.
- **Secondary / Ghost:** Transparent background with 1px border (`#272732`), foreground `#F7F5F0`. Hover: background `#1A1A22`, border-color `#96907F`.
- **Terminal / Micro-Action:** Space Mono 11px uppercase pill with an amber prefix glyph (`>`), padding `6px 12px`.

### Pricing Cards
- **Starter & White Label:** Charcoal surface `#121216`, 1px border `#272732`. Features monospaced tier tag, price in large cream Sora, and quiet muted gray checkmarks.
- **Agency (Featured Tier):** Surface `#16161E`, wrapped in the amber luminous border gradient with a persistent ambient halo. Includes a floating top badge: "MOST POPULAR", styled with Space Mono uppercase lettering on an amber background.
- **Feature Items:** Checkmarks rendered in warm amber (`#F5A623`) or vibrant emerald (`#10B981`) inside a subtle circular container (`rgba(245, 166, 35, 0.1)`).

### Interactive Billing Toggle
- Pill-shaped track (`#121216` with 1px `#272732` border).
- Active thumb: Smooth sliding capsule in `#1A1A22` with a subtle white highlight border. Text switches between active cream `#F7F5F0` and inactive `#96907F`, accompanied by a green micro-badge: "2 MONTHS FREE".

### FAQ Accordions
- Minimalist hairline dividers (`#272732`).
- Rest state: Sora 16px medium text with an amber/gold minimal plus (`+`) indicator on the far right.
- Expanded state: Question shifts to cream `#F7F5F0`, plus rotates 45 degrees into a multiplication sign (`×`), revealing an indented answer block in `#96907F` with a soft fading slide transition.

### Status Indicators & Badges
- System heartbeat pill: 8px circular emerald beacon with an animated radial ping (`box-shadow: 0 0 8px #10B981`), paired with Space Mono label: "ALL SYSTEMS OPERATIONAL".
