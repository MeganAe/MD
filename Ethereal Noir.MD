---
name: Ethereal Noir
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#37393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#d5c3bb'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#9e8d86'
  outline-variant: '#51443e'
  surface-tint: '#f2baa0'
  primary: '#f2baa0'
  on-primary: '#4a2816'
  primary-container: '#bd8b73'
  on-primary-container: '#482614'
  inverse-primary: '#7f543f'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#4a4949'
  on-secondary-container: '#bab8b7'
  tertiary: '#e3bfaf'
  on-tertiary: '#422b20'
  tertiary-container: '#b08f81'
  on-tertiary-container: '#40291f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbcb'
  primary-fixed-dim: '#f2baa0'
  on-primary-fixed: '#301304'
  on-primary-fixed-variant: '#643d2a'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#ffdbcb'
  tertiary-fixed-dim: '#e3bfaf'
  on-tertiary-fixed: '#2a170d'
  on-tertiary-fixed-variant: '#5a4135'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  section-padding: 80px
---

## Brand & Style

The design system embodies a high-fashion, editorial aesthetic tailored for the luxury beauty and hair industry. It speaks to a sophisticated audience that values premium quality and craftsmanship. The emotional response is one of aspiration, exclusivity, and timeless elegance.

The visual style is a blend of **Minimalism** and **Tactile Luxury**. It leverages expansive white space (or "noir" space in dark mode) to allow imagery to breathe, while incorporating metallic copper and rose gold accents to provide a sense of physical texture and value. The interface acts as a quiet, dark gallery that showcases vibrant product photography and warm skin tones with cinematic intensity.

## Colors

The palette is centered on a "Midnight and Metallic" theme. 

- **Primary (Copper/Rose Gold):** Used for call-to-action elements, key headings, and decorative accents. It should evoke a sense of shimmering metal.
- **Secondary (Deep Black):** The foundation of the UI. Not a pure flat black, but a rich, deep onyx that provides depth.
- **Tertiary (Dusty Rose/Skin):** A muted, warm tone used for secondary backgrounds, hover states, and to harmonize with the human elements in photography.
- **Neutral:** Pure white is used sparingly for high-legibility body text, while light grays are used for subtle UI borders.

Gradients should be used to simulate metallic reflections, moving from `#BD8B73` to `#E5C1B1`.

## Typography

The typography strategy relies on the contrast between the romantic, high-contrast strokes of **Playfair Display** and the functional, modern clarity of **Work Sans**.

- **Headlines:** Always Serif. Use generous tracking (letter spacing) for a more "fashion-spread" feel in subheadings, but keep it tight for large display headers.
- **Body:** Always Sans-Serif. Maintain high line-heights to ensure readability against dark backgrounds.
- **Micro-copy:** Small labels and buttons use uppercase Work Sans with increased letter spacing to denote a premium, curated feel.

## Layout & Spacing

This design system utilizes a **Fixed Grid** for desktop and a **Fluid Grid** for mobile. The layout is intentionally "airy," favoring large margins and substantial vertical breathing room between sections.

- **Desktop:** 12-column grid with a 1280px max-width.
- **Tablet:** 8-column grid with 32px side margins.
- **Mobile:** 4-column grid with 16px side margins.

Vertical rhythm is strictly controlled. Sections should be separated by at least `80px` to maintain the editorial feel. Component spacing is based on an 8px base unit.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layering** and **Subtle Metallic Shadows**. 

1. **Base:** The deepest black surface.
2. **Elevated Surfaces (Cards/Modals):** A slightly lighter shade of charcoal (`#1A1A1A`) with very soft, diffused copper-tinted shadows (`box-shadow: 0 20px 40px rgba(189, 139, 115, 0.1)`).
3. **Overlays:** Semi-transparent black overlays (80% opacity) are used over photography to ensure text legibility.
4. **Outlines:** Instead of heavy shadows, use 1px "inner-glow" borders in a faint copper tone to define elements.

## Shapes

To maintain a sharp, high-fashion edge, the design system utilizes **Sharp (0px)** corners for primary UI elements like buttons, input fields, and image containers. 

For softer, lifestyle-oriented components (like profile avatars or "special offers"), a subtle **Soft (4px)** radius may be applied, but the core identity remains architectural and geometric. Metallic "brushstroke" textures are used as organic overlays to break the rigidity of the sharp grid.

## Components

### Buttons
- **Primary:** Sharp corners, metallic copper gradient background, black text, uppercase label.
- **Secondary:** Transparent background, 1px copper border, white text.
- **Ghost:** No border, white or copper text, underline on hover.

### Cards
- Images should be the hero. Use a "frame" style where the image is inset within a thin metallic border.
- Text overlays should be centered using Playfair Display for titles.

### Input Fields
- Underline style preferred over boxed containers. 1px copper bottom border.
- Placeholder text in muted taupe.

### Navigation
- Top-aligned, centered logo.
- Links in Work Sans, uppercase, 12px.
- Subtle 1px divider between the announcement bar and main nav.

### Special Accents
- Use a "Signature" font or script for decorative sub-quotes that overlap images, simulating a handwritten editorial note.
