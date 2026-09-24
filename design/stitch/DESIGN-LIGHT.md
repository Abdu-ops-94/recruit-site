---
name: Alabaster Amber
colors:
  surface: '#f9f9f6'
  surface-dim: '#dadad7'
  surface-bright: '#f9f9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f4f1'
  surface-container: '#eeeeeb'
  surface-container-high: '#e8e8e5'
  surface-container-highest: '#e2e3e0'
  on-surface: '#1a1c1a'
  on-surface-variant: '#564338'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f1f1ee'
  outline: '#897267'
  outline-variant: '#ddc1b3'
  surface-tint: '#9b4500'
  primary: '#903f00'
  on-primary: '#ffffff'
  primary-container: '#b45309'
  on-primary-container: '#fff1eb'
  inverse-primary: '#ffb68e'
  secondary: '#555f6f'
  on-secondary: '#ffffff'
  secondary-container: '#d6e0f3'
  on-secondary-container: '#596373'
  tertiary: '#8a421c'
  on-tertiary: '#ffffff'
  tertiary-container: '#a85a32'
  on-tertiary-container: '#fff0eb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  background: '#f9f9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e2e3e0'
typography:
  headline-xl: {fontFamily: Newsreader, fontSize: 40px, fontWeight: '400', lineHeight: 48px, letterSpacing: -0.02em}
  headline-lg: {fontFamily: Newsreader, fontSize: 32px, fontWeight: '400', lineHeight: 40px, letterSpacing: -0.015em}
  headline-md: {fontFamily: Newsreader, fontSize: 22px, fontWeight: '500', lineHeight: 28px, letterSpacing: -0.01em}
  headline-sm: {fontFamily: Newsreader, fontSize: 18px, fontWeight: '500', lineHeight: 24px}
  body-lg: {fontFamily: Plus Jakarta Sans, fontSize: 16px, fontWeight: '400', lineHeight: 24px}
  body-md: {fontFamily: Plus Jakarta Sans, fontSize: 14px, fontWeight: '400', lineHeight: 20px}
  body-sm: {fontFamily: Plus Jakarta Sans, fontSize: 13px, fontWeight: '400', lineHeight: 18px}
  label-md: {fontFamily: Plus Jakarta Sans, fontSize: 12px, fontWeight: '600', lineHeight: 16px, letterSpacing: 0.02em}
  label-sm: {fontFamily: Plus Jakarta Sans, fontSize: 11px, fontWeight: '600', lineHeight: 14px, letterSpacing: 0.03em}
  mono-data: {fontFamily: JetBrains Mono, fontSize: 12px, fontWeight: '500', lineHeight: 16px}
  mono-code: {fontFamily: JetBrains Mono, fontSize: 11px, fontWeight: '400', lineHeight: 14px}
rounded: {sm: 0.125rem, DEFAULT: 0.25rem, md: 0.375rem, lg: 0.5rem, xl: 0.75rem, full: 9999px}
spacing: {gutter: 1.25rem, gutter-desktop: 1.75rem, margin: 1.5rem, margin-desktop: 2.5rem, space-xs: 0.25rem, space-sm: 0.5rem, space-md: 1rem, space-lg: 1.5rem, space-xl: 2.5rem}
---

## Brand & Style

Editorial, high-trust "private advisory firm" aesthetic — the opposite of the Obsidian Gold dark theme. Generous whitespace, razor-sharp hairline borders, warm paper-derived surfaces (alabaster, ivory, bone), and a single burnished-amber accent (`#B45309`) instead of the dark theme's glowing gold. No drop shadows for depth — only hairline borders (`#E2E2DC`) and faint umber-tinted micro-shadows.

## Colors

- **Canvas:** `#FBFBFA`/`#f9f9f6` alabaster warm white. Cards sit on pure white `#FFFFFF` with a `1px solid #E2E2DC` hairline border.
- **Accent:** Burnished amber `#B45309` (hover `#92400E`) — used sparingly for primary buttons, active nav state, focus rings.
- **Text:** Deep obsidian ink `#111827`/`#1a1c1a` primary, slate charcoal `#4B5563`/`#564338` secondary.

## Typography

Newsreader (serif headlines, same as dark) + **Plus Jakarta Sans** (body/UI — not Sora) + **JetBrains Mono** (data/labels — not Space Mono). This is a different font pairing from the dark theme, not just a recolor.

## Shapes

Roundness is tighter than dark theme: `rounded` default 4px (vs 8px dark). Crisp, print-editorial geometry rather than soft glassmorphism.

## Components

- **Primary button:** solid `#B45309`, white text, 4px corners, `0 1px 2px` shadow only.
- **Cards:** white on alabaster, `1px solid #E2E2DC`, no glow.
- **Status chips:** light tint pill, e.g. "Vetted" = `#FEF3C7` bg / `#78350F` text.
- **Focus ring:** `0 0 0 3px rgba(180, 83, 9, 0.12)` amber glow on inputs.
