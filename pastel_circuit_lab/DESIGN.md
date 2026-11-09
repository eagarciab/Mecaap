---
name: Pastel Circuit Lab
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
  on-surface-variant: '#3d4a3e'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#6d7b6d'
  outline-variant: '#bccabb'
  surface-tint: '#006d36'
  primary: '#006d36'
  on-primary: '#ffffff'
  primary-container: '#4ade80'
  on-primary-container: '#005e2d'
  inverse-primary: '#4de082'
  secondary: '#4953bc'
  on-secondary: '#ffffff'
  secondary-container: '#8792fe'
  on-secondary-container: '#17228f'
  tertiary: '#00668a'
  on-tertiary: '#ffffff'
  tertiary-container: '#73ceff'
  on-tertiary-container: '#005777'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#6dfe9c'
  primary-fixed-dim: '#4de082'
  on-primary-fixed: '#00210c'
  on-primary-fixed-variant: '#005227'
  secondary-fixed: '#e0e0ff'
  secondary-fixed-dim: '#bdc2ff'
  on-secondary-fixed: '#000767'
  on-secondary-fixed-variant: '#2f3aa3'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.005em
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system establishes a welcoming, exploratory, and technically precise environment tailored for engineering and computer science students. The atmosphere balances the rigor of physical hardware design—breadboards, microcontrollers, signal generators, and circuit traces—with an approachable, soft pastel aesthetic that removes intimidation from technical education.

The visual direction merges **Clean Technical Minimalism** with **Soft Modern Tactility**:
- Crisp, clinical structure: Systematic layouts, modular breadboard-inspired card grids, and high-legibility telemetry readouts.
- Gentle warmth: Soft mint, periwinkle, sky blue, and pastel rose tones that code logic states, signal groups, and component libraries without triggering visual fatigue during long lab sessions.
- Student confidence: The interface favors clarity over dense industrial skepticism, offering tangible feedback, friendly curves, and calm visual rhythm.

## Colors

The palette uses calibrated pastel tones paired with functional contrast anchors:

- **Primary (Mint / Logic High)**: Base `#4ade80` with soft surface tint `#86efac` and deep functional tone `#15803d`. Used for operational success, running simulations, active probes, and primary interactive buttons.
- **Secondary (Periwinkle / Clock & Signals)**: Base `#818cf8` with tinted tint `#c7d2fe` and deep accent `#4338ca`. Encodes clock pins, frequency analysis, buses, and secondary controls.
- **Tertiary (Sky / Power & Telemetry)**: Base `#38bdf8` with wash `#bae6fd` and deep text `#0369a1`. Designated for VCC rails, oscilloscope traces, documentation tags, and ambient highlights.
- **Accent Rose (Alarm / Anomaly / VSS)**: Base `#fb7185` with soft tint `#fecdd3` and deep alert `#be123c`. Assigned to ground faults, cut traces, threshold warnings, and critical breakpoints.
- **Neutrals & Canvases**:
  - Global Canvas: `#f8fafc`
  - Sub-Canvas & Wells: `#f1f5f9`
  - Component Surface: `#ffffff`
  - Structural Borders: `#e2e8f0` (subtle inner separators `#f1f5f9`)
  - Typography: Primary Slate `#0f172a`, Secondary Body `#334155`, Muted Metadata `#64748b`

## Typography

The design system exclusively utilizes **Space Grotesk** across headlines, running text, technical readouts, and UI controls. Its distinct geometric cuts, rounded loops, and engineered rhythm mirror printed circuit schematics and modular hardware packaging, avoiding cold clinical dryness.

- **Headlines**: Set tightly with negative tracking to assert structural clarity in lab bench viewports and instrument dashboards.
- **Body Text**: Spaced for extended reading in experiment guides and pinout specification tables, retaining clarity against `#f8fafc` backdrops.
- **Labels & Values**: Leveraged for pin numbers, Ohm/Volt/Amp designations, oscillograph channel names, and toggle statuses. Numeric tabular figures should be enforced via font-feature settings (`tnum`) for live voltage and frequency streams.

## Layout & Spacing

The layout model is anchored on an **8-point modular grid** structured around breadboard logic and modular lab benches.

- **Grid System**: 
  - **Desktop (1024px+)**: 12-column layout with 24px (`1.5rem`) gutters and 32px (`2rem`) outer margins. Supports side-by-side breadboard schematics, waveform inspectors, and component rails.
  - **Tablet (768px - 1023px)**: 8-column layout with 16px (`1rem`) gutters and 24px (`1.5rem`) outer margins. Inspector panels collapse into lower drawers.
  - **Mobile (<768px)**: 4-column layout with 12px (`0.75rem`) gutters and 16px (`1rem`) outer margins. Modular instruments stack vertically.

- **Rhythm Rules**:
  - `space-xs` (4px) & `space-sm` (8px): Micro spacing between pin indicators, icon-label locks, and segmented chip arrays.
  - `space-md` (16px): Standard padding inside cards, table rows, and input field bodies.
  - `space-lg` (24px): Separation between component blocks and control toolbars.
  - `space-xl` (32px): Primary section division on the canvas.

## Elevation & Depth

Visual hierarchy employs a **soft ambient layer system** combining crisp structural hairlines with diffused pastel shadows. Surfaces feel physical, calm, and elevated like modular resin instrument bays.

