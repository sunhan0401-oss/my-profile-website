---
name: Lumina Portfolio
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#434655'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#0058be'
  on-secondary: '#ffffff'
  secondary-container: '#2170e4'
  on-secondary-container: '#fefcff'
  tertiary: '#4e565d'
  on-tertiary: '#ffffff'
  tertiary-container: '#676e76'
  on-tertiary-container: '#eaf1fa'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#dce3ec'
  tertiary-fixed-dim: '#c0c7d0'
  on-tertiary-fixed: '#151c23'
  on-tertiary-fixed-variant: '#40484f'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-xl:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.025em
  display-lg:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.025em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system crafts an intentional, high-credibility digital presence for tech-forward professionals, engineers, and digital architects. The visual language balances meticulous precision with approachable warmth, conveying engineering rigor and refined product sensibility.

### Design Archetype
The style relies on **Modern Tech-Forward Minimalism** integrated with subtle, structural elevation:
- **Calm, High-Key Canvas:** A dual-layer light backdrop system prioritizing signal over noise.
- **Micro-Structured Containers:** Thin, architectural hairline dividers and low-contrast borders establishing quiet order.
- **Tactile Clarity:** Crisp typography pairing utilitarian readability with refined proportions, punctuated by purposeful cobalt and azure signals.
- **Editorial Breathing Room:** Expansive negative space that guides scanning, respects eye cadence, and highlights artifact outcomes over ornamental noise.

## Colors

The palette balances stark, functional slate typography against an airy dual-white environment, accented with authoritative blue signals.

### Color Tokens & Roles
- **Canvas Base (`#FFFFFF`):** Primary canvas surface for nested cards, interactive surfaces, and dialog panels.
- **Canvas Substrate (`#F8FAFC`):** Viewport-level backdrop providing subtle tonal separation beneath pure white surface cards.
- **Primary Accent (`#2563EB`):** High-priority actions, key metric callouts, active timeline markers, and focus rings.
- **Secondary Accent (`#3B82F6`):** Hover transitions, active navigational states, and iconography accents.
- **Tertiary Soft Accent (`#EFF6FF`):** Background fills for metadata chips, capability badges, and code snippets.
- **Border Substrate (`#E2E8F0`):** Single-pixel perimeter strokes framing structural cards, dividers, and inputs.
- **Text Primary (`#0F172A`):** Headlines, hero titles, stat values, and heavy interactive labels.
- **Text Secondary (`#334155`):** Body paragraphs, narrative excerpts, and role descriptions.
- **Text Muted (`#64748B`):** Timestamps, metadata keys, tertiary icons, and micro-labels.

## Typography

Typography relies uniformly on **Inter** to maintain an engineered, neutral aesthetic across all breakpoints.

- **Display & Large Headlines:** Dense optical tracking (`-0.02em` to `-0.03em`) creates a solid architectural anchor for project titles and hero intros.
- **Body & Explanatory Copy:** Relaxed line heights (1.5x–1.6x) ensure effortless reading across deep-dive case studies and bios.
- **Labels & Micro-Tags:** Subtle positive tracking (`0.02em`) on small uppercase or badge labels keeps dense technical tags legible.
- **Dynamic Adaptability:** All titles above 32px step down precisely for mobile screens, preventing awkward text wrapping and maintaining vertical visual balance.

## Layout & Spacing

The layout is built around a structured, maximum-width containment grid to deliver intentional pacing and clear reading order.

### Grid Infrastructure
- **Desktop (≥ 1024px):** Centered container maxing at `1120px` (or `1280px` for wide case studies) using a 12-column grid, `1.5rem` gutters, and `2rem` outer edge safety margins.
- **Tablet (768px – 1023px):** 8-column layout with `1.5rem` gutters and `2rem` outer margins. Side-by-side modules shift from 4/8 column allocations to balanced vertical stacks.
- **Mobile (< 768px):** 4-column responsive grid with `1rem` gutters and `1.25rem` outer margins. Multi-column cards collapse to linear stacks.

### Vertical Rhythm
- Section separations use `space-2xl` on mobile and `space-3xl` on desktop.
- Card padding remains strict: `space-lg` for standard cards, expanding to `space-xl` for key hero cards on desktop.

