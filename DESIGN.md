---
name: Botanical Haute Cuisine
colors:
  surface: '#14130f'
  surface-dim: '#14130f'
  surface-bright: '#3a3934'
  surface-container-lowest: '#0f0e0a'
  surface-container-low: '#1c1c17'
  surface-container: '#20201b'
  surface-container-high: '#2b2a25'
  surface-container-highest: '#363530'
  on-surface: '#e6e2da'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e6e2da'
  inverse-on-surface: '#31302b'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#afceb9'
  on-secondary: '#1b3627'
  secondary-container: '#314d3d'
  on-secondary-container: '#9ebca8'
  tertiary: '#bed4c1'
  on-tertiary: '#233427'
  tertiary-container: '#a3b8a6'
  on-tertiary-container: '#37493b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#cbead5'
  secondary-fixed-dim: '#afceb9'
  on-secondary-fixed: '#052013'
  on-secondary-fixed-variant: '#314d3d'
  tertiary-fixed: '#d3e8d5'
  tertiary-fixed-dim: '#b7ccb9'
  on-tertiary-fixed: '#0e1f13'
  on-tertiary-fixed-variant: '#394b3d'
  background: '#14130f'
  on-background: '#e6e2da'
  surface-variant: '#363530'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 38px
    fontWeight: '600'
    lineHeight: 46px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 30px
    fontWeight: '500'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: 0em
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: 0em
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 17px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0.005em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.14em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.12em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
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
The design system establishes an intimate, sensory-forward narrative that evokes the quiet majesty of a conservatory dining room at twilight. Targeted at discerning epicures, international travelers, and celebratory diners, the experience must feel grounded yet distinctly elevated—balancing historic culinary reverence with architectural modernity.

The visual style synthesizes **Organic Luxury** and **Refined Glassmorphism**. Dark botanical backgrounds provide a low-light ambient theater where culinary photography and warm golden lighting take precedence. Subtle, frosted surfaces mimic moisture-kissed glass cloches, while metallic gold foil treatments punctuate interactive moments with crisp, tactile feedback. Spatial generosity, disciplined typographic tension, and velvet-deep tonal fields create an emotional state of anticipation, warmth, and unhurried decadence.

## Colors
The palette evokes botanical depth and candlelit luminescence across deep forest surfaces.

- **Primary (`#d4af37` - Golden Amber):** Reserved for focal calls to action, active navigation markers, reservation indicators, and luxury accents. It radiates with warmth, flanked by highlight gold (`#e5c058`) and pressed deep gold (`#b8972e`) for states and gradients.
- **Secondary (`#132e20` - Forest Emerald):** The foundational tone of structured UI containers, dropdown menus, and elevated cards, sitting immediately above the deeper canvas.
- **Tertiary (`#4a5d4e` - Muted Olive):** Applied to subtle structural dividers, inactive icon strokes, secondary tags, and delicate ingredient metadata.
- **Neutral (`#faf6ee` - Warm Rich Cream):** Provides radiant legibility against dark grounds. Used across primary typographic hierarchies, high-contrast labels, and illuminated pill states.

Background canvas tokens resolve to `#0c1f15` (Deep Twilight Forest), preserving visual depth and preventing stark OLED clipping. Primary body typography settles into warm muted cream `#f3ede0` on dark canvas, while inverted day-cards leverage charcoal text (`#1a201c`) on cream containers.

## Typography
Typographic rhythm relies on high-contrast pairing: romantic, editorial serif display headers coupled with precise, neutral geometric grotesques.

- **Editorial Headings (Playfair Display):** Conveys Michelin-caliber culinary pedigree. Used for section anchors, course names, tasting menu titles, and pull quotes. Italics should be applied sparingly to signature seasonal ingredients or sommelier pairings.
- **Functional Interface & Narrative (Plus Jakarta Sans):** Balances clarity with warmth. Modest x-height and open apertures guarantee micro-legibility inside dense reservation schedules, wine vintage lists, and ingredient sourcing breakdowns.
- **Eyebrows & Luxury Badges (Labels):** Must always be set in uppercase with tracked spacing (`0.12em` to `0.14em`) to impart an archival, tailored impression.

## Layout & Spacing
The layout relies on a 12-column responsive grid architecture designed for dramatic visual pacing, generous margins, and deliberate editorial breathing space.

