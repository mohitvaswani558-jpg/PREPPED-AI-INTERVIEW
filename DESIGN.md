---
name: Cognitive Prestige
colors:
  surface: '#051424'
  surface-dim: '#051424'
  surface-bright: '#2c3a4c'
  surface-container-lowest: '#010f1f'
  surface-container-low: '#0d1c2d'
  surface-container: '#122131'
  surface-container-high: '#1c2b3c'
  surface-container-highest: '#273647'
  on-surface: '#d4e4fa'
  on-surface-variant: '#c6c6cd'
  inverse-surface: '#d4e4fa'
  inverse-on-surface: '#233143'
  outline: '#909097'
  outline-variant: '#45464d'
  surface-tint: '#bec6e0'
  primary: '#bec6e0'
  on-primary: '#283044'
  primary-container: '#0f172a'
  on-primary-container: '#798098'
  inverse-primary: '#565e74'
  secondary: '#adc6ff'
  on-secondary: '#002e6a'
  secondary-container: '#0566d9'
  on-secondary-container: '#e6ecff'
  tertiary: '#ebc07c'
  on-tertiary: '#432c00'
  tertiary-container: '#231500'
  on-tertiary-container: '#9f7b3e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#ffdeac'
  tertiary-fixed-dim: '#ebc07c'
  on-tertiary-fixed: '#281900'
  on-tertiary-fixed-variant: '#5e4108'
  background: '#051424'
  on-background: '#d4e4fa'
  surface-variant: '#273647'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

The design system is engineered to evoke the persona of an **Expert Mentor**—a presence that is authoritative yet empowering, sophisticated yet accessible. The target audience consists of high-achieving professionals and elite candidates who require a platform that mirrors the gravity of their career ambitions.

The visual style is **Corporate Modern with Glassmorphic accents**. It avoids the sterility of typical SaaS platforms by introducing tactile depth and high-fidelity finishes. The emotional response should be one of "composed confidence"—the feeling of walking into a high-end executive boardroom. Key characteristics include:
- **Precision:** High-contrast borders and surgical typography alignment.
- **Sophistication:** Subtle use of metallic accents (soft gold) and deep tonal layering.
- **Intelligence:** Translucent surfaces that suggest a "look under the hood" at the underlying AI logic.

## Colors

The palette is anchored in a **Deep Navy and Slate** foundation to establish trust and stability.
- **Primary (Deep Navy):** Used for background surfaces and deep structural elements to provide a sense of groundedness.
- **Secondary (Intelligence Blue):** A vibrant, high-energy blue used for primary actions and to signify active AI processing or "intelligence" states.
- **Tertiary (Soft Gold):** Reserved for "premium" indicators, achievement milestones, and subtle high-fidelity accents like thin borders or highlight pips.
- **Neutral (Slate):** Provides the scale for secondary text and decorative UI borders.

The default mode is **Dark**, utilizing a range of charcoal and navy tones to reduce eye strain during intensive prep sessions while maintaining a high-end aesthetic.

## Typography

The typography system utilizes **Inter** exclusively to lean into a systematic, utilitarian, and modern aesthetic. 

- **Headlines:** Use tighter letter spacing and semi-bold weights to create a "dense" and authoritative look.
- **Body:** Optimized for legibility with generous line heights (1.5x - 1.6x) to ensure long-form feedback is easily digestible.
- **Labels:** Small, uppercase labels with increased tracking are used for metadata and category tags to differentiate them from interactive text.
- **Hierarchy:** Contrast is achieved through weight transitions rather than extreme size shifts, maintaining a disciplined, professional cadence.

## Layout & Spacing

The design system employs a **Fixed Grid** on desktop to maintain a "contained" and high-end editorial feel, while transitioning to a fluid model for mobile devices.

- **Grid:** A 12-column grid is used for the main dashboard. Content is often centered with significant lateral margins to create a sense of focus and prestige.
- **Spacing Scale:** Based on an 8px baseline. Large internal paddings (32px+) are encouraged within containers to provide "breathing room" for complex data.
- **Responsive Behavior:** 
    - **Desktop (1280px+):** Fixed container with 64px margins.
    - **Tablet (768px - 1024px):** Fluid 8-column grid with 32px margins.
    - **Mobile (below 768px):** Fluid 4-column grid with 20px margins; stacked layout for card components.

## Elevation & Depth

Depth is conveyed through a combination of **Tonal Layering** and **Glassmorphism**, specifically:

- **Surface Levels:** 
  - `Level 0 (Background)`: Deepest Navy (#0F172A).
  - `Level 1 (Card)`: Slightly lighter Slate-Navy (#1E293B) with a 1px border.
  - `Level 2 (Overlay)`: Semi-transparent glass layer with a `backdrop-filter: blur(12px)`.
- **Shadows:** Use "Ambient Shadows"—extremely low opacity (8-10%) with a large spread, tinted with the primary blue color rather than pure black, to create a subtle glow.
- **Borders:** Every card and button must have a 1px "crisp border." For glass layers, use a top-weighted gradient border to simulate a light source from above.

## Shapes

The shape language is **Soft (0.25rem - 0.75rem)**. This provides enough curvature to feel modern and approachable without losing the professional "edge" required for an elite platform.

- **Primary Elements:** Buttons and Input fields use a 4px (0.25rem) radius for a sharp, precise look.
- **Containers:** Dashboard cards and modal containers use an 8px (0.5rem) radius.
- **Interactive Pips:** Small indicators (like online status or notification dots) are the only elements allowed to be fully circular.

## Components

- **Buttons:** 
  - *Primary:* Solid Intelligence Blue with a subtle inner top-glow. 
  - *Secondary:* Ghost style with a Soft Gold border and gold-tinted text for premium actions.
- **Input Fields:** Darker than the card surface, using a 1px Slate border that illuminates into Blue on focus.
- **Cards (Interview Session):** Utilize glassmorphism for the header section of the card. Use high-contrast dividers to separate data points.
- **Chips (Skill Tags):** Small, rectangular with a subtle background tint and 1px border; no icons unless they represent AI-verified skills.
- **AI Feedback List:** Uses alternating tonal backgrounds (zebra striping) but with very low contrast to keep the interface calm.
- **Progress Gauges:** High-fidelity ring charts using a gradient of Blue to Gold to represent "Readiness Score."