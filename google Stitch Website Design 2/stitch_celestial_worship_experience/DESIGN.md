---
name: Arid Cinematic Expedition
colors:
  surface: '#fff9ed'
  surface-dim: '#e2dabf'
  surface-bright: '#fff9ed'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fcf3d8'
  surface-container: '#f7eed2'
  surface-container-high: '#f1e8cd'
  surface-container-highest: '#ebe2c8'
  on-surface: '#1f1c0b'
  on-surface-variant: '#544437'
  inverse-surface: '#35301e'
  inverse-on-surface: '#faf0d5'
  outline: '#877366'
  outline-variant: '#dac2b2'
  surface-tint: '#904d00'
  primary: '#904d00'
  on-primary: '#ffffff'
  primary-container: '#d27d2d'
  on-primary-container: '#452200'
  inverse-primary: '#ffb77d'
  secondary: '#934b19'
  on-secondary: '#ffffff'
  secondary-container: '#ffa26a'
  on-secondary-container: '#783603'
  tertiary: '#765a05'
  on-tertiary: '#ffffff'
  tertiary-container: '#ae8e3a'
  on-tertiary-container: '#372900'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc3'
  primary-fixed-dim: '#ffb77d'
  on-primary-fixed: '#2f1500'
  on-primary-fixed-variant: '#6e3900'
  secondary-fixed: '#ffdbc9'
  secondary-fixed-dim: '#ffb68c'
  on-secondary-fixed: '#321200'
  on-secondary-fixed-variant: '#753401'
  tertiary-fixed: '#ffdf96'
  tertiary-fixed-dim: '#e7c268'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#5a4400'
  background: '#fff9ed'
  on-background: '#1f1c0b'
  surface-variant: '#ebe2c8'
typography:
  display-lg:
    fontFamily: Quicksand
    fontSize: 48px
    fontWeight: '300'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Quicksand
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Quicksand
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  body-md:
    fontFamily: Quicksand
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Quicksand
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1280px
---

## Brand & Style

The design system evokes the expansive, awe-inspiring scale of a desert landscape at dusk. It balances an **approachable, human-centric friendliness** with a **cinematic, high-production atmosphere**. The aesthetic is a sophisticated blend of **Minimalism** and **Tactile/Skeuomorphic** influences, using soft lighting and depth to create a sense of physical space and warmth.

The target audience seeks adventure but values comfort and clarity. The UI should feel like a premium travel journal or a high-end outdoor gear interface: rugged yet refined, optimistic yet grounded. Every interaction should feel soft and intentional, avoiding the harshness of traditional digital interfaces in favor of "sun-drenched" surfaces and organic flow.

## Colors

The palette is rooted in the natural gradients of geological formations. 

- **Primary (Rich Ochre):** Used for key actions and focal points, representing the glow of the sun on sandstone.
- **Secondary (Terracotta):** A deeper, earthy tone used for structural accents and secondary buttons to provide contrast without breaking the warm harmony.
- **Surface (Warm Sand):** The background is not white, but a soft, desaturated sandy beige (#F4EBD0), reducing eye strain and reinforcing the organic theme.
- **Accents:** Darker, "burnt" yellows are used for status indicators and icons to maintain the monochromatic depth.

Avoid pure blacks; use deep charcoal with a brown tint for text to maintain the cinematic softness.

## Typography

This design system exclusively utilizes **Quicksand** to reinforce its approachable and optimistic personality. To achieve a "cinematic" feel with such a friendly font, we utilize contrasting weights and generous letter spacing.

- **Display text** should use Light (300) or Regular (400) weights with slight negative tracking to feel modern and expansive.
- **Headlines** utilize Medium (500) weights to ensure hierarchy against the warm background.
- **Labels** are often uppercase with increased letter spacing to provide a "navigational" or "instrumental" look, reminiscent of luxury watch faces or compasses.

## Layout & Spacing

The layout philosophy is **Expansive and Fluid**. We utilize a 12-column grid that emphasizes horizontal breathing room, mimicking the horizon line of a desert.

- **Margins:** Desktop margins are deliberately large (64px) to center the focus and create a "gallery" effect.
- **Vertical Rhythm:** A strict 8px baseline grid ensures consistency, but section padding is generous (80px+) to prevent the UI from feeling cluttered.
- **Mobile Adaption:** On mobile, margins shrink to 16px, and components stack into a single column, relying on large image headers to maintain the cinematic scale.

## Elevation & Depth

Visual hierarchy is achieved through **Ambient Shadows** and **Tonal Layers**. Instead of harsh grey shadows, this design system uses "sun-cast shadows"—soft, diffused shadows with a warm, low-opacity terracotta tint.

- **Surface Levels:** Lower levels are slightly more saturated sandy tones, while "elevated" cards are lighter, almost cream-colored, appearing to catch more light.
- **Inner Glows:** To create a tactile, "squishy" or molded effect, buttons and input fields may use a very subtle inner shadow (1-2px) to look as if they are embossed into the sand-like surface.
- **Backdrop Blurs:** High-level modals use a soft frost effect (glassmorphism) that carries the warm background color through, maintaining the "golden hour" glow.

## Shapes

The shape language is consistently **Rounded**, echoing the geometry of wind-swept dunes and the Quicksand typeface.

- **Cards and Containers:** Use a 16px (1rem) radius for a soft, approachable structure.
- **Interactive Elements:** Buttons and tags utilize a **Pill-shaped** (32px+) radius to maximize the "friendly" aesthetic and make them feel distinct from structural containers.
- **Input Fields:** Use the same roundedness as cards to feel integrated into the "ground" of the interface.

## Components

### Buttons
Primary buttons are rich Ochre with white or deep-brown text. They should feel high-contrast and slightly tactile. Secondary buttons use an "Outlined" style with a 2px Terracotta border, emphasizing the cinematic, technical feel.

### Cards
Cards are the primary vehicle for "Cinematic" content. They should feature large, edge-to-edge imagery with typography overlaid using a gradient scrim (fading from transparent to deep brown) to ensure legibility.

### Chips & Tags
Used for categorization, these are small pill-shaped elements with a light Terracotta background and dark brown text.

### Input Fields
Inputs are "Warm Sand" with a slightly darker border. On focus, the border transitions to the Primary Ochre with a soft, glowing outer shadow to indicate the "sunlight" hitting the active field.

### Lists
Lists use horizontal dividers that are very subtle (5% opacity Terracotta) to maintain a clean, uninterrupted look. Iconography within lists should be thin-stroke and rounded.