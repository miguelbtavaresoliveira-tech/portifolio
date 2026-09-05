---
name: Terminal Obsidian
colors:
  surface: '#0b141c'
  surface-dim: '#0b141c'
  surface-bright: '#313a43'
  surface-container-lowest: '#060f16'
  surface-container-low: '#141c24'
  surface-container: '#182028'
  surface-container-high: '#222b33'
  surface-container-highest: '#2d363e'
  on-surface: '#dae3ee'
  on-surface-variant: '#c0c7d4'
  inverse-surface: '#dae3ee'
  inverse-on-surface: '#29313a'
  outline: '#8b919d'
  outline-variant: '#414752'
  surface-tint: '#a2c9ff'
  primary: '#a2c9ff'
  on-primary: '#00315c'
  primary-container: '#58a6ff'
  on-primary-container: '#003a6b'
  inverse-primary: '#0060aa'
  secondary: '#67df70'
  on-secondary: '#00390d'
  secondary-container: '#27a640'
  on-secondary-container: '#00320a'
  tertiary: '#ffb4ac'
  on-tertiary: '#690007'
  tertiary-container: '#ff7b70'
  on-tertiary-container: '#790009'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d3e4ff'
  primary-fixed-dim: '#a2c9ff'
  on-primary-fixed: '#001c38'
  on-primary-fixed-variant: '#004882'
  secondary-fixed: '#83fc89'
  secondary-fixed-dim: '#67df70'
  on-secondary-fixed: '#002105'
  on-secondary-fixed-variant: '#005317'
  tertiary-fixed: '#ffdad6'
  tertiary-fixed-dim: '#ffb4ac'
  on-tertiary-fixed: '#410002'
  on-tertiary-fixed-variant: '#93000d'
  background: '#0b141c'
  on-background: '#dae3ee'
  surface-variant: '#2d363e'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 21px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  code-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  badge-label:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.04em
  table-header:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
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
  space-2xs: 0.125rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-base: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4rem
  gutter-mobile: 1rem
  gutter-desktop: 1.5rem
  container-max: 1440px
---

## Brand & Style

This design system blends developer-centric engineering aesthetics with high-assurance offensive security operations. Built for modern portfolios, vulnerability management suites, and penetration testing consoles, the visual tone conveys precision, tactical restraint, and authoritative domain expertise.

The design movement anchors in **Precision Engineering & Tactical Minimalism**. It avoids decorative neon clichés in favor of deliberate, high-density interfaces reminiscent of Unix terminals and mission-critical audit consoles. 

Key attributes:
- **Operative Rigor:** Visual hierarchy is governed by semantic status cues, structured tabular data, and explicit structural boundaries rather than soft decorative blurs.
- **Cognitive Quiet:** A near-black canvas absorbs visual fatigue during extended nocturnal workflows, enabling tactical alerts and telemetry data to communicate state instantaneously.
- **Architectural Contrast:** Crisp 1px structural outlines delineate spatial zones, reinforcing an uncompromising sense of safety, precision, and order.

## Colors

The palette establishes an ultra-high-contrast hierarchy (exceeding WCAG AAA for body text at >11:1 against the canvas). Surface colors establish layered modular zones without heavy drop shadows.

### Surface Palette
- **Canvas Base (`#0D1117`):** Primary background for dashboards, root shell containers, and full-bleed viewport roots.
- **Surface Card / Raised (`#161B22`):** Default container tier for cards, table rows, and navigational sidebars.
- **Surface Overlay / Hover (`#21262D`):** Interactive resting states, hovered rows, tooltips, and elevated modal panels.
- **Surface Inset (`#010409`):** Recessed code blocks, integrated terminal consoles, and nested telemetry streams.

### Borders & Dividers
- **Subtle Stroke (`#30363D`):** 1px explicit division lines, input borders, structural panels, and grid dividers.
- **Muted Stroke (`#21262D`):** Low-priority internal separators and disabled control outlines.
- **Active Focus Stroke (`#58A6FF`):** Focus rings and selected node highlights.