## Elevation & Depth

Visual hierarchy uses a refined system of crisp hairline borders alongside soft, tinted ambient diffusion rather than standard heavy drop shadows.

### Elevation Levels
- **Level 0 (Flat Canvas):** Surfaces rest flush on `#F8FAFC`. Zero elevation, separated purely via spatial margins or hairline strokes.
- **Level 1 (Resting Cards & Modules):** Pure `#FFFFFF` fill resting on the `#F8FAFC` canvas, bounded by a 1px solid `#E2E8F0` border. Shadow is ambient and feathered:
  `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.03), 0 1px 2px -1px rgba(15, 23, 42, 0.02);`
- **Level 2 (Hovered Cards & Interactive States):** Applied smoothly on interaction (`transition: all 200ms cubic-bezier(0.16, 1, 0.3, 1)`):
  `border-color: #CBD5E1;`
  `box-shadow: 0 10px 25px -5px rgba(15, 23, 42, 0.05), 0 8px 10px -6px rgba(15, 23, 42, 0.03);`
  Subtle vertical translation (`translateY(-2px)`).
- **Level 3 (Floating Modals & Overlays):** Detached navigation menus, project image lightboxes, and quick-contact drawers:
  `border: 1px solid #E2E8F0;`
  `box-shadow: 0 20px 25px -5px rgba(15, 23, 42, 0.08), 0 10px 10px -5px rgba(15, 23, 42, 0.02);`

## Shapes

The geometric form factor balances crisp modern edges with approachable, subtle curvature (`roundedness: 2`).

### Geometry Rules
- **Base Containers & Cards:** `0.75rem` (12px) to `1rem` (16px) border-radius, pairing naturally with internal `space-lg` padding to avoid interior corner clipping.
- **Buttons, Inputs & Interactive Triggers:** Standardized at `0.5rem` (8px), delivering tactile sharpness and alignment with structural UI grids.
- **Chips, Badges & Micro-Pills:** Full circular curvature (`rounded-full` / `9999px`) to create clear visual contrast between functional cards and informative metadata tags.

## Components

### Buttons
- **Primary:** Filled `#2563EB` background with `#FFFFFF` text. Subtle inner highlight on hover (`#1D4ED8`), transition time of 150ms. Padding: `0.625rem 1.25rem`. Height: `40px`. Font: `label-md`.
- **Secondary / Outline:** Background `#FFFFFF`, 1px solid border `#E2E8F0`, text `#0F172A`. Hover: background `#F8FAFC`, border `#CBD5E1`.
- **Ghost:** Transparent background, text `#334155`. Hover: background `#EFF6FF`, text `#2563EB`.

### Chips & Badges
- **Skill / Tech Stack Pill:** Full pill radius (`9999px`), background `#EFF6FF`, text `#2563EB`, font `label-sm`, padding `0.25rem 0.75rem`. Border: 1px solid `rgba(37, 99, 235, 0.12)`.
- **Status Badge (e.g., "Available for work"):** Pill container with `#F8FAFC` base, `#E2E8F0` border, featuring a pulsing 6px `#22C55E` green indicator dot followed by `#334155` text.

### Cards (Project & Experience)
- **Structure:** `#FFFFFF` fill, 1px border `#E2E8F0`, radius `1rem` (16px), inner padding `1.5rem`.
- **Media Inset:** Featured project thumbnails sit inside with a subtle 1px border `#F1F5F9` and matching `0.5rem` internal corner radius.
- **Hover Behavior:** Slight translation up (`-2px`), subtle box shadow expansion, title color shifts smoothly to `#2563EB`.

### Form Inputs & Textareas (Contact Inquiries)
- **Resting:** Background `#FFFFFF`, border 1px solid `#E2E8F0`, placeholder `#64748B`, font `body-md`. Padding: `0.75rem 1rem`.
- **Focus:** Border color shifts to `#2563EB`, paired with a delicate focus ring: `box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.15)`.

### Timeline & Experience Items
- Monospaced or clean date indicators in `#64748B`, linked vertically by a clean 1.5px solid `#E2E8F0` timeline track. Active/current nodes are anchored with a 8px solid `#2563EB` circular dot.