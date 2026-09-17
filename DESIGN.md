---
name: Serene Dignity
colors:
  surface: '#f8f9ff'
  surface-dim: '#d0dbed'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dee9fc'
  surface-container-highest: '#d9e3f6'
  on-surface: '#121c2a'
  on-surface-variant: '#43474e'
  inverse-surface: '#27313f'
  inverse-on-surface: '#eaf1ff'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#465f86'
  primary: '#032448'
  on-primary: '#ffffff'
  primary-container: '#1f3a5f'
  on-primary-container: '#8ba4cf'
  inverse-primary: '#aec8f4'
  secondary: '#585f6c'
  on-secondary: '#ffffff'
  secondary-container: '#dce2f3'
  on-secondary-container: '#5e6572'
  tertiary: '#302200'
  on-tertiary: '#ffffff'
  tertiary-container: '#4b3601'
  on-tertiary-container: '#be9f61'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#aec8f4'
  on-primary-fixed: '#001c3b'
  on-primary-fixed-variant: '#2d476d'
  secondary-fixed: '#dce2f3'
  secondary-fixed-dim: '#c0c7d6'
  on-secondary-fixed: '#151c27'
  on-secondary-fixed-variant: '#404754'
  tertiary-fixed: '#ffdf9f'
  tertiary-fixed-dim: '#e3c281'
  on-tertiary-fixed: '#261a00'
  on-tertiary-fixed-variant: '#5a430e'
  background: '#f8f9ff'
  on-background: '#121c2a'
  surface-variant: '#d9e3f6'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 68px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  display-md:
    fontFamily: Playfair Display
    fontSize: 44px
    fontWeight: '600'
    lineHeight: 54px
    letterSpacing: -0.015em
  display-md-mobile:
    fontFamily: Playfair Display
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-xl:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.03em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style

This design system embodies compassionate elegance, quiet authority, and timeless grace. It is tailored for families and individuals navigating moments of loss, pre-planning arrangements, or honoring a loved one's legacy. The interface balances high-end editorial sophistication with profound emotional sensitivity.

The design movement blends **Warm Minimalism** with **Editorial Classicalism**. Every element prioritizes emotional ease:
- Ample negative space to avoid cognitive overload during grief.
- Warm, grounded surfaces that feel reassuring rather than sterile or cold.
- Understated golden radiance to convey honor, reverence, and enduring value.
- Reassuring micro-interactions that operate gently without sudden flashes, aggressive alerts, or abrupt transitions.

## Colors

The palette is rooted in solemnity, warmth, and quiet prestige. 

- **Primary (`#1F3A5F`)**: Deep Navy Blue provides structural authority, steadfast presence, and enduring security. Used for critical navigation headers, primary actions, and commanding titles.
- **Secondary (`#6B7280`)**: Soft Slate Gray delivers neutral balance, low-pressure metadata, and calm supportive copy.
- **Accent / Tertiary (`#C8A96A`)**: Soft Antique Gold introduces warmth, honor, and reverent polish. Applied strictly for subtle borders, active stepper highlights, delicate badges, and premium tier distinctions.
- **Neutral (`#1F2937`)**: Deep Charcoal ensures effortless, high-contrast readability without the stark severity of pure `#000000`.
- **Canvas & Surface**: An ivory-tinted Off-White (`#F8F9FA`) grounds the background canvas, while Elevated Cards leverage Pure White (`#FFFFFF`) to maintain luminous clarity. Borders utilize muted warm gray (`#E5E7EB`) infused with soft gold-tinted outlines (`rgba(200, 169, 106, 0.2)`).

## Typography

The typography couples the classical grace of **Playfair Display** with the functional clarity of **Inter**.

- **Headlines & Editorial Statements**: Playfair Display delivers emotional gravity, dignity, and warmth. Tight tracking on large display headings brings an artisanal, book-bound editorial quality.
- **Body & Functional UI**: Inter ensures fatigue-free reading across all form factors. Generous line heights (`1.5` to `1.6`) ensure scanning remains effortless and soothing, accommodating users under emotional duress.
- **Labels & Numbers**: Uppercase tracking is used sparingly on micro-labels (service codes, pricing frequencies, date tags) with moderate kerning (`0.03em` - `0.04em`) to project intentional craftsmanship.

## Layout & Spacing

A 12-column responsive grid underpins all desktop templates, collapsing cleanly into 6 columns on tablet and a single-column stacked flow on mobile screens. Maximum content width is restrained to `1200px` for editorial balance and intimate reading widths.

