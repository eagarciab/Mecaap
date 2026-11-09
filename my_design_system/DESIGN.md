---
name: My Design System
colors:
  surface: '#fff8ef'
  surface-dim: '#e0d9cd'
  surface-bright: '#fff8ef'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#faf3e6'
  surface-container: '#f4ede1'
  surface-container-high: '#eee7db'
  surface-container-highest: '#e9e2d5'
  on-surface: '#1e1b14'
  on-surface-variant: '#4c4636'
  inverse-surface: '#333028'
  inverse-on-surface: '#f7f0e3'
  outline: '#7d7764'
  outline-variant: '#cec6b1'
  surface-tint: '#705d00'
  primary: '#705d00'
  on-primary: '#ffffff'
  primary-container: '#f9db6c'
  on-primary-container: '#735f00'
  inverse-primary: '#e2c559'
  secondary: '#6a5e38'
  on-secondary: '#ffffff'
  secondary-container: '#f3e1b1'
  on-secondary-container: '#70643d'
  tertiary: '#006c4a'
  on-tertiary: '#ffffff'
  tertiary-container: '#41f9b4'
  on-tertiary-container: '#006f4c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe173'
  primary-fixed-dim: '#e2c559'
  on-primary-fixed: '#221b00'
  on-primary-fixed-variant: '#554600'
  secondary-fixed: '#f3e1b1'
  secondary-fixed-dim: '#d6c697'
  on-secondary-fixed: '#231b00'
  on-secondary-fixed-variant: '#514622'
  tertiary-fixed: '#4affb9'
  tertiary-fixed-dim: '#0ce29e'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005237'
  background: '#fff8ef'
  on-background: '#1e1b14'
  surface-variant: '#e9e2d5'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

# Design System

## Brand & Style
The design system adopts a modern, clean, and accessible style utilizing the **Inter** typography family and a vibrant, warm color palette rooted in a sunny yellow seed color (`#f6c325`). The aesthetic is balanced and professional ("fidelity" color variant), leaning into friendly yet robust UI elements with a roundedness level of 2, offering soft, approachable corners across components.

## Colors
The color palette is built around a bright primary yellow (`#f9db6c`) that anchors actions and primary focal points, supported by a muted secondary tone (`#b5a67a`) for secondary elements, and a high-vibrancy mint tertiary accent (`#4affb9`) for dynamic callouts and highlights. The default color mode is light, ensuring high legibility and an open, airy feel.

## Typography
**Inter** is used exclusively across all text roles—headlines, body, and labels—providing a neutral, highly readable geometric sans-serif aesthetic. Typography scales cleanly from dense mobile layouts up to expansive desktop screens, maintaining strict hierarchy.

## Layout & Spacing
A balanced spacing scale based on a 2x factor ensures harmonious layouts. A standard 16px (`1rem`) gutter and 24px (`1.5rem`) outer margin structure fluid grid layouts that easily adapt across mobile, tablet, and desktop viewports.

## Elevation & Depth
Visual hierarchy is maintained through tonal surface layering and soft, diffused ambient shadows. Low-contrast outlines are used alongside subtle depth to separate interactive surfaces without feeling heavy or aggressive.

## Shapes
The shape language relies on a roundedness level of `2`. Standard UI elements feature a friendly 0.5rem corner radius, while larger containers (`rounded-lg`, `rounded-xl`) scale up to 1rem and 1.5rem respectively, keeping the interface approachable and modern.

## Components
Components leverage the primary yellow (`#f9db6c`) for key interactive states, rounded corners (`roundedness: 2`), and clean **Inter** typography. Buttons, chips, input fields, and cards maintain consistent padding using the defined spacing scale.