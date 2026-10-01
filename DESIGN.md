---
name: Clinical Precision
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#444653'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#747684'
  outline-variant: '#c4c5d5'
  surface-tint: '#3456c1'
  primary: '#00216e'
  on-primary: '#ffffff'
  primary-container: '#0033a0'
  on-primary-container: '#8ea6ff'
  inverse-primary: '#b6c4ff'
  secondary: '#006874'
  on-secondary: '#ffffff'
  secondary-container: '#7fedfe'
  on-secondary-container: '#006b77'
  tertiary: '#102a45'
  on-tertiary: '#ffffff'
  tertiary-container: '#28405c'
  on-tertiary-container: '#94accd'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#001550'
  on-primary-fixed-variant: '#133ca8'
  secondary-fixed: '#97f0ff'
  secondary-fixed-dim: '#66d6e7'
  on-secondary-fixed: '#001f24'
  on-secondary-fixed-variant: '#004f58'
  tertiary-fixed: '#d2e4ff'
  tertiary-fixed-dim: '#b0c8eb'
  on-tertiary-fixed: '#001c37'
  on-tertiary-fixed-variant: '#314865'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
  deep-navy: '#001B44'
  clinical-cyan: '#00B4D8'
  surface-ice: '#F4F7FB'
  border-subtle: '#E2E8F0'
  success-clinical: '#059669'
  warning-clinical: '#D97706'
  critical-clinical: '#DC2626'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.015em
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  metric-counter:
    fontFamily: Plus Jakarta Sans
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.03em
  data-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an authoritative, clinical, and human-centric visual vocabulary for next-generation biotechnology and healthcare interfaces. Driven by the empirical clarity of pharmaceutical giants and modern digital health platforms, it pairs institutional trust with technical agility.

The aesthetic philosophy centers on **Corporate Modernism with Precision Engineering**:
- Crisp, clinical whitespace that allows high-density clinical data, molecular metrics, and narrative breakthroughs to breathe.
- Uncompromising visual contrast, ensuring clinical-grade accessibility (WCAG AAA alignment where diagnostics and telemetry occur).
- Precision structural framing via micro-borders and deliberate tonal stratification rather than heavy artificial shadows.
- Micro-interactions that feel engineered, instantaneous, and purposeful—avoiding frivolous animation in favor of stable, confident state transitions.

## Colors

The palette is anchored by the authoritative depth of **Pfizer Royal Blue** (`#0033A0`) and deep clinical navy (`#0A2540`), evoking institutional research, pharmacological efficacy, and verified authority. 

### Color Roles
- **Primary (`#0033A0`)**: Directs focused interactive intent—primary CTAs, selected tab anchors, key graph nodes, and prominent brand accents.
- **Secondary (`#0097A7` / Clinical Cyan `#00B4D8`)**: Represents digital diagnostics, active laboratory telemetry, discovery highlights, and molecular indicators.
- **Tertiary (`#0A2540`)**: Imparts structural weight to headlines, metric counters, active navigation items, and dense observational readouts.
- **Neutrals & Surfaces**: Clean white (`#FFFFFF`) forms the primary interaction card face, resting against `surface-ice` (`#F4F7FB`) for crisp page hierarchy. Slate neutrals (`#64748B`) govern supporting metadata, secondary icons, and structural divider rules.

## Typography

The type system blends the architectural authority and humanistic geometry of **Plus Jakarta Sans** for headlines and high-impact metrics with the utilitarian legibility of **Inter** for clinical data sets, narrative scientific documentation, and UI controls.

### Structural Roles
- **Display & Headlines (`Plus Jakarta Sans`)**: Tight negative letter-spacing creates compact, executive authority suited for scientific titles, trial phases, and high-level medical findings.
- **Data & Body (`Inter`)**: Tuned for maximum screen legibility, dense tabular readouts, and multi-paragraph technical disclosures.
- **Diagnostics & Telemetry (`JetBrains Mono`)**: Applied to gene sequences, chemical assay lot codes, specimen IDs, and calibrated instrumentation metrics.

## Layout & Spacing

A disciplined 12-column responsive grid underpins all desktop surfaces, enforcing structural cohesion across data dashboards and public-facing scientific communications.