### Typography
- **Primary Text (`#E6EDF3`):** High-clarity headings, metric values, and primary interface labels.
- **Muted Text (`#8B949E`):** Secondary descriptions, meta attributes, timestamps, and column headers.
- **Subtle / Ghost Text (`#484F58`):** Placeholders, disabled states, and auxiliary terminal lines.

### Functional & Semantic Accents
- **Tech Blue (`#58A6FF`):** Interactive actions, active tabs, hyperlinks, information indicators, and primary CTAs.
- **Operational Green (`#3FB950`):** Pass statuses, active daemons, secure configurations, and clean vulnerability scans.
- **Critical Red (`#F85149`):** Exploitable CVEs, unauthenticated breaches, danger action confirmations, and critical severities.
- **Warning Amber (`#D29922`):** Medium risks, stale credentials, and pending audits.
- **Purple (`#BC8CFF`):** Exploitation vector markers, custom script payloads, and tagged metadata.

## Typography

The typographic hierarchy enforces clear cognitive separation between executive-level UI context and technical machine data.

- **Primary Interface Font (Inter):** Leveraged for all navigation, headings, informational copy, metrics, and standard form controls. Inter provides neutral, highly readable geometry at small pixel densities.
- **Monospaced Data Font (JetBrains Mono):** Mandated for code snippets, hash digests, IP addresses, CVE IDs, terminal output, status indicators, and numeric badges. It delivers vertical character alignment essential for scan-heavy data inspections.

Numeric tabulations and metrics must enforce tabular figures (`font-feature-settings: 'tnum' 1`) to ensure stable alignment during real-time telemetry updates.

## Layout & Spacing

This design system uses a strict 8pt base grid system (with 4pt micro-steps for tight inline controls, badges, and terminal blocks). 

### Layout Model
- **Grid Structure:** 12-column fluid grid bounded by a max-width of `1440px`.
- **Gutters:** `16px` on mobile/tablet viewports, widening to `24px` on desktop viewports.
- **Margins:** `16px` outer gutters on viewports `< 768px`; `24px` on viewports `< 1280px`; auto-centered with minimum `32px` padding on expansive displays.

### Responsive Breakpoints & Adaptations
- **Mobile (< 768px):** Single-column stacked layout. Left-hand terminal trees and telemetry sidebars collapse into drawer sheets. Tables shift to card-list summaries. Typography scales down via mobile tokens.
- **Tablet (768px – 1023px):** 2-column split configuration. Metric dashboards collapse into 2x2 grids. Filter bars allow horizontal overflow scrolling with muted edge fades.
- **Desktop (1024px+):** Full 12-column persistent dashboard layout. Fixed 260px tactical navigation sidebar, 3-to-4 column security metric cards, and side-by-side terminal log inspections.

## Elevation & Depth

Visual depth is achieved through **tonal stacking and low-contrast outlines** rather than fuzzy drop shadows, reinforcing an authentic software-engineer/security-console feel.

### Layering Hierarchy
1. **Base Surface (0dp / Lowest):** `#0D1117` — Deepest viewport canvas.
2. **Sunken Panes (-1dp):** `#010409` with `1px solid #21262D` border — Terminal consoles, code inspectors, and real-time packet monitors.
3. **Resting Cards (1dp):** `#161B22` with `1px solid #30363D` border — Security cards, portfolio project modules, and tabular sections.
4. **Elevated Panels & Flyouts (2dp):** `#1F242C` with `1px solid #383F47` — Dropdowns, popovers, and quick-filter trays. Adds subtle ambient shadow: `box-shadow: 0 8px 24px rgba(1, 4, 9, 0.6)`.
5. **Modal Overlays (3dp):** `#161B22` with `1px solid #58A6FF` (subtle 20% opacity border) — Exploit payload inspectors, modal confirmations, and prompt overrides. Backdrop uses `background-color: rgba(1, 4, 9, 0.8)` with `backdrop-filter: blur(4px)`.

