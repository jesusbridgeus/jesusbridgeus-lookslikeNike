---
name: Apostolic Editorial
colors:
  surface: '#fef9ef'
  surface-dim: '#ded9d1'
  surface-bright: '#fef9ef'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f3ea'
  surface-container: '#f2ede4'
  surface-container-high: '#ede8df'
  surface-container-highest: '#e7e2d9'
  on-surface: '#1d1c16'
  on-surface-variant: '#4c4546'
  inverse-surface: '#32302a'
  inverse-on-surface: '#f5f0e7'
  outline: '#7e7576'
  outline-variant: '#cfc4c5'
  surface-tint: '#5e5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1b'
  on-primary-container: '#848484'
  inverse-primary: '#c6c6c6'
  secondary: '#755a28'
  on-secondary: '#ffffff'
  secondary-container: '#fdd79a'
  on-secondary-container: '#785c2a'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b1b1b'
  on-tertiary-container: '#848484'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#ffdeaa'
  secondary-fixed-dim: '#e6c185'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5b4313'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1b1b1b'
  on-tertiary-fixed-variant: '#474747'
  background: '#fef9ef'
  on-background: '#1d1c16'
  surface-variant: '#e7e2d9'
  deep-canvas: '#0D0D0D'
  paper-white: '#F9F8F6'
  divine-gold: '#C5A36A'
typography:
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 84px
    fontWeight: '700'
    lineHeight: 90px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
  nav-link:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
spacing:
  margin-desktop: 64px
  margin-mobile: 20px
  gutter: 24px
  stack-sm: 8px
  stack-md: 24px
  stack-lg: 80px
---

## Brand & Style

This design system is built for a non-profit that bridges faith with high-end modern culture. The brand personality is authoritative yet welcoming, sophisticated, and deeply intentional. 

The aesthetic follows a **Modern Editorial** movement. It utilizes high-contrast visual storytelling, expansive whitespace, and a rigorous grid system. By blending the raw, bold energy of premium streetwear commerce with the dignified pacing of a literary journal, the UI evokes a sense of "sacred modernism"—clean, high-end, and profoundly focused on the message.

## Colors

The palette is rooted in a "Paper and Ink" philosophy. The primary interaction color is a deep, absolute black, providing a grounded foundation for the brand's message.

- **Primary (Black):** Used for primary typography, icons, and high-impact structural elements.
- **Secondary (Divine Gold):** A warm, muted gold used sparingly for calls to action, highlights, and moments of spiritual significance.
- **Neutral (Paper):** A soft, off-white (`#ECE7DE`) serves as the secondary background to reduce eye strain and add a tactile, high-end parchment feel.
- **Background:** The main canvas is a crisp `paper-white` to maintain maximum contrast and clarity for photography.

## Typography

The typographic strategy relies on the tension between the classic, high-contrast Serif (**Bodoni Moda**) and the utilitarian, systematic Sans-Serif (**Inter**).

- **Headlines:** Use Bodoni Moda for all editorial headings. It should be used at large scales with tight tracking to emphasize the high-end editorial aesthetic.
- **Body & Navigation:** Use Inter for all functional text. This provides "Nike-like" clarity—efficient, readable, and modern. 
- **Scale:** On mobile, display sizes must scale aggressively to maintain a single-column impact without breaking word wraps.

## Layout & Spacing

The design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. 

- **Storytelling Layouts:** Use asymmetrical column spans (e.g., an image spanning 7 columns and text spanning 4) to create an editorial feel.
- **Vertical Rhythm:** Large vertical gaps (`stack-lg`) are used between major sections to allow the content to "breathe," mimicking the layout of a premium physical magazine.
- **Safe Zones:** Content should be contained within wide margins to ensure that imagery feels framed rather than edge-to-edge, enhancing the gallery-like experience.

## Elevation & Depth

This system avoids traditional drop shadows in favor of **Tonal Layering** and **Flat Structuralism**.

- **Depth:** Created through the use of overlapping elements and varying background shades (e.g., a `paper-white` card on an `ECE7DE` background).
- **Outlines:** Use ultra-fine (1px) borders in high-contrast black or soft neutral tones to define sections without adding "weight."
- **Imagery:** High-quality photography provides the "third dimension." Parallax effects on background images are encouraged to create a sense of depth during scroll.

## Shapes

To maintain a sophisticated and architectural feel, this design system uses **Sharp (0px)** corners for all primary UI elements including buttons, input fields, and image containers. 

The absence of rounding communicates precision, authority, and a modern edge. Softness is introduced through the color palette and typography rather than the geometry of the interface.

## Components

- **Buttons:** Primary buttons are solid black rectangles with white `label-caps` typography. Secondary buttons use a 1px black border with no fill.
- **Inputs:** Minimalist bottom-border-only fields with floating labels in `Inter`. Error states are indicated by a subtle shift to a deep red or the `secondary-gold`.
- **Cards:** Borderless containers. Depth is signaled by subtle background color shifts or high-contrast image-to-text ratios.
- **Editorial Chips:** Small, rectangular tags using `label-caps` and a light neutral background to categorize content or products.
- **Navigation:** Top-tier navigation uses `nav-link` styling. The active state is indicated by a simple 1px underline rather than a color change.
- **Product Tiles:** Focus on large-scale imagery with minimal text overlays. Prices and titles should use `body-md` in Inter for a clean, commercial look.