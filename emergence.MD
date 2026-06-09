---
name: Emergency Response Framework
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
  on-surface-variant: '#5b403e'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#906f6d'
  outline-variant: '#e4bdbb'
  surface-tint: '#bc1127'
  primary: '#840015'
  on-primary: '#ffffff'
  primary-container: '#b00020'
  on-primary-container: '#ffbbb8'
  inverse-primary: '#ffb3af'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dfe0e0'
  on-secondary-container: '#616363'
  tertiary: '#761f24'
  on-tertiary: '#ffffff'
  tertiary-container: '#953639'
  on-tertiary-container: '#ffbbb9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3af'
  on-primary-fixed: '#410006'
  on-primary-fixed-variant: '#930019'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#ffdad8'
  tertiary-fixed-dim: '#ffb3b1'
  on-tertiary-fixed: '#410007'
  on-tertiary-fixed-variant: '#80272b'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 26px
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
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  emergency-button:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '800'
    lineHeight: 24px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  margin-mobile: 20px
  margin-desktop: 40px
  gutter: 16px
  touch-target-min: 48px
  component-gap: 12px
---

## Brand & Style

The design system is engineered for high-stakes environments where cognitive load must be minimized. The brand personality is **authoritative, immediate, and reliable**, serving as a digital lifeline for the citizens of Bukavu. 

The visual style is **Corporate / Modern** with a lean toward **High-Contrast Functionalism**. It prioritizes utility over decoration, utilizing a stark white canvas to make critical red action elements pop. The emotional response is one of "calm within the storm"—the UI does not panic, it provides a structured, clear path to safety. Elements are sized for "fat-finger" accessibility, ensuring that even under physical duress or environmental instability, the user can successfully trigger an alert.

## Colors

This design system utilizes a high-visibility palette rooted in emergency signal standards. 

- **Primary (Deep Red):** Used exclusively for critical calls to action (SOS), destructive actions, and active emergency status indicators.
- **Secondary (Pure White):** The base for all containers and backgrounds to ensure maximum contrast for text and icons.
- **Accents (Light Red/Pink):** Employed for secondary alert tiles and progress indicators to maintain the thematic urgency without competing with the primary SOS triggers.
- **Text & UI Neutral:** A nearly-black grey is used for all primary text to ensure readability against white backgrounds, meeting WCAG AAA standards.

## Typography

The typography system relies on **Inter** for its exceptional legibility and neutral tone. In emergency contexts, we prioritize sans-serif typefaces with generous x-heights.

- **Headlines:** Bold and tight-letterspaced to convey urgency and hierarchy.
- **Emergency Button Text:** Uses an increased weight and uppercase styling to stand out as the most important element on any screen.
- **Body Text:** Scaled slightly larger than standard consumer apps (16px minimum) to ensure readability in low-light or vibrating environments.
- **Timeline Labels:** Use a combination of weight and color (Deep Red) to distinguish between status updates and descriptive metadata.

## Layout & Spacing

The layout philosophy follows a **Fluid Grid** model with a focus on mobile-first accessibility. 

- **Grid:** On mobile, a 4-column layout is used with 20px outer margins. On desktop/tablet, this scales to 12 columns.
- **Touch Targets:** All interactive elements maintain a minimum size of 48x48px. 
- **Rhythm:** An 8px base unit drives all spacing. Emergency Type cards use a "square-grid" layout (2 columns on mobile) to provide large, easily tappable areas.
- **Reflow:** Map views are intended to occupy the top 40-50% of the screen on mobile, reflowing to a side-panel on desktop, ensuring the timeline and tracking data remain visible at all times.

## Elevation & Depth

This design system uses **Tonal Layers** and **Ambient Shadows** to create a functional hierarchy without visual clutter.

- **Base Layer:** Pure White (#FFFFFF).
- **Secondary Layer (Cards):** Subsurface white with a very soft, diffused 10% opacity black shadow (Y: 4px, Blur: 12px). This lifts active information (like the current address) off the base.
- **Critical Layer (SOS):** Uses a pulsing radial glow effect rather than a traditional shadow to signify an "active" state and draw the eye immediately.
- **Navigation:** A flat bottom-bar with a subtle top border (#EEEEEE) ensures the primary app controls remain anchored without obstructing the map view.

## Shapes

The shape language is **Rounded (Level 2)**. 

- **Standard Buttons:** 0.5rem (8px) radius provides a modern, approachable feel while remaining professional.
- **Emergency Cards:** 1rem (16px) radius for larger containers like the "Join Operation" modal or Emergency Type selectors.
- **The SOS Button:** A perfect circle, distinguishing it from all other UI elements as the primary life-saving action.
- **Inputs:** Soft 8px rounding to match button styles, creating a cohesive form-entry experience.

## Components

### Buttons
- **Primary Action:** Solid Deep Red background, white text, 8px radius. Large height (56px).
- **Secondary Alert:** Tinted Red background (#FFEBEE), Deep Red text/icons. Used for category selection.
- **Ghost Buttons:** Deep Red outline and text, no fill. Used for "Cancel" or "Recover" actions.

### Map Elements
- **Tracking Lines:** 4px stroke width in Deep Red.
- **User Marker:** Circular avatar with a Red stroke.
- **Responder Marker:** Blue shield icon to distinguish official help from civilian users.

### Timeline
- **Vertical Track:** 2px solid line in Light Red.
- **Milestones:** Hollow circles for past events; Solid pulsating circles for "Current" status.
- **Timestamps:** 12px medium weight, aligned right for quick scanning.

### Input Fields
- **Default:** Light grey border (1px), centered icons (20px size).
- **Active:** Deep Red border with 2px stroke to clearly indicate focus.
- **Icons:** Use thick, simple line-weights to ensure visibility at small sizes.
