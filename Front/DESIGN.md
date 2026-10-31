---
name: Neutral Soft Tech
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#464555'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#004d70'
  on-tertiary: '#ffffff'
  tertiary-container: '#006693'
  on-tertiary-container: '#b8e0ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#c9e6ff'
  tertiary-fixed-dim: '#89ceff'
  on-tertiary-fixed: '#001e2f'
  on-tertiary-fixed-variant: '#004c6e'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  reading-body-lg:
    fontFamily: Literata
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 30px
  reading-body-md:
    fontFamily: Literata
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  ui-body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  ui-label-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

This design system is engineered for the intersection of academic rigor and modern technical infrastructure. The brand personality is **Precise, Academic, and Sincere**, prioritizing information clarity and cognitive ease over decorative flair.

The visual direction follows a **Modern / Corporate** style with a "Neutral Soft Tech" twist. It utilizes a refined palette of cool grays and architectural blues to create a calm environment for sustained intellectual work. The interface is intentionally understated to allow complex data and long-form educational content to remain the primary focus. 

Key design principles include:
- **Low Visual Fatigue:** Avoiding high-saturation backgrounds and aggressive transitions.
- **Academic Seriousness:** Utilizing sophisticated typography that commands respect without feeling archaic.
- **Functional Density:** Maintaining a high information-to-ink ratio in management views while allowing generous whitespace in learning environments.

## Colors

The color strategy is built on a foundation of "Subtle Sophistication." We prioritize accessibility and long-term legibility.

- **Primary (Indigo):** A professional Indigo-Slate serves as the primary action color. It is optimized for WCAG AA contrast against white and off-white backgrounds.
- **Secondary (Slate):** Used for metadata, secondary iconography, and supporting UI elements to reduce visual weight.
- **Backgrounds (Off-White/Slate-50):** The primary surface color is a very soft slate-white (#F8FAFC) to reduce the "starkness" of pure white, which can cause eye strain during long reading sessions.
- **Semantic Colors:** 
  - **Success:** Emerald for completion states.
  - **Warning:** Amber for pending academic actions.
  - **Error:** Rose for critical system alerts or failed validations.

## Typography

This design system employs a multi-typeface strategy to distinguish between management interfaces and educational content.

- **UI & Navigation (Geist):** A technical sans-serif used for buttons, labels, inputs, and navigation. Its precise geometry aids in scanning densly packed admin panels.
- **Long-form Reading (Literata):** A refined serif specifically designed for digital reading. It is used for course materials, essays, and documentation to ensure maximum legibility and reduced fatigue.
- **Technical/Code (JetBrains Mono):** Used for code snippets, formulaic notation, and system logs.

**Scale & Rhythm:**
Headlines use tight tracking and bold weights for clear hierarchy. Reading text uses a more generous line-height (approx. 1.6x) to facilitate comfortable horizontal eye movement.

## Layout & Spacing

The layout is governed by an **8px grid system**, ensuring mathematical consistency across all components.

- **Layout Philosophy:** A **Fixed-Fluid Hybrid**. Admin dashboards utilize a fluid 12-column grid to maximize screen real estate, while reading-centric pages (like lessons) use a fixed-width central container (max 720px for text) to prevent excessively long line lengths.
- **Density Tiers:**
  - **Compact:** Used in data tables and sidebars (8px gutters).
  - **Comfortable:** Used in lesson content and landing pages (24px - 32px gutters).
- **Breakpoints:**
  - **Mobile (<640px):** Single column, 16px margins.
  - **Tablet (640px - 1024px):** 8-column grid, 24px margins.
  - **Desktop (>1024px):** 12-column grid, 24px-48px margins.

## Elevation & Depth

To maintain a "Soft Tech" feel, this design system moves away from heavy drop shadows, favoring **low-contrast outlines** and **tonal layers**.

- **Surface Tiers:**
  - **Level 0 (Background):** #F8FAFC (Slate-50).
  - **Level 1 (Cards/Sidebar):** #FFFFFF with a 1px border (#E2E8F0).
  - **Level 2 (Popovers/Modals):** #FFFFFF with a subtle, highly-diffused shadow (0px 10px 15px -3px rgba(0, 0, 0, 0.05)).
- **Ghost Borders:** Elements like input fields and inactive cards use a subtle 1px border that sits just above the background color, creating a "contained" rather than "floating" feel.
- **Depth through Saturation:** Active states are indicated by shifts in background tint (e.g., a 5% Indigo tint on a selected list item) rather than physical elevation.

## Shapes

The shape language is **Professional and Sober**. We use a "Rounded" standard (8px) to soften the technical nature of the application without making it appear juvenile.

- **Standard Elements:** Buttons, Inputs, and Cards use `rounded-md` (8px).
- **Large Containers:** Modals and large content sections use `rounded-lg` (16px).
- **Contextual Shapes:** Badges and status indicators may use `rounded-full` (pill) to distinguish them from interactive buttons.
- **Precision:** Consistency in corner radii is critical. Do not mix sharp and rounded corners within the same component hierarchy.

## Components

### Buttons
- **Primary:** Solid Indigo background, white text, 8px radius. High contrast.
- **Secondary:** Transparent background with a Slate-200 border. Indigo text.
- **Ghost:** No background or border. Slate-600 text, used for low-priority actions.

### Cards
- Card components should use a white background and a 1px Slate-200 border. 
- Avoid shadows unless the card is being dragged or is a primary modal. 
- Padding should be generous (24px) for content and compact (12px) for data-heavy stats.

### Input Fields
- Use a soft gray background (#F1F5F9) for the field with a 1px bottom border or subtle outline.
- Focus state: A 2px Indigo ring with 0% offset to highlight the active field clearly.
- Labels are always Geist Medium, 12px, placed above the field.

### Data Tables
- Use a "Zebra-stripe" layout with very low contrast (Slate-50 and White).
- Header row: Geist Bold, 12px, All-caps, Slate-500 text color.
- Row height: 48px (Standard) or 36px (Compact).

### Chips & Badges
- Used for course tags or status indicators.
- Lightly tinted backgrounds based on the semantic color (e.g., Success = Light Green background + Dark Green text).
- No borders; 12px Geist Medium text.

### Progress Indicators
- Linear, thin (4px) bars for course progress.
- Use the Primary Indigo for progress, and Slate-100 for the track.