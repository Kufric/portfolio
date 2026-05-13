---
name: Anti-System Portfolio
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#ccc3d3'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#968e9c'
  outline-variant: '#4a4451'
  surface-tint: '#d7baff'
  primary: '#d7baff'
  on-primary: '#411478'
  primary-container: '#bd93f9'
  on-primary-container: '#4e2484'
  inverse-primary: '#714aaa'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#474746'
  on-secondary-container: '#b7b5b4'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#a6a7a7'
  on-tertiary-container: '#3b3d3d'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#eddcff'
  primary-fixed-dim: '#d7baff'
  on-primary-fixed: '#290055'
  on-primary-fixed-variant: '#593090'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-xl:
    fontFamily: Anton
    fontSize: 120px
    fontWeight: '400'
    lineHeight: 110px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Anton
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 60px
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 44px
  headline-md:
    fontFamily: Anton
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 32px
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Space Mono
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  stack-sm: 8px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style
This design system is built on a foundation of **Aggressive Brutalism** mixed with **Grunge Street-Art** aesthetics. It is designed for creators who reject the polished, corporate "clean" look in favor of something raw, disruptive, and high-energy. The mood is unapologetic, underground, and loud.

Visual hallmarks include:
- **Raw Textures:** Heavy use of grain, noise overlays, and digital "glitch" artifacts.
- **High-Contrast Impact:** A pitch-black void contrasted against a singular, electrifying lavender.
- **Urban Utility:** Structural elements that feel like wheat-paste posters or stenciled street markings.
- **Disruption:** Intentional use of overlapping elements and "broken" grid moments to create tension and visual interest.

## Colors
The palette is dominated by **#050505 (Pure Dark)** to provide a deep, immersive background. The primary accent is a **Vibrant Lavender (#BD93F9)**, which replaces the previous coral. This lavender is used specifically for high-priority calls to action, highlights, and "spray-paint" style accents.

Secondary surfaces use a slightly lighter charcoal (#1A1A1A) to provide subtle separation. Typography is primarily White (#FFFFFF) for maximum legibility, with the Lavender reserved for emphasis and interactive states. A lighter shade of lavender (#D6BCFA) is used for subtle gradients or soft glows behind elements to simulate neon tube lighting on a dark street.

## Typography
The typographic voice is dominated by **Anton**, a heavy, condensed sans-serif that demands immediate attention. It must be used in all caps for headlines to maintain the street-poster aesthetic.

For technical clarity and balance, **Space Grotesk** is used for body copy, providing a modern, slightly geometric feel that complements the "anti-system" vibe. **Space Mono** is utilized for labels, metadata, and "system" information (like timestamps or tags), reinforcing a technical, underground hacker aesthetic. Headlines should often utilize tight tracking and leading to create dense "blocks" of text.

## Layout & Spacing
This system uses a **Fixed-Fluid Hybrid Grid**. On desktop, content is contained within a 12-column grid with wide 64px margins to create a focused, editorial look. On mobile, margins drop to 16px to maximize screen real estate.

Spacing follows a strict 4px base unit, but the implementation is intentionally "tight." Gutters are generous (24px) to allow individual pieces of content to breathe against the dark background. Elements should often be "stacked" vertically with minimal vertical padding to create a sense of density and urgency, similar to a social media feed or a wall of flyers.

## Elevation & Depth
In this system, depth is not created with shadows, but through **Tonal Layering and Hard Borders**.

- **Z-Axis:** Instead of soft shadows, use 1px or 2px solid Lavender borders to "lift" an element.
- **Backgrounds:** Use a "Grain" texture overlay (5-10% opacity) across the entire UI to kill the digital perfection of the black background.
- **Glassmorphism:** Reserved exclusively for navigation bars and overlays. Use a heavy backdrop-blur (20px) with a dark, semi-transparent lavender tint to create a "smoke and neon" effect.
- **Offset Strokes:** Create a "stencil" effect by duplicating a text layer or box and offsetting the stroke by 4px to the bottom-right.

## Shapes
The shape language is strictly **Sharp (0px)**. Roundness is perceived as "friendly" and "safe," which contradicts the brand narrative. Every button, card, and input field must have hard 90-degree angles.

Diagonal cuts (chamfers) are permitted on large containers or decorative elements to mimic industrial hardware or architectural "anti-design." Media containers (images/videos) should always be hard-edged with no corner masking.

## Components
- **Buttons:** Large, blocky, and filled with Vibrant Lavender. Text is Anton, All-Caps, in Black. On hover, the button should invert (Black background, Lavender border and text).
- **Chips/Tags:** Space Mono text inside a 1px Lavender border. No background fill unless the tag is "Active."
- **Input Fields:** A single bottom border (2px White). When focused, the border turns Lavender and a subtle glow appears beneath the text.
- **Cards:** No background color (transparent). Use a 1px solid White border. Images inside cards should have a "Grayscale" or "Duotone (Lavender/Black)" filter applied as a default state.
- **Checkboxes:** Square boxes. When checked, they fill with a solid Lavender "X" mark rather than a checkmark to maintain the "Anti-System" vibe.
- **Scrollbar:** Custom thin Lavender scrollbar on a transparent track to minimize visual clutter while maintaining the accent theme.