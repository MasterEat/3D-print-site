---
name: Kinetic Industrial
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#b9cbb9'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#849585'
  outline-variant: '#3b4b3d'
  surface-tint: '#00e479'
  primary: '#f1ffef'
  on-primary: '#003919'
  primary-container: '#00ff88'
  on-primary-container: '#007139'
  inverse-primary: '#006d37'
  secondary: '#c8c6c5'
  on-secondary: '#303030'
  secondary-container: '#474746'
  on-secondary-container: '#b6b5b4'
  tertiary: '#fefafa'
  on-tertiary: '#313030'
  tertiary-container: '#e1dedd'
  on-tertiary-container: '#636261'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#60ff99'
  primary-fixed-dim: '#00e479'
  on-primary-fixed: '#00210c'
  on-primary-fixed-variant: '#005228'
  secondary-fixed: '#e4e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  h1:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h3:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0em
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
  mono-data:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: 0.02em
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin: 32px
---

## Brand & Style

The design system is engineered to evoke the precision and raw power of high-end additive manufacturing. It targets a professional demographic that values both technical capability and premium aesthetics. The brand personality is "Industrial Futurist"—clean, disciplined, and technologically advanced.

The visual style is a hybrid of **Minimalism** and **Tactile High-Contrast**. It utilizes heavy dark matte surfaces to create a sense of physical density, contrasted by precise neon accents that simulate laser-cutting paths or active digital readouts. The emotional response should be one of reliability and "pro-sumer" luxury, moving away from generic tech aesthetics toward something that feels like a physical piece of laboratory equipment.

## Colors

The palette is strictly anchored in deep blacks and tactical grays to allow the primary neon green to function as a beacon for interaction and status. 

- **Primary Background (#0F0F0F):** Used for the core canvas of the application, providing a matte, non-reflective feel.
- **Secondary Background (#181818):** Used for structural sections, sidebars, and modular blocks to create subtle depth without relying on shadows.
- **Accent Background (#2A2A2A):** Used for interactive surfaces like input fields and inactive button states.
- **Primary Accent (#00FF88):** Reserved for high-priority actions, active states, and "printing" indicators. It should be paired with a subtle outer glow (0px 0px 12px) to simulate light emission.
- **Text (#F5F5F5):** High-contrast off-white to ensure maximum readability against dark backgrounds while avoiding the harshness of pure white.

## Typography

The typography strategy leverages **Space Grotesk** for its technical, geometric architecture in headings and functional labels. This font's unique apertures give the design system an innovative, cutting-edge edge. 

For long-form data and body text, **Inter** is utilized for its supreme legibility and neutral character, ensuring that the interface remains functional during complex 3D printing workflows. Use the `label-caps` style for all metadata and small headers to maintain an industrial, schematic-like appearance.

## Layout & Spacing

This design system employs a **fixed-fluid hybrid grid**. The main workspace uses a 12-column grid with 24px gutters, but internal dashboard modules use a strict 8px square rhythm to align industrial elements precisely.

Layouts should favor ample "negative space" to prevent the dark UI from feeling claustrophobic. Margins are generous (32px+) to frame the high-tech content as premium. Elements should be grouped into distinct containers with clear gutters, avoiding overlapping elements to maintain a clean, architectural structure.

## Elevation & Depth

In this design system, depth is achieved through **Tonal Layering** and **Subtle Glows** rather than traditional shadows. 

1.  **Base:** The lowest level is the #0F0F0F matte background.
2.  **Raised:** Secondary sections use #181818. These should not have shadows but rather 1px solid borders in #2A2A2A.
3.  **Active/Hover:** Active elements or focused cards utilize a 1px border of #00FF88 with a very soft, diffused outer glow (0px 0px 15px 0px) of the same color at 20% opacity.
4.  **Glass Insets:** For modal overlays or temporary panels, a slight backdrop blur (10px) with #181818 at 80% opacity is used to maintain context of the underlying industrial data.

## Shapes

The shape language is strictly **Sharp (0px)**. To reinforce the industrial nature of 3D printing—where precision and hard edges are paramount—all buttons, cards, and input fields must have square corners. 

A "chamfered" corner effect (a 45-degree cut) may be used on primary action buttons or decorative elements to further the technical aesthetic, but standard rounding is prohibited. This creates a rigorous, machine-like interface.

## Components

- **Buttons:** 
    - *Primary:* Solid #00FF88 background with #0F0F0F text. High-density padding. No border.
    - *Secondary:* Transparent background with 1px border in #00FF88 and neon text.
    - *Ghost:* Solid #2A2A2A background with #F5F5F5 text.
- **Cards:** Use #181818 background with a 1px #2A2A2A border. On hover, the border transitions to #00FF88 with a subtle bloom effect.
- **Inputs:** Dark #2A2A2A background with a bottom-only 2px border in #F5F5F5. When focused, the bottom border turns #00FF88.
- **Chips/Status Tags:** Small, rectangular tags. Active status uses #00FF88 text with a 10% opacity green fill.
- **Data Visualizations:** Use thin 1px lines for charts. The primary data path should always be #00FF88 with a glow, while grid lines remain #2A2A2A.
- **Progress Bars:** Representing the 3D print progress, these should be thin (4px) with a glowing #00FF88 leading edge that leaves a faint trail.