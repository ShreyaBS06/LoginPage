---
name: Aura Executive
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#464554'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#777586'
  outline-variant: '#c7c4d7'
  surface-tint: '#5148d7'
  primary: '#2a14b4'
  on-primary: '#ffffff'
  primary-container: '#4338ca'
  on-primary-container: '#c1beff'
  inverse-primary: '#c3c0ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#1f1ab3'
  on-tertiary: '#ffffff'
  tertiary-container: '#3b3bc9'
  on-tertiary-container: '#bebfff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e3dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#100069'
  on-primary-fixed-variant: '#372abf'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#e1e0ff'
  tertiary-fixed-dim: '#c0c1ff'
  on-tertiary-fixed: '#07006c'
  on-tertiary-fixed-variant: '#2f2ebe'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Hanken Grotesk
    fontSize: 3.5rem
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: '1.25'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 1.5rem
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Hanken Grotesk
    fontSize: 1.25rem
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: -0.01em
  body-md:
    fontFamily: Geist
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: '1.55'
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Geist
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0em
  label-lg:
    fontFamily: Geist
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.01em
  label-md:
    fontFamily: Geist
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.03em
  label-sm:
    fontFamily: Geist
    fontSize: 0.6875rem
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 2rem
  gutter-mobile: 1rem
  margin: 4rem
  margin-tablet: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system channels an editorial, high-trust SaaS aesthetic tailored for enterprise leaders, technical founders, and operators. The visual tone is composed, authoritative, and frictionless. It avoids overt playfulness and neon saturation, favoring deliberate architectural layout, deep tonal contrast, and expansive breathing room. 

The aesthetic merges **Minimalism** with subtle **Glassmorphic** depth. The split-screen dynamic creates two complementary atmospheres:
1. **The Brand Showcase (Left Frame):** A rich, deep-slate canvas serving as an ambient editorial stage. It highlights product validation through crisp typography, subdued metric badges, and layered quote blocks.
2. **The Authentication Canvas (Right Frame):** An expansive, pristine workspace centered on effortless interaction. The interface prioritizes clear visual paths, frictionless input focus, and non-distracting hierarchy.

## Colors

The palette leverages deep atmospheric slates anchored by precise indigo touches.

- **Primary (`#4338CA` - Indigo 700):** Reserved for primary conversion vectors, primary interactive states, and high-visibility focus borders. Communicates operational intelligence and focus.
- **Secondary (`#0F172A` - Slate 900):** Anchors the brand showcase pane, primary headers, and base typography. Imparts structural weight and high editorial contrast.
- **Tertiary (`#6366F1` - Indigo 500):** Accents, subtle glow diffusions, active toggles, and contextual highlights within data metrics or testimonial callouts.
- **Neutral (`#64748B` - Slate 500):** Structural lines, subtle dividers, helper text, and secondary icon outlines.
- **Surface Foundations:** The form panel rests on clean, unblemished light surfaces (`#FFFFFF` to `#F8FAFC`), while the brand showcase utilizes layered dark tones (`#020617` base with `#0F172A` containers and translucent indigo-tinted borders).

## Typography

The typographic strategy balances editorial display cadence with clinical legibility. 

- **Hanken Grotesk** commands display titles, testimonials, and section lead-ins. Its precise geometry and subtle optical cuts present authority without feeling mechanical.
- **Geist** governs microcopy, input states, buttons, labels, and analytical metrics. Its engineered proportions ensure crisp rendering at compact sizes, critical for low-friction authentication flows.
- Tight negative tracking (`-0.03em` to `-0.015em`) is applied systematically across heading scales to create density and tension, while body copy retains neutral or slightly open tracking for rapid scanning.

## Layout & Spacing

The layout is built around an uncompromising 50/50 desktop split that transitions gracefully across viewport scales.

- **Desktop (1024px+):** A rigid dual-pane architecture pinned to 100vh. The left panel houses the brand showcase within a fixed container featuring internal fluid padding (`margin: 4rem`), preventing visual drift. The right panel is vertically centered with a maximum content constraint of `440px` to maintain strict optical balance.
- **Tablet (768px - 1023px):** The left showcase panel reduces to 40% width, collapsing secondary metrics while maintaining the testimonial quote. Outer margins compress to `margin-tablet`.
- **Mobile (<768px):** The screen reflows into a single-column layout. The brand showcase drops the ambient graphical backdrop, reducing to a compact header banner (brand mark and a streamlined value statement) while the authentication form takes full viewport precedence with `margin-mobile`.
- Spacing within the interaction panel follows an eight-point rhythm; form elements maintain an internal `space-lg` separation to isolate interactive tap targets.