1. **Flat Canvas (`#f8fafc`)**: Base plane with an optional 16px dot-matrix grid (`#cbd5e1`, 30% opacity) evoking physical prototyping boards.
2. **Surface Level 1 (Cards, Modules, Workbenches)**: 
   - Background: Pure White (`#ffffff`)
   - Border: 1px solid `#e2e8f0`
   - Shadow: `0 4px 12px -2px rgba(15, 23, 42, 0.04), 0 2px 6px -1px rgba(15, 23, 42, 0.02)`
3. **Surface Level 2 (Hover States, Floating Toolbars, Active Probes)**: 
   - Background: `#ffffff`
   - Border: 1px solid `#cbd5e1`
   - Shadow: `0 10px 24px -4px rgba(15, 23, 42, 0.07), 0 4px 10px -2px rgba(15, 23, 42, 0.03)`
4. **Surface Level 3 (Modals, Component Palettes, Oscilloscope Overlays)**:
   - Background: `#ffffff`
   - Border: 1px solid `#cbd5e1`
   - Shadow: `0 20px 35px -8px rgba(15, 23, 42, 0.1), 0 8px 16px -4px rgba(15, 23, 42, 0.04)`
5. **Interactive Glows (Tonal Emissives)**:
   - Mint Active: Box shadow `0 0 0 3px rgba(74, 222, 128, 0.25)`
   - Periwinkle Focus: Box shadow `0 0 0 3px rgba(129, 140, 248, 0.3)`
   - Rose Triggered: Box shadow `0 0 0 3px rgba(251, 113, 133, 0.3)`

## Shapes

The interface embraces a balanced, friendly geometric radius (Level `2`):

- **Default Component Radius (0.5rem / 8px)**: Applied to input elements, toolbars, buttons, notification banners, and status chips.
- **Large Container Radius (1rem / 16px)**: Applied to cards, instrument panels, waveform displays, and oscilloscope views.
- **Extra Large Radius (1.5rem / 24px)**: Applied to modal dialogs, drawer panels, and slide-in lab tutorial guides.
- **Full Pill (`9999px`)**: Reserved for connection terminal nodes, live signal frequency badges, toggle track pills, and breadboard pin indicators.

## Components

### Buttons
- **Primary Action (Run Simulation / Flash Code)**: Background `#4ade80`, text `#0f172a`, font weight `600`, border `1px solid #22c55e`. Hover: `#86efac` with subtle scale transition (0.99 active press).
- **Secondary Action (Signal Toggle / Step Logic)**: Background `#c7d2fe`, text `#1e1b4b`, border `1px solid #818cf8`. Hover: `#818cf8` with text `#ffffff`.
- **Tertiary / Ghost (Reset / Clear Bus)**: Background `#ffffff`, text `#334155`, border `1px solid #e2e8f0`. Hover: `#f1f5f9`.
- **Danger (Cut Power / Short Circuit Warning)**: Background `#fecdd3`, text `#881337`, border `1px solid #fb7185`.

### Chips & Badges
- Constructed with pill shapes (`9999px`), 6px horizontal padding, and `label-sm` typography.
- Status variants leverage tinted pastel backgrounds with solid high-contrast text:
  - *Active / HIGH*: `#dcfce7` background, `#15803d` label, 6px `#22c55e` bullet dot.
  - *Clock / Bus*: `#e0e7ff` background, `#3730a3` label, 6px `#6366f1` bullet dot.
  - *Analog / Power*: `#e0f2fe` background, `#0369a1` label, 6px `#0284c7` bullet dot.
  - *Fault / LOW*: `#ffe4e6` background, `#9f1239` label, 6px `#e11d48` bullet dot.

### Cards & Modular Enclosures
- Enclosed with `#ffffff` fill, `1rem` corner radius, `1px solid #e2e8f0`, and ambient drop shadow.
- Feature header bands separated by a delicate `1px solid #f1f5f9` rule with integrated instrument icons and pin state chips.
- Interactive terminal cards shift border to `#818cf8` on hover.

### Inputs & Sliders
- **Text Inputs**: Height 40px, rounded to `0.5rem`, filled with `#ffffff`, bordered by `1px solid #cbd5e1`. Focus creates a periwinkle ring (`0 0 0 3px rgba(129, 140, 248, 0.25)` and border `#818cf8`).
- **Hardware Sliders (Resistance / Voltage)**: Track height 6px, track background `#e2e8f0` with active fill `#38bdf8`. Thumb is a 20px circle in `#ffffff` with a `2px solid #0284c7` ring and subtle shadow.

### Checkboxes & Radios
- Checkboxes feature a `6px` radius; Radios are circular.
- Unchecked: `#ffffff` background with `2px solid #cbd5e1`.
- Checked: `#4ade80` background with a crisp `#0f172a` checkmark or center pip. Focus utilizes the mint glow.

### Lists & Telemetry Tables
- Striped alternating row backgrounds with `#ffffff` and `#f8fafc`.
- Row height: 44px with `space-md` horizontal cell padding.
- Values rendered in `Space Grotesk` with tabular figures for real-time oscilloscope samples and voltage reads.

### Hardware-Specific Components
- **Pin Terminal Blocks**: Discrete square/pill connection points (`#f1f5f9` with `#cbd5e1` ring) that turn pastel sky blue (`#38bdf8`) on wire snap.
- **Waveform Canvas Frame**: Recessed `#0f172a` viewport with `#38bdf8` trace lines and `#4ade80` trigger points, softened by a rounded `1rem` outer bezel.