- **Desktop (1200px+):** 12 columns, `1.5rem` gutters, and `4rem` outer margins. Hero compositions and tasting narratives utilize asymmetric column spans (e.g., 7 columns food imagery, 5 columns tasting notes with offset negative top margin).
- **Tablet (768px - 1199px):** 8 columns, `1.25rem` gutters, and `2rem` outer margins. Content groups collapse to alternating 4-column cards or full 8-column culinary showcases.
- **Mobile (< 768px):** 4 columns, `1rem` gutters, and `1.25rem` outer canvas boundaries. Stacked single-column layouts dominate, preserving generous vertical flow (`space-xl` between modular sections) to prevent a cluttered dining guide aesthetic.

## Elevation & Depth
Depth is constructed through atmospheric physical layering rather than synthetic high-drop shadows.

- **Canvas Foundation:** Base level `#0c1f15` provides deep field tone.
- **Surface Layer 1 (Cards & Side Panels):** Semi-translucent `#132e20` blended with `85%` opacity, reinforced with an inner stroke of `1px solid rgba(212, 175, 55, 0.12)` and a soft ambient shadow (`0 20px 40px rgba(4, 10, 7, 0.45)`).
- **Surface Layer 2 (Frosted Modals & Floating Navigation):** Tactile frosted glassmorphism utilizing `rgba(19, 46, 32, 0.65)` layered over `backdrop-filter: blur(16px) saturate(140%)`, wrapped with a delicate perimeter border `1px solid rgba(250, 246, 238, 0.15)`.
- **Gold Foil Accents:** Interactive elements feature a warm golden specular glow (`box-shadow: 0 4px 20px rgba(212, 175, 55, 0.25)`) that intensifies on cursor hover to mimic polished metallic luster under candlelight.

## Shapes
A disciplined **Soft (`1`)** shape geometry conveys architectural craftsmanship. Base interactive elements use `0.25rem` (4px) radii, retaining crisp corner discipline. Substantial surfaces such as wine collection showcases, course cards, and dialog modals utilize `rounded-lg` (`0.5rem` / 8px). 

Circular treatments are strictly preserved for editorial circular stamps, sommelier signature badges, and carousel step indicators. Avoid bubbly or excessive border curves to safeguard the refined haute-cuisine atmosphere.

## Components

### Buttons & CTAs
- **Primary Foil CTA ("Reserve a Table"):** Features a linear metallic gold gradient background (`linear-gradient(135deg, #e5c058 0%, #d4af37 50%, #b8972e 100%)`) with deep charcoal text (`#1a201c`), bold weight, and a subtle inner top bevel (`inset 0 1px 1px rgba(255, 255, 255, 0.4)`). Hover states elevate with an ambient amber bloom.
- **Secondary Ghost Button ("View Degustation"):** Transparent fill framed by a crisp border (`1px solid rgba(212, 175, 55, 0.6)`), warm cream typography, and transitions to a rich forest emerald fill on hover.

### Culinary Cards
- Built using dark forest emerald containers with a `0.5rem` radius. Photography sits bleed-edge at the top or left, paired with an integrated dark gradient overlay that fades into the container background. Dish descriptions employ `body-md` in cream tone `#f3ede0`, accompanied by prices formatted in Playfair Display italic gold.

### Dietary & Vintage Chips
- Compact, low-profile pill capsules (`rounded-xl`) set in semi-transparent olive (`rgba(74, 93, 78, 0.25)`) with an ultra-fine border (`1px solid rgba(212, 175, 55, 0.2)`). Text is rendered in uppercase `label-sm` cream typography. Active dietary filters switch to gold borders with gold text.

### Form Inputs & Date Selectors
- Flat dark surfaces (`#0c1f15`) with a `1px` subtle outline of `#4a5d4e`. Focus triggers an amber border transition (`#d4af37`) and an ultra-subtle golden ambient ring. Input text displays in warm cream, with placeholders toned down in muted olive.

### Lists & Degustation Progressions
- Menu listings utilize full-width rows divided by hairline rules (`rgba(74, 93, 78, 0.35)`). Course titles (Serif) align left, accompanied by dot leaders in gold opacity or generous whitespace, resolving into price and pairing selections aligned right.