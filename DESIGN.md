---
name: Whimsical Kitchen
colors:
  surface: '#fef8f0'
  surface-dim: '#dfd9d2'
  surface-bright: '#fef8f0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f9f3eb'
  surface-container: '#f3ede5'
  surface-container-high: '#ede7e0'
  surface-container-highest: '#e7e2da'
  on-surface: '#1d1b17'
  on-surface-variant: '#434841'
  inverse-surface: '#32302b'
  inverse-on-surface: '#f6f0e8'
  outline: '#747871'
  outline-variant: '#c3c8bf'
  surface-tint: '#4f644c'
  primary: '#4f644c'
  on-primary: '#ffffff'
  primary-container: '#a8bfa3'
  on-primary-container: '#3a4e38'
  inverse-primary: '#b6cdb0'
  secondary: '#72594c'
  on-secondary: '#ffffff'
  secondary-container: '#fad9c8'
  on-secondary-container: '#765d50'
  tertiary: '#785653'
  on-tertiary: '#ffffff'
  tertiary-container: '#d9afab'
  on-tertiary-container: '#60413f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d1e9cb'
  primary-fixed-dim: '#b6cdb0'
  on-primary-fixed: '#0d200d'
  on-primary-fixed-variant: '#384c36'
  secondary-fixed: '#fddccb'
  secondary-fixed-dim: '#e0c0b0'
  on-secondary-fixed: '#29180d'
  on-secondary-fixed-variant: '#584236'
  tertiary-fixed: '#ffdad7'
  tertiary-fixed-dim: '#e8bcb8'
  on-tertiary-fixed: '#2d1513'
  on-tertiary-fixed-variant: '#5e3f3c'
  background: '#fef8f0'
  on-background: '#1d1b17'
  surface-variant: '#e7e2da'
  butter-yellow: '#F4E6B8'
  ink-brown: '#4A4038'
  accent-pink: '#F2C6C2'
typography:
  display-lg:
    fontFamily: Nunito Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Nunito Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Nunito Sans
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 34px
  headline-md:
    fontFamily: Nunito Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-sm:
    fontFamily: Nunito Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
  body-lg:
    fontFamily: Nunito Sans
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 28px
  body-md:
    fontFamily: Nunito Sans
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  label-md:
    fontFamily: Nunito Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Nunito Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.03em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 16px
  margin-mobile: 24px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system adopts a **Cute, Aesthetic Cartoon** personality, shifting the focus from editorial minimalism to a playful, hand-drawn "doodle" aesthetic. The target audience seeks a delightful, stress-free escape while managing their culinary lives. 

The visual style is characterized by:
- **Illustrative Warmth:** Utilizing soft, organic lines that mimic hand-drawn ink.
- **Playful Ornamentation:** Small doodle-style decorative elements (stars, hearts, leaves, and sparkles) are used as accents around headings and within empty states to create a sense of joy.
- **Soft Tactility:** Combining "squishy" pill-shaped elements with subtle, playful shadows that give the UI a sticker-like quality.
- **Artistic Imagery:** Food photography should feel integrated through the use of soft-focus filters or subtle illustrated overlays, ensuring they match the hand-drawn UI elements.

## Colors

The palette is anchored in a "Cream" (#FFF9F1) background to establish a warm, paper-like canvas. 

- **Primary (Sage Green):** Reserved for high-priority actions, primary buttons, and active navigational states. It represents growth and fresh ingredients.
- **Secondary (Soft Peach):** Used for secondary containers, cards, and grouped background elements to provide soft contrast against the cream base.
- **Tertiary (Blush Pink):** The "emotional" accent. Use this exclusively for favorites, hearts, and celebratory UI moments.
- **Highlight (Butter Yellow):** Applied to tags, badges, and "sparkle" doodle elements to draw the eye to specific metadata.
- **Typography:** All text should be rendered in **Ink Brown** (#4A4038) instead of black to maintain the soft, illustrated feel.

## Typography

This design system uses **Nunito Sans** for all levels. Its rounded terminals perfectly complement the cartoon aesthetic. 

Headlines utilize "Extra Bold" (800) weights to mimic the weight of a thick marker or felt-tip pen. Body text uses "Medium" (500) weights to ensure legibility while maintaining a soft presence. For a more "doodled" look, use `label-sm` in all-caps for categories or tags. 

*Note: Large display titles can be paired with small leaf or star doodles positioned at the start or end of the text string.*

## Layout & Spacing

The layout philosophy is a **Fluid Grid** with generous, "loose" spacing to prevent the interface from feeling cramped or technical.

- **Mobile:** 24px side margins provide a safe "frame" for the content.
- **Consistency:** Use 16px (stack-md) for internal padding within cards and 32px (stack-lg) to separate distinct functional blocks.
- **Asymmetry:** Occasionally break the grid with decorative doodles that "peek" out from behind cards or bleed into the margins to reinforce the hand-drawn theme.

## Elevation & Depth

Depth in this system is conveyed through **Playful Shadows** and **Tonal Stacking**.

- **Shadow Character:** Use highly diffused shadows with a slight color tint (using a low-opacity Ink Brown or Sage Green) to create a "sticker" effect. Shadows should have a larger Y-offset to suggest items are floating slightly off the cream paper background.
- **Tonal Layers:**
  - **Level 0:** Cream (#FFF9F1) background.
  - **Level 1:** Soft Peach (#F4D3C2) or White cards.
  - **Level 2:** Sage Green or Blush Pink buttons/interactive elements.
- **Outlines:** Use thin, Soft Peach or light Sage Green borders (1px) on containers to define edges without the harshness of a dark stroke.

## Shapes

The shape language is defined by **Maximum Roundness**. Sharp corners are strictly prohibited.

- **Pill Shapes:** All buttons, chips, and selection indicators must be fully pill-shaped.
- **Cards:** Use `rounded-xl` (1.5rem / 24px) for all content containers to maintain a "bouncy," friendly appearance.
- **Inputs:** Text fields should use `rounded-lg` (1rem / 16px) to soften the data entry experience.

## Components

- **Buttons:** Primary buttons are pill-shaped, Sage Green, with Ink Brown or White text. Use a subtle inner-glow or a slightly darker bottom border to give them a "squishy" 3D look.
- **Cards:** Use White or Soft Peach backgrounds. Add a decorative "doodle" (like a small leaf) in the corner of featured recipe cards.
- **Chips & Tags:** Use Butter Yellow for informational tags. They should be pill-shaped with `label-sm` bold text.
- **Input Fields:** Use a Soft Peach background for the field itself. The focus state should be a thicker Sage Green border.
- **Checkboxes & Radios:** These should be extra large and rounded. When checked, use a Sage Green fill with a hand-drawn "check" or "heart" icon.
- **Doodles:** Integrate a library of SVG assets (stars, sparkles, hearts, citrus slices) that can be randomly placed near headings or used as list bullets to enhance the cartoon aesthetic.
- **Imagery:** Apply a subtle "illustrated" or "vibrant/warm" filter to all food photography to ensure the realistic photos don't clash with the playful UI.