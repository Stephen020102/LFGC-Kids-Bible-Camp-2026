---
name: Luminous Grace
colors:
  surface: '#fef7ff'
  surface-dim: '#e1d6e9'
  surface-bright: '#fef7ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#faf0ff'
  surface-container: '#f5eafd'
  surface-container-high: '#efe4f7'
  surface-container-highest: '#eadef2'
  on-surface: '#1f1926'
  on-surface-variant: '#494454'
  inverse-surface: '#342e3c'
  inverse-on-surface: '#f8edff'
  outline: '#7b7486'
  outline-variant: '#cbc3d7'
  surface-tint: '#6d3bd7'
  primary: '#6b38d4'
  on-primary: '#ffffff'
  primary-container: '#8455ef'
  on-primary-container: '#fffbff'
  inverse-primary: '#d0bcff'
  secondary: '#6f5092'
  on-secondary: '#ffffff'
  secondary-container: '#d9b5ff'
  on-secondary-container: '#614283'
  tertiary: '#5b5b65'
  on-tertiary: '#ffffff'
  tertiary-container: '#74747e'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#d0bcff'
  on-primary-fixed: '#23005c'
  on-primary-fixed-variant: '#5516be'
  secondary-fixed: '#efdbff'
  secondary-fixed-dim: '#dbb8ff'
  on-secondary-fixed: '#29074a'
  on-secondary-fixed-variant: '#573878'
  tertiary-fixed: '#e3e1ed'
  tertiary-fixed-dim: '#c7c5d1'
  on-tertiary-fixed: '#1a1b23'
  on-tertiary-fixed-variant: '#46464f'
  background: '#fef7ff'
  on-background: '#1f1926'
  surface-variant: '#eadef2'
typography:
  display-xl:
    fontFamily: Montserrat
    fontSize: 84px
    fontWeight: '800'
    lineHeight: 92px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: 0.05em
  headline-md:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-page: 64px
  section-gap: 120px
---

## Brand & Style

This design system is defined by an atmosphere of "Ethereal Radiance." It reimagines the high-production, cinematic aesthetic of a modern worship conference through a lens of light and air. The brand personality is transcendent yet accessible, moving away from heavy, dark-mode solemnity toward a luminous, morning-light spirituality.

The visual style blends **Glassmorphism** with **Minimalism**. It utilizes semi-transparent white layers over soft lavender gradients to create depth without weight. The "VESPER" heritage is preserved through wide-tracked, uppercase typography and high-contrast editorial layouts, but the emotional response is shifted toward hope, clarity, and openness.

## Colors

The palette is anchored by a "Vibrant Amethyst" primary color that provides energy and focal points. The background is a "Soft Mist" lavender-white, providing a luminous surface that feels breathable. 

- **Primary:** A vivid, saturated purple used for call-to-action elements and brand identifiers.
- **Secondary:** A soft, mid-tone lavender used for accents and subtle button states.
- **Surface/Tertiary:** A very pale purple-tinted white used for card backgrounds and elevated containers.
- **Neutrals:** Deep violet-grays are used for text to maintain legibility while ensuring the palette feels cohesive and avoids harsh blacks.

## Typography

This design system relies exclusively on **Montserrat** to maintain a clean, geometric, and modern conference aesthetic. 

Headlines should be used aggressively. Large display text should have slight negative tracking for a cinematic feel, while secondary headlines should utilize wide tracking and uppercase transformations to mirror the established "VESPER" branding. Body text is kept spacious with generous line-heights to support the airy aesthetic of the design system.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model to ensure the "elegant conference" structure remains intact across desktop displays. A 12-column grid is used with wide gutters to prevent content from feeling crowded.

Spacing is intentionally oversized. Large vertical gaps (section-gaps) are used to separate content blocks, creating a sense of "rhythm and pause" that feels spiritual and unhurried. Padding within containers should be generous to maintain the luminous, airy feel.

## Elevation & Depth

Depth in this design system is achieved through **Luminous Layering** rather than traditional shadows. 

- **Backdrop Blurs:** Use high-diffusion (20px-40px) background blurs on semi-transparent white surfaces (Opacity: 70-80%) to create a frosted glass effect.
- **Glow Shadows:** Instead of black or gray shadows, use soft, low-opacity purple shadows (`rgba(139, 92, 246, 0.15)`) with a large spread to make elements appear as if they are floating on a bed of light.
- **Inner Glows:** Subtle 1px white inner borders help define the edges of glass elements against the lavender-white backgrounds.

## Shapes

The shape language is consistently **Rounded**, avoiding sharp corners to maintain a soft and welcoming presence. Standard components use a 0.5rem radius, while larger cards and modal containers should use the 1.5rem (rounded-xl) setting to emphasize a modern, premium feel. 

Iconography should follow this trend, utilizing "Filled" styles with rounded terminals to match the geometric nature of the Montserrat typeface.

## Components

- **Buttons:** Primary buttons use a vibrant purple-to-lavender gradient with white text. Secondary buttons should be "Glass Action" style—semi-transparent white with a thin purple stroke.
- **Cards:** Use "Aura Cards"—white backgrounds at 60% opacity with a 32px backdrop blur and a very soft purple outer glow.
- **Chips/Tags:** Small, pill-shaped elements with light purple backgrounds and high-contrast deep purple text for categorization.
- **Inputs:** Minimalist fields with a soft lavender bottom border. Upon focus, the border transforms into a vibrant purple glow.
- **Lists:** Clean, borderless rows separated by subtle lavender-tinted dividers or increased whitespace.
- **Navigation:** A floating "Glass Header" that remains fixed at the top, blurring the content beneath it to maintain the cinematic depth.
- **Hero Sections:** Incorporate soft, out-of-focus purple light orbs (bokeh) in the background to reinforce the airy, spiritual theme.