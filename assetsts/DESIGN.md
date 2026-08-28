---
name: Modern Persian Luxury
colors:
  surface: '#14130e'
  surface-dim: '#14130e'
  surface-bright: '#3b3932'
  surface-container-lowest: '#0f0e09'
  surface-container-low: '#1d1c16'
  surface-container: '#21201a'
  surface-container-high: '#2b2a24'
  surface-container-highest: '#36352e'
  on-surface: '#e7e2d8'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e7e2d8'
  inverse-on-surface: '#32302a'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c9c6c5'
  primary: '#c9c6c5'
  on-primary: '#313030'
  primary-container: '#080808'
  on-primary-container: '#7a7878'
  inverse-primary: '#5f5e5e'
  secondary: '#ecc246'
  on-secondary: '#3d2e00'
  secondary-container: '#b18c09'
  on-secondary-container: '#352800'
  tertiary: '#c8c6c5'
  on-tertiary: '#313030'
  tertiary-container: '#080808'
  on-tertiary-container: '#7a7878'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#ffe08e'
  secondary-fixed-dim: '#ecc246'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#584400'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474646'
  background: '#14130e'
  on-background: '#e7e2d8'
  surface-variant: '#36352e'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '300'
    lineHeight: '1.6'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
spacing:
  container-max: 1440px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  stack-lg: 4rem
  stack-md: 2rem
  stack-sm: 1rem
---

## Brand & Style
The design system for this luxury Islamic fashion house marries traditional Persian elegance with high-end modern e-commerce. The aesthetic is rooted in **Minimalism** and **Modern Corporate** styles, utilizing cinematic photography and expansive whitespace to convey exclusivity.

The brand personality is authoritative yet welcoming, focusing on the craftsmanship of the Chador. The UI should feel like a high-end physical boutique—quiet, spacious, and meticulously organized. Visual interest is generated through subtle gold accents and high-contrast typography rather than decorative clutter.

## Colors
The palette is dominated by **Deep Black** and **Charcoal**, creating a prestigious "Dark Mode" foundation that allows the textiles in photography to remain the focal point. 

- **Primary & Tertiary:** Used for the main canvas and deep UI layering to provide a sense of infinite depth.
- **Secondary (Luxury Gold):** Reserved strictly for calls to action, high-level branding elements, and active states.
- **Neutral (Cream):** Used for typography on dark backgrounds and as an occasional high-contrast section background to signal premium collection launches.

## Typography
The typography strategy utilizes a pairing of a high-contrast serif for an editorial feel and a clean, contemporary sans-serif for functional legibility.

- **Headlines:** Use **Libre Caslon Text** to evoke the heritage of Persian literature and classical fashion magazines.
- **Body & Interface:** Use **Be Vietnam Pro** at lighter weights (300/400) to maintain a modern, airy feel.
- **RTL Support:** For Persian text (Vazirmatn or Yekan Bakh), maintain equivalent optical sizing to the English counterparts.
- **Labels:** Use uppercase tracking (letter-spacing) for categories and breadcrumbs to reinforce the luxury aesthetic.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy on desktop to ensure a curated, gallery-like experience. 

- **Generous Margins:** Desktop layouts utilize 80px side margins to push content toward the center, creating a "boutique" focal point.
- **Vertical Rhythm:** Use large vertical gaps (`stack-lg`) between sections to allow the brand's cinematic imagery to "breathe."
- **Mobile Reflow:** On mobile, transition to a 2-column masonry grid for product listings to maximize visibility of fabric textures while maintaining readability.

## Elevation & Depth
This design system avoids heavy drop shadows in favor of **Tonal Layers** and **Low-Contrast Outlines**.

- **Surface Tiering:** Use Charcoal Black (#151515) for elevated cards or menus against the Deep Black (#080808) background.
- **Gold Accents:** Use 1px solid gold borders (#C9A227) for active input fields or primary button outlines to indicate interactivity.
- **Glassmorphism:** Navigation bars should use a 20px backdrop blur with 80% opacity on the primary background color to maintain context during scrolling.

## Shapes
To maintain an architectural and high-fashion aesthetic, this design system uses **Sharp (0px)** corners. 

Straight lines and right angles project a sense of discipline, precision, and modernism. This applies to all buttons, input fields, image containers, and cards. Use 1px strokes for dividers to mimic the fine stitching of luxury garments.

## Components
- **Buttons:** Primary buttons are solid Deep Black with a 1px Luxury Gold border and Gold text. On hover, the background transitions to a subtle Gold gradient.
- **Input Fields:** Minimalist design—bottom-border only (1px Luxury Gold) with floating labels in Be Vietnam Pro.
- **Product Cards:** No borders or background colors. Large-scale photography is primary. Product names are in Libre Caslon Text, prices in Be Vietnam Pro.
- **Chips/Filters:** Outlined boxes with 1px width. Active filters utilize the Luxury Gold color for the border and text.
- **Lists/Navigation:** Clean, high-contrast text with significant line height. Use a Gold dot indicator for active navigation items.
- **Additional Component - Image Hotspots:** Use a subtle Gold pulsing ring on model photography to allow users to "shop the look" directly from cinematic shots.