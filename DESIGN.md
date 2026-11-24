---
name: Warm Luxury Hospitality
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#4e453f'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#80756f'
  outline-variant: '#d1c4bc'
  surface-tint: '#6a5b51'
  primary: '#110804'
  on-primary: '#ffffff'
  primary-container: '#2a1f17'
  on-primary-container: '#96857a'
  inverse-primary: '#d6c3b6'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#0f0900'
  on-tertiary: '#ffffff'
  tertiary-container: '#2c1f00'
  on-tertiary-container: '#aa8306'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f3dfd2'
  primary-fixed-dim: '#d6c3b6'
  on-primary-fixed: '#241912'
  on-primary-fixed-variant: '#52443b'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#ffdf98'
  tertiary-fixed-dim: '#eec14b'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#5a4300'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 38px
    fontWeight: '600'
    lineHeight: 46px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 26px
    fontWeight: '500'
    lineHeight: 34px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.08em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.1em
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
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style
The design system delivers an elevated sensory experience inspired by fine dining, intimate candlelight, and bespoke hospitality. It caters to discerning patrons seeking refined culinary craftsmanship and effortless digital reservation workflows.

The visual direction pairs **Editorial Warm Luxury** with **Modern Tactile Restraint**:
- Atmospheric depth generated through rich, roasted espresso tones and delicate, warm cream backdrops.
- Precision metallic accents reminiscent of gold leafing, architectural brass, and polished tableware.
- Subtle luxury cues—such as hairline borders, generous negative space, and luminous warm-spectrum blurs—evoke quiet confidence rather than ostentation.
- Smooth, micro-calibrated transitions simulate tactile weight and friction, reminiscent of fine linen and heavyweight menu cardstock.

## Colors
The palette balances deeply roasted foundational darks against luminous, culinary-inspired creams and metallic gold highlights.

- **Primary (`#2A1F17` / Espresso Noir):** Anchors primary actions, high-contrast headings, and foundational surfaces in inverse/evening views.
- **Secondary (`#D4AF37` / Imperial Gold):** Reserved for focal moments, selected states, premium badges, and delicate metallic accents.
- **Tertiary (`#C59B27` / Aged Amber):** Provides interactive depth, pressed button states, and rich contextual highlights.
- **Neutral Canvas (`#FDFBF7` / Porcelain Cream):** Replaces harsh optic white with a soft, warm paper tone that eliminates eye fatigue and conveys tactile warmth.
- **Support Tones:** Soft taupe (`#E8E0D5`) for subtle architectural borders; muted charcoal brown (`#1C140E`) for deep shadow anchors and night-menu treatments.

## Typography
Typographic rhythm sets the tempo of the dining journey. High-contrast transitional serifs provide literary drama for storytelling, dish titles, and editorial showcases, while an engineered geometric grotesque delivers pristine legibility across scheduling grids, pricing tiers, and reservation flows.

- **Display & Headlines:** Set in **Playfair Display**. Characterized by sculpted serifs and high stroke contrast. All large display tokens use tighter negative letter spacing to preserve visual cadence.
- **Body & UI Elements:** Set in **Plus Jakarta Sans**. Ensures frictionless legibility at compact sizes within ingredient lists, cellar notes, and form inputs.
- **Labels & Microcopy:** Rendered with tracked uppercase styling (`letterSpacing: 0.06em` to `0.1em`) to create an authentic engraved menu appearance.

## Layout & Spacing
A rhythmic, editorial layout system engineered for balanced pacing:

- **Desktop (1024px+):** 12-column responsive fluid grid anchored by a maximum content container of 1320px. Generous `3rem` canvas margins mimic high-end publication margins.
- **Tablet (768px - 1023px):** 8-column grid with `1.5rem` gutters, enabling tasting flight cards and course menus to sit comfortably side by side.
- **Mobile (<768px):** 4-column fluid layout with snug `1rem` gutters and `1.25rem` margins, collapsing complex split columns into vertically stacked narratives.
- **Vertical Spacing:** Section transitions rely on rhythmic multiples of `space-xl` (48px) and double-xl intervals (96px) to emulate uncluttered, quiet spaces.

## Elevation & Depth
Depth is created through ambient warmth and luminous proximity rather than cold greyscale drop shadows:

- **Candlelight Diffuse Glow:** Drop shadows are infused with amber undertones (`rgba(42, 31, 23, 0.08)` to `rgba(212, 175, 55, 0.12)`). Blur radii are expansive (up to 32px) with minimal displacement, recreating soft candlelight cast on textured linen.
- **Low-Contrast Hairlines:** Elevation boundaries and card surfaces employ a delicate `1px` border with gold-tinted taupe (`rgba(212, 175, 55, 0.25)` or `rgba(42, 31, 23, 0.08)`), reducing visual clutter.
- **Tiered Overlays:** Modal reservations, wine lists, and bottom sheets leverage a frosted surface treatment: semi-translucent warm cream (`rgba(253, 251, 247, 0.94)`) combined with a soft backdrop blur (12px) to keep the cellar or dining room imagery subtly visible underneath.

## Shapes
A tailored architectural curvature brings modernity while respecting classical refinement:

- **Base Radius (`rounded`, 0.5rem / 8px):** Applied to interactive buttons, field inputs, and pill metadata tags to soften corners without feeling overly informal.
- **Container Radius (`rounded-lg`, 1rem / 16px):** Standard across food item cards, reservation calendar blocks, and visual showcases.
- **Specialty Radius (`rounded-xl`, 1.5rem / 24px):** Reserved for floating dialogs, full-course modal overlays, and signature dish hero frames.
- **Geometry Rules:** Circular silhouettes (`border-radius: 9999px`) are exclusively used for avatar frames, date pickers, and round icon badges.

## Components

### Buttons & Interactive Controls
- **Primary Action (Reserve, Confirm):** Deep espresso background (`#2A1F17`) with porcelain white typography and a subtle amber perimeter border. On hover, transitions smoothly to a warm burnished tone with an amber-tinted shadow glow.
- **Secondary Action (Wine Pairing, Private Dining):** Transparent fill framed by a crisp `1px` gold accent border (`#D4AF37`), displaying deep espresso text that transitions to a delicate gold wash background upon hover.
- **Tertiary / Text Link:** Uppercase tracked `label-md` accompanied by an animating underline that expands outward from center.

### Cards & Menu Showcases
- **Tasting Menu Cards:** Porcelain cream surface (`#FDFBF7`) framed by a subtle border (`#E8E0D5`) with an interior padding of `space-lg`. Features an integrated pricing label top-aligned with the course title.
- **Chef's Selection / Featured Item:** Accented with an interior 1px gold foil stroke (`rgba(212, 175, 55, 0.4)`) and a delicate label badge positioned at the card header.

### Chips & Filters
- Compact pill-shaped elements for dietary filters (e.g., Vegan, Cellar Reserve, Gluten-Free). Inactive chips feature an outline border; active states fill with rich espresso (`#2A1F17`) paired with crisp white text.

### Form Inputs & Reservation Flow
- Text inputs and date pickers use a soft ivory fill (`#F5EFEB`) and a subtle lower-border accent. Focus states activate a radiant imperial gold border (`#D4AF37`) accompanied by a gentle candlelight halo.

### Selection Controls (Checkboxes & Radios)
- Radios and checkboxes feature delicate metallic accents. When checked, the inner core illuminates in solid `#D4AF37` wrapped by an espresso boundary.

### Micro-Interactions
- All hover states engage an ease-out timing curve (240ms `cubic-bezier(0.16, 1, 0.3, 1)`), evoking the deliberate grace of five-star table service.