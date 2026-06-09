---
name: AlertBukavu
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#5b403e'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#906f6d'
  outline-variant: '#e4bdbb'
  surface-tint: '#bc1127'
  primary: '#840015'
  on-primary: '#ffffff'
  primary-container: '#b00020'
  on-primary-container: '#ffbbb8'
  inverse-primary: '#ffb3af'
  secondary: '#795900'
  on-secondary: '#ffffff'
  secondary-container: '#ffbf00'
  on-secondary-container: '#6d5000'
  tertiary: '#004171'
  on-tertiary: '#ffffff'
  tertiary-container: '#005997'
  on-tertiary-container: '#a9cfff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3af'
  on-primary-fixed: '#410006'
  on-primary-fixed-variant: '#930019'
  secondary-fixed: '#ffdfa0'
  secondary-fixed-dim: '#fbbc00'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#5c4300'
  tertiary-fixed: '#d1e4ff'
  tertiary-fixed-dim: '#9fcaff'
  on-tertiary-fixed: '#001d36'
  on-tertiary-fixed-variant: '#00497d'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  container-margin: 16px
  gutter: 16px
---

## Brand & Style

The visual identity of the design system is rooted in the pillars of reliability, community, and rapid communication. It is designed to be a "trusted companion" for the citizens of Bukavu, offering a calm and structured environment during potentially stressful situations.

The style follows a **Modern Corporate** aesthetic—clean, functional, and devoid of unnecessary decoration. The primary goal is legibility and speed of information processing. By using a light, airy background paired with high-contrast status colors, the interface ensures that critical alerts are immediately distinguishable from general community information. The overall tone is professional and institutional, yet the community-focused slogan "Informer. Protéger. Agir." grounds the brand in a local, human-centric mission.

## Colors

The color palette is functionally driven, using color as a primary signal for urgency and categorization.

- **Primary (Emergency Red):** Used exclusively for high-priority, life-threatening, or critical alerts. It demands immediate attention.
- **Secondary (Amber):** Reserved for medium-priority warnings, such as traffic disruptions or weather advisories that require caution but not immediate evacuation.
- **Tertiary (Blue):** Utilized for informational updates, community news, and general public service announcements.
- **Success (Green):** Indicates resolved issues or "all-clear" status updates.
- **Neutral/Background:** A clean, off-white foundation ensures that the status colors pop effectively without causing visual fatigue. Deep charcoal is used for text to maintain high accessibility.

## Typography

The design system utilizes **Inter** for all typographic needs. As a highly utilitarian and legible sans-serif, it provides the clarity necessary for an emergency response application.

- **Headlines:** Use a tighter tracking and heavier weights to create a strong visual anchor for alert titles.
- **Body Copy:** Set with generous line heights to ensure readability, especially for users who may be viewing the screen in high-glare outdoor environments or in stressful situations.
- **Labels:** Used for urgency badges and metadata (time, location), these utilize slightly increased letter-spacing and medium weights to remain legible even at very small sizes.

## Layout & Spacing

This design system employs a **Fluid Grid** model centered on an 8px rhythmic scale. This ensures a consistent vertical and horizontal cadence across all components.

- **Mobile (Default):** A 4-column layout with 16px side margins. Most alerts will span the full width of the 4 columns as cards.
- **Tablet/Desktop:** A 12-column grid. Content is typically centered in a maximum width container (1200px) to prevent long line lengths that hinder readability.
- **Padding:** Use the `md` (16px) spacing unit for internal card padding and the `lg` (24px) unit to separate distinct content sections or alert groups.

## Elevation & Depth

To maintain a "clean and light" feel while highlighting critical information, the design system uses **Tonal Layers** supplemented by **Ambient Shadows**.

- **Level 0 (Background):** The base surface (#f8f9fa).
- **Level 1 (Default Cards):** Pure white (#ffffff) with a subtle, 1px border (#e9ecef) and no shadow for non-critical information.
- **Level 2 (Active Alerts):** Pure white with a soft, diffused shadow (10% opacity, 12px blur) to lift the alert above the background, signaling its importance.
- **Critical Override:** For high-priority alerts, a subtle tinted glow or a thick 4px left-hand border in Emergency Red is used instead of heavy shadows to maintain a clean aesthetic while indicating extreme urgency.

## Shapes

The design system uses a **Rounded** shape language to create a sense of approachability and community care. 

- **Cards & Input Fields:** Use a 0.5rem (8px) radius to feel modern and professional.
- **Urgency Badges:** Use a fully rounded/pill shape to distinguish them from other UI elements and make them instantly recognizable as status indicators.
- **Buttons:** Large action buttons (e.g., "Report an Incident") follow the 8px radius to match the card containers, providing a cohesive and structured appearance.

## Components

### Buttons
Primary buttons use high-contrast fills. The "Report" button should always be prominent, using a saturated blue or green to encourage constructive action without mimicking the "Emergency Red" reserved for system alerts.

### Urgency Badges
- **Critical:** Emergency Red background with White text.
- **Medium:** Amber background with Dark Gray text.
- **Low:** Light Blue/Green background with Deep Blue/Green text.
These should be positioned in the top-right corner of alert cards for immediate identification.

### Alert Cards
Cards are the primary vehicle for information. They feature a white background, a bold headline (Inter 600), a timestamp, and a location label. High-priority cards should include a vertical "status bar" on the left edge in the corresponding urgency color.

### Input Fields
Inputs are clean with a light gray stroke. Upon focus, the stroke should change to the tertiary blue color. Placeholders should be clear and instructive to facilitate quick data entry during reports.

### Lists
Lists of community updates should use subtle dividers (1px, light gray) with generous vertical padding (16px) to ensure touch targets are large enough for mobile users on the go.
