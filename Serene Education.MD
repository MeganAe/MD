---
name: Serene Education
colors:
  surface: '#f8f9fd'
  surface-dim: '#d9dade'
  surface-bright: '#f8f9fd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3f7'
  surface-container: '#edeef2'
  surface-container-high: '#e7e8ec'
  surface-container-highest: '#e1e2e6'
  on-surface: '#191c1f'
  on-surface-variant: '#484552'
  inverse-surface: '#2e3134'
  inverse-on-surface: '#eff1f5'
  outline: '#797583'
  outline-variant: '#c9c4d3'
  surface-tint: '#5e50b0'
  primary: '#5e50b0'
  on-primary: '#ffffff'
  primary-container: '#a294f9'
  on-primary-container: '#372687'
  inverse-primary: '#c8bfff'
  secondary: '#4c635e'
  on-secondary: '#ffffff'
  secondary-container: '#cce5df'
  on-secondary-container: '#506763'
  tertiary: '#635b70'
  on-tertiary: '#ffffff'
  tertiary-container: '#a79db4'
  on-tertiary-container: '#3c3448'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5deff'
  primary-fixed-dim: '#c8bfff'
  on-primary-fixed: '#1a0064'
  on-primary-fixed-variant: '#463796'
  secondary-fixed: '#cfe8e2'
  secondary-fixed-dim: '#b3ccc6'
  on-secondary-fixed: '#081f1c'
  on-secondary-fixed-variant: '#354b47'
  tertiary-fixed: '#eadef7'
  tertiary-fixed-dim: '#cdc2da'
  on-tertiary-fixed: '#1f182a'
  on-tertiary-fixed-variant: '#4b4357'
  background: '#f8f9fd'
  on-background: '#191c1f'
  surface-variant: '#e1e2e6'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  display-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 36px
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  base: 4px
  container-padding: 24px
  stack-gap: 16px
  card-gap: 12px
  section-margin: 32px
---

## Brand & Style
The design system focuses on a friendly, welcoming, and encouraging atmosphere for personal growth and education. It targets lifelong learners who seek a low-stress, high-clarity environment for skill building.

The aesthetic blends **Modern Corporate** clarity with **Soft Playful** elements. It utilizes high-radius containers, gentle pastel color blocking, and whimsical illustrative backgrounds (stars, subtle patterns) to reduce cognitive load and make learning feel like a delightful, approachable journey rather than a chore.

## Colors
The palette is built on soft pastels that provide organizational cues without visual aggression.

- **Lavender (#A294F9/E5D9F2):** Used for primary actions, progress indicators, and subject-specific card backgrounds (e.g., Creative/Data Analysis).
- **Mint Green (#CBE4DE):** Used for secondary highlights and category-specific backgrounds (e.g., Tech/Software).
- **Light Blue (#DDE6ED):** Used for neutral supportive elements and book illustrations.
- **Accent Dark (#121417):** Reserved for high-priority CTA buttons and primary headlines to ensure strong legibility.
- **Surface:** A clean, off-white neutral base ensures pastels pop without creating excessive glare.

## Typography
This design system uses **Plus Jakarta Sans** exclusively to maintain a modern, friendly, and geometric feel. 

Typography is characterized by tight tracking in headlines and generous line height in body text to improve readability. Content hierarchy is established through significant weight shifts (Bold for titles, Medium for body) rather than just size. Captions and labels often use a semi-bold weight to remain legible against colorful pastel backgrounds.

## Layout & Spacing
The layout follows a **fluid grid** model optimized for mobile-first consumption. 

- **Safe Zones:** A standard 24px horizontal margin is applied to all screens.
- **Rhythm:** An 8px linear scale drives all vertical spacing.
- **Card Layouts:** Information is grouped into large, distinct cards. Each card has internal padding of 20px-24px to ensure content does not feel cramped against the high-radius corners.
- **Adaptive Strategy:** On tablets, the single-column list reflows into a 2-column masonry grid for course cards, maintaining the 24px gutter.

## Elevation & Depth
Depth is created through **Tonal Layering** rather than traditional shadows. 

- **Base Layer:** The canvas uses a light grey/white neutral.
- **Mid Layer:** Cards use flat pastel fills (Lavender/Mint) to distinguish different content types.
- **Top Layer:** Interactive elements like "Play" buttons or "Next" arrows are often white circular buttons with very soft, high-diffusion shadows (10% opacity, 20px blur) to suggest clickability.
- **Overlays:** Modals and bottom sheets utilize a backdrop blur (glassmorphism) to maintain the sense of place while focusing the user.

## Shapes
The shape language is extremely soft and organic. 

- **Main Containers:** Course cards and progress sections use a generous 32px radius.
- **Buttons:** Primary CTA buttons are pill-shaped (fully rounded) to maximize the "friendly" feel.
- **Icons:** Icons are contained within soft-square backgrounds (12px radius) or circular strokes. 
- **Calendar:** Active dates use circular high-contrast fills, while the calendar container itself mirrors the 32px course card radius.

## Components

### Cards
- **Course Cards:** Feature a background illustration, a category label, a star rating chip, and a bottom-right circular navigation arrow. 
- **Stat Cards:** Use white backgrounds with subtle pastel icons to represent "streak" or "hours spent."

### Buttons
- **Primary:** Dark background with white text, pill-shaped. Often paired with a trailing icon in a separate circular container.
- **Icon Buttons:** Circular white containers with centered black/dark grey strokes.

### Progress Bars
- Use a thick track with a secondary pastel color (e.g., Light Lavender) and a primary pastel color for the fill (e.g., Deep Lavender). Terminals are fully rounded.

### Calendar
- **Header:** Integrated within the card, using simple chevron navigation.
- **Date States:** 
  - *Default:* Dark text on light pastel background.
  - *Active/Current:* Solid dark circle with white text.
  - *Selected Range:* Connected soft-pastel pill background.

### Input & Fields
- Search bars use high-radius (pill) shapes with a search icon prefix and subtle interior padding.
