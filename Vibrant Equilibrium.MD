---
name: Vibrant Equilibrium
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
  on-surface-variant: '#4c4637'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#7e7665'
  outline-variant: '#cfc6b2'
  surface-tint: '#725c00'
  primary: '#725c00'
  on-primary: '#ffffff'
  primary-container: '#f9d976'
  on-primary-container: '#745e00'
  inverse-primary: '#e3c464'
  secondary: '#8c476e'
  on-secondary: '#ffffff'
  secondary-container: '#ffaad6'
  on-secondary-container: '#7c3a60'
  tertiary: '#406743'
  on-tertiary: '#ffffff'
  tertiary-container: '#bae7b9'
  on-tertiary-container: '#426944'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe083'
  primary-fixed-dim: '#e3c464'
  on-primary-fixed: '#231b00'
  on-primary-fixed-variant: '#564500'
  secondary-fixed: '#ffd8e9'
  secondary-fixed-dim: '#ffafd7'
  on-secondary-fixed: '#3b0228'
  on-secondary-fixed-variant: '#713055'
  tertiary-fixed: '#c1eebf'
  tertiary-fixed-dim: '#a6d2a5'
  on-tertiary-fixed: '#002107'
  on-tertiary-fixed-variant: '#284f2d'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-bold:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
  data-display:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 28px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 16px
  margin-mobile: 20px
  card-padding: 24px
  stack-gap: 12px
---

## Brand & Style

The design system is a dual-natured framework that balances high-energy, expressive exploration with calm, functional utility. It is designed for lifestyle and health platforms that need to transition seamlessly between "discovery mode" (creative, social, playful) and "management mode" (data-driven, organized, focused).

The aesthetic marries **Modern Minimalism** with **Organic Playfulness**. It utilizes large, soft-edged geometric shapes and a vibrant pastel palette to create a friendly, low-stress environment. The visual language relies on significant whitespace, bold "lifestyle" typography, and a "squishy" tactile feel that makes digital interactions feel more approachable and less clinical.

Key brand attributes:
- **Optimistic:** Bright colors and rounded forms reduce cognitive friction.
- **Adaptive:** Scales from expressive, abstract layouts to dense, information-rich dashboards.
- **Human-Centric:** Uses soft shadows and layered surfaces to mimic physical cards and stickers.

## Colors

The palette is divided into "Expressive Pastels" and "Functional Neutrals." The primary yellow (`#F9D976`) serves as the core brand identifier, used for high-impact surfaces and primary calls to action. Secondary and tertiary colors (Pink and Mint) are used to categorize content or represent different data streams in health visualizations.

The background is a warm off-white (`#FDFCF5`) to maintain a soft, paper-like feel rather than a sterile digital white. Navigation elements and heavy contrast areas utilize a deep neutral (`#1A1A1A`) to ground the airy colors and provide a clear structural anchor for the user’s thumb on mobile devices.

## Typography

This design system uses a combination of **Plus Jakarta Sans** for high-energy display moments and **Hanken Grotesk** for functional, high-legibility interface copy. 

Headlines should use tight letter spacing and bold weights to create a "poster-like" feel in discovery views. In functional health views, the typography shifts toward Hanken Grotesk to ensure that numerical data and metrics are clear and easily scannable. Use "data-display" for primary metrics like heart rate or calorie counts to ensure they stand out within modular card layouts.

## Layout & Spacing

The layout philosophy relies on a **Fluid Grid** with generous internal container padding. 
- **Discovery Layouts:** Use an "Organic Flow" where elements like stickers or circles can break the grid, overlapping slightly to create depth.
- **Functional Layouts:** Transition to a structured 2-column or 1-column card stack. 
- **Safe Zones:** Always maintain a bottom margin of at least 100px on mobile to accommodate the floating navigation bar and centered action buttons.

Spacing rhythm follows a 4px baseline, but primary grouping uses 12px (stack-gap) to maintain a "tight but breathable" appearance.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Soft Ambient Shadows**. 

1.  **Base Layer:** The off-white background.
2.  **Card Layer:** Colored surfaces (Yellow, Pink, Mint) or White cards with a very soft, high-blur shadow (y: 4px, blur: 20px, opacity: 5%). 
3.  **Floating Layer:** Primary navigation bars and Floating Action Buttons (FABs) use a high-contrast dark fill to appear at the highest elevation, visually "popping" off the pastel background.
4.  **Glassmorphism:** Use subtle backdrop blurs (10px) on top-tier navigation headers or overlay modals to maintain context of the layer beneath.

## Shapes

The shape language is the defining characteristic of the design system. It avoids sharp corners entirely to maintain a friendly, approachable mood.

- **Primary Cards:** 1rem (16px) corner radius.
- **Interactive Buttons:** 2rem (32px) or full pill-shape.
- **Organic Elements:** Use "Squircle" logic or circular masks for lifestyle images.
- **Icons:** Set within rounded square or circular containers to act as "mini-stickers."

## Components

### Buttons & Navigation
- **Primary FAB:** A central, oversized circular button in the bottom navigation bar. Usually dark or primary colored with a white "+" icon.
- **Bottom Navigation:** A pill-shaped dark container floating above the bottom edge, featuring simplified line icons.
- **Chips:** Small, pill-shaped tags used for filtering (e.g., "Days", "Weeks") or status indicators.

### Cards & Data
- **Metric Cards:** Dual-toned or white cards with a corner icon and large-scale typography for primary numbers. 
- **Progress Rings:** Use thick strokes with rounded end-caps for data visualization.
- **List Items:** Grouped within a single card container with subtle dividers, using the `body-md` type for titles and `label-bold` for secondary metadata.

### Inputs
- **Search Bars:** Full pill-shaped containers with a background tint slightly darker or lighter than the parent surface to indicate interactivity.
