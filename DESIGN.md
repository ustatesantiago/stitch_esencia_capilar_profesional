---
name: Botanical Excellence
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#424843'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#737973'
  outline-variant: '#c2c8c2'
  surface-tint: '#4d6355'
  primary: '#051a0f'
  on-primary: '#ffffff'
  primary-container: '#1a2f23'
  on-primary-container: '#809787'
  inverse-primary: '#b4ccbb'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#221307'
  on-tertiary: '#ffffff'
  tertiary-container: '#382719'
  on-tertiary-container: '#a78d7a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d0e9d6'
  primary-fixed-dim: '#b4ccbb'
  on-primary-fixed: '#0a2014'
  on-primary-fixed-variant: '#364c3e'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#fbddc7'
  tertiary-fixed-dim: '#dec1ac'
  on-tertiary-fixed: '#28180b'
  on-tertiary-fixed-variant: '#574333'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style

The design system is rooted in the intersection of botanical science and high-end luxury. It targets a discerning audience that seeks professional-grade hair care with a natural soul. The aesthetic is **Modern Minimalist with Editorial influences**, prioritizing vast whitespace and structured layouts to evoke a sense of calm, trust, and premium quality.

The visual mood is aspirational yet grounded. It avoids the clinical coldness of traditional pharmaceuticals in favor of a warm, organic sophistication. Every element is designed to feel intentional, reflecting the meticulous formulation of the products themselves.

## Colors

The palette is derived directly from the forest floor and artisanal apothecary glass.

- **Primary (Forest Green):** A deep, scholarly green used for primary brand moments and high-contrast text. It represents the botanical heart of the brand.
- **Secondary (Harvest Gold):** A refined metallic tone used for highlights, calls to action, and premium accents. It reflects the luxury and high-performance results.
- **Tertiary (Deep Amber):** A rich, warm brown used for secondary containers and supporting elements, echoing the natural oils and product packaging.
- **Neutral (Bone):** A soft, off-white base that prevents the "starkness" of pure white, providing a warm and organic canvas for the layout.

Backgrounds should primarily use the Bone neutral, while text remains high-contrast in Forest Green or Deep Amber.

## Typography

This design system employs a classic serif/sans-serif pairing to balance tradition with modernity. 

**Libre Caslon Text** is used for headlines to provide an authoritative, editorial feel. Its high-contrast strokes convey luxury and history. 

**Manrope** serves as the functional workhorse for body copy and UI labels. Its geometric but warm construction ensures legibility and a contemporary, professional edge. Use wide letter-spacing on labels to create a sense of breathability and "boutique" styling.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop to maintain the integrity of white space and content density. 

- **Desktop:** 12-column grid with 64px outer margins. Use asymmetrical placements to create an editorial, high-fashion look.
- **Tablet:** 8-column grid with 32px margins. 
- **Mobile:** 4-column grid with 20px margins.

Spacing is generous. Group related items closely, but use large vertical gaps (80px+) between major sections to emphasize the premium nature of the brand. Horizontal alignment should be strict to maintain a professional, structured appearance.

## Elevation & Depth

To maintain a clean and modern aesthetic, depth is communicated through **Tonal Layers** rather than heavy shadows.

- **Surface Tiers:** Use subtle variations of the Neutral palette (e.g., a slightly darker cream or a very faint tint of Forest Green) to separate content sections.
- **Low-Contrast Outlines:** Use 1px solid borders in a desaturated version of the Secondary Gold or a light Taupe to define cards and input fields.
- **Soft Ambient Shadows:** Reserved only for floating elements like modals or dropdowns. These should be extremely diffused (20px+ blur) with a very low opacity (5-8%) using a tint of the Deep Amber color to keep them "warm."

## Shapes

The shape language is **Soft**. This design system avoids perfectly sharp corners to appear approachable, but also avoids overly rounded/pill shapes which can feel too casual or "techy."

- UI containers and buttons use a subtle 4px radius.
- Imagery should feature 0px or very small 4px corners to maintain a "gallery" or "editorial" aesthetic.
- Buttons should never be pill-shaped; they should remain rectangular with soft corners to maintain the professional, premium architectural feel.

## Components

- **Buttons:** Primary buttons use a solid Forest Green background with Bone text. Secondary buttons use a transparent background with a 1px Gold border. Use uppercase labels with increased letter spacing.
- **Input Fields:** Minimalist design with only a bottom border or a very faint 1px outline. Labels should be small and uppercase, placed above the field.
- **Cards:** Product cards should have no shadow; instead, use a 1px border or a slight tonal background shift. Product photography should be the hero.
- **Chips/Badges:** Used for ingredients or product benefits. Minimal styling: thin Forest Green outline with Manrope Bold text.
- **Lists:** Use custom icons for list bullets (e.g., a small gold botanical leaf) to reinforce brand identity.
- **Accordions:** Clean, hairline dividers between items. Use Caslon Serif for the accordion titles to maintain the editorial vibe even in functional areas like FAQs.