---
name: AVA Logistics Design System
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#515f74'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3fd'
  on-secondary-container: '#57657b'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#271901'
  on-tertiary-container: '#98805d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#d5e3fd'
  secondary-fixed-dim: '#b9c7e0'
  on-secondary-fixed: '#0d1c2f'
  on-secondary-fixed-variant: '#3a485c'
  tertiary-fixed: '#fcdeb5'
  tertiary-fixed-dim: '#dec29a'
  on-tertiary-fixed: '#271901'
  on-tertiary-fixed-variant: '#574425'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Manrope
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Manrope
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
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
  margin-mobile: 16px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style
The design system for AVA Logistics is built upon the pillars of **Precision, Authority, and Global Connectivity**. It targets high-level enterprise decision-makers who value reliability and sophisticated infrastructure. 

The visual style is a refined blend of **Minimalism** and **Modern Corporate** aesthetics. It utilizes expansive whitespace to denote premium quality, combined with a "mechanical" precision in alignment and grid usage. The emotional response should be one of absolute confidence—moving complex freight should feel as effortless and controlled as the UI itself. 

Key stylistic principles:
- **Quiet Luxury:** High-end aesthetics achieved through restraint rather than decoration.
- **Directional Clarity:** Using strong vertical and horizontal lines to mimic logistics lanes and movement.
- **Architectural Hierarchy:** Information is structured in clear tiers, ensuring critical data points (like shipping status or KPIs) are immediately visible.

## Colors
The palette is anchored by **Deep Navy (#0F172A)**, providing a foundation of institutional trust and strength. **Charcoal Gray** is utilized for secondary information and iconography to maintain high legibility without the harshness of pure black.

**Luxury Gold (#D4AF37)** is our "surgical" accent. It must be used sparingly to highlight premium services, active states, or critical calls to action. It represents the "Gold Standard" of logistics.

**Background Strategy:** 
- Use **#FFFFFF** for primary content areas and cards to maximize contrast. 
- Use **#F8FAFC (Soft Gray)** for section backgrounds to create subtle visual separation and reduce eye strain in data-heavy enterprise environments.

## Typography
This design system employs a dual-font strategy. **Manrope** is used for headlines to provide a modern, slightly geometric, and tech-forward personality. **Inter** is used for all body copy and UI elements due to its exceptional legibility in professional, data-driven contexts.

**Scale & Rhythm:**
- Headlines utilize tighter letter-spacing to create a "locked" and authoritative appearance.
- Labels and Small Caps use increased letter-spacing (0.05em) to ensure clarity in navigation and status badges.
- Content-heavy sections should prioritize `body-md` for maximum readability.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for desktop to maintain a premium, editorial feel, while transitioning to a fluid model for mobile devices.

- **Grid:** A 12-column grid is used for desktop (1280px max-width). Components should align to these columns to maintain structural integrity.
- **Vertical Rhythm:** A strict 8px baseline grid ensures consistency across all components.
- **White Space:** Generous section gaps (120px+) are required to separate high-level service offerings, preventing the "cluttered" look common in traditional logistics websites.
- **Mobile:** Margins scale down to 16px, and complex 3-column service grids reflow into a single-column vertical stack.

## Elevation & Depth
In this design system, depth is communicated through **Tonal Layering** and **Micro-Shadows** rather than heavy gradients.

- **Surface Tiers:** Backgrounds are `Soft Gray`, while active content cards are `White`. This creates a natural "lift" without needing shadows.
- **The "B2B Shadow":** Use ultra-diffused shadows for interactive elements. (e.g., `box-shadow: 0 4px 20px rgba(15, 23, 42, 0.04)`). The goal is for the shadow to be felt, not seen.
- **Interactive Depth:** On hover, cards should subtly lift using a slightly more pronounced shadow and a 2px upward translation.
- **Glassmorphism:** Reserved exclusively for the **Sticky Navigation** bar. Use a 12px backdrop blur with a 90% opaque white background to maintain legibility while allowing content to flow underneath.

## Shapes
The shape language is **Soft (0.25rem / 4px)**. This choice strikes a balance between the "sharp" efficiency of the logistics industry and the "soft" approachability of modern B2B SaaS.

- **Buttons & Inputs:** Use the standard 4px radius.
- **Service Cards:** Use `rounded-lg` (8px) to create a distinct container feel.
- **Trust Badges:** May use `rounded-xl` (12px) or full pill-shapes to differentiate them from functional UI components.

## Components

### Buttons
- **Primary:** Solid Deep Navy background with White text. No border. On hover, background shifts to Secondary Gray.
- **Secondary:** Outlined with a 1.5px Deep Navy border. On hover, fills with a very faint (5%) Deep Navy tint.
- **CTA Sizing:** Use 16px padding (top/bottom) and 32px padding (left/right) for a substantial, premium feel.

### Premium Service Cards
- Background: White.
- Border: 1px Soft Gray.
- Iconography: 32px icons in Luxury Gold.
- Hover State: 2px slide-up animation with a 4px Gold bottom-border accent.

### Statistic Cards
- Typography: Large `display-lg` numbers in Deep Navy.
- Label: `label-md` in Charcoal Gray.
- Accent: A 24px vertical Luxury Gold line to the left of the text content.

### Floating WhatsApp
- Position: Bottom-right, 32px offset.
- Style: Circular Deep Navy button (not green, to maintain brand integrity) with a Gold icon. 
- Notification: A small "active" dot in Gold to draw attention non-intrusively.

### Form Fields
- Fields: 1.5px border in Soft Gray. 
- Focus State: Border color changes to Deep Navy. 
- Labels: Always visible, positioned above the field in `label-md`.

### Timelines & Process Workflows
- Line: 2px solid Soft Gray.
- Active Nodes: 12px solid Luxury Gold circles.
- Past Nodes: 12px solid Deep Navy circles with a white checkmark icon.