## Shapes

The design system maintains a **Soft (Level 1)** structural rounding profile. Excessively round or pill-shaped cards feel too consumer-oriented; strict sharp corners feel overly legacy. A compact 6px (`0.375rem`) default creates a balanced, modern, and disciplined industrial look.

- **Base Radius (`0.25rem` / 4px):** Badges, tags, audit status pills, inline code containers, checkboxes, and tooltips.
- **Container Radius (`0.375rem` / 6px):** Buttons, text inputs, segmented tabs, and compact dropdown menus.
- **Card Radius (`0.5rem` / 8px):** Primary content cards, code blocks, modal windows, and terminal envelopes.

## Components

### Buttons
- **Primary:** Background `#238636` (tactical green) with text `#FFFFFF` and subtle border `rgba(240, 246, 252, 0.1)`. Hover state `#2EA043`. Active state `#298E3B`.
- **Secondary (Default):** Background `#21262D`, text `#C9D1D9`, border `1px solid #30363D`. Hover state background `#30363D`, border `#8B949E`.
- **Danger:** Background `#21262D`, text `#F85149`, border `1px solid #30363D`. Hover: background `#B62324`, text `#FFFFFF`, border `transparent`.
- **Ghost / Terminal Action:** Background transparent, text `#8B949E`. Hover: text `#58A6FF`, background `#161B22`.

### Chips & Badges
- Constructed exclusively with `JetBrains Mono` at `11px` (medium weight).
- **Format:** `px-2 py-0.5`, rounded `4px`, border `1px solid`.
- **Success / Passed:** Background `rgba(63, 185, 80, 0.15)`, text `#3FB950`, border `rgba(63, 185, 80, 0.4)`. Includes a small inline green pulsing dot.
- **Critical / Vulnerable:** Background `rgba(248, 81, 73, 0.15)`, text `#F85149`, border `rgba(248, 81, 73, 0.4)`.
- **Info / CVE Tag:** Background `rgba(88, 166, 255, 0.15)`, text `#58A6FF`, border `rgba(88, 166, 255, 0.4)`.

### Form Controls (Inputs, Checkboxes, Radios)
- **Input Fields:** Background `#0D1117`, border `1px solid #30363D`, text `#E6EDF3`, placeholder `#484F58`. Height `32px` or `36px`. On focus: border `#58A6FF`, outline `1px solid #58A6FF`, box-shadow `0 0 0 3px rgba(88, 166, 255, 0.25)`.
- **Checkboxes & Radios:** Size `16px x 16px`, background `#0D1117`, border `1px solid #30363D`. Checked: background `#1F6FEB`, border `#1F6FEB` with high-contrast `#FFFFFF` checkmark icon.

### Cards & Modules
- Resting state uses `#161B22` background with `#30363D` border.
- Headers are divided from card content with a continuous `1px solid #21262D` horizontal rule.
- Interactive cards feature a top border hover accent: transition border-top color to `#58A6FF`.

### Lists & Data Tables
- Headers: Background `#161B22`, text `#8B949E`, text-transform uppercase, size `12px`, padding `8px 16px`.
- Rows: Background `#0D1117`, alternating rows `#11161D`. Hover row state: background `#161B22`. Bottom divider: `1px solid #21262D`.
- Numeric columns and status indicators right-align and utilize `JetBrains Mono`.

### Domain-Specific Components
- **Audit Log Console:** Sunken container (`#010409`) with a sticky header bar containing mock window dots (red/yellow/green) and an active branch/target badge. Text stream renders in `JetBrains Mono` with timestamp in `#484F58`, severity in `#3FB950`/`#F85149`, and payload messages in `#E6EDF3`.
- **CVSS Score Meter:** Compact segmented bar (10 blocks) showing numerical score (e.g., `9.8 CRITICAL`) colored dynamically based on threshold (`#3FB950` low, `#D29922` medium, `#F85149` critical).