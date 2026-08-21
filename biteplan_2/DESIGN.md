---
name: BitePlan
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
  on-surface-variant: '#42474c'
  inverse-surface: '#32302b'
  inverse-on-surface: '#f6f0e8'
  outline: '#73777d'
  outline-variant: '#c3c7cd'
  surface-tint: '#466177'
  primary: '#466177'
  on-primary: '#ffffff'
  primary-container: '#a3bfd8'
  on-primary-container: '#334e63'
  inverse-primary: '#aecae3'
  secondary: '#7e5357'
  on-secondary: '#ffffff'
  secondary-container: '#ffc6ca'
  on-secondary-container: '#7b5054'
  tertiary: '#72594c'
  on-tertiary: '#ffffff'
  tertiary-container: '#d5b5a5'
  on-tertiary-container: '#5d463a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cae6ff'
  primary-fixed-dim: '#aecae3'
  on-primary-fixed: '#001e30'
  on-primary-fixed-variant: '#2e4a5e'
  secondary-fixed: '#ffdadc'
  secondary-fixed-dim: '#f0b9bd'
  on-secondary-fixed: '#311216'
  on-secondary-fixed-variant: '#633c40'
  tertiary-fixed: '#fedccb'
  tertiary-fixed-dim: '#e0c0b0'
  on-tertiary-fixed: '#29170d'
  on-tertiary-fixed-variant: '#594236'
  background: '#fef8f0'
  on-background: '#1d1b17'
  surface-variant: '#e7e2da'
  dusty-rose: '#7E5357'
  soft-peach: '#FFC6CB'
  butter-yellow: '#FDDCCB'
  warm-brown: '#30312E'
  cream: '#FFF9F1'
typography:
  display-lg:
    fontFamily: DM Sans
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: DM Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: DM Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: DM Sans
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  headline-sm:
    fontFamily: DM Sans
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-margin: 24px
  gutter: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  stack-xl: 48px
---

## Brand & Style
The design system is centered on "Culinary Comfort"—a philosophy that transforms meal planning from a chore into a restorative ritual. The target audience includes home cooks and busy individuals seeking a digital environment that feels as warm and inviting as a sunlit kitchen.

The aesthetic blends **Modern Minimalism** with a **Tactile Softness**. It draws inspiration from lifestyle editorial design, utilizing generous whitespace, organic shapes, and a soft, high-key lighting approach. The UI should evoke an emotional response of calm, competence, and domestic joy. All visual elements are intentionally de-cluttered to ensure that the vibrant, warm-toned food photography remains the focal point of the experience. The introduction of a soft blue primary tone shifts the mood toward a serene, refreshing, and airy kitchen atmosphere.

## Colors
The palette is a curated collection of "kitchen-natural" tones. The **Soft Blue** (#A3BFD8) primary color is used for the "path of least resistance"—primary actions, progress indicators, and active navigation states, replacing the previous green aesthetic with a calming, airy feel. 

The **Cream** background is the foundational surface; it provides a softer, more organic feel than pure white, reducing eye strain. **Dusty Rose** acts as a sentimental accent for favorites and "loved" recipes. Supporting tones of **Soft Peach** and **Butter Yellow** are used for secondary categorization (e.g., "Breakfast" or "Snacks") or as soft container backgrounds. Text is rendered in **Warm Brown** to maintain an earthy feel and avoid the sterile contrast of pure black.

## Typography
This design system utilizes **DM Sans** for its geometric yet approachable character. The typographic hierarchy is designed to feel editorial and spacious.

- **Page Titles:** Use `display-lg` or `headline-lg` with Semi-bold (600) weights for clear entry points.
- **Section Headings:** Use `headline-md` with Medium (500) weights to group recipe categories or meal plan days.
- **Body Text:** Use `body-md` for ingredients and instructions. The line height is intentionally loose (1.5x) to ensure legibility while cooking.
- **Labels:** Use `label-md` for meta-data like "Prep Time" or "Calories," often paired with the secondary text color.

## Layout & Spacing
The layout follows a strict **8px spacing system** to maintain mathematical harmony while appearing visually "loose" and effortless.

- **Grid:** On desktop, use a 12-column centered grid with a max-width of 1200px. On mobile, use a single-column fluid layout with **24px side margins**.
- **Content Spacing:** Use `stack-lg` (32px) between major sections. Use `stack-md` (16px) for internal card padding and spacing between related items.
- **Whitespace:** Embrace empty space. Avoid crowding the cream background; the layout should feel like a well-organized physical recipe binder.

## Elevation & Depth
Depth is created through **Tonal Layers** and **Ambient Shadows** to maintain a soft and cozy aesthetic. Avoid heavy dropshadows or harsh black offsets.

1.  **The Base:** The Cream (#FFF9F1) background.
2.  **The Surface:** Cards and containers use pure White (#FFFFFF) or very subtle Peach/Yellow tints to sit slightly "above" the background.
3.  **The Shadow:** Use a very diffused, low-opacity shadow (Color: #4A4038 at 5-8% opacity, Blur: 20px, Y-Offset: 4px) to give a "resting on paper" effect.
4.  **Active State:** When an item is pressed or dragged, increase the blur and offset slightly to simulate physical lift.

## Shapes
The shape language is defined by significant **Roundedness**. There are no sharp corners in this design system.

- **Standard Elements:** Buttons, input fields, and small tags use `rounded` (8px).
- **Cards & Containers:** All main recipe and meal plan cards must use `rounded-lg` (16px).
- **Feature Modules:** Large promotional banners or hero images should use `rounded-xl` (24px) to emphasize the soft, friendly nature of the app.
- **Interactive States:** Floating Action Buttons (FABs) and specific tags (like meal categories) should be fully **Pill-shaped** to encourage touch.

## Components
- **Buttons:** Primary buttons use the Soft Blue background with White text. Secondary buttons use a Soft Blue outline or a Soft Peach background with Warm Brown text.
- **Recipe Cards:** Use a White surface with `rounded-lg` corners. Images should occupy the top half, with title and prep-time metadata below in Warm Brown.
- **Chips/Tags:** Use Butter Yellow or Soft Peach backgrounds for tags like "Gluten-Free" or "15 Min". Text should be the Warm Brown `label-sm`.
- **Inputs:** Text fields use a Cream or very light Gray stroke with `rounded` (8px) corners. Focus states transition the border to Soft Blue.
- **Lists:** Ingredient lists have generous vertical padding (12px-16px). Custom checkboxes turn Soft Blue when checked for the grocery list.
- **Calendar/Planner:** Uses a horizontal-scroll "Day Picker" at the top, with Soft Blue as the selected date indicator.