- **Desktop (>= 1024px)**: Generous 48px (`3rem`) outer margins and 24px (`1.5rem`) gutters ensure a relaxed canvas. Multi-step forms and pricing matrices sit centered with dedicated side breathing room.
- **Tablet (768px - 1023px)**: 32px (`2rem`) margins maintain safe separation; cards shift to 2-column groupings.
- **Mobile (< 768px)**: Margins compress to 20px (`1.25rem`) with 16px (`1rem`) gutters. Complex pricing cards decouple into swipeable or stacked flows with full-width primary contact actions pinned gracefully to reach zones.
- **Vertical Spacing Rhythm**: Section intervals use spacious paddings (`space-xl` and above) to evoke quiet stillness between topical sections.

## Elevation & Depth

Visual depth avoids cold, modern dropped shadows in favor of soft, natural illumination reminiscent of morning daylight:

- **Ambient Light Shadows**: Shadows use low-opacity, warm amber/navy undertones rather than stark black: `box-shadow: 0 10px 30px -5px rgba(31, 58, 95, 0.05), 0 4px 12px -2px rgba(200, 169, 106, 0.04)`.
- **Low-Contrast Perimeter**: Every elevated card pairs its soft ambient shadow with a delicate, continuous border: `1px solid #E5E7EB` or `1px solid rgba(200, 169, 106, 0.25)`.
- **Selected & Tier States**: Emphasized pricing plans or active step cards gain an ambient golden halo: `0 12px 36px -4px rgba(200, 169, 106, 0.18)` coupled with an accent border.
- **Floating Overlays & Helplines**: Modals and persistent urgent care headers maintain crisp definition via semi-translucent backdrop blur (`backdrop-filter: blur(12px)`) over an ivory scrim.

## Shapes

The shape vocabulary uses welcoming, organic curves (`Level 2: Rounded`) to soften the emotional atmosphere:

- **Standard Containers & Cards**: Base cards use `rounded-xl` (`1rem`) and `rounded-2xl` (`1.5rem`), softening harsh rectilinear corners and inviting physical comfort.
- **Input Fields & Form Elements**: Form text boxes, select dropdowns, and date pickers feature `rounded-md` (`0.5rem`) to maintain precision and structure without rigid angles.
- **Buttons & Chips**: Interactive action points use refined `rounded-lg` (`0.75rem`) or gentle pill shapes for badges and helpline links to preserve an inviting, approachable touch.

## Components

### Navigation & Emergency Helpline Header
- Persistent, dignified top bar featuring a prominent 24/7 care helpline (`tel:` link styled with a subtle gold phone icon).
- Transparent navigation bar on scroll that transitions into an ivory blurred panel (`rgba(248, 249, 250, 0.9)`).
- Clean typographic links with subtle under-line transitions in gold.

### Buttons
- **Primary Button**: Deep Navy background (`#1F3A5F`), white Inter typography, gold focus rings. Mild hover shift to a deeper midnight shade (`#162A45`) with smooth 200ms ease.
- **Secondary Button**: Crisp white background, charcoal label, and a refined border of muted gold (`rgba(200, 169, 106, 0.5)`).
- **Subtle / Text Button**: Understated navy or soft gray text with a quiet gold-underline state for reverent, low-priority exploration.

### Pricing Cards
- Structured 3-tier card layouts (e.g., Simple Farewell, Traditional Service, Bespoke Legacy).
- Most Popular / Recommended tier sits prominently elevated with an elegant gold badge atop the card border, accompanied by a faint warm aura (`rgba(200, 169, 106, 0.15)`).
- Included services listed with delicate golden checkmarks; excluded or optional services displayed in soft gray.

### Multi-Step Booking & Arrangement Stepper
- Horizontal progress trail connected by hair-thin tracks (`#E5E7EB`).
- Completed and active steps are signaled via soft gold numbered medallions (`#C8A96A`) with gentle glowing outer bands; upcoming steps remain muted slate gray.
- Step transitions slide smoothly with fading opacity to eliminate sudden layout flashes.

### Memorial & Tribute Cards
- Portrait aspect ratios featuring soft rounded corners (`rounded-xl`).
- High-fidelity portraiture framed by thin gold-tint hairline boundaries.
- Dedicated space for lifespan dates, loving quotes set in italicized *Playfair Display*, and a tranquil candle/floral homage icon.

### Form Inputs & Selectors
- Calm white input fields with `#E5E7EB` borders that shift to soft gold glow (`#C8A96A`) upon focus.
- Generous internal padding (`14px 16px`) for comfortable touch targets and serene, unhurried interactions.