---
name: PinPoint Lab
colors:
  surface: '#061423'
  surface-dim: '#061423'
  surface-bright: '#2d3a4a'
  surface-container-lowest: '#020f1e'
  surface-container-low: '#0f1c2c'
  surface-container: '#132030'
  surface-container-high: '#1e2b3b'
  surface-container-highest: '#283646'
  on-surface: '#d6e4f9'
  on-surface-variant: '#bcc9cd'
  inverse-surface: '#d6e4f9'
  inverse-on-surface: '#243141'
  outline: '#869397'
  outline-variant: '#3d494c'
  surface-tint: '#4cd7f6'
  primary: '#4cd7f6'
  on-primary: '#003640'
  primary-container: '#06b6d4'
  on-primary-container: '#00424f'
  inverse-primary: '#00687a'
  secondary: '#adc6ff'
  on-secondary: '#002e6a'
  secondary-container: '#0566d9'
  on-secondary-container: '#e6ecff'
  tertiary: '#ffb95f'
  on-tertiary: '#472a00'
  tertiary-container: '#e79400'
  on-tertiary-container: '#563400'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#acedff'
  primary-fixed-dim: '#4cd7f6'
  on-primary-fixed: '#001f26'
  on-primary-fixed-variant: '#004e5c'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#061423'
  on-background: '#d6e4f9'
  surface-variant: '#283646'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  code-lg:
    fontFamily: JetBrains Mono
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
  code-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
  label-pin:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style

The design system establishes a high-precision, utilitarian aesthetic tuned for workbench electronics diagnostics, embedded systems prototyping, and mechatronics lab instruction. Tailored for undergraduate engineers, lab researchers, and bench technicians working beneath harsh task lamps or low-ambient oscilloscope zones, the interface communicates structural reliability, surgical accuracy, and rapid scan-readiness.

The aesthetic fuses **Modern Technical Functionalism** with **Instrumentation Precision**:
- High-density information layouts prioritized over decorative whitespace.
- Crisp, legible contrasts engineered to eliminate misread pin mappings, flipped polarities, or burnt ICs.
- Tactile, mechanical feedback cues evoking physical DIP/QFP packages, test leads, and breadboard rails.
- Structural grounding: surfaces mirror treated matte anodized aluminum chassis, anti-static workmats, and silkscreen PCB legends.

## Colors

The system uses a native dark mode canvas engineered for screen glare reduction around bench oscilloscopes, power supplies, and soldering stations. The palette directly maps to standard electronics hardware semantics:

- **Primary (`#06B6D4` - Electric Cyan):** Active states, selected pins, live logic traces, and active multimeter mode indications.
- **Secondary (`#3B82F6` - Signal Blue):** Information links, secondary logic channels, and protocol bus grouping (I2C, SPI, UART).
- **Tertiary (`#F59E0B` - Volt Amber):** Threshold alerts, floating inputs, warning conditions, and intermediate voltage values.
- **Neutral Core (`#0D1B2A` - Bench Deep Indigo):** Canvas background, paired with `#1E293B` (Chassis Slate) for structural cards and `#334155` (GND/Muted Slate) for inactive hardware traces and unassigned pins.

### Functional Electronics Palette
- **VCC / Power (`#EF4444`):** Positive voltage lines, thermal overshoots, reverse polarity risks.
- **GND / Reference (`#334155` / `#64748B`):** 0V reference, ground rails, grounded shielding.
- **Logic High / Pass (`#10B981`):** Active HIGH pulses, successful continuity verification, nominal telemetry.
- **High-Z / Inactive (`#475569`):** High impedance states, tri-state outputs, disconnected jumpers.

## Typography

Typography enforces strict cognitive separation between descriptive guidance, electrical metrics, and physical package diagrams:

- **Headlines (`Space Grotesk`):** Delivers clean, geometric, engineering-forward structure for module titles, datasheet headers, and tool modes.
- **Body Text (`Inter`):** Neutral, hyper-legible sans-serif for instructions, formula derivations, and step-by-step procedures.
- **Hardware & Telemetry (`JetBrains Mono`):** Applied to all physical pin numbers, register maps, electrical units (`kΩ`, `µF`, `mV`), hex addresses, and baud rates. Tabular figures must remain enabled across the mono family to ensure instantaneous vertical alignment of data readouts.

## Layout & Spacing

The layout is built upon a high-density, modular grid modeled after hardware rack units and prototyping breadboards (2.54mm pitch equivalent scaling):

