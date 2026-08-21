---
name: BitePlan
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f0'
  surface-container: '#efeeea'
  surface-container-high: '#e9e8e4'
  surface-container-highest: '#e4e2df'
  on-surface: '#1b1c1a'
  on-surface-variant: '#434841'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ed'
  outline: '#747871'
  outline-variant: '#c3c8bf'
  surface-tint: '#4f644c'
  primary: '#4f644c'
  on-primary: '#ffffff'
  primary-container: '#a8bfa3'
  on-primary-container: '#3a4e38'
  inverse-primary: '#b6cdb0'
  secondary: '#7e5357'
  on-secondary: '#ffffff'
  secondary-container: '#ffc6cb'
  on-secondary-container: '#7b5055'
  tertiary: '#72594c'
  on-tertiary: '#ffffff'
  tertiary-container: '#d1b2a2'
  on-tertiary-container: '#5a4437'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d1e9cb'
  primary-fixed-dim: '#b6cdb0'
  on-primary-fixed: '#0d200d'
  on-primary-fixed-variant: '#384c36'
  secondary-fixed: '#ffd9dc'
  secondary-fixed-dim: '#f0b9be'
  on-secondary-fixed: '#311216'
  on-secondary-fixed-variant: '#633c40'
  tertiary-fixed: '#fddccb'
  tertiary-fixed-dim: '#e0c0b0'
  on-tertiary-fixed: '#29180d'
  on-tertiary-fixed-variant: '#584236'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2df'
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

The aesthetic blends **Modern Minimalism** with a **Tactile Softness**. It draws inspiration from lifestyle editorial design, utilizing generous whitespace, organic shapes, and a soft, high-key lighting approach. The UI should evoke an emotional response of calm, competence, and domestic joy. All visual elements are intentionally de-cluttered to ensure that the vibrant, warm-toned food photography remains the focal point of the experience.

## Colors
The palette is a curated collection of "kitchen-natural" tones. The **Sage Green** primary color is used for the "path of least resistance"—primary actions, progress indicators, and active navigation states. **Dusty Rose** acts as a sentimental accent, reserved for favorites, "loved" recipes, and delicate highlights.

The **Cream** background is non-negotiable; it provides a softer, more organic feel than pure white, reducing eye strain during long browsing sessions. Supporting tones of **Soft Peach** and **Butter Yellow** should be used sparingly for secondary categorization (e.g., meal types like "Breakfast" or "Snacks") or as soft container backgrounds to differentiate content blocks without using harsh lines. Text is rendered in **Warm Brown** to maintain the "earthy" feel and avoid the sterile contrast of pure black.

## Typography
This design system utilizes **DM Sans** for its geometric yet approachable character. The typographic hierarchy is designed to feel editorial and spacious.

- **Page Titles:** Use `display-lg` or `headline-lg` with Semi-bold (600) weights to provide clear entry points.
- **Section Headings:** Use `headline-md` with Medium (500) weights to group recipe categories or meal plan days.
- **Body Text:** Use `body-md` for ingredients and instructions. The line height is intentionally loose (1.5x) to ensure legibility while cooking.
- **Labels:** Use `label-md` for meta-data like "Prep Time" or "Calories," often paired with the secondary text color.

## Layout & Spacing
The layout follows a strict **8px spacing system** to maintain mathematical harmony while appearing visually "loose" and effortless. 

- **Grid:** On desktop, use a 12-column centered grid with a max-width of 1200px. On mobile, use a single-column fluid layout with **24px side margins**.
- **Content Spacing:** Use `stack-lg` (32px) between major sections (e.g., between "Recent Recipes" and "Meal Plan"). Use `stack-md` (16px) for internal card padding and spacing between related items.
- **Whitespace:** Embrace empty space. Avoid crowding the cream background; the layout should feel like a well-organized physical recipe binder.

## Elevation & Depth
In alignment with the soft and cozy aesthetic, depth is created through **Tonal Layers** and **Ambient Shadows**. 

Avoid heavy dropshadows or harsh black offsets. Instead, use "Organic Depth": 
1. **The Base:** The Cream (#FFF9F1) background.
2. **The Surface:** Cards and containers use pure White (#FFFFFF) or very subtle Peach/Yellow tints to sit slightly "above" the background.
3. **The Shadow:** Use a very diffused, low-opacity shadow (Color: #4A4038 at 5-8% opacity, Blur: 20px, Y-Offset: 4px) to give a "resting on paper" effect.
4. **Active State:** When an item is pressed or dragged, increase the blur and offset slightly to simulate a physical lift.

## Shapes
The shape language is defined by significant **Roundedness**. There are no sharp corners in this design system.

- **Standard Elements:** Buttons, input fields, and small tags use `rounded` (8px).
- **Cards & Containers:** All main recipe and meal plan cards must use `rounded-lg` (16px).
- **Feature Modules:** Large promotional banners or hero images should use `rounded-xl` (24px) to emphasize the soft, friendly nature of the app.
- **Interactive States:** Floating Action Buttons (FABs) and specific tags (like meal categories) should be fully **Pill-shaped** to encourage touch.

## Components
- **Buttons:** Primary buttons use the Sage Green background with White text. They should have a minimum height of 48px to be thumb-friendly. Secondary buttons use a Sage Green outline or a Peach background with Warm Brown text.
- **Recipe Cards:** These are the core of the app. Use a White surface with `rounded-lg` corners. The image should occupy the top half (or the full background with a soft gradient overlay), with title and prep-time metadata below in Warm Brown.
- **Chips/Tags:** Use the Butter Yellow or Soft Peach backgrounds for tags like "Gluten-Free" or "15 Min". Text should be the Warm Brown `label-sm`.
- **Inputs:** Text fields should have a Cream or very light Gray stroke and `rounded` (8px) corners. Focus states should transition the border to Sage Green.
- **Lists:** Ingredient lists should have generous vertical padding (12px-16px) between items, with custom-styled checkboxes that turn Sage Green when "collected" for the grocery list.
- **Calendar/Planner:** The meal planner should use a horizontal-scroll "Day Picker" at the top, using the Sage Green for the selected date indicator.