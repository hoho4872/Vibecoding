---
name: Heritage Grand Touring
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#404942'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#717971'
  outline-variant: '#c0c9c0'
  surface-tint: '#316948'
  primary: '#002a15'
  on-primary: '#ffffff'
  primary-container: '#004225'
  on-primary-container: '#75af89'
  inverse-primary: '#98d4ac'
  secondary: '#5e5f56'
  on-secondary: '#ffffff'
  secondary-container: '#e4e3d7'
  on-secondary-container: '#64655c'
  tertiary: '#202327'
  on-tertiary: '#ffffff'
  tertiary-container: '#35393d'
  on-tertiary-container: '#9fa2a7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b4f0c7'
  primary-fixed-dim: '#98d4ac'
  on-primary-fixed: '#002110'
  on-primary-fixed-variant: '#165132'
  secondary-fixed: '#e4e3d7'
  secondary-fixed-dim: '#c7c7bc'
  on-secondary-fixed: '#1b1c15'
  on-secondary-fixed-variant: '#46473f'
  tertiary-fixed: '#e0e2e8'
  tertiary-fixed-dim: '#c4c6cc'
  on-tertiary-fixed: '#181c20'
  on-tertiary-fixed-variant: '#44474b'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Source Sans 3
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: Source Sans 3
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Source Sans 3
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  section-gap-desktop: 120px
  section-gap-mobile: 64px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
---

## Brand & Style
This design system embodies the era of gentleman drivers and grand touring. The brand personality is rooted in **Classic Sophistication**, targeting a discerning clientele that values heritage, mechanical artistry, and the romance of the open road. 

The visual style blends **Minimalism** with **Tactile** accents. It prioritizes heavy whitespace and structured editorial layouts to evoke a premium, "concierge" feel. While the interface is digitally fluent, it borrows physical cues from vintage automotive cockpits—polished metals, fine leather grains, and high-quality enamel finishes—to create a nostalgic yet high-performance user experience.

## Colors
The palette is a tribute to historic motoring excellence.
- **British Racing Green (Primary):** A deep, saturated green used for primary actions, branding, and hero elements. It signifies prestige and depth.
- **Antique Ivory (Secondary/Background):** A warm, off-white surface color that replaces harsh pure whites, providing a paper-like, editorial quality.
- **Polished Chrome (Tertiary):** A metallic silver-grey used for accents, borders, and decorative dividers, mimicking car trim.
- **Obsidian (Neutral):** A soft, rich black used for high-contrast typography and deep structural elements.

## Typography
The typographic scale emphasizes contrast between the expressive, high-contrast serifs of the headings and the functional, understated sans-serif of the body. 

**Headlines** utilize Playfair Display to convey elegance and authority. Large display sizes should use tighter letter spacing to maintain a cohesive visual block. **Body text** uses Source Sans 3 for maximum legibility at all sizes, ensuring the technical details of the vintage fleet are easily digestible. **Labels** should frequently use the "label-caps" style to mimic stamped metal plates or dashboard gauges.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop to maintain an editorial, magazine-like feel. 
- **Desktop:** 12-column grid with an 1140px max-width container. 
- **Spacing Philosophy:** Embrace "Airy Sophistication." Use generous vertical padding (section-gap) to allow images of cars to breathe. 
- **Asymmetry:** Occasionally break the grid with offset images or floating text blocks to create a dynamic, curated aesthetic rather than a rigid template.

## Elevation & Depth
Elevation in this design system is subtle and intentional, mimicking the way light hits polished surfaces.
- **Tonal Layers:** Deep Racing Green containers should be used as "feature" blocks against the Ivory background.
- **Ambient Shadows:** Use extremely soft, large-radius shadows with a hint of the primary color in the tint (e.g., a dark green-tinted shadow). Shadows should feel like the object is resting on a surface, not floating high above it.
- **Inner Glows:** Apply a 1px subtle inner highlight to buttons and cards to simulate the beveled edge of a chrome dial or leather-wrapped panel.

## Shapes
The shape language is **Soft** and restrained. While sharp corners feel too aggressive and pill-shaped corners feel too modern, a 0.25rem (4px) base radius provides a sense of craftsmanship and hand-finished quality. This subtle rounding should be applied to car gallery cards, input fields, and primary buttons.

## Components
- **Buttons:** Primary buttons are solid Deep Racing Green with Ivory text. Secondary buttons use a Polished Chrome outline. All buttons should have a slight transition on hover that increases the inner highlight.
- **Cards:** Vehicle cards feature a full-bleed image with a thin Chrome-colored border and an Ivory content area below.
- **Inputs:** Search and booking fields should use Ivory backgrounds with a thin 1px border in a muted neutral. Use the "label-caps" typography for field headers.
- **Chips:** Status indicators (e.g., "Available", "Reserved") should use a subtle enamel-like finish—low-contrast background with a high-gloss edge.
- **Dividers:** Use thin, 1px horizontal lines in Polished Chrome to separate content sections, occasionally punctuated with a small decorative diamond or brand mark in the center.