- **Grid Strategy:** 12-column responsive fluid grid on tablet and desktop interfaces; 4-column high-density layout on mobile handhelds.
- **Touch Target Exceptions:** While dense visually, pin taps and jumper endpoints must maintain an invisible 44×44px interactive bounding box for reliable thumb operation while one hand holds a probe lead.
- **Breakpoints:**
  - `Mobile` (<640px): Single-column tool views, horizontal scrolling breadboard rails, sticky bottom telemetry bars.
  - `Tablet / Bench Mount` (640px - 1024px): Split-pane viewer (Left: Interactive IC pinout, Right: Formula scratchpad/readouts).
  - `Desktop / Workstation` (>1024px): 3-column workspace with concurrent logic tree, package schematics, and live register monitors.

## Elevation & Depth

To maintain high contrast and avoid "muddy" edges in harsh workbench light, depth is communicated through **structural tonal layering** combined with **subtle, high-precision ghost borders** rather than diffused drop shadows:

- **Base Canvas (Level 0):** `#0D1B2A` flat background.
- **Card & Silkscreen Surfaces (Level 1):** `#1E293B` with a 1px border of `#334155`.
- **Floating Overlays & Dialogs (Level 2):** `#1E293B` elevated with an interior hairline highlight (`rgba(255, 255, 255, 0.08)`), surrounded by a crisp `0 8px 24px rgba(0, 0, 0, 0.6)` ambient occlusion.
- **Active Pin / Trace Illumination:** Instead of blurred shadows, active pins and signal connections use solid electrical borders paired with a razor-thin 2px edge glow using `rgba(6, 182, 212, 0.35)` to simulate LED diagnostic diodes.

## Shapes

The design system uses deliberate, low-radius geometric forms (`roundedness: 1` / `0.25rem` / `4px`) reflecting dual-in-line packaging, surface-mount component profiles, and laboratory equipment bezels:

- **Base Inputs & Buttons:** 4px border radius. Keeps interfaces mechanical, precise, and space-efficient.
- **IC Packages & Breadboards:** Rounded 4px corners on package bodies with physical 1px rectangular lead notches.
- **Status Pills & Chips:** 4px radius with strict 1px framing borders. Pill-shaped circular ends are forbidden except for ground/terminal circular lugs.

## Components

### 1. Interactive IC Pinout Blocks
- **Structure:** Dual-in-line (DIP) or quad-flat (QFP) chip representation with numbered metallic contact leads flanking a central dark core (`#0B1320`).
- **Pins:** Each pin displays its index (`JetBrains Mono`, 11px) and signal acronym (e.g., `SDA`, `MOSI`, `TX`, `GND`).
- **Color Coding:** Left-border indicator on the pin badge using functional electrical colors (Red = VCC, Charcoal = GND, Amber = Analog, Cyan = Digital/PWM).
- **Interactions:** Tapping a pin highlights all internally bridged pins and highlights associated schematic notes in the adjacent panel.

### 2. Buttons & Bench Controls
- **Primary:** High-contrast electric cyan fill (`#06B6D4`), solid black bold label, 4px corner radius.
- **Secondary:** Transparent fill, 1px border in `#334155`, text in `#E2E8F0`. Hover/Active: Background shifts to `#1E293B` with `#06B6D4` border.
- **Hazard / Burn Risk Actions:** Crimson fill (`#EF4444`), white mono label, reserved for reverse polarity warnings or external power overrides.

### 3. Quick Calculation Cards (Resistors, Filters, Regulators)
- **Header:** Metric formula overview in monospace notation.
- **Input Fields:** Stepped unit counters with native multiplier tags (`p`, `n`, `µ`, `m`, `k`, `M`) eliminating decimal ambiguity.
- **Step-by-Step Color Bands:** Graphical standard 4-band and 5-band interactive resistor displays directly displaying official EIA color values alongside exact nominal and tolerance ranges.

### 4. Safety Callouts & Caution Badges
- **Severity Levels:** `INFO` (Signal Blue), `CAUTION` (Volt Amber), `CRITICAL/OVERLOAD` (VCC Red).
- **Visuals:** 1px solid border matching the severity color, a 10% opacity tint background, a monospace severity tag in bold uppercase, and a clean sans-serif explanation detailing the component max rating (e.g., `MAX 3.3V TOLERANT — DO NOT APPLY 5V VBUS`).

### 5. Selection Chips & Filter Traces
- **Default:** Inactive pins or filter channels rest at `#1E293B` background with `#475569` text.
- **Selected:** Border in `#06B6D4`, text in `#FFFFFF`, with a 6px circular dot indicator glowing in cyan or logic green.

### 6. Breadboard Coordinate Matrix
- **Grid Nodes:** Small tie-points styled as inset circles with subtle inner shading.
- **Rail Legend:** Red (+) and Blue (-) silkscreen lines running parallel with clear polarity markers positioned every 5 grid units.