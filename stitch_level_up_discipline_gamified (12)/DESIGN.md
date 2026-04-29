---
name: LEVEL UP
colors:
  surface: '#131318'
  surface-dim: '#131318'
  surface-bright: '#39383e'
  surface-container-lowest: '#0e0e13'
  surface-container-low: '#1b1b20'
  surface-container: '#1f1f25'
  surface-container-high: '#2a292f'
  surface-container-highest: '#35343a'
  on-surface: '#e4e1e9'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#e4e1e9'
  inverse-on-surface: '#303036'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#ffafd7'
  on-secondary: '#620044'
  secondary-container: '#ff3cbb'
  on-secondary-container: '#56003b'
  tertiary: '#fdf2ff'
  on-tertiary: '#4b007e'
  tertiary-container: '#ebcfff'
  on-tertiary-container: '#8d00e5'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#ffd8e9'
  secondary-fixed-dim: '#ffafd7'
  on-secondary-fixed: '#3c0029'
  on-secondary-fixed-variant: '#8a0062'
  tertiary-fixed: '#f1daff'
  tertiary-fixed-dim: '#dfb7ff'
  on-tertiary-fixed: '#2d004f'
  on-tertiary-fixed-variant: '#6b00b0'
  background: '#131318'
  on-background: '#e4e1e9'
  surface-variant: '#35343a'
typography:
  display-xl:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin: 40px
  container-max: 1440px
---

## Brand & Style

This design system is engineered to transform productivity into a high-stakes, high-reward gaming experience. It merges **Futuristic Glassmorphism** with a **Cyberpunk** edge to create a UI that feels like a premium pilot's HUD. The aesthetic is built on the contrast between a "Deep Void" background and searingly bright neon accents.

The target audience consists of high-performers who seek a "flow state" through visual stimulation. The mood is intentionally addictive and luxurious, utilizing light-refraction effects and vibrant color-coding to signal achievement and progress. Every interaction should feel like an upgrade in a high-fidelity tech simulation.

## Colors

The color palette is dominated by **Deep Void Black** to provide an infinite canvas for neon elements. **Neon Cyan** serves as the primary action color, representing system stability and "Level 1" interactions. **Neon Magenta** and **Electric Purple** are used for high-tier achievements and premium UI states.

**Neon Emerald Green** is strictly reserved for "Success" and "Task Complete" states, while **Neon Orange** signals high-priority alerts or "Overdrive" modes. All colors should be applied with an outer glow (bloom) to simulate physical light emission from the screen.

## Typography

This design system utilizes **Space Grotesk** across all levels to maintain a technical, geometric consistency. Headlines should be bold and aggressive, often paired with subtle neon drop-shadows to ensure legibility against complex glass backgrounds.

For secondary metadata and technical readouts, use the **label-caps** style to evoke the feeling of a machine interface. Text within glass containers should maintain a high contrast ratio; use pure white (#FFFFFF) for body text and primary color tints for headers to ensure focus in a high-performance environment.

## Layout & Spacing

The layout follows a **Rigid Technical Grid** model. Use a 12-column fluid grid for desktop views, but constrain the content to a 1440px max-width to maintain the "cockpit" feel. 

Spacing is based on an 8px base unit. Heavy margins (40px+) are used between major functional modules to prevent the glass surfaces from feeling cluttered. Elements should feel "docked" into the UI, using consistent gutters of 24px to separate data panels. Components within glass cards should use generous internal padding (32px) to let the backdrop blur effect breathe.

## Elevation & Depth

Depth is the core of this design system, achieved through **Heavy Glassmorphism**. UI levels are defined by the intensity of the backdrop blur and the thickness of the neon borders.

1.  **Base Layer:** Deep Void Black (#0A0A0F) with a subtle grain texture.
2.  **Standard Cards:** 15% opacity white fill, 40px backdrop blur, and a 1px solid border using a 40% opacity primary color.
3.  **Active/Floating Elements:** 20% opacity white fill, 60px backdrop blur, and a 2px neon border with a high-intensity outer glow (bloom).

Use "Mirror Reflections"—subtle linear gradients from top-left to bottom-right (White at 10% to Transparent)—to simulate the sheen of a physical glass screen.

## Shapes

The design system uses a **Soft Tech** shape language. While the world of "LEVEL UP" is futuristic, the slight rounding (0.25rem - 0.75rem) prevents the UI from feeling hostile or overly sharp, lending a "premium product" finish.

- **Small Components (Buttons, Inputs):** 0.25rem (4px) corner radius.
- **Medium Components (Cards, Modals):** 0.5rem (8px) corner radius.
- **Interactive Zones:** Use chamfered corners (clipped 45-degree angles) sparingly for specific "Global Action" buttons to lean into the gaming aesthetic.

## Components

### Buttons & Interaction
Buttons are high-gloss glass elements. The **Primary Button** uses a solid Neon Cyan fill with a 20px outer bloom. **Secondary Buttons** are ghost-style with a neon border and an inner glow that intensifies on hover. 

### Glass Cards
Every card must feature a 1px border. For premium data, use a "double-border" effect: a 1px solid neon stroke paired with a 2px semi-transparent white stroke offset by 1px to create a glass-edge refraction.

### HUD Inputs
Input fields should appear as recessed slots. Use a dark graphite background (#0F0F12) with a bottom-only neon border that "pulses" when the field is focused.

### Progress Meters
As a productivity game, progress bars are central. Use "Segmented" bars (similar to a battery indicator) where each segment glows individually. Use Neon Emerald Green for completed segments and Neon Orange for "Deadline Approaching" states.

### Additional Components
- **Achievement Toasts:** Floating glass cards with Magenta borders and center-aligned "Glitch" entrance animations.
- **XP Chips:** Small, pill-shaped labels with Electric Purple backgrounds and high-contrast white text.