## Elevation & Depth

Visual hierarchy relies on flat architectural planes framed by ultra-subtle ambient shadows and low-contrast borders rather than exaggerated skeuomorphic drop shadows.

- **Light Surfaces (Form Panel):** Structural depth is established using crisp, hairline boundaries (`1px solid #E2E8F0`). Secondary panels (such as social authentication buttons) rely on a rested state with an imperceptible ambient drop shadow: `0 1px 2px 0 rgba(15, 23, 42, 0.04)`.
- **Dark Showcase (Left Panel):** Depth is created via tonal stacking. The root background is `#020617`, overlaid with glass-tinted metric cards using surface blur (`backdrop-filter: blur(16px)`), a dark fill of `#0F172A` at 70% opacity, and a rim light stroke of `1px solid rgba(255, 255, 255, 0.08)`.
- **Interactive Elevations:** Form input focus and primary buttons utilize a soft indigo ambient aura (`0 0 0 3px rgba(99, 102, 241, 0.15)`) instead of standard browser rings, emphasizing refined digital craft.

## Shapes

The design system employs a soft, restrained corner radius (`roundedness: 1`). Interactive elements use `0.25rem` (4px) to `0.5rem` (8px), reinforcing an architectural, professional tone. 

- Form inputs, buttons, and alert states use `0.375rem` (6px) base geometry.
- Ambient cards, social containers, and testimonial panels employ `rounded-lg` (8px).
- Circular pills are intentionally avoided except for compact numerical status indicators and subtle live metrics badges.

## Components

### Buttons
- **Primary Action:** Solid `#4338CA` background, `#FFFFFF` text, `0.375rem` radius, 44px minimum touch height, `Geist label-lg`. Transitions on hover to `#3730A3` with subtle elevation. Active state slightly scales (`transform: scale(0.99)`).
- **Secondary / Social Login:** Clean white background with a `#E2E8F0` border and `#0F172A` text. Icons sit at 18px with optical alignment. Hover triggers `#F8FAFC` background and a `#CBD5E1` border transition.
- **Text Link:** `#4338CA` text, semi-bold weight, no underline in rest state; reveals a 1px offset underline on hover.

### Input Fields
- **Container:** Minimum 44px height, light background (`#FFFFFF`), hairline perimeter stroke (`#CBD5E1`).
- **Floating / Clean Labels:** Small, crisp label positioned directly above the input in `label-md` uppercase styling using `#64748B`.
- **Focus State:** Border transitions to `#4338CA` accompanied by an ambient halo `box-shadow: 0 0 0 3px rgba(99, 102, 241, 0.12)`.
- **Validation:** Error triggers an inline indicator in `#EF4444` accompanied by a crimson border tint (`#F87171`); helper text occupies fixed height beneath the field to prevent layout shift.

### Checkboxes & Segmented Controls
- **Checkbox:** Crisp 16px square with a `0.25rem` radius. Unchecked state is bordered with `#CBD5E1`. Checked state fills `#4338CA` with a white checkmark icon.
- **Labels:** Paired with `body-sm` typography in `#334155`, vertically centered with a generous tap target padding.

### Brand Showcase Cards & Testimonials
- **Quote Module:** Features an oversized, low-opacity quote glyph or crisp company mark, followed by `body-lg` text in `#F1F5F9`. The attribution row displays a high-resolution avatar paired with the author's title in `#94A3B8`.
- **Metrics Chips:** Translucent containers sitting inside the showcase with glowing indigo metric highlights (`label-sm` combined with `headline-sm`), providing immediate enterprise proof points.

### Dividers & Ancillary Elements
- **Or-Divider:** Thin hairline rule (`#E2E8F0`) broken centered by a `label-sm` uppercase string (`OR CONTINUE WITH`) styled in `#94A3B8` with `0.5rem` horizontal padding.