- **Desktop (1200px+)**: 12 columns with `gutter` of 1.5rem and lateral page `margin` of 3rem to 4rem (or max container width of 1360px centered).
- **Tablet (768px - 1199px)**: 8 columns with 1.25rem gutters and 2rem outer margins. Multicolumn research cards collapse into dual-column modules.
- **Mobile (< 768px)**: 4 columns with 1rem gutter and 1.25rem margin. Side rails and metric panels compress into horizontally scrolling trays or stacked status cards.

The system uses an 8px base rhythmic grid (`space-xs` = 4px, `space-sm` = 8px, `space-md` = 16px, `space-lg` = 24px, `space-xl` = 40px) to maintain predictable, harmonious spacing between diagnostic widgets and prose elements.

## Elevation & Depth

To sustain a sterile, clinical environment, depth is achieved through **tonal stratification and micro-borders** rather than heavy drop shadows.

- **Surface Level 0 (Canvas)**: Tinted medical background (`#F4F7FB`), serving as the stable baseline for page structure.
- **Surface Level 1 (Panels & Cards)**: Pure white (`#FFFFFF`) with a sharp 1px micro-border (`#E2E8F0`). Shadow is minimal: `0 1px 3px rgba(10, 37, 64, 0.04)`.
- **Surface Level 2 (Interactive Overlays & Flyouts)**: Elevated white cards with subtle cyan-tinted atmospheric depth: `0 8px 24px -4px rgba(0, 51, 160, 0.08), 0 2px 6px rgba(10, 37, 64, 0.03)`.
- **Surface Level 3 (Modals & Critical Alerts)**: Floating centered surfaces backed by an accessible 40% deep-navy wash (`#001B44` at 0.40 opacity) with smooth backdrop blur (4px) to retain clinical context.

## Shapes

The design system maintains a **Soft (`1`)** shape language. Sharp precision edges are slightly tempered to balance surgical accuracy with human-centered care.

- Standard cards, input fields, containers, and data grids employ `0.25rem` (4px) to `0.5rem` (8px) corner radii.
- Interactive status tags, clinical phase markers, and scientific badges use continuous pill radiuses (9999px) to immediately signal status without competing with rectangular content scaffolding.
- Strict visual restraint: Avoid circular floating buttons or oversized organic blobs that compromise technical gravitas.

## Components

### Buttons
- **Primary**: Solid clinical blue (`#0033A0`) background with crisp white typography, 40px height, 8px radius, and 16px horizontal padding. Subtle hover shifts to `#002575` with zero vertical displacement.
- **Secondary / Scientific Ghost**: Transparent fill with a 1px border (`#0033A0`), blue text, and light ice-blue tint (`#0033A0` at 4% opacity) on interaction.
- **Destructive**: Minimal white background with a `#DC2626` outline and text, transitioning to full crimson fill on deliberate confirmation.

### Badges & Scientific Pills
- Continuous pill shape (rounded-full), uppercase or title-case text in `label-sm` (`font-weight: 600`).
- Color mappings:
  - *Phase I/II/Active Research*: Pale cyan fill (`rgba(0, 180, 216, 0.1)`) with deep cyan text (`#007799`).
  - *Approved / Verified*: Pale emerald (`rgba(5, 150, 105, 0.1)`) with clinical green text (`#059669`).
  - *Under Review*: Soft amber (`rgba(217, 119, 6, 0.1)`) with warm amber text (`#B45309`).

### Cards & Clinical Containers
- White background with a 1px border in `#E2E8F0`. Internal padding is generous (`space-lg` / 24px).
- Optional 3px solid accent spine on the left border (using `#0033A0` or `#00B4D8`) to signal primary research categories or critical triage levels.

### Data Metrics & Key Performance Indicators (KPIs)
- Prominent metric readouts paired with micro-labels. Value uses `metric-counter` in deep navy (`#0A2540`), accompanied by a trend chip (pill badge) and a caption in `body-sm` (`#64748B`).

### Form Inputs & Search
- Height: 42px. 1px border `#CBD5E1` on pure white background.
- Focus state triggers an immediate, sharp outline: 1px `#0033A0` accompanied by a 2px outer aura in `rgba(0, 51, 160, 0.15)`.

### Lists & Protocol Tables
- Clean horizontal separator lines (`#F1F5F9`) with no vertical grid lines.
- Alternate zebra-striping is omitted; hover states gently tint rows with `#F8FAFC`. Table headers are set in `label-sm`, all caps, tracking +0.05em in